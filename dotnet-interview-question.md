# Senior .NET Developer Interview Questions

## Table of Contents

### [C# and .NET Fundamentals](#c-and-net-fundamentals)
- [Explain the difference between value types and reference types in C#](#explain-the-difference-between-value-types-and-reference-types-in-c)
- [What is the difference between string and StringBuilder? When would you use each?](#what-is-the-difference-between-string-and-stringbuilder-when-would-you-use-each)
- [Explain the concepts of boxing and unboxing with performance implications](#explain-the-concepts-of-boxing-and-unboxing-with-performance-implications)
- [What are extension methods and when should you use them?](#what-are-extension-methods-and-when-should-you-use-them)
- [Explain the difference between IEnumerable, ICollection, IList, and IQueryable](#explain-the-difference-between-ienumerable-icollection-ilist-and-iqueryable)
- [What is the difference between abstract class and interface? When would you use each?](#what-is-the-difference-between-abstract-class-and-interface-when-would-you-use-each)
- [Explain covariance and contravariance in C#](#explain-covariance-and-contravariance-in-c)
- [What are delegates, events, and how do they differ?](#what-are-delegates-events-and-how-do-they-differ)
- [Describe the difference between readonly and const in C#](#describe-the-difference-between-readonly-and-const-in-c)
- [What is reflection and what are its use cases and drawbacks?](#what-is-reflection-and-what-are-its-use-cases-and-drawbacks)
- [Explain the concept of nullable reference types introduced in C# 8.0](#explain-the-concept-of-nullable-reference-types-introduced-in-c-80)
- [What is the difference between Finalize() and Dispose() methods?](#what-is-the-difference-between-finalize-and-dispose-methods)
- [What are generics and what are their benefits?](#what-are-generics-and-what-are-their-benefits)
- [Explain the concept of attributes in C# and provide examples](#explain-the-concept-of-attributes-in-c-and-provide-examples)
- [What is the difference between `using` statement and `using` declaration?](#what-is-the-difference-between-using-statement-and-using-declaration)

### [Object-Oriented Programming](#object-oriented-programming)
- [Explain the four pillars of OOP with real-world examples](#explain-the-four-pillars-of-oop-with-real-world-examples)
- [What is the SOLID principle? Explain each letter with examples](#what-is-the-solid-principle-explain-each-letter-with-examples)
- [What is the difference between method overloading and method overriding?](#what-is-the-difference-between-method-overloading-and-method-overriding)
- [Explain the concept of polymorphism with examples](#explain-the-concept-of-polymorphism-with-examples)
- [What are sealed classes and sealed methods?](#what-are-sealed-classes-and-sealed-methods)
- [Describe the difference between composition and inheritance](#describe-the-difference-between-composition-and-inheritance)
- [What is the Liskov Substitution Principle and why is it important?](#what-is-the-liskov-substitution-principle-and-why-is-it-important)
- [Explain dependency injection and its benefits](#explain-dependency-injection-and-its-benefits)
- [What are design patterns? Name and explain 5 commonly used patterns](#what-are-design-patterns-name-and-explain-5-commonly-used-patterns)
- [What is the difference between shallow copy and deep copy?](#what-is-the-difference-between-shallow-copy-and-deep-copy)

### [Asynchronous Programming](#asynchronous-programming)
- [Explain `async` and `await` keywords in C#](#explain-async-and-await-keywords-in-c)
- [What is the difference between `Task` and `Thread`?](#what-is-the-difference-between-task-and-thread)
- [What is `Task.Run()` vs `Task.Factory.StartNew()`?](#what-is-taskrun-vs-taskfactorystartnew)
- [Explain what `ConfigureAwait(false)` does and when to use it](#explain-what-configureawaitfalse-does-and-when-to-use-it)
- [What is a deadlock and how can async/await cause it?](#what-is-a-deadlock-and-how-can-asyncawait-cause-it)
- [Explain the difference between `Task.WhenAll()` and `Task.WhenAny()`](#explain-the-difference-between-taskwhenall-and-taskwhenany)
- [What is `ValueTask` and when should you use it over `Task`?](#what-is-valuetask-and-when-should-you-use-it-over-task)
- [How do you handle exceptions in async methods?](#how-do-you-handle-exceptions-in-async-methods)
- [What is the difference between synchronous and asynchronous programming?](#what-is-the-difference-between-synchronous-and-asynchronous-programming)
- [Explain the concept of the `SynchronizationContext`](#explain-the-concept-of-the-synchronizationcontext)
- [What are the best practices for cancellation in async operations using `CancellationToken`?](#what-are-the-best-practices-for-cancellation-in-async-operations-using-cancellationtoken)
- [How would you implement parallel processing in .NET?](#how-would-you-implement-parallel-processing-in-net)
- [What is the difference between `async void` and `async Task`?](#what-is-the-difference-between-async-void-and-async-task)
- [Explain the `IAsyncEnumerable<T>` interface and when to use it](#explain-the-iasyncenumerablet-interface-and-when-to-use-it)
- [What is the difference between `TaskCompletionSource<T>` and regular `Task<T>`?](#what-is-the-difference-between-taskcompletionsourcet-and-regular-taskt)
- [How do you handle timeouts in async operations?](#how-do-you-handle-timeouts-in-async-operations)
- [What is the difference between `Task.Run()` and `Task.Factory.StartNew()`?](#what-is-the-difference-between-taskrun-and-taskfactorystartnew)
- [Explain the concept of async streams and `IAsyncDisposable`](#explain-the-concept-of-async-streams-and-iasyncdisposable)

### [ASP.NET Core](#aspnet-core)
- [Explain the middleware pipeline in ASP.NET Core](#explain-the-middleware-pipeline-in-aspnet-core)
- [What is the difference between ASP.NET and ASP.NET Core?](#what-is-the-difference-between-aspnet-and-aspnet-core)
- [Explain dependency injection in ASP.NET Core (Transient, Scoped, Singleton)](#explain-dependency-injection-in-aspnet-core-transient-scoped-singleton)
- [What are action filters and how do you create custom filters?](#what-are-action-filters-and-how-do-you-create-custom-filters)
- [Explain the difference between `IActionResult`, `ActionResult<T>`, and returning a concrete type](#explain-the-difference-between-iactionresult-actionresultt-and-returning-a-concrete-type)
- [What is model binding and validation in ASP.NET Core?](#what-is-model-binding-and-validation-in-aspnet-core)
- [How do you implement authentication and authorization in ASP.NET Core?](#how-do-you-implement-authentication-and-authorization-in-aspnet-core)
- [Explain the difference between authentication and authorization](#explain-the-difference-between-authentication-and-authorization)
- [What is JWT and how do you implement JWT authentication?](#what-is-jwt-and-how-do-you-implement-jwt-authentication)
- [How do you handle CORS in ASP.NET Core?](#how-do-you-handle-cors-in-aspnet-core)
- [What are the different ways to manage application configuration?](#what-are-the-different-ways-to-manage-application-configuration)
- [Explain routing in ASP.NET Core (conventional vs attribute routing)](#explain-routing-in-aspnet-core-conventional-vs-attribute-routing)
- [What is Razor Pages and how does it differ from MVC?](#what-is-razor-pages-and-how-does-it-differ-from-mvc)
- [How do you implement versioning in Web APIs?](#how-do-you-implement-versioning-in-web-apis)
- [What are health checks in ASP.NET Core?](#what-are-health-checks-in-aspnet-core)

### [Entity Framework and Database](#entity-framework-and-database)
- [What is Entity Framework Core and how does it differ from Entity Framework 6?](#what-is-entity-framework-core-and-how-does-it-differ-from-entity-framework-6)
- [Explain Code First vs Database First approaches](#explain-code-first-vs-database-first-approaches)
- [What is the difference between eager loading, lazy loading, and explicit loading?](#what-is-the-difference-between-eager-loading-lazy-loading-and-explicit-loading)
- [What are migration strategies in EF Core?](#what-are-migration-strategies-in-ef-core)
- [Explain the Unit of Work and Repository patterns](#explain-the-unit-of-work-and-repository-patterns)
- [What is the N+1 query problem and how do you solve it?](#what-is-the-n1-query-problem-and-how-do-you-solve-it)
- [How do you optimize Entity Framework queries?](#how-do-you-optimize-entity-framework-queries)
- [Explain tracking vs no-tracking queries in EF Core](#explain-tracking-vs-no-tracking-queries-in-ef-core)
- [What are owned entities and table splitting in EF Core?](#what-are-owned-entities-and-table-splitting-in-ef-core)
- [How do you handle concurrency in Entity Framework?](#how-do-you-handle-concurrency-in-entity-framework)
- [Explain the difference between `SaveChanges()` and `SaveChangesAsync()`](#explain-the-difference-between-savechanges-and-savechangesasync)
- [What are shadow properties in EF Core?](#what-are-shadow-properties-in-ef-core)

### [Performance and Memory Management](#performance-and-memory-management)
- [Explain garbage collection in .NET and its generations](#explain-garbage-collection-in-net-and-its-generations)
- [What are memory leaks and how do you identify them in .NET?](#what-are-memory-leaks-and-how-do-you-identify-them-in-net)
- [What is the difference between stack and heap memory?](#what-is-the-difference-between-stack-and-heap-memory)
- [How would you profile and optimize a .NET application?](#how-would-you-profile-and-optimize-a-net-application)
- [What is `Span<T>` and `Memory<T>`? When should you use them?](#what-is-spant-and-memoryt-when-should-you-use-them)
- [Explain object pooling and when to use it](#explain-object-pooling-and-when-to-use-it)
- [What are the best practices for string concatenation in loops?](#what-are-the-best-practices-for-string-concatenation-in-loops)
- [How do you reduce memory allocations in performance-critical code?](#how-do-you-reduce-memory-allocations-in-performance-critical-code)
- [What is the Large Object Heap (LOH)?](#what-is-the-large-object-heap-loh)
- [Explain the concept of weak references](#explain-the-concept-of-weak-references)

### [LINQ and Collections](#linq-and-collections)
- [What is LINQ and what are its advantages?](#what-is-linq-and-what-are-its-advantages)
- [Explain the difference between LINQ query syntax and method syntax](#explain-the-difference-between-linq-query-syntax-and-method-syntax)
- [What is the difference between `First()`, `FirstOrDefault()`, `Single()`, and `SingleOrDefault()`?](#what-is-the-difference-between-first-firstordefault-single-and-singleordefault)
- [Explain deferred execution in LINQ](#explain-deferred-execution-in-linq)
- [What is the difference between `Select()` and `SelectMany()`?](#what-is-the-difference-between-select-and-selectmany)
- [How do you optimize LINQ queries?](#how-do-you-optimize-linq-queries)
- [What are the differences between `List<T>`, `HashSet<T>`, and `Dictionary<TKey, TValue>`?](#what-are-the-differences-between-listt-hashsett-and-dictionarytkey-tvalue)
- [When would you use `ConcurrentDictionary` over `Dictionary`?](#when-would-you-use-concurrentdictionary-over-dictionary)
- [Explain `GroupBy()` and `Join()` operations in LINQ](#explain-groupby-and-join-operations-in-linq)
- [What is the difference between `Where().Select()` and `Select().Where()`?](#what-is-the-difference-between-whereselect-and-selectwhere)

### [Testing](#testing)
- [What is unit testing and why is it important?](#what-is-unit-testing-and-why-is-it-important)
- [Explain the AAA pattern (Arrange, Act, Assert)](#explain-the-aaa-pattern-arrange-act-assert)
- [What is the difference between mocking, stubbing, and faking?](#what-is-the-difference-between-mocking-stubbing-and-faking)
- [What testing frameworks have you used in .NET (xUnit, NUnit, MSTest)?](#what-testing-frameworks-have-you-used-in-net-xunit-nunit-mstest)
- [How do you write testable code?](#how-do-you-write-testable-code)
- [What is TDD (Test-Driven Development)?](#what-is-tdd-test-driven-development)
- [Explain integration testing vs unit testing](#explain-integration-testing-vs-unit-testing)
- [What is code coverage and what is a good coverage percentage?](#what-is-code-coverage-and-what-is-a-good-coverage-percentage)

### [Microservices and Architecture](#microservices-and-architecture)
- [What are microservices and what are their advantages and disadvantages?](#what-are-microservices-and-what-are-their-advantages-and-disadvantages)
- [Explain the difference between monolithic and microservices architecture](#explain-the-difference-between-monolithic-and-microservices-architecture)
- [What is API Gateway pattern?](#what-is-api-gateway-pattern)
- [How do you handle inter-service communication in microservices?](#how-do-you-handle-inter-service-communication-in-microservices)
- [What is the Circuit Breaker pattern?](#what-is-the-circuit-breaker-pattern)
- [Explain eventual consistency in distributed systems](#explain-eventual-consistency-in-distributed-systems)
- [What is the Saga pattern for distributed transactions?](#what-is-the-saga-pattern-for-distributed-transactions)
- [How do you implement service discovery?](#how-do-you-implement-service-discovery)
- [What are containers and how do they relate to microservices?](#what-are-containers-and-how-do-they-relate-to-microservices)
- [Explain the strangler pattern for migrating to microservices](#explain-the-strangler-pattern-for-migrating-to-microservices)

### [Security](#security)
- [What is SQL injection and how do you prevent it?](#what-is-sql-injection-and-how-do-you-prevent-it)
- [Explain Cross-Site Scripting (XSS) and Cross-Site Request Forgery (CSRF)](#explain-cross-site-scripting-xss-and-cross-site-request-forgery-csrf)
- [What are the best practices for storing passwords?](#what-are-the-best-practices-for-storing-passwords)
- [How do you implement OAuth 2.0 and OpenID Connect?](#how-do-you-implement-oauth-20-and-openid-connect)
- [What is the principle of least privilege?](#what-is-the-principle-of-least-privilege)
- [How do you secure sensitive data in configuration files?](#how-do-you-secure-sensitive-data-in-configuration-files)
- [Explain the importance of HTTPS and how to implement it](#explain-the-importance-of-https-and-how-to-implement-it)
- [What are the OWASP Top 10 security risks?](#what-are-the-owasp-top-10-security-risks)

### [DevOps and CI/CD](#devops-and-cicd)
- [What is CI/CD and why is it important?](#what-is-cicd-and-why-is-it-important)
- [Have you worked with Docker? Explain containerization](#have-you-worked-with-docker-explain-containerization)
- [What is Kubernetes and what problems does it solve?](#what-is-kubernetes-and-what-problems-does-it-solve)
- [Explain the concept of Infrastructure as Code](#explain-the-concept-of-infrastructure-as-code)
- [What Azure/AWS services have you worked with for .NET applications?](#what-azureaws-services-have-you-worked-with-for-net-applications)

### [General and Behavioral](#general-and-behavioral)
- [How do you stay updated with the latest .NET technologies?](#how-do-you-stay-updated-with-the-latest-net-technologies)
- [Describe a challenging bug you've encountered and how you resolved it](#describe-a-challenging-bug-youve-encountered-and-how-you-resolved-it)
- [How do you handle technical debt in a project?](#how-do-you-handle-technical-debt-in-a-project)
- [Explain your code review process and what you look for](#explain-your-code-review-process-and-what-you-look-for)
- [How do you mentor junior developers on your team?](#how-do-you-mentor-junior-developers-on-your-team)

---

## C# and .NET Fundamentals

### Explain the difference between value types and reference types in C#.

**Answer:**

**Value Types:**
- Stored directly on the stack (or inline in containing types)
- Contain the actual data directly
- Each variable has its own copy of the data
- When you copy a value type, you copy the actual data
- Examples: int, double, bool, struct, enum, decimal, DateTime
- Derive from System.ValueType
- Cannot be null (unless nullable value type like int?)

**Reference Types:**
- Stored on the heap
- Variable contains a reference (pointer) to the actual data
- Multiple variables can reference the same object
- When you copy a reference type, you copy the reference, not the data
- Examples: class, interface, delegate, string, object, arrays
- Derive from System.Object
- Can be null

**Key Differences Illustrated:**

Value Type Example:
```csharp
int a = 10;
int b = a;  // Creates a COPY of the value
b = 20;
Console.WriteLine(a);  // Output: 10 (unchanged)
Console.WriteLine(b);  // Output: 20
```

Reference Type Example:
```csharp
class Person { public string Name { get; set; } }

Person person1 = new Person { Name = "John" };
Person person2 = person1;  // Copies the REFERENCE, not the object
person2.Name = "Jane";

Console.WriteLine(person1.Name);  // Output: "Jane" (changed!)
Console.WriteLine(person2.Name);  // Output: "Jane"
// Both variables point to the same object in memory
```

**Memory Allocation:**
- Value types are typically faster to allocate/deallocate (stack allocation)
- Reference types require heap allocation and garbage collection
- Value types have less memory overhead (no object header)

**Performance Implications:**
- Use value types for small, simple data structures
- Use reference types when you need shared references or large data
- Boxing occurs when converting value type to reference type (performance cost)

---

### What is the difference between string and StringBuilder? When would you use each?

**Answer:**

**String:**
- Immutable - once created, cannot be changed
- Any modification creates a new string object in memory
- Thread-safe by nature (due to immutability)
- Use when: Few modifications, constant strings, or passing data between methods

Example of immutability:
```csharp
string str = "Hello";
str = str + " World";  // Creates a NEW string object, original "Hello" is garbage collected
```

**StringBuilder:**
- Mutable - can be modified without creating new objects
- More efficient for multiple string manipulations
- Not thread-safe (use synchronization if needed)
- Use when: Multiple modifications, loops, or building large strings

Performance comparison:
```csharp
// BAD PRACTICE - Creates 1000 new string objects
string result = "";
for (int i = 0; i < 1000; i++)
{
    result += i.ToString();  // Very inefficient!
}

// GOOD PRACTICE - Modifies same StringBuilder object
StringBuilder sb = new StringBuilder();
for (int i = 0; i < 1000; i++)
{
    sb.Append(i.ToString());  // Efficient!
}
string result = sb.ToString();
```

**When to use each:**
- String: 1-5 concatenations, constant values, simple operations
- StringBuilder: Loops, multiple operations, building complex strings, performance-critical code

---

### Explain the concepts of boxing and unboxing with performance implications.

**Answer:**

**Boxing:**
- Converting a value type to a reference type (object)
- The value is wrapped in an object and stored on the heap
- Implicit operation

**Unboxing:**
- Converting a reference type back to a value type
- Explicit operation (requires casting)
- Can throw InvalidCastException if types don't match

**Example:**
```csharp
// BOXING - value type to reference type
int num = 123;
object obj = num;  // Boxing occurs - int copied to heap

// UNBOXING - reference type to value type
int num2 = (int)obj;  // Unboxing occurs - must cast explicitly
```

**Performance Implications:**

1. Memory Allocation: Boxing allocates memory on the heap (slower than stack)
2. Garbage Collection: Boxed objects need to be garbage collected
3. Type Safety: Unboxing requires explicit casting and runtime type checking
4. CPU Overhead: Both operations require CPU cycles

**Common scenarios where boxing occurs:**
```csharp
// Adding value type to non-generic collection
ArrayList list = new ArrayList();
list.Add(1);  // Boxing occurs!

// String formatting
int age = 30;
string message = string.Format("Age: {0}", age);  // Boxing occurs!

// Using value types as object parameters
void PrintObject(object obj) { }
PrintObject(42);  // Boxing occurs!
```

**How to avoid boxing:**
```csharp
// Use generic collections
List numbers = new List();
numbers.Add(1);  // No boxing!

// Use string interpolation or generic methods
string message = $"Age: {age}";  // No boxing in most cases

// Use generic constraints
void Print(T value) { }
Print(42);  // No boxing!
```

**Performance Impact:**
- Boxing/unboxing in tight loops can significantly degrade performance
- Can cause increased garbage collection pressure
- Benchmark shows boxing can be 10-100x slower than working with value types directly

---

### What are extension methods and when should you use them?

**Answer:**

**Extension Methods** allow you to add new methods to existing types without modifying the original type, creating a new derived type, or recompiling.

**Key Characteristics:**
- Must be defined in a static class
- Must be static methods
- First parameter uses the "this" keyword to specify the type being extended
- Called as if they were instance methods

**Syntax:**
```csharp
public static class StringExtensions
{
    public static bool IsValidEmail(this string str)
    {
        if (string.IsNullOrWhiteSpace(str))
            return false;
        
        return str.Contains("@") && str.Contains(".");
    }
    
    public static string Truncate(this string str, int maxLength)
    {
        if (string.IsNullOrEmpty(str) || str.Length <= maxLength)
            return str;
        
        return str.Substring(0, maxLength) + "...";
    }
}

// Usage
string email = "user@example.com";
bool isValid = email.IsValidEmail();  // Called like an instance method

string longText = "This is a very long text";
string shortened = longText.Truncate(10);  // "This is a ..."
```

**LINQ is built on extension methods:**
```csharp
// These are all extension methods on IEnumerable
var result = numbers
    .Where(n => n > 5)
    .Select(n => n * 2)
    .OrderBy(n => n);
```

**When to use Extension Methods:**

1. Adding utility methods to framework types you can't modify
2. Improving code readability with fluent APIs
3. Adding domain-specific functionality to existing types
4. Creating LINQ-like query operations

**When NOT to use:**
1. When you can modify the original class
2. When it breaks encapsulation (accessing private members)
3. For core business logic (prefer regular methods)
4. When it might conflict with existing or future methods

**Best Practices:**
- Use clear, descriptive names
- Keep them simple and focused
- Group related extensions in appropriately named static classes
- Be careful with common types (string, int) to avoid naming conflicts
- Document them well

---

### Explain the difference between IEnumerable, ICollection, IList, and IQueryable.

**Answer:**

These are all collection interfaces with different capabilities and use cases.

**IEnumerable<T>:**
- Most basic interface for iteration
- Forward-only, read-only iteration
- Deferred execution (lazy evaluation)
- In-memory collections
- Methods: GetEnumerator()

```csharp
IEnumerable numbers = new List { 1, 2, 3, 4, 5 };
foreach (var num in numbers)  // Can only iterate forward
{
    Console.WriteLine(num);
}
// Cannot: Add, Remove, Count, or Index access
```

**ICollection<T>:**
- Extends IEnumerable<T>
- Adds Count property
- Allows Add, Remove, Clear operations
- Still no index-based access
- Methods: Add(), Remove(), Clear(), Contains()
- Properties: Count, IsReadOnly

```csharp
ICollection numbers = new List();
numbers.Add(1);
numbers.Remove(1);
int count = numbers.Count;  // Can get count
// Cannot: Index access like numbers[0]
```

**IList<T>:**
- Extends ICollection<T> (and IEnumerable<T>)
- Adds index-based access
- Allows insertion at specific positions
- Most feature-rich in-memory collection interface
- Methods: Insert(), RemoveAt(), IndexOf()
- Properties: Indexer [int index]

```csharp
IList numbers = new List { 1, 2, 3 };
numbers[0] = 10;  // Index-based access
numbers.Insert(1, 5);  // Insert at position
int value = numbers[2];  // Read by index
```

**IQueryable<T>:**
- Extends IEnumerable<T>
- Designed for out-of-memory data sources (databases)
- Expression trees for query translation
- Deferred execution
- Queries translated to native query language (SQL, etc.)
- Used with LINQ to SQL, Entity Framework

```csharp
// IQueryable - Query executed on DATABASE
IQueryable query = dbContext.Users
    .Where(u => u.Age > 18)  // Translated to SQL WHERE clause
    .OrderBy(u => u.Name);   // Translated to SQL ORDER BY

// IEnumerable - Query executed in MEMORY
IEnumerable query = dbContext.Users.ToList()  // Loads all data first!
    .Where(u => u.Age > 18)  // Filters in C# memory
    .OrderBy(u => u.Name);   // Sorts in C# memory
```

**Comparison Table:**

| Feature | IEnumerable | ICollection | IList | IQueryable |
|---------|-------------|-------------|-------|------------|
| Iteration | ✓ | ✓ | ✓ | ✓ |
| Count | ✗ | ✓ | ✓ | ✓ |
| Add/Remove | ✗ | ✓ | ✓ | ✗ |
| Index Access | ✗ | ✗ | ✓ | ✗ |
| Database Query | ✗ | ✗ | ✗ | ✓ |
| Deferred Execution | ✓ | ✗ | ✗ | ✓ |

**Performance Implications:**
```csharp
// BAD - Loads all users into memory, then filters
IEnumerable users = dbContext.Users.ToList()
    .Where(u => u.Age > 18);

// GOOD - Filters in database, loads only matching records
IQueryable users = dbContext.Users
    .Where(u => u.Age > 18);
```

**Best Practices:**
- Return IEnumerable<T> for simple read-only sequences
- Use ICollection<T> when you need Count and Add/Remove
- Use IList<T> when you need index-based access
- Use IQueryable<T> for database queries to leverage server-side filtering

---

### What is the difference between abstract class and interface? When would you use each?

**Answer:**

**Abstract Class:**
- Can have implementation (concrete methods)
- Can have fields, properties, constructors
- Supports access modifiers (public, protected, private)
- Single inheritance only (a class can inherit from one abstract class)
- Can have static members
- Use "abstract" keyword

**Interface:**
- Cannot have implementation (before C# 8.0)
- C# 8.0+: Can have default implementation
- Cannot have fields (can have properties)
- All members are public by default
- Multiple inheritance (a class can implement multiple interfaces)
- Cannot have constructors or static members (except C# 8.0+)
- Use "interface" keyword

**Example:**
```csharp
// ABSTRACT CLASS
public abstract class Animal
{
    protected string name;  // Field
    
    public Animal(string name)  // Constructor
    {
        this.name = name;
    }
    
    public abstract void MakeSound();  // Abstract method - must be implemented
    
    public void Sleep()  // Concrete method - shared implementation
    {
        Console.WriteLine($"{name} is sleeping");
    }
}

public class Dog : Animal
{
    public Dog(string name) : base(name) { }
    
    public override void MakeSound()
    {
        Console.WriteLine("Woof!");
    }
}

// INTERFACE
public interface IFlyable
{
    void Fly();  // No implementation
    int MaxAltitude { get; set; }  // Property
}

public interface ISwimmable
{
    void Swim();
}

public class Duck : Animal, IFlyable, ISwimmable  // Multiple interfaces!
{
    public Duck(string name) : base(name) { }
    
    public override void MakeSound()
    {
        Console.WriteLine("Quack!");
    }
    
    public void Fly()
    {
        Console.WriteLine("Duck is flying");
    }
    
    public void Swim()
    {
        Console.WriteLine("Duck is swimming");
    }
    
    public int MaxAltitude { get; set; }
}
```

**When to use Abstract Class:**
1. You have shared code that multiple derived classes can use
2. You need to define constructors or fields
3. You need non-public members (protected, private)
4. You want to provide a common base with some default behavior
5. Related classes in an "is-a" relationship (Dog IS-A Animal)

**When to use Interface:**
1. You need multiple inheritance
2. You want to define a contract without implementation
3. Unrelated classes need to share behavior (Duck and Airplane both implement IFlyable)
4. You want to achieve loose coupling
5. You need to define capabilities ("can-do" relationship)

**Real-world example:**
```csharp
// Abstract class for shared behavior
public abstract class Vehicle
{
    public string Make { get; set; }
    public string Model { get; set; }
    
    public abstract void Start();
    
    public void DisplayInfo()  // Shared implementation
    {
        Console.WriteLine($"{Make} {Model}");
    }
}

// Interfaces for capabilities
public interface IElectric
{
    void Charge();
    int BatteryLevel { get; }
}

public interface IAutonomous
{
    void EnableAutoPilot();
    void DisableAutoPilot();
}

// Tesla combines abstract class and multiple interfaces
public class Tesla : Vehicle, IElectric, IAutonomous
{
    public int BatteryLevel { get; private set; }
    
    public override void Start()
    {
        Console.WriteLine("Tesla started silently");
    }
    
    public void Charge()
    {
        BatteryLevel = 100;
    }
    
    public void EnableAutoPilot()
    {
        Console.WriteLine("AutoPilot enabled");
    }
    
    public void DisableAutoPilot()
    {
        Console.WriteLine("AutoPilot disabled");
    }
}
```

**C# 8.0+ Default Interface Implementation:**
```csharp
public interface ILogger
{
    void Log(string message);
    
    // Default implementation (C# 8.0+)
    void LogError(string message)
    {
        Log($"ERROR: {message}");
    }
}
```

**Key Decision Factors:**
- Need shared state/fields? → Abstract Class
- Need multiple inheritance? → Interface
- Need constructors? → Abstract Class
- Defining a contract? → Interface
- Related types? → Abstract Class
- Capabilities/behaviors? → Interface

---

### Explain covariance and contravariance in C#.

**Answer:**

**Covariance and Contravariance** allow for implicit reference conversion for array types, delegate types, and generic type arguments.

**Covariance (out keyword):**
- Allows you to use a more derived type than originally specified
- Enables you to assign an instance of a type to a variable of its base type
- Used with return types
- "out" keyword in generic interfaces and delegates

**Contravariance (in keyword):**
- Allows you to use a less derived type than originally specified
- Used with input parameters
- "in" keyword in generic interfaces and delegates

**Covariance Example:**
```csharp
// Class hierarchy
class Animal { }
class Dog : Animal { }
class Cat : Animal { }

// COVARIANCE with IEnumerable
IEnumerable dogs = new List();
IEnumerable animals = dogs;  // OK! Covariance allows this
// You can read Dogs as Animals

// Custom covariant interface
public interface IProducer  // "out" keyword
{
    T Produce();  // T only in output position
}

class AnimalProducer : IProducer
{
    public Animal Produce() => new Animal();
}

class DogProducer : IProducer
{
    public Dog Produce() => new Dog();
}

// Usage
IProducer dogProducer = new DogProducer();
IProducer animalProducer = dogProducer;  // Covariance!
Animal animal = animalProducer.Produce();  // Returns Dog, treated as Animal
```

**Contravariance Example:**
```csharp
// CONTRAVARIANCE with Action
Action animalAction = (animal) => Console.WriteLine("Animal action");
Action dogAction = animalAction;  // OK! Contravariance allows this
// You can handle Animals where Dogs are expected

// Custom contravariant interface
public interface IConsumer  // "in" keyword
{
    void Consume(T item);  // T only in input position
}

class AnimalConsumer : IConsumer
{
    public void Consume(Animal animal)
    {
        Console.WriteLine("Consuming animal");
    }
}

// Usage
IConsumer animalConsumer = new AnimalConsumer();
IConsumer dogConsumer = animalConsumer;  // Contravariance!
dogConsumer.Consume(new Dog());  // Passes Dog to method expecting Animal
```

**Why this works:**

Covariance (out): If a method returns a Dog, it's always safe to treat it as an Animal (Dog IS-A Animal)

Contravariance (in): If a method can handle any Animal, it can definitely handle a Dog (Dog IS-A Animal)

**Built-in .NET Examples:**
```csharp
// Covariant interfaces
IEnumerable
IEnumerator
IQueryable
IGrouping
Func

// Contravariant interfaces
IComparable
IComparer
Action
Predicate
```

**Real-world Example:**
```csharp
// Covariance - returning more specific types
public interface IAnimalRepository where T : Animal
{
    T GetById(int id);
    IEnumerable GetAll();
}

class DogRepository : IAnimalRepository
{
    public Dog GetById(int id) => new Dog();
    public IEnumerable GetAll() => new List();
}

IAnimalRepository dogRepo = new DogRepository();
IAnimalRepository animalRepo = dogRepo;  // Covariance allows this!

// Contravariance - accepting less specific types
public interface IAnimalValidator where T : Animal
{
    bool Validate(T animal);
}

class AnimalValidator : IAnimalValidator
{
    public bool Validate(Animal animal)
    {
        return animal != null;
    }
}

IAnimalValidator animalValidator = new AnimalValidator();
IAnimalValidator dogValidator = animalValidator;  // Contravariance!
bool isValid = dogValidator.Validate(new Dog());
```

**Restrictions:**
```csharp
// INVALID - Can't use 'out' parameter in input position
public interface IInvalid
{
    void Process(T item);  // ERROR! T is output-only
}

// INVALID - Can't use 'in' parameter in output position
public interface IInvalid
{
    T GetItem();  // ERROR! T is input-only
}

// VALID - Can use invariant (no in/out)
public interface IValid
{
    T GetItem();
    void Process(T item);
}
```

**Memory Tip:**
- **COvariance** = **CO**mes **OUT** (return types) → "out"
- **CONTRAvariance** = goes **IN** (parameters) → "in"

---

### What are delegates, events, and how do they differ?

**Answer:**

**Delegates:**
- Type-safe function pointers
- Reference type that holds references to methods
- Can point to any method with matching signature
- Supports multicast (calling multiple methods)
- Can be called directly by any code that has access

**Events:**
- Built on top of delegates
- Special kind of delegate with restrictions
- Provides publisher-subscriber pattern
- Can only be invoked from within the declaring class
- Add/remove methods only (cannot be assigned from outside)

**Delegate Example:**
```csharp
// Define delegate type
public delegate void NotificationHandler(string message);

public class Example
{
    // Delegate field - can be called and assigned from anywhere
    public NotificationHandler OnNotification;
    
    public void SendNotification(string msg)
    {
        // Anyone can call this delegate
        OnNotification?.Invoke(msg);
    }
}

// Usage
Example example = new Example();

// Problem: Can be assigned from outside, replacing all subscribers!
example.OnNotification = (msg) => Console.WriteLine($"Handler 1: {msg}");

// Problem: Can be called from outside the class!
example.OnNotification?.Invoke("Direct call");
```

**Event Example:**
```csharp
// Define delegate type
public delegate void NotificationHandler(string message);

public class Example
{
    // Event - restricted delegate
    public event NotificationHandler OnNotification;
    
    public void SendNotification(string msg)
    {
        // Only the class itself can invoke the event
        OnNotification?.Invoke(msg);
    }
}

// Usage
Example example = new Example();

// Can only add/remove handlers (+=, -=)
example.OnNotification += (msg) => Console.WriteLine($"Handler 1: {msg}");
example.OnNotification += (msg) => Console.WriteLine($"Handler 2: {msg}");

// ERROR: Cannot assign directly
// example.OnNotification = (msg) => Console.WriteLine("Test");

// ERROR: Cannot call from outside
// example.OnNotification?.Invoke("Test");
```

**Built-in EventHandler:**
```csharp
public class Button
{
    // Using built-in EventHandler delegate
    public event EventHandler Click;
    
    // Using generic EventHandler with custom args
    public event EventHandler MouseMove;
    
    protected virtual void OnClick()
    {
        Click?.Invoke(this, EventArgs.Empty);
    }
    
    protected virtual void OnMouseMove(MouseEventArgs e)
    {
        MouseMove?.Invoke(this, e);
    }
}

// Custom EventArgs
public class MouseEventArgs : EventArgs
{
    public int X { get; set; }
    public int Y { get; set; }
}

// Usage
Button button = new Button();
button.Click += (sender, e) => Console.WriteLine("Button clicked!");
button.MouseMove += (sender, e) => Console.WriteLine($"Mouse at {e.X}, {e.Y}");
```

**Multicast Delegates:**
```csharp
public delegate void LogHandler(string message);

public class Logger
{
    private LogHandler logHandler;
    
    public void AddLogMethod(LogHandler handler)
    {
        logHandler += handler;  // Add to invocation list
    }
    
    public void RemoveLogMethod(LogHandler handler)
    {
        logHandler -= handler;  // Remove from invocation list
    }
    
    public void Log(string message)
    {
        // Calls all methods in invocation list
        logHandler?.Invoke(message);
    }
}

// Usage
Logger logger = new Logger();
logger.AddLogMethod(msg => Console.WriteLine($"Console: {msg}"));
logger.AddLogMethod(msg => File.AppendAllText("log.txt", msg));
logger.AddLogMethod(msg => Debug.WriteLine(msg));

logger.Log("Error occurred");  // Calls all three methods
```

**Key Differences:**

| Feature | Delegate | Event |
|---------|----------|-------|
| Assignment | Can be directly assigned (=) | Cannot be assigned, only += or -= |
| Invocation | Can be called from anywhere | Can only be invoked within declaring class |
| Purpose | General callback mechanism | Publisher-subscriber pattern |
| Encapsulation | Weak | Strong |
| Protection | No protection from outside | Protected from outside manipulation |

**Real-world Example - Stock Market:**
```csharp
public class Stock
{
    private decimal price;
    
    // Event with custom EventArgs
    public event EventHandler PriceChanged;
    
    public decimal Price
    {
        get => price;
        set
        {
            if (price != value)
            {
                decimal oldPrice = price;
                price = value;
                OnPriceChanged(new PriceChangedEventArgs(oldPrice, value));
            }
        }
    }
    
    protected virtual void OnPriceChanged(PriceChangedEventArgs e)
    {
        PriceChanged?.Invoke(this, e);
    }
}

public class PriceChangedEventArgs : EventArgs
{
    public decimal OldPrice { get; }
    public decimal NewPrice { get; }
    public decimal Change => NewPrice - OldPrice;
    
    public PriceChangedEventArgs(decimal oldPrice, decimal newPrice)
    {
        OldPrice = oldPrice;
        NewPrice = newPrice;
    }
}

// Subscribers
public class StockAlert
{
    public StockAlert(Stock stock)
    {
        stock.PriceChanged += OnPriceChanged;
    }
    
    private void OnPriceChanged(object sender, PriceChangedEventArgs e)
    {
        if (e.Change > 10)
            Console.WriteLine($"Alert: Price jumped by {e.Change:C}");
    }
}

public class StockLogger
{
    public StockLogger(Stock stock)
    {
        stock.PriceChanged += OnPriceChanged;
    }
    
    private void OnPriceChanged(object sender, PriceChangedEventArgs e)
    {
        Console.WriteLine($"Price changed from {e.OldPrice:C} to {e.NewPrice:C}");
    }
}

// Usage
Stock appleStock = new Stock { Price = 150 };
StockAlert alert = new StockAlert(appleStock);
StockLogger logger = new StockLogger(appleStock);

appleStock.Price = 165;  // Both alert and logger are notified
```

**Action and Func Delegates:**
```csharp
// Action - no return value
Action logAction = msg => Console.WriteLine(msg);
Action addAction = (x, y) => Console.WriteLine(x + y);

// Func - with return value (last type parameter is return type)
Func add = (x, y) => x + y;
Func isValid = str => !string.IsNullOrEmpty(str);

// Usage
int result = add(5, 3);  // 8
bool valid = isValid("test");  // true
```

**When to use what:**
- Use **delegates** when you need direct method reference or callbacks
- Use **events** when implementing observer/publisher-subscriber pattern
- Use **Action/Func** for simple inline delegates (LINQ, callbacks)
- Use **custom delegates** when you need specific naming or complex signatures

---

### Describe the difference between readonly and const in C#.

**Answer:**

**const:**
- Compile-time constant
- Value must be assigned at declaration
- Value is embedded in IL code
- Implicitly static
- Can only be primitive types, enums, or string
- Better performance (no runtime lookup)

**readonly:**
- Runtime constant
- Can be assigned in declaration or constructor
- Value stored in memory
- Can be instance or static
- Can be any type
- More flexible

**Examples:**
```csharp
public class Configuration
{
    // CONST - Compile-time constant
    public const int MaxConnections = 100;
    public const string AppName = "MyApp";
    public const double Pi = 3.14159;
    
    // READONLY - Runtime constant
    public readonly string ConnectionString;
    public readonly DateTime StartTime;
    public static readonly int ProcessorCount;
    
    // Readonly can be assigned in constructor
    public Configuration(string connStr)
    {
        ConnectionString = connStr;
        StartTime = DateTime.Now;  // Runtime value!
    }
    
    // Static readonly can be assigned in static constructor
    static Configuration()
    {
        ProcessorCount = Environment.ProcessorCount;
    }
}

// Usage
// Const access (no instance needed)
int max = Configuration.MaxConnections;

// Readonly access (needs instance or static)
Configuration config = new Configuration("Server=localhost");
string connStr = config.ConnectionString;
```

**Key Differences:**

| Feature | const | readonly |
|---------|-------|----------|
| Assignment Time | Compile-time | Runtime |
| Assignment | Only at declaration | Declaration or constructor |
| Modifier | Implicitly static | Can be instance or static |
| Types Allowed | Primitives, string, enum | Any type |
| Performance | Faster (inline) | Slightly slower |
| Value Change | Never | Once per instance/lifetime |
| Memory | IL code | Heap/Stack |

**Versioning Issue with const:**
```csharp
// Assembly A (Library)
public class Constants
{
    public const int MaxValue = 100;
}

// Assembly B (Application) - uses Assembly A
public class Program
{
    public void Process()
    {
        // Value 100 is embedded in Assembly B's IL code!
        int max = Constants.MaxValue;
    }
}

// Problem: If you change MaxValue to 200 in Assembly A and recompile only A,
// Assembly B still uses 100 (old value) until B is also recompiled!
```

**Solution with readonly:**
```csharp
// Assembly A (Library)
public class Constants
{
    public static readonly int MaxValue = 100;
}

// Assembly B (Application)
public class Program
{
    public void Process()
    {
        // Value is looked up from Assembly A at runtime
        int max = Constants.MaxValue;
    }
}

// If you change MaxValue to 200 and recompile only A,
// Assembly B automatically gets the new value without recompilation!
```

**readonly with reference types:**
```csharp
public class Container
{
    // readonly reference - cannot reassign, but can modify contents
    private readonly List items = new List();
    
    public void AddItem(string item)
    {
        items.Add(item);  // OK - modifying contents
        
        // ERROR - cannot reassign
        // items = new List();
    }
}
```

**readonly struct (C# 7.2+):**
```csharp
// All fields must be readonly
public readonly struct Point
{
    public readonly int X;
    public readonly int Y;
    
    public Point(int x, int y)
    {
        X = x;
        Y = y;
    }
    
    // All properties must be read-only
    public int Sum => X + Y;
}
```

**When to use:**
- Use **const** for: True constants that never change (Pi, MaxInt), configuration values that are known at compile-time
- Use **readonly** for: Values initialized at runtime, dependency injection, values from configuration files, reference types, values that may change between versions

**Best Practices:**
```csharp
public class Settings
{
    // Good - compile-time constant
    public const int DefaultTimeout = 30;
    
    // Good - runtime value from constructor
    public readonly string Environment;
    
    // Good - complex object
    public readonly ILogger Logger;
    
    // Bad - should be const (never changes)
    public readonly int MaxRetries = 3;
    
    public Settings(string environment, ILogger logger)
    {
        Environment = environment;
        Logger = logger;
    }
}
```

---

### What is reflection and what are its use cases and drawbacks?

**Answer:**

**Reflection** is the ability to inspect and interact with metadata of types, assemblies, methods, and properties at runtime.

**What Reflection Allows:**
- Inspect types, methods, properties, and fields at runtime
- Create instances of types dynamically
- Invoke methods and access properties dynamically
- Read attributes and metadata
- Generate code at runtime

**Common Use Cases:**

1. **Serialization/Deserialization:**
```csharp
// JSON serialization uses reflection to read properties
public class Person
{
    public string Name { get; set; }
    public int Age { get; set; }
}

Person person = new Person { Name = "John", Age = 30 };
string json = JsonSerializer.Serialize(person);  // Uses reflection internally
```

2. **Dependency Injection:**
```csharp
// DI containers use reflection to create instances
services.AddTransient();
// Container uses reflection to find constructor and inject dependencies
```

3. **Attribute-Based Programming:**
```csharp
[Route("api/users")]
public class UsersController : ControllerBase
{
    [HttpGet("{id}")]
    [Authorize(Roles = "Admin")]
    public IActionResult GetUser(int id)
    {
        // Framework uses reflection to read Route and Authorize attributes
    }
}
```

4. **Plugin Systems:**
```csharp
// Load plugins dynamically
Assembly assembly = Assembly.LoadFrom("MyPlugin.dll");
Type pluginType = assembly.GetType("MyPlugin.PluginClass");
IPlugin plugin = (IPlugin)Activator.CreateInstance(pluginType);
plugin.Execute();
```

**Reflection Examples:**

**Type Inspection:**
```csharp
Type type = typeof(Person);

// Get properties
PropertyInfo[] properties = type.GetProperties();
foreach (var prop in properties)
{
    Console.WriteLine($"{prop.Name}: {prop.PropertyType}");
}

// Get methods
MethodInfo[] methods = type.GetMethods();

// Check if type implements interface
bool implementsInterface = typeof(IDisposable).IsAssignableFrom(type);

// Get custom attributes
var attributes = type.GetCustomAttributes(typeof(ObsoleteAttribute), false);
```

**Dynamic Instantiation:**
```csharp
// Create instance without new keyword
Type type = typeof(Person);
object instance = Activator.CreateInstance(type);

// With constructor parameters
object instance = Activator.CreateInstance(type, "John", 30);

// Set property value
PropertyInfo nameProp = type.GetProperty("Name");
nameProp.SetValue(instance, "Jane");

// Get property value
object value = nameProp.GetValue(instance);
```

**Dynamic Method Invocation:**
```csharp
public class Calculator
{
    public int Add(int a, int b) => a + b;
    public int Multiply(int a, int b) => a * b;
}

// Invoke method dynamically
Calculator calc = new Calculator();
Type type = typeof(Calculator);
MethodInfo method = type.GetMethod("Add");

// Invoke with parameters
object result = method.Invoke(calc, new object[] { 5, 3 });
Console.WriteLine(result);  // 8
```

**Reading Attributes:**
```csharp
[AttributeUsage(AttributeTargets.Property)]
public class ValidationAttribute : Attribute
{
    public int MaxLength { get; set; }
    public bool Required { get; set; }
}

public class User
{
    [Validation(MaxLength = 50, Required = true)]
    public string Name { get; set; }
    
    [Validation(MaxLength = 100)]
    public string Email { get; set; }
}

// Read attributes using reflection
Type type = typeof(User);
foreach (PropertyInfo prop in type.GetProperties())
{
    var attr = prop.GetCustomAttribute();
    if (attr != null)
    {
        Console.WriteLine($"{prop.Name}: MaxLength={attr.MaxLength}, Required={attr.Required}");
    }
}
```

**Generic Type Creation:**
```csharp
// Create List dynamically
Type listType = typeof(List<>);
Type genericListType = listType.MakeGenericType(typeof(int));
object listInstance = Activator.CreateInstance(genericListType);

MethodInfo addMethod = genericListType.GetMethod("Add");
addMethod.Invoke(listInstance, new object[] { 42 });
```

**Drawbacks and Limitations:**

1. **Performance:**
```csharp
// Direct call
person.Name = "John";  // Fast

// Reflection call
PropertyInfo prop = typeof(Person).GetProperty("Name");
prop.SetValue(person, "John");  // 10-100x slower!
```

2. **Type Safety:**
```csharp
// Compile-time error - caught immediately
// person.NonExistentProperty = "value";  // Won't compile

// Runtime error - only caught when executed
PropertyInfo prop = type.GetProperty("NonExistentProperty");  // Returns null
prop.SetValue(person, "value");  // NullReferenceException at runtime!
```

3. **Security Risks:**
```csharp
// Can access private members!
Type type = typeof(Person);
FieldInfo privateField = type.GetField("secretKey", 
    BindingFlags.NonPublic | BindingFlags.Instance);
privateField.SetValue(person, "hacked");  // Breaks encapsulation!
```

4. **Code Maintenance:**
```csharp
// Refactoring tools can't update string-based references
MethodInfo method = type.GetMethod("OldMethodName");
// If method is renamed, this code breaks at runtime, not compile-time
```

**Performance Comparison:**
```csharp
// Benchmark results (approximate)
// Direct call: 1 ns
// Cached reflection: 10-50 ns
// Uncached reflection: 100-1000 ns
// Expression trees: 5-10 ns
```

**Better Alternatives:**

**1. Expression Trees (faster than reflection):**
```csharp
// Compile expression once, reuse many times
public static class PropertyAccessor
{
    private static readonly Dictionary> Getters = new();
    
    public static object GetValue(T obj, string propertyName)
    {
        if (!Getters.ContainsKey(propertyName))
        {
            var param = Expression.Parameter(typeof(T));
            var prop = Expression.Property(param, propertyName);
            var convert = Expression.Convert(prop, typeof(object));
            var lambda = Expression.Lambda<Func>(convert, param);
            Getters[propertyName] = lambda.Compile();
        }
        
        return Getters[propertyName](obj);
    }
}
```

**2. Source Generators (C# 9+):**
```csharp
// Generate code at compile-time instead of runtime reflection
[AutoMapper]
public partial class PersonDto
{
    public string Name { get; set; }
    // Source generator creates mapping code at compile-time
}
```

**When to Use Reflection:**
- Building frameworks or libraries (DI, ORM, serialization)
- Plugin architectures
- Unit testing tools
- Code generation tools
- When dynamic behavior is absolutely necessary

**When NOT to Use Reflection:**
- Performance-critical code paths
- When compile-time checking is important
- When simpler alternatives exist (interfaces, delegates, generics)
- Hot paths in loops

**Best Practices:**
```csharp
// Cache reflection results
private static readonly PropertyInfo NameProperty = typeof(Person).GetProperty("Name");

// Use binding flags to be specific
type.GetMethod("MyMethod", BindingFlags.Public | BindingFlags.Instance);

// Check for null before using
PropertyInfo prop = type.GetProperty("Name");
if (prop != null)
{
    // Safe to use
}

// Use reflection only when necessary
// Prefer: interfaces, generics, delegates
```

---

### Explain the concept of nullable reference types introduced in C# 8.0.

**Answer:**

**Nullable Reference Types** is a C# 8.0 feature that helps prevent null reference exceptions by making reference types non-nullable by default when enabled.

**Before C# 8.0:**
```csharp
// Any reference type could be null
string name = null;  // Always allowed
Person person = null;  // Always allowed
// NullReferenceException was common at runtime
```

**After C# 8.0 (when enabled):**
```csharp
// Non-nullable reference type (default)
string name = null;  // Compiler warning!

// Nullable reference type (explicit)
string? nullableName = null;  // OK

// Using nullable reference type
void ProcessName(string name)  // name should never be null
{
    Console.WriteLine(name.Length);  // Safe, no null check needed
}

void ProcessNullableName(string? name)  // name might be null
{
    // Compiler warns if you don't check for null
    Console.WriteLine(name.Length);  // Warning!
    
    // Proper null check
    if (name != null)
    {
        Console.WriteLine(name.Length);  // OK
    }
    
    // Or use null-conditional operator
    Console.WriteLine(name?.Length);  // OK
}
```

**Enabling Nullable Reference Types:**

**Project-wide (in .csproj):**
```xml

    enable

```

**File-level:**
```csharp
#nullable enable
public class MyClass
{
    public string Name { get; set; }  // Non-nullable
}
#nullable restore
```

**Nullable Annotations:**
```csharp
public class Person
{
    // Non-nullable - must be initialized
    public string FirstName { get; set; } = string.Empty;
    
    // Non-nullable - initialized in constructor
    public string LastName { get; set; }
    
    // Nullable - can be null
    public string? MiddleName { get; set; }
    
    // Nullable - optional parameter
    public string? Suffix { get; set; }
    
    public Person(string lastName)
    {
        LastName = lastName;
    }
}

// Usage
Person person = new Person("Doe")
{
    FirstName = "John",
    MiddleName = null  // OK, explicitly nullable
};

// Warning - FirstName is non-nullable
// Person invalid = new Person("Doe"); // Warning: FirstName not initialized
```

**Null-Forgiving Operator (!):**
```csharp
public class UserService
{
    private string? _cachedData;
    
    public void Initialize()
    {
        _cachedData = "initialized";
    }
    
    public string GetData()
    {
        // You know it's not null, but compiler doesn't
        // Use ! to tell compiler "trust me, it's not null"
        return _cachedData!;  // Null-forgiving operator
    }
}
```

**Nullable Attributes:**
```csharp
public class StringHelper
{
    // If string is not null/empty, return is not null
    public static bool IsNullOrEmpty([NotNullWhen(false)] string? value)
    {
        return string.IsNullOrEmpty(value);
    }
    
    // Method ensures parameter is not null after return
    public static void ThrowIfNull([NotNull] string? value, string paramName)
    {
        if (value == null)
            throw new ArgumentNullException(paramName);
    }
}

// Usage
string? input = GetUserInput();

if (!StringHelper.IsNullOrEmpty(input))
{
    // Compiler knows input is not null here
    Console.WriteLine(input.Length);  // No warning
}
```

**Common Nullable Attributes:**
```csharp
// [NotNull] - Parameter won't be null when method returns
void EnsureInitialized([NotNull] ref string? value);

// [NotNullWhen(bool)] - Parameter is not null when method returns true/false
bool TryParse(string? input, [NotNullWhen(true)] out int result);

// [NotNullIfNotNull("parameter")] - Return is not null if parameter is not null
[return: NotNullIfNotNull("input")]
string? Process(string? input);

// [MaybeNull] - Return may be null even for non-nullable type
[return: MaybeNull]
T GetValueOrDefault();

// [MemberNotNull("field")] - Ensures field is not null after method
[MemberNotNull(nameof(_cache))]
void Initialize();
```

**Real-World Example:**
```csharp
#nullable enable

public class UserRepository
{
    private readonly DbContext _context;
    
    public UserRepository(DbContext context)
    {
        _context = context;  // Non-nullable, must be provided
    }
    
    // Returns nullable - user might not exist
    public User? FindById(int id)
    {
        return _context.Users.FirstOrDefault(u => u.Id == id);
    }
    
    // Returns non-nullable - throws if not found
    public User GetById(int id)
    {
        return _context.Users.First(u => u.Id == id);
    }
    
    // Parameter is non-nullable - user must not be null
    public void Save(User user)
    {
        ArgumentNullException.ThrowIfNull(user);  // C# 11+
        _context.Users.Add(user);
        _context.SaveChanges();
    }
    
    // Parameter is nullable - updates if exists
    public void UpdateIfExists(User? user)
    {
        if (user == null)
            return;
            
        _context.Users.Update(user);
        _context.SaveChanges();
    }
}

// Usage
var repo = new UserRepository(dbContext);

// Handle nullable return
User? user = repo.FindById(123);
if (user != null)
{
    Console.WriteLine(user.Name);  // Safe
}

// Or use null-conditional
Console.WriteLine(user?.Name ?? "Not found");

// Non-nullable return
User existingUser = repo.GetById(123);  // Throws if not found
Console.WriteLine(existingUser.Name);  // No null check needed
```

**Migration Strategy:**
```csharp
// Step 1: Enable for new files only
#nullable enable
// Your code here
#nullable restore

// Step 2: Gradually enable per project/assembly
// enable

// Step 3: Fix warnings incrementally
// Use nullable annotations where appropriate
// Add null checks where needed
// Use ! operator sparingly for legacy code
```

**Generic Constraints:**
```csharp
// T can be null
public class Container
{
    private T? _value;  // Nullable for any T
}

// T must be non-nullable reference type
public class NonNullContainer where T : notnull
{
    private T _value = default!;  // Must be initialized
}

// T is nullable reference type
public T? GetOrDefault() where T : class
{
    return default;  // Returns null
}
```

**Benefits:**
1. Catch null reference bugs at compile-time
2. Self-documenting code (intent is clear)
3. Better IDE support and intellisense
4. Reduced NullReferenceException at runtime
5. More confident refactoring

**Common Warnings:**
```csharp
// CS8600: Converting null literal or possible null value to non-nullable type
string name = null;  // Warning

// CS8602: Dereference of a possibly null reference
string? nullable = null;
int length = nullable.Length;  // Warning

// CS8603: Possible null reference return
public string GetName()
{
    return null;  // Warning
}

// CS8618: Non-nullable field must contain a non-null value when exiting constructor
public class Person
{
    public string Name { get; set; }  // Warning
}
```

**Best Practices:**
- Enable nullable reference types for new projects
- Use ? for truly optional values
- Avoid using ! (null-forgiving operator) unless necessary
- Add appropriate null checks
- Use nullable attributes to provide hints to compiler
- Make intent explicit in APIs

---

### What is the difference between Finalize() and Dispose() methods?

**Answer:**

Both methods are related to resource cleanup, but they serve different purposes and are called at different times.

**Dispose():**
- Part of IDisposable interface
- Called explicitly by developer
- Deterministic cleanup (you control when)
- Used for managed and unmanaged resources
- Should be called as soon as resource is no longer needed
- Can be called multiple times (should be idempotent)

**Finalize():**
- Also called destructor (~ClassName)
- Called by Garbage Collector
- Non-deterministic cleanup (GC decides when)
- Used primarily for unmanaged resources
- Called when object is being collected
- Cannot be called explicitly
- Delays garbage collection (performance impact)

**Basic Example:**
```csharp
public class ResourceHolder : IDisposable
{
    private IntPtr unmanagedResource;
    private FileStream managedResource;
    private bool disposed = false;
    
    public ResourceHolder()
    {
        unmanagedResource = // Allocate unmanaged resource
        managedResource = new FileStream("file.txt", FileMode.Open);
    }
    
    // IDisposable implementation - called explicitly
    public void Dispose()
    {
        Dispose(true);
        GC.SuppressFinalize(this);  // Tell GC not to call finalizer
    }
    
    // Finalizer - called by GC
    ~ResourceHolder()
    {
        Dispose(false);
    }
    
    // Protected dispose method - actual cleanup logic
    protected virtual void Dispose(bool disposing)
    {
        if (!disposed)
        {
            if (disposing)
            {
                // Dispose managed resources
                managedResource?.Dispose();
            }
            
            // Free unmanaged resources
            if (unmanagedResource != IntPtr.Zero)
            {
                // Free unmanaged resource
                unmanagedResource = IntPtr.Zero;
            }
            
            disposed = true;
        }
    }
}
```

**Key Differences:**

| Aspect | Dispose() | Finalize() |
|--------|-----------|------------|
| Interface | IDisposable | Object (destructor) |
| Invocation | Explicit (using/Dispose()) | Automatic (by GC) |
| Timing | Deterministic | Non-deterministic |
| Performance | Fast | Slow (promotes to Gen2) |
| Resources | Managed + Unmanaged | Unmanaged only |
| Control | Developer | Garbage Collector |
| Can be called multiple times | Yes (should handle) | No (once by GC) |

**Using Dispose() - Recommended Pattern:**
```csharp
// Manual disposal
ResourceHolder resource = new ResourceHolder();
try
{
    // Use resource
}
finally
{
    resource.Dispose();
}

// Better - using statement
using (ResourceHolder resource = new ResourceHolder())
{
    // Use resource
}  // Dispose() called automatically

// C# 8+ - using declaration
using ResourceHolder resource = new ResourceHolder();
// Use resource
// Dispose() called at end of scope
```

**Full Dispose Pattern (IDisposable):**
```csharp
public class DatabaseConnection : IDisposable
{
    private SqlConnection connection;
    private SqlCommand command;
    private bool disposed = false;
    
    public DatabaseConnection(string connectionString)
    {
        connection = new SqlConnection(connectionString);
        command = connection.CreateCommand();
    }
    
    // Public dispose method
    public void Dispose()
    {
        Dispose(disposing: true);
        
        // Tell GC not to call finalizer
        // Improves performance by avoiding finalization queue
        GC.SuppressFinalize(this);
    }
    
    // Protected virtual dispose method
    protected virtual void Dispose(bool disposing)
    {
        if (!disposed)
        {
            if (disposing)
            {
                // Dispose managed resources
                command?.Dispose();
                connection?.Dispose();
            }
            
            // Free unmanaged resources here (if any)
            // Note: Most .NET types handle their own unmanaged resources
            
            disposed = true;
        }
    }
    
    // Optional: Finalizer (only if holding unmanaged resources directly)
    ~DatabaseConnection()
    {
        Dispose(disposing: false);
    }
    
    // Helper method to prevent use after disposal
    private void ThrowIfDisposed()
    {
        if (disposed)
            throw new ObjectDisposedException(GetType().Name);
    }
    
    public void ExecuteQuery(string query)
    {
        ThrowIfDisposed();
        command.CommandText = query;
        command.ExecuteNonQuery();
    }
}
```

**Why Finalize() is Slow:**
```csharp
// Object lifecycle WITHOUT finalizer:
// 1. Object created in Gen0
// 2. GC collects Gen0
// 3. Object memory reclaimed immediately

// Object lifecycle WITH finalizer:
// 1. Object created in Gen0
// 2. GC collects Gen0
// 3. Object moved to finalization queue
// 4. Object promoted to Gen1
// 5. Finalizer thread runs ~ClassName()
// 6. GC collects Gen1
// 7. Object memory finally reclaimed

// Finalizers cause objects to survive at least one GC cycle!
```

**When to Use Each:**

**Use Dispose() when:**
- Working with files, database connections, network connections
- Using any IDisposable resource
- You need immediate cleanup
- Most common scenario

**Use Finalize() when:**
- Directly managing unmanaged resources (rare in modern C#)
- P/Invoke scenarios with unmanaged memory
- Safety net for forgotten Dispose() calls

**Modern Approach - Usually No Finalizer Needed:**
```csharp
public class ModernResourceHolder : IDisposable
{
    private readonly FileStream _file;
    private bool _disposed;
    
    public ModernResourceHolder(string path)
    {
        _file = new FileStream(path, FileMode.Open);
    }
    
    public void Dispose()
    {
        if (_disposed)
            return;
            
        _file?.Dispose();  // FileStream handles its own finalization
        _disposed = true;
    }
    
    // No finalizer needed!
    // FileStream already has its own finalizer
}
```

**SafeHandle - Better than Finalizer:**
```csharp
using System.Runtime.InteropServices;
using Microsoft.Win32.SafeHandles;

public class UnmanagedResource : IDisposable
{
    // SafeHandle provides reliable finalization
    private SafeFileHandle _handle;
    private bool _disposed;
    
    public UnmanagedResource(string path)
    {
        _handle = // Create safe handle
    }
    
    public void Dispose()
    {
        if (_disposed)
            return;
            
        _handle?.Dispose();  // SafeHandle handles finalization
        _disposed = true;
    }
    
    // No finalizer needed!
    // SafeHandle has reliable finalization built-in
}
```

**Common Mistakes:**
```csharp
// WRONG - Accessing managed objects in finalizer
~BadClass()
{
    // Dangerous! Managed objects might already be finalized
    managedResource.Dispose();  // Could throw exception!
}

// WRONG - Not checking if already disposed
public void Dispose()
{
    resource.Dispose();  // Might throw if called twice
}

// WRONG - Forgetting to suppress finalization
public void Dispose()
{
    // Clean up
    // Missing: GC.SuppressFinalize(this);
}

// WRONG - Throwing exceptions in Dispose
public void Dispose()
{
    throw new Exception();  // Never throw from Dispose!
}
```

**Best Practices:**
1. Always implement IDisposable for types that hold disposable resources
2. Make Dispose() safe to call multiple times
3. Call GC.SuppressFinalize(this) in Dispose()
4. Only use finalizers when directly managing unmanaged resources
5. Prefer SafeHandle over manual finalization
6. Never throw exceptions from Dispose() or finalizers
7. Use using statements for automatic disposal
8. Document disposal requirements clearly

---


## Object-Oriented Programming

### Explain the four pillars of OOP with real-world examples.

**Answer:**

The four pillars of Object-Oriented Programming are: **Encapsulation, Abstraction, Inheritance, and Polymorphism**.

**1. Encapsulation:**

Bundling data (fields) and methods that operate on that data within a single unit (class), and restricting direct access to some components.

**Real-world analogy:** A car's engine - you don't need to know how the engine works internally, you just use the gas pedal and steering wheel (public interface).

```csharp
public class BankAccount
{
    // Private fields - hidden from outside
    private decimal balance;
    private string accountNumber;
    private List transactions;
    
    // Public constructor
    public BankAccount(string accountNumber, decimal initialBalance)
    {
        this.accountNumber = accountNumber;
        this.balance = initialBalance;
        transactions = new List();
    }
    
    // Public property with validation
    public decimal Balance
    {
        get { return balance; }
        private set  // Can only be set internally
        {
            if (value < 0)
                throw new InvalidOperationException("Balance cannot be negative");
            balance = value;
        }
    }
    
    // Public methods - controlled interface
    public void Deposit(decimal amount)
    {
        if (amount <= 0)
            throw new ArgumentException("Amount must be positive");
            
        Balance += amount;
        AddTransaction("Deposit", amount);
    }
    
    public bool Withdraw(decimal amount)
    {
        if (amount <= 0)
            throw new ArgumentException("Amount must be positive");
            
        if (balance >= amount)
        {
            Balance -= amount;
            AddTransaction("Withdrawal", -amount);
            return true;
        }
        return false;
    }
    
    // Private helper method
    private void AddTransaction(string type, decimal amount)
    {
        transactions.Add(new Transaction
        {
            Date = DateTime.Now,
            Type = type,
            Amount = amount
        });
    }
}

// Usage - clean public interface, implementation hidden
BankAccount account = new BankAccount("123456", 1000);
account.Deposit(500);  // OK
account.Withdraw(200);  // OK
// account.balance = -1000;  // ERROR - can't access private field
// account.Balance = -1000;  // ERROR - setter is private
```

**Benefits:**
- Data protection and validation
- Flexibility to change implementation
- Controlled access
- Maintainability

**2. Abstraction:**

Hiding complex implementation details and showing only essential features. Focusing on "what" rather than "how".

**Real-world analogy:** Using a smartphone - you tap icons to make calls, send messages, but don't need to understand the underlying cellular technology.

```csharp
// Abstract class - defines contract
public abstract class PaymentProcessor
{
    // Abstract methods - must be implemented
    public abstract bool ProcessPayment(decimal amount);
    public abstract string GetPaymentMethod();
    
    // Concrete method - shared implementation
    public void LogTransaction(decimal amount)
    {
        Console.WriteLine($"{GetPaymentMethod()}: ${amount} at {DateTime.Now}");
    }
    
    // Template method pattern
    public bool MakePayment(decimal amount)
    {
        if (ValidateAmount(amount))
        {
            bool success = ProcessPayment(amount);
            if (success)
            {
                LogTransaction(amount);
            }
            return success;
        }
        return false;
    }
    
    private bool ValidateAmount(decimal amount)
    {
        return amount > 0;
    }
}

// Concrete implementations
public class CreditCardProcessor : PaymentProcessor
{
    private string cardNumber;
    
    public CreditCardProcessor(string cardNumber)
    {
        this.cardNumber = cardNumber;
    }
    
    public override bool ProcessPayment(decimal amount)
    {
        // Credit card specific logic
        Console.WriteLine($"Processing credit card payment: {cardNumber}");
        return true;  // Simplified
    }
    
    public override string GetPaymentMethod()
    {
        return "Credit Card";
    }
}

public class PayPalProcessor : PaymentProcessor
{
    private string email;
    
    public PayPalProcessor(string email)
    {
        this.email = email;
    }
    
    public override bool ProcessPayment(decimal amount)
    {
        // PayPal specific logic
        Console.WriteLine($"Processing PayPal payment: {email}");
        return true;  // Simplified
    }
    
    public override string GetPaymentMethod()
    {
        return "PayPal";
    }
}

// Usage - work with abstraction, not concrete types
public class CheckoutService
{
    public void Checkout(PaymentProcessor processor, decimal amount)
    {
        // Don't care about implementation details
        if (processor.MakePayment(amount))
        {
            Console.WriteLine("Payment successful!");
        }
    }
}

// Client code
CheckoutService checkout = new CheckoutService();
checkout.Checkout(new CreditCardProcessor("1234-5678"), 99.99m);
checkout.Checkout(new PayPalProcessor("user@email.com"), 49.99m);
```

**Benefits:**
- Reduces complexity
- Easier to understand and use
- Changes in implementation don't affect users
- Promotes code reusability

**3. Inheritance:**

Mechanism where a new class derives properties and behaviors from an existing class, establishing a parent-child relationship.

**Real-world analogy:** Biological inheritance - children inherit characteristics from parents (eye color, height), but can have their own unique traits.

```csharp
// Base class
public class Vehicle
{
    public string Make { get; set; }
    public string Model { get; set; }
    public int Year { get; set; }
    protected bool isEngineRunning;
    
    public Vehicle(string make, string model, int year)
    {
        Make = make;
        Model = model;
        Year = year;
    }
    
    public virtual void Start()
    {
        isEngineRunning = true;
        Console.WriteLine($"{Make} {Model} engine started");
    }
    
    public virtual void Stop()
    {
        isEngineRunning = false;
        Console.WriteLine($"{Make} {Model} engine stopped");
    }
    
    public void DisplayInfo()
    {
        Console.WriteLine($"{Year} {Make} {Model}");
    }
}

// Derived class - inherits from Vehicle
public class Car : Vehicle
{
    public int NumberOfDoors { get; set; }
    public string TransmissionType { get; set; }
    
    public Car(string make, string model, int year, int doors, string transmission)
        : base(make, model, year)  // Call parent constructor
    {
        NumberOfDoors = doors;
        TransmissionType = transmission;
    }
    
    // Override parent method
    public override void Start()
    {
        Console.WriteLine("Checking car systems...");
        base.Start();  // Call parent implementation
        Console.WriteLine("Car is ready to drive");
    }
    
    // New method specific to Car
    public void OpenTrunk()
    {
        Console.WriteLine("Trunk opened");
    }
}

// Another derived class
public class Motorcycle : Vehicle
{
    public bool HasSidecar { get; set; }
    
    public Motorcycle(string make, string model, int year, bool hasSidecar)
        : base(make, model, year)
    {
        HasSidecar = hasSidecar;
    }
    
    public override void Start()
    {
        Console.WriteLine("Kick-starting motorcycle...");
        base.Start();
    }
    
    // New method specific to Motorcycle
    public void Wheelie()
    {
        Console.WriteLine("Performing wheelie!");
    }
}

// Derived class from Car
public class ElectricCar : Car
{
    public int BatteryCapacity { get; set; }
    
    public ElectricCar(string make, string model, int year, int doors, int batteryCapacity)
        : base(make, model, year, doors, "Automatic")
    {
        BatteryCapacity = batteryCapacity;
    }
    
    public override void Start()
    {
        Console.WriteLine("Electric car booting up...");
        isEngineRunning = true;  // Can access protected member
        Console.WriteLine("Ready to drive - silent mode");
    }
    
    public void Charge()
    {
        Console.WriteLine("Charging battery...");
    }
}

// Usage
Vehicle vehicle1 = new Car("Toyota", "Camry", 2023, 4, "Automatic");
Vehicle vehicle2 = new Motorcycle("Harley", "Street 750", 2023, false);
Vehicle vehicle3 = new ElectricCar("Tesla", "Model 3", 2023, 4, 75);

vehicle1.Start();  // Calls Car.Start()
vehicle2.Start();  // Calls Motorcycle.Start()
vehicle3.Start();  // Calls ElectricCar.Start()
```

**Benefits:**
- Code reusability (DRY principle)
- Hierarchical classification
- Extensibility
- Polymorphic behavior

**4. Polymorphism:**

Ability of objects to take multiple forms. Same interface, different implementations.

**Real-world analogy:** A person can be a student, employee, athlete simultaneously - same person, different roles/behaviors in different contexts.

**Types of Polymorphism:**

**a) Compile-time Polymorphism (Method Overloading):**
```csharp
public class Calculator
{
    // Same method name, different parameters
    public int Add(int a, int b)
    {
        return a + b;
    }
    
    public double Add(double a, double b)
    {
        return a + b;
    }
    
    public int Add(int a, int b, int c)
    {
        return a + b + c;
    }
    
    public string Add(string a, string b)
    {
        return a + b;
    }
}

// Usage - compiler decides which method to call
Calculator calc = new Calculator();
int result1 = calc.Add(5, 3);           // Calls Add(int, int)
double result2 = calc.Add(5.5, 3.2);    // Calls Add(double, double)
int result3 = calc.Add(5, 3, 2);        // Calls Add(int, int, int)
string result4 = calc.Add("Hello", "World");  // Calls Add(string, string)
```

**b) Runtime Polymorphism (Method Overriding):**
```csharp
// Base class
public abstract class Shape
{
    public abstract double CalculateArea();
    public abstract double CalculatePerimeter();
    
    public virtual void Display()
    {
        Console.WriteLine($"Area: {CalculateArea()}");
        Console.WriteLine($"Perimeter: {CalculatePerimeter()}");
    }
}

// Derived classes with different implementations
public class Circle : Shape
{
    public double Radius { get; set; }
    
    public Circle(double radius)
    {
        Radius = radius;
    }
    
    public override double CalculateArea()
    {
        return Math.PI * Radius * Radius;
    }
    
    public override double CalculatePerimeter()
    {
        return 2 * Math.PI * Radius;
    }
    
    public override void Display()
    {
        Console.WriteLine($"Circle with radius {Radius}");
        base.Display();
    }
}

public class Rectangle : Shape
{
    public double Width { get; set; }
    public double Height { get; set; }
    
    public Rectangle(double width, double height)
    {
        Width = width;
        Height = height;
    }
    
    public override double CalculateArea()
    {
        return Width * Height;
    }
    
    public override double CalculatePerimeter()
    {
        return 2 * (Width + Height);
    }
    
    public override void Display()
    {
        Console.WriteLine($"Rectangle {Width}x{Height}");
        base.Display();
    }
}

public class Triangle : Shape
{
    public double Base { get; set; }
    public double Height { get; set; }
    public double SideA { get; set; }
    public double SideB { get; set; }
    public double SideC { get; set; }
    
    public Triangle(double baseLength, double height, double sideA, double sideB, double sideC)
    {
        Base = baseLength;
        Height = height;
        SideA = sideA;
        SideB = sideB;
        SideC = sideC;
    }
    
    public override double CalculateArea()
    {
        return (Base * Height) / 2;
    }
    
    public override double CalculatePerimeter()
    {
        return SideA + SideB + SideC;
    }
}

// Polymorphic behavior - same interface, different implementations
public class ShapeProcessor
{
    public void ProcessShapes(List shapes)
    {
        double totalArea = 0;
        
        foreach (Shape shape in shapes)
        {
            // Polymorphism in action!
            // Calls appropriate CalculateArea() based on actual type
            totalArea += shape.CalculateArea();
            shape.Display();
            Console.WriteLine("---");
        }
        
        Console.WriteLine($"Total area of all shapes: {totalArea:F2}");
    }
}

// Usage
List shapes = new List
{
    new Circle(5),
    new Rectangle(4, 6),
    new Triangle(3, 4, 3, 4, 5)
};

ShapeProcessor processor = new ShapeProcessor();
processor.ProcessShapes(shapes);  // Each shape behaves differently!
```

**c) Interface Polymorphism:**
```csharp
public interface INotificationSender
{
    void Send(string message, string recipient);
}

public class EmailSender : INotificationSender
{
    public void Send(string message, string recipient)
    {
        Console.WriteLine($"Sending email to {recipient}: {message}");
        // Email sending logic
    }
}

public class SmsSender : INotificationSender
{
    public void Send(string message, string recipient)
    {
        Console.WriteLine($"Sending SMS to {recipient}: {message}");
        // SMS sending logic
    }
}

public class PushNotificationSender : INotificationSender
{
    public void Send(string message, string recipient)
    {
        Console.WriteLine($"Sending push notification to {recipient}: {message}");
        // Push notification logic
    }
}

// Notification service using polymorphism
public class NotificationService
{
    private readonly List senders;
    
    public NotificationService()
    {
        senders = new List
        {
            new EmailSender(),
            new SmsSender(),
            new PushNotificationSender()
        };
    }
    
    public void NotifyAll(string message, string recipient)
    {
        // Polymorphism - each sender implements Send() differently
        foreach (var sender in senders)
        {
            sender.Send(message, recipient);
        }
    }
}

// Usage
NotificationService service = new NotificationService();
service.NotifyAll("Your order has shipped!", "user@example.com");
```

**Benefits:**
- Flexibility and extensibility
- Code reusability
- Easier maintenance
- Loose coupling
- Supports Open/Closed Principle

**Summary of Four Pillars:**

| Pillar | What it does | Key benefit |
|--------|-------------|-------------|
| Encapsulation | Bundles data and methods, hides internals | Data protection, controlled access |
| Abstraction | Hides complexity, shows only essentials | Simplicity, reduces complexity |
| Inheritance | Reuses code from parent classes | Code reusability, hierarchy |
| Polymorphism | Same interface, different implementations | Flexibility, extensibility |

**Real-world complete example combining all four:**
```csharp
// Encapsulation & Abstraction
public abstract class Employee
{
    // Encapsulation - private fields
    private string name;
    private decimal baseSalary;
    
    // Public properties
    public string Name
    {
        get => name;
        set => name = value ?? throw new ArgumentNullException(nameof(value));
    }
    
    protected decimal BaseSalary
    {
        get => baseSalary;
        set => baseSalary = value > 0 ? value : throw new ArgumentException("Salary must be positive");
    }
    
    // Abstraction - abstract method
    public abstract decimal CalculateSalary();
    
    public virtual void DisplayInfo()
    {
        Console.WriteLine($"Employee: {Name}");
        Console.WriteLine($"Salary: ${CalculateSalary():F2}");
    }
}

// Inheritance
public class FullTimeEmployee : Employee
{
    public decimal Bonus { get; set; }
    
    public FullTimeEmployee(string name, decimal baseSalary, decimal bonus)
    {
        Name = name;
        BaseSalary = baseSalary;
        Bonus = bonus;
    }
    
    // Polymorphism - override
    public override decimal CalculateSalary()
    {
        return BaseSalary + Bonus;
    }
}

public class ContractEmployee : Employee
{
    public int HoursWorked { get; set; }
    public decimal HourlyRate { get; set; }
    
    public ContractEmployee(string name, int hours, decimal rate)
    {
        Name = name;
        HoursWorked = hours;
        HourlyRate = rate;
        BaseSalary = 0;
    }
    
    // Polymorphism - different implementation
    public override decimal CalculateSalary()
    {
        return HoursWorked * HourlyRate;
    }
    
    public override void DisplayInfo()
    {
        base.DisplayInfo();
        Console.WriteLine($"Hours: {HoursWorked}, Rate: ${HourlyRate}/hr");
    }
}

// Polymorphic usage
List employees = new List
{
    new FullTimeEmployee("John Doe", 5000, 1000),
    new ContractEmployee("Jane Smith", 160, 50)
};

foreach (Employee emp in employees)
{
    emp.DisplayInfo();  // Polymorphic call
    Console.WriteLine("---");
}
```

---

### What is the SOLID principle? Explain each letter with examples.

**Answer:**

**SOLID** is an acronym for five design principles that make software designs more understandable, flexible, and maintainable.

**S - Single Responsibility Principle (SRP)**

A class should have only one reason to change, meaning it should have only one job or responsibility.

**Bad Example (Violates SRP):**
```csharp
// This class has multiple responsibilities
public class User
{
    public string Name { get; set; }
    public string Email { get; set; }
    
    // Responsibility 1: User data validation
    public bool ValidateEmail()
    {
        return Email.Contains("@");
    }
    
    // Responsibility 2: Database operations
    public void SaveToDatabase()
    {
        // Database save logic
        Console.WriteLine("Saving to database...");
    }
    
    // Responsibility 3: Email notifications
    public void SendWelcomeEmail()
    {
        // Email sending logic
        Console.WriteLine($"Sending email to {Email}");
    }
    
    // Responsibility 4: Report generation
    public string GenerateReport()
    {
        return $"User Report: {Name}";
    }
}
```

**Good Example (Follows SRP):**
```csharp
// Each class has a single responsibility
public class User
{
    public string Name { get; set; }
    public string Email { get; set; }
}

public class UserValidator
{
    public bool ValidateEmail(User user)
    {
        return !string.IsNullOrEmpty(user.Email) && user.Email.Contains("@");
    }
    
    public bool ValidateName(User user)
    {
        return !string.IsNullOrEmpty(user.Name);
    }
}

public class UserRepository
{
    public void Save(User user)
    {
        // Database save logic
        Console.WriteLine($"Saving {user.Name} to database...");
    }
    
    public User GetById(int id)
    {
        // Database retrieval logic
        return new User();
    }
}

public class EmailService
{
    public void SendWelcomeEmail(User user)
    {
        Console.WriteLine($"Sending welcome email to {user.Email}");
    }
}

public class UserReportGenerator
{
    public string GenerateReport(User user)
    {
        return $"User Report: {user.Name} ({user.Email})";
    }
}

// Usage
User user = new User { Name = "John", Email = "john@example.com" };
UserValidator validator = new UserValidator();
if (validator.ValidateEmail(user))
{
    UserRepository repo = new UserRepository();
    repo.Save(user);
    
    EmailService emailService = new EmailService();
    emailService.SendWelcomeEmail(user);
}
```

**O - Open/Closed Principle (OCP)**

Software entities should be open for extension but closed for modification. You should be able to add new functionality without changing existing code.

**Bad Example (Violates OCP):**
```csharp
public class PaymentProcessor
{
    public void ProcessPayment(string paymentType, decimal amount)
    {
        if (paymentType == "CreditCard")
        {
            Console.WriteLine($"Processing credit card payment: ${amount}");
        }
        else if (paymentType == "PayPal")
        {
            Console.WriteLine($"Processing PayPal payment: ${amount}");
        }
        else if (paymentType == "Crypto")
        {
            // Need to modify existing code to add new payment type!
            Console.WriteLine($"Processing crypto payment: ${amount}");
        }
        // Adding new payment type requires modifying this method
    }
}
```

**Good Example (Follows OCP):**
```csharp
// Abstraction - closed for modification
public interface IPaymentMethod
{
    void ProcessPayment(decimal amount);
}

// Open for extension - add new payment methods without changing existing code
public class CreditCardPayment : IPaymentMethod
{
    public void ProcessPayment(decimal amount)
    {
        Console.WriteLine($"Processing credit card payment: ${amount}");
    }
}

public class PayPalPayment : IPaymentMethod
{
    public void ProcessPayment(decimal amount)
    {
        Console.WriteLine($"Processing PayPal payment: ${amount}");
    }
}

public class CryptoPayment : IPaymentMethod
{
    public void ProcessPayment(decimal amount)
    {
        Console.WriteLine($"Processing crypto payment: ${amount}");
    }
}

// Can add new payment methods like ApplePay without modifying existing code
public class ApplePayPayment : IPaymentMethod
{
    public void ProcessPayment(decimal amount)
    {
        Console.WriteLine($"Processing Apple Pay payment: ${amount}");
    }
}

// Processor doesn't need to change when adding new payment types
public class PaymentProcessor
{
    public void Process(IPaymentMethod paymentMethod, decimal amount)
    {
        paymentMethod.ProcessPayment(amount);
    }
}

// Usage
PaymentProcessor processor = new PaymentProcessor();
processor.Process(new CreditCardPayment(), 100);
processor.Process(new PayPalPayment(), 50);
processor.Process(new CryptoPayment(), 200);
processor.Process(new ApplePayPayment(), 75);  // New payment type, no changes needed!
```

**L - Liskov Substitution Principle (LSP)**

Objects of a superclass should be replaceable with objects of its subclasses without breaking the application. Derived classes must be substitutable for their base classes.

**Bad Example (Violates LSP):**
```csharp
public class Bird
{
    public virtual void Fly()
    {
        Console.WriteLine("Flying...");
    }
}

public class Sparrow : Bird
{
    public override void Fly()
    {
        Console.WriteLine("Sparrow flying");
    }
}

public class Penguin : Bird
{
    public override void Fly()
    {
        // Penguins can't fly! This violates LSP
        throw new NotImplementedException("Penguins can't fly!");
    }
}

// Usage - breaks LSP
void MakeBirdFly(Bird bird)
{
    bird.Fly();  // Throws exception if bird is a Penguin!
}
```

**Good Example (Follows LSP):**
```csharp
// Better abstraction
public abstract class Bird
{
    public abstract void Move();
}

public interface IFlyable
{
    void Fly();
}

public interface ISwimmable
{
    void Swim();
}

public class Sparrow : Bird, IFlyable
{
    public override void Move()
    {
        Fly();
    }
    
    public void Fly()
    {
        Console.WriteLine("Sparrow flying");
    }
}

public class Penguin : Bird, ISwimmable
{
    public override void Move()
    {
        Swim();
    }
    
    public void Swim()
    {
        Console.WriteLine("Penguin swimming");
    }
}

public class Duck : Bird, IFlyable, ISwimmable
{
    public override void Move()
    {
        Fly();
    }
    
    public void Fly()
    {
        Console.WriteLine("Duck flying");
    }
    
    public void Swim()
    {
        Console.WriteLine("Duck swimming");
    }
}

// Usage - respects LSP
void MakeBirdMove(Bird bird)
{
    bird.Move();  // Works for all birds!
}

void MakeFlyableFly(IFlyable flyable)
{
    flyable.Fly();  // Only called on birds that can fly
}
```

**I - Interface Segregation Principle (ISP)**

Clients should not be forced to depend on interfaces they don't use. Many specific interfaces are better than one general-purpose interface.

**Bad Example (Violates ISP):**
```csharp
// Fat interface - forces implementations to implement methods they don't need
public interface IWorker
{
    void Work();
    void Eat();
    void Sleep();
    void GetPaid();
}

public class HumanWorker : IWorker
{
    public void Work()
    {
        Console.WriteLine("Human working");
    }
    
    public void Eat()
    {
        Console.WriteLine("Human eating");
    }
    
    public void Sleep()
    {
        Console.WriteLine("Human sleeping");
    }
    
    public void GetPaid()
    {
        Console.WriteLine("Human getting paid");
    }
}

public class RobotWorker : IWorker
{
    public void Work()
    {
        Console.WriteLine("Robot working");
    }
    
    // Robots don't eat or sleep!
    public void Eat()
    {
        throw new NotImplementedException();  // Forced to implement
    }
    
    public void Sleep()
    {
        throw new NotImplementedException();  // Forced to implement
    }
    
    public void GetPaid()
    {
        throw new NotImplementedException();  // Robots don't get paid
    }
}
```

**Good Example (Follows ISP):**
```csharp
// Segregated interfaces - clients only depend on what they need
public interface IWorkable
{
    void Work();
}

public interface IEatable
{
    void Eat();
}

public interface ISleepable
{
    void Sleep();
}

public interface IPayable
{
    void GetPaid();
}

public class HumanWorker : IWorkable, IEatable, ISleepable, IPayable
{
    public void Work()
    {
        Console.WriteLine("Human working");
    }
    
    public void Eat()
    {
        Console.WriteLine("Human eating");
    }
    
    public void Sleep()
    {
        Console.WriteLine("Human sleeping");
    }
    
    public void GetPaid()
    {
        Console.WriteLine("Human getting paid");
    }
}

public class RobotWorker : IWorkable
{
    public void Work()
    {
        Console.WriteLine("Robot working");
    }
    // Only implements what it needs!
}

public class ContractWorker : IWorkable, IPayable
{
    public void Work()
    {
        Console.WriteLine("Contractor working");
    }
    
    public void GetPaid()
    {
        Console.WriteLine("Contractor getting paid");
    }
    // Doesn't need Eat or Sleep
}

// Usage
void ManageWorkable(IWorkable worker)
{
    worker.Work();  // Can work with any workable, don't care about other behaviors
}
```

**D - Dependency Inversion Principle (DIP)**

High-level modules should not depend on low-level modules. Both should depend on abstractions. Abstractions should not depend on details. Details should depend on abstractions.

**Bad Example (Violates DIP):**
```csharp
// Low-level module
public class EmailService
{
    public void SendEmail(string message)
    {
        Console.WriteLine($"Sending email: {message}");
    }
}

// High-level module depends on low-level module directly
public class UserService
{
    private EmailService emailService;  // Tight coupling!
    
    public UserService()
    {
        emailService = new EmailService();  // Creates concrete instance
    }
    
    public void RegisterUser(string username)
    {
        // Registration logic
        emailService.SendEmail($"Welcome {username}");
        // If we want to use SMS instead, we need to modify this class!
    }
}
```

**Good Example (Follows DIP):**
```csharp
// Abstraction
public interface IMessageService
{
    void SendMessage(string message);
}

// Low-level modules implement abstraction
public class EmailService : IMessageService
{
    public void SendMessage(string message)
    {
        Console.WriteLine($"Sending email: {message}");
    }
}

public class SmsService : IMessageService
{
    public void SendMessage(string message)
    {
        Console.WriteLine($"Sending SMS: {message}");
    }
}

public class PushNotificationService : IMessageService
{
    public void SendMessage(string message)
    {
        Console.WriteLine($"Sending push notification: {message}");
    }
}

// High-level module depends on abstraction
public class UserService
{
    private readonly IMessageService messageService;
    
    // Dependency injected through constructor
    public UserService(IMessageService messageService)
    {
        this.messageService = messageService;
    }
    
    public void RegisterUser(string username)
    {
        // Registration logic
        messageService.SendMessage($"Welcome {username}");
        // Works with any IMessageService implementation!
    }
}

// Usage with Dependency Injection
IMessageService emailService = new EmailService();
UserService userService1 = new UserService(emailService);
userService1.RegisterUser("John");

IMessageService smsService = new SmsService();
UserService userService2 = new UserService(smsService);
userService2.RegisterUser("Jane");

// Easy to switch implementations without modifying UserService
```

**Complete Example Demonstrating All SOLID Principles:**
```csharp
// S - Single Responsibility
public class Order
{
    public int OrderId { get; set; }
    public List Items { get; set; }
    public decimal TotalAmount { get; set; }
}

// S - Single Responsibility for validation
public class OrderValidator
{
    public bool Validate(Order order)
    {
        return order != null && order.Items?.Count > 0;
    }
}

// O & D - Open for extension, depends on abstraction
public interface IOrderRepository
{
    void Save(Order order);
}

public interface IPaymentProcessor
{
    bool ProcessPayment(decimal amount);
}

public interface INotificationService
{
    void Notify(string message);
}

// O - Closed for modification, open for extension
public class SqlOrderRepository : IOrderRepository
{
    public void Save(Order order)
    {
        Console.WriteLine("Saving order to SQL database");
    }
}

public class MongoOrderRepository : IOrderRepository
{
    public void Save(Order order)
    {
        Console.WriteLine("Saving order to MongoDB");
    }
}

// I - Interface Segregation - specific interfaces
public class StripePaymentProcessor : IPaymentProcessor
{
    public bool ProcessPayment(decimal amount)
    {
        Console.WriteLine($"Processing ${amount} via Stripe");
        return true;
    }
}

public class EmailNotificationService : INotificationService
{
    public void Notify(string message)
    {
        Console.WriteLine($"Email notification: {message}");
    }
}

// D - High-level module depends on abstractions
public class OrderService
{
    private readonly IOrderRepository repository;
    private readonly IPaymentProcessor paymentProcessor;
    private readonly INotificationService notificationService;
    private readonly OrderValidator validator;
    
    // D - Dependencies injected
    public OrderService(
        IOrderRepository repository,
        IPaymentProcessor paymentProcessor,
        INotificationService notificationService)
    {
        this.repository = repository;
        this.paymentProcessor = paymentProcessor;
        this.notificationService = notificationService;
        this.validator = new OrderValidator();  // S - Single responsibility
    }
    
    public bool PlaceOrder(Order order)
    {
        // S - Single responsibility for each step
        if (!validator.Validate(order))
            return false;
        
        if (!paymentProcessor.ProcessPayment(order.TotalAmount))
            return false;
        
        repository.Save(order);
        notificationService.Notify($"Order {order.OrderId} placed successfully");
        
        return true;
    }
}

// Usage - easy to test and extend
var orderService = new OrderService(
    new SqlOrderRepository(),
    new StripePaymentProcessor(),
    new EmailNotificationService()
);

Order order = new Order
{
    OrderId = 1,
    Items = new List(),
    TotalAmount = 99.99m
};

orderService.PlaceOrder(order);
```

**Benefits of SOLID:**
- Easier to maintain and extend
- More testable code
- Reduced coupling
- Better code organization
- Easier to understand
- Facilitates refactoring

---
# C# Object-Oriented Programming Concepts

### What is the difference between method overloading and method overriding?

**Method Overloading** occurs when multiple methods in the same class have the same name but different parameters (different number, type, or order of parameters). It's a compile-time polymorphism.

**Method Overriding** occurs when a derived class provides a specific implementation of a method that is already defined in its base class. It's a runtime polymorphism.

**Example:**

```csharp
// Method Overloading
public class Calculator
{
    // Same method name, different parameters
    public int Add(int a, int b)
    {
        return a + b;
    }
    
    public int Add(int a, int b, int c)
    {
        return a + b + c;
    }
    
    public double Add(double a, double b)
    {
        return a + b;
    }
}

// Method Overriding
public class Animal
{
    public virtual void MakeSound()
    {
        Console.WriteLine("Some generic animal sound");
    }
}

public class Dog : Animal
{
    public override void MakeSound()
    {
        Console.WriteLine("Woof!");
    }
}

public class Cat : Animal
{
    public override void MakeSound()
    {
        Console.WriteLine("Meow!");
    }
}

// Usage
var calc = new Calculator();
calc.Add(5, 10);        // Calls first method
calc.Add(5, 10, 15);    // Calls second method

Animal myDog = new Dog();
myDog.MakeSound();      // Outputs: Woof!
```

---

### Explain the concept of polymorphism with examples.

**Polymorphism** means "many forms" and allows objects to be treated as instances of their parent class while exhibiting behavior specific to their actual class. There are two types:

1. **Compile-time Polymorphism** (Static) - Method Overloading, Operator Overloading
2. **Runtime Polymorphism** (Dynamic) - Method Overriding

**Example:**

```csharp
// Runtime Polymorphism Example
public abstract class Shape
{
    public abstract double CalculateArea();
}

public class Circle : Shape
{
    public double Radius { get; set; }
    
    public Circle(double radius)
    {
        Radius = radius;
    }
    
    public override double CalculateArea()
    {
        return Math.PI * Radius * Radius;
    }
}

public class Rectangle : Shape
{
    public double Width { get; set; }
    public double Height { get; set; }
    
    public Rectangle(double width, double height)
    {
        Width = width;
        Height = height;
    }
    
    public override double CalculateArea()
    {
        return Width * Height;
    }
}

public class Triangle : Shape
{
    public double Base { get; set; }
    public double Height { get; set; }
    
    public Triangle(double baseLength, double height)
    {
        Base = baseLength;
        Height = height;
    }
    
    public override double CalculateArea()
    {
        return 0.5 * Base * Height;
    }
}

// Usage - Single interface, multiple forms
List<Shape> shapes = new List<Shape>
{
    new Circle(5),
    new Rectangle(4, 6),
    new Triangle(3, 8)
};

foreach (Shape shape in shapes)
{
    Console.WriteLine($"Area: {shape.CalculateArea()}");
    // Each shape calculates area differently (polymorphic behavior)
}
```

---

### What are sealed classes and sealed methods?

**Sealed Classes** are classes that cannot be inherited. They prevent other classes from deriving from them.

**Sealed Methods** are overridden methods that cannot be overridden further in derived classes.

**Example:**

```csharp
// Sealed Class Example
public sealed class FinalClass
{
    public void Display()
    {
        Console.WriteLine("This class cannot be inherited");
    }
}

// This will cause a compilation error
// public class DerivedClass : FinalClass { }  // ERROR!

// Sealed Method Example
public class BaseClass
{
    public virtual void Print()
    {
        Console.WriteLine("Base Print");
    }
}

public class MiddleClass : BaseClass
{
    public sealed override void Print()
    {
        Console.WriteLine("Middle Print - This cannot be overridden further");
    }
}

public class DerivedClass : MiddleClass
{
    // This will cause a compilation error
    // public override void Print() { }  // ERROR! Cannot override sealed method
}

// Real-world example: String class in .NET is sealed
// public sealed class String { ... }
```

---

### Describe the difference between composition and inheritance.

**Inheritance** ("is-a" relationship) - A class derives from another class and inherits its members.

**Composition** ("has-a" relationship) - A class contains instances of other classes as members.

**Key Principle:** Favor composition over inheritance for better flexibility and loose coupling.

**Example:**

```csharp
// Inheritance Example (is-a relationship)
public class Vehicle
{
    public string Brand { get; set; }
    public void Start()
    {
        Console.WriteLine("Vehicle started");
    }
}

public class Car : Vehicle  // Car IS-A Vehicle
{
    public int NumberOfDoors { get; set; }
}

// Composition Example (has-a relationship)
public class Engine
{
    public int Horsepower { get; set; }
    
    public void Start()
    {
        Console.WriteLine("Engine started");
    }
}

public class Transmission
{
    public string Type { get; set; }
    
    public void ShiftGear()
    {
        Console.WriteLine("Gear shifted");
    }
}

public class Car2
{
    // Car HAS-A Engine
    private Engine engine;
    // Car HAS-A Transmission
    private Transmission transmission;
    
    public Car2()
    {
        engine = new Engine { Horsepower = 200 };
        transmission = new Transmission { Type = "Automatic" };
    }
    
    public void Start()
    {
        engine.Start();
        Console.WriteLine("Car is ready to drive");
    }
    
    public void Drive()
    {
        transmission.ShiftGear();
    }
}

// Why Composition is often better:
// 1. More flexible - can change components at runtime
// 2. No tight coupling
// 3. Avoids deep inheritance hierarchies
// 4. Easier to test and maintain
```

---

### What is the Liskov Substitution Principle and why is it important?

The **Liskov Substitution Principle (LSP)** is one of the SOLID principles. It states that objects of a derived class should be able to replace objects of the base class without affecting the correctness of the program.

**In simple terms:** If class B is a subtype of class A, then objects of type A should be replaceable with objects of type B without breaking the application.

**Example:**

```csharp
// Violation of LSP
public class Rectangle
{
    public virtual int Width { get; set; }
    public virtual int Height { get; set; }
    
    public int GetArea()
    {
        return Width * Height;
    }
}

public class Square : Rectangle
{
    private int side;
    
    public override int Width
    {
        get { return side; }
        set { side = value; }  // Setting width also affects height
    }
    
    public override int Height
    {
        get { return side; }
        set { side = value; }  // Setting height also affects width
    }
}

// This violates LSP because:
void TestRectangle(Rectangle rect)
{
    rect.Width = 5;
    rect.Height = 4;
    Console.WriteLine(rect.GetArea());  // Expected: 20
    // But if rect is Square, result will be 16 (4*4), breaking expectations
}

// Correct approach following LSP
public abstract class Shape
{
    public abstract int GetArea();
}

public class Rectangle : Shape
{
    public int Width { get; set; }
    public int Height { get; set; }
    
    public override int GetArea()
    {
        return Width * Height;
    }
}

public class Square : Shape
{
    public int Side { get; set; }
    
    public override int GetArea()
    {
        return Side * Side;
    }
}

// Why LSP is important:
// 1. Ensures reliable polymorphism
// 2. Prevents unexpected behavior in derived classes
// 3. Makes code more maintainable and predictable
// 4. Enables proper use of inheritance hierarchies
```

---

### Explain dependency injection and its benefits.

**Dependency Injection (DI)** is a design pattern where objects receive their dependencies from external sources rather than creating them internally. It implements the Dependency Inversion Principle (one of SOLID principles).

**Three types of DI:**
1. Constructor Injection (most common)
2. Property/Setter Injection
3. Method Injection

**Example:**

```csharp
// WITHOUT Dependency Injection (Tight Coupling)
public class EmailService
{
    public void SendEmail(string message)
    {
        Console.WriteLine($"Sending email: {message}");
    }
}

public class NotificationService
{
    private EmailService emailService;
    
    public NotificationService()
    {
        // Tightly coupled - hard to test and change
        emailService = new EmailService();
    }
    
    public void Notify(string message)
    {
        emailService.SendEmail(message);
    }
}

// WITH Dependency Injection (Loose Coupling)
public interface IMessageService
{
    void SendMessage(string message);
}

public class EmailService : IMessageService
{
    public void SendMessage(string message)
    {
        Console.WriteLine($"Sending email: {message}");
    }
}

public class SmsService : IMessageService
{
    public void SendMessage(string message)
    {
        Console.WriteLine($"Sending SMS: {message}");
    }
}

// Constructor Injection
public class NotificationService
{
    private readonly IMessageService messageService;
    
    // Dependency is injected through constructor
    public NotificationService(IMessageService messageService)
    {
        this.messageService = messageService;
    }
    
    public void Notify(string message)
    {
        messageService.SendMessage(message);
    }
}

// Usage
var emailService = new EmailService();
var notificationService = new NotificationService(emailService);
notificationService.Notify("Hello via Email");

// Can easily switch to SMS
var smsService = new SmsService();
var smsNotificationService = new NotificationService(smsService);
smsNotificationService.Notify("Hello via SMS");

// Using DI Container (e.g., Microsoft.Extensions.DependencyInjection)
// In Startup.cs or Program.cs
services.AddScoped<IMessageService, EmailService>();
services.AddScoped<NotificationService>();
```

**Benefits of Dependency Injection:**
1. **Loose Coupling** - Classes depend on abstractions, not concrete implementations
2. **Testability** - Easy to mock dependencies for unit testing
3. **Maintainability** - Changes in dependencies don't affect dependent classes
4. **Flexibility** - Easy to swap implementations without changing code
5. **Reusability** - Components can be reused in different contexts

---

### What are design patterns? Name and explain 5 commonly used patterns.

**Design Patterns** are reusable solutions to common software design problems. They represent best practices and provide a template for solving specific issues in software development.

#### 1. Singleton Pattern
Ensures a class has only one instance and provides a global point of access to it.

```csharp
public sealed class DatabaseConnection
{
    private static DatabaseConnection instance = null;
    private static readonly object lockObject = new object();
    
    private DatabaseConnection()
    {
        // Private constructor prevents instantiation
    }
    
    public static DatabaseConnection Instance
    {
        get
        {
            lock (lockObject)
            {
                if (instance == null)
                {
                    instance = new DatabaseConnection();
                }
                return instance;
            }
        }
    }
    
    public void Query(string sql)
    {
        Console.WriteLine($"Executing: {sql}");
    }
}

// Usage
var db1 = DatabaseConnection.Instance;
var db2 = DatabaseConnection.Instance;
// db1 and db2 refer to the same instance
```

#### 2. Factory Pattern
Creates objects without specifying the exact class to create.

```csharp
public interface IPayment
{
    void ProcessPayment(decimal amount);
}

public class CreditCardPayment : IPayment
{
    public void ProcessPayment(decimal amount)
    {
        Console.WriteLine($"Processing credit card payment: ${amount}");
    }
}

public class PayPalPayment : IPayment
{
    public void ProcessPayment(decimal amount)
    {
        Console.WriteLine($"Processing PayPal payment: ${amount}");
    }
}

public class CryptoPayment : IPayment
{
    public void ProcessPayment(decimal amount)
    {
        Console.WriteLine($"Processing crypto payment: ${amount}");
    }
}

public class PaymentFactory
{
    public static IPayment CreatePayment(string paymentType)
    {
        return paymentType.ToLower() switch
        {
            "creditcard" => new CreditCardPayment(),
            "paypal" => new PayPalPayment(),
            "crypto" => new CryptoPayment(),
            _ => throw new ArgumentException("Invalid payment type")
        };
    }
}

// Usage
IPayment payment = PaymentFactory.CreatePayment("creditcard");
payment.ProcessPayment(100.50m);
```

#### 3. Observer Pattern
Defines a one-to-many dependency between objects so that when one object changes state, all its dependents are notified.

```csharp
public interface IObserver
{
    void Update(string message);
}

public interface ISubject
{
    void Attach(IObserver observer);
    void Detach(IObserver observer);
    void Notify(string message);
}

public class NewsAgency : ISubject
{
    private List<IObserver> observers = new List<IObserver>();
    
    public void Attach(IObserver observer)
    {
        observers.Add(observer);
    }
    
    public void Detach(IObserver observer)
    {
        observers.Remove(observer);
    }
    
    public void Notify(string message)
    {
        foreach (var observer in observers)
        {
            observer.Update(message);
        }
    }
    
    public void PublishNews(string news)
    {
        Console.WriteLine($"Breaking News: {news}");
        Notify(news);
    }
}

public class NewsChannel : IObserver
{
    public string Name { get; set; }
    
    public NewsChannel(string name)
    {
        Name = name;
    }
    
    public void Update(string message)
    {
        Console.WriteLine($"{Name} received news: {message}");
    }
}

// Usage
var agency = new NewsAgency();
var channel1 = new NewsChannel("CNN");
var channel2 = new NewsChannel("BBC");

agency.Attach(channel1);
agency.Attach(channel2);
agency.PublishNews("Major event occurred!");
```

#### 4. Strategy Pattern
Defines a family of algorithms, encapsulates each one, and makes them interchangeable.

```csharp
public interface ISortStrategy
{
    void Sort(List<int> list);
}

public class BubbleSort : ISortStrategy
{
    public void Sort(List<int> list)
    {
        Console.WriteLine("Sorting using Bubble Sort");
        // Bubble sort implementation
        for (int i = 0; i < list.Count - 1; i++)
        {
            for (int j = 0; j < list.Count - i - 1; j++)
            {
                if (list[j] > list[j + 1])
                {
                    int temp = list[j];
                    list[j] = list[j + 1];
                    list[j + 1] = temp;
                }
            }
        }
    }
}

public class QuickSort : ISortStrategy
{
    public void Sort(List<int> list)
    {
        Console.WriteLine("Sorting using Quick Sort");
        // Quick sort implementation
        list.Sort();
    }
}

public class SortContext
{
    private ISortStrategy sortStrategy;
    
    public void SetSortStrategy(ISortStrategy strategy)
    {
        sortStrategy = strategy;
    }
    
    public void SortList(List<int> list)
    {
        sortStrategy.Sort(list);
    }
}

// Usage
var numbers = new List<int> { 5, 2, 8, 1, 9 };
var context = new SortContext();

context.SetSortStrategy(new BubbleSort());
context.SortList(numbers);

context.SetSortStrategy(new QuickSort());
context.SortList(numbers);
```

#### 5. Repository Pattern
Mediates between the domain and data mapping layers, acting like an in-memory collection of domain objects.

```csharp
public class Product
{
    public int Id { get; set; }
    public string Name { get; set; }
    public decimal Price { get; set; }
}

public interface IRepository<T> where T : class
{
    T GetById(int id);
    IEnumerable<T> GetAll();
    void Add(T entity);
    void Update(T entity);
    void Delete(int id);
}

public class ProductRepository : IRepository<Product>
{
    private List<Product> products = new List<Product>();
    
    public Product GetById(int id)
    {
        return products.FirstOrDefault(p => p.Id == id);
    }
    
    public IEnumerable<Product> GetAll()
    {
        return products;
    }
    
    public void Add(Product entity)
    {
        products.Add(entity);
        Console.WriteLine($"Product {entity.Name} added");
    }
    
    public void Update(Product entity)
    {
        var existing = GetById(entity.Id);
        if (existing != null)
        {
            existing.Name = entity.Name;
            existing.Price = entity.Price;
            Console.WriteLine($"Product {entity.Id} updated");
        }
    }
    
    public void Delete(int id)
    {
        var product = GetById(id);
        if (product != null)
        {
            products.Remove(product);
            Console.WriteLine($"Product {id} deleted");
        }
    }
}

// Usage
var repository = new ProductRepository();
repository.Add(new Product { Id = 1, Name = "Laptop", Price = 999.99m });
repository.Add(new Product { Id = 2, Name = "Mouse", Price = 29.99m });

var allProducts = repository.GetAll();
var laptop = repository.GetById(1);
```

---

### What is the difference between shallow copy and deep copy?

**Shallow Copy** creates a new object but copies only the reference of nested objects. Changes to nested objects affect both the original and copied object.

**Deep Copy** creates a new object and recursively copies all nested objects. Changes to the copy don't affect the original.

**Example:**

```csharp
public class Address
{
    public string Street { get; set; }
    public string City { get; set; }
    
    public Address Clone()
    {
        return new Address
        {
            Street = this.Street,
            City = this.City
        };
    }
}

public class Person
{
    public string Name { get; set; }
    public int Age { get; set; }
    public Address Address { get; set; }
    
    // Shallow Copy using MemberwiseClone
    public Person ShallowCopy()
    {
        return (Person)this.MemberwiseClone();
    }
    
    // Deep Copy - manually copying all reference types
    public Person DeepCopy()
    {
        return new Person
        {
            Name = this.Name,
            Age = this.Age,
            Address = this.Address?.Clone()  // Clone nested object
        };
    }
}

// Demonstration
class Program
{
    static void Main()
    {
        // Original object
        var person1 = new Person
        {
            Name = "John",
            Age = 30,
            Address = new Address { Street = "123 Main St", City = "New York" }
        };
        
        // Shallow Copy
        var shallowCopy = person1.ShallowCopy();
        shallowCopy.Name = "Jane";  // Changing value type
        shallowCopy.Address.City = "Los Angeles";  // Changing reference type
        
        Console.WriteLine("After Shallow Copy:");
        Console.WriteLine($"Original: {person1.Name}, {person1.Address.City}");
        // Output: Original: John, Los Angeles (City changed!)
        Console.WriteLine($"Shallow Copy: {shallowCopy.Name}, {shallowCopy.Address.City}");
        // Output: Shallow Copy: Jane, Los Angeles
        
        Console.WriteLine();
        
        // Deep Copy
        var person2 = new Person
        {
            Name = "Bob",
            Age = 25,
            Address = new Address { Street = "456 Oak Ave", City = "Chicago" }
        };
        
        var deepCopy = person2.DeepCopy();
        deepCopy.Name = "Alice";
        deepCopy.Address.City = "Boston";
        
        Console.WriteLine("After Deep Copy:");
        Console.WriteLine($"Original: {person2.Name}, {person2.Address.City}");
        // Output: Original: Bob, Chicago (City unchanged!)
        Console.WriteLine($"Deep Copy: {deepCopy.Name}, {deepCopy.Address.City}");
        // Output: Deep Copy: Alice, Boston
    }
}

// Alternative: Using serialization for deep copy
public class PersonSerializable
{
    public string Name { get; set; }
    public int Age { get; set; }
    public Address Address { get; set; }
    
    public PersonSerializable DeepCopyUsingSerialization()
    {
        using (var stream = new MemoryStream())
        {
            var formatter = new BinaryFormatter();
            formatter.Serialize(stream, this);
            stream.Position = 0;
            return (PersonSerializable)formatter.Deserialize(stream);
        }
    }
}
```

**Key Differences:**

| Aspect | Shallow Copy | Deep Copy |
|--------|--------------|-----------|
| Reference Types | Copies references only | Creates new instances |
| Independence | Nested objects are shared | Completely independent |
| Performance | Faster | Slower |
| Memory | Uses less memory | Uses more memory |
| Implementation | Simple (MemberwiseClone) | Complex (manual or serialization) |
---

## Asynchronous Programming

### Explain `async` and `await` keywords in C#.

**`async`** is a modifier that marks a method as asynchronous, indicating it can contain asynchronous operations.

**`await`** is an operator that suspends the execution of an async method until the awaited task completes, without blocking the thread.

**How it works:**
- When `await` is encountered, the method returns control to its caller
- The thread is freed to do other work
- When the awaited task completes, execution resumes from where it left off

**Example:**

```csharp
// Basic async/await example
public class DataService
{
    // Async method must return Task, Task, or void (avoid void except for event handlers)
    public async Task GetDataAsync()
    {
        // Simulate a network call or database operation
        await Task.Delay(2000); // Non-blocking delay
        return "Data retrieved successfully";
    }
    
    public async Task CalculateAsync(int x, int y)
    {
        // Simulate CPU-intensive work
        await Task.Run(() =>
        {
            Thread.Sleep(1000);
        });
        
        return x + y;
    }
}

// Calling async methods
public class Program
{
    public static async Task Main(string[] args)
    {
        var service = new DataService();
        
        Console.WriteLine("Starting async operation...");
        
        // await suspends execution until GetDataAsync completes
        string result = await service.GetDataAsync();
        Console.WriteLine(result);
        
        // Multiple async operations
        int sum = await service.CalculateAsync(5, 10);
        Console.WriteLine($"Sum: {sum}");
    }
}

// Real-world example: Fetching data from an API
public class WeatherService
{
    private readonly HttpClient httpClient = new HttpClient();
    
    public async Task GetWeatherAsync(string city)
    {
        try
        {
            Console.WriteLine($"Fetching weather for {city}...");
            
            // await makes the HTTP call non-blocking
            string response = await httpClient.GetStringAsync(
                $"https://api.weather.com/forecast?city={city}"
            );
            
            Console.WriteLine("Weather data received");
            return response;
        }
        catch (HttpRequestException ex)
        {
            Console.WriteLine($"Error: {ex.Message}");
            return null;
        }
    }
    
    // Processing multiple cities concurrently
    public async Task<List> GetWeatherForMultipleCitiesAsync(List cities)
    {
        var tasks = cities.Select(city => GetWeatherAsync(city));
        
        // Wait for all tasks to complete
        string[] results = await Task.WhenAll(tasks);
        
        return results.ToList();
    }
}

// Usage
var weatherService = new WeatherService();
var cities = new List { "New York", "London", "Tokyo" };
var weatherData = await weatherService.GetWeatherForMultipleCitiesAsync(cities);
```

**Key Points:**
- `async` methods should be named with the `Async` suffix by convention
- `await` can only be used inside `async` methods
- `async void` should be avoided (except for event handlers) - use `async Task` instead
- Exception handling works naturally with try/catch blocks

---

### What is the difference between `Task` and `Thread`?

**Thread** is a lower-level construct that represents an actual OS thread. It's part of the threading infrastructure.

**Task** is a higher-level abstraction that represents an asynchronous operation. It doesn't necessarily map to a single thread.

**Example:**

```csharp
// Using Thread (lower-level, more control, more overhead)
public class ThreadExample
{
    public void RunWithThread()
    {
        Thread thread = new Thread(() =>
        {
            Console.WriteLine($"Thread ID: {Thread.CurrentThread.ManagedThreadId}");
            Thread.Sleep(2000);
            Console.WriteLine("Thread work completed");
        });
        
        thread.Start();
        thread.Join(); // Wait for thread to complete
    }
    
    // Creating multiple threads
    public void RunMultipleThreads()
    {
        for (int i = 0; i < 5; i++)
        {
            int taskNumber = i;
            Thread thread = new Thread(() =>
            {
                Console.WriteLine($"Thread {taskNumber} executing");
                Thread.Sleep(1000);
            });
            thread.Start();
        }
    }
}

// Using Task (higher-level, better performance, easier to use)
public class TaskExample
{
    public async Task RunWithTaskAsync()
    {
        await Task.Run(() =>
        {
            Console.WriteLine($"Task on Thread ID: {Thread.CurrentThread.ManagedThreadId}");
            Thread.Sleep(2000);
            Console.WriteLine("Task work completed");
        });
    }
    
    // Creating multiple tasks
    public async Task RunMultipleTasksAsync()
    {
        var tasks = new List();
        
        for (int i = 0; i < 5; i++)
        {
            int taskNumber = i;
            tasks.Add(Task.Run(() =>
            {
                Console.WriteLine($"Task {taskNumber} executing on Thread {Thread.CurrentThread.ManagedThreadId}");
                Thread.Sleep(1000);
            }));
        }
        
        await Task.WhenAll(tasks); // Wait for all tasks to complete
    }
    
    // Task with return value
    public async Task CalculateAsync()
    {
        return await Task.Run(() =>
        {
            Thread.Sleep(1000);
            return 42;
        });
    }
}

// Comparison example
public class ComparisonDemo
{
    public void CompareThreadAndTask()
    {
        // Thread approach - manual management
        var threads = new List();
        for (int i = 0; i < 10; i++)
        {
            var thread = new Thread(() => DoWork());
            threads.Add(thread);
            thread.Start();
        }
        
        foreach (var thread in threads)
        {
            thread.Join(); // Wait for completion
        }
        
        // Task approach - automatic management
        var tasks = new List();
        for (int i = 0; i < 10; i++)
        {
            tasks.Add(Task.Run(() => DoWork()));
        }
        
        Task.WaitAll(tasks.ToArray()); // Wait for completion
    }
    
    private void DoWork()
    {
        Thread.Sleep(500);
    }
}

// Task with proper async/await pattern
public class AsyncPatternExample
{
    public async Task FetchDataAsync()
    {
        // This doesn't block the calling thread
        await Task.Delay(1000);
        return "Data fetched";
    }
    
    public async Task ProcessDataAsync()
    {
        Console.WriteLine("Start processing");
        
        // Multiple async operations
        var task1 = FetchDataAsync();
        var task2 = FetchDataAsync();
        var task3 = FetchDataAsync();
        
        // Wait for all to complete
        string[] results = await Task.WhenAll(task1, task2, task3);
        
        Console.WriteLine($"Processed {results.Length} items");
    }
}
```

**Key Differences:**

| Aspect | Thread | Task |
|--------|--------|------|
| Level | Low-level OS construct | High-level abstraction |
| Resource Usage | Heavy (1 MB stack per thread) | Lightweight |
| Pooling | No built-in pooling | Uses ThreadPool |
| Return Value | Cannot return values easily | Can return values via Task<T> |
| Exception Handling | Complex | Integrated with async/await |
| Cancellation | Manual implementation | Built-in via CancellationToken |
| Composability | Difficult | Easy with Task.WhenAll, WhenAny |
| Use Case | Low-level threading control | Most async operations |

---

### What is `Task.Run()` vs `Task.Factory.StartNew()`?

**`Task.Run()`** is the simpler, modern method for starting a task. It's the recommended approach for most scenarios.

**`Task.Factory.StartNew()`** provides more control and configuration options but is more complex and has some gotchas.

**Example:**

```csharp
public class TaskCreationComparison
{
    // Task.Run() - Simple and recommended
    public async Task RunWithTaskRunAsync()
    {
        // Task.Run() always uses TaskScheduler.Default (ThreadPool)
        var result = await Task.Run(() =>
        {
            Console.WriteLine($"Task.Run on thread: {Thread.CurrentThread.ManagedThreadId}");
            Thread.Sleep(1000);
            return 42;
        });
        
        Console.WriteLine($"Result: {result}");
    }
    
    // Task.Run() with async lambda
    public async Task RunWithAsyncLambdaAsync()
    {
        // Task.Run properly unwraps async lambdas
        var result = await Task.Run(async () =>
        {
            await Task.Delay(1000);
            return "Completed";
        });
        
        Console.WriteLine(result);
    }
    
    // Task.Factory.StartNew() - More control but complex
    public async Task RunWithFactoryStartNewAsync()
    {
        // Requires explicit unwrapping for async lambdas
        var task = Task.Factory.StartNew(() =>
        {
            Console.WriteLine($"Factory.StartNew on thread: {Thread.CurrentThread.ManagedThreadId}");
            Thread.Sleep(1000);
            return 42;
        });
        
        var result = await task;
        Console.WriteLine($"Result: {result}");
    }
    
    // Task.Factory.StartNew() with options
    public async Task RunWithOptionsAsync()
    {
        var task = Task.Factory.StartNew(
            () =>
            {
                Console.WriteLine("Long-running task started");
                Thread.Sleep(5000);
                return "Done";
            },
            CancellationToken.None,
            TaskCreationOptions.LongRunning, // Creates dedicated thread
            TaskScheduler.Default
        );
        
        var result = await task;
        Console.WriteLine(result);
    }
    
    // Demonstrating the async lambda gotcha with Factory.StartNew
    public async Task DemonstrateGotchaAsync()
    {
        // WRONG: This returns Task<Task>, not Task
        Task<Task> outerTask = Task.Factory.StartNew(async () =>
        {
            await Task.Delay(1000);
            return "Result";
        });
        
        // Need to unwrap manually
        Task innerTask = await outerTask;
        string result = await innerTask;
        
        // OR use Unwrap()
        var unwrappedTask = Task.Factory.StartNew(async () =>
        {
            await Task.Delay(1000);
            return "Result";
        }).Unwrap();
        
        result = await unwrappedTask;
        
        // Task.Run handles this automatically - CORRECT WAY
        result = await Task.Run(async () =>
        {
            await Task.Delay(1000);
            return "Result";
        });
    }
}

// Practical examples showing when to use each
public class PracticalExamples
{
    // Use Task.Run for most scenarios
    public async Task<List> ProcessDataAsync(List data)
    {
        // Offload CPU-intensive work to thread pool
        return await Task.Run(() =>
        {
            return data.Select(x => x * x).ToList();
        });
    }
    
    // Use Task.Factory.StartNew for long-running tasks
    public Task StartBackgroundServiceAsync()
    {
        return Task.Factory.StartNew(
            () =>
            {
                while (true)
                {
                    // Long-running background work
                    Console.WriteLine("Service running...");
                    Thread.Sleep(5000);
                }
            },
            TaskCreationOptions.LongRunning // Gets dedicated thread
        );
    }
    
    // Use Task.Factory.StartNew with custom scheduler
    public async Task RunWithCustomSchedulerAsync()
    {
        var scheduler = new CustomTaskScheduler();
        
        var task = Task.Factory.StartNew(
            () =>
            {
                Console.WriteLine("Running with custom scheduler");
                return 100;
            },
            CancellationToken.None,
            TaskCreationOptions.None,
            scheduler
        );
        
        var result = await task;
        Console.WriteLine($"Result: {result}");
    }
}

// Custom task scheduler example
public class CustomTaskScheduler : TaskScheduler
{
    protected override IEnumerable GetScheduledTasks()
    {
        return Enumerable.Empty();
    }
    
    protected override void QueueTask(Task task)
    {
        ThreadPool.QueueUserWorkItem(_ => TryExecuteTask(task));
    }
    
    protected override bool TryExecuteTaskInline(Task task, bool taskWasPreviouslyQueued)
    {
        return TryExecuteTask(task);
    }
}
```

**Key Differences:**

| Aspect | Task.Run() | Task.Factory.StartNew() |
|--------|-----------|-------------------------|
| Simplicity | Simple, recommended | Complex, more options |
| Default Scheduler | ThreadPool (TaskScheduler.Default) | Can specify custom scheduler |
| Async Lambda | Automatically unwraps | Returns Task<Task<T>> - needs Unwrap() |
| Task Options | Limited options | Full TaskCreationOptions |
| Long-Running | Not ideal | Supports LongRunning option |
| When to Use | 99% of scenarios | Custom schedulers, long-running tasks |

**Recommendation:** Use `Task.Run()` unless you specifically need the advanced features of `Task.Factory.StartNew()`.

---

### Explain what `ConfigureAwait(false)` does and when to use it.

**`ConfigureAwait(false)`** tells the awaited task not to capture and resume on the original synchronization context. This improves performance and avoids potential deadlocks in library code.

**When to use:**
- In library code (not UI code)
- When you don't need to return to the original context
- To improve performance
- To avoid deadlocks

**Example:**

```csharp
// Understanding SynchronizationContext
public class SynchronizationContextExample
{
    // WITHOUT ConfigureAwait(false) - captures context
    public async Task GetDataWithContextAsync()
    {
        Console.WriteLine($"Before await - Thread: {Thread.CurrentThread.ManagedThreadId}");
        
        // By default, await captures the current SynchronizationContext
        await Task.Delay(1000);
        
        // Resumes on the same context (same thread in UI apps)
        Console.WriteLine($"After await - Thread: {Thread.CurrentThread.ManagedThreadId}");
        
        return "Data with context";
    }
    
    // WITH ConfigureAwait(false) - doesn't capture context
    public async Task GetDataWithoutContextAsync()
    {
        Console.WriteLine($"Before await - Thread: {Thread.CurrentThread.ManagedThreadId}");
        
        // ConfigureAwait(false) tells it not to capture context
        await Task.Delay(1000).ConfigureAwait(false);
        
        // Can resume on any thread pool thread
        Console.WriteLine($"After await - Thread: {Thread.CurrentThread.ManagedThreadId}");
        
        return "Data without context";
    }
}

// Library code example - SHOULD use ConfigureAwait(false)
public class DataLibrary
{
    private readonly HttpClient httpClient = new HttpClient();
    
    // Good: Library code using ConfigureAwait(false)
    public async Task FetchDataAsync(string url)
    {
        // Library code doesn't need UI context
        var response = await httpClient.GetAsync(url).ConfigureAwait(false);
        
        // Still on thread pool thread (not UI thread)
        var content = await response.Content.ReadAsStringAsync().ConfigureAwait(false);
        
        // Process data without needing UI thread
        var processedData = ProcessData(content);
        
        return processedData;
    }
    
    public async Task<List> FetchMultipleAsync(List urls)
    {
        var results = new List();
        
        foreach (var url in urls)
        {
            // Each await uses ConfigureAwait(false)
            var data = await FetchDataAsync(url).ConfigureAwait(false);
            results.Add(data);
        }
        
        return results;
    }
    
    private string ProcessData(string data)
    {
        // CPU-bound processing
        return data.ToUpper();
    }
}

// UI/Application code example - DON'T use ConfigureAwait(false)
public class UserInterfaceCode
{
    // Bad: Don't use ConfigureAwait(false) in UI code
    public async Task UpdateUIAsync()
    {
        var library = new DataLibrary();
        
        // Get data (library uses ConfigureAwait(false) internally)
        var data = await library.FetchDataAsync("https://api.example.com/data");
        
        // We're back on UI thread here, can update UI safely
        // Don't use ConfigureAwait(false) here!
        UpdateTextBox(data);
    }
    
    private void UpdateTextBox(string text)
    {
        // This needs to run on UI thread
        Console.WriteLine($"Updating UI with: {text}");
    }
}

// Deadlock prevention example
public class DeadlockExample
{
    // This can cause a deadlock in UI apps
    public string GetDataSync()
    {
        // .Result blocks and waits for task
        // But task tries to resume on UI thread which is blocked
        // DEADLOCK!
        return GetDataAsync().Result;
    }
    
    private async Task GetDataAsync()
    {
        await Task.Delay(1000); // Tries to resume on UI thread
        return "Data";
    }
    
    // Fix with ConfigureAwait(false)
    public string GetDataSyncFixed()
    {
        return GetDataAsyncFixed().Result; // Still not ideal, but won't deadlock
    }
    
    private async Task GetDataAsyncFixed()
    {
        await Task.Delay(1000).ConfigureAwait(false); // Won't try to resume on UI thread
        return "Data";
    }
}

// Complete example showing best practices
public class BestPracticesExample
{
    // Library/Service layer - use ConfigureAwait(false)
    public class OrderService
    {
        public async Task GetOrderAsync(int orderId)
        {
            await Task.Delay(100).ConfigureAwait(false);
            
            var order = await FetchFromDatabaseAsync(orderId).ConfigureAwait(false);
            var details = await FetchOrderDetailsAsync(orderId).ConfigureAwait(false);
            
            order.Details = details;
            return order;
        }
        
        private async Task FetchFromDatabaseAsync(int id)
        {
            await Task.Delay(50).ConfigureAwait(false);
            return new Order { Id = id, CustomerName = "John Doe" };
        }
        
        private async Task<List> FetchOrderDetailsAsync(int orderId)
        {
            await Task.Delay(50).ConfigureAwait(false);
            return new List
            {
                new OrderDetail { ProductName = "Widget", Quantity = 2 }
            };
        }
    }
    
    // UI/Controller layer - DON'T use ConfigureAwait(false)
    public class OrderController
    {
        private readonly OrderService orderService = new OrderService();
        
        public async Task DisplayOrderAsync(int orderId)
        {
            // No ConfigureAwait(false) here - we need UI context
            var order = await orderService.GetOrderAsync(orderId);
            
            // Can safely update UI because we're on UI thread
            Console.WriteLine($"Order for: {order.CustomerName}");
            Console.WriteLine($"Items: {order.Details.Count}");
        }
    }
    
    public class Order
    {
        public int Id { get; set; }
        public string CustomerName { get; set; }
        public List Details { get; set; }
    }
    
    public class OrderDetail
    {
        public string ProductName { get; set; }
        public int Quantity { get; set; }
    }
}
```

**Guidelines:**
- **Use `ConfigureAwait(false)`** in:
  - Library/framework code
  - Service layer methods
  - Any code that doesn't need to return to the original context
  
- **DON'T use `ConfigureAwait(false)`** in:
  - UI event handlers
  - ASP.NET Core controllers (post .NET Core 2.0+ - no sync context anyway)
  - Code that needs to update UI elements
  - Top-level application code

---

### What is a deadlock and how can async/await cause it?

A **deadlock** occurs when two or more operations are waiting for each other to complete, causing the application to freeze indefinitely.

**Common async/await deadlock scenario:** Blocking on async code (using `.Result` or `.Wait()`) in a context with a synchronization context (like UI applications).

**Example:**

```csharp
// DEADLOCK EXAMPLES

// Example 1: Classic UI Deadlock
public class UIDeadlockExample
{
    // THIS CAUSES A DEADLOCK IN UI APPLICATIONS
    public void ButtonClick()
    {
        // UI thread blocks here waiting for result
        var result = GetDataAsync().Result;
        
        // Never reaches here - DEADLOCK!
        Console.WriteLine(result);
    }
    
    private async Task GetDataAsync()
    {
        // Simulates async operation (HTTP call, database query, etc.)
        await Task.Delay(1000);
        
        // Tries to resume on UI thread, but UI thread is blocked waiting!
        // DEADLOCK!
        return "Data";
    }
    
    // Explanation:
    // 1. UI thread calls GetDataAsync().Result and blocks
    // 2. GetDataAsync starts and awaits Task.Delay
    // 3. When Task.Delay completes, it tries to resume on UI thread
    // 4. But UI thread is blocked waiting for the result
    // 5. DEADLOCK - each is waiting for the other
}

// Example 2: ASP.NET Deadlock (pre-.NET Core)
public class AspNetDeadlockExample
{
    // THIS CAUSES A DEADLOCK IN ASP.NET (not ASP.NET Core)
    public ActionResult Index()
    {
        // ASP.NET request thread blocks here
        var data = GetDataAsync().Result;
        
        return View(data);
    }
    
    private async Task GetDataAsync()
    {
        await Task.Delay(1000);
        // Tries to resume on ASP.NET synchronization context
        return "Data";
    }
}

// SOLUTIONS TO DEADLOCKS

// Solution 1: Use async all the way (BEST)
public class AsyncAllTheWayExample
{
    // Proper async implementation
    public async Task ButtonClickAsync()
    {
        // Don't block - await instead
        var result = await GetDataAsync();
        Console.WriteLine(result);
    }
    
    private async Task GetDataAsync()
    {
        await Task.Delay(1000);
        return "Data";
    }
}

// Solution 2: Use ConfigureAwait(false) in library code
public class ConfigureAwaitSolution
{
    public void ButtonClick()
    {
        // Still not ideal, but won't deadlock
        var result = GetDataAsync().Result;
        Console.WriteLine(result);
    }
    
    private async Task GetDataAsync()
    {
        // ConfigureAwait(false) prevents capturing sync context
        await Task.Delay(1000).ConfigureAwait(false);
        
        // Won't try to resume on UI thread
        return "Data";
    }
}

// Solution 3: Run on thread pool
public class ThreadPoolSolution
{
    public void ButtonClick()
    {
        // Move work to thread pool
        Task.Run(async () =>
        {
            var result = await GetDataAsync();
            
            // Need to marshal back to UI thread for UI updates
            Application.Current.Dispatcher.Invoke(() =>
            {
                Console.WriteLine(result);
            });
        });
    }
    
    private async Task GetDataAsync()
    {
        await Task.Delay(1000);
        return "Data";
    }
}

// COMPLEX DEADLOCK SCENARIOS

// Scenario 1: Nested async calls
public class NestedDeadlockExample
{
    public void ProcessData()
    {
        // Blocking on first async method
        var result = FirstMethodAsync().Result;
    }
    
    private async Task FirstMethodAsync()
    {
        // This method awaits another async method
        var data = await SecondMethodAsync();
        return data.ToUpper();
    }
    
    private async Task SecondMethodAsync()
    {
        await Task.Delay(1000);
        // Deadlock occurs here trying to resume
        return "data";
    }
}

// Scenario 2: Multiple blocking calls
public class MultipleBlockingExample
{
    public void ProcessMultiple()
    {
        // Each of these can cause a deadlock
        var result1 = GetData1Async().Result;
        var result2 = GetData2Async().Result;
        var result3 = GetData3Async().Result;
    }
    
    private async Task GetData1Async()
    {
        await Task.Delay(100);
        return "Data1";
    }
    
    private async Task GetData2Async()
    {
        await Task.Delay(100);
        return "Data2";
    }
    
    private async Task GetData3Async()
    {
        await Task.Delay(100);
        return "Data3";
    }
}

// CORRECT PATTERNS

// Pattern 1: Async all the way up
public class CorrectAsyncPattern
{
    // Controller/UI method is async
    public async Task ProcessDataAsync()
    {
        var result1 = await GetData1Async();
        var result2 = await GetData2Async();
        var result3 = await GetData3Async();
        
        Console.WriteLine($"{result1}, {result2}, {result3}");
    }
    
    private async Task GetData1Async()
    {
        await Task.Delay(100);
        return "Data1";
    }
    
    private async Task GetData2Async()
    {
        await Task.Delay(100);
        return "Data2";
    }
    
    private async Task GetData3Async()
    {
        await Task.Delay(100);
        return "Data3";
    }
}

// Pattern 2: Library code with ConfigureAwait
public class LibraryCodePattern
{
    public async Task GetUserDataAsync(int userId)
    {
        // All awaits use ConfigureAwait(false)
        var user = await FetchUserAsync(userId).ConfigureAwait(false);
        var orders = await FetchOrdersAsync(userId).ConfigureAwait(false);
        var preferences = await FetchPreferencesAsync(userId).ConfigureAwait(false);
        
        return new UserData
        {
            User = user,
            Orders = orders,
            Preferences = preferences
        };
    }
    
    private async Task FetchUserAsync(int id)
    {
        await Task.Delay(100).ConfigureAwait(false);
        return new User { Id = id, Name = "John" };
    }
    
    private async Task<List> FetchOrdersAsync(int userId)
    {
        await Task.Delay(100).ConfigureAwait(false);
        return new List();
    }
    
    private async Task FetchPreferencesAsync(int userId)
    {
        await Task.Delay(100).ConfigureAwait(false);
        return new Preferences();
    }
    
    public class User { public int Id { get; set; } public string Name { get; set; } }
    public class Order { }
    public class Preferences { }
    public class UserData
    {
        public User User { get; set; }
        public List Orders { get; set; }
        public Preferences Preferences { get; set; }
    }
}

// Detecting deadlocks
public class DeadlockDetection
{
    public void DetectDeadlock()
    {
        try
        {
            // Set a timeout to detect potential deadlock
            var task = GetDataAsync();
            
            if (!task.Wait(TimeSpan.FromSeconds(5)))
            {
                Console.WriteLine("Potential deadlock detected!");
            }
        }
        catch (AggregateException ex)
        {
            Console.WriteLine($"Error: {ex.InnerException?.Message}");
        }
    }
    
    private async Task GetDataAsync()
    {
        await Task.Delay(1000);
        return "Data";
    }
}
```

**Key Takeaways:**
1. **Never block on async code** - Don't use `.Result` or `.Wait()` in UI or ASP.NET contexts
2. **Async all the way** - Make your methods async from top to bottom
3. **Use ConfigureAwait(false)** in library code
4. **ASP.NET Core is safer** - It doesn't have a synchronization context, reducing deadlock risk
5. **Be careful with Task.WaitAll()** - Same issues as `.Result`

---
### Explain the difference between `Task.WhenAll()` and `Task.WhenAny()`

**Task.WhenAll()** waits for all tasks in a collection to complete before continuing. It returns a task that completes when all input tasks have completed.

**Key characteristics of Task.WhenAll():**
- Waits for ALL tasks to finish
- Returns an array of results (if tasks return values)
- If any task throws an exception, the returned task will be faulted
- All exceptions are aggregated in an AggregateException
- Useful for parallel execution where you need all results

```csharp
// Example: Download multiple files concurrently
var task1 = DownloadFileAsync("file1.txt");
var task2 = DownloadFileAsync("file2.txt");
var task3 = DownloadFileAsync("file3.txt");

// Wait for all downloads to complete
await Task.WhenAll(task1, task2, task3);
Console.WriteLine("All files downloaded");
```

**Task.WhenAny()** returns as soon as ANY one of the tasks completes. It returns a task that represents the first completed task.

**Key characteristics of Task.WhenAny():**
- Returns when the FIRST task completes
- Returns the completed task itself (not the result)
- Useful for timeout scenarios or racing multiple operations
- Other tasks continue running in the background

```csharp
// Example: Implement timeout pattern
var dataTask = FetchDataAsync();
var timeoutTask = Task.Delay(TimeSpan.FromSeconds(5));

var completedTask = await Task.WhenAny(dataTask, timeoutTask);

if (completedTask == timeoutTask)
{
    throw new TimeoutException("Operation timed out");
}

var result = await dataTask;
```

---

### What is `ValueTask` and when should you use it over `Task`?

**ValueTask** is a value type (struct) that represents an asynchronous operation, introduced to reduce heap allocations in high-performance scenarios.

**Key differences from Task:**

**Task:**
- Reference type (class) - allocated on the heap
- Can be awaited multiple times
- Can be cached and reused safely
- Slightly more overhead due to allocation

**ValueTask:**
- Value type (struct) - can be allocated on the stack
- Should only be awaited once
- More efficient when the operation completes synchronously
- Less garbage collection pressure

**When to use ValueTask:**

Use ValueTask when:
1. The operation frequently completes synchronously (e.g., cached results)
2. Performance is critical and you want to avoid allocations
3. You're building high-throughput libraries or APIs
4. The result is only awaited once

```csharp
// Good use case: Cache-backed operation
public async ValueTask GetUserAsync(int userId)
{
    // Check cache first - often completes synchronously
    if (_cache.TryGetValue(userId, out var user))
    {
        return user; // No Task allocation needed
    }
    
    // Cache miss - fetch from database
    user = await _database.GetUserAsync(userId);
    _cache.Add(userId, user);
    return user;
}
```

**When to use Task:**

Use Task when:
1. The operation is always asynchronous
2. You need to await the result multiple times
3. You need to store the task for later use
4. Working with public APIs where simplicity matters

```csharp
// Task is better here - result may be awaited multiple times
public Task FetchDataAsync()
{
    return _httpClient.GetStringAsync("https://api.example.com/data");
}
```

**Important rules for ValueTask:**
- Only await a ValueTask once
- Don't store ValueTask in fields or properties
- Convert to Task if you need multiple awaits: `valueTask.AsTask()`

---

### How do you handle exceptions in async methods?

Exception handling in async methods uses try-catch blocks, but with important considerations for how exceptions are propagated.

**Basic exception handling:**

```csharp
public async Task ProcessDataAsync()
{
    try
    {
        var data = await FetchDataAsync();
        await SaveDataAsync(data);
    }
    catch (HttpRequestException ex)
    {
        // Handle network errors
        _logger.LogError(ex, "Network error occurred");
        throw;
    }
    catch (Exception ex)
    {
        // Handle other errors
        _logger.LogError(ex, "Unexpected error");
        throw;
    }
    finally
    {
        // Cleanup code always runs
        _logger.LogInformation("Processing completed");
    }
}
```

**Handling exceptions with Task.WhenAll():**

When using Task.WhenAll(), only the first exception is thrown. To get all exceptions:

```csharp
public async Task ProcessMultipleAsync()
{
    var tasks = new[]
    {
        ProcessItem1Async(),
        ProcessItem2Async(),
        ProcessItem3Async()
    };
    
    try
    {
        await Task.WhenAll(tasks);
    }
    catch (Exception ex)
    {
        // Only first exception is caught here
        _logger.LogError(ex, "At least one task failed");
        
        // To get ALL exceptions:
        foreach (var task in tasks)
        {
            if (task.IsFaulted)
            {
                foreach (var exception in task.Exception.InnerExceptions)
                {
                    _logger.LogError(exception, "Task exception");
                }
            }
        }
    }
}
```

**Fire-and-forget pattern (dangerous but sometimes necessary):**

```csharp
// BAD: Exception will crash the application
public void StartBackgroundWork()
{
    _ = DoWorkAsync(); // Fire and forget - DON'T DO THIS
}

// GOOD: Properly handled fire-and-forget
public void StartBackgroundWork()
{
    _ = SafeFireAndForgetAsync(DoWorkAsync());
}

private async Task SafeFireAndForgetAsync(Task task)
{
    try
    {
        await task;
    }
    catch (Exception ex)
    {
        _logger.LogError(ex, "Background task failed");
    }
}
```

**Exception handling with ConfigureAwait:**

```csharp
public async Task ProcessAsync()
{
    try
    {
        // ConfigureAwait doesn't affect exception handling
        var result = await FetchDataAsync().ConfigureAwait(false);
        await SaveAsync(result).ConfigureAwait(false);
    }
    catch (Exception ex)
    {
        // Exceptions are still caught normally
        _logger.LogError(ex, "Error in processing");
    }
}
```

**Key principles:**
- Always await async methods to catch exceptions
- Use try-catch around await statements
- Log exceptions before rethrowing
- Be aware of AggregateException with Task.WhenAll()
- Never ignore exceptions in fire-and-forget scenarios

---

### What is the difference between synchronous and asynchronous programming?

**Synchronous Programming:**

In synchronous programming, operations execute sequentially. Each operation must complete before the next one begins, blocking the thread until finished.

**Characteristics:**
- Sequential execution
- Thread blocking
- Simple and predictable
- Can lead to poor responsiveness
- Easier to reason about

```csharp
// Synchronous example
public void ProcessData()
{
    var data = FetchData(); // Blocks thread until complete
    var processed = TransformData(data); // Waits for previous line
    SaveData(processed); // Waits for previous line
    
    Console.WriteLine("Done"); // Only executes after everything above
}
```

**Asynchronous Programming:**

In asynchronous programming, operations can run concurrently without blocking the thread. The thread is freed to do other work while waiting for I/O operations.

**Characteristics:**
- Non-blocking execution
- Better resource utilization
- Improved responsiveness
- More complex control flow
- Requires careful exception handling

```csharp
// Asynchronous example
public async Task ProcessDataAsync()
{
    var data = await FetchDataAsync(); // Thread released during I/O
    var processed = await TransformDataAsync(data); // Non-blocking
    await SaveDataAsync(processed); // Non-blocking
    
    Console.WriteLine("Done");
}
```

**Key differences:**

| Aspect | Synchronous | Asynchronous |
|--------|-------------|--------------|
| Thread Blocking | Yes | No |
| Resource Usage | One thread per operation | Threads reused efficiently |
| UI Responsiveness | Can freeze UI | UI remains responsive |
| Complexity | Simple | More complex |
| Best For | CPU-bound operations | I/O-bound operations |
| Scalability | Limited | High |

**When to use each:**

**Use Synchronous when:**
- CPU-bound operations (calculations)
- Simple console applications
- Operations complete quickly
- Code simplicity is paramount

**Use Asynchronous when:**
- I/O operations (database, file, network)
- Web applications (ASP.NET Core)
- UI applications (WPF, WinForms)
- Need to handle many concurrent operations
- Scalability is important

```csharp
// CPU-bound: Synchronous is fine
public int CalculatePrimes(int max)
{
    int count = 0;
    for (int i = 2; i < max; i++)
    {
        if (IsPrime(i)) count++;
    }
    return count;
}

// I/O-bound: Asynchronous is better
public async Task GetWebPageAsync(string url)
{
    using var client = new HttpClient();
    return await client.GetStringAsync(url);
}
```

---

### Explain the concept of the `SynchronizationContext`

**SynchronizationContext** is an abstraction that represents a scheduling context where code can be executed. It determines which thread executes continuation code after an await.

**Purpose:**
- Marshals callbacks to the appropriate thread
- Ensures UI updates happen on the UI thread
- Maintains thread affinity for frameworks that require it

**How it works:**

When you await an async operation:
1. The SynchronizationContext is captured before the await
2. When the operation completes, the continuation is posted back to that context
3. The continuation runs on the correct thread

**Different SynchronizationContext types:**

**1. UI Context (WPF, WinForms):**
```csharp
// In a WPF application
private async void Button_Click(object sender, RoutedEventArgs e)
{
    // Running on UI thread - SynchronizationContext captured
    var data = await FetchDataAsync();
    
    // Automatically back on UI thread - can update UI safely
    TextBlock.Text = data; // Safe - on UI thread
}
```

**2. ASP.NET Context (ASP.NET Framework, not Core):**
```csharp
// In ASP.NET Framework
public async Task Index()
{
    // HttpContext available
    var userId = HttpContext.User.Identity.Name;
    
    var data = await GetDataAsync();
    
    // Still in same request context
    return View(data);
}
```

**3. No Context (Console apps, ASP.NET Core):**
```csharp
// Console application or ASP.NET Core
public async Task ProcessAsync()
{
    // No specific context
    var data = await FetchDataAsync();
    
    // May continue on any thread pool thread
    Console.WriteLine(data);
}
```

**ConfigureAwait and SynchronizationContext:**

ConfigureAwait(false) tells the runtime NOT to capture and restore the SynchronizationContext:

```csharp
// Library code - don't need to return to original context
public async Task GetDataAsync()
{
    // Don't capture context - better performance
    var response = await _httpClient.GetAsync(url).ConfigureAwait(false);
    var content = await response.Content.ReadAsStringAsync().ConfigureAwait(false);
    
    return ParseData(content); // May run on any thread
}

// UI code - need to return to UI thread
private async void Button_Click(object sender, EventArgs e)
{
    var data = await GetDataAsync(); // Uses ConfigureAwait(false) internally
    
    // This continuation DOES capture context
    // Back on UI thread to update UI
    label.Text = data.ToString();
}
```

**Best practices:**

1. **Use ConfigureAwait(false) in library code:**
```csharp
// Library method
public async Task CalculateAsync()
{
    await Task.Delay(100).ConfigureAwait(false);
    return 42;
}
```

2. **Don't use ConfigureAwait(false) in UI code:**
```csharp
// UI code
private async void LoadData()
{
    var data = await FetchDataAsync(); // Keep default behavior
    textBox.Text = data; // Must be on UI thread
}
```

3. **ASP.NET Core has no SynchronizationContext:**
```csharp
// ASP.NET Core - ConfigureAwait has no effect
public async Task Index()
{
    // No context to capture
    var data = await GetDataAsync();
    return View(data);
}
```

**Key points:**
- SynchronizationContext ensures continuations run on the correct thread
- UI applications have a SynchronizationContext (UI thread)
- ASP.NET Core and console apps typically don't
- Use ConfigureAwait(false) to avoid capturing context when not needed
- Improves performance by avoiding unnecessary thread switches

---

### What are the best practices for cancellation in async operations using `CancellationToken`?

**CancellationToken** provides a cooperative cancellation mechanism for async operations. Here are the best practices:

**1. Always accept CancellationToken parameters:**

```csharp
// Good: Accepts cancellation token
public async Task FetchDataAsync(CancellationToken cancellationToken = default)
{
    return await _httpClient.GetFromJsonAsync(url, cancellationToken);
}

// Bad: No way to cancel
public async Task FetchDataAsync()
{
    return await _httpClient.GetFromJsonAsync(url);
}
```

**2. Pass tokens through the call chain:**

```csharp
public async Task ProcessOrderAsync(Order order, CancellationToken cancellationToken)
{
    // Pass token to all async calls
    await ValidateOrderAsync(order, cancellationToken);
    await SaveOrderAsync(order, cancellationToken);
    await SendConfirmationAsync(order, cancellationToken);
}

private async Task ValidateOrderAsync(Order order, CancellationToken cancellationToken)
{
    await _validator.ValidateAsync(order, cancellationToken);
}
```

**3. Check for cancellation in long-running operations:**

```csharp
public async Task ProcessItemsAsync(List items, CancellationToken cancellationToken)
{
    foreach (var item in items)
    {
        // Check before each iteration
        cancellationToken.ThrowIfCancellationRequested();
        
        await ProcessItemAsync(item, cancellationToken);
    }
}
```

**4. Use timeout with CancellationTokenSource:**

```csharp
public async Task FetchWithTimeoutAsync()
{
    using var cts = new CancellationTokenSource(TimeSpan.FromSeconds(30));
    
    try
    {
        return await FetchDataAsync(cts.Token);
    }
    catch (OperationCanceledException)
    {
        throw new TimeoutException("Operation timed out after 30 seconds");
    }
}
```

**5. Link multiple cancellation tokens:**

```csharp
public async Task ProcessAsync(CancellationToken userToken)
{
    using var timeoutCts = new CancellationTokenSource(TimeSpan.FromMinutes(5));
    using var linkedCts = CancellationTokenSource.CreateLinkedTokenSource(
        userToken, 
        timeoutCts.Token
    );
    
    // Cancelled if either user cancels OR timeout occurs
    await LongRunningOperationAsync(linkedCts.Token);
}
```

**6. Handle OperationCanceledException appropriately:**

```csharp
public async Task TryProcessAsync(CancellationToken cancellationToken)
{
    try
    {
        var data = await FetchDataAsync(cancellationToken);
        return Result.Success(data);
    }
    catch (OperationCanceledException)
    {
        // Expected when cancelled - don't log as error
        _logger.LogInformation("Operation was cancelled");
        return Result.Cancelled();
    }
    catch (Exception ex)
    {
        // Unexpected exception - log as error
        _logger.LogError(ex, "Operation failed");
        return Result.Failed(ex.Message);
    }
}
```

**7. Register cleanup actions:**

```csharp
public async Task ProcessWithCleanupAsync(CancellationToken cancellationToken)
{
    var resource = await AcquireResourceAsync();
    
    // Register cleanup when cancelled
    using var registration = cancellationToken.Register(() =>
    {
        _logger.LogInformation("Cancellation requested - cleaning up");
        resource.Dispose();
    });
    
    try
    {
        await ProcessResourceAsync(resource, cancellationToken);
    }
    finally
    {
        resource.Dispose();
    }
}
```

**8. Use CancellationToken in ASP.NET Core:**

```csharp
[HttpGet]
public async Task GetData(CancellationToken cancellationToken)
{
    // Automatically cancelled if client disconnects
    var data = await _service.FetchDataAsync(cancellationToken);
    return Ok(data);
}
```

**9. Provide meaningful default values:**

```csharp
// Use default parameter for optional cancellation
public async Task LoadDataAsync(CancellationToken cancellationToken = default)
{
    // Works with or without cancellation token
    await Task.Delay(1000, cancellationToken);
    return new Data();
}
```

**10. Don't swallow OperationCanceledException unnecessarily:**

```csharp
// Bad: Hides cancellation
public async Task ProcessAsync(CancellationToken cancellationToken)
{
    try
    {
        await DoWorkAsync(cancellationToken);
    }
    catch (Exception ex) // Catches OperationCanceledException too
    {
        _logger.LogError(ex, "Error");
        // Cancellation is hidden
    }
}

// Good: Let OperationCanceledException propagate
public async Task ProcessAsync(CancellationToken cancellationToken)
{
    try
    {
        await DoWorkAsync(cancellationToken);
    }
    catch (OperationCanceledException)
    {
        // Let it propagate or handle specifically
        throw;
    }
    catch (Exception ex)
    {
        _logger.LogError(ex, "Error");
        throw;
    }
}
```

**Complete example:**

```csharp
public class DataService
{
    private readonly HttpClient _httpClient;
    private readonly ILogger _logger;
    
    public async Task ProcessDataAsync(
        string url, 
        CancellationToken cancellationToken = default)
    {
        // Add timeout protection
        using var cts = CancellationTokenSource.CreateLinkedTokenSource(cancellationToken);
        cts.CancelAfter(TimeSpan.FromMinutes(5));
        
        try
        {
            // Pass token through call chain
            var data = await FetchDataAsync(url, cts.Token);
            var processed = await TransformDataAsync(data, cts.Token);
            await SaveDataAsync(processed, cts.Token);
            
            return ProcessingResult.Success();
        }
        catch (OperationCanceledException)
        {
            _logger.LogInformation("Processing cancelled");
            return ProcessingResult.Cancelled();
        }
        catch (Exception ex)
        {
            _logger.LogError(ex, "Processing failed");
            return ProcessingResult.Failed(ex.Message);
        }
    }
    
    private async Task FetchDataAsync(string url, CancellationToken cancellationToken)
    {
        return await _httpClient.GetFromJsonAsync(url, cancellationToken);
    }
}
```

---

### How would you implement parallel processing in .NET?

.NET provides several approaches for parallel processing depending on your scenario:

**1. Parallel.ForEach (CPU-bound operations):**

Best for CPU-intensive operations on collections:

```csharp
public void ProcessLargeDataset(List items)
{
    Parallel.ForEach(items, new ParallelOptions
    {
        MaxDegreeOfParallelism = Environment.ProcessorCount
    },
    item =>
    {
        // CPU-intensive work
        var result = PerformComplexCalculation(item);
        SaveResult(result);
    });
}
```

**2. Parallel.For (indexed iterations):**

```csharp
public void ProcessArray(int[] numbers)
{
    Parallel.For(0, numbers.Length, i =>
    {
        // Process each element
        numbers[i] = ComplexCalculation(numbers[i]);
    });
}
```

**3. PLINQ (Parallel LINQ):**

For declarative parallel queries:

```csharp
public List ProcessWithPLINQ(List items)
{
    var results = items
        .AsParallel()
        .WithDegreeOfParallelism(8)
        .Where(item => item.IsValid)
        .Select(item => ProcessItem(item))
        .ToList();
    
    return results;
}

// With ordering preserved
public List ProcessOrdered(List items)
{
    var results = items
        .AsParallel()
        .AsOrdered() // Maintain original order
        .Select(item => ProcessItem(item))
        .ToList();
    
    return results;
}
```

**4. Task.WhenAll (I/O-bound operations):**

Best for concurrent I/O operations:

```csharp
public async Task<List> ProcessConcurrentlyAsync(List urls)
{
    // Create all tasks
    var tasks = urls.Select(url => FetchDataAsync(url)).ToList();
    
    // Wait for all to complete
    var results = await Task.WhenAll(tasks);
    
    return results.ToList();
}
```

**5. Parallel processing with cancellation:**

```csharp
public void ProcessWithCancellation(
    List items, 
    CancellationToken cancellationToken)
{
    var options = new ParallelOptions
    {
        CancellationToken = cancellationToken,
        MaxDegreeOfParallelism = Environment.ProcessorCount
    };
    
    try
    {
        Parallel.ForEach(items, options, item =>
        {
            cancellationToken.ThrowIfCancellationRequested();
            ProcessItem(item);
        });
    }
    catch (OperationCanceledException)
    {
        Console.WriteLine("Processing cancelled");
    }
}
```

**6. Partitioning for better load balancing:**

```csharp
public void ProcessWithPartitioning(List items)
{
    var partitioner = Partitioner.Create(items, loadBalance: true);
    
    Parallel.ForEach(partitioner, item =>
    {
        ProcessItem(item);
    });
}
```

**7. Thread-safe result collection:**

```csharp
public List ProcessAndCollectResults(List items)
{
    var results = new ConcurrentBag();
    
    Parallel.ForEach(items, item =>
    {
        var result = ProcessItem(item);
        results.Add(result); // Thread-safe
    });
    
    return results.ToList();
}
```

**8. Async parallel processing with throttling:**

```csharp
public async Task<List> ProcessWithThrottlingAsync(
    List urls, 
    int maxConcurrency)
{
    var semaphore = new SemaphoreSlim(maxConcurrency);
    var tasks = new List<Task>();
    
    foreach (var url in urls)
    {
        await semaphore.WaitAsync();
        
        var task = Task.Run(async () =>
        {
            try
            {
                return await FetchDataAsync(url);
            }
            finally
            {
                semaphore.Release();
            }
        });
        
        tasks.Add(task);
    }
    
    var results = await Task.WhenAll(tasks);
    return results.ToList();
}
```

**9. Producer-Consumer pattern with BlockingCollection:**

```csharp
public void ProcessWithProducerConsumer(IEnumerable items)
{
    var queue = new BlockingCollection(boundedCapacity: 100);
    
    // Producer task
    var producer = Task.Run(() =>
    {
        foreach (var item in items)
        {
            queue.Add(item);
        }
        queue.CompleteAdding();
    });
    
    // Consumer tasks
    var consumers = Enumerable.Range(0, Environment.ProcessorCount)
        .Select(_ => Task.Run(() =>
        {
            foreach (var item in queue.GetConsumingEnumerable())
            {
                ProcessItem(item);
            }
        }))
        .ToArray();
    
    Task.WaitAll(consumers);
}
```

**10. Dataflow (TPL Dataflow) for complex pipelines:**

```csharp
using System.Threading.Tasks.Dataflow;

public async Task ProcessPipelineAsync(List items)
{
    var downloadBlock = new TransformBlock(
        async item => await DownloadAsync(item),
        new ExecutionDataflowBlockOptions 
        { 
            MaxDegreeOfParallelism = 10 
        });
    
    var processBlock = new TransformBlock(
        data => ProcessData(data),
        new ExecutionDataflowBlockOptions 
        { 
            MaxDegreeOfParallelism = Environment.ProcessorCount 
        });
    
    var saveBlock = new ActionBlock(
        async data => await SaveAsync(data),
        new ExecutionDataflowBlockOptions 
        { 
            MaxDegreeOfParallelism = 5 
        });
    
    // Link the pipeline
    downloadBlock.LinkTo(processBlock, new DataflowLinkOptions { PropagateCompletion = true });
    processBlock.LinkTo(saveBlock, new DataflowLinkOptions { PropagateCompletion = true });
    
    // Post items
    foreach (var item in items)
    {
        await downloadBlock.SendAsync(item);
    }
    
    downloadBlock.Complete();
    await saveBlock.Completion;
}
```

**Best practices:**

1. **Choose the right approach:**
   - CPU-bound: Parallel.ForEach, PLINQ
   - I/O-bound: Task.WhenAll, async/await
   - Complex pipelines: TPL Dataflow

2. **Control degree of parallelism:**
   ```csharp
   var options = new ParallelOptions 
   { 
       MaxDegreeOfParallelism = Environment.ProcessorCount 
   };
   ```

3. **Handle exceptions properly:**
   ```csharp
   try
   {
       Parallel.ForEach(items, item => ProcessItem(item));
   }
   catch (AggregateException ae)
   {
       foreach (var ex in ae.InnerExceptions)
       {
           _logger.LogError(ex, "Processing failed");
       }
   }
   ```

4. **Use thread-safe collections:**
   - ConcurrentBag, ConcurrentQueue, ConcurrentDictionary

5. **Avoid over-parallelization:**
   - Too many threads can degrade performance
   - Measure and optimize based on actual workload
---

## ASP.NET Core

### Explain the middleware pipeline in ASP.NET Core

The middleware pipeline in ASP.NET Core is a series of components that handle HTTP requests and responses. Each middleware component can:

- Process an incoming request before passing it to the next component
- Process the outgoing response after the next component has executed
- Short-circuit the pipeline by not calling the next middleware

**Key characteristics:**

- Middleware components are executed in the order they are added
- Each component can perform operations before and after the next component
- Built using the `Use`, `Run`, and `Map` extension methods

**Example:**

```csharp
public void Configure(IApplicationBuilder app)
{
    // Middleware 1
    app.Use(async (context, next) =>
    {
        // Do work before next middleware
        await next.Invoke();
        // Do work after next middleware
    });

    // Middleware 2
    app.UseRouting();
    app.UseAuthentication();
    app.UseAuthorization();
    
    // Terminal middleware
    app.UseEndpoints(endpoints =>
    {
        endpoints.MapControllers();
    });
}
```

**Common middleware order:**
1. Exception handling
2. HTTPS redirection
3. Static files
4. Routing
5. Authentication
6. Authorization
7. Endpoints

### What is the difference between ASP.NET and ASP.NET Core?

| Feature | ASP.NET | ASP.NET Core |
|---------|---------|--------------|
| **Platform** | Windows only | Cross-platform (Windows, Linux, macOS) |
| **Framework** | Built on .NET Framework | Built on .NET Core/.NET 5+ |
| **Performance** | Good | Significantly faster and more efficient |
| **Hosting** | IIS only | IIS, Kestrel, Nginx, Apache, Docker |
| **Open Source** | Partially | Fully open source |
| **Configuration** | Web.config (XML) | appsettings.json, environment variables |
| **Dependency Injection** | Not built-in (needs third-party) | Built-in DI container |
| **Web Forms** | Supported | Not supported |
| **Project Structure** | Complex, tightly coupled | Modular, lightweight |
| **Side-by-side deployment** | Not supported | Supported |
| **Cloud optimization** | Limited | Highly optimized for cloud |

**Key advantages of ASP.NET Core:**
- Better performance and scalability
- Modern architecture with cleaner separation of concerns
- Built-in dependency injection
- Unified programming model for web UI and web APIs
- Can run on multiple platforms

### Explain dependency injection in ASP.NET Core (Transient, Scoped, Singleton)

Dependency Injection (DI) is a built-in design pattern in ASP.NET Core that achieves Inversion of Control (IoC) between classes and their dependencies. Services are registered with specific lifetimes.

**Service Lifetimes:**

#### Transient
- A new instance is created every time the service is requested
- Best for lightweight, stateless services
- Registered using `AddTransient<TService, TImplementation>()`

```csharp
services.AddTransient();
```

**Use case:** Operations that don't maintain state, like sending emails or generating random numbers.

#### Scoped
- A single instance is created per client request (HTTP request)
- The same instance is used throughout the entire request
- Registered using `AddScoped<TService, TImplementation>()`

```csharp
services.AddScoped();
```

**Use case:** Database contexts (Entity Framework), repository patterns, services that need to maintain state during a request.

#### Singleton
- A single instance is created for the entire application lifetime
- The same instance is shared across all requests
- Registered using `AddSingleton<TService, TImplementation>()`

```csharp
services.AddSingleton();
```

**Use case:** Configuration, logging, caching services, thread-safe services.

**Registration example in Program.cs:**

```csharp
var builder = WebApplication.CreateBuilder(args);

// Transient
builder.Services.AddTransient();

// Scoped
builder.Services.AddScoped();

// Singleton
builder.Services.AddSingleton(builder.Configuration);

var app = builder.Build();
```

**Important considerations:**
- Avoid injecting scoped or transient services into singleton services (causes memory leaks)
- Singleton services must be thread-safe
- Scoped is the most commonly used lifetime for business logic

### What are action filters and how do you create custom filters?

Action filters are attributes that add extra processing logic before or after specific stages in the request processing pipeline. They allow cross-cutting concerns like logging, caching, authorization, and exception handling.

**Filter types and execution order:**

1. **Authorization filters** - Run first, verify authorization
2. **Resource filters** - Run after authorization, good for caching
3. **Action filters** - Run before and after action method execution
4. **Exception filters** - Handle exceptions
5. **Result filters** - Run before and after result execution

**Creating a custom action filter:**

```csharp
// Method 1: Inherit from ActionFilterAttribute
public class LogActivityFilter : ActionFilterAttribute
{
    private readonly ILogger _logger;

    public LogActivityFilter(ILogger logger)
    {
        _logger = logger;
    }

    public override void OnActionExecuting(ActionExecutingContext context)
    {
        _logger.LogInformation($"Executing action: {context.ActionDescriptor.DisplayName}");
        base.OnActionExecuting(context);
    }

    public override void OnActionExecuted(ActionExecutedContext context)
    {
        _logger.LogInformation($"Executed action: {context.ActionDescriptor.DisplayName}");
        base.OnActionExecuted(context);
    }
}

// Method 2: Implement IActionFilter interface
public class ValidateModelFilter : IActionFilter
{
    public void OnActionExecuting(ActionExecutingContext context)
    {
        if (!context.ModelState.IsValid)
        {
            context.Result = new BadRequestObjectResult(context.ModelState);
        }
    }

    public void OnActionExecuted(ActionExecutedContext context)
    {
        // Logic after action execution
    }
}

// Async version
public class AsyncLoggingFilter : IAsyncActionFilter
{
    public async Task OnActionExecutionAsync(
        ActionExecutingContext context, 
        ActionExecutionDelegate next)
    {
        // Before action execution
        await next(); // Execute the action
        // After action execution
    }
}
```

**Using filters:**

```csharp
// Apply to specific action
[LogActivityFilter]
public IActionResult GetUser(int id)
{
    return Ok();
}

// Apply to controller
[ValidateModelFilter]
public class UsersController : ControllerBase
{
}

// Register globally in Program.cs
builder.Services.AddControllers(options =>
{
    options.Filters.Add();
});
```

### Explain the difference between `IActionResult`, `ActionResult<T>`, and returning a concrete type

These are different return types for controller actions in ASP.NET Core, each with specific use cases.

#### IActionResult

- Non-generic interface
- Can return any type of action result
- No compile-time type safety for the return value
- Requires runtime type checking

```csharp
[HttpGet("{id}")]
public IActionResult GetUser(int id)
{
    var user = _userService.GetUser(id);
    
    if (user == null)
        return NotFound(); // Returns 404
    
    return Ok(user); // Returns 200 with user object
}
```

**Pros:** Flexible, can return different result types
**Cons:** No automatic OpenAPI/Swagger documentation for response type

#### ActionResult<T>

- Generic wrapper combining IActionResult flexibility with type safety
- Best of both worlds approach
- Enables automatic API documentation
- Implicit conversion from T or ActionResult

```csharp
[HttpGet("{id}")]
public ActionResult GetUser(int id)
{
    var user = _userService.GetUser(id);
    
    if (user == null)
        return NotFound(); // Returns ActionResult
    
    return user; // Implicitly converted to ActionResult
}
```

**Pros:** 
- Type safety
- Automatic OpenAPI/Swagger documentation
- Can still return status codes like NotFound(), BadRequest()

**Cons:** Can only specify one success return type

#### Concrete Type

- Returns the actual object type directly
- Simplest approach
- Always returns 200 OK status
- Cannot return different status codes

```csharp
[HttpGet]
public List GetAllUsers()
{
    return _userService.GetAllUsers();
}

[HttpGet("{id}")]
public User GetUser(int id)
{
    return _userService.GetUser(id); // Always 200 OK
}
```

**Pros:** Simple, clean code for straightforward scenarios
**Cons:** 
- Cannot return different HTTP status codes
- No error handling at the action level
- Limited flexibility

**Comparison table:**

| Feature | IActionResult | ActionResult<T> | Concrete Type |
|---------|---------------|-----------------|---------------|
| Multiple return types | ✅ Yes | ✅ Yes | ❌ No |
| Type safety | ❌ No | ✅ Yes | ✅ Yes |
| OpenAPI documentation | ⚠️ Manual | ✅ Automatic | ✅ Automatic |
| HTTP status control | ✅ Full | ✅ Full | ❌ Always 200 |
| Recommended for APIs | ⚠️ Legacy | ✅ Best choice | ❌ Limited use |

**Best practice:** Use `ActionResult<T>` for modern ASP.NET Core Web APIs as it provides the best balance of flexibility and type safety.

### What is model binding and validation in ASP.NET Core?

Model binding is the process of mapping HTTP request data to action method parameters. Validation ensures that the bound data meets specified constraints before processing.

#### Model Binding

Model binding automatically extracts values from:
- **Form data** - POST form submissions
- **Route values** - URL segments like `/users/{id}`
- **Query strings** - URL parameters like `?name=John&age=30`
- **Request body** - JSON, XML payloads
- **Headers** - HTTP headers

**Binding sources:**

```csharp
public class UsersController : ControllerBase
{
    // From route
    [HttpGet("{id}")]
    public IActionResult GetUser([FromRoute] int id) { }

    // From query string
    [HttpGet]
    public IActionResult Search([FromQuery] string name, [FromQuery] int? age) { }

    // From body (JSON)
    [HttpPost]
    public IActionResult Create([FromBody] UserDto user) { }

    // From form
    [HttpPost]
    public IActionResult Upload([FromForm] IFormFile file) { }

    // From header
    [HttpGet]
    public IActionResult Get([FromHeader(Name = "X-API-Key")] string apiKey) { }
}
```

#### Model Validation

Validation uses data annotations to define rules. ASP.NET Core automatically validates models before action execution.

**Common validation attributes:**

```csharp
public class UserDto
{
    [Required(ErrorMessage = "Name is required")]
    [StringLength(100, MinimumLength = 2)]
    public string Name { get; set; }

    [Required]
    [EmailAddress(ErrorMessage = "Invalid email format")]
    public string Email { get; set; }

    [Range(18, 120, ErrorMessage = "Age must be between 18 and 120")]
    public int Age { get; set; }

    [Phone]
    public string PhoneNumber { get; set; }

    [Url]
    public string Website { get; set; }

    [RegularExpression(@"^[A-Z]{2}\d{6}$", ErrorMessage = "Invalid format")]
    public string Code { get; set; }

    [Compare("Email", ErrorMessage = "Emails must match")]
    public string ConfirmEmail { get; set; }

    [CreditCard]
    public string CardNumber { get; set; }
}
```

**Checking validation in controller:**

```csharp
[HttpPost]
public IActionResult CreateUser([FromBody] UserDto user)
{
    if (!ModelState.IsValid)
    {
        return BadRequest(ModelState);
    }

    // Process valid model
    return Ok();
}
```

**Custom validation attribute:**

```csharp
public class FutureDateAttribute : ValidationAttribute
{
    protected override ValidationResult IsValid(
        object value, 
        ValidationContext validationContext)
    {
        if (value is DateTime date)
        {
            if (date > DateTime.Now)
            {
                return ValidationResult.Success;
            }
            return new ValidationResult("Date must be in the future");
        }
        return new ValidationResult("Invalid date");
    }
}

// Usage
public class EventDto
{
    [FutureDate]
    public DateTime EventDate { get; set; }
}
```

**Fluent validation (alternative approach):**

```csharp
// Install: FluentValidation.AspNetCore
public class UserDtoValidator : AbstractValidator
{
    public UserDtoValidator()
    {
        RuleFor(x => x.Name)
            .NotEmpty()
            .Length(2, 100);

        RuleFor(x => x.Email)
            .NotEmpty()
            .EmailAddress();

        RuleFor(x => x.Age)
            .InclusiveBetween(18, 120);
    }
}
```

**Automatic validation with API behavior:**

```csharp
// In Program.cs - ASP.NET Core 2.1+ automatically returns 400 for invalid models
builder.Services.AddControllers()
    .ConfigureApiBehaviorOptions(options =>
    {
        options.SuppressModelStateInvalidFilter = false; // Default
    });
```

**Key points:**
- Model binding happens automatically based on parameter names and types
- Validation attributes are checked before the action executes
- `ModelState.IsValid` contains validation results
- For APIs, ASP.NET Core automatically returns 400 Bad Request for invalid models
- Custom validation can be created via attributes or FluentValidation library

---
### How do you implement authentication and authorization in ASP.NET Core?

Authentication and authorization in ASP.NET Core are implemented through middleware and services:

**Step 1: Install Required Packages**
```bash
dotnet add package Microsoft.AspNetCore.Authentication.JwtBearer
dotnet add package Microsoft.AspNetCore.Identity.EntityFrameworkCore
```

**Step 2: Configure Services in Program.cs**
```csharp
builder.Services.AddAuthentication(options =>
{
    options.DefaultAuthenticateScheme = JwtBearerDefaults.AuthenticationScheme;
    options.DefaultChallengeScheme = JwtBearerDefaults.AuthenticationScheme;
})
.AddJwtBearer(options =>
{
    options.TokenValidationParameters = new TokenValidationParameters
    {
        ValidateIssuer = true,
        ValidateAudience = true,
        ValidateLifetime = true,
        ValidateIssuerSigningKey = true,
        ValidIssuer = builder.Configuration["Jwt:Issuer"],
        ValidAudience = builder.Configuration["Jwt:Audience"],
        IssuerSigningKey = new SymmetricSecurityKey(
            Encoding.UTF8.GetBytes(builder.Configuration["Jwt:Key"]))
    };
});

builder.Services.AddAuthorization(options =>
{
    options.AddPolicy("AdminOnly", policy => policy.RequireRole("Admin"));
    options.AddPolicy("MinimumAge", policy => policy.Requirements.Add(new MinimumAgeRequirement(18)));
});
```

**Step 3: Add Middleware**
```csharp
app.UseAuthentication();
app.UseAuthorization();
```

**Step 4: Protect Endpoints**
```csharp
[Authorize]
[ApiController]
[Route("api/[controller]")]
public class SecureController : ControllerBase
{
    [Authorize(Roles = "Admin")]
    public IActionResult AdminOnly() => Ok("Admin access");
    
    [Authorize(Policy = "MinimumAge")]
    public IActionResult AgeRestricted() => Ok("Age verified");
}
```

### Explain the difference between authentication and authorization.

**Authentication** is the process of verifying WHO the user is (identity verification).
- Confirms user identity through credentials (username/password, tokens, biometrics)
- Answers: "Are you who you claim to be?"
- Example: Logging in with username and password

**Authorization** is the process of verifying WHAT the user can access (permission verification).
- Determines what resources/actions an authenticated user can access
- Answers: "What are you allowed to do?"
- Example: Checking if a user has admin rights to delete records

**Key Differences:**
- Authentication comes before authorization
- Authentication verifies identity; authorization verifies permissions
- Authentication uses credentials; authorization uses roles, policies, and claims
- You can be authenticated but not authorized for specific resources

**Example Flow:**
```
User Login → Authentication (verify credentials) → User Authenticated
   ↓
Access Admin Panel → Authorization (check role) → Access Granted/Denied
```

### What is JWT and how do you implement JWT authentication?

**JWT (JSON Web Token)** is a compact, URL-safe token format for securely transmitting information between parties as a JSON object. It consists of three parts: Header, Payload, and Signature.

**JWT Structure:**
```
xxxxx.yyyyy.zzzzz
Header.Payload.Signature
```

**Implementation:**

**Step 1: Create JWT Token Generation Service**
```csharp
public class JwtTokenService
{
    private readonly IConfiguration _configuration;

    public JwtTokenService(IConfiguration configuration)
    {
        _configuration = configuration;
    }

    public string GenerateToken(string userId, string email, List roles)
    {
        var securityKey = new SymmetricSecurityKey(
            Encoding.UTF8.GetBytes(_configuration["Jwt:Key"]));
        var credentials = new SigningCredentials(securityKey, SecurityAlgorithms.HmacSha256);

        var claims = new List
        {
            new Claim(JwtRegisteredClaimNames.Sub, userId),
            new Claim(JwtRegisteredClaimNames.Email, email),
            new Claim(JwtRegisteredClaimNames.Jti, Guid.NewGuid().ToString())
        };

        claims.AddRange(roles.Select(role => new Claim(ClaimTypes.Role, role)));

        var token = new JwtSecurityToken(
            issuer: _configuration["Jwt:Issuer"],
            audience: _configuration["Jwt:Audience"],
            claims: claims,
            expires: DateTime.Now.AddHours(1),
            signingCredentials: credentials
        );

        return new JwtSecurityTokenHandler().WriteToken(token);
    }
}
```

**Step 2: Login Endpoint**
```csharp
[HttpPost("login")]
public IActionResult Login([FromBody] LoginModel model)
{
    // Validate credentials (simplified)
    if (ValidateUser(model.Username, model.Password))
    {
        var token = _jwtTokenService.GenerateToken(
            userId: "123",
            email: model.Username,
            roles: new List { "User", "Admin" }
        );

        return Ok(new { token });
    }

    return Unauthorized();
}
```

**Step 3: appsettings.json Configuration**
```json
{
  "Jwt": {
    "Key": "YourSuperSecretKeyThatIsAtLeast32CharactersLong",
    "Issuer": "YourApp",
    "Audience": "YourAppUsers"
  }
}
```

### How do you handle CORS in ASP.NET Core?

**CORS (Cross-Origin Resource Sharing)** allows you to control which domains can access your API.

**Method 1: Named Policy (Recommended)**
```csharp
// Program.cs
builder.Services.AddCors(options =>
{
    options.AddPolicy("AllowSpecificOrigin", policy =>
    {
        policy.WithOrigins("https://example.com", "https://app.example.com")
              .AllowAnyHeader()
              .AllowAnyMethod()
              .AllowCredentials();
    });

    options.AddPolicy("AllowAll", policy =>
    {
        policy.AllowAnyOrigin()
              .AllowAnyHeader()
              .AllowAnyMethod();
    });
});

// Must be called before UseAuthorization
app.UseCors("AllowSpecificOrigin");
```

**Method 2: Apply to Specific Controllers**
```csharp
[EnableCors("AllowSpecificOrigin")]
[ApiController]
[Route("api/[controller]")]
public class ProductsController : ControllerBase
{
    [HttpGet]
    public IActionResult Get() => Ok("Products");
    
    [DisableCors] // Disable CORS for specific action
    [HttpPost]
    public IActionResult Post() => Ok();
}
```

**Method 3: Apply to Specific Actions**
```csharp
[HttpGet]
[EnableCors("AllowAll")]
public IActionResult GetPublicData() => Ok("Public data");
```

**Common CORS Configurations:**
```csharp
// Development - Allow all
policy.AllowAnyOrigin()
      .AllowAnyHeader()
      .AllowAnyMethod();

// Production - Specific origins with credentials
policy.WithOrigins("https://myapp.com")
      .AllowAnyHeader()
      .AllowAnyMethod()
      .AllowCredentials();

// Specific methods and headers
policy.WithOrigins("https://myapp.com")
      .WithMethods("GET", "POST")
      .WithHeaders("Content-Type", "Authorization");
```

### What are the different ways to manage application configuration?

ASP.NET Core provides multiple ways to manage configuration:

**1. appsettings.json (Most Common)**
```json
{
  "Logging": {
    "LogLevel": {
      "Default": "Information"
    }
  },
  "ConnectionStrings": {
    "DefaultConnection": "Server=.;Database=MyDb;Trusted_Connection=true;"
  },
  "AppSettings": {
    "ApplicationName": "MyApp",
    "MaxFileSize": 10485760
  }
}
```

**2. Environment-Specific Configuration**
```
appsettings.json (base configuration)
appsettings.Development.json (development overrides)
appsettings.Production.json (production overrides)
```

**3. User Secrets (Development Only)**
```bash
dotnet user-secrets init
dotnet user-secrets set "ApiKey" "secret-key-value"
```

**4. Environment Variables**
```csharp
// Access in code
var apiKey = builder.Configuration["ApiKey"];

// Set in launchSettings.json
"environmentVariables": {
    "ASPNETCORE_ENVIRONMENT": "Development",
    "ApiKey": "dev-key"
}
```

**5. Command Line Arguments**
```bash
dotnet run --ApiKey="command-line-key"
```

**6. Azure Key Vault**
```csharp
builder.Configuration.AddAzureKeyVault(
    new Uri("https://myvault.vault.azure.net/"),
    new DefaultAzureCredential());
```

**7. Options Pattern (Strongly Typed)**
```csharp
// Settings class
public class AppSettings
{
    public string ApplicationName { get; set; }
    public int MaxFileSize { get; set; }
}

// Register
builder.Services.Configure(
    builder.Configuration.GetSection("AppSettings"));

// Use in controller
public class HomeController : Controller
{
    private readonly AppSettings _settings;

    public HomeController(IOptions settings)
    {
        _settings = settings.Value;
    }
}
```

**Configuration Priority (Highest to Lowest):**
1. Command-line arguments
2. Environment variables
3. User secrets
4. appsettings.{Environment}.json
5. appsettings.json

### Explain routing in ASP.NET Core (conventional vs attribute routing).

**Conventional Routing** defines routes in a central location using patterns.

```csharp
// Program.cs
app.MapControllerRoute(
    name: "default",
    pattern: "{controller=Home}/{action=Index}/{id?}");

app.MapControllerRoute(
    name: "blog",
    pattern: "blog/{year}/{month}/{day}/{slug}",
    defaults: new { controller = "Blog", action = "Post" });
```

**Controller using Conventional Routing:**
```csharp
public class HomeController : Controller
{
    // Matches: /Home/Index
    public IActionResult Index() => View();

    // Matches: /Home/About
    public IActionResult About() => View();
    
    // Matches: /Home/Details/5
    public IActionResult Details(int id) => View();
}
```

**Attribute Routing** defines routes directly on controllers and actions using attributes.

```csharp
[Route("api/[controller]")]
[ApiController]
public class ProductsController : ControllerBase
{
    // GET: api/products
    [HttpGet]
    public IActionResult GetAll() => Ok();

    // GET: api/products/5
    [HttpGet("{id}")]
    public IActionResult GetById(int id) => Ok();

    // GET: api/products/5/reviews
    [HttpGet("{id}/reviews")]
    public IActionResult GetReviews(int id) => Ok();

    // POST: api/products
    [HttpPost]
    public IActionResult Create([FromBody] Product product) => Ok();

    // PUT: api/products/5
    [HttpPut("{id}")]
    public IActionResult Update(int id, [FromBody] Product product) => Ok();

    // DELETE: api/products/5
    [HttpDelete("{id}")]
    public IActionResult Delete(int id) => Ok();
}
```

**Advanced Attribute Routing:**
```csharp
[Route("api/v{version:apiVersion}/[controller]")]
[ApiController]
public class CustomersController : ControllerBase
{
    // Custom route: api/v1/customers/search?name=John
    [HttpGet("search")]
    public IActionResult Search([FromQuery] string name) => Ok();

    // Route constraint: api/v1/customers/5 (id must be int)
    [HttpGet("{id:int}")]
    public IActionResult GetById(int id) => Ok();

    // Multiple routes for same action
    [HttpGet("")]
    [HttpGet("all")]
    public IActionResult GetAll() => Ok();
}
```

**Key Differences:**

| Aspect | Conventional Routing | Attribute Routing |
|--------|---------------------|-------------------|
| Definition Location | Centralized in Program.cs | On controllers/actions |
| Flexibility | Less flexible | More flexible |
| Best For | MVC web apps | Web APIs |
| Visibility | Global patterns | Local to action |
| Maintenance | Single location | Scattered across controllers |

### What is Razor Pages and how does it differ from MVC?

**Razor Pages** is a page-based programming model that makes building web UI easier and more productive.

**Razor Pages Structure:**
```
Pages/
├── Index.cshtml          (View)
├── Index.cshtml.cs       (PageModel - code-behind)
├── Privacy.cshtml
├── Privacy.cshtml.cs
└── Shared/
    └── _Layout.cshtml
```

**Example Razor Page:**
```csharp
// Index.cshtml.cs
public class IndexModel : PageModel
{
    private readonly ILogger _logger;

    [BindProperty]
    public string UserName { get; set; }

    public List Products { get; set; }

    public IndexModel(ILogger logger)
    {
        _logger = logger;
    }

    public void OnGet()
    {
        Products = GetProducts();
    }

    public IActionResult OnPost()
    {
        if (!ModelState.IsValid)
        {
            return Page();
        }

        // Process form
        return RedirectToPage("Success");
    }
}
```

```html

@page
@model IndexModel

Welcome @Model.UserName


    
    Submit


@foreach (var product in Model.Products)
{
    @product.Name
}
```

**Key Differences:**

| Feature | Razor Pages | MVC |
|---------|-------------|-----|
| Structure | Page-centric (cshtml + cs) | Controller-centric |
| Routing | Convention-based on folder | Attribute or conventional |
| Best For | Simple CRUD, forms | Complex apps, APIs |
| Organization | Page-focused | Separated concerns |
| Learning Curve | Easier | Steeper |
| Handler Methods | OnGet, OnPost | Action methods |

**MVC Example (for comparison):**
```csharp
// Controller
public class HomeController : Controller
{
    public IActionResult Index()
    {
        var model = new IndexViewModel();
        return View(model);
    }

    [HttpPost]
    public IActionResult Index(IndexViewModel model)
    {
        if (!ModelState.IsValid)
            return View(model);
        
        return RedirectToAction("Success");
    }
}
```

**When to Use:**
- **Razor Pages**: Simple pages, forms, CRUD operations, page-focused scenarios
- **MVC**: Complex applications, RESTful APIs, when you need more control over routing

### How do you implement versioning in Web APIs?

API versioning allows you to maintain multiple versions of your API simultaneously.

**Installation:**
```bash
dotnet add package Asp.Versioning.Mvc
dotnet add package Asp.Versioning.Mvc.ApiExplorer
```

**Method 1: URL Path Versioning (Most Common)**
```csharp
// Program.cs
builder.Services.AddApiVersioning(options =>
{
    options.DefaultApiVersion = new ApiVersion(1, 0);
    options.AssumeDefaultVersionWhenUnspecified = true;
    options.ReportApiVersions = true;
});

// Controller
[ApiController]
[Route("api/v{version:apiVersion}/[controller]")]
[ApiVersion("1.0")]
public class ProductsV1Controller : ControllerBase
{
    [HttpGet]
    public IActionResult Get() => Ok("Version 1.0");
}

[ApiController]
[Route("api/v{version:apiVersion}/[controller]")]
[ApiVersion("2.0")]
public class ProductsV2Controller : ControllerBase
{
    [HttpGet]
    public IActionResult Get() => Ok("Version 2.0 with new features");
}

// Usage:
// GET /api/v1/products
// GET /api/v2/products
```

**Method 2: Query String Versioning**
```csharp
builder.Services.AddApiVersioning(options =>
{
    options.ApiVersionReader = new QueryStringApiVersionReader("api-version");
});

[ApiController]
[Route("api/[controller]")]
[ApiVersion("1.0")]
[ApiVersion("2.0")]
public class ProductsController : ControllerBase
{
    [HttpGet]
    [MapToApiVersion("1.0")]
    public IActionResult GetV1() => Ok("Version 1.0");

    [HttpGet]
    [MapToApiVersion("2.0")]
    public IActionResult GetV2() => Ok("Version 2.0");
}

// Usage:
// GET /api/products?api-version=1.0
// GET /api/products?api-version=2.0
```

**Method 3: Header Versioning**
```csharp
builder.Services.AddApiVersioning(options =>
{
    options.ApiVersionReader = new HeaderApiVersionReader("X-Api-Version");
});

// Usage:
// GET /api/products
// Headers: X-Api-Version: 1.0
```

**Method 4: Media Type Versioning**
```csharp
builder.Services.AddApiVersioning(options =>
{
    options.ApiVersionReader = new MediaTypeApiVersionReader();
});

// Usage:
// GET /api/products
// Headers: Accept: application/json;v=1.0
```

**Deprecating Old Versions:**
```csharp
[ApiVersion("1.0", Deprecated = true)]
[ApiVersion("2.0")]
[ApiController]
[Route("api/v{version:apiVersion}/[controller]")]
public class ProductsController : ControllerBase
{
    // Implementation
}
```

**Multiple Versioning Strategies:**
```csharp
builder.Services.AddApiVersioning(options =>
{
    options.ApiVersionReader = ApiVersionReader.Combine(
        new QueryStringApiVersionReader("api-version"),
        new HeaderApiVersionReader("X-Api-Version"),
        new UrlSegmentApiVersionReader()
    );
});
```

### What are health checks in ASP.NET Core?

**Health Checks** allow you to monitor the health and availability of your application and its dependencies.

**Basic Implementation:**
```csharp
// Program.cs
builder.Services.AddHealthChecks()
    .AddCheck("self", () => HealthCheckResult.Healthy())
    .AddSqlServer(
        builder.Configuration.GetConnectionString("DefaultConnection"),
        name: "database",
        timeout: TimeSpan.FromSeconds(5))
    .AddUrlGroup(
        new Uri("https://api.external.com/health"),
        name: "external-api",
        timeout: TimeSpan.FromSeconds(3))
    .AddRedis(
        builder.Configuration.GetConnectionString("Redis"),
        name: "redis");

app.MapHealthChecks("/health");
```

**Custom Health Check:**
```csharp
public class CustomHealthCheck : IHealthCheck
{
    private readonly IHttpClientFactory _httpClientFactory;

    public CustomHealthCheck(IHttpClientFactory httpClientFactory)
    {
        _httpClientFactory = httpClientFactory;
    }

    public async Task CheckHealthAsync(
        HealthCheckContext context,
        CancellationToken cancellationToken = default)
    {
        try
        {
            var client = _httpClientFactory.CreateClient();
            var response = await client.GetAsync("https://api.example.com/status");

            if (response.IsSuccessStatusCode)
            {
                return HealthCheckResult.Healthy("External API is responding");
            }

            return HealthCheckResult.Degraded("External API returned non-success status");
        }
        catch (Exception ex)
        {
            return HealthCheckResult.Unhealthy("External API is not accessible", ex);
        }
    }
}

// Register
builder.Services.AddHealthChecks()
    .AddCheck("custom-check");
```

**Health Check with Detailed Response:**
```csharp
app.MapHealthChecks("/health/detailed", new HealthCheckOptions
{
    ResponseWriter = async (context, report) =>
    {
        context.Response.ContentType = "application/json";

        var result = JsonSerializer.Serialize(new
        {
            status = report.Status.ToString(),
            checks = report.Entries.Select(e => new
            {
                name = e.Key,
                status = e.Value.Status.ToString(),
                description = e.Value.Description,
                duration = e.Value.Duration.ToString()
            }),
            totalDuration = report.TotalDuration
        });

        await context.Response.WriteAsync(result);
    }
});
```

**Health Check with Tags:**
```csharp
builder.Services.AddHealthChecks()
    .AddSqlServer(
        connectionString,
        name: "database",
        tags: new[] { "db", "sql" })
    .AddRedis(
        redisConnection,
        name: "cache",
        tags: new[] { "cache", "redis" });

// Endpoint for specific tags
app.MapHealthChecks("/health/ready", new HealthCheckOptions
{
    Predicate = check => check.Tags.Contains("ready")
});

app.MapHealthChecks("/health/live", new HealthCheckOptions
{
    Predicate = check => check.Tags.Contains("live")
});
```

**Health Check UI (Optional Package):**
```bash
dotnet add package AspNetCore.HealthChecks.UI
dotnet add package AspNetCore.HealthChecks.UI.InMemory.Storage
```

```csharp
builder.Services
    .AddHealthChecksUI()
    .AddInMemoryStorage();

app.MapHealthChecksUI();

// Access UI at: /healthchecks-ui
```

**Common Use Cases:**
- Kubernetes liveness and readiness probes
- Load balancer health endpoints
- Monitoring and alerting systems
- Circuit breaker patterns
- Graceful degradation

**Example Response:**
```json
{
  "status": "Healthy",
  "checks": [
    {
      "name": "database",
      "status": "Healthy",
      "description": "SQL Server is healthy",
      "duration": "00:00:00.1234567"
    },
    {
      "name": "redis",
      "status": "Healthy",
      "description": "Redis is healthy",
      "duration": "00:00:00.0234567"
    }
  ],
  "totalDuration": "00:00:00.1469134"
}
```
---

## Entity Framework and Database

### What is Entity Framework Core and how does it differ from Entity Framework 6?

**Entity Framework Core (EF Core)** is a lightweight, extensible, open-source, and cross-platform version of Entity Framework, Microsoft's Object-Relational Mapper (ORM) for .NET.

**Key Differences:**

| Aspect | EF Core | EF 6 |
|--------|---------|------|
| Platform | Cross-platform (.NET Core, .NET 5+) | Windows only (.NET Framework) |
| Performance | Faster, more efficient | Slower |
| Features | Modern, lightweight | Feature-rich, mature |
| LINQ Translation | Improved client/server evaluation | Limited |
| Batching | Better batch operations | Limited batching |
| Global Query Filters | Supported | Not supported |
| Shadow Properties | Enhanced support | Limited |
| Owned Entities | Better support | Limited |
| Database Providers | More providers available | Fewer providers |

**What EF Core doesn't have (from EF6):**
- Lazy loading by default (needs configuration)
- Automatic migrations
- ObjectContext API
- Entity splitting
- Some inheritance strategies

### Explain Code First vs Database First approaches.

**Code First Approach:**
- Define your domain model classes first
- EF generates the database schema from your code
- Uses migrations to evolve the database
- Better for new projects and version control

```csharp
public class Product
{
    public int Id { get; set; }
    public string Name { get; set; }
    public decimal Price { get; set; }
}

public class AppDbContext : DbContext
{
    public DbSet Products { get; set; }
}

// Generate migration: dotnet ef migrations add InitialCreate
// Update database: dotnet ef database update
```

**Database First Approach:**
- Start with an existing database
- Generate entity classes from the database
- Uses scaffolding to create models
- Better for existing databases

```bash
# Scaffold from existing database
dotnet ef dbcontext scaffold "ConnectionString" Microsoft.EntityFrameworkCore.SqlServer -o Models
```

**When to use each:**
- **Code First**: New projects, agile development, domain-driven design
- **Database First**: Legacy databases, DBA-controlled schemas, multiple applications sharing one database

### What is the difference between eager loading, lazy loading, and explicit loading?

**1. Eager Loading**
Load related data as part of the initial query using `Include()`.

```csharp
// Single level
var orders = context.Orders
    .Include(o => o.Customer)
    .ToList();

// Multiple levels
var orders = context.Orders
    .Include(o => o.Customer)
    .Include(o => o.OrderItems)
        .ThenInclude(oi => oi.Product)
    .ToList();
```

**2. Lazy Loading**
Related data is automatically loaded when accessed. Requires `Microsoft.EntityFrameworkCore.Proxies`.

```csharp
// Enable lazy loading
services.AddDbContext(options =>
    options.UseLazyLoadingProxies()
           .UseSqlServer(connectionString));

// Make navigation properties virtual
public class Order
{
    public int Id { get; set; }
    public virtual Customer Customer { get; set; }
    public virtual ICollection OrderItems { get; set; }
}

// Data loaded when accessed
var order = context.Orders.First();
var customerName = order.Customer.Name; // Triggers database query
```

**3. Explicit Loading**
Manually load related data when needed using `Load()`.

```csharp
var order = context.Orders.First();

// Load single reference
context.Entry(order)
    .Reference(o => o.Customer)
    .Load();

// Load collection
context.Entry(order)
    .Collection(o => o.OrderItems)
    .Load();

// Load with filter
context.Entry(order)
    .Collection(o => o.OrderItems)
    .Query()
    .Where(oi => oi.Quantity > 5)
    .Load();
```

**Comparison:**

| Type | Pros | Cons | Use Case |
|------|------|------|----------|
| Eager | Single query, no N+1 problem | Can over-fetch data | Known data needs |
| Lazy | Load only what's needed | N+1 problem, requires open connection | Exploratory operations |
| Explicit | Fine-grained control | More code, manual management | Conditional loading |

### What are migration strategies in EF Core?

**Migrations** track changes to your data model and update the database schema.

**1. Basic Migration Commands:**

```bash
# Add a new migration
dotnet ef migrations add MigrationName

# Update database to latest migration
dotnet ef database update

# Update to specific migration
dotnet ef database update MigrationName

# Remove last migration (if not applied)
dotnet ef migrations remove

# Generate SQL script
dotnet ef migrations script

# List all migrations
dotnet ef migrations list
```

**2. Migration Strategies:**

**A. Automatic Migrations (Development)**
```csharp
public static void Main(string[] args)
{
    var host = CreateHostBuilder(args).Build();
    
    using (var scope = host.Services.CreateScope())
    {
        var context = scope.ServiceProvider.GetRequiredService();
        context.Database.Migrate(); // Apply pending migrations
    }
    
    host.Run();
}
```

**B. Manual SQL Scripts (Production)**
```bash
# Generate SQL script for deployment
dotnet ef migrations script --idempotent --output migration.sql
```

**C. Custom Migration Code**
```csharp
public partial class AddProductIndex : Migration
{
    protected override void Up(MigrationBuilder migrationBuilder)
    {
        migrationBuilder.CreateIndex(
            name: "IX_Products_Name",
            table: "Products",
            column: "Name");
            
        // Custom SQL
        migrationBuilder.Sql(@"
            UPDATE Products 
            SET Price = Price * 1.1 
            WHERE CategoryId = 1
        ");
    }

    protected override void Down(MigrationBuilder migrationBuilder)
    {
        migrationBuilder.DropIndex(
            name: "IX_Products_Name",
            table: "Products");
    }
}
```

**D. Data Seeding in Migrations**
```csharp
protected override void Up(MigrationBuilder migrationBuilder)
{
    migrationBuilder.InsertData(
        table: "Categories",
        columns: new[] { "Id", "Name" },
        values: new object[,]
        {
            { 1, "Electronics" },
            { 2, "Books" },
            { 3, "Clothing" }
        });
}
```

**Best Practices:**
- Keep migrations small and focused
- Test migrations in development first
- Use `--idempotent` scripts for production
- Never modify applied migrations
- Keep migration history in source control

### Explain the Unit of Work and Repository patterns.

**Repository Pattern**
Abstracts data access logic and provides a collection-like interface for accessing domain objects.

```csharp
public interface IRepository where T : class
{
    Task GetByIdAsync(int id);
    Task<IEnumerable> GetAllAsync();
    Task<IEnumerable> FindAsync(Expression<Func> predicate);
    Task AddAsync(T entity);
    void Update(T entity);
    void Remove(T entity);
}

public class Repository : IRepository where T : class
{
    protected readonly DbContext _context;
    protected readonly DbSet _dbSet;

    public Repository(DbContext context)
    {
        _context = context;
        _dbSet = context.Set();
    }

    public async Task GetByIdAsync(int id)
    {
        return await _dbSet.FindAsync(id);
    }

    public async Task<IEnumerable> GetAllAsync()
    {
        return await _dbSet.ToListAsync();
    }

    public async Task<IEnumerable> FindAsync(Expression<Func> predicate)
    {
        return await _dbSet.Where(predicate).ToListAsync();
    }

    public async Task AddAsync(T entity)
    {
        await _dbSet.AddAsync(entity);
    }

    public void Update(T entity)
    {
        _dbSet.Update(entity);
    }

    public void Remove(T entity)
    {
        _dbSet.Remove(entity);
    }
}
```

**Unit of Work Pattern**
Maintains a list of objects affected by a business transaction and coordinates writing changes to the database.

```csharp
public interface IUnitOfWork : IDisposable
{
    IRepository Products { get; }
    IRepository Categories { get; }
    IRepository Orders { get; }
    
    Task SaveChangesAsync();
    Task BeginTransactionAsync();
    Task CommitTransactionAsync();
    Task RollbackTransactionAsync();
}

public class UnitOfWork : IUnitOfWork
{
    private readonly AppDbContext _context;
    private IDbContextTransaction _transaction;

    public UnitOfWork(AppDbContext context)
    {
        _context = context;
        Products = new Repository(_context);
        Categories = new Repository(_context);
        Orders = new Repository(_context);
    }

    public IRepository Products { get; private set; }
    public IRepository Categories { get; private set; }
    public IRepository Orders { get; private set; }

    public async Task SaveChangesAsync()
    {
        return await _context.SaveChangesAsync();
    }

    public async Task BeginTransactionAsync()
    {
        _transaction = await _context.Database.BeginTransactionAsync();
    }

    public async Task CommitTransactionAsync()
    {
        await _transaction.CommitAsync();
    }

    public async Task RollbackTransactionAsync()
    {
        await _transaction.RollbackAsync();
    }

    public void Dispose()
    {
        _transaction?.Dispose();
        _context.Dispose();
    }
}
```

**Usage Example:**
```csharp
public class ProductService
{
    private readonly IUnitOfWork _unitOfWork;

    public ProductService(IUnitOfWork unitOfWork)
    {
        _unitOfWork = unitOfWork;
    }

    public async Task CreateProductWithCategoryAsync(Product product, Category category)
    {
        await _unitOfWork.BeginTransactionAsync();
        
        try
        {
            await _unitOfWork.Categories.AddAsync(category);
            await _unitOfWork.SaveChangesAsync();
            
            product.CategoryId = category.Id;
            await _unitOfWork.Products.AddAsync(product);
            await _unitOfWork.SaveChangesAsync();
            
            await _unitOfWork.CommitTransactionAsync();
        }
        catch
        {
            await _unitOfWork.RollbackTransactionAsync();
            throw;
        }
    }
}
```

**Benefits:**
- Separation of concerns
- Testability (easy to mock)
- Centralized data access logic
- Transaction management
- Reduced coupling

**Note:** DbContext already implements Unit of Work pattern, so this is often considered over-engineering for simple applications.

### What is the N+1 query problem and how do you solve it?

**N+1 Query Problem** occurs when you execute 1 query to fetch N records, then N additional queries to fetch related data for each record.

**Example of N+1 Problem:**
```csharp
// 1 query to get orders
var orders = context.Orders.ToList();

// N queries (one per order) to get customers
foreach (var order in orders)
{
    Console.WriteLine(order.Customer.Name); // Lazy loading triggers query
}
// Total: 1 + N queries!
```

**Solutions:**

**1. Eager Loading with Include()**
```csharp
// Single query with JOIN
var orders = context.Orders
    .Include(o => o.Customer)
    .ToList();

foreach (var order in orders)
{
    Console.WriteLine(order.Customer.Name); // No additional query
}
```

**2. Select/Projection**
```csharp
// Query only needed data
var orderSummaries = context.Orders
    .Select(o => new 
    {
        OrderId = o.Id,
        CustomerName = o.Customer.Name,
        Total = o.Total
    })
    .ToList();
```

**3. Split Queries for Multiple Includes**
```csharp
// Instead of one large JOIN, use multiple queries
var orders = context.Orders
    .Include(o => o.Customer)
    .Include(o => o.OrderItems)
    .AsSplitQuery() // EF Core 5.0+
    .ToList();
```

**4. Explicit Loading with Batch**
```csharp
var orders = context.Orders.ToList();

// Load all customers in one query
var customerIds = orders.Select(o => o.CustomerId).Distinct();
var customers = context.Customers
    .Where(c => customerIds.Contains(c.Id))
    .ToDictionary(c => c.Id);

// Map in memory
foreach (var order in orders)
{
    order.Customer = customers[order.CustomerId];
}
```

**5. Disable Lazy Loading**
```csharp
// Don't enable lazy loading proxies
services.AddDbContext(options =>
    options.UseSqlServer(connectionString)
    // Don't use: .UseLazyLoadingProxies()
);
```

**Detection Tools:**
```csharp
// Enable sensitive data logging and detailed errors
optionsBuilder
    .EnableSensitiveDataLogging()
    .EnableDetailedErrors()
    .LogTo(Console.WriteLine, LogLevel.Information);
```

### How do you optimize Entity Framework queries?

**1. Use AsNoTracking() for Read-Only Queries**
```csharp
// 30-40% faster for read-only scenarios
var products = context.Products
    .AsNoTracking()
    .Where(p => p.IsActive)
    .ToList();
```

**2. Project Only Needed Columns**
```csharp
// Bad: Fetches all columns
var products = context.Products.ToList();

// Good: Fetch only needed data
var products = context.Products
    .Select(p => new { p.Id, p.Name, p.Price })
    .ToList();
```

**3. Use Compiled Queries**
```csharp
private static readonly Func GetProductById =
    EF.CompileQuery((AppDbContext context, int id) =>
        context.Products.FirstOrDefault(p => p.Id == id));

// Usage
var product = GetProductById(context, 123);
```

**4. Batch Operations**
```csharp
// Bad: Multiple round trips
foreach (var product in products)
{
    context.Products.Add(product);
    context.SaveChanges(); // Don't do this!
}

// Good: Single batch
context.Products.AddRange(products);
context.SaveChanges();
```

**5. Use Pagination**
```csharp
var products = context.Products
    .OrderBy(p => p.Name)
    .Skip((page - 1) * pageSize)
    .Take(pageSize)
    .ToList();
```

**6. Filter Before Loading**
```csharp
// Bad: Load all then filter in memory
var activeProducts = context.Products
    .ToList()
    .Where(p => p.IsActive);

// Good: Filter in database
var activeProducts = context.Products
    .Where(p => p.IsActive)
    .ToList();
```

**7. Use Indexes**
```csharp
protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    modelBuilder.Entity()
        .HasIndex(p => p.Name);
        
    modelBuilder.Entity()
        .HasIndex(o => new { o.CustomerId, o.OrderDate });
}
```

**8. Avoid Cartesian Explosion with Split Queries**
```csharp
// Multiple collections can create huge result sets
var customers = context.Customers
    .Include(c => c.Orders)
    .Include(c => c.Addresses)
    .AsSplitQuery() // Prevents cartesian product
    .ToList();
```

**9. Use Raw SQL for Complex Queries**
```csharp
var results = context.Products
    .FromSqlRaw("SELECT * FROM Products WHERE Price > {0}", minPrice)
    .ToList();
```

**10. Configure Query Splitting Strategy**
```csharp
protected override void OnConfiguring(DbContextOptionsBuilder optionsBuilder)
{
    optionsBuilder
        .UseSqlServer(connectionString,
            options => options.UseQuerySplittingBehavior(QuerySplittingBehavior.SplitQuery));
}
```

**11. Use Database-Side Evaluation**
```csharp
// Good: Evaluated in database
var count = context.Products
    .Count(p => p.Price > 100);

// Bad: All data loaded into memory first
var count = context.Products
    .ToList()
    .Count(p => p.Price > 100);
```

### Explain tracking vs no-tracking queries in EF Core.

**Tracking Queries (Default)**
EF Core keeps track of entity changes in the change tracker for `SaveChanges()`.

```csharp
// Tracking enabled by default
var product = context.Products.First();
product.Price = 99.99m;
context.SaveChanges(); // Change tracked and saved
```

**How Change Tracking Works:**
```csharp
var product = context.Products.Find(1);

// Check tracking state
var entry = context.Entry(product);
Console.WriteLine(entry.State); // EntityState.Unchanged

product.Name = "Updated";
Console.WriteLine(entry.State); // EntityState.Modified

// See what changed
foreach (var property in entry.Properties)
{
    if (property.IsModified)
    {
        Console.WriteLine($"{property.Metadata.Name}: " +
            $"{property.OriginalValue} -> {property.CurrentValue}");
    }
}
```

**No-Tracking Queries**
Entities are not tracked, improving performance for read-only scenarios.

```csharp
// No-tracking for single query
var products = context.Products
    .AsNoTracking()
    .Where(p => p.IsActive)
    .ToList();

// Changes are NOT tracked
products[0].Price = 99.99m;
context.SaveChanges(); // Nothing saved!
```

**Global No-Tracking Configuration:**
```csharp
protected override void OnConfiguring(DbContextOptionsBuilder optionsBuilder)
{
    optionsBuilder
        .UseSqlServer(connectionString)
        .UseQueryTrackingBehavior(QueryTrackingBehavior.NoTracking);
}

// Override for specific query
var product = context.Products
    .AsTracking()
    .First();
```

**AsNoTrackingWithIdentityResolution**
```csharp
// Maintains identity resolution within query without full tracking
var orders = context.Orders
    .Include(o => o.Customer)
    .Include(o => o.OrderItems)
        .ThenInclude(oi => oi.Product)
    .AsNoTrackingWithIdentityResolution() // Same customer instance reused
    .ToList();
```

**Comparison:**

| Aspect | Tracking | No-Tracking |
|--------|----------|-------------|
| Performance | Slower (memory overhead) | 30-40% faster |
| Memory | Higher | Lower |
| Use Case | Update/Delete operations | Read-only queries |
| Identity Resolution | Automatic | Not by default |
| SaveChanges() | Detects changes | No changes detected |

**When to Use Each:**

**Use Tracking:**
- Updating or deleting entities
- Need automatic change detection
- Working with related entities
- Short-lived contexts

**Use No-Tracking:**
- Read-only queries
- Display/reporting
- API GET endpoints
- Large result sets
- Performance critical scenarios

**Manual Tracking Control:**
```csharp
// Detach entity
context.Entry(product).State = EntityState.Detached;

// Attach and mark as modified
context.Attach(product);
context.Entry(product).State = EntityState.Modified;

// Track specific properties
context.Entry(product).Property(p => p.Price).IsModified = true;
```

### What are owned entities and table splitting in EF Core?

**Owned Entities**
Owned types are value objects that belong to another entity and share its lifetime.

```csharp
// Value object
public class Address
{
    public string Street { get; set; }
    public string City { get; set; }
    public string ZipCode { get; set; }
    public string Country { get; set; }
}

// Entity owning the value object
public class Customer
{
    public int Id { get; set; }
    public string Name { get; set; }
    public Address ShippingAddress { get; set; }
    public Address BillingAddress { get; set; }
}

// Configuration
protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    modelBuilder.Entity()
        .OwnsOne(c => c.ShippingAddress, sa =>
        {
            sa.Property(a => a.Street).HasColumnName("ShippingStreet");
            sa.Property(a => a.City).HasColumnName("ShippingCity");
        });
        
    modelBuilder.Entity()
        .OwnsOne(c => c.BillingAddress, ba =>
        {
            ba.Property(a => a.Street).HasColumnName("BillingStreet");
            ba.Property(a => a.City).HasColumnName("BillingCity");
        });
}
```

**Result:** All columns in same table:
```
Customers Table:
Id | Name | ShippingStreet | ShippingCity | ... | BillingStreet | BillingCity | ...
```

**Owned Collections:**
```csharp
public class Order
{
    public int Id { get; set; }
    public ICollection Items { get; set; }
}

public class OrderItem
{
    public string ProductName { get; set; }
    public int Quantity { get; set; }
    public decimal Price { get; set; }
}

protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    modelBuilder.Entity()
        .OwnsMany(o => o.Items, item =>
        {
            item.WithOwner().HasForeignKey("OrderId");
            item.Property("Id");
            item.HasKey("Id");
        });
}
```

**Owned Types in Separate Table:**
```csharp
modelBuilder.Entity()
    .OwnsOne(c => c.ShippingAddress)
    .ToTable("ShippingAddresses");
```

**Table Splitting**
Multiple entity types share the same table.

```csharp
public class Order
{
    public int Id { get; set; }
    public DateTime OrderDate { get; set; }
    public OrderDetails Details { get; set; }
}

public class OrderDetails
{
    public int OrderId { get; set; }
    public string Notes { get; set; }
    public string ShippingMethod { get; set; }
    public DateTime? DeliveryDate { get; set; }
}

protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    modelBuilder.Entity()
        .ToTable("Orders");
        
    modelBuilder.Entity()
        .ToTable("Orders"); // Same table!
        
    // Configure relationship
    modelBuilder.Entity()
        .HasOne(o => o.Details)
        .WithOne()
        .HasForeignKey(d => d.OrderId);
        
    // Shared primary key
    modelBuilder.Entity()
        .HasKey(d => d.OrderId);
}
```

**Result:** Single table with columns from both entities:
```
Orders Table:
Id | OrderDate | Notes | ShippingMethod | DeliveryDate
```

**Benefits of Table Splitting:**
- Logical separation of concerns in code
- Single table in database
- Can load entities independently
- Useful for large tables with many columns

**Usage Example:**
```csharp
// Load only main entity
var order = context.Orders
    .AsNoTracking()
    .First();

// Load with details
var orderWithDetails = context.Orders
    .Include(o => o.Details)
    .First();
```

**Owned Entity Navigation:**
```csharp
// Query owned entity
var customersInNewYork = context.Customers
    .Where(c => c.ShippingAddress.City == "New York")
    .ToList();
```

**Key Differences:**

| Feature | Owned Entities | Table Splitting |
|---------|----------------|-----------------|
| Relationship | One-to-one or one-to-many | One-to-one only |
| Identity | No separate identity | Separate entities |
| Querying | Part of owner | Can query independently |
| Use Case | Value objects | Logical separation |

### How do you handle concurrency in Entity Framework?

**Concurrency Control** prevents data conflicts when multiple users update the same record simultaneously.

**1. Optimistic Concurrency with RowVersion (Timestamp)**

```csharp
public class Product
{
    public int Id { get; set; }
    public string Name { get; set; }
    public decimal Price { get; set; }
    
    [Timestamp]
    public byte[] RowVersion { get; set; }
}

// Or using Fluent API
protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    modelBuilder.Entity()
        .Property(p => p.RowVersion)
        .IsRowVersion();
}
```

**How It Works:**
```csharp
try
{
    var product = context.Products.Find(1);
    product.Price = 99.99m;
    
    context.SaveChanges(); // Checks RowVersion
}
catch (DbUpdateConcurrencyException ex)
{
    // Handle conflict
    var entry = ex.Entries.Single();
    var databaseValues = entry.GetDatabaseValues();
    var currentValues = entry.CurrentValues;
    
    Console.WriteLine("Conflict detected!");
    Console.WriteLine($"Current: {currentValues["Price"]}");
    Console.WriteLine($"Database: {databaseValues["Price"]}");
}
```

**2. Concurrency Token (Any Property)**

```csharp
public class Product
{
    public int Id { get; set; }
    public string Name { get; set; }
    public decimal Price { get; set; }
    
    [ConcurrencyCheck]
    public DateTime LastModified { get; set; }
}

// Or Fluent API
modelBuilder.Entity()
    .Property(p => p.LastModified)
    .IsConcurrencyToken();
```

**3. Complete Concurrency Handling Strategy**

```csharp
public async Task UpdateProductAsync(Product product)
{
    using var transaction = await context.Database.BeginTransactionAsync();
    
    try
    {
        context.Entry(product).State = EntityState.Modified;
        await context.SaveChangesAsync();
        await transaction.CommitAsync();
        return true;
    }
    catch (DbUpdateConcurrencyException ex)
    {
        await transaction.RollbackAsync();
        
        foreach (var entry in ex.Entries)
        {
            if (entry.Entity is Product)
            {
                var proposedValues = entry.CurrentValues;
                var databaseValues = entry.GetDatabaseValues();
                
                if (databaseValues == null)
                {
                    // Entity was deleted
                    Console.WriteLine("Entity was deleted by another user");
                }
                else
                {
                    // Conflict resolution strategies:
                    
                    // 1. Client Wins (overwrite database)
                    entry.OriginalValues.SetValues(databaseValues);
                    
                    // 2. Database Wins (discard client changes)
                    // entry.CurrentValues.SetValues(databaseValues);
                    
                    // 3. Merge (selective update)
                    // foreach (var property in proposedValues.Properties)
                    // {
                    //     var proposed = proposedValues[property];
                    //     var database = databaseValues[property];
                    //     // Custom merge logic
                    // }
                }
            }
        }
        
        // Retry the save operation
        try
        {
            await context.SaveChangesAsync();
            return true;
        }
        catch (DbUpdateConcurrencyException)
        {
            return false; // Give up after retry
        }
    }
}
```

**4. Disconnected Entity Scenario (Web API)**

```csharp
[HttpPut("products/{id}")]
public async Task UpdateProduct(int id, ProductDto dto)
{
    var product = new Product
    {
        Id = id,
        Name = dto.Name,
        Price = dto.Price,
        RowVersion = dto.RowVersion // From client
    };
    
    context.Products.Attach(product);
    context.Entry(product).Property(p => p.Name).IsModified = true;
    context.Entry(product).Property(p => p.Price).IsModified = true;
    
    try
    {
        await context.SaveChangesAsync();
        return Ok();
    }
    catch (DbUpdateConcurrencyException)
    {
        return Conflict(new { message = "This record was modified by another user" });
    }
}
```

**5. Manual Concurrency Check**

```csharp
modelBuilder.Entity()
    .Property(p => p.Name)
    .IsConcurrencyToken();

// SQL Server generates:
// UPDATE Products 
// SET Price = @price 
// WHERE Id = @id AND Name = @originalName
```

**Concurrency Resolution Strategies:**

| Strategy | Description | Use Case |
|----------|-------------|----------|
| Client Wins | Overwrite database with client values | User is always right |
| Database Wins | Discard client changes | Latest change wins |
| Merge | Combine non-conflicting changes | Collaborative editing |
| User Decides | Show both versions, let user choose | Critical data |

**Best Practices:**
- Always use RowVersion/Timestamp for SQL Server
- Handle DbUpdateConcurrencyException appropriately
- Inform users about conflicts
- Use optimistic concurrency for web applications
- Consider pessimistic locking (database locks) for critical sections
- Log concurrency conflicts for monitoring
---
### Explain the difference between `SaveChanges()` and `SaveChangesAsync()`.

**SaveChanges()** - Synchronous
Blocks the current thread until database operations complete.

```csharp
public void AddProduct(Product product)
{
    context.Products.Add(product);
    int affectedRows = context.SaveChanges(); // Blocks here
    Console.WriteLine($"Saved {affectedRows} rows");
}
```

**SaveChangesAsync()** - Asynchronous
Returns a Task, allowing the thread to do other work while waiting.

```csharp
public async Task AddProductAsync(Product product)
{
    context.Products.Add(product);
    int affectedRows = await context.SaveChangesAsync(); // Doesn't block
    Console.WriteLine($"Saved {affectedRows} rows");
}
```

**Key Differences:**

| Aspect | SaveChanges() | SaveChangesAsync() |
|--------|---------------|-------------------|
| Thread Blocking | Blocks thread | Non-blocking |
| Return Type | `int` | `Task<int>` |
| Performance | Can bottleneck | Better scalability |
| Use Case | Console apps, batch jobs | Web APIs, UI apps |
| Thread Pool | Occupies thread | Releases thread |

**Performance Impact:**

```csharp
// Synchronous - Thread blocked during I/O
public void ProcessOrders()
{
    for (int i = 0; i < 1000; i++)
    {
        var order = new Order { /* ... */ };
        context.Orders.Add(order);
        context.SaveChanges(); // Thread waits for DB
    }
}

// Asynchronous - Thread available for other work
public async Task ProcessOrdersAsync()
{
    for (int i = 0; i < 1000; i++)
    {
        var order = new Order { /* ... */ };
        context.Orders.Add(order);
        await context.SaveChangesAsync(); // Thread released during DB operation
    }
}
```

**Web API Example:**

```csharp
// BAD: Synchronous in async controller
[HttpPost]
public async Task CreateProduct(Product product)
{
    context.Products.Add(product);
    context.SaveChanges(); // Don't do this!
    return Ok();
}

// GOOD: Async all the way
[HttpPost]
public async Task CreateProduct(Product product)
{
    context.Products.Add(product);
    await context.SaveChangesAsync();
    return Ok();
}
```

**CancellationToken Support:**

```csharp
public async Task CreateProductAsync(
    Product product, 
    CancellationToken cancellationToken)
{
    context.Products.Add(product);
    await context.SaveChangesAsync(cancellationToken);
    return product;
}
```

**When to Use Each:**

**Use SaveChanges():**
- Console applications
- Batch processing jobs
- Synchronous codebases
- Simple scripts
- When async is not available

**Use SaveChangesAsync():**
- ASP.NET Core Web APIs
- Web applications
- Desktop apps with UI
- High-concurrency scenarios
- When scalability matters

**Important Notes:**
- Mixing sync and async can cause deadlocks
- Always use async in ASP.NET Core
- Async doesn't make individual operations faster, but improves scalability
- Don't use `SaveChangesAsync().Wait()` or `.Result` - use proper async/await

**Transaction Example:**

```csharp
// Synchronous transaction
using (var transaction = context.Database.BeginTransaction())
{
    try
    {
        context.Products.Add(product);
        context.SaveChanges();
        
        context.Categories.Add(category);
        context.SaveChanges();
        
        transaction.Commit();
    }
    catch
    {
        transaction.Rollback();
        throw;
    }
}

// Asynchronous transaction
using (var transaction = await context.Database.BeginTransactionAsync())
{
    try
    {
        context.Products.Add(product);
        await context.SaveChangesAsync();
        
        context.Categories.Add(category);
        await context.SaveChangesAsync();
        
        await transaction.CommitAsync();
    }
    catch
    {
        await transaction.RollbackAsync();
        throw;
    }
}
```

### What are shadow properties in EF Core?

**Shadow Properties** are properties that exist in the EF Core model but not in the .NET entity class. They only exist in the database and change tracker.

**Why Use Shadow Properties?**
- Foreign keys you don't want in your domain model
- Audit fields (CreatedDate, ModifiedDate)
- Soft delete flags
- Database-specific metadata
- Keep domain model clean

**1. Basic Shadow Property Configuration:**

```csharp
public class Product
{
    public int Id { get; set; }
    public string Name { get; set; }
    public decimal Price { get; set; }
    // No CreatedDate or ModifiedDate properties in class!
}

protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    // Add shadow properties
    modelBuilder.Entity()
        .Property("CreatedDate")
        .HasDefaultValueSql("GETDATE()");
        
    modelBuilder.Entity()
        .Property("ModifiedDate");
        
    modelBuilder.Entity()
        .Property("CreatedBy")
        .HasMaxLength(100);
}
```

**2. Accessing Shadow Properties:**

```csharp
// Setting shadow property values
var product = new Product { Name = "Laptop", Price = 999.99m };
context.Products.Add(product);

// Access through Entry API
context.Entry(product).Property("CreatedBy").CurrentValue = "john.doe";
context.Entry(product).Property("ModifiedDate").CurrentValue = DateTime.UtcNow;

await context.SaveChangesAsync();

// Reading shadow property values
var createdDate = context.Entry(product).Property("CreatedDate").CurrentValue;
Console.WriteLine($"Created: {createdDate}");
```

**3. Querying Shadow Properties:**

```csharp
// Use EF.Property in LINQ queries
var recentProducts = context.Products
    .Where(p => EF.Property(p, "CreatedDate") > DateTime.UtcNow.AddDays(-7))
    .ToList();

// Order by shadow property
var products = context.Products
    .OrderByDescending(p => EF.Property(p, "ModifiedDate"))
    .ToList();

// Select shadow properties
var productInfo = context.Products
    .Select(p => new
    {
        p.Name,
        Created = EF.Property(p, "CreatedDate"),
        Modified = EF.Property(p, "ModifiedDate")
    })
    .ToList();
```

**4. Shadow Foreign Keys:**

```csharp
public class Order
{
    public int Id { get; set; }
    public Customer Customer { get; set; }
    // No CustomerId property!
}

public class Customer
{
    public int Id { get; set; }
    public string Name { get; set; }
}

protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    modelBuilder.Entity()
        .HasOne(o => o.Customer)
        .WithMany()
        .HasForeignKey("CustomerId"); // Shadow FK
}

// Usage
var order = new Order { Customer = customer };
context.Orders.Add(order);
await context.SaveChangesAsync();

// Access shadow FK
var customerId = context.Entry(order).Property("CustomerId").CurrentValue;
```

**5. Audit Trail with Shadow Properties:**

```csharp
public abstract class AuditableEntity
{
    public int Id { get; set; }
}

protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    foreach (var entityType in modelBuilder.Model.GetEntityTypes())
    {
        if (typeof(AuditableEntity).IsAssignableFrom(entityType.ClrType))
        {
            modelBuilder.Entity(entityType.ClrType)
                .Property("CreatedDate")
                .HasDefaultValueSql("GETDATE()");
                
            modelBuilder.Entity(entityType.ClrType)
                .Property("ModifiedDate");
                
            modelBuilder.Entity(entityType.ClrType)
                .Property("CreatedBy")
                .HasMaxLength(256);
                
            modelBuilder.Entity(entityType.ClrType)
                .Property("ModifiedBy")
                .HasMaxLength(256);
        }
    }
}

// Auto-populate on SaveChanges
public override int SaveChanges()
{
    var entries = ChangeTracker.Entries()
        .Where(e => e.Entity is AuditableEntity && 
                   (e.State == EntityState.Added || e.State == EntityState.Modified));
    
    foreach (var entry in entries)
    {
        var currentUser = GetCurrentUser(); // Your user service
        
        if (entry.State == EntityState.Added)
        {
            entry.Property("CreatedDate").CurrentValue = DateTime.UtcNow;
            entry.Property("CreatedBy").CurrentValue = currentUser;
        }
        
        entry.Property("ModifiedDate").CurrentValue = DateTime.UtcNow;
        entry.Property("ModifiedBy").CurrentValue = currentUser;
    }
    
    return base.SaveChanges();
}
```

**6. Soft Delete with Shadow Property:**

```csharp
protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    // Add IsDeleted shadow property to all entities
    foreach (var entityType in modelBuilder.Model.GetEntityTypes())
    {
        modelBuilder.Entity(entityType.ClrType)
            .Property("IsDeleted")
            .HasDefaultValue(false);
            
        // Global query filter
        var parameter = Expression.Parameter(entityType.ClrType, "e");
        var property = Expression.Property(parameter, "IsDeleted");
        var filter = Expression.Lambda(
            Expression.Equal(property, Expression.Constant(false)),
            parameter);
            
        modelBuilder.Entity(entityType.ClrType).HasQueryFilter(filter);
    }
}

// Soft delete implementation
public void SoftDelete(T entity) where T : class
{
    context.Entry(entity).Property("IsDeleted").CurrentValue = true;
}

// Usage
var product = context.Products.Find(1);
SoftDelete(product);
context.SaveChanges();

// Query automatically filters soft-deleted records
var products = context.Products.ToList(); // Only non-deleted

// Include soft-deleted records
var allProducts = context.Products
    .IgnoreQueryFilters()
    .ToList();
```

**7. Indexing Shadow Properties:**

```csharp
protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    modelBuilder.Entity()
        .Property("CreatedDate");
        
    modelBuilder.Entity()
        .HasIndex("CreatedDate")
        .HasDatabaseName("IX_Product_CreatedDate");
}
```

**8. Shadow Properties vs Regular Properties:**

| Aspect | Shadow Properties | Regular Properties |
|--------|------------------|-------------------|
| In Entity Class | No | Yes |
| Type Safety | Runtime only | Compile-time |
| IntelliSense | No | Yes |
| Access | EF.Property() | Direct access |
| Refactoring | Manual | Automatic |
| Use Case | Infrastructure concerns | Domain model |

**Advantages:**
- Keep domain model clean
- Separate infrastructure concerns
- Database-specific features
- Flexible schema management
- Audit without polluting model

**Disadvantages:**
- No compile-time safety
- No IntelliSense support
- String-based access (typo-prone)
- Less discoverable
- More complex queries

**Best Practices:**
- Use for infrastructure concerns only
- Document shadow properties clearly
- Create helper methods for common access patterns
- Consider using interfaces for better discoverability
- Use constants for property names to avoid typos

```csharp
// Good practice: Use constants
public static class ShadowProperties
{
    public const string CreatedDate = nameof(CreatedDate);
    public const string ModifiedDate = nameof(ModifiedDate);
    public const string IsDeleted = nameof(IsDeleted);
}

// Usage
var createdDate = context.Entry(product)
    .Property(ShadowProperties.CreatedDate)
    .CurrentValue;
```

---

## Summary

Entity Framework Core provides a powerful and flexible ORM solution for .NET applications. Key takeaways:

1. **EF Core vs EF6**: Cross-platform, better performance, modern features
2. **Code First vs Database First**: Choose based on project requirements
3. **Loading Strategies**: Eager, lazy, and explicit loading - each with specific use cases
4. **Migrations**: Track and manage database schema changes
5. **Patterns**: Repository and Unit of Work for better architecture
6. **N+1 Problem**: Use eager loading and projections to avoid performance issues
7. **Query Optimization**: AsNoTracking, projections, compiled queries, and proper indexing
8. **Tracking**: Understand when to use tracking vs no-tracking queries
9. **Owned Entities**: Model value objects effectively
10. **Concurrency**: Use optimistic concurrency control with RowVersion
11. **Async Operations**: Always use async in web applications for scalability
12. **Shadow Properties**: Keep infrastructure concerns separate from domain model

Master these concepts to build efficient, maintainable, and scalable applications with Entity Framework Core!
---

## Performance and Memory Management

### Explain garbage collection in .NET and its generations.

**Garbage Collection (GC)** is .NET's automatic memory management system that reclaims memory occupied by unused objects.

**How Garbage Collection Works:**

1. **Mark Phase**: GC identifies which objects are still in use by traversing object references from roots (static fields, local variables, CPU registers)
2. **Sweep Phase**: GC removes unreachable objects
3. **Compact Phase**: GC moves surviving objects together to reduce fragmentation

**GC Generations:**

.NET uses a generational garbage collection model with three generations:

```
Generation 0 (Gen 0) - Young objects
├── Short-lived objects
├── Temporary variables
├── Fast collection (< 1ms typically)
└── Most frequent collections

Generation 1 (Gen 1) - Middle-aged objects
├── Survived one Gen 0 collection
├── Buffer between Gen 0 and Gen 2
├── Fast collection
└── Intermediate frequency

Generation 2 (Gen 2) - Old objects
├── Long-lived objects
├── Static data
├── Slower collection (can be 100ms+)
└── Least frequent collections

Large Object Heap (LOH)
├── Objects > 85,000 bytes
├── Not compacted by default
├── Collected with Gen 2
└── Can cause fragmentation
```

**Generation Promotion:**

```csharp
// Example of object lifetime
public void DemonstrateGenerations()
{
    // Gen 0 - temporary object
    var temp = new byte[100];
    
    // Gen 0 collection happens
    GC.Collect(0);
    
    // 'temp' survives, promoted to Gen 1
    
    // More Gen 0 collections...
    GC.Collect(0);
    
    // 'temp' still alive, promoted to Gen 2
    
    Console.WriteLine($"Generation: {GC.GetGeneration(temp)}");
}
```

**GC Modes:**

**1. Workstation GC**
- For client applications
- Optimized for responsiveness
- Runs on same thread that triggered collection

```csharp
// In .csproj

  false

```

**2. Server GC**
- For server applications
- Optimized for throughput
- Multiple GC threads (one per CPU)
- Larger heap segments

```csharp
// In .csproj

  true

```

**GC Collection Types:**

```csharp
// Check GC mode
bool isServerGC = GCSettings.IsServerGC;
Console.WriteLine($"Server GC: {isServerGC}");

// Check latency mode
Console.WriteLine($"Latency Mode: {GCSettings.LatencyMode}");

// Set latency mode
GCSettings.LatencyMode = GCLatencyMode.LowLatency; // For time-critical operations

// Force garbage collection (avoid in production!)
GC.Collect(); // Full collection
GC.Collect(0); // Gen 0 only
GC.Collect(2, GCCollectionMode.Optimized);

// Wait for finalization
GC.WaitForPendingFinalizers();

// Get GC stats
for (int i = 0; i <= GC.MaxGeneration; i++)
{
    Console.WriteLine($"Gen {i} collections: {GC.CollectionCount(i)}");
}
```

**GC Notifications:**

```csharp
// Register for GC notifications
GC.RegisterForFullGCNotification(10, 10);

// In a monitoring thread
while (true)
{
    GCNotificationStatus status = GC.WaitForFullGCApproach();
    if (status == GCNotificationStatus.Succeeded)
    {
        Console.WriteLine("Full GC is approaching...");
        // Prepare: redirect traffic, pause operations, etc.
    }
    
    status = GC.WaitForFullGCComplete();
    if (status == GCNotificationStatus.Succeeded)
    {
        Console.WriteLine("Full GC completed.");
        // Resume normal operations
    }
}
```

**GC Performance Tips:**

```csharp
// 1. Reuse objects when possible
private static readonly StringBuilder _builder = new StringBuilder();

public string BuildString(params string[] parts)
{
    _builder.Clear();
    foreach (var part in parts)
        _builder.Append(part);
    return _builder.ToString();
}

// 2. Use object pooling
private static readonly ObjectPool _pool = 
    new DefaultObjectPool(new StringBuilderPooledObjectPolicy());

public string BuildStringPooled(params string[] parts)
{
    var builder = _pool.Get();
    try
    {
        foreach (var part in parts)
            builder.Append(part);
        return builder.ToString();
    }
    finally
    {
        _pool.Return(builder);
    }
}

// 3. Use structs for small, short-lived data
public struct Point // Value type, stack allocated
{
    public int X { get; set; }
    public int Y { get; set; }
}

// 4. Avoid finalizers unless necessary
public class ResourceHolder : IDisposable
{
    private bool _disposed;
    
    public void Dispose()
    {
        if (!_disposed)
        {
            // Clean up managed resources
            _disposed = true;
            GC.SuppressFinalize(this); // Prevent finalizer call
        }
    }
    
    // Only add finalizer if holding unmanaged resources
    ~ResourceHolder()
    {
        Dispose();
    }
}
```

**GC Pressure:**

```csharp
// Add memory pressure for unmanaged resources
public class UnmanagedResourceHolder : IDisposable
{
    private IntPtr _unmanagedMemory;
    private const long ResourceSize = 1024 * 1024; // 1MB
    
    public UnmanagedResourceHolder()
    {
        _unmanagedMemory = Marshal.AllocHGlobal((int)ResourceSize);
        GC.AddMemoryPressure(ResourceSize); // Tell GC about unmanaged memory
    }
    
    public void Dispose()
    {
        if (_unmanagedMemory != IntPtr.Zero)
        {
            Marshal.FreeHGlobal(_unmanagedMemory);
            GC.RemoveMemoryPressure(ResourceSize);
            _unmanagedMemory = IntPtr.Zero;
        }
    }
}
```

**Weak References:**

```csharp
// Hold reference without preventing collection
public class CacheManager
{
    private readonly Dictionary> _cache = new();
    
    public void AddToCache(string key, byte[] data)
    {
        _cache[key] = new WeakReference(data);
    }
    
    public byte[] GetFromCache(string key)
    {
        if (_cache.TryGetValue(key, out var weakRef) && 
            weakRef.TryGetTarget(out var data))
        {
            return data; // Object still alive
        }
        return null; // Object was collected
    }
}
```

**Best Practices:**
- Don't call `GC.Collect()` manually in production
- Use `IDisposable` for deterministic cleanup
- Minimize allocations in hot paths
- Use structs for small, short-lived data
- Pool objects for frequently allocated types
- Monitor GC metrics in production

### What are memory leaks and how do you identify them in .NET?

A **memory leak** in .NET occurs when objects that are no longer needed remain referenced, preventing garbage collection.

**Common Causes of Memory Leaks:**

**1. Event Handler Leaks**

```csharp
// BAD: Memory leak
public class Publisher
{
    public event EventHandler OnDataChanged;
}

public class Subscriber
{
    public Subscriber(Publisher publisher)
    {
        publisher.OnDataChanged += HandleDataChanged; // Leak!
    }
    
    private void HandleDataChanged(object sender, EventArgs e)
    {
        // Handle event
    }
}

// GOOD: Proper cleanup
public class Subscriber : IDisposable
{
    private readonly Publisher _publisher;
    
    public Subscriber(Publisher publisher)
    {
        _publisher = publisher;
        _publisher.OnDataChanged += HandleDataChanged;
    }
    
    public void Dispose()
    {
        _publisher.OnDataChanged -= HandleDataChanged; // Unsubscribe!
    }
    
    private void HandleDataChanged(object sender, EventArgs e)
    {
        // Handle event
    }
}
```

**2. Static References**

```csharp
// BAD: Keeps all users in memory forever
public static class UserCache
{
    private static readonly List _users = new List();
    
    public static void AddUser(User user)
    {
        _users.Add(user); // Never released!
    }
}

// GOOD: Use weak references or implement eviction
public static class UserCache
{
    private static readonly Dictionary> _users = new();
    
    public static void AddUser(User user)
    {
        _users[user.Id] = new WeakReference(user);
    }
    
    public static User GetUser(int id)
    {
        if (_users.TryGetValue(id, out var weakRef) && 
            weakRef.TryGetTarget(out var user))
        {
            return user;
        }
        return null;
    }
}
```

**3. Timer Leaks**

```csharp
// BAD: Timer keeps object alive
public class DataRefresher
{
    private Timer _timer;
    
    public DataRefresher()
    {
        _timer = new Timer(RefreshData, null, 0, 1000);
    }
    
    private void RefreshData(object state)
    {
        // Refresh logic
    }
    
    // No disposal - leak!
}

// GOOD: Dispose timer
public class DataRefresher : IDisposable
{
    private Timer _timer;
    
    public DataRefresher()
    {
        _timer = new Timer(RefreshData, null, 0, 1000);
    }
    
    private void RefreshData(object state)
    {
        // Refresh logic
    }
    
    public void Dispose()
    {
        _timer?.Dispose();
        _timer = null;
    }
}
```

**4. Captured Variables in Closures**

```csharp
// BAD: Captures large object
public void ProcessData()
{
    var largeData = LoadLargeDataSet(); // 100MB
    
    Task.Run(() =>
    {
        // Only need one field, but captures entire object
        Console.WriteLine(largeData.Count);
    });
}

// GOOD: Capture only what you need
public void ProcessData()
{
    var largeData = LoadLargeDataSet();
    int count = largeData.Count; // Copy value
    largeData = null; // Allow GC
    
    Task.Run(() =>
    {
        Console.WriteLine(count);
    });
}
```

**5. Unmanaged Resources**

```csharp
// BAD: Native memory leak
public class ImageProcessor
{
    private IntPtr _nativeBuffer;
    
    public ImageProcessor()
    {
        _nativeBuffer = Marshal.AllocHGlobal(1024 * 1024);
    }
    
    // No cleanup!
}

// GOOD: Implement IDisposable
public class ImageProcessor : IDisposable
{
    private IntPtr _nativeBuffer;
    private bool _disposed;
    
    public ImageProcessor()
    {
        _nativeBuffer = Marshal.AllocHGlobal(1024 * 1024);
    }
    
    protected virtual void Dispose(bool disposing)
    {
        if (!_disposed)
        {
            if (disposing)
            {
                // Dispose managed resources
            }
            
            // Free unmanaged resources
            if (_nativeBuffer != IntPtr.Zero)
            {
                Marshal.FreeHGlobal(_nativeBuffer);
                _nativeBuffer = IntPtr.Zero;
            }
            
            _disposed = true;
        }
    }
    
    public void Dispose()
    {
        Dispose(true);
        GC.SuppressFinalize(this);
    }
    
    ~ImageProcessor()
    {
        Dispose(false);
    }
}
```

**Identifying Memory Leaks:**

**1. Using Visual Studio Diagnostic Tools**

```csharp
// Take memory snapshots during execution
// Debug -> Windows -> Show Diagnostic Tools
// Take Snapshot -> Compare snapshots to find growing objects
```

**2. Using dotMemory or ANTS Memory Profiler**

```bash
# Professional memory profilers
# - Show object retention paths
# - Identify event handler leaks
# - Compare snapshots
# - Find large object heap fragmentation
```

**3. Using PerfView**

```bash
# Free Microsoft tool
dotnet tool install -g Microsoft.Diagnostics.Tools.dotnet-trace
dotnet-trace collect --process-id  --providers Microsoft-Windows-DotNETRuntime
```

**4. Custom Memory Monitoring**

```csharp
public class MemoryMonitor
{
    private readonly Timer _timer;
    
    public MemoryMonitor()
    {
        _timer = new Timer(CheckMemory, null, 0, 5000);
    }
    
    private void CheckMemory(object state)
    {
        var process = Process.GetCurrentProcess();
        var memoryMB = process.WorkingSet64 / 1024 / 1024;
        
        Console.WriteLine($"Memory Usage: {memoryMB} MB");
        Console.WriteLine($"Gen 0: {GC.CollectionCount(0)}");
        Console.WriteLine($"Gen 1: {GC.CollectionCount(1)}");
        Console.WriteLine($"Gen 2: {GC.CollectionCount(2)}");
        
        // Alert if memory grows continuously
        if (memoryMB > 1000)
        {
            Console.WriteLine("WARNING: High memory usage!");
            
            // Force GC to see if memory is really leaked
            GC.Collect();
            GC.WaitForPendingFinalizers();
            GC.Collect();
            
            var afterGC = Process.GetCurrentProcess().WorkingSet64 / 1024 / 1024;
            Console.WriteLine($"After GC: {afterGC} MB");
        }
    }
}
```

**5. Using Memory Dumps**

```bash
# Create dump file
dotnet-dump collect --process-id 

# Analyze dump
dotnet-dump analyze dump_file.dmp

# Commands in dump analysis
> dumpheap -stat  # Show object statistics
> dumpheap -mt   # Show instances
> gcroot   # Show what keeps object alive
> eeheap -gc  # Show heap stats
```

**6. Application Insights / Logging**

```csharp
public class MemoryMetrics
{
    private readonly ILogger _logger;
    private readonly IMetricsCollector _metrics;
    
    public void LogMemoryUsage()
    {
        var info = GC.GetGCMemoryInfo();
        
        _logger.LogInformation(
            "Memory: Heap={HeapSize}MB, FragmentedBytes={Fragmented}MB",
            info.HeapSizeBytes / 1024 / 1024,
            info.FragmentedBytes / 1024 / 1024);
            
        _metrics.TrackMetric("MemoryUsage", info.HeapSizeBytes);
        _metrics.TrackMetric("Gen2Collections", GC.CollectionCount(2));
    }
}
```

**Detection Patterns:**

```csharp
public class LeakDetector
{
    private long _baselineMemory;
    private int _measurementCount;
    
    public void EstablishBaseline()
    {
        // Force GC to get accurate baseline
        GC.Collect();
        GC.WaitForPendingFinalizers();
        GC.Collect();
        
        _baselineMemory = GC.GetTotalMemory(false);
        _measurementCount = 0;
    }
    
    public bool CheckForLeak()
    {
        _measurementCount++;
        
        if (_measurementCount % 10 == 0) // Check every 10 operations
        {
            GC.Collect();
            GC.WaitForPendingFinalizers();
            GC.Collect();
            
            var currentMemory = GC.GetTotalMemory(false);
            var growth = currentMemory - _baselineMemory;
            var growthPercentage = (growth * 100.0) / _baselineMemory;
            
            if (growthPercentage > 20) // 20% growth
            {
                Console.WriteLine($"Potential leak detected! Growth: {growthPercentage:F2}%");
                return true;
            }
        }
        
        return false;
    }
}
```

**Best Practices:**
- Always unsubscribe from events
- Implement IDisposable properly
- Use weak references for caches
- Avoid static collections of objects
- Use `using` statements for disposable resources
- Monitor memory in production
- Profile regularly during development
- Use memory profilers to find retention paths
---

# .NET Memory Management & Performance Guide

## Memory Management

### What is the difference between stack and heap memory?

**Stack Memory:**
- Used for static memory allocation
- Stores value types, method parameters, and local variables
- LIFO (Last In, First Out) structure
- Very fast allocation and deallocation
- Memory is automatically managed when methods enter/exit scope
- Limited in size (typically 1MB per thread)
- Thread-specific - each thread has its own stack
- No garbage collection needed

**Heap Memory:**
- Used for dynamic memory allocation
- Stores reference types (objects, arrays, strings)
- Managed by the Garbage Collector
- Slower allocation and deallocation compared to stack
- Much larger size (limited by available system memory)
- Shared across all threads in the application
- Requires garbage collection to reclaim unused memory
- Memory fragmentation can occur

**Example:**
```csharp
public void Example()
{
    // Stack: value type stored on stack
    int x = 5;
    
    // Stack: variable 'person' (reference) on stack
    // Heap: actual Person object on heap
    Person person = new Person();
    
    // Stack: struct stored on stack
    Point point = new Point(10, 20);
}
```

**Key Differences:**
- Stack is faster but limited in size
- Heap is slower but can hold larger amounts of data
- Stack variables are automatically cleaned up
- Heap requires garbage collection
- Value types typically go on stack (unless part of reference type)
- Reference types always go on heap

---

### How would you profile and optimize a .NET application?

**Profiling Tools:**

1. **Visual Studio Profiler**
   - CPU Usage
   - Memory Usage
   - Database performance
   - .NET Object Allocation Tracking

2. **dotTrace** (JetBrains)
   - Timeline profiling
   - Sampling and tracing
   - Call tree analysis

3. **dotMemory** (JetBrains)
   - Memory snapshots
   - Memory leak detection
   - Retention analysis

4. **PerfView**
   - ETW-based performance analysis
   - CPU and memory profiling
   - Free Microsoft tool

5. **BenchmarkDotNet**
   - Micro-benchmarking library
   - Precise performance measurements

**Optimization Strategy:**

**1. Measure First**
```csharp
// Use BenchmarkDotNet
[Benchmark]
public void MethodToProfile()
{
    // Code to measure
}
```

**2. Identify Bottlenecks**
- CPU hotspots
- Memory allocations
- I/O operations
- Database queries
- Lock contention

**3. Common Optimization Techniques**

**Reduce Allocations:**
```csharp
// Bad: Creates new string on each call
public string GetFullName(string first, string last)
{
    return first + " " + last;
}

// Better: Use StringBuilder for multiple concatenations
public string GetFullName(string first, string last)
{
    return string.Concat(first, " ", last);
}

// Best for frequent calls: Use Span
public void GetFullName(ReadOnlySpan first, ReadOnlySpan last, Span destination)
{
    first.CopyTo(destination);
    destination[first.Length] = ' ';
    last.CopyTo(destination.Slice(first.Length + 1));
}
```

**Use Value Types When Appropriate:**
```csharp
// Instead of class for small data
public readonly struct Point
{
    public int X { get; }
    public int Y { get; }
}
```

**Async/Await for I/O:**
```csharp
public async Task GetDataAsync()
{
    using var client = new HttpClient();
    return await client.GetStringAsync(url);
}
```

**4. Memory Optimization**
- Use object pooling for frequently created objects
- Dispose IDisposable objects properly
- Avoid boxing/unboxing
- Use `Span<T>` and `Memory<T>` for data manipulation
- Consider using `stackalloc` for small arrays

**5. Monitoring in Production**
- Application Insights
- Performance counters
- Custom logging and metrics
- Health checks

---

### What is `Span<T>` and `Memory<T>`? When should you use them?

**Span<T>:**

A ref struct that provides a type-safe and memory-safe representation of a contiguous region of arbitrary memory.

**Key Characteristics:**
- Stack-only type (ref struct)
- Zero allocation
- Can point to stack memory, managed heap, or native memory
- Cannot be used in async methods
- Cannot be stored as a field in regular classes

**Example:**
```csharp
// Working with arrays without allocation
public int Sum(Span numbers)
{
    int sum = 0;
    foreach (int num in numbers)
    {
        sum += num;
    }
    return sum;
}

// Can be called with different memory sources
int[] array = {1, 2, 3, 4, 5};
Sum(array); // Works with array
Sum(array.AsSpan(1, 3)); // Works with slice
Span stackArray = stackalloc int[5];
Sum(stackArray); // Works with stack memory
```

**String Manipulation:**
```csharp
public ReadOnlySpan ExtractUsername(string email)
{
    int atIndex = email.IndexOf('@');
    return email.AsSpan(0, atIndex); // No allocation!
}
```

**Memory<T>:**

Similar to `Span<T>` but can be stored on the heap and used in async methods.

**Key Characteristics:**
- Can be stored as a field in classes
- Can be used in async methods
- Slightly more overhead than Span<T>
- Provides `.Span` property to get a Span<T>

**Example:**
```csharp
public class BufferProcessor
{
    private Memory _buffer;
    
    public async Task ProcessAsync()
    {
        // Memory can be used across await
        await Task.Delay(100);
        
        // Get Span when doing actual work
        Span span = _buffer.Span;
        ProcessData(span);
    }
    
    private void ProcessData(Span data)
    {
        // Fast processing without allocations
    }
}
```

**When to Use:**

**Use Span<T> when:**
- Working with buffers in synchronous code
- Need maximum performance and zero allocations
- Manipulating strings or arrays without creating copies
- Working with stack-allocated memory

**Use Memory<T> when:**
- Need to store reference to memory as a field
- Working in async methods
- Need to pass memory across async boundaries
- Building APIs that might be used in async contexts

**Use ReadOnlySpan<T>/ReadOnlyMemory<T> when:**
- You don't need to modify the data
- Provides additional safety guarantees

**Performance Benefits:**
```csharp
// Traditional approach - allocations!
public string[] SplitData(string data)
{
    return data.Split(','); // Allocates array + strings
}

// Span approach - zero allocations!
public void SplitData(ReadOnlySpan data, Span ranges)
{
    int rangeIndex = 0;
    int start = 0;
    
    for (int i = 0; i < data.Length; i++)
    {
        if (data[i] == ',')
        {
            ranges[rangeIndex++] = start..i;
            start = i + 1;
        }
    }
    ranges[rangeIndex] = start..data.Length;
}
```

---

### Explain object pooling and when to use it.

**Object Pooling** is a design pattern that reuses objects instead of creating and destroying them repeatedly, reducing garbage collection pressure and improving performance.

**How It Works:**

1. Create a pool of pre-initialized objects
2. Rent an object when needed
3. Return the object to the pool when done
4. Reset the object state before returning to pool

**Implementation Example:**

```csharp
// Using ObjectPool from Microsoft.Extensions.ObjectPool
public class BufferPool
{
    private readonly ObjectPool _pool;
    
    public BufferPool()
    {
        var policy = new DefaultPooledObjectPolicy
        {
            MaximumRetained = 100
        };
        
        _pool = new DefaultObjectPool(
            new BufferPoolPolicy(), 
            100
        );
    }
    
    public byte[] Rent()
    {
        return _pool.Get();
    }
    
    public void Return(byte[] buffer)
    {
        Array.Clear(buffer, 0, buffer.Length);
        _pool.Return(buffer);
    }
}

public class BufferPoolPolicy : IPooledObjectPolicy
{
    public byte[] Create()
    {
        return new byte[4096];
    }
    
    public bool Return(byte[] obj)
    {
        Array.Clear(obj, 0, obj.Length);
        return true;
    }
}
```

**Using ArrayPool<T>:**

```csharp
public void ProcessData()
{
    // Rent array from pool
    byte[] buffer = ArrayPool.Shared.Rent(1024);
    
    try
    {
        // Use the buffer
        ReadData(buffer);
        ProcessBuffer(buffer);
    }
    finally
    {
        // Always return to pool
        ArrayPool.Shared.Return(buffer, clearArray: true);
    }
}
```

**Custom Object Pool:**

```csharp
public class Connection
{
    public void Open() { }
    public void Close() { }
    public void Reset() { }
}

public class ConnectionPool
{
    private readonly ConcurrentBag _pool = new();
    private readonly int _maxSize;
    private int _count;
    
    public ConnectionPool(int maxSize)
    {
        _maxSize = maxSize;
    }
    
    public Connection Rent()
    {
        if (_pool.TryTake(out var connection))
        {
            return connection;
        }
        
        if (_count < _maxSize)
        {
            Interlocked.Increment(ref _count);
            return new Connection();
        }
        
        // Wait for available connection
        SpinWait.SpinUntil(() => _pool.TryTake(out connection));
        return connection;
    }
    
    public void Return(Connection connection)
    {
        connection.Reset();
        _pool.Add(connection);
    }
}
```

**When to Use Object Pooling:**

**Use When:**
- Objects are expensive to create (database connections, large arrays)
- Objects are created and destroyed frequently
- Garbage collection pressure is high
- Application has predictable object usage patterns
- Objects can be safely reused after resetting state

**Good Candidates:**
- Database connections
- HTTP client instances
- Large buffers or arrays
- StringBuilder instances
- MemoryStream objects
- Socket connections
- Encryption/hashing objects

**Don't Use When:**
- Objects are lightweight and cheap to create
- Object creation rate is low
- Objects cannot be safely reset or reused
- Pool management overhead exceeds creation cost
- Objects have complex state that's hard to reset

**Benefits:**
- Reduced GC pressure
- Improved performance
- Lower memory allocation
- Predictable memory usage
- Faster object acquisition

**Considerations:**
- Thread safety
- Proper cleanup/reset of pooled objects
- Pool size management
- Memory leaks if objects aren't returned
- Potential for holding onto memory longer than needed

**Example Use Case:**

```csharp
public class ImageProcessor
{
    private readonly ObjectPool _stringBuilderPool;
    private readonly ArrayPool _byteArrayPool;
    
    public async Task ProcessImageAsync(Stream imageStream)
    {
        // Rent pooled objects
        var sb = _stringBuilderPool.Get();
        var buffer = _byteArrayPool.Rent(8192);
        
        try
        {
            int bytesRead;
            while ((bytesRead = await imageStream.ReadAsync(buffer, 0, buffer.Length)) > 0)
            {
                // Process buffer
                sb.Append(Convert.ToBase64String(buffer, 0, bytesRead));
            }
            
            return sb.ToString();
        }
        finally
        {
            // Always return to pools
            sb.Clear();
            _stringBuilderPool.Return(sb);
            _byteArrayPool.Return(buffer, clearArray: true);
        }
    }
}
```

**Built-in .NET Pools:**
- `ArrayPool<T>.Shared`
- `MemoryPool<T>.Shared`
- `ObjectPool<T>` (Microsoft.Extensions.ObjectPool)
- HttpClient connection pooling (automatic)
- Thread pool

---
### What are the best practices for string concatenation in loops?

String concatenation in loops can severely impact performance because strings are immutable in C#. Each concatenation creates a new string object, leading to excessive memory allocations and garbage collection pressure.

**Bad Practice:**
```csharp
string result = "";
for (int i = 0; i < 1000; i++)
{
    result += i.ToString(); // Creates 1000 new string objects
}
```

**Best Practices:**

1. **Use StringBuilder for multiple concatenations:**
```csharp
var sb = new StringBuilder();
for (int i = 0; i < 1000; i++)
{
    sb.Append(i);
}
string result = sb.ToString();
```

2. **Pre-allocate capacity when size is known:**
```csharp
var sb = new StringBuilder(capacity: 5000);
for (int i = 0; i < 1000; i++)
{
    sb.Append(i);
}
```

3. **Use string.Join() for collections:**
```csharp
var numbers = Enumerable.Range(0, 1000);
string result = string.Join(",", numbers);
```

4. **Use string interpolation for simple cases:**
```csharp
// For few concatenations (2-3), this is optimized by the compiler
string result = $"{firstName} {lastName}";
```

**Performance Impact:**
- String concatenation: O(n²) time complexity
- StringBuilder: O(n) time complexity
- For 1000+ concatenations, StringBuilder is 100-1000x faster

---

### How do you reduce memory allocations in performance-critical code?

Reducing memory allocations minimizes garbage collection overhead and improves performance in hot paths.

**Key Strategies:**

1. **Use Span<T> and Memory<T> for array slicing:**
```csharp
// Bad: Creates new array
byte[] subset = sourceArray.Skip(10).Take(20).ToArray();

// Good: No allocation
Span subset = sourceArray.AsSpan(10, 20);
```

2. **Pool and reuse objects:**
```csharp
// Use ArrayPool for temporary buffers
byte[] buffer = ArrayPool.Shared.Rent(1024);
try
{
    // Use buffer
}
finally
{
    ArrayPool.Shared.Return(buffer);
}
```

3. **Use struct instead of class for small data:**
```csharp
// Allocated on stack, not heap
public struct Point
{
    public int X { get; set; }
    public int Y { get; set; }
}
```

4. **Avoid boxing value types:**
```csharp
// Bad: Boxing occurs
object obj = 42;

// Good: Use generics to avoid boxing
void Process(T value) where T : struct { }
```

5. **Use stackalloc for small temporary arrays:**
```csharp
// Allocated on stack (< 1KB recommended)
Span numbers = stackalloc int[100];
```

6. **Reuse StringBuilder instances:**
```csharp
private static readonly ThreadLocal _stringBuilder = 
    new ThreadLocal(() => new StringBuilder());

public string BuildString()
{
    var sb = _stringBuilder.Value;
    sb.Clear();
    // Build string
    return sb.ToString();
}
```

7. **Use ValueTask<T> instead of Task<T> when result is often synchronous:**
```csharp
public ValueTask GetCachedValueAsync(string key)
{
    if (_cache.TryGetValue(key, out int value))
        return new ValueTask(value); // No allocation
    
    return new ValueTask(LoadFromDatabaseAsync(key));
}
```

---

### What is the Large Object Heap (LOH)?

The Large Object Heap is a special region of the managed heap designed for objects larger than 85,000 bytes (approximately 85 KB).

**Key Characteristics:**

1. **Separate from Generation 0, 1, 2:**
   - LOH is collected only during Gen 2 collections
   - Objects allocated directly to LOH, bypassing Gen 0 and Gen 1

2. **No Compaction (by default):**
   - LOH is not compacted during garbage collection (before .NET 4.5.1)
   - Can lead to memory fragmentation
   - From .NET 4.5.1+, can enable compaction

3. **Performance Implications:**
```csharp
// Goes to LOH
byte[] largeArray = new byte[100_000]; // > 85KB

// Stays in regular heap
byte[] smallArray = new byte[80_000];  // < 85KB
```

**Best Practices:**

1. **Avoid frequent LOH allocations:**
```csharp
// Bad: Creates LOH allocations repeatedly
for (int i = 0; i < 1000; i++)
{
    byte[] buffer = new byte[100_000];
    ProcessData(buffer);
}

// Good: Reuse large buffers
byte[] buffer = ArrayPool.Shared.Rent(100_000);
try
{
    for (int i = 0; i < 1000; i++)
    {
        ProcessData(buffer);
    }
}
finally
{
    ArrayPool.Shared.Return(buffer);
}
```

2. **Enable LOH compaction when needed:**
```csharp
GCSettings.LargeObjectHeapCompactionMode = 
    GCLargeObjectHeapCompactionMode.CompactOnce;
GC.Collect();
```

3. **Monitor LOH fragmentation:**
```csharp
long lohSize = GC.GetGCMemoryInfo().HeapSizeBytes;
```

**When LOH Matters:**
- Image processing applications
- Large buffer operations
- Video/audio processing
- Scientific computing with large datasets

---

### Explain the concept of weak references

Weak references allow you to maintain a reference to an object while still permitting the garbage collector to reclaim it if memory is needed.

**How It Works:**

```csharp
// Strong reference prevents GC
MyClass strongRef = new MyClass();

// Weak reference allows GC
WeakReference weakRef = new WeakReference(new MyClass());
```

**Use Cases:**

1. **Caching without preventing garbage collection:**
```csharp
public class ImageCache
{
    private Dictionary _cache = new();

    public Image GetImage(string path)
    {
        if (_cache.TryGetValue(path, out WeakReference weakRef))
        {
            if (weakRef.Target is Image image)
                return image; // Still alive
        }

        // Load image if not cached or was collected
        Image newImage = LoadImage(path);
        _cache[path] = new WeakReference(newImage);
        return newImage;
    }
}
```

2. **Event handlers to prevent memory leaks:**
```csharp
public class WeakEventManager
{
    private List _subscribers = new();

    public void Subscribe(EventHandler handler)
    {
        _subscribers.Add(new WeakReference(handler));
    }

    public void RaiseEvent(object sender, EventArgs e)
    {
        _subscribers.RemoveAll(wr => !wr.IsAlive);
        
        foreach (var wr in _subscribers)
        {
            if (wr.Target is EventHandler handler)
                handler(sender, e);
        }
    }
}
```

**Types of Weak References:**

1. **Short Weak Reference (default):**
```csharp
WeakReference wr = new WeakReference(target);
// Target can be collected, even before finalizer runs
```

2. **Long Weak Reference:**
```csharp
WeakReference wr = new WeakReference(target, trackResurrection: true);
// Target accessible until after finalizer runs
```

**Generic WeakReference<T>:**
```csharp
WeakReference weakRef = new WeakReference(obj);

if (weakRef.TryGetTarget(out MyClass target))
{
    // Object still alive, use it
    target.DoSomething();
}
else
{
    // Object was collected
}
```

**Important Considerations:**

- Check `IsAlive` or use `TryGetTarget()` before accessing target
- Target can be collected between checking and accessing
- Not thread-safe by default
- Adds slight overhead for GC tracking
- Best for large objects with expensive recreation costs

**When to Use Weak References:**
- Implementing caches that shouldn't prevent GC
- Managing event subscriptions
- Tracking objects without keeping them alive
- Building object pools with automatic cleanup
---

## LINQ and Collections

### What is LINQ and what are its advantages?

**LINQ (Language Integrated Query)** is a powerful feature in C# that provides a unified syntax for querying different data sources including collections, databases, XML, and more.

**Advantages:**

- **Unified Syntax**: Single query syntax works across multiple data sources (objects, databases, XML, etc.)
- **Type Safety**: Compile-time checking prevents runtime errors
- **IntelliSense Support**: IDE provides autocomplete and suggestions
- **Readable Code**: Declarative syntax is more intuitive than traditional loops
- **Less Code**: Reduces boilerplate code significantly
- **Strongly Typed**: Leverages C#'s type system for safety
- **Extensible**: Can create custom LINQ operators
- **Deferred Execution**: Queries execute only when enumerated, improving performance

```csharp
// Traditional approach
List evenNumbers = new List();
foreach (int num in numbers)
{
    if (num % 2 == 0)
        evenNumbers.Add(num);
}

// LINQ approach
var evenNumbers = numbers.Where(n => n % 2 == 0);
```

### Explain the difference between LINQ query syntax and method syntax.

**Query Syntax** (Comprehension Syntax):
- SQL-like syntax using keywords like `from`, `where`, `select`
- More readable for complex queries with multiple operations
- Limited to common operations

**Method Syntax** (Fluent Syntax):
- Uses extension methods with lambda expressions
- More flexible and supports all LINQ operators
- Better for simple operations and chaining

```csharp
// Query Syntax
var queryResult = from student in students
                  where student.Age > 18
                  orderby student.Name
                  select student.Name;

// Method Syntax
var methodResult = students
    .Where(s => s.Age > 18)
    .OrderBy(s => s.Name)
    .Select(s => s.Name);

// Both produce identical results
// Query syntax is converted to method syntax by the compiler
```

**Key Differences:**
- Query syntax requires `from` and `select`/`group` clauses
- Method syntax can access all LINQ operators
- You can mix both syntaxes in a single query
- Method syntax is more commonly used in practice

### What is the difference between `First()`, `FirstOrDefault()`, `Single()`, and `SingleOrDefault()`?

These methods retrieve elements from a collection but differ in their expectations and error handling:

**`First()`**
- Returns the first element
- Throws `InvalidOperationException` if sequence is empty
- Use when you expect at least one element

**`FirstOrDefault()`**
- Returns the first element or default value (null for reference types, 0 for numbers)
- Never throws exception for empty sequences
- Use when the sequence might be empty

**`Single()`**
- Returns the only element
- Throws if sequence is empty OR has more than one element
- Use when you expect exactly one element

**`SingleOrDefault()`**
- Returns the only element or default value
- Throws if sequence has more than one element (but not if empty)
- Use when you expect zero or one element

```csharp
var numbers = new List { 1, 2, 3, 4, 5 };

// First() - returns 1
var first = numbers.First();

// FirstOrDefault() - returns 1, or 0 if empty
var firstOrDefault = numbers.FirstOrDefault();

// Single() - throws exception (more than one element)
var single = numbers.Single(); // InvalidOperationException!

// With predicate
var firstEven = numbers.First(n => n % 2 == 0); // returns 2
var singleFive = numbers.Single(n => n == 5); // returns 5

// Empty sequence
var empty = new List();
// empty.First(); // throws InvalidOperationException
var result = empty.FirstOrDefault(); // returns 0
```

### Explain deferred execution in LINQ.

**Deferred Execution** means LINQ queries are not executed when they are defined, but only when the results are actually enumerated.

**How it works:**
- Query definition creates an execution plan
- Actual execution happens when you iterate (foreach, ToList(), Count(), etc.)
- Query is re-executed each time you enumerate it
- Benefits: improved performance, fresh data on each execution

```csharp
var numbers = new List { 1, 2, 3, 4, 5 };

// Query is DEFINED but NOT executed
var query = numbers.Where(n => n > 2);
Console.WriteLine("Query defined");

// NOW the query executes (deferred execution)
foreach (var num in query)
{
    Console.WriteLine(num); // Outputs: 3, 4, 5
}

// Modifying source affects query results
numbers.Add(6);
numbers.Add(7);

// Query executes AGAIN with new data
foreach (var num in query)
{
    Console.WriteLine(num); // Outputs: 3, 4, 5, 6, 7
}

// Force immediate execution
var immediateResult = numbers.Where(n => n > 2).ToList();
numbers.Add(8); // This won't affect immediateResult
```

**Operations with Immediate Execution:**
- `ToList()`, `ToArray()`, `ToDictionary()`
- `Count()`, `Sum()`, `Average()`, `Max()`, `Min()`
- `First()`, `Single()`, `Last()`
- `Any()`, `All()`

**Operations with Deferred Execution:**
- `Where()`, `Select()`, `OrderBy()`
- `Skip()`, `Take()`, `GroupBy()`
- `Join()`, `SelectMany()`

### What is the difference between `Select()` and `SelectMany()`?

**`Select()`**
- Projects each element into a new form (1-to-1 transformation)
- Returns `IEnumerable<T>`
- Maintains the structure of the collection

**`SelectMany()`**
- Flattens nested collections into a single sequence (1-to-many transformation)
- Returns flattened `IEnumerable<T>`
- Useful for hierarchical or nested data

```csharp
// Sample data
var schools = new List
{
    new School 
    { 
        Name = "Lincoln High", 
        Students = new[] { "Alice", "Bob" } 
    },
    new School 
    { 
        Name = "Jefferson High", 
        Students = new[] { "Charlie", "Diana" } 
    }
};

// Select() - Returns IEnumerable
var selectResult = schools.Select(s => s.Students);
// Result: [ ["Alice", "Bob"], ["Charlie", "Diana"] ]
// You get a collection of collections

// SelectMany() - Returns IEnumerable
var selectManyResult = schools.SelectMany(s => s.Students);
// Result: ["Alice", "Bob", "Charlie", "Diana"]
// You get a flattened single collection

// Another example
var numbers = new List<List>
{
    new List { 1, 2, 3 },
    new List { 4, 5, 6 },
    new List { 7, 8, 9 }
};

// Select - nested structure preserved
var selected = numbers.Select(list => list);
// Type: IEnumerable<List>

// SelectMany - flattened
var flattened = numbers.SelectMany(list => list);
// Type: IEnumerable
// Result: [1, 2, 3, 4, 5, 6, 7, 8, 9]

// Practical example: Get all words from sentences
var sentences = new[] { "Hello world", "LINQ is powerful" };
var allWords = sentences.SelectMany(s => s.Split(' '));
// Result: ["Hello", "world", "LINQ", "is", "powerful"]
```

### How do you optimize LINQ queries?

**Optimization Techniques:**

**1. Use Appropriate Methods**
```csharp
// Bad: Materializing entire collection
if (list.Where(x => x > 5).Count() > 0)

// Good: Short-circuit evaluation
if (list.Any(x => x > 5))
```

**2. Avoid Multiple Enumeration**
```csharp
// Bad: Query executed twice
var query = list.Where(x => x > 5);
var count = query.Count();
var sum = query.Sum();

// Good: Materialize once
var results = list.Where(x => x > 5).ToList();
var count = results.Count;
var sum = results.Sum();
```

**3. Filter Early**
```csharp
// Bad: Select then filter
var result = list.Select(x => new { x.Id, x.Name })
                 .Where(x => x.Id > 100);

// Good: Filter then select
var result = list.Where(x => x.Id > 100)
                 .Select(x => new { x.Id, x.Name });
```

**4. Use Proper Collection Types**
```csharp
// For lookups, use HashSet or Dictionary
var hashSet = new HashSet(largeList);
if (hashSet.Contains(value)) // O(1) instead of O(n)

// For indexed access, use arrays or lists
int[] array = list.ToArray(); // Better than IEnumerable for iteration
```

**5. Avoid Unnecessary Sorting**
```csharp
// Bad: Sort entire collection to get top 10
var top10 = list.OrderBy(x => x.Score).Take(10);

// Good: Use efficient algorithm for top N
var top10 = list.OrderByDescending(x => x.Score).Take(10);
// Or use a priority queue for large datasets
```

**6. Use AsParallel() for Large Datasets**
```csharp
// Sequential
var result = hugeList.Where(x => ExpensiveOperation(x));

// Parallel (for CPU-bound operations)
var result = hugeList.AsParallel()
                     .Where(x => ExpensiveOperation(x));
```

**7. Avoid Closures in Loops**
```csharp
// Bad: Captured variable
for (int i = 0; i < items.Count; i++)
{
    var query = list.Where(x => x.Id == i); // Captures 'i'
}

// Good: Local copy
for (int i = 0; i < items.Count; i++)
{
    var index = i;
    var query = list.Where(x => x.Id == index);
}
```

**8. Use Compiled Queries for Repeated Execution**
```csharp
// Entity Framework example
var compiledQuery = EF.CompileQuery(
    (MyContext ctx, int id) => ctx.Users.Where(u => u.Id == id)
);
```

### What are the differences between `List<T>`, `HashSet<T>`, and `Dictionary<TKey, TValue>`?

**`List<T>`**
- **Structure**: Dynamic array (ordered collection)
- **Duplicates**: Allows duplicates
- **Access**: Index-based (O(1) by index)
- **Search**: O(n) for Contains/Find
- **Insertion**: O(1) at end, O(n) at beginning/middle
- **Use Case**: When order matters and you need indexed access

```csharp
var list = new List { 1, 2, 3, 2, 1 }; // Duplicates allowed
list.Add(4); // O(1)
var item = list[2]; // O(1) - indexed access
bool exists = list.Contains(3); // O(n)
```

**`HashSet<T>`**
- **Structure**: Hash table (unordered collection)
- **Duplicates**: No duplicates (enforced)
- **Access**: No indexing
- **Search**: O(1) average for Contains
- **Insertion**: O(1) average
- **Use Case**: Unique items, fast lookups, set operations

```csharp
var hashSet = new HashSet { 1, 2, 3, 2, 1 }; // Only {1, 2, 3}
hashSet.Add(4); // O(1)
bool exists = hashSet.Contains(3); // O(1) - fast!
// No indexed access: hashSet[0] is invalid

// Set operations
var set1 = new HashSet { 1, 2, 3 };
var set2 = new HashSet { 3, 4, 5 };
set1.UnionWith(set2); // {1, 2, 3, 4, 5}
set1.IntersectWith(set2); // {3}
```

**`Dictionary<TKey, TValue>`**
- **Structure**: Hash table with key-value pairs
- **Duplicates**: Unique keys, duplicate values allowed
- **Access**: By key (O(1) average)
- **Search**: O(1) for key lookup
- **Insertion**: O(1) average
- **Use Case**: Key-value mappings, fast lookups by key

```csharp
var dict = new Dictionary
{
    { 1, "One" },
    { 2, "Two" },
    { 3, "Three" }
};

dict.Add(4, "Four"); // O(1)
string value = dict[2]; // O(1) - by key
bool exists = dict.ContainsKey(3); // O(1)
bool hasValue = dict.ContainsValue("Two"); // O(n)
```

**Comparison Table:**

| Feature | List<T> | HashSet<T> | Dictionary<TKey, TValue> |
|---------|---------|------------|--------------------------|
| Order | Preserved | Not preserved | Not preserved |
| Duplicates | Yes | No | Keys: No, Values: Yes |
| Index Access | Yes | No | By key |
| Contains | O(n) | O(1) | O(1) for keys |
| Add/Remove | O(1) end, O(n) middle | O(1) | O(1) |
| Memory | Less | More | Most |

### When would you use `ConcurrentDictionary` over `Dictionary`?

**Use `ConcurrentDictionary<TKey, TValue>` when:**

1. **Multiple threads access the collection simultaneously**
2. **Thread-safety is required**
3. **High-performance concurrent operations needed**

**Use regular `Dictionary<TKey, TValue>` when:**

1. **Single-threaded scenarios**
2. **External synchronization is handled**
3. **Performance is critical (Dictionary is faster in single-threaded)**

```csharp
// Regular Dictionary - NOT thread-safe
var dict = new Dictionary();
// Multiple threads accessing this will cause issues!

// ConcurrentDictionary - Thread-safe
var concurrentDict = new ConcurrentDictionary();

// Thread-safe operations
Parallel.For(0, 1000, i =>
{
    concurrentDict.TryAdd(i, $"Value{i}");
});

// Atomic operations
concurrentDict.AddOrUpdate(
    key: 1,
    addValue: "New",
    updateValueFactory: (key, oldValue) => oldValue + "_Updated"
);

// GetOrAdd - atomic operation
var value = concurrentDict.GetOrAdd(5, key => $"Value{key}");

// TryRemove - thread-safe removal
concurrentDict.TryRemove(1, out string removed);

// Update with condition
concurrentDict.TryUpdate(
    key: 2,
    newValue: "NewValue",
    comparisonValue: "OldValue"
);
```

**Key Differences:**

**ConcurrentDictionary Advantages:**
- Built-in thread-safety
- Atomic operations (AddOrUpdate, GetOrAdd)
- Lock-free reads in most cases
- Fine-grained locking (only locks affected buckets)

**ConcurrentDictionary Disadvantages:**
- Higher memory overhead
- Slightly slower in single-threaded scenarios
- More complex API

**Common Scenarios:**

```csharp
// Caching in multi-threaded applications
public class CacheService
{
    private readonly ConcurrentDictionary _cache = new();

    public object GetOrAdd(string key, Func factory)
    {
        return _cache.GetOrAdd(key, factory);
    }
}

// Counting in parallel processing
var wordCounts = new ConcurrentDictionary();
Parallel.ForEach(documents, doc =>
{
    foreach (var word in doc.Split())
    {
        wordCounts.AddOrUpdate(word, 1, (key, count) => count + 1);
    }
});

// Session storage in web applications
private static ConcurrentDictionary _sessions = new();
```

### Explain `GroupBy()` and `Join()` operations in LINQ.

**`GroupBy()`**
- Groups elements by a specified key
- Returns `IEnumerable<IGrouping<TKey, TElement>>`
- Each group has a Key property and contains elements

```csharp
var students = new[]
{
    new { Name = "Alice", Grade = "A", Age = 20 },
    new { Name = "Bob", Grade = "B", Age = 22 },
    new { Name = "Charlie", Grade = "A", Age = 21 },
    new { Name = "Diana", Grade = "B", Age = 20 }
};

// Group by Grade
var byGrade = students.GroupBy(s => s.Grade);
foreach (var group in byGrade)
{
    Console.WriteLine($"Grade {group.Key}:");
    foreach (var student in group)
    {
        Console.WriteLine($"  {student.Name}");
    }
}
// Output:
// Grade A:
//   Alice
//   Charlie
// Grade B:
//   Bob
//   Diana

// Group with projection
var gradeStats = students.GroupBy(s => s.Grade)
                         .Select(g => new
                         {
                             Grade = g.Key,
                             Count = g.Count(),
                             AverageAge = g.Average(s => s.Age),
                             Students = g.Select(s => s.Name).ToList()
                         });

// Group by multiple keys
var byGradeAndAge = students.GroupBy(s => new { s.Grade, s.Age });
```

**`Join()`**
- Performs inner join (like SQL JOIN)
- Combines elements from two sequences based on matching keys
- Returns only matching pairs

```csharp
var students = new[]
{
    new { Id = 1, Name = "Alice" },
    new { Id = 2, Name = "Bob" },
    new { Id = 3, Name = "Charlie" }
};

var grades = new[]
{
    new { StudentId = 1, Course = "Math", Grade = "A" },
    new { StudentId = 2, Course = "Math", Grade = "B" },
    new { StudentId = 1, Course = "Science", Grade = "A" },
    new { StudentId = 4, Course = "Math", Grade = "C" } // No matching student
};

// Inner Join
var studentGrades = students.Join(
    grades,                           // Second collection
    student => student.Id,            // Key from first collection
    grade => grade.StudentId,         // Key from second collection
    (student, grade) => new           // Result selector
    {
        student.Name,
        grade.Course,
        grade.Grade
    }
);

// Result: Only matching pairs (StudentId 4 excluded)
// { Name = "Alice", Course = "Math", Grade = "A" }
// { Name = "Alice", Course = "Science", Grade = "A" }
// { Name = "Bob", Course = "Math", Grade = "B" }

// Query syntax
var queryResult = from student in students
                  join grade in grades on student.Id equals grade.StudentId
                  select new { student.Name, grade.Course, grade.Grade };

// GroupJoin - like LEFT JOIN
var studentAllGrades = students.GroupJoin(
    grades,
    student => student.Id,
    grade => grade.StudentId,
    (student, studentGrades) => new
    {
        student.Name,
        Grades = studentGrades.ToList()
    }
);
// Charlie will appear with empty Grades list
```

**Common Patterns:**

```csharp
// Multiple joins
var result = from student in students
             join grade in grades on student.Id equals grade.StudentId
             join teacher in teachers on grade.TeacherId equals teacher.Id
             select new { student.Name, grade.Course, teacher.Name };

// Join with composite keys
var result = students.Join(
    enrollments,
    s => new { s.Id, s.Year },
    e => new { e.StudentId, e.Year },
    (s, e) => new { s.Name, e.Course }
);

// Left outer join pattern
var leftJoin = from student in students
               join grade in grades on student.Id equals grade.StudentId 
                   into studentGrades
               from grade in studentGrades.DefaultIfEmpty()
               select new 
               { 
                   student.Name, 
                   Course = grade?.Course ?? "No courses" 
               };
```

### What is the difference between `Where().Select()` and `Select().Where()`?

Both produce the same final result, but they differ in **performance and efficiency**.

**`Where().Select()` - Filter First, Then Transform**
- **Better Performance**: Filters data before transformation
- **Fewer operations**: Only transforms elements that pass the filter
- **Recommended approach** in most cases

**`Select().Where()` - Transform First, Then Filter**
- **Worse Performance**: Transforms all elements before filtering
- **More operations**: Wastes resources on elements that will be filtered out
- **Useful only** when the transformation is needed for filtering logic

```csharp
var numbers = Enumerable.Range(1, 1000);

// WHERE THEN SELECT (Recommended)
var result1 = numbers
    .Where(n => n > 500)           // 1. Filter: 500 elements remain
    .Select(n => n * n);            // 2. Transform: 500 operations

// SELECT THEN WHERE (Less Efficient)
var result2 = numbers
    .Select(n => n * n)             // 1. Transform: 1000 operations
    .Where(n => n > 250000);        // 2. Filter: 500 elements remain

// Both produce the same result, but result1 performs half the transformations!
```

**Performance Comparison:**

```csharp
// Example with complex objects
var users = GetUsers(); // 10,000 users

// EFFICIENT: Filter first
var result1 = users
    .Where(u => u.Age > 18)                          // Filter 10,000 -> 6,000
    .Select(u => new UserDto                         // Transform 6,000 objects
    { 
        FullName = u.FirstName + " " + u.LastName,
        Email = u.Email 
    });

// INEFFICIENT: Select first
var result2 = users
    .Select(u => new UserDto                         // Transform 10,000 objects
    { 
        FullName = u.FirstName + " " + u.LastName,
        Email = u.Email 
    })
    .Where(dto => CalculateAge(dto) > 18);          // Filter 10,000 -> 6,000

// result1 creates 6,000 DTO objects
// result2 creates 10,000 DTO objects (4,000 wasted)
```

**When to Use Each:**

**Use `Where().Select()` when:**
- Filter condition uses original object properties
- You want to minimize transformations
- Performance matters (almost always)

```csharp
var activeUsers = users
    .Where(u => u.IsActive)
    .Select(u => u.Name);
```

**Use `Select().Where()` when:**
- Filter condition requires the transformed data
- The transformation is necessary for filtering logic

```csharp
var validEmails = users
    .Select(u => u.Email.Trim().ToLower())
    .Where(email => email.Contains("@company.com"));

// Or even better, combine them:
var validEmails = users
    .Where(u => u.Email != null)
    .Select(u => u.Email.Trim().ToLower())
    .Where(email => email.Contains("@company.com"));
```

**Rule of Thumb:**
Filter as early as possible in the LINQ chain to reduce the number of elements processed by subsequent operations.

```csharp
// BEST: Filter -> Filter -> Select
var result = items
    .Where(i => i.IsActive)         // First filter
    .Where(i => i.Price > 100)      // Second filter
    .Select(i => i.Name);            // Final transformation

// WORST: Select -> Where -> Where
var result = items
    .Select(i => new { i.Name, i.Price, i.IsActive })
    .Where(i => i.IsActive)
    .Where(i => i.Price > 100);
```
---

## Testing

### What is unit testing and why is it important?

**Unit testing** is the practice of testing individual units or components of code in isolation, typically at the function or method level. A unit test verifies that a specific piece of code behaves as expected under various conditions.

**Why it's important:**

- **Early Bug Detection**: Catches bugs early in development when they're cheaper to fix
- **Documentation**: Tests serve as living documentation showing how code should be used
- **Refactoring Confidence**: Enables safe refactoring by ensuring existing functionality isn't broken
- **Design Improvement**: Writing testable code often leads to better architecture and loose coupling
- **Regression Prevention**: Prevents old bugs from reappearing
- **Faster Development**: Though initial setup takes time, it speeds up long-term development
- **Quality Assurance**: Provides confidence that code works correctly

### Explain the AAA pattern (Arrange, Act, Assert)

The **AAA pattern** is a common structure for organizing unit tests, making them clear and consistent:

**1. Arrange**: Set up the test conditions
- Initialize objects
- Configure dependencies
- Set up test data and expected values

**2. Act**: Execute the code under test
- Call the method or function being tested
- Trigger the behavior you want to verify

**3. Assert**: Verify the results
- Check that the actual outcome matches expectations
- Verify state changes, return values, or method calls

**Example:**
```csharp
[Fact]
public void Withdraw_WithSufficientFunds_DecreasesBalance()
{
    // Arrange
    var account = new BankAccount(initialBalance: 100);
    var withdrawAmount = 30;
    
    // Act
    account.Withdraw(withdrawAmount);
    
    // Assert
    Assert.Equal(70, account.Balance);
}
```

### What is the difference between mocking, stubbing, and faking?

These are different types of test doubles used to isolate code during testing:

**Stubbing**:
- Provides predefined answers to method calls
- Used when you need to control what dependencies return
- Doesn't verify interactions
- Simple, passive replacement

```csharp
var userRepository = new Mock();
userRepository.Setup(x => x.GetById(1)).Returns(new User { Id = 1, Name = "John" });
```

**Mocking**:
- Records and verifies interactions with dependencies
- Used to verify that specific methods were called with expected parameters
- Active verification of behavior

```csharp
var emailService = new Mock();
// Act
service.SendWelcomeEmail(userId);
// Assert
emailService.Verify(x => x.Send(It.IsAny(), "Welcome!"), Times.Once);
```

**Faking**:
- Working implementation with shortcuts (not production-ready)
- More complex than stubs, simpler than real implementations
- Example: in-memory database instead of real SQL database

```csharp
public class FakeUserRepository : IUserRepository
{
    private List _users = new();
    
    public User GetById(int id) => _users.FirstOrDefault(u => u.Id == id);
    public void Add(User user) => _users.Add(user);
}
```

**Key Difference**: Stubs provide data, mocks verify behavior, fakes are simplified implementations.

### What testing frameworks have you used in .NET (xUnit, NUnit, MSTest)?

**xUnit.net** (Modern, Recommended):
- Most modern and actively maintained
- Used by .NET Core team
- No [SetUp]/[TearDown] attributes (uses constructors/IDisposable)
- Better parallelization support
- `[Fact]` for simple tests, `[Theory]` for parameterized tests

```csharp
public class CalculatorTests
{
    [Fact]
    public void Add_TwoNumbers_ReturnsSum()
    {
        var calculator = new Calculator();
        var result = calculator.Add(2, 3);
        Assert.Equal(5, result);
    }
    
    [Theory]
    [InlineData(2, 3, 5)]
    [InlineData(0, 0, 0)]
    [InlineData(-1, 1, 0)]
    public void Add_VariousInputs_ReturnsCorrectSum(int a, int b, int expected)
    {
        var calculator = new Calculator();
        Assert.Equal(expected, calculator.Add(a, b));
    }
}
```

**NUnit** (Mature, Feature-Rich):
- Oldest and most feature-rich
- Rich assertion library
- Supports parallel test execution
- `[Test]`, `[TestCase]` attributes

```csharp
[TestFixture]
public class CalculatorTests
{
    [Test]
    public void Add_TwoNumbers_ReturnsSum()
    {
        var calculator = new Calculator();
        var result = calculator.Add(2, 3);
        Assert.That(result, Is.EqualTo(5));
    }
    
    [TestCase(2, 3, 5)]
    [TestCase(0, 0, 0)]
    public void Add_VariousInputs_ReturnsCorrectSum(int a, int b, int expected)
    {
        var calculator = new Calculator();
        Assert.That(calculator.Add(a, b), Is.EqualTo(expected));
    }
}
```

**MSTest** (Microsoft's Framework):
- Built into Visual Studio
- Good integration with Microsoft tools
- Less popular in community
- `[TestMethod]`, `[DataRow]` attributes

```csharp
[TestClass]
public class CalculatorTests
{
    [TestMethod]
    public void Add_TwoNumbers_ReturnsSum()
    {
        var calculator = new Calculator();
        var result = calculator.Add(2, 3);
        Assert.AreEqual(5, result);
    }
}
```

**Personal Preference**: xUnit for new projects due to modern design and .NET team support.

### How do you write testable code?

**Principles for testable code:**

**1. Dependency Injection**:
- Inject dependencies rather than creating them internally
- Enables easy substitution with test doubles

```csharp
// Bad - Hard to test
public class OrderService
{
    public void ProcessOrder(Order order)
    {
        var repository = new OrderRepository(); // Hard-coded dependency
        repository.Save(order);
    }
}

// Good - Easy to test
public class OrderService
{
    private readonly IOrderRepository _repository;
    
    public OrderService(IOrderRepository repository)
    {
        _repository = repository;
    }
    
    public void ProcessOrder(Order order)
    {
        _repository.Save(order);
    }
}
```

**2. Single Responsibility Principle**:
- Each class/method should have one reason to change
- Smaller, focused units are easier to test

**3. Avoid Static Dependencies**:
- Static methods and classes are difficult to mock
- Use interfaces and instance methods

**4. Pure Functions When Possible**:
- Given the same input, always return the same output
- No side effects
- Easiest to test

**5. Separate Logic from Infrastructure**:
- Keep business logic separate from database, file system, network calls
- Makes logic testable without external dependencies

**6. Avoid Hidden Dependencies**:
- Make all dependencies explicit in constructor
- Don't use service locators or global state

**7. Keep Methods Small**:
- Easier to understand and test
- Single level of abstraction

**8. Use Interfaces**:
- Program to interfaces, not implementations
- Enables mocking and substitution

### What is TDD (Test-Driven Development)?

**Test-Driven Development** is a software development approach where tests are written before the actual code. It follows a cycle called **Red-Green-Refactor**:

**The TDD Cycle:**

1. **Red**: Write a failing test
   - Define what you want to achieve
   - Test fails because functionality doesn't exist yet

2. **Green**: Write minimal code to make the test pass
   - Focus on making it work, not perfect
   - Get to green as quickly as possible

3. **Refactor**: Improve the code
   - Clean up implementation
   - Remove duplication
   - Tests ensure behavior is preserved

**Example TDD Process:**

```csharp
// Step 1: RED - Write failing test
[Fact]
public void Deposit_PositiveAmount_IncreasesBalance()
{
    var account = new BankAccount(100);
    account.Deposit(50);
    Assert.Equal(150, account.Balance);
}

// Step 2: GREEN - Make it pass (minimal code)
public class BankAccount
{
    public decimal Balance { get; private set; }
    
    public BankAccount(decimal initialBalance)
    {
        Balance = initialBalance;
    }
    
    public void Deposit(decimal amount)
    {
        Balance += amount;
    }
}

// Step 3: REFACTOR - Improve (add validation)
public void Deposit(decimal amount)
{
    if (amount <= 0)
        throw new ArgumentException("Amount must be positive");
    
    Balance += amount;
}
```

**Benefits of TDD:**
- Better design (code is inherently testable)
- Comprehensive test coverage
- Less debugging time
- Documentation through tests
- Confidence in refactoring
- Focus on requirements

**Challenges:**
- Initial learning curve
- Slower initial development
- Requires discipline
- Not suitable for all scenarios (e.g., UI, exploratory work)

### Explain integration testing vs unit testing

**Unit Testing**:
- Tests individual components in isolation
- Fast execution (milliseconds)
- No external dependencies
- Uses mocks/stubs for dependencies
- Runs frequently (every build)
- Large number of tests
- Focuses on single method/class behavior

```csharp
[Fact]
public void CalculateDiscount_PremiumCustomer_Returns20Percent()
{
    var calculator = new DiscountCalculator();
    var result = calculator.Calculate(100, CustomerType.Premium);
    Assert.Equal(20, result);
}
```

**Integration Testing**:
- Tests how components work together
- Slower execution (seconds to minutes)
- Uses real dependencies (database, APIs, file system)
- Tests interactions between modules
- Runs less frequently (pre-commit, CI/CD)
- Fewer tests than unit tests
- Focuses on component collaboration

```csharp
[Fact]
public async Task CreateOrder_ValidData_SavesToDatabase()
{
    // Uses real database (or test database)
    var dbContext = new OrderContext(connectionString);
    var repository = new OrderRepository(dbContext);
    var service = new OrderService(repository);
    
    var order = new Order { CustomerId = 1, Total = 100 };
    await service.CreateOrder(order);
    
    var saved = await dbContext.Orders.FindAsync(order.Id);
    Assert.NotNull(saved);
    Assert.Equal(100, saved.Total);
}
```

**Comparison Table**:

| Aspect | Unit Testing | Integration Testing |
|--------|-------------|---------------------|
| Scope | Single unit | Multiple components |
| Speed | Very fast | Slower |
| Dependencies | Mocked | Real |
| Isolation | Complete | Partial |
| Quantity | Hundreds/Thousands | Dozens/Hundreds |
| Complexity | Simple | Complex |
| Maintenance | Easy | More difficult |
| When to Run | Every build | CI/CD pipeline |

**Best Practice**: Use both! Follow the testing pyramid:
- 70% Unit Tests (base)
- 20% Integration Tests (middle)
- 10% E2E/UI Tests (top)

### What is code coverage and what is a good coverage percentage?

**Code Coverage** is a metric that measures the percentage of code executed during automated tests. It shows which parts of your codebase are tested and which aren't.

**Types of Coverage:**

**1. Line Coverage**: Percentage of code lines executed
**2. Branch Coverage**: Percentage of decision branches taken (if/else, switch)
**3. Method Coverage**: Percentage of methods called
**4. Statement Coverage**: Percentage of statements executed

**Example:**
```csharp
public int Divide(int a, int b)
{
    if (b == 0)  // Branch 1
        throw new DivideByZeroException();
    
    return a / b;  // Branch 2
}

// Test only happy path = 50% branch coverage
[Fact]
public void Divide_ValidNumbers_ReturnsQuotient()
{
    var result = calculator.Divide(10, 2);
    Assert.Equal(5, result);
}

// Test both branches = 100% branch coverage
[Fact]
public void Divide_ByZero_ThrowsException()
{
    Assert.Throws(() => calculator.Divide(10, 0));
}
```

**What is a "good" coverage percentage?**

**The Nuanced Answer**: There's no magic number, but context matters:

- **80-90%** is often cited as a good target
- **100%** is usually unrealistic and unnecessary
- **Below 70%** suggests insufficient testing

**Important Considerations:**

**Coverage doesn't equal quality**:
- 100% coverage doesn't mean bug-free code
- You can have high coverage with poor assertions
- Focus on meaningful tests, not just coverage numbers

```csharp
// Bad: 100% coverage, but useless test
[Fact]
public void Add_TwoNumbers_DoesNotThrow()
{
    var result = calculator.Add(2, 3);
    // No assertion! But technically covers the line
}

// Good: Lower coverage, but actually validates behavior
[Fact]
public void Add_TwoNumbers_ReturnsCorrectSum()
{
    var result = calculator.Add(2, 3);
    Assert.Equal(5, result);
}
```

**What to focus on**:
- Critical business logic: Aim for 90%+
- Complex algorithms: High coverage essential
- Simple getters/setters: Don't obsess over coverage
- Generated code: Often excluded from coverage
- Configuration code: Lower priority

**Better metrics to combine with coverage**:
- Mutation testing (tests' ability to catch bugs)
- Code review quality
- Defect rates in production
- Test execution time

**Tools for .NET**:
- Coverlet
- dotCover (JetBrains)
- NCover
- Visual Studio Code Coverage

**Conclusion**: Aim for 80%+ coverage, but prioritize **meaningful tests** over hitting a number. High coverage with poor tests is worse than moderate coverage with excellent tests.

---

## Microservices and Architecture

### What are microservices and what are their advantages and disadvantages?

**Microservices** are an architectural style where an application is built as a collection of small, independent services that communicate over network protocols. Each service is self-contained, focuses on a specific business capability, and can be deployed independently.

**Advantages:**
- **Independent Deployment**: Services can be deployed without affecting others
- **Technology Flexibility**: Each service can use different tech stacks
- **Scalability**: Scale individual services based on demand
- **Fault Isolation**: Failures in one service don't crash the entire system
- **Team Autonomy**: Small teams can own and develop services independently
- **Faster Development**: Parallel development across multiple teams

**Disadvantages:**
- **Complexity**: Distributed systems are inherently complex
- **Network Latency**: Inter-service communication overhead
- **Data Consistency**: Maintaining consistency across services is challenging
- **Testing Difficulty**: End-to-end testing becomes more complex
- **Operational Overhead**: More services to monitor, deploy, and maintain
- **Distributed Transactions**: Harder to implement ACID transactions

**Example in .NET Core:**
```csharp
// Product Service
public class ProductService
{
    private readonly IHttpClientFactory _httpClientFactory;
    
    public async Task GetProductWithInventory(int productId)
    {
        var product = await _productRepository.GetByIdAsync(productId);
        
        // Call inventory microservice
        var client = _httpClientFactory.CreateClient("InventoryService");
        var inventory = await client.GetFromJsonAsync($"/api/inventory/{productId}");
        
        product.StockLevel = inventory.Quantity;
        return product;
    }
}
```

---

### Explain the difference between monolithic and microservices architecture.

**Monolithic Architecture:**
- Single, unified codebase and deployment unit
- All components tightly coupled within one application
- Shared database for all modules
- Scaling requires scaling the entire application
- Simple deployment but limited flexibility

**Microservices Architecture:**
- Multiple independent services
- Loosely coupled with clear boundaries
- Each service has its own database (database per service pattern)
- Individual services can be scaled independently
- Complex deployment but high flexibility

**Comparison Table:**

| Aspect | Monolithic | Microservices |
|--------|-----------|---------------|
| Deployment | Single unit | Multiple independent services |
| Database | Shared database | Database per service |
| Scaling | Vertical (entire app) | Horizontal (per service) |
| Technology | Single stack | Polyglot architecture |
| Development | Simple initially | Complex from start |
| Team Structure | Single large team | Multiple small teams |

**Monolithic Example (.NET Core):**
```csharp
// All in one application
public class Startup
{
    public void ConfigureServices(IServiceCollection services)
    {
        services.AddScoped();
        services.AddScoped();
        services.AddScoped();
        services.AddScoped();
        // All services in one application
    }
}
```

**Microservices Example (.NET Core):**
```csharp
// Product Service - Separate application
public class ProductServiceStartup
{
    public void ConfigureServices(IServiceCollection services)
    {
        services.AddScoped();
    }
}

// Order Service - Separate application
public class OrderServiceStartup
{
    public void ConfigureServices(IServiceCollection services)
    {
        services.AddScoped();
        services.AddHttpClient("ProductService", c => 
            c.BaseAddress = new Uri("http://product-service"));
    }
}
```

---

### What is API Gateway pattern?

The **API Gateway pattern** provides a single entry point for all clients to access microservices. It acts as a reverse proxy, routing requests to appropriate microservices and aggregating responses.

**Key Responsibilities:**
- Request routing and composition
- Authentication and authorization
- Rate limiting and throttling
- Load balancing
- Protocol translation
- Response aggregation
- Caching

**Implementation with Ocelot in .NET Core:**

```csharp
// Install: Install-Package Ocelot

// ocelot.json configuration
{
  "Routes": [
    {
      "DownstreamPathTemplate": "/api/products/{everything}",
      "DownstreamScheme": "http",
      "DownstreamHostAndPorts": [
        {
          "Host": "product-service",
          "Port": 5001
        }
      ],
      "UpstreamPathTemplate": "/products/{everything}",
      "UpstreamHttpMethod": [ "Get", "Post", "Put", "Delete" ]
    },
    {
      "DownstreamPathTemplate": "/api/orders/{everything}",
      "DownstreamScheme": "http",
      "DownstreamHostAndPorts": [
        {
          "Host": "order-service",
          "Port": 5002
        }
      ],
      "UpstreamPathTemplate": "/orders/{everything}",
      "UpstreamHttpMethod": [ "Get", "Post" ],
      "AuthenticationOptions": {
        "AuthenticationProviderKey": "Bearer"
      }
    }
  ],
  "GlobalConfiguration": {
    "BaseUrl": "http://localhost:5000"
  }
}

// Program.cs
public class Program
{
    public static void Main(string[] args)
    {
        var builder = WebApplication.CreateBuilder(args);
        
        builder.Configuration.AddJsonFile("ocelot.json", optional: false, reloadOnChange: true);
        builder.Services.AddOcelot(builder.Configuration);
        
        var app = builder.Build();
        app.UseOcelot().Wait();
        app.Run();
    }
}
```

**Custom API Gateway:**
```csharp
[ApiController]
[Route("api/gateway")]
public class ApiGatewayController : ControllerBase
{
    private readonly IHttpClientFactory _httpClientFactory;
    
    public ApiGatewayController(IHttpClientFactory httpClientFactory)
    {
        _httpClientFactory = httpClientFactory;
    }
    
    [HttpGet("product/{id}/details")]
    public async Task GetProductDetails(int id)
    {
        var productClient = _httpClientFactory.CreateClient("ProductService");
        var inventoryClient = _httpClientFactory.CreateClient("InventoryService");
        var reviewClient = _httpClientFactory.CreateClient("ReviewService");
        
        // Aggregate responses from multiple services
        var productTask = productClient.GetFromJsonAsync($"/api/products/{id}");
        var inventoryTask = inventoryClient.GetFromJsonAsync($"/api/inventory/{id}");
        var reviewsTask = reviewClient.GetFromJsonAsync<List>($"/api/reviews/product/{id}");
        
        await Task.WhenAll(productTask, inventoryTask, reviewsTask);
        
        return Ok(new {
            Product = productTask.Result,
            Inventory = inventoryTask.Result,
            Reviews = reviewsTask.Result
        });
    }
}
```

---

### How do you handle inter-service communication in microservices?

Inter-service communication can be **synchronous** or **asynchronous**.

**Synchronous Communication (Request/Response):**

**1. HTTP/REST with HttpClient:**
```csharp
// Startup.cs
services.AddHttpClient("OrderService", c =>
{
    c.BaseAddress = new Uri("http://order-service:5000");
    c.DefaultRequestHeaders.Add("Accept", "application/json");
});

// Service implementation
public class ProductService
{
    private readonly IHttpClientFactory _httpClientFactory;
    
    public ProductService(IHttpClientFactory httpClientFactory)
    {
        _httpClientFactory = httpClientFactory;
    }
    
    public async Task CheckOrderStatus(int orderId)
    {
        var client = _httpClientFactory.CreateClient("OrderService");
        var response = await client.GetAsync($"/api/orders/{orderId}/status");
        response.EnsureSuccessStatusCode();
        return await response.Content.ReadFromJsonAsync();
    }
}
```

**2. gRPC (High-performance RPC):**
```protobuf
// order.proto
syntax = "proto3";

service OrderService {
  rpc GetOrder (OrderRequest) returns (OrderResponse);
  rpc CreateOrder (CreateOrderRequest) returns (OrderResponse);
}

message OrderRequest {
  int32 order_id = 1;
}

message OrderResponse {
  int32 order_id = 1;
  string status = 2;
  double total = 3;
}
```

```csharp
// gRPC Server
public class OrderServiceImpl : OrderService.OrderServiceBase
{
    public override async Task GetOrder(OrderRequest request, ServerCallContext context)
    {
        var order = await _orderRepository.GetByIdAsync(request.OrderId);
        return new OrderResponse
        {
            OrderId = order.Id,
            Status = order.Status,
            Total = order.Total
        };
    }
}

// gRPC Client
public class ProductService
{
    private readonly OrderService.OrderServiceClient _orderClient;
    
    public async Task GetOrderDetails(int orderId)
    {
        var request = new OrderRequest { OrderId = orderId };
        return await _orderClient.GetOrderAsync(request);
    }
}
```

**Asynchronous Communication (Message-based):**

**1. RabbitMQ:**
```csharp
// Install: Install-Package RabbitMQ.Client

// Message Publisher
public class OrderCreatedPublisher
{
    private readonly IConnection _connection;
    
    public void PublishOrderCreated(OrderCreatedEvent orderEvent)
    {
        using var channel = _connection.CreateModel();
        
        channel.ExchangeDeclare("orders", ExchangeType.Topic, durable: true);
        
        var message = JsonSerializer.Serialize(orderEvent);
        var body = Encoding.UTF8.GetBytes(message);
        
        channel.BasicPublish(
            exchange: "orders",
            routingKey: "order.created",
            basicProperties: null,
            body: body);
    }
}

// Message Consumer
public class InventoryService : BackgroundService
{
    protected override Task ExecuteAsync(CancellationToken stoppingToken)
    {
        var channel = _connection.CreateModel();
        channel.QueueDeclare("inventory-queue", durable: true, exclusive: false);
        channel.QueueBind("inventory-queue", "orders", "order.created");
        
        var consumer = new EventingBasicConsumer(channel);
        consumer.Received += (model, ea) =>
        {
            var body = ea.Body.ToArray();
            var message = Encoding.UTF8.GetString(body);
            var orderEvent = JsonSerializer.Deserialize(message);
            
            // Process the order
            ProcessOrder(orderEvent);
        };
        
        channel.BasicConsume("inventory-queue", autoAck: true, consumer);
        return Task.CompletedTask;
    }
}
```

**2. Azure Service Bus:**
```csharp
// Install: Install-Package Azure.Messaging.ServiceBus

public class ServiceBusPublisher
{
    private readonly ServiceBusClient _client;
    private readonly ServiceBusSender _sender;
    
    public async Task PublishAsync(T message)
    {
        var messageBody = JsonSerializer.Serialize(message);
        var serviceBusMessage = new ServiceBusMessage(messageBody);
        await _sender.SendMessageAsync(serviceBusMessage);
    }
}

public class ServiceBusConsumer : BackgroundService
{
    private readonly ServiceBusProcessor _processor;
    
    protected override async Task ExecuteAsync(CancellationToken stoppingToken)
    {
        _processor.ProcessMessageAsync += MessageHandler;
        _processor.ProcessErrorAsync += ErrorHandler;
        
        await _processor.StartProcessingAsync(stoppingToken);
    }
    
    private async Task MessageHandler(ProcessMessageEventArgs args)
    {
        var body = args.Message.Body.ToString();
        var order = JsonSerializer.Deserialize(body);
        
        // Process message
        await ProcessOrderAsync(order);
        await args.CompleteMessageAsync(args.Message);
    }
}
```

---

### What is the Circuit Breaker pattern?

The **Circuit Breaker pattern** prevents an application from repeatedly trying to execute an operation that's likely to fail, allowing it to continue without waiting for the fault to be fixed or wasting CPU cycles.

**States:**
- **Closed**: Requests flow normally, failures are counted
- **Open**: Requests fail immediately without attempting the call
- **Half-Open**: Limited requests are allowed to test if the issue is resolved

**Implementation with Polly:**

```csharp
// Install: Install-Package Polly
// Install: Install-Package Microsoft.Extensions.Http.Polly

// Startup.cs
public void ConfigureServices(IServiceCollection services)
{
    services.AddHttpClient("OrderService", c =>
    {
        c.BaseAddress = new Uri("http://order-service:5000");
    })
    .AddPolicyHandler(GetCircuitBreakerPolicy())
    .AddPolicyHandler(GetRetryPolicy());
}

private IAsyncPolicy GetCircuitBreakerPolicy()
{
    return HttpPolicyExtensions
        .HandleTransientHttpError()
        .CircuitBreakerAsync(
            handledEventsAllowedBeforeBreaking: 3,
            durationOfBreak: TimeSpan.FromSeconds(30),
            onBreak: (result, timespan) =>
            {
                // Log circuit breaker opened
                Console.WriteLine($"Circuit breaker opened for {timespan.TotalSeconds}s");
            },
            onReset: () =>
            {
                // Log circuit breaker reset
                Console.WriteLine("Circuit breaker reset");
            },
            onHalfOpen: () =>
            {
                // Log circuit breaker half-open
                Console.WriteLine("Circuit breaker half-open");
            });
}

private IAsyncPolicy GetRetryPolicy()
{
    return HttpPolicyExtensions
        .HandleTransientHttpError()
        .WaitAndRetryAsync(
            retryCount: 3,
            sleepDurationProvider: retryAttempt => TimeSpan.FromSeconds(Math.Pow(2, retryAttempt)),
            onRetry: (outcome, timespan, retryCount, context) =>
            {
                Console.WriteLine($"Retry {retryCount} after {timespan.TotalSeconds}s");
            });
}
```

**Custom Circuit Breaker:**
```csharp
public class CircuitBreaker
{
    private readonly int _threshold;
    private readonly TimeSpan _timeout;
    private int _failureCount;
    private DateTime _lastFailureTime;
    private CircuitBreakerState _state = CircuitBreakerState.Closed;
    
    public async Task ExecuteAsync(Func<Task> operation)
    {
        if (_state == CircuitBreakerState.Open)
        {
            if (DateTime.UtcNow - _lastFailureTime > _timeout)
            {
                _state = CircuitBreakerState.HalfOpen;
            }
            else
            {
                throw new CircuitBreakerOpenException();
            }
        }
        
        try
        {
            var result = await operation();
            
            if (_state == CircuitBreakerState.HalfOpen)
            {
                _state = CircuitBreakerState.Closed;
                _failureCount = 0;
            }
            
            return result;
        }
        catch (Exception)
        {
            _failureCount++;
            _lastFailureTime = DateTime.UtcNow;
            
            if (_failureCount >= _threshold)
            {
                _state = CircuitBreakerState.Open;
            }
            
            throw;
        }
    }
}

public enum CircuitBreakerState
{
    Closed,
    Open,
    HalfOpen
}
```

---

### Explain eventual consistency in distributed systems.

**Eventual Consistency** means that if no new updates are made to a data item, eventually all accesses to that item will return the last updated value. Unlike strong consistency, there may be a temporary period where different nodes have different versions of the data.

**Key Concepts:**
- Data updates propagate asynchronously across services
- Temporary inconsistencies are acceptable
- System favors availability over immediate consistency (CAP theorem)
- Eventually, all replicas converge to the same state

**Example Scenario:**

```csharp
// Order Service - Creates order immediately
[HttpPost]
public async Task CreateOrder(CreateOrderRequest request)
{
    var order = new Order
    {
        CustomerId = request.CustomerId,
        Status = OrderStatus.Pending,
        Total = request.Total
    };
    
    await _orderRepository.AddAsync(order);
    
    // Publish event - asynchronous
    await _messageBus.PublishAsync(new OrderCreatedEvent
    {
        OrderId = order.Id,
        CustomerId = order.CustomerId,
        Items = request.Items
    });
    
    return Ok(order); // Returns immediately, other services update eventually
}

// Inventory Service - Updates stock eventually
public class OrderCreatedHandler : IEventHandler
{
    public async Task Handle(OrderCreatedEvent @event)
    {
        // This happens eventually, not immediately
        foreach (var item in @event.Items)
        {
            await _inventoryRepository.DecreaseStockAsync(item.ProductId, item.Quantity);
        }
    }
}

// Notification Service - Sends email eventually
public class OrderCreatedNotificationHandler : IEventHandler
{
    public async Task Handle(OrderCreatedEvent @event)
    {
        // This also happens eventually
        var customer = await _customerRepository.GetByIdAsync(@event.CustomerId);
        await _emailService.SendOrderConfirmationAsync(customer.Email, @event.OrderId);
    }
}
```

**Handling Eventual Consistency:**

```csharp
// 1. Optimistic UI Updates
public class OrderViewModel
{
    public int OrderId { get; set; }
    public string Status { get; set; }
    public bool IsSyncing { get; set; } // Shows data is still being synchronized
}

// 2. Compensating Actions
public class OrderCompensationService
{
    public async Task CompensateFailedOrder(int orderId)
    {
        // If inventory update fails, compensate by canceling the order
        await _orderRepository.UpdateStatusAsync(orderId, OrderStatus.Cancelled);
        await _messageBus.PublishAsync(new OrderCancelledEvent { OrderId = orderId });
    }
}

// 3. Read Your Own Writes
public class OrderService
{
    private readonly IMemoryCache _cache;
    
    public async Task GetOrderAsync(int orderId, int userId)
    {
        // Check cache first for recently created orders
        if (_cache.TryGetValue($"order:{orderId}:{userId}", out Order cachedOrder))
        {
            return cachedOrder;
        }
        
        return await _orderRepository.GetByIdAsync(orderId);
    }
    
    public async Task CreateOrderAsync(CreateOrderRequest request)
    {
        var order = await _orderRepository.AddAsync(new Order { /* ... */ });
        
        // Cache for immediate read
        _cache.Set($"order:{order.Id}:{request.UserId}", order, TimeSpan.FromMinutes(5));
        
        return order;
    }
}

// 4. Version Vectors/Timestamps
public class EventEnvelope
{
    public T Event { get; set; }
    public long Timestamp { get; set; }
    public string EventId { get; set; }
    public int Version { get; set; }
}

public class EventProcessor
{
    private long _lastProcessedTimestamp;
    
    public async Task ProcessEvent(EventEnvelope envelope)
    {
        // Ignore out-of-order events
        if (envelope.Timestamp <= _lastProcessedTimestamp)
        {
            return;
        }
        
        await HandleEvent(envelope.Event);
        _lastProcessedTimestamp = envelope.Timestamp;
    }
}
```

---

### What is the Saga pattern for distributed transactions?

The **Saga pattern** manages data consistency across microservices in distributed transactions by breaking the transaction into a series of local transactions, each with a compensating transaction to undo changes if something fails.

**Two Types:**

**1. Choreography-based Saga** (Event-driven):
```csharp
// Order Service
public class OrderService
{
    public async Task CreateOrder(CreateOrderRequest request)
    {
        var order = new Order { Status = OrderStatus.Pending };
        await _repository.AddAsync(order);
        
        // Publish event to start saga
        await _eventBus.PublishAsync(new OrderCreatedEvent
        {
            OrderId = order.Id,
            CustomerId = request.CustomerId,
            Items = request.Items,
            Total = request.Total
        });
        
        return order;
    }
    
    // Compensating transaction
    public async Task CancelOrder(OrderCancelledEvent @event)
    {
        await _repository.UpdateStatusAsync(@event.OrderId, OrderStatus.Cancelled);
    }
}

// Inventory Service
public class InventoryEventHandler
{
    public async Task Handle(OrderCreatedEvent @event)
    {
        try
        {
            // Reserve inventory
            await _inventoryService.ReserveItemsAsync(@event.Items);
            
            // Publish success event
            await _eventBus.PublishAsync(new InventoryReservedEvent
            {
                OrderId = @event.OrderId,
                Items = @event.Items
            });
        }
        catch (InsufficientStockException)
        {
            // Publish failure event
            await _eventBus.PublishAsync(new InventoryReservationFailedEvent
            {
                OrderId = @event.OrderId
            });
        }
    }
    
    // Compensating transaction
    public async Task Handle(OrderCancelledEvent @event)
    {
        await _inventoryService.ReleaseReservationAsync(@event.OrderId);
    }
}

// Payment Service
public class PaymentEventHandler
{
    public async Task Handle(InventoryReservedEvent @event)
    {
        try
        {
            await _paymentService.ProcessPaymentAsync(@event.OrderId);
            
            await _eventBus.PublishAsync(new PaymentProcessedEvent
            {
                OrderId = @event.OrderId
            });
        }
        catch (PaymentFailedException)
        {
            // Trigger compensation
            await _eventBus.PublishAsync(new PaymentFailedEvent
            {
                OrderId = @event.OrderId
            });
        }
    }
    
    // Compensating transaction
    public async Task Handle(OrderCancelledEvent @event)
    {
        await _paymentService.RefundAsync(@event.OrderId);
    }
}
```

**2. Orchestration-based Saga** (Centralized coordinator):
```csharp
// Saga Orchestrator
public class OrderSagaOrchestrator
{
    private readonly IOrderService _orderService;
    private readonly IInventoryService _inventoryService;
    private readonly IPaymentService _paymentService;
    
    public async Task ExecuteOrderSaga(CreateOrderRequest request)
    {
        var sagaState = new SagaState();
        
        try
        {
            // Step 1: Create Order
            var order = await _orderService.CreateOrderAsync(request);
            sagaState.OrderId = order.Id;
            sagaState.CompletedSteps.Add(SagaStep.OrderCreated);
            
            // Step 2: Reserve Inventory
            await _inventoryService.ReserveItemsAsync(order.Id, request.Items);
            sagaState.CompletedSteps.Add(SagaStep.InventoryReserved);
            
            // Step 3: Process Payment
            await _paymentService.ProcessPaymentAsync(order.Id, request.Total);
            sagaState.CompletedSteps.Add(SagaStep.PaymentProcessed);
            
            // Step 4: Confirm Order
            await _orderService.ConfirmOrderAsync(order.Id);
            
            return SagaResult.Success(order.Id);
        }
        catch (Exception ex)
        {
            // Compensate in reverse order
            await CompensateAsync(sagaState);
            return SagaResult.Failure(ex.Message);
        }
    }
    
    private async Task CompensateAsync(SagaState state)
    {
        if (state.CompletedSteps.Contains(SagaStep.PaymentProcessed))
        {
            await _paymentService.RefundAsync(state.OrderId);
        }
        
        if (state.CompletedSteps.Contains(SagaStep.InventoryReserved))
        {
            await _inventoryService.ReleaseReservationAsync(state.OrderId);
        }
        
        if (state.CompletedSteps.Contains(SagaStep.OrderCreated))
        {
            await _orderService.CancelOrderAsync(state.OrderId);
        }
    }
}

// Saga State Management
public class SagaState
{
    public int OrderId { get; set; }
    public List CompletedSteps { get; set; } = new();
}

public enum SagaStep
{
    OrderCreated,
    InventoryReserved,
    PaymentProcessed
}

// Using MassTransit for Saga Orchestration
public class OrderStateMachine : MassTransitStateMachine
{
    public OrderStateMachine()
    {
        InstanceState(x => x.CurrentState);
        
        Event(() => OrderCreated);
        Event(() => InventoryReserved);
        Event(() => PaymentProcessed);
        
        Initially(
            When(OrderCreated)
                .Then(context => context.Instance.OrderId = context.Data.OrderId)
                .TransitionTo(AwaitingInventory)
                .Publish(context => new ReserveInventoryCommand(context.Data.OrderId)));
        
        During(AwaitingInventory,
            When(InventoryReserved)
                .TransitionTo(AwaitingPayment)
                .Publish(context => new ProcessPaymentCommand(context.Data.OrderId)));
        
        During(AwaitingPayment,
            When(PaymentProcessed)
                .TransitionTo(Completed)
                .Publish(context => new OrderCompletedEvent(context.Data.OrderId)));
    }
    
    public State AwaitingInventory { get; private set; }
    public State AwaitingPayment { get; private set; }
    public State Completed { get; private set; }
    
    public Event OrderCreated { get; private set; }
    public Event InventoryReserved { get; private set; }
    public Event PaymentProcessed { get; private set; }
}
```

---

### How do you implement service discovery?

**Service Discovery** allows services to find and communicate with each other without hard-coding network locations. Services register themselves and discover other services dynamically.

**1. Client-Side Discovery with Consul:**

```csharp
// Install: Install-Package Consul

// Service Registration
public class ConsulServiceRegistration : IHostedService
{
    private readonly IConsulClient _consulClient;
    private readonly IConfiguration _configuration;
    private string _registrationId;
    
    public async Task StartAsync(CancellationToken cancellationToken)
    {
        var serviceName = _configuration["ServiceName"];
        var serviceId = $"{serviceName}-{Guid.NewGuid()}";
        
        var registration = new AgentServiceRegistration
        {
            ID = serviceId,
            Name = serviceName,
            Address = _configuration["ServiceAddress"],
            Port = int.Parse(_configuration["ServicePort"]),
            Check = new AgentServiceCheck
            {
                HTTP = $"http://{_configuration["ServiceAddress"]}:{_configuration["ServicePort"]}/health",
                Interval = TimeSpan.FromSeconds(10),
                Timeout = TimeSpan.FromSeconds(5)
            }
        };
        
        await _consulClient.Agent.ServiceDeregister(serviceId, cancellationToken);
        await _consulClient.Agent.ServiceRegister(registration, cancellationToken);
        
        _registrationId = serviceId;
    }
    
    public async Task StopAsync(CancellationToken cancellationToken)
    {
        await _consulClient.Agent.ServiceDeregister(_registrationId, cancellationToken);
    }
}

// Service Discovery
public class ConsulServiceDiscovery
{
    private readonly IConsulClient _consulClient;
    
    public async Task GetServiceUriAsync(string serviceName)
    {
        var services = await _consulClient.Health.Service(serviceName, tag: null, passingOnly: true);
        
        if (!services.Response.Any())
        {
            throw new Exception($"Service {serviceName} not found");
        }
        
        // Simple round-robin
        var service = services.Response[Random.Shared.Next(services.Response.Length)];
        
        return new Uri($"http://{service.Service.Address}:{service.Service.Port}");
    }
}

// Usage in HttpClient
public class OrderServiceClient
{
    private readonly IHttpClientFactory _httpClientFactory;
    private readonly ConsulServiceDiscovery _serviceDiscovery;
    
    public async Task GetOrderAsync(int orderId)
    {
        var serviceUri = await _serviceDiscovery.GetServiceUriAsync("order-service");
        var client = _httpClientFactory.CreateClient();
        client.BaseAddress = serviceUri;
        
        return await client.GetFromJsonAsync($"/api/orders/{orderId}");
    }
}

// Startup.cs
public void ConfigureServices(IServiceCollection services)
{
    services.AddSingleton(p => new ConsulClient(config =>
    {
        config.Address = new Uri("http://consul:8500");
    }));
    
    services.AddSingleton();
    services.AddHostedService();
}
```

**2. Server-Side Discovery with Kubernetes:**

```yaml
# Kubernetes Service Definition
apiVersion: v1
kind: Service
metadata:
  name: order-service
spec:
  selector:
    app: order-service
  ports:
    - protocol: TCP
      port: 80
      targetPort: 5000
  type: ClusterIP
```

```csharp
// In .NET Core, services discover each other via Kubernetes DNS
public void ConfigureServices(IServiceCollection services)
{
    services.AddHttpClient("OrderService", c =>
    {
        // Kubernetes DNS: ..svc.cluster.local
        c.BaseAddress = new Uri("http://order-service.default.svc.cluster.local");
    });
}
```

**3. Using Eureka (Netflix OSS):**

```csharp
// Install: Install-Package Steeltoe.Discovery.Eureka

// appsettings.json
{
  "spring": {
    "application": {
      "name": "product-service"
    }
  },
  "eureka": {
    "client": {
      "serviceUrl": "http://eureka-server:8761/eureka/",
      "shouldRegisterWithEureka": true,
      "shouldFetchRegistry": true
    },
    "instance": {
      "port": 5000,
      "preferIpAddress": true,
      "healthCheckUrlPath": "/health"
    }
  }
}

// Program.cs
public class Program
{
    public static void Main(string[] args)
    {
        var builder = WebApplication.CreateBuilder(args);
        
        builder.Services.AddDiscoveryClient(builder.Configuration);
        builder.Services.AddHttpClient();
        
        var app = builder.Build();
        app.Run();
    }
}

// Service Client with Discovery
public class ProductServiceClient
{
    private readonly IDiscoveryClient _discoveryClient;
    private readonly IHttpClientFactory _httpClientFactory;
    
    public ProductServiceClient(IDiscoveryClient discoveryClient, IHttpClientFactory httpClientFactory)
    {
        _discoveryClient = discoveryClient;
        _httpClientFactory = httpClientFactory;
    }
    
    public async Task GetProductAsync(int productId)
    {
        var instances = await _discoveryClient.GetInstancesAsync("product-service");
        var instance = instances.FirstOrDefault();
        
        if (instance == null)
            throw new Exception("No instances of product-service available");
        
        var client = _httpClientFactory.CreateClient();
        var uri = new Uri($"{instance.Uri}/api/products/{productId}");
        
        return await client.GetFromJsonAsync(uri);
    }
}
```

**4. Custom Service Registry:**

```csharp
// Simple in-memory service registry
public interface IServiceRegistry
{
    Task RegisterServiceAsync(ServiceRegistration registration);
    Task DeregisterServiceAsync(string serviceId);
    Task<List> DiscoverServiceAsync(string serviceName);
}

public class InMemoryServiceRegistry : IServiceRegistry
{
    private readonly ConcurrentDictionary _services = new();
    
    public Task RegisterServiceAsync(ServiceRegistration registration)
    {
        _services[registration.ServiceId] = registration;
        return Task.CompletedTask;
    }
    
    public Task DeregisterServiceAsync(string serviceId)
    {
        _services.TryRemove(serviceId, out _);
        return Task.CompletedTask;
    }
    
    public Task<List> DiscoverServiceAsync(string serviceName)
    {
        var instances = _services.Values
            .Where(s => s.ServiceName == serviceName && s.IsHealthy)
            .Select(s => new ServiceInstance
            {
                ServiceId = s.ServiceId,
                Host = s.Host,
                Port = s.Port
            })
            .ToList();
        
        return Task.FromResult(instances);
    }
}

public class ServiceRegistration
{
    public string ServiceId { get; set; }
    public string ServiceName { get; set; }
    public string Host { get; set; }
    public int Port { get; set; }
    public bool IsHealthy { get; set; }
    public DateTime LastHeartbeat { get; set; }
}
```

---

### What are containers and how do they relate to microservices?

**Containers** are lightweight, standalone packages that include application code, runtime, libraries, and dependencies needed to run the application. They provide isolation and consistency across different environments.

**Why Containers for Microservices:**
- **Isolation**: Each microservice runs in its own container
- **Portability**: Run anywhere (dev, test, production)
- **Scalability**: Easy to scale individual services
- **Consistency**: Same environment across all stages
- **Resource Efficiency**: Lighter than virtual machines
- **Fast Deployment**: Quick startup and shutdown

**Docker for .NET Core:**

**1. Dockerfile for .NET Core Service:**

```dockerfile
# Build stage
FROM mcr.microsoft.com/dotnet/sdk:8.0 AS build
WORKDIR /src

# Copy csproj and restore dependencies
COPY ["ProductService/ProductService.csproj", "ProductService/"]
RUN dotnet restore "ProductService/ProductService.csproj"

# Copy source code and build
COPY . .
WORKDIR "/src/ProductService"
RUN dotnet build "ProductService.csproj" -c Release -o /app/build

# Publish stage
FROM build AS publish
RUN dotnet publish "ProductService.csproj" -c Release -o /app/publish

# Runtime stage
FROM mcr.microsoft.com/dotnet/aspnet:8.0 AS final
WORKDIR /app
COPY --from=publish /app/publish .

# Configure environment
ENV ASPNETCORE_URLS=http://+:80
EXPOSE 80

ENTRYPOINT ["dotnet", "ProductService.dll"]
```

**2. Docker Compose for Multiple Services:**

```yaml
# docker-compose.yml
version: '3.8'

services:
  # API Gateway
  api-gateway:
    build:
      context: ./ApiGateway
      dockerfile: Dockerfile
    ports:
      - "5000:80"
    environment:
      - ASPNETCORE_ENVIRONMENT=Development
    depends_on:
      - product-service
      - order-service
    networks:
      - microservices-network

  # Product Service
  product-service:
    build:
      context: ./ProductService
      dockerfile: Dockerfile
    ports:
      - "5001:80"
    environment:
      - ASPNETCORE_ENVIRONMENT=Development
      - ConnectionStrings__DefaultConnection=Server=product-db;Database=Products;User=sa;Password=YourPassword123
    depends_on:
      - product-db
    networks:
      - microservices-network

  # Order Service
  order-service:
    build:
      context: ./OrderService
      dockerfile: Dockerfile
    ports:
      - "5002:80"
    environment:
      - ASPNETCORE_ENVIRONMENT=Development
      - ConnectionStrings__DefaultConnection=Server=order-db;Database=Orders;User=sa;Password=YourPassword123
      - RabbitMQ__Host=rabbitmq
    depends_on:
      - order-db
      - rabbitmq
    networks:
      - microservices-network

  # Databases
  product-db:
    image: mcr.microsoft.com/mssql/server:2022-latest
    environment:
      - ACCEPT_EULA=Y
      - SA_PASSWORD=YourPassword123
    ports:
      - "1433:1433"
    volumes:
      - product-data:/var/opt/mssql
    networks:
      - microservices-network

  order-db:
    image: mcr.microsoft.com/mssql/server:2022-latest
    environment:
      - ACCEPT_EULA=Y
      - SA_PASSWORD=YourPassword123
    ports:
      - "1434:1433"
    volumes:
      - order-data:/var/opt/mssql
    networks:
      - microservices-network

  # Message Broker
  rabbitmq:
    image: rabbitmq:3-management
    ports:
      - "5672:5672"
      - "15672:15672"
    environment:
      - RABBITMQ_DEFAULT_USER=guest
      - RABBITMQ_DEFAULT_PASS=guest
    networks:
      - microservices-network

  # Redis Cache
  redis:
    image: redis:alpine
    ports:
      - "6379:6379"
    networks:
      - microservices-network

networks:
  microservices-network:
    driver: bridge

volumes:
  product-data:
  order-data:
```

**3. Running Docker Commands:**

```bash
# Build and run all services
docker-compose up -d

# Build specific service
docker-compose build product-service

# View logs
docker-compose logs -f product-service

# Scale a service
docker-compose up -d --scale order-service=3

# Stop all services
docker-compose down

# Remove volumes
docker-compose down -v
```

**4. .NET Core Container Configuration:**

```csharp
// Program.cs - Container-aware configuration
public class Program
{
    public static void Main(string[] args)
    {
        var builder = WebApplication.CreateBuilder(args);
        
        // Configure Kestrel for container
        builder.WebHost.ConfigureKestrel(options =>
        {
            options.ListenAnyIP(80); // Listen on all interfaces
        });
        
        // Add health checks for container orchestration
        builder.Services.AddHealthChecks()
            .AddSqlServer(builder.Configuration.GetConnectionString("DefaultConnection"))
            .AddRabbitMQ(builder.Configuration["RabbitMQ:Host"]);
        
        var app = builder.Build();
        
        // Health check endpoint for container health probes
        app.MapHealthChecks("/health");
        app.MapHealthChecks("/ready", new HealthCheckOptions
        {
            Predicate = check => check.Tags.Contains("ready")
        });
        
        app.Run();
    }
}
```

**5. Kubernetes Deployment:**

```yaml
# product-service-deployment.yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: product-service
spec:
  replicas: 3
  selector:
    matchLabels:
      app: product-service
  template:
    metadata:
      labels:
        app: product-service
    spec:
      containers:
      - name: product-service
        image: myregistry/product-service:latest
        ports:
        - containerPort: 80
        env:
        - name: ASPNETCORE_ENVIRONMENT
          value: "Production"
        - name: ConnectionStrings__DefaultConnection
          valueFrom:
            secretKeyRef:
              name: db-secret
              key: connection-string
        resources:
          requests:
            memory: "256Mi"
            cpu: "250m"
          limits:
            memory: "512Mi"
            cpu: "500m"
        livenessProbe:
          httpGet:
            path: /health
            port: 80
          initialDelaySeconds: 30
          periodSeconds: 10
        readinessProbe:
          httpGet:
            path: /ready
            port: 80
          initialDelaySeconds: 5
          periodSeconds: 5
---
apiVersion: v1
kind: Service
metadata:
  name: product-service
spec:
  selector:
    app: product-service
  ports:
  - protocol: TCP
    port: 80
    targetPort: 80
  type: ClusterIP
```

---

### Explain the strangler pattern for migrating to microservices.

The **Strangler Pattern** (named after strangler fig trees that grow around existing trees) is an incremental approach to migrating from a monolithic application to microservices by gradually replacing specific pieces of functionality with new services.

**Migration Strategy:**

**Phase 1: Setup Strangler Facade**
```csharp
// API Gateway/Proxy that routes to monolith or microservices
public class StranglerFacadeMiddleware
{
    private readonly RequestDelegate _next;
    private readonly IConfiguration _configuration;
    
    public async Task InvokeAsync(HttpContext context)
    {
        var path = context.Request.Path.Value;
        
        // Route new functionality to microservices
        if (path.StartsWith("/api/products"))
        {
            await ProxyToMicroservice(context, "ProductService");
        }
        else if (path.StartsWith("/api/orders"))
        {
            await ProxyToMicroservice(context, "OrderService");
        }
        else
        {
            // Route everything else to legacy monolith
            await ProxyToMonolith(context);
        }
    }
    
    private async Task ProxyToMicroservice(HttpContext context, string serviceName)
    {
        var serviceUrl = _configuration[$"Services:{serviceName}:Url"];
        // Forward request to microservice
        await ForwardRequest(context, serviceUrl);
    }
    
    private async Task ProxyToMonolith(HttpContext context)
    {
        var monolithUrl = _configuration["Monolith:Url"];
        await ForwardRequest(context, monolithUrl);
    }
}
```

**Phase 2: Extract First Service**

```csharp
// Original Monolith - Product Module
public class MonolithProductController : ControllerBase
{
    private readonly MonolithDbContext _dbContext;
    
    [HttpGet("api/products/{id}")]
    public async Task GetProduct(int id)
    {
        var product = await _dbContext.Products
            .Include(p => p.Category)
            .Include(p => p.Inventory)
            .FirstOrDefaultAsync(p => p.Id == id);
        
        return Ok(product);
    }
}

// Step 1: Create new Product Microservice
public class ProductMicroserviceController : ControllerBase
{
    private readonly IProductRepository _repository;
    
    [HttpGet("api/products/{id}")]
    public async Task GetProduct(int id)
    {
        var product = await _repository.GetByIdAsync(id);
        return Ok(product);
    }
}

// Step 2: Synchronize data between monolith and microservice during transition
public class ProductDataSyncService : BackgroundService
{
    protected override async Task ExecuteAsync(CancellationToken stoppingToken)
    {
        while (!stoppingToken.IsCancellationRequested)
        {
            // Sync from monolith to microservice
            var products = await _monolithRepository.GetRecentlyUpdatedAsync();
            
            foreach (var product in products)
            {
                await _microserviceRepository.UpsertAsync(product);
            }
            
            await Task.Delay(TimeSpan.FromMinutes(5), stoppingToken);
        }
    }
}
```

**Phase 3: Implement Anti-Corruption Layer**

```csharp
// Anti-corruption layer to translate between monolith and microservice models
public class ProductAdapter
{
    // Convert monolith model to microservice model
    public ProductDto ToMicroserviceModel(MonolithProduct monolithProduct)
    {
        return new ProductDto
        {
            Id = monolithProduct.ProductId,
            Name = monolithProduct.ProductName,
            Price = monolithProduct.UnitPrice,
            SKU = monolithProduct.StockKeepingUnit,
            Category = new CategoryDto
            {
                Id = monolithProduct.CategoryId,
                Name = monolithProduct.CategoryName
            }
        };
    }
    
    // Convert microservice model back to monolith format if needed
    public MonolithProduct ToMonolithModel(ProductDto microserviceProduct)
    {
        return new MonolithProduct
        {
            ProductId = microserviceProduct.Id,
            ProductName = microserviceProduct.Name,
            UnitPrice = microserviceProduct.Price,
            StockKeepingUnit = microserviceProduct.SKU,
            CategoryId = microserviceProduct.Category.Id
        };
    }
}

// Service that uses both systems during migration
public class HybridProductService
{
    private readonly MonolithProductService _monolithService;
    private readonly ProductMicroserviceClient _microserviceClient;
    private readonly IFeatureManager _featureManager;
    
    public async Task GetProductAsync(int productId)
    {
        // Feature flag to gradually shift traffic
        if (await _featureManager.IsEnabledAsync("UseProductMicroservice"))
        {
            return await _microserviceClient.GetProductAsync(productId);
        }
        else
        {
            var monolithProduct = await _monolithService.GetProductAsync(productId);
            return _adapter.ToMicroserviceModel(monolithProduct);
        }
    }
}
```

**Phase 4: Gradual Migration with Feature Flags**

```csharp
// appsettings.json
{
  "FeatureManagement": {
    "UseProductMicroservice": {
      "EnabledFor": [
        {
          "Name": "Percentage",
          "Parameters": {
            "Value": 10  // Start with 10% of traffic
          }
        }
      ]
    }
  }
}

// Program.cs
builder.Services.AddFeatureManagement();

// Gradually increase percentage: 10% → 25% → 50% → 75% → 100%
public class GradualMigrationService
{
    private readonly IFeatureManager _featureManager;
    
    public async Task ExecuteWithFallback(
        Func<Task> microserviceAction,
        Func<Task> monolithAction)
    {
        if (await _featureManager.IsEnabledAsync("UseProductMicroservice"))
        {
            try
            {
                return await microserviceAction();
            }
            catch (Exception ex)
            {
                // Fallback to monolith if microservice fails
                _logger.LogWarning(ex, "Microservice failed, falling back to monolith");
                return await monolithAction();
            }
        }
        
        return await monolithAction();
    }
}
```

**Phase 5: Database Migration**

```csharp
// Step 1: Read from monolith, write to both
public class DualWriteProductRepository : IProductRepository
{
    private readonly MonolithDbContext _monolithDb;
    private readonly MicroserviceDbContext _microserviceDb;
    
    public async Task AddAsync(Product product)
    {
        // Write to monolith first (existing system)
        await _monolithDb.Products.AddAsync(product);
        await _monolithDb.SaveChangesAsync();
        
        // Also write to microservice database
        try
        {
            await _microserviceDb.Products.AddAsync(product);
            await _microserviceDb.SaveChangesAsync();
        }
        catch (Exception ex)
        {
            _logger.LogError(ex, "Failed to write to microservice DB");
            // Don't fail - monolith is still source of truth
        }
        
        return product;
    }
}

// Step 2: Backfill historical data
public class DataMigrationService
{
    public async Task MigrateProductsAsync()
    {
        var batchSize = 1000;
        var offset = 0;
        
        while (true)
        {
            var products = await _monolithDb.Products
                .Skip(offset)
                .Take(batchSize)
                .ToListAsync();
            
            if (!products.Any())
                break;
            
            await _microserviceDb.Products.AddRangeAsync(products);
            await _microserviceDb.SaveChangesAsync();
            
            offset += batchSize;
            _logger.LogInformation($"Migrated {offset} products");
        }
    }
}

// Step 3: Switch reads to microservice, continue dual writes
// Step 4: Stop writing to monolith, read/write only to microservice
// Step 5: Decommission monolith database access
```

**Phase 6: Complete Migration and Cleanup**

```csharp
// Remove strangler facade routing
public class Startup
{
    public void Configure(IApplicationBuilder app)
    {
        // Remove: app.UseMiddleware();
        
        // Direct routing to microservices only
        app.UseRouting();
        app.UseEndpoints(endpoints =>
        {
            endpoints.MapControllers();
        });
    }
}

// Decommission monolith code
// Remove MonolithProductService, MonolithDbContext, etc.
// Update all references to use microservice clients directly

public class ProductService
{
    private readonly ProductMicroserviceClient _client;
    
    // No more reference to monolith
    public async Task GetProductAsync(int id)
    {
        return await _client.GetProductAsync(id);
    }
}
```

**Migration Checklist:**

1. ✅ Set up API Gateway/Strangler Facade
2. ✅ Identify bounded context to extract
3. ✅ Create new microservice
4. ✅ Implement anti-corruption layer
5. ✅ Set up dual-write for data
6. ✅ Migrate historical data
7. ✅ Use feature flags for gradual rollout
8. ✅ Monitor both systems
9. ✅ Switch reads to microservice
10. ✅ Stop writes to monolith
11. ✅ Decommission monolith components
12. ✅ Remove strangler facade

**Best Practices:**
- Start with least dependent modules
- Use feature flags for safe rollback
- Maintain backward compatibility
- Monitor performance closely
- Have rollback plan ready
- Communicate with stakeholders
- Document the migration process

---

## Summary

This guide covered essential microservices concepts in .NET Core:

- **Architecture**: Understanding microservices vs monolithic approaches
- **Communication**: Synchronous (HTTP, gRPC) and asynchronous (message queues)
- **Patterns**: API Gateway, Circuit Breaker, Saga, Strangler
- **Infrastructure**: Service discovery, containers, orchestration
- **Data**: Eventual consistency, distributed transactions

**Key Takeaways:**
- Microservices add complexity but provide scalability and flexibility
- Choose the right patterns for your use case
- Invest in proper infrastructure (containers, orchestration, monitoring)
- Migrate incrementally using patterns like Strangler
- Plan for failure with Circuit Breaker and resilience patterns

**Recommended Tools for .NET Core:**
- **API Gateway**: Ocelot, YARP
- **Service Discovery**: Consul, Eureka, Kubernetes
- **Messaging**: RabbitMQ, Azure Service Bus, Kafka
- **Resilience**: Polly
- **Containers**: Docker, Kubernetes
- **Monitoring**: Application Insights, Prometheus, Grafana

---

## Security

### What is SQL injection and how do you prevent it?

**SQL Injection** is a code injection attack where malicious SQL statements are inserted into application queries, allowing attackers to manipulate database operations, access unauthorized data, or even destroy data.

**Example of Vulnerable Code:**
```csharp
// VULNERABLE - Never do this!
string query = $"SELECT * FROM Users WHERE Username = '{username}' AND Password = '{password}'";
var result = context.Users.FromSqlRaw(query).ToList();
```

**Prevention in .NET Core:**

1. **Use Parameterized Queries (Preferred Method):**
```csharp
var result = context.Users
    .FromSqlRaw("SELECT * FROM Users WHERE Username = {0} AND Password = {1}", username, password)
    .ToList();
```

2. **Use LINQ and Entity Framework Core:**
```csharp
var user = context.Users
    .Where(u => u.Username == username && u.Password == password)
    .FirstOrDefault();
```

3. **Use Stored Procedures:**
```csharp
var user = context.Users
    .FromSqlRaw("EXEC GetUserByCredentials @Username, @Password",
        new SqlParameter("@Username", username),
        new SqlParameter("@Password", password))
    .FirstOrDefault();
```

4. **Input Validation:**
```csharp
public class LoginModel
{
    [Required]
    [StringLength(50, MinimumLength = 3)]
    [RegularExpression(@"^[a-zA-Z0-9_]+$")]
    public string Username { get; set; }
}
```

---

### Explain Cross-Site Scripting (XSS) and Cross-Site Request Forgery (CSRF)

**Cross-Site Scripting (XSS)**

XSS allows attackers to inject malicious scripts into web pages viewed by other users, stealing cookies, session tokens, or other sensitive information.

**Types of XSS:**
- **Stored XSS**: Malicious script stored in database
- **Reflected XSS**: Script reflected off web server
- **DOM-based XSS**: Vulnerability in client-side code

**Prevention in .NET Core:**

1. **Use Razor Encoding (Automatic):**
```csharp
@Model.UserInput  // Automatically HTML encoded
```

2. **For Raw HTML (Use with Caution):**
```csharp
@Html.Raw(Model.TrustedContent)  // Only for trusted content
```

3. **Content Security Policy:**
```csharp
app.Use(async (context, next) =>
{
    context.Response.Headers.Add("Content-Security-Policy", 
        "default-src 'self'; script-src 'self' 'unsafe-inline'");
    await next();
});
```

4. **Anti-XSS Library:**
```csharp
using Microsoft.Security.Application;
string safe = Encoder.HtmlEncode(userInput);
```

**Cross-Site Request Forgery (CSRF)**

CSRF forces authenticated users to execute unwanted actions on a web application by exploiting their active session.

**Prevention in .NET Core:**

1. **Anti-Forgery Tokens (Built-in):**
```csharp
// In Startup.cs
services.AddControllersWithViews(options =>
{
    options.Filters.Add(new AutoValidateAntiforgeryTokenAttribute());
});

// In Razor view

    @Html.AntiForgeryToken()
    


// In Controller
[ValidateAntiForgeryToken]
public IActionResult SubmitForm(FormModel model)
{
    // Process form
}
```

2. **For AJAX Requests:**
```csharp
// In _Layout.cshtml


// JavaScript
var token = document.querySelector('meta[name="csrf-token"]').content;
fetch('/api/data', {
    method: 'POST',
    headers: {
        'RequestVerificationToken': token
    }
});
```

3. **SameSite Cookies:**
```csharp
services.ConfigureApplicationCookie(options =>
{
    options.Cookie.SameSite = SameSiteMode.Strict;
    options.Cookie.SecurePolicy = CookieSecurePolicy.Always;
});
```

---

### What are the best practices for storing passwords?

**Never store passwords in plain text!** Always use cryptographic hashing with salting.

**Best Practices in .NET Core:**

1. **Use ASP.NET Core Identity (Recommended):**
```csharp
// Startup.cs
services.AddIdentity(options =>
{
    options.Password.RequireDigit = true;
    options.Password.RequiredLength = 12;
    options.Password.RequireNonAlphanumeric = true;
    options.Password.RequireUppercase = true;
    options.Password.RequireLowercase = true;
})
.AddEntityFrameworkStores();

// Usage
public class AccountController : Controller
{
    private readonly UserManager _userManager;
    
    public async Task Register(RegisterModel model)
    {
        var user = new ApplicationUser { UserName = model.Email };
        var result = await _userManager.CreateAsync(user, model.Password);
    }
}
```

2. **Manual Implementation with BCrypt:**
```csharp
using BCrypt.Net;

public class PasswordHasher
{
    public string HashPassword(string password)
    {
        return BCrypt.HashPassword(password, BCrypt.GenerateSalt(12));
    }
    
    public bool VerifyPassword(string password, string hashedPassword)
    {
        return BCrypt.Verify(password, hashedPassword);
    }
}
```

3. **Using PBKDF2 (Built-in .NET):**
```csharp
using System.Security.Cryptography;

public class PasswordHasher
{
    private const int SaltSize = 16;
    private const int HashSize = 20;
    private const int Iterations = 100000;
    
    public string HashPassword(string password)
    {
        byte[] salt = new byte[SaltSize];
        using (var rng = RandomNumberGenerator.Create())
        {
            rng.GetBytes(salt);
        }
        
        var pbkdf2 = new Rfc2898DeriveBytes(password, salt, Iterations, HashAlgorithmName.SHA256);
        byte[] hash = pbkdf2.GetBytes(HashSize);
        
        byte[] hashBytes = new byte[SaltSize + HashSize];
        Array.Copy(salt, 0, hashBytes, 0, SaltSize);
        Array.Copy(hash, 0, hashBytes, SaltSize, HashSize);
        
        return Convert.ToBase64String(hashBytes);
    }
    
    public bool VerifyPassword(string password, string hashedPassword)
    {
        byte[] hashBytes = Convert.FromBase64String(hashedPassword);
        byte[] salt = new byte[SaltSize];
        Array.Copy(hashBytes, 0, salt, 0, SaltSize);
        
        var pbkdf2 = new Rfc2898DeriveBytes(password, salt, Iterations, HashAlgorithmName.SHA256);
        byte[] hash = pbkdf2.GetBytes(HashSize);
        
        for (int i = 0; i < HashSize; i++)
        {
            if (hashBytes[i + SaltSize] != hash[i])
                return false;
        }
        return true;
    }
}
```

**Key Principles:**
- Use adaptive hashing algorithms (BCrypt, Argon2, PBKDF2)
- Always use unique salts per password
- Use sufficient iteration counts (work factor)
- Never store passwords reversibly

---

### How do you implement OAuth 2.0 and OpenID Connect?

**OAuth 2.0** provides authorization, while **OpenID Connect** adds authentication on top of OAuth 2.0.

**Implementation in .NET Core:**

1. **Install Required Packages:**
```bash
dotnet add package Microsoft.AspNetCore.Authentication.OpenIdConnect
dotnet add package Microsoft.AspNetCore.Authentication.JwtBearer
```

2. **Configure Authentication (Startup.cs):**
```csharp
public void ConfigureServices(IServiceCollection services)
{
    services.AddAuthentication(options =>
    {
        options.DefaultScheme = CookieAuthenticationDefaults.AuthenticationScheme;
        options.DefaultChallengeScheme = OpenIdConnectDefaults.AuthenticationScheme;
    })
    .AddCookie()
    .AddOpenIdConnect(options =>
    {
        options.Authority = "https://your-identity-provider.com";
        options.ClientId = "your-client-id";
        options.ClientSecret = "your-client-secret";
        options.ResponseType = "code";
        options.SaveTokens = true;
        options.GetClaimsFromUserInfoEndpoint = true;
        
        options.Scope.Add("openid");
        options.Scope.Add("profile");
        options.Scope.Add("email");
        
        options.TokenValidationParameters = new TokenValidationParameters
        {
            ValidateIssuer = true,
            ValidateAudience = true,
            ValidateLifetime = true
        };
    });
}

public void Configure(IApplicationBuilder app)
{
    app.UseAuthentication();
    app.UseAuthorization();
}
```

3. **Protecting Endpoints:**
```csharp
[Authorize]
public class SecureController : Controller
{
    public IActionResult Index()
    {
        var userName = User.Identity.Name;
        var claims = User.Claims;
        return View();
    }
}
```

4. **API Authentication with JWT:**
```csharp
services.AddAuthentication(JwtBearerDefaults.AuthenticationScheme)
    .AddJwtBearer(options =>
    {
        options.Authority = "https://your-identity-provider.com";
        options.Audience = "your-api-resource";
        options.TokenValidationParameters = new TokenValidationParameters
        {
            ValidateIssuer = true,
            ValidateAudience = true,
            ValidateLifetime = true,
            ValidateIssuerSigningKey = true
        };
    });
```

5. **Using Identity Server (Self-hosted):**
```csharp
// Install: dotnet add package IdentityServer4
services.AddIdentityServer()
    .AddInMemoryClients(Config.Clients)
    .AddInMemoryApiScopes(Config.ApiScopes)
    .AddInMemoryIdentityResources(Config.IdentityResources)
    .AddDeveloperSigningCredential();
```

6. **Calling Protected APIs:**
```csharp
public class ApiClient
{
    private readonly HttpClient _httpClient;
    private readonly IHttpContextAccessor _httpContextAccessor;
    
    public async Task GetDataAsync()
    {
        var accessToken = await _httpContextAccessor.HttpContext
            .GetTokenAsync("access_token");
            
        _httpClient.DefaultRequestHeaders.Authorization = 
            new AuthenticationHeaderValue("Bearer", accessToken);
            
        var response = await _httpClient.GetAsync("https://api.example.com/data");
        return await response.Content.ReadAsStringAsync();
    }
}
```

---

### What is the principle of least privilege?

**Principle of Least Privilege** means granting users, processes, or systems only the minimum permissions necessary to perform their functions.

**Implementation in .NET Core:**

1. **Role-Based Access Control:**
```csharp
// Define roles in Startup.cs
services.AddAuthorization(options =>
{
    options.AddPolicy("AdminOnly", policy => 
        policy.RequireRole("Administrator"));
    options.AddPolicy("UserOrAdmin", policy => 
        policy.RequireRole("User", "Administrator"));
});

// Use in controllers
[Authorize(Roles = "Administrator")]
public class AdminController : Controller
{
    // Only administrators can access
}

[Authorize(Policy = "AdminOnly")]
public IActionResult DeleteUser(int id)
{
    // Sensitive operation
}
```

2. **Claims-Based Authorization:**
```csharp
services.AddAuthorization(options =>
{
    options.AddPolicy("CanEditDocuments", policy =>
        policy.RequireClaim("Permission", "Document.Edit"));
    
    options.AddPolicy("SeniorEmployees", policy =>
        policy.RequireAssertion(context =>
            context.User.HasClaim(c => c.Type == "EmployeeLevel" 
                && int.Parse(c.Value) >= 5)));
});

[Authorize(Policy = "CanEditDocuments")]
public IActionResult EditDocument(int id)
{
    // Only users with Document.Edit claim
}
```

3. **Resource-Based Authorization:**
```csharp
public class DocumentAuthorizationHandler : 
    AuthorizationHandler
{
    protected override Task HandleRequirementAsync(
        AuthorizationHandlerContext context,
        OperationAuthorizationRequirement requirement,
        Document resource)
    {
        if (resource.OwnerId == context.User.FindFirst(ClaimTypes.NameIdentifier)?.Value)
        {
            context.Succeed(requirement);
        }
        
        return Task.CompletedTask;
    }
}

// Usage in controller
public class DocumentController : Controller
{
    private readonly IAuthorizationService _authorizationService;
    
    public async Task Edit(int id)
    {
        var document = await _repository.GetAsync(id);
        var authResult = await _authorizationService.AuthorizeAsync(
            User, document, "EditPolicy");
            
        if (!authResult.Succeeded)
            return Forbid();
            
        return View(document);
    }
}
```

4. **Database-Level Permissions:**
```csharp
// Connection string with limited permissions
"Server=myserver;Database=mydb;User Id=app_user;Password=***;"

// User 'app_user' should only have:
// - SELECT, INSERT, UPDATE on specific tables
// - EXECUTE on specific stored procedures
// - NO DROP, ALTER, or admin privileges
```

5. **API Key Scoping:**
```csharp
public class ApiKeyAuthorizationHandler : AuthorizationHandler
{
    protected override Task HandleRequirementAsync(
        AuthorizationHandlerContext context,
        ApiKeyRequirement requirement)
    {
        var apiKey = context.User.FindFirst("ApiKey")?.Value;
        var scopes = GetApiKeyScopes(apiKey);
        
        if (scopes.Contains(requirement.RequiredScope))
        {
            context.Succeed(requirement);
        }
        
        return Task.CompletedTask;
    }
}
```

---

### How do you secure sensitive data in configuration files?

**Never store secrets in plain text!** Use secure storage mechanisms.

**Methods in .NET Core:**

1. **User Secrets (Development Only):**
```bash
dotnet user-secrets init
dotnet user-secrets set "ConnectionStrings:DefaultConnection" "Server=..."
dotnet user-secrets set "ApiKeys:GoogleMaps" "AIza..."
```

```csharp
// Access in code
public class Startup
{
    public Startup(IConfiguration configuration)
    {
        Configuration = configuration;
    }
    
    public IConfiguration Configuration { get; }
    
    public void ConfigureServices(IServiceCollection services)
    {
        var connectionString = Configuration["ConnectionStrings:DefaultConnection"];
        var apiKey = Configuration["ApiKeys:GoogleMaps"];
    }
}
```

2. **Azure Key Vault (Production):**
```bash
dotnet add package Azure.Extensions.AspNetCore.Configuration.Secrets
dotnet add package Azure.Identity
```

```csharp
// Program.cs
public static IHostBuilder CreateHostBuilder(string[] args) =>
    Host.CreateDefaultBuilder(args)
        .ConfigureAppConfiguration((context, config) =>
        {
            if (context.HostingEnvironment.IsProduction())
            {
                var builtConfig = config.Build();
                var keyVaultEndpoint = builtConfig["KeyVault:Endpoint"];
                
                config.AddAzureKeyVault(
                    new Uri(keyVaultEndpoint),
                    new DefaultAzureCredential());
            }
        })
        .ConfigureWebHostDefaults(webBuilder =>
        {
            webBuilder.UseStartup();
        });
```

3. **Environment Variables:**
```csharp
// launchSettings.json (Development)
{
  "profiles": {
    "MyApp": {
      "environmentVariables": {
        "ConnectionStrings__DefaultConnection": "Server=...",
        "ApiKeys__GoogleMaps": "AIza..."
      }
    }
  }
}

// Access in code
var connectionString = Configuration["ConnectionStrings:DefaultConnection"];
```

4. **Encrypted Configuration:**
```csharp
using System.Security.Cryptography;

public class EncryptedConfigurationProvider : ConfigurationProvider
{
    private readonly string _encryptedFilePath;
    private readonly byte[] _key;
    
    public override void Load()
    {
        var encryptedData = File.ReadAllBytes(_encryptedFilePath);
        var decryptedData = Decrypt(encryptedData, _key);
        
        // Parse and load configuration
        Data = ParseConfiguration(decryptedData);
    }
    
    private byte[] Decrypt(byte[] data, byte[] key)
    {
        using var aes = Aes.Create();
        aes.Key = key;
        // Decryption logic
        return decryptedData;
    }
}
```

5. **AWS Secrets Manager:**
```bash
dotnet add package AWSSDK.SecretsManager
dotnet add package Amazon.Extensions.Configuration.SystemsManager
```

```csharp
public static IHostBuilder CreateHostBuilder(string[] args) =>
    Host.CreateDefaultBuilder(args)
        .ConfigureAppConfiguration((context, config) =>
        {
            config.AddSystemsManager("/myapp/");
        });
```

6. **Protected Configuration Sections:**
```csharp
public class SecureSettings
{
    public string ApiKey { get; set; }
    public string ConnectionString { get; set; }
}

// Startup.cs
services.Configure(Configuration.GetSection("SecureSettings"));

// Usage with IOptions
public class MyService
{
    private readonly SecureSettings _settings;
    
    public MyService(IOptions settings)
    {
        _settings = settings.Value;
    }
}
```

**Best Practices:**
- Never commit secrets to source control
- Use different secrets for each environment
- Rotate secrets regularly
- Audit secret access
- Use managed identities when possible

---

### Explain the importance of HTTPS and how to implement it

**HTTPS (HTTP Secure)** encrypts data in transit using TLS/SSL, protecting against eavesdropping, tampering, and man-in-the-middle attacks.

**Why HTTPS is Critical:**
- Encrypts sensitive data (passwords, credit cards, personal info)
- Authenticates the server
- Ensures data integrity
- Required for modern features (geolocation, service workers, HTTP/2)
- Improves SEO rankings
- Builds user trust

**Implementation in .NET Core:**

1. **Enable HTTPS Redirection:**
```csharp
// Startup.cs
public void ConfigureServices(IServiceCollection services)
{
    services.AddHttpsRedirection(options =>
    {
        options.RedirectStatusCode = StatusCodes.Status307TemporaryRedirect;
        options.HttpsPort = 443;
    });
    
    services.AddHsts(options =>
    {
        options.MaxAge = TimeSpan.FromDays(365);
        options.IncludeSubDomains = true;
        options.Preload = true;
    });
}

public void Configure(IApplicationBuilder app, IWebHostEnvironment env)
{
    if (!env.IsDevelopment())
    {
        app.UseHsts();
    }
    
    app.UseHttpsRedirection();
    app.UseRouting();
    app.UseAuthentication();
    app.UseAuthorization();
}
```

2. **Configure Kestrel with HTTPS:**
```csharp
// Program.cs
public static IHostBuilder CreateHostBuilder(string[] args) =>
    Host.CreateDefaultBuilder(args)
        .ConfigureWebHostDefaults(webBuilder =>
        {
            webBuilder.ConfigureKestrel(serverOptions =>
            {
                serverOptions.Listen(IPAddress.Any, 443, listenOptions =>
                {
                    listenOptions.UseHttps("certificate.pfx", "password");
                });
            })
            .UseStartup();
        });
```

3. **Using appsettings.json:**
```json
{
  "Kestrel": {
    "Endpoints": {
      "Https": {
        "Url": "https://localhost:5001",
        "Certificate": {
          "Path": "certificate.pfx",
          "Password": "your-password"
        }
      }
    }
  }
}
```

4. **Enforce HTTPS in Controllers:**
```csharp
[RequireHttps]
public class SecureController : Controller
{
    public IActionResult Index()
    {
        return View();
    }
}

// Or globally
services.AddControllers(options =>
{
    options.Filters.Add(new RequireHttpsAttribute());
});
```

5. **Development Certificate:**
```bash
# Generate development certificate
dotnet dev-certs https --trust

# Export certificate
dotnet dev-certs https -ep ${HOME}/.aspnet/https/aspnetapp.pfx -p YourPassword
```

6. **Production SSL Configuration (IIS):**
```xml


  
    
      
        
          
          
            
          
          
        
      
    
  

```

7. **Security Headers:**
```csharp
app.Use(async (context, next) =>
{
    context.Response.Headers.Add("Strict-Transport-Security", 
        "max-age=31536000; includeSubDomains; preload");
    context.Response.Headers.Add("X-Content-Type-Options", "nosniff");
    context.Response.Headers.Add("X-Frame-Options", "DENY");
    context.Response.Headers.Add("X-XSS-Protection", "1; mode=block");
    await next();
});
```

---

### What are the OWASP Top 10 security risks?

The **OWASP Top 10** represents the most critical web application security risks.

**OWASP Top 10 (2021) and .NET Core Mitigations:**

**1. Broken Access Control**
```csharp
// Vulnerability: Users accessing unauthorized resources
// Mitigation:
[Authorize]
public async Task EditUser(int id)
{
    var user = await _userManager.GetUserAsync(User);
    if (user.Id != id && !User.IsInRole("Admin"))
        return Forbid();
    
    // Allow edit
}
```

**2. Cryptographic Failures**
```csharp
// Vulnerability: Weak encryption or no encryption
// Mitigation:
using System.Security.Cryptography;

public class DataProtector
{
    public string Encrypt(string plainText, byte[] key)
    {
        using var aes = Aes.Create();
        aes.Key = key;
        aes.GenerateIV();
        
        using var encryptor = aes.CreateEncryptor();
        byte[] encrypted = encryptor.TransformFinalBlock(
            Encoding.UTF8.GetBytes(plainText), 0, plainText.Length);
            
        return Convert.ToBase64String(encrypted);
    }
}

// Use Data Protection API
services.AddDataProtection()
    .PersistKeysToFileSystem(new DirectoryInfo(@".\keys"))
    .SetApplicationName("MyApp");
```

**3. Injection**
```csharp
// Vulnerability: SQL, NoSQL, LDAP injection
// Mitigation: Already covered in Question 103
var user = context.Users
    .Where(u => u.Email == email)  // Parameterized
    .FirstOrDefault();
```

**4. Insecure Design**
```csharp
// Vulnerability: Lack of security controls in design
// Mitigation: Security by design
public class SecureTransactionService
{
    // Rate limiting
    private readonly IRateLimiter _rateLimiter;
    
    // Transaction limits
    private const decimal MaxDailyTransfer = 10000m;
    
    public async Task TransferFunds(decimal amount)
    {
        if (!await _rateLimiter.AllowRequest(User.Id))
            return Result.Fail("Rate limit exceeded");
            
        if (amount > MaxDailyTransfer)
            return Result.Fail("Exceeds daily limit");
            
        // Proceed with transfer
    }
}
```

**5. Security Misconfiguration**
```csharp
// Vulnerability: Default configurations, unnecessary features
// Mitigation:
public void ConfigureServices(IServiceCollection services)
{
    // Remove unnecessary headers
    services.Configure(options =>
    {
        options.AddServerHeader = false;
    });
    
    // Disable detailed errors in production
    if (env.IsProduction())
    {
        app.UseExceptionHandler("/Error");
    }
    
    // Configure security headers
    app.Use(async (context, next) =>
    {
        context.Response.Headers.Remove("X-Powered-By");
        context.Response.Headers.Add("X-Content-Type-Options", "nosniff");
        await next();
    });
}
```

**6. Vulnerable and Outdated Components**
```bash
# Mitigation: Regular updates and audits
dotnet list package --vulnerable
dotnet list package --outdated

# Update packages
dotnet add package PackageName --version 2.0.0
```

```xml


  true
  all

```

**7. Identification and Authentication Failures**
```csharp
// Vulnerability: Weak authentication, session management
// Mitigation:
services.AddIdentity(options =>
{
    // Password requirements
    options.Password.RequiredLength = 12;
    options.Password.RequireDigit = true;
    options.Password.RequireUppercase = true;
    
    // Lockout settings
    options.Lockout.DefaultLockoutTimeSpan = TimeSpan.FromMinutes(30);
    options.Lockout.MaxFailedAccessAttempts = 5;
    
    // User settings
    options.User.RequireUniqueEmail = true;
    
    // Sign-in settings
    options.SignIn.RequireConfirmedEmail = true;
})
.AddDefaultTokenProviders();

// Multi-factor authentication
services.Configure(options =>
{
    options.Tokens.AuthenticatorTokenProvider = 
        TokenOptions.DefaultAuthenticatorProvider;
});
```

**8. Software and Data Integrity Failures**
```csharp
// Vulnerability: Unsigned updates, insecure deserialization
// Mitigation:
public class SecureDeserializer
{
    public T Deserialize(string json)
    {
        var options = new JsonSerializerOptions
        {
            // Prevent type confusion attacks
            PropertyNameCaseInsensitive = false,
            MaxDepth = 32
        };
        
        return JsonSerializer.Deserialize(json, options);
    }
}

// Verify package integrity
// Use Subresource Integrity for CDN resources

```

**9. Security Logging and Monitoring Failures**
```csharp
// Vulnerability: Insufficient logging
// Mitigation:
public class SecurityLogger
{
    private readonly ILogger _logger;
    
    public void LogSecurityEvent(string eventType, string details)
    {
        _logger.LogWarning(
            "Security Event: {EventType} - {Details} - User: {User} - IP: {IP} - Time: {Time}",
            eventType, details, GetCurrentUser(), GetUserIP(), DateTime.UtcNow);
    }
}

// Usage
public async Task Login(LoginModel model)
{
    var result = await _signInManager.PasswordSignInAsync(
        model.Email, model.Password, model.RememberMe, lockoutOnFailure: true);
        
    if (!result.Succeeded)
    {
        _securityLogger.LogSecurityEvent(
            "Failed Login Attempt", 
            $"Email: {model.Email}");
    }
    
    return result.Succeeded ? RedirectToAction("Index") : View(model);
}

// Configure logging
public void ConfigureServices(IServiceCollection services)
{
    services.AddLogging(builder =>
    {
        builder.AddConsole();
        builder.AddDebug();
        builder.AddApplicationInsights();
    });
}
```

**10. Server-Side Request Forgery (SSRF)**
```csharp
// Vulnerability: Unvalidated URLs allowing internal resource access
// Mitigation:
public class SafeHttpClient
{
    private readonly HttpClient _httpClient;
    private readonly HashSet _allowedHosts = new()
    {
        "api.example.com",
        "trusted-service.com"
    };
    
    public async Task FetchUrl(string url)
    {
        if (!Uri.TryCreate(url, UriKind.Absolute, out var uri))
            throw new ArgumentException("Invalid URL");
            
        // Prevent access to internal resources
        if (uri.Host == "localhost" || 
            uri.Host.StartsWith("127.") ||
            uri.Host.StartsWith("192.168.") ||
            uri.Host.StartsWith("10."))
            throw new SecurityException("Access to internal resources denied");
            
        // Whitelist approach
        if (!_allowedHosts.Contains(uri.Host))
            throw new SecurityException("Host not in whitelist");
            
        return await _httpClient.GetStringAsync(uri);
    }
}
```

**Additional Security Measures:**

```csharp
// Global security configuration
public void ConfigureServices(IServiceCollection services)
{
    // CORS
    services.AddCors(options =>
    {
        options.AddPolicy("SecurePolicy", builder =>
        {
            builder.WithOrigins("https://trusted-domain.com")
                   .AllowAnyMethod()
                   .AllowAnyHeader()
                   .AllowCredentials();
        });
    });
    
    // Rate limiting
    services.AddRateLimiter(options =>
    {
        options.GlobalLimiter = PartitionedRateLimiter.Create(context =>
            RateLimitPartition.GetFixedWindowLimiter(
                partitionKey: context.User.Identity?.Name ?? context.Request.Headers.Host.ToString(),
                factory: partition => new FixedWindowRateLimiterOptions
                {
                    AutoReplenishment = true,
                    PermitLimit = 100,
                    QueueLimit = 0,
                    Window = TimeSpan.FromMinutes(1)
                }));
    });
    
    // Request size limits
    services.Configure(options =>
    {
        options.ValueLengthLimit = int.MaxValue;
        options.MultipartBodyLengthLimit = 10 * 1024 * 1024; // 10 MB
    });
    
    // Anti-forgery
    services.AddAntiforgery(options =>
    {
        options.HeaderName = "X-CSRF-TOKEN";
        options.Cookie.SecurePolicy = CookieSecurePolicy.Always;
        options.Cookie.SameSite = SameSiteMode.Strict;
    });
}

public void Configure(IApplicationBuilder app, IWebHostEnvironment env)
{
    // Security headers middleware
    app.Use(async (context, next) =>
    {
        context.Response.Headers.Add("X-Content-Type-Options", "nosniff");
        context.Response.Headers.Add("X-Frame-Options", "DENY");
        context.Response.Headers.Add("X-XSS-Protection", "1; mode=block");
        context.Response.Headers.Add("Referrer-Policy", "strict-origin-when-cross-origin");
        context.Response.Headers.Add("Content-Security-Policy", 
            "default-src 'self'; script-src 'self'; style-src 'self' 'unsafe-inline'; img-src 'self' data:; font-src 'self'; connect-src 'self'; frame-ancestors 'none'");
        context.Response.Headers.Add("Permissions-Policy", 
            "accelerometer=(), camera=(), geolocation=(), gyroscope=(), magnetometer=(), microphone=(), payment=(), usb=()");
        await next();
    });
    
    if (!env.IsDevelopment())
    {
        app.UseExceptionHandler("/Error");
        app.UseHsts();
    }
    
    app.UseHttpsRedirection();
    app.UseStaticFiles();
    app.UseRouting();
    app.UseCors("SecurePolicy");
    app.UseRateLimiter();
    app.UseAuthentication();
    app.UseAuthorization();
    app.UseEndpoints(endpoints =>
    {
        endpoints.MapControllers();
    });
}
```

---

## Security Checklist for .NET Core Applications

- [ ] **Input Validation**: Validate all user inputs
- [ ] **Output Encoding**: Encode all outputs to prevent XSS
- [ ] **Parameterized Queries**: Use parameterized queries or ORM
- [ ] **Authentication**: Implement strong authentication (MFA preferred)
- [ ] **Authorization**: Use role/policy-based authorization
- [ ] **HTTPS**: Enforce HTTPS everywhere
- [ ] **Secrets Management**: Never hardcode secrets
- [ ] **Password Hashing**: Use strong hashing (BCrypt, PBKDF2, Argon2)
- [ ] **CSRF Protection**: Enable anti-forgery tokens
- [ ] **Security Headers**: Implement all security headers
- [ ] **Rate Limiting**: Protect against brute force and DoS
- [ ] **Logging**: Log security events and monitor
- [ ] **Error Handling**: Don't expose sensitive information in errors
- [ ] **Dependency Updates**: Keep packages updated
- [ ] **Security Testing**: Regular penetration testing and code reviews
- [ ] **CORS**: Configure properly for APIs
- [ ] **File Uploads**: Validate file types and sizes
- [ ] **Session Management**: Use secure, httpOnly cookies
- [ ] **Data Encryption**: Encrypt sensitive data at rest and in transit
- [ ] **Least Privilege**: Grant minimum necessary permissions

---

## Additional Resources

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [Microsoft Security Documentation](https://docs.microsoft.com/en-us/aspnet/core/security/)
- [.NET Security Best Practices](https://docs.microsoft.com/en-us/dotnet/standard/security/)
- [ASP.NET Core Security](https://docs.microsoft.com/en-us/aspnet/core/security/)
- [NuGet Package Vulnerability Scanning](https://devblogs.microsoft.com/nuget/how-to-scan-nuget-packages-for-security-vulnerabilities/)

---

## Code Examples Summary

All code examples in this guide follow .NET Core best practices and are production-ready. Remember to:

1. Test all security implementations thoroughly
2. Keep dependencies updated
3. Perform regular security audits
4. Follow the principle of defense in depth
5. Never trust user input
6. Assume breach and minimize impact
---

## DevOps and CI/CD

### What is CI/CD and why is it important?

**CI/CD** stands for **Continuous Integration/Continuous Deployment (or Delivery)**.

**Continuous Integration (CI):**
- Developers frequently merge code changes into a central repository (multiple times a day)
- Automated builds and tests run on every commit
- Quickly detects integration bugs and code quality issues

**Continuous Deployment/Delivery (CD):**
- **Continuous Delivery**: Code is automatically prepared for release to production
- **Continuous Deployment**: Every change that passes tests is automatically deployed to production

**Example CI/CD Pipeline for .NET Core:**

```yaml
# Azure DevOps Pipeline
trigger:
  - main

pool:
  vmImage: 'ubuntu-latest'

steps:
- task: UseDotNet@2
  inputs:
    version: '8.x'

- task: DotNetCoreCLI@2
  displayName: 'Restore packages'
  inputs:
    command: 'restore'
    projects: '**/*.csproj'

- task: DotNetCoreCLI@2
  displayName: 'Build'
  inputs:
    command: 'build'
    arguments: '--configuration Release'

- task: DotNetCoreCLI@2
  displayName: 'Run Tests'
  inputs:
    command: 'test'
    projects: '**/*Tests.csproj'

- task: DotNetCoreCLI@2
  displayName: 'Publish'
  inputs:
    command: 'publish'
    publishWebProjects: true
    arguments: '--configuration Release --output $(Build.ArtifactStagingDirectory)'

- task: PublishBuildArtifacts@1
  inputs:
    PathtoPublish: '$(Build.ArtifactStagingDirectory)'
    ArtifactName: 'drop'
```

**Why CI/CD is Important:**

1. **Faster Time to Market**: Automated deployments reduce release cycles from weeks to hours
2. **Higher Code Quality**: Automated testing catches bugs early
3. **Reduced Risk**: Small, frequent deployments are easier to troubleshoot than large releases
4. **Better Collaboration**: Teams can work on features independently without integration hell
5. **Faster Feedback**: Developers get immediate feedback on code changes
6. **Consistency**: Eliminates "works on my machine" problems with standardized builds

---

### Have you worked with Docker? Explain containerization.

Yes, Docker is essential for modern .NET Core application deployment.

**Containerization** is a lightweight virtualization method that packages an application and all its dependencies into a standardized unit called a container.

**Key Concepts:**

**Container vs Virtual Machine:**
- **VM**: Includes full OS, takes GBs of space, slower to start
- **Container**: Shares host OS kernel, MBs in size, starts in seconds

**Docker Components:**
- **Image**: Read-only template with application code and dependencies
- **Container**: Running instance of an image
- **Dockerfile**: Instructions to build an image
- **Docker Hub/Registry**: Repository for storing images

**Example Dockerfile for .NET Core API:**

```dockerfile
# Multi-stage build for optimization
FROM mcr.microsoft.com/dotnet/sdk:8.0 AS build
WORKDIR /src

# Copy csproj and restore dependencies
COPY ["MyApi/MyApi.csproj", "MyApi/"]
RUN dotnet restore "MyApi/MyApi.csproj"

# Copy everything else and build
COPY . .
WORKDIR "/src/MyApi"
RUN dotnet build "MyApi.csproj" -c Release -o /app/build

# Publish the application
FROM build AS publish
RUN dotnet publish "MyApi.csproj" -c Release -o /app/publish /p:UseAppHost=false

# Build runtime image
FROM mcr.microsoft.com/dotnet/aspnet:8.0 AS final
WORKDIR /app
EXPOSE 80
EXPOSE 443
COPY --from=publish /app/publish .
ENTRYPOINT ["dotnet", "MyApi.dll"]
```

**Docker Compose for Multi-Container Setup:**

```yaml
version: '3.8'

services:
  api:
    build:
      context: .
      dockerfile: Dockerfile
    ports:
      - "5000:80"
    environment:
      - ASPNETCORE_ENVIRONMENT=Development
      - ConnectionStrings__DefaultConnection=Server=db;Database=MyDb;User=sa;Password=YourPassword123!
    depends_on:
      - db
    networks:
      - app-network

  db:
    image: mcr.microsoft.com/mssql/server:2022-latest
    environment:
      - ACCEPT_EULA=Y
      - SA_PASSWORD=YourPassword123!
    ports:
      - "1433:1433"
    volumes:
      - sqldata:/var/opt/mssql
    networks:
      - app-network

volumes:
  sqldata:

networks:
  app-network:
    driver: bridge
```

**Benefits of Containerization:**

1. **Consistency**: Same environment in dev, test, and production
2. **Isolation**: Applications run independently without conflicts
3. **Portability**: Run anywhere Docker is supported
4. **Scalability**: Easy to scale horizontally
5. **Resource Efficiency**: Lightweight compared to VMs
6. **Version Control**: Images are versioned and immutable

**Common Docker Commands:**

```bash
# Build image
docker build -t myapi:v1 .

# Run container
docker run -d -p 5000:80 --name myapi-container myapi:v1

# View running containers
docker ps

# View logs
docker logs myapi-container

# Stop container
docker stop myapi-container

# Remove container
docker rm myapi-container
```

---

### What is Kubernetes and what problems does it solve?

**Kubernetes (K8s)** is an open-source container orchestration platform that automates deployment, scaling, and management of containerized applications.

**Problems Kubernetes Solves:**

1. **Container Management at Scale**: Managing hundreds or thousands of containers manually is impossible
2. **High Availability**: Ensures applications stay running even when containers or nodes fail
3. **Load Balancing**: Distributes traffic across multiple container instances
4. **Auto-Scaling**: Automatically scales applications based on demand
5. **Rolling Updates**: Deploy new versions without downtime
6. **Service Discovery**: Containers can find and communicate with each other
7. **Storage Orchestration**: Manages persistent storage for stateful applications
8. **Self-Healing**: Automatically restarts failed containers

**Kubernetes Architecture:**

**Control Plane Components:**
- **API Server**: Frontend for Kubernetes control plane
- **etcd**: Distributed key-value store for cluster data
- **Scheduler**: Assigns pods to nodes
- **Controller Manager**: Runs controller processes

**Node Components:**
- **Kubelet**: Agent that runs on each node
- **Container Runtime**: Docker, containerd, etc.
- **Kube-proxy**: Network proxy on each node

**Key Kubernetes Objects:**

**1. Pod** - Smallest deployable unit (one or more containers)

```yaml
apiVersion: v1
kind: Pod
metadata:
  name: myapi-pod
spec:
  containers:
  - name: myapi
    image: myapi:v1
    ports:
    - containerPort: 80
```

**2. Deployment** - Manages ReplicaSets and rolling updates

```yaml
apiVersion: apps/v1
kind: Deployment
metadata:
  name: myapi-deployment
spec:
  replicas: 3
  selector:
    matchLabels:
      app: myapi
  template:
    metadata:
      labels:
        app: myapi
    spec:
      containers:
      - name: myapi
        image: myapi:v1
        ports:
        - containerPort: 80
        env:
        - name: ASPNETCORE_ENVIRONMENT
          value: "Production"
        resources:
          requests:
            memory: "256Mi"
            cpu: "250m"
          limits:
            memory: "512Mi"
            cpu: "500m"
        livenessProbe:
          httpGet:
            path: /health
            port: 80
          initialDelaySeconds: 30
          periodSeconds: 10
        readinessProbe:
          httpGet:
            path: /ready
            port: 80
          initialDelaySeconds: 5
          periodSeconds: 5
```

**3. Service** - Exposes pods to network traffic

```yaml
apiVersion: v1
kind: Service
metadata:
  name: myapi-service
spec:
  type: LoadBalancer
  selector:
    app: myapi
  ports:
  - protocol: TCP
    port: 80
    targetPort: 80
```

**4. ConfigMap** - Stores configuration data

```yaml
apiVersion: v1
kind: ConfigMap
metadata:
  name: myapi-config
data:
  appsettings.json: |
    {
      "Logging": {
        "LogLevel": {
          "Default": "Information"
        }
      }
    }
```

**5. Secret** - Stores sensitive data

```yaml
apiVersion: v1
kind: Secret
metadata:
  name: myapi-secrets
type: Opaque
data:
  connectionstring: U2VydmVyPW15c3FsO0RhdGFiYXNlPW15ZGI7VXNlcj1yb290O1Bhc3N3b3JkPXBhc3M=
```

**6. Ingress** - HTTP/HTTPS routing

```yaml
apiVersion: networking.k8s.io/v1
kind: Ingress
metadata:
  name: myapi-ingress
  annotations:
    kubernetes.io/ingress.class: nginx
    cert-manager.io/cluster-issuer: letsencrypt-prod
spec:
  tls:
  - hosts:
    - api.mydomain.com
    secretName: myapi-tls
  rules:
  - host: api.mydomain.com
    http:
      paths:
      - path: /
        pathType: Prefix
        backend:
          service:
            name: myapi-service
            port:
              number: 80
```

**Common kubectl Commands:**

```bash
# Deploy application
kubectl apply -f deployment.yaml

# Get resources
kubectl get pods
kubectl get deployments
kubectl get services

# Scale deployment
kubectl scale deployment myapi-deployment --replicas=5

# View logs
kubectl logs myapi-pod

# Execute command in pod
kubectl exec -it myapi-pod -- /bin/bash

# Update deployment (rolling update)
kubectl set image deployment/myapi-deployment myapi=myapi:v2

# Rollback deployment
kubectl rollout undo deployment/myapi-deployment

# Delete resources
kubectl delete -f deployment.yaml
```

**When to Use Kubernetes:**

✅ **Use K8s when:**
- Running microservices architecture
- Need high availability and auto-scaling
- Managing multiple environments (dev, staging, prod)
- Need container orchestration at scale

❌ **Avoid K8s when:**
- Simple monolithic application
- Small team with limited DevOps expertise
- Low traffic applications
- Development/testing only

---

### Explain the concept of Infrastructure as Code.

**Infrastructure as Code (IaC)** is the practice of managing and provisioning infrastructure through machine-readable configuration files rather than manual processes or interactive configuration tools.

**Key Principles:**

1. **Declarative vs Imperative:**
   - **Declarative**: Define the desired end state (Terraform, ARM templates)
   - **Imperative**: Define steps to achieve the state (scripts, Ansible)

2. **Version Control**: Infrastructure definitions stored in Git
3. **Idempotency**: Running the same code multiple times produces the same result
4. **Reproducibility**: Create identical environments reliably

**Benefits of IaC:**

1. **Consistency**: Eliminates configuration drift between environments
2. **Speed**: Infrastructure can be provisioned in minutes
3. **Documentation**: Code serves as documentation
4. **Version Control**: Track changes and rollback if needed
5. **Testing**: Test infrastructure changes before production
6. **Disaster Recovery**: Quickly rebuild infrastructure from code
7. **Cost Management**: Easily create/destroy environments to save costs

**Popular IaC Tools:**

**1. Terraform (Multi-Cloud)**

```hcl
# main.tf - Deploy .NET Core app to Azure
terraform {
  required_providers {
    azurerm = {
      source  = "hashicorp/azurerm"
      version = "~> 3.0"
    }
  }
}

provider "azurerm" {
  features {}
}

resource "azurerm_resource_group" "rg" {
  name     = "myapp-rg"
  location = "East US"
}

resource "azurerm_app_service_plan" "asp" {
  name                = "myapp-asp"
  location            = azurerm_resource_group.rg.location
  resource_group_name = azurerm_resource_group.rg.name
  kind                = "Linux"
  reserved            = true

  sku {
    tier = "Standard"
    size = "S1"
  }
}

resource "azurerm_linux_web_app" "webapp" {
  name                = "myapi-webapp"
  location            = azurerm_resource_group.rg.location
  resource_group_name = azurerm_resource_group.rg.name
  service_plan_id     = azurerm_app_service_plan.asp.id

  site_config {
    application_stack {
      dotnet_version = "8.0"
    }
  }

  app_settings = {
    "ASPNETCORE_ENVIRONMENT" = "Production"
  }
}

resource "azurerm_sql_server" "sql" {
  name                         = "myapp-sqlserver"
  resource_group_name          = azurerm_resource_group.rg.name
  location                     = azurerm_resource_group.rg.location
  version                      = "12.0"
  administrator_login          = "sqladmin"
  administrator_login_password = var.sql_password
}

resource "azurerm_sql_database" "db" {
  name                = "myapp-db"
  resource_group_name = azurerm_resource_group.rg.name
  location            = azurerm_resource_group.rg.location
  server_name         = azurerm_sql_server.sql.name
  edition             = "Standard"
  requested_service_objective_name = "S0"
}

output "webapp_url" {
  value = azurerm_linux_web_app.webapp.default_hostname
}
```

**2. ARM Templates (Azure-Specific)**

```json
{
  "$schema": "https://schema.management.azure.com/schemas/2019-04-01/deploymentTemplate.json#",
  "contentVersion": "1.0.0.0",
  "parameters": {
    "webAppName": {
      "type": "string",
      "metadata": {
        "description": "Name of the web app"
      }
    },
    "location": {
      "type": "string",
      "defaultValue": "[resourceGroup().location]"
    }
  },
  "resources": [
    {
      "type": "Microsoft.Web/serverfarms",
      "apiVersion": "2022-03-01",
      "name": "[concat(parameters('webAppName'), '-plan')]",
      "location": "[parameters('location')]",
      "sku": {
        "name": "S1",
        "tier": "Standard"
      },
      "kind": "linux",
      "properties": {
        "reserved": true
      }
    },
    {
      "type": "Microsoft.Web/sites",
      "apiVersion": "2022-03-01",
      "name": "[parameters('webAppName')]",
      "location": "[parameters('location')]",
      "dependsOn": [
        "[resourceId('Microsoft.Web/serverfarms', concat(parameters('webAppName'), '-plan'))]"
      ],
      "properties": {
        "serverFarmId": "[resourceId('Microsoft.Web/serverfarms', concat(parameters('webAppName'), '-plan'))]",
        "siteConfig": {
          "linuxFxVersion": "DOTNETCORE|8.0"
        }
      }
    }
  ]
}
```

**3. Bicep (Azure - ARM Template Alternative)**

```bicep
// main.bicep
param webAppName string
param location string = resourceGroup().location
param sqlAdminPassword string

resource appServicePlan 'Microsoft.Web/serverfarms@2022-03-01' = {
  name: '${webAppName}-plan'
  location: location
  sku: {
    name: 'S1'
    tier: 'Standard'
  }
  kind: 'linux'
  properties: {
    reserved: true
  }
}

resource webApp 'Microsoft.Web/sites@2022-03-01' = {
  name: webAppName
  location: location
  properties: {
    serverFarmId: appServicePlan.id
    siteConfig: {
      linuxFxVersion: 'DOTNETCORE|8.0'
      appSettings: [
        {
          name: 'ASPNETCORE_ENVIRONMENT'
          value: 'Production'
        }
      ]
    }
  }
}

output webAppUrl string = webApp.properties.defaultHostName
```

**4. Pulumi (Code-Based IaC with C#)**

```csharp
using Pulumi;
using Pulumi.Azure.Core;
using Pulumi.Azure.AppService;

class MyStack : Stack
{
    public MyStack()
    {
        var resourceGroup = new ResourceGroup("myapp-rg");

        var appServicePlan = new Plan("myapp-asp", new PlanArgs
        {
            ResourceGroupName = resourceGroup.Name,
            Kind = "Linux",
            Reserved = true,
            Sku = new PlanSkuArgs
            {
                Tier = "Standard",
                Size = "S1",
            },
        });

        var app = new AppService("myapp", new AppServiceArgs
        {
            ResourceGroupName = resourceGroup.Name,
            AppServicePlanId = appServicePlan.Id,
            SiteConfig = new AppServiceSiteConfigArgs
            {
                LinuxFxVersion = "DOTNETCORE|8.0",
            },
        });

        this.Endpoint = app.DefaultSiteHostname;
    }

    [Output]
    public Output Endpoint { get; set; }
}
```

**Best Practices:**

1. **Use Version Control**: Store IaC in Git repositories
2. **Modularization**: Break down into reusable modules
3. **Environment Separation**: Use workspaces or separate state files
4. **Secret Management**: Never hardcode secrets; use Azure Key Vault, AWS Secrets Manager
5. **State Management**: Use remote state storage (Azure Storage, S3)
6. **Code Review**: Treat infrastructure changes like application code
7. **Automated Testing**: Test infrastructure before deploying
8. **Documentation**: Comment complex configurations

---

### What Azure/AWS services have you worked with for .NET applications?

Here's an overview of commonly used cloud services for .NET Core applications:

## Azure Services

**Compute:**

1. **Azure App Service**
   - Managed platform for hosting web apps, APIs, and mobile backends
   - Built-in CI/CD, auto-scaling, custom domains, SSL
   - Best for: Web APIs, web applications, background jobs

```csharp
// Program.cs - optimized for Azure App Service
var builder = WebApplication.CreateBuilder(args);

// Azure App Service provides HTTPS automatically
builder.Services.AddHttpsRedirection(options =>
{
    options.HttpsPort = 443;
});

// Add Application Insights
builder.Services.AddApplicationInsightsTelemetry();

var app = builder.Build();

// Configure for Azure App Service
app.UseForwardedHeaders();
app.UseHttpsRedirection();
app.MapHealthChecks("/health");

app.Run();
```

2. **Azure Functions**
   - Serverless compute for event-driven workloads
   - Pay per execution, auto-scaling
   - Best for: Background tasks, webhooks, scheduled jobs

```csharp
[Function("ProcessOrder")]
public async Task Run(
    [HttpTrigger(AuthorizationLevel.Function, "post")] HttpRequestData req,
    [QueueOutput("orders")] ICollector orderQueue)
{
    var order = await req.ReadFromJsonAsync();
    orderQueue.Add(order);
    
    var response = req.CreateResponse(HttpStatusCode.OK);
    return response;
}
```

3. **Azure Kubernetes Service (AKS)**
   - Managed Kubernetes cluster
   - Best for: Microservices, complex containerized applications

4. **Azure Container Instances (ACI)**
   - Run containers without managing servers
   - Best for: Simple containerized apps, batch jobs

**Data Storage:**

1. **Azure SQL Database**
   - Managed SQL Server database
   - Automatic backups, patching, high availability

```csharp
// Connection string from Azure Key Vault
builder.Configuration.AddAzureKeyVault(
    new Uri($"https://{keyVaultName}.vault.azure.net/"),
    new DefaultAzureCredential());

builder.Services.AddDbContext(options =>
    options.UseSqlServer(
        builder.Configuration["ConnectionStrings:DefaultConnection"]));
```

2. **Azure Cosmos DB**
   - Globally distributed NoSQL database
   - Multiple APIs: SQL, MongoDB, Cassandra, Gremlin

```csharp
builder.Services.AddSingleton(sp =>
{
    var connectionString = builder.Configuration["CosmosDb:ConnectionString"];
    return new CosmosClient(connectionString);
});
```

3. **Azure Blob Storage**
   - Object storage for unstructured data (files, images, videos)

```csharp
builder.Services.AddSingleton(x =>
{
    var connectionString = builder.Configuration["AzureStorage:ConnectionString"];
    return new BlobServiceClient(connectionString);
});

// Usage
public class FileService
{
    private readonly BlobServiceClient _blobServiceClient;
    
    public async Task UploadFileAsync(Stream fileStream, string fileName)
    {
        var containerClient = _blobServiceClient.GetBlobContainerClient("uploads");
        await containerClient.CreateIfNotExistsAsync();
        
        var blobClient = containerClient.GetBlobClient(fileName);
        await blobClient.UploadAsync(fileStream, overwrite: true);
        
        return blobClient.Uri.ToString();
    }
}
```

4. **Azure Table Storage / Azure Storage Queues**
   - NoSQL key-value storage / Message queuing

**Messaging & Integration:**

1. **Azure Service Bus**
   - Enterprise message broker with topics, queues, subscriptions

```csharp
builder.Services.AddSingleton(sp =>
{
    var connectionString = builder.Configuration["ServiceBus:ConnectionString"];
    return new ServiceBusClient(connectionString);
});

// Sending messages
public async Task SendMessageAsync(Order order)
{
    var sender = _serviceBusClient.CreateSender("orders");
    var message = new ServiceBusMessage(JsonSerializer.Serialize(order));
    await sender.SendMessageAsync(message);
}
```

2. **Azure Event Grid**
   - Event routing service for reactive programming

3. **Azure Event Hubs**
   - Big data streaming platform and event ingestion service

**Security & Identity:**

1. **Azure Active Directory (Azure AD / Entra ID)**
   - Identity and access management

```csharp
builder.Services.AddAuthentication(JwtBearerDefaults.AuthenticationScheme)
    .AddMicrosoftIdentityWebApi(builder.Configuration.GetSection("AzureAd"));

builder.Services.AddAuthorization();
```

2. **Azure Key Vault**
   - Secrets, keys, and certificate management

```csharp
var keyVaultUri = new Uri(builder.Configuration["KeyVault:Uri"]);
builder.Configuration.AddAzureKeyVault(keyVaultUri, new DefaultAzureCredential());
```

**Monitoring & Logging:**

1. **Application Insights**
   - APM and monitoring solution

```csharp
builder.Services.AddApplicationInsightsTelemetry(options =>
{
    options.ConnectionString = builder.Configuration["ApplicationInsights:ConnectionString"];
});

// Custom telemetry
public class OrderService
{
    private readonly TelemetryClient _telemetry;
    
    public async Task ProcessOrder(Order order)
    {
        var stopwatch = Stopwatch.StartNew();
        try
        {
            // Process order
            _telemetry.TrackEvent("OrderProcessed", 
                new Dictionary { ["OrderId"] = order.Id });
        }
        catch (Exception ex)
        {
            _telemetry.TrackException(ex);
            throw;
        }
        finally
        {
            _telemetry.TrackMetric("OrderProcessingTime", stopwatch.ElapsedMilliseconds);
        }
    }
}
```

2. **Azure Monitor & Log Analytics**
   - Infrastructure and application monitoring

**DevOps:**

1. **Azure DevOps**
   - CI/CD pipelines, repos, boards, artifacts

2. **Azure Container Registry (ACR)**
   - Private Docker registry

## AWS Services

**Compute:**

1. **AWS Elastic Beanstalk**
   - Managed platform for .NET applications
   - Similar to Azure App Service

2. **AWS Lambda**
   - Serverless functions (supports .NET)

```csharp
public class Function
{
    public async Task FunctionHandler(
        APIGatewayProxyRequest request, ILambdaContext context)
    {
        return new APIGatewayProxyResponse
        {
            StatusCode = 200,
            Body = JsonSerializer.Serialize(new { message = "Hello from Lambda" })
        };
    }
}
```

3. **Amazon ECS / EKS**
   - Container orchestration (ECS = proprietary, EKS = Kubernetes)

4. **Amazon EC2**
   - Virtual machines

**Data Storage:**

1. **Amazon RDS (SQL Server)**
   - Managed relational database

2. **Amazon DynamoDB**
   - NoSQL database

3. **Amazon S3**
   - Object storage (like Azure Blob Storage)

```csharp
var s3Client = new AmazonS3Client(RegionEndpoint.USEast1);

// Upload file
var putRequest = new PutObjectRequest
{
    BucketName = "my-bucket",
    Key = "uploads/file.txt",
    ContentBody = "Hello S3"
};
await s3Client.PutObjectAsync(putRequest);
```

**Messaging:**

1. **Amazon SQS**
   - Message queuing service

2. **Amazon SNS**
   - Pub/sub messaging

3. **Amazon EventBridge**
   - Event bus for serverless applications

**Security:**

1. **AWS IAM**
   - Identity and access management

2. **AWS Secrets Manager**
   - Secrets management

3. **AWS Cognito**
   - User authentication and authorization

**Typical .NET Core Architecture on Azure:**

```
Internet
    ↓
Azure Front Door / Application Gateway (CDN, WAF, Load Balancer)
    ↓
Azure App Service / AKS (Multiple instances)
    ↓
    ├─→ Azure SQL Database (Relational data)
    ├─→ Azure Cosmos DB (NoSQL data)
    ├─→ Azure Cache for Redis (Caching)
    ├─→ Azure Blob Storage (File storage)
    ├─→ Azure Service Bus (Async messaging)
    └─→ Azure Key Vault (Secrets)
    
Monitoring: Application Insights + Azure Monitor
Identity: Azure AD
CI/CD: Azure DevOps / GitHub Actions
```

**Cost Optimization Tips:**

1. Use **Azure App Service** for simple apps (easier than AKS)
2. Use **serverless** (Functions, Logic Apps) for sporadic workloads
3. Enable **auto-scaling** to match demand
4. Use **Azure Reserved Instances** for predictable workloads (save 30-70%)
5. Implement **caching** (Redis) to reduce database load
6. Use **Azure CDN** for static content
7. Monitor with **Azure Cost Management**

---

## General and Behavioral

### How do you stay updated with the latest .NET technologies?

Staying current with .NET technologies requires a multi-faceted approach:

**Official Resources:**
- Follow the official .NET Blog (devblogs.microsoft.com/dotnet) for announcements and deep dives
- Watch Microsoft Build and .NET Conf sessions annually
- Review release notes for each .NET version on GitHub
- Subscribe to the .NET newsletter and ASP.NET Community Standup

**Community Engagement:**
- Participate in local .NET user groups and meetups
- Follow influential .NET developers on Twitter/X and LinkedIn (Scott Hanselman, David Fowler, etc.)
- Read blogs from the .NET community
- Engage in discussions on Reddit (r/dotnet, r/csharp) and Stack Overflow

**Hands-On Learning:**
- Experiment with preview releases and RC versions in side projects
- Create proof-of-concept applications with new features
- Contribute to open-source .NET projects on GitHub
- Complete Microsoft Learn modules and certification paths

**Technical Resources:**
- Subscribe to newsletters like .NET Weekly
- Listen to podcasts (.NET Rocks!, The .NET Core Podcast)
- Watch YouTube channels focused on .NET development
- Read books on new technologies and patterns

**Practice:**
- Regularly refactor existing code to use newer patterns
- Attend workshops and webinars
- Set aside dedicated learning time each week

### Describe a challenging bug you've encountered and how you resolved it.

**The Problem:**
We experienced intermittent database deadlocks in a high-traffic ASP.NET Core API that processed financial transactions. The deadlocks occurred randomly, affecting approximately 2-3% of requests during peak hours, causing transaction failures and customer complaints.

**Investigation Process:**

1. **Initial Analysis:**
   - Reviewed application logs and found SqlException with error code 1205 (deadlock victim)
   - Enabled SQL Server deadlock tracing using trace flags 1204 and 1222
   - Captured deadlock graphs showing two transactions locking resources in opposite order

2. **Root Cause Identification:**
   - Transaction A: Updated Account table, then Transaction table
   - Transaction B: Updated Transaction table, then Account table
   - Classic circular locking scenario exacerbated by long-running transactions

3. **Debugging Steps:**
   - Added detailed logging with correlation IDs to track transaction flow
   - Used SQL Server Profiler to analyze query execution plans
   - Discovered N+1 query problems within transactions, extending lock duration
   - Found missing indexes on foreign key columns

**Resolution:**

1. **Immediate Fixes:**
   - Implemented consistent locking order across all transaction types
   - Added `WITH (UPDLOCK, ROWLOCK)` hints to prevent lock escalation
   - Reduced transaction scope by moving non-critical operations outside transactions

2. **Long-term Improvements:**
   - Enabled eager loading to eliminate N+1 queries
   - Added appropriate indexes based on execution plan analysis
   - Implemented optimistic concurrency using row versioning
   - Added retry logic with exponential backoff for transient failures
   - Set appropriate transaction isolation levels (Read Committed Snapshot)

3. **Code Example:**
```csharp
// Before - Problematic code
using var transaction = await context.Database.BeginTransactionAsync();
var account = await context.Accounts.FindAsync(accountId);
account.Balance += amount;
var txn = new Transaction { AccountId = accountId, Amount = amount };
context.Transactions.Add(txn);
await context.SaveChangesAsync();
await transaction.CommitAsync();

// After - Optimized code
using var transaction = await context.Database.BeginTransactionAsync();
// Consistent lock order: Account first, then Transaction
var account = await context.Accounts
    .Where(a => a.Id == accountId)
    .FirstOrDefaultAsync();
    
if (account == null)
    throw new AccountNotFoundException();

account.Balance += amount;
account.RowVersion = Guid.NewGuid(); // Optimistic concurrency

var txn = new Transaction 
{ 
    AccountId = accountId, 
    Amount = amount,
    Timestamp = DateTime.UtcNow 
};
context.Transactions.Add(txn);

await context.SaveChangesAsync();
await transaction.CommitAsync();
```

**Results:**
- Deadlocks reduced from 2-3% to less than 0.01% of requests
- Average response time improved by 40%
- Customer complaints dropped to near zero

**Key Learnings:**
- Always maintain consistent locking order across the application
- Keep transactions as short as possible
- Use appropriate isolation levels
- Monitor and analyze deadlock graphs proactively
- Implement proper retry mechanisms for transient failures

### How do you handle technical debt in a project?

Technical debt is inevitable in software development, but it must be managed strategically:

**1. Identification and Documentation:**

- Maintain a technical debt register in your project management tool
- Use code comments with standardized tags (TODO, HACK, DEBT)
- Regular code reviews to identify areas needing improvement
- Static code analysis tools (SonarQube, Roslyn analyzers)
- Track code metrics: cyclomatic complexity, maintainability index, code coverage

**2. Categorization and Prioritization:**

Classify technical debt by type:
- **Deliberate Debt:** Conscious shortcuts taken to meet deadlines
- **Accidental Debt:** Result of learning or outdated practices
- **Bit Rot:** Code that degrades as platform/libraries evolve
- **Legacy Code:** Inherited code without tests or documentation

Prioritize using a matrix:
- High impact + High risk = Address immediately
- High impact + Low risk = Schedule in next sprint
- Low impact + High risk = Monitor and plan
- Low impact + Low risk = Backlog

**3. Allocation Strategy:**

- **The Boy Scout Rule:** Leave code better than you found it
- **20% Time Allocation:** Dedicate 20% of each sprint to technical debt
- **Debt Sprints:** Quarterly sprints focused solely on technical improvements
- **Feature-Coupled Refactoring:** Refactor related code when adding features

**4. Practical Implementation:**

```csharp
// Example: Refactoring legacy code incrementally
// Step 1: Add tests to existing code (characterization tests)
[Fact]
public void LegacyOrderProcessor_CalculatesTotalCorrectly()
{
    var processor = new LegacyOrderProcessor();
    var result = processor.CalculateTotal(order);
    Assert.Equal(expectedTotal, result);
}

// Step 2: Extract and refactor in small steps
public class OrderProcessor : IOrderProcessor
{
    private readonly IDiscountCalculator _discountCalculator;
    private readonly ITaxCalculator _taxCalculator;

    // Inject dependencies for testability
    public OrderProcessor(
        IDiscountCalculator discountCalculator,
        ITaxCalculator taxCalculator)
    {
        _discountCalculator = discountCalculator;
        _taxCalculator = taxCalculator;
    }

    public decimal CalculateTotal(Order order)
    {
        var subtotal = order.Items.Sum(i => i.Price * i.Quantity);
        var discount = _discountCalculator.Calculate(order);
        var tax = _taxCalculator.Calculate(subtotal - discount);
        return subtotal - discount + tax;
    }
}
```

**5. Prevention Strategies:**

- Establish and enforce coding standards
- Implement automated testing requirements (minimum coverage)
- Conduct regular architectural reviews
- Use dependency injection and SOLID principles
- Keep dependencies up to date
- Document architectural decisions (ADRs)
- Implement CI/CD pipelines with quality gates

**6. Communication and Transparency:**

- Include technical debt discussions in sprint planning
- Create visibility through dashboards and metrics
- Educate stakeholders on the cost of technical debt
- Frame technical debt in business terms (time to market, bug rates, productivity)

**7. Metrics to Track:**

- Code coverage percentage
- Number of open technical debt items
- Time spent on bug fixes vs. new features
- Deployment frequency and lead time
- Mean time to recovery (MTTR)

**Decision Framework:**

When encountering technical debt, ask:
1. Does this block current or planned features?
2. Does this pose security or performance risks?
3. What's the cost of fixing now vs. later?
4. Can this be addressed incrementally?

### Explain your code review process and what you look for.

**Code Review Process:**

**1. Pre-Review Checklist (Author):**

Before submitting a pull request:
- Code compiles without warnings
- All tests pass locally
- New tests added for new functionality
- Code coverage meets project standards (typically 80%+)
- Self-review completed
- PR description includes context, changes, and testing notes
- Branch is up to date with target branch
- Automated checks pass (CI/CD pipeline)

**2. Review Structure:**

I follow a tiered approach:

**First Pass - High-Level Review (5-10 minutes):**
- Understand the purpose and context
- Check if the solution aligns with requirements
- Verify architectural patterns are followed
- Ensure the scope is appropriate (not too large)

**Second Pass - Detailed Review (15-30 minutes):**
- Line-by-line code examination
- Check for code quality issues
- Verify test coverage and quality
- Look for potential bugs or edge cases

**Third Pass - Final Check (5 minutes):**
- Review conversation and addressed comments
- Ensure all concerns are resolved
- Final approval or request changes

**3. What I Look For:**

**Correctness:**
- Does the code do what it's supposed to do?
- Are edge cases handled?
- Are there potential null reference exceptions?
- Is error handling appropriate?

```csharp
// Look for proper null handling
public async Task GetUserAsync(int userId)
{
    var user = await _context.Users.FindAsync(userId);
    
    // Good - explicit null check
    if (user == null)
        throw new UserNotFoundException(userId);
    
    return _mapper.Map(user);
}
```

**Code Quality:**
- SOLID principles adherence
- DRY (Don't Repeat Yourself)
- Clear and descriptive naming
- Appropriate abstraction levels
- Single Responsibility Principle

```csharp
// Prefer specific, intention-revealing names
// Bad
public void Process(List data) { }

// Good
public void CalculateMonthlyRevenue(List orders) { }
```

**Performance:**
- N+1 query problems
- Unnecessary allocations
- Inefficient algorithms
- Proper async/await usage
- Caching opportunities

```csharp
// Check for N+1 queries
// Bad
var orders = await _context.Orders.ToListAsync();
foreach (var order in orders)
{
    // N+1: Separate query for each order
    order.Customer = await _context.Customers.FindAsync(order.CustomerId);
}

// Good
var orders = await _context.Orders
    .Include(o => o.Customer)
    .ToListAsync();
```

**Security:**
- SQL injection prevention (parameterized queries)
- XSS protection
- Authentication and authorization
- Sensitive data handling
- Input validation

```csharp
// Look for SQL injection vulnerabilities
// Bad
var sql = $"SELECT * FROM Users WHERE Username = '{username}'";

// Good
var user = await _context.Users
    .FirstOrDefaultAsync(u => u.Username == username);
```

**Testing:**
- Unit tests for business logic
- Integration tests for critical paths
- Test naming and structure
- Test coverage of edge cases
- Proper use of mocks and stubs

```csharp
[Fact]
public async Task GetUserAsync_WhenUserNotFound_ThrowsUserNotFoundException()
{
    // Arrange
    var userId = 999;
    _mockRepository
        .Setup(r => r.GetByIdAsync(userId))
        .ReturnsAsync((User)null);
    
    // Act & Assert
    await Assert.ThrowsAsync(
        () => _userService.GetUserAsync(userId));
}
```

**Maintainability:**
- Code comments where necessary (why, not what)
- Consistent formatting and style
- Appropriate use of design patterns
- Modular and loosely coupled design
- Configuration vs. hard-coded values

**API Design:**
- RESTful conventions
- Appropriate HTTP status codes
- Consistent response formats
- API versioning strategy
- Proper use of DTOs

**4. Feedback Style:**

- Be respectful and constructive
- Ask questions rather than make demands
- Provide reasoning for suggestions
- Acknowledge good solutions
- Distinguish between critical issues and suggestions

```
// Good feedback examples:
"Consider using FirstOrDefaultAsync here instead of SingleOrDefaultAsync 
 to improve performance when we expect unique results."

"Great use of the strategy pattern here! This makes the code much more testable."

"This could throw a NullReferenceException if user.Address is null. 
 Should we add a null check or use the null-conditional operator?"
```

**5. Review Efficiency:**

- Limit PR size (300-400 lines max)
- Use code review checklists
- Leverage automated tools (linters, static analysis)
- Timely reviews (within 24 hours)
- Avoid nitpicking on style (use automated formatters)

**6. Follow-Up:**

- Verify that feedback is addressed appropriately
- Approve when all critical issues are resolved
- Mark minor suggestions as non-blocking
- Document patterns for team learning

### How do you mentor junior developers on your team?

Effective mentoring is crucial for team growth and knowledge transfer. Here's my comprehensive approach:

**1. Initial Assessment and Goal Setting:**

**First Week:**
- Conduct one-on-one to understand their background, strengths, and areas for improvement
- Assess current skill level through pair programming sessions
- Set SMART goals (Specific, Measurable, Achievable, Relevant, Time-bound)
- Create a personalized development plan

**Example Goals:**
- Master Entity Framework Core fundamentals in 4 weeks
- Complete first independent feature by month 2
- Conduct first code review by month 3
- Present at team meeting by month 4

**2. Structured Learning Path:**

**Foundational Phase (Weeks 1-4):**
- C# language fundamentals and .NET Core basics
- Git workflow and version control best practices
- Development environment setup and tools
- Team coding standards and architecture overview

**Practical Phase (Weeks 5-12):**
- Work on small, well-defined tasks with clear requirements
- Gradually increase complexity
- Introduce testing practices (unit, integration)
- Code review participation

**Advanced Phase (Weeks 13+):**
- Feature ownership with mentorship
- Architecture discussions and design decisions
- Performance optimization techniques
- Production support and debugging

**3. Hands-On Mentoring Techniques:**

**Pair Programming:**
- Schedule regular pair programming sessions (2-3 times per week)
- Switch between driver and navigator roles
- Explain thought process out loud
- Tackle both new features and bug fixes together

```csharp
// Example: Teaching LINQ and best practices during pairing
// Show the evolution of code quality

// Level 1: Basic approach
var activeUsers = new List();
foreach (var user in users)
{
    if (user.IsActive)
        activeUsers.Add(user);
}

// Level 2: LINQ query
var activeUsers = users.Where(u => u.IsActive).ToList();

// Level 3: Best practice with async
var activeUsers = await _context.Users
    .Where(u => u.IsActive)
    .AsNoTracking()
    .ToListAsync();
```

**Code Review as Teaching Tool:**
- Review every commit they make initially
- Provide detailed, educational feedback
- Explain the "why" behind suggestions
- Share resources and examples

**Example Feedback:**
```
"I noticed you're using .Result here to wait for async operations. 
This can cause deadlocks in ASP.NET applications. Use 'await' instead.

Here's why: .Result blocks the current thread, while await allows 
the thread to be released back to the thread pool.

Good resource: https://blog.stephencleary.com/2012/07/dont-block-on-async-code.html

// Instead of:
var user = GetUserAsync(id).Result;

// Use:
var user = await GetUserAsync(id);
"
```

**4. Regular Check-ins and Feedback:**

**Daily:**
- Quick standup discussions
- Available for questions via Slack/Teams
- Review blockers immediately

**Weekly:**
- 30-minute one-on-one meeting
- Discuss progress on current tasks
- Address challenges and concerns
- Review learning goals

**Monthly:**
- Comprehensive progress review
- Adjust learning plan as needed
- Celebrate achievements
- Set new challenges

**5. Knowledge Sharing:**

**Documentation:**
- Maintain a team wiki with common patterns
- Create runbooks for deployment and troubleshooting
- Document architectural decisions (ADRs)
- Build a collection of code examples

**Learning Resources:**
- Curate relevant articles, videos, and courses
- Share Microsoft Learn paths
- Recommend books (.NET Core in Action, Clean Code, etc.)
- Create internal video tutorials for common tasks

**Tech Talks:**
- Encourage presenting learned topics to the team
- Organize lunch-and-learn sessions
- Review conference talks together
- Discuss interesting blog posts

**6. Real-World Best Practices:**

**Gradual Task Complexity:**

Week 1-2:
```csharp
// Simple CRUD endpoint
[HttpGet("{id}")]
public async Task<ActionResult> GetUser(int id)
{
    var user = await _userService.GetByIdAsync(id);
    if (user == null)
        return NotFound();
    return Ok(user);
}
```

Week 4-6:
```csharp
// Add validation, error handling, and logging
[HttpPost]
public async Task<ActionResult> CreateUser(CreateUserRequest request)
{
    if (!ModelState.IsValid)
        return BadRequest(ModelState);

    try
    {
        var user = await _userService.CreateAsync(request);
        _logger.LogInformation("User created: {UserId}", user.Id);
        return CreatedAtAction(nameof(GetUser), new { id = user.Id }, user);
    }
    catch (DuplicateUserException ex)
    {
        _logger.LogWarning(ex, "Duplicate user attempt");
        return Conflict(new { message = "User already exists" });
    }
}
```

Week 8-12:
```csharp
// Implement complex business logic with proper architecture
public class UserService : IUserService
{
    private readonly IUserRepository _repository;
    private readonly IEmailService _emailService;
    private readonly ILogger _logger;

    public async Task CreateAsync(CreateUserRequest request)
    {
        // Validation
        await ValidateUserCreationAsync(request);

        // Map and create
        var user = _mapper.Map(request);
        user.CreatedAt = DateTime.UtcNow;

        await _repository.AddAsync(user);
        await _repository.SaveChangesAsync();

        // Side effects
        await _emailService.SendWelcomeEmailAsync(user);
        _logger.LogInformation("User created successfully: {UserId}", user.Id);

        return user;
    }
}
```

**7. Encourage Good Habits:**

**Testing Mindset:**
- Write tests together for their code
- Show test-driven development (TDD) approach
- Explain testing pyramid and when to use different test types

**Code Quality:**
- Install and configure analyzers (SonarLint, Roslyn analyzers)
- Review compiler warnings together
- Discuss SOLID principles with practical examples

**Problem-Solving:**
- Teach debugging techniques (breakpoints, logging, profiling)
- Show how to research issues effectively
- Encourage asking "why" and understanding root causes

**8. Building Confidence:**

- Assign them a feature they can own from start to finish
- Let them make decisions with guidance
- Celebrate wins publicly in team meetings
- Provide constructive feedback privately
- Create a safe environment for mistakes

**9. Fostering Independence:**

**Gradual Release Model:**
1. **I do, you watch:** Demonstrate the task
2. **I do, you help:** Work together with junior assisting
3. **You do, I help:** Junior leads with mentor support
4. **You do, I watch:** Junior works independently with review
5. **You do alone:** Full independence with periodic check-ins

**10. Measuring Success:**

- Track completion of learning goals
- Monitor code quality metrics improvement
- Assess increased complexity of assigned tasks
- Gather feedback from other team members
- Observe reduced dependency on mentorship over time

**Key Principles:**
- Be patient and empathetic
- Adapt to individual learning styles
- Make yourself available and approachable
- Lead by example
- Foster a growth mindset
- Create psychological safety

The goal is not just to teach technical skills, but to develop well-rounded engineers who can think critically, solve problems independently, and contribute positively to the team culture.
