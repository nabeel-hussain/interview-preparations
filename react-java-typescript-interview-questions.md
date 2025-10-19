# Interview Questions JavaScript, TypeScript and React

- [Interview Questions JavaScript, TypeScript and React](#interview-questions-javascript-typescript-and-react)
  - [1. JavaScript Core Concepts](#1-javascript-core-concepts)
    - [1.1. Explain how the JavaScript event loop works. What's the difference between microtasks and macrotasks?](#11-explain-how-the-javascript-event-loop-works-whats-the-difference-between-microtasks-and-macrotasks)
    - [1.2. Explain closures and provide a practical use case where closures are essential. What are potential memory leak concerns with closures?](#12-explain-closures-and-provide-a-practical-use-case-where-closures-are-essential-what-are-potential-memory-leak-concerns-with-closures)
    - [1.3. How does prototypal inheritance differ from classical inheritance? Explain the prototype chain and how you would implement inheritance in modern JavaScript.](#13-how-does-prototypal-inheritance-differ-from-classical-inheritance-explain-the-prototype-chain-and-how-you-would-implement-inheritance-in-modern-javascript)
    - [1.4. Explain the different ways `this` can be bound in JavaScript. What are the differences between `.call()`, `.apply()`, and `.bind()`?](#14-explain-the-different-ways-this-can-be-bound-in-javascript-what-are-the-differences-between-call-apply-and-bind)
    - [1.5. What's the difference between Promise.all(), Promise.race(), Promise.allSettled(), and Promise.any()? When would you use each?](#15-whats-the-difference-between-promiseall-promiserace-promiseallsettled-and-promiseany-when-would-you-use-each)
    - [1.6. Explain the differences between var, let, and const. When should you use each?](#16-explain-the-differences-between-var-let-and-const-when-should-you-use-each)
    - [1.7. Explain how garbage collection works in JavaScript. What patterns can lead to memory leaks?](#17-explain-how-garbage-collection-works-in-javascript-what-patterns-can-lead-to-memory-leaks)
  - [2. ES6+ Features and Modern JavaScript](#2-es6-features-and-modern-javascript)
    - [2.1. Explain arrow functions and their differences from regular functions. When should you use each?](#21-explain-arrow-functions-and-their-differences-from-regular-functions-when-should-you-use-each)
    - [2.2. Explain destructuring assignment. Provide examples of object and array destructuring with practical use cases.](#22-explain-destructuring-assignment-provide-examples-of-object-and-array-destructuring-with-practical-use-cases)
    - [2.3. Explain the spread and rest operators. When would you use each?](#23-explain-the-spread-and-rest-operators-when-would-you-use-each)
    - [2.4. Explain template literals and tagged template literals. Provide practical examples.](#24-explain-template-literals-and-tagged-template-literals-provide-practical-examples)
    - [2.5. Explain ES6 modules (import/export). Compare with CommonJS and discuss module bundling.](#25-explain-es6-modules-importexport-compare-with-commonjs-and-discuss-module-bundling)
    - [2.6. Explain async/await syntax and how it relates to Promises. What are the benefits and potential pitfalls?](#26-explain-asyncawait-syntax-and-how-it-relates-to-promises-what-are-the-benefits-and-potential-pitfalls)
    - [2.7. Explain the Fetch API and how it differs from XMLHttpRequest. Provide examples of common use cases.](#27-explain-the-fetch-api-and-how-it-differs-from-xmlhttprequest-provide-examples-of-common-use-cases)
    - [2.8. Explain localStorage, sessionStorage, and IndexedDB. When would you use each?](#28-explain-localstorage-sessionstorage-and-indexeddb-when-would-you-use-each)
    - [2.9. Explain DOM manipulation and event handling. What are event delegation, bubbling, and capturing?](#29-explain-dom-manipulation-and-event-handling-what-are-event-delegation-bubbling-and-capturing)
    - [2.10. Explain Regular Expressions in JavaScript. Provide examples of common patterns and use cases.](#210-explain-regular-expressions-in-javascript-provide-examples-of-common-patterns-and-use-cases)
    - [2.11. Explain error handling in JavaScript. Compare different error handling strategies and when to use each.](#211-explain-error-handling-in-javascript-compare-different-error-handling-strategies-and-when-to-use-each)
  - [3. TypeScript Advanced Topics](#3-typescript-advanced-topics)
    - [3.1. Explain the difference between `type` and `interface`. When would you choose one over the other?](#31-explain-the-difference-between-type-and-interface-when-would-you-choose-one-over-the-other)
    - [3.2. What are generics and why are they useful? Provide an example of a generic function that demonstrates type safety.](#32-what-are-generics-and-why-are-they-useful-provide-an-example-of-a-generic-function-that-demonstrates-type-safety)
    - [3.3. Explain how Partial, Pick, Omit, and Record utility types work. When would you use conditional types?](#33-explain-how-partial-pick-omit-and-record-utility-types-work-when-would-you-use-conditional-types)
    - [3.4. What are type guards? Implement a custom type guard function and explain how TypeScript narrows types.](#34-what-are-type-guards-implement-a-custom-type-guard-function-and-explain-how-typescript-narrows-types)
    - [3.5. Explain mapped types and template literal types. Provide a practical example where these would be beneficial.](#35-explain-mapped-types-and-template-literal-types-provide-a-practical-example-where-these-would-be-beneficial)
    - [3.6. How does TypeScript's type inference work? What are the limitations, and when should you explicitly type things?](#36-how-does-typescripts-type-inference-work-what-are-the-limitations-and-when-should-you-explicitly-type-things)
  - [4. React Architecture \& Patterns](#4-react-architecture--patterns)
    - [4.1. Explain the React component lifecycle in function components. How do useEffect dependencies work, and what are common pitfalls?](#41-explain-the-react-component-lifecycle-in-function-components-how-do-useeffect-dependencies-work-and-what-are-common-pitfalls)
    - [4.2. Compare different state management solutions (Context API, Redux, Zustand, Jotai). When would you choose each?](#42-compare-different-state-management-solutions-context-api-redux-zustand-jotai-when-would-you-choose-each)
    - [4.3. Explain React.memo, useMemo, and useCallback. What's the difference, and when should each be used?](#43-explain-reactmemo-usememo-and-usecallback-whats-the-difference-and-when-should-each-be-used)
    - [4.4. What are the rules of hooks? Design a custom hook for handling form state with validation.](#44-what-are-the-rules-of-hooks-design-a-custom-hook-for-handling-form-state-with-validation)
    - [4.5. Explain React 18's concurrent features (useTransition, useDeferredValue, Suspense). How do they improve user experience?](#45-explain-react-18s-concurrent-features-usetransition-usedeferredvalue-suspense-how-do-they-improve-user-experience)
    - [4.6. Explain how React's reconciliation algorithm works. What is the significance of keys in lists?](#46-explain-how-reacts-reconciliation-algorithm-works-what-is-the-significance-of-keys-in-lists)
    - [4.7. What are Error Boundaries and their limitations? How would you implement error handling in a React application?](#47-what-are-error-boundaries-and-their-limitations-how-would-you-implement-error-handling-in-a-react-application)
    - [4.8. Explain the difference between Server Components and Client Components. What are the trade-offs?](#48-explain-the-difference-between-server-components-and-client-components-what-are-the-trade-offs)
    - [4.9. What's the difference between useEffect and useLayoutEffect? When would you use each?](#49-whats-the-difference-between-useeffect-and-uselayouteffect-when-would-you-use-each)
    - [4.10. When should you use useState vs useReducer? Provide examples of each.](#410-when-should-you-use-usestate-vs-usereducer-provide-examples-of-each)
    - [4.11. Explain the Context API in detail. How do you avoid performance issues with Context?](#411-explain-the-context-api-in-detail-how-do-you-avoid-performance-issues-with-context)
    - [4.12. How do you implement routing in React applications? Compare different routing solutions.](#412-how-do-you-implement-routing-in-react-applications-compare-different-routing-solutions)
    - [4.13. What are React Portals and when would you use them?](#413-what-are-react-portals-and-when-would-you-use-them)
    - [4.14. Provide a comprehensive overview of all React hooks in table format with brief descriptions and use cases.](#414-provide-a-comprehensive-overview-of-all-react-hooks-in-table-format-with-brief-descriptions-and-use-cases)
    - [4.15. How do you use refs for DOM interaction in React? What are the different types of refs?](#415-how-do-you-use-refs-for-dom-interaction-in-react-what-are-the-different-types-of-refs)
    - [4.16. What are the new features in React 19? How do they improve developer experience and performance?](#416-what-are-the-new-features-in-react-19-how-do-they-improve-developer-experience-and-performance)
    - [4.17. How do you use React DevTools for debugging and performance optimization?](#417-how-do-you-use-react-devtools-for-debugging-and-performance-optimization)
    - [4.18. How do you analyze and optimize React bundle size? What tools and techniques do you use?](#418-how-do-you-analyze-and-optimize-react-bundle-size-what-tools-and-techniques-do-you-use)
    - [4.19. What are the key security considerations when building React applications? How do you prevent common vulnerabilities?](#419-what-are-the-key-security-considerations-when-building-react-applications-how-do-you-prevent-common-vulnerabilities)
    - [4.20. Compare Webpack and Vite for React development. What are the advantages and disadvantages of each?](#420-compare-webpack-and-vite-for-react-development-what-are-the-advantages-and-disadvantages-of-each)
  - [5. System Design \& Architecture](#5-system-design--architecture)
    - [5.1. How would you design a reusable, accessible component library? What principles would you follow?](#51-how-would-you-design-a-reusable-accessible-component-library-what-principles-would-you-follow)
      - [5.1.1. Core Design Principles](#511-core-design-principles)
      - [5.1.2. Accessibility (a11y) Principles](#512-accessibility-a11y-principles)
      - [5.1.3. TypeScript Integration](#513-typescript-integration)
      - [5.1.4. Styling Strategy](#514-styling-strategy)
      - [5.1.5. Documentation \& Testing](#515-documentation--testing)
      - [5.1.6. Performance Considerations](#516-performance-considerations)
    - [5.2. Explain different strategies for code splitting in React. How would you implement route-based code splitting?](#52-explain-different-strategies-for-code-splitting-in-react-how-would-you-implement-route-based-code-splitting)
      - [5.2.1. Code Splitting Strategies](#521-code-splitting-strategies)
      - [5.2.2. Advanced Code Splitting Patterns](#522-advanced-code-splitting-patterns)
      - [5.2.3. Webpack Configuration for Code Splitting](#523-webpack-configuration-for-code-splitting)
      - [5.2.4. Performance Monitoring](#524-performance-monitoring)
      - [5.2.5. Best Practices](#525-best-practices)
    - [5.3. What's your approach to testing React applications? How do you balance unit, integration, and e2e tests?](#53-whats-your-approach-to-testing-react-applications-how-do-you-balance-unit-integration-and-e2e-tests)
      - [5.3.1. Testing Pyramid Structure](#531-testing-pyramid-structure)
      - [5.3.2. Unit Testing](#532-unit-testing)
      - [5.3.3. Integration Testing](#533-integration-testing)
      - [5.3.4. End-to-End Testing](#534-end-to-end-testing)
      - [5.3.5. Testing Configuration](#535-testing-configuration)
      - [5.3.6. Testing Best Practices](#536-testing-best-practices)
      - [5.3.7. Continuous Integration](#537-continuous-integration)
    - [5.4. How would you implement authentication in a React SPA? Discuss token management, refresh strategies, and protected routes.](#54-how-would-you-implement-authentication-in-a-react-spa-discuss-token-management-refresh-strategies-and-protected-routes)
      - [5.4.1. Authentication Architecture](#541-authentication-architecture)
      - [5.4.2. Token Management](#542-token-management)
      - [5.4.3. Protected Routes](#543-protected-routes)
      - [5.4.4. Advanced Security Features](#544-advanced-security-features)
      - [5.4.5. Security Best Practices](#545-security-best-practices)
      - [5.4.6. Error Handling and User Experience](#546-error-handling-and-user-experience)
    - [5.5. Design a robust data fetching layer for a React application. How would you handle caching, error states, and optimistic updates?](#55-design-a-robust-data-fetching-layer-for-a-react-application-how-would-you-handle-caching-error-states-and-optimistic-updates)
      - [5.5.1. Core Data Fetching Architecture](#551-core-data-fetching-architecture)
      - [5.5.2. Advanced Caching with React Query](#552-advanced-caching-with-react-query)
      - [5.5.3. Optimistic Updates](#553-optimistic-updates)
      - [5.5.4. Error Handling and Retry Logic](#554-error-handling-and-retry-logic)
      - [5.5.5. Real-time Data with WebSockets](#555-real-time-data-with-websockets)
      - [5.5.6. Offline Support and Background Sync](#556-offline-support-and-background-sync)
      - [5.5.7. Performance Optimization](#557-performance-optimization)
  - [6. Coding Challenges](#6-coding-challenges)
    - [6.1. Implement a Debounce Function](#61-implement-a-debounce-function)
    - [6.2. Build a Custom useIntersectionObserver Hook](#62-build-a-custom-useintersectionobserver-hook)
    - [6.3. Create a Higher-Order Component](#63-create-a-higher-order-component)
    - [6.4. Implement a Virtual Scroll List](#64-implement-a-virtual-scroll-list)
    - [6.5. Build a Form Builder](#65-build-a-form-builder)
  - [7. Behavioral \& Scenario-Based](#7-behavioral--scenario-based)
    - [7.1. Your React application is experiencing slow rendering. Walk through your debugging process.](#71-your-react-application-is-experiencing-slow-rendering-walk-through-your-debugging-process)
    - [7.2. How would you approach migrating a large JavaScript codebase to TypeScript?](#72-how-would-you-approach-migrating-a-large-javascript-codebase-to-typescript)
    - [7.3. You're building a dashboard with real-time updates, complex filtering, and must support 1000+ concurrent users. Describe your architecture.](#73-youre-building-a-dashboard-with-real-time-updates-complex-filtering-and-must-support-1000-concurrent-users-describe-your-architecture)
    - [7.4. What do you look for during code reviews? How do you balance perfectionism with pragmatism?](#74-what-do-you-look-for-during-code-reviews-how-do-you-balance-perfectionism-with-pragmatism)
    - [7.5. How do you identify and prioritize technical debt? Give an example of when you advocated for refactoring.](#75-how-do-you-identify-and-prioritize-technical-debt-give-an-example-of-when-you-advocated-for-refactoring)
  - [8. Best Practices \& Patterns](#8-best-practices--patterns)
    - [8.1. What are your preferred patterns for handling side effects in React?](#81-what-are-your-preferred-patterns-for-handling-side-effects-in-react)
    - [8.2. How do you ensure type safety when working with external APIs?](#82-how-do-you-ensure-type-safety-when-working-with-external-apis)
    - [8.3. What's your approach to styling in React applications? (CSS Modules, Styled Components, Tailwind, etc.)](#83-whats-your-approach-to-styling-in-react-applications-css-modules-styled-components-tailwind-etc)
    - [8.4. How do you handle internationalization (i18n) and accessibility (a11y) in React apps?](#84-how-do-you-handle-internationalization-i18n-and-accessibility-a11y-in-react-apps)
    - [8.5. What tools and processes do you use for maintaining code quality? (ESLint, Prettier, Husky, CI/CD, etc.)](#85-what-tools-and-processes-do-you-use-for-maintaining-code-quality-eslint-prettier-husky-cicd-etc)


## 1. JavaScript Core Concepts

### 1.1. Explain how the JavaScript event loop works. What's the difference between microtasks and macrotasks?

**Answer:**
The JavaScript event loop is the mechanism that allows JavaScript to handle asynchronous operations despite being single-threaded. Here's how it works:

**Components:**
- **Call Stack**: Executes synchronous code (LIFO - Last In, First Out)
- **Web APIs**: Browser APIs for timers, DOM events, HTTP requests
- **Task Queue (Macrotask Queue)**: For callbacks from setTimeout, setInterval, DOM events
- **Microtask Queue**: For callbacks from Promises, queueMicrotask, MutationObserver

**Execution Flow:**
1. Execute all synchronous code in the call stack
2. When call stack is empty, process ALL microtasks first
3. Then process ONE macrotask
4. Repeat

**Microtasks vs Macrotasks:**
- **Microtasks** (higher priority): Promise callbacks (.then, .catch, .finally), queueMicrotask(), MutationObserver callbacks
- **Macrotasks** (lower priority): setTimeout/setInterval callbacks, DOM event callbacks, I/O operations

**Example:**
```javascript
console.log('1'); // Synchronous
setTimeout(() => console.log('2'), 0); // Macrotask
Promise.resolve().then(() => console.log('3')); // Microtask
console.log('4'); // Synchronous
// Output: 1, 4, 3, 2
```

**Follow-up:** How would you handle a situation where you need to execute multiple async operations in parallel but want to wait for all of them to complete?

**Answer:**
Use `Promise.all()` for parallel execution with all-or-nothing behavior, or `Promise.allSettled()` for handling individual failures:

```javascript
// All-or-nothing approach
async function fetchMultipleData() {
  try {
    const [users, posts, comments] = await Promise.all([
      fetch('/api/users').then(res => res.json()),
      fetch('/api/posts').then(res => res.json()),
      fetch('/api/comments').then(res => res.json())
    ]);
    return { users, posts, comments };
  } catch (error) {
    console.error('One or more requests failed:', error);
    throw error;
  }
}

// Handle individual failures
async function fetchWithFallback() {
  const results = await Promise.allSettled([
    fetch('/api/users').then(res => res.json()),
    fetch('/api/posts').then(res => res.json()),
    fetch('/api/comments').then(res => res.json())
  ]);
  
  return results.map((result, index) => {
    if (result.status === 'fulfilled') {
      return result.value;
    } else {
      console.error(`Request ${index} failed:`, result.reason);
      return null; // or default value
    }
  });
}
```

### 1.2. Explain closures and provide a practical use case where closures are essential. What are potential memory leak concerns with closures?

**Answer:**
A closure is a function that has access to variables in its outer (enclosing) scope even after the outer function has returned. The closure "closes over" the variables it needs.

**Basic Example:**
```javascript
function outerFunction(x) {
  const outerVariable = x;
  
  function innerFunction(y) {
    console.log(outerVariable + y); // Access to outer scope
  }
  
  return innerFunction;
}

const closure = outerFunction(10);
closure(5); // Output: 15
// outerFunction has finished, but innerFunction still has access to outerVariable
```

**Practical Use Cases:**

1. **Data Privacy (Module Pattern):**
```javascript
function createCounter() {
  let count = 0; // Private variable
  
  return {
    increment: () => ++count,
    decrement: () => --count,
    getCount: () => count
  };
}

const counter = createCounter();
console.log(counter.getCount()); // 0
counter.increment();
console.log(counter.getCount()); // 1
// count is not directly accessible from outside
```

2. **Function Factories:**
```javascript
function createMultiplier(factor) {
  return function(number) {
    return number * factor;
  };
}

const double = createMultiplier(2);
const triple = createMultiplier(3);

console.log(double(5)); // 10
console.log(triple(5)); // 15
```

3. **Event Handlers with State:**
```javascript
function setupButton(buttonId, clickCount) {
  const button = document.getElementById(buttonId);
  
  button.addEventListener('click', function() {
    clickCount++;
    console.log(`Button clicked ${clickCount} times`);
  });
}

setupButton('myButton', 0);
// Each button maintains its own click count
```

**Memory Leak Concerns:**
- **Circular References**: Closures can create circular references that prevent garbage collection
- **Large Objects**: Keeping references to large objects in closures
- **Event Listeners**: Not removing event listeners that reference closures

**Prevention:**
```javascript
// Good: Explicit cleanup
function createLeakyClosure() {
  const largeObject = new Array(1000000).fill('data');
  
  return function() {
    // Use largeObject
    return largeObject.length;
  };
}

// Better: Clear references when done
function createSafeClosure() {
  const largeObject = new Array(1000000).fill('data');
  
  const closure = function() {
    return largeObject.length;
  };
  
  // Provide cleanup method
  closure.cleanup = function() {
    largeObject.length = 0; // Clear the array
  };
  
  return closure;
}
```

### 1.3. How does prototypal inheritance differ from classical inheritance? Explain the prototype chain and how you would implement inheritance in modern JavaScript.

**Answer:**
**Classical vs Prototypal Inheritance:**

**Classical Inheritance:**
- Based on classes (blueprints)
- Objects are instances of classes
- Inheritance is defined at compile time
- Single inheritance (one parent class)
- Found in Java, C++, C#

**Prototypal Inheritance:**
- Based on prototypes (objects)
- Objects inherit directly from other objects
- Inheritance is dynamic and flexible
- Can have multiple prototypes (mixins)
- Found in JavaScript

**Prototype Chain:**
Every object in JavaScript has a prototype property that points to another object. When you access a property, JavaScript looks up the prototype chain until it finds the property or reaches `null`.

```javascript
// Prototype chain example
const animal = {
  type: 'animal',
  speak() {
    console.log('Some sound');
  }
};

const dog = Object.create(animal);
dog.breed = 'Labrador';
dog.speak = function() {
  console.log('Woof!');
};

const puppy = Object.create(dog);
puppy.age = 2;

console.log(puppy.type); // 'animal' (from animal prototype)
console.log(puppy.breed); // 'Labrador' (from dog prototype)
console.log(puppy.age); // 2 (own property)
puppy.speak(); // 'Woof!' (from dog prototype)
```

**Modern JavaScript Inheritance Implementation:**

1. **Using ES6 Classes (Syntactic Sugar):**
```javascript
class Animal {
  constructor(name) {
    this.name = name;
  }
  
  speak() {
    console.log(`${this.name} makes a sound`);
  }
}

class Dog extends Animal {
  constructor(name, breed) {
    super(name);
    this.breed = breed;
  }
  
  speak() {
    console.log(`${this.name} barks`);
  }
  
  fetch() {
    console.log(`${this.name} fetches the ball`);
  }
}

const dog = new Dog('Buddy', 'Golden Retriever');
dog.speak(); // 'Buddy barks'
dog.fetch(); // 'Buddy fetches the ball'
```

2. **Using Object.create() (True Prototypal):**
```javascript
// Base object
const animal = {
  init(name) {
    this.name = name;
    return this;
  },
  
  speak() {
    console.log(`${this.name} makes a sound`);
  }
};

// Create dog object that inherits from animal
const dog = Object.create(animal);
dog.init = function(name, breed) {
  animal.init.call(this, name);
  this.breed = breed;
  return this;
};

dog.speak = function() {
  console.log(`${this.name} barks`);
};

dog.fetch = function() {
  console.log(`${this.name} fetches the ball`);
};

const buddy = Object.create(dog).init('Buddy', 'Golden Retriever');
buddy.speak(); // 'Buddy barks'
buddy.fetch(); // 'Buddy fetches the ball'
```

3. **Using Factory Functions:**
```javascript
function createAnimal(name) {
  return {
    name,
    speak() {
      console.log(`${this.name} makes a sound`);
    }
  };
}

function createDog(name, breed) {
  const dog = createAnimal(name);
  dog.breed = breed;
  
  const originalSpeak = dog.speak;
  dog.speak = function() {
    console.log(`${this.name} barks`);
  };
  
  dog.fetch = function() {
    console.log(`${this.name} fetches the ball`);
  };
  
  return dog;
}

const buddy = createDog('Buddy', 'Golden Retriever');
buddy.speak(); // 'Buddy barks'
buddy.fetch(); // 'Buddy fetches the ball'
```

**Key Differences:**
- **Flexibility**: Prototypal inheritance is more flexible - you can add/remove properties at runtime
- **Memory**: Prototypal inheritance can be more memory efficient as methods are shared
- **Multiple Inheritance**: Easier to achieve with mixins in prototypal inheritance
- **Performance**: Modern engines optimize both approaches similarly

### 1.4. Explain the different ways `this` can be bound in JavaScript. What are the differences between `.call()`, `.apply()`, and `.bind()`?

**Answer:**
The `this` keyword in JavaScript refers to the object that is currently executing the function. Its value depends on how the function is called, not where it's defined.

**Different Ways `this` Can Be Bound:**

1. **Default Binding (Global/Window):**
```javascript
function greet() {
  console.log(this); // Window object (in browser) or global (in Node.js)
}
greet(); // Called without any context
```

2. **Implicit Binding (Object Method):**
```javascript
const person = {
  name: 'John',
  greet() {
    console.log(`Hello, I'm ${this.name}`);
  }
};
person.greet(); // this = person object
```

3. **Explicit Binding (.call(), .apply(), .bind()):**
```javascript
function greet() {
  console.log(`Hello, I'm ${this.name}`);
}

const person1 = { name: 'Alice' };
const person2 = { name: 'Bob' };

// .call() - calls function immediately with specified this
greet.call(person1); // "Hello, I'm Alice"

// .apply() - same as call but takes array of arguments
greet.apply(person2); // "Hello, I'm Bob"

// .bind() - returns new function with bound this
const boundGreet = greet.bind(person1);
boundGreet(); // "Hello, I'm Alice"
```

4. **New Binding (Constructor):**
```javascript
function Person(name) {
  this.name = name;
  this.greet = function() {
    console.log(`Hello, I'm ${this.name}`);
  };
}

const john = new Person('John');
john.greet(); // this = john instance
```

5. **Arrow Functions (Lexical Binding):**
```javascript
const person = {
  name: 'John',
  greet: () => {
    console.log(this.name); // this = global object, not person
  },
  greetProperly() {
    const inner = () => {
      console.log(this.name); // this = person (inherited from outer scope)
    };
    inner();
  }
};
```

**Differences Between .call(), .apply(), and .bind():**

```javascript
function introduce(age, city) {
  console.log(`I'm ${this.name}, ${age} years old, from ${city}`);
}

const person = { name: 'Alice' };

// .call() - immediate execution, arguments passed individually
introduce.call(person, 25, 'New York');
// Output: "I'm Alice, 25 years old, from New York"

// .apply() - immediate execution, arguments passed as array
introduce.apply(person, [25, 'New York']);
// Output: "I'm Alice, 25 years old, from New York"

// .bind() - returns new function, can be called later
const boundIntroduce = introduce.bind(person, 25, 'New York');
boundIntroduce(); // Same output as above

// Partial binding
const boundWithAge = introduce.bind(person, 25);
boundWithAge('Boston'); // "I'm Alice, 25 years old, from Boston"
```

**Practical Examples:**

```javascript
// Borrowing methods
const arrayLike = {
  0: 'a',
  1: 'b',
  2: 'c',
  length: 3
};

// Use Array.prototype.slice on array-like object
const realArray = Array.prototype.slice.call(arrayLike);
console.log(realArray); // ['a', 'b', 'c']

// Event handlers
class Button {
  constructor(element) {
    this.element = element;
    this.clickCount = 0;
    
    // Without bind, this would be the DOM element
    this.element.addEventListener('click', this.handleClick.bind(this));
  }
  
  handleClick() {
    this.clickCount++;
    console.log(`Clicked ${this.clickCount} times`);
  }
}

// Currying with bind
function multiply(a, b) {
  return a * b;
}

const double = multiply.bind(null, 2);
console.log(double(5)); // 10

const triple = multiply.bind(null, 3);
console.log(triple(4)); // 12
```

### 1.5. What's the difference between Promise.all(), Promise.race(), Promise.allSettled(), and Promise.any()? When would you use each?

**Answer:**
These are different Promise combinator methods that handle multiple promises in various ways:

**Promise.all():**
- Waits for ALL promises to resolve
- Fails fast - rejects if ANY promise rejects
- Returns array of resolved values in same order
- Use when: You need all operations to succeed

```javascript
const promises = [
  fetch('/api/users'),
  fetch('/api/posts'),
  fetch('/api/comments')
];

try {
  const [users, posts, comments] = await Promise.all(promises);
  // All requests succeeded
} catch (error) {
  // At least one request failed
  console.error('One or more requests failed:', error);
}
```

**Promise.race():**
- Returns the FIRST promise to settle (resolve or reject)
- Use when: You want the fastest result, regardless of success/failure

```javascript
const timeoutPromise = new Promise((_, reject) => 
  setTimeout(() => reject(new Error('Timeout')), 5000)
);

const dataPromise = fetch('/api/slow-endpoint');

try {
  const result = await Promise.race([dataPromise, timeoutPromise]);
  // Got data before timeout
} catch (error) {
  // Either timeout or request failed
  console.error('Request failed or timed out:', error);
}
```

**Promise.allSettled():**
- Waits for ALL promises to settle (resolve or reject)
- Never rejects - always resolves with array of results
- Use when: You want to know the outcome of all operations

```javascript
const promises = [
  fetch('/api/users'),
  fetch('/api/posts'),
  fetch('/api/comments')
];

const results = await Promise.allSettled(promises);

results.forEach((result, index) => {
  if (result.status === 'fulfilled') {
    console.log(`Request ${index} succeeded:`, result.value);
  } else {
    console.log(`Request ${index} failed:`, result.reason);
  }
});
```

**Promise.any():**
- Returns the FIRST promise to resolve (ignores rejections)
- Only rejects if ALL promises reject
- Use when: You want the first successful result

```javascript
const fallbackPromises = [
  fetch('/api/primary'),
  fetch('/api/backup1'),
  fetch('/api/backup2')
];

try {
  const result = await Promise.any(fallbackPromises);
  // Got data from first successful endpoint
} catch (error) {
  // All endpoints failed
  console.error('All endpoints failed:', error);
}
```

**Coding Challenge:** Implement a function that retries a failed async operation with exponential backoff.

**Answer:**
```javascript
async function retryWithBackoff(
  asyncFn, 
  maxRetries = 3, 
  baseDelay = 1000, 
  maxDelay = 10000
) {
  let lastError;
  
  for (let attempt = 0; attempt <= maxRetries; attempt++) {
    try {
      return await asyncFn();
    } catch (error) {
      lastError = error;
      
      if (attempt === maxRetries) {
        throw new Error(`Failed after ${maxRetries + 1} attempts: ${error.message}`);
      }
      
      // Calculate delay with exponential backoff and jitter
      const delay = Math.min(
        baseDelay * Math.pow(2, attempt) + Math.random() * 1000,
        maxDelay
      );
      
      console.log(`Attempt ${attempt + 1} failed, retrying in ${Math.round(delay)}ms...`);
      await new Promise(resolve => setTimeout(resolve, delay));
    }
  }
}

// Usage example
async function fetchUserData(userId) {
  const response = await fetch(`/api/users/${userId}`);
  if (!response.ok) {
    throw new Error(`HTTP ${response.status}: ${response.statusText}`);
  }
  return response.json();
}

// Retry with custom configuration
try {
  const userData = await retryWithBackoff(
    () => fetchUserData(123),
    5,    // max retries
    1000, // base delay (1s)
    30000 // max delay (30s)
  );
  console.log('User data:', userData);
} catch (error) {
  console.error('Failed to fetch user data:', error);
}

// Advanced version with different retry strategies
class RetryStrategy {
  static async exponentialBackoff(asyncFn, options = {}) {
    const {
      maxRetries = 3,
      baseDelay = 1000,
      maxDelay = 10000,
      jitter = true,
      retryCondition = () => true
    } = options;
    
    let lastError;
    
    for (let attempt = 0; attempt <= maxRetries; attempt++) {
      try {
        return await asyncFn();
      } catch (error) {
        lastError = error;
        
        if (attempt === maxRetries || !retryCondition(error)) {
          throw error;
        }
        
        const delay = Math.min(
          baseDelay * Math.pow(2, attempt) + (jitter ? Math.random() * 1000 : 0),
          maxDelay
        );
        
        await new Promise(resolve => setTimeout(resolve, delay));
      }
    }
  }
  
  static async linearBackoff(asyncFn, options = {}) {
    const { maxRetries = 3, delay = 1000 } = options;
    
    for (let attempt = 0; attempt <= maxRetries; attempt++) {
      try {
        return await asyncFn();
      } catch (error) {
        if (attempt === maxRetries) throw error;
        await new Promise(resolve => setTimeout(resolve, delay));
      }
    }
  }
}
```

### 1.6. Explain the differences between var, let, and const. When should you use each?

**Answer:**
The three variable declaration keywords in JavaScript have different scoping rules, hoisting behavior, and mutability characteristics.

**Key Differences:**

| Feature | var | let | const |
|---------|-----|-----|-------|
| Scope | Function-scoped | Block-scoped | Block-scoped |
| Hoisting | Hoisted and initialized with undefined | Hoisted but not initialized (TDZ) | Hoisted but not initialized (TDZ) |
| Re-declaration | Allowed | Not allowed | Not allowed |
| Re-assignment | Allowed | Allowed | Not allowed |
| Temporal Dead Zone | No | Yes | Yes |

**1. Scope Differences:**
```javascript
// var - function scoped
function example() {
  if (true) {
    var functionScoped = 'I am function scoped';
  }
  console.log(functionScoped); // Works - accessible outside block
}

// let/const - block scoped
function example() {
  if (true) {
    let blockScoped = 'I am block scoped';
    const alsoBlockScoped = 'I am also block scoped';
  }
  console.log(blockScoped); // ReferenceError: blockScoped is not defined
  console.log(alsoBlockScoped); // ReferenceError: alsoBlockScoped is not defined
}
```

**2. Hoisting Behavior:**
```javascript
// var - hoisted and initialized with undefined
console.log(varVariable); // undefined (not ReferenceError)
var varVariable = 'Hello';

// let/const - hoisted but in Temporal Dead Zone
console.log(letVariable); // ReferenceError: Cannot access 'letVariable' before initialization
let letVariable = 'Hello';

console.log(constVariable); // ReferenceError: Cannot access 'constVariable' before initialization
const constVariable = 'Hello';
```

**3. Re-declaration:**
```javascript
// var - allows re-declaration
var name = 'John';
var name = 'Jane'; // No error
console.log(name); // 'Jane'

// let - does not allow re-declaration
let age = 25;
let age = 30; // SyntaxError: Identifier 'age' has already been declared

// const - does not allow re-declaration
const city = 'NYC';
const city = 'LA'; // SyntaxError: Identifier 'city' has already been declared
```

**4. Re-assignment:**
```javascript
// var and let - allow re-assignment
var count = 0;
count = 1; // Works

let total = 10;
total = 20; // Works

// const - does not allow re-assignment
const PI = 3.14159;
PI = 3.14; // TypeError: Assignment to constant variable
```

**5. Temporal Dead Zone (TDZ):**
```javascript
// TDZ for let and const
function tdzExample() {
  console.log(typeof x); // ReferenceError: Cannot access 'x' before initialization
  let x = 10;
}

// var does not have TDZ
function noTdzExample() {
  console.log(typeof y); // 'undefined'
  var y = 10;
}
```

**When to Use Each:**

**Use `const` by default:**
```javascript
// ✅ Use const for values that won't change
const API_URL = 'https://api.example.com';
const MAX_RETRIES = 3;
const user = { name: 'John', age: 30 };

// const with objects/arrays - you can modify contents
const users = [];
users.push({ name: 'Jane' }); // Works - modifying array contents
// users = []; // Error - cannot reassign the array reference

const config = { theme: 'dark' };
config.theme = 'light'; // Works - modifying object properties
// config = {}; // Error - cannot reassign the object reference
```

**Use `let` when you need to reassign:**
```javascript
// ✅ Use let when value needs to change
let currentUser = null;
let isLoading = false;
let counter = 0;

// In loops
for (let i = 0; i < 10; i++) {
  setTimeout(() => console.log(i), 100); // Each i is block-scoped
}

// In conditionals
let result;
if (condition) {
  result = 'success';
} else {
  result = 'failure';
}
```

**Avoid `var` (legacy):**
```javascript
// ❌ Avoid var in modern JavaScript
var oldStyle = 'avoid this';

// Problems with var:
// 1. Function scoping can be confusing
for (var i = 0; i < 3; i++) {
  setTimeout(() => console.log(i), 100); // Prints 3, 3, 3
}

// 2. Hoisting can lead to unexpected behavior
console.log(hoisted); // undefined (not ReferenceError)
var hoisted = 'I am hoisted';

// 3. Re-declaration can cause bugs
var name = 'John';
// ... 100 lines later ...
var name = 'Jane'; // Accidentally overwrites previous declaration
```

**Modern Best Practices:**
```javascript
// ✅ Modern approach
const DEFAULT_CONFIG = {
  apiUrl: 'https://api.example.com',
  timeout: 5000
};

function processData(data) {
  const results = [];
  let hasErrors = false;
  
  for (const item of data) {
    try {
      const processed = transformItem(item);
      results.push(processed);
    } catch (error) {
      hasErrors = true;
      console.error('Processing error:', error);
    }
  }
  
  return { results, hasErrors };
}

// ✅ Use const for function declarations
const calculateTotal = (items) => {
  return items.reduce((sum, item) => sum + item.price, 0);
};

// ✅ Use const for imported modules
import { useState, useEffect } from 'react';
const MyComponent = () => {
  const [count, setCount] = useState(0);
  // ...
};
```

**Summary:**
- **const**: Use by default for all variables that won't be reassigned
- **let**: Use when you need to reassign the variable
- **var**: Avoid in modern JavaScript due to confusing scoping and hoisting behavior

### 1.7. Explain how garbage collection works in JavaScript. What patterns can lead to memory leaks?

**Answer:**
JavaScript uses automatic garbage collection to manage memory, freeing up memory that is no longer referenced by the program.

**How Garbage Collection Works:**

**Mark and Sweep Algorithm:**
1. **Mark Phase**: Traverses all reachable objects from root references (global variables, call stack)
2. **Sweep Phase**: Removes all unmarked objects (unreachable)
3. **Compact Phase**: Defragments memory (optional, varies by engine)

**Generational Collection:**
- **Young Generation**: New objects, collected frequently
- **Old Generation**: Long-lived objects, collected less frequently
- Objects that survive multiple collections move to old generation

**Memory Leak Patterns:**

1. **Global Variables:**
```javascript
// BAD: Creates global variables
function createUser() {
  name = 'John'; // Missing var/let/const
  this.email = 'john@example.com'; // this refers to global in non-strict mode
}

// GOOD: Proper variable declaration
function createUser() {
  const name = 'John';
  const email = 'john@example.com';
  return { name, email };
}
```

2. **Closures with Large Objects:**
```javascript
// BAD: Keeps large object in memory
function createHandler() {
  const largeData = new Array(1000000).fill('data');
  
  return function(event) {
    // Handler keeps reference to largeData
    console.log('Event handled');
  };
}

// GOOD: Clear references when done
function createHandler() {
  const largeData = new Array(1000000).fill('data');
  
  const handler = function(event) {
    console.log('Event handled');
  };
  
  // Provide cleanup method
  handler.cleanup = function() {
    largeData.length = 0;
  };
  
  return handler;
}
```

3. **Event Listeners:**
```javascript
// BAD: No cleanup
class Component {
  constructor(element) {
    this.element = element;
    this.element.addEventListener('click', this.handleClick);
  }
  
  handleClick = () => {
    console.log('Clicked');
  }
}

// GOOD: Proper cleanup
class Component {
  constructor(element) {
    this.element = element;
    this.boundHandleClick = this.handleClick.bind(this);
    this.element.addEventListener('click', this.boundHandleClick);
  }
  
  handleClick() {
    console.log('Clicked');
  }
  
  destroy() {
    this.element.removeEventListener('click', this.boundHandleClick);
    this.element = null;
  }
}
```

4. **Timers and Intervals:**
```javascript
// BAD: No cleanup
class Timer {
  constructor() {
    this.interval = setInterval(() => {
      console.log('Timer tick');
    }, 1000);
  }
}

// GOOD: Proper cleanup
class Timer {
  constructor() {
    this.interval = setInterval(() => {
      console.log('Timer tick');
    }, 1000);
  }
  
  destroy() {
    if (this.interval) {
      clearInterval(this.interval);
      this.interval = null;
    }
  }
}
```

5. **DOM References:**
```javascript
// BAD: Keeps DOM references
class Component {
  constructor() {
    this.elements = document.querySelectorAll('.item');
    this.cache = new Map();
  }
  
  processItems() {
    this.elements.forEach(element => {
      // Process elements
      this.cache.set(element.id, element.offsetHeight);
    });
  }
}

// GOOD: Clear references
class Component {
  constructor() {
    this.elements = document.querySelectorAll('.item');
    this.cache = new Map();
  }
  
  processItems() {
    this.elements.forEach(element => {
      this.cache.set(element.id, element.offsetHeight);
    });
  }
  
  destroy() {
    this.elements = null;
    this.cache.clear();
  }
}
```

6. **Circular References:**
```javascript
// BAD: Circular reference
function createCircularRef() {
  const objA = { name: 'A' };
  const objB = { name: 'B' };
  
  objA.ref = objB;
  objB.ref = objA; // Circular reference
  
  return objA;
}

// GOOD: Use WeakMap or WeakSet for weak references
function createWeakRef() {
  const objA = { name: 'A' };
  const objB = { name: 'B' };
  
  const weakMap = new WeakMap();
  weakMap.set(objA, objB);
  weakMap.set(objB, objA);
  
  return { objA, objB, weakMap };
}
```

**Memory Leak Detection:**

```javascript
// Monitor memory usage
function logMemoryUsage() {
  if (performance.memory) {
    const memory = performance.memory;
    console.log({
      used: Math.round(memory.usedJSHeapSize / 1048576) + ' MB',
      total: Math.round(memory.totalJSHeapSize / 1048576) + ' MB',
      limit: Math.round(memory.jsHeapSizeLimit / 1048576) + ' MB'
    });
  }
}

// Use Chrome DevTools
// 1. Open DevTools → Memory tab
// 2. Take heap snapshots
// 3. Compare snapshots to find memory leaks
// 4. Use Performance tab to monitor memory over time
```

**Best Practices:**
- Use `let`/`const` instead of `var`
- Remove event listeners when components are destroyed
- Clear timers and intervals
- Use WeakMap/WeakSet for weak references
- Avoid storing large objects in closures
- Use object pooling for frequently created/destroyed objects
- Monitor memory usage in development

---

## 2. ES6+ Features and Modern JavaScript

### 2.1. Explain arrow functions and their differences from regular functions. When should you use each?

Arrow functions are a concise syntax for writing function expressions in ES6. Here are the key differences:

**Syntax Differences:**
```javascript
// Regular function
function add(a, b) {
  return a + b;
}

// Arrow function
const add = (a, b) => a + b;

// Multiple parameters
const multiply = (a, b) => {
  return a * b;
};

// Single parameter (parentheses optional)
const square = x => x * x;

// No parameters
const getTime = () => new Date();
```

**Key Differences:**

1. **`this` Binding:**
```javascript
const obj = {
  name: 'John',
  regularFunction: function() {
    console.log(this.name); // 'John' - this refers to obj
  },
  arrowFunction: () => {
    console.log(this.name); // undefined - this refers to global/window
  }
};

obj.regularFunction(); // 'John'
obj.arrowFunction(); // undefined
```

2. **Arguments Object:**
```javascript
function regularFunction() {
  console.log(arguments); // Has arguments object
}

const arrowFunction = () => {
  console.log(arguments); // ReferenceError: arguments is not defined
};
```

3. **Constructor Usage:**
```javascript
function RegularConstructor() {
  this.name = 'test';
}

const ArrowConstructor = () => {
  this.name = 'test';
};

new RegularConstructor(); // Works
new ArrowConstructor(); // TypeError: ArrowConstructor is not a constructor
```

4. **Hoisting:**
```javascript
// Regular functions are hoisted
console.log(regularFunc()); // Works - 'Hello'

function regularFunc() {
  return 'Hello';
}

// Arrow functions are not hoisted
console.log(arrowFunc()); // ReferenceError: Cannot access 'arrowFunc' before initialization

const arrowFunc = () => 'Hello';
```

**When to Use Each:**

**Use Arrow Functions When:**
- Writing short, simple functions
- Working with array methods (map, filter, reduce)
- Need lexical `this` binding
- Writing functional programming style code

```javascript
// Great for array methods
const numbers = [1, 2, 3, 4, 5];
const doubled = numbers.map(n => n * 2);
const evens = numbers.filter(n => n % 2 === 0);
const sum = numbers.reduce((acc, n) => acc + n, 0);
```

**Use Regular Functions When:**
- Need `this` to be dynamically bound
- Need access to `arguments` object
- Creating constructors
- Need function hoisting
- Writing methods in objects/classes

```javascript
// Object methods should use regular functions
const calculator = {
  value: 0,
  add: function(num) {
    this.value += num;
    return this;
  },
  multiply: function(num) {
    this.value *= num;
    return this;
  }
};
```

### 2.2. Explain destructuring assignment. Provide examples of object and array destructuring with practical use cases.

Destructuring assignment allows you to extract values from arrays or properties from objects into distinct variables.

**Array Destructuring:**
```javascript
// Basic array destructuring
const colors = ['red', 'green', 'blue'];
const [first, second, third] = colors;
console.log(first); // 'red'
console.log(second); // 'green'
console.log(third); // 'blue'

// Skip elements
const [primary, , tertiary] = colors;
console.log(primary); // 'red'
console.log(tertiary); // 'blue'

// Default values
const [a, b, c, d = 'yellow'] = colors;
console.log(d); // 'yellow'

// Rest operator
const [head, ...tail] = colors;
console.log(head); // 'red'
console.log(tail); // ['green', 'blue']

// Swap variables
let x = 1, y = 2;
[x, y] = [y, x];
console.log(x, y); // 2, 1
```

**Object Destructuring:**
```javascript
const user = {
  id: 1,
  name: 'John Doe',
  email: 'john@example.com',
  address: {
    city: 'New York',
    country: 'USA'
  }
};

// Basic object destructuring
const { name, email, id } = user;
console.log(name); // 'John Doe'

// Rename variables
const { name: userName, email: userEmail } = user;
console.log(userName); // 'John Doe'

// Default values
const { name, age = 25 } = user;
console.log(age); // 25

// Nested destructuring
const { address: { city, country } } = user;
console.log(city); // 'New York'

// Rest operator
const { id, ...userInfo } = user;
console.log(userInfo); // { name: 'John Doe', email: 'john@example.com', address: {...} }
```

**Practical Use Cases:**

1. **Function Parameters:**
```javascript
// Instead of passing many parameters
function createUser(name, email, age, city, country) {
  // ...
}

// Use object destructuring
function createUser({ name, email, age = 18, address: { city, country } }) {
  return { name, email, age, city, country };
}

createUser({
  name: 'John',
  email: 'john@example.com',
  address: { city: 'NYC', country: 'USA' }
});
```

2. **API Response Handling:**
```javascript
async function fetchUser(id) {
  const response = await fetch(`/api/users/${id}`);
  const { data: user, status, message } = await response.json();
  
  if (status === 'success') {
    const { name, email, profile: { avatar, bio } } = user;
    return { name, email, avatar, bio };
  }
  throw new Error(message);
}
```

3. **React Props:**
```javascript
function UserCard({ user: { name, email, avatar }, onEdit, onDelete }) {
  return (
    <div>
      <img src={avatar} alt={name} />
      <h3>{name}</h3>
      <p>{email}</p>
      <button onClick={onEdit}>Edit</button>
      <button onClick={onDelete}>Delete</button>
    </div>
  );
}
```

4. **Array Methods:**
```javascript
const users = [
  { id: 1, name: 'John', role: 'admin' },
  { id: 2, name: 'Jane', role: 'user' }
];

// Destructure in map
const userNames = users.map(({ name }) => name);

// Destructure in filter
const admins = users.filter(({ role }) => role === 'admin');
```

### 2.3. Explain the spread and rest operators. When would you use each?

The spread (`...`) and rest (`...`) operators use the same syntax but serve different purposes depending on context.

**Spread Operator (`...`):**
Expands an iterable (array, string, object) into individual elements.

**Array Spread:**
```javascript
const arr1 = [1, 2, 3];
const arr2 = [4, 5, 6];

// Combine arrays
const combined = [...arr1, ...arr2]; // [1, 2, 3, 4, 5, 6]

// Add elements
const withExtra = [...arr1, 4, 5]; // [1, 2, 3, 4, 5]

// Clone array
const cloned = [...arr1]; // [1, 2, 3] - shallow copy

// Convert string to array
const chars = [...'hello']; // ['h', 'e', 'l', 'l', 'o']

// Function arguments
function sum(a, b, c) {
  return a + b + c;
}
const numbers = [1, 2, 3];
console.log(sum(...numbers)); // 6
```

**Object Spread:**
```javascript
const obj1 = { a: 1, b: 2 };
const obj2 = { c: 3, d: 4 };

// Combine objects
const combined = { ...obj1, ...obj2 }; // { a: 1, b: 2, c: 3, d: 4 }

// Override properties
const updated = { ...obj1, b: 10 }; // { a: 1, b: 10 }

// Clone object
const cloned = { ...obj1 }; // { a: 1, b: 2 } - shallow copy

// Add properties
const withExtra = { ...obj1, e: 5 }; // { a: 1, b: 2, e: 5 }
```

**Rest Operator (`...`):**
Collects multiple elements into a single variable.

**Function Parameters:**
```javascript
// Collect remaining arguments
function sum(...numbers) {
  return numbers.reduce((total, num) => total + num, 0);
}

console.log(sum(1, 2, 3, 4)); // 10

// Mix with regular parameters
function greet(greeting, ...names) {
  return `${greeting} ${names.join(', ')}!`;
}

console.log(greet('Hello', 'John', 'Jane', 'Bob')); // "Hello John, Jane, Bob!"
```

**Array Destructuring:**
```javascript
const [first, second, ...rest] = [1, 2, 3, 4, 5];
console.log(first); // 1
console.log(second); // 2
console.log(rest); // [3, 4, 5]

// Skip elements
const [a, , ...remaining] = [1, 2, 3, 4, 5];
console.log(a); // 1
console.log(remaining); // [3, 4, 5]
```

**Object Destructuring:**
```javascript
const { name, ...otherProps } = { name: 'John', age: 30, city: 'NYC' };
console.log(name); // 'John'
console.log(otherProps); // { age: 30, city: 'NYC' }
```

**Practical Use Cases:**

1. **Array Manipulation:**
```javascript
// Remove duplicates
const unique = [...new Set([1, 2, 2, 3, 3, 4])]; // [1, 2, 3, 4]

// Insert at specific position
function insertAt(array, index, ...items) {
  return [...array.slice(0, index), ...items, ...array.slice(index)];
}

const result = insertAt([1, 2, 5], 2, 3, 4); // [1, 2, 3, 4, 5]
```

2. **Object Updates:**
```javascript
// Immutable updates
const updateUser = (user, updates) => ({ ...user, ...updates });

const user = { name: 'John', age: 30 };
const updated = updateUser(user, { age: 31, city: 'NYC' });
// { name: 'John', age: 31, city: 'NYC' }
```

3. **React State Updates:**
```javascript
// Add item to array
const addItem = (items, newItem) => [...items, newItem];

// Remove item from array
const removeItem = (items, id) => items.filter(item => item.id !== id);

// Update object in array
const updateItem = (items, id, updates) => 
  items.map(item => item.id === id ? { ...item, ...updates } : item);
```

4. **API Calls:**
```javascript
// Merge query parameters
const buildUrl = (baseUrl, ...params) => {
  const queryString = params.join('&');
  return `${baseUrl}?${queryString}`;
};

const url = buildUrl('/api/users', 'page=1', 'limit=10', 'sort=name');
```

### 2.4. Explain template literals and tagged template literals. Provide practical examples.

Template literals are string literals that allow embedded expressions and multi-line strings.

**Basic Template Literals:**
```javascript
const name = 'John';
const age = 30;

// String interpolation
const message = `Hello, my name is ${name} and I am ${age} years old.`;

// Multi-line strings
const html = `
  <div class="user-card">
    <h2>${name}</h2>
    <p>Age: ${age}</p>
  </div>
`;

// Expressions
const price = 19.99;
const total = `Total: $${(price * 1.08).toFixed(2)}`;
```

**Tagged Template Literals:**
```javascript
function myTag(strings, ...values) {
  return strings.reduce((result, string, i) => {
    return result + string + (values[i] || '');
  }, '');
}

const name = 'John';
const result = myTag`Hello ${name}, you are ${30} years old.`;

// Practical example: SQL query builder
function sql(strings, ...values) {
  return strings.reduce((query, string, i) => {
    const value = values[i];
    const escaped = typeof value === 'string' ? `'${value.replace(/'/g, "''")}'` : value;
    return query + string + (escaped || '');
  }, '');
}

const userId = 123;
const query = sql`SELECT * FROM users WHERE id = ${userId}`;
```

### 2.5. Explain ES6 modules (import/export). Compare with CommonJS and discuss module bundling.

ES6 modules provide a standardized way to organize and share code between files.

**Export Syntax:**
```javascript
// Named exports
export const PI = 3.14159;
export function add(a, b) { return a + b; }
export class Calculator { multiply(a, b) { return a * b; } }

// Default export
export default function subtract(a, b) { return a - b; }

// Mixed exports
export const VERSION = '1.0.0';
export default class MathUtils { static divide(a, b) { return a / b; } }
```

**Import Syntax:**
```javascript
// Named imports
import { PI, add, Calculator } from './math.js';

// Default import
import subtract from './math.js';

// Mixed imports
import MathUtils, { VERSION } from './math.js';

// Namespace import
import * as math from './math.js';

// Dynamic import
const { add, subtract } = await import('./math.js');
```

**CommonJS vs ES6 Modules:**
```javascript
// CommonJS
const fs = require('fs');
module.exports = { readFile: fs.readFile };

// ES6 Modules
import fs from 'fs';
export { readFile: fs.readFile };
```

**Module Bundling:**
```javascript
// Code splitting
const Home = lazy(() => import('./components/Home'));
const About = lazy(() => import('./components/About'));

// Tree shaking (only used exports are bundled)
import { debounce } from 'lodash-es'; // Only debounce is bundled
import _ from 'lodash'; // Entire library bundled
```

### 2.6. Explain async/await syntax and how it relates to Promises. What are the benefits and potential pitfalls?

Async/await is syntactic sugar built on top of Promises, making asynchronous code look and behave more like synchronous code.

**Basic Syntax:**
```javascript
// Promise-based
function fetchUser(id) {
  return fetch(`/api/users/${id}`)
    .then(response => response.json())
    .then(user => {
      console.log(user);
      return user;
    })
    .catch(error => {
      console.error('Error:', error);
      throw error;
    });
}

// Async/await equivalent
async function fetchUser(id) {
  try {
    const response = await fetch(`/api/users/${id}`);
    const user = await response.json();
    console.log(user);
    return user;
  } catch (error) {
    console.error('Error:', error);
    throw error;
  }
}
```

**Key Benefits:**
- **Readability:** Easier to read than promise chains
- **Error Handling:** Better error handling with try/catch
- **Debugging:** Easier to debug with stack traces

**Common Pitfalls:**
```javascript
// ❌ Sequential (slow)
async function fetchSequential() {
  const user = await fetchUser(1);     // Wait 100ms
  const posts = await fetchPosts(1);   // Wait 200ms
  const comments = await fetchComments(1); // Wait 150ms
  // Total: 450ms
}

// ✅ Parallel (fast)
async function fetchParallel() {
  const [user, posts, comments] = await Promise.all([
    fetchUser(1),      // All start simultaneously
    fetchPosts(1),     // All start simultaneously
    fetchComments(1)   // All start simultaneously
  ]);
  // Total: 200ms (longest operation)
}

// ❌ Missing await
async function badExample() {
  const user = fetchUser(1); // Returns Promise, not user data
  console.log(user.name); // Error: Cannot read property 'name' of undefined
}

// ✅ Correct
async function goodExample() {
  const user = await fetchUser(1); // Waits for Promise to resolve
  console.log(user.name); // Works correctly
}
```

**Error Handling:**
```javascript
async function fetchWithRetry(url, maxRetries = 3) {
  for (let i = 0; i < maxRetries; i++) {
    try {
      const response = await fetch(url);
      if (!response.ok) throw new Error(`HTTP ${response.status}`);
      return await response.json();
    } catch (error) {
      if (i === maxRetries - 1) throw error;
      await new Promise(resolve => setTimeout(resolve, 1000 * (i + 1)));
    }
  }
}
```

### 2.7. Explain the Fetch API and how it differs from XMLHttpRequest. Provide examples of common use cases.

The Fetch API is a modern, promise-based interface for making HTTP requests that replaces the older XMLHttpRequest.

**Basic Fetch Usage:**
```javascript
// Simple GET request
async function fetchUser(id) {
  try {
    const response = await fetch(`/api/users/${id}`);
    if (!response.ok) {
      throw new Error(`HTTP error! status: ${response.status}`);
    }
    const user = await response.json();
    return user;
  } catch (error) {
    console.error('Fetch failed:', error);
    throw error;
  }
}

// POST request with JSON
async function createUser(userData) {
  const response = await fetch('/api/users', {
    method: 'POST',
    headers: {
      'Content-Type': 'application/json',
      'Authorization': `Bearer ${token}`
    },
    body: JSON.stringify(userData)
  });
  return await response.json();
}
```

**Fetch vs XMLHttpRequest:**
```javascript
// XMLHttpRequest (old way)
function fetchUserXHR(id) {
  return new Promise((resolve, reject) => {
    const xhr = new XMLHttpRequest();
    xhr.open('GET', `/api/users/${id}`);
    xhr.onload = function() {
      if (xhr.status >= 200 && xhr.status < 300) {
        resolve(JSON.parse(xhr.responseText));
      } else {
        reject(new Error(`HTTP ${xhr.status}: ${xhr.statusText}`));
      }
    };
    xhr.onerror = function() {
      reject(new Error('Network error'));
    };
    xhr.send();
  });
}

// Fetch API (modern way)
async function fetchUserFetch(id) {
  const response = await fetch(`/api/users/${id}`);
  if (!response.ok) {
    throw new Error(`HTTP ${response.status}: ${response.statusText}`);
  }
  return await response.json();
}
```

**Advanced Features:**
```javascript
// AbortController for cancellation
async function fetchWithAbort(url, timeout = 5000) {
  const controller = new AbortController();
  const timeoutId = setTimeout(() => controller.abort(), timeout);
  
  try {
    const response = await fetch(url, { signal: controller.signal });
    clearTimeout(timeoutId);
    return await response.json();
  } catch (error) {
    clearTimeout(timeoutId);
    if (error.name === 'AbortError') {
      throw new Error('Request was aborted');
    }
    throw error;
  }
}
```

### 2.8. Explain localStorage, sessionStorage, and IndexedDB. When would you use each?

These are different browser storage mechanisms with varying capabilities and use cases.

**localStorage:**
```javascript
// Persistent storage that survives browser restarts
localStorage.setItem('username', 'john_doe');
localStorage.setItem('userPreferences', JSON.stringify({ theme: 'dark', lang: 'en' }));

const username = localStorage.getItem('username');
const preferences = JSON.parse(localStorage.getItem('userPreferences') || '{}');

localStorage.removeItem('username');
localStorage.clear(); // Remove all items

// Storage event (fires on other tabs)
window.addEventListener('storage', (e) => {
  if (e.key === 'username') {
    console.log('Username changed in another tab:', e.newValue);
  }
});
```

**sessionStorage:**
```javascript
// Temporary storage that lasts only for the browser session
sessionStorage.setItem('currentPage', 'dashboard');
sessionStorage.setItem('formData', JSON.stringify({ name: 'John', email: 'john@example.com' }));

const currentPage = sessionStorage.getItem('currentPage');
// Automatically cleared when tab closes
```

**IndexedDB:**
```javascript
// Low-level API for client-side storage of significant amounts of structured data
function openDB() {
  return new Promise((resolve, reject) => {
    const request = indexedDB.open('MyDatabase', 1);
    request.onerror = () => reject(request.error);
    request.onsuccess = () => resolve(request.result);
    request.onupgradeneeded = (event) => {
      const db = event.target.result;
      if (!db.objectStoreNames.contains('users')) {
        const store = db.createObjectStore('users', { keyPath: 'id' });
        store.createIndex('email', 'email', { unique: true });
      }
    };
  });
}

async function addUser(user) {
  const db = await openDB();
  const transaction = db.transaction(['users'], 'readwrite');
  const store = transaction.objectStore('users');
  return new Promise((resolve, reject) => {
    const request = store.add(user);
    request.onsuccess = () => resolve(request.result);
    request.onerror = () => reject(request.error);
  });
}
```

**Comparison:**
| Feature | localStorage | sessionStorage | IndexedDB |
|---------|--------------|----------------|-----------|
| Storage Limit | ~5-10MB | ~5-10MB | ~50MB+ |
| Persistence | Survives restart | Tab session only | Survives restart |
| Data Type | Strings only | Strings only | Any structured data |
| Synchronous | Yes | Yes | No (async) |

### 2.9. Explain DOM manipulation and event handling. What are event delegation, bubbling, and capturing?

DOM manipulation involves interacting with HTML elements, and event handling manages user interactions.

**Basic DOM Manipulation:**
```javascript
// Selecting elements
const element = document.getElementById('myId');
const elements = document.querySelectorAll('.myClass');
const firstElement = document.querySelector('.myClass');

// Creating elements
const newDiv = document.createElement('div');
newDiv.textContent = 'Hello World';
newDiv.className = 'my-class';
newDiv.setAttribute('data-id', '123');

// Appending elements
document.body.appendChild(newDiv);
element.insertBefore(newDiv, element.firstChild);

// Modifying content
element.innerHTML = '<p>New content</p>';
element.textContent = 'Plain text content';
element.style.color = 'red';
element.classList.add('active');
element.classList.remove('inactive');
element.classList.toggle('visible');
```

**Event Handling:**
```javascript
// Basic event listener
element.addEventListener('click', function(event) {
  console.log('Element clicked:', event.target);
});

// Event delegation
document.addEventListener('click', function(event) {
  if (event.target.matches('.button')) {
    console.log('Button clicked:', event.target);
  }
});

// Event bubbling and capturing
// Bubbling (default): event goes from target to root
// Capturing: event goes from root to target

element.addEventListener('click', handler, true); // Capturing phase
element.addEventListener('click', handler, false); // Bubbling phase (default)
```

**Event Delegation:**
```javascript
// Instead of adding listeners to each button
const buttons = document.querySelectorAll('.button');
buttons.forEach(button => {
  button.addEventListener('click', handleClick);
});

// Use event delegation (more efficient)
document.addEventListener('click', function(event) {
  if (event.target.classList.contains('button')) {
    handleClick(event);
  }
});

// Dynamic content example
document.addEventListener('click', function(event) {
  if (event.target.matches('.delete-btn')) {
    const item = event.target.closest('.item');
    item.remove();
  }
});
```

**Event Bubbling and Capturing:**
```javascript
// HTML: <div id="parent"><button id="child">Click me</button></div>

const parent = document.getElementById('parent');
const child = document.getElementById('child');

// Capturing phase (parent -> child)
parent.addEventListener('click', () => console.log('Parent capturing'), true);
child.addEventListener('click', () => console.log('Child capturing'), true);

// Bubbling phase (child -> parent)
child.addEventListener('click', () => console.log('Child bubbling'), false);
parent.addEventListener('click', () => console.log('Parent bubbling'), false);

// Clicking child outputs:
// Parent capturing
// Child capturing
// Child bubbling
// Parent bubbling

// Stop propagation
child.addEventListener('click', (event) => {
  event.stopPropagation(); // Prevents bubbling
  console.log('Child clicked, propagation stopped');
});
```

### 2.10. Explain Regular Expressions in JavaScript. Provide examples of common patterns and use cases.

Regular expressions are patterns used to match character combinations in strings.

**Basic Syntax:**
```javascript
// Literal notation
const regex = /pattern/flags;

// Constructor notation
const regex = new RegExp('pattern', 'flags');

// Common flags
const regex = /hello/gi; // g = global, i = case-insensitive
```

**Common Patterns:**
```javascript
// Email validation
const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
console.log(emailRegex.test('user@example.com')); // true

// Phone number (US format)
const phoneRegex = /^\(\d{3}\) \d{3}-\d{4}$/;
console.log(phoneRegex.test('(555) 123-4567')); // true

// URL validation
const urlRegex = /^https?:\/\/[\w\-]+(\.[\w\-]+)+([\w\-\.,@?^=%&:\/~\+#]*[\w\-\@?^=%&\/~\+#])?$/;
console.log(urlRegex.test('https://www.example.com')); // true

// Password (8+ chars, 1 uppercase, 1 lowercase, 1 number)
const passwordRegex = /^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)[a-zA-Z\d@$!%*?&]{8,}$/;
console.log(passwordRegex.test('Password123')); // true
```

**String Methods:**
```javascript
const text = 'Hello World! Hello JavaScript!';

// test() - returns boolean
const regex = /hello/i;
console.log(regex.test(text)); // true

// exec() - returns match details or null
const match = regex.exec(text);
console.log(match); // ['Hello', index: 0, input: 'Hello World! Hello JavaScript!']

// match() - returns array of matches
const matches = text.match(/hello/gi);
console.log(matches); // ['Hello', 'Hello']

// replace() - replaces matches
const newText = text.replace(/hello/gi, 'Hi');
console.log(newText); // 'Hi World! Hi JavaScript!'

// search() - returns index of first match
const index = text.search(/world/i);
console.log(index); // 6

// split() - splits string by pattern
const words = text.split(/\s+/);
console.log(words); // ['Hello', 'World!', 'Hello', 'JavaScript!']
```

**Common Use Cases:**
```javascript
// Extract data from strings
const text = 'Contact: John Doe (555) 123-4567, jane@example.com';
const phoneRegex = /\(\d{3}\) \d{3}-\d{4}/g;
const emailRegex = /[^\s@]+@[^\s@]+\.[^\s@]+/g;

const phones = text.match(phoneRegex); // ['(555) 123-4567']
const emails = text.match(emailRegex); // ['jane@example.com']

// Format strings
function formatPhoneNumber(phone) {
  const cleaned = phone.replace(/\D/g, ''); // Remove non-digits
  const match = cleaned.match(/^(\d{3})(\d{3})(\d{4})$/);
  if (match) {
    return `(${match[1]}) ${match[2]}-${match[3]}`;
  }
  return phone;
}

console.log(formatPhoneNumber('5551234567')); // '(555) 123-4567'

// Validate and sanitize input
function sanitizeInput(input) {
  return input
    .replace(/<script\b[^<]*(?:(?!<\/script>)<[^<]*)*<\/script>/gi, '') // Remove script tags
    .replace(/[<>]/g, ''); // Remove angle brackets
}

// Extract URLs from text
function extractUrls(text) {
  const urlRegex = /https?:\/\/[^\s]+/g;
  return text.match(urlRegex) || [];
}
```

### 2.11. Explain error handling in JavaScript. Compare different error handling strategies and when to use each.

Error handling in JavaScript involves catching and managing errors to prevent application crashes.

**Basic Error Handling:**
```javascript
// try-catch blocks
try {
  const result = riskyOperation();
  console.log('Success:', result);
} catch (error) {
  console.error('Error occurred:', error.message);
} finally {
  console.log('This always runs');
}

// Throwing custom errors
function validateAge(age) {
  if (age < 0) {
    throw new Error('Age cannot be negative');
  }
  if (age > 150) {
    throw new Error('Age cannot exceed 150');
  }
  return true;
}
```

**Error Types:**
```javascript
// Built-in error types
throw new Error('Generic error');
throw new TypeError('Type error');
throw new ReferenceError('Reference error');
throw new SyntaxError('Syntax error');
throw new RangeError('Range error');

// Custom error classes
class ValidationError extends Error {
  constructor(message, field) {
    super(message);
    this.name = 'ValidationError';
    this.field = field;
  }
}

class APIError extends Error {
  constructor(message, status, url) {
    super(message);
    this.name = 'APIError';
    this.status = status;
    this.url = url;
  }
}
```

**Error Handling Strategies:**
```javascript
// 1. Defensive programming
function safeDivide(a, b) {
  if (typeof a !== 'number' || typeof b !== 'number') {
    throw new TypeError('Arguments must be numbers');
  }
  if (b === 0) {
    throw new Error('Division by zero');
  }
  return a / b;
}

// 2. Error boundaries (React pattern)
class ErrorBoundary extends React.Component {
  constructor(props) {
    super(props);
    this.state = { hasError: false, error: null };
  }
  
  static getDerivedStateFromError(error) {
    return { hasError: true, error };
  }
  
  componentDidCatch(error, errorInfo) {
    console.error('Error caught:', error, errorInfo);
  }
  
  render() {
    if (this.state.hasError) {
      return <div>Something went wrong.</div>;
    }
    return this.props.children;
  }
}

// 3. Result pattern
class Result {
  constructor(success, data, error) {
    this.success = success;
    this.data = data;
    this.error = error;
  }
  
  static success(data) {
    return new Result(true, data, null);
  }
  
  static failure(error) {
    return new Result(false, null, error);
  }
}

async function safeFetchUser(id) {
  try {
    const user = await fetchUser(id);
    return Result.success(user);
  } catch (error) {
    return Result.failure(error);
  }
}

// 4. Global error handling
window.addEventListener('error', (event) => {
  console.error('Global error:', event.error);
  // Send to error reporting service
});

window.addEventListener('unhandledrejection', (event) => {
  console.error('Unhandled promise rejection:', event.reason);
  // Send to error reporting service
});
```

**Async Error Handling:**
```javascript
// Promise error handling
fetch('/api/data')
  .then(response => response.json())
  .then(data => console.log(data))
  .catch(error => console.error('Fetch error:', error));

// Async/await error handling
async function fetchData() {
  try {
    const response = await fetch('/api/data');
    if (!response.ok) {
      throw new Error(`HTTP ${response.status}: ${response.statusText}`);
    }
    const data = await response.json();
    return data;
  } catch (error) {
    console.error('Fetch error:', error);
    throw error; // Re-throw if needed
  }
}

// Error handling in loops
async function processItems(items) {
  const results = [];
  const errors = [];
  
  for (const item of items) {
    try {
      const result = await processItem(item);
      results.push(result);
    } catch (error) {
      errors.push({ item, error });
      console.error(`Failed to process item ${item.id}:`, error);
    }
  }
  
  return { results, errors };
}
```

### 2.12. Explain preventDefault, stopPropagation, and stopImmediatePropagation in event handlers. When would you use each?

These are methods available on event objects that control how events behave in the DOM.

**preventDefault():**
Prevents the default action that the browser would normally take for this event.

```javascript
// Prevent form submission
function handleSubmit(event) {
  event.preventDefault();
  // Custom form handling logic
  console.log('Form submitted with custom logic');
}

// Prevent link navigation
function handleLinkClick(event) {
  event.preventDefault();
  // Custom navigation logic
  router.push('/custom-route');
}

// Prevent context menu
function handleRightClick(event) {
  event.preventDefault();
  // Show custom context menu
  showCustomMenu(event.clientX, event.clientY);
}

// Prevent text selection
function handleMouseDown(event) {
  event.preventDefault();
  // Custom drag behavior
  startDragging(event);
}
```

**stopPropagation():**
Stops the event from bubbling up to parent elements.

```javascript
// Stop event from reaching parent elements
function handleButtonClick(event) {
  event.stopPropagation();
  console.log('Button clicked, parent won\'t receive this event');
}

// Example with nested elements
function App() {
  const handleParentClick = () => {
    console.log('Parent clicked');
  };
  
  const handleChildClick = (event) => {
    event.stopPropagation();
    console.log('Child clicked, parent won\'t be notified');
  };
  
  return (
    <div onClick={handleParentClick}>
      <button onClick={handleChildClick}>
        Click me
      </button>
    </div>
  );
}
```

**stopImmediatePropagation():**
Stops the event from bubbling up AND prevents other event listeners on the same element from being called.

```javascript
// Multiple listeners on same element
element.addEventListener('click', function(event) {
  console.log('First listener');
  event.stopImmediatePropagation();
  console.log('Second listener will NOT be called');
});

element.addEventListener('click', function(event) {
  console.log('Second listener'); // This won't execute
});

// Practical example - preventing multiple handlers
function handleFormSubmit(event) {
  event.stopImmediatePropagation();
  
  // Prevent other submit handlers from running
  if (isSubmitting) {
    return;
  }
  
  isSubmitting = true;
  submitForm();
}
```

**Comparison Table:**

| Method | Prevents Default Action | Stops Bubbling | Stops Other Listeners |
|--------|------------------------|----------------|----------------------|
| `preventDefault()` | ✅ | ❌ | ❌ |
| `stopPropagation()` | ❌ | ✅ | ❌ |
| `stopImmediatePropagation()` | ❌ | ✅ | ✅ |

**Common Use Cases:**

1. **Form Handling:**
```javascript
function handleFormSubmit(event) {
  event.preventDefault(); // Prevent page reload
  
  const formData = new FormData(event.target);
  const data = Object.fromEntries(formData.entries());
  
  // Custom validation
  if (!validateForm(data)) {
    return;
  }
  
  // Submit via AJAX
  submitForm(data);
}

// Prevent form submission on Enter key in textarea
function handleTextareaKeyDown(event) {
  if (event.key === 'Enter' && !event.shiftKey) {
    event.preventDefault();
    // Custom behavior instead of form submission
    addNewLine();
  }
}
```

2. **Custom Navigation:**
```javascript
function handleNavigation(event) {
  event.preventDefault();
  
  const href = event.target.getAttribute('href');
  
  // Check if user is logged in
  if (!isAuthenticated() && href.startsWith('/protected')) {
    showLoginModal();
    return;
  }
  
  // Custom navigation logic
  navigateTo(href);
}
```

3. **Drag and Drop:**
```javascript
function handleDragStart(event) {
  event.preventDefault(); // Prevent default drag behavior
  
  const draggedElement = event.target;
  draggedElement.classList.add('dragging');
  
  // Set drag data
  event.dataTransfer.setData('text/plain', draggedElement.id);
}

function handleDrop(event) {
  event.preventDefault(); // Prevent default drop behavior
  event.stopPropagation(); // Stop bubbling
  
  const data = event.dataTransfer.getData('text/plain');
  const dropZone = event.target;
  
  // Custom drop logic
  moveElement(data, dropZone);
}
```

4. **Event Delegation with Selective Handling:**
```javascript
// Handle clicks on dynamically added buttons
document.addEventListener('click', function(event) {
  if (event.target.matches('.delete-btn')) {
    event.stopPropagation(); // Don't trigger parent click handlers
    
    const itemId = event.target.dataset.itemId;
    deleteItem(itemId);
  }
  
  if (event.target.matches('.edit-btn')) {
    event.stopImmediatePropagation(); // Don't trigger other click handlers
    
    const itemId = event.target.dataset.itemId;
    editItem(itemId);
  }
});
```

5. **Keyboard Shortcuts:**
```javascript
function handleKeyDown(event) {
  // Prevent default browser shortcuts
  if (event.ctrlKey && event.key === 's') {
    event.preventDefault();
    saveDocument();
  }
  
  if (event.key === 'Escape') {
    event.preventDefault();
    closeModal();
  }
  
  // Prevent arrow keys from scrolling in certain contexts
  if (event.target.matches('.no-scroll')) {
    if (['ArrowUp', 'ArrowDown', 'ArrowLeft', 'ArrowRight'].includes(event.key)) {
      event.preventDefault();
      // Custom navigation logic
    }
  }
}
```

6. **File Upload Customization:**
```javascript
function handleFileDrop(event) {
  event.preventDefault();
  event.stopPropagation();
  
  const files = event.dataTransfer.files;
  
  // Custom file validation
  const validFiles = Array.from(files).filter(file => {
    return file.type.startsWith('image/') && file.size < 5 * 1024 * 1024;
  });
  
  if (validFiles.length !== files.length) {
    showError('Some files are invalid');
    return;
  }
  
  uploadFiles(validFiles);
}

// Prevent default drag behaviors on drop zone
function handleDragOver(event) {
  event.preventDefault();
  event.dataTransfer.dropEffect = 'copy';
}
```

**Best Practices:**

1. **Use preventDefault() for custom behavior:**
```javascript
// ✅ Good - prevent default and implement custom logic
function handleCustomSubmit(event) {
  event.preventDefault();
  // Custom submission logic
}

// ❌ Bad - prevent default without alternative
function handleSubmit(event) {
  event.preventDefault();
  // No alternative behavior provided
}
```

2. **Use stopPropagation() sparingly:**
```javascript
// ✅ Good - prevent parent from handling child events
function handleButtonClick(event) {
  event.stopPropagation();
  // Button-specific logic
}

// ❌ Bad - overuse can break event delegation
function handleAllClicks(event) {
  event.stopPropagation(); // Breaks parent event handlers
}
```

3. **Use stopImmediatePropagation() for priority handling:**
```javascript
// ✅ Good - ensure only one handler runs
function handlePriorityClick(event) {
  event.stopImmediatePropagation();
  // Critical logic that must run first
}
```

**Summary:**
- **preventDefault()**: Prevents browser's default action (form submission, link navigation, etc.)
- **stopPropagation()**: Stops event from bubbling to parent elements
- **stopImmediatePropagation()**: Stops bubbling AND prevents other listeners on same element
- Use them judiciously to implement custom behaviors while maintaining good event handling practices

---

## 3. TypeScript Advanced Topics

### 3.1. Explain the difference between `type` and `interface`. When would you choose one over the other?

**Answer:**
Both `type` and `interface` are used to define object shapes in TypeScript, but they have important differences:

**Key Differences:**

1. **Declaration Merging:**
```typescript
// Interface - supports declaration merging
interface User {
  name: string;
}

interface User {
  age: number;
}

// Result: User has both name and age
const user: User = { name: 'John', age: 30 };

// Type - does NOT support declaration merging
type UserType = {
  name: string;
}

// This would cause an error
type UserType = {
  age: number;
}
```

2. **Extensibility:**
```typescript
// Interface - uses 'extends'
interface Animal {
  name: string;
}

interface Dog extends Animal {
  breed: string;
}

// Type - uses intersection (&)
type AnimalType = {
  name: string;
}

type DogType = AnimalType & {
  breed: string;
}
```

3. **Union Types:**
```typescript
// Type - supports union types
type Status = 'loading' | 'success' | 'error';

// Interface - cannot represent union types directly
interface StatusInterface {
  // Cannot represent 'loading' | 'success' | 'error'
}
```

4. **Computed Properties:**
```typescript
// Type - supports computed/mapped properties
type Keys = 'name' | 'age';
type User = {
  [K in Keys]: string;
}

// Interface - limited support for computed properties
interface UserInterface {
  [key: string]: any; // Only index signatures
}
```

5. **Primitive Types:**
```typescript
// Type - can alias primitive types
type ID = string | number;
type Status = 'active' | 'inactive';

// Interface - cannot alias primitives
interface IDInterface = string; // Error!
```

**When to Use Each:**

**Use `interface` when:**
- Defining object shapes that might be extended
- Working with classes (implements)
- You need declaration merging
- Creating public APIs that others might extend

```typescript
// Good for interfaces
interface ApiResponse {
  data: any;
  status: number;
}

interface UserResponse extends ApiResponse {
  data: User;
}

class UserService implements UserResponse {
  data: User;
  status: number;
}
```

**Use `type` when:**
- Creating union types
- Aliasing primitive types
- Creating complex mapped types
- You need computed properties
- Creating utility types

```typescript
// Good for types
type Theme = 'light' | 'dark';
type EventHandler<T> = (event: T) => void;
type Partial<T> = {
  [P in keyof T]?: T[P];
}

// Complex utility type
type DeepPartial<T> = {
  [P in keyof T]?: T[P] extends object ? DeepPartial<T[P]> : T[P];
}
```

**Performance Considerations:**
- Interfaces are slightly faster to compile
- Types can be more memory intensive for complex unions
- Both are erased at runtime (no performance difference)

**Best Practices:**
1. Use `interface` for object shapes that represent contracts
2. Use `type` for unions, primitives, and complex transformations
3. Be consistent within your codebase
4. Prefer `interface` for public APIs
5. Use `type` for internal utilities and transformations

### 3.2. What are generics and why are they useful? Provide an example of a generic function that demonstrates type safety.

**Answer:**
Generics allow you to create reusable components that work with multiple types while maintaining type safety. They act as placeholders for types that will be specified later.

**Why Generics Are Useful:**
1. **Type Safety**: Catch errors at compile time
2. **Code Reusability**: Write once, use with multiple types
3. **IntelliSense**: Better IDE support and autocomplete
4. **Flexibility**: Work with any type while maintaining constraints

**Basic Generic Function:**
```typescript
// Without generics - loses type information
function identity(arg: any): any {
  return arg;
}

// With generics - preserves type information
function identity<T>(arg: T): T {
  return arg;
}

const stringResult = identity<string>("hello"); // Type: string
const numberResult = identity<number>(42); // Type: number
const inferredResult = identity("world"); // Type: "world" (inferred)
```

**Generic Constraints:**
```typescript
// Constraint: T must have a length property
function logLength<T extends { length: number }>(arg: T): T {
  console.log(arg.length);
  return arg;
}

logLength("hello"); // OK - string has length
logLength([1, 2, 3]); // OK - array has length
logLength(42); // Error - number doesn't have length
```

**Multiple Type Parameters:**
```typescript
function merge<T, U>(obj1: T, obj2: U): T & U {
  return { ...obj1, ...obj2 };
}

const result = merge(
  { name: "John" },
  { age: 30 }
); // Type: { name: string } & { age: number }
```

**Generic Classes:**
```typescript
class Container<T> {
  private items: T[] = [];

  add(item: T): void {
    this.items.push(item);
  }

  get(index: number): T | undefined {
    return this.items[index];
  }

  getAll(): T[] {
    return [...this.items];
  }
}

const stringContainer = new Container<string>();
stringContainer.add("hello");
stringContainer.add("world");

const numberContainer = new Container<number>();
numberContainer.add(1);
numberContainer.add(2);
```

**Advanced Generic Patterns:**
```typescript
// Conditional types
type ApiResponse<T> = T extends string 
  ? { message: T } 
  : { data: T };

// Mapped types with generics
type Optional<T, K extends keyof T> = Omit<T, K> & Partial<Pick<T, K>>;

// Generic utility functions
function createAsyncHandler<T, R>(
  handler: (data: T) => Promise<R>
): (data: T) => Promise<R> {
  return async (data: T) => {
    try {
      return await handler(data);
    } catch (error) {
      console.error('Handler error:', error);
      throw error;
    }
  };
}
```

**Coding Challenge:** Create a type-safe function that deep clones an object while preserving all type information.

**Answer:**
```typescript
// Basic deep clone with type preservation
function deepClone<T>(obj: T): T {
  if (obj === null || typeof obj !== 'object') {
    return obj;
  }

  if (obj instanceof Date) {
    return new Date(obj.getTime()) as T;
  }

  if (obj instanceof Array) {
    return obj.map(item => deepClone(item)) as T;
  }

  if (obj instanceof RegExp) {
    return new RegExp(obj.source, obj.flags) as T;
  }

  if (obj instanceof Map) {
    const clonedMap = new Map();
    for (const [key, value] of obj) {
      clonedMap.set(deepClone(key), deepClone(value));
    }
    return clonedMap as T;
  }

  if (obj instanceof Set) {
    const clonedSet = new Set();
    for (const value of obj) {
      clonedSet.add(deepClone(value));
    }
    return clonedSet as T;
  }

  // Handle plain objects
  const clonedObj = {} as T;
  for (const key in obj) {
    if (obj.hasOwnProperty(key)) {
      clonedObj[key] = deepClone(obj[key]);
    }
  }

  return clonedObj;
}

// Advanced version with better type inference and error handling
type DeepCloneable = 
  | string 
  | number 
  | boolean 
  | null 
  | undefined 
  | Date 
  | RegExp 
  | Map<any, any> 
  | Set<any> 
  | Array<any> 
  | { [key: string]: any };

function advancedDeepClone<T extends DeepCloneable>(obj: T): T {
  // Handle primitives and null/undefined
  if (obj === null || obj === undefined || typeof obj !== 'object') {
    return obj;
  }

  // Handle Date objects
  if (obj instanceof Date) {
    return new Date(obj.getTime()) as T;
  }

  // Handle RegExp objects
  if (obj instanceof RegExp) {
    return new RegExp(obj.source, obj.flags) as T;
  }

  // Handle Map objects
  if (obj instanceof Map) {
    const clonedMap = new Map();
    for (const [key, value] of obj) {
      clonedMap.set(advancedDeepClone(key), advancedDeepClone(value));
    }
    return clonedMap as T;
  }

  // Handle Set objects
  if (obj instanceof Set) {
    const clonedSet = new Set();
    for (const value of obj) {
      clonedSet.add(advancedDeepClone(value));
    }
    return clonedSet as T;
  }

  // Handle Arrays
  if (Array.isArray(obj)) {
    return obj.map(item => advancedDeepClone(item)) as T;
  }

  // Handle plain objects
  const clonedObj = {} as T;
  for (const key in obj) {
    if (Object.prototype.hasOwnProperty.call(obj, key)) {
      clonedObj[key] = advancedDeepClone(obj[key]);
    }
  }

  return clonedObj;
}

// Usage examples
interface User {
  id: number;
  name: string;
  preferences: {
    theme: 'light' | 'dark';
    notifications: boolean;
  };
  tags: string[];
  createdAt: Date;
}

const originalUser: User = {
  id: 1,
  name: 'John Doe',
  preferences: {
    theme: 'dark',
    notifications: true
  },
  tags: ['developer', 'typescript'],
  createdAt: new Date('2023-01-01')
};

const clonedUser = deepClone(originalUser);
// clonedUser has the exact same type as originalUser
// Modifying clonedUser won't affect originalUser

// Test with complex nested structures
const complexObject = {
  users: new Map([
    ['user1', { name: 'Alice', age: 30 }],
    ['user2', { name: 'Bob', age: 25 }]
  ]),
  settings: new Set(['feature1', 'feature2']),
  metadata: {
    version: '1.0.0',
    lastUpdated: new Date(),
    config: {
      apiUrl: 'https://api.example.com',
      timeout: 5000
    }
  }
};

const clonedComplex = advancedDeepClone(complexObject);
// All nested objects, Maps, Sets, and Dates are properly cloned
```

**Key Benefits of This Implementation:**
1. **Type Safety**: Returns the exact same type as input
2. **Deep Cloning**: Handles nested objects, arrays, Maps, Sets
3. **Special Object Support**: Properly clones Dates, RegExp, etc.
4. **Performance**: Efficient handling of different object types
5. **Error Prevention**: Avoids circular reference issues with proper checks

### 3.3. Explain how Partial, Pick, Omit, and Record utility types work. When would you use conditional types?

**Answer:**
TypeScript provides several built-in utility types that help transform existing types. These are essential for creating flexible and reusable type definitions.

**Core Utility Types:**

1. **Partial<T>** - Makes all properties optional:
```typescript
interface User {
  id: number;
  name: string;
  email: string;
  age: number;
}

type PartialUser = Partial<User>;
// Equivalent to:
// {
//   id?: number;
//   name?: string;
//   email?: string;
//   age?: number;
// }

// Usage in update functions
function updateUser(id: number, updates: Partial<User>): void {
  // Only some fields need to be provided
  console.log(`Updating user ${id} with:`, updates);
}

updateUser(1, { name: 'John' }); // OK - only name provided
updateUser(1, { name: 'John', age: 30 }); // OK - multiple fields
```

2. **Pick<T, K>** - Selects specific properties:
```typescript
type UserSummary = Pick<User, 'id' | 'name'>;
// Equivalent to:
// {
//   id: number;
//   name: string;
// }

// Usage for API responses
function getUserSummary(id: number): UserSummary {
  const user = getUserById(id);
  return {
    id: user.id,
    name: user.name
  };
}
```

3. **Omit<T, K>** - Excludes specific properties:
```typescript
type UserWithoutId = Omit<User, 'id'>;
// Equivalent to:
// {
//   name: string;
//   email: string;
//   age: number;
// }

// Usage for creating new users (without ID)
function createUser(userData: Omit<User, 'id'>): User {
  return {
    id: generateId(),
    ...userData
  };
}
```

4. **Record<K, V>** - Creates object type with specific keys and values:
```typescript
type Status = 'loading' | 'success' | 'error';
type StatusMessages = Record<Status, string>;
// Equivalent to:
// {
//   loading: string;
//   success: string;
//   error: string;
// }

const messages: StatusMessages = {
  loading: 'Please wait...',
  success: 'Operation completed!',
  error: 'Something went wrong!'
};

// Dynamic object creation
type UserRoles = Record<string, string[]>;
const userRoles: UserRoles = {
  admin: ['read', 'write', 'delete'],
  user: ['read'],
  guest: []
};
```

**Advanced Utility Types:**

5. **Required<T>** - Makes all properties required:
```typescript
interface Config {
  apiUrl?: string;
  timeout?: number;
  retries?: number;
}

type RequiredConfig = Required<Config>;
// All properties are now required
```

6. **Readonly<T>** - Makes all properties readonly:
```typescript
type ReadonlyUser = Readonly<User>;
// All properties are now readonly
```

7. **Exclude<T, U>** - Excludes types from union:
```typescript
type AllColors = 'red' | 'green' | 'blue' | 'yellow';
type PrimaryColors = Exclude<AllColors, 'yellow'>; // 'red' | 'green' | 'blue'
```

8. **Extract<T, U>** - Extracts types from union:
```typescript
type MixedTypes = string | number | boolean | Date;
type PrimitiveTypes = Extract<MixedTypes, string | number | boolean>;
// 'string' | 'number' | 'boolean'
```

**Custom Utility Types:**
```typescript
// Deep partial - makes nested properties optional too
type DeepPartial<T> = {
  [P in keyof T]?: T[P] extends object ? DeepPartial<T[P]> : T[P];
};

// Non-nullable - removes null and undefined
type NonNullable<T> = T extends null | undefined ? never : T;

// Function properties only
type FunctionPropertyNames<T> = {
  [K in keyof T]: T[K] extends Function ? K : never;
}[keyof T];

// Optional properties only
type OptionalPropertyNames<T> = {
  [K in keyof T]-?: {} extends Pick<T, K> ? K : never;
}[keyof T];
```

**Conditional Types:**
Conditional types allow you to create types that depend on other types. They use the syntax `T extends U ? X : Y`.

**When to Use Conditional Types:**

1. **API Response Handling:**
```typescript
type ApiResponse<T> = T extends string 
  ? { message: T } 
  : { data: T };

type StringResponse = ApiResponse<string>; // { message: string }
type ObjectResponse = ApiResponse<User>; // { data: User }
```

2. **Function Overloading:**
```typescript
type OverloadedFunction<T> = T extends string
  ? (input: T) => string
  : T extends number
  ? (input: T) => number
  : (input: T) => T;

const process: OverloadedFunction<string> = (input) => input.toUpperCase();
const processNumber: OverloadedFunction<number> = (input) => input * 2;
```

3. **Array vs Non-Array Handling:**
```typescript
type Flatten<T> = T extends (infer U)[] ? U : T;

type StringArray = Flatten<string[]>; // string
type StringType = Flatten<string>; // string
```

4. **Infer Keyword - Extract Types:**
```typescript
// Extract return type from function
type ReturnType<T> = T extends (...args: any[]) => infer R ? R : never;

// Extract parameter types
type Parameters<T> = T extends (...args: infer P) => any ? P : never;

// Extract array element type
type ArrayElement<T> = T extends (infer U)[] ? U : never;

// Usage
type MyFunction = (a: string, b: number) => boolean;
type MyReturnType = ReturnType<MyFunction>; // boolean
type MyParameters = Parameters<MyFunction>; // [string, number]
```

5. **Recursive Conditional Types:**
```typescript
// Deep readonly
type DeepReadonly<T> = {
  readonly [P in keyof T]: T[P] extends object ? DeepReadonly<T[P]> : T[P];
};

// Deep required
type DeepRequired<T> = {
  [P in keyof T]-?: T[P] extends object ? DeepRequired<T[P]> : T[P];
};

// JSON serializable types
type JSONValue = 
  | string 
  | number 
  | boolean 
  | null 
  | JSONValue[] 
  | { [key: string]: JSONValue };

type JSONSerializable<T> = T extends JSONValue ? T : never;
```

**Practical Examples:**

```typescript
// Form handling with partial updates
interface UserForm {
  name: string;
  email: string;
  age: number;
  preferences: {
    theme: 'light' | 'dark';
    notifications: boolean;
  };
}

type UserFormUpdate = DeepPartial<UserForm>;

function updateUserForm(updates: UserFormUpdate): void {
  // Can update any nested property
  console.log('Updating form with:', updates);
}

updateUserForm({
  name: 'John',
  preferences: {
    theme: 'dark'
    // notifications can be omitted
  }
});

// Event handler types
type EventMap = {
  click: MouseEvent;
  keydown: KeyboardEvent;
  load: Event;
};

type EventHandler<T extends keyof EventMap> = (event: EventMap[T]) => void;

function addEventListener<T extends keyof EventMap>(
  event: T,
  handler: EventHandler<T>
): void {
  // Type-safe event handling
}

addEventListener('click', (event) => {
  // event is typed as MouseEvent
  console.log(event.clientX, event.clientY);
});

addEventListener('keydown', (event) => {
  // event is typed as KeyboardEvent
  console.log(event.key, event.code);
});
```

**Best Practices:**
1. Use utility types to create variations of existing types
2. Combine utility types for complex transformations
3. Use conditional types for type-dependent logic
4. Leverage `infer` to extract types from complex structures
5. Create custom utility types for domain-specific needs
6. Use conditional types sparingly - they can make code hard to understand

### 3.4. What are type guards? Implement a custom type guard function and explain how TypeScript narrows types.

**Answer:**
Type guards are expressions that perform runtime checks to narrow down the type of a variable within a specific scope. They help TypeScript understand the actual type of a value at runtime, enabling better type safety and IntelliSense.

**How Type Narrowing Works:**
TypeScript uses control flow analysis to narrow types based on certain conditions. When a type guard returns `true`, TypeScript narrows the type in the subsequent code block.

**Built-in Type Guards:**

1. **typeof Guards:**
```typescript
function processValue(value: string | number) {
  if (typeof value === 'string') {
    // TypeScript knows value is string here
    console.log(value.toUpperCase()); // OK
    console.log(value.length); // OK
  } else {
    // TypeScript knows value is number here
    console.log(value.toFixed(2)); // OK
    console.log(value * 2); // OK
  }
}
```

2. **instanceof Guards:**
```typescript
function processError(error: Error | string) {
  if (error instanceof Error) {
    // TypeScript knows error is Error here
    console.log(error.message);
    console.log(error.stack);
  } else {
    // TypeScript knows error is string here
    console.log(error.toUpperCase());
  }
}
```

3. **in Guards:**
```typescript
interface Bird {
  fly(): void;
  layEggs(): void;
}

interface Fish {
  swim(): void;
  layEggs(): void;
}

function move(animal: Bird | Fish) {
  if ('fly' in animal) {
    // TypeScript knows animal is Bird
    animal.fly();
  } else {
    // TypeScript knows animal is Fish
    animal.swim();
  }
}
```

4. **Equality Guards:**
```typescript
function processValue(value: string | null | undefined) {
  if (value === null) {
    // TypeScript knows value is null
    console.log('Value is null');
  } else if (value === undefined) {
    // TypeScript knows value is undefined
    console.log('Value is undefined');
  } else {
    // TypeScript knows value is string
    console.log(value.toUpperCase());
  }
}
```

**Custom Type Guards:**

Type guards are functions that return a type predicate: `value is Type`.

```typescript
// Basic custom type guard
function isString(value: unknown): value is string {
  return typeof value === 'string';
}

function processUnknown(value: unknown) {
  if (isString(value)) {
    // TypeScript knows value is string
    console.log(value.toUpperCase());
  }
}

// More complex type guard
interface User {
  id: number;
  name: string;
  email: string;
}

interface Admin {
  id: number;
  name: string;
  permissions: string[];
}

function isUser(obj: any): obj is User {
  return obj && 
         typeof obj.id === 'number' && 
         typeof obj.name === 'string' && 
         typeof obj.email === 'string' &&
         !('permissions' in obj);
}

function isAdmin(obj: any): obj is Admin {
  return obj && 
         typeof obj.id === 'number' && 
         typeof obj.name === 'string' && 
         Array.isArray(obj.permissions);
}

function processPerson(person: User | Admin) {
  if (isUser(person)) {
    // TypeScript knows person is User
    console.log(`User email: ${person.email}`);
  } else if (isAdmin(person)) {
    // TypeScript knows person is Admin
    console.log(`Admin permissions: ${person.permissions.join(', ')}`);
  }
}
```

**Advanced Type Guard Patterns:**

1. **Discriminated Union Guards:**
```typescript
interface LoadingState {
  status: 'loading';
}

interface SuccessState {
  status: 'success';
  data: any;
}

interface ErrorState {
  status: 'error';
  error: string;
}

type AppState = LoadingState | SuccessState | ErrorState;

function handleState(state: AppState) {
  switch (state.status) {
    case 'loading':
      // TypeScript knows state is LoadingState
      console.log('Loading...');
      break;
    case 'success':
      // TypeScript knows state is SuccessState
      console.log('Data:', state.data);
      break;
    case 'error':
      // TypeScript knows state is ErrorState
      console.log('Error:', state.error);
      break;
  }
}
```

2. **Array Type Guards:**
```typescript
function isStringArray(value: unknown): value is string[] {
  return Array.isArray(value) && value.every(item => typeof item === 'string');
}

function processArray(value: unknown) {
  if (isStringArray(value)) {
    // TypeScript knows value is string[]
    value.forEach(str => console.log(str.toUpperCase()));
  }
}
```

3. **Generic Type Guards:**
```typescript
function isOfType<T>(
  value: unknown,
  type: string
): value is T {
  return typeof value === type;
}

function isNumber(value: unknown): value is number {
  return isOfType<number>(value, 'number');
}

function isBoolean(value: unknown): value is boolean {
  return isOfType<boolean>(value, 'boolean');
}
```

4. **Complex Object Validation:**
```typescript
interface ApiResponse {
  success: boolean;
  data?: any;
  error?: string;
}

function isApiResponse(obj: unknown): obj is ApiResponse {
  return (
    typeof obj === 'object' &&
    obj !== null &&
    'success' in obj &&
    typeof (obj as any).success === 'boolean'
  );
}

function handleApiResponse(response: unknown) {
  if (isApiResponse(response)) {
    if (response.success) {
      // TypeScript knows response.data exists
      console.log('Data:', response.data);
    } else {
      // TypeScript knows response.error exists
      console.log('Error:', response.error);
    }
  }
}
```

5. **Branded Types with Type Guards:**
```typescript
// Branded types for additional type safety
type UserId = number & { readonly __brand: 'UserId' };
type ProductId = number & { readonly __brand: 'ProductId' };

function createUserId(id: number): UserId {
  if (id <= 0) {
    throw new Error('Invalid user ID');
  }
  return id as UserId;
}

function createProductId(id: number): ProductId {
  if (id <= 0) {
    throw new Error('Invalid product ID');
  }
  return id as ProductId;
}

function isUserId(value: unknown): value is UserId {
  return typeof value === 'number' && value > 0;
}

function processId(id: UserId | ProductId) {
  if (isUserId(id)) {
    // TypeScript knows id is UserId
    console.log('Processing user ID:', id);
  } else {
    // TypeScript knows id is ProductId
    console.log('Processing product ID:', id);
  }
}
```

**Type Guard Best Practices:**

1. **Use Type Predicates:**
```typescript
// Good - uses type predicate
function isString(value: unknown): value is string {
  return typeof value === 'string';
}

// Avoid - doesn't narrow types
function isString(value: unknown): boolean {
  return typeof value === 'string';
}
```

2. **Combine Multiple Guards:**
```typescript
function isValidUser(obj: unknown): obj is User {
  return (
    typeof obj === 'object' &&
    obj !== null &&
    'id' in obj &&
    'name' in obj &&
    'email' in obj &&
    typeof (obj as any).id === 'number' &&
    typeof (obj as any).name === 'string' &&
    typeof (obj as any).email === 'string'
  );
}
```

3. **Use Assertion Functions:**
```typescript
function assertIsString(value: unknown): asserts value is string {
  if (typeof value !== 'string') {
    throw new Error('Expected string');
  }
}

function processValue(value: unknown) {
  assertIsString(value);
  // TypeScript knows value is string after assertion
  console.log(value.toUpperCase());
}
```

4. **Create Reusable Guard Libraries:**
```typescript
// Type guard utilities
export const TypeGuards = {
  isString: (value: unknown): value is string => typeof value === 'string',
  isNumber: (value: unknown): value is number => typeof value === 'number',
  isBoolean: (value: unknown): value is boolean => typeof value === 'boolean',
  isObject: (value: unknown): value is object => typeof value === 'object' && value !== null,
  isArray: (value: unknown): value is unknown[] => Array.isArray(value),
  isFunction: (value: unknown): value is Function => typeof value === 'function',
  isNull: (value: unknown): value is null => value === null,
  isUndefined: (value: unknown): value is undefined => value === undefined,
  isNullish: (value: unknown): value is null | undefined => value == null,
};
```

**Common Pitfalls:**

1. **Don't forget the type predicate:**
```typescript
// Wrong - doesn't narrow types
function isString(value: unknown): boolean {
  return typeof value === 'string';
}

// Correct - narrows types
function isString(value: unknown): value is string {
  return typeof value === 'string';
}
```

2. **Be careful with any:**
```typescript
// Avoid using any in type guards
function badGuard(value: any): value is User {
  return value.name && value.email; // Too permissive
}

// Better - be specific
function goodGuard(value: unknown): value is User {
  return (
    typeof value === 'object' &&
    value !== null &&
    'name' in value &&
    'email' in value &&
    typeof (value as any).name === 'string' &&
    typeof (value as any).email === 'string'
  );
}
```

Type guards are essential for working with dynamic data, API responses, and user input where types aren't known at compile time. They provide runtime type safety while maintaining TypeScript's compile-time benefits.

### 3.5. Explain mapped types and template literal types. Provide a practical example where these would be beneficial.

**Answer:**
Mapped types and template literal types are advanced TypeScript features that allow you to create new types by transforming existing ones. They're powerful tools for creating reusable and flexible type definitions.

**Mapped Types:**

Mapped types allow you to create new types by iterating over the keys of an existing type and transforming them.

**Basic Mapped Type Syntax:**
```typescript
type MappedType<T> = {
  [K in keyof T]: T[K];
};
```

**Common Mapped Type Patterns:**

1. **Making All Properties Optional:**
```typescript
type Partial<T> = {
  [P in keyof T]?: T[P];
};

interface User {
  id: number;
  name: string;
  email: string;
}

type PartialUser = Partial<User>;
// { id?: number; name?: string; email?: string; }
```

2. **Making All Properties Required:**
```typescript
type Required<T> = {
  [P in keyof T]-?: T[P];
};

interface Config {
  apiUrl?: string;
  timeout?: number;
}

type RequiredConfig = Required<Config>;
// { apiUrl: string; timeout: number; }
```

3. **Making All Properties Readonly:**
```typescript
type Readonly<T> = {
  readonly [P in keyof T]: T[P];
};

type ReadonlyUser = Readonly<User>;
// { readonly id: number; readonly name: string; readonly email: string; }
```

4. **Transforming Property Types:**
```typescript
type Stringify<T> = {
  [K in keyof T]: string;
};

type StringifiedUser = Stringify<User>;
// { id: string; name: string; email: string; }
```

5. **Conditional Property Transformation:**
```typescript
type NonNullable<T> = {
  [P in keyof T]: T[P] extends null | undefined ? never : T[P];
};

type NonNullableUser = NonNullable<{
  id: number;
  name: string | null;
  email: string | undefined;
}>;
// { id: number; name: never; email: never; }
```

**Advanced Mapped Type Patterns:**

1. **Key Remapping:**
```typescript
type Getters<T> = {
  [K in keyof T as `get${Capitalize<string & K>}`]: () => T[K];
};

type UserGetters = Getters<User>;
// { getId: () => number; getName: () => string; getEmail: () => string; }
```

2. **Filtering Properties:**
```typescript
type FunctionProperties<T> = {
  [K in keyof T as T[K] extends Function ? K : never]: T[K];
};

interface MixedObject {
  name: string;
  age: number;
  greet: () => void;
  calculate: (x: number) => number;
}

type FunctionsOnly = FunctionProperties<MixedObject>;
// { greet: () => void; calculate: (x: number) => number; }
```

3. **Conditional Key Mapping:**
```typescript
type ApiEndpoints<T> = {
  [K in keyof T as T[K] extends { id: any } ? `get${Capitalize<string & K>}` : never]: 
    (id: T[K]['id']) => Promise<T[K]>;
};

interface ApiResources {
  user: { id: number; name: string };
  product: { id: string; title: string };
  category: { name: string }; // No id property
}

type Endpoints = ApiEndpoints<ApiResources>;
// { getUser: (id: number) => Promise<{ id: number; name: string }>; 
//   getProduct: (id: string) => Promise<{ id: string; title: string }>; }
```

**Template Literal Types:**

Template literal types allow you to create string literal types by combining other types.

**Basic Template Literal Syntax:**
```typescript
type TemplateLiteral = `prefix-${string}-suffix`;
```

**Common Template Literal Patterns:**

1. **String Concatenation:**
```typescript
type EventName = 'click' | 'hover' | 'focus';
type EventHandler = `on${Capitalize<EventName>}`;
// 'onClick' | 'onHover' | 'onFocus'

type CSSProperty = 'margin' | 'padding' | 'border';
type CSSDirection = 'top' | 'right' | 'bottom' | 'left';
type CSSPropertyWithDirection = `${CSSProperty}-${CSSDirection}`;
// 'margin-top' | 'margin-right' | 'margin-bottom' | 'margin-left' | 
// 'padding-top' | 'padding-right' | 'padding-bottom' | 'padding-left' | 
// 'border-top' | 'border-right' | 'border-bottom' | 'border-left'
```

2. **API Route Generation:**
```typescript
type HttpMethod = 'GET' | 'POST' | 'PUT' | 'DELETE';
type Resource = 'users' | 'posts' | 'comments';
type ApiRoute = `${HttpMethod} /api/${Resource}`;
// 'GET /api/users' | 'GET /api/posts' | 'GET /api/comments' | 
// 'POST /api/users' | 'POST /api/posts' | 'POST /api/comments' | ...
```

3. **CSS Class Generation:**
```typescript
type Component = 'button' | 'input' | 'card';
type Variant = 'primary' | 'secondary' | 'danger';
type Size = 'sm' | 'md' | 'lg';
type CSSClass = `${Component}-${Variant}-${Size}`;
// 'button-primary-sm' | 'button-primary-md' | 'button-primary-lg' | ...
```

**Advanced Template Literal Patterns:**

1. **String Manipulation Utilities:**
```typescript
type Capitalize<S extends string> = S extends `${infer F}${infer R}` 
  ? `${Uppercase<F>}${R}` 
  : S;

type Uncapitalize<S extends string> = S extends `${infer F}${infer R}` 
  ? `${Lowercase<F>}${R}` 
  : S;

type CamelCase<S extends string> = S extends `${infer P1}-${infer P2}${infer P3}`
  ? `${P1}${Capitalize<`${P2}${P3}`>}`
  : S;

type PascalCase<S extends string> = Capitalize<CamelCase<S>>;

type KebabCase<S extends string> = S extends `${infer C}${infer T}`
  ? T extends Uncapitalize<T>
    ? `${Uncapitalize<C>}${KebabCase<T>}`
    : `${Uncapitalize<C>}-${KebabCase<Uncapitalize<T>>}`
  : S;
```

2. **Path Parameter Extraction:**
```typescript
type ExtractParams<T extends string> = T extends `${string}:${infer P}/${infer R}`
  ? P | ExtractParams<R>
  : T extends `${string}:${infer P}`
  ? P
  : never;

type RouteParams = ExtractParams<'/users/:id/posts/:postId'>;
// 'id' | 'postId'
```

**Practical Example: Form Builder System**

Here's a comprehensive example that combines mapped types and template literal types to create a type-safe form builder:

```typescript
// Base field types
type FieldType = 'text' | 'email' | 'number' | 'select' | 'checkbox' | 'textarea';

// Field configuration
interface BaseField {
  type: FieldType;
  label: string;
  required?: boolean;
  placeholder?: string;
}

interface SelectField extends BaseField {
  type: 'select';
  options: Array<{ value: string; label: string }>;
}

interface CheckboxField extends BaseField {
  type: 'checkbox';
  defaultChecked?: boolean;
}

type Field = BaseField | SelectField | CheckboxField;

// Form schema definition
interface FormSchema {
  [fieldName: string]: Field;
}

// Generate form data type from schema
type FormData<T extends FormSchema> = {
  [K in keyof T]: T[K] extends { type: 'number' }
    ? number
    : T[K] extends { type: 'checkbox' }
    ? boolean
    : string;
};

// Generate validation rules type
type ValidationRules<T extends FormSchema> = {
  [K in keyof T as `${string & K}Validation`]: {
    required?: boolean;
    minLength?: T[K] extends { type: 'text' | 'textarea' } ? number : never;
    maxLength?: T[K] extends { type: 'text' | 'textarea' } ? number : never;
    min?: T[K] extends { type: 'number' } ? number : never;
    max?: T[K] extends { type: 'number' } ? number : never;
    pattern?: T[K] extends { type: 'text' | 'email' } ? RegExp : never;
  };
};

// Generate error messages type
type ErrorMessages<T extends FormSchema> = {
  [K in keyof T as `${string & K}Error`]?: string;
};

// Generate form state type
type FormState<T extends FormSchema> = {
  data: FormData<T>;
  errors: ErrorMessages<T>;
  touched: {
    [K in keyof T]?: boolean;
  };
  isValid: boolean;
  isSubmitting: boolean;
};

// Generate event handler types
type FormEventHandlers<T extends FormSchema> = {
  [K in keyof T as `handle${Capitalize<string & K>}Change`]: (
    value: FormData<T>[K]
  ) => void;
} & {
  handleSubmit: (data: FormData<T>) => void | Promise<void>;
  handleReset: () => void;
  validateField: (fieldName: keyof T) => string | undefined;
};

// Example usage
const userFormSchema: FormSchema = {
  firstName: {
    type: 'text',
    label: 'First Name',
    required: true,
    placeholder: 'Enter your first name'
  },
  lastName: {
    type: 'text',
    label: 'Last Name',
    required: true,
    placeholder: 'Enter your last name'
  },
  email: {
    type: 'email',
    label: 'Email Address',
    required: true,
    placeholder: 'Enter your email'
  },
  age: {
    type: 'number',
    label: 'Age',
    required: false
  },
  country: {
    type: 'select',
    label: 'Country',
    required: true,
    options: [
      { value: 'us', label: 'United States' },
      { value: 'ca', label: 'Canada' },
      { value: 'uk', label: 'United Kingdom' }
    ]
  },
  newsletter: {
    type: 'checkbox',
    label: 'Subscribe to newsletter',
    defaultChecked: false
  }
};

// Generated types
type UserFormData = FormData<typeof userFormSchema>;
// {
//   firstName: string;
//   lastName: string;
//   email: string;
//   age: number;
//   country: string;
//   newsletter: boolean;
// }

type UserFormValidation = ValidationRules<typeof userFormSchema>;
// {
//   firstNameValidation: { required?: boolean; minLength?: number; maxLength?: number; };
//   lastNameValidation: { required?: boolean; minLength?: number; maxLength?: number; };
//   emailValidation: { required?: boolean; pattern?: RegExp; };
//   ageValidation: { required?: boolean; min?: number; max?: number; };
//   countryValidation: { required?: boolean; };
//   newsletterValidation: { required?: boolean; };
// }

type UserFormEventHandlers = FormEventHandlers<typeof userFormSchema>;
// {
//   handleFirstNameChange: (value: string) => void;
//   handleLastNameChange: (value: string) => void;
//   handleEmailChange: (value: string) => void;
//   handleAgeChange: (value: number) => void;
//   handleCountryChange: (value: string) => void;
//   handleNewsletterChange: (value: boolean) => void;
//   handleSubmit: (data: UserFormData) => void | Promise<void>;
//   handleReset: () => void;
//   validateField: (fieldName: keyof typeof userFormSchema) => string | undefined;
// }

// Form builder implementation
class FormBuilder<T extends FormSchema> {
  private schema: T;
  private validationRules: ValidationRules<T>;

  constructor(schema: T, validationRules: ValidationRules<T>) {
    this.schema = schema;
    this.validationRules = validationRules;
  }

  createFormState(): FormState<T> {
    const data = {} as FormData<T>;
    const errors = {} as ErrorMessages<T>;
    const touched = {} as { [K in keyof T]?: boolean };

    // Initialize form data with default values
    for (const [fieldName, field] of Object.entries(this.schema)) {
      if (field.type === 'checkbox') {
        (data as any)[fieldName] = field.defaultChecked || false;
      } else if (field.type === 'number') {
        (data as any)[fieldName] = 0;
      } else {
        (data as any)[fieldName] = '';
      }
    }

    return {
      data,
      errors,
      touched,
      isValid: false,
      isSubmitting: false
    };
  }

  validateField(fieldName: keyof T, value: any): string | undefined {
    const field = this.schema[fieldName];
    const rules = (this.validationRules as any)[`${String(fieldName)}Validation`];

    if (rules?.required && (!value || value === '')) {
      return `${field.label} is required`;
    }

    if (field.type === 'email' && value && !/^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(value)) {
      return 'Please enter a valid email address';
    }

    if (rules?.minLength && value && value.length < rules.minLength) {
      return `${field.label} must be at least ${rules.minLength} characters`;
    }

    if (rules?.maxLength && value && value.length > rules.maxLength) {
      return `${field.label} must be no more than ${rules.maxLength} characters`;
    }

    if (rules?.min && field.type === 'number' && value < rules.min) {
      return `${field.label} must be at least ${rules.min}`;
    }

    if (rules?.max && field.type === 'number' && value > rules.max) {
      return `${field.label} must be no more than ${rules.max}`;
    }

    return undefined;
  }
}

// Usage example
const userFormValidation: UserFormValidation = {
  firstNameValidation: { required: true, minLength: 2, maxLength: 50 },
  lastNameValidation: { required: true, minLength: 2, maxLength: 50 },
  emailValidation: { required: true },
  ageValidation: { min: 0, max: 120 },
  countryValidation: { required: true },
  newsletterValidation: {}
};

const userFormBuilder = new FormBuilder(userFormSchema, userFormValidation);
const formState = userFormBuilder.createFormState();

// Type-safe form handling
const handleFirstNameChange = (value: string) => {
  const error = userFormBuilder.validateField('firstName', value);
  // Update form state...
};

const handleSubmit = (data: UserFormData) => {
  console.log('Submitting form data:', data);
  // Submit to API...
};
```

**Benefits of This Approach:**

1. **Type Safety**: All form data, validation rules, and event handlers are fully typed
2. **IntelliSense**: Full autocomplete support for all generated types
3. **Compile-time Validation**: TypeScript catches errors at compile time
4. **Reusability**: The form builder can work with any schema
5. **Maintainability**: Changes to the schema automatically update all related types
6. **Consistency**: Generated types ensure consistency across the application

This example demonstrates how mapped types and template literal types can be combined to create powerful, type-safe abstractions that would be impossible to achieve with traditional type definitions alone.

### 3.6. How does TypeScript's type inference work? What are the limitations, and when should you explicitly type things?

**Answer:**
TypeScript's type inference is the compiler's ability to automatically determine types without explicit type annotations. It uses contextual information, usage patterns, and type relationships to infer the most appropriate types.

**How Type Inference Works:**

1. **Variable Declaration Inference:**
```typescript
// TypeScript infers the type based on the initial value
let message = "Hello World"; // Type: string
let count = 42; // Type: number
let isActive = true; // Type: boolean
let items = [1, 2, 3]; // Type: number[]
let user = { name: "John", age: 30 }; // Type: { name: string; age: number; }

// Arrays with mixed types
let mixed = [1, "hello", true]; // Type: (string | number | boolean)[]
```

2. **Function Return Type Inference:**
```typescript
// Return type inferred as number
function add(a: number, b: number) {
  return a + b; // TypeScript knows this returns number
}

// Return type inferred as string
function greet(name: string) {
  return `Hello, ${name}!`; // TypeScript knows this returns string
}

// Complex return type inference
function processUser(user: { name: string; age: number }) {
  return {
    displayName: user.name.toUpperCase(),
    isAdult: user.age >= 18,
    nextBirthday: user.age + 1
  };
  // TypeScript infers: { displayName: string; isAdult: boolean; nextBirthday: number; }
}
```

3. **Contextual Type Inference:**
```typescript
// TypeScript infers parameter types from context
const numbers = [1, 2, 3, 4, 5];
const doubled = numbers.map(n => n * 2); // n is inferred as number

// Event handler context
button.addEventListener('click', (event) => {
  // event is inferred as MouseEvent
  console.log(event.clientX, event.clientY);
});

// Array method context
const users = [
  { name: 'Alice', age: 25 },
  { name: 'Bob', age: 30 }
];
const names = users.map(user => user.name); // user is inferred as { name: string; age: number; }
```

4. **Best Common Type Inference:**
```typescript
// TypeScript finds the best common type
let values = [0, 1, null]; // Type: (number | null)[]
let moreValues = [0, 1, null, "hello"]; // Type: (string | number | null)[]

// With explicit typing
let numbers: number[] = [0, 1, null]; // Error: null not assignable to number
```

**Advanced Inference Patterns:**

1. **Generic Type Inference:**
```typescript
// TypeScript infers generic types from usage
function identity<T>(arg: T): T {
  return arg;
}

const stringResult = identity("hello"); // T inferred as string
const numberResult = identity(42); // T inferred as number
const arrayResult = identity([1, 2, 3]); // T inferred as number[]

// Multiple generic parameters
function pair<T, U>(first: T, second: U): [T, U] {
  return [first, second];
}

const result = pair("hello", 42); // T inferred as string, U inferred as number
```

2. **Conditional Type Inference:**
```typescript
// TypeScript infers based on conditional logic
type ApiResponse<T> = T extends string 
  ? { message: T } 
  : { data: T };

function createResponse<T>(value: T): ApiResponse<T> {
  if (typeof value === 'string') {
    return { message: value } as ApiResponse<T>;
  } else {
    return { data: value } as ApiResponse<T>;
  }
}

const stringResponse = createResponse("success"); // Type: { message: string }
const objectResponse = createResponse({ id: 1 }); // Type: { data: { id: number } }
```

3. **Template Literal Inference:**
```typescript
// TypeScript infers template literal types
type EventName = 'click' | 'hover' | 'focus';
type HandlerName<T extends string> = `on${Capitalize<T>}`;

function createHandler<T extends EventName>(event: T): HandlerName<T> {
  return `on${event.charAt(0).toUpperCase() + event.slice(1)}` as HandlerName<T>;
}

const clickHandler = createHandler('click'); // Type: 'onClick'
const hoverHandler = createHandler('hover'); // Type: 'onHover'
```

**Limitations of Type Inference:**

1. **Ambiguous Context:**
```typescript
// TypeScript can't infer the intended type
let ambiguous = []; // Type: never[] - can't infer element type
let alsoAmbiguous = null; // Type: any (in strict mode: null)

// Solution: Provide explicit types
let numbers: number[] = [];
let user: User | null = null;
```

2. **Complex Generic Constraints:**
```typescript
// TypeScript may not infer complex generic relationships
function processData<T extends Record<string, any>>(data: T) {
  return Object.keys(data).map(key => ({
    key,
    value: data[key],
    type: typeof data[key]
  }));
}

// TypeScript infers a complex type that might not be what you want
const result = processData({ name: "John", age: 30 });
// Type: { key: string; value: any; type: string; }[]
```

3. **Circular References:**
```typescript
// TypeScript can't infer circular type relationships
interface Node {
  value: number;
  children: Node[]; // Circular reference
}

// Sometimes needs explicit typing
const createNode = (value: number): Node => ({
  value,
  children: []
});
```

4. **Union Type Widening:**
```typescript
// TypeScript widens literal types to their base types
const config = {
  theme: 'dark', // Type: string (not 'dark')
  port: 3000,    // Type: number (not 3000)
  debug: true    // Type: boolean (not true)
};

// Solution: Use 'as const' assertion
const configConst = {
  theme: 'dark',
  port: 3000,
  debug: true
} as const;
// Type: { readonly theme: 'dark'; readonly port: 3000; readonly debug: true; }
```

**When to Use Explicit Typing:**

1. **Public APIs and Interfaces:**
```typescript
// Always explicitly type public interfaces
interface UserService {
  getUser(id: number): Promise<User>;
  createUser(userData: CreateUserRequest): Promise<User>;
  updateUser(id: number, updates: Partial<User>): Promise<User>;
}

// Explicit return types for public methods
export function calculateTotal(items: Item[]): number {
  return items.reduce((sum, item) => sum + item.price, 0);
}
```

2. **Complex Function Signatures:**
```typescript
// Explicit typing for complex functions
function createAsyncHandler<TInput, TOutput>(
  handler: (input: TInput) => Promise<TOutput>,
  options: {
    retries?: number;
    timeout?: number;
    onError?: (error: Error) => void;
  } = {}
): (input: TInput) => Promise<TOutput> {
  // Implementation...
}
```

3. **Type Assertions and Narrowing:**
```typescript
// When you know more about the type than TypeScript
const element = document.getElementById('myButton') as HTMLButtonElement;
const data = response.data as User[];

// Type guards for runtime type checking
function isUser(obj: unknown): obj is User {
  return typeof obj === 'object' && obj !== null && 'id' in obj;
}
```

4. **Performance-Critical Code:**
```typescript
// Explicit typing can help with performance in some cases
const processLargeDataset = (data: number[]): number[] => {
  // TypeScript doesn't need to infer types during compilation
  return data.map(x => x * 2).filter(x => x > 10);
};
```

5. **Library Development:**
```typescript
// Explicit types for better developer experience
export interface Config {
  apiUrl: string;
  timeout: number;
  retries: number;
}

export function createClient(config: Config): ApiClient {
  // Implementation...
}
```

**Best Practices for Type Inference:**

1. **Let TypeScript Infer When Possible:**
```typescript
// Good - let TypeScript infer
const users = await fetchUsers();
const activeUsers = users.filter(user => user.isActive);

// Avoid unnecessary explicit typing
const users: User[] = await fetchUsers(); // Redundant if fetchUsers() returns User[]
```

2. **Use Type Annotations for Clarity:**
```typescript
// Good - explicit for clarity
const config: Config = {
  apiUrl: process.env.API_URL,
  timeout: 5000,
  retries: 3
};

// Good - explicit for complex types
const eventHandlers: Record<string, (event: Event) => void> = {
  click: handleClick,
  hover: handleHover
};
```

3. **Use 'as const' for Literal Types:**
```typescript
// Good - preserves literal types
const themes = ['light', 'dark', 'auto'] as const;
type Theme = typeof themes[number]; // 'light' | 'dark' | 'auto'

// Good - preserves object structure
const defaultConfig = {
  theme: 'light',
  language: 'en',
  notifications: true
} as const;
```

4. **Use Type Assertions Sparingly:**
```typescript
// Good - when you're certain about the type
const canvas = document.getElementById('canvas') as HTMLCanvasElement;

// Avoid - when you're not certain
const user = response.data as User; // What if response.data is not a User?
```

5. **Leverage Type Inference in Generics:**
```typescript
// Good - let TypeScript infer generic types
function createState<T>(initialValue: T) {
  let value = initialValue;
  return {
    get: () => value,
    set: (newValue: T) => { value = newValue; }
  };
}

const stringState = createState("hello"); // T inferred as string
const numberState = createState(42); // T inferred as number
```

**Common Inference Pitfalls:**

1. **Array Inference Issues:**
```typescript
// Problem: TypeScript infers never[] for empty arrays
let items = []; // Type: never[]
items.push(1); // Error: Argument of type 'number' is not assignable to parameter of type 'never'

// Solution: Provide explicit type
let items: number[] = [];
items.push(1); // OK
```

2. **Function Parameter Inference:**
```typescript
// Problem: TypeScript can't infer parameter types in some contexts
const handlers = {
  click: (event) => { /* event is any */ },
  hover: (event) => { /* event is any */ }
};

// Solution: Provide explicit types
const handlers: Record<string, (event: Event) => void> = {
  click: (event) => { /* event is Event */ },
  hover: (event) => { /* event is Event */ }
};
```

3. **Object Property Inference:**
```typescript
// Problem: TypeScript infers string instead of literal types
const config = {
  environment: 'production', // Type: string
  debug: false // Type: boolean
};

// Solution: Use 'as const' or explicit typing
const config = {
  environment: 'production' as const,
  debug: false
};
```

Type inference is a powerful feature that reduces boilerplate while maintaining type safety. The key is to understand when to let TypeScript infer types and when to provide explicit annotations for better clarity and control.

---

## 4. React Architecture & Patterns

### 4.1. Explain the React component lifecycle in function components. How do useEffect dependencies work, and what are common pitfalls?

**Answer:**
React function components use hooks to manage lifecycle behavior, replacing the traditional class component lifecycle methods. The main lifecycle hook is `useEffect`, which handles side effects and cleanup.

**Function Component Lifecycle Phases:**

1. **Mount Phase:**
```typescript
function MyComponent() {
  // 1. Component function runs (like constructor)
  const [state, setState] = useState(initialValue);
  
  // 2. useEffect with empty dependency array runs (like componentDidMount)
  useEffect(() => {
    console.log('Component mounted');
    // Setup subscriptions, timers, etc.
    
    // 3. Cleanup function (like componentWillUnmount)
    return () => {
      console.log('Component will unmount');
      // Cleanup subscriptions, timers, etc.
    };
  }, []); // Empty dependency array = run once on mount
  
  // 4. Render phase
  return <div>Component content</div>;
}
```

2. **Update Phase:**
```typescript
function MyComponent({ userId }) {
  const [user, setUser] = useState(null);
  
  // Runs on every render (like componentDidUpdate)
  useEffect(() => {
    console.log('Component updated');
    fetchUser(userId).then(setUser);
  }, [userId]); // Runs when userId changes
  
  // Runs on every render (no dependency array)
  useEffect(() => {
    console.log('Runs on every render');
  }); // No dependency array = runs on every render
  
  return <div>{user?.name}</div>;
}
```

3. **Unmount Phase:**
```typescript
function MyComponent() {
  useEffect(() => {
    const timer = setInterval(() => {
      console.log('Timer tick');
    }, 1000);
    
    // Cleanup function runs on unmount
    return () => {
      clearInterval(timer);
      console.log('Timer cleaned up');
    };
  }, []);
  
  return <div>Component with timer</div>;
}
```

**useEffect Dependencies Deep Dive:**

The dependency array controls when the effect runs:

```typescript
function UserProfile({ userId }) {
  const [user, setUser] = useState(null);
  const [posts, setPosts] = useState([]);
  
  // 1. Empty array - runs once on mount
  useEffect(() => {
    console.log('Component mounted');
  }, []);
  
  // 2. Specific dependencies - runs when dependencies change
  useEffect(() => {
    if (userId) {
      fetchUser(userId).then(setUser);
    }
  }, [userId]); // Runs when userId changes
  
  // 3. No dependency array - runs on every render
  useEffect(() => {
    console.log('Runs on every render');
  });
  
  // 4. Multiple dependencies
  useEffect(() => {
    if (user && user.isActive) {
      fetchUserPosts(user.id).then(setPosts);
    }
  }, [user]); // Runs when user object changes
  
  // 5. Function dependencies (be careful!)
  const fetchData = useCallback(() => {
    return fetchUser(userId);
  }, [userId]);
  
  useEffect(() => {
    fetchData().then(setUser);
  }, [fetchData]); // Runs when fetchData function changes
}
```

**Common useEffect Pitfalls:**

1. **Missing Dependencies:**
```typescript
// BAD - Missing userId dependency
function UserProfile({ userId }) {
  const [user, setUser] = useState(null);
  
  useEffect(() => {
    fetchUser(userId).then(setUser); // userId not in dependencies!
  }, []); // Empty array - will only run once
  
  return <div>{user?.name}</div>;
}

// GOOD - Include all dependencies
function UserProfile({ userId }) {
  const [user, setUser] = useState(null);
  
  useEffect(() => {
    fetchUser(userId).then(setUser);
  }, [userId]); // userId included in dependencies
  
  return <div>{user?.name}</div>;
}
```

2. **Infinite Re-render Loops:**
```typescript
// BAD - Creates new object on every render
function MyComponent() {
  const [data, setData] = useState(null);
  
  useEffect(() => {
    setData({ timestamp: Date.now() }); // New object every time!
  }, [data]); // data changes, effect runs, data changes again...
  
  return <div>{data?.timestamp}</div>;
}

// GOOD - Use useCallback or move object creation inside effect
function MyComponent() {
  const [data, setData] = useState(null);
  
  useEffect(() => {
    setData({ timestamp: Date.now() });
  }, []); // Run once on mount
  
  return <div>{data?.timestamp}</div>;
}
```

3. **Stale Closures:**
```typescript
// BAD - Stale closure problem
function Counter() {
  const [count, setCount] = useState(0);
  
  useEffect(() => {
    const timer = setInterval(() => {
      setCount(count + 1); // Always uses initial count value (0)
    }, 1000);
    
    return () => clearInterval(timer);
  }, []); // Empty dependency array
  
  return <div>{count}</div>;
}

// GOOD - Use functional updates
function Counter() {
  const [count, setCount] = useState(0);
  
  useEffect(() => {
    const timer = setInterval(() => {
      setCount(prevCount => prevCount + 1); // Uses latest count value
    }, 1000);
    
    return () => clearInterval(timer);
  }, []);
  
  return <div>{count}</div>;
}
```

4. **Object/Array Dependencies:**
```typescript
// BAD - New object/array on every render
function MyComponent({ filters }) {
  const [data, setData] = useState([]);
  
  useEffect(() => {
    fetchData(filters).then(setData);
  }, [filters]); // filters is a new object every render
  
  return <div>{data.length} items</div>;
}

// GOOD - Use useMemo for stable references
function MyComponent({ filters }) {
  const [data, setData] = useState([]);
  
  const stableFilters = useMemo(() => filters, [
    filters.category,
    filters.status,
    filters.dateRange
  ]);
  
  useEffect(() => {
    fetchData(stableFilters).then(setData);
  }, [stableFilters]);
  
  return <div>{data.length} items</div>;
}
```

**Follow-up:** How would you implement componentDidMount, componentDidUpdate, and componentWillUnmount behavior using hooks?

**Answer:**
Here's how to replicate class component lifecycle methods using hooks:

```typescript
// Class component equivalent
class MyClassComponent extends React.Component {
  componentDidMount() {
    console.log('Component mounted');
    this.setupSubscriptions();
  }
  
  componentDidUpdate(prevProps, prevState) {
    if (prevProps.userId !== this.props.userId) {
      this.fetchUserData();
    }
  }
  
  componentWillUnmount() {
    console.log('Component will unmount');
    this.cleanupSubscriptions();
  }
  
  render() {
    return <div>Class component</div>;
  }
}

// Function component equivalent
function MyFunctionComponent({ userId }) {
  const [userData, setUserData] = useState(null);
  const prevUserIdRef = useRef();
  
  // componentDidMount equivalent
  useEffect(() => {
    console.log('Component mounted');
    setupSubscriptions();
    
    // componentWillUnmount equivalent
    return () => {
      console.log('Component will unmount');
      cleanupSubscriptions();
    };
  }, []); // Empty dependency array = mount/unmount only
  
  // componentDidUpdate equivalent
  useEffect(() => {
    if (prevUserIdRef.current !== userId) {
      fetchUserData(userId).then(setUserData);
      prevUserIdRef.current = userId;
    }
  }, [userId]);
  
  return <div>Function component</div>;
}
```

**Advanced Lifecycle Patterns:**

1. **Custom Hook for Lifecycle:**
```typescript
function useLifecycle({
  onMount,
  onUpdate,
  onUnmount,
  dependencies = []
}) {
  const isFirstRender = useRef(true);
  const prevDeps = useRef(dependencies);
  
  // Mount effect
  useEffect(() => {
    if (onMount) {
      onMount();
    }
    
    return () => {
      if (onUnmount) {
        onUnmount();
      }
    };
  }, []);
  
  // Update effect
  useEffect(() => {
    if (isFirstRender.current) {
      isFirstRender.current = false;
      return;
    }
    
    if (onUpdate) {
      onUpdate(prevDeps.current, dependencies);
    }
    
    prevDeps.current = dependencies;
  }, dependencies);
}

// Usage
function MyComponent({ userId }) {
  useLifecycle({
    onMount: () => console.log('Mounted'),
    onUpdate: (prevDeps, currentDeps) => {
      if (prevDeps[0] !== currentDeps[0]) {
        console.log('userId changed');
      }
    },
    onUnmount: () => console.log('Unmounting'),
    dependencies: [userId]
  });
  
  return <div>Component with custom lifecycle</div>;
}
```

2. **Conditional Effects:**
```typescript
function ConditionalComponent({ shouldFetch, userId }) {
  // Only run effect when shouldFetch is true
  useEffect(() => {
    if (shouldFetch && userId) {
      fetchUserData(userId);
    }
  }, [shouldFetch, userId]);
  
  // Early return pattern
  if (!shouldFetch) {
    return <div>Fetching disabled</div>;
  }
  
  return <div>Fetching enabled</div>;
}
```

3. **Effect Cleanup Patterns:**
```typescript
function DataFetcher({ url }) {
  const [data, setData] = useState(null);
  const [loading, setLoading] = useState(false);
  const abortControllerRef = useRef();
  
  useEffect(() => {
    // Cancel previous request
    if (abortControllerRef.current) {
      abortControllerRef.current.abort();
    }
    
    // Create new abort controller
    abortControllerRef.current = new AbortController();
    
    setLoading(true);
    fetch(url, { signal: abortControllerRef.current.signal })
      .then(response => response.json())
      .then(setData)
      .catch(error => {
        if (error.name !== 'AbortError') {
          console.error('Fetch error:', error);
        }
      })
      .finally(() => setLoading(false));
    
    // Cleanup function
    return () => {
      if (abortControllerRef.current) {
        abortControllerRef.current.abort();
      }
    };
  }, [url]);
  
  return <div>{loading ? 'Loading...' : JSON.stringify(data)}</div>;
}
```

**Best Practices:**

1. **Always include dependencies:**
```typescript
// Use ESLint plugin to catch missing dependencies
// eslint-disable-next-line react-hooks/exhaustive-deps
useEffect(() => {
  // Only if you're absolutely sure about the dependencies
}, []);
```

2. **Use useCallback for stable function references:**
```typescript
function MyComponent({ onDataChange }) {
  const [data, setData] = useState(null);
  
  const handleDataChange = useCallback((newData) => {
    setData(newData);
    onDataChange?.(newData);
  }, [onDataChange]);
  
  useEffect(() => {
    // handleDataChange is stable
    setupDataListener(handleDataChange);
  }, [handleDataChange]);
  
  return <div>{data}</div>;
}
```

3. **Separate concerns with multiple effects:**
```typescript
function ComplexComponent({ userId, settings }) {
  // Separate effects for different concerns
  useEffect(() => {
    // User data fetching
    fetchUser(userId);
  }, [userId]);
  
  useEffect(() => {
    // Settings synchronization
    syncSettings(settings);
  }, [settings]);
  
  useEffect(() => {
    // Analytics tracking
    trackPageView();
  }, []); // Run once on mount
  
  return <div>Complex component</div>;
}
```

Understanding useEffect dependencies and lifecycle patterns is crucial for building reliable React applications. The key is to think about when effects should run and ensure proper cleanup to prevent memory leaks.

### 4.2. Compare different state management solutions (Context API, Redux, Zustand, Jotai). When would you choose each?

**Answer:**
Choosing the right state management solution depends on your application's complexity, team preferences, and specific requirements. Here's a comprehensive comparison:

**1. Context API (Built-in React)**

**Pros:**
- Built into React, no additional dependencies
- Simple for small to medium applications
- Good for theme, authentication, or user preferences
- No learning curve for React developers

**Cons:**
- Can cause performance issues with frequent updates
- No built-in devtools or time-travel debugging
- Can lead to prop drilling if overused
- No middleware or side effect handling

**When to Use:**
- Small to medium applications
- Global state that doesn't change frequently
- Theme, language, or user authentication state
- When you want to avoid external dependencies

```typescript
// Context API Example
interface AppState {
  user: User | null;
  theme: 'light' | 'dark';
  language: string;
}

const AppContext = createContext<{
  state: AppState;
  dispatch: React.Dispatch<AppAction>;
} | null>(null);

function AppProvider({ children }: { children: React.ReactNode }) {
  const [state, dispatch] = useReducer(appReducer, initialState);
  
  return (
    <AppContext.Provider value={{ state, dispatch }}>
      {children}
    </AppContext.Provider>
  );
}

function useAppContext() {
  const context = useContext(AppContext);
  if (!context) {
    throw new Error('useAppContext must be used within AppProvider');
  }
  return context;
}
```

**2. Redux Toolkit (RTK)**

**Pros:**
- Predictable state updates with immutable patterns
- Excellent devtools with time-travel debugging
- Large ecosystem and community
- Great for complex applications
- Middleware support for side effects
- RTK Query for data fetching

**Cons:**
- Steep learning curve
- Lots of boilerplate (though RTK reduces this)
- Can be overkill for simple applications
- Bundle size impact

**When to Use:**
- Large, complex applications
- When you need time-travel debugging
- Applications with complex state logic
- When multiple developers need to work on state management
- When you need middleware for side effects

```typescript
// Redux Toolkit Example
import { createSlice, createAsyncThunk } from '@reduxjs/toolkit';

interface UserState {
  users: User[];
  loading: boolean;
  error: string | null;
}

const initialState: UserState = {
  users: [],
  loading: false,
  error: null,
};

export const fetchUsers = createAsyncThunk(
  'users/fetchUsers',
  async () => {
    const response = await api.getUsers();
    return response.data;
  }
);

const userSlice = createSlice({
  name: 'users',
  initialState,
  reducers: {
    clearError: (state) => {
      state.error = null;
    },
  },
  extraReducers: (builder) => {
    builder
      .addCase(fetchUsers.pending, (state) => {
        state.loading = true;
      })
      .addCase(fetchUsers.fulfilled, (state, action) => {
        state.loading = false;
        state.users = action.payload;
      })
      .addCase(fetchUsers.rejected, (state, action) => {
        state.loading = false;
        state.error = action.error.message || 'Failed to fetch users';
      });
  },
});

export const { clearError } = userSlice.actions;
export default userSlice.reducer;
```

**3. Zustand**

**Pros:**
- Minimal boilerplate
- Small bundle size (~2KB)
- No providers needed
- TypeScript-first
- Simple API
- Good performance
- Can be used outside React

**Cons:**
- Smaller ecosystem compared to Redux
- Less tooling and devtools
- No built-in middleware system
- Can become complex with large applications

**When to Use:**
- Medium-sized applications
- When you want Redux-like patterns with less boilerplate
- TypeScript projects
- When bundle size matters
- Applications that need state outside React

```typescript
// Zustand Example
import { create } from 'zustand';
import { devtools, persist } from 'zustand/middleware';

interface UserStore {
  users: User[];
  loading: boolean;
  error: string | null;
  fetchUsers: () => Promise<void>;
  addUser: (user: User) => void;
  updateUser: (id: string, updates: Partial<User>) => void;
  deleteUser: (id: string) => void;
  clearError: () => void;
}

export const useUserStore = create<UserStore>()(
  devtools(
    persist(
      (set, get) => ({
        users: [],
        loading: false,
        error: null,
        
        fetchUsers: async () => {
          set({ loading: true, error: null });
          try {
            const users = await api.getUsers();
            set({ users, loading: false });
          } catch (error) {
            set({ 
              error: error.message, 
              loading: false 
            });
          }
        },
        
        addUser: (user) => {
          set((state) => ({
            users: [...state.users, user]
          }));
        },
        
        updateUser: (id, updates) => {
          set((state) => ({
            users: state.users.map(user =>
              user.id === id ? { ...user, ...updates } : user
            )
          }));
        },
        
        deleteUser: (id) => {
          set((state) => ({
            users: state.users.filter(user => user.id !== id)
          }));
        },
        
        clearError: () => set({ error: null }),
      }),
      {
        name: 'user-store',
        partialize: (state) => ({ users: state.users }),
      }
    )
  )
);
```

**4. Jotai**

**Pros:**
- Atomic approach - each piece of state is independent
- Excellent TypeScript support
- No providers needed
- Great performance with fine-grained updates
- Composable and flexible
- Small bundle size

**Cons:**
- Different mental model (atomic vs global state)
- Smaller ecosystem
- Can be complex for simple state
- Less familiar to developers

**When to Use:**
- When you want fine-grained reactivity
- Complex state with many interdependencies
- When you need to avoid unnecessary re-renders
- Applications with complex derived state
- When you prefer atomic state management

```typescript
// Jotai Example
import { atom, useAtom, useAtomValue, useSetAtom } from 'jotai';
import { atomWithQuery } from 'jotai/utils';

// Base atoms
const usersAtom = atom<User[]>([]);
const selectedUserIdAtom = atom<string | null>(null);
const searchQueryAtom = atom<string>('');

// Derived atoms
const filteredUsersAtom = atom((get) => {
  const users = get(usersAtom);
  const query = get(searchQueryAtom);
  
  if (!query) return users;
  
  return users.filter(user =>
    user.name.toLowerCase().includes(query.toLowerCase())
  );
});

const selectedUserAtom = atom((get) => {
  const users = get(usersAtom);
  const selectedId = get(selectedUserIdAtom);
  
  return users.find(user => user.id === selectedId) || null;
});

// Async atom
const usersQueryAtom = atomWithQuery(() => ({
  queryKey: ['users'],
  queryFn: () => api.getUsers(),
}));

// Action atoms
const addUserAtom = atom(
  null,
  (get, set, newUser: User) => {
    const currentUsers = get(usersAtom);
    set(usersAtom, [...currentUsers, newUser]);
  }
);

// Component usage
function UserList() {
  const [searchQuery, setSearchQuery] = useAtom(searchQueryAtom);
  const filteredUsers = useAtomValue(filteredUsersAtom);
  const setSelectedUserId = useSetAtom(selectedUserIdAtom);
  
  return (
    <div>
      <input
        value={searchQuery}
        onChange={(e) => setSearchQuery(e.target.value)}
        placeholder="Search users..."
      />
      {filteredUsers.map(user => (
        <div
          key={user.id}
          onClick={() => setSelectedUserId(user.id)}
        >
          {user.name}
        </div>
      ))}
    </div>
  );
}
```

**Comparison Table:**

| Feature | Context API | Redux Toolkit | Zustand | Jotai |
|---------|-------------|---------------|---------|-------|
| Bundle Size | 0KB | ~50KB | ~2KB | ~3KB |
| Learning Curve | Low | High | Medium | Medium |
| Boilerplate | Low | Medium | Low | Low |
| DevTools | Basic | Excellent | Good | Good |
| TypeScript | Good | Excellent | Excellent | Excellent |
| Performance | Poor (frequent updates) | Good | Good | Excellent |
| Ecosystem | Small | Large | Medium | Small |
| Time Travel | No | Yes | No | No |
| Middleware | No | Yes | Limited | No |

**Decision Matrix:**

**Choose Context API when:**
- Building a small to medium app
- State doesn't change frequently
- You want to avoid external dependencies
- Simple global state (theme, auth, etc.)

**Choose Redux Toolkit when:**
- Building a large, complex application
- You need time-travel debugging
- Multiple developers working on state
- Complex state logic with side effects
- You need middleware support

**Choose Zustand when:**
- You want Redux-like patterns with less boilerplate
- Bundle size is important
- You need good TypeScript support
- Medium-sized applications
- You want to use state outside React

**Choose Jotai when:**
- You need fine-grained reactivity
- Complex derived state
- Performance is critical
- You prefer atomic state management
- Complex state interdependencies

**Follow-up:** How would you prevent unnecessary re-renders in a large application?

**Answer:**
Preventing unnecessary re-renders is crucial for performance in large React applications. Here are comprehensive strategies:

**1. React.memo for Component Memoization:**

```typescript
// Memoize expensive components
const ExpensiveComponent = React.memo(({ data, onUpdate }) => {
  const processedData = useMemo(() => {
    return data.map(item => ({
      ...item,
      processed: expensiveCalculation(item)
    }));
  }, [data]);
  
  return (
    <div>
      {processedData.map(item => (
        <ItemComponent key={item.id} item={item} onUpdate={onUpdate} />
      ))}
    </div>
  );
});

// Custom comparison function
const UserCard = React.memo(({ user, onEdit }) => {
  return (
    <div>
      <h3>{user.name}</h3>
      <button onClick={() => onEdit(user.id)}>Edit</button>
    </div>
  );
}, (prevProps, nextProps) => {
  // Only re-render if user data actually changed
  return (
    prevProps.user.id === nextProps.user.id &&
    prevProps.user.name === nextProps.user.name &&
    prevProps.user.email === nextProps.user.email
  );
});
```

**2. useMemo for Expensive Calculations:**

```typescript
function DataVisualization({ data, filters }) {
  // Memoize expensive calculations
  const processedData = useMemo(() => {
    console.log('Processing data...');
    return data
      .filter(item => filters.category === 'all' || item.category === filters.category)
      .map(item => ({
        ...item,
        score: calculateComplexScore(item),
        trend: calculateTrend(item.history)
      }))
      .sort((a, b) => b.score - a.score);
  }, [data, filters.category]);
  
  // Memoize derived values
  const statistics = useMemo(() => ({
    total: processedData.length,
    average: processedData.reduce((sum, item) => sum + item.score, 0) / processedData.length,
    topPerformer: processedData[0]?.name || 'N/A'
  }), [processedData]);
  
  return (
    <div>
      <StatsDisplay stats={statistics} />
      <Chart data={processedData} />
    </div>
  );
}
```

**3. useCallback for Stable Function References:**

```typescript
function UserManagement() {
  const [users, setUsers] = useState<User[]>([]);
  const [selectedUserId, setSelectedUserId] = useState<string | null>(null);
  
  // Memoize event handlers
  const handleUserSelect = useCallback((userId: string) => {
    setSelectedUserId(userId);
  }, []);
  
  const handleUserUpdate = useCallback((userId: string, updates: Partial<User>) => {
    setUsers(prevUsers =>
      prevUsers.map(user =>
        user.id === userId ? { ...user, ...updates } : user
      )
    );
  }, []);
  
  const handleUserDelete = useCallback((userId: string) => {
    setUsers(prevUsers => prevUsers.filter(user => user.id !== userId));
    if (selectedUserId === userId) {
      setSelectedUserId(null);
    }
  }, [selectedUserId]);
  
  // Memoize filtered users
  const activeUsers = useMemo(() => {
    return users.filter(user => user.isActive);
  }, [users]);
  
  return (
    <div>
      <UserList
        users={activeUsers}
        onUserSelect={handleUserSelect}
        onUserUpdate={handleUserUpdate}
        onUserDelete={handleUserDelete}
      />
      {selectedUserId && (
        <UserDetails
          userId={selectedUserId}
          onUpdate={handleUserUpdate}
        />
      )}
    </div>
  );
}
```

**4. State Structure Optimization:**

```typescript
// BAD - Nested state causes unnecessary re-renders
function BadExample() {
  const [state, setState] = useState({
    users: [],
    ui: {
      selectedUserId: null,
      filters: { category: 'all', status: 'active' },
      pagination: { page: 1, limit: 10 }
    }
  });
  
  // Changing any UI property re-renders everything
  const updateFilters = (filters) => {
    setState(prev => ({
      ...prev,
      ui: { ...prev.ui, filters }
    }));
  };
}

// GOOD - Separate concerns
function GoodExample() {
  const [users, setUsers] = useState([]);
  const [selectedUserId, setSelectedUserId] = useState(null);
  const [filters, setFilters] = useState({ category: 'all', status: 'active' });
  const [pagination, setPagination] = useState({ page: 1, limit: 10 });
  
  // Only components using filters will re-render
  const updateFilters = useCallback((newFilters) => {
    setFilters(newFilters);
  }, []);
}
```

**5. Context Optimization:**

```typescript
// BAD - Single context with everything
const AppContext = createContext();

function AppProvider({ children }) {
  const [user, setUser] = useState(null);
  const [theme, setTheme] = useState('light');
  const [notifications, setNotifications] = useState([]);
  const [settings, setSettings] = useState({});
  
  const value = {
    user, setUser,
    theme, setTheme,
    notifications, setNotifications,
    settings, setSettings
  };
  
  return (
    <AppContext.Provider value={value}>
      {children}
    </AppContext.Provider>
  );
}

// GOOD - Split contexts by domain
const UserContext = createContext();
const ThemeContext = createContext();
const NotificationContext = createContext();

function UserProvider({ children }) {
  const [user, setUser] = useState(null);
  const value = useMemo(() => ({ user, setUser }), [user]);
  
  return (
    <UserContext.Provider value={value}>
      {children}
    </UserContext.Provider>
  );
}

// Or use atomic selectors
function useUser() {
  const context = useContext(UserContext);
  if (!context) {
    throw new Error('useUser must be used within UserProvider');
  }
  return context;
}

function useUserSelector(selector) {
  const { user } = useUser();
  return useMemo(() => selector(user), [user, selector]);
}

// Usage - only re-renders when user.name changes
function UserName() {
  const name = useUserSelector(user => user?.name);
  return <span>{name}</span>;
}
```

**6. Virtual Scrolling for Large Lists:**

```typescript
import { FixedSizeList as List } from 'react-window';

function VirtualizedUserList({ users }) {
  const Row = useCallback(({ index, style }) => (
    <div style={style}>
      <UserCard user={users[index]} />
    </div>
  ), [users]);
  
  return (
    <List
      height={600}
      itemCount={users.length}
      itemSize={80}
      width="100%"
    >
      {Row}
    </List>
  );
}
```

**7. Lazy Loading and Code Splitting:**

```typescript
// Lazy load heavy components
const HeavyChart = lazy(() => import('./HeavyChart'));
const DataTable = lazy(() => import('./DataTable'));

function Dashboard() {
  const [activeTab, setActiveTab] = useState('overview');
  
  return (
    <div>
      <TabNavigation activeTab={activeTab} onTabChange={setActiveTab} />
      <Suspense fallback={<LoadingSpinner />}>
        {activeTab === 'charts' && <HeavyChart />}
        {activeTab === 'data' && <DataTable />}
      </Suspense>
    </div>
  );
}
```

**8. Custom Hooks for Performance:**

```typescript
// Custom hook for debounced search
function useDebounce<T>(value: T, delay: number): T {
  const [debouncedValue, setDebouncedValue] = useState<T>(value);
  
  useEffect(() => {
    const handler = setTimeout(() => {
      setDebouncedValue(value);
    }, delay);
    
    return () => {
      clearTimeout(handler);
    };
  }, [value, delay]);
  
  return debouncedValue;
}

// Custom hook for stable references
function useStableCallback<T extends (...args: any[]) => any>(callback: T): T {
  const callbackRef = useRef(callback);
  callbackRef.current = callback;
  
  return useCallback((...args: any[]) => {
    return callbackRef.current(...args);
  }, []) as T;
}

// Usage
function SearchComponent() {
  const [query, setQuery] = useState('');
  const debouncedQuery = useDebounce(query, 300);
  
  const handleSearch = useStableCallback((searchQuery: string) => {
    // This function reference is stable
    performSearch(searchQuery);
  });
  
  useEffect(() => {
    if (debouncedQuery) {
      handleSearch(debouncedQuery);
    }
  }, [debouncedQuery, handleSearch]);
  
  return (
    <input
      value={query}
      onChange={(e) => setQuery(e.target.value)}
      placeholder="Search..."
    />
  );
}
```

**9. Performance Monitoring:**

```typescript
// Custom hook for performance monitoring
function useRenderCount(componentName: string) {
  const renderCount = useRef(0);
  renderCount.current++;
  
  useEffect(() => {
    console.log(`${componentName} rendered ${renderCount.current} times`);
  });
}

// React DevTools Profiler
function ProfiledComponent() {
  useRenderCount('ProfiledComponent');
  
  return <div>Component content</div>;
}

// Wrap with Profiler
<Profiler id="UserList" onRender={onRenderCallback}>
  <UserList users={users} />
</Profiler>
```

**10. State Management Best Practices:**

```typescript
// Use selectors to prevent unnecessary re-renders
function UserList() {
  // Only re-renders when users array changes
  const users = useSelector(state => state.users.items);
  
  // Only re-renders when loading state changes
  const loading = useSelector(state => state.users.loading);
  
  // Memoize expensive selectors
  const activeUsers = useSelector(
    useCallback(state => 
      state.users.items.filter(user => user.isActive), 
      []
    )
  );
  
  return (
    <div>
      {loading ? <LoadingSpinner /> : <UserGrid users={activeUsers} />}
    </div>
  );
}
```

**Key Takeaways:**

1. **Measure First**: Use React DevTools Profiler to identify actual performance bottlenecks
2. **Memoize Strategically**: Don't over-memoize; focus on expensive operations and frequently re-rendering components
3. **Split State**: Keep state as flat as possible and split by domain
4. **Use Stable References**: Prevent unnecessary re-renders with useCallback and useMemo
5. **Lazy Load**: Code split heavy components and load them on demand
6. **Virtual Scrolling**: For large lists, use virtualization libraries
7. **Context Optimization**: Split contexts and use selectors to minimize re-renders
8. **Monitor Performance**: Use profiling tools to measure and optimize

The key is to profile your application first to identify the actual bottlenecks, then apply these techniques strategically rather than preemptively.

### 4.3. Explain React.memo, useMemo, and useCallback. What's the difference, and when should each be used?

**Answer:**
React provides three main optimization hooks/methods to prevent unnecessary re-renders and expensive calculations. Understanding when and how to use each is crucial for building performant React applications.

**React.memo - Component Memoization**

`React.memo` is a higher-order component that memoizes the result of a component. It only re-renders when its props change.

```typescript
// Basic usage
const ExpensiveComponent = React.memo(({ data, onUpdate }) => {
  console.log('ExpensiveComponent rendered');
  
  return (
    <div>
      <h3>Data: {data.title}</h3>
      <button onClick={() => onUpdate(data.id)}>Update</button>
    </div>
  );
});

// Custom comparison function
const UserCard = React.memo(({ user, onEdit }) => {
  return (
    <div className="user-card">
      <img src={user.avatar} alt={user.name} />
      <h3>{user.name}</h3>
      <p>{user.email}</p>
      <button onClick={() => onEdit(user.id)}>Edit</button>
    </div>
  );
}, (prevProps, nextProps) => {
  // Only re-render if specific properties change
  return (
    prevProps.user.id === nextProps.user.id &&
    prevProps.user.name === nextProps.user.name &&
    prevProps.user.email === nextProps.user.email &&
    prevProps.user.avatar === nextProps.user.avatar
  );
});

// Usage
function UserList({ users, onUserEdit }) {
  return (
    <div>
      {users.map(user => (
        <UserCard
          key={user.id}
          user={user}
          onEdit={onUserEdit}
        />
      ))}
    </div>
  );
}
```

**useMemo - Value Memoization**

`useMemo` memoizes the result of a computation and only recalculates when dependencies change.

```typescript
function DataVisualization({ data, filters, sortBy }) {
  // Expensive calculation - only runs when data, filters, or sortBy changes
  const processedData = useMemo(() => {
    console.log('Processing data...');
    
    return data
      .filter(item => {
        if (filters.category !== 'all' && item.category !== filters.category) {
          return false;
        }
        if (filters.status !== 'all' && item.status !== filters.status) {
          return false;
        }
        return true;
      })
      .map(item => ({
        ...item,
        score: calculateComplexScore(item),
        trend: calculateTrend(item.history),
        normalizedValue: normalizeValue(item.value, data)
      }))
      .sort((a, b) => {
        switch (sortBy) {
          case 'score':
            return b.score - a.score;
          case 'name':
            return a.name.localeCompare(b.name);
          case 'date':
            return new Date(b.date) - new Date(a.date);
          default:
            return 0;
        }
      });
  }, [data, filters.category, filters.status, sortBy]);
  
  // Derived calculations - only recalculates when processedData changes
  const statistics = useMemo(() => ({
    total: processedData.length,
    average: processedData.reduce((sum, item) => sum + item.score, 0) / processedData.length,
    topPerformer: processedData[0]?.name || 'N/A',
    categories: [...new Set(processedData.map(item => item.category))],
    scoreDistribution: calculateScoreDistribution(processedData)
  }), [processedData]);
  
  // Expensive object creation - memoized to prevent child re-renders
  const chartConfig = useMemo(() => ({
    data: processedData,
    options: {
      responsive: true,
      plugins: {
        legend: { position: 'top' },
        title: { display: true, text: 'Data Visualization' }
      },
      scales: {
        y: { beginAtZero: true },
        x: { type: 'category' }
      }
    }
  }), [processedData]);
  
  return (
    <div>
      <StatisticsDisplay stats={statistics} />
      <Chart config={chartConfig} />
      <DataTable data={processedData} />
    </div>
  );
}
```

**useCallback - Function Memoization**

`useCallback` memoizes a function and only recreates it when dependencies change.

```typescript
function UserManagement() {
  const [users, setUsers] = useState<User[]>([]);
  const [selectedUserId, setSelectedUserId] = useState<string | null>(null);
  const [searchQuery, setSearchQuery] = useState('');
  
  // Memoize event handlers to prevent child re-renders
  const handleUserSelect = useCallback((userId: string) => {
    setSelectedUserId(userId);
  }, []);
  
  const handleUserUpdate = useCallback((userId: string, updates: Partial<User>) => {
    setUsers(prevUsers =>
      prevUsers.map(user =>
        user.id === userId ? { ...user, ...updates } : user
      )
    );
  }, []);
  
  const handleUserDelete = useCallback((userId: string) => {
    setUsers(prevUsers => prevUsers.filter(user => user.id !== userId));
    if (selectedUserId === userId) {
      setSelectedUserId(null);
    }
  }, [selectedUserId]);
  
  const handleSearch = useCallback((query: string) => {
    setSearchQuery(query);
  }, []);
  
  // Memoize filtered users
  const filteredUsers = useMemo(() => {
    if (!searchQuery) return users;
    
    return users.filter(user =>
      user.name.toLowerCase().includes(searchQuery.toLowerCase()) ||
      user.email.toLowerCase().includes(searchQuery.toLowerCase())
    );
  }, [users, searchQuery]);
  
  // Memoize sorted users
  const sortedUsers = useMemo(() => {
    return [...filteredUsers].sort((a, b) => a.name.localeCompare(b.name));
  }, [filteredUsers]);
  
  return (
    <div>
      <SearchInput onSearch={handleSearch} />
      <UserList
        users={sortedUsers}
        onUserSelect={handleUserSelect}
        onUserUpdate={handleUserUpdate}
        onUserDelete={handleUserDelete}
      />
      {selectedUserId && (
        <UserDetails
          userId={selectedUserId}
          onUpdate={handleUserUpdate}
        />
      )}
    </div>
  );
}
```

**Key Differences and When to Use Each:**

| Hook/Method | Purpose | When to Use | Dependencies |
|-------------|---------|-------------|--------------|
| `React.memo` | Prevents component re-renders | When component receives same props frequently | Props comparison |
| `useMemo` | Memoizes expensive calculations | Expensive computations, object/array creation | Value dependencies |
| `useCallback` | Memoizes function references | Event handlers, functions passed as props | Function dependencies |

**Detailed Comparison:**

1. **React.memo vs useMemo:**
```typescript
// React.memo - prevents component re-renders
const ExpensiveComponent = React.memo(({ data }) => {
  // This component only re-renders when 'data' prop changes
  return <div>{data.title}</div>;
});

// useMemo - prevents expensive calculations
function ParentComponent({ data }) {
  const expensiveValue = useMemo(() => {
    // This calculation only runs when 'data' changes
    return data.reduce((sum, item) => sum + item.value, 0);
  }, [data]);
  
  return <div>{expensiveValue}</div>;
}
```

2. **useCallback vs useMemo:**
```typescript
function Example() {
  const [count, setCount] = useState(0);
  const [name, setName] = useState('');
  
  // useMemo - memoizes a value
  const expensiveValue = useMemo(() => {
    return count * 1000; // Expensive calculation
  }, [count]);
  
  // useCallback - memoizes a function
  const handleClick = useCallback(() => {
    setCount(prev => prev + 1);
  }, []);
  
  return (
    <div>
      <p>Value: {expensiveValue}</p>
      <button onClick={handleClick}>Increment</button>
    </div>
  );
}
```

**Advanced Patterns:**

1. **Combining All Three:**
```typescript
// Memoized component
const UserCard = React.memo(({ user, onEdit, onDelete }) => {
  // Memoized expensive calculation
  const userStats = useMemo(() => {
    return {
      activityScore: calculateActivityScore(user),
      riskLevel: assessRiskLevel(user),
      recommendations: generateRecommendations(user)
    };
  }, [user.id, user.lastActivity, user.transactions]);
  
  // Memoized event handlers
  const handleEdit = useCallback(() => {
    onEdit(user.id);
  }, [user.id, onEdit]);
  
  const handleDelete = useCallback(() => {
    onDelete(user.id);
  }, [user.id, onDelete]);
  
  return (
    <div className="user-card">
      <h3>{user.name}</h3>
      <p>Activity Score: {userStats.activityScore}</p>
      <p>Risk Level: {userStats.riskLevel}</p>
      <button onClick={handleEdit}>Edit</button>
      <button onClick={handleDelete}>Delete</button>
    </div>
  );
});

// Parent component with stable references
function UserList({ users, onUserEdit, onUserDelete }) {
  const handleUserEdit = useCallback((userId: string) => {
    onUserEdit(userId);
  }, [onUserEdit]);
  
  const handleUserDelete = useCallback((userId: string) => {
    onUserDelete(userId);
  }, [onUserDelete]);
  
  return (
    <div>
      {users.map(user => (
        <UserCard
          key={user.id}
          user={user}
          onEdit={handleUserEdit}
          onDelete={handleUserDelete}
        />
      ))}
    </div>
  );
}
```

2. **Custom Comparison Functions:**
```typescript
// Deep comparison for complex objects
const DeepMemoComponent = React.memo(({ config, data }) => {
  return <ComplexVisualization config={config} data={data} />;
}, (prevProps, nextProps) => {
  // Custom deep comparison
  return (
    JSON.stringify(prevProps.config) === JSON.stringify(nextProps.config) &&
    prevProps.data.length === nextProps.data.length &&
    prevProps.data.every((item, index) => 
      JSON.stringify(item) === JSON.stringify(nextProps.data[index])
    )
  );
});

// Shallow comparison for specific properties
const SelectiveMemoComponent = React.memo(({ user, settings, onUpdate }) => {
  return <UserProfile user={user} settings={settings} onUpdate={onUpdate} />;
}, (prevProps, nextProps) => {
  // Only compare specific properties
  return (
    prevProps.user.id === nextProps.user.id &&
    prevProps.user.name === nextProps.user.name &&
    prevProps.settings.theme === nextProps.settings.theme
    // Ignore other properties
  );
});
```

3. **Conditional Memoization:**
```typescript
function ConditionalComponent({ data, shouldOptimize }) {
  // Only memoize when optimization is enabled
  const processedData = shouldOptimize 
    ? useMemo(() => expensiveProcessing(data), [data])
    : expensiveProcessing(data);
  
  return <div>{processedData}</div>;
}

// Or with custom hook
function useConditionalMemo<T>(factory: () => T, deps: any[], condition: boolean): T {
  return condition ? useMemo(factory, deps) : factory();
}
```

**Common Pitfalls and Best Practices:**

1. **Don't Over-Memoize:**
```typescript
// BAD - Unnecessary memoization
function SimpleComponent({ name }) {
  const memoizedName = useMemo(() => name, [name]); // Unnecessary!
  return <div>{memoizedName}</div>;
}

// GOOD - Only memoize when needed
function SimpleComponent({ name }) {
  return <div>{name}</div>; // Simple values don't need memoization
}
```

2. **Include All Dependencies:**
```typescript
// BAD - Missing dependencies
function BadExample({ userId, filters }) {
  const data = useMemo(() => {
    return fetchData(userId, filters); // filters not in deps!
  }, [userId]);
  
  return <div>{data}</div>;
}

// GOOD - Include all dependencies
function GoodExample({ userId, filters }) {
  const data = useMemo(() => {
    return fetchData(userId, filters);
  }, [userId, filters]);
  
  return <div>{data}</div>;
}
```

3. **Use Stable References:**
```typescript
// BAD - New object on every render
function BadParent() {
  const config = { theme: 'dark', size: 'large' }; // New object every time!
  
  return <ChildComponent config={config} />;
}

// GOOD - Memoized object
function GoodParent() {
  const config = useMemo(() => ({
    theme: 'dark',
    size: 'large'
  }), []);
  
  return <ChildComponent config={config} />;
}
```

**Coding Challenge:** Identify and fix performance issues in a provided code sample with excessive re-renders.

**Problem Code:**
```typescript
function UserDashboard({ userId }) {
  const [users, setUsers] = useState([]);
  const [selectedUser, setSelectedUser] = useState(null);
  const [filters, setFilters] = useState({ status: 'all', role: 'all' });
  
  // Problem 1: Expensive calculation runs on every render
  const processedUsers = users.map(user => ({
    ...user,
    score: calculateUserScore(user),
    risk: assessRisk(user),
    recommendations: generateRecommendations(user)
  }));
  
  // Problem 2: New object created on every render
  const chartData = {
    users: processedUsers,
    config: { type: 'bar', colors: ['blue', 'green'] }
  };
  
  // Problem 3: New function created on every render
  const handleUserSelect = (user) => {
    setSelectedUser(user);
  };
  
  // Problem 4: New function created on every render
  const handleFilterChange = (newFilters) => {
    setFilters(newFilters);
  };
  
  // Problem 5: Expensive filtering runs on every render
  const filteredUsers = processedUsers.filter(user => {
    if (filters.status !== 'all' && user.status !== filters.status) return false;
    if (filters.role !== 'all' && user.role !== filters.role) return false;
    return true;
  });
  
  return (
    <div>
      <FilterPanel filters={filters} onFilterChange={handleFilterChange} />
      <UserChart data={chartData} />
      <UserList 
        users={filteredUsers} 
        onUserSelect={handleUserSelect}
      />
      {selectedUser && <UserDetails user={selectedUser} />}
    </div>
  );
}
```

**Optimized Solution:**
```typescript
function UserDashboard({ userId }) {
  const [users, setUsers] = useState([]);
  const [selectedUser, setSelectedUser] = useState(null);
  const [filters, setFilters] = useState({ status: 'all', role: 'all' });
  
  // Fix 1: Memoize expensive calculations
  const processedUsers = useMemo(() => {
    return users.map(user => ({
      ...user,
      score: calculateUserScore(user),
      risk: assessRisk(user),
      recommendations: generateRecommendations(user)
    }));
  }, [users]);
  
  // Fix 2: Memoize filtered users
  const filteredUsers = useMemo(() => {
    return processedUsers.filter(user => {
      if (filters.status !== 'all' && user.status !== filters.status) return false;
      if (filters.role !== 'all' && user.role !== filters.role) return false;
      return true;
    });
  }, [processedUsers, filters.status, filters.role]);
  
  // Fix 3: Memoize chart data object
  const chartData = useMemo(() => ({
    users: filteredUsers,
    config: { type: 'bar', colors: ['blue', 'green'] }
  }), [filteredUsers]);
  
  // Fix 4: Memoize event handlers
  const handleUserSelect = useCallback((user) => {
    setSelectedUser(user);
  }, []);
  
  const handleFilterChange = useCallback((newFilters) => {
    setFilters(newFilters);
  }, []);
  
  return (
    <div>
      <FilterPanel filters={filters} onFilterChange={handleFilterChange} />
      <UserChart data={chartData} />
      <UserList 
        users={filteredUsers} 
        onUserSelect={handleUserSelect}
      />
      {selectedUser && <UserDetails user={selectedUser} />}
    </div>
  );
}

// Fix 5: Memoize child components
const UserList = React.memo(({ users, onUserSelect }) => {
  return (
    <div>
      {users.map(user => (
        <UserCard
          key={user.id}
          user={user}
          onSelect={onUserSelect}
        />
      ))}
    </div>
  );
});

const UserCard = React.memo(({ user, onSelect }) => {
  const handleClick = useCallback(() => {
    onSelect(user);
  }, [user, onSelect]);
  
  return (
    <div onClick={handleClick}>
      <h3>{user.name}</h3>
      <p>Score: {user.score}</p>
      <p>Risk: {user.risk}</p>
    </div>
  );
});
```

**Performance Monitoring:**
```typescript
// Custom hook to measure render performance
function useRenderPerformance(componentName: string) {
  const renderCount = useRef(0);
  const startTime = useRef(performance.now());
  
  renderCount.current++;
  
  useEffect(() => {
    const endTime = performance.now();
    const renderTime = endTime - startTime.current;
    
    console.log(`${componentName} rendered ${renderCount.current} times in ${renderTime.toFixed(2)}ms`);
    
    startTime.current = performance.now();
  });
}

// Usage
function OptimizedComponent() {
  useRenderPerformance('OptimizedComponent');
  
  return <div>Component content</div>;
}
```

**Key Takeaways:**

1. **React.memo**: Use for components that receive the same props frequently
2. **useMemo**: Use for expensive calculations and object/array creation
3. **useCallback**: Use for functions passed as props to prevent child re-renders
4. **Measure First**: Use React DevTools Profiler to identify actual bottlenecks
5. **Don't Over-Optimize**: Only optimize when you have performance issues
6. **Include Dependencies**: Always include all dependencies in dependency arrays
7. **Stable References**: Ensure objects and functions have stable references

The key is to understand that these optimizations come with a cost (memory usage, complexity) and should only be used when they provide actual performance benefits.

### 4.4. What are the rules of hooks? Design a custom hook for handling form state with validation.

**Answer:**
Custom hooks are functions that start with "use" and can call other hooks. They allow you to extract component logic into reusable functions, making your code more modular and testable.

**Rules of Hooks:**

1. **Only Call Hooks at the Top Level:**
   - Never call hooks inside loops, conditions, or nested functions
   - Always call hooks in the same order on every render

2. **Only Call Hooks from React Functions:**
   - Call hooks from React function components
   - Call hooks from other custom hooks

```typescript
// ✅ GOOD - Hooks called at top level
function MyComponent() {
  const [count, setCount] = useState(0);
  const [name, setName] = useState('');
  
  useEffect(() => {
    document.title = `Count: ${count}`;
  }, [count]);
  
  return <div>{count}</div>;
}

// ❌ BAD - Hooks called conditionally
function BadComponent({ shouldUseEffect }) {
  const [count, setCount] = useState(0);
  
  if (shouldUseEffect) {
    useEffect(() => { // This violates the rules!
      document.title = `Count: ${count}`;
    }, [count]);
  }
  
  return <div>{count}</div>;
}

// ❌ BAD - Hooks called in loops
function BadComponent({ items }) {
  const [count, setCount] = useState(0);
  
  items.forEach(item => {
    useEffect(() => { // This violates the rules!
      console.log(item);
    }, [item]);
  });
  
  return <div>{count}</div>;
}
```

**Custom Hook for Form State with Validation:**

Here's a comprehensive form hook that handles state, validation, and submission:

```typescript
// Types for form validation
interface ValidationRule<T> {
  required?: boolean;
  minLength?: number;
  maxLength?: number;
  pattern?: RegExp;
  custom?: (value: T) => string | undefined;
  message?: string;
}

interface FormField<T> {
  value: T;
  error: string | undefined;
  touched: boolean;
  rules: ValidationRule<T>[];
}

interface FormState<T extends Record<string, any>> {
  fields: { [K in keyof T]: FormField<T[K]> };
  isValid: boolean;
  isSubmitting: boolean;
  isDirty: boolean;
}

interface UseFormOptions<T extends Record<string, any>> {
  initialValues: T;
  validationRules?: Partial<{ [K in keyof T]: ValidationRule<T[K]>[] }>;
  onSubmit: (values: T) => Promise<void> | void;
  validateOnChange?: boolean;
  validateOnBlur?: boolean;
}

// Custom form hook
function useForm<T extends Record<string, any>>({
  initialValues,
  validationRules = {},
  onSubmit,
  validateOnChange = true,
  validateOnBlur = true
}: UseFormOptions<T>) {
  // Initialize form state
  const [formState, setFormState] = useState<FormState<T>>(() => {
    const fields = {} as { [K in keyof T]: FormField<T[K]> };
    
    for (const key in initialValues) {
      fields[key] = {
        value: initialValues[key],
        error: undefined,
        touched: false,
        rules: validationRules[key] || []
      };
    }
    
    return {
      fields,
      isValid: true,
      isSubmitting: false,
      isDirty: false
    };
  });

  // Validation function
  const validateField = useCallback(<K extends keyof T>(
    fieldName: K,
    value: T[K],
    rules: ValidationRule<T[K]>[]
  ): string | undefined => {
    for (const rule of rules) {
      // Required validation
      if (rule.required && (value === undefined || value === null || value === '')) {
        return rule.message || `${String(fieldName)} is required`;
      }
      
      // Skip other validations if value is empty and not required
      if (!rule.required && (value === undefined || value === null || value === '')) {
        continue;
      }
      
      // String length validations
      if (typeof value === 'string') {
        if (rule.minLength && value.length < rule.minLength) {
          return rule.message || `${String(fieldName)} must be at least ${rule.minLength} characters`;
        }
        
        if (rule.maxLength && value.length > rule.maxLength) {
          return rule.message || `${String(fieldName)} must be no more than ${rule.maxLength} characters`;
        }
        
        if (rule.pattern && !rule.pattern.test(value)) {
          return rule.message || `${String(fieldName)} format is invalid`;
        }
      }
      
      // Custom validation
      if (rule.custom) {
        const customError = rule.custom(value);
        if (customError) {
          return customError;
        }
      }
    }
    
    return undefined;
  }, []);

  // Update field value
  const setFieldValue = useCallback(<K extends keyof T>(
    fieldName: K,
    value: T[K]
  ) => {
    setFormState(prevState => {
      const field = prevState.fields[fieldName];
      const error = validateOnChange 
        ? validateField(fieldName, value, field.rules)
        : field.error;
      
      const newFields = {
        ...prevState.fields,
        [fieldName]: {
          ...field,
          value,
          error,
          touched: true
        }
      };
      
      // Check if form is valid
      const isValid = Object.values(newFields).every(field => !field.error);
      
      // Check if form is dirty
      const isDirty = Object.keys(newFields).some(key => 
        newFields[key as keyof T].value !== initialValues[key as keyof T]
      );
      
      return {
        ...prevState,
        fields: newFields,
        isValid,
        isDirty
      };
    });
  }, [validateField, validateOnChange, initialValues]);

  // Set field error
  const setFieldError = useCallback(<K extends keyof T>(
    fieldName: K,
    error: string | undefined
  ) => {
    setFormState(prevState => ({
      ...prevState,
      fields: {
        ...prevState.fields,
        [fieldName]: {
          ...prevState.fields[fieldName],
          error
        }
      }
    }));
  }, []);

  // Touch field
  const touchField = useCallback(<K extends keyof T>(fieldName: K) => {
    setFormState(prevState => {
      const field = prevState.fields[fieldName];
      const error = validateOnBlur 
        ? validateField(fieldName, field.value, field.rules)
        : field.error;
      
      return {
        ...prevState,
        fields: {
          ...prevState.fields,
          [fieldName]: {
            ...field,
            touched: true,
            error
          }
        }
      };
    });
  }, [validateField, validateOnBlur]);

  // Validate all fields
  const validateForm = useCallback(() => {
    setFormState(prevState => {
      const newFields = { ...prevState.fields };
      let isValid = true;
      
      for (const key in newFields) {
        const field = newFields[key];
        const error = validateField(key, field.value, field.rules);
        
        newFields[key] = {
          ...field,
          error,
          touched: true
        };
        
        if (error) {
          isValid = false;
        }
      }
      
      return {
        ...prevState,
        fields: newFields,
        isValid
      };
    });
    
    return formState.isValid;
  }, [validateField, formState.isValid]);

  // Reset form
  const resetForm = useCallback(() => {
    setFormState(prevState => {
      const fields = {} as { [K in keyof T]: FormField<T[K]> };
      
      for (const key in initialValues) {
        fields[key] = {
          value: initialValues[key],
          error: undefined,
          touched: false,
          rules: validationRules[key] || []
        };
      }
      
      return {
        fields,
        isValid: true,
        isSubmitting: false,
        isDirty: false
      };
    });
  }, [initialValues, validationRules]);

  // Submit form
  const handleSubmit = useCallback(async (e?: React.FormEvent) => {
    e?.preventDefault();
    
    // Validate all fields
    const isValid = validateForm();
    
    if (!isValid) {
      return;
    }
    
    setFormState(prevState => ({ ...prevState, isSubmitting: true }));
    
    try {
      // Extract values from form state
      const values = {} as T;
      for (const key in formState.fields) {
        values[key] = formState.fields[key].value;
      }
      
      await onSubmit(values);
    } catch (error) {
      console.error('Form submission error:', error);
    } finally {
      setFormState(prevState => ({ ...prevState, isSubmitting: false }));
    }
  }, [validateForm, formState.fields, onSubmit]);

  // Get field props for input elements
  const getFieldProps = useCallback(<K extends keyof T>(fieldName: K) => {
    const field = formState.fields[fieldName];
    
    return {
      value: field.value,
      onChange: (e: React.ChangeEvent<HTMLInputElement | HTMLTextAreaElement | HTMLSelectElement>) => {
        setFieldValue(fieldName, e.target.value as T[K]);
      },
      onBlur: () => touchField(fieldName),
      error: field.error,
      touched: field.touched,
      hasError: field.touched && !!field.error
    };
  }, [formState.fields, setFieldValue, touchField]);

  // Get form values
  const getValues = useCallback(() => {
    const values = {} as T;
    for (const key in formState.fields) {
      values[key] = formState.fields[key].value;
    }
    return values;
  }, [formState.fields]);

  // Set form values
  const setValues = useCallback((values: Partial<T>) => {
    setFormState(prevState => {
      const newFields = { ...prevState.fields };
      
      for (const key in values) {
        if (key in newFields) {
          const field = newFields[key];
          const error = validateOnChange 
            ? validateField(key, values[key]!, field.rules)
            : field.error;
          
          newFields[key] = {
            ...field,
            value: values[key]!,
            error,
            touched: true
          };
        }
      }
      
      // Recalculate form validity
      const isValid = Object.values(newFields).every(field => !field.error);
      const isDirty = Object.keys(newFields).some(key => 
        newFields[key as keyof T].value !== initialValues[key as keyof T]
      );
      
      return {
        ...prevState,
        fields: newFields,
        isValid,
        isDirty
      };
    });
  }, [validateField, validateOnChange, initialValues]);

  return {
    // Form state
    isValid: formState.isValid,
    isSubmitting: formState.isSubmitting,
    isDirty: formState.isDirty,
    
    // Field methods
    getFieldProps,
    setFieldValue,
    setFieldError,
    touchField,
    
    // Form methods
    validateForm,
    resetForm,
    handleSubmit,
    getValues,
    setValues,
    
    // Raw form state (for advanced usage)
    formState
  };
}

// Usage example
interface UserFormData {
  name: string;
  email: string;
  age: number;
  password: string;
  confirmPassword: string;
  terms: boolean;
}

function UserRegistrationForm() {
  const form = useForm<UserFormData>({
    initialValues: {
      name: '',
      email: '',
      age: 0,
      password: '',
      confirmPassword: '',
      terms: false
    },
    validationRules: {
      name: [
        { required: true, message: 'Name is required' },
        { minLength: 2, message: 'Name must be at least 2 characters' },
        { maxLength: 50, message: 'Name must be no more than 50 characters' }
      ],
      email: [
        { required: true, message: 'Email is required' },
        { 
          pattern: /^[^\s@]+@[^\s@]+\.[^\s@]+$/, 
          message: 'Please enter a valid email address' 
        }
      ],
      age: [
        { required: true, message: 'Age is required' },
        { 
          custom: (value) => {
            if (value < 18) return 'You must be at least 18 years old';
            if (value > 120) return 'Please enter a valid age';
            return undefined;
          }
        }
      ],
      password: [
        { required: true, message: 'Password is required' },
        { minLength: 8, message: 'Password must be at least 8 characters' },
        { 
          pattern: /^(?=.*[a-z])(?=.*[A-Z])(?=.*\d)/, 
          message: 'Password must contain at least one lowercase letter, one uppercase letter, and one number' 
        }
      ],
      confirmPassword: [
        { required: true, message: 'Please confirm your password' },
        { 
          custom: (value) => {
            if (value !== form.getValues().password) {
              return 'Passwords do not match';
            }
            return undefined;
          }
        }
      ],
      terms: [
        { 
          custom: (value) => {
            if (!value) return 'You must accept the terms and conditions';
            return undefined;
          }
        }
      ]
    },
    onSubmit: async (values) => {
      console.log('Submitting form:', values);
      // Simulate API call
      await new Promise(resolve => setTimeout(resolve, 1000));
      alert('Registration successful!');
      form.resetForm();
    }
  });

  const nameProps = form.getFieldProps('name');
  const emailProps = form.getFieldProps('email');
  const ageProps = form.getFieldProps('age');
  const passwordProps = form.getFieldProps('password');
  const confirmPasswordProps = form.getFieldProps('confirmPassword');
  const termsProps = form.getFieldProps('terms');

  return (
    <form onSubmit={form.handleSubmit} className="user-form">
      <h2>User Registration</h2>
      
      <div className="form-group">
        <label htmlFor="name">Name</label>
        <input
          id="name"
          type="text"
          {...nameProps}
          className={nameProps.hasError ? 'error' : ''}
        />
        {nameProps.hasError && (
          <span className="error-message">{nameProps.error}</span>
        )}
      </div>
      
      <div className="form-group">
        <label htmlFor="email">Email</label>
        <input
          id="email"
          type="email"
          {...emailProps}
          className={emailProps.hasError ? 'error' : ''}
        />
        {emailProps.hasError && (
          <span className="error-message">{emailProps.error}</span>
        )}
      </div>
      
      <div className="form-group">
        <label htmlFor="age">Age</label>
        <input
          id="age"
          type="number"
          {...ageProps}
          className={ageProps.hasError ? 'error' : ''}
        />
        {ageProps.hasError && (
          <span className="error-message">{ageProps.error}</span>
        )}
      </div>
      
      <div className="form-group">
        <label htmlFor="password">Password</label>
        <input
          id="password"
          type="password"
          {...passwordProps}
          className={passwordProps.hasError ? 'error' : ''}
        />
        {passwordProps.hasError && (
          <span className="error-message">{passwordProps.error}</span>
        )}
      </div>
      
      <div className="form-group">
        <label htmlFor="confirmPassword">Confirm Password</label>
        <input
          id="confirmPassword"
          type="password"
          {...confirmPasswordProps}
          className={confirmPasswordProps.hasError ? 'error' : ''}
        />
        {confirmPasswordProps.hasError && (
          <span className="error-message">{confirmPasswordProps.error}</span>
        )}
      </div>
      
      <div className="form-group">
        <label>
          <input
            type="checkbox"
            checked={termsProps.value}
            onChange={(e) => form.setFieldValue('terms', e.target.checked)}
            onBlur={() => form.touchField('terms')}
          />
          I accept the terms and conditions
        </label>
        {termsProps.hasError && (
          <span className="error-message">{termsProps.error}</span>
        )}
      </div>
      
      <div className="form-actions">
        <button
          type="button"
          onClick={form.resetForm}
          disabled={form.isSubmitting}
        >
          Reset
        </button>
        <button
          type="submit"
          disabled={!form.isValid || form.isSubmitting}
        >
          {form.isSubmitting ? 'Submitting...' : 'Submit'}
        </button>
      </div>
      
      <div className="form-status">
        <p>Form is {form.isValid ? 'valid' : 'invalid'}</p>
        <p>Form is {form.isDirty ? 'dirty' : 'clean'}</p>
      </div>
    </form>
  );
}
```

**Additional Custom Hooks Examples:**

1. **useLocalStorage Hook:**
```typescript
function useLocalStorage<T>(key: string, initialValue: T) {
  const [storedValue, setStoredValue] = useState<T>(() => {
    try {
      const item = window.localStorage.getItem(key);
      return item ? JSON.parse(item) : initialValue;
    } catch (error) {
      console.error(`Error reading localStorage key "${key}":`, error);
      return initialValue;
    }
  });

  const setValue = useCallback((value: T | ((val: T) => T)) => {
    try {
      const valueToStore = value instanceof Function ? value(storedValue) : value;
      setStoredValue(valueToStore);
      window.localStorage.setItem(key, JSON.stringify(valueToStore));
    } catch (error) {
      console.error(`Error setting localStorage key "${key}":`, error);
    }
  }, [key, storedValue]);

  return [storedValue, setValue] as const;
}
```

2. **useDebounce Hook:**
```typescript
function useDebounce<T>(value: T, delay: number): T {
  const [debouncedValue, setDebouncedValue] = useState<T>(value);

  useEffect(() => {
    const handler = setTimeout(() => {
      setDebouncedValue(value);
    }, delay);

    return () => {
      clearTimeout(handler);
    };
  }, [value, delay]);

  return debouncedValue;
}
```

3. **useAsync Hook:**
```typescript
interface AsyncState<T> {
  data: T | null;
  loading: boolean;
  error: Error | null;
}

function useAsync<T>(asyncFunction: () => Promise<T>, dependencies: any[] = []) {
  const [state, setState] = useState<AsyncState<T>>({
    data: null,
    loading: false,
    error: null
  });

  const execute = useCallback(async () => {
    setState(prev => ({ ...prev, loading: true, error: null }));
    
    try {
      const data = await asyncFunction();
      setState({ data, loading: false, error: null });
    } catch (error) {
      setState({ 
        data: null, 
        loading: false, 
        error: error instanceof Error ? error : new Error('Unknown error') 
      });
    }
  }, dependencies);

  useEffect(() => {
    execute();
  }, [execute]);

  return { ...state, refetch: execute };
}
```

**Best Practices for Custom Hooks:**

1. **Always start with "use":**
```typescript
// ✅ Good
function useCounter() { /* ... */ }
function useLocalStorage() { /* ... */ }

// ❌ Bad
function counter() { /* ... */ }
function localStorage() { /* ... */ }
```

2. **Return consistent interfaces:**
```typescript
// ✅ Good - consistent return pattern
function useToggle(initialValue: boolean) {
  const [value, setValue] = useState(initialValue);
  const toggle = useCallback(() => setValue(v => !v), []);
  return [value, toggle] as const;
}
```

3. **Handle cleanup properly:**
```typescript
function useEventListener(
  eventName: string,
  handler: (event: Event) => void,
  element: Element | Window = window
) {
  useEffect(() => {
    element.addEventListener(eventName, handler);
    
    return () => {
      element.removeEventListener(eventName, handler);
    };
  }, [eventName, handler, element]);
}
```

4. **Use TypeScript for better type safety:**
```typescript
interface UseApiOptions<T> {
  url: string;
  initialData?: T;
  dependencies?: any[];
}

function useApi<T>({ url, initialData, dependencies = [] }: UseApiOptions<T>) {
  // Implementation with proper typing
}
```

Custom hooks are powerful tools for code reuse and separation of concerns. They allow you to extract complex logic from components and make it reusable across your application while maintaining the benefits of React's hooks system.

### 4.5. Explain React 18's concurrent features (useTransition, useDeferredValue, Suspense). How do they improve user experience?

**Answer:**
React 18 introduced concurrent features that allow React to interrupt, pause, and resume work, enabling better user experience through non-blocking updates and improved responsiveness. These features work together to make applications feel more responsive and fluid.

**Core Concurrent Features:**

**1. useTransition - Marking Updates as Non-Urgent**

`useTransition` allows you to mark state updates as transitions, which are non-urgent and can be interrupted by more urgent updates.

```typescript
import { useTransition, useState, useMemo } from 'react';

function SearchResults({ query }: { query: string }) {
  const [isPending, startTransition] = useTransition();
  const [results, setResults] = useState<string[]>([]);
  
  // Expensive computation that can be deferred
  const expensiveResults = useMemo(() => {
    if (!query) return [];
    
    // Simulate expensive search operation
    return Array.from({ length: 10000 }, (_, i) => 
      `Result ${i} for "${query}"`
    ).filter(result => 
      result.toLowerCase().includes(query.toLowerCase())
    );
  }, [query]);
  
  const handleSearch = (newQuery: string) => {
    // Mark this update as a transition (non-urgent)
    startTransition(() => {
      setResults(expensiveResults);
    });
  };
  
  return (
    <div>
      <input 
        value={query}
        onChange={(e) => handleSearch(e.target.value)}
        placeholder="Search..."
      />
      
      {isPending && <div>Searching...</div>}
      
      <div>
        {results.map((result, index) => (
          <div key={index}>{result}</div>
        ))}
      </div>
    </div>
  );
}

// More practical example with data fetching
function UserList() {
  const [isPending, startTransition] = useTransition();
  const [users, setUsers] = useState<User[]>([]);
  const [filter, setFilter] = useState('');
  
  const handleFilterChange = (newFilter: string) => {
    // Urgent update - happens immediately
    setFilter(newFilter);
    
    // Non-urgent update - can be interrupted
    startTransition(() => {
      // Expensive filtering operation
      const filteredUsers = users.filter(user =>
        user.name.toLowerCase().includes(newFilter.toLowerCase())
      );
      setUsers(filteredUsers);
    });
  };
  
  return (
    <div>
      <input
        value={filter}
        onChange={(e) => handleFilterChange(e.target.value)}
        placeholder="Filter users..."
      />
      
      {isPending && <div>Filtering...</div>}
      
      <div>
        {users.map(user => (
          <UserCard key={user.id} user={user} />
        ))}
      </div>
    </div>
  );
}
```

**2. useDeferredValue - Deferring Expensive Values**

`useDeferredValue` returns a deferred version of a value that may lag behind the original value during urgent updates.

```typescript
import { useDeferredValue, useMemo, useState } from 'react';

function ExpensiveComponent({ query }: { query: string }) {
  // Defer the query value - it will lag behind during urgent updates
  const deferredQuery = useDeferredValue(query);
  
  // Expensive computation based on deferred value
  const expensiveResults = useMemo(() => {
    if (!deferredQuery) return [];
    
    // Simulate expensive computation
    return Array.from({ length: 1000 }, (_, i) => ({
      id: i,
      name: `Item ${i} for "${deferredQuery}"`,
      score: Math.random() * 100
    })).filter(item => 
      item.name.toLowerCase().includes(deferredQuery.toLowerCase())
    );
  }, [deferredQuery]);
  
  return (
    <div>
      <h3>Results for: {deferredQuery}</h3>
      <div>
        {expensiveResults.map(item => (
          <div key={item.id}>
            {item.name} (Score: {item.score.toFixed(1)})
          </div>
        ))}
      </div>
    </div>
  );
}

function SearchApp() {
  const [query, setQuery] = useState('');
  
  return (
    <div>
      <input
        value={query}
        onChange={(e) => setQuery(e.target.value)}
        placeholder="Search..."
      />
      
      {/* This component will receive deferred updates */}
      <ExpensiveComponent query={query} />
    </div>
  );
}

// Advanced example with multiple deferred values
function DataVisualization({ data, filters }: { data: any[], filters: any }) {
  const deferredData = useDeferredValue(data);
  const deferredFilters = useDeferredValue(filters);
  
  const processedData = useMemo(() => {
    console.log('Processing data...');
    
    return deferredData
      .filter(item => {
        if (deferredFilters.category && item.category !== deferredFilters.category) {
          return false;
        }
        if (deferredFilters.status && item.status !== deferredFilters.status) {
          return false;
        }
        return true;
      })
      .map(item => ({
        ...item,
        processed: expensiveProcessing(item)
      }));
  }, [deferredData, deferredFilters]);
  
  return (
    <div>
      <Chart data={processedData} />
    </div>
  );
}
```

**3. Suspense - Declarative Loading States**

Suspense allows components to "suspend" rendering while waiting for data, providing a declarative way to handle loading states.

```typescript
import { Suspense, lazy, useState } from 'react';

// Lazy load components
const HeavyChart = lazy(() => import('./HeavyChart'));
const DataTable = lazy(() => import('./DataTable'));
const UserProfile = lazy(() => import('./UserProfile'));

// Loading fallback components
function ChartSkeleton() {
  return (
    <div className="skeleton">
      <div className="skeleton-header"></div>
      <div className="skeleton-chart"></div>
    </div>
  );
}

function TableSkeleton() {
  return (
    <div className="skeleton">
      <div className="skeleton-header"></div>
      <div className="skeleton-rows">
        {Array.from({ length: 5 }, (_, i) => (
          <div key={i} className="skeleton-row"></div>
        ))}
      </div>
    </div>
  );
}

function Dashboard() {
  const [activeTab, setActiveTab] = useState('overview');
  
  return (
    <div>
      <TabNavigation activeTab={activeTab} onTabChange={setActiveTab} />
      
      <div className="content">
        {activeTab === 'charts' && (
          <Suspense fallback={<ChartSkeleton />}>
            <HeavyChart />
          </Suspense>
        )}
        
        {activeTab === 'data' && (
          <Suspense fallback={<TableSkeleton />}>
            <DataTable />
          </Suspense>
        )}
        
        {activeTab === 'profile' && (
          <Suspense fallback={<div>Loading profile...</div>}>
            <UserProfile />
          </Suspense>
        )}
      </div>
    </div>
  );
}

// Nested Suspense boundaries
function App() {
  return (
    <div>
      <Header />
      
      <Suspense fallback={<div>Loading main content...</div>}>
        <MainContent />
        
        <Suspense fallback={<div>Loading sidebar...</div>}>
          <Sidebar />
        </Suspense>
      </Suspense>
      
      <Footer />
    </div>
  );
}
```

**4. Combining Concurrent Features**

Here's how to combine all concurrent features for optimal user experience:

```typescript
import { 
  useTransition, 
  useDeferredValue, 
  Suspense, 
  useState, 
  useMemo,
  lazy 
} from 'react';

const SearchResults = lazy(() => import('./SearchResults'));

function AdvancedSearchApp() {
  const [isPending, startTransition] = useTransition();
  const [query, setQuery] = useState('');
  const [results, setResults] = useState<any[]>([]);
  
  // Defer the query for expensive operations
  const deferredQuery = useDeferredValue(query);
  
  // Expensive search operation
  const searchResults = useMemo(() => {
    if (!deferredQuery) return [];
    
    // Simulate expensive search
    return performExpensiveSearch(deferredQuery);
  }, [deferredQuery]);
  
  const handleSearch = (newQuery: string) => {
    // Urgent update - input responds immediately
    setQuery(newQuery);
    
    // Non-urgent update - can be interrupted
    startTransition(() => {
      setResults(searchResults);
    });
  };
  
  return (
    <div>
      <div className="search-header">
        <input
          value={query}
          onChange={(e) => handleSearch(e.target.value)}
          placeholder="Search..."
          className="search-input"
        />
        
        {isPending && (
          <div className="search-indicator">
            <Spinner />
            <span>Searching...</span>
          </div>
        )}
      </div>
      
      <div className="search-content">
        <Suspense fallback={<SearchResultsSkeleton />}>
          <SearchResults 
            query={deferredQuery} 
            results={results}
            isPending={isPending}
          />
        </Suspense>
      </div>
    </div>
  );
}

// Custom hook combining concurrent features
function useConcurrentSearch<T>(
  searchFn: (query: string) => Promise<T[]>,
  delay: number = 300
) {
  const [isPending, startTransition] = useTransition();
  const [query, setQuery] = useState('');
  const [results, setResults] = useState<T[]>([]);
  const [isLoading, setIsLoading] = useState(false);
  
  const deferredQuery = useDeferredValue(query);
  
  const handleSearch = (newQuery: string) => {
    setQuery(newQuery);
    
    startTransition(async () => {
      if (!newQuery.trim()) {
        setResults([]);
        return;
      }
      
      setIsLoading(true);
      try {
        const searchResults = await searchFn(newQuery);
        setResults(searchResults);
      } catch (error) {
        console.error('Search error:', error);
        setResults([]);
      } finally {
        setIsLoading(false);
      }
    });
  };
  
  return {
    query,
    deferredQuery,
    results,
    isPending,
    isLoading,
    handleSearch
  };
}

// Usage
function UserSearch() {
  const {
    query,
    deferredQuery,
    results,
    isPending,
    isLoading,
    handleSearch
  } = useConcurrentSearch(
    async (query) => {
      const response = await fetch(`/api/users?search=${query}`);
      return response.json();
    }
  );
  
  return (
    <div>
      <input
        value={query}
        onChange={(e) => handleSearch(e.target.value)}
        placeholder="Search users..."
      />
      
      {(isPending || isLoading) && <div>Searching...</div>}
      
      <div>
        {results.map(user => (
          <UserCard key={user.id} user={user} />
        ))}
      </div>
    </div>
  );
}
```

**How Concurrent Features Improve User Experience:**

**1. Responsive Input Fields:**
```typescript
function ResponsiveInput() {
  const [isPending, startTransition] = useTransition();
  const [inputValue, setInputValue] = useState('');
  const [searchResults, setSearchResults] = useState([]);
  
  const handleInputChange = (value: string) => {
    // Urgent update - input responds immediately
    setInputValue(value);
    
    // Non-urgent update - search can be interrupted
    startTransition(() => {
      performSearch(value).then(setSearchResults);
    });
  };
  
  return (
    <div>
      <input
        value={inputValue}
        onChange={(e) => handleInputChange(e.target.value)}
        placeholder="Type to search..."
      />
      
      {/* Input remains responsive even during search */}
      {isPending && <div>Searching...</div>}
      
      <SearchResults results={searchResults} />
    </div>
  );
}
```

**2. Smooth Navigation:**
```typescript
function App() {
  const [isPending, startTransition] = useTransition();
  const [currentPage, setCurrentPage] = useState('home');
  
  const navigateTo = (page: string) => {
    // Urgent update - navigation happens immediately
    setCurrentPage(page);
    
    // Non-urgent update - page content loads in background
    startTransition(() => {
      // Preload page content
      preloadPageContent(page);
    });
  };
  
  return (
    <div>
      <Navigation 
        currentPage={currentPage} 
        onNavigate={navigateTo}
      />
      
      {isPending && <PageTransitionIndicator />}
      
      <Suspense fallback={<PageSkeleton />}>
        <PageContent page={currentPage} />
      </Suspense>
    </div>
  );
}
```

**3. Optimistic Updates:**
```typescript
function OptimisticTodoList() {
  const [isPending, startTransition] = useTransition();
  const [todos, setTodos] = useState<Todo[]>([]);
  
  const addTodo = (text: string) => {
    const newTodo = {
      id: Date.now(),
      text,
      completed: false,
      optimistic: true // Mark as optimistic
    };
    
    // Optimistic update - UI updates immediately
    setTodos(prev => [...prev, newTodo]);
    
    // Non-urgent update - sync with server
    startTransition(async () => {
      try {
        const savedTodo = await saveTodo(text);
        setTodos(prev => 
          prev.map(todo => 
            todo.id === newTodo.id 
              ? { ...savedTodo, optimistic: false }
              : todo
          )
        );
      } catch (error) {
        // Revert optimistic update on error
        setTodos(prev => prev.filter(todo => todo.id !== newTodo.id));
      }
    });
  };
  
  return (
    <div>
      <TodoForm onSubmit={addTodo} />
      
      {isPending && <div>Syncing...</div>}
      
      <TodoList todos={todos} />
    </div>
  );
}
```

**4. Progressive Loading:**
```typescript
function ProgressiveDataLoader() {
  const [isPending, startTransition] = useTransition();
  const [data, setData] = useState<any[]>([]);
  const [page, setPage] = useState(1);
  
  const loadMoreData = () => {
    startTransition(async () => {
      const newData = await fetchData(page + 1);
      setData(prev => [...prev, ...newData]);
      setPage(prev => prev + 1);
    });
  };
  
  return (
    <div>
      <DataList data={data} />
      
      {isPending && <LoadingIndicator />}
      
      <button onClick={loadMoreData}>
        Load More
      </button>
    </div>
  );
}
```

**Key Benefits:**

1. **Immediate Responsiveness**: Urgent updates (like input changes) happen immediately
2. **Non-blocking Updates**: Expensive operations don't block the UI
3. **Better Perceived Performance**: Users see immediate feedback
4. **Smoother Animations**: Transitions can be interrupted without jarring effects
5. **Progressive Enhancement**: Content loads progressively as it becomes available
6. **Optimistic Updates**: UI can update optimistically while syncing in background

**Best Practices:**

1. **Use useTransition for expensive operations**
2. **Use useDeferredValue for values that can lag behind**
3. **Wrap lazy-loaded components in Suspense**
4. **Provide meaningful loading fallbacks**
5. **Combine features for optimal user experience**
6. **Test with slow devices and networks**

These concurrent features work together to create a more responsive and fluid user experience, especially in applications with complex state updates and data fetching.

### 4.6. Explain how React's reconciliation algorithm works. What is the significance of keys in lists?

**Answer:**
React's reconciliation is the process by which React updates the DOM to match the new component tree. It's a diffing algorithm that determines what changes need to be made to the actual DOM based on the differences between the previous and current virtual DOM trees.

**Virtual DOM Overview:**

The Virtual DOM is a JavaScript representation of the real DOM. React creates a virtual representation of the UI in memory and syncs it with the real DOM through a process called reconciliation.

```typescript
// Virtual DOM representation
const virtualDOM = {
  type: 'div',
  props: {
    className: 'container',
    children: [
      {
        type: 'h1',
        props: {
          children: 'Hello World'
        }
      },
      {
        type: 'p',
        props: {
          children: 'This is a paragraph'
        }
      }
    ]
  }
};

// Real DOM representation
<div class="container">
  <h1>Hello World</h1>
  <p>This is a paragraph</p>
</div>
```

**Reconciliation Algorithm:**

React's reconciliation follows these key principles:

1. **Different Root Elements**: If the root elements have different types, React will tear down the old tree and build the new one from scratch.

2. **Same Root Element**: If the root elements have the same type, React will update only the changed attributes.

3. **Component Elements**: If the element is a component, React will update the component's props and re-render.

4. **List Elements**: For lists, React uses keys to determine which items have changed, been added, or removed.

**Detailed Reconciliation Process:**

```typescript
// Example of reconciliation in action
function App() {
  const [count, setCount] = useState(0);
  const [items, setItems] = useState(['A', 'B', 'C']);
  
  return (
    <div>
      <h1>Count: {count}</h1>
      <button onClick={() => setCount(count + 1)}>
        Increment
      </button>
      
      <ul>
        {items.map(item => (
          <li key={item}>{item}</li>
        ))}
      </ul>
      
      <button onClick={() => setItems([...items, 'D'])}>
        Add Item
      </button>
    </div>
  );
}

// When count changes:
// 1. React compares the old and new virtual DOM
// 2. Finds that only the text content of h1 has changed
// 3. Updates only that specific text node in the real DOM
// 4. Leaves all other elements unchanged

// When items change:
// 1. React compares the old and new lists
// 2. Uses keys to identify which items are new
// 3. Adds only the new <li> element to the real DOM
// 4. Leaves existing items unchanged
```

**Key Significance in Lists:**

Keys are crucial for React's reconciliation algorithm when dealing with lists. They help React identify which items have changed, been added, or removed.

**Without Keys (Bad Practice):**

```typescript
// BAD - No keys
function BadList({ items }: { items: string[] }) {
  return (
    <ul>
      {items.map(item => (
        <li>{item}</li> // No key prop!
      ))}
    </ul>
  );
}

// What happens when items change from ['A', 'B', 'C'] to ['A', 'B', 'C', 'D']:
// 1. React compares the old and new virtual DOM
// 2. Without keys, React assumes the order is significant
// 3. React will update the third <li> from 'C' to 'D'
// 4. Then add a new <li> with 'C' at the end
// 5. This is inefficient and can cause issues with component state
```

**With Keys (Good Practice):**

```typescript
// GOOD - With keys
function GoodList({ items }: { items: string[] }) {
  return (
    <ul>
      {items.map(item => (
        <li key={item}>{item}</li> // Key prop provided
      ))}
    </ul>
  );
}

// What happens when items change from ['A', 'B', 'C'] to ['A', 'B', 'C', 'D']:
// 1. React compares the old and new virtual DOM
// 2. With keys, React can identify that 'A', 'B', 'C' are the same
// 3. React will only add the new <li> with 'D'
// 4. All existing items remain unchanged
// 5. This is efficient and preserves component state
```

**Key Requirements and Best Practices:**

1. **Keys Must Be Unique:**
```typescript
// BAD - Duplicate keys
function BadList({ items }: { items: string[] }) {
  return (
    <ul>
      {items.map(item => (
        <li key="item">{item}</li> // All keys are the same!
      ))}
    </ul>
  );
}

// GOOD - Unique keys
function GoodList({ items }: { items: string[] }) {
  return (
    <ul>
      {items.map((item, index) => (
        <li key={`${item}-${index}`}>{item}</li> // Unique keys
      ))}
    </ul>
  );
}
```

2. **Keys Should Be Stable:**
```typescript
// BAD - Unstable keys
function BadList({ items }: { items: string[] }) {
  return (
    <ul>
      {items.map(item => (
        <li key={Math.random()}>{item}</li> // Key changes every render!
      ))}
    </ul>
  );
}

// GOOD - Stable keys
function GoodList({ items }: { items: string[] }) {
  return (
    <ul>
      {items.map(item => (
        <li key={item}>{item}</li> // Key is stable
      ))}
    </ul>
  );
}
```

3. **Keys Should Be Meaningful:**
```typescript
// BAD - Using array index as key
function BadList({ items }: { items: string[] }) {
  return (
    <ul>
      {items.map((item, index) => (
        <li key={index}>{item}</li> // Index can change!
      ))}
    </ul>
  );
}

// GOOD - Using meaningful identifier
function GoodList({ items }: { items: { id: string, name: string }[] }) {
  return (
    <ul>
      {items.map(item => (
        <li key={item.id}>{item.name}</li> // Stable, unique identifier
      ))}
    </ul>
  );
}
```

**Advanced Reconciliation Examples:**

1. **Component State Preservation:**
```typescript
function TodoItem({ todo, onToggle }: { todo: Todo, onToggle: (id: string) => void }) {
  const [isEditing, setIsEditing] = useState(false);
  
  return (
    <div>
      <input
        type="checkbox"
        checked={todo.completed}
        onChange={() => onToggle(todo.id)}
      />
      {isEditing ? (
        <input
          defaultValue={todo.text}
          onBlur={() => setIsEditing(false)}
        />
      ) : (
        <span onClick={() => setIsEditing(true)}>
          {todo.text}
        </span>
      )}
    </div>
  );
}

function TodoList({ todos }: { todos: Todo[] }) {
  const [todos, setTodos] = useState<Todo[]>([]);
  
  const toggleTodo = (id: string) => {
    setTodos(prev => prev.map(todo =>
      todo.id === id ? { ...todo, completed: !todo.completed } : todo
    ));
  };
  
  return (
    <div>
      {todos.map(todo => (
        <TodoItem
          key={todo.id} // Crucial for preserving component state
          todo={todo}
          onToggle={toggleTodo}
        />
      ))}
    </div>
  );
}

// Without proper keys, editing state would be lost when todos reorder
// With proper keys, each TodoItem maintains its editing state
```

2. **Performance Optimization:**
```typescript
function ExpensiveComponent({ data }: { data: any }) {
  // Expensive computation
  const processedData = useMemo(() => {
    return data.map(item => ({
      ...item,
      processed: expensiveProcessing(item)
    }));
  }, [data]);
  
  return (
    <div>
      {processedData.map(item => (
        <ExpensiveChild
          key={item.id} // Prevents unnecessary re-renders
          data={item}
        />
      ))}
    </div>
  );
}

// With proper keys, React can:
// 1. Identify which items are new, changed, or removed
// 2. Only re-render components that actually changed
// 3. Preserve component state and memoized values
```

3. **Dynamic List Operations:**
```typescript
function DynamicList() {
  const [items, setItems] = useState([
    { id: '1', text: 'Item 1' },
    { id: '2', text: 'Item 2' },
    { id: '3', text: 'Item 3' }
  ]);
  
  const addItem = () => {
    const newItem = {
      id: Date.now().toString(),
      text: `Item ${items.length + 1}`
    };
    setItems(prev => [...prev, newItem]);
  };
  
  const removeItem = (id: string) => {
    setItems(prev => prev.filter(item => item.id !== id));
  };
  
  const moveItem = (fromIndex: number, toIndex: number) => {
    setItems(prev => {
      const newItems = [...prev];
      const [movedItem] = newItems.splice(fromIndex, 1);
      newItems.splice(toIndex, 0, movedItem);
      return newItems;
    });
  };
  
  return (
    <div>
      <button onClick={addItem}>Add Item</button>
      
      {items.map((item, index) => (
        <div key={item.id} className="item">
          <span>{item.text}</span>
          <button onClick={() => removeItem(item.id)}>Remove</button>
          <button onClick={() => moveItem(index, 0)}>Move to Top</button>
        </div>
      ))}
    </div>
  );
}

// With proper keys, React can efficiently handle:
// 1. Adding new items (only new components are created)
// 2. Removing items (only removed components are destroyed)
// 3. Reordering items (components are moved, not recreated)
```

**Reconciliation Performance Tips:**

1. **Use React.memo for Expensive Components:**
```typescript
const ExpensiveChild = React.memo(({ data }: { data: any }) => {
  // Expensive rendering logic
  return <div>{data.processed}</div>;
});

// This prevents unnecessary re-renders when parent re-renders
// but props haven't changed
```

2. **Optimize Key Selection:**
```typescript
// BAD - Using unstable keys
function BadList({ items }: { items: any[] }) {
  return (
    <div>
      {items.map((item, index) => (
        <ExpensiveChild key={index} data={item} />
      ))}
    </div>
  );
}

// GOOD - Using stable, unique keys
function GoodList({ items }: { items: any[] }) {
  return (
    <div>
      {items.map(item => (
        <ExpensiveChild key={item.id} data={item} />
      ))}
    </div>
  );
}
```

3. **Avoid Inline Objects and Functions:**
```typescript
// BAD - Creates new objects/functions on every render
function BadList({ items }: { items: any[] }) {
  return (
    <div>
      {items.map(item => (
        <ExpensiveChild
          key={item.id}
          data={item}
          onClick={() => handleClick(item.id)} // New function every render
          config={{ theme: 'dark' }} // New object every render
        />
      ))}
    </div>
  );
}

// GOOD - Stable references
function GoodList({ items }: { items: any[] }) {
  const handleClick = useCallback((id: string) => {
    // Handle click
  }, []);
  
  const config = useMemo(() => ({ theme: 'dark' }), []);
  
  return (
    <div>
      {items.map(item => (
        <ExpensiveChild
          key={item.id}
          data={item}
          onClick={handleClick}
          config={config}
        />
      ))}
    </div>
  );
}
```

**Key Takeaways:**

1. **Reconciliation is React's diffing algorithm** that determines what changes to make to the DOM
2. **Keys are essential for list reconciliation** - they help React identify which items have changed
3. **Keys must be unique, stable, and meaningful** to work effectively
4. **Proper key usage prevents unnecessary re-renders** and preserves component state
5. **Reconciliation performance can be optimized** with React.memo, stable references, and proper key selection

Understanding reconciliation and keys is crucial for building performant React applications, especially when dealing with dynamic lists and complex component trees.

### 4.7. What are Error Boundaries and their limitations? How would you implement error handling in a React application?

**Answer:**
Error Boundaries are React components that catch JavaScript errors anywhere in their child component tree, log those errors, and display a fallback UI instead of the component tree that crashed. They're essential for building robust React applications that can gracefully handle errors.

**What Error Boundaries Are:**

Error Boundaries are class components that implement one or both of the lifecycle methods:
- `static getDerivedStateFromError()` - Used to render a fallback UI after an error has been thrown
- `componentDidCatch()` - Used to log error information

**Basic Error Boundary Implementation:**

```typescript
import React, { Component, ErrorInfo, ReactNode } from 'react';

interface Props {
  children: ReactNode;
  fallback?: ReactNode;
  onError?: (error: Error, errorInfo: ErrorInfo) => void;
}

interface State {
  hasError: boolean;
  error?: Error;
}

class ErrorBoundary extends Component<Props, State> {
  constructor(props: Props) {
    super(props);
    this.state = { hasError: false };
  }

  static getDerivedStateFromError(error: Error): State {
    // Update state so the next render will show the fallback UI
    return { hasError: true, error };
  }

  componentDidCatch(error: Error, errorInfo: ErrorInfo) {
    // Log the error to an error reporting service
    console.error('Error caught by boundary:', error, errorInfo);
    
    // Call custom error handler if provided
    this.props.onError?.(error, errorInfo);
    
    // You can also log the error to an error reporting service
    // logErrorToService(error, errorInfo);
  }

  render() {
    if (this.state.hasError) {
      // You can render any custom fallback UI
      return this.props.fallback || (
        <div className="error-boundary">
          <h2>Something went wrong.</h2>
          <details style={{ whiteSpace: 'pre-wrap' }}>
            {this.state.error && this.state.error.toString()}
          </details>
        </div>
      );
    }

    return this.props.children;
  }
}

// Usage
function App() {
  return (
    <ErrorBoundary
      fallback={<div>Custom error message</div>}
      onError={(error, errorInfo) => {
        // Send to error reporting service
        console.log('Error occurred:', error, errorInfo);
      }}
    >
      <MyComponent />
    </ErrorBoundary>
  );
}
```

**Advanced Error Boundary with Retry Functionality:**

```typescript
interface AdvancedErrorBoundaryProps {
  children: ReactNode;
  fallback?: (error: Error, retry: () => void) => ReactNode;
  onError?: (error: Error, errorInfo: ErrorInfo) => void;
  onRetry?: () => void;
}

interface AdvancedErrorBoundaryState {
  hasError: boolean;
  error?: Error;
  retryCount: number;
}

class AdvancedErrorBoundary extends Component<
  AdvancedErrorBoundaryProps,
  AdvancedErrorBoundaryState
> {
  private retryTimeoutId?: NodeJS.Timeout;

  constructor(props: AdvancedErrorBoundaryProps) {
    super(props);
    this.state = { hasError: false, retryCount: 0 };
  }

  static getDerivedStateFromError(error: Error): Partial<AdvancedErrorBoundaryState> {
    return { hasError: true, error };
  }

  componentDidCatch(error: Error, errorInfo: ErrorInfo) {
    console.error('Error caught by advanced boundary:', error, errorInfo);
    this.props.onError?.(error, errorInfo);
  }

  componentDidUpdate(prevProps: AdvancedErrorBoundaryProps) {
    // Reset error state when children change
    if (prevProps.children !== this.props.children && this.state.hasError) {
      this.setState({ hasError: false, error: undefined });
    }
  }

  componentWillUnmount() {
    if (this.retryTimeoutId) {
      clearTimeout(this.retryTimeoutId);
    }
  }

  handleRetry = () => {
    this.setState(prevState => ({
      hasError: false,
      error: undefined,
      retryCount: prevState.retryCount + 1
    }));
    
    this.props.onRetry?.();
  };

  render() {
    if (this.state.hasError) {
      if (this.props.fallback) {
        return this.props.fallback(this.state.error!, this.handleRetry);
      }

      return (
        <div className="error-boundary">
          <h2>Something went wrong</h2>
          <p>Error: {this.state.error?.message}</p>
          <button onClick={this.handleRetry}>
            Try again (Attempt {this.state.retryCount + 1})
          </button>
        </div>
      );
    }

    return this.props.children;
  }
}

// Usage with custom fallback
function App() {
  return (
    <AdvancedErrorBoundary
      fallback={(error, retry) => (
        <div className="custom-error">
          <h2>Oops! Something went wrong</h2>
          <p>{error.message}</p>
          <button onClick={retry}>Retry</button>
        </div>
      )}
      onError={(error, errorInfo) => {
        // Send to error reporting service
        console.log('Error occurred:', error, errorInfo);
      }}
    >
      <MyComponent />
    </AdvancedErrorBoundary>
  );
}
```

**Error Boundary Limitations:**

1. **Event Handlers**: Error Boundaries don't catch errors inside event handlers.

```typescript
// This error will NOT be caught by Error Boundary
function MyComponent() {
  const handleClick = () => {
    throw new Error('Event handler error'); // Not caught!
  };

  return <button onClick={handleClick}>Click me</button>;
}

// To handle event handler errors, use try-catch
function MyComponent() {
  const handleClick = () => {
    try {
      throw new Error('Event handler error');
    } catch (error) {
      console.error('Event handler error:', error);
      // Handle error appropriately
    }
  };

  return <button onClick={handleClick}>Click me</button>;
}
```

2. **Asynchronous Code**: Error Boundaries don't catch errors in async code.

```typescript
// This error will NOT be caught by Error Boundary
function MyComponent() {
  useEffect(() => {
    setTimeout(() => {
      throw new Error('Async error'); // Not caught!
    }, 1000);
  }, []);

  return <div>Component</div>;
}

// To handle async errors, use try-catch
function MyComponent() {
  useEffect(() => {
    const handleAsyncOperation = async () => {
      try {
        await someAsyncOperation();
      } catch (error) {
        console.error('Async error:', error);
        // Handle error appropriately
      }
    };

    handleAsyncOperation();
  }, []);

  return <div>Component</div>;
}
```

3. **Server-Side Rendering**: Error Boundaries don't work during server-side rendering.

4. **Self-Errors**: Error Boundaries don't catch errors in the Error Boundary component itself.

**Comprehensive Error Handling Strategy:**

```typescript
// 1. Global Error Boundary
class GlobalErrorBoundary extends Component {
  static getDerivedStateFromError(error: Error) {
    return { hasError: true, error };
  }

  componentDidCatch(error: Error, errorInfo: ErrorInfo) {
    // Log to error reporting service
    this.logErrorToService(error, errorInfo);
  }

  logErrorToService = (error: Error, errorInfo: ErrorInfo) => {
    // Send to error reporting service (e.g., Sentry, LogRocket)
    console.error('Global error:', error, errorInfo);
  };

  render() {
    if (this.state.hasError) {
      return (
        <div className="global-error">
          <h1>Something went wrong</h1>
          <p>We're sorry, but something unexpected happened.</p>
          <button onClick={() => window.location.reload()}>
            Reload Page
          </button>
        </div>
      );
    }

    return this.props.children;
  }
}

// 2. Feature-Specific Error Boundary
class FeatureErrorBoundary extends Component {
  static getDerivedStateFromError(error: Error) {
    return { hasError: true, error };
  }

  componentDidCatch(error: Error, errorInfo: ErrorInfo) {
    // Log feature-specific error
    console.error('Feature error:', error, errorInfo);
  }

  render() {
    if (this.state.hasError) {
      return (
        <div className="feature-error">
          <h3>This feature is temporarily unavailable</h3>
          <p>Please try again later.</p>
        </div>
      );
    }

    return this.props.children;
  }
}

// 3. Component-Level Error Handling
function MyComponent() {
  const [error, setError] = useState<Error | null>(null);

  const handleAsyncOperation = async () => {
    try {
      await someAsyncOperation();
    } catch (error) {
      setError(error as Error);
    }
  };

  if (error) {
    return (
      <div className="component-error">
        <p>Error: {error.message}</p>
        <button onClick={() => setError(null)}>Dismiss</button>
      </div>
    );
  }

  return (
    <div>
      <button onClick={handleAsyncOperation}>
        Perform Async Operation
      </button>
    </div>
  );
}

// 4. Custom Hook for Error Handling
function useErrorHandler() {
  const [error, setError] = useState<Error | null>(null);

  const handleError = useCallback((error: Error) => {
    setError(error);
    console.error('Error handled by hook:', error);
  }, []);

  const clearError = useCallback(() => {
    setError(null);
  }, []);

  return { error, handleError, clearError };
}

// Usage of custom hook
function ComponentWithErrorHandling() {
  const { error, handleError, clearError } = useErrorHandler();

  const handleClick = () => {
    try {
      // Some operation that might fail
      throw new Error('Something went wrong');
    } catch (error) {
      handleError(error as Error);
    }
  };

  if (error) {
    return (
      <div>
        <p>Error: {error.message}</p>
        <button onClick={clearError}>Clear Error</button>
      </div>
    );
  }

  return <button onClick={handleClick}>Click me</button>;
}
```

**Error Reporting Integration:**

```typescript
// Error reporting service integration
class ErrorReportingService {
  static logError(error: Error, errorInfo: ErrorInfo, context?: any) {
    // Send to error reporting service
    console.error('Error reported:', {
      error: error.message,
      stack: error.stack,
      componentStack: errorInfo.componentStack,
      context
    });

    // Example: Send to Sentry
    // Sentry.captureException(error, {
    //   contexts: { react: { componentStack: errorInfo.componentStack } },
    //   extra: context
    // });
  }
}

// Enhanced Error Boundary with reporting
class ReportingErrorBoundary extends Component {
  static getDerivedStateFromError(error: Error) {
    return { hasError: true, error };
  }

  componentDidCatch(error: Error, errorInfo: ErrorInfo) {
    ErrorReportingService.logError(error, errorInfo, {
      component: this.constructor.name,
      timestamp: new Date().toISOString()
    });
  }

  render() {
    if (this.state.hasError) {
      return (
        <div className="error-boundary">
          <h2>Something went wrong</h2>
          <p>We've been notified about this error.</p>
        </div>
      );
    }

    return this.props.children;
  }
}
```

**Best Practices for Error Handling:**

1. **Use Error Boundaries at Strategic Points:**
```typescript
function App() {
  return (
    <GlobalErrorBoundary>
      <Header />
      <MainContent />
      <Footer />
    </GlobalErrorBoundary>
  );
}

function MainContent() {
  return (
    <div>
      <FeatureErrorBoundary>
        <UserProfile />
      </FeatureErrorBoundary>
      
      <FeatureErrorBoundary>
        <DataVisualization />
      </FeatureErrorBoundary>
    </div>
  );
}
```

2. **Handle Different Types of Errors:**
```typescript
// Network errors
function useNetworkErrorHandler() {
  const [networkError, setNetworkError] = useState<Error | null>(null);

  const handleNetworkError = useCallback((error: Error) => {
    if (error.name === 'NetworkError' || error.message.includes('fetch')) {
      setNetworkError(error);
    }
  }, []);

  return { networkError, handleNetworkError };
}

// Validation errors
function useValidationErrorHandler() {
  const [validationErrors, setValidationErrors] = useState<string[]>([]);

  const handleValidationError = useCallback((errors: string[]) => {
    setValidationErrors(errors);
  }, []);

  return { validationErrors, handleValidationError };
}
```

3. **Provide Meaningful Error Messages:**
```typescript
function ErrorMessage({ error, type }: { error: Error, type: string }) {
  const getErrorMessage = (error: Error, type: string) => {
    switch (type) {
      case 'network':
        return 'Please check your internet connection and try again.';
      case 'validation':
        return 'Please check your input and try again.';
      case 'permission':
        return 'You do not have permission to perform this action.';
      default:
        return 'Something went wrong. Please try again.';
    }
  };

  return (
    <div className="error-message">
      <p>{getErrorMessage(error, type)}</p>
    </div>
  );
}
```

**Key Takeaways:**

1. **Error Boundaries catch JavaScript errors** in component trees and display fallback UI
2. **They have limitations** - don't catch event handler errors, async errors, or SSR errors
3. **Use them strategically** at different levels of your component tree
4. **Combine with other error handling** techniques for comprehensive coverage
5. **Integrate with error reporting services** for production monitoring
6. **Provide meaningful error messages** to users
7. **Test error scenarios** to ensure your error handling works correctly

Error Boundaries are a crucial part of building robust React applications, but they should be combined with other error handling techniques for comprehensive coverage.

### 4.8. Explain the difference between Server Components and Client Components. What are the trade-offs?

**Answer:**
Server Components and Client Components are two different rendering paradigms in React, each with distinct characteristics and use cases. Understanding their differences is crucial for building modern React applications.

**Server Components:**

Server Components are React components that run on the server during the build process or at request time. They can directly access server-side resources like databases, file systems, and internal APIs.

**Key Characteristics:**
- Run on the server (Node.js environment)
- Can access server-side resources directly
- Don't have access to browser APIs
- Can't use React hooks (useState, useEffect, etc.)
- Can't handle user interactions
- Are rendered to a special format that can be streamed to the client

**Client Components:**

Client Components are traditional React components that run in the browser. They have access to browser APIs and can handle user interactions.

**Key Characteristics:**
- Run in the browser
- Have access to browser APIs (localStorage, DOM, etc.)
- Can use React hooks
- Can handle user interactions
- Are hydrated on the client

**Detailed Comparison:**

```typescript
// Server Component (runs on server)
// Note: This is a conceptual example - actual syntax may vary
async function ServerUserProfile({ userId }: { userId: string }) {
  // Can directly access database
  const user = await db.users.findById(userId);
  const posts = await db.posts.findByUserId(userId);
  
  // Can access server-side APIs
  const analytics = await fetchInternalAPI(`/analytics/user/${userId}`);
  
  return (
    <div>
      <h1>{user.name}</h1>
      <p>Email: {user.email}</p>
      <p>Posts: {posts.length}</p>
      <p>Analytics: {analytics.views}</p>
      
      {/* Can render other Server Components */}
      <ServerPostList posts={posts} />
      
      {/* Can render Client Components */}
      <ClientInteractiveChart data={analytics} />
    </div>
  );
}

// Client Component (runs in browser)
'use client'; // Directive to mark as Client Component

function ClientInteractiveChart({ data }: { data: any }) {
  const [selectedPeriod, setSelectedPeriod] = useState('week');
  const [isLoading, setIsLoading] = useState(false);
  
  // Can use browser APIs
  useEffect(() => {
    const savedPeriod = localStorage.getItem('chartPeriod');
    if (savedPeriod) {
      setSelectedPeriod(savedPeriod);
    }
  }, []);
  
  // Can handle user interactions
  const handlePeriodChange = (period: string) => {
    setSelectedPeriod(period);
    localStorage.setItem('chartPeriod', period);
    setIsLoading(true);
    
    // Can make client-side API calls
    fetch(`/api/analytics?period=${period}`)
      .then(response => response.json())
      .then(data => {
        // Update chart data
        setIsLoading(false);
      });
  };
  
  return (
    <div>
      <select value={selectedPeriod} onChange={(e) => handlePeriodChange(e.target.value)}>
        <option value="week">Week</option>
        <option value="month">Month</option>
        <option value="year">Year</option>
      </select>
      
      {isLoading ? (
        <div>Loading...</div>
      ) : (
        <Chart data={data} period={selectedPeriod} />
      )}
    </div>
  );
}
```

**When to Use Each:**

**Use Server Components for:**
1. **Data Fetching**: Direct database access, file system operations
2. **Static Content**: Content that doesn't change based on user interactions
3. **SEO-Critical Content**: Content that needs to be available for search engines
4. **Performance**: Reducing client-side JavaScript bundle size

```typescript
// Server Component for data fetching
async function ServerProductList({ category }: { category: string }) {
  // Direct database access - no API calls needed
  const products = await db.products.findByCategory(category);
  const categoryInfo = await db.categories.findById(category);
  
  return (
    <div>
      <h1>{categoryInfo.name}</h1>
      <p>{categoryInfo.description}</p>
      
      <div className="product-grid">
        {products.map(product => (
          <div key={product.id} className="product-card">
            <h3>{product.name}</h3>
            <p>{product.description}</p>
            <p>Price: ${product.price}</p>
            
            {/* Client Component for interactive features */}
            <ClientAddToCartButton productId={product.id} />
          </div>
        ))}
      </div>
    </div>
  );
}
```

**Use Client Components for:**
1. **User Interactions**: Forms, buttons, input fields
2. **Browser APIs**: localStorage, geolocation, camera access
3. **State Management**: Complex state logic, real-time updates
4. **Third-party Libraries**: Libraries that require browser APIs

```typescript
// Client Component for user interactions
'use client';

function ClientAddToCartButton({ productId }: { productId: string }) {
  const [isAdding, setIsAdding] = useState(false);
  const [cartCount, setCartCount] = useState(0);
  
  // Can access browser APIs
  useEffect(() => {
    const savedCartCount = localStorage.getItem('cartCount');
    if (savedCartCount) {
      setCartCount(parseInt(savedCartCount));
    }
  }, []);
  
  const handleAddToCart = async () => {
    setIsAdding(true);
    
    try {
      // Client-side API call
      const response = await fetch('/api/cart/add', {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify({ productId })
      });
      
      if (response.ok) {
        setCartCount(prev => prev + 1);
        localStorage.setItem('cartCount', (cartCount + 1).toString());
      }
    } catch (error) {
      console.error('Failed to add to cart:', error);
    } finally {
      setIsAdding(false);
    }
  };
  
  return (
    <button 
      onClick={handleAddToCart}
      disabled={isAdding}
      className="add-to-cart-btn"
    >
      {isAdding ? 'Adding...' : 'Add to Cart'}
      {cartCount > 0 && <span className="cart-count">{cartCount}</span>}
    </button>
  );
}
```

**Trade-offs and Considerations:**

**Server Components Advantages:**
1. **Performance**: Reduced client-side JavaScript bundle size
2. **Security**: Sensitive operations stay on the server
3. **SEO**: Content is available for search engines
4. **Direct Data Access**: No need for API endpoints for simple data fetching
5. **Cost**: Reduced server costs for data processing

**Server Components Disadvantages:**
1. **Limited Interactivity**: No user interactions or state management
2. **No Browser APIs**: Can't access localStorage, DOM, etc.
3. **Complexity**: Requires understanding of server-side rendering
4. **Debugging**: Harder to debug server-side code
5. **Deployment**: Requires server infrastructure

**Client Components Advantages:**
1. **Full Interactivity**: Complete user interaction capabilities
2. **Browser APIs**: Access to all browser features
3. **State Management**: Full React hooks support
4. **Third-party Libraries**: Can use any client-side library
5. **Debugging**: Easier to debug with browser dev tools

**Client Components Disadvantages:**
1. **Bundle Size**: Increases client-side JavaScript
2. **Performance**: Can impact initial page load
3. **SEO**: Content may not be available for search engines
4. **Security**: Sensitive logic exposed to client
5. **API Calls**: Requires additional API endpoints

**Hybrid Approach - Best of Both Worlds:**

```typescript
// Server Component for data fetching and static content
async function ServerProductPage({ productId }: { productId: string }) {
  // Server-side data fetching
  const product = await db.products.findById(productId);
  const reviews = await db.reviews.findByProductId(productId);
  const relatedProducts = await db.products.findRelated(productId);
  
  return (
    <div className="product-page">
      {/* Static content rendered on server */}
      <h1>{product.name}</h1>
      <p>{product.description}</p>
      <p>Price: ${product.price}</p>
      
      {/* Client Component for interactive features */}
      <ClientProductActions product={product} />
      
      {/* Server Component for reviews */}
      <ServerReviewList reviews={reviews} />
      
      {/* Client Component for related products with interactions */}
      <ClientRelatedProducts products={relatedProducts} />
    </div>
  );
}

// Client Component for interactive features
'use client';

function ClientProductActions({ product }: { product: Product }) {
  const [quantity, setQuantity] = useState(1);
  const [isWishlisted, setIsWishlisted] = useState(false);
  
  const handleAddToCart = async () => {
    // Client-side interaction
    await addToCart(product.id, quantity);
  };
  
  const handleWishlistToggle = async () => {
    // Client-side interaction
    if (isWishlisted) {
      await removeFromWishlist(product.id);
    } else {
      await addToWishlist(product.id);
    }
    setIsWishlisted(!isWishlisted);
  };
  
  return (
    <div className="product-actions">
      <div className="quantity-selector">
        <button onClick={() => setQuantity(Math.max(1, quantity - 1))}>-</button>
        <span>{quantity}</span>
        <button onClick={() => setQuantity(quantity + 1)}>+</button>
      </div>
      
      <button onClick={handleAddToCart} className="add-to-cart">
        Add to Cart
      </button>
      
      <button 
        onClick={handleWishlistToggle}
        className={`wishlist ${isWishlisted ? 'active' : ''}`}
      >
        {isWishlisted ? 'Remove from Wishlist' : 'Add to Wishlist'}
      </button>
    </div>
  );
}
```

**Migration Strategy:**

When migrating from traditional React to Server Components:

1. **Identify Static Content**: Move data fetching and static rendering to Server Components
2. **Keep Interactive Features**: Maintain Client Components for user interactions
3. **Gradual Migration**: Start with new features, then migrate existing ones
4. **Performance Monitoring**: Measure bundle size and performance improvements

```typescript
// Before: Traditional Client Component
function ProductList({ category }: { category: string }) {
  const [products, setProducts] = useState([]);
  const [loading, setLoading] = useState(true);
  
  useEffect(() => {
    // Client-side data fetching
    fetch(`/api/products?category=${category}`)
      .then(response => response.json())
      .then(data => {
        setProducts(data);
        setLoading(false);
      });
  }, [category]);
  
  if (loading) return <div>Loading...</div>;
  
  return (
    <div>
      {products.map(product => (
        <ProductCard key={product.id} product={product} />
      ))}
    </div>
  );
}

// After: Server Component + Client Component
// Server Component for data fetching
async function ServerProductList({ category }: { category: string }) {
  // Direct database access
  const products = await db.products.findByCategory(category);
  
  return (
    <div>
      {products.map(product => (
        <ClientProductCard key={product.id} product={product} />
      ))}
    </div>
  );
}

// Client Component for interactions
'use client';

function ClientProductCard({ product }: { product: Product }) {
  const [isWishlisted, setIsWishlisted] = useState(false);
  
  const handleWishlistToggle = () => {
    // Client-side interaction
    setIsWishlisted(!isWishlisted);
  };
  
  return (
    <div className="product-card">
      <h3>{product.name}</h3>
      <p>{product.description}</p>
      <p>Price: ${product.price}</p>
      
      <button onClick={handleWishlistToggle}>
        {isWishlisted ? 'Remove from Wishlist' : 'Add to Wishlist'}
      </button>
    </div>
  );
}
```

**Key Takeaways:**

1. **Server Components** are ideal for data fetching, static content, and SEO-critical features
2. **Client Components** are necessary for user interactions, browser APIs, and state management
3. **Hybrid approach** provides the best performance and user experience
4. **Consider trade-offs** carefully when choosing between Server and Client Components
5. **Migration** should be gradual and performance-focused
6. **Bundle size** and **initial load performance** are key considerations

Server Components represent a significant shift in React architecture, enabling better performance and user experience when used appropriately alongside Client Components.

---

### 4.9. What's the difference between useEffect and useLayoutEffect? When would you use each?

**Answer:**

`useEffect` and `useLayoutEffect` are both hooks for handling side effects, but they differ in **when** they execute during the React rendering cycle.

**Key Differences:**

1. **Timing:**
   - `useEffect`: Runs **after** the DOM has been updated and painted to the screen (asynchronous)
   - `useLayoutEffect`: Runs **synchronously** after all DOM mutations but **before** the browser paints

2. **Performance Impact:**
   - `useEffect`: Non-blocking, doesn't delay visual updates
   - `useLayoutEffect`: Blocking, can delay visual updates if it takes too long

**When to Use useEffect (Most Common):**

```typescript
function DataFetcher({ userId }: { userId: string }) {
  const [user, setUser] = useState(null);
  const [loading, setLoading] = useState(false);

  // Good for data fetching, subscriptions, timers
  useEffect(() => {
    setLoading(true);
    fetchUser(userId)
      .then(setUser)
      .finally(() => setLoading(false));
  }, [userId]);

  // Good for cleanup
  useEffect(() => {
    const timer = setInterval(() => {
      console.log('Timer tick');
    }, 1000);

    return () => clearInterval(timer);
  }, []);

  return loading ? <div>Loading...</div> : <div>{user?.name}</div>;
}
```

**When to Use useLayoutEffect (Specific Cases):**

```typescript
function Tooltip({ children, content }: { children: React.ReactNode; content: string }) {
  const [position, setPosition] = useState({ top: 0, left: 0 });
  const tooltipRef = useRef<HTMLDivElement>(null);
  const triggerRef = useRef<HTMLDivElement>(null);

  // Use useLayoutEffect to prevent visual flicker
  useLayoutEffect(() => {
    if (tooltipRef.current && triggerRef.current) {
      const triggerRect = triggerRef.current.getBoundingClientRect();
      const tooltipRect = tooltipRef.current.getBoundingClientRect();
      
      // Calculate position to prevent tooltip from going off-screen
      const top = triggerRect.bottom + 8;
      const left = Math.max(8, Math.min(
        triggerRect.left,
        window.innerWidth - tooltipRect.width - 8
      ));
      
      setPosition({ top, left });
    }
  }, [content]);

  return (
    <div ref={triggerRef} style={{ position: 'relative' }}>
      {children}
      <div
        ref={tooltipRef}
        style={{
          position: 'absolute',
          top: position.top,
          left: position.left,
          background: 'black',
          color: 'white',
          padding: '4px 8px',
          borderRadius: '4px',
          zIndex: 1000,
        }}
      >
        {content}
      </div>
    </div>
  );
}

// Another example: Measuring DOM elements
function DynamicHeightComponent({ content }: { content: string }) {
  const [height, setHeight] = useState(0);
  const contentRef = useRef<HTMLDivElement>(null);

  useLayoutEffect(() => {
    if (contentRef.current) {
      // Measure the actual rendered height
      const measuredHeight = contentRef.current.scrollHeight;
      setHeight(measuredHeight);
    }
  }, [content]);

  return (
    <div style={{ height: height || 'auto' }}>
      <div ref={contentRef}>{content}</div>
    </div>
  );
}
```

**Summary:**
- Use `useEffect` for 99% of side effects (data fetching, subscriptions, cleanup)
- Use `useLayoutEffect` only when you need to read layout from the DOM and synchronously re-render to prevent visual flicker
- Common use cases for `useLayoutEffect`: tooltips, modals, measuring elements, animations that depend on DOM measurements

### 4.10. When should you use useState vs useReducer? Provide examples of each.

**Answer:**

Both `useState` and `useReducer` manage component state, but they're suited for different scenarios based on state complexity and update patterns.

**useState - Simple State Management:**

```typescript
// Good for simple, independent state values
function SimpleForm() {
  const [name, setName] = useState('');
  const [email, setEmail] = useState('');
  const [isSubmitting, setIsSubmitting] = useState(false);

  const handleSubmit = async (e: React.FormEvent) => {
    e.preventDefault();
    setIsSubmitting(true);
    
    try {
      await submitForm({ name, email });
      setName('');
      setEmail('');
    } finally {
      setIsSubmitting(false);
    }
  };

  return (
    <form onSubmit={handleSubmit}>
      <input
        value={name}
        onChange={(e) => setName(e.target.value)}
        placeholder="Name"
      />
      <input
        value={email}
        onChange={(e) => setEmail(e.target.value)}
        placeholder="Email"
      />
      <button disabled={isSubmitting}>
        {isSubmitting ? 'Submitting...' : 'Submit'}
      </button>
    </form>
  );
}

// Good for simple toggles and counters
function Counter() {
  const [count, setCount] = useState(0);
  
  return (
    <div>
      <p>Count: {count}</p>
      <button onClick={() => setCount(count + 1)}>+</button>
      <button onClick={() => setCount(count - 1)}>-</button>
      <button onClick={() => setCount(0)}>Reset</button>
    </div>
  );
}
```

**useReducer - Complex State Management:**

```typescript
// Good for complex state with multiple related values
interface TodoState {
  todos: Todo[];
  filter: 'all' | 'active' | 'completed';
  loading: boolean;
  error: string | null;
}

type TodoAction =
  | { type: 'ADD_TODO'; payload: string }
  | { type: 'TOGGLE_TODO'; payload: string }
  | { type: 'DELETE_TODO'; payload: string }
  | { type: 'SET_FILTER'; payload: 'all' | 'active' | 'completed' }
  | { type: 'SET_LOADING'; payload: boolean }
  | { type: 'SET_ERROR'; payload: string | null }
  | { type: 'CLEAR_COMPLETED' };

function todoReducer(state: TodoState, action: TodoAction): TodoState {
  switch (action.type) {
    case 'ADD_TODO':
      return {
        ...state,
        todos: [...state.todos, { id: Date.now().toString(), text: action.payload, completed: false }]
      };
    
    case 'TOGGLE_TODO':
      return {
        ...state,
        todos: state.todos.map(todo =>
          todo.id === action.payload ? { ...todo, completed: !todo.completed } : todo
        )
      };
    
    case 'DELETE_TODO':
      return {
        ...state,
        todos: state.todos.filter(todo => todo.id !== action.payload)
      };
    
    case 'SET_FILTER':
      return { ...state, filter: action.payload };
    
    case 'SET_LOADING':
      return { ...state, loading: action.payload };
    
    case 'SET_ERROR':
      return { ...state, error: action.payload };
    
    case 'CLEAR_COMPLETED':
      return {
        ...state,
        todos: state.todos.filter(todo => !todo.completed)
      };
    
    default:
      return state;
  }
}

function TodoApp() {
  const [state, dispatch] = useReducer(todoReducer, {
    todos: [],
    filter: 'all',
    loading: false,
    error: null
  });

  const filteredTodos = state.todos.filter(todo => {
    switch (state.filter) {
      case 'active': return !todo.completed;
      case 'completed': return todo.completed;
      default: return true;
    }
  });

  const addTodo = (text: string) => {
    dispatch({ type: 'ADD_TODO', payload: text });
  };

  const toggleTodo = (id: string) => {
    dispatch({ type: 'TOGGLE_TODO', payload: id });
  };

  return (
    <div>
      <TodoInput onAdd={addTodo} />
      <FilterButtons 
        currentFilter={state.filter}
        onFilterChange={(filter) => dispatch({ type: 'SET_FILTER', payload: filter })}
      />
      <TodoList todos={filteredTodos} onToggle={toggleTodo} />
    </div>
  );
}
```

**When to Choose Each:**

**Use useState when:**
- State is simple (single values, booleans, strings)
- State updates are independent
- No complex logic needed for updates
- State doesn't need to be shared between components

**Use useReducer when:**
- State has multiple related values
- State updates depend on previous state
- Complex update logic
- Need to share state logic between components
- State updates follow predictable patterns
- Want to test state logic separately

**Example: Form with Complex Validation (useReducer)**

```typescript
interface FormState {
  values: Record<string, string>;
  errors: Record<string, string>;
  touched: Record<string, boolean>;
  isSubmitting: boolean;
}

type FormAction =
  | { type: 'SET_FIELD'; field: string; value: string }
  | { type: 'SET_ERROR'; field: string; error: string }
  | { type: 'TOUCH_FIELD'; field: string }
  | { type: 'SET_SUBMITTING'; payload: boolean }
  | { type: 'RESET_FORM' };

function formReducer(state: FormState, action: FormAction): FormState {
  switch (action.type) {
    case 'SET_FIELD':
      return {
        ...state,
        values: { ...state.values, [action.field]: action.value },
        errors: { ...state.errors, [action.field]: '' } // Clear error when user types
      };
    
    case 'SET_ERROR':
      return {
        ...state,
        errors: { ...state.errors, [action.field]: action.error }
      };
    
    case 'TOUCH_FIELD':
      return {
        ...state,
        touched: { ...state.touched, [action.field]: true }
      };
    
    case 'SET_SUBMITTING':
      return { ...state, isSubmitting: action.payload };
    
    case 'RESET_FORM':
      return { values: {}, errors: {}, touched: {}, isSubmitting: false };
    
    default:
      return state;
  }
}
```

### 4.11. Explain the Context API in detail. How do you avoid performance issues with Context?

**Answer:**

The Context API provides a way to share data between components without prop drilling. It's built into React and consists of `createContext`, `Provider`, and `useContext`.

**Basic Context Implementation:**

```typescript
// 1. Create Context
interface ThemeContextType {
  theme: 'light' | 'dark';
  toggleTheme: () => void;
}

const ThemeContext = createContext<ThemeContextType | undefined>(undefined);

// 2. Create Provider Component
function ThemeProvider({ children }: { children: React.ReactNode }) {
  const [theme, setTheme] = useState<'light' | 'dark'>('light');

  const toggleTheme = useCallback(() => {
    setTheme(prev => prev === 'light' ? 'dark' : 'light');
  }, []);

  const value = useMemo(() => ({
    theme,
    toggleTheme
  }), [theme, toggleTheme]);

  return (
    <ThemeContext.Provider value={value}>
      {children}
    </ThemeContext.Provider>
  );
}

// 3. Custom Hook for Using Context
function useTheme() {
  const context = useContext(ThemeContext);
  if (context === undefined) {
    throw new Error('useTheme must be used within a ThemeProvider');
  }
  return context;
}

// 4. Using the Context
function App() {
  return (
    <ThemeProvider>
      <Header />
      <Main />
    </ThemeProvider>
  );
}

function Header() {
  const { theme, toggleTheme } = useTheme();
  
  return (
    <header style={{ background: theme === 'light' ? 'white' : 'black' }}>
      <button onClick={toggleTheme}>
        Switch to {theme === 'light' ? 'dark' : 'light'} theme
      </button>
    </header>
  );
}
```

**Performance Issues and Solutions:**

**Problem 1: Unnecessary Re-renders**

```typescript
// BAD - Causes all consumers to re-render when any value changes
const AppContext = createContext();

function AppProvider({ children }) {
  const [user, setUser] = useState(null);
  const [theme, setTheme] = useState('light');
  const [notifications, setNotifications] = useState([]);

  // This object is recreated on every render!
  const value = {
    user,
    setUser,
    theme,
    setTheme,
    notifications,
    setNotifications
  };

  return (
    <AppContext.Provider value={value}>
      {children}
    </AppContext.Provider>
  );
}

// GOOD - Split contexts by domain
const UserContext = createContext();
const ThemeContext = createContext();
const NotificationContext = createContext();

function UserProvider({ children }) {
  const [user, setUser] = useState(null);
  
  const value = useMemo(() => ({
    user,
    setUser
  }), [user]);

  return (
    <UserContext.Provider value={value}>
      {children}
    </UserContext.Provider>
  );
}

function ThemeProvider({ children }) {
  const [theme, setTheme] = useState('light');
  
  const value = useMemo(() => ({
    theme,
    setTheme
  }), [theme]);

  return (
    <ThemeContext.Provider value={value}>
      {children}
    </ThemeContext.Provider>
  );
}
```

**Problem 2: Expensive Context Values**

```typescript
// BAD - Expensive computation on every render
function DataProvider({ children }) {
  const [rawData, setRawData] = useState([]);
  
  // This runs on every render!
  const processedData = rawData.map(item => ({
    ...item,
    computed: expensiveCalculation(item)
  }));

  const value = { processedData, setRawData };
  
  return (
    <DataContext.Provider value={value}>
      {children}
    </DataContext.Provider>
  );
}

// GOOD - Memoize expensive computations
function DataProvider({ children }) {
  const [rawData, setRawData] = useState([]);
  
  const processedData = useMemo(() => {
    return rawData.map(item => ({
      ...item,
      computed: expensiveCalculation(item)
    }));
  }, [rawData]);

  const value = useMemo(() => ({
    processedData,
    setRawData
  }), [processedData]);

  return (
    <DataContext.Provider value={value}>
      {children}
    </DataContext.Provider>
  );
}
```

**Advanced Pattern: Context with Selectors**

```typescript
// Create a context that only re-renders when specific values change
function createSelectorContext<T>() {
  const Context = createContext<T | undefined>(undefined);
  
  const Provider = ({ value, children }: { value: T; children: React.ReactNode }) => {
    return <Context.Provider value={value}>{children}</Context.Provider>;
  };
  
  const useSelector = <R>(selector: (value: T) => R): R => {
    const context = useContext(Context);
    if (context === undefined) {
      throw new Error('useSelector must be used within Provider');
    }
    
    const selectedValue = useMemo(() => selector(context), [context, selector]);
    return selectedValue;
  };
  
  return { Provider, useSelector };
}

// Usage
interface AppState {
  user: User | null;
  theme: string;
  notifications: Notification[];
}

const { Provider: AppProvider, useSelector: useAppSelector } = createSelectorContext<AppState>();

function UserProfile() {
  // Only re-renders when user changes, not when theme or notifications change
  const user = useAppSelector(state => state.user);
  
  return <div>{user?.name}</div>;
}

function ThemeButton() {
  // Only re-renders when theme changes
  const theme = useAppSelector(state => state.theme);
  
  return <button>Current theme: {theme}</button>;
}
```

**Best Practices:**

1. **Split contexts by domain** - Don't put everything in one context
2. **Memoize context values** - Use `useMemo` for the value object
3. **Use custom hooks** - Create `useContext` wrappers with error handling
4. **Consider alternatives** - For complex state, consider Redux or Zustand
5. **Avoid frequent updates** - Batch updates when possible

### 4.12. How do you implement routing in React applications? Compare different routing solutions.

**Answer:**

Routing in React applications is typically handled by client-side routing libraries since React is a single-page application framework.

**React Router (Most Popular):**

```typescript
import { BrowserRouter, Routes, Route, Link, useParams, useNavigate } from 'react-router-dom';

// Basic routing setup
function App() {
  return (
    <BrowserRouter>
      <nav>
        <Link to="/">Home</Link>
        <Link to="/about">About</Link>
        <Link to="/users">Users</Link>
      </nav>
      
      <Routes>
        <Route path="/" element={<Home />} />
        <Route path="/about" element={<About />} />
        <Route path="/users" element={<Users />} />
        <Route path="/users/:id" element={<UserDetail />} />
        <Route path="*" element={<NotFound />} />
      </Routes>
    </BrowserRouter>
  );
}

// Using route parameters
function UserDetail() {
  const { id } = useParams<{ id: string }>();
  const navigate = useNavigate();
  
  return (
    <div>
      <h2>User {id}</h2>
      <button onClick={() => navigate('/users')}>
        Back to Users
      </button>
    </div>
  );
}

// Protected routes
function ProtectedRoute({ children }: { children: React.ReactNode }) {
  const { user } = useAuth();
  
  if (!user) {
    return <Navigate to="/login" replace />;
  }
  
  return <>{children}</>;
}

// Usage
<Route 
  path="/dashboard" 
  element={
    <ProtectedRoute>
      <Dashboard />
    </ProtectedRoute>
  } 
/>
```

**Nested Routes:**

```typescript
function App() {
  return (
    <BrowserRouter>
      <Routes>
        <Route path="/" element={<Layout />}>
          <Route index element={<Home />} />
          <Route path="products" element={<Products />}>
            <Route index element={<ProductList />} />
            <Route path=":id" element={<ProductDetail />} />
            <Route path="new" element={<NewProduct />} />
          </Route>
          <Route path="about" element={<About />} />
        </Route>
      </Routes>
    </BrowserRouter>
  );
}

function Layout() {
  return (
    <div>
      <Header />
      <main>
        <Outlet /> {/* Renders child routes */}
      </main>
      <Footer />
    </div>
  );
}
```

**Route Guards and Authentication:**

```typescript
// Custom hook for authentication
function useAuth() {
  const [user, setUser] = useState(null);
  const [loading, setLoading] = useState(true);
  
  useEffect(() => {
    checkAuth().then(user => {
      setUser(user);
      setLoading(false);
    });
  }, []);
  
  return { user, loading };
}

// Protected route component
function ProtectedRoute({ children, requiredRole }: { 
  children: React.ReactNode; 
  requiredRole?: string;
}) {
  const { user, loading } = useAuth();
  const location = useLocation();
  
  if (loading) {
    return <div>Loading...</div>;
  }
  
  if (!user) {
    return <Navigate to="/login" state={{ from: location }} replace />;
  }
  
  if (requiredRole && user.role !== requiredRole) {
    return <Navigate to="/unauthorized" replace />;
  }
  
  return <>{children}</>;
}

// Usage
<Route 
  path="/admin" 
  element={
    <ProtectedRoute requiredRole="admin">
      <AdminPanel />
    </ProtectedRoute>
  } 
/>
```

**Alternative Routing Solutions:**

**1. Next.js Router (File-based routing):**

```typescript
// pages/index.tsx
import { useRouter } from 'next/router';

export default function Home() {
  const router = useRouter();
  
  const handleNavigate = () => {
    router.push('/about');
  };
  
  return (
    <div>
      <h1>Home Page</h1>
      <button onClick={handleNavigate}>Go to About</button>
    </div>
  );
}

// pages/users/[id].tsx - Dynamic route
export default function UserDetail() {
  const router = useRouter();
  const { id } = router.query;
  
  return <div>User ID: {id}</div>;
}
```

**2. Wouter (Lightweight alternative):**

```typescript
import { Router, Route, Link, useLocation } from 'wouter';

function App() {
  return (
    <Router>
      <nav>
        <Link href="/">Home</Link>
        <Link href="/about">About</Link>
      </nav>
      
      <Route path="/" component={Home} />
      <Route path="/about" component={About} />
      <Route path="/users/:id" component={UserDetail} />
    </Router>
  );
}
```

**3. Reach Router (Deprecated, but concepts still relevant):**

```typescript
// Focus management and accessibility features
import { Router, Link, navigate } from '@reach/router';

function App() {
  return (
    <Router>
      <Home path="/" />
      <About path="/about" />
      <Users path="/users" />
      <UserDetail path="/users/:id" />
    </Router>
  );
}
```

**Routing Best Practices:**

1. **Use BrowserRouter for production** - Provides clean URLs
2. **Implement route guards** - Protect sensitive routes
3. **Handle loading states** - Show loading indicators during navigation
4. **Use lazy loading** - Code split routes for better performance
5. **Handle 404s** - Provide fallback routes
6. **Consider SEO** - Use proper meta tags and structured data

```typescript
// Lazy loading routes
const Home = lazy(() => import('./pages/Home'));
const About = lazy(() => import('./pages/About'));

function App() {
  return (
    <BrowserRouter>
      <Suspense fallback={<div>Loading...</div>}>
        <Routes>
          <Route path="/" element={<Home />} />
          <Route path="/about" element={<About />} />
        </Routes>
      </Suspense>
    </BrowserRouter>
  );
}
```

### 4.13. What are React Portals and when would you use them?

**Answer:**

React Portals provide a way to render children into a DOM node that exists outside the parent component's DOM hierarchy. This is useful for modals, tooltips, dropdowns, and other UI elements that need to break out of their container's styling constraints.

**Basic Portal Implementation:**

```typescript
import { createPortal } from 'react-dom';

interface ModalProps {
  isOpen: boolean;
  onClose: () => void;
  children: React.ReactNode;
}

function Modal({ isOpen, onClose, children }: ModalProps) {
  if (!isOpen) return null;

  return createPortal(
    <div className="modal-overlay" onClick={onClose}>
      <div className="modal-content" onClick={(e) => e.stopPropagation()}>
        <button className="modal-close" onClick={onClose}>×</button>
        {children}
      </div>
    </div>,
    document.body // Portal target
  );
}

// Usage
function App() {
  const [isModalOpen, setIsModalOpen] = useState(false);

  return (
    <div>
      <button onClick={() => setIsModalOpen(true)}>
        Open Modal
      </button>
      
      <Modal 
        isOpen={isModalOpen} 
        onClose={() => setIsModalOpen(false)}
      >
        <h2>Modal Title</h2>
        <p>Modal content goes here...</p>
      </Modal>
    </div>
  );
}
```

**Advanced Portal with Dynamic Container:**

```typescript
function Portal({ children, containerId = 'portal-root' }: { 
  children: React.ReactNode; 
  containerId?: string;
}) {
  const [container, setContainer] = useState<HTMLElement | null>(null);

  useEffect(() => {
    // Find or create portal container
    let portalContainer = document.getElementById(containerId);
    
    if (!portalContainer) {
      portalContainer = document.createElement('div');
      portalContainer.id = containerId;
      document.body.appendChild(portalContainer);
    }
    
    setContainer(portalContainer);
    
    // Cleanup
    return () => {
      if (portalContainer && portalContainer.parentNode) {
        portalContainer.parentNode.removeChild(portalContainer);
      }
    };
  }, [containerId]);

  if (!container) return null;

  return createPortal(children, container);
}

// Usage
function Tooltip({ children, content }: { children: React.ReactNode; content: string }) {
  const [isVisible, setIsVisible] = useState(false);
  const [position, setPosition] = useState({ top: 0, left: 0 });
  const triggerRef = useRef<HTMLDivElement>(null);

  const updatePosition = useCallback(() => {
    if (triggerRef.current) {
      const rect = triggerRef.current.getBoundingClientRect();
      setPosition({
        top: rect.bottom + window.scrollY + 8,
        left: rect.left + window.scrollX
      });
    }
  }, []);

  return (
    <>
      <div
        ref={triggerRef}
        onMouseEnter={() => {
          updatePosition();
          setIsVisible(true);
        }}
        onMouseLeave={() => setIsVisible(false)}
      >
        {children}
      </div>
      
      <Portal>
        {isVisible && (
          <div
            style={{
              position: 'absolute',
              top: position.top,
              left: position.left,
              background: 'black',
              color: 'white',
              padding: '4px 8px',
              borderRadius: '4px',
              zIndex: 1000,
              pointerEvents: 'none'
            }}
          >
            {content}
          </div>
        )}
      </Portal>
    </>
  );
}
```

**Portal with Focus Management:**

```typescript
function AccessibleModal({ isOpen, onClose, children }: ModalProps) {
  const modalRef = useRef<HTMLDivElement>(null);
  const previousActiveElement = useRef<HTMLElement | null>(null);

  useEffect(() => {
    if (isOpen) {
      // Store the currently focused element
      previousActiveElement.current = document.activeElement as HTMLElement;
      
      // Focus the modal
      modalRef.current?.focus();
      
      // Prevent body scroll
      document.body.style.overflow = 'hidden';
      
      // Handle escape key
      const handleEscape = (e: KeyboardEvent) => {
        if (e.key === 'Escape') {
          onClose();
        }
      };
      
      document.addEventListener('keydown', handleEscape);
      
      return () => {
        document.removeEventListener('keydown', handleEscape);
        document.body.style.overflow = 'unset';
        
        // Restore focus
        previousActiveElement.current?.focus();
      };
    }
  }, [isOpen, onClose]);

  if (!isOpen) return null;

  return createPortal(
    <div 
      className="modal-overlay"
      onClick={onClose}
      role="dialog"
      aria-modal="true"
    >
      <div
        ref={modalRef}
        className="modal-content"
        onClick={(e) => e.stopPropagation()}
        tabIndex={-1}
      >
        {children}
      </div>
    </div>,
    document.body
  );
}
```

**When to Use Portals:**

1. **Modals and Dialogs** - Break out of parent container styling
2. **Tooltips and Popovers** - Position relative to viewport
3. **Dropdowns** - Avoid z-index and overflow issues
4. **Notifications** - Render at app level
5. **Loading Overlays** - Cover entire application

**Portal Best Practices:**

1. **Always clean up** - Remove portal containers when unmounting
2. **Handle focus management** - For accessibility
3. **Use proper z-index** - Ensure portals appear above other content
4. **Consider SSR** - Portals don't work during server-side rendering
5. **Test with screen readers** - Ensure accessibility

```typescript
// Custom hook for portal management
function usePortal(containerId: string) {
  const [container, setContainer] = useState<HTMLElement | null>(null);

  useEffect(() => {
    let portalContainer = document.getElementById(containerId);
    
    if (!portalContainer) {
      portalContainer = document.createElement('div');
      portalContainer.id = containerId;
      document.body.appendChild(portalContainer);
    }
    
    setContainer(portalContainer);
    
    return () => {
      if (portalContainer?.parentNode) {
        portalContainer.parentNode.removeChild(portalContainer);
      }
    };
  }, [containerId]);

  const Portal = useCallback(({ children }: { children: React.ReactNode }) => {
    if (!container) return null;
    return createPortal(children, container);
  }, [container]);

  return Portal;
}

// Usage
function MyComponent() {
  const Portal = usePortal('my-portal');
  
  return (
    <div>
      <Portal>
        <div>This renders in a portal!</div>
      </Portal>
    </div>
  );
}
```

### 4.14. Provide a comprehensive overview of all React hooks in table format with brief descriptions and use cases.

**Answer:**

Here's a complete reference table of all React hooks with their purposes, return values, and common use cases:

| Hook | Purpose | Returns | Common Use Cases |
|------|---------|---------|------------------|
| **useState** | Manage local component state | `[state, setState]` | Form inputs, counters, toggles, simple state |
| **useReducer** | Manage complex state with actions | `[state, dispatch]` | Complex forms, state machines, multiple related values |
| **useEffect** | Handle side effects after render | `undefined` | Data fetching, subscriptions, timers, cleanup |
| **useLayoutEffect** | Handle side effects before paint | `undefined` | DOM measurements, preventing visual flicker |
| **useMemo** | Memoize expensive calculations | `memoizedValue` | Expensive computations, derived state |
| **useCallback** | Memoize function references | `memoizedCallback` | Event handlers, preventing child re-renders |
| **useRef** | Access DOM elements or store mutable values | `{ current: value }` | DOM manipulation, timers, previous values |
| **useContext** | Access context values | `contextValue` | Theme, user data, global state |
| **createContext** | Create context for sharing data | `Context` | Provider setup, avoiding prop drilling |
| **useImperativeHandle** | Expose imperative API to parent | `undefined` | Focus management, custom refs |
| **useId** | Generate unique IDs | `string` | Accessibility, form labels, SSR |
| **useSyncExternalStore** | Subscribe to external stores | `snapshot` | Browser APIs, third-party state |
| **useTransition** | Mark updates as non-urgent | `[isPending, startTransition]` | Expensive updates, search filtering |
| **useDeferredValue** | Defer value updates | `deferredValue` | Search input, large lists |
| **useInsertionEffect** | Insert styles before layout | `undefined` | CSS-in-JS libraries, dynamic styles |
| **useDebugValue** | Display custom hook values in DevTools | `undefined` | Custom hook debugging |

**Detailed Hook Categories:**

**State Management Hooks:**
```typescript
// useState - Simple state
const [count, setCount] = useState(0);

// useReducer - Complex state
const [state, dispatch] = useReducer(reducer, initialState);
```

**Effect Hooks:**
```typescript
// useEffect - Side effects after render
useEffect(() => {
  fetchData();
}, [dependency]);

// useLayoutEffect - Side effects before paint
useLayoutEffect(() => {
  measureElement();
}, []);
```

**Performance Hooks:**
```typescript
// useMemo - Memoize calculations
const expensiveValue = useMemo(() => 
  computeExpensiveValue(a, b), [a, b]
);

// useCallback - Memoize functions
const handleClick = useCallback(() => {
  doSomething();
}, [dependency]);
```

**Ref Hooks:**
```typescript
// useRef - DOM access or mutable values
const inputRef = useRef<HTMLInputElement>(null);
const previousValue = useRef(value);

// useImperativeHandle - Custom ref API
useImperativeHandle(ref, () => ({
  focus: () => inputRef.current?.focus()
}));
```

**Context Hooks:**
```typescript
// createContext - Create context
const ThemeContext = createContext('light');

// useContext - Use context
const theme = useContext(ThemeContext);
```

**Concurrent Features (React 18+):**
```typescript
// useTransition - Non-urgent updates
const [isPending, startTransition] = useTransition();

// useDeferredValue - Defer value updates
const deferredQuery = useDeferredValue(query);
```

**Utility Hooks:**
```typescript
// useId - Unique IDs
const id = useId();

// useSyncExternalStore - External store subscription
const snapshot = useSyncExternalStore(subscribe, getSnapshot);

// useInsertionEffect - Style insertion
useInsertionEffect(() => {
  insertStyles();
});

// useDebugValue - DevTools debugging
useDebugValue(value, format);
```

**Hook Rules Summary:**
1. Only call hooks at the top level
2. Only call hooks from React functions
3. Use exhaustive-deps ESLint rule
4. Prefer custom hooks for reusable logic

**When to Use Each Hook:**
- **useState**: Simple, independent state values
- **useReducer**: Complex state with multiple related values
- **useEffect**: Data fetching, subscriptions, cleanup
- **useLayoutEffect**: DOM measurements, preventing flicker
- **useMemo**: Expensive calculations that depend on specific values
- **useCallback**: Functions passed to child components
- **useRef**: DOM access, storing mutable values, previous values
- **useContext**: Accessing shared data without prop drilling
- **useTransition**: Marking expensive updates as non-urgent
- **useDeferredValue**: Deferring expensive value updates

### 4.15. How do you use refs for DOM interaction in React? What are the different types of refs?

**Answer:**

Refs provide a way to access DOM elements or component instances directly. They're essential for DOM manipulation, focus management, and integrating with third-party libraries.

**Types of Refs:**

**1. useRef Hook (Most Common):**

```typescript
function TextInput() {
  const inputRef = useRef<HTMLInputElement>(null);
  const [value, setValue] = useState('');

  const focusInput = () => {
    inputRef.current?.focus();
  };

  const selectAll = () => {
    inputRef.current?.select();
  };

  return (
    <div>
      <input
        ref={inputRef}
        value={value}
        onChange={(e) => setValue(e.target.value)}
        placeholder="Type something..."
      />
      <button onClick={focusInput}>Focus Input</button>
      <button onClick={selectAll}>Select All</button>
    </div>
  );
}
```

**2. Callback Refs:**

```typescript
function CallbackRefExample() {
  const [inputElement, setInputElement] = useState<HTMLInputElement | null>(null);

  const inputRef = useCallback((node: HTMLInputElement | null) => {
    if (node) {
      setInputElement(node);
      node.focus(); // Auto-focus when element is created
    }
  }, []);

  const measureElement = () => {
    if (inputElement) {
      const rect = inputElement.getBoundingClientRect();
      console.log('Input dimensions:', rect);
    }
  };

  return (
    <div>
      <input ref={inputRef} placeholder="Auto-focused input" />
      <button onClick={measureElement}>Measure Input</button>
    </div>
  );
}
```

**3. String Refs (Legacy - Don't Use):**

```typescript
// DON'T USE - Legacy pattern
class LegacyComponent extends Component {
  render() {
    return <input ref="myInput" />;
  }
  
  componentDidMount() {
    this.refs.myInput.focus(); // Deprecated
  }
}
```

**DOM Manipulation Examples:**

**Measuring Elements:**

```typescript
function MeasurableComponent() {
  const [dimensions, setDimensions] = useState({ width: 0, height: 0 });
  const elementRef = useRef<HTMLDivElement>(null);

  const measureElement = useCallback(() => {
    if (elementRef.current) {
      const rect = elementRef.current.getBoundingClientRect();
      setDimensions({
        width: rect.width,
        height: rect.height
      });
    }
  }, []);

  useEffect(() => {
    measureElement();
    window.addEventListener('resize', measureElement);
    
    return () => window.removeEventListener('resize', measureElement);
  }, [measureElement]);

  return (
    <div>
      <div
        ref={elementRef}
        style={{
          width: '200px',
          height: '100px',
          background: 'lightblue',
          margin: '20px'
        }}
      >
        Measurable content
      </div>
      <p>Width: {dimensions.width}px, Height: {dimensions.height}px</p>
      <button onClick={measureElement}>Re-measure</button>
    </div>
  );
}
```

**Scroll Management:**

```typescript
function ScrollableList() {
  const listRef = useRef<HTMLDivElement>(null);
  const [items] = useState(Array.from({ length: 100 }, (_, i) => `Item ${i + 1}`));

  const scrollToTop = () => {
    listRef.current?.scrollTo({ top: 0, behavior: 'smooth' });
  };

  const scrollToBottom = () => {
    if (listRef.current) {
      listRef.current.scrollTo({
        top: listRef.current.scrollHeight,
        behavior: 'smooth'
      });
    }
  };

  const scrollToItem = (index: number) => {
    const itemElement = listRef.current?.children[index] as HTMLElement;
    if (itemElement) {
      itemElement.scrollIntoView({ behavior: 'smooth', block: 'center' });
    }
  };

  return (
    <div>
      <div style={{ marginBottom: '10px' }}>
        <button onClick={scrollToTop}>Scroll to Top</button>
        <button onClick={scrollToBottom}>Scroll to Bottom</button>
        <button onClick={() => scrollToItem(50)}>Scroll to Item 50</button>
      </div>
      
      <div
        ref={listRef}
        style={{
          height: '300px',
          overflow: 'auto',
          border: '1px solid #ccc',
          padding: '10px'
        }}
      >
        {items.map((item, index) => (
          <div key={index} style={{ padding: '5px', borderBottom: '1px solid #eee' }}>
            {item}
          </div>
        ))}
      </div>
    </div>
  );
}
```

**Focus Management:**

```typescript
function FocusManager() {
  const firstInputRef = useRef<HTMLInputElement>(null);
  const secondInputRef = useRef<HTMLInputElement>(null);
  const buttonRef = useRef<HTMLButtonElement>(null);

  const handleKeyDown = (e: React.KeyboardEvent, nextRef: React.RefObject<HTMLElement>) => {
    if (e.key === 'Enter' || e.key === 'Tab') {
      e.preventDefault();
      nextRef.current?.focus();
    }
  };

  return (
    <div>
      <input
        ref={firstInputRef}
        placeholder="First input (press Enter to go to next)"
        onKeyDown={(e) => handleKeyDown(e, secondInputRef)}
      />
      <input
        ref={secondInputRef}
        placeholder="Second input (press Enter to go to button)"
        onKeyDown={(e) => handleKeyDown(e, buttonRef)}
      />
      <button
        ref={buttonRef}
        onClick={() => firstInputRef.current?.focus()}
      >
        Back to First Input
      </button>
    </div>
  );
}
```

**Custom Hook for DOM Measurements:**

```typescript
function useElementSize<T extends HTMLElement = HTMLDivElement>() {
  const ref = useRef<T>(null);
  const [size, setSize] = useState({ width: 0, height: 0 });

  useEffect(() => {
    const element = ref.current;
    if (!element) return;

    const resizeObserver = new ResizeObserver((entries) => {
      for (const entry of entries) {
        const { width, height } = entry.contentRect;
        setSize({ width, height });
      }
    });

    resizeObserver.observe(element);

    return () => {
      resizeObserver.disconnect();
    };
  }, []);

  return { ref, size };
}

// Usage
function ResizableComponent() {
  const { ref, size } = useElementSize<HTMLDivElement>();

  return (
    <div>
      <div
        ref={ref}
        style={{
          width: '100%',
          minHeight: '100px',
          background: 'lightgreen',
          padding: '20px'
        }}
      >
        This element is {size.width}px wide and {size.height}px tall
      </div>
    </div>
  );
}
```

**Refs with Third-party Libraries:**

```typescript
function ChartComponent() {
  const chartRef = useRef<HTMLCanvasElement>(null);
  const chartInstance = useRef<Chart | null>(null);

  useEffect(() => {
    if (chartRef.current && !chartInstance.current) {
      // Initialize chart library
      chartInstance.current = new Chart(chartRef.current, {
        type: 'line',
        data: {
          labels: ['Jan', 'Feb', 'Mar', 'Apr'],
          datasets: [{
            label: 'Sales',
            data: [12, 19, 3, 5],
            borderColor: 'rgb(75, 192, 192)',
          }]
        }
      });
    }

    return () => {
      if (chartInstance.current) {
        chartInstance.current.destroy();
        chartInstance.current = null;
      }
    };
  }, []);

  const updateChart = (newData: number[]) => {
    if (chartInstance.current) {
      chartInstance.current.data.datasets[0].data = newData;
      chartInstance.current.update();
    }
  };

  return (
    <div>
      <canvas ref={chartRef} width={400} height={200} />
      <button onClick={() => updateChart([1, 2, 3, 4])}>
        Update Chart
      </button>
    </div>
  );
}
```

**Ref Best Practices:**

1. **Use useRef for DOM access** - Most common pattern
2. **Use callback refs for dynamic refs** - When ref target changes
3. **Always check if ref.current exists** - Use optional chaining
4. **Clean up third-party library instances** - In useEffect cleanup
5. **Don't use refs for data flow** - Use state and props instead
6. **Use forwardRef for component refs** - When passing refs to child components

```typescript
// forwardRef example
const FancyInput = forwardRef<HTMLInputElement, { placeholder: string }>(
  ({ placeholder }, ref) => {
    return (
      <input
        ref={ref}
        placeholder={placeholder}
        style={{
          border: '2px solid #007bff',
          borderRadius: '4px',
          padding: '8px'
        }}
      />
    );
  }
);

// Usage
function ParentComponent() {
  const inputRef = useRef<HTMLInputElement>(null);

  const focusInput = () => {
    inputRef.current?.focus();
  };

  return (
    <div>
      <FancyInput ref={inputRef} placeholder="Fancy input" />
      <button onClick={focusInput}>Focus Input</button>
    </div>
  );
}
```

### 4.16. What are the new features in React 19? How do they improve developer experience and performance?

React 19 introduces several significant features that enhance both developer experience and application performance.

**New Features:**

1. **React Compiler:**
```javascript
// Automatic memoization - no need for useMemo/useCallback
function ExpensiveComponent({ items, filter }) {
  // React Compiler automatically optimizes this
  const filteredItems = items.filter(item => item.category === filter);
  const expensiveValue = filteredItems.reduce((sum, item) => sum + item.value, 0);
  
  return <div>{expensiveValue}</div>;
}

// Before React 19, you'd need:
function ExpensiveComponentOld({ items, filter }) {
  const filteredItems = useMemo(() => 
    items.filter(item => item.category === filter), [items, filter]
  );
  const expensiveValue = useMemo(() => 
    filteredItems.reduce((sum, item) => sum + item.value, 0), [filteredItems]
  );
  
  return <div>{expensiveValue}</div>;
}
```

2. **Actions and useActionState:**
```javascript
import { useActionState } from 'react';

// Server actions with built-in state management
async function updateUser(prevState, formData) {
  try {
    const result = await fetch('/api/users', {
      method: 'POST',
      body: formData
    });
    
    if (!result.ok) {
      return { error: 'Failed to update user' };
    }
    
    return { success: true, user: await result.json() };
  } catch (error) {
    return { error: error.message };
  }
}

function UserForm() {
  const [state, formAction, isPending] = useActionState(updateUser, {});
  
  return (
    <form action={formAction}>
      <input name="name" required />
      <button disabled={isPending}>
        {isPending ? 'Updating...' : 'Update User'}
      </button>
      {state.error && <div className="error">{state.error}</div>}
      {state.success && <div className="success">User updated!</div>}
    </form>
  );
}
```

3. **use() Hook:**
```javascript
import { use } from 'react';

function UserProfile({ userPromise }) {
  // Can unwrap promises directly
  const user = use(userPromise);
  
  return (
    <div>
      <h1>{user.name}</h1>
      <p>{user.email}</p>
    </div>
  );
}

// Usage with async data
function App() {
  const userPromise = fetch('/api/user/123').then(res => res.json());
  
  return (
    <Suspense fallback={<div>Loading...</div>}>
      <UserProfile userPromise={userPromise} />
    </Suspense>
  );
}
```

4. **Document Metadata:**
```javascript
import { Title, Meta, Link } from 'react';

function BlogPost({ post }) {
  return (
    <>
      <Title>{post.title}</Title>
      <Meta name="description" content={post.excerpt} />
      <Meta property="og:title" content={post.title} />
      <Link rel="canonical" href={`/posts/${post.slug}`} />
      
      <article>
        <h1>{post.title}</h1>
        <div dangerouslySetInnerHTML={{ __html: post.content }} />
      </article>
    </>
  );
}
```

5. **Ref as Prop:**
```javascript
// ref can now be passed as a regular prop
function MyInput({ ref, ...props }) {
  return <input ref={ref} {...props} />;
}

function Form() {
  const inputRef = useRef(null);
  
  return (
    <form>
      <MyInput ref={inputRef} placeholder="Enter text..." />
      <button onClick={() => inputRef.current?.focus()}>
        Focus Input
      </button>
    </form>
  );
}
```

**Performance Improvements:**
- Automatic memoization reduces unnecessary re-renders
- Better tree-shaking and bundle optimization
- Improved hydration performance
- Enhanced concurrent features

### 4.17. How do you use React DevTools for debugging and performance optimization?

React DevTools is an essential browser extension for debugging React applications.

**Installation and Setup:**
```javascript
// Install via browser extension store
// Chrome: React Developer Tools
// Firefox: React Developer Tools

// For development, you can also use the standalone version
npm install -g react-devtools
react-devtools
```

**Component Inspection:**
```javascript
// Components tab shows the component tree
function App() {
  const [count, setCount] = useState(0);
  const [users, setUsers] = useState([]);
  
  return (
    <div>
      <Counter count={count} onIncrement={() => setCount(c => c + 1)} />
      <UserList users={users} />
    </div>
  );
}

// In DevTools:
// - Inspect component props and state
// - Edit props/state in real-time
// - View component hierarchy
// - Check component render count
```

**Profiler Usage:**
```javascript
import { Profiler } from 'react';

function onRenderCallback(id, phase, actualDuration, baseDuration, startTime, commitTime) {
  console.log('Component:', id);
  console.log('Phase:', phase); // mount or update
  console.log('Actual duration:', actualDuration);
  console.log('Base duration:', baseDuration);
}

function App() {
  return (
    <Profiler id="App" onRender={onRenderCallback}>
      <ExpensiveComponent />
    </Profiler>
  );
}

// Profiler tab in DevTools:
// - Record performance sessions
// - Identify slow components
// - Analyze render times
// - Find unnecessary re-renders
```

**Debugging Techniques:**
```javascript
// 1. Component state debugging
function UserProfile({ userId }) {
  const [user, setUser] = useState(null);
  const [loading, setLoading] = useState(true);
  
  useEffect(() => {
    fetchUser(userId).then(userData => {
      setUser(userData);
      setLoading(false);
    });
  }, [userId]);
  
  // DevTools shows state changes in real-time
  return loading ? <div>Loading...</div> : <div>{user.name}</div>;
}

// 2. Props debugging
function Button({ onClick, children, disabled, ...props }) {
  // DevTools shows all props including spread props
  return (
    <button onClick={onClick} disabled={disabled} {...props}>
      {children}
    </button>
  );
}

// 3. Context debugging
const ThemeContext = createContext();

function ThemeProvider({ children }) {
  const [theme, setTheme] = useState('light');
  
  // DevTools shows context value and consumers
  return (
    <ThemeContext.Provider value={{ theme, setTheme }}>
      {children}
    </ThemeContext.Provider>
  );
}
```

**Performance Optimization:**
```javascript
// 1. Identify unnecessary re-renders
function ExpensiveComponent({ data, filter }) {
  // DevTools Profiler shows this re-renders on every parent update
  const processedData = useMemo(() => {
    return data.filter(item => item.category === filter);
  }, [data, filter]);
  
  return <div>{processedData.length} items</div>;
}

// 2. Debug memoization issues
const MemoizedComponent = React.memo(function MyComponent({ name, age }) {
  return <div>{name} is {age} years old</div>;
});

// DevTools shows when memoization works/fails
function Parent() {
  const [count, setCount] = useState(0);
  const [user, setUser] = useState({ name: 'John', age: 30 });
  
  return (
    <div>
      <button onClick={() => setCount(c => c + 1)}>Count: {count}</button>
      <MemoizedComponent name={user.name} age={user.age} />
    </div>
  );
}
```

### 4.18. How do you analyze and optimize React bundle size? What tools and techniques do you use?

Bundle analysis is crucial for optimizing React application performance and loading times.

**Bundle Analysis Tools:**

1. **Webpack Bundle Analyzer:**
```bash
# Install
npm install --save-dev webpack-bundle-analyzer

# Add to webpack.config.js
const BundleAnalyzerPlugin = require('webpack-bundle-analyzer').BundleAnalyzerPlugin;

module.exports = {
  plugins: [
    new BundleAnalyzerPlugin({
      analyzerMode: 'server',
      openAnalyzer: true,
    })
  ]
};

# Or use with Create React App
npm install --save-dev webpack-bundle-analyzer
npx webpack-bundle-analyzer build/static/js/*.js
```

2. **Source Map Explorer:**
```bash
# Install
npm install --save-dev source-map-explorer

# Analyze build
npx source-map-explorer 'build/static/js/*.js'
```

3. **Bundlephobia:**
```bash
# Check package sizes before installing
npx bundlephobia lodash
npx bundlephobia react-router-dom
```

**Code Splitting Strategies:**
```javascript
// 1. Route-based splitting
import { lazy, Suspense } from 'react';
import { BrowserRouter, Routes, Route } from 'react-router-dom';

const Home = lazy(() => import('./pages/Home'));
const About = lazy(() => import('./pages/About'));
const Contact = lazy(() => import('./pages/Contact'));

function App() {
  return (
    <BrowserRouter>
      <Suspense fallback={<div>Loading...</div>}>
        <Routes>
          <Route path="/" element={<Home />} />
          <Route path="/about" element={<About />} />
          <Route path="/contact" element={<Contact />} />
        </Routes>
      </Suspense>
    </BrowserRouter>
  );
}

// 2. Component-based splitting
const HeavyChart = lazy(() => import('./components/HeavyChart'));
const DataTable = lazy(() => import('./components/DataTable'));

function Dashboard() {
  const [showChart, setShowChart] = useState(false);
  
  return (
    <div>
      <button onClick={() => setShowChart(true)}>Show Chart</button>
      {showChart && (
        <Suspense fallback={<div>Loading chart...</div>}>
          <HeavyChart />
        </Suspense>
      )}
    </div>
  );
}

// 3. Library splitting
const loadMoment = () => import('moment');
const loadChart = () => import('chart.js');

async function handleExport() {
  const moment = await loadMoment();
  const chart = await loadChart();
  // Use libraries
}
```

**Bundle Optimization Techniques:**
```javascript
// 1. Tree shaking
// ✅ Good - only imports what you need
import { debounce } from 'lodash-es';
import { format } from 'date-fns';

// ❌ Bad - imports entire library
import _ from 'lodash';
import * as dateFns from 'date-fns';

// 2. Dynamic imports for large libraries
async function loadPDFLibrary() {
  const { PDFDocument } = await import('pdf-lib');
  return PDFDocument;
}

// 3. Vendor chunk splitting
// webpack.config.js
module.exports = {
  optimization: {
    splitChunks: {
      chunks: 'all',
      cacheGroups: {
        vendor: {
          test: /[\\/]node_modules[\\/]/,
          name: 'vendors',
          chunks: 'all',
        },
        react: {
          test: /[\\/]node_modules[\\/](react|react-dom)[\\/]/,
          name: 'react',
          chunks: 'all',
        }
      }
    }
  }
};
```

**Performance Monitoring:**
```javascript
// 1. Bundle size monitoring
// package.json
{
  "scripts": {
    "analyze": "npm run build && npx webpack-bundle-analyzer build/static/js/*.js",
    "size-limit": "size-limit"
  }
}

// 2. Runtime performance monitoring
import { getCLS, getFID, getFCP, getLCP, getTTFB } from 'web-vitals';

function sendToAnalytics(metric) {
  // Send to your analytics service
  console.log(metric);
}

getCLS(sendToAnalytics);
getFID(sendToAnalytics);
getFCP(sendToAnalytics);
getLCP(sendToAnalytics);
getTTFB(sendToAnalytics);

// 3. Bundle size tracking in CI
// .github/workflows/bundle-size.yml
name: Bundle Size
on: [pull_request]
jobs:
  bundle-size:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v2
      - uses: actions/setup-node@v2
      - run: npm ci
      - run: npm run build
      - uses: preactjs/compressed-size-action@v2
        with:
          repo-token: ${{ secrets.GITHUB_TOKEN }}
          pattern: './build/static/js/*.js'
```

### 4.19. What are the key security considerations when building React applications? How do you prevent common vulnerabilities?

React applications face various security challenges that developers must address.

**XSS Prevention:**
```javascript
// 1. Sanitize user input
import DOMPurify from 'dompurify';

function UserComment({ comment }) {
  // ❌ Dangerous - can execute scripts
  // return <div dangerouslySetInnerHTML={{ __html: comment }} />;
  
  // ✅ Safe - sanitize HTML
  const cleanHTML = DOMPurify.sanitize(comment);
  return <div dangerouslySetInnerHTML={{ __html: cleanHTML }} />;
}

// 2. Use textContent instead of innerHTML
function UserName({ name }) {
  // ✅ Safe - automatically escapes HTML
  return <div>{name}</div>;
  
  // ❌ Dangerous if name contains HTML
  // return <div dangerouslySetInnerHTML={{ __html: name }} />;
}

// 3. Validate and escape props
function Link({ href, children }) {
  // Validate URL to prevent javascript: protocol
  const isValidUrl = (url) => {
    try {
      const urlObj = new URL(url);
      return ['http:', 'https:'].includes(urlObj.protocol);
    } catch {
      return false;
    }
  };
  
  if (!isValidUrl(href)) {
    throw new Error('Invalid URL provided');
  }
  
  return <a href={href}>{children}</a>;
}
```

**CSRF Protection:**
```javascript
// 1. Include CSRF tokens in requests
function useCSRFToken() {
  const [token, setToken] = useState(null);
  
  useEffect(() => {
    // Get CSRF token from meta tag or API
    const csrfToken = document.querySelector('meta[name="csrf-token"]')?.content;
    setToken(csrfToken);
  }, []);
  
  return token;
}

function UserForm() {
  const csrfToken = useCSRFToken();
  
  const handleSubmit = async (formData) => {
    await fetch('/api/users', {
      method: 'POST',
      headers: {
        'Content-Type': 'application/json',
        'X-CSRF-Token': csrfToken
      },
      body: JSON.stringify(formData)
    });
  };
  
  return <form onSubmit={handleSubmit}>...</form>;
}

// 2. Use SameSite cookies
// Server-side: Set SameSite=Strict on cookies
// res.cookie('session', sessionId, { sameSite: 'strict' });
```

**Authentication Security:**
```javascript
// 1. Secure token storage
class AuthService {
  static setToken(token) {
    // ✅ Store in httpOnly cookie (server-side)
    // ✅ Or use secure storage for client-side
    sessionStorage.setItem('token', token); // Temporary storage
  }
  
  static getToken() {
    return sessionStorage.getItem('token');
  }
  
  static removeToken() {
    sessionStorage.removeItem('token');
  }
  
  static isTokenExpired(token) {
    try {
      const payload = JSON.parse(atob(token.split('.')[1]));
      return Date.now() >= payload.exp * 1000;
    } catch {
      return true;
    }
  }
}

// 2. Protected routes with token validation
function ProtectedRoute({ children }) {
  const [isAuthenticated, setIsAuthenticated] = useState(false);
  const [loading, setLoading] = useState(true);
  
  useEffect(() => {
    const token = AuthService.getToken();
    if (token && !AuthService.isTokenExpired(token)) {
      setIsAuthenticated(true);
    }
    setLoading(false);
  }, []);
  
  if (loading) return <div>Loading...</div>;
  if (!isAuthenticated) return <Navigate to="/login" />;
  
  return children;
}
```

**Content Security Policy (CSP):**
```html
<!-- index.html -->
<meta http-equiv="Content-Security-Policy" 
      content="default-src 'self'; 
               script-src 'self' 'unsafe-inline' https://cdn.example.com; 
               style-src 'self' 'unsafe-inline'; 
               img-src 'self' data: https:; 
               connect-src 'self' https://api.example.com;">
```

```javascript
// 1. Nonce-based CSP
function App() {
  const nonce = useMemo(() => {
    return btoa(Math.random().toString()).substring(0, 16);
  }, []);
  
  useEffect(() => {
    // Add nonce to dynamically created scripts
    const script = document.createElement('script');
    script.nonce = nonce;
    script.src = '/dynamic-script.js';
    document.head.appendChild(script);
  }, [nonce]);
  
  return <div>App content</div>;
}

// 2. Report CSP violations
// Add to CSP header: report-uri /csp-report
```

**Environment Security:**
```javascript
// 1. Secure environment variables
// ✅ Only expose necessary variables to client
const config = {
  apiUrl: process.env.REACT_APP_API_URL,
  // ❌ Never expose secrets
  // secretKey: process.env.SECRET_KEY // This would be undefined in client
};

// 2. Validate environment in production
function validateEnvironment() {
  const requiredVars = ['REACT_APP_API_URL'];
  
  for (const varName of requiredVars) {
    if (!process.env[varName]) {
      throw new Error(`Missing required environment variable: ${varName}`);
    }
  }
}

// 3. Use different configs for different environments
const getConfig = () => {
  switch (process.env.NODE_ENV) {
    case 'development':
      return { apiUrl: 'http://localhost:3001' };
    case 'production':
      return { apiUrl: 'https://api.myapp.com' };
    default:
      throw new Error('Unknown environment');
  }
};
```

**Dependency Security:**
```bash
# 1. Audit dependencies regularly
npm audit
npm audit fix

# 2. Use tools like Snyk
npm install -g snyk
snyk test
snyk monitor

# 3. Keep dependencies updated
npm update
npm outdated
```

**Secure Development Practices:**
```javascript
// 1. Input validation
function validateEmail(email) {
  const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
  return emailRegex.test(email);
}

function validatePassword(password) {
  return password.length >= 8 && 
         /[A-Z]/.test(password) && 
         /[a-z]/.test(password) && 
         /\d/.test(password);
}

// 2. Rate limiting on client side
class RateLimiter {
  constructor(maxRequests, windowMs) {
    this.maxRequests = maxRequests;
    this.windowMs = windowMs;
    this.requests = [];
  }
  
  isAllowed() {
    const now = Date.now();
    this.requests = this.requests.filter(time => now - time < this.windowMs);
    
    if (this.requests.length >= this.maxRequests) {
      return false;
    }
    
    this.requests.push(now);
    return true;
  }
}

const apiRateLimiter = new RateLimiter(10, 60000); // 10 requests per minute

async function makeAPICall() {
  if (!apiRateLimiter.isAllowed()) {
    throw new Error('Rate limit exceeded');
  }
  
  return fetch('/api/data');
}
```

### 4.20. Compare Webpack and Vite for React development. What are the advantages and disadvantages of each?

Webpack and Vite are both popular build tools for React applications, but they have different approaches to bundling and development.

**Webpack Overview:**
Webpack is a mature, feature-rich module bundler that processes all modules and creates dependency graphs.

**Vite Overview:**
Vite is a modern build tool that uses native ES modules during development and Rollup for production builds.

**Key Differences:**

| Feature | Webpack | Vite |
|---------|---------|------|
| Development Server | Bundles everything | Native ES modules |
| Hot Module Replacement | Full bundle reload | Native HMR |
| Build Speed | Slower (bundles everything) | Faster (uses Rollup) |
| Configuration | Complex, highly configurable | Simple, opinionated |
| Plugin Ecosystem | Mature, extensive | Growing, modern |
| Bundle Size | Larger | Smaller (better tree-shaking) |
| Learning Curve | Steep | Gentle |

**Webpack Advantages:**
```javascript
// 1. Extensive plugin ecosystem
const webpack = require('webpack');
const HtmlWebpackPlugin = require('html-webpack-plugin');
const MiniCssExtractPlugin = require('mini-css-extract-plugin');

module.exports = {
  plugins: [
    new HtmlWebpackPlugin({
      template: './src/index.html'
    }),
    new MiniCssExtractPlugin({
      filename: '[name].[contenthash].css'
    }),
    new webpack.DefinePlugin({
      'process.env.NODE_ENV': JSON.stringify('production')
    })
  ],
  module: {
    rules: [
      {
        test: /\.jsx?$/,
        use: 'babel-loader',
        exclude: /node_modules/
      },
      {
        test: /\.css$/,
        use: [MiniCssExtractPlugin.loader, 'css-loader']
      }
    ]
  }
};

// 2. Advanced code splitting
module.exports = {
  optimization: {
    splitChunks: {
      chunks: 'all',
      cacheGroups: {
        vendor: {
          test: /[\\/]node_modules[\\/]/,
          name: 'vendors',
          chunks: 'all'
        },
        common: {
          name: 'common',
          minChunks: 2,
          chunks: 'all',
          enforce: true
        }
      }
    }
  }
};

// 3. Custom loaders and plugins
const customLoader = {
  test: /\.custom$/,
  use: {
    loader: path.resolve('./custom-loader.js'),
    options: {
      customOption: true
    }
  }
};
```

**Vite Advantages:**
```javascript
// 1. Lightning-fast development server
// vite.config.js
import { defineConfig } from 'vite';
import react from '@vitejs/plugin-react';

export default defineConfig({
  plugins: [react()],
  server: {
    port: 3000,
    open: true
  },
  build: {
    outDir: 'dist',
    sourcemap: true
  }
});

// 2. Native ES modules in development
// No bundling during development - browser loads modules directly
import React from 'react';
import { useState } from 'react';
import MyComponent from './MyComponent.jsx';

// 3. Built-in optimizations
export default defineConfig({
  build: {
    rollupOptions: {
      output: {
        manualChunks: {
          vendor: ['react', 'react-dom'],
          utils: ['lodash', 'date-fns']
        }
      }
    }
  }
});
```

**Development Experience Comparison:**

**Webpack Development:**
```javascript
// webpack.config.js - Development configuration
module.exports = {
  mode: 'development',
  devtool: 'eval-source-map',
  devServer: {
    contentBase: './dist',
    hot: true,
    port: 3000,
    historyApiFallback: true
  },
  module: {
    rules: [
      {
        test: /\.jsx?$/,
        use: {
          loader: 'babel-loader',
          options: {
            presets: ['@babel/preset-env', '@babel/preset-react']
          }
        }
      }
    ]
  }
};

// Slower startup time - bundles everything
// npm start -> 10-30 seconds for large apps
```

**Vite Development:**
```javascript
// vite.config.js - Much simpler configuration
import { defineConfig } from 'vite';
import react from '@vitejs/plugin-react';

export default defineConfig({
  plugins: [react()],
  server: {
    port: 3000,
    hmr: true
  }
});

// Faster startup time - no bundling
// npm run dev -> 1-3 seconds for any app size
```

**Production Build Comparison:**

**Webpack Production:**
```javascript
// webpack.prod.js
module.exports = {
  mode: 'production',
  optimization: {
    minimize: true,
    splitChunks: {
      chunks: 'all',
      cacheGroups: {
        vendor: {
          test: /[\\/]node_modules[\\/]/,
          name: 'vendors',
          chunks: 'all'
        }
      }
    }
  },
  plugins: [
    new MiniCssExtractPlugin({
      filename: '[name].[contenthash].css'
    }),
    new webpack.DefinePlugin({
      'process.env.NODE_ENV': JSON.stringify('production')
    })
  ]
};

// Build time: 30-60 seconds for large apps
// Bundle size: Larger due to webpack overhead
```

**Vite Production:**
```javascript
// vite.config.js
export default defineConfig({
  build: {
    minify: 'terser',
    rollupOptions: {
      output: {
        manualChunks: {
          vendor: ['react', 'react-dom']
        }
      }
    }
  }
});

// Build time: 10-20 seconds for large apps
// Bundle size: Smaller, better tree-shaking
```

**When to Choose Webpack:**

1. **Complex Build Requirements:**
```javascript
// Custom webpack configurations
module.exports = {
  module: {
    rules: [
      {
        test: /\.worker\.js$/,
        use: { loader: 'worker-loader' }
      },
      {
        test: /\.wasm$/,
        type: 'webassembly/async'
      }
    ]
  }
};
```

2. **Legacy Browser Support:**
```javascript
// Extensive polyfill support
module.exports = {
  entry: ['core-js/stable', './src/index.js'],
  module: {
    rules: [
      {
        test: /\.js$/,
        use: {
          loader: 'babel-loader',
          options: {
            presets: [
              ['@babel/preset-env', {
                targets: {
                  browsers: ['> 1%', 'last 2 versions', 'ie >= 11']
                }
              }]
            ]
          }
        }
      }
    ]
  }
};
```

3. **Micro-frontend Architecture:**
```javascript
// Module Federation
const ModuleFederationPlugin = require('@module-federation/webpack');

module.exports = {
  plugins: [
    new ModuleFederationPlugin({
      name: 'shell',
      remotes: {
        mfe1: 'mfe1@http://localhost:3001/remoteEntry.js',
        mfe2: 'mfe2@http://localhost:3002/remoteEntry.js'
      }
    })
  ]
};
```

**When to Choose Vite:**

1. **Modern Development:**
```javascript
// Simple, fast development
// vite.config.js
export default defineConfig({
  plugins: [react()],
  server: {
    port: 3000
  }
});

// Instant server start
// Fast HMR
// Native ES modules
```

2. **Small to Medium Projects:**
```javascript
// Minimal configuration needed
// Built-in optimizations
// Great for React, Vue, Svelte
```

3. **Performance-Critical Applications:**
```javascript
// Faster builds
// Smaller bundle sizes
// Better tree-shaking
// Modern browser support
```

**Migration Considerations:**

**From Webpack to Vite:**
```javascript
// 1. Update package.json
{
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview"
  },
  "devDependencies": {
    "vite": "^4.0.0",
    "@vitejs/plugin-react": "^3.0.0"
  }
}

// 2. Create vite.config.js
import { defineConfig } from 'vite';
import react from '@vitejs/plugin-react';

export default defineConfig({
  plugins: [react()],
  resolve: {
    alias: {
      '@': path.resolve(__dirname, './src')
    }
  }
});

// 3. Update imports (if needed)
// Change .jsx extensions to .jsx or configure resolve.extensions
```

**Summary:**

**Choose Webpack when:**
- You need extensive customization
- Working with legacy browsers
- Building micro-frontends
- You have complex build requirements
- Your team is already familiar with webpack

**Choose Vite when:**
- You want fast development experience
- Building modern applications
- You prefer minimal configuration
- Performance is critical
- You're starting a new project

**Recommendation:**
For new React projects, Vite is often the better choice due to its speed and simplicity. For existing projects with complex webpack configurations, the migration effort might not be worth it unless development speed is a major concern.

## 5. System Design & Architecture

### 5.1. How would you design a reusable, accessible component library? What principles would you follow?

**Answer:**

Designing a reusable, accessible component library requires careful consideration of multiple aspects:

#### 5.1.1. Core Design Principles

1. **Single Responsibility Principle**
   - Each component should have one clear purpose
   - Avoid components that try to do too many things
   - Example: Separate `Button` from `ButtonGroup`

2. **Composition over Configuration**
   - Prefer composition patterns over complex prop interfaces
   - Use render props, children, or compound components
   ```tsx
   // Good: Composable
   <Card>
     <Card.Header>Title</Card.Header>
     <Card.Body>Content</Card.Body>
     <Card.Footer>Actions</Card.Footer>
   </Card>
   
   // Avoid: Over-configured
   <Card 
     hasHeader={true} 
     headerText="Title" 
     hasFooter={true} 
     footerContent="Actions"
   />
   ```

3. **Consistent API Design**
   - Standardize prop naming conventions
   - Use consistent patterns across components
   - Example: `size`, `variant`, `disabled` props across all interactive components

#### 5.1.2. Accessibility (a11y) Principles

1. **Semantic HTML**
   ```tsx
   // Good: Semantic button
   <button 
     type="button" 
     aria-label="Close dialog"
     onClick={onClose}
   >
     <CloseIcon aria-hidden="true" />
   </button>
   ```

2. **Keyboard Navigation**
   - Ensure all interactive elements are keyboard accessible
   - Implement proper focus management
   - Use appropriate ARIA attributes

3. **Screen Reader Support**
   ```tsx
   const Modal = ({ isOpen, onClose, children }) => {
     const modalRef = useRef<HTMLDivElement>(null);
     
     useEffect(() => {
       if (isOpen && modalRef.current) {
         modalRef.current.focus();
       }
     }, [isOpen]);
     
     return (
       <div 
         role="dialog" 
         aria-modal="true"
         aria-labelledby="modal-title"
         ref={modalRef}
         tabIndex={-1}
       >
         {children}
       </div>
     );
   };
   ```

#### 5.1.3. TypeScript Integration

1. **Strong Typing**
   ```tsx
   interface ButtonProps {
     variant: 'primary' | 'secondary' | 'danger';
     size: 'small' | 'medium' | 'large';
     disabled?: boolean;
     loading?: boolean;
     children: React.ReactNode;
     onClick?: (event: React.MouseEvent<HTMLButtonElement>) => void;
   }
   
   const Button: React.FC<ButtonProps> = ({
     variant,
     size,
     disabled = false,
     loading = false,
     children,
     onClick,
     ...props
   }) => {
     // Implementation
   };
   ```

2. **Generic Components**
   ```tsx
   interface ListProps<T> {
     items: T[];
     renderItem: (item: T, index: number) => React.ReactNode;
     keyExtractor: (item: T) => string | number;
   }
   
   function List<T>({ items, renderItem, keyExtractor }: ListProps<T>) {
     return (
       <ul>
         {items.map((item, index) => (
           <li key={keyExtractor(item)}>
             {renderItem(item, index)}
           </li>
         ))}
       </ul>
     );
   }
   ```

#### 5.1.4. Styling Strategy

1. **CSS-in-JS with Theme Support**
   ```tsx
   const StyledButton = styled.button<ButtonProps>`
     padding: ${({ size, theme }) => theme.spacing[size]};
     background-color: ${({ variant, theme }) => theme.colors[variant]};
     border: none;
     border-radius: ${({ theme }) => theme.borderRadius.medium};
     
     &:disabled {
       opacity: 0.6;
       cursor: not-allowed;
     }
   `;
   ```

2. **CSS Custom Properties for Theming**
   ```css
   :root {
     --color-primary: #007bff;
     --color-secondary: #6c757d;
     --spacing-small: 8px;
     --spacing-medium: 16px;
   }
   ```

#### 5.1.5. Documentation & Testing

1. **Storybook Integration**
   - Document all component variants
   - Provide interactive examples
   - Include accessibility testing

2. **Comprehensive Testing**
   ```tsx
   describe('Button Component', () => {
     it('renders with correct accessibility attributes', () => {
       render(<Button aria-label="Test button">Click me</Button>);
       const button = screen.getByRole('button', { name: 'Test button' });
       expect(button).toBeInTheDocument();
     });
     
     it('handles keyboard navigation', () => {
       const handleClick = jest.fn();
       render(<Button onClick={handleClick}>Click me</Button>);
       const button = screen.getByRole('button');
       
       fireEvent.keyDown(button, { key: 'Enter' });
       expect(handleClick).toHaveBeenCalled();
     });
   });
   ```

#### 5.1.6. Performance Considerations

1. **Memoization**
   ```tsx
   const ExpensiveComponent = React.memo<Props>(({ data, onAction }) => {
     const processedData = useMemo(() => {
       return data.map(item => expensiveTransformation(item));
     }, [data]);
     
     return <div>{/* Render processed data */}</div>;
   });
   ```

2. **Lazy Loading**
   ```tsx
   const LazyModal = React.lazy(() => import('./Modal'));
   
   const App = () => (
     <Suspense fallback={<Spinner />}>
       <LazyModal />
     </Suspense>
   );
   ```

This approach ensures components are maintainable, accessible, performant, and provide a great developer experience.

### 5.2. Explain different strategies for code splitting in React. How would you implement route-based code splitting?

**Answer:**

Code splitting is a technique to split your code into smaller chunks that can be loaded on demand, improving initial load performance.

#### 5.2.1. Code Splitting Strategies

1. **Route-Based Code Splitting**
   ```tsx
   import { lazy, Suspense } from 'react';
   import { BrowserRouter, Routes, Route } from 'react-router-dom';
   
   // Lazy load route components
   const Home = lazy(() => import('./pages/Home'));
   const About = lazy(() => import('./pages/About'));
   const Contact = lazy(() => import('./pages/Contact'));
   const Dashboard = lazy(() => import('./pages/Dashboard'));
   
   const App = () => (
     <BrowserRouter>
       <Suspense fallback={<div>Loading...</div>}>
         <Routes>
           <Route path="/" element={<Home />} />
           <Route path="/about" element={<About />} />
           <Route path="/contact" element={<Contact />} />
           <Route path="/dashboard" element={<Dashboard />} />
         </Routes>
       </Suspense>
     </BrowserRouter>
   );
   ```

2. **Component-Based Code Splitting**
   ```tsx
   import { lazy, Suspense, useState } from 'react';
   
   const HeavyChart = lazy(() => import('./HeavyChart'));
   const DataTable = lazy(() => import('./DataTable'));
   
   const Dashboard = () => {
     const [showChart, setShowChart] = useState(false);
     const [showTable, setShowTable] = useState(false);
   
     return (
       <div>
         <button onClick={() => setShowChart(true)}>
           Load Chart
         </button>
         <button onClick={() => setShowTable(true)}>
           Load Table
         </button>
   
         {showChart && (
           <Suspense fallback={<div>Loading chart...</div>}>
             <HeavyChart />
           </Suspense>
         )}
   
         {showTable && (
           <Suspense fallback={<div>Loading table...</div>}>
             <DataTable />
           </Suspense>
         )}
       </div>
     );
   };
   ```

3. **Library-Based Code Splitting**
   ```tsx
   // Split large libraries
   const loadMoment = () => import('moment');
   const loadLodash = () => import('lodash');
   
   const DateFormatter = () => {
     const [moment, setMoment] = useState(null);
   
     useEffect(() => {
       loadMoment().then(({ default: moment }) => {
         setMoment(moment);
       });
     }, []);
   
     if (!moment) return <div>Loading date formatter...</div>;
   
     return <div>{moment().format('YYYY-MM-DD')}</div>;
   };
   ```

#### 5.2.2. Advanced Code Splitting Patterns

1. **Preloading with Intersection Observer**
   ```tsx
   const usePreloadOnIntersection = (importFn: () => Promise<any>) => {
     const [isLoaded, setIsLoaded] = useState(false);
     const ref = useRef<HTMLDivElement>(null);
   
     useEffect(() => {
       const observer = new IntersectionObserver(
         ([entry]) => {
           if (entry.isIntersecting && !isLoaded) {
             importFn().then(() => setIsLoaded(true));
             observer.disconnect();
           }
         },
         { threshold: 0.1 }
       );
   
       if (ref.current) {
         observer.observe(ref.current);
       }
   
       return () => observer.disconnect();
     }, [importFn, isLoaded]);
   
     return { ref, isLoaded };
   };
   
   const LazyComponent = () => {
     const { ref, isLoaded } = usePreloadOnIntersection(
       () => import('./HeavyComponent')
     );
   
     return (
       <div ref={ref}>
         {isLoaded ? (
           <Suspense fallback={<div>Loading...</div>}>
             <HeavyComponent />
           </Suspense>
         ) : (
           <div>Component will load when visible</div>
         )}
       </div>
     );
   };
   ```

2. **Dynamic Imports with Error Boundaries**
   ```tsx
   class ChunkLoadErrorBoundary extends React.Component {
     constructor(props) {
       super(props);
       this.state = { hasError: false, retryCount: 0 };
     }
   
     static getDerivedStateFromError(error) {
       if (error.name === 'ChunkLoadError') {
         return { hasError: true };
       }
       return null;
     }
   
     componentDidCatch(error, errorInfo) {
       if (error.name === 'ChunkLoadError') {
         console.error('Chunk load failed:', error);
       }
     }
   
     retry = () => {
       this.setState(prevState => ({
         hasError: false,
         retryCount: prevState.retryCount + 1
       }));
     };
   
     render() {
       if (this.state.hasError) {
         return (
           <div>
             <h2>Failed to load component</h2>
             <button onClick={this.retry}>
               Retry (Attempt {this.state.retryCount + 1})
             </button>
           </div>
         );
       }
   
       return this.props.children;
     }
   }
   
   const App = () => (
     <ChunkLoadErrorBoundary>
       <Suspense fallback={<div>Loading...</div>}>
         <Routes>
           <Route path="/dashboard" element={<Dashboard />} />
         </Routes>
       </Suspense>
     </ChunkLoadErrorBoundary>
   );
   ```

3. **Conditional Code Splitting**
   ```tsx
   const ConditionalComponent = ({ userRole }: { userRole: string }) => {
     const [AdminPanel, setAdminPanel] = useState<React.ComponentType | null>(null);
   
     useEffect(() => {
       if (userRole === 'admin') {
         import('./AdminPanel').then(({ default: AdminPanelComponent }) => {
           setAdminPanel(() => AdminPanelComponent);
         });
       }
     }, [userRole]);
   
     if (userRole === 'admin' && AdminPanel) {
       return (
         <Suspense fallback={<div>Loading admin panel...</div>}>
           <AdminPanel />
         </Suspense>
       );
     }
   
     return <div>Regular user content</div>;
   };
   ```

#### 5.2.3. Webpack Configuration for Code Splitting

```javascript
// webpack.config.js
module.exports = {
  optimization: {
    splitChunks: {
      chunks: 'all',
      cacheGroups: {
        vendor: {
          test: /[\\/]node_modules[\\/]/,
          name: 'vendors',
          chunks: 'all',
        },
        common: {
          name: 'common',
          minChunks: 2,
          chunks: 'all',
          enforce: true,
        },
      },
    },
  },
};
```

#### 5.2.4. Performance Monitoring

```tsx
const useChunkLoadTime = () => {
  const [loadTimes, setLoadTimes] = useState<Record<string, number>>({});
  
  const trackChunkLoad = (chunkName: string) => {
    const startTime = performance.now();
    
    return () => {
      const endTime = performance.now();
      const loadTime = endTime - startTime;
      
      setLoadTimes(prev => ({
        ...prev,
        [chunkName]: loadTime
      }));
      
      // Send to analytics
      analytics.track('chunk_loaded', {
        chunk: chunkName,
        loadTime,
        timestamp: Date.now()
      });
    };
  };
  
  return { loadTimes, trackChunkLoad };
};

// Usage
const Dashboard = () => {
  const { trackChunkLoad } = useChunkLoadTime();
  
  useEffect(() => {
    const endTracking = trackChunkLoad('dashboard');
    return endTracking;
  }, [trackChunkLoad]);
  
  return <div>Dashboard content</div>;
};
```

#### 5.2.5. Best Practices

1. **Bundle Analysis**
   ```bash
   # Analyze bundle size
   npm install --save-dev webpack-bundle-analyzer
   npx webpack-bundle-analyzer build/static/js/*.js
   ```

2. **Loading States**
   - Always provide meaningful loading states
   - Consider skeleton screens for better UX
   - Implement retry mechanisms for failed chunks

3. **Preloading Strategy**
   - Preload critical routes on user interaction
   - Use `<link rel="prefetch">` for likely next pages
   - Implement intelligent preloading based on user behavior

4. **Error Handling**
   - Wrap lazy components in error boundaries
   - Provide fallback UI for chunk load failures
   - Implement retry mechanisms

This comprehensive approach ensures optimal performance while maintaining a great user experience.

### 5.3. What's your approach to testing React applications? How do you balance unit, integration, and e2e tests?

**Answer:**

A comprehensive testing strategy for React applications follows the testing pyramid principle, balancing different types of tests for optimal coverage and maintainability.

#### 5.3.1. Testing Pyramid Structure

1. **Unit Tests (70%)** - Fast, isolated tests for individual functions/components
2. **Integration Tests (20%)** - Test component interactions and data flow
3. **End-to-End Tests (10%)** - Full user journey testing

#### 5.3.2. Unit Testing

**Component Testing with React Testing Library**
```tsx
import { render, screen, fireEvent, waitFor } from '@testing-library/react';
import userEvent from '@testing-library/user-event';
import { Button } from './Button';

describe('Button Component', () => {
  it('renders with correct text', () => {
    render(<Button>Click me</Button>);
    expect(screen.getByRole('button', { name: /click me/i })).toBeInTheDocument();
  });

  it('handles click events', async () => {
    const handleClick = jest.fn();
    const user = userEvent.setup();
    
    render(<Button onClick={handleClick}>Click me</Button>);
    
    await user.click(screen.getByRole('button'));
    expect(handleClick).toHaveBeenCalledTimes(1);
  });

  it('shows loading state', () => {
    render(<Button loading>Click me</Button>);
    expect(screen.getByRole('button')).toBeDisabled();
    expect(screen.getByText(/loading/i)).toBeInTheDocument();
  });
});
```

**Custom Hook Testing**
```tsx
import { renderHook, act } from '@testing-library/react';
import { useCounter } from './useCounter';

describe('useCounter Hook', () => {
  it('initializes with default value', () => {
    const { result } = renderHook(() => useCounter());
    expect(result.current.count).toBe(0);
  });

  it('increments counter', () => {
    const { result } = renderHook(() => useCounter());
    
    act(() => {
      result.current.increment();
    });
    
    expect(result.current.count).toBe(1);
  });

  it('resets counter', () => {
    const { result } = renderHook(() => useCounter());
    
    act(() => {
      result.current.increment();
      result.current.reset();
    });
    
    expect(result.current.count).toBe(0);
  });
});
```

**Utility Function Testing**
```tsx
import { formatCurrency, validateEmail } from './utils';

describe('Utility Functions', () => {
  describe('formatCurrency', () => {
    it('formats positive numbers correctly', () => {
      expect(formatCurrency(1234.56)).toBe('$1,234.56');
    });

    it('handles zero', () => {
      expect(formatCurrency(0)).toBe('$0.00');
    });

    it('handles negative numbers', () => {
      expect(formatCurrency(-100)).toBe('-$100.00');
    });
  });

  describe('validateEmail', () => {
    it('validates correct email formats', () => {
      expect(validateEmail('test@example.com')).toBe(true);
      expect(validateEmail('user.name@domain.co.uk')).toBe(true);
    });

    it('rejects invalid email formats', () => {
      expect(validateEmail('invalid-email')).toBe(false);
      expect(validateEmail('@domain.com')).toBe(false);
      expect(validateEmail('user@')).toBe(false);
    });
  });
});
```

#### 5.3.3. Integration Testing

**Component Integration with Context**
```tsx
import { render, screen, waitFor } from '@testing-library/react';
import { ThemeProvider } from './ThemeProvider';
import { ThemedButton } from './ThemedButton';

const renderWithTheme = (component: React.ReactElement) => {
  return render(
    <ThemeProvider theme="dark">
      {component}
    </ThemeProvider>
  );
};

describe('ThemedButton Integration', () => {
  it('applies theme styles correctly', () => {
    renderWithTheme(<ThemedButton>Click me</ThemedButton>);
    
    const button = screen.getByRole('button');
    expect(button).toHaveClass('dark-theme');
  });
});
```

**API Integration Testing**
```tsx
import { render, screen, waitFor } from '@testing-library/react';
import { rest } from 'msw';
import { setupServer } from 'msw/node';
import { UserList } from './UserList';

const server = setupServer(
  rest.get('/api/users', (req, res, ctx) => {
    return res(
      ctx.json([
        { id: 1, name: 'John Doe', email: 'john@example.com' },
        { id: 2, name: 'Jane Smith', email: 'jane@example.com' }
      ])
    );
  })
);

beforeAll(() => server.listen());
afterEach(() => server.resetHandlers());
afterAll(() => server.close());

describe('UserList Integration', () => {
  it('fetches and displays users', async () => {
    render(<UserList />);
    
    expect(screen.getByText(/loading/i)).toBeInTheDocument();
    
    await waitFor(() => {
      expect(screen.getByText('John Doe')).toBeInTheDocument();
      expect(screen.getByText('Jane Smith')).toBeInTheDocument();
    });
  });

  it('handles API errors gracefully', async () => {
    server.use(
      rest.get('/api/users', (req, res, ctx) => {
        return res(ctx.status(500));
      })
    );

    render(<UserList />);
    
    await waitFor(() => {
      expect(screen.getByText(/error loading users/i)).toBeInTheDocument();
    });
  });
});
```

**Form Integration Testing**
```tsx
import { render, screen, waitFor } from '@testing-library/react';
import userEvent from '@testing-library/user-event';
import { ContactForm } from './ContactForm';

describe('ContactForm Integration', () => {
  it('submits form with valid data', async () => {
    const user = userEvent.setup();
    const onSubmit = jest.fn();
    
    render(<ContactForm onSubmit={onSubmit} />);
    
    await user.type(screen.getByLabelText(/name/i), 'John Doe');
    await user.type(screen.getByLabelText(/email/i), 'john@example.com');
    await user.type(screen.getByLabelText(/message/i), 'Hello world');
    
    await user.click(screen.getByRole('button', { name: /submit/i }));
    
    await waitFor(() => {
      expect(onSubmit).toHaveBeenCalledWith({
        name: 'John Doe',
        email: 'john@example.com',
        message: 'Hello world'
      });
    });
  });

  it('shows validation errors', async () => {
    const user = userEvent.setup();
    
    render(<ContactForm onSubmit={jest.fn()} />);
    
    await user.click(screen.getByRole('button', { name: /submit/i }));
    
    await waitFor(() => {
      expect(screen.getByText(/name is required/i)).toBeInTheDocument();
      expect(screen.getByText(/email is required/i)).toBeInTheDocument();
    });
  });
});
```

#### 5.3.4. End-to-End Testing

**Playwright E2E Tests**
```typescript
import { test, expect } from '@playwright/test';

test.describe('User Authentication Flow', () => {
  test('user can login and access dashboard', async ({ page }) => {
    await page.goto('/login');
    
    await page.fill('[data-testid="email"]', 'user@example.com');
    await page.fill('[data-testid="password"]', 'password123');
    await page.click('[data-testid="login-button"]');
    
    await expect(page).toHaveURL('/dashboard');
    await expect(page.locator('[data-testid="user-menu"]')).toBeVisible();
  });

  test('user can logout', async ({ page }) => {
    // Login first
    await page.goto('/login');
    await page.fill('[data-testid="email"]', 'user@example.com');
    await page.fill('[data-testid="password"]', 'password123');
    await page.click('[data-testid="login-button"]');
    
    // Logout
    await page.click('[data-testid="user-menu"]');
    await page.click('[data-testid="logout-button"]');
    
    await expect(page).toHaveURL('/login');
  });
});

test.describe('Shopping Cart Flow', () => {
  test('user can add items to cart and checkout', async ({ page }) => {
    await page.goto('/products');
    
    // Add first product
    await page.click('[data-testid="product-1"] [data-testid="add-to-cart"]');
    await expect(page.locator('[data-testid="cart-count"]')).toHaveText('1');
    
    // Add second product
    await page.click('[data-testid="product-2"] [data-testid="add-to-cart"]');
    await expect(page.locator('[data-testid="cart-count"]')).toHaveText('2');
    
    // Go to cart
    await page.click('[data-testid="cart-icon"]');
    await expect(page).toHaveURL('/cart');
    
    // Proceed to checkout
    await page.click('[data-testid="checkout-button"]');
    await expect(page).toHaveURL('/checkout');
  });
});
```

#### 5.3.5. Testing Configuration

**Jest Configuration**
```javascript
// jest.config.js
module.exports = {
  testEnvironment: 'jsdom',
  setupFilesAfterEnv: ['<rootDir>/src/setupTests.ts'],
  moduleNameMapping: {
    '^@/(.*)$': '<rootDir>/src/$1',
    '\\.(css|less|scss|sass)$': 'identity-obj-proxy',
  },
  collectCoverageFrom: [
    'src/**/*.{ts,tsx}',
    '!src/**/*.d.ts',
    '!src/index.tsx',
    '!src/setupTests.ts',
  ],
  coverageThreshold: {
    global: {
      branches: 80,
      functions: 80,
      lines: 80,
      statements: 80,
    },
  },
};
```

**Test Setup**
```typescript
// src/setupTests.ts
import '@testing-library/jest-dom';
import { server } from './mocks/server';

// Establish API mocking before all tests
beforeAll(() => server.listen());

// Reset any request handlers that we may add during the tests
afterEach(() => server.resetHandlers());

// Clean up after the tests are finished
afterAll(() => server.close());

// Mock IntersectionObserver
global.IntersectionObserver = class IntersectionObserver {
  constructor() {}
  disconnect() {}
  observe() {}
  unobserve() {}
};
```

#### 5.3.6. Testing Best Practices

1. **Test Behavior, Not Implementation**
   ```tsx
   // Good: Tests user behavior
   it('shows error message when form is invalid', () => {
     render(<ContactForm />);
     fireEvent.click(screen.getByRole('button'));
     expect(screen.getByText(/please fill all fields/i)).toBeInTheDocument();
   });

   // Avoid: Tests implementation details
   it('calls validateForm when submit button is clicked', () => {
     const validateForm = jest.fn();
     render(<ContactForm validateForm={validateForm} />);
     fireEvent.click(screen.getByRole('button'));
     expect(validateForm).toHaveBeenCalled();
   });
   ```

2. **Use Data Test IDs Sparingly**
   ```tsx
   // Use semantic queries first
   screen.getByRole('button', { name: /submit/i });
   screen.getByLabelText(/email address/i);
   
   // Use data-testid only when necessary
   screen.getByTestId('complex-component');
   ```

3. **Mock External Dependencies**
   ```tsx
   // Mock API calls
   jest.mock('./api', () => ({
    fetchUsers: jest.fn(() => Promise.resolve(mockUsers)),
  }));

  // Mock browser APIs
  Object.defineProperty(window, 'localStorage', {
    value: {
      getItem: jest.fn(),
      setItem: jest.fn(),
      removeItem: jest.fn(),
    },
  });
  ```

4. **Test Accessibility**
   ```tsx
   import { axe, toHaveNoViolations } from 'jest-axe';
   
   expect.extend(toHaveNoViolations);
   
   it('should not have accessibility violations', async () => {
     const { container } = render(<MyComponent />);
     const results = await axe(container);
     expect(results).toHaveNoViolations();
   });
   ```

#### 5.3.7. Continuous Integration

**GitHub Actions Workflow**
```yaml
name: Tests

on: [push, pull_request]

jobs:
  test:
    runs-on: ubuntu-latest
    
    steps:
      - uses: actions/checkout@v3
      
      - name: Setup Node.js
        uses: actions/setup-node@v3
        with:
          node-version: '18'
          cache: 'npm'
      
      - name: Install dependencies
        run: npm ci
      
      - name: Run unit tests
        run: npm run test:unit
      
      - name: Run integration tests
        run: npm run test:integration
      
      - name: Run E2E tests
        run: npm run test:e2e
      
      - name: Upload coverage
        uses: codecov/codecov-action@v3
```

This comprehensive testing strategy ensures code quality, catches regressions early, and provides confidence when deploying changes to production.

### 5.4. How would you implement authentication in a React SPA? Discuss token management, refresh strategies, and protected routes.

**Answer:**

Implementing authentication in a React SPA requires careful consideration of security, user experience, and token management. Here's a comprehensive approach:

#### 5.4.1. Authentication Architecture

**Auth Context and Provider**
```tsx
interface User {
  id: string;
  email: string;
  name: string;
  role: 'user' | 'admin';
  permissions: string[];
}

interface AuthState {
  user: User | null;
  token: string | null;
  refreshToken: string | null;
  isAuthenticated: boolean;
  isLoading: boolean;
  error: string | null;
}

interface AuthContextType extends AuthState {
  login: (email: string, password: string) => Promise<void>;
  logout: () => void;
  refreshAuthToken: () => Promise<void>;
  hasPermission: (permission: string) => boolean;
  hasRole: (role: string) => boolean;
}

const AuthContext = createContext<AuthContextType | undefined>(undefined);

export const AuthProvider: React.FC<{ children: React.ReactNode }> = ({ children }) => {
  const [state, setState] = useState<AuthState>({
    user: null,
    token: null,
    refreshToken: null,
    isAuthenticated: false,
    isLoading: true,
    error: null,
  });

  // Initialize auth state from localStorage
  useEffect(() => {
    const initializeAuth = async () => {
      try {
        const token = localStorage.getItem('accessToken');
        const refreshToken = localStorage.getItem('refreshToken');
        
        if (token && refreshToken) {
          // Verify token and get user data
          const user = await verifyToken(token);
          setState(prev => ({
            ...prev,
            user,
            token,
            refreshToken,
            isAuthenticated: true,
            isLoading: false,
          }));
        } else {
          setState(prev => ({ ...prev, isLoading: false }));
        }
      } catch (error) {
        // Clear invalid tokens
        localStorage.removeItem('accessToken');
        localStorage.removeItem('refreshToken');
        setState(prev => ({ ...prev, isLoading: false }));
      }
    };

    initializeAuth();
  }, []);

  const login = async (email: string, password: string) => {
    setState(prev => ({ ...prev, isLoading: true, error: null }));
    
    try {
      const response = await fetch('/api/auth/login', {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify({ email, password }),
      });

      if (!response.ok) {
        throw new Error('Invalid credentials');
      }

      const { user, accessToken, refreshToken } = await response.json();
      
      // Store tokens securely
      localStorage.setItem('accessToken', accessToken);
      localStorage.setItem('refreshToken', refreshToken);
      
      setState({
        user,
        token: accessToken,
        refreshToken,
        isAuthenticated: true,
        isLoading: false,
        error: null,
      });
    } catch (error) {
      setState(prev => ({
        ...prev,
        isLoading: false,
        error: error instanceof Error ? error.message : 'Login failed',
      }));
      throw error;
    }
  };

  const logout = () => {
    localStorage.removeItem('accessToken');
    localStorage.removeItem('refreshToken');
    setState({
      user: null,
      token: null,
      refreshToken: null,
      isAuthenticated: false,
      isLoading: false,
      error: null,
    });
  };

  const refreshAuthToken = async () => {
    const refreshToken = localStorage.getItem('refreshToken');
    if (!refreshToken) {
      logout();
      return;
    }

    try {
      const response = await fetch('/api/auth/refresh', {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify({ refreshToken }),
      });

      if (!response.ok) {
        throw new Error('Token refresh failed');
      }

      const { accessToken, refreshToken: newRefreshToken } = await response.json();
      
      localStorage.setItem('accessToken', accessToken);
      localStorage.setItem('refreshToken', newRefreshToken);
      
      setState(prev => ({
        ...prev,
        token: accessToken,
        refreshToken: newRefreshToken,
      }));
    } catch (error) {
      logout();
      throw error;
    }
  };

  const hasPermission = (permission: string): boolean => {
    return state.user?.permissions.includes(permission) ?? false;
  };

  const hasRole = (role: string): boolean => {
    return state.user?.role === role;
  };

  return (
    <AuthContext.Provider
      value={{
        ...state,
        login,
        logout,
        refreshAuthToken,
        hasPermission,
        hasRole,
      }}
    >
      {children}
    </AuthContext.Provider>
  );
};

export const useAuth = () => {
  const context = useContext(AuthContext);
  if (context === undefined) {
    throw new Error('useAuth must be used within an AuthProvider');
  }
  return context;
};
```

#### 5.4.2. Token Management

**HTTP Client with Automatic Token Refresh**
```tsx
class ApiClient {
  private baseURL: string;
  private refreshPromise: Promise<string> | null = null;

  constructor(baseURL: string) {
    this.baseURL = baseURL;
  }

  private async makeRequest<T>(
    endpoint: string,
    options: RequestInit = {}
  ): Promise<T> {
    const token = localStorage.getItem('accessToken');
    
    const config: RequestInit = {
      ...options,
      headers: {
        'Content-Type': 'application/json',
        ...(token && { Authorization: `Bearer ${token}` }),
        ...options.headers,
      },
    };

    let response = await fetch(`${this.baseURL}${endpoint}`, config);

    // Handle token expiration
    if (response.status === 401 && token) {
      try {
        const newToken = await this.refreshToken();
        config.headers = {
          ...config.headers,
          Authorization: `Bearer ${newToken}`,
        };
        response = await fetch(`${this.baseURL}${endpoint}`, config);
      } catch (error) {
        // Redirect to login
        window.location.href = '/login';
        throw error;
      }
    }

    if (!response.ok) {
      throw new Error(`HTTP error! status: ${response.status}`);
    }

    return response.json();
  }

  private async refreshToken(): Promise<string> {
    if (this.refreshPromise) {
      return this.refreshPromise;
    }

    this.refreshPromise = this.performTokenRefresh();
    
    try {
      const newToken = await this.refreshPromise;
      return newToken;
    } finally {
      this.refreshPromise = null;
    }
  }

  private async performTokenRefresh(): Promise<string> {
    const refreshToken = localStorage.getItem('refreshToken');
    if (!refreshToken) {
      throw new Error('No refresh token available');
    }

    const response = await fetch(`${this.baseURL}/auth/refresh`, {
      method: 'POST',
      headers: { 'Content-Type': 'application/json' },
      body: JSON.stringify({ refreshToken }),
    });

    if (!response.ok) {
      throw new Error('Token refresh failed');
    }

    const { accessToken, refreshToken: newRefreshToken } = await response.json();
    
    localStorage.setItem('accessToken', accessToken);
    localStorage.setItem('refreshToken', newRefreshToken);
    
    return accessToken;
  }

  // Public methods
  async get<T>(endpoint: string): Promise<T> {
    return this.makeRequest<T>(endpoint, { method: 'GET' });
  }

  async post<T>(endpoint: string, data: any): Promise<T> {
    return this.makeRequest<T>(endpoint, {
      method: 'POST',
      body: JSON.stringify(data),
    });
  }

  async put<T>(endpoint: string, data: any): Promise<T> {
    return this.makeRequest<T>(endpoint, {
      method: 'PUT',
      body: JSON.stringify(data),
    });
  }

  async delete<T>(endpoint: string): Promise<T> {
    return this.makeRequest<T>(endpoint, { method: 'DELETE' });
  }
}

export const apiClient = new ApiClient(process.env.REACT_APP_API_URL || '');
```

#### 5.4.3. Protected Routes

**Route Protection Components**
```tsx
interface ProtectedRouteProps {
  children: React.ReactNode;
  requiredPermission?: string;
  requiredRole?: string;
  fallback?: React.ReactNode;
}

export const ProtectedRoute: React.FC<ProtectedRouteProps> = ({
  children,
  requiredPermission,
  requiredRole,
  fallback = <Navigate to="/login" replace />,
}) => {
  const { isAuthenticated, user, isLoading } = useAuth();

  if (isLoading) {
    return <LoadingSpinner />;
  }

  if (!isAuthenticated || !user) {
    return <>{fallback}</>;
  }

  if (requiredRole && !user.role.includes(requiredRole)) {
    return <Navigate to="/unauthorized" replace />;
  }

  if (requiredPermission && !user.permissions.includes(requiredPermission)) {
    return <Navigate to="/unauthorized" replace />;
  }

  return <>{children}</>;
};

// Usage in routing
const AppRoutes = () => {
  return (
    <Routes>
      <Route path="/login" element={<LoginPage />} />
      <Route path="/register" element={<RegisterPage />} />
      
      <Route
        path="/dashboard"
        element={
          <ProtectedRoute>
            <Dashboard />
          </ProtectedRoute>
        }
      />
      
      <Route
        path="/admin"
        element={
          <ProtectedRoute requiredRole="admin">
            <AdminPanel />
          </ProtectedRoute>
        }
      />
      
      <Route
        path="/settings"
        element={
          <ProtectedRoute requiredPermission="manage_settings">
            <SettingsPage />
          </ProtectedRoute>
        }
      />
      
      <Route path="/unauthorized" element={<UnauthorizedPage />} />
      <Route path="*" element={<NotFoundPage />} />
    </Routes>
  );
};
```

#### 5.4.4. Advanced Security Features

**Session Management**
```tsx
const useSessionManagement = () => {
  const { logout } = useAuth();
  const [lastActivity, setLastActivity] = useState(Date.now());
  const SESSION_TIMEOUT = 30 * 60 * 1000; // 30 minutes

  useEffect(() => {
    const updateActivity = () => setLastActivity(Date.now());
    
    // Track user activity
    const events = ['mousedown', 'mousemove', 'keypress', 'scroll', 'touchstart'];
    events.forEach(event => {
      document.addEventListener(event, updateActivity, true);
    });

    // Check for session timeout
    const checkSession = setInterval(() => {
      if (Date.now() - lastActivity > SESSION_TIMEOUT) {
        logout();
        clearInterval(checkSession);
      }
    }, 60000); // Check every minute

    return () => {
      events.forEach(event => {
        document.removeEventListener(event, updateActivity, true);
      });
      clearInterval(checkSession);
    };
  }, [lastActivity, logout]);

  return { lastActivity };
};
```

**Multi-Factor Authentication**
```tsx
interface MFAState {
  isEnabled: boolean;
  backupCodes: string[];
  qrCode: string;
}

const useMFA = () => {
  const [mfaState, setMfaState] = useState<MFAState | null>(null);
  const { user } = useAuth();

  const enableMFA = async () => {
    try {
      const response = await apiClient.post('/auth/mfa/setup', {});
      setMfaState(response);
    } catch (error) {
      console.error('Failed to setup MFA:', error);
    }
  };

  const verifyMFA = async (token: string) => {
    try {
      await apiClient.post('/auth/mfa/verify', { token });
      return true;
    } catch (error) {
      return false;
    }
  };

  const disableMFA = async (password: string) => {
    try {
      await apiClient.post('/auth/mfa/disable', { password });
      setMfaState(null);
    } catch (error) {
      console.error('Failed to disable MFA:', error);
    }
  };

  return {
    mfaState,
    enableMFA,
    verifyMFA,
    disableMFA,
  };
};
```

#### 5.4.5. Security Best Practices

**Token Storage Security**
```tsx
// Secure token storage with encryption
class SecureStorage {
  private static encrypt(data: string): string {
    // Implement encryption logic
    return btoa(data); // Simple base64 for demo
  }

  private static decrypt(encryptedData: string): string {
    // Implement decryption logic
    return atob(encryptedData); // Simple base64 for demo
  }

  static setItem(key: string, value: string): void {
    const encrypted = this.encrypt(value);
    localStorage.setItem(key, encrypted);
  }

  static getItem(key: string): string | null {
    const encrypted = localStorage.getItem(key);
    if (!encrypted) return null;
    
    try {
      return this.decrypt(encrypted);
    } catch {
      return null;
    }
  }

  static removeItem(key: string): void {
    localStorage.removeItem(key);
  }
}

// Use secure storage for tokens
SecureStorage.setItem('accessToken', token);
const token = SecureStorage.getItem('accessToken');
```

**CSRF Protection**
```tsx
const useCSRFProtection = () => {
  const [csrfToken, setCsrfToken] = useState<string | null>(null);

  useEffect(() => {
    const fetchCSRFToken = async () => {
      try {
        const response = await fetch('/api/csrf-token');
        const { token } = await response.json();
        setCsrfToken(token);
      } catch (error) {
        console.error('Failed to fetch CSRF token:', error);
      }
    };

    fetchCSRFToken();
  }, []);

  const getHeaders = () => ({
    'X-CSRF-Token': csrfToken,
  });

  return { csrfToken, getHeaders };
};
```

#### 5.4.6. Error Handling and User Experience

**Auth Error Boundary**
```tsx
class AuthErrorBoundary extends React.Component<
  { children: React.ReactNode },
  { hasError: boolean }
> {
  constructor(props: { children: React.ReactNode }) {
    super(props);
    this.state = { hasError: false };
  }

  static getDerivedStateFromError(error: Error) {
    if (error.message.includes('401') || error.message.includes('403')) {
      return { hasError: true };
    }
    return null;
  }

  componentDidCatch(error: Error, errorInfo: React.ErrorInfo) {
    if (error.message.includes('401')) {
      // Redirect to login
      window.location.href = '/login';
    }
  }

  render() {
    if (this.state.hasError) {
      return <Navigate to="/login" replace />;
    }

    return this.props.children;
  }
}
```

This comprehensive authentication system provides secure, user-friendly authentication with proper token management, role-based access control, and advanced security features.

### 5.5. Design a robust data fetching layer for a React application. How would you handle caching, error states, and optimistic updates?

**Answer:**

A robust data fetching layer is crucial for modern React applications. Here's a comprehensive approach that handles caching, error states, optimistic updates, and more:

#### 5.5.1. Core Data Fetching Architecture

**Custom Hook for Data Fetching**
```tsx
interface FetchState<T> {
  data: T | null;
  loading: boolean;
  error: Error | null;
  refetch: () => Promise<void>;
}

interface FetchOptions {
  enabled?: boolean;
  retry?: number;
  retryDelay?: number;
  staleTime?: number;
  cacheTime?: number;
  onSuccess?: (data: any) => void;
  onError?: (error: Error) => void;
}

const useFetch = <T>(
  url: string,
  options: FetchOptions = {}
): FetchState<T> => {
  const {
    enabled = true,
    retry = 3,
    retryDelay = 1000,
    staleTime = 5 * 60 * 1000, // 5 minutes
    cacheTime = 10 * 60 * 1000, // 10 minutes
    onSuccess,
    onError,
  } = options;

  const [state, setState] = useState<FetchState<T>>({
    data: null,
    loading: false,
    error: null,
    refetch: () => Promise.resolve(),
  });

  const cache = useRef<Map<string, { data: T; timestamp: number }>>(new Map());

  const fetchData = useCallback(async (retryCount = 0): Promise<void> => {
    if (!enabled) return;

    // Check cache first
    const cached = cache.current.get(url);
    if (cached && Date.now() - cached.timestamp < staleTime) {
      setState(prev => ({ ...prev, data: cached.data, loading: false }));
      onSuccess?.(cached.data);
      return;
    }

    setState(prev => ({ ...prev, loading: true, error: null }));

    try {
      const response = await fetch(url);
      if (!response.ok) {
        throw new Error(`HTTP error! status: ${response.status}`);
      }

      const data = await response.json();
      
      // Cache the data
      cache.current.set(url, { data, timestamp: Date.now() });
      
      setState(prev => ({ ...prev, data, loading: false }));
      onSuccess?.(data);
    } catch (error) {
      const err = error instanceof Error ? error : new Error('Unknown error');
      
      if (retryCount < retry) {
        // Retry with exponential backoff
        setTimeout(() => {
          fetchData(retryCount + 1);
        }, retryDelay * Math.pow(2, retryCount));
      } else {
        setState(prev => ({ ...prev, error: err, loading: false }));
        onError?.(err);
      }
    }
  }, [url, enabled, retry, retryDelay, staleTime, onSuccess, onError]);

  const refetch = useCallback(() => {
    cache.current.delete(url);
    return fetchData();
  }, [fetchData, url]);

  useEffect(() => {
    fetchData();
  }, [fetchData]);

  // Cleanup old cache entries
  useEffect(() => {
    const cleanup = setInterval(() => {
      const now = Date.now();
      for (const [key, value] of cache.current.entries()) {
        if (now - value.timestamp > cacheTime) {
          cache.current.delete(key);
        }
      }
    }, 60000); // Cleanup every minute

    return () => clearInterval(cleanup);
  }, [cacheTime]);

  return { ...state, refetch };
};
```

#### 5.5.2. Advanced Caching with React Query

**React Query Setup**
```tsx
import { QueryClient, QueryClientProvider, useQuery, useMutation, useQueryClient } from '@tanstack/react-query';

const queryClient = new QueryClient({
  defaultOptions: {
    queries: {
      staleTime: 5 * 60 * 1000, // 5 minutes
      cacheTime: 10 * 60 * 1000, // 10 minutes
      retry: 3,
      retryDelay: attemptIndex => Math.min(1000 * 2 ** attemptIndex, 30000),
    },
    mutations: {
      retry: 1,
    },
  },
});

// Custom hooks for different data types
export const useUsers = () => {
  return useQuery({
    queryKey: ['users'],
    queryFn: () => fetch('/api/users').then(res => res.json()),
    select: (data) => data.users,
  });
};

export const useUser = (id: string) => {
  return useQuery({
    queryKey: ['users', id],
    queryFn: () => fetch(`/api/users/${id}`).then(res => res.json()),
    enabled: !!id,
  });
};

export const useCreateUser = () => {
  const queryClient = useQueryClient();
  
  return useMutation({
    mutationFn: (userData: CreateUserData) =>
      fetch('/api/users', {
        method: 'POST',
        headers: { 'Content-Type': 'application/json' },
        body: JSON.stringify(userData),
      }).then(res => res.json()),
    onSuccess: (newUser) => {
      // Invalidate and refetch users list
      queryClient.invalidateQueries({ queryKey: ['users'] });
      
      // Optimistically update the cache
      queryClient.setQueryData(['users', newUser.id], newUser);
    },
    onError: (error) => {
      console.error('Failed to create user:', error);
    },
  });
};
```

#### 5.5.3. Optimistic Updates

**Optimistic Update Implementation**
```tsx
interface OptimisticUpdate<T> {
  queryKey: string[];
  updateFn: (oldData: T) => T;
  rollbackFn?: (oldData: T) => T;
}

const useOptimisticMutation = <T, TVariables>(
  mutationFn: (variables: TVariables) => Promise<T>,
  optimisticUpdate: OptimisticUpdate<T>
) => {
  const queryClient = useQueryClient();
  const [isOptimistic, setIsOptimistic] = useState(false);

  return useMutation({
    mutationFn,
    onMutate: async (variables) => {
      // Cancel outgoing refetches
      await queryClient.cancelQueries({ queryKey: optimisticUpdate.queryKey });

      // Snapshot previous value
      const previousData = queryClient.getQueryData<T>(optimisticUpdate.queryKey);

      // Optimistically update
      if (previousData) {
        queryClient.setQueryData(
          optimisticUpdate.queryKey,
          optimisticUpdate.updateFn(previousData)
        );
        setIsOptimistic(true);
      }

      return { previousData };
    },
    onError: (err, variables, context) => {
      // Rollback on error
      if (context?.previousData && optimisticUpdate.rollbackFn) {
        queryClient.setQueryData(
          optimisticUpdate.queryKey,
          optimisticUpdate.rollbackFn(context.previousData)
        );
      }
      setIsOptimistic(false);
    },
    onSettled: () => {
      // Always refetch after error or success
      queryClient.invalidateQueries({ queryKey: optimisticUpdate.queryKey });
      setIsOptimistic(false);
    },
  });
};

// Usage example
const useToggleLike = () => {
  return useOptimisticMutation(
    (postId: string) => fetch(`/api/posts/${postId}/like`, { method: 'POST' }).then(res => res.json()),
    {
      queryKey: ['posts'],
      updateFn: (oldData) => ({
        ...oldData,
        posts: oldData.posts.map(post => 
          post.id === postId 
            ? { ...post, liked: !post.liked, likes: post.liked ? post.likes - 1 : post.likes + 1 }
            : post
        ),
      }),
      rollbackFn: (oldData) => ({
        ...oldData,
        posts: oldData.posts.map(post => 
          post.id === postId 
            ? { ...post, liked: !post.liked, likes: post.liked ? post.likes + 1 : post.likes - 1 }
            : post
        ),
      }),
    }
  );
};
```

#### 5.5.4. Error Handling and Retry Logic

**Advanced Error Handling**
```tsx
interface ApiError extends Error {
  status?: number;
  code?: string;
  details?: any;
}

class ApiErrorHandler {
  static async handleResponse(response: Response): Promise<any> {
    if (!response.ok) {
      const error: ApiError = new Error(`HTTP ${response.status}: ${response.statusText}`);
      error.status = response.status;
      
      try {
        const errorData = await response.json();
        error.details = errorData;
        error.message = errorData.message || error.message;
      } catch {
        // If response is not JSON, use status text
      }
      
      throw error;
    }
    
    return response.json();
  }

  static isRetryableError(error: ApiError): boolean {
    if (!error.status) return true; // Network errors are retryable
    
    // Retry on server errors and rate limiting
    return error.status >= 500 || error.status === 429;
  }

  static getRetryDelay(attempt: number, baseDelay = 1000): number {
    // Exponential backoff with jitter
    const delay = baseDelay * Math.pow(2, attempt);
    const jitter = Math.random() * 0.1 * delay;
    return Math.min(delay + jitter, 30000); // Max 30 seconds
  }
}

const useApiCall = <T>(
  url: string,
  options: RequestInit = {},
  retryOptions = { maxRetries: 3, baseDelay: 1000 }
) => {
  const [state, setState] = useState<{
    data: T | null;
    loading: boolean;
    error: ApiError | null;
  }>({
    data: null,
    loading: false,
    error: null,
  });

  const execute = useCallback(async (retryCount = 0): Promise<T> => {
    setState(prev => ({ ...prev, loading: true, error: null }));

    try {
      const response = await fetch(url, options);
      const data = await ApiErrorHandler.handleResponse(response);
      
      setState({ data, loading: false, error: null });
      return data;
    } catch (error) {
      const apiError = error as ApiError;
      
      if (
        retryCount < retryOptions.maxRetries &&
        ApiErrorHandler.isRetryableError(apiError)
      ) {
        const delay = ApiErrorHandler.getRetryDelay(retryCount, retryOptions.baseDelay);
        
        await new Promise(resolve => setTimeout(resolve, delay));
        return execute(retryCount + 1);
      }
      
      setState({ data: null, loading: false, error: apiError });
      throw apiError;
    }
  }, [url, options, retryOptions]);

  return { ...state, execute };
};
```

#### 5.5.5. Real-time Data with WebSockets

**WebSocket Integration**
```tsx
interface WebSocketMessage {
  type: string;
  payload: any;
  timestamp: number;
}

const useWebSocket = (url: string, options: { reconnect?: boolean; reconnectInterval?: number } = {}) => {
  const { reconnect = true, reconnectInterval = 3000 } = options;
  const [socket, setSocket] = useState<WebSocket | null>(null);
  const [isConnected, setIsConnected] = useState(false);
  const [lastMessage, setLastMessage] = useState<WebSocketMessage | null>(null);
  const [error, setError] = useState<Event | null>(null);

  const connect = useCallback(() => {
    const ws = new WebSocket(url);
    
    ws.onopen = () => {
      setIsConnected(true);
      setError(null);
    };
    
    ws.onmessage = (event) => {
      try {
        const message: WebSocketMessage = JSON.parse(event.data);
        setLastMessage(message);
      } catch (err) {
        console.error('Failed to parse WebSocket message:', err);
      }
    };
    
    ws.onclose = () => {
      setIsConnected(false);
      if (reconnect) {
        setTimeout(connect, reconnectInterval);
      }
    };
    
    ws.onerror = (event) => {
      setError(event);
    };
    
    setSocket(ws);
  }, [url, reconnect, reconnectInterval]);

  const sendMessage = useCallback((message: any) => {
    if (socket && isConnected) {
      socket.send(JSON.stringify(message));
    }
  }, [socket, isConnected]);

  const disconnect = useCallback(() => {
    if (socket) {
      socket.close();
      setSocket(null);
    }
  }, [socket]);

  useEffect(() => {
    connect();
    return disconnect;
  }, [connect, disconnect]);

  return {
    isConnected,
    lastMessage,
    error,
    sendMessage,
    disconnect,
    reconnect: connect,
  };
};

// Usage with React Query for real-time updates
const useRealtimePosts = () => {
  const queryClient = useQueryClient();
  
  const { lastMessage } = useWebSocket('ws://localhost:8080/posts');
  
  useEffect(() => {
    if (lastMessage) {
      switch (lastMessage.type) {
        case 'POST_CREATED':
          queryClient.invalidateQueries({ queryKey: ['posts'] });
          break;
        case 'POST_UPDATED':
          queryClient.setQueryData(['posts', lastMessage.payload.id], lastMessage.payload);
          break;
        case 'POST_DELETED':
          queryClient.setQueryData(['posts'], (old: any) => 
            old?.filter((post: any) => post.id !== lastMessage.payload.id)
          );
          break;
      }
    }
  }, [lastMessage, queryClient]);
  
  return useQuery({
    queryKey: ['posts'],
    queryFn: () => fetch('/api/posts').then(res => res.json()),
  });
};
```

#### 5.5.6. Offline Support and Background Sync

**Service Worker Integration**
```tsx
// service-worker.js
const CACHE_NAME = 'api-cache-v1';
const OFFLINE_QUEUE = 'offline-queue';

// Cache API responses
self.addEventListener('fetch', (event) => {
  if (event.request.url.includes('/api/')) {
    event.respondWith(
      caches.match(event.request).then((response) => {
        if (response) {
          return response;
        }
        
        return fetch(event.request).then((response) => {
          if (response.status === 200) {
            const responseClone = response.clone();
            caches.open(CACHE_NAME).then((cache) => {
              cache.put(event.request, responseClone);
            });
          }
          return response;
        }).catch(() => {
          // Return cached version or queue for later
          return caches.match(event.request);
        });
      })
    );
  }
});

// Background sync for offline actions
self.addEventListener('sync', (event) => {
  if (event.tag === 'background-sync') {
    event.waitUntil(processOfflineQueue());
  }
});

const processOfflineQueue = async () => {
  const queue = await getOfflineQueue();
  
  for (const request of queue) {
    try {
      await fetch(request.url, request.options);
      await removeFromOfflineQueue(request.id);
    } catch (error) {
      console.error('Failed to sync request:', error);
    }
  }
};
```

**Offline-Aware Data Fetching**
```tsx
const useOfflineAwareFetch = <T>(url: string, options: RequestInit = {}) => {
  const [isOnline, setIsOnline] = useState(navigator.onLine);
  const [offlineQueue, setOfflineQueue] = useState<any[]>([]);

  useEffect(() => {
    const handleOnline = () => setIsOnline(true);
    const handleOffline = () => setIsOnline(false);

    window.addEventListener('online', handleOnline);
    window.addEventListener('offline', handleOffline);

    return () => {
      window.removeEventListener('online', handleOnline);
      window.removeEventListener('offline', handleOffline);
    };
  }, []);

  const executeRequest = useCallback(async (): Promise<T> => {
    if (!isOnline && options.method !== 'GET') {
      // Queue non-GET requests when offline
      const queuedRequest = {
        id: Date.now().toString(),
        url,
        options,
        timestamp: Date.now(),
      };
      
      setOfflineQueue(prev => [...prev, queuedRequest]);
      throw new Error('Request queued for offline sync');
    }

    const response = await fetch(url, options);
    return ApiErrorHandler.handleResponse(response);
  }, [url, options, isOnline]);

  return { executeRequest, isOnline, offlineQueue };
};
```

#### 5.5.7. Performance Optimization

**Request Deduplication**
```tsx
class RequestDeduplicator {
  private static pendingRequests = new Map<string, Promise<any>>();

  static async deduplicate<T>(key: string, requestFn: () => Promise<T>): Promise<T> {
    if (this.pendingRequests.has(key)) {
      return this.pendingRequests.get(key)!;
    }

    const promise = requestFn().finally(() => {
      this.pendingRequests.delete(key);
    });

    this.pendingRequests.set(key, promise);
    return promise;
  }
}

const useDeduplicatedFetch = <T>(url: string) => {
  return useQuery({
    queryKey: [url],
    queryFn: () => RequestDeduplicator.deduplicate(url, () => 
      fetch(url).then(res => res.json())
    ),
  });
};
```

This comprehensive data fetching layer provides robust caching, error handling, optimistic updates, real-time capabilities, offline support, and performance optimizations for modern React applications.

---

## 6. Coding Challenges

### 6.1. Implement a Debounce Function
Create a debounce function with TypeScript types that properly handles the `this` context and cleanup.

**Solution:**

```typescript
function debounce<T extends (...args: any[]) => any>(
  func: T,
  wait: number,
  immediate?: boolean
): (...args: Parameters<T>) => void {
  let timeout: NodeJS.Timeout | null = null;
  
  return function executedFunction(this: any, ...args: Parameters<T>) {
    const later = () => {
      timeout = null;
      if (!immediate) func.apply(this, args);
    };
    
    const callNow = immediate && !timeout;
    
    if (timeout) clearTimeout(timeout);
    timeout = setTimeout(later, wait);
    
    if (callNow) func.apply(this, args);
  };
}

// Usage
const debouncedSearch = debounce(function(this: any, query: string) {
  console.log('Searching:', query);
}, 300);

// Cleanup method
function debounceWithCleanup<T extends (...args: any[]) => any>(
  func: T,
  wait: number
): T & { cancel: () => void } {
  let timeout: NodeJS.Timeout | null = null;
  
  const debounced = function(this: any, ...args: Parameters<T>) {
    if (timeout) clearTimeout(timeout);
    timeout = setTimeout(() => func.apply(this, args), wait);
  } as T & { cancel: () => void };
  
  debounced.cancel = () => {
    if (timeout) {
      clearTimeout(timeout);
      timeout = null;
    }
  };
  
  return debounced;
}
```

### 6.2. Build a Custom useIntersectionObserver Hook
Implement a hook that tracks when an element enters/exits the viewport with proper TypeScript typing.

**Solution:**

```typescript
function useIntersectionObserver(
  options: IntersectionObserverInit = {}
): [React.RefObject<HTMLElement>, IntersectionObserverEntry | null] {
  const [entry, setEntry] = useState<IntersectionObserverEntry | null>(null);
  const ref = useRef<HTMLElement>(null);
  
  useEffect(() => {
    const element = ref.current;
    if (!element) return;
    
    const observer = new IntersectionObserver(
      ([entry]) => setEntry(entry),
      options
    );
    
    observer.observe(element);
    
    return () => observer.disconnect();
  }, [options]);
  
  return [ref, entry];
}

// Usage
const MyComponent = () => {
  const [ref, entry] = useIntersectionObserver({
    threshold: 0.5,
    rootMargin: '0px'
  });
  
  return (
    <div ref={ref}>
      {entry?.isIntersecting ? 'Visible' : 'Hidden'}
    </div>
  );
};
```

### 6.3. Create a Higher-Order Component
Build a HOC that adds loading and error states to any component that fetches data.

**Solution:**

```typescript
interface WithDataFetchingProps {
  loading: boolean;
  error: Error | null;
  data: any;
}

function withDataFetching<P extends object>(
  WrappedComponent: React.ComponentType<P & WithDataFetchingProps>,
  fetchData: () => Promise<any>
) {
  return function WithDataFetchingComponent(props: P) {
    const [loading, setLoading] = useState(true);
    const [error, setError] = useState<Error | null>(null);
    const [data, setData] = useState(null);
    
    useEffect(() => {
      fetchData()
        .then(setData)
        .catch(setError)
        .finally(() => setLoading(false));
    }, []);
    
    if (loading) return <div>Loading...</div>;
    if (error) return <div>Error: {error.message}</div>;
    
    return <WrappedComponent {...props} loading={loading} error={error} data={data} />;
  };
}

// Usage
const UserProfile = ({ data, loading, error }: { data: any } & WithDataFetchingProps) => (
  <div>{data?.name}</div>
);

const UserProfileWithData = withDataFetching(
  UserProfile,
  () => fetch('/api/user').then(res => res.json())
);
```

### 6.4. Implement a Virtual Scroll List
Design a component that efficiently renders large lists by only rendering visible items.

**Solution:**

```typescript
interface VirtualListProps<T> {
  items: T[];
  itemHeight: number;
  containerHeight: number;
  renderItem: (item: T, index: number) => React.ReactNode;
}

function VirtualList<T>({ items, itemHeight, containerHeight, renderItem }: VirtualListProps<T>) {
  const [scrollTop, setScrollTop] = useState(0);
  const containerRef = useRef<HTMLDivElement>(null);
  
  const visibleStart = Math.floor(scrollTop / itemHeight);
  const visibleEnd = Math.min(
    visibleStart + Math.ceil(containerHeight / itemHeight) + 1,
    items.length
  );
  
  const visibleItems = items.slice(visibleStart, visibleEnd);
  const totalHeight = items.length * itemHeight;
  const offsetY = visibleStart * itemHeight;
  
  return (
    <div
      ref={containerRef}
      style={{ height: containerHeight, overflow: 'auto' }}
      onScroll={(e) => setScrollTop(e.currentTarget.scrollTop)}
    >
      <div style={{ height: totalHeight, position: 'relative' }}>
        <div style={{ transform: `translateY(${offsetY}px)` }}>
          {visibleItems.map((item, index) => (
            <div key={visibleStart + index} style={{ height: itemHeight }}>
              {renderItem(item, visibleStart + index)}
            </div>
          ))}
        </div>
      </div>
    </div>
  );
}

// Usage
const LargeList = () => {
  const items = Array.from({ length: 10000 }, (_, i) => ({ id: i, name: `Item ${i}` }));
  
  return (
    <VirtualList
      items={items}
      itemHeight={50}
      containerHeight={400}
      renderItem={(item) => <div>{item.name}</div>}
    />
  );
};
```

### 6.5. Build a Form Builder
Create a dynamic form system with validation, conditional fields, and TypeScript type safety for form values.

**Solution:**

```typescript
interface FormField {
  name: string;
  type: 'text' | 'email' | 'select' | 'checkbox';
  label: string;
  required?: boolean;
  options?: string[];
  condition?: (values: any) => boolean;
  validation?: (value: any) => string | null;
}

interface FormBuilderProps {
  fields: FormField[];
  onSubmit: (values: any) => void;
}

function FormBuilder({ fields, onSubmit }: FormBuilderProps) {
  const [values, setValues] = useState<Record<string, any>>({});
  const [errors, setErrors] = useState<Record<string, string>>({});
  
  const handleChange = (name: string, value: any) => {
    setValues(prev => ({ ...prev, [name]: value }));
    
    // Clear error when user starts typing
    if (errors[name]) {
      setErrors(prev => ({ ...prev, [name]: '' }));
    }
  };
  
  const validate = () => {
    const newErrors: Record<string, string> = {};
    
    fields.forEach(field => {
      const value = values[field.name];
      
      if (field.required && (!value || value === '')) {
        newErrors[field.name] = `${field.label} is required`;
      }
      
      if (field.validation && value) {
        const error = field.validation(value);
        if (error) newErrors[field.name] = error;
      }
    });
    
    setErrors(newErrors);
    return Object.keys(newErrors).length === 0;
  };
  
  const handleSubmit = (e: React.FormEvent) => {
    e.preventDefault();
    if (validate()) {
      onSubmit(values);
    }
  };
  
  const visibleFields = fields.filter(field => 
    !field.condition || field.condition(values)
  );
  
  return (
    <form onSubmit={handleSubmit}>
      {visibleFields.map(field => (
        <div key={field.name}>
          <label>{field.label}</label>
          {field.type === 'text' || field.type === 'email' ? (
            <input
              type={field.type}
              value={values[field.name] || ''}
              onChange={(e) => handleChange(field.name, e.target.value)}
            />
          ) : field.type === 'select' ? (
            <select
              value={values[field.name] || ''}
              onChange={(e) => handleChange(field.name, e.target.value)}
            >
              <option value="">Select...</option>
              {field.options?.map(option => (
                <option key={option} value={option}>{option}</option>
              ))}
            </select>
          ) : (
            <input
              type="checkbox"
              checked={values[field.name] || false}
              onChange={(e) => handleChange(field.name, e.target.checked)}
            />
          )}
          {errors[field.name] && <span style={{ color: 'red' }}>{errors[field.name]}</span>}
        </div>
      ))}
      <button type="submit">Submit</button>
    </form>
  );
}

// Usage
const MyForm = () => {
  const fields: FormField[] = [
    { name: 'name', type: 'text', label: 'Name', required: true },
    { name: 'email', type: 'email', label: 'Email', required: true, 
      validation: (value) => !/\S+@\S+\.\S+/.test(value) ? 'Invalid email' : null },
    { name: 'country', type: 'select', label: 'Country', options: ['US', 'CA', 'UK'] },
    { name: 'subscribe', type: 'checkbox', label: 'Subscribe to newsletter' },
    { name: 'phone', type: 'text', label: 'Phone', 
      condition: (values) => values.country === 'US' }
  ];
  
  return (
    <FormBuilder
      fields={fields}
      onSubmit={(values) => console.log(values)}
    />
  );
};
```

---

## 7. Behavioral & Scenario-Based

### 7.1. Your React application is experiencing slow rendering. Walk through your debugging process.

**Answer:**
1. **Identify the Problem:**
   - Use React DevTools Profiler to measure component render times
   - Check for unnecessary re-renders using React DevTools highlight updates
   - Monitor bundle size and initial load time
   - Use browser DevTools Performance tab to identify bottlenecks

2. **Common Causes & Solutions:**
   - **Unnecessary Re-renders:** Use `React.memo()`, `useMemo()`, `useCallback()` to prevent unnecessary renders
   - **Large Lists:** Implement virtualization with libraries like `react-window` or `react-virtualized`
   - **Heavy Computations:** Move expensive calculations to `useMemo()` or Web Workers
   - **Large Bundle Size:** Implement code splitting with `React.lazy()` and `Suspense`
   - **Memory Leaks:** Check for uncleaned event listeners, timers, or subscriptions

3. **Debugging Tools:**
   - React DevTools Profiler
   - Chrome DevTools Performance tab
   - Bundle analyzers (webpack-bundle-analyzer)
   - Lighthouse for performance audits

4. **Example Debugging Process:**
   ```javascript
   // Before: Component re-renders on every parent update
   const ExpensiveComponent = ({ data, filter }) => {
     const processedData = data.filter(item => item.category === filter)
       .map(item => expensiveTransformation(item));
     return <div>{processedData.map(item => <Item key={item.id} data={item} />)}</div>;
   };

   // After: Optimized with memoization
   const ExpensiveComponent = React.memo(({ data, filter }) => {
     const processedData = useMemo(() => 
       data.filter(item => item.category === filter)
         .map(item => expensiveTransformation(item)), 
       [data, filter]
     );
     
     const renderItem = useCallback((item) => <Item key={item.id} data={item} />, []);
     
     return <div>{processedData.map(renderItem)}</div>;
   });
   ```

### 7.2. How would you approach migrating a large JavaScript codebase to TypeScript?

**Answer:**
1. **Planning Phase:**
   - **Assessment:** Audit the codebase to identify complexity, dependencies, and potential challenges
   - **Strategy:** Choose between gradual migration (file-by-file) vs. big-bang approach
   - **Timeline:** Create a realistic timeline with milestones and rollback plans
   - **Team Training:** Ensure team is familiar with TypeScript concepts and best practices

2. **Setup & Configuration:**
   ```json
   // tsconfig.json - Start with loose settings, gradually tighten
   {
     "compilerOptions": {
       "allowJs": true,
       "checkJs": false,
       "noImplicitAny": false,
       "strict": false,
       "skipLibCheck": true
     },
     "include": ["src/**/*"],
     "exclude": ["node_modules", "dist"]
   }
   ```

3. **Migration Strategy:**
   - **Phase 1:** Rename `.js` files to `.ts` (allowJs: true)
   - **Phase 2:** Add basic type annotations for function parameters and returns
   - **Phase 3:** Create interfaces for complex objects and API responses
   - **Phase 4:** Add generic types and advanced TypeScript features
   - **Phase 5:** Enable strict mode gradually

4. **Practical Steps:**
   ```javascript
   // Before: JavaScript
   function processUserData(userData) {
     return userData.map(user => ({
       id: user.id,
       name: user.firstName + ' ' + user.lastName,
       email: user.email.toLowerCase()
     }));
   }

   // After: TypeScript
   interface User {
     id: number;
     firstName: string;
     lastName: string;
     email: string;
   }

   interface ProcessedUser {
     id: number;
     name: string;
     email: string;
   }

   function processUserData(userData: User[]): ProcessedUser[] {
     return userData.map(user => ({
       id: user.id,
       name: `${user.firstName} ${user.lastName}`,
       email: user.email.toLowerCase()
     }));
   }
   ```

5. **Challenges & Solutions:**
   - **Third-party Libraries:** Use `@types/` packages or create custom `.d.ts` files
   - **Dynamic Properties:** Use index signatures or `Record<string, any>`
   - **Complex Legacy Code:** Start with `any` type and gradually add proper types
   - **Build Process:** Update build tools (Webpack, Babel) to handle TypeScript

6. **Best Practices:**
   - Start with utility functions and data models
   - Use `// @ts-ignore` sparingly and with comments explaining why
   - Create shared type definitions for common interfaces
   - Set up ESLint rules for TypeScript
   - Use gradual strict mode enabling

### 7.3. You're building a dashboard with real-time updates, complex filtering, and must support 1000+ concurrent users. Describe your architecture.

**Answer:**

**Frontend Architecture:**
1. **Framework & State Management:**
   - React with TypeScript for type safety
   - Redux Toolkit + RTK Query for state management and caching
   - React Query for server state synchronization
   - Zustand for lightweight local state

2. **Real-time Updates:**
   ```javascript
   // WebSocket connection with reconnection logic
   const useWebSocket = (url) => {
     const [socket, setSocket] = useState(null);
     const [connectionStatus, setConnectionStatus] = useState('disconnected');
     
     useEffect(() => {
       const ws = new WebSocket(url);
       
       ws.onopen = () => setConnectionStatus('connected');
       ws.onclose = () => {
         setConnectionStatus('disconnected');
         // Auto-reconnect with exponential backoff
         setTimeout(() => setSocket(new WebSocket(url)), 1000);
       };
       
       setSocket(ws);
       return () => ws.close();
     }, [url]);
     
     return { socket, connectionStatus };
   };
   ```

3. **Performance Optimizations:**
   - Virtual scrolling for large datasets (react-window)
   - Debounced search and filtering
   - Memoized components with React.memo
   - Code splitting with React.lazy
   - Service Worker for offline capabilities

**Backend Architecture:**
1. **API Design:**
   - RESTful APIs with GraphQL for complex queries
   - WebSocket server for real-time updates
   - Rate limiting and authentication middleware
   - API versioning strategy

2. **Database Strategy:**
   ```sql
   -- Optimized queries with proper indexing
   CREATE INDEX idx_dashboard_data_timestamp ON dashboard_data(timestamp);
   CREATE INDEX idx_dashboard_data_user_id ON dashboard_data(user_id);
   CREATE INDEX idx_dashboard_data_category ON dashboard_data(category);
   ```

3. **Caching Layer:**
   - Redis for session management and real-time data
   - CDN for static assets
   - Application-level caching with TTL
   - Database query result caching

**Scalability Considerations:**
1. **Load Balancing:**
   - Horizontal scaling with multiple server instances
   - Load balancer with sticky sessions for WebSocket connections
   - Database read replicas for query distribution

2. **Microservices Architecture:**
   ```
   ┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
   │   Auth Service  │    │  Data Service   │    │  Real-time      │
   │                 │    │                 │    │  Service        │
   └─────────────────┘    └─────────────────┘    └─────────────────┘
           │                       │                       │
           └───────────────────────┼───────────────────────┘
                                   │
                    ┌─────────────────┐
                    │   API Gateway   │
                    │   (Rate Limit,  │
                    │   Auth, Routing)│
                    └─────────────────┘
   ```

3. **Monitoring & Observability:**
   - Application Performance Monitoring (APM)
   - Real-time metrics with Prometheus + Grafana
   - Error tracking with Sentry
   - Log aggregation with ELK stack

**Security & Performance:**
1. **Authentication:**
   - JWT tokens with refresh mechanism
   - Role-based access control (RBAC)
   - API key management for external integrations

2. **Data Flow:**
   ```javascript
   // Optimized data fetching with caching
   const useDashboardData = (filters) => {
     return useQuery({
       queryKey: ['dashboard', filters],
       queryFn: () => fetchDashboardData(filters),
       staleTime: 30000, // 30 seconds
       cacheTime: 300000, // 5 minutes
       refetchOnWindowFocus: false,
     });
   };
   ```

3. **Real-time Data Pipeline:**
   - WebSocket connections with connection pooling
   - Message queuing (Redis Pub/Sub or RabbitMQ)
   - Data streaming with Apache Kafka for high-volume updates
   - Client-side data synchronization with conflict resolution

### 7.4. What do you look for during code reviews? How do you balance perfectionism with pragmatism?

**Answer:**

**Code Review Checklist:**

1. **Functionality & Logic:**
   - Does the code solve the intended problem?
   - Are edge cases handled appropriately?
   - Is error handling comprehensive?
   - Are there any potential security vulnerabilities?

2. **Code Quality:**
   - **Readability:** Clear variable names, proper comments, logical structure
   - **Maintainability:** Modular design, single responsibility principle
   - **Performance:** Efficient algorithms, proper use of React optimization techniques
   - **Type Safety:** Proper TypeScript usage, avoiding `any` types

3. **React-Specific Considerations:**
   ```javascript
   // Good: Proper dependency array
   useEffect(() => {
     fetchData(userId);
   }, [userId]);

   // Bad: Missing dependency
   useEffect(() => {
     fetchData(userId);
   }, []); // userId changes won't trigger refetch

   // Good: Memoized expensive calculation
   const expensiveValue = useMemo(() => {
     return heavyCalculation(data);
   }, [data]);

   // Bad: Recalculated on every render
   const expensiveValue = heavyCalculation(data);
   ```

4. **Testing & Documentation:**
   - Are there appropriate unit tests?
   - Is the code self-documenting?
   - Are complex business logic explained?

**Balancing Perfectionism vs. Pragmatism:**

1. **Must-Fix Issues (Non-negotiable):**
   - Security vulnerabilities
   - Performance bottlenecks
   - Breaking changes without proper migration
   - Accessibility violations
   - Type safety issues that could cause runtime errors

2. **Should-Fix Issues (Important but flexible):**
   - Code style inconsistencies
   - Missing error handling
   - Inefficient algorithms
   - Poor naming conventions

3. **Nice-to-Have Issues (Pragmatic approach):**
   - Minor style preferences
   - Over-engineering for simple problems
   - Perfect test coverage vs. adequate coverage
   - Micro-optimizations with minimal impact

**Example Review Process:**
```javascript
// Before Review: Multiple issues
const UserList = ({ users, onUserClick }) => {
  const [filteredUsers, setFilteredUsers] = useState([]);
  
  useEffect(() => {
    const filtered = users.filter(user => user.active);
    setFilteredUsers(filtered);
  }, [users]); // Missing dependency on filter logic
  
  return (
    <div>
      {filteredUsers.map(user => (
        <div key={user.id} onClick={() => onUserClick(user)}>
          {user.name}
        </div>
      ))}
    </div>
  );
};

// After Review: Improved version
interface User {
  id: string;
  name: string;
  active: boolean;
}

interface UserListProps {
  users: User[];
  onUserClick: (user: User) => void;
  showActiveOnly?: boolean;
}

const UserList: React.FC<UserListProps> = ({ 
  users, 
  onUserClick, 
  showActiveOnly = false 
}) => {
  const filteredUsers = useMemo(() => {
    return showActiveOnly 
      ? users.filter(user => user.active)
      : users;
  }, [users, showActiveOnly]);

  const handleUserClick = useCallback((user: User) => {
    onUserClick(user);
  }, [onUserClick]);

  if (filteredUsers.length === 0) {
    return <div>No users found</div>;
  }

  return (
    <div role="list">
      {filteredUsers.map(user => (
        <div 
          key={user.id} 
          onClick={() => handleUserClick(user)}
          role="listitem"
          tabIndex={0}
          onKeyDown={(e) => e.key === 'Enter' && handleUserClick(user)}
        >
          {user.name}
        </div>
      ))}
    </div>
  );
};
```

**Review Communication:**
- **Constructive Feedback:** Focus on the code, not the person
- **Explain the "Why":** Don't just say "this is wrong," explain the reasoning
- **Suggest Alternatives:** Provide concrete examples of better approaches
- **Acknowledge Good Practices:** Recognize when code follows best practices

**Pragmatic Decision Framework:**
1. **Impact Assessment:** How critical is this issue?
2. **Effort vs. Benefit:** Is the fix worth the time investment?
3. **Timeline Constraints:** Does the deadline allow for perfection?
4. **Technical Debt:** Will this create future maintenance issues?
5. **Team Standards:** What are the established coding standards?

### 7.5. How do you identify and prioritize technical debt? Give an example of when you advocated for refactoring.

**Answer:**

**Identifying Technical Debt:**

1. **Code Smells:**
   - **Duplicated Code:** Same logic repeated across multiple files
   - **Long Methods:** Functions exceeding 20-30 lines
   - **Large Classes/Components:** Components with too many responsibilities
   - **Deep Nesting:** Complex conditional logic or deeply nested components
   - **Magic Numbers/Strings:** Hardcoded values without constants
   - **Dead Code:** Unused imports, functions, or components

2. **Performance Indicators:**
   - Slow build times
   - Large bundle sizes
   - Memory leaks
   - Slow test execution
   - Frequent production bugs

3. **Maintenance Pain Points:**
   - Difficult to add new features
   - High bug rate in specific areas
   - Developer onboarding challenges
   - Frequent merge conflicts

**Prioritization Framework:**

1. **Impact vs. Effort Matrix:**
   ```
   High Impact, Low Effort    |  High Impact, High Effort
   (Quick Wins)              |  (Strategic Projects)
   --------------------------|--------------------------
   Low Impact, Low Effort    |  Low Impact, High Effort
   (Nice to Have)           |  (Avoid)
   ```

2. **Risk Assessment:**
   - **High Risk:** Security vulnerabilities, performance bottlenecks
   - **Medium Risk:** Code maintainability, developer productivity
   - **Low Risk:** Code style, minor optimizations

3. **Business Value:**
   - Customer-facing impact
   - Developer productivity gains
   - Future feature development speed
   - Maintenance cost reduction

**Example: Advocating for Refactoring**

**Situation:** A React application had a 2000-line `UserDashboard` component that was becoming increasingly difficult to maintain.

**Problems Identified:**
```javascript
// Before: Monolithic component with multiple responsibilities
const UserDashboard = () => {
  // 2000+ lines of code handling:
  // - User data fetching
  // - Chart rendering
  // - Form validation
  // - Real-time updates
  // - Export functionality
  // - Multiple state management patterns
  
  const [users, setUsers] = useState([]);
  const [charts, setCharts] = useState({});
  const [filters, setFilters] = useState({});
  const [exportData, setExportData] = useState(null);
  // ... 50+ more state variables
  
  // Mixed concerns: API calls, UI logic, business logic
  const fetchUsers = async () => { /* 100+ lines */ };
  const renderChart = () => { /* 200+ lines */ };
  const validateForm = () => { /* 150+ lines */ };
  const handleExport = () => { /* 100+ lines */ };
  
  return (
    <div>
      {/* 500+ lines of JSX */}
    </div>
  );
};
```

**Advocacy Approach:**

1. **Data Collection:**
   - Measured bug rate: 3x higher in this component
   - Developer time: 2x longer to add new features
   - Code review time: 4x longer than average
   - Test coverage: Only 30% due to complexity

2. **Business Case:**
   - **Cost:** 2 weeks of refactoring effort
   - **Benefit:** 50% reduction in bug rate, 40% faster feature development
   - **ROI:** Break-even in 3 months, significant long-term savings

3. **Proposed Solution:**
```javascript
// After: Modular architecture
const UserDashboard = () => {
  return (
    <DashboardLayout>
      <UserDataProvider>
        <UserFilters />
        <UserCharts />
        <UserTable />
        <ExportPanel />
      </UserDataProvider>
    </DashboardLayout>
  );
};

// Separated concerns into focused components
const UserDataProvider = ({ children }) => {
  const { users, loading, error } = useUsers();
  const { filters, updateFilters } = useFilters();
  const { exportData, handleExport } = useExport();
  
  return (
    <UserDataContext.Provider value={{
      users, loading, error, filters, updateFilters, exportData, handleExport
    }}>
      {children}
    </UserDataContext.Provider>
  );
};

const UserCharts = () => {
  const { users, filters } = useUserData();
  const chartData = useMemo(() => 
    processChartData(users, filters), [users, filters]
  );
  
  return (
    <div className="charts-container">
      <RevenueChart data={chartData.revenue} />
      <UserGrowthChart data={chartData.growth} />
      <ActivityChart data={chartData.activity} />
    </div>
  );
};
```

4. **Implementation Strategy:**
   - **Phase 1:** Extract data fetching logic into custom hooks
   - **Phase 2:** Break down UI into smaller components
   - **Phase 3:** Implement proper state management
   - **Phase 4:** Add comprehensive testing
   - **Phase 5:** Performance optimization

**Results:**
- **Code Reduction:** 2000 lines → 5 focused components (~200 lines each)
- **Bug Rate:** Reduced by 60%
- **Feature Development:** 40% faster
- **Test Coverage:** Increased to 85%
- **Developer Satisfaction:** Significantly improved

**Key Lessons:**
1. **Quantify the Problem:** Use metrics to support your case
2. **Propose Incremental Solutions:** Break large refactoring into phases
3. **Demonstrate Business Value:** Show ROI and long-term benefits
4. **Get Stakeholder Buy-in:** Involve team leads and product managers
5. **Plan for Maintenance:** Ensure ongoing commitment to prevent regression

---

## 8. Best Practices & Patterns

### 8.1. What are your preferred patterns for handling side effects in React?

**Answer:**

**1. useEffect Hook Patterns:**

```javascript
// Basic data fetching pattern
const useUserData = (userId) => {
  const [user, setUser] = useState(null);
  const [loading, setLoading] = useState(true);
  const [error, setError] = useState(null);

  useEffect(() => {
    let cancelled = false;
    
    const fetchUser = async () => {
      try {
        setLoading(true);
        setError(null);
        const userData = await api.getUser(userId);
        
        if (!cancelled) {
          setUser(userData);
        }
      } catch (err) {
        if (!cancelled) {
          setError(err.message);
        }
      } finally {
        if (!cancelled) {
          setLoading(false);
        }
      }
    };

    fetchUser();
    
    return () => {
      cancelled = true; // Cleanup to prevent state updates on unmounted component
    };
  }, [userId]);

  return { user, loading, error };
};
```

**2. Custom Hooks for Reusable Side Effects:**

```javascript
// Debounced search hook
const useDebounce = (value, delay) => {
  const [debouncedValue, setDebouncedValue] = useState(value);

  useEffect(() => {
    const handler = setTimeout(() => {
      setDebouncedValue(value);
    }, delay);

    return () => {
      clearTimeout(handler);
    };
  }, [value, delay]);

  return debouncedValue;
};

// Usage
const SearchComponent = () => {
  const [searchTerm, setSearchTerm] = useState('');
  const debouncedSearchTerm = useDebounce(searchTerm, 300);
  const { results, loading } = useSearchResults(debouncedSearchTerm);

  return (
    <div>
      <input 
        value={searchTerm}
        onChange={(e) => setSearchTerm(e.target.value)}
        placeholder="Search..."
      />
      {loading && <div>Searching...</div>}
      {results.map(result => <div key={result.id}>{result.title}</div>)}
    </div>
  );
};
```

**3. Event Listeners and Cleanup:**

```javascript
const useWindowSize = () => {
  const [windowSize, setWindowSize] = useState({
    width: window.innerWidth,
    height: window.innerHeight,
  });

  useEffect(() => {
    const handleResize = () => {
      setWindowSize({
        width: window.innerWidth,
        height: window.innerHeight,
      });
    };

    window.addEventListener('resize', handleResize);
    
    return () => {
      window.removeEventListener('resize', handleResize);
    };
  }, []);

  return windowSize;
};
```

**4. Subscription Management:**

```javascript
const useWebSocket = (url) => {
  const [socket, setSocket] = useState(null);
  const [lastMessage, setLastMessage] = useState(null);
  const [connectionStatus, setConnectionStatus] = useState('disconnected');

  useEffect(() => {
    const ws = new WebSocket(url);
    
    ws.onopen = () => {
      setConnectionStatus('connected');
      setSocket(ws);
    };
    
    ws.onmessage = (event) => {
      setLastMessage(JSON.parse(event.data));
    };
    
    ws.onclose = () => {
      setConnectionStatus('disconnected');
      setSocket(null);
    };
    
    ws.onerror = (error) => {
      console.error('WebSocket error:', error);
      setConnectionStatus('error');
    };

    return () => {
      ws.close();
    };
  }, [url]);

  const sendMessage = useCallback((message) => {
    if (socket && socket.readyState === WebSocket.OPEN) {
      socket.send(JSON.stringify(message));
    }
  }, [socket]);

  return { lastMessage, connectionStatus, sendMessage };
};
```

**5. Advanced Patterns with useReducer:**

```javascript
const dataFetchReducer = (state, action) => {
  switch (action.type) {
    case 'FETCH_INIT':
      return {
        ...state,
        loading: true,
        error: null,
      };
    case 'FETCH_SUCCESS':
      return {
        ...state,
        loading: false,
        data: action.payload,
        error: null,
      };
    case 'FETCH_FAILURE':
      return {
        ...state,
        loading: false,
        error: action.payload,
      };
    default:
      throw new Error(`Unhandled action type: ${action.type}`);
  }
};

const useDataFetcher = (initialUrl) => {
  const [url, setUrl] = useState(initialUrl);
  const [state, dispatch] = useReducer(dataFetchReducer, {
    data: null,
    loading: false,
    error: null,
  });

  useEffect(() => {
    let cancelled = false;

    const fetchData = async () => {
      dispatch({ type: 'FETCH_INIT' });

      try {
        const result = await fetch(url);
        const data = await result.json();
        
        if (!cancelled) {
          dispatch({ type: 'FETCH_SUCCESS', payload: data });
        }
      } catch (error) {
        if (!cancelled) {
          dispatch({ type: 'FETCH_FAILURE', payload: error.message });
        }
      }
    };

    if (url) {
      fetchData();
    }

    return () => {
      cancelled = true;
    };
  }, [url]);

  return { ...state, setUrl };
};
```

**6. Best Practices:**

- **Always provide cleanup functions** to prevent memory leaks
- **Use dependency arrays correctly** to avoid infinite loops
- **Extract complex side effects into custom hooks** for reusability
- **Handle loading and error states** consistently
- **Use useCallback and useMemo** to prevent unnecessary re-renders
- **Consider using libraries** like React Query for complex data fetching scenarios

### 8.2. How do you ensure type safety when working with external APIs?

**Answer:**

**1. API Response Type Definitions:**

```typescript
// Define API response types
interface User {
  id: number;
  name: string;
  email: string;
  avatar?: string;
  createdAt: string;
  updatedAt: string;
}

interface ApiResponse<T> {
  data: T;
  message: string;
  status: 'success' | 'error';
  timestamp: string;
}

interface PaginatedResponse<T> {
  data: T[];
  pagination: {
    page: number;
    limit: number;
    total: number;
    totalPages: number;
  };
  message: string;
  status: 'success' | 'error';
}

// Specific API response types
type UserResponse = ApiResponse<User>;
type UsersListResponse = PaginatedResponse<User>;
```

**2. API Client with Type Safety:**

```typescript
class ApiClient {
  private baseURL: string;
  private defaultHeaders: Record<string, string>;

  constructor(baseURL: string) {
    this.baseURL = baseURL;
    this.defaultHeaders = {
      'Content-Type': 'application/json',
    };
  }

  private async request<T>(
    endpoint: string,
    options: RequestInit = {}
  ): Promise<T> {
    const url = `${this.baseURL}${endpoint}`;
    const config: RequestInit = {
      ...options,
      headers: {
        ...this.defaultHeaders,
        ...options.headers,
      },
    };

    try {
      const response = await fetch(url, config);
      
      if (!response.ok) {
        throw new Error(`HTTP error! status: ${response.status}`);
      }

      const data = await response.json();
      return data as T;
    } catch (error) {
      console.error('API request failed:', error);
      throw error;
    }
  }

  // Typed API methods
  async getUsers(page: number = 1, limit: number = 10): Promise<UsersListResponse> {
    return this.request<UsersListResponse>(`/users?page=${page}&limit=${limit}`);
  }

  async getUser(id: number): Promise<UserResponse> {
    return this.request<UserResponse>(`/users/${id}`);
  }

  async createUser(userData: Omit<User, 'id' | 'createdAt' | 'updatedAt'>): Promise<UserResponse> {
    return this.request<UserResponse>('/users', {
      method: 'POST',
      body: JSON.stringify(userData),
    });
  }

  async updateUser(id: number, userData: Partial<User>): Promise<UserResponse> {
    return this.request<UserResponse>(`/users/${id}`, {
      method: 'PUT',
      body: JSON.stringify(userData),
    });
  }
}
```

**3. Runtime Validation with Zod:**

```typescript
import { z } from 'zod';

// Define schemas for runtime validation
const UserSchema = z.object({
  id: z.number(),
  name: z.string().min(1),
  email: z.string().email(),
  avatar: z.string().url().optional(),
  createdAt: z.string().datetime(),
  updatedAt: z.string().datetime(),
});

const ApiResponseSchema = z.object({
  data: z.any(),
  message: z.string(),
  status: z.enum(['success', 'error']),
  timestamp: z.string(),
});

// Type-safe API client with validation
class ValidatedApiClient extends ApiClient {
  async getUsers(page: number = 1, limit: number = 10): Promise<UsersListResponse> {
    const response = await this.request(`/users?page=${page}&limit=${limit}`);
    
    // Runtime validation
    const validatedResponse = ApiResponseSchema.parse(response);
    
    // Validate the data array
    if (Array.isArray(validatedResponse.data)) {
      validatedResponse.data.forEach(user => UserSchema.parse(user));
    }
    
    return validatedResponse as UsersListResponse;
  }

  async getUser(id: number): Promise<UserResponse> {
    const response = await this.request(`/users/${id}`);
    
    // Validate the response structure
    const validatedResponse = ApiResponseSchema.parse(response);
    
    // Validate the user data
    const validatedUser = UserSchema.parse(validatedResponse.data);
    
    return {
      ...validatedResponse,
      data: validatedUser,
    } as UserResponse;
  }
}
```

**4. React Hooks with Type Safety:**

```typescript
// Custom hook for API calls
const useApi = <T>(apiCall: () => Promise<T>) => {
  const [data, setData] = useState<T | null>(null);
  const [loading, setLoading] = useState(true);
  const [error, setError] = useState<string | null>(null);

  useEffect(() => {
    let cancelled = false;

    const fetchData = async () => {
      try {
        setLoading(true);
        setError(null);
        const result = await apiCall();
        
        if (!cancelled) {
          setData(result);
        }
      } catch (err) {
        if (!cancelled) {
          setError(err instanceof Error ? err.message : 'An error occurred');
        }
      } finally {
        if (!cancelled) {
          setLoading(false);
        }
      }
    };

    fetchData();

    return () => {
      cancelled = true;
    };
  }, [apiCall]);

  return { data, loading, error };
};

// Usage with type safety
const UserProfile: React.FC<{ userId: number }> = ({ userId }) => {
  const { data: userResponse, loading, error } = useApi<UserResponse>(
    () => apiClient.getUser(userId)
  );

  if (loading) return <div>Loading...</div>;
  if (error) return <div>Error: {error}</div>;
  if (!userResponse?.data) return <div>User not found</div>;

  const user = userResponse.data; // TypeScript knows this is a User

  return (
    <div>
      <h1>{user.name}</h1>
      <p>{user.email}</p>
      {user.avatar && <img src={user.avatar} alt={user.name} />}
    </div>
  );
};
```

**5. Error Handling with Discriminated Unions:**

```typescript
// Define error types
interface ApiError {
  type: 'API_ERROR';
  message: string;
  statusCode: number;
  details?: Record<string, any>;
}

interface ValidationError {
  type: 'VALIDATION_ERROR';
  message: string;
  field: string;
  value: any;
}

interface NetworkError {
  type: 'NETWORK_ERROR';
  message: string;
  originalError: Error;
}

type ApiResult<T> = 
  | { success: true; data: T }
  | { success: false; error: ApiError | ValidationError | NetworkError };

// Type-safe error handling
const safeApiCall = async <T>(
  apiCall: () => Promise<T>
): Promise<ApiResult<T>> => {
  try {
    const data = await apiCall();
    return { success: true, data };
  } catch (error) {
    if (error instanceof TypeError && error.message.includes('fetch')) {
      return {
        success: false,
        error: {
          type: 'NETWORK_ERROR',
          message: 'Network request failed',
          originalError: error,
        },
      };
    }

    if (error instanceof z.ZodError) {
      return {
        success: false,
        error: {
          type: 'VALIDATION_ERROR',
          message: 'Data validation failed',
          field: error.errors[0]?.path.join('.') || 'unknown',
          value: error.errors[0]?.received,
        },
      };
    }

    return {
      success: false,
      error: {
        type: 'API_ERROR',
        message: error instanceof Error ? error.message : 'Unknown error',
        statusCode: 500,
      },
    };
  }
};
```

**6. Best Practices:**

- **Always define interfaces** for API responses
- **Use runtime validation** with libraries like Zod or Yup
- **Implement proper error handling** with discriminated unions
- **Create type-safe API clients** with generic methods
- **Use custom hooks** to encapsulate API logic
- **Validate data at runtime** to catch API changes
- **Use TypeScript strict mode** for better type checking
- **Document API contracts** and keep types in sync

### 8.3. What's your approach to styling in React applications? (CSS Modules, Styled Components, Tailwind, etc.)

**Answer:**

**1. Tailwind CSS (Preferred Approach):**

```typescript
// Component with Tailwind classes
const Button: React.FC<ButtonProps> = ({ 
  variant = 'primary', 
  size = 'md', 
  children, 
  ...props 
}) => {
  const baseClasses = 'font-medium rounded-lg transition-colors focus:outline-none focus:ring-2 focus:ring-offset-2';
  
  const variantClasses = {
    primary: 'bg-blue-600 text-white hover:bg-blue-700 focus:ring-blue-500',
    secondary: 'bg-gray-200 text-gray-900 hover:bg-gray-300 focus:ring-gray-500',
    danger: 'bg-red-600 text-white hover:bg-red-700 focus:ring-red-500',
  };
  
  const sizeClasses = {
    sm: 'px-3 py-1.5 text-sm',
    md: 'px-4 py-2 text-base',
    lg: 'px-6 py-3 text-lg',
  };

  return (
    <button
      className={`${baseClasses} ${variantClasses[variant]} ${sizeClasses[size]}`}
      {...props}
    >
      {children}
    </button>
  );
};

// Responsive design with Tailwind
const Dashboard: React.FC = () => {
  return (
    <div className="min-h-screen bg-gray-50">
      <header className="bg-white shadow-sm border-b border-gray-200">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="flex justify-between items-center h-16">
            <h1 className="text-xl font-semibold text-gray-900">Dashboard</h1>
            <nav className="hidden md:flex space-x-8">
              <a href="#" className="text-gray-500 hover:text-gray-900">Home</a>
              <a href="#" className="text-gray-500 hover:text-gray-900">Analytics</a>
            </nav>
          </div>
        </div>
      </header>
      
      <main className="max-w-7xl mx-auto py-6 sm:px-6 lg:px-8">
        <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
          <div className="bg-white overflow-hidden shadow rounded-lg">
            <div className="p-5">
              <div className="flex items-center">
                <div className="flex-shrink-0">
                  <div className="w-8 h-8 bg-blue-500 rounded-md flex items-center justify-center">
                    <span className="text-white text-sm font-medium">📊</span>
                  </div>
                </div>
                <div className="ml-5 w-0 flex-1">
                  <dl>
                    <dt className="text-sm font-medium text-gray-500 truncate">
                      Total Revenue
                    </dt>
                    <dd className="text-lg font-medium text-gray-900">
                      $45,231.89
                    </dd>
                  </dl>
                </div>
              </div>
            </div>
          </div>
        </div>
      </main>
    </div>
  );
};
```

**2. CSS Modules:**

```typescript
// Button.module.css
.button {
  @apply font-medium rounded-lg transition-colors focus:outline-none focus:ring-2 focus:ring-offset-2;
}

.primary {
  @apply bg-blue-600 text-white hover:bg-blue-700 focus:ring-blue-500;
}

.secondary {
  @apply bg-gray-200 text-gray-900 hover:bg-gray-300 focus:ring-gray-500;
}

.small {
  @apply px-3 py-1.5 text-sm;
}

.medium {
  @apply px-4 py-2 text-base;
}

.large {
  @apply px-6 py-3 text-lg;
}

// Button.tsx
import styles from './Button.module.css';
import { clsx } from 'clsx';

interface ButtonProps extends React.ButtonHTMLAttributes<HTMLButtonElement> {
  variant?: 'primary' | 'secondary';
  size?: 'small' | 'medium' | 'large';
}

const Button: React.FC<ButtonProps> = ({ 
  variant = 'primary', 
  size = 'medium', 
  className,
  children, 
  ...props 
}) => {
  return (
    <button
      className={clsx(
        styles.button,
        styles[variant],
        styles[size],
        className
      )}
      {...props}
    >
      {children}
    </button>
  );
};
```

**3. Styled Components:**

```typescript
import styled, { css } from 'styled-components';

interface ButtonProps {
  variant?: 'primary' | 'secondary' | 'danger';
  size?: 'sm' | 'md' | 'lg';
  fullWidth?: boolean;
}

const StyledButton = styled.button<ButtonProps>`
  font-weight: 500;
  border-radius: 0.5rem;
  transition: all 0.2s ease-in-out;
  border: none;
  cursor: pointer;
  display: inline-flex;
  align-items: center;
  justify-content: center;
  
  &:focus {
    outline: none;
    box-shadow: 0 0 0 2px rgba(59, 130, 246, 0.5);
  }
  
  ${({ variant = 'primary' }) => {
    switch (variant) {
      case 'primary':
        return css`
          background-color: #2563eb;
          color: white;
          &:hover {
            background-color: #1d4ed8;
          }
        `;
      case 'secondary':
        return css`
          background-color: #e5e7eb;
          color: #111827;
          &:hover {
            background-color: #d1d5db;
          }
        `;
      case 'danger':
        return css`
          background-color: #dc2626;
          color: white;
          &:hover {
            background-color: #b91c1c;
          }
        `;
    }
  }}
  
  ${({ size = 'md' }) => {
    switch (size) {
      case 'sm':
        return css`
          padding: 0.375rem 0.75rem;
          font-size: 0.875rem;
        `;
      case 'md':
        return css`
          padding: 0.5rem 1rem;
          font-size: 1rem;
        `;
      case 'lg':
        return css`
          padding: 0.75rem 1.5rem;
          font-size: 1.125rem;
        `;
    }
  }}
  
  ${({ fullWidth }) =>
    fullWidth &&
    css`
      width: 100%;
    `}
`;

// Theme provider setup
const theme = {
  colors: {
    primary: '#2563eb',
    secondary: '#6b7280',
    success: '#10b981',
    danger: '#dc2626',
  },
  spacing: {
    xs: '0.25rem',
    sm: '0.5rem',
    md: '1rem',
    lg: '1.5rem',
    xl: '2rem',
  },
  breakpoints: {
    mobile: '768px',
    tablet: '1024px',
    desktop: '1280px',
  },
};

const ThemeProvider: React.FC<{ children: React.ReactNode }> = ({ children }) => {
  return <StyledThemeProvider theme={theme}>{children}</StyledThemeProvider>;
};
```

**4. Emotion (CSS-in-JS Alternative):**

```typescript
import { css } from '@emotion/react';
import styled from '@emotion/styled';

// Using css prop
const Card: React.FC = () => {
  return (
    <div
      css={css`
        background: white;
        border-radius: 8px;
        box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1);
        padding: 1.5rem;
        margin-bottom: 1rem;
        
        &:hover {
          box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
          transform: translateY(-2px);
          transition: all 0.2s ease-in-out;
        }
      `}
    >
      <h3
        css={css`
          margin: 0 0 1rem 0;
          color: #1f2937;
          font-size: 1.25rem;
          font-weight: 600;
        `}
      >
        Card Title
      </h3>
      <p
        css={css`
          margin: 0;
          color: #6b7280;
          line-height: 1.5;
        `}
      >
        Card content goes here...
      </p>
    </div>
  );
};

// Using styled components with Emotion
const StyledInput = styled.input`
  width: 100%;
  padding: 0.75rem;
  border: 1px solid #d1d5db;
  border-radius: 0.375rem;
  font-size: 1rem;
  
  &:focus {
    outline: none;
    border-color: #2563eb;
    box-shadow: 0 0 0 3px rgba(37, 99, 235, 0.1);
  }
  
  &::placeholder {
    color: #9ca3af;
  }
`;
```

**5. Design System Approach:**

```typescript
// Design tokens
export const tokens = {
  colors: {
    primary: {
      50: '#eff6ff',
      500: '#3b82f6',
      900: '#1e3a8a',
    },
    gray: {
      50: '#f9fafb',
      500: '#6b7280',
      900: '#111827',
    },
  },
  spacing: {
    xs: '0.25rem',
    sm: '0.5rem',
    md: '1rem',
    lg: '1.5rem',
    xl: '2rem',
  },
  typography: {
    fontFamily: {
      sans: ['Inter', 'system-ui', 'sans-serif'],
      mono: ['JetBrains Mono', 'monospace'],
    },
    fontSize: {
      sm: '0.875rem',
      base: '1rem',
      lg: '1.125rem',
      xl: '1.25rem',
    },
  },
  breakpoints: {
    sm: '640px',
    md: '768px',
    lg: '1024px',
    xl: '1280px',
  },
};

// Utility functions
export const createResponsiveValue = <T>(values: Partial<Record<keyof typeof tokens.breakpoints, T>>) => {
  return Object.entries(values)
    .map(([breakpoint, value]) => {
      const minWidth = tokens.breakpoints[breakpoint as keyof typeof tokens.breakpoints];
      return `@media (min-width: ${minWidth}) { ${value} }`;
    })
    .join(' ');
};
```

**6. Best Practices & Recommendations:**

**When to use each approach:**

- **Tailwind CSS:** Best for rapid prototyping, consistent design systems, and utility-first development
- **CSS Modules:** Good for component-scoped styles with traditional CSS syntax
- **Styled Components:** Ideal for dynamic styling based on props and complex component logic
- **Emotion:** Great alternative to Styled Components with better performance
- **CSS-in-JS:** Best for applications requiring runtime theming and dynamic styles

**General Guidelines:**

1. **Consistency:** Choose one primary approach and stick to it
2. **Performance:** Consider bundle size and runtime performance
3. **Developer Experience:** Ensure good TypeScript support and tooling
4. **Maintainability:** Use design tokens and consistent naming conventions
5. **Accessibility:** Ensure styles support keyboard navigation and screen readers
6. **Responsive Design:** Always consider mobile-first approach
7. **Theme Support:** Plan for dark mode and theme switching if needed

### 8.4. How do you handle internationalization (i18n) and accessibility (a11y) in React apps?

**Answer:**

**1. Internationalization (i18n) with react-i18next:**

```typescript
// i18n configuration
import i18n from 'i18next';
import { initReactI18next } from 'react-i18next';
import LanguageDetector from 'i18next-browser-languagedetector';

// Translation resources
const resources = {
  en: {
    translation: {
      welcome: 'Welcome',
      hello: 'Hello {{name}}!',
      buttons: {
        save: 'Save',
        cancel: 'Cancel',
        delete: 'Delete',
      },
      messages: {
        success: 'Operation completed successfully',
        error: 'An error occurred',
        confirm: 'Are you sure you want to delete this item?',
      },
      navigation: {
        home: 'Home',
        about: 'About',
        contact: 'Contact',
      },
    },
  },
  es: {
    translation: {
      welcome: 'Bienvenido',
      hello: '¡Hola {{name}}!',
      buttons: {
        save: 'Guardar',
        cancel: 'Cancelar',
        delete: 'Eliminar',
      },
      messages: {
        success: 'Operación completada exitosamente',
        error: 'Ocurrió un error',
        confirm: '¿Estás seguro de que quieres eliminar este elemento?',
      },
      navigation: {
        home: 'Inicio',
        about: 'Acerca de',
        contact: 'Contacto',
      },
    },
  },
};

i18n
  .use(LanguageDetector)
  .use(initReactI18next)
  .init({
    resources,
    fallbackLng: 'en',
    debug: process.env.NODE_ENV === 'development',
    
    interpolation: {
      escapeValue: false, // React already escapes values
    },
    
    detection: {
      order: ['localStorage', 'navigator', 'htmlTag'],
      caches: ['localStorage'],
    },
  });

export default i18n;
```

**2. Using i18n in Components:**

```typescript
import { useTranslation } from 'react-i18next';

// Basic usage
const WelcomePage: React.FC = () => {
  const { t, i18n } = useTranslation();

  const changeLanguage = (lng: string) => {
    i18n.changeLanguage(lng);
  };

  return (
    <div>
      <h1>{t('welcome')}</h1>
      <p>{t('hello', { name: 'John' })}</p>
      
      <div>
        <button onClick={() => changeLanguage('en')}>English</button>
        <button onClick={() => changeLanguage('es')}>Español</button>
      </div>
    </div>
  );
};

// Advanced usage with namespaces
const UserProfile: React.FC = () => {
  const { t } = useTranslation(['user', 'common']);
  
  return (
    <div>
      <h2>{t('user:profile.title')}</h2>
      <p>{t('user:profile.description')}</p>
      <button>{t('common:buttons.save')}</button>
    </div>
  );
};

// Custom hook for complex translations
const useLocalizedDate = (date: Date) => {
  const { i18n } = useTranslation();
  
  return useMemo(() => {
    return new Intl.DateTimeFormat(i18n.language, {
      year: 'numeric',
      month: 'long',
      day: 'numeric',
    }).format(date);
  }, [date, i18n.language]);
};
```

**3. Accessibility (a11y) Implementation:**

```typescript
// Accessible form component
const AccessibleForm: React.FC = () => {
  const [formData, setFormData] = useState({
    name: '',
    email: '',
    message: '',
  });
  const [errors, setErrors] = useState<Record<string, string>>({});

  const handleSubmit = (e: React.FormEvent) => {
    e.preventDefault();
    // Form validation logic
  };

  return (
    <form onSubmit={handleSubmit} noValidate>
      <fieldset>
        <legend>Contact Information</legend>
        
        <div className="form-group">
          <label htmlFor="name" className="required">
            Full Name
            <span className="sr-only"> (required)</span>
          </label>
          <input
            id="name"
            type="text"
            value={formData.name}
            onChange={(e) => setFormData({ ...formData, name: e.target.value })}
            aria-describedby={errors.name ? 'name-error' : undefined}
            aria-invalid={!!errors.name}
            required
          />
          {errors.name && (
            <div id="name-error" role="alert" className="error-message">
              {errors.name}
            </div>
          )}
        </div>

        <div className="form-group">
          <label htmlFor="email" className="required">
            Email Address
            <span className="sr-only"> (required)</span>
          </label>
          <input
            id="email"
            type="email"
            value={formData.email}
            onChange={(e) => setFormData({ ...formData, email: e.target.value })}
            aria-describedby={errors.email ? 'email-error' : undefined}
            aria-invalid={!!errors.email}
            required
          />
          {errors.email && (
            <div id="email-error" role="alert" className="error-message">
              {errors.email}
            </div>
          )}
        </div>

        <div className="form-group">
          <label htmlFor="message">Message</label>
          <textarea
            id="message"
            value={formData.message}
            onChange={(e) => setFormData({ ...formData, message: e.target.value })}
            rows={4}
            aria-describedby="message-help"
          />
          <div id="message-help" className="help-text">
            Please provide details about your inquiry.
          </div>
        </div>

        <button type="submit" className="primary-button">
          Send Message
        </button>
      </fieldset>
    </form>
  );
};
```

**4. Accessible Navigation:**

```typescript
const AccessibleNavigation: React.FC = () => {
  const [isMenuOpen, setIsMenuOpen] = useState(false);
  const menuRef = useRef<HTMLUListElement>(null);
  const buttonRef = useRef<HTMLButtonElement>(null);

  const toggleMenu = () => {
    setIsMenuOpen(!isMenuOpen);
  };

  const closeMenu = () => {
    setIsMenuOpen(false);
    buttonRef.current?.focus();
  };

  // Handle keyboard navigation
  const handleKeyDown = (e: React.KeyboardEvent) => {
    if (e.key === 'Escape') {
      closeMenu();
    }
  };

  // Handle focus management
  useEffect(() => {
    if (isMenuOpen && menuRef.current) {
      const firstMenuItem = menuRef.current.querySelector('a');
      firstMenuItem?.focus();
    }
  }, [isMenuOpen]);

  return (
    <nav role="navigation" aria-label="Main navigation">
      <button
        ref={buttonRef}
        onClick={toggleMenu}
        aria-expanded={isMenuOpen}
        aria-controls="main-menu"
        aria-haspopup="true"
        className="menu-toggle"
      >
        <span className="sr-only">
          {isMenuOpen ? 'Close' : 'Open'} main menu
        </span>
        <span aria-hidden="true">☰</span>
      </button>

      <ul
        ref={menuRef}
        id="main-menu"
        className={`main-menu ${isMenuOpen ? 'open' : ''}`}
        onKeyDown={handleKeyDown}
        role="menubar"
      >
        <li role="none">
          <a href="/" role="menuitem" tabIndex={isMenuOpen ? 0 : -1}>
            Home
          </a>
        </li>
        <li role="none">
          <a href="/about" role="menuitem" tabIndex={isMenuOpen ? 0 : -1}>
            About
          </a>
        </li>
        <li role="none">
          <a href="/contact" role="menuitem" tabIndex={isMenuOpen ? 0 : -1}>
            Contact
          </a>
        </li>
      </ul>
    </nav>
  );
};
```

**5. Accessible Data Tables:**

```typescript
interface TableData {
  id: string;
  name: string;
  email: string;
  role: string;
  status: 'active' | 'inactive';
}

const AccessibleTable: React.FC<{ data: TableData[] }> = ({ data }) => {
  const [sortConfig, setSortConfig] = useState<{
    key: keyof TableData;
    direction: 'asc' | 'desc';
  } | null>(null);

  const handleSort = (key: keyof TableData) => {
    setSortConfig(prev => ({
      key,
      direction: prev?.key === key && prev.direction === 'asc' ? 'desc' : 'asc',
    }));
  };

  const sortedData = useMemo(() => {
    if (!sortConfig) return data;
    
    return [...data].sort((a, b) => {
      const aVal = a[sortConfig.key];
      const bVal = b[sortConfig.key];
      
      if (aVal < bVal) return sortConfig.direction === 'asc' ? -1 : 1;
      if (aVal > bVal) return sortConfig.direction === 'asc' ? 1 : -1;
      return 0;
    });
  }, [data, sortConfig]);

  return (
    <div className="table-container">
      <table role="table" aria-label="User data table">
        <caption className="sr-only">
          User data table with sortable columns
        </caption>
        <thead>
          <tr role="row">
            <th
              role="columnheader"
              tabIndex={0}
              onClick={() => handleSort('name')}
              onKeyDown={(e) => e.key === 'Enter' && handleSort('name')}
              aria-sort={
                sortConfig?.key === 'name'
                  ? sortConfig.direction === 'asc' ? 'ascending' : 'descending'
                  : 'none'
              }
            >
              Name
              <span className="sr-only">
                {sortConfig?.key === 'name'
                  ? `Sorted ${sortConfig.direction === 'asc' ? 'ascending' : 'descending'}`
                  : 'Click to sort'}
              </span>
            </th>
            <th
              role="columnheader"
              tabIndex={0}
              onClick={() => handleSort('email')}
              onKeyDown={(e) => e.key === 'Enter' && handleSort('email')}
              aria-sort={
                sortConfig?.key === 'email'
                  ? sortConfig.direction === 'asc' ? 'ascending' : 'descending'
                  : 'none'
              }
            >
              Email
            </th>
            <th
              role="columnheader"
              tabIndex={0}
              onClick={() => handleSort('role')}
              onKeyDown={(e) => e.key === 'Enter' && handleSort('role')}
              aria-sort={
                sortConfig?.key === 'role'
                  ? sortConfig.direction === 'asc' ? 'ascending' : 'descending'
                  : 'none'
              }
            >
              Role
            </th>
            <th
              role="columnheader"
              tabIndex={0}
              onClick={() => handleSort('status')}
              onKeyDown={(e) => e.key === 'Enter' && handleSort('status')}
              aria-sort={
                sortConfig?.key === 'status'
                  ? sortConfig.direction === 'asc' ? 'ascending' : 'descending'
                  : 'none'
              }
            >
              Status
            </th>
          </tr>
        </thead>
        <tbody>
          {sortedData.map((row) => (
            <tr key={row.id} role="row">
              <td role="cell">{row.name}</td>
              <td role="cell">{row.email}</td>
              <td role="cell">{row.role}</td>
              <td role="cell">
                <span
                  className={`status-badge ${row.status}`}
                  aria-label={`Status: ${row.status}`}
                >
                  {row.status}
                </span>
              </td>
            </tr>
          ))}
        </tbody>
      </table>
    </div>
  );
};
```

**6. Custom Accessibility Hooks:**

```typescript
// Focus management hook
const useFocusManagement = () => {
  const focusableElements = useRef<HTMLElement[]>([]);
  
  const trapFocus = (container: HTMLElement) => {
    const focusable = container.querySelectorAll(
      'button, [href], input, select, textarea, [tabindex]:not([tabindex="-1"])'
    ) as NodeListOf<HTMLElement>;
    
    focusableElements.current = Array.from(focusable);
    
    const handleKeyDown = (e: KeyboardEvent) => {
      if (e.key === 'Tab') {
        const firstElement = focusableElements.current[0];
        const lastElement = focusableElements.current[focusableElements.current.length - 1];
        
        if (e.shiftKey) {
          if (document.activeElement === firstElement) {
            lastElement.focus();
            e.preventDefault();
          }
        } else {
          if (document.activeElement === lastElement) {
            firstElement.focus();
            e.preventDefault();
          }
        }
      }
    };
    
    container.addEventListener('keydown', handleKeyDown);
    
    return () => {
      container.removeEventListener('keydown', handleKeyDown);
    };
  };
  
  return { trapFocus };
};

// Screen reader announcements
const useScreenReaderAnnouncement = () => {
  const announce = useCallback((message: string, priority: 'polite' | 'assertive' = 'polite') => {
    const announcement = document.createElement('div');
    announcement.setAttribute('aria-live', priority);
    announcement.setAttribute('aria-atomic', 'true');
    announcement.className = 'sr-only';
    announcement.textContent = message;
    
    document.body.appendChild(announcement);
    
    setTimeout(() => {
      document.body.removeChild(announcement);
    }, 1000);
  }, []);
  
  return { announce };
};
```

**7. Best Practices:**

**Internationalization:**
- Use semantic keys for translations
- Support pluralization and interpolation
- Handle RTL languages properly
- Test with different text lengths
- Use proper date/number formatting
- Consider cultural differences in UI patterns

**Accessibility:**
- Use semantic HTML elements
- Provide proper ARIA labels and roles
- Ensure keyboard navigation works
- Maintain proper focus management
- Test with screen readers
- Use sufficient color contrast
- Provide alternative text for images
- Make interactive elements large enough
- Use proper heading hierarchy
- Test with real users with disabilities

### 8.5. What tools and processes do you use for maintaining code quality? (ESLint, Prettier, Husky, CI/CD, etc.)

**Answer:**

**1. ESLint Configuration:**

```json
// .eslintrc.json
{
  "extends": [
    "eslint:recommended",
    "@typescript-eslint/recommended",
    "plugin:react/recommended",
    "plugin:react-hooks/recommended",
    "plugin:jsx-a11y/recommended",
    "plugin:import/recommended",
    "plugin:import/typescript",
    "prettier"
  ],
  "parser": "@typescript-eslint/parser",
  "parserOptions": {
    "ecmaVersion": 2022,
    "sourceType": "module",
    "ecmaFeatures": {
      "jsx": true
    }
  },
  "plugins": [
    "@typescript-eslint",
    "react",
    "react-hooks",
    "jsx-a11y",
    "import"
  ],
  "rules": {
    "react/react-in-jsx-scope": "off",
    "react/prop-types": "off",
    "@typescript-eslint/no-unused-vars": "error",
    "@typescript-eslint/explicit-function-return-type": "warn",
    "@typescript-eslint/no-explicit-any": "warn",
    "react-hooks/rules-of-hooks": "error",
    "react-hooks/exhaustive-deps": "warn",
    "jsx-a11y/anchor-is-valid": "error",
    "import/order": [
      "error",
      {
        "groups": [
          "builtin",
          "external",
          "internal",
          "parent",
          "sibling",
          "index"
        ],
        "newlines-between": "always"
      }
    ]
  },
  "settings": {
    "react": {
      "version": "detect"
    },
    "import/resolver": {
      "typescript": {
        "alwaysTryTypes": true
      }
    }
  }
}
```

**2. Prettier Configuration:**

```json
// .prettierrc
{
  "semi": true,
  "trailingComma": "es5",
  "singleQuote": true,
  "printWidth": 80,
  "tabWidth": 2,
  "useTabs": false,
  "bracketSpacing": true,
  "bracketSameLine": false,
  "arrowParens": "avoid",
  "endOfLine": "lf",
  "quoteProps": "as-needed",
  "jsxSingleQuote": true,
  "proseWrap": "preserve"
}
```

```json
// .prettierignore
node_modules/
dist/
build/
.next/
coverage/
*.min.js
*.min.css
package-lock.json
yarn.lock
```

**3. Husky Git Hooks:**

```json
// package.json
{
  "scripts": {
    "lint": "eslint src --ext .ts,.tsx --max-warnings 0",
    "lint:fix": "eslint src --ext .ts,.tsx --fix",
    "format": "prettier --write \"src/**/*.{ts,tsx,js,jsx,json,css,md}\"",
    "format:check": "prettier --check \"src/**/*.{ts,tsx,js,jsx,json,css,md}\"",
    "type-check": "tsc --noEmit",
    "test": "jest",
    "test:coverage": "jest --coverage",
    "test:watch": "jest --watch",
    "build": "tsc && vite build",
    "prepare": "husky install"
  },
  "husky": {
    "hooks": {
      "pre-commit": "lint-staged",
      "pre-push": "npm run type-check && npm run test"
    }
  },
  "lint-staged": {
    "*.{ts,tsx}": [
      "eslint --fix",
      "prettier --write"
    ],
    "*.{js,jsx,json,css,md}": [
      "prettier --write"
    ]
  }
}
```

**4. TypeScript Configuration:**

```json
// tsconfig.json
{
  "compilerOptions": {
    "target": "ES2020",
    "lib": ["DOM", "DOM.Iterable", "ES6"],
    "allowJs": true,
    "skipLibCheck": true,
    "esModuleInterop": true,
    "allowSyntheticDefaultImports": true,
    "strict": true,
    "forceConsistentCasingInFileNames": true,
    "noFallthroughCasesInSwitch": true,
    "module": "esnext",
    "moduleResolution": "node",
    "resolveJsonModule": true,
    "isolatedModules": true,
    "noEmit": true,
    "jsx": "react-jsx",
    "baseUrl": "src",
    "paths": {
      "@/*": ["*"],
      "@/components/*": ["components/*"],
      "@/hooks/*": ["hooks/*"],
      "@/utils/*": ["utils/*"],
      "@/types/*": ["types/*"]
    }
  },
  "include": [
    "src/**/*"
  ],
  "exclude": [
    "node_modules",
    "dist",
    "build"
  ]
}
```

**5. Jest Testing Configuration:**

```javascript
// jest.config.js
module.exports = {
  preset: 'ts-jest',
  testEnvironment: 'jsdom',
  setupFilesAfterEnv: ['<rootDir>/src/setupTests.ts'],
  moduleNameMapping: {
    '^@/(.*)$': '<rootDir>/src/$1',
    '\\.(css|less|scss|sass)$': 'identity-obj-proxy',
  },
  collectCoverageFrom: [
    'src/**/*.{ts,tsx}',
    '!src/**/*.d.ts',
    '!src/index.tsx',
    '!src/setupTests.ts',
  ],
  coverageThreshold: {
    global: {
      branches: 80,
      functions: 80,
      lines: 80,
      statements: 80,
    },
  },
  testMatch: [
    '<rootDir>/src/**/__tests__/**/*.{ts,tsx}',
    '<rootDir>/src/**/*.{test,spec}.{ts,tsx}',
  ],
  transform: {
    '^.+\\.(ts|tsx)$': 'ts-jest',
  },
};
```

```typescript
// src/setupTests.ts
import '@testing-library/jest-dom';
import { configure } from '@testing-library/react';

// Configure testing library
configure({ testIdAttribute: 'data-testid' });

// Mock IntersectionObserver
global.IntersectionObserver = class IntersectionObserver {
  constructor() {}
  disconnect() {}
  observe() {}
  unobserve() {}
};

// Mock ResizeObserver
global.ResizeObserver = class ResizeObserver {
  constructor() {}
  disconnect() {}
  observe() {}
  unobserve() {}
};
```

**6. CI/CD Pipeline (GitHub Actions):**

```yaml
# .github/workflows/ci.yml
name: CI/CD Pipeline

on:
  push:
    branches: [main, develop]
  pull_request:
    branches: [main, develop]

jobs:
  quality-checks:
    runs-on: ubuntu-latest
    
    steps:
      - name: Checkout code
        uses: actions/checkout@v3
        
      - name: Setup Node.js
        uses: actions/setup-node@v3
        with:
          node-version: '18'
          cache: 'npm'
          
      - name: Install dependencies
        run: npm ci
        
      - name: Type checking
        run: npm run type-check
        
      - name: Linting
        run: npm run lint
        
      - name: Format checking
        run: npm run format:check
        
      - name: Run tests
        run: npm run test:coverage
        
      - name: Upload coverage to Codecov
        uses: codecov/codecov-action@v3
        with:
          file: ./coverage/lcov.info
          
  build:
    needs: quality-checks
    runs-on: ubuntu-latest
    
    steps:
      - name: Checkout code
        uses: actions/checkout@v3
        
      - name: Setup Node.js
        uses: actions/setup-node@v3
        with:
          node-version: '18'
          cache: 'npm'
          
      - name: Install dependencies
        run: npm ci
        
      - name: Build application
        run: npm run build
        
      - name: Upload build artifacts
        uses: actions/upload-artifact@v3
        with:
          name: build-files
          path: dist/
          
  deploy:
    needs: build
    runs-on: ubuntu-latest
    if: github.ref == 'refs/heads/main'
    
    steps:
      - name: Download build artifacts
        uses: actions/download-artifact@v3
        with:
          name: build-files
          path: dist/
          
      - name: Deploy to production
        run: |
          # Deployment commands here
          echo "Deploying to production..."
```

**7. Additional Quality Tools:**

```json
// package.json - Additional dev dependencies
{
  "devDependencies": {
    "@commitlint/cli": "^17.0.0",
    "@commitlint/config-conventional": "^17.0.0",
    "commitizen": "^4.2.4",
    "cz-conventional-changelog": "^3.3.0",
    "husky": "^8.0.0",
    "lint-staged": "^13.0.0",
    "npm-run-all": "^4.1.5",
    "plop": "^3.0.0",
    "size-limit": "^8.0.0",
    "@size-limit/preset-small-lib": "^8.0.0"
  }
}
```

```javascript
// commitlint.config.js
module.exports = {
  extends: ['@commitlint/config-conventional'],
  rules: {
    'type-enum': [
      2,
      'always',
      [
        'feat',
        'fix',
        'docs',
        'style',
        'refactor',
        'perf',
        'test',
        'chore',
        'ci',
        'build',
        'revert'
      ]
    ]
  }
};
```

```javascript
// .size-limit.json
[
  {
    "path": "dist/index.js",
    "limit": "10 KB"
  },
  {
    "path": "dist/index.css",
    "limit": "2 KB"
  }
]
```

**8. VS Code Configuration:**

```json
// .vscode/settings.json
{
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.organizeImports": true
  },
  "typescript.preferences.importModuleSpecifier": "relative",
  "typescript.suggest.autoImports": true,
  "emmet.includeLanguages": {
    "typescript": "html",
    "typescriptreact": "html"
  },
  "files.associations": {
    "*.css": "tailwindcss"
  }
}
```

```json
// .vscode/extensions.json
{
  "recommendations": [
    "esbenp.prettier-vscode",
    "dbaeumer.vscode-eslint",
    "bradlc.vscode-tailwindcss",
    "ms-vscode.vscode-typescript-next",
    "formulahendry.auto-rename-tag",
    "christian-kohler.path-intellisense",
    "ms-vscode.vscode-json"
  ]
}
```

**9. Automated Code Generation:**

```javascript
// plopfile.js
module.exports = function (plop) {
  plop.setGenerator('component', {
    description: 'Create a new React component',
    prompts: [
      {
        type: 'input',
        name: 'name',
        message: 'Component name:',
      },
      {
        type: 'confirm',
        name: 'withProps',
        message: 'Include props interface?',
        default: true,
      },
      {
        type: 'confirm',
        name: 'withTests',
        message: 'Include test file?',
        default: true,
      },
    ],
    actions: [
      {
        type: 'add',
        path: 'src/components/{{pascalCase name}}/{{pascalCase name}}.tsx',
        templateFile: 'templates/component.hbs',
      },
      {
        type: 'add',
        path: 'src/components/{{pascalCase name}}/{{pascalCase name}}.test.tsx',
        templateFile: 'templates/component.test.hbs',
        skip: (data) => !data.withTests,
      },
      {
        type: 'add',
        path: 'src/components/{{pascalCase name}}/index.ts',
        templateFile: 'templates/index.hbs',
      },
    ],
  });
};
```

**10. Best Practices Summary:**

**Code Quality Tools:**
- **ESLint:** Catch bugs and enforce coding standards
- **Prettier:** Consistent code formatting
- **TypeScript:** Type safety and better developer experience
- **Husky:** Git hooks for pre-commit checks
- **lint-staged:** Run linters only on staged files
- **Jest:** Unit testing with coverage reports
- **Commitlint:** Enforce conventional commit messages

**Processes:**
- **Pre-commit hooks:** Automatic linting and formatting
- **CI/CD pipeline:** Automated testing and deployment
- **Code reviews:** Peer review process with quality gates
- **Automated testing:** Unit, integration, and E2E tests
- **Performance monitoring:** Bundle size limits and performance budgets
- **Documentation:** Automated API documentation generation

**Quality Metrics:**
- Code coverage thresholds (80%+)
- Bundle size limits
- Performance budgets
- Accessibility compliance
- Security vulnerability scanning
- Dependency audit and updates