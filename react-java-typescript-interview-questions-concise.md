# JavaScript, TypeScript & React Interview Questions - Quick Reference

> **Concise revision guide** - Essential concepts, key points, and quick answers for rapid preparation
> 
> 📖 **For detailed explanations**: Each question links to the corresponding section in the [detailed version](./react-java-typescript-interview-questions.md)

---

## 📋 Table of Contents

1. [JavaScript Core Concepts](#1-javascript-core-concepts)
2. [TypeScript Advanced Topics](#2-typescript-advanced-topics)
3. [React Architecture & Patterns](#3-react-architecture--patterns)
4. [System Design & Architecture](#4-system-design--architecture)
5. [Coding Challenges](#5-coding-challenges)
6. [Behavioral & Scenario-Based](#6-behavioral--scenario-based)
7. [Best Practices & Patterns](#7-best-practices--patterns)

---

## 1. JavaScript Core Concepts

### 1.1 Event Loop & Asynchronous JavaScript
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#11-explain-how-the-javascript-event-loop-works-whats-the-difference-between-microtasks-and-macrotasks)

**Key Points:**
- **Call Stack**: LIFO structure for synchronous code execution
- **Web APIs**: Browser APIs (setTimeout, fetch, DOM events)
- **Task Queue**: Macrotasks (setTimeout, setInterval, I/O)
- **Microtask Queue**: Microtasks (Promises, queueMicrotask, MutationObserver)

**Execution Order:**
1. Execute all synchronous code
2. Process all microtasks
3. Process one macrotask
4. Repeat

```javascript
console.log('1'); // sync
setTimeout(() => console.log('2'), 0); // macrotask
Promise.resolve().then(() => console.log('3')); // microtask
console.log('4'); // sync
// Output: 1, 4, 3, 2
```

### 1.2 Closures
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#12-explain-closures-and-provide-a-practical-use-case-where-closures-are-essential-what-are-potential-memory-leak-concerns-with-closures)

**Definition:** Function that has access to variables in its outer scope even after the outer function returns.

**Use Cases:**
- Data privacy/encapsulation
- Function factories
- Event handlers
- Module pattern

```javascript
function createCounter() {
  let count = 0;
  return function() {
    return ++count;
  };
}
const counter = createCounter();
counter(); // 1
counter(); // 2
```

**Memory Leak Prevention:**
- Remove event listeners
- Clear timers/intervals
- Set references to null

### 1.3 Prototypal Inheritance
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#13-how-does-prototypal-inheritance-differ-from-classical-inheritance-explain-the-prototype-chain-and-how-you-would-implement-inheritance-in-modern-javascript)

**Key Concepts:**
- **Prototype Chain**: Object → Object.prototype → null
- **`__proto__`**: Points to prototype object
- **`Object.create()`**: Creates object with specified prototype
- **`Object.setPrototypeOf()`**: Sets prototype of object

```javascript
// Modern inheritance
class Animal {
  constructor(name) { this.name = name; }
  speak() { console.log(`${this.name} makes a sound`); }
}

class Dog extends Animal {
  speak() { console.log(`${this.name} barks`); }
}
```

### 1.4 `this` Binding
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#14-explain-the-different-ways-this-can-be-bound-in-javascript-what-are-the-differences-between-call-apply-and-bind)

**Binding Rules:**
1. **Default**: Global object (undefined in strict mode)
2. **Implicit**: Object calling the method
3. **Explicit**: `.call()`, `.apply()`, `.bind()`
4. **New**: New instance when using `new` keyword
5. **Arrow functions**: Lexical `this` (from enclosing scope)

```javascript
// .call() - immediate execution with arguments
func.call(context, arg1, arg2);

// .apply() - immediate execution with array of arguments
func.apply(context, [arg1, arg2]);

// .bind() - returns new function with bound context
const boundFunc = func.bind(context);
```

### 1.5 Promise Methods
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#15-whats-the-difference-between-promiseall-promiserace-promiseallsettled-and-promiseany-when-would-you-use-each)

| Method | Behavior | Use Case |
|--------|----------|----------|
| `Promise.all()` | All must resolve, fails on first rejection | Parallel operations, all required |
| `Promise.race()` | First to settle (resolve/reject) | Timeouts, fastest response |
| `Promise.allSettled()` | Waits for all to settle | Independent operations |
| `Promise.any()` | First to resolve, fails if all reject | Fallback strategies |

### 1.6 var, let, const Differences
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#16-explain-the-differences-between-var-let-and-const-when-should-you-use-each)

| Feature | var | let | const |
|---------|-----|-----|-------|
| Scope | Function-scoped | Block-scoped | Block-scoped |
| Hoisting | Hoisted + initialized | Hoisted (TDZ) | Hoisted (TDZ) |
| Re-declaration | ✅ Allowed | ❌ Not allowed | ❌ Not allowed |
| Re-assignment | ✅ Allowed | ✅ Allowed | ❌ Not allowed |

**When to use:**
- **const**: Default choice for all variables
- **let**: When you need to reassign
- **var**: Avoid in modern JavaScript

```javascript
// ✅ Modern approach
const API_URL = 'https://api.example.com';
let isLoading = false;

// ❌ Avoid var
var oldStyle = 'avoid this';
```

### 1.7 Garbage Collection
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#17-explain-how-garbage-collection-works-in-javascript-what-patterns-can-lead-to-memory-leaks)

**Mark and Sweep Algorithm:**
1. Mark all reachable objects
2. Sweep unmarked objects
3. Compact memory

**Memory Leak Patterns:**
- Global variables
- Closures holding references
- Event listeners not removed
- Timers not cleared
- Circular references

### 1.8 ES6+ Features
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#21-explain-arrow-functions-and-their-differences-from-regular-functions-when-should-you-use-each)

**Arrow Functions:**
```javascript
// Arrow function
const add = (a, b) => a + b;

// Regular function
function add(a, b) { return a + b; }
```

**Key Differences:**
- **this binding**: Arrow functions use lexical `this`
- **arguments object**: Not available in arrow functions
- **Constructor**: Arrow functions can't be constructors
- **Hoisting**: Arrow functions are not hoisted

### 1.9 Destructuring & Spread/Rest
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#22-explain-destructuring-assignment-provide-examples-of-object-and-array-destructuring-with-practical-use-cases)

**Array Destructuring:**
```javascript
const [first, second, ...rest] = [1, 2, 3, 4, 5];
const [a, , c] = [1, 2, 3]; // Skip elements
```

**Object Destructuring:**
```javascript
const { name, age, ...other } = user;
const { name: userName } = user; // Rename
```

**Spread/Rest:**
```javascript
// Spread - expand
const combined = [...arr1, ...arr2];
const newObj = { ...obj1, ...obj2 };

// Rest - collect
function sum(...numbers) { return numbers.reduce((a, b) => a + b, 0); }
```

### 1.10 Template Literals
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#24-explain-template-literals-and-tagged-template-literals-provide-practical-examples)

```javascript
// String interpolation
const message = `Hello ${name}, you are ${age} years old.`;

// Multi-line strings
const html = `
  <div>
    <h1>${title}</h1>
  </div>
`;

// Tagged templates
function sql(strings, ...values) {
  return strings.reduce((query, string, i) => {
    return query + string + (values[i] || '');
  }, '');
}
```

### 1.11 ES6 Modules
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#25-explain-es6-modules-importexport-compare-with-commonjs-and-discuss-module-bundling)

**Export/Import:**
```javascript
// Named exports
export const PI = 3.14159;
export function add(a, b) { return a + b; }

// Default export
export default function subtract(a, b) { return a - b; }

// Import
import { PI, add } from './math.js';
import subtract from './math.js';
import * as math from './math.js';
```

**Dynamic Import:**
```javascript
const { add, subtract } = await import('./math.js');
```

### 1.12 Async/Await
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#26-explain-asyncawait-syntax-and-how-it-relates-to-promises-what-are-the-benefits-and-potential-pitfalls)

**Benefits:**
- More readable than Promise chains
- Better error handling with try/catch
- Easier debugging

**Common Pitfalls:**
```javascript
// ❌ Sequential (slow)
const user = await fetchUser(1);
const posts = await fetchPosts(1);

// ✅ Parallel (fast)
const [user, posts] = await Promise.all([
  fetchUser(1),
  fetchPosts(1)
]);
```

### 1.13 Web APIs
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#27-explain-the-fetch-api-and-how-it-differs-from-xmlhttprequest-provide-examples-of-common-use-cases)

**Fetch API:**
```javascript
// GET request
const response = await fetch('/api/users');
const users = await response.json();

// POST request
const response = await fetch('/api/users', {
  method: 'POST',
  headers: { 'Content-Type': 'application/json' },
  body: JSON.stringify(userData)
});
```

**vs XMLHttpRequest:**
- Promise-based vs callback-based
- Simpler API
- Better error handling
- Built-in JSON parsing

### 1.14 Browser Storage
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#28-explain-localstorage-sessionstorage-and-indexeddb-when-would-you-use-each)

| Storage | Persistence | Size Limit | Data Type | Use Case |
|---------|-------------|------------|-----------|----------|
| **localStorage** | Survives restart | ~5-10MB | Strings | User preferences |
| **sessionStorage** | Tab session only | ~5-10MB | Strings | Form data |
| **IndexedDB** | Survives restart | ~50MB+ | Any structured | Offline data |

### 1.15 DOM Manipulation
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#29-explain-dom-manipulation-and-event-handling-what-are-event-delegation-bubbling-and-capturing)

**Event Delegation:**
```javascript
// Instead of adding listeners to each button
document.addEventListener('click', (event) => {
  if (event.target.matches('.button')) {
    handleClick(event);
  }
});
```

**Event Bubbling vs Capturing:**
- **Bubbling**: Event goes from target to root (default)
- **Capturing**: Event goes from root to target

### 1.16 Regular Expressions
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#210-explain-regular-expressions-in-javascript-provide-examples-of-common-patterns-and-use-cases)

**Common Patterns:**
```javascript
// Email validation
const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;

// Phone number
const phoneRegex = /^\(\d{3}\) \d{3}-\d{4}$/;

// Password (8+ chars, 1 uppercase, 1 lowercase, 1 number)
const passwordRegex = /^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)[a-zA-Z\d@$!%*?&]{8,}$/;
```

**String Methods:**
- `test()`: Returns boolean
- `exec()`: Returns match details
- `match()`: Returns array of matches
- `replace()`: Replaces matches
- `search()`: Returns index of first match

### 1.17 Error Handling
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#211-explain-error-handling-in-javascript-compare-different-error-handling-strategies-and-when-to-use-each)

**Try-Catch:**
```javascript
try {
  const result = riskyOperation();
} catch (error) {
  console.error('Error:', error.message);
} finally {
  console.log('Always runs');
}
```

**Custom Error Classes:**
```javascript
class ValidationError extends Error {
  constructor(message, field) {
    super(message);
    this.name = 'ValidationError';
    this.field = field;
  }
}
```

**Error Handling Strategies:**
- Defensive programming
- Error boundaries (React)
- Result pattern
- Global error handling

---

## 2. TypeScript Advanced Topics

### 2.1 Type vs Interface
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#21-explain-the-difference-between-type-and-interface-when-would-you-choose-one-over-the-other)

| Feature | `type` | `interface` |
|---------|--------|-------------|
| Declaration merging | ❌ | ✅ |
| Extends | `&` | `extends` |
| Implements | ✅ | ✅ |
| Union types | ✅ | ❌ |
| Computed properties | ✅ | ❌ |
| Mapped types | ✅ | ❌ |

**When to use:**
- **Interface**: Object shapes, extensible APIs
- **Type**: Unions, computed properties, complex types

### 2.2 Generics
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#22-what-are-generics-and-why-are-they-useful-provide-an-example-of-a-generic-function-that-demonstrates-type-safety)

**Purpose:** Create reusable components that work with multiple types while maintaining type safety.

```typescript
function identity<T>(arg: T): T {
  return arg;
}

interface ApiResponse<T> {
  data: T;
  status: number;
  message: string;
}
```

### 2.3 Utility Types
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#23-explain-how-partial-pick-omit-and-record-utility-types-work-when-would-you-use-conditional-types)

| Type | Purpose | Example |
|------|---------|---------|
| `Partial<T>` | All properties optional | `Partial<User>` |
| `Pick<T, K>` | Select specific properties | `Pick<User, 'name' \| 'email'>` |
| `Omit<T, K>` | Exclude specific properties | `Omit<User, 'password'>` |
| `Record<K, V>` | Object with specific keys/values | `Record<string, number>` |

### 2.4 Type Guards
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#24-what-are-type-guards-implement-a-custom-type-guard-function-and-explain-how-typescript-narrows-types)

**Purpose:** Narrow types at runtime for type safety.

```typescript
function isString(value: unknown): value is string {
  return typeof value === 'string';
}

function processValue(value: string | number) {
  if (isString(value)) {
    // TypeScript knows value is string here
    return value.toUpperCase();
  }
  return value.toString();
}
```

### 2.5 Advanced Types
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#25-explain-mapped-types-and-template-literal-types-provide-a-practical-example-where-these-would-be-beneficial)

**Mapped Types:**
```typescript
type Readonly<T> = {
  readonly [P in keyof T]: T[P];
};
```

**Template Literal Types:**
```typescript
type EventName<T extends string> = `on${Capitalize<T>}`;
type ClickEvent = EventName<'click'>; // 'onClick'
```

### 2.6 Type Inference
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#26-how-does-typescripts-type-inference-work-what-are-the-limitations-and-when-should-you-explicitly-type-things)

**When to explicitly type:**
- Function parameters
- Object literals
- Complex return types
- API boundaries

**Limitations:**
- Contextual typing issues
- Complex generic inference
- Ambiguous literal types

---

## 3. React Architecture & Patterns

### 3.1 Component Lifecycle (Function Components)
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#31-explain-the-react-component-lifecycle-in-function-components-how-do-useeffect-dependencies-work-and-what-are-common-pitfalls)

**Key Hooks:**
- `useState`: Local state management
- `useEffect`: Side effects and lifecycle
- `useContext`: Context consumption
- `useReducer`: Complex state logic
- `useMemo`: Expensive calculations
- `useCallback`: Function memoization

**useEffect Dependencies:**
```javascript
useEffect(() => {
  // Effect logic
}, [dependency1, dependency2]); // Re-run when dependencies change
```

**Common Pitfalls:**
- Missing dependencies
- Infinite loops
- Stale closures
- Memory leaks

### 3.2 State Management Comparison
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#32-compare-different-state-management-solutions-context-api-redux-zustand-jotai-when-would-you-choose-each)

| Solution | Use Case | Pros | Cons |
|----------|----------|------|------|
| **useState** | Local component state | Simple, built-in | Not for complex state |
| **Context API** | App-wide state | Built-in, no dependencies | Performance issues |
| **Redux** | Complex global state | Predictable, devtools | Boilerplate, learning curve |
| **Zustand** | Lightweight global state | Simple API, TypeScript | Less ecosystem |
| **Jotai** | Atomic state management | Fine-grained updates | New paradigm |

### 3.3 Performance Optimization
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#33-explain-reactmemo-usememo-and-usecallback-whats-the-difference-and-when-should-each-be-used)

**React.memo:**
```javascript
const MemoizedComponent = React.memo(({ data }) => {
  return <div>{data}</div>;
});
```

**useMemo:**
```javascript
const expensiveValue = useMemo(() => {
  return heavyCalculation(data);
}, [data]);
```

**useCallback:**
```javascript
const handleClick = useCallback(() => {
  doSomething(id);
}, [id]);
```

**When to use:**
- **React.memo**: Prevent unnecessary re-renders
- **useMemo**: Expensive calculations
- **useCallback**: Stable function references

### 3.4 Custom Hooks
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#34-what-are-the-rules-of-hooks-design-a-custom-hook-for-handling-form-state-with-validation)

**Rules of Hooks:**
1. Only call hooks at the top level
2. Only call hooks from React functions
3. Don't call hooks inside loops, conditions, or nested functions

**Custom Hook Example:**
```javascript
function useForm(initialValues) {
  const [values, setValues] = useState(initialValues);
  const [errors, setErrors] = useState({});
  
  const handleChange = (name, value) => {
    setValues(prev => ({ ...prev, [name]: value }));
    // Clear error when user starts typing
    if (errors[name]) {
      setErrors(prev => ({ ...prev, [name]: '' }));
    }
  };
  
  const validate = () => {
    // Validation logic
  };
  
  return { values, errors, handleChange, validate };
}
```

### 3.5 React 18 Concurrent Features
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#35-explain-react-18s-concurrent-features-usetransition-usedeferredvalue-suspense-how-do-they-improve-user-experience)

**useTransition:**
```javascript
const [isPending, startTransition] = useTransition();

const handleClick = () => {
  startTransition(() => {
    setState(newState); // Non-urgent update
  });
};
```

**useDeferredValue:**
```javascript
const deferredValue = useDeferredValue(value);
```

**Suspense:**
```javascript
<Suspense fallback={<Loading />}>
  <LazyComponent />
</Suspense>
```

### 3.6 React Hooks Reference
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#314-provide-a-comprehensive-overview-of-all-react-hooks-in-table-format-with-brief-descriptions-and-use-cases)

| Hook | Purpose | Dependencies |
|------|---------|--------------|
| `useState` | State management | Initial value |
| `useEffect` | Side effects | Dependency array |
| `useContext` | Context consumption | Context object |
| `useReducer` | Complex state | Reducer, initial state |
| `useMemo` | Memoized value | Dependency array |
| `useCallback` | Memoized function | Dependency array |
| `useRef` | Mutable reference | Initial value |
| `useLayoutEffect` | Synchronous effects | Dependency array |
| `useImperativeHandle` | Custom ref value | Ref, function, deps |
| `useDebugValue` | DevTools display | Value, formatter |

### 3.7 Error Boundaries
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#37-what-are-error-boundaries-and-their-limitations-how-would-you-implement-error-handling-in-a-react-application)

**Class Component:**
```javascript
class ErrorBoundary extends React.Component {
  constructor(props) {
    super(props);
    this.state = { hasError: false };
  }
  
  static getDerivedStateFromError(error) {
    return { hasError: true };
  }
  
  componentDidCatch(error, errorInfo) {
    console.error('Error caught:', error, errorInfo);
  }
  
  render() {
    if (this.state.hasError) {
      return <h1>Something went wrong.</h1>;
    }
    return this.props.children;
  }
}
```

**Limitations:**
- Don't catch errors in event handlers
- Don't catch errors in async code
- Don't catch errors during SSR

### 3.8 React 19 Features
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#316-what-are-the-new-features-in-react-19-how-do-they-improve-developer-experience-and-performance)

**New Features:**
- **React Compiler**: Automatic memoization
- **Actions & useActionState**: Server actions with state management
- **use() Hook**: Direct promise unwrapping
- **Document Metadata**: Built-in Title, Meta, Link components
- **Ref as Prop**: Pass refs as regular props

```javascript
// React Compiler - automatic optimization
function ExpensiveComponent({ items, filter }) {
  // Automatically memoized
  const filteredItems = items.filter(item => item.category === filter);
  return <div>{filteredItems.length}</div>;
}

// useActionState
const [state, formAction, isPending] = useActionState(updateUser, {});
```

### 3.9 React DevTools
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#317-how-do-you-use-react-devtools-for-debugging-and-performance-optimization)

**Key Features:**
- **Components Tab**: Inspect component tree, props, state
- **Profiler Tab**: Record performance sessions, identify slow components
- **Real-time editing**: Modify props/state during development

**Debugging Techniques:**
- Component state debugging
- Props inspection
- Context value monitoring
- Performance profiling

### 3.10 Bundle Analysis
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#318-how-do-you-analyze-and-optimize-react-bundle-size-what-tools-and-techniques-do-you-use)

**Tools:**
- **Webpack Bundle Analyzer**: Visual bundle analysis
- **Source Map Explorer**: Bundle size breakdown
- **Bundlephobia**: Package size checking

**Optimization Techniques:**
- Code splitting (route-based, component-based)
- Tree shaking
- Dynamic imports
- Vendor chunk splitting

```javascript
// Route-based splitting
const Home = lazy(() => import('./pages/Home'));

// Component-based splitting
const HeavyChart = lazy(() => import('./HeavyChart'));
```

### 3.11 React Security
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#319-what-are-the-key-security-considerations-when-building-react-applications-how-do-you-prevent-common-vulnerabilities)

**XSS Prevention:**
```javascript
// ✅ Safe - sanitize HTML
import DOMPurify from 'dompurify';
const cleanHTML = DOMPurify.sanitize(userInput);

// ✅ Safe - use textContent
return <div>{userInput}</div>;
```

**Security Best Practices:**
- Input validation and sanitization
- CSRF protection with tokens
- Secure token storage
- Content Security Policy (CSP)
- Environment variable security
- Dependency auditing

### 3.12 Webpack vs Vite
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#320-compare-webpack-and-vite-for-react-development-what-are-the-advantages-and-disadvantages-of-each)

| Feature | Webpack | Vite |
|---------|---------|------|
| Development Server | Bundles everything | Native ES modules |
| Build Speed | Slower | Faster |
| Configuration | Complex | Simple |
| Plugin Ecosystem | Mature | Growing |
| Bundle Size | Larger | Smaller |

**Choose Webpack when:**
- Complex build requirements
- Legacy browser support
- Micro-frontend architecture

**Choose Vite when:**
- Fast development experience
- Modern applications
- Minimal configuration needed

---

## 4. System Design & Architecture

### 4.1 Component Library Design
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#41-how-would-you-design-a-reusable-accessible-component-library-what-principles-would-you-follow)

**Core Principles:**
- **Composition over inheritance**
- **Single responsibility**
- **Consistent API design**
- **Accessibility first**
- **TypeScript support**

**Accessibility Checklist:**
- Semantic HTML
- ARIA attributes
- Keyboard navigation
- Screen reader support
- Color contrast
- Focus management

### 4.2 Code Splitting Strategies
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#42-explain-different-strategies-for-code-splitting-in-react-how-would-you-implement-route-based-code-splitting)

**Route-based Splitting:**
```javascript
const Home = lazy(() => import('./pages/Home'));
const About = lazy(() => import('./pages/About'));

function App() {
  return (
    <Router>
      <Suspense fallback={<Loading />}>
        <Routes>
          <Route path="/" element={<Home />} />
          <Route path="/about" element={<About />} />
        </Routes>
      </Suspense>
    </Router>
  );
}
```

**Component-based Splitting:**
```javascript
const HeavyComponent = lazy(() => import('./HeavyComponent'));
```

### 4.3 Testing Strategy
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#43-whats-your-approach-to-testing-react-applications-how-do-you-balance-unit-integration-and-e2e-tests)

**Testing Pyramid:**
1. **Unit Tests** (70%): Individual functions/components
2. **Integration Tests** (20%): Component interactions
3. **E2E Tests** (10%): Full user workflows

**Tools:**
- **Jest**: Unit testing framework
- **React Testing Library**: Component testing
- **Cypress/Playwright**: E2E testing

### 4.4 Authentication Implementation
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#44-how-would-you-implement-authentication-in-a-react-spa-discuss-token-management-refresh-strategies-and-protected-routes)

**Token Management:**
```javascript
// Token storage
const token = localStorage.getItem('token');

// Axios interceptor
axios.interceptors.request.use((config) => {
  const token = getToken();
  if (token) {
    config.headers.Authorization = `Bearer ${token}`;
  }
  return config;
});

// Token refresh
const refreshToken = async () => {
  try {
    const response = await api.post('/refresh');
    setToken(response.data.token);
  } catch (error) {
    logout();
  }
};
```

**Protected Routes:**
```javascript
function ProtectedRoute({ children }) {
  const { isAuthenticated } = useAuth();
  
  if (!isAuthenticated) {
    return <Navigate to="/login" />;
  }
  
  return children;
}
```

### 4.5 Data Fetching Architecture
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#45-design-a-robust-data-fetching-layer-for-a-react-application-how-would-you-handle-caching-error-states-and-optimistic-updates)

**React Query Setup:**
```javascript
function App() {
  return (
    <QueryClient client={queryClient}>
      <Router>
        <Routes>
          <Route path="/" element={<Home />} />
        </Routes>
      </Router>
    </QueryClient>
  );
}

// Data fetching
function useUsers() {
  return useQuery({
    queryKey: ['users'],
    queryFn: fetchUsers,
    staleTime: 5 * 60 * 1000, // 5 minutes
  });
}
```

**Optimistic Updates:**
```javascript
const mutation = useMutation({
  mutationFn: updateUser,
  onMutate: async (newUser) => {
    await queryClient.cancelQueries(['users']);
    const previousUsers = queryClient.getQueryData(['users']);
    queryClient.setQueryData(['users'], old => [...old, newUser]);
    return { previousUsers };
  },
  onError: (err, newUser, context) => {
    queryClient.setQueryData(['users'], context.previousUsers);
  },
});
```

---

## 5. Coding Challenges

### 5.1 Debounce Function
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#51-implement-a-debounce-function)

```javascript
function debounce(func, delay) {
  let timeoutId;
  return function(...args) {
    clearTimeout(timeoutId);
    timeoutId = setTimeout(() => func.apply(this, args), delay);
  };
}

// Usage
const debouncedSearch = debounce((query) => {
  searchAPI(query);
}, 300);
```

### 5.2 Custom useIntersectionObserver Hook
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#52-build-a-custom-useintersectionobserver-hook)

```javascript
function useIntersectionObserver(ref, options = {}) {
  const [isIntersecting, setIsIntersecting] = useState(false);
  
  useEffect(() => {
    const observer = new IntersectionObserver(
      ([entry]) => setIsIntersecting(entry.isIntersecting),
      options
    );
    
    if (ref.current) {
      observer.observe(ref.current);
    }
    
    return () => observer.disconnect();
  }, [ref, options]);
  
  return isIntersecting;
}
```

### 5.3 Higher-Order Component
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#53-create-a-higher-order-component)

```javascript
function withLoading(WrappedComponent) {
  return function WithLoadingComponent({ isLoading, ...props }) {
    if (isLoading) {
      return <div>Loading...</div>;
    }
    return <WrappedComponent {...props} />;
  };
}

// Usage
const UserProfileWithLoading = withLoading(UserProfile);
```

### 5.4 Virtual Scroll List
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#54-implement-a-virtual-scroll-list)

```javascript
function VirtualList({ items, itemHeight, containerHeight }) {
  const [scrollTop, setScrollTop] = useState(0);
  
  const visibleStart = Math.floor(scrollTop / itemHeight);
  const visibleEnd = Math.min(
    visibleStart + Math.ceil(containerHeight / itemHeight),
    items.length
  );
  
  const visibleItems = items.slice(visibleStart, visibleEnd);
  
  return (
    <div
      style={{ height: containerHeight, overflow: 'auto' }}
      onScroll={(e) => setScrollTop(e.target.scrollTop)}
    >
      <div style={{ height: items.length * itemHeight, position: 'relative' }}>
        {visibleItems.map((item, index) => (
          <div
            key={visibleStart + index}
            style={{
              position: 'absolute',
              top: (visibleStart + index) * itemHeight,
              height: itemHeight,
            }}
          >
            {item}
          </div>
        ))}
      </div>
    </div>
  );
}
```

---

## 6. Behavioral & Scenario-Based

### 6.1 Performance Debugging Process
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#61-your-react-application-is-experiencing-slow-rendering-walk-through-your-debugging-process)

1. **Identify the problem**
   - Use React DevTools Profiler
   - Check bundle size
   - Monitor Core Web Vitals

2. **Analyze root cause**
   - Unnecessary re-renders
   - Large bundle size
   - Memory leaks
   - Inefficient algorithms

3. **Implement solutions**
   - Memoization (React.memo, useMemo, useCallback)
   - Code splitting
   - Lazy loading
   - Optimize images

4. **Measure improvements**
   - Performance budgets
   - Lighthouse scores
   - User experience metrics

### 6.2 TypeScript Migration Strategy
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#62-how-would-you-approach-migrating-a-large-javascript-codebase-to-typescript)

1. **Setup TypeScript**
   - Install dependencies
   - Configure tsconfig.json
   - Add type checking to CI

2. **Gradual migration**
   - Start with new files
   - Add types to existing files incrementally
   - Use `any` temporarily for complex types

3. **Type safety improvements**
   - Add strict mode gradually
   - Use utility types
   - Implement proper error handling

### 6.3 Scalable Dashboard Architecture
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#63-youre-building-a-dashboard-with-real-time-updates-complex-filtering-and-must-support-1000-concurrent-users-describe-your-architecture)

**Frontend Architecture:**
- **Micro-frontends** for different modules
- **Shared component library**
- **State management** with Redux Toolkit
- **Real-time updates** with WebSockets
- **Caching** with React Query

**Performance Optimizations:**
- **Virtual scrolling** for large lists
- **Debounced search** and filtering
- **Lazy loading** of components
- **Service workers** for offline support

### 6.4 Code Review Checklist
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#64-what-do-you-look-for-during-code-reviews-how-do-you-balance-perfectionism-with-pragmatism)

**Functionality:**
- ✅ Code works as expected
- ✅ Edge cases handled
- ✅ Error handling implemented
- ✅ Tests written and passing

**Code Quality:**
- ✅ Follows coding standards
- ✅ No code duplication
- ✅ Proper naming conventions
- ✅ Comments for complex logic

**Performance:**
- ✅ No unnecessary re-renders
- ✅ Efficient algorithms
- ✅ Proper memory management
- ✅ Bundle size considerations

**Security:**
- ✅ No sensitive data exposure
- ✅ Input validation
- ✅ XSS prevention
- ✅ CSRF protection

---

## 7. Best Practices & Patterns

### 7.1 Side Effects Management
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#71-what-are-your-preferred-patterns-for-handling-side-effects-in-react)

**useEffect Patterns:**
```javascript
// Data fetching
useEffect(() => {
  let cancelled = false;
  
  async function fetchData() {
    try {
      const data = await api.getData();
      if (!cancelled) {
        setData(data);
      }
    } catch (error) {
      if (!cancelled) {
        setError(error);
      }
    }
  }
  
  fetchData();
  
  return () => {
    cancelled = true;
  };
}, []);
```

### 7.2 Type Safety with APIs
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#72-how-do-you-ensure-type-safety-when-working-with-external-apis)

```typescript
// API response types
interface User {
  id: number;
  name: string;
  email: string;
}

interface ApiResponse<T> {
  data: T;
  status: 'success' | 'error';
  message?: string;
}

// API client with type safety
class ApiClient {
  async get<T>(url: string): Promise<ApiResponse<T>> {
    const response = await fetch(url);
    return response.json();
  }
}

// Usage
const api = new ApiClient();
const users = await api.get<User[]>('/users');
```

### 7.3 Styling Approaches
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#73-whats-your-approach-to-styling-in-react-applications-css-modules-styled-components-tailwind-etc)

| Approach | Pros | Cons | Use Case |
|----------|------|------|----------|
| **CSS Modules** | Scoped, simple | No dynamic styling | Component styling |
| **Styled Components** | Dynamic, themeable | Runtime overhead | Themed components |
| **Tailwind CSS** | Utility-first, fast | Learning curve | Rapid prototyping |
| **CSS-in-JS** | Component-scoped | Bundle size | Complex styling |

### 7.4 Internationalization (i18n)
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#74-how-do-you-handle-internationalization-i18n-and-accessibility-a11y-in-react-apps)

```javascript
// i18n setup
import i18n from 'i18next';
import { initReactI18next } from 'react-i18next';

i18n.use(initReactI18next).init({
  resources: {
    en: { translation: require('./locales/en.json') },
    es: { translation: require('./locales/es.json') },
  },
  lng: 'en',
  fallbackLng: 'en',
});

// Usage
function Component() {
  const { t } = useTranslation();
  return <h1>{t('welcome')}</h1>;
}
```

### 7.5 Code Quality Tools
> 📖 [Detailed explanation](./react-java-typescript-interview-questions.md#75-what-tools-and-processes-do-you-use-for-maintaining-code-quality-eslint-prettier-husky-cicd-etc)

**Essential Tools:**
- **ESLint**: Code linting and style enforcement
- **Prettier**: Code formatting
- **TypeScript**: Type safety
- **Husky**: Git hooks
- **lint-staged**: Pre-commit checks
- **Jest**: Unit testing
- **Cypress**: E2E testing

**Configuration Example:**
```json
// package.json
{
  "scripts": {
    "lint": "eslint src --ext .ts,.tsx",
    "lint:fix": "eslint src --ext .ts,.tsx --fix",
    "format": "prettier --write src/**/*.{ts,tsx}",
    "test": "jest",
    "test:coverage": "jest --coverage"
  },
  "husky": {
    "hooks": {
      "pre-commit": "lint-staged"
    }
  },
  "lint-staged": {
    "*.{ts,tsx}": ["eslint --fix", "prettier --write"]
  }
}
```

---

## 🎯 Quick Reference Cheat Sheet

### JavaScript Essentials
- **Event Loop**: Call Stack → Microtasks → Macrotasks
- **Closures**: Function + Lexical Environment
- **`this`**: Context-dependent, use `.bind()`, `.call()`, `.apply()`
- **Promises**: `.all()`, `.race()`, `.allSettled()`, `.any()`
- **var/let/const**: Block scope, hoisting, TDZ
- **ES6+**: Arrow functions, destructuring, spread/rest, modules
- **Async/Await**: Promise-based, try/catch error handling
- **Web APIs**: Fetch, localStorage, sessionStorage, IndexedDB
- **DOM**: Event delegation, bubbling/capturing
- **Regex**: Pattern matching, validation, string methods

### TypeScript Essentials
- **Types**: `string`, `number`, `boolean`, `object`, `array`
- **Interfaces**: Object shapes, extensible
- **Generics**: `<T>` for reusable components
- **Utility Types**: `Partial`, `Pick`, `Omit`, `Record`

### React Essentials
- **Hooks**: `useState`, `useEffect`, `useContext`, `useReducer`
- **Performance**: `React.memo`, `useMemo`, `useCallback`
- **Lifecycle**: Mount → Update → Unmount
- **State Management**: Local state → Context → Redux
- **React 19**: Compiler, Actions, use() hook, Document metadata
- **DevTools**: Component inspection, Profiler, Performance debugging
- **Bundle Analysis**: Webpack Bundle Analyzer, Code splitting, Tree shaking
- **Security**: XSS prevention, CSRF protection, Input validation
- **Build Tools**: Webpack vs Vite comparison

### System Design Essentials
- **Architecture**: Component-based, modular
- **Performance**: Code splitting, lazy loading, memoization
- **Testing**: Unit → Integration → E2E
- **Security**: Authentication, authorization, input validation

---

## 📚 Additional Resources

- [React Documentation](https://react.dev/)
- [TypeScript Handbook](https://www.typescriptlang.org/docs/)
- [MDN JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
- [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
- [Web.dev Performance](https://web.dev/performance/)

---

## 🔗 GitHub Navigation

When this repository is hosted on GitHub, all the links above will automatically work to navigate between the concise and detailed versions. The links use GitHub's automatic anchor generation for markdown headers.

**Repository Structure:**
```
interview-preparations/
├── react-java-typescript-interview-questions.md          # Detailed version
└── react-java-typescript-interview-questions-concise.md  # This concise version
```

**How to use:**
1. **Quick Revision**: Use this concise file for rapid review
2. **Deep Dive**: Click any "📖 Detailed explanation" link to jump to the comprehensive answer
3. **GitHub Navigation**: Links work seamlessly when hosted on GitHub

---

*This concise guide covers the essential concepts for JavaScript, TypeScript, and React interviews. Use it for quick revision and reference during preparation.*
