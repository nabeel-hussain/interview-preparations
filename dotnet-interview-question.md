
- [1. C# and .NET Fundamentals](#1-c-and-net-fundamentals)
  - [1.1. What is the CLR, and why is it important?](#11-what-is-the-clr-and-why-is-it-important)
  - [1.2. What is CIL (Common Intermediate Language)?](#12-what-is-cil-common-intermediate-language)
  - [1.3. What is the difference between managed and unmanaged code?](#13-what-is-the-difference-between-managed-and-unmanaged-code)
  - [1.4. Explain the difference between value types and reference types in C#.](#14-explain-the-difference-between-value-types-and-reference-types-in-c)
  - [1.5. What is the difference between string and StringBuilder? When would you use each?](#15-what-is-the-difference-between-string-and-stringbuilder-when-would-you-use-each)
  - [1.6. Explain the concepts of boxing and unboxing with performance implications.](#16-explain-the-concepts-of-boxing-and-unboxing-with-performance-implications)
  - [1.7. What are extension methods and when should you use them?](#17-what-are-extension-methods-and-when-should-you-use-them)
  - [1.8. Explain the difference between IEnumerable, ICollection, IList, and IQueryable.](#18-explain-the-difference-between-ienumerable-icollection-ilist-and-iqueryable)
  - [1.9. What is the difference between abstract class and interface? When would you use each?](#19-what-is-the-difference-between-abstract-class-and-interface-when-would-you-use-each)
  - [1.10. Explain covariance and contravariance in C#.](#110-explain-covariance-and-contravariance-in-c)
  - [1.11. What are delegates, events, and how do they differ?](#111-what-are-delegates-events-and-how-do-they-differ)
  - [1.12. Describe the difference between readonly and const in C#.](#112-describe-the-difference-between-readonly-and-const-in-c)
  - [1.13. What is reflection and what are its use cases and drawbacks?](#113-what-is-reflection-and-what-are-its-use-cases-and-drawbacks)
  - [1.14. Explain the concept of nullable reference types introduced in C# 8.0.](#114-explain-the-concept-of-nullable-reference-types-introduced-in-c-80)
  - [1.15. What is the difference between Finalize() and Dispose() methods?](#115-what-is-the-difference-between-finalize-and-dispose-methods)
  - [1.16. What is exception handling and how does it work in C#?](#116-what-is-exception-handling-and-how-does-it-work-in-c)
  - [1.17. What are properties and indexers in C#?](#117-what-are-properties-and-indexers-in-c)
  - [1.18. What are the key differences between .NET Framework, .NET Core, and .NET 5+?](#118-what-are-the-key-differences-between-net-framework-net-core-and-net-5)
  - [1.19. What are assemblies and namespaces in .NET?](#119-what-are-assemblies-and-namespaces-in-net)
  - [1.20. What are lambda expressions and how do they work in C#?](#120-what-are-lambda-expressions-and-how-do-they-work-in-c)
  - [1.21. What are the fundamental concepts of threading in .NET?](#121-what-are-the-fundamental-concepts-of-threading-in-net)
- [2. Object-Oriented Programming](#2-object-oriented-programming)
  - [2.1. Explain the four pillars of OOP with real-world examples.](#21-explain-the-four-pillars-of-oop-with-real-world-examples)
  - [2.2. What is the SOLID principle? Explain each letter with examples.](#22-what-is-the-solid-principle-explain-each-letter-with-examples)
  - [2.3. What is the difference between method overloading and method overriding?](#23-what-is-the-difference-between-method-overloading-and-method-overriding)
  - [2.4. Explain the concept of polymorphism with examples.](#24-explain-the-concept-of-polymorphism-with-examples)
  - [2.5. What are sealed classes and sealed methods?](#25-what-are-sealed-classes-and-sealed-methods)
  - [2.6. Describe the difference between composition and inheritance.](#26-describe-the-difference-between-composition-and-inheritance)
  - [2.7. What is the Liskov Substitution Principle and why is it important?](#27-what-is-the-liskov-substitution-principle-and-why-is-it-important)
  - [2.8. Explain dependency injection and its benefits.](#28-explain-dependency-injection-and-its-benefits)
  - [2.9. What are design patterns? Name and explain 5 commonly used patterns.](#29-what-are-design-patterns-name-and-explain-5-commonly-used-patterns)
    - [2.9.1. Singleton Pattern](#291-singleton-pattern)
    - [2.9.2. Factory Pattern](#292-factory-pattern)
    - [2.9.3. Observer Pattern](#293-observer-pattern)
    - [2.9.4. Strategy Pattern](#294-strategy-pattern)
    - [2.9.5. Repository Pattern](#295-repository-pattern)
  - [2.10. What is the difference between shallow copy and deep copy?](#210-what-is-the-difference-between-shallow-copy-and-deep-copy)
  - [2.11. What is the difference between virtual, override, and new keywords in C#?](#211-what-is-the-difference-between-virtual-override-and-new-keywords-in-c)
  - [2.12. What are access modifiers in C# and when would you use each?](#212-what-are-access-modifiers-in-c-and-when-would-you-use-each)
  - [2.13. What is the difference between static and instance members?](#213-what-is-the-difference-between-static-and-instance-members)
  - [2.14. What are constructors and destructors in C#?](#214-what-are-constructors-and-destructors-in-c)
  - [2.15. What is method hiding and how does it differ from method overriding?](#215-what-is-method-hiding-and-how-does-it-differ-from-method-overriding)
  - [2.16. What are partial classes and partial methods in C#?](#216-what-are-partial-classes-and-partial-methods-in-c)
- [3. Asynchronous Programming](#3-asynchronous-programming)
  - [3.1. Explain `async` and `await` keywords in C#.](#31-explain-async-and-await-keywords-in-c)
  - [3.2. What is the difference between `Task` and `Thread`?](#32-what-is-the-difference-between-task-and-thread)
  - [3.3. What is `Task.Run()` vs `Task.Factory.StartNew()`?](#33-what-is-taskrun-vs-taskfactorystartnew)
  - [3.4. Explain what `ConfigureAwait(false)` does and when to use it.](#34-explain-what-configureawaitfalse-does-and-when-to-use-it)
  - [3.5. What is a deadlock and how can async/await cause it?](#35-what-is-a-deadlock-and-how-can-asyncawait-cause-it)
  - [3.6. Explain the difference between `Task.WhenAll()` and `Task.WhenAny()`](#36-explain-the-difference-between-taskwhenall-and-taskwhenany)
  - [3.7. What is `ValueTask` and when should you use it over `Task`?](#37-what-is-valuetask-and-when-should-you-use-it-over-task)
  - [3.8. How do you handle exceptions in async methods?](#38-how-do-you-handle-exceptions-in-async-methods)
  - [3.9. What is the difference between synchronous and asynchronous programming?](#39-what-is-the-difference-between-synchronous-and-asynchronous-programming)
  - [3.10. Explain the concept of the `SynchronizationContext`](#310-explain-the-concept-of-the-synchronizationcontext)
  - [3.11. What are the best practices for cancellation in async operations using `CancellationToken`?](#311-what-are-the-best-practices-for-cancellation-in-async-operations-using-cancellationtoken)
  - [3.12. How would you implement parallel processing in .NET?](#312-how-would-you-implement-parallel-processing-in-net)
  - [3.13. What is the difference between `Task.FromResult()` and `Task.Run()`?](#313-what-is-the-difference-between-taskfromresult-and-taskrun)
  - [3.14. How do you implement async/await in a custom class or library?](#314-how-do-you-implement-asyncawait-in-a-custom-class-or-library)
  - [3.15. What are the performance implications of async/await?](#315-what-are-the-performance-implications-of-asyncawait)
  - [3.16. How do you handle async operations in constructors and static methods?](#316-how-do-you-handle-async-operations-in-constructors-and-static-methods)
- [4. ASP.NET Core](#4-aspnet-core)
  - [4.1. Explain the middleware pipeline in ASP.NET Core](#41-explain-the-middleware-pipeline-in-aspnet-core)
  - [4.2. What is the difference between ASP.NET and ASP.NET Core?](#42-what-is-the-difference-between-aspnet-and-aspnet-core)
  - [4.3. Explain dependency injection in ASP.NET Core (Transient, Scoped, Singleton)](#43-explain-dependency-injection-in-aspnet-core-transient-scoped-singleton)
    - [4.3.1. Transient](#431-transient)
    - [4.3.2. Scoped](#432-scoped)
    - [4.3.3. Singleton](#433-singleton)
  - [4.4. What are action filters and how do you create custom filters?](#44-what-are-action-filters-and-how-do-you-create-custom-filters)
  - [4.5. Explain the difference between `IActionResult`, `ActionResult<T>`, and returning a concrete type](#45-explain-the-difference-between-iactionresult-actionresultt-and-returning-a-concrete-type)
    - [4.5.1. IActionResult](#451-iactionresult)
    - [4.5.2. ActionResult](#452-actionresult)
    - [4.5.3. Concrete Type](#453-concrete-type)
  - [4.6. What is model binding and validation in ASP.NET Core?](#46-what-is-model-binding-and-validation-in-aspnet-core)
    - [4.6.1. Model Binding](#461-model-binding)
    - [4.6.2. Model Validation](#462-model-validation)
  - [4.7. How do you implement authentication and authorization in ASP.NET Core?](#47-how-do-you-implement-authentication-and-authorization-in-aspnet-core)
  - [4.8. Explain the difference between authentication and authorization.](#48-explain-the-difference-between-authentication-and-authorization)
  - [4.9. What is JWT and how do you implement JWT authentication?](#49-what-is-jwt-and-how-do-you-implement-jwt-authentication)
  - [4.10. How do you handle CORS in ASP.NET Core?](#410-how-do-you-handle-cors-in-aspnet-core)
  - [4.11. What are the different ways to manage application configuration?](#411-what-are-the-different-ways-to-manage-application-configuration)
  - [4.12. Explain routing in ASP.NET Core (conventional vs attribute routing).](#412-explain-routing-in-aspnet-core-conventional-vs-attribute-routing)
  - [4.13. What is Razor Pages and how does it differ from MVC?](#413-what-is-razor-pages-and-how-does-it-differ-from-mvc)
  - [4.14. How do you implement versioning in Web APIs?](#414-how-do-you-implement-versioning-in-web-apis)
  - [4.15. What are health checks in ASP.NET Core?](#415-what-are-health-checks-in-aspnet-core)
- [5. Entity Framework and Database](#5-entity-framework-and-database)
  - [5.1. What is Entity Framework Core and how does it differ from Entity Framework 6?](#51-what-is-entity-framework-core-and-how-does-it-differ-from-entity-framework-6)
  - [5.2. Explain Code First vs Database First approaches.](#52-explain-code-first-vs-database-first-approaches)
  - [5.3. What is the difference between eager loading, lazy loading, and explicit loading?](#53-what-is-the-difference-between-eager-loading-lazy-loading-and-explicit-loading)
  - [5.4. What are migration strategies in EF Core?](#54-what-are-migration-strategies-in-ef-core)
  - [5.5. Explain the Unit of Work and Repository patterns.](#55-explain-the-unit-of-work-and-repository-patterns)
  - [5.6. What is the N+1 query problem and how do you solve it?](#56-what-is-the-n1-query-problem-and-how-do-you-solve-it)
  - [5.7. How do you optimize Entity Framework queries?](#57-how-do-you-optimize-entity-framework-queries)
  - [5.8. Explain tracking vs no-tracking queries in EF Core.](#58-explain-tracking-vs-no-tracking-queries-in-ef-core)
  - [5.9. What are owned entities and table splitting in EF Core?](#59-what-are-owned-entities-and-table-splitting-in-ef-core)
  - [5.10. How do you handle concurrency in Entity Framework?](#510-how-do-you-handle-concurrency-in-entity-framework)
  - [5.11. Explain the difference between `SaveChanges()` and `SaveChangesAsync()`.](#511-explain-the-difference-between-savechanges-and-savechangesasync)
  - [5.12. What are shadow properties in EF Core?](#512-what-are-shadow-properties-in-ef-core)
  - [5.13. How do you handle database transactions in Entity Framework Core?](#513-how-do-you-handle-database-transactions-in-entity-framework-core)
  - [5.14. What are global query filters and how do you use them?](#514-what-are-global-query-filters-and-how-do-you-use-them)
  - [5.15. How do you implement database connection management and connection pooling in EF Core?](#515-how-do-you-implement-database-connection-management-and-connection-pooling-in-ef-core)
- [6. Performance and Memory Management](#6-performance-and-memory-management)
  - [6.1. Explain garbage collection in .NET and its generations.](#61-explain-garbage-collection-in-net-and-its-generations)
  - [6.2. What are memory leaks and how do you identify them in .NET?](#62-what-are-memory-leaks-and-how-do-you-identify-them-in-net)
  - [6.3. What is the difference between stack and heap memory?](#63-what-is-the-difference-between-stack-and-heap-memory)
  - [6.4. How would you profile and optimize a .NET application?](#64-how-would-you-profile-and-optimize-a-net-application)
  - [6.5. What is `Span<T>` and `Memory<T>`? When should you use them?](#65-what-is-spant-and-memoryt-when-should-you-use-them)
  - [6.6. Explain object pooling and when to use it.](#66-explain-object-pooling-and-when-to-use-it)
  - [6.7. What are the best practices for string concatenation in loops?](#67-what-are-the-best-practices-for-string-concatenation-in-loops)
  - [6.8. How do you reduce memory allocations in performance-critical code?](#68-how-do-you-reduce-memory-allocations-in-performance-critical-code)
  - [6.9. What is the Large Object Heap (LOH)?](#69-what-is-the-large-object-heap-loh)
  - [6.10. Explain the concept of weak references](#610-explain-the-concept-of-weak-references)
- [7. LINQ and Collections](#7-linq-and-collections)
  - [7.1. What is LINQ and what are its advantages?](#71-what-is-linq-and-what-are-its-advantages)
  - [7.2. Explain the difference between LINQ query syntax and method syntax.](#72-explain-the-difference-between-linq-query-syntax-and-method-syntax)
  - [7.3. What is the difference between `First()`, `FirstOrDefault()`, `Single()`, and `SingleOrDefault()`?](#73-what-is-the-difference-between-first-firstordefault-single-and-singleordefault)
  - [7.4. Explain deferred execution in LINQ.](#74-explain-deferred-execution-in-linq)
  - [7.5. What is the difference between `Select()` and `SelectMany()`?](#75-what-is-the-difference-between-select-and-selectmany)
  - [7.6. How do you optimize LINQ queries?](#76-how-do-you-optimize-linq-queries)
  - [7.7. What are the differences between `List<T>`, `HashSet<T>`, and `Dictionary<TKey, TValue>`?](#77-what-are-the-differences-between-listt-hashsett-and-dictionarytkey-tvalue)
  - [7.8. When would you use `ConcurrentDictionary` over `Dictionary`?](#78-when-would-you-use-concurrentdictionary-over-dictionary)
  - [7.9. Explain `GroupBy()` and `Join()` operations in LINQ.](#79-explain-groupby-and-join-operations-in-linq)
  - [7.10. What is the difference between `Where().Select()` and `Select().Where()`?](#710-what-is-the-difference-between-whereselect-and-selectwhere)
- [8. Testing](#8-testing)
  - [8.1. What is unit testing and why is it important?](#81-what-is-unit-testing-and-why-is-it-important)
  - [8.2. Explain the AAA pattern (Arrange, Act, Assert)](#82-explain-the-aaa-pattern-arrange-act-assert)
  - [8.3. What is the difference between mocking, stubbing, and faking?](#83-what-is-the-difference-between-mocking-stubbing-and-faking)
  - [8.4. What testing frameworks have you used in .NET (xUnit, NUnit, MSTest)?](#84-what-testing-frameworks-have-you-used-in-net-xunit-nunit-mstest)
  - [8.5. How do you write testable code?](#85-how-do-you-write-testable-code)
  - [8.6. What is TDD (Test-Driven Development)?](#86-what-is-tdd-test-driven-development)
  - [8.7. Explain integration testing vs unit testing](#87-explain-integration-testing-vs-unit-testing)
  - [8.8. What is code coverage and what is a good coverage percentage?](#88-what-is-code-coverage-and-what-is-a-good-coverage-percentage)
- [9. Microservices and Architecture](#9-microservices-and-architecture)
  - [9.1. What are microservices and what are their advantages and disadvantages?](#91-what-are-microservices-and-what-are-their-advantages-and-disadvantages)
  - [9.2. Explain the difference between monolithic and microservices architecture.](#92-explain-the-difference-between-monolithic-and-microservices-architecture)
  - [9.3. What is API Gateway pattern?](#93-what-is-api-gateway-pattern)
  - [9.4. How do you handle inter-service communication in microservices?](#94-how-do-you-handle-inter-service-communication-in-microservices)
  - [9.5. What is the Circuit Breaker pattern?](#95-what-is-the-circuit-breaker-pattern)
  - [9.6. Explain eventual consistency in distributed systems.](#96-explain-eventual-consistency-in-distributed-systems)
  - [9.7. What is the Saga pattern for distributed transactions?](#97-what-is-the-saga-pattern-for-distributed-transactions)
  - [9.8. How do you implement service discovery?](#98-how-do-you-implement-service-discovery)
  - [9.9. What are containers and how do they relate to microservices?](#99-what-are-containers-and-how-do-they-relate-to-microservices)
  - [9.10. Explain the strangler pattern for migrating to microservices.](#910-explain-the-strangler-pattern-for-migrating-to-microservices)
- [10. Security](#10-security)
  - [10.1. What is SQL injection and how do you prevent it?](#101-what-is-sql-injection-and-how-do-you-prevent-it)
  - [10.2. Explain Cross-Site Scripting (XSS) and Cross-Site Request Forgery (CSRF)](#102-explain-cross-site-scripting-xss-and-cross-site-request-forgery-csrf)
  - [10.3. What are the best practices for storing passwords?](#103-what-are-the-best-practices-for-storing-passwords)
  - [10.4. How do you implement OAuth 2.0 and OpenID Connect?](#104-how-do-you-implement-oauth-20-and-openid-connect)
  - [10.5. What is the principle of least privilege?](#105-what-is-the-principle-of-least-privilege)
  - [10.6. How do you secure sensitive data in configuration files?](#106-how-do-you-secure-sensitive-data-in-configuration-files)
  - [10.7. Explain the importance of HTTPS and how to implement it](#107-explain-the-importance-of-https-and-how-to-implement-it)
  - [10.8. What are the OWASP Top 10 security risks?](#108-what-are-the-owasp-top-10-security-risks)
  - [10.9. Security Checklist for .NET Core Applications](#109-security-checklist-for-net-core-applications)
  - [10.10. Additional Resources](#1010-additional-resources)
  - [10.11. Code Examples Summary](#1011-code-examples-summary)
- [11. Domain-Driven Design and Clean Architecture](#11-domain-driven-design-and-clean-architecture)
  - [11.1. What is Domain-Driven Design (DDD) and what are its core principles?](#111-what-is-domain-driven-design-ddd-and-what-are-its-core-principles)
  - [11.2. Explain the difference between Domain, Application, Infrastructure, and Presentation layers in Clean Architecture.](#112-explain-the-difference-between-domain-application-infrastructure-and-presentation-layers-in-clean-architecture)
  - [11.3. What are the main building blocks of DDD (Entities, Value Objects, Aggregates, Domain Services)?](#113-what-are-the-main-building-blocks-of-ddd-entities-value-objects-aggregates-domain-services)
  - [11.4. What is the difference between Entities and Value Objects in DDD?](#114-what-is-the-difference-between-entities-and-value-objects-in-ddd)
  - [11.5. Explain the concept of Aggregates in DDD and how they maintain consistency.](#115-explain-the-concept-of-aggregates-in-ddd-and-how-they-maintain-consistency)
  - [11.6. What are Domain Services and when should you use them?](#116-what-are-domain-services-and-when-should-you-use-them)
  - [11.7. What are Domain Events and how do you implement them in .NET?](#117-what-are-domain-events-and-how-do-you-implement-them-in-net)
  - [11.8. What is the difference between Domain Models and Data Transfer Objects (DTOs)?](#118-what-is-the-difference-between-domain-models-and-data-transfer-objects-dtos)
  - [11.9. How do you implement the CQRS (Command Query Responsibility Segregation) pattern?](#119-how-do-you-implement-the-cqrs-command-query-responsibility-segregation-pattern)
  - [11.10. What is Event Sourcing and how does it relate to DDD?](#1110-what-is-event-sourcing-and-how-does-it-relate-to-ddd)
- [12. DevOps and CI/CD](#12-devops-and-cicd)
  - [12.1. What is CI/CD and why is it important?](#121-what-is-cicd-and-why-is-it-important)
  - [12.2. Have you worked with Docker? Explain containerization.](#122-have-you-worked-with-docker-explain-containerization)
  - [12.3. What is Kubernetes and what problems does it solve?](#123-what-is-kubernetes-and-what-problems-does-it-solve)
  - [12.4. Explain the concept of Infrastructure as Code.](#124-explain-the-concept-of-infrastructure-as-code)
  - [12.5. What Azure/AWS services have you worked with for .NET applications?](#125-what-azureaws-services-have-you-worked-with-for-net-applications)
  - [12.6. Azure Services](#126-azure-services)
  - [12.7. AWS Services](#127-aws-services)
- [13. General and Behavioral](#13-general-and-behavioral)
  - [13.1. How do you stay updated with the latest .NET technologies?](#131-how-do-you-stay-updated-with-the-latest-net-technologies)
  - [13.2. Describe a challenging bug you've encountered and how you resolved it.](#132-describe-a-challenging-bug-youve-encountered-and-how-you-resolved-it)
  - [13.3. How do you handle technical debt in a project?](#133-how-do-you-handle-technical-debt-in-a-project)
  - [13.4. Explain your code review process and what you look for.](#134-explain-your-code-review-process-and-what-you-look-for)
  - [13.5. How do you mentor junior developers on your team?](#135-how-do-you-mentor-junior-developers-on-your-team)






## 1. C# and .NET Fundamentals

### 1.1. What is the CLR, and why is it important?

**Answer:**

The **CLR (Common Language Runtime)** is the execution engine of the .NET platform that provides a managed execution environment for .NET applications. It's a crucial component that sits between your .NET code and the underlying operating system.

**Key Components of the CLR:**

1. **Just-In-Time (JIT) Compiler**
   - Converts CIL (Common Intermediate Language) to native machine code
   - Optimizes code for the specific platform at runtime
   - Enables cross-platform execution

2. **Garbage Collector (GC)**
   - Automatically manages memory allocation and deallocation
   - Prevents memory leaks and dangling pointers
   - Performs automatic cleanup of unused objects

3. **Type System**
   - Enforces type safety and prevents type-related errors
   - Provides metadata about types, methods, and assemblies
   - Enables reflection and dynamic type inspection

4. **Security System**
   - Implements Code Access Security (CAS)
   - Validates code permissions and execution rights
   - Provides sandboxing capabilities

5. **Exception Handling**
   - Provides structured exception handling across languages
   - Ensures consistent error handling behavior
   - Supports stack unwinding and cleanup

**Why the CLR is Important:**

1. **Language Interoperability**
   ```csharp
   // C# code can use VB.NET assemblies and vice versa
   using VBProject;
   
   public class CSharpClass
   {
       public void UseVBNetClass()
       {
           var vbClass = new VBProject.VBNetClass();
           vbClass.DoSomething(); // Seamless interop
       }
   }
   ```

2. **Memory Management**
   ```csharp
   public class MemoryExample
   {
       public void DemonstrateGC()
       {
           // No need to manually free memory
           var largeObject = new byte[1000000];
           // GC automatically handles cleanup when object goes out of scope
       }
   }
   ```

3. **Type Safety**
   ```csharp
   public class TypeSafetyExample
   {
       public void DemonstrateTypeSafety()
       {
           int number = 42;
           // string text = number; // Compile-time error - type safety enforced
           string text = number.ToString(); // Explicit conversion required
       }
   }
   ```

4. **Cross-Platform Execution**
   ```csharp
   // Same C# code runs on Windows, Linux, macOS
   public class CrossPlatformExample
   {
       public void PlatformIndependentCode()
       {
           Console.WriteLine($"Running on: {Environment.OSVersion}");
           // Works on any platform with .NET runtime
       }
   }
   ```

5. **Performance Optimization**
   ```csharp
   public class PerformanceExample
   {
       public void JITOptimization()
       {
           // JIT compiler optimizes this code for the specific CPU
           for (int i = 0; i < 1000000; i++)
           {
               // Hot code gets optimized during execution
               ProcessData(i);
           }
       }
   }
   ```

**CLR Execution Process:**

1. **Compilation**: Source code → CIL (Common Intermediate Language)
2. **Loading**: CLR loads assemblies and metadata
3. **JIT Compilation**: CIL → Native machine code
4. **Execution**: Native code runs with CLR services
5. **Garbage Collection**: Automatic memory management

**CLR Versions and Evolution:**

| .NET Version | CLR Version | Key Features |
|--------------|-------------|--------------|
| .NET Framework 1.0 | CLR 1.0 | Initial release |
| .NET Framework 2.0 | CLR 2.0 | Generics, partial classes |
| .NET Framework 4.0 | CLR 4.0 | Dynamic language runtime |
| .NET Core 1.0 | CoreCLR | Cross-platform, modular |
| .NET 5+ | CoreCLR | Unified platform |

**Benefits of CLR:**

1. **Automatic Memory Management**: No manual memory allocation/deallocation
2. **Exception Safety**: Structured exception handling
3. **Security**: Code access security and validation
4. **Performance**: JIT compilation and optimization
5. **Interoperability**: Language and platform independence
6. **Reliability**: Type safety and runtime checks

**CLR vs Native Code:**

```csharp
// CLR Managed Code
public class ManagedExample
{
    public void ManagedMethod()
    {
        // Automatic memory management
        var list = new List<int>();
        list.Add(1);
        // GC handles cleanup automatically
    }
}

// Unmanaged Code (P/Invoke)
public class UnmanagedExample
{
    [DllImport("kernel32.dll")]
    public static extern IntPtr GetCurrentProcess();
    
    public void UnmanagedMethod()
    {
        // Manual memory management required
        IntPtr handle = GetCurrentProcess();
        // Must manually free resources
    }
}
```

**Key Takeaways:**

1. **CLR** is the execution engine that runs .NET applications
2. **Provides** memory management, type safety, and security
3. **Enables** language interoperability and cross-platform execution
4. **Optimizes** performance through JIT compilation
5. **Essential** for the .NET ecosystem and managed code execution

---

### 1.2. What is CIL (Common Intermediate Language)?

**Answer:**

**CIL (Common Intermediate Language)**, also known as **MSIL (Microsoft Intermediate Language)**, is the intermediate language that all .NET languages compile to. It's a platform-agnostic, object-oriented assembly language that serves as the bridge between high-level .NET languages and the Common Language Runtime (CLR).

**Key Characteristics of CIL:**

1. **Platform Independent**: CIL code can run on any platform with a .NET runtime
2. **Language Agnostic**: All .NET languages compile to the same CIL format
3. **Object-Oriented**: Supports classes, inheritance, polymorphism, and interfaces
4. **Stack-Based**: Uses a stack-based execution model
5. **Strongly Typed**: Enforces type safety at the intermediate language level

**CIL Compilation Process:**

```
Source Code (C#) → CIL → Native Code (JIT)
Source Code (VB.NET) → CIL → Native Code (JIT)
Source Code (F#) → CIL → Native Code (JIT)
```

**Example: C# to CIL Translation**

**C# Source Code:**
```csharp
public class Calculator
{
    public int Add(int a, int b)
    {
        return a + b;
    }
    
    public static void Main()
    {
        var calc = new Calculator();
        int result = calc.Add(5, 3);
        Console.WriteLine(result);
    }
}
```

**Equivalent CIL Code:**
```cil
.class public auto ansi beforefieldinit Calculator
       extends [mscorlib]System.Object
{
  .method public hidebysig instance int32 Add(int32 a, int32 b) cil managed
  {
    .maxstack 2
    .locals init (int32 V_0)
    IL_0000: ldarg.1      // Load first argument (a)
    IL_0001: ldarg.2      // Load second argument (b)
    IL_0002: add          // Add the two values
    IL_0003: stloc.0      // Store result in local variable
    IL_0004: ldloc.0      // Load result
    IL_0005: ret          // Return the result
  }
  
  .method public hidebysig static void Main() cil managed
  {
    .entrypoint
    .maxstack 2
    .locals init (class Calculator V_0, int32 V_1)
    IL_0000: newobj instance void Calculator::.ctor()
    IL_0005: stloc.0
    IL_0006: ldloc.0
    IL_0007: ldc.i4.5
    IL_0008: ldc.i4.3
    IL_0009: callvirt instance int32 Calculator::Add(int32, int32)
    IL_000e: stloc.1
    IL_000f: ldloc.1
    IL_0010: call void [mscorlib]System.Console::WriteLine(int32)
    IL_0015: ret
  }
}
```

**CIL Instruction Types:**

1. **Load Instructions**
   ```cil
   ldarg.0    // Load argument 0 (this)
   ldarg.1    // Load argument 1
   ldloc.0    // Load local variable 0
   ldc.i4.5   // Load constant integer 5
   ```

2. **Store Instructions**
   ```cil
   stloc.0    // Store to local variable 0
   starg.1    // Store to argument 1
   ```

3. **Arithmetic Instructions**
   ```cil
   add        // Addition
   sub        // Subtraction
   mul        // Multiplication
   div        // Division
   ```

4. **Control Flow Instructions**
   ```cil
   br         // Unconditional branch
   brtrue     // Branch if true
   brfalse    // Branch if false
   ret        // Return
   ```

5. **Object Instructions**
   ```cil
   newobj     // Create new object
   call       // Call method
   callvirt   // Call virtual method
   ```

**CIL Metadata:**

CIL assemblies contain rich metadata that describes:

```csharp
// C# code with attributes
[Serializable]
public class Person
{
    [Required]
    public string Name { get; set; }
    
    [Range(0, 120)]
    public int Age { get; set; }
}
```

**CIL Metadata includes:**
- Type definitions and inheritance hierarchies
- Method signatures and implementations
- Field definitions and properties
- Custom attributes and annotations
- Assembly references and dependencies

**Benefits of CIL:**

1. **Language Interoperability**
   ```csharp
   // C# can inherit from VB.NET classes
   public class CSharpClass : VBProject.VBNetBaseClass
   {
       // Seamless inheritance across languages
   }
   ```

2. **Platform Independence**
   ```csharp
   // Same CIL runs on Windows, Linux, macOS
   public class CrossPlatformClass
   {
       public void PlatformIndependentMethod()
       {
           // CIL ensures consistent behavior
       }
   }
   ```

3. **Optimization Opportunities**
   ```csharp
   public class OptimizationExample
   {
       public void OptimizedMethod()
       {
           // JIT compiler can optimize CIL based on runtime conditions
           for (int i = 0; i < 1000000; i++)
           {
               // Hot code gets aggressive optimization
           }
       }
   }
   ```

4. **Security and Verification**
   ```csharp
   public class SecurityExample
   {
       public void SafeMethod()
       {
           // CIL enforces type safety and security policies
           object obj = new string("test");
           // Type safety prevents dangerous operations
       }
   }
   ```

**CIL vs Native Code:**

| Aspect | CIL | Native Code |
|--------|-----|-------------|
| **Platform** | Platform-independent | Platform-specific |
| **Execution** | JIT compiled | Direct execution |
| **Size** | Larger (intermediate) | Smaller (optimized) |
| **Startup** | Slower (JIT overhead) | Faster (no compilation) |
| **Optimization** | Runtime optimization | Compile-time optimization |

**Tools for Working with CIL:**

1. **ILDASM (IL Disassembler)**
   ```bash
   ildasm MyAssembly.dll
   ```

2. **ILASM (IL Assembler)**
   ```bash
   ilasm MyAssembly.il
   ```

3. **Reflection**
   ```csharp
   public class CILInspection
   {
       public void InspectAssembly()
       {
           Assembly assembly = Assembly.LoadFrom("MyAssembly.dll");
           foreach (Type type in assembly.GetTypes())
           {
               Console.WriteLine($"Type: {type.Name}");
               foreach (MethodInfo method in type.GetMethods())
               {
                   Console.WriteLine($"  Method: {method.Name}");
               }
           }
       }
   }
   ```

**CIL in Modern .NET:**

```csharp
// C# 9.0 features compile to CIL
public record Person(string Name, int Age);

public class ModernCILExample
{
    public void DemonstrateModernFeatures()
    {
        // Records, pattern matching, etc. all compile to CIL
        var person = new Person("John", 30);
        var result = person switch
        {
            Person("John", var age) when age > 25 => "Adult John",
            _ => "Other person"
        };
    }
}
```

**Key Takeaways:**

1. **CIL** is the intermediate language all .NET languages compile to
2. **Platform-independent** and language-agnostic
3. **Stack-based** execution model with rich metadata
4. **Enables** language interoperability and cross-platform execution
5. **JIT compiled** to native code for optimal performance
6. **Essential** for understanding .NET's execution model

---

### 1.3. What is the difference between managed and unmanaged code?

**Answer:**

The distinction between **managed** and **unmanaged** code is fundamental to understanding how .NET applications work and how they interact with system resources and external libraries.

**Managed Code:**

Managed code is code that runs under the control of the **Common Language Runtime (CLR)**. The CLR provides automatic memory management, type safety, and other services.

**Characteristics of Managed Code:**

1. **Automatic Memory Management**
   ```csharp
   public class ManagedExample
   {
       public void ManagedMethod()
       {
           // Memory automatically allocated
           var list = new List<int>();
           list.Add(1);
           list.Add(2);
           // Memory automatically freed by Garbage Collector
       }
   }
   ```

2. **Type Safety**
   ```csharp
   public class TypeSafetyExample
   {
       public void SafeOperations()
       {
           int number = 42;
           // string text = number; // Compile-time error
           string text = number.ToString(); // Explicit conversion
           
           // Runtime type checking
           object obj = "Hello";
           if (obj is string str)
           {
               Console.WriteLine(str.ToUpper()); // Safe operation
           }
       }
   }
   ```

3. **Exception Handling**
   ```csharp
   public class ExceptionHandlingExample
   {
       public void ManagedExceptionHandling()
       {
           try
           {
               int result = Divide(10, 0);
           }
           catch (DivideByZeroException ex)
           {
               // Structured exception handling
               Console.WriteLine($"Error: {ex.Message}");
           }
       }
       
       private int Divide(int a, int b)
       {
           return a / b; // Throws managed exception
       }
   }
   ```

4. **Security**
   ```csharp
   public class SecurityExample
   {
       public void SecureOperation()
       {
           // Code Access Security (CAS) applies
           // CLR validates permissions before execution
           File.WriteAllText("test.txt", "Hello World");
       }
   }
   ```

**Unmanaged Code:**

Unmanaged code runs directly on the operating system without the CLR's management. It's typically written in languages like C, C++, or assembly.

**Characteristics of Unmanaged Code:**

1. **Manual Memory Management**
   ```c
   // C code example
   #include <stdlib.h>
   
   void unmanaged_memory_example() {
       // Manual memory allocation
       int* numbers = malloc(100 * sizeof(int));
       
       // Use the memory
       for (int i = 0; i < 100; i++) {
           numbers[i] = i;
       }
       
       // Manual memory deallocation (must not forget!)
       free(numbers);
   }
   ```

2. **Direct System Access**
   ```c
   // C code - direct system calls
   #include <windows.h>
   
   void direct_system_access() {
       // Direct Windows API call
       HANDLE file = CreateFile(
           L"test.txt",
           GENERIC_WRITE,
           0,
           NULL,
           CREATE_ALWAYS,
           FILE_ATTRIBUTE_NORMAL,
           NULL
       );
       
       if (file != INVALID_HANDLE_VALUE) {
           // Use the file handle
           CloseHandle(file); // Manual cleanup
       }
   }
   ```

3. **No Automatic Exception Handling**
   ```c
   // C code - manual error handling
   int divide_numbers(int a, int b) {
       if (b == 0) {
           // Manual error handling - no exceptions
           return -1; // Error code
       }
       return a / b;
   }
   ```

**Interop Between Managed and Unmanaged Code:**

1. **P/Invoke (Platform Invoke)**
   ```csharp
   public class PInvokeExample
   {
       // Import unmanaged Windows API
       [DllImport("kernel32.dll", SetLastError = true)]
       public static extern IntPtr GetCurrentProcess();
       
       [DllImport("user32.dll")]
       public static extern int MessageBox(IntPtr hWnd, string text, string caption, uint type);
       
       public void CallUnmanagedCode()
       {
           // Call unmanaged function from managed code
           IntPtr process = GetCurrentProcess();
           MessageBox(IntPtr.Zero, "Hello from unmanaged code!", "Message", 0);
       }
   }
   ```

2. **COM Interop**
   ```csharp
   public class COMInteropExample
   {
       public void UseCOMObject()
       {
           // Create COM object from managed code
           var excel = new Microsoft.Office.Interop.Excel.Application();
           excel.Visible = true;
           
           // Use COM object
           var workbook = excel.Workbooks.Add();
           var worksheet = workbook.ActiveSheet;
           worksheet.Cells[1, 1] = "Hello from COM!";
           
           // Cleanup (important for COM objects)
           System.Runtime.InteropServices.Marshal.ReleaseComObject(worksheet);
           System.Runtime.InteropServices.Marshal.ReleaseComObject(workbook);
           System.Runtime.InteropServices.Marshal.ReleaseComObject(excel);
       }
   }
   ```

3. **C++/CLI (Managed C++)**
   ```cpp
   // C++/CLI code - can mix managed and unmanaged
   #include <iostream>
   #include <msclr/marshal_cppstd.h>
   
   using namespace System;
   using namespace msclr::interop;
   
   public ref class MixedCode
   {
   public:
       void ManagedMethod()
       {
           Console::WriteLine("This is managed C++");
           UnmanagedMethod(); // Call unmanaged code
       }
       
   private:
       void UnmanagedMethod()
       {
           std::cout << "This is unmanaged C++" << std::endl;
       }
   };
   ```

**Performance Comparison:**

| Aspect | Managed Code | Unmanaged Code |
|--------|--------------|----------------|
| **Memory Management** | Automatic (GC) | Manual |
| **Type Safety** | Enforced | Manual |
| **Exception Handling** | Structured | Manual |
| **Performance** | Slightly slower | Faster |
| **Security** | CLR security | Manual |
| **Development Speed** | Faster | Slower |
| **Debugging** | Easier | Harder |

**Memory Management Comparison:**

```csharp
// Managed Code - Automatic
public class ManagedMemoryExample
{
    public void AutomaticMemoryManagement()
    {
        var largeArray = new byte[1000000];
        // GC automatically handles cleanup
        // No memory leaks (unless circular references)
    }
}

// Unmanaged Code - Manual
public class UnmanagedMemoryExample
{
    public void ManualMemoryManagement()
    {
        IntPtr ptr = Marshal.AllocHGlobal(1000000);
        try
        {
            // Use the memory
            Marshal.WriteByte(ptr, 0, 255);
        }
        finally
        {
            // Must manually free memory
            Marshal.FreeHGlobal(ptr);
        }
    }
}
```

**When to Use Each:**

**Use Managed Code when:**
- Building business applications
- Rapid development is important
- Memory safety is critical
- Cross-platform compatibility needed
- Team productivity is priority

**Use Unmanaged Code when:**
- Maximum performance is required
- Direct hardware access needed
- Interfacing with legacy systems
- Real-time systems
- System-level programming

**Best Practices:**

1. **Prefer Managed Code**
   ```csharp
   // Good - Use managed alternatives
   public class BestPractices
   {
       public void PreferManaged()
       {
           // Use FileStream instead of P/Invoke
           using (var file = new FileStream("test.txt", FileMode.Create))
           {
               // Managed file operations
           }
       }
   }
   ```

2. **Minimize Interop**
   ```csharp
   // Minimize calls across managed/unmanaged boundary
   public class InteropOptimization
   {
       [DllImport("native.dll")]
       private static extern void ProcessData(IntPtr data, int count);
       
       public void OptimizedInterop()
       {
           var data = new byte[1000];
           // Process in batches to minimize interop calls
           for (int i = 0; i < data.Length; i += 100)
           {
               fixed (byte* ptr = &data[i])
               {
                   ProcessData((IntPtr)ptr, 100);
               }
           }
       }
   }
   ```

**Key Takeaways:**

1. **Managed Code** runs under CLR control with automatic services
2. **Unmanaged Code** runs directly on the OS without CLR management
3. **Managed Code** provides safety, productivity, and cross-platform support
4. **Unmanaged Code** provides maximum performance and direct system access
5. **Interop** allows mixing both approaches when needed
6. **Choose** based on requirements: safety vs performance, productivity vs control

---

### 1.4. Explain the difference between value types and reference types in C#.

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

### 1.5. What is the difference between string and StringBuilder? When would you use each?

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

### 1.6. Explain the concepts of boxing and unboxing with performance implications.

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

### 1.7. What are extension methods and when should you use them?

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

### 1.8. Explain the difference between IEnumerable, ICollection, IList, and IQueryable.

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

### 1.9. What is the difference between abstract class and interface? When would you use each?

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

### 1.10. Explain covariance and contravariance in C#.

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

### 1.11. What are delegates, events, and how do they differ?

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

### 1.12. Describe the difference between readonly and const in C#.

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

### 1.13. What is reflection and what are its use cases and drawbacks?

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

### 1.14. Explain the concept of nullable reference types introduced in C# 8.0.

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

### 1.15. What is the difference between Finalize() and Dispose() methods?

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

### 1.16. What is exception handling and how does it work in C#?

**Answer:**

**Exception Handling** is a mechanism in C# that allows you to handle runtime errors gracefully, preventing your application from crashing and providing meaningful error messages to users.

**How Exception Handling Works:**
- When an error occurs, an exception object is created
- The runtime searches for an appropriate exception handler
- If found, the handler executes and the program continues
- If not found, the program terminates with an unhandled exception

**Basic Exception Handling Structure:**
```csharp
try
{
    // Code that might throw an exception
    int result = Divide(10, 0);
}
catch (DivideByZeroException ex)
{
    // Handle specific exception
    Console.WriteLine($"Error: {ex.Message}");
}
catch (Exception ex)
{
    // Handle any other exception
    Console.WriteLine($"Unexpected error: {ex.Message}");
}
finally
{
    // Always executes (cleanup code)
    Console.WriteLine("Cleanup code here");
}
```

**Exception Hierarchy:**
```csharp
System.Object
└── System.Exception
    ├── System.SystemException
    │   ├── ArgumentException
    │   ├── NullReferenceException
    │   ├── IndexOutOfRangeException
    │   └── DivideByZeroException
    └── System.ApplicationException
        └── Custom exceptions
```

**Key Differences: throw vs throw ex vs throw new**

**1. `throw` (rethrow):**
```csharp
try
{
    // Some operation
}
catch (Exception ex)
{
    // Log the exception
    LogError(ex);
    
    // Rethrow the original exception (preserves stack trace)
    throw;  // GOOD - keeps original stack trace
}
```

**2. `throw ex` (lose stack trace):**
```csharp
try
{
    // Some operation
}
catch (Exception ex)
{
    // Log the exception
    LogError(ex);
    
    // Rethrow but lose original stack trace
    throw ex;  // BAD - loses original stack trace
}
```

**3. `throw new` (new exception):**
```csharp
try
{
    // Some operation
}
catch (Exception ex)
{
    // Create new exception with original as inner exception
    throw new CustomException("Something went wrong", ex);  // GOOD
}
```

**When to Use Each:**
- **try-catch**: Handle exceptions you can recover from
- **try-finally**: Ensure cleanup code always runs
- **try-catch-finally**: Handle exceptions AND ensure cleanup

**Custom Exceptions:**
```csharp
// Custom exception class
public class InsufficientFundsException : Exception
{
    public decimal CurrentBalance { get; }
    public decimal RequiredAmount { get; }
    
    public InsufficientFundsException(decimal currentBalance, decimal requiredAmount)
        : base($"Insufficient funds. Current: {currentBalance:C}, Required: {requiredAmount:C}")
    {
        CurrentBalance = currentBalance;
        RequiredAmount = requiredAmount;
    }
    
    public InsufficientFundsException(string message, Exception innerException)
        : base(message, innerException)
    {
    }
}

// Usage
public void Withdraw(decimal amount)
{
    if (amount > Balance)
    {
        throw new InsufficientFundsException(Balance, amount);
    }
    
    Balance -= amount;
}
```

**Best Practices:**
1. **Catch specific exceptions** when possible
2. **Don't catch and ignore** exceptions silently
3. **Use `throw`** instead of `throw ex` to preserve stack trace
4. **Include inner exceptions** when creating new exceptions
5. **Log exceptions** before rethrowing
6. **Use finally blocks** for cleanup code
7. **Don't throw exceptions** for normal program flow

---

### 1.17. What are properties and indexers in C#?

**Answer:**

**Properties** are members that provide a flexible mechanism to read, write, or compute the values of private fields. They act as intermediaries between the outside world and the internal state of a class.

**Basic Property Syntax:**
```csharp
public class Person
{
    private string _name;
    private int _age;
    
    // Traditional property with backing field
    public string Name
    {
        get { return _name; }
        set { _name = value; }
    }
    
    // Auto-property (C# 3.0+)
    public int Age { get; set; }
    
    // Read-only auto-property
    public DateTime CreatedAt { get; } = DateTime.Now;
    
    // Property with validation
    public string Email
    {
        get => _email;
        set
        {
            if (string.IsNullOrEmpty(value) || !value.Contains("@"))
                throw new ArgumentException("Invalid email format");
            _email = value;
        }
    }
    private string _email;
}
```

**Property Types:**

**1. Auto-Properties:**
```csharp
public class Product
{
    // Auto-property with getter and setter
    public string Name { get; set; }
    
    // Read-only auto-property
    public int Id { get; }
    
    // Auto-property with initializer
    public decimal Price { get; set; } = 0m;
    
    // Auto-property with different access modifiers
    public string Description { get; private set; }
}
```

**2. Expression-Bodied Properties (C# 6.0+):**
```csharp
public class Rectangle
{
    public double Width { get; set; }
    public double Height { get; set; }
    
    // Expression-bodied property
    public double Area => Width * Height;
    
    // Expression-bodied property with getter/setter
    public double Perimeter
    {
        get => 2 * (Width + Height);
        set => Width = Height = value / 4; // Square
    }
}
```

**3. Init-Only Properties (C# 9.0+):**
```csharp
public class User
{
    // Can only be set during object initialization
    public string FirstName { get; init; }
    public string LastName { get; init; }
    
    // Computed property
    public string FullName => $"{FirstName} {LastName}";
}

// Usage
var user = new User
{
    FirstName = "John",
    LastName = "Doe"
    // Cannot set FirstName after initialization
    // user.FirstName = "Jane"; // Compile error
};
```

**Indexers:**
Indexers allow objects to be indexed like arrays, providing a way to access elements using square bracket notation.

**Basic Indexer:**
```csharp
public class StringCollection
{
    private string[] _items = new string[10];
    
    // Indexer
    public string this[int index]
    {
        get
        {
            if (index < 0 || index >= _items.Length)
                throw new IndexOutOfRangeException();
            return _items[index];
        }
        set
        {
            if (index < 0 || index >= _items.Length)
                throw new IndexOutOfRangeException();
            _items[index] = value;
        }
    }
}

// Usage
StringCollection collection = new StringCollection();
collection[0] = "Hello";
collection[1] = "World";
Console.WriteLine(collection[0]); // "Hello"
```

**Multi-dimensional Indexers:**
```csharp
public class Matrix
{
    private int[,] _matrix;
    
    public Matrix(int rows, int columns)
    {
        _matrix = new int[rows, columns];
    }
    
    // Multi-dimensional indexer
    public int this[int row, int column]
    {
        get => _matrix[row, column];
        set => _matrix[row, column] = value;
    }
}

// Usage
Matrix matrix = new Matrix(3, 3);
matrix[0, 0] = 1;
matrix[1, 1] = 2;
```

**String-based Indexers:**
```csharp
public class Dictionary
{
    private Dictionary<string, string> _items = new();
    
    // String-based indexer
    public string this[string key]
    {
        get => _items.TryGetValue(key, out string value) ? value : null;
        set => _items[key] = value;
    }
}

// Usage
Dictionary dict = new Dictionary();
dict["name"] = "John";
dict["age"] = "30";
Console.WriteLine(dict["name"]); // "John"
```

**Properties vs Fields:**
```csharp
public class Example
{
    // Field - direct access to memory
    public string FieldName;
    
    // Property - controlled access with logic
    private string _propertyName;
    public string PropertyName
    {
        get => _propertyName;
        set => _propertyName = value?.Trim();
    }
}
```

**Key Differences:**
- **Fields**: Direct memory access, no validation, no side effects
- **Properties**: Controlled access, validation, side effects, encapsulation

**Best Practices:**
1. Use properties for public data access
2. Use fields only for private implementation details
3. Use auto-properties when no validation is needed
4. Use expression-bodied properties for simple computations
5. Use init-only properties for immutable data
6. Validate input in property setters
7. Use indexers when your class represents a collection

---

### 1.18. What are the key differences between .NET Framework, .NET Core, and .NET 5+?

**Answer:**

The .NET ecosystem has evolved significantly, with different versions serving different purposes and platforms.

**Historical Timeline:**
- **.NET Framework (2002)**: Original .NET platform for Windows
- **.NET Core (2016)**: Cross-platform, open-source rewrite
- **.NET 5+ (2020)**: Unified platform combining Framework and Core

**Key Differences:**

| Feature | .NET Framework | .NET Core | .NET 5+ |
|---------|---------------|-----------|---------|
| **Platform Support** | Windows only | Cross-platform | Cross-platform |
| **Open Source** | No | Yes | Yes |
| **Side-by-side** | No | Yes | Yes |
| **Performance** | Good | Better | Best |
| **Deployment** | Framework-dependent | Self-contained | Self-contained |
| **Package Size** | Large | Smaller | Smallest |
| **Docker Support** | Limited | Excellent | Excellent |

**.NET Framework:**
```csharp
// .NET Framework - Windows only
// Uses System.Web for web applications
// Requires .NET Framework runtime installed
// Larger package size
// Limited cross-platform support

// Example: ASP.NET Web Forms (Framework only)
public partial class Default : System.Web.UI.Page
{
    protected void Page_Load(object sender, EventArgs e)
    {
        // Framework-specific code
    }
}
```

**.NET Core:**
```csharp
// .NET Core - Cross-platform
// Modern, lightweight, fast
// Self-contained deployments
// Better performance
// Docker-friendly

// Example: ASP.NET Core Web API
[ApiController]
[Route("api/[controller]")]
public class WeatherController : ControllerBase
{
    [HttpGet]
    public IEnumerable<WeatherForecast> Get()
    {
        // Core-specific code
        return Enumerable.Range(1, 5).Select(index => new WeatherForecast
        {
            Date = DateTime.Now.AddDays(index),
            TemperatureC = Random.Shared.Next(-20, 55)
        });
    }
}
```

**.NET 5+ (Unified):**
```csharp
// .NET 5+ - Best of both worlds
// Single platform for all scenarios
// Improved performance
// Modern language features
// Long-term support versions

// Example: Modern .NET 6+ Web API
var builder = WebApplication.CreateBuilder(args);
var app = builder.Build();

app.MapGet("/", () => "Hello World!");
app.Run();
```

**Migration Path:**
```csharp
// .NET Framework → .NET Core → .NET 5+
// 1. Update project file format
// 2. Replace Framework-specific APIs
// 3. Update dependencies
// 4. Test cross-platform compatibility

// Old .NET Framework project file
<Project ToolsVersion="15.0" xmlns="http://schemas.microsoft.com/developer/msbuild/2003">
  <PropertyGroup>
    <TargetFrameworkVersion>v4.8</TargetFrameworkVersion>
  </PropertyGroup>
</Project>

// New .NET 5+ project file
<Project Sdk="Microsoft.NET.Sdk">
  <PropertyGroup>
    <TargetFramework>net6.0</TargetFramework>
  </PropertyGroup>
</Project>
```

**When to Use Each:**

**.NET Framework:**
- Legacy Windows applications
- When you need Windows-specific features
- Existing applications that are difficult to migrate
- When you need specific Framework-only libraries

**.NET Core:**
- New cross-platform applications
- Microservices and containers
- High-performance scenarios
- Cloud-native applications

**.NET 5+:**
- All new development (recommended)
- Modern applications
- When you want the latest features
- Long-term support and updates

**Performance Comparison:**
```csharp
// Benchmark results (approximate)
// .NET Framework: Baseline
// .NET Core: 2-3x faster
// .NET 5+: 3-4x faster
// .NET 6+: 4-5x faster

// Example: JSON serialization performance
var data = new { Name = "John", Age = 30 };
var json = JsonSerializer.Serialize(data); // Much faster in .NET 5+
```

**Package Size Comparison:**
```
.NET Framework: ~50MB (runtime)
.NET Core: ~30MB (runtime)
.NET 5+: ~25MB (runtime)
Self-contained: ~100MB+ (includes runtime)
```

**API Differences:**
```csharp
// .NET Framework
using System.Web;
using System.Web.Mvc;

// .NET Core/5+
using Microsoft.AspNetCore.Mvc;
using Microsoft.Extensions.DependencyInjection;

// Configuration differences
// Framework: web.config, app.config
// Core/5+: appsettings.json, environment variables
```

**Best Practices:**
1. **Use .NET 5+** for all new development
2. **Migrate gradually** from Framework to .NET 5+
3. **Test thoroughly** when migrating
4. **Use self-contained deployments** for containers
5. **Leverage cross-platform benefits** when possible
6. **Keep dependencies updated** for security and performance

---

### 1.19. What are assemblies and namespaces in .NET?

**Answer:**

**Assemblies** are the fundamental unit of deployment and versioning in .NET. They contain compiled code, metadata, and resources that make up a .NET application.

**Namespaces** are logical groupings of related types that help organize code and avoid naming conflicts.

**Assemblies:**

**What is an Assembly:**
- A compiled unit of code (usually a .dll or .exe file)
- Contains Intermediate Language (IL) code, metadata, and resources
- The smallest unit of deployment in .NET
- Has a unique identity (name, version, culture, public key)

**Assembly Structure:**
```
MyAssembly.dll
├── Assembly Manifest (metadata)
├── Type Metadata
├── IL Code
├── Resources (images, strings, etc.)
└── Security Information
```

**Types of Assemblies:**
```csharp
// 1. Executable Assembly (.exe)
// Contains an entry point (Main method)
// Can be run directly

// 2. Library Assembly (.dll)
// Contains reusable code
// Cannot be run directly
// Referenced by other assemblies

// Example: Creating a library assembly
namespace MyLibrary
{
    public class Calculator
    {
        public int Add(int a, int b) => a + b;
        public int Multiply(int a, int b) => a * b;
    }
}

// Compile to: MyLibrary.dll
```

**Assembly Manifest:**
```csharp
// Assembly information (in AssemblyInfo.cs or project file)
[assembly: AssemblyTitle("MyApplication")]
[assembly: AssemblyDescription("A sample application")]
[assembly: AssemblyVersion("1.0.0.0")]
[assembly: AssemblyFileVersion("1.0.0.0")]
[assembly: AssemblyCompany("MyCompany")]
[assembly: AssemblyProduct("MyProduct")]
[assembly: AssemblyCopyright("Copyright © 2024")]
```

**Global Assembly Cache (GAC):**
```csharp
// GAC is a machine-wide cache for shared assemblies
// Only available in .NET Framework (not in .NET Core/5+)
// Used for system assemblies and shared libraries

// Installing to GAC (Framework only)
gacutil -i MyAssembly.dll

// Strong-named assemblies can be installed in GAC
[assembly: AssemblyKeyFile("MyKey.snk")]
```

**Namespaces:**

**What is a Namespace:**
- A logical grouping of related types
- Helps avoid naming conflicts
- Provides a hierarchical organization
- Similar to folders in a file system

**Namespace Declaration:**
```csharp
// Single namespace
namespace MyCompany.MyProject
{
    public class User { }
    public class Product { }
}

// Multiple namespaces in same file
namespace MyCompany.MyProject.Data
{
    public class UserRepository { }
}

namespace MyCompany.MyProject.Services
{
    public class UserService { }
}

// Nested namespaces
namespace MyCompany
{
    namespace MyProject
    {
        namespace Data
        {
            public class UserRepository { }
        }
    }
}
```

**Using Namespaces:**
```csharp
// Fully qualified name
MyCompany.MyProject.User user = new MyCompany.MyProject.User();

// Using directive
using MyCompany.MyProject;
User user = new User();

// Using alias
using Data = MyCompany.MyProject.Data;
Data.UserRepository repo = new Data.UserRepository();

// Global using (C# 10+)
global using System;
global using System.Collections.Generic;
```

**Assembly vs Namespace Relationship:**
```csharp
// One assembly can contain multiple namespaces
// MyLibrary.dll contains:
namespace MyCompany.Data
{
    public class UserRepository { }
}

namespace MyCompany.Services
{
    public class UserService { }
}

// Multiple assemblies can contain the same namespace
// MyLibrary1.dll and MyLibrary2.dll both contain:
namespace MyCompany.Common
{
    // Different types in each assembly
}
```

**Assembly Loading:**
```csharp
// Load assembly dynamically
Assembly assembly = Assembly.LoadFrom("MyLibrary.dll");
Type type = assembly.GetType("MyCompany.MyClass");
object instance = Activator.CreateInstance(type);

// Get all types in assembly
Assembly currentAssembly = Assembly.GetExecutingAssembly();
Type[] types = currentAssembly.GetTypes();

// Get assembly from type
Assembly userAssembly = typeof(User).Assembly;
```

**Best Practices:**

**Assemblies:**
1. **Keep assemblies focused** - one responsibility per assembly
2. **Use strong naming** for shared libraries
3. **Version your assemblies** properly
4. **Minimize assembly dependencies** to reduce complexity
5. **Use assembly attributes** for metadata

**Namespaces:**
1. **Follow naming conventions** - Company.Project.Feature
2. **Keep namespaces shallow** - avoid deep nesting
3. **Use meaningful names** that describe the purpose
4. **Group related types** together
5. **Avoid namespace conflicts** with well-known libraries

**Example Project Structure:**
```
MyProject/
├── MyProject.Core/           (Assembly)
│   ├── Models/              (Namespace)
│   │   ├── User.cs
│   │   └── Product.cs
│   └── Interfaces/          (Namespace)
│       └── IRepository.cs
├── MyProject.Data/          (Assembly)
│   └── Repositories/        (Namespace)
│       └── UserRepository.cs
└── MyProject.Web/           (Assembly)
    └── Controllers/         (Namespace)
        └── UserController.cs
```

---

### 1.20. What are lambda expressions and how do they work in C#?

**Answer:**

**Lambda Expressions** are anonymous functions that allow you to write inline code blocks that can be passed as arguments to methods or assigned to variables. They provide a concise way to represent delegates or expression trees.

**Basic Lambda Syntax:**
```csharp
// Lambda expression syntax: (parameters) => expression
// Simple lambda
Func<int, int> square = x => x * x;
int result = square(5); // 25

// Lambda with multiple parameters
Func<int, int, int> add = (x, y) => x + y;
int sum = add(3, 4); // 7

// Lambda with no parameters
Func<string> getMessage = () => "Hello World";
string message = getMessage(); // "Hello World"
```

**Lambda vs Anonymous Methods:**
```csharp
// Anonymous method (C# 2.0)
Func<int, int> oldWay = delegate(int x) { return x * x; };

// Lambda expression (C# 3.0+) - more concise
Func<int, int> newWay = x => x * x;

// Both do the same thing, but lambda is cleaner
```

**Lambda with LINQ:**
```csharp
List<int> numbers = new List<int> { 1, 2, 3, 4, 5, 6, 7, 8, 9, 10 };

// Using lambda with LINQ methods
var evenNumbers = numbers.Where(x => x % 2 == 0);
var doubled = numbers.Select(x => x * 2);
var sum = numbers.Aggregate((x, y) => x + y);

// Lambda with complex expressions
var result = numbers
    .Where(x => x > 5)
    .Select(x => x * x)
    .OrderByDescending(x => x);
```

**Lambda with Events:**
```csharp
public class Button
{
    public event EventHandler Click;
    
    protected virtual void OnClick()
    {
        Click?.Invoke(this, EventArgs.Empty);
    }
}

// Using lambda with events
Button button = new Button();
button.Click += (sender, e) => Console.WriteLine("Button clicked!");
button.Click += (sender, e) => MessageBox.Show("Hello!");
```

**Lambda with Action and Func:**
```csharp
// Action - no return value
Action<string> printMessage = message => Console.WriteLine(message);
printMessage("Hello"); // Prints "Hello"

// Action with multiple parameters
Action<string, int> printMessageWithCount = (msg, count) => 
    Console.WriteLine($"{msg} (Count: {count})");

// Func - with return value
Func<int, int, int> multiply = (x, y) => x * y;
int product = multiply(3, 4); // 12

// Func with different return types
Func<string, int> getLength = str => str.Length;
int length = getLength("Hello"); // 5
```

**Lambda with Complex Logic:**
```csharp
// Lambda with multiple statements (use braces)
Func<int, int> complexOperation = x =>
{
    int temp = x * 2;
    if (temp > 10)
        return temp + 5;
    else
        return temp - 2;
};

// Lambda with local variables
Func<int, int> factorial = n =>
{
    int result = 1;
    for (int i = 1; i <= n; i++)
        result *= i;
    return result;
};
```

**Lambda with Predicates:**
```csharp
// Predicate<T> - returns bool
Predicate<int> isEven = x => x % 2 == 0;
bool result = isEven(4); // true

// Using with List<T>.FindAll
List<int> numbers = new List<int> { 1, 2, 3, 4, 5, 6 };
var evenNumbers = numbers.FindAll(x => x % 2 == 0); // [2, 4, 6]
```

**Lambda with Custom Delegates:**
```csharp
// Custom delegate
public delegate int MathOperation(int x, int y);

// Using lambda with custom delegate
MathOperation add = (x, y) => x + y;
MathOperation multiply = (x, y) => x * y;

int sum = add(5, 3); // 8
int product = multiply(5, 3); // 15
```

**Lambda with Expression Trees:**
```csharp
using System.Linq.Expressions;

// Expression tree - represents code as data
Expression<Func<int, int, int>> expression = (x, y) => x + y;

// Can be compiled to executable code
Func<int, int, int> compiled = expression.Compile();
int result = compiled(3, 4); // 7

// Can be analyzed and modified
BinaryExpression body = (BinaryExpression)expression.Body;
ParameterExpression left = (ParameterExpression)body.Left;
ParameterExpression right = (ParameterExpression)body.Right;
```

**Lambda with Closures:**
```csharp
// Lambda captures variables from outer scope
int multiplier = 10;
Func<int, int> multiplyByTen = x => x * multiplier;

int result = multiplyByTen(5); // 50

// Changing the captured variable affects the lambda
multiplier = 20;
int newResult = multiplyByTen(5); // 100
```

**Lambda with Async/Await:**
```csharp
// Async lambda
Func<Task<string>> asyncLambda = async () =>
{
    await Task.Delay(1000);
    return "Async result";
};

// Using async lambda
string result = await asyncLambda();
```

**When to Use Lambda Expressions:**
1. **LINQ operations** - Where, Select, OrderBy, etc.
2. **Event handlers** - Simple event handling
3. **Callback functions** - Passing behavior as parameters
4. **Functional programming** - Map, filter, reduce operations
5. **Short, simple operations** - One-liner functions

**When NOT to Use Lambda Expressions:**
1. **Complex logic** - Use regular methods instead
2. **Reusable code** - Create named methods
3. **Performance-critical code** - Regular methods might be faster
4. **Debugging** - Harder to debug than named methods

**Best Practices:**
1. **Keep lambdas simple** - avoid complex logic
2. **Use meaningful parameter names** when possible
3. **Consider readability** - don't sacrifice clarity for brevity
4. **Use parentheses** for multiple parameters: `(x, y) => x + y`
5. **Use braces** for multiple statements: `x => { /* multiple statements */ }`

---

### 1.21. What are the fundamental concepts of threading in .NET?

**Answer:**

**Threading** allows your application to perform multiple operations concurrently, improving responsiveness and utilizing multiple CPU cores effectively.

**Basic Threading Concepts:**

**Thread vs Process:**
```csharp
// Process: Complete application with its own memory space
// Thread: Unit of execution within a process
// A process can have multiple threads

// Creating a new thread
Thread newThread = new Thread(() =>
{
    Console.WriteLine("Running on background thread");
    Thread.Sleep(2000);
    Console.WriteLine("Background thread completed");
});

newThread.Start();
Console.WriteLine("Main thread continues...");
```

**Thread Class:**
```csharp
public class ThreadExample
{
    public static void Main()
    {
        // Create and start a thread
        Thread workerThread = new Thread(DoWork);
        workerThread.Start();
        
        // Main thread continues
        for (int i = 0; i < 5; i++)
        {
            Console.WriteLine($"Main thread: {i}");
            Thread.Sleep(500);
        }
        
        // Wait for worker thread to complete
        workerThread.Join();
        Console.WriteLine("All threads completed");
    }
    
    static void DoWork()
    {
        for (int i = 0; i < 5; i++)
        {
            Console.WriteLine($"Worker thread: {i}");
            Thread.Sleep(300);
        }
    }
}
```

**ThreadPool:**
```csharp
// ThreadPool manages a pool of worker threads
// More efficient than creating new threads manually
// Automatically manages thread lifecycle

public class ThreadPoolExample
{
    public static void Main()
    {
        // Queue work to ThreadPool
        ThreadPool.QueueUserWorkItem(DoWork, "Task 1");
        ThreadPool.QueueUserWorkItem(DoWork, "Task 2");
        ThreadPool.QueueUserWorkItem(DoWork, "Task 3");
        
        Console.WriteLine("Main thread continues...");
        Thread.Sleep(3000); // Wait for tasks to complete
    }
    
    static void DoWork(object state)
    {
        string taskName = (string)state;
        Console.WriteLine($"ThreadPool thread executing: {taskName}");
        Thread.Sleep(1000);
        Console.WriteLine($"Completed: {taskName}");
    }
}
```

**Race Conditions:**
```csharp
// Race condition example
public class RaceConditionExample
{
    private static int counter = 0;
    
    public static void Main()
    {
        // Start multiple threads that modify shared data
        Thread[] threads = new Thread[5];
        
        for (int i = 0; i < 5; i++)
        {
            threads[i] = new Thread(IncrementCounter);
            threads[i].Start();
        }
        
        // Wait for all threads
        foreach (Thread thread in threads)
        {
            thread.Join();
        }
        
        Console.WriteLine($"Final counter value: {counter}");
        // Expected: 5000, Actual: varies due to race condition
    }
    
    static void IncrementCounter()
    {
        for (int i = 0; i < 1000; i++)
        {
            counter++; // Race condition here!
        }
    }
}
```

**Thread Synchronization:**

**1. Lock Statement:**
```csharp
public class SynchronizedExample
{
    private static int counter = 0;
    private static readonly object lockObject = new object();
    
    public static void Main()
    {
        Thread[] threads = new Thread[5];
        
        for (int i = 0; i < 5; i++)
        {
            threads[i] = new Thread(IncrementCounterSafely);
            threads[i].Start();
        }
        
        foreach (Thread thread in threads)
        {
            thread.Join();
        }
        
        Console.WriteLine($"Final counter value: {counter}"); // Always 5000
    }
    
    static void IncrementCounterSafely()
    {
        for (int i = 0; i < 1000; i++)
        {
            lock (lockObject) // Thread-safe increment
            {
                counter++;
            }
        }
    }
}
```

**2. Monitor Class:**
```csharp
public class MonitorExample
{
    private static readonly object lockObject = new object();
    
    public static void Main()
    {
        Thread thread1 = new Thread(DoWorkWithMonitor);
        Thread thread2 = new Thread(DoWorkWithMonitor);
        
        thread1.Start();
        thread2.Start();
        
        thread1.Join();
        thread2.Join();
    }
    
    static void DoWorkWithMonitor()
    {
        Monitor.Enter(lockObject);
        try
        {
            Console.WriteLine($"Thread {Thread.CurrentThread.ManagedThreadId} acquired lock");
            Thread.Sleep(2000);
        }
        finally
        {
            Monitor.Exit(lockObject);
            Console.WriteLine($"Thread {Thread.CurrentThread.ManagedThreadId} released lock");
        }
    }
}
```

**3. Mutex:**
```csharp
public class MutexExample
{
    private static Mutex mutex = new Mutex();
    
    public static void Main()
    {
        Thread[] threads = new Thread[3];
        
        for (int i = 0; i < 3; i++)
        {
            threads[i] = new Thread(DoWorkWithMutex);
            threads[i].Start();
        }
        
        foreach (Thread thread in threads)
        {
            thread.Join();
        }
    }
    
    static void DoWorkWithMutex()
    {
        mutex.WaitOne(); // Acquire mutex
        try
        {
            Console.WriteLine($"Thread {Thread.CurrentThread.ManagedThreadId} in critical section");
            Thread.Sleep(1000);
        }
        finally
        {
            mutex.ReleaseMutex(); // Release mutex
        }
    }
}
```

**Thread vs Task:**
```csharp
// Thread - lower level, more control
Thread thread = new Thread(() =>
{
    Console.WriteLine("Thread-based work");
});
thread.Start();

// Task - higher level, better for most scenarios
Task task = Task.Run(() =>
{
    Console.WriteLine("Task-based work");
});

// Task with return value
Task<int> taskWithResult = Task.Run(() =>
{
    Thread.Sleep(1000);
    return 42;
});

int result = await taskWithResult;
Console.WriteLine($"Result: {result}");
```

**Thread Safety:**
```csharp
public class ThreadSafeCounter
{
    private int _count = 0;
    private readonly object _lock = new object();
    
    public int Count
    {
        get
        {
            lock (_lock)
            {
                return _count;
            }
        }
    }
    
    public void Increment()
    {
        lock (_lock)
        {
            _count++;
        }
    }
    
    public void Decrement()
    {
        lock (_lock)
        {
            _count--;
        }
    }
}
```

**Best Practices:**
1. **Use Task instead of Thread** for most scenarios
2. **Avoid shared mutable state** when possible
3. **Use appropriate synchronization** mechanisms
4. **Don't lock on public objects** or types
5. **Keep critical sections short** to avoid blocking
6. **Use thread-safe collections** when available
7. **Avoid Thread.Sleep** in production code
8. **Use async/await** for I/O operations

**Common Threading Issues:**
1. **Race conditions** - multiple threads accessing shared data
2. **Deadlocks** - threads waiting for each other indefinitely
3. **Starvation** - some threads never get CPU time
4. **Context switching overhead** - too many threads can hurt performance

---

## 2. Object-Oriented Programming

### 2.1. Explain the four pillars of OOP with real-world examples.

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

### 2.2. What is the SOLID principle? Explain each letter with examples.

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


### 2.3. What is the difference between method overloading and method overriding?

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

### 2.4. Explain the concept of polymorphism with examples.

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

### 2.5. What are sealed classes and sealed methods?

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

### 2.6. Describe the difference between composition and inheritance.

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

### 2.7. What is the Liskov Substitution Principle and why is it important?

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

### 2.8. Explain dependency injection and its benefits.

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

### 2.9. What are design patterns? Name and explain 5 commonly used patterns.

**Design Patterns** are reusable solutions to common software design problems. They represent best practices and provide a template for solving specific issues in software development.

#### 2.9.1. Singleton Pattern
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

#### 2.9.2. Factory Pattern
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

#### 2.9.3. Observer Pattern
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

#### 2.9.4. Strategy Pattern
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

#### 2.9.5. Repository Pattern
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

### 2.10. What is the difference between shallow copy and deep copy?

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

### 2.11. What is the difference between virtual, override, and new keywords in C#?

**Answer:**

These three keywords control how methods behave in inheritance hierarchies and are fundamental to understanding polymorphism in C#.

**1. `virtual` Keyword:**
- Marks a method in the base class as **overridable**
- Allows derived classes to provide their own implementation
- Enables **runtime polymorphism**

**2. `override` Keyword:**
- Used in derived classes to **replace** the virtual method implementation
- Provides **runtime polymorphism** - the correct method is called based on the actual object type
- Must override a virtual, abstract, or override method

**3. `new` Keyword:**
- Used for **method hiding** (not overriding)
- Creates a new method that **hides** the base class method
- Provides **compile-time polymorphism** - method called depends on reference type, not object type

**Example:**

```csharp
public class Animal
{
    // Virtual method - can be overridden
    public virtual void MakeSound()
    {
        Console.WriteLine("Animal makes a sound");
    }
    
    // Regular method - can be hidden with 'new'
    public void Move()
    {
        Console.WriteLine("Animal moves");
    }
}

public class Dog : Animal
{
    // Override - runtime polymorphism
    public override void MakeSound()
    {
        Console.WriteLine("Dog barks: Woof!");
    }
    
    // Method hiding with 'new' - compile-time polymorphism
    public new void Move()
    {
        Console.WriteLine("Dog runs on four legs");
    }
}

public class Cat : Animal
{
    // Override - runtime polymorphism
    public override void MakeSound()
    {
        Console.WriteLine("Cat meows: Meow!");
    }
    
    // Method hiding with 'new' - compile-time polymorphism
    public new void Move()
    {
        Console.WriteLine("Cat walks gracefully");
    }
}

// Demonstration of the differences
public class PolymorphismDemo
{
    public static void DemonstratePolymorphism()
    {
        // Runtime Polymorphism (override)
        Animal animal1 = new Dog();
        Animal animal2 = new Cat();
        
        // Calls the overridden method based on actual object type
        animal1.MakeSound(); // Output: "Dog barks: Woof!"
        animal2.MakeSound(); // Output: "Cat meows: Meow!"
        
        // Compile-time Polymorphism (new)
        // Calls the method based on reference type, not object type
        animal1.Move(); // Output: "Animal moves" (base class method)
        animal2.Move(); // Output: "Animal moves" (base class method)
        
        // To call the hidden method, need to cast to derived type
        ((Dog)animal1).Move(); // Output: "Dog runs on four legs"
        ((Cat)animal2).Move(); // Output: "Cat walks gracefully"
        
        // Direct instantiation calls the correct method
        Dog dog = new Dog();
        Cat cat = new Cat();
        
        dog.MakeSound(); // Output: "Dog barks: Woof!"
        dog.Move();      // Output: "Dog runs on four legs"
        
        cat.MakeSound(); // Output: "Cat meows: Meow!"
        cat.Move();      // Output: "Cat walks gracefully"
    }
}
```

**Advanced Example with Method Chaining:**

```csharp
public class Vehicle
{
    public virtual void Start()
    {
        Console.WriteLine("Vehicle started");
    }
    
    public virtual void Stop()
    {
        Console.WriteLine("Vehicle stopped");
    }
    
    // Virtual method that can be overridden
    public virtual void DisplayInfo()
    {
        Console.WriteLine("This is a vehicle");
    }
}

public class Car : Vehicle
{
    public override void Start()
    {
        Console.WriteLine("Car engine started");
        base.Start(); // Call base implementation
    }
    
    public override void Stop()
    {
        Console.WriteLine("Car engine stopped");
        base.Stop(); // Call base implementation
    }
    
    // Override with additional functionality
    public override void DisplayInfo()
    {
        base.DisplayInfo(); // Call base method
        Console.WriteLine("It has 4 wheels");
    }
}

public class ElectricCar : Car
{
    public override void Start()
    {
        Console.WriteLine("Electric car booting up...");
        // Don't call base.Start() - we want different behavior
        Console.WriteLine("Electric car ready");
    }
    
    // Hide the Stop method with new implementation
    public new void Stop()
    {
        Console.WriteLine("Electric car shutting down");
        // This doesn't call the base Stop method
    }
}

// Usage
Vehicle vehicle = new ElectricCar();
vehicle.Start(); // Calls ElectricCar.Start() - runtime polymorphism
vehicle.Stop();  // Calls Vehicle.Stop() - compile-time polymorphism (hiding)

ElectricCar electricCar = new ElectricCar();
electricCar.Stop(); // Calls ElectricCar.Stop() - the hidden method
```

**Key Differences Summary:**

| Aspect | `virtual` | `override` | `new` |
|--------|-----------|------------|-------|
| **Purpose** | Makes method overridable | Replaces virtual method | Hides base method |
| **Polymorphism** | Enables runtime | Runtime polymorphism | Compile-time binding |
| **Method Resolution** | Based on object type | Based on object type | Based on reference type |
| **Base Method Call** | Can call with `base.` | Can call with `base.` | Cannot call base method |
| **When to Use** | Base class design | Derived class implementation | Method hiding scenarios |

**Best Practices:**
- Use `virtual` in base classes when you want derived classes to customize behavior
- Use `override` when you want true polymorphism and method replacement
- Use `new` sparingly - only when you need to hide a method and don't want polymorphism
- Prefer `override` over `new` for better object-oriented design
- Always call `base.MethodName()` in overrides when you want to extend, not replace, functionality

---

### 2.12. What are access modifiers in C# and when would you use each?

**Answer:**

Access modifiers control the visibility and accessibility of classes, methods, properties, and other members in C#. They are fundamental to encapsulation and object-oriented design.

**Available Access Modifiers:**

**1. `public` - Most Permissive**
- Accessible from anywhere
- No restrictions on access

**2. `private` - Most Restrictive**
- Only accessible within the same class
- Default for class members

**3. `protected` - Family Access**
- Accessible within the same class and derived classes
- Not accessible from outside the inheritance hierarchy

**4. `internal` - Assembly Access**
- Accessible within the same assembly (project)
- Default for classes and interfaces

**5. `protected internal` - Family or Assembly Access**
- Accessible within the same assembly OR derived classes (even in different assemblies)

**6. `private protected` - Family and Assembly Access (C# 7.2+)**
- Accessible within the same class, derived classes, AND same assembly

**Example:**

```csharp
// Assembly: MyLibrary.dll
namespace MyLibrary
{
    // Internal class - only accessible within this assembly
    internal class InternalHelper
    {
        public void DoWork() { }
    }
    
    // Public class - accessible from other assemblies
    public class BankAccount
    {
        // Private field - only accessible within this class
        private decimal balance;
        private string accountNumber;
        
        // Protected field - accessible in derived classes
        protected DateTime lastTransactionDate;
        
        // Internal field - accessible within this assembly
        internal string internalNotes;
        
        // Protected internal - accessible in derived classes OR same assembly
        protected internal string specialNotes;
        
        // Private protected - accessible in derived classes AND same assembly
        private protected string confidentialNotes;
        
        // Public constructor
        public BankAccount(string accountNumber, decimal initialBalance)
        {
            this.accountNumber = accountNumber;
            this.balance = initialBalance;
            lastTransactionDate = DateTime.Now;
        }
        
        // Public property - accessible from anywhere
        public decimal Balance
        {
            get { return balance; }
            private set // Private setter - only this class can modify
            {
                if (value < 0)
                    throw new ArgumentException("Balance cannot be negative");
                balance = value;
            }
        }
        
        // Public method - accessible from anywhere
        public void Deposit(decimal amount)
        {
            if (amount <= 0)
                throw new ArgumentException("Amount must be positive");
            
            Balance += amount;
            lastTransactionDate = DateTime.Now;
            LogTransaction("Deposit", amount);
        }
        
        // Protected method - accessible in derived classes
        protected virtual void LogTransaction(string type, decimal amount)
        {
            Console.WriteLine($"{type}: {amount:C} on {lastTransactionDate}");
        }
        
        // Internal method - accessible within this assembly
        internal void InternalAudit()
        {
            Console.WriteLine($"Internal audit for account {accountNumber}");
        }
        
        // Private method - only accessible within this class
        private void ValidateAccount()
        {
            if (string.IsNullOrEmpty(accountNumber))
                throw new InvalidOperationException("Invalid account number");
        }
    }
    
    // Derived class in the same assembly
    public class SavingsAccount : BankAccount
    {
        private decimal interestRate;
        
        public SavingsAccount(string accountNumber, decimal initialBalance, decimal interestRate)
            : base(accountNumber, initialBalance)
        {
            this.interestRate = interestRate;
        }
        
        // Can access protected members
        public void ApplyInterest()
        {
            decimal interest = Balance * interestRate;
            Balance += interest; // Can access protected setter through property
            lastTransactionDate = DateTime.Now; // Can access protected field
            LogTransaction("Interest", interest); // Can access protected method
        }
        
        // Can access protected internal members
        public void UpdateSpecialNotes(string notes)
        {
            specialNotes = notes; // Accessible
        }
        
        // Can access private protected members
        public void UpdateConfidentialNotes(string notes)
        {
            confidentialNotes = notes; // Accessible (same assembly + derived)
        }
        
        // Override protected method
        protected override void LogTransaction(string type, decimal amount)
        {
            base.LogTransaction(type, amount);
            Console.WriteLine($"Interest Rate: {interestRate:P}");
        }
    }
}

// Assembly: MyApplication.exe (references MyLibrary.dll)
namespace MyApplication
{
    public class Program
    {
        public static void Main()
        {
            var account = new BankAccount("123456", 1000);
            
            // Public members - accessible
            account.Deposit(500);
            Console.WriteLine($"Balance: {account.Balance}");
            
            // Internal members - NOT accessible (different assembly)
            // account.InternalAudit(); // Compilation error
            
            // Protected members - NOT accessible (not derived class)
            // account.lastTransactionDate = DateTime.Now; // Compilation error
            
            // Private members - NOT accessible
            // account.balance = 2000; // Compilation error
            
            var savingsAccount = new SavingsAccount("789012", 2000, 0.05m);
            savingsAccount.ApplyInterest();
            savingsAccount.UpdateSpecialNotes("VIP Customer");
        }
    }
    
    // Derived class in different assembly
    public class CheckingAccount : BankAccount
    {
        public CheckingAccount(string accountNumber, decimal initialBalance)
            : base(accountNumber, initialBalance)
        {
        }
        
        // Can access protected members
        public void ProcessCheck(decimal amount)
        {
            Balance -= amount; // Can access protected setter
            lastTransactionDate = DateTime.Now; // Can access protected field
        }
        
        // Can access protected internal members
        public void UpdateSpecialNotes(string notes)
        {
            specialNotes = notes; // Accessible (derived class)
        }
        
        // CANNOT access private protected members (different assembly)
        // public void UpdateConfidentialNotes(string notes)
        // {
        //     confidentialNotes = notes; // Compilation error
        // }
    }
}
```

**Access Modifier Guidelines:**

**When to use `public`:**
- API surface that external code needs to use
- Properties that represent the object's state
- Methods that provide core functionality

**When to use `private`:**
- Implementation details that should be hidden
- Helper methods used only within the class
- Fields that should only be modified through properties

**When to use `protected`:**
- Members that derived classes need to access
- Virtual methods that can be overridden
- Fields that derived classes need to modify

**When to use `internal`:**
- Classes that are implementation details of your library
- Methods that should only be used within your assembly
- Testing utilities that shouldn't be exposed publicly

**When to use `protected internal`:**
- Members that derived classes OR assembly code needs
- Rarely used - consider if you really need this level of access

**When to use `private protected`:**
- Members that only derived classes in the same assembly should access
- Very specific use case - rarely needed

**Default Access Levels:**
- **Class members**: `private`
- **Classes and interfaces**: `internal`
- **Namespaces**: Always `public` (cannot be modified)

**Best Practices:**
- Start with the most restrictive access level (`private`)
- Only increase visibility when necessary
- Use properties instead of public fields
- Prefer `protected` over `protected internal` when possible
- Document public APIs thoroughly
- Use `internal` for testing utilities

---

### 2.13. What is the difference between static and instance members?

**Answer:**

**Static members** belong to the class itself, while **instance members** belong to individual objects (instances) of the class. This fundamental difference affects memory allocation, access patterns, and usage scenarios.

**Key Differences:**

| Aspect | Static Members | Instance Members |
|--------|----------------|------------------|
| **Memory** | One copy per class | One copy per instance |
| **Access** | Accessed via class name | Accessed via object reference |
| **Lifecycle** | Created when class is first used | Created when object is instantiated |
| **Context** | No access to instance data | Can access both instance and static data |
| **Thread Safety** | Shared across all instances | Each instance has its own copy |

**Example:**

```csharp
public class Counter
{
    // Static field - shared across all instances
    private static int totalCount = 0;
    
    // Instance field - each object has its own copy
    private int instanceCount = 0;
    
    // Static property - accessed via class name
    public static int TotalCount
    {
        get { return totalCount; }
        private set { totalCount = value; }
    }
    
    // Instance property - accessed via object reference
    public int InstanceCount
    {
        get { return instanceCount; }
        private set { instanceCount = value; }
    }
    
    // Static constructor - called once when class is first used
    static Counter()
    {
        Console.WriteLine("Static constructor called - Counter class initialized");
        TotalCount = 0;
    }
    
    // Instance constructor - called for each new object
    public Counter()
    {
        Console.WriteLine("Instance constructor called - new Counter created");
        InstanceCount = 0;
    }
    
    // Static method - can only access static members
    public static void ResetTotalCount()
    {
        TotalCount = 0;
        Console.WriteLine("Total count reset to 0");
    }
    
    // Instance method - can access both static and instance members
    public void Increment()
    {
        InstanceCount++;
        TotalCount++; // Can access static members from instance methods
        Console.WriteLine($"Instance count: {InstanceCount}, Total count: {TotalCount}");
    }
    
    // Static method that creates and returns instances
    public static Counter CreateCounter()
    {
        return new Counter();
    }
    
    // Instance method that uses static members
    public void DisplayStats()
    {
        Console.WriteLine($"This counter: {InstanceCount}");
        Console.WriteLine($"All counters total: {TotalCount}");
    }
}

// Usage demonstration
public class StaticVsInstanceDemo
{
    public static void Demonstrate()
    {
        Console.WriteLine("=== Static vs Instance Members Demo ===");
        
        // Access static members via class name
        Console.WriteLine($"Initial total count: {Counter.TotalCount}");
        Counter.ResetTotalCount();
        
        // Create instances
        Counter counter1 = new Counter();
        Counter counter2 = new Counter();
        Counter counter3 = new Counter();
        
        // Use instance methods
        counter1.Increment(); // Instance: 1, Total: 1
        counter1.Increment(); // Instance: 2, Total: 2
        
        counter2.Increment(); // Instance: 1, Total: 3
        counter2.Increment(); // Instance: 2, Total: 4
        counter2.Increment(); // Instance: 3, Total: 5
        
        counter3.Increment(); // Instance: 1, Total: 6
        
        // Display stats for each instance
        counter1.DisplayStats();
        counter2.DisplayStats();
        counter3.DisplayStats();
        
        // Static count is shared across all instances
        Console.WriteLine($"Final total count: {Counter.TotalCount}");
    }
}
```

**Advanced Example - Utility Classes:**

```csharp
// Static utility class - cannot be instantiated
public static class MathUtils
{
    // Static constants
    public const double PI = 3.14159265359;
    public const double E = 2.71828182846;
    
    // Static readonly field
    private static readonly Random random = new Random();
    
    // Static methods - no instance needed
    public static double CalculateCircleArea(double radius)
    {
        return PI * radius * radius;
    }
    
    public static double CalculateHypotenuse(double a, double b)
    {
        return Math.Sqrt(a * a + b * b);
    }
    
    public static int GetRandomNumber(int min, int max)
    {
        return random.Next(min, max + 1);
    }
    
    // Static method with generic type
    public static T Max<T>(T a, T b) where T : IComparable<T>
    {
        return a.CompareTo(b) > 0 ? a : b;
    }
}

// Instance class with both static and instance members
public class BankAccount
{
    // Static field - shared across all accounts
    private static int nextAccountNumber = 1000;
    
    // Static property
    public static int NextAccountNumber => nextAccountNumber;
    
    // Instance fields
    private int accountNumber;
    private decimal balance;
    private string accountHolder;
    
    // Static method to generate account numbers
    public static int GenerateAccountNumber()
    {
        return ++nextAccountNumber;
    }
    
    // Instance constructor
    public BankAccount(string accountHolder, decimal initialBalance)
    {
        this.accountNumber = GenerateAccountNumber(); // Uses static method
        this.accountHolder = accountHolder;
        this.balance = initialBalance;
    }
    
    // Instance methods
    public void Deposit(decimal amount)
    {
        balance += amount;
    }
    
    public void Withdraw(decimal amount)
    {
        if (balance >= amount)
            balance -= amount;
        else
            throw new InvalidOperationException("Insufficient funds");
    }
    
    // Instance method that uses static members
    public void DisplayAccountInfo()
    {
        Console.WriteLine($"Account #{accountNumber}");
        Console.WriteLine($"Holder: {accountHolder}");
        Console.WriteLine($"Balance: {balance:C}");
        Console.WriteLine($"Next account number will be: {NextAccountNumber}");
    }
}

// Usage
public class Program
{
    public static void Main()
    {
        // Use static utility methods
        double area = MathUtils.CalculateCircleArea(5.0);
        double hypotenuse = MathUtils.CalculateHypotenuse(3.0, 4.0);
        int randomNum = MathUtils.GetRandomNumber(1, 100);
        
        Console.WriteLine($"Circle area: {area:F2}");
        Console.WriteLine($"Hypotenuse: {hypotenuse:F2}");
        Console.WriteLine($"Random number: {randomNum}");
        
        // Create bank accounts
        var account1 = new BankAccount("John Doe", 1000);
        var account2 = new BankAccount("Jane Smith", 2000);
        
        account1.DisplayAccountInfo();
        account2.DisplayAccountInfo();
        
        // Static members are shared
        Console.WriteLine($"Next account number: {BankAccount.NextAccountNumber}");
    }
}
```

**When to Use Static Members:**

**Use static for:**
- Utility methods that don't need instance data
- Constants and configuration values
- Factory methods
- Extension methods
- Mathematical operations
- Caching mechanisms
- Logging utilities

**Use instance members for:**
- Data that varies per object
- Methods that operate on object state
- Properties that represent object characteristics
- Methods that need access to instance fields

**Important Considerations:**

**Static Members:**
- Cannot access instance members directly
- Are shared across all instances (thread safety concerns)
- Cannot be overridden (but can be hidden with `new`)
- Cannot implement interfaces (except for static interface members in C# 8+)

**Instance Members:**
- Can access both static and instance members
- Each instance has its own copy
- Can be virtual and overridden
- Can implement interface members

**Best Practices:**
- Use static for stateless operations
- Use instance for stateful operations
- Be careful with static mutable data (thread safety)
- Prefer instance members for testability
- Use static constructors for one-time initialization
- Consider using static classes for utility functions

---

### 2.14. What are constructors and destructors in C#?

**Answer:**

**Constructors** are special methods that initialize objects when they are created, while **destructors** (finalizers) are special methods that clean up resources when objects are destroyed by the garbage collector.

**Constructor Types:**

**1. Default Constructor**
- Parameterless constructor
- Automatically provided if no constructors are defined
- Initializes fields to default values

**2. Parameterized Constructor**
- Takes parameters to initialize the object
- Allows custom initialization

**3. Copy Constructor**
- Creates a new object by copying another object
- Useful for creating deep copies

**4. Static Constructor**
- Initializes static members
- Called once before the class is first used

**Example:**

```csharp
public class Person
{
    // Fields
    private string name;
    private int age;
    private DateTime birthDate;
    private static int totalPersons = 0;
    
    // Static constructor - called once when class is first used
    static Person()
    {
        Console.WriteLine("Person class initialized");
        totalPersons = 0;
    }
    
    // Default constructor
    public Person()
    {
        Console.WriteLine("Default constructor called");
        name = "Unknown";
        age = 0;
        birthDate = DateTime.MinValue;
        totalPersons++;
    }
    
    // Parameterized constructor
    public Person(string name, int age)
    {
        Console.WriteLine($"Parameterized constructor called for {name}");
        this.name = name;
        this.age = age;
        this.birthDate = DateTime.Now.AddYears(-age);
        totalPersons++;
    }
    
    // Copy constructor
    public Person(Person other)
    {
        Console.WriteLine($"Copy constructor called for {other.name}");
        this.name = other.name;
        this.age = other.age;
        this.birthDate = other.birthDate;
        totalPersons++;
    }
    
    // Constructor chaining using 'this'
    public Person(string name) : this(name, 0)
    {
        Console.WriteLine("Constructor chaining - calling parameterized constructor");
    }
    
    // Properties
    public string Name
    {
        get => name;
        set => name = value ?? throw new ArgumentNullException(nameof(value));
    }
    
    public int Age
    {
        get => age;
        set => age = value >= 0 ? value : throw new ArgumentException("Age cannot be negative");
    }
    
    public static int TotalPersons => totalPersons;
    
    // Methods
    public void DisplayInfo()
    {
        Console.WriteLine($"Name: {name}, Age: {age}, Born: {birthDate:yyyy-MM-dd}");
    }
    
    // Destructor (Finalizer) - called by garbage collector
    ~Person()
    {
        Console.WriteLine($"Destructor called for {name}");
        totalPersons--;
    }
}

// Advanced example with resource management
public class FileManager : IDisposable
{
    private string fileName;
    private FileStream fileStream;
    private bool disposed = false;
    
    // Constructor with file validation
    public FileManager(string fileName)
    {
        if (string.IsNullOrEmpty(fileName))
            throw new ArgumentException("File name cannot be null or empty");
        
        this.fileName = fileName;
        Console.WriteLine($"FileManager created for: {fileName}");
    }
    
    // Method to open file
    public void OpenFile()
    {
        if (fileStream != null)
            throw new InvalidOperationException("File is already open");
        
        try
        {
            fileStream = File.Open(fileName, FileMode.OpenOrCreate);
            Console.WriteLine($"File opened: {fileName}");
        }
        catch (Exception ex)
        {
            throw new InvalidOperationException($"Failed to open file: {ex.Message}");
        }
    }
    
    // Method to write data
    public void WriteData(string data)
    {
        if (fileStream == null)
            throw new InvalidOperationException("File is not open");
        
        byte[] bytes = Encoding.UTF8.GetBytes(data);
        fileStream.Write(bytes, 0, bytes.Length);
        fileStream.Flush();
        Console.WriteLine($"Data written to {fileName}");
    }
    
    // Destructor - backup cleanup (not guaranteed to be called)
    ~FileManager()
    {
        Console.WriteLine($"Destructor called for {fileName}");
        Dispose(false);
    }
    
    // IDisposable implementation for proper resource cleanup
    public void Dispose()
    {
        Dispose(true);
        GC.SuppressFinalize(this); // Prevents destructor from being called
    }
    
    protected virtual void Dispose(bool disposing)
    {
        if (!disposed)
        {
            if (disposing)
            {
                // Dispose managed resources
                fileStream?.Dispose();
                Console.WriteLine($"File closed: {fileName}");
            }
            
            // Dispose unmanaged resources (if any)
            disposed = true;
        }
    }
}

// Constructor inheritance example
public class Animal
{
    protected string species;
    protected int age;
    
    // Base class constructor
    public Animal(string species, int age)
    {
        this.species = species;
        this.age = age;
        Console.WriteLine($"Animal constructor: {species}, {age} years old");
    }
    
    public virtual void MakeSound()
    {
        Console.WriteLine("Animal makes a sound");
    }
}

public class Dog : Animal
{
    private string breed;
    
    // Derived class constructor - must call base constructor
    public Dog(string breed, int age) : base("Canine", age)
    {
        this.breed = breed;
        Console.WriteLine($"Dog constructor: {breed} breed");
    }
    
    // Constructor with default breed
    public Dog(int age) : this("Mixed", age)
    {
        Console.WriteLine("Dog constructor with default breed");
    }
    
    public override void MakeSound()
    {
        Console.WriteLine($"{breed} dog barks: Woof!");
    }
    
    public void DisplayInfo()
    {
        Console.WriteLine($"Species: {species}, Breed: {breed}, Age: {age}");
    }
}

// Usage demonstration
public class ConstructorDestructorDemo
{
    public static void Demonstrate()
    {
        Console.WriteLine("=== Constructor and Destructor Demo ===");
        
        // Default constructor
        var person1 = new Person();
        person1.DisplayInfo();
        
        // Parameterized constructor
        var person2 = new Person("John Doe", 30);
        person2.DisplayInfo();
        
        // Constructor chaining
        var person3 = new Person("Jane Smith");
        person3.DisplayInfo();
        
        // Copy constructor
        var person4 = new Person(person2);
        person4.DisplayInfo();
        
        // Constructor inheritance
        var dog = new Dog("Golden Retriever", 3);
        dog.DisplayInfo();
        dog.MakeSound();
        
        // Resource management with using statement
        using (var fileManager = new FileManager("test.txt"))
        {
            fileManager.OpenFile();
            fileManager.WriteData("Hello, World!");
        } // Dispose() is called automatically
        
        Console.WriteLine($"Total persons created: {Person.TotalPersons}");
        
        // Force garbage collection to see destructors
        person1 = null;
        person2 = null;
        person3 = null;
        person4 = null;
        GC.Collect();
        GC.WaitForPendingFinalizers();
    }
}
```

**Constructor Best Practices:**

**1. Constructor Chaining:**
```csharp
public class Employee
{
    private string name;
    private int id;
    private string department;
    
    // Chain constructors to avoid code duplication
    public Employee(string name) : this(name, 0, "Unknown")
    {
    }
    
    public Employee(string name, int id) : this(name, id, "Unknown")
    {
    }
    
    public Employee(string name, int id, string department)
    {
        this.name = name;
        this.id = id;
        this.department = department;
    }
}
```

**2. Validation in Constructors:**
```csharp
public class BankAccount
{
    private string accountNumber;
    private decimal balance;
    
    public BankAccount(string accountNumber, decimal initialBalance)
    {
        // Validate parameters
        if (string.IsNullOrWhiteSpace(accountNumber))
            throw new ArgumentException("Account number cannot be null or empty");
        
        if (initialBalance < 0)
            throw new ArgumentException("Initial balance cannot be negative");
        
        this.accountNumber = accountNumber;
        this.balance = initialBalance;
    }
}
```

**Destructor Guidelines:**

**When to use destructors:**
- Clean up unmanaged resources as a safety net
- Log object destruction for debugging
- Update static counters or statistics

**When NOT to use destructors:**
- Don't rely on them for critical cleanup
- Don't perform time-consuming operations
- Don't access other managed objects (they might be finalized)

**Best Practices:**
- Implement `IDisposable` for proper resource management
- Use `using` statements for automatic disposal
- Call `GC.SuppressFinalize(this)` in `Dispose()`
- Keep destructors simple and fast
- Use constructor chaining to avoid code duplication
- Validate parameters in constructors
- Make constructors fail fast with clear error messages

---

### 2.15. What is method hiding and how does it differ from method overriding?

**Answer:**

**Method hiding** uses the `new` keyword to hide a base class method, while **method overriding** uses the `override` keyword to replace a virtual method. The key difference is in **when** the method resolution occurs and **how** polymorphism behaves.

**Key Differences:**

| Aspect | Method Hiding (`new`) | Method Overriding (`override`) |
|--------|----------------------|-------------------------------|
| **Resolution** | Compile-time | Runtime |
| **Polymorphism** | Based on reference type | Based on object type |
| **Base Method** | Cannot call base method | Can call base method with `base.` |
| **Virtual Required** | No (can hide any method) | Yes (must be virtual/abstract/override) |
| **Method Signature** | Must match exactly | Must match exactly |

**Example:**

```csharp
public class Animal
{
    // Virtual method - can be overridden
    public virtual void MakeSound()
    {
        Console.WriteLine("Animal makes a sound");
    }
    
    // Regular method - can be hidden
    public void Move()
    {
        Console.WriteLine("Animal moves");
    }
    
    // Virtual method for demonstration
    public virtual void Sleep()
    {
        Console.WriteLine("Animal sleeps");
    }
}

public class Dog : Animal
{
    // Method Overriding - runtime polymorphism
    public override void MakeSound()
    {
        Console.WriteLine("Dog barks: Woof!");
    }
    
    // Method Hiding - compile-time polymorphism
    public new void Move()
    {
        Console.WriteLine("Dog runs on four legs");
    }
    
    // Method Hiding with new keyword (explicit)
    public new void Sleep()
    {
        Console.WriteLine("Dog sleeps in a dog bed");
    }
}

public class Cat : Animal
{
    // Method Overriding
    public override void MakeSound()
    {
        Console.WriteLine("Cat meows: Meow!");
    }
    
    // Method Hiding
    public new void Move()
    {
        Console.WriteLine("Cat walks gracefully");
    }
    
    // Method Hiding
    public new void Sleep()
    {
        Console.WriteLine("Cat sleeps on a windowsill");
    }
}

// Demonstration of the differences
public class MethodHidingVsOverridingDemo
{
    public static void Demonstrate()
    {
        Console.WriteLine("=== Method Hiding vs Overriding Demo ===");
        
        // Create objects
        Animal animal1 = new Dog();
        Animal animal2 = new Cat();
        
        Dog dog = new Dog();
        Cat cat = new Cat();
        
        Console.WriteLine("\n--- Runtime Polymorphism (Override) ---");
        // Method resolution based on ACTUAL object type
        animal1.MakeSound(); // Calls Dog.MakeSound() - runtime polymorphism
        animal2.MakeSound(); // Calls Cat.MakeSound() - runtime polymorphism
        
        Console.WriteLine("\n--- Compile-time Polymorphism (Hiding) ---");
        // Method resolution based on REFERENCE type
        animal1.Move(); // Calls Animal.Move() - compile-time polymorphism
        animal2.Move(); // Calls Animal.Move() - compile-time polymorphism
        
        animal1.Sleep(); // Calls Animal.Sleep() - compile-time polymorphism
        animal2.Sleep(); // Calls Animal.Sleep() - compile-time polymorphism
        
        Console.WriteLine("\n--- Direct Object Access ---");
        // When accessing directly, the hidden method is called
        dog.Move();  // Calls Dog.Move()
        cat.Move();  // Calls Cat.Move()
        
        dog.Sleep(); // Calls Dog.Sleep()
        cat.Sleep(); // Calls Cat.Sleep()
        
        Console.WriteLine("\n--- Casting to Access Hidden Methods ---");
        // To call the hidden method through base reference, cast to derived type
        ((Dog)animal1).Move();  // Calls Dog.Move()
        ((Cat)animal2).Move();  // Calls Cat.Move()
    }
}
```

**Advanced Example with Method Chaining:**

```csharp
public class Vehicle
{
    public virtual void Start()
    {
        Console.WriteLine("Vehicle started");
    }
    
    public virtual void Stop()
    {
        Console.WriteLine("Vehicle stopped");
    }
    
    // Regular method that can be hidden
    public void DisplayInfo()
    {
        Console.WriteLine("This is a vehicle");
    }
    
    // Virtual method for overriding
    public virtual void Maintenance()
    {
        Console.WriteLine("Performing general vehicle maintenance");
    }
}

public class Car : Vehicle
{
    // Override - can call base method
    public override void Start()
    {
        Console.WriteLine("Car engine started");
        base.Start(); // Can call base implementation
    }
    
    // Override - can call base method
    public override void Stop()
    {
        Console.WriteLine("Car engine stopped");
        base.Stop(); // Can call base implementation
    }
    
    // Method hiding - cannot call base method directly
    public new void DisplayInfo()
    {
        Console.WriteLine("This is a car with 4 wheels");
        // Cannot call base.DisplayInfo() directly
        // Would need to cast: ((Vehicle)this).DisplayInfo();
    }
    
    // Method hiding with new keyword
    public new void Maintenance()
    {
        Console.WriteLine("Performing car-specific maintenance");
        Console.WriteLine("- Checking oil");
        Console.WriteLine("- Checking tires");
        // Cannot call base.Maintenance() directly
    }
}

public class ElectricCar : Car
{
    // Override the overridden method
    public override void Start()
    {
        Console.WriteLine("Electric car booting up...");
        base.Start(); // Calls Car.Start()
    }
    
    // Hide the overridden method (not recommended)
    public new void Stop()
    {
        Console.WriteLine("Electric car shutting down");
        // This hides Car.Stop(), not Vehicle.Stop()
    }
    
    // Override the hidden method
    public override void Maintenance()
    {
        Console.WriteLine("Performing electric car maintenance");
        Console.WriteLine("- Checking battery");
        Console.WriteLine("- Checking electric systems");
        base.Maintenance(); // Calls Car.Maintenance()
    }
}

// Usage demonstration
public class AdvancedDemo
{
    public static void Demonstrate()
    {
        Console.WriteLine("=== Advanced Method Hiding vs Overriding ===");
        
        Vehicle vehicle = new ElectricCar();
        
        Console.WriteLine("\n--- Through Vehicle Reference ---");
        vehicle.Start();        // Calls ElectricCar.Start() (override chain)
        vehicle.Stop();         // Calls Car.Stop() (override)
        vehicle.DisplayInfo();  // Calls Vehicle.DisplayInfo() (hiding)
        vehicle.Maintenance();  // Calls Car.Maintenance() (override)
        
        Console.WriteLine("\n--- Through Car Reference ---");
        Car car = new ElectricCar();
        car.Start();        // Calls ElectricCar.Start()
        car.Stop();         // Calls Car.Stop()
        car.DisplayInfo();  // Calls Car.DisplayInfo() (hiding)
        car.Maintenance();  // Calls Car.Maintenance()
        
        Console.WriteLine("\n--- Through ElectricCar Reference ---");
        ElectricCar electricCar = new ElectricCar();
        electricCar.Start();        // Calls ElectricCar.Start()
        electricCar.Stop();         // Calls ElectricCar.Stop() (hiding)
        electricCar.DisplayInfo();  // Calls Car.DisplayInfo() (hiding)
        electricCar.Maintenance();  // Calls ElectricCar.Maintenance()
    }
}
```

**When to Use Method Hiding:**

**Use `new` (method hiding) when:**
- You want to provide a completely different implementation
- The base method is not virtual and you can't override it
- You want compile-time method resolution
- You're implementing a different interface or behavior

**Use `override` (method overriding) when:**
- You want true polymorphism
- You want to extend or modify base behavior
- You want runtime method resolution
- You're following the Liskov Substitution Principle

**Best Practices:**

**1. Prefer Override over Hiding:**
```csharp
// Good: Use override for polymorphism
public class BaseClass
{
    public virtual void Method() { }
}

public class DerivedClass : BaseClass
{
    public override void Method() // Preferred
    {
        base.Method(); // Can call base implementation
    }
}

// Avoid: Method hiding unless necessary
public class DerivedClass2 : BaseClass
{
    public new void Method() // Avoid unless you have a good reason
    {
        // Cannot call base.Method() directly
    }
}
```

**2. Be Explicit with `new` Keyword:**
```csharp
public class DerivedClass : BaseClass
{
    // Explicitly use 'new' to show intent
    public new void Method()
    {
        // Implementation
    }
}
```

**3. Document the Intent:**
```csharp
public class DerivedClass : BaseClass
{
    /// <summary>
    /// Hides the base class method with a different implementation.
    /// This method provides car-specific behavior and does not call the base method.
    /// </summary>
    public new void Method()
    {
        // Implementation
    }
}
```

**Common Pitfalls:**

1. **Accidental Hiding:** Forgetting to use `override` when you meant to override
2. **Confusing Behavior:** Method hiding can be confusing because it breaks polymorphism
3. **Cannot Call Base:** Hidden methods cannot call the base method directly
4. **Compile-time Resolution:** Method hiding uses compile-time resolution, which can be unexpected

**Summary:**
- Use `override` for true polymorphism and when you want to extend base behavior
- Use `new` only when you need to hide a method and provide completely different behavior
- Always be explicit about your intent
- Prefer `override` over `new` in most scenarios
- Document why you're using method hiding

---

### 2.16. What are partial classes and partial methods in C#?

**Answer:**

**Partial classes** allow you to split a single class definition across multiple files, while **partial methods** allow you to declare a method in one part and optionally implement it in another part. This is particularly useful for code generation, designer files, and organizing large classes.

**Partial Classes:**

**Benefits:**
- Split large classes across multiple files
- Separate generated code from hand-written code
- Organize related functionality
- Enable multiple developers to work on the same class

**Example:**

```csharp
// File: Person.cs
public partial class Person
{
    private string firstName;
    private string lastName;
    
    public Person(string firstName, string lastName)
    {
        this.firstName = firstName;
        this.lastName = lastName;
    }
    
    public string GetFullName()
    {
        return $"{firstName} {lastName}";
    }
}

// File: Person.Properties.cs
public partial class Person
{
    public string FirstName
    {
        get => firstName;
        set => firstName = value ?? throw new ArgumentNullException(nameof(value));
    }
    
    public string LastName
    {
        get => lastName;
        set => lastName = value ?? throw new ArgumentNullException(nameof(value));
    }
    
    public int Age { get; set; }
    public string Email { get; set; }
}

// File: Person.Methods.cs
public partial class Person
{
    public void DisplayInfo()
    {
        Console.WriteLine($"Name: {GetFullName()}");
        Console.WriteLine($"Age: {Age}");
        Console.WriteLine($"Email: {Email}");
    }
    
    public bool IsAdult()
    {
        return Age >= 18;
    }
    
    public void SendEmail(string subject, string body)
    {
        if (string.IsNullOrEmpty(Email))
            throw new InvalidOperationException("Email address is not set");
        
        Console.WriteLine($"Sending email to {Email}");
        Console.WriteLine($"Subject: {subject}");
        Console.WriteLine($"Body: {body}");
    }
}

// File: Person.Validation.cs
public partial class Person
{
    public bool Validate()
    {
        return !string.IsNullOrEmpty(firstName) &&
               !string.IsNullOrEmpty(lastName) &&
               Age >= 0 &&
               IsValidEmail(Email);
    }
    
    private bool IsValidEmail(string email)
    {
        return !string.IsNullOrEmpty(email) && email.Contains("@");
    }
}
```

**Advanced Example - Code Generation Scenario:**

```csharp
// File: User.cs (Hand-written code)
public partial class User
{
    private int id;
    private string username;
    private string email;
    
    public User(string username, string email)
    {
        this.username = username;
        this.email = email;
    }
    
    // Hand-written business logic
    public bool IsActive()
    {
        return !string.IsNullOrEmpty(username) && !string.IsNullOrEmpty(email);
    }
    
    public void UpdateProfile(string newEmail)
    {
        if (IsValidEmail(newEmail))
        {
            email = newEmail;
            OnProfileUpdated(); // Partial method call
        }
    }
    
    // Partial method declaration - implemented in generated code
    partial void OnProfileUpdated();
    
    // Partial method for validation - implemented in generated code
    partial void ValidateUser();
    
    private bool IsValidEmail(string email)
    {
        return !string.IsNullOrEmpty(email) && email.Contains("@");
    }
}

// File: User.Generated.cs (Generated code - e.g., from Entity Framework)
public partial class User
{
    // Generated properties
    public int Id
    {
        get => id;
        set => id = value;
    }
    
    public string Username
    {
        get => username;
        set => username = value;
    }
    
    public string Email
    {
        get => email;
        set => email = value;
    }
    
    // Generated methods
    public override string ToString()
    {
        return $"User: {username} ({email})";
    }
    
    public override bool Equals(object obj)
    {
        if (obj is User other)
            return id == other.id;
        return false;
    }
    
    public override int GetHashCode()
    {
        return id.GetHashCode();
    }
    
    // Partial method implementations
    partial void OnProfileUpdated()
    {
        Console.WriteLine($"Profile updated for user: {username}");
        // Could trigger events, update database, etc.
    }
    
    partial void ValidateUser()
    {
        if (string.IsNullOrEmpty(username))
            throw new InvalidOperationException("Username is required");
        
        if (string.IsNullOrEmpty(email))
            throw new InvalidOperationException("Email is required");
    }
}
```

**Partial Methods:**

**Characteristics:**
- Must be declared with `partial` keyword
- Must return `void`
- Cannot have access modifiers (implicitly `private`)
- Cannot be `virtual`, `override`, `sealed`, or `extern`
- Can have `ref` and `out` parameters
- If not implemented, the compiler removes the method call

**Example:**

```csharp
// File: DataProcessor.cs
public partial class DataProcessor
{
    private List<string> data;
    
    public DataProcessor()
    {
        data = new List<string>();
    }
    
    public void ProcessData()
    {
        Console.WriteLine("Starting data processing...");
        
        // Partial method calls - will be removed if not implemented
        OnProcessingStarted();
        
        foreach (var item in data)
        {
            ProcessItem(item);
            OnItemProcessed(item);
        }
        
        OnProcessingCompleted();
        Console.WriteLine("Data processing completed.");
    }
    
    private void ProcessItem(string item)
    {
        // Process the item
        Console.WriteLine($"Processing: {item}");
    }
    
    // Partial method declarations
    partial void OnProcessingStarted();
    partial void OnItemProcessed(string item);
    partial void OnProcessingCompleted();
    partial void OnError(string error);
}

// File: DataProcessor.Logging.cs
public partial class DataProcessor
{
    // Implement some partial methods
    partial void OnProcessingStarted()
    {
        Console.WriteLine("LOG: Processing started at " + DateTime.Now);
    }
    
    partial void OnItemProcessed(string item)
    {
        Console.WriteLine($"LOG: Processed item: {item}");
    }
    
    partial void OnProcessingCompleted()
    {
        Console.WriteLine("LOG: Processing completed at " + DateTime.Now);
    }
    
    // OnError is not implemented, so calls to it will be removed by compiler
}

// File: DataProcessor.Monitoring.cs
public partial class DataProcessor
{
    private int processedCount = 0;
    
    // Override the implementation from Logging.cs
    partial void OnItemProcessed(string item)
    {
        processedCount++;
        Console.WriteLine($"MONITOR: Item {processedCount} processed: {item}");
    }
    
    partial void OnProcessingCompleted()
    {
        Console.WriteLine($"MONITOR: Total items processed: {processedCount}");
    }
}
```

**Real-world Example - Entity Framework:**

```csharp
// File: Customer.cs (Hand-written)
public partial class Customer
{
    public Customer()
    {
        Orders = new HashSet<Order>();
    }
    
    // Hand-written business logic
    public bool IsVIP()
    {
        return Orders.Count > 10 || TotalSpent > 10000;
    }
    
    public void AddOrder(Order order)
    {
        Orders.Add(order);
        OnOrderAdded(order);
    }
    
    // Partial methods for extensibility
    partial void OnOrderAdded(Order order);
    partial void OnCustomerUpdated();
}

// File: Customer.Designer.cs (Generated by EF)
public partial class Customer
{
    public int CustomerId { get; set; }
    public string FirstName { get; set; }
    public string LastName { get; set; }
    public string Email { get; set; }
    public DateTime CreatedDate { get; set; }
    public decimal TotalSpent { get; set; }
    
    public virtual ICollection<Order> Orders { get; set; }
    
    // Generated partial method implementations
    partial void OnOrderAdded(Order order)
    {
        // Could update TotalSpent, send notifications, etc.
        TotalSpent += order.TotalAmount;
    }
    
    partial void OnCustomerUpdated()
    {
        // Could log changes, update audit trail, etc.
        Console.WriteLine($"Customer {CustomerId} was updated");
    }
}
```

**Usage and Best Practices:**

```csharp
public class PartialClassDemo
{
    public static void Demonstrate()
    {
        Console.WriteLine("=== Partial Classes and Methods Demo ===");
        
        // Create and use partial class
        var person = new Person("John", "Doe");
        person.Age = 30;
        person.Email = "john.doe@example.com";
        person.DisplayInfo();
        
        // Use partial methods
        var processor = new DataProcessor();
        processor.ProcessData();
        
        // Entity Framework example
        var customer = new Customer();
        customer.FirstName = "Jane";
        customer.LastName = "Smith";
        customer.Email = "jane.smith@example.com";
        
        var order = new Order { TotalAmount = 150.00m };
        customer.AddOrder(order); // Triggers partial method
        
        Console.WriteLine($"Customer is VIP: {customer.IsVIP()}");
    }
}
```

**Best Practices:**

**For Partial Classes:**
- Use for code generation scenarios
- Organize large classes logically
- Keep related functionality together
- Use consistent naming conventions
- Document the purpose of each partial class

**For Partial Methods:**
- Use for optional extensibility points
- Keep method signatures simple
- Don't rely on partial methods for critical functionality
- Use for logging, validation, and notification scenarios
- Consider using events instead for complex scenarios

**When to Use:**
- **Partial Classes:** Code generation, large classes, multiple developers
- **Partial Methods:** Optional extensibility, code generation hooks, lightweight events

**When NOT to Use:**
- Don't use partial classes just to organize small classes
- Don't use partial methods for complex logic
- Don't rely on partial methods for critical functionality

---

## 3. Asynchronous Programming

### 3.1. Explain `async` and `await` keywords in C#.

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

### 3.2. What is the difference between `Task` and `Thread`?

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

### 3.3. What is `Task.Run()` vs `Task.Factory.StartNew()`?

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

### 3.4. Explain what `ConfigureAwait(false)` does and when to use it.

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

### 3.5. What is a deadlock and how can async/await cause it?

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
### 3.6. Explain the difference between `Task.WhenAll()` and `Task.WhenAny()`

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

### 3.7. What is `ValueTask` and when should you use it over `Task`?

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

### 3.8. How do you handle exceptions in async methods?

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

### 3.9. What is the difference between synchronous and asynchronous programming?

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

### 3.10. Explain the concept of the `SynchronizationContext`

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

### 3.11. What are the best practices for cancellation in async operations using `CancellationToken`?

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

### 3.12. How would you implement parallel processing in .NET?

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

### 3.13. What is the difference between `Task.FromResult()` and `Task.Run()`?

**Answer:**

**`Task.FromResult()`** creates a completed task with a result value, while **`Task.Run()`** queues work to run on the ThreadPool. The key difference is that `Task.FromResult()` is synchronous and immediate, while `Task.Run()` is asynchronous and offloads work to a background thread.

**Key Differences:**

| Aspect | `Task.FromResult()` | `Task.Run()` |
|--------|-------------------|--------------|
| **Execution** | Synchronous, immediate | Asynchronous, queued |
| **Thread** | Runs on current thread | Runs on ThreadPool thread |
| **Use Case** | Already computed values | CPU-bound work |
| **Performance** | No overhead | Thread switching overhead |
| **When to Use** | Converting sync to async API | Offloading CPU work |

**Example:**

```csharp
public class TaskCreationComparison
{
    // Task.FromResult() - for already computed values
    public async Task<string> GetCachedDataAsync(string key)
    {
        // Simulate cache lookup (synchronous operation)
        string cachedValue = GetFromCache(key);
        
        if (cachedValue != null)
        {
            // Already have the value - use Task.FromResult()
            return await Task.FromResult(cachedValue);
        }
        
        // Need to fetch from database (async operation)
        return await FetchFromDatabaseAsync(key);
    }
    
    // Task.Run() - for CPU-bound work
    public async Task<int> CalculatePrimeCountAsync(int maxNumber)
    {
        // CPU-intensive work - offload to ThreadPool
        return await Task.Run(() =>
        {
            int count = 0;
            for (int i = 2; i <= maxNumber; i++)
            {
                if (IsPrime(i))
                    count++;
            }
            return count;
        });
    }
    
    // WRONG: Using Task.Run() for already computed values
    public async Task<string> GetCachedDataWrongAsync(string key)
    {
        string cachedValue = GetFromCache(key);
        
        if (cachedValue != null)
        {
            // BAD: Unnecessary thread switching overhead
            return await Task.Run(() => cachedValue);
        }
        
        return await FetchFromDatabaseAsync(key);
    }
    
    // WRONG: Using Task.FromResult() for CPU-bound work
    public async Task<int> CalculatePrimeCountWrongAsync(int maxNumber)
    {
        // BAD: Blocks the current thread
        int count = 0;
        for (int i = 2; i <= maxNumber; i++)
        {
            if (IsPrime(i))
                count++;
        }
        
        return await Task.FromResult(count);
    }
    
    private string GetFromCache(string key)
    {
        // Simulate cache lookup
        return key == "cached" ? "cached_value" : null;
    }
    
    private async Task<string> FetchFromDatabaseAsync(string key)
    {
        await Task.Delay(1000); // Simulate database call
        return $"database_value_for_{key}";
    }
    
    private bool IsPrime(int number)
    {
        if (number < 2) return false;
        for (int i = 2; i * i <= number; i++)
        {
            if (number % i == 0) return false;
        }
        return true;
    }
}
```

**Advanced Examples:**

```csharp
public class AdvancedTaskCreation
{
    // Task.FromResult() for configuration values
    public async Task<AppSettings> GetAppSettingsAsync()
    {
        // Configuration is already loaded - no need for async
        var settings = LoadConfiguration();
        return await Task.FromResult(settings);
    }
    
    // Task.FromResult() for constants
    public async Task<string> GetApiVersionAsync()
    {
        return await Task.FromResult("v1.0");
    }
    
    // Task.FromResult() for simple calculations
    public async Task<decimal> CalculateTaxAsync(decimal amount, decimal rate)
    {
        decimal tax = amount * rate;
        return await Task.FromResult(tax);
    }
    
    // Task.Run() for file processing
    public async Task<string> ProcessLargeFileAsync(string filePath)
    {
        return await Task.Run(() =>
        {
            // CPU-intensive file processing
            var lines = File.ReadAllLines(filePath);
            var processedLines = lines
                .Where(line => !string.IsNullOrWhiteSpace(line))
                .Select(line => line.ToUpper())
                .OrderBy(line => line)
                .ToArray();
            
            return string.Join("\n", processedLines);
        });
    }
    
    // Task.Run() for image processing
    public async Task<byte[]> ResizeImageAsync(byte[] imageData, int width, int height)
    {
        return await Task.Run(() =>
        {
            // CPU-intensive image processing
            using (var originalImage = Image.FromStream(new MemoryStream(imageData)))
            using (var resizedImage = new Bitmap(originalImage, width, height))
            using (var stream = new MemoryStream())
            {
                resizedImage.Save(stream, ImageFormat.Jpeg);
                return stream.ToArray();
            }
        });
    }
    
    private AppSettings LoadConfiguration()
    {
        // Simulate configuration loading
        return new AppSettings { DatabaseConnection = "Server=localhost", ApiKey = "secret" };
    }
}

public class AppSettings
{
    public string DatabaseConnection { get; set; }
    public string ApiKey { get; set; }
}
```

**Performance Comparison:**

```csharp
public class PerformanceComparison
{
    public async Task ComparePerformance()
    {
        const int iterations = 10000;
        
        // Task.FromResult() - very fast
        var stopwatch = Stopwatch.StartNew();
        for (int i = 0; i < iterations; i++)
        {
            await Task.FromResult(i);
        }
        stopwatch.Stop();
        Console.WriteLine($"Task.FromResult(): {stopwatch.ElapsedMilliseconds}ms");
        
        // Task.Run() - slower due to thread switching
        stopwatch.Restart();
        for (int i = 0; i < iterations; i++)
        {
            await Task.Run(() => i);
        }
        stopwatch.Stop();
        Console.WriteLine($"Task.Run(): {stopwatch.ElapsedMilliseconds}ms");
    }
}
```

**Best Practices:**

**Use `Task.FromResult()` when:**
- You already have the computed value
- Converting synchronous APIs to async
- Returning constants or configuration values
- Simple calculations that don't block

**Use `Task.Run()` when:**
- Performing CPU-intensive work
- Processing large files or data
- Image/video processing
- Mathematical calculations
- Any work that could block the UI thread

**Avoid `Task.Run()` when:**
- You already have the result
- The work is already asynchronous
- You're just wrapping synchronous I/O operations
- The operation is very fast

**Common Anti-patterns:**

```csharp
// BAD: Unnecessary Task.Run()
public async Task<string> GetUserNameAsync(int userId)
{
    var user = await GetUserFromDatabaseAsync(userId);
    return await Task.Run(() => user.Name); // Unnecessary!
}

// GOOD: Use Task.FromResult() or just return directly
public async Task<string> GetUserNameAsync(int userId)
{
    var user = await GetUserFromDatabaseAsync(userId);
    return user.Name; // Simple return
}

// BAD: Blocking with Task.FromResult()
public async Task<string> ProcessDataAsync(string data)
{
    var result = ExpensiveProcessing(data); // Blocks current thread
    return await Task.FromResult(result);
}

// GOOD: Use Task.Run() for CPU work
public async Task<string> ProcessDataAsync(string data)
{
    return await Task.Run(() => ExpensiveProcessing(data));
}
```

**Summary:**
- `Task.FromResult()`: For already computed values, no thread switching
- `Task.Run()`: For CPU-bound work that needs to run on background thread
- Choose based on whether you need to offload work or just return a value
- Performance matters: avoid unnecessary thread switching

---

### 3.14. How do you implement async/await in a custom class or library?

**Answer:**

Implementing async/await in custom classes requires following specific patterns to ensure proper async behavior, exception handling, and resource management. The key is to implement the async pattern correctly and provide both sync and async versions when appropriate.

**Basic Async Implementation:**

```csharp
public class DataService
{
    private readonly HttpClient httpClient;
    
    public DataService(HttpClient httpClient)
    {
        this.httpClient = httpClient ?? throw new ArgumentNullException(nameof(httpClient));
    }
    
    // Async method with proper naming convention
    public async Task<string> GetDataAsync(string url, CancellationToken cancellationToken = default)
    {
        try
        {
            // Use ConfigureAwait(false) in library code
            var response = await httpClient.GetAsync(url, cancellationToken).ConfigureAwait(false);
            response.EnsureSuccessStatusCode();
            
            var content = await response.Content.ReadAsStringAsync().ConfigureAwait(false);
            return content;
        }
        catch (HttpRequestException ex)
        {
            // Wrap in more specific exception
            throw new DataServiceException($"Failed to retrieve data from {url}", ex);
        }
    }
    
    // Async method with return value
    public async Task<T> GetDataAsync<T>(string url, CancellationToken cancellationToken = default)
    {
        var json = await GetDataAsync(url, cancellationToken).ConfigureAwait(false);
        return JsonSerializer.Deserialize<T>(json);
    }
    
    // Async method with multiple operations
    public async Task<ProcessedData> ProcessDataAsync(string input, CancellationToken cancellationToken = default)
    {
        // Validate input
        if (string.IsNullOrEmpty(input))
            throw new ArgumentException("Input cannot be null or empty", nameof(input));
        
        // Step 1: Fetch data
        var rawData = await GetDataAsync("https://api.example.com/data", cancellationToken).ConfigureAwait(false);
        
        // Step 2: Process data (CPU-bound work)
        var processedData = await Task.Run(() => ProcessRawData(rawData), cancellationToken).ConfigureAwait(false);
        
        // Step 3: Save result
        await SaveDataAsync(processedData, cancellationToken).ConfigureAwait(false);
        
        return processedData;
    }
    
    private ProcessedData ProcessRawData(string rawData)
    {
        // CPU-intensive processing
        Thread.Sleep(1000); // Simulate processing
        return new ProcessedData { Content = rawData.ToUpper(), ProcessedAt = DateTime.UtcNow };
    }
    
    private async Task SaveDataAsync(ProcessedData data, CancellationToken cancellationToken)
    {
        // Simulate saving to database
        await Task.Delay(100, cancellationToken).ConfigureAwait(false);
    }
}

public class ProcessedData
{
    public string Content { get; set; }
    public DateTime ProcessedAt { get; set; }
}

public class DataServiceException : Exception
{
    public DataServiceException(string message) : base(message) { }
    public DataServiceException(string message, Exception innerException) : base(message, innerException) { }
}
```

**Advanced Async Patterns:**

```csharp
public class FileProcessor
{
    private readonly SemaphoreSlim semaphore;
    private readonly ILogger logger;
    
    public FileProcessor(int maxConcurrency = 4, ILogger logger = null)
    {
        this.semaphore = new SemaphoreSlim(maxConcurrency, maxConcurrency);
        this.logger = logger;
    }
    
    // Async method with concurrency control
    public async Task<ProcessingResult> ProcessFileAsync(string filePath, CancellationToken cancellationToken = default)
    {
        await semaphore.WaitAsync(cancellationToken).ConfigureAwait(false);
        
        try
        {
            logger?.LogInformation($"Starting to process file: {filePath}");
            
            // Validate file exists
            if (!File.Exists(filePath))
                throw new FileNotFoundException($"File not found: {filePath}");
            
            // Read file asynchronously
            var content = await File.ReadAllTextAsync(filePath, cancellationToken).ConfigureAwait(false);
            
            // Process content (CPU-bound)
            var processedContent = await Task.Run(() => ProcessContent(content), cancellationToken).ConfigureAwait(false);
            
            // Write result asynchronously
            var outputPath = GetOutputPath(filePath);
            await File.WriteAllTextAsync(outputPath, processedContent, cancellationToken).ConfigureAwait(false);
            
            logger?.LogInformation($"Successfully processed file: {filePath}");
            
            return new ProcessingResult
            {
                InputPath = filePath,
                OutputPath = outputPath,
                ProcessedAt = DateTime.UtcNow,
                Success = true
            };
        }
        catch (OperationCanceledException)
        {
            logger?.LogWarning($"Processing cancelled for file: {filePath}");
            throw;
        }
        catch (Exception ex)
        {
            logger?.LogError(ex, $"Error processing file: {filePath}");
            return new ProcessingResult
            {
                InputPath = filePath,
                ProcessedAt = DateTime.UtcNow,
                Success = false,
                Error = ex.Message
            };
        }
        finally
        {
            semaphore.Release();
        }
    }
    
    // Batch processing with progress reporting
    public async Task<BatchProcessingResult> ProcessFilesAsync(
        IEnumerable<string> filePaths, 
        IProgress<ProcessingProgress> progress = null,
        CancellationToken cancellationToken = default)
    {
        var tasks = filePaths.Select(async filePath =>
        {
            var result = await ProcessFileAsync(filePath, cancellationToken).ConfigureAwait(false);
            progress?.Report(new ProcessingProgress { FilePath = filePath, Completed = true });
            return result;
        });
        
        var results = await Task.WhenAll(tasks).ConfigureAwait(false);
        
        return new BatchProcessingResult
        {
            TotalFiles = results.Length,
            SuccessfulFiles = results.Count(r => r.Success),
            FailedFiles = results.Count(r => !r.Success),
            Results = results
        };
    }
    
    private string ProcessContent(string content)
    {
        // Simulate CPU-intensive processing
        Thread.Sleep(500);
        return content.ToUpper();
    }
    
    private string GetOutputPath(string inputPath)
    {
        return Path.ChangeExtension(inputPath, ".processed");
    }
    
    public void Dispose()
    {
        semaphore?.Dispose();
    }
}

public class ProcessingResult
{
    public string InputPath { get; set; }
    public string OutputPath { get; set; }
    public DateTime ProcessedAt { get; set; }
    public bool Success { get; set; }
    public string Error { get; set; }
}

public class BatchProcessingResult
{
    public int TotalFiles { get; set; }
    public int SuccessfulFiles { get; set; }
    public int FailedFiles { get; set; }
    public ProcessingResult[] Results { get; set; }
}

public class ProcessingProgress
{
    public string FilePath { get; set; }
    public bool Completed { get; set; }
}
```

**Async Stream Implementation:**

```csharp
public class DataStreamer
{
    private readonly HttpClient httpClient;
    
    public DataStreamer(HttpClient httpClient)
    {
        this.httpClient = httpClient ?? throw new ArgumentNullException(nameof(httpClient));
    }
    
    // Async enumerable for streaming data
    public async IAsyncEnumerable<DataItem> StreamDataAsync(
        string endpoint,
        [EnumeratorCancellation] CancellationToken cancellationToken = default)
    {
        var response = await httpClient.GetAsync(endpoint, HttpCompletionOption.ResponseHeadersRead, cancellationToken)
            .ConfigureAwait(false);
        
        response.EnsureSuccessStatusCode();
        
        using var stream = await response.Content.ReadAsStreamAsync().ConfigureAwait(false);
        using var reader = new StreamReader(stream);
        
        string line;
        while ((line = await reader.ReadLineAsync().ConfigureAwait(false)) != null)
        {
            cancellationToken.ThrowIfCancellationRequested();
            
            if (!string.IsNullOrWhiteSpace(line))
            {
                var item = ParseDataItem(line);
                yield return item;
            }
        }
    }
    
    // Async method with timeout
    public async Task<string> GetDataWithTimeoutAsync(string url, TimeSpan timeout)
    {
        using var cts = new CancellationTokenSource(timeout);
        
        try
        {
            var response = await httpClient.GetAsync(url, cts.Token).ConfigureAwait(false);
            return await response.Content.ReadAsStringAsync().ConfigureAwait(false);
        }
        catch (OperationCanceledException) when (cts.Token.IsCancellationRequested)
        {
            throw new TimeoutException($"Request timed out after {timeout.TotalSeconds} seconds");
        }
    }
    
    private DataItem ParseDataItem(string line)
    {
        // Simple parsing logic
        var parts = line.Split(',');
        return new DataItem
        {
            Id = parts[0],
            Value = parts[1],
            Timestamp = DateTime.Parse(parts[2])
        };
    }
}

public class DataItem
{
    public string Id { get; set; }
    public string Value { get; set; }
    public DateTime Timestamp { get; set; }
}
```

**Async Factory Pattern:**

```csharp
public class DatabaseConnection
{
    private readonly string connectionString;
    
    private DatabaseConnection(string connectionString)
    {
        this.connectionString = connectionString;
    }
    
    // Async factory method
    public static async Task<DatabaseConnection> CreateAsync(string connectionString)
    {
        if (string.IsNullOrEmpty(connectionString))
            throw new ArgumentException("Connection string cannot be null or empty", nameof(connectionString));
        
        var connection = new DatabaseConnection(connectionString);
        
        // Test the connection asynchronously
        await connection.TestConnectionAsync().ConfigureAwait(false);
        
        return connection;
    }
    
    private async Task TestConnectionAsync()
    {
        // Simulate connection test
        await Task.Delay(100).ConfigureAwait(false);
        
        // In real implementation, you would test the actual database connection
        if (connectionString.Contains("invalid"))
            throw new InvalidOperationException("Invalid connection string");
    }
    
    public async Task<T> QueryAsync<T>(string sql, CancellationToken cancellationToken = default)
    {
        // Simulate database query
        await Task.Delay(50, cancellationToken).ConfigureAwait(false);
        
        // Return mock data
        return default(T);
    }
}
```

**Best Practices for Async Implementation:**

1. **Naming Convention:**
   - Always suffix async methods with `Async`
   - Use descriptive names that indicate the operation

2. **Return Types:**
   - Use `Task` for void operations
   - Use `Task<T>` for operations that return values
   - Use `IAsyncEnumerable<T>` for streaming data

3. **Cancellation Support:**
   - Always accept `CancellationToken` parameters
   - Pass cancellation tokens to all async operations
   - Check `cancellationToken.IsCancellationRequested` in loops

4. **Exception Handling:**
   - Let exceptions bubble up naturally
   - Wrap low-level exceptions in domain-specific exceptions
   - Use `ConfigureAwait(false)` in library code

5. **Resource Management:**
   - Use `using` statements for disposable resources
   - Implement `IAsyncDisposable` when needed
   - Clean up resources in finally blocks

6. **Performance:**
   - Use `ConfigureAwait(false)` in library code
   - Avoid blocking async methods with `.Result` or `.Wait()`
   - Use `Task.Run()` only for CPU-bound work

---

### 3.15. What are the performance implications of async/await?

**Answer:**

Async/await has both benefits and performance costs. Understanding these implications is crucial for making informed decisions about when to use async programming and how to optimize it.

**Performance Benefits:**

1. **Better Resource Utilization**
2. **Improved Scalability**
3. **Non-blocking I/O Operations**
4. **Better User Experience**

**Performance Costs:**

1. **Memory Allocation Overhead**
2. **State Machine Generation**
3. **Context Switching**
4. **Exception Handling Overhead**

**Example:**

```csharp
public class PerformanceAnalysis
{
    private readonly HttpClient httpClient = new HttpClient();
    
    // Synchronous version - blocks thread
    public string GetDataSync(string url)
    {
        var response = httpClient.GetStringAsync(url).Result; // BAD: Blocking
        return response;
    }
    
    // Asynchronous version - better resource utilization
    public async Task<string> GetDataAsync(string url)
    {
        var response = await httpClient.GetStringAsync(url).ConfigureAwait(false);
        return response;
    }
    
    // Performance comparison
    public async Task ComparePerformance()
    {
        const int iterations = 1000;
        var urls = Enumerable.Range(1, iterations)
            .Select(i => $"https://api.example.com/data/{i}")
            .ToArray();
        
        // Synchronous approach - sequential, blocking
        var stopwatch = Stopwatch.StartNew();
        var syncResults = new List<string>();
        
        foreach (var url in urls.Take(10)) // Limit to 10 for demo
        {
            syncResults.Add(GetDataSync(url));
        }
        
        stopwatch.Stop();
        Console.WriteLine($"Synchronous: {stopwatch.ElapsedMilliseconds}ms for 10 requests");
        
        // Asynchronous approach - concurrent, non-blocking
        stopwatch.Restart();
        var asyncTasks = urls.Take(10).Select(GetDataAsync);
        var asyncResults = await Task.WhenAll(asyncTasks);
        
        stopwatch.Stop();
        Console.WriteLine($"Asynchronous: {stopwatch.ElapsedMilliseconds}ms for 10 requests");
    }
}
```

**Memory Allocation Analysis:**

```csharp
public class MemoryAllocationAnalysis
{
    // High allocation - creates new Task for each operation
    public async Task<string> HighAllocationAsync(string input)
    {
        // Each await creates a state machine
        var step1 = await ProcessStep1Async(input).ConfigureAwait(false);
        var step2 = await ProcessStep2Async(step1).ConfigureAwait(false);
        var step3 = await ProcessStep3Async(step2).ConfigureAwait(false);
        
        return step3;
    }
    
    // Lower allocation - fewer await points
    public async Task<string> LowerAllocationAsync(string input)
    {
        // Batch operations to reduce state machine overhead
        var (step1, step2, step3) = await ProcessAllStepsAsync(input).ConfigureAwait(false);
        
        return step3;
    }
    
    // Optimized - minimal allocation
    public Task<string> OptimizedAsync(string input)
    {
        // For simple operations, consider if async is needed
        if (IsCached(input))
        {
            return Task.FromResult(GetCachedValue(input));
        }
        
        return ProcessAsync(input);
    }
    
    private async Task<string> ProcessStep1Async(string input)
    {
        await Task.Delay(10).ConfigureAwait(false);
        return input.ToUpper();
    }
    
    private async Task<string> ProcessStep2Async(string input)
    {
        await Task.Delay(10).ConfigureAwait(false);
        return input + "_processed";
    }
    
    private async Task<string> ProcessStep3Async(string input)
    {
        await Task.Delay(10).ConfigureAwait(false);
        return input + "_final";
    }
    
    private async Task<(string, string, string)> ProcessAllStepsAsync(string input)
    {
        await Task.Delay(30).ConfigureAwait(false); // Simulate all work
        return (input.ToUpper(), input.ToUpper() + "_processed", input.ToUpper() + "_processed_final");
    }
    
    private bool IsCached(string input) => input.Length < 5;
    private string GetCachedValue(string input) => input.ToUpper();
    private async Task<string> ProcessAsync(string input)
    {
        await Task.Delay(100).ConfigureAwait(false);
        return input.ToUpper();
    }
}
```

**When Async Hurts Performance:**

```csharp
public class AsyncPerformancePitfalls
{
    // BAD: Unnecessary async for simple operations
    public async Task<int> BadAsync(int a, int b)
    {
        // This creates unnecessary overhead
        return await Task.FromResult(a + b).ConfigureAwait(false);
    }
    
    // GOOD: Simple synchronous operation
    public int GoodSync(int a, int b)
    {
        return a + b;
    }
    
    // BAD: Using Task.Run() for I/O operations
    public async Task<string> BadTaskRunAsync(string url)
    {
        // Task.Run() is for CPU-bound work, not I/O
        return await Task.Run(async () =>
        {
            var client = new HttpClient();
            return await client.GetStringAsync(url);
        }).ConfigureAwait(false);
    }
    
    // GOOD: Direct async I/O
    public async Task<string> GoodAsync(string url)
    {
        var client = new HttpClient();
        return await client.GetStringAsync(url).ConfigureAwait(false);
    }
    
    // BAD: Blocking async methods
    public string BadBlockingAsync(string url)
    {
        // This defeats the purpose of async
        return GetDataAsync(url).Result; // Can cause deadlocks
    }
    
    // BAD: Fire-and-forget without proper error handling
    public void BadFireAndForget(string url)
    {
        // Exceptions will be lost
        _ = GetDataAsync(url);
    }
    
    // GOOD: Proper fire-and-forget with error handling
    public void GoodFireAndForget(string url)
    {
        _ = GetDataAsync(url).ContinueWith(task =>
        {
            if (task.IsFaulted)
            {
                // Log the exception
                Console.WriteLine($"Error: {task.Exception?.GetBaseException().Message}");
            }
        }, TaskContinuationOptions.OnlyOnFaulted);
    }
    
    private async Task<string> GetDataAsync(string url)
    {
        var client = new HttpClient();
        return await client.GetStringAsync(url).ConfigureAwait(false);
    }
}
```

**Performance Optimization Techniques:**

```csharp
public class AsyncOptimization
{
    private readonly HttpClient httpClient = new HttpClient();
    private readonly SemaphoreSlim semaphore = new SemaphoreSlim(10, 10); // Limit concurrency
    
    // Optimized: Limit concurrent operations
    public async Task<string[]> GetDataWithConcurrencyLimitAsync(string[] urls)
    {
        var tasks = urls.Select(async url =>
        {
            await semaphore.WaitAsync().ConfigureAwait(false);
            try
            {
                return await httpClient.GetStringAsync(url).ConfigureAwait(false);
            }
            finally
            {
                semaphore.Release();
            }
        });
        
        return await Task.WhenAll(tasks).ConfigureAwait(false);
    }
    
    // Optimized: Use ValueTask for hot paths
    public async ValueTask<string> GetCachedDataAsync(string key)
    {
        if (TryGetFromCache(key, out string cachedValue))
        {
            return cachedValue; // No allocation
        }
        
        var value = await FetchFromDatabaseAsync(key).ConfigureAwait(false);
        CacheValue(key, value);
        return value;
    }
    
    // Optimized: Batch operations
    public async Task<Dictionary<string, string>> GetMultipleDataAsync(string[] keys)
    {
        // Single database call instead of multiple
        return await FetchMultipleFromDatabaseAsync(keys).ConfigureAwait(false);
    }
    
    // Optimized: Use ConfigureAwait(false) in library code
    public async Task<string> LibraryMethodAsync(string input)
    {
        var result = await ProcessInputAsync(input).ConfigureAwait(false);
        return await TransformResultAsync(result).ConfigureAwait(false);
    }
    
    private bool TryGetFromCache(string key, out string value)
    {
        // Simulate cache lookup
        value = key == "cached" ? "cached_value" : null;
        return value != null;
    }
    
    private void CacheValue(string key, string value)
    {
        // Simulate caching
    }
    
    private async Task<string> FetchFromDatabaseAsync(string key)
    {
        await Task.Delay(100).ConfigureAwait(false);
        return $"database_value_for_{key}";
    }
    
    private async Task<Dictionary<string, string>> FetchMultipleFromDatabaseAsync(string[] keys)
    {
        await Task.Delay(100).ConfigureAwait(false);
        return keys.ToDictionary(k => k, k => $"database_value_for_{k}");
    }
    
    private async Task<string> ProcessInputAsync(string input)
    {
        await Task.Delay(50).ConfigureAwait(false);
        return input.ToUpper();
    }
    
    private async Task<string> TransformResultAsync(string input)
    {
        await Task.Delay(50).ConfigureAwait(false);
        return input + "_transformed";
    }
}
```

**Performance Measurement:**

```csharp
public class AsyncPerformanceMeasurement
{
    public async Task MeasureAsyncPerformance()
    {
        const int iterations = 10000;
        
        // Measure memory allocation
        var initialMemory = GC.GetTotalMemory(true);
        
        // Test 1: Simple async method
        var stopwatch = Stopwatch.StartNew();
        for (int i = 0; i < iterations; i++)
        {
            await SimpleAsyncMethod().ConfigureAwait(false);
        }
        stopwatch.Stop();
        
        var finalMemory = GC.GetTotalMemory(false);
        var allocatedMemory = finalMemory - initialMemory;
        
        Console.WriteLine($"Simple async method:");
        Console.WriteLine($"  Time: {stopwatch.ElapsedMilliseconds}ms");
        Console.WriteLine($"  Memory allocated: {allocatedMemory / 1024.0:F2} KB");
        Console.WriteLine($"  Memory per call: {allocatedMemory / (double)iterations:F2} bytes");
        
        // Test 2: Synchronous equivalent
        initialMemory = GC.GetTotalMemory(true);
        stopwatch.Restart();
        
        for (int i = 0; i < iterations; i++)
        {
            SimpleSyncMethod();
        }
        stopwatch.Stop();
        
        finalMemory = GC.GetTotalMemory(false);
        allocatedMemory = finalMemory - initialMemory;
        
        Console.WriteLine($"\nSynchronous method:");
        Console.WriteLine($"  Time: {stopwatch.ElapsedMilliseconds}ms");
        Console.WriteLine($"  Memory allocated: {allocatedMemory / 1024.0:F2} KB");
        Console.WriteLine($"  Memory per call: {allocatedMemory / (double)iterations:F2} bytes");
    }
    
    private async Task<int> SimpleAsyncMethod()
    {
        await Task.Delay(1).ConfigureAwait(false);
        return 42;
    }
    
    private int SimpleSyncMethod()
    {
        Thread.Sleep(1);
        return 42;
    }
}
```

**Best Practices for Performance:**

1. **Use async only when beneficial:**
   - I/O operations (network, file, database)
   - Operations that can benefit from concurrency
   - Operations that might block the UI thread

2. **Avoid async for:**
   - Simple calculations
   - Already computed values
   - CPU-bound work (use Task.Run() instead)

3. **Optimize hot paths:**
   - Use `ValueTask` for frequently called methods
   - Cache results when possible
   - Batch operations when feasible

4. **Monitor performance:**
   - Profile memory allocation
   - Measure execution time
   - Use performance counters

5. **Use proper patterns:**
   - `ConfigureAwait(false)` in library code
   - Limit concurrency with `SemaphoreSlim`
   - Handle exceptions properly

**Summary:**
- Async/await has overhead but provides scalability benefits
- Use async for I/O operations, not CPU-bound work
- Monitor memory allocation and execution time
- Optimize hot paths with `ValueTask` and caching
- Use proper async patterns to avoid performance pitfalls

---

### 3.16. How do you handle async operations in constructors and static methods?

**Answer:**

Constructors cannot be async, and static methods have specific considerations for async operations. This limitation requires alternative patterns and approaches to handle asynchronous initialization and operations.

**Constructor Limitations and Solutions:**

```csharp
public class DatabaseService
{
    private readonly string connectionString;
    private Task<IDbConnection> connectionTask;
    
    // Constructor cannot be async
    public DatabaseService(string connectionString)
    {
        this.connectionString = connectionString ?? throw new ArgumentNullException(nameof(connectionString));
        
        // Start async initialization but don't await
        this.connectionTask = InitializeConnectionAsync();
    }
    
    // Async initialization method
    private async Task<IDbConnection> InitializeConnectionAsync()
    {
        var connection = new SqlConnection(connectionString);
        await connection.OpenAsync().ConfigureAwait(false);
        return connection;
    }
    
    // Public method to get the connection when needed
    public async Task<IDbConnection> GetConnectionAsync()
    {
        return await connectionTask.ConfigureAwait(false);
    }
    
    // Example usage
    public async Task<User> GetUserAsync(int userId)
    {
        var connection = await GetConnectionAsync().ConfigureAwait(false);
        // Use connection for database operations
        return new User { Id = userId, Name = "John Doe" };
    }
}

public interface IDbConnection
{
    Task OpenAsync();
    void Close();
}

public class SqlConnection : IDbConnection
{
    private readonly string connectionString;
    
    public SqlConnection(string connectionString)
    {
        this.connectionString = connectionString;
    }
    
    public async Task OpenAsync()
    {
        await Task.Delay(100).ConfigureAwait(false); // Simulate connection
    }
    
    public void Close()
    {
        // Close connection
    }
}

public class User
{
    public int Id { get; set; }
    public string Name { get; set; }
}
```

**Factory Pattern for Async Initialization:**

```csharp
public class FileProcessor
{
    private readonly string filePath;
    private readonly Stream fileStream;
    
    // Private constructor
    private FileProcessor(string filePath, Stream fileStream)
    {
        this.filePath = filePath;
        this.fileStream = fileStream;
    }
    
    // Async factory method
    public static async Task<FileProcessor> CreateAsync(string filePath)
    {
        if (string.IsNullOrEmpty(filePath))
            throw new ArgumentException("File path cannot be null or empty", nameof(filePath));
        
        if (!File.Exists(filePath))
            throw new FileNotFoundException($"File not found: {filePath}");
        
        // Perform async initialization
        var fileStream = await OpenFileAsync(filePath).ConfigureAwait(false);
        
        return new FileProcessor(filePath, fileStream);
    }
    
    private static async Task<Stream> OpenFileAsync(string filePath)
    {
        // Simulate async file opening
        await Task.Delay(100).ConfigureAwait(false);
        return File.OpenRead(filePath);
    }
    
    public async Task<string> ReadContentAsync()
    {
        using var reader = new StreamReader(fileStream);
        return await reader.ReadToEndAsync().ConfigureAwait(false);
    }
    
    public void Dispose()
    {
        fileStream?.Dispose();
    }
}

// Usage
public class FileProcessorExample
{
    public static async Task ProcessFileExample()
    {
        // Use factory method for async initialization
        using var processor = await FileProcessor.CreateAsync("data.txt");
        var content = await processor.ReadContentAsync();
        Console.WriteLine(content);
    }
}
```

**Static Async Methods:**

```csharp
public static class UtilityService
{
    // Static async methods are allowed
    public static async Task<string> GetConfigurationAsync(string key)
    {
        // Simulate async configuration loading
        await Task.Delay(100).ConfigureAwait(false);
        return $"config_value_for_{key}";
    }
    
    public static async Task<T> DeserializeJsonAsync<T>(string json)
    {
        await Task.Delay(50).ConfigureAwait(false); // Simulate processing
        return JsonSerializer.Deserialize<T>(json);
    }
    
    // Static async method with caching
    private static readonly ConcurrentDictionary<string, Task<string>> cache = new();
    
    public static async Task<string> GetCachedDataAsync(string key)
    {
        return await cache.GetOrAdd(key, async k =>
        {
            await Task.Delay(200).ConfigureAwait(false); // Simulate expensive operation
            return $"expensive_data_for_{k}";
        }).ConfigureAwait(false);
    }
    
    // Static async method with error handling
    public static async Task<bool> TryGetDataAsync(string url, out string data)
    {
        data = null;
        
        try
        {
            using var client = new HttpClient();
            data = await client.GetStringAsync(url).ConfigureAwait(false);
            return true;
        }
        catch (Exception)
        {
            return false;
        }
    }
}

// Usage of static async methods
public class StaticAsyncExample
{
    public static async Task UseStaticAsyncMethods()
    {
        // Direct usage
        var config = await UtilityService.GetConfigurationAsync("database");
        Console.WriteLine(config);
        
        // With caching
        var data1 = await UtilityService.GetCachedDataAsync("key1");
        var data2 = await UtilityService.GetCachedDataAsync("key1"); // Uses cache
        
        // With error handling
        if (await UtilityService.TryGetDataAsync("https://api.example.com/data", out string result))
        {
            Console.WriteLine(result);
        }
        else
        {
            Console.WriteLine("Failed to get data");
        }
    }
}
```

**Lazy Initialization Pattern:**

```csharp
public class LazyAsyncService
{
    private readonly Lazy<Task<ExpensiveResource>> lazyResource;
    
    public LazyAsyncService()
    {
        // Lazy initialization of async resource
        lazyResource = new Lazy<Task<ExpensiveResource>>(async () =>
        {
            await Task.Delay(1000).ConfigureAwait(false); // Simulate expensive initialization
            return new ExpensiveResource();
        });
    }
    
    public async Task<string> DoWorkAsync()
    {
        // Resource is initialized only when first accessed
        var resource = await lazyResource.Value.ConfigureAwait(false);
        return await resource.ProcessAsync().ConfigureAwait(false);
    }
}

public class ExpensiveResource
{
    public async Task<string> ProcessAsync()
    {
        await Task.Delay(100).ConfigureAwait(false);
        return "Processed by expensive resource";
    }
}
```

**Async Initialization with IAsyncDisposable:**

```csharp
public class AsyncInitializedService : IAsyncDisposable
{
    private readonly string connectionString;
    private IDbConnection connection;
    private bool isInitialized = false;
    
    public AsyncInitializedService(string connectionString)
    {
        this.connectionString = connectionString;
    }
    
    // Async initialization method
    public async Task InitializeAsync()
    {
        if (isInitialized)
            return;
        
        connection = new SqlConnection(connectionString);
        await connection.OpenAsync().ConfigureAwait(false);
        isInitialized = true;
    }
    
    // Ensure initialization before use
    private async Task EnsureInitializedAsync()
    {
        if (!isInitialized)
        {
            await InitializeAsync().ConfigureAwait(false);
        }
    }
    
    public async Task<User> GetUserAsync(int userId)
    {
        await EnsureInitializedAsync().ConfigureAwait(false);
        
        // Use the initialized connection
        return new User { Id = userId, Name = "John Doe" };
    }
    
    public async ValueTask DisposeAsync()
    {
        if (connection != null)
        {
            connection.Close();
            connection = null;
        }
        isInitialized = false;
        await Task.CompletedTask.ConfigureAwait(false);
    }
}

// Usage with using statement
public class AsyncDisposableExample
{
    public static async Task UseAsyncDisposable()
    {
        await using var service = new AsyncInitializedService("connection_string");
        await service.InitializeAsync();
        
        var user = await service.GetUserAsync(1);
        Console.WriteLine(user.Name);
    } // DisposeAsync is called automatically
}
```

**Static Constructor with Async Initialization:**

```csharp
public static class StaticAsyncInitializer
{
    private static readonly Task initializationTask;
    private static bool isInitialized = false;
    
    // Static constructor - cannot be async
    static StaticAsyncInitializer()
    {
        initializationTask = InitializeAsync();
    }
    
    private static async Task InitializeAsync()
    {
        // Perform async initialization
        await Task.Delay(1000).ConfigureAwait(false);
        isInitialized = true;
    }
    
    // Public method to ensure initialization
    public static async Task EnsureInitializedAsync()
    {
        await initializationTask.ConfigureAwait(false);
    }
    
    public static async Task<string> GetDataAsync()
    {
        await EnsureInitializedAsync().ConfigureAwait(false);
        return "Data from initialized service";
    }
}
```

**Best Practices:**

1. **For Constructors:**
   - Use factory methods for async initialization
   - Start async operations but don't await them
   - Provide methods to access async results
   - Use lazy initialization when appropriate

2. **For Static Methods:**
   - Static async methods are perfectly fine
   - Use caching for expensive operations
   - Handle errors appropriately
   - Consider thread safety

3. **Alternative Patterns:**
   - Factory pattern for async object creation
   - Lazy initialization for expensive resources
   - IAsyncDisposable for async cleanup
   - Static async methods for utility functions

4. **Common Pitfalls to Avoid:**
   - Don't use `.Result` or `.Wait()` in constructors
   - Don't make constructors async (it's not allowed)
   - Don't forget to handle exceptions in async initialization
   - Don't block on async operations in constructors

**Summary:**
- Constructors cannot be async - use factory methods or lazy initialization
- Static async methods are allowed and useful for utility functions
- Use proper patterns like factory methods, lazy initialization, and IAsyncDisposable
- Always handle exceptions and ensure proper resource cleanup

---

## 4. ASP.NET Core

### 4.1. Explain the middleware pipeline in ASP.NET Core

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

### 4.2. What is the difference between ASP.NET and ASP.NET Core?

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

### 4.3. Explain dependency injection in ASP.NET Core (Transient, Scoped, Singleton)

Dependency Injection (DI) is a built-in design pattern in ASP.NET Core that achieves Inversion of Control (IoC) between classes and their dependencies. Services are registered with specific lifetimes.

**Service Lifetimes:**

#### 4.3.1. Transient
- A new instance is created every time the service is requested
- Best for lightweight, stateless services
- Registered using `AddTransient<TService, TImplementation>()`

```csharp
services.AddTransient();
```

**Use case:** Operations that don't maintain state, like sending emails or generating random numbers.

#### 4.3.2. Scoped
- A single instance is created per client request (HTTP request)
- The same instance is used throughout the entire request
- Registered using `AddScoped<TService, TImplementation>()`

```csharp
services.AddScoped();
```

**Use case:** Database contexts (Entity Framework), repository patterns, services that need to maintain state during a request.

#### 4.3.3. Singleton
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

### 4.4. What are action filters and how do you create custom filters?

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

### 4.5. Explain the difference between `IActionResult`, `ActionResult<T>`, and returning a concrete type

These are different return types for controller actions in ASP.NET Core, each with specific use cases.

#### 4.5.1. IActionResult

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

#### 4.5.2. ActionResult<T>

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

#### 4.5.3. Concrete Type

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

### 4.6. What is model binding and validation in ASP.NET Core?

Model binding is the process of mapping HTTP request data to action method parameters. Validation ensures that the bound data meets specified constraints before processing.

#### 4.6.1. Model Binding

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

#### 4.6.2. Model Validation

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
### 4.7. How do you implement authentication and authorization in ASP.NET Core?

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

### 4.8. Explain the difference between authentication and authorization.

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

### 4.9. What is JWT and how do you implement JWT authentication?

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

### 4.10. How do you handle CORS in ASP.NET Core?

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

### 4.11. What are the different ways to manage application configuration?

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

### 4.12. Explain routing in ASP.NET Core (conventional vs attribute routing).

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

### 4.13. What is Razor Pages and how does it differ from MVC?

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

### 4.14. How do you implement versioning in Web APIs?

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

### 4.15. What are health checks in ASP.NET Core?

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

## 5. Entity Framework and Database

### 5.1. What is Entity Framework Core and how does it differ from Entity Framework 6?

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

### 5.2. Explain Code First vs Database First approaches.

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

### 5.3. What is the difference between eager loading, lazy loading, and explicit loading?

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

### 5.4. What are migration strategies in EF Core?

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

### 5.5. Explain the Unit of Work and Repository patterns.

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

### 5.6. What is the N+1 query problem and how do you solve it?

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

### 5.7. How do you optimize Entity Framework queries?

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

### 5.8. Explain tracking vs no-tracking queries in EF Core.

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

### 5.9. What are owned entities and table splitting in EF Core?

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

### 5.10. How do you handle concurrency in Entity Framework?

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
### 5.11. Explain the difference between `SaveChanges()` and `SaveChangesAsync()`.

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

### 5.12. What are shadow properties in EF Core?

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

**Summary**

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

### 5.13. How do you handle database transactions in Entity Framework Core?

**Answer:**

Database transactions in Entity Framework Core ensure data consistency by grouping multiple operations into a single unit of work. If any operation fails, all changes are rolled back.

**1. Automatic Transactions (Default Behavior)**

EF Core automatically creates a transaction for each `SaveChanges()` call:

```csharp
public class OrderService
{
    private readonly AppDbContext _context;

    public OrderService(AppDbContext context)
    {
        _context = context;
    }

    // Single SaveChanges() = single transaction
    public async Task CreateOrderAsync(Order order)
    {
        _context.Orders.Add(order);
        _context.OrderItems.AddRange(order.OrderItems);
        
        // This creates and commits a transaction automatically
        await _context.SaveChangesAsync();
    }
}
```

**2. Manual Transaction Management**

Use `BeginTransaction()` for explicit transaction control:

```csharp
public async Task TransferMoneyAsync(int fromAccountId, int toAccountId, decimal amount)
{
    using var transaction = await _context.Database.BeginTransactionAsync();
    
    try
    {
        // Withdraw from source account
        var fromAccount = await _context.Accounts.FindAsync(fromAccountId);
        if (fromAccount.Balance < amount)
            throw new InsufficientFundsException();
        
        fromAccount.Balance -= amount;
        
        // Deposit to target account
        var toAccount = await _context.Accounts.FindAsync(toAccountId);
        toAccount.Balance += amount;
        
        // Create transaction record
        _context.Transactions.Add(new Transaction
        {
            FromAccountId = fromAccountId,
            ToAccountId = toAccountId,
            Amount = amount,
            Timestamp = DateTime.UtcNow
        });
        
        // Save all changes
        await _context.SaveChangesAsync();
        
        // Commit transaction
        await transaction.CommitAsync();
    }
    catch
    {
        // Rollback happens automatically when transaction is disposed
        await transaction.RollbackAsync();
        throw;
    }
}
```

**3. Transaction with Isolation Levels**

Control transaction isolation for different consistency requirements:

```csharp
public async Task ProcessOrderWithLockAsync(int orderId)
{
    using var transaction = await _context.Database.BeginTransactionAsync(
        IsolationLevel.ReadCommitted);
    
    try
    {
        // Lock the order row for update
        var order = await _context.Orders
            .FromSqlRaw("SELECT * FROM Orders WITH (UPDLOCK) WHERE Id = {0}", orderId)
            .FirstOrDefaultAsync();
        
        if (order.Status != OrderStatus.Pending)
            throw new InvalidOperationException("Order already processed");
        
        order.Status = OrderStatus.Processing;
        order.ProcessedAt = DateTime.UtcNow;
        
        await _context.SaveChangesAsync();
        await transaction.CommitAsync();
    }
    catch
    {
        await transaction.RollbackAsync();
        throw;
    }
}
```

**4. Distributed Transactions (Multiple Contexts)**

Handle transactions across multiple database contexts:

```csharp
public async Task ProcessOrderAcrossDatabasesAsync(Order order)
{
    using var transaction = await _context.Database.BeginTransactionAsync();
    
    try
    {
        // Save to main database
        _context.Orders.Add(order);
        await _context.SaveChangesAsync();
        
        // Save to audit database
        using var auditContext = new AuditDbContext();
        auditContext.Database.UseTransaction(transaction.GetDbTransaction());
        
        auditContext.AuditLogs.Add(new AuditLog
        {
            EntityType = "Order",
            EntityId = order.Id,
            Action = "Created",
            Timestamp = DateTime.UtcNow
        });
        
        await auditContext.SaveChangesAsync();
        
        await transaction.CommitAsync();
    }
    catch
    {
        await transaction.RollbackAsync();
        throw;
    }
}
```

**5. Transaction Scope (System.Transactions)**

Use `TransactionScope` for distributed transactions:

```csharp
public async Task ProcessOrderWithTransactionScopeAsync(Order order)
{
    using var scope = new TransactionScope(TransactionScopeAsyncFlowOption.Enabled);
    
    try
    {
        // Multiple operations that can span different databases
        await _context.Orders.AddAsync(order);
        await _context.SaveChangesAsync();
        
        // Call external service
        await _paymentService.ProcessPaymentAsync(order.PaymentInfo);
        
        // Send notification
        await _notificationService.SendOrderConfirmationAsync(order);
        
        scope.Complete(); // Commit all operations
    }
    catch
    {
        // Automatic rollback when scope is disposed
        throw;
    }
}
```

**6. Nested Transactions**

Handle nested transaction scenarios:

```csharp
public async Task ProcessBulkOrdersAsync(List<Order> orders)
{
    using var outerTransaction = await _context.Database.BeginTransactionAsync();
    
    try
    {
        foreach (var order in orders)
        {
            // Each order processing is a nested transaction
            await ProcessSingleOrderAsync(order);
        }
        
        await outerTransaction.CommitAsync();
    }
    catch
    {
        await outerTransaction.RollbackAsync();
        throw;
    }
}

private async Task ProcessSingleOrderAsync(Order order)
{
    using var innerTransaction = await _context.Database.BeginTransactionAsync();
    
    try
    {
        _context.Orders.Add(order);
        await _context.SaveChangesAsync();
        
        // Additional processing
        await UpdateInventoryAsync(order.OrderItems);
        
        await innerTransaction.CommitAsync();
    }
    catch
    {
        await innerTransaction.RollbackAsync();
        throw;
    }
}
```

**7. Transaction Best Practices**

```csharp
public class TransactionBestPractices
{
    private readonly AppDbContext _context;

    // ✅ Good: Use using statements for automatic disposal
    public async Task GoodTransactionAsync()
    {
        using var transaction = await _context.Database.BeginTransactionAsync();
        try
        {
            // Your operations here
            await _context.SaveChangesAsync();
            await transaction.CommitAsync();
        }
        catch
        {
            await transaction.RollbackAsync();
            throw;
        }
    }

    // ❌ Bad: Manual transaction management without proper cleanup
    public async Task BadTransactionAsync()
    {
        var transaction = await _context.Database.BeginTransactionAsync();
        try
        {
            await _context.SaveChangesAsync();
            await transaction.CommitAsync();
        }
        catch
        {
            await transaction.RollbackAsync();
            throw;
        }
        // Missing: transaction.Dispose() - can cause connection leaks
    }

    // ✅ Good: Appropriate isolation level
    public async Task ReadCommittedTransactionAsync()
    {
        using var transaction = await _context.Database.BeginTransactionAsync(
            IsolationLevel.ReadCommitted);
        
        // Operations that need to see committed data
        await _context.SaveChangesAsync();
        await transaction.CommitAsync();
    }

    // ✅ Good: Handle transaction timeouts
    public async Task TransactionWithTimeoutAsync()
    {
        using var transaction = await _context.Database.BeginTransactionAsync();
        transaction.GetDbTransaction().CommandTimeout = 30; // 30 seconds
        
        try
        {
            // Long-running operations
            await _context.SaveChangesAsync();
            await transaction.CommitAsync();
        }
        catch (SqlException ex) when (ex.Number == -2) // Timeout
        {
            await transaction.RollbackAsync();
            throw new TimeoutException("Transaction timed out", ex);
        }
    }
}
```

**8. Transaction Monitoring and Logging**

```csharp
public class TransactionMonitoring
{
    private readonly ILogger<TransactionMonitoring> _logger;

    public async Task MonitoredTransactionAsync()
    {
        var stopwatch = Stopwatch.StartNew();
        
        using var transaction = await _context.Database.BeginTransactionAsync();
        
        try
        {
            _logger.LogInformation("Transaction started: {TransactionId}", 
                transaction.TransactionId);
            
            // Your operations
            await _context.SaveChangesAsync();
            
            await transaction.CommitAsync();
            
            stopwatch.Stop();
            _logger.LogInformation("Transaction committed successfully in {Duration}ms", 
                stopwatch.ElapsedMilliseconds);
        }
        catch (Exception ex)
        {
            await transaction.RollbackAsync();
            
            stopwatch.Stop();
            _logger.LogError(ex, "Transaction rolled back after {Duration}ms", 
                stopwatch.ElapsedMilliseconds);
            
            throw;
        }
    }
}
```

**Key Points:**

1. **Automatic Transactions**: Each `SaveChanges()` creates a transaction automatically
2. **Manual Control**: Use `BeginTransaction()` for explicit transaction management
3. **Isolation Levels**: Control data consistency with different isolation levels
4. **Distributed Transactions**: Handle transactions across multiple databases
5. **Error Handling**: Always rollback on exceptions
6. **Resource Management**: Use `using` statements for automatic cleanup
7. **Performance**: Keep transactions short to avoid blocking
8. **Monitoring**: Log transaction duration and outcomes

**Best Practices:**

- Keep transactions as short as possible
- Use appropriate isolation levels
- Always handle exceptions and rollback
- Use `using` statements for automatic disposal
- Monitor transaction performance
- Avoid long-running operations in transactions
- Consider using `TransactionScope` for distributed scenarios

---

### 5.14. What are global query filters and how do you use them?

**Answer:**

Global query filters in Entity Framework Core allow you to automatically apply filtering logic to all queries for specific entity types. They're particularly useful for implementing soft deletes, multi-tenancy, and row-level security.

**1. Basic Global Query Filter**

```csharp
public class AppDbContext : DbContext
{
    public DbSet<Product> Products { get; set; }
    public DbSet<Category> Categories { get; set; }

    protected override void OnModelCreating(ModelBuilder modelBuilder)
    {
        // Global filter for soft deletes
        modelBuilder.Entity<Product>()
            .HasQueryFilter(p => !p.IsDeleted);
        
        modelBuilder.Entity<Category>()
            .HasQueryFilter(c => !c.IsDeleted);
    }
}

public class Product
{
    public int Id { get; set; }
    public string Name { get; set; }
    public bool IsDeleted { get; set; }
    public DateTime? DeletedAt { get; set; }
}

// Usage - filter is automatically applied
var products = await context.Products.ToListAsync();
// SQL: SELECT * FROM Products WHERE IsDeleted = 0
```

**2. Multi-Tenancy with Global Filters**

```csharp
public class AppDbContext : DbContext
{
    private readonly ITenantService _tenantService;

    public AppDbContext(DbContextOptions<AppDbContext> options, ITenantService tenantService)
        : base(options)
    {
        _tenantService = tenantService;
    }

    protected override void OnModelCreating(ModelBuilder modelBuilder)
    {
        // Multi-tenant filter
        modelBuilder.Entity<Product>()
            .HasQueryFilter(p => p.TenantId == _tenantService.GetCurrentTenantId());
        
        modelBuilder.Entity<Order>()
            .HasQueryFilter(o => o.TenantId == _tenantService.GetCurrentTenantId());
    }
}

public class Product
{
    public int Id { get; set; }
    public string Name { get; set; }
    public int TenantId { get; set; }
}

public interface ITenantService
{
    int GetCurrentTenantId();
}

// Usage - automatically filters by tenant
var products = await context.Products.ToListAsync();
// SQL: SELECT * FROM Products WHERE TenantId = @currentTenantId
```

**3. Complex Filter Conditions**

```csharp
protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    // Complex filter with multiple conditions
    modelBuilder.Entity<Product>()
        .HasQueryFilter(p => 
            !p.IsDeleted && 
            p.IsActive && 
            p.PublishedAt <= DateTime.UtcNow);
    
    // Filter based on user permissions
    modelBuilder.Entity<Document>()
        .HasQueryFilter(d => 
            d.IsPublic || 
            d.OwnerId == _userService.GetCurrentUserId() ||
            d.SharedWith.Contains(_userService.GetCurrentUserId()));
}
```

**4. Ignoring Global Filters**

Sometimes you need to bypass global filters:

```csharp
public class ProductService
{
    private readonly AppDbContext _context;

    // Normal query - filter is applied
    public async Task<List<Product>> GetActiveProductsAsync()
    {
        return await _context.Products.ToListAsync();
        // SQL: SELECT * FROM Products WHERE IsDeleted = 0
    }

    // Ignore global filter - get all products including deleted
    public async Task<List<Product>> GetAllProductsIncludingDeletedAsync()
    {
        return await _context.Products
            .IgnoreQueryFilters()
            .ToListAsync();
        // SQL: SELECT * FROM Products (no WHERE clause)
    }

    // Ignore specific filter for admin operations
    public async Task<List<Product>> GetProductsForAdminAsync()
    {
        return await _context.Products
            .IgnoreQueryFilters()
            .Where(p => p.IsDeleted)
            .ToListAsync();
    }
}
```

**5. Dynamic Global Filters**

Create filters that can be modified at runtime:

```csharp
public class AppDbContext : DbContext
{
    private readonly ICurrentUserService _userService;

    protected override void OnModelCreating(ModelBuilder modelBuilder)
    {
        // Dynamic filter based on current user
        modelBuilder.Entity<Document>()
            .HasQueryFilter(d => 
                d.IsPublic || 
                d.OwnerId == _userService.GetCurrentUserId());
    }
}

public interface ICurrentUserService
{
    int? GetCurrentUserId();
}

// Usage with different users
public class DocumentService
{
    private readonly AppDbContext _context;
    private readonly ICurrentUserService _userService;

    public async Task<List<Document>> GetUserDocumentsAsync()
    {
        // Filter automatically applies based on current user
        return await _context.Documents.ToListAsync();
    }
}
```

**6. Global Filters with Navigation Properties**

```csharp
protected override void OnModelCreating(ModelBuilder modelBuilder)
{
    // Filter on related entities
    modelBuilder.Entity<Order>()
        .HasQueryFilter(o => 
            !o.IsDeleted && 
            o.Customer.IsActive);
    
    // Filter with multiple levels
    modelBuilder.Entity<OrderItem>()
        .HasQueryFilter(oi => 
            !oi.Order.IsDeleted && 
            !oi.Product.IsDeleted);
}

public class Order
{
    public int Id { get; set; }
    public bool IsDeleted { get; set; }
    public int CustomerId { get; set; }
    public Customer Customer { get; set; }
    public List<OrderItem> OrderItems { get; set; }
}

public class OrderItem
{
    public int Id { get; set; }
    public int OrderId { get; set; }
    public Order Order { get; set; }
    public int ProductId { get; set; }
    public Product Product { get; set; }
}
```

**7. Performance Considerations**

```csharp
public class OptimizedGlobalFilters
{
    // ✅ Good: Simple, indexed conditions
    protected override void OnModelCreating(ModelBuilder modelBuilder)
    {
        modelBuilder.Entity<Product>()
            .HasQueryFilter(p => p.IsActive); // Simple boolean check
    }

    // ❌ Avoid: Complex calculations in filters
    protected override void OnModelCreating(ModelBuilder modelBuilder)
    {
        modelBuilder.Entity<Product>()
            .HasQueryFilter(p => 
                p.CreatedAt.AddDays(30) > DateTime.UtcNow); // Complex calculation
    }

    // ✅ Better: Pre-calculate values
    protected override void OnModelCreating(ModelBuilder modelBuilder)
    {
        var thirtyDaysAgo = DateTime.UtcNow.AddDays(-30);
        
        modelBuilder.Entity<Product>()
            .HasQueryFilter(p => p.CreatedAt > thirtyDaysAgo);
    }
}
```

**8. Testing with Global Filters**

```csharp
public class ProductServiceTests
{
    [Test]
    public async Task GetProducts_ShouldExcludeDeletedProducts()
    {
        // Arrange
        var options = new DbContextOptionsBuilder<AppDbContext>()
            .UseInMemoryDatabase(databaseName: Guid.NewGuid().ToString())
            .Options;

        using var context = new AppDbContext(options);
        
        // Add test data
        context.Products.AddRange(new[]
        {
            new Product { Id = 1, Name = "Active Product", IsDeleted = false },
            new Product { Id = 2, Name = "Deleted Product", IsDeleted = true }
        });
        await context.SaveChangesAsync();

        // Act
        var products = await context.Products.ToListAsync();

        // Assert
        Assert.That(products.Count, Is.EqualTo(1));
        Assert.That(products[0].Name, Is.EqualTo("Active Product"));
    }

    [Test]
    public async Task GetAllProducts_WithIgnoreQueryFilters_ShouldReturnAll()
    {
        // Arrange
        var options = new DbContextOptionsBuilder<AppDbContext>()
            .UseInMemoryDatabase(databaseName: Guid.NewGuid().ToString())
            .Options;

        using var context = new AppDbContext(options);
        
        context.Products.AddRange(new[]
        {
            new Product { Id = 1, Name = "Active Product", IsDeleted = false },
            new Product { Id = 2, Name = "Deleted Product", IsDeleted = true }
        });
        await context.SaveChangesAsync();

        // Act
        var products = await context.Products
            .IgnoreQueryFilters()
            .ToListAsync();

        // Assert
        Assert.That(products.Count, Is.EqualTo(2));
    }
}
```

**9. Advanced Global Filter Patterns**

```csharp
public class AdvancedGlobalFilters
{
    protected override void OnModelCreating(ModelBuilder modelBuilder)
    {
        // Time-based filtering
        modelBuilder.Entity<Event>()
            .HasQueryFilter(e => e.StartDate > DateTime.UtcNow);
        
        // Status-based filtering
        modelBuilder.Entity<Job>()
            .HasQueryFilter(j => j.Status != JobStatus.Cancelled);
        
        // Permission-based filtering
        modelBuilder.Entity<File>()
            .HasQueryFilter(f => 
                f.IsPublic || 
                f.OwnerId == _userService.GetCurrentUserId() ||
                f.Permissions.Any(p => p.UserId == _userService.GetCurrentUserId()));
        
        // Hierarchical filtering
        modelBuilder.Entity<Comment>()
            .HasQueryFilter(c => 
                !c.IsDeleted && 
                !c.Post.IsDeleted && 
                c.Post.IsPublished);
    }
}
```

**Key Benefits:**

1. **Automatic Filtering**: No need to remember to add filters to every query
2. **Consistency**: Ensures all queries follow the same filtering rules
3. **Security**: Implements row-level security automatically
4. **Multi-tenancy**: Easy implementation of tenant isolation
5. **Soft Deletes**: Automatic exclusion of deleted records

**Best Practices:**

- Keep filters simple and performant
- Use indexed columns in filter conditions
- Test with `IgnoreQueryFilters()` when needed
- Consider performance impact on complex filters
- Use for security and data isolation, not business logic
- Document global filters for team understanding

---

### 5.15. How do you implement database connection management and connection pooling in EF Core?

**Answer:**

Database connection management and pooling in EF Core are crucial for performance and scalability. EF Core uses ADO.NET connection pooling by default, but you can configure and optimize it for your specific needs.

**1. Basic Connection String Configuration**

```csharp
// appsettings.json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Database=MyApp;Trusted_Connection=true;TrustServerCertificate=true;",
    "ProductionConnection": "Server=prod-server;Database=MyApp;User Id=appuser;Password=securepassword;TrustServerCertificate=true;"
  }
}

// Program.cs
var builder = WebApplication.CreateBuilder(args);

builder.Services.AddDbContext<AppDbContext>(options =>
    options.UseSqlServer(builder.Configuration.GetConnectionString("DefaultConnection")));
```

**2. Connection Pooling Configuration**

```csharp
// Connection string with pooling settings
var connectionString = "Server=localhost;Database=MyApp;Trusted_Connection=true;" +
    "Min Pool Size=5;" +           // Minimum connections in pool
    "Max Pool Size=100;" +         // Maximum connections in pool
    "Connection Lifetime=300;" +   // Connection lifetime in seconds
    "Connection Timeout=30;" +     // Connection timeout
    "Command Timeout=60;" +        // Command timeout
    "Pooling=true;";               // Enable pooling (default: true)

builder.Services.AddDbContext<AppDbContext>(options =>
    options.UseSqlServer(connectionString));
```

**3. Advanced Connection Configuration**

```csharp
public class AppDbContext : DbContext
{
    public AppDbContext(DbContextOptions<AppDbContext> options) : base(options)
    {
    }

    protected override void OnConfiguring(DbContextOptionsBuilder optionsBuilder)
    {
        if (!optionsBuilder.IsConfigured)
        {
            optionsBuilder.UseSqlServer(connectionString, sqlOptions =>
            {
                sqlOptions.CommandTimeout(60);
                sqlOptions.EnableRetryOnFailure(
                    maxRetryCount: 3,
                    maxRetryDelay: TimeSpan.FromSeconds(30),
                    errorNumbersToAdd: null);
            });
        }
    }
}
```

**4. Multiple Database Contexts with Different Pools**

```csharp
// Program.cs
builder.Services.AddDbContext<AppDbContext>(options =>
    options.UseSqlServer(builder.Configuration.GetConnectionString("DefaultConnection")));

builder.Services.AddDbContext<AuditDbContext>(options =>
    options.UseSqlServer(builder.Configuration.GetConnectionString("AuditConnection")));

builder.Services.AddDbContext<ReportingDbContext>(options =>
    options.UseSqlServer(builder.Configuration.GetConnectionString("ReportingConnection")));

// Usage in services
public class OrderService
{
    private readonly AppDbContext _context;
    private readonly AuditDbContext _auditContext;

    public OrderService(AppDbContext context, AuditDbContext auditContext)
    {
        _context = context;
        _auditContext = auditContext;
    }
}
```

**5. Connection Pool Monitoring**

```csharp
public class ConnectionPoolMonitor
{
    private readonly ILogger<ConnectionPoolMonitor> _logger;
    private readonly AppDbContext _context;

    public ConnectionPoolMonitor(ILogger<ConnectionPoolMonitor> logger, AppDbContext context)
    {
        _logger = logger;
        _context = context;
    }

    public async Task MonitorConnectionPoolAsync()
    {
        try
        {
            // Get connection pool statistics
            var connection = _context.Database.GetDbConnection();
            
            if (connection is SqlConnection sqlConnection)
            {
                _logger.LogInformation("Connection Pool Statistics:");
                _logger.LogInformation("Connection String: {ConnectionString}", 
                    sqlConnection.ConnectionString);
                _logger.LogInformation("Connection State: {State}", 
                    sqlConnection.State);
                _logger.LogInformation("Server Version: {Version}", 
                    sqlConnection.ServerVersion);
            }

            // Test connection
            await _context.Database.OpenConnectionAsync();
            _logger.LogInformation("Database connection successful");
        }
        catch (Exception ex)
        {
            _logger.LogError(ex, "Database connection failed");
        }
        finally
        {
            await _context.Database.CloseConnectionAsync();
        }
    }
}
```

**6. Custom Connection Factory**

```csharp
public class CustomConnectionFactory : IDbConnectionFactory
{
    private readonly IConfiguration _configuration;
    private readonly ILogger<CustomConnectionFactory> _logger;

    public CustomConnectionFactory(IConfiguration configuration, ILogger<CustomConnectionFactory> logger)
    {
        _configuration = configuration;
        _logger = logger;
    }

    public DbConnection CreateConnection(string connectionString)
    {
        var connection = new SqlConnection(connectionString);
        
        // Add connection event handlers
        connection.StateChange += OnConnectionStateChange;
        connection.InfoMessage += OnConnectionInfoMessage;
        
        return connection;
    }

    private void OnConnectionStateChange(object sender, StateChangeEventArgs e)
    {
        _logger.LogInformation("Connection state changed from {OriginalState} to {CurrentState}",
            e.OriginalState, e.CurrentState);
    }

    private void OnConnectionInfoMessage(object sender, SqlInfoMessageEventArgs e)
    {
        _logger.LogInformation("SQL Info: {Message}", e.Message);
    }
}

// Register custom connection factory
builder.Services.AddSingleton<IDbConnectionFactory, CustomConnectionFactory>();
```

**7. Connection Resilience and Retry Policies**

```csharp
// Program.cs
builder.Services.AddDbContext<AppDbContext>(options =>
{
    options.UseSqlServer(connectionString, sqlOptions =>
    {
        // Retry policy for transient failures
        sqlOptions.EnableRetryOnFailure(
            maxRetryCount: 3,
            maxRetryDelay: TimeSpan.FromSeconds(30),
            errorNumbersToAdd: null);
        
        // Connection timeout
        sqlOptions.CommandTimeout(60);
    });
});

// Custom retry policy
public class ResilientDbContext : AppDbContext
{
    public ResilientDbContext(DbContextOptions<AppDbContext> options) : base(options)
    {
    }

    public override async Task<int> SaveChangesAsync(CancellationToken cancellationToken = default)
    {
        var retryPolicy = Policy
            .Handle<SqlException>(ex => IsTransientError(ex))
            .WaitAndRetryAsync(
                retryCount: 3,
                sleepDurationProvider: retryAttempt => TimeSpan.FromSeconds(Math.Pow(2, retryAttempt)),
                onRetry: (outcome, timespan, retryCount, context) =>
                {
                    Console.WriteLine($"Retry {retryCount} after {timespan} seconds");
                });

        return await retryPolicy.ExecuteAsync(async () =>
        {
            return await base.SaveChangesAsync(cancellationToken);
        });
    }

    private static bool IsTransientError(SqlException ex)
    {
        // SQL Server transient error numbers
        var transientErrors = new[] { 2, 53, 121, 1205, 1222, 8645, 8651 };
        return transientErrors.Contains(ex.Number);
    }
}
```

**8. Connection Pool Optimization**

```csharp
public class ConnectionPoolOptimizer
{
    private readonly IConfiguration _configuration;

    public ConnectionPoolOptimizer(IConfiguration configuration)
    {
        _configuration = configuration;
    }

    public string GetOptimizedConnectionString(string baseConnectionString)
    {
        var builder = new SqlConnectionStringBuilder(baseConnectionString);
        
        // Optimize for high-throughput scenarios
        builder.MinPoolSize = 10;           // Keep more connections ready
        builder.MaxPoolSize = 200;          // Allow more concurrent connections
        builder.ConnectionLifetime = 600;   // 10 minutes connection lifetime
        builder.ConnectionTimeout = 15;     // Faster connection timeout
        builder.CommandTimeout = 30;        // Reasonable command timeout
        
        // Enable connection pooling
        builder.Pooling = true;
        
        // Enable multiple active result sets
        builder.MultipleActiveResultSets = true;
        
        // Optimize for read-heavy workloads
        builder.ApplicationIntent = ApplicationIntent.ReadOnly;
        
        return builder.ConnectionString;
    }

    public string GetOptimizedConnectionStringForWrites(string baseConnectionString)
    {
        var builder = new SqlConnectionStringBuilder(baseConnectionString);
        
        // Optimize for write-heavy scenarios
        builder.MinPoolSize = 5;            // Fewer connections for writes
        builder.MaxPoolSize = 50;           // Limit concurrent writes
        builder.ConnectionLifetime = 300;   // Shorter connection lifetime
        builder.ConnectionTimeout = 30;     // Longer connection timeout for writes
        builder.CommandTimeout = 60;        // Longer command timeout for writes
        
        // Enable connection pooling
        builder.Pooling = true;
        
        // Optimize for write workloads
        builder.ApplicationIntent = ApplicationIntent.ReadWrite;
        
        return builder.ConnectionString;
    }
}
```

**9. Environment-Specific Connection Management**

```csharp
// Program.cs
public static void ConfigureDatabase(WebApplicationBuilder builder)
{
    var environment = builder.Environment.EnvironmentName;
    
    switch (environment)
    {
        case "Development":
            ConfigureDevelopmentDatabase(builder);
            break;
        case "Staging":
            ConfigureStagingDatabase(builder);
            break;
        case "Production":
            ConfigureProductionDatabase(builder);
            break;
    }
}

private static void ConfigureDevelopmentDatabase(WebApplicationBuilder builder)
{
    builder.Services.AddDbContext<AppDbContext>(options =>
    {
        options.UseSqlServer(builder.Configuration.GetConnectionString("DefaultConnection"));
        options.EnableSensitiveDataLogging();
        options.EnableDetailedErrors();
        options.LogTo(Console.WriteLine, LogLevel.Information);
    });
}

private static void ConfigureProductionDatabase(WebApplicationBuilder builder)
{
    builder.Services.AddDbContext<AppDbContext>(options =>
    {
        var connectionString = builder.Configuration.GetConnectionString("ProductionConnection");
        
        options.UseSqlServer(connectionString, sqlOptions =>
        {
            sqlOptions.EnableRetryOnFailure(
                maxRetryCount: 3,
                maxRetryDelay: TimeSpan.FromSeconds(30));
            sqlOptions.CommandTimeout(60);
        });
        
        // Disable sensitive data logging in production
        options.EnableSensitiveDataLogging(false);
        options.EnableDetailedErrors(false);
    });
}
```

**10. Connection Health Checks**

```csharp
public class DatabaseHealthCheck : IHealthCheck
{
    private readonly AppDbContext _context;

    public DatabaseHealthCheck(AppDbContext context)
    {
        _context = context;
    }

    public async Task<HealthCheckResult> CheckHealthAsync(
        HealthCheckContext context, 
        CancellationToken cancellationToken = default)
    {
        try
        {
            // Test database connection
            await _context.Database.OpenConnectionAsync(cancellationToken);
            
            // Test simple query
            await _context.Database.ExecuteSqlRawAsync("SELECT 1", cancellationToken);
            
            // Get connection pool info
            var connection = _context.Database.GetDbConnection();
            var connectionState = connection.State;
            
            return HealthCheckResult.Healthy($"Database is healthy. Connection state: {connectionState}");
        }
        catch (Exception ex)
        {
            return HealthCheckResult.Unhealthy("Database connection failed", ex);
        }
        finally
        {
            await _context.Database.CloseConnectionAsync();
        }
    }
}

// Register health check
builder.Services.AddHealthChecks()
    .AddCheck<DatabaseHealthCheck>("database");
```

**Key Points:**

1. **Default Pooling**: EF Core uses ADO.NET connection pooling by default
2. **Connection String**: Configure pool size, timeouts, and lifetime
3. **Multiple Contexts**: Each context can have its own connection pool
4. **Resilience**: Implement retry policies for transient failures
5. **Monitoring**: Track connection pool health and performance
6. **Environment-Specific**: Different configurations for different environments
7. **Resource Management**: Proper disposal and connection lifecycle management

**Best Practices:**

- Configure appropriate pool sizes based on your workload
- Use connection timeouts to prevent hanging connections
- Implement retry policies for transient failures
- Monitor connection pool health and performance
- Use different connection strings for read vs write operations
- Test connection resilience under load
- Implement proper error handling and logging
- Use health checks to monitor database connectivity

---

## 6. Performance and Memory Management

### 6.1. Explain garbage collection in .NET and its generations.

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

### 6.2. What are memory leaks and how do you identify them in .NET?

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



### 6.3. What is the difference between stack and heap memory?

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

### 6.4. How would you profile and optimize a .NET application?

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

### 6.5. What is `Span<T>` and `Memory<T>`? When should you use them?

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

### 6.6. Explain object pooling and when to use it.

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
### 6.7. What are the best practices for string concatenation in loops?

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

### 6.8. How do you reduce memory allocations in performance-critical code?

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

### 6.9. What is the Large Object Heap (LOH)?

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

### 6.10. Explain the concept of weak references

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

## 7. LINQ and Collections

### 7.1. What is LINQ and what are its advantages?

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

### 7.2. Explain the difference between LINQ query syntax and method syntax.

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

### 7.3. What is the difference between `First()`, `FirstOrDefault()`, `Single()`, and `SingleOrDefault()`?

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

### 7.4. Explain deferred execution in LINQ.

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

### 7.5. What is the difference between `Select()` and `SelectMany()`?

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

### 7.6. How do you optimize LINQ queries?

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

### 7.7. What are the differences between `List<T>`, `HashSet<T>`, and `Dictionary<TKey, TValue>`?

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

### 7.8. When would you use `ConcurrentDictionary` over `Dictionary`?

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

### 7.9. Explain `GroupBy()` and `Join()` operations in LINQ.

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

### 7.10. What is the difference between `Where().Select()` and `Select().Where()`?

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

## 8. Testing

### 8.1. What is unit testing and why is it important?

**Unit testing** is the practice of testing individual units or components of code in isolation, typically at the function or method level. A unit test verifies that a specific piece of code behaves as expected under various conditions.

**Why it's important:**

- **Early Bug Detection**: Catches bugs early in development when they're cheaper to fix
- **Documentation**: Tests serve as living documentation showing how code should be used
- **Refactoring Confidence**: Enables safe refactoring by ensuring existing functionality isn't broken
- **Design Improvement**: Writing testable code often leads to better architecture and loose coupling
- **Regression Prevention**: Prevents old bugs from reappearing
- **Faster Development**: Though initial setup takes time, it speeds up long-term development
- **Quality Assurance**: Provides confidence that code works correctly

### 8.2. Explain the AAA pattern (Arrange, Act, Assert)

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

### 8.3. What is the difference between mocking, stubbing, and faking?

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

### 8.4. What testing frameworks have you used in .NET (xUnit, NUnit, MSTest)?

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

### 8.5. How do you write testable code?

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

### 8.6. What is TDD (Test-Driven Development)?

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

### 8.7. Explain integration testing vs unit testing

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

### 8.8. What is code coverage and what is a good coverage percentage?

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

## 9. Microservices and Architecture

### 9.1. What are microservices and what are their advantages and disadvantages?

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

### 9.2. Explain the difference between monolithic and microservices architecture.

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

### 9.3. What is API Gateway pattern?

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

### 9.4. How do you handle inter-service communication in microservices?

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

### 9.5. What is the Circuit Breaker pattern?

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

### 9.6. Explain eventual consistency in distributed systems.

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

### 9.7. What is the Saga pattern for distributed transactions?

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

### 9.8. How do you implement service discovery?

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

### 9.9. What are containers and how do they relate to microservices?

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

### 9.10. Explain the strangler pattern for migrating to microservices.

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

**Summary**

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

## 10. Security

### 10.1. What is SQL injection and how do you prevent it?

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

### 10.2. Explain Cross-Site Scripting (XSS) and Cross-Site Request Forgery (CSRF)

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

### 10.3. What are the best practices for storing passwords?

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

### 10.4. How do you implement OAuth 2.0 and OpenID Connect?

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

### 10.5. What is the principle of least privilege?

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

### 10.6. How do you secure sensitive data in configuration files?

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

### 10.7. Explain the importance of HTTPS and how to implement it

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

### 10.8. What are the OWASP Top 10 security risks?

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

### 10.9. Security Checklist for .NET Core Applications

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

### 10.10. Additional Resources

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [Microsoft Security Documentation](https://docs.microsoft.com/en-us/aspnet/core/security/)
- [.NET Security Best Practices](https://docs.microsoft.com/en-us/dotnet/standard/security/)
- [ASP.NET Core Security](https://docs.microsoft.com/en-us/aspnet/core/security/)
- [NuGet Package Vulnerability Scanning](https://devblogs.microsoft.com/nuget/how-to-scan-nuget-packages-for-security-vulnerabilities/)

---

### 10.11. Code Examples Summary

All code examples in this guide follow .NET Core best practices and are production-ready. Remember to:

1. Test all security implementations thoroughly
2. Keep dependencies updated
3. Perform regular security audits
4. Follow the principle of defense in depth
5. Never trust user input
6. Assume breach and minimize impact
---

## 11. Domain-Driven Design and Clean Architecture

### 11.1. What is Domain-Driven Design (DDD) and what are its core principles?

**Answer:**

Domain-Driven Design (DDD) is a software development approach that focuses on creating software that reflects a deep understanding of the business domain. It emphasizes collaboration between technical and domain experts to build software that accurately models the business.

**Core Principles of DDD:**

1. **Focus on the Domain**
   - The domain is the heart of the software
   - Business logic should be the primary concern
   - Technical concerns are secondary

2. **Ubiquitous Language**
   - Use the same language throughout the codebase, documentation, and conversations
   - Terms should be consistent between developers and domain experts
   - Code should reflect business terminology

3. **Model-Driven Design**
   - The code should be a direct reflection of the domain model
   - Changes in understanding should lead to changes in the code
   - The model should evolve with business understanding

**Example of Ubiquitous Language:**

```csharp
// ❌ Technical language
public class UserAccount
{
    public int Id { get; set; }
    public string Username { get; set; }
    public bool IsActive { get; set; }
}

// ✅ Domain language
public class Customer
{
    public CustomerId Id { get; set; }
    public CustomerName Name { get; set; }
    public CustomerStatus Status { get; set; }
}

public enum CustomerStatus
{
    Active,
    Suspended,
    Closed
}
```

**Strategic Design Patterns:**

1. **Bounded Contexts**
   - Define clear boundaries around models
   - Each context has its own ubiquitous language
   - Models can be different in different contexts

```csharp
// E-commerce context
public class Product
{
    public ProductId Id { get; set; }
    public ProductName Name { get; set; }
    public Money Price { get; set; }
    public ProductCategory Category { get; set; }
}

// Inventory context
public class InventoryItem
{
    public InventoryItemId Id { get; set; }
    public string SKU { get; set; }
    public int QuantityOnHand { get; set; }
    public int ReorderLevel { get; set; }
}
```

2. **Context Mapping**
   - Define relationships between bounded contexts
   - Shared Kernel, Customer-Supplier, Conformist, Anti-Corruption Layer

**Tactical Design Patterns:**

1. **Entities**
   - Objects with identity that persists over time
   - Identity is more important than attributes

```csharp
public class Order : Entity<OrderId>
{
    public OrderId Id { get; private set; }
    public CustomerId CustomerId { get; private set; }
    public OrderStatus Status { get; private set; }
    private readonly List<OrderItem> _items = new();
    
    public IReadOnlyList<OrderItem> Items => _items.AsReadOnly();
    
    public void AddItem(ProductId productId, Quantity quantity, Money unitPrice)
    {
        // Business logic for adding items
        if (Status != OrderStatus.Draft)
            throw new InvalidOperationException("Cannot add items to a confirmed order");
            
        _items.Add(new OrderItem(productId, quantity, unitPrice));
    }
}
```

2. **Value Objects**
   - Objects defined by their attributes, not identity
   - Immutable and comparable by value

```csharp
public class Money : ValueObject
{
    public decimal Amount { get; }
    public string Currency { get; }
    
    public Money(decimal amount, string currency)
    {
        if (amount < 0) throw new ArgumentException("Amount cannot be negative");
        if (string.IsNullOrEmpty(currency)) throw new ArgumentException("Currency is required");
        
        Amount = amount;
        Currency = currency;
    }
    
    protected override IEnumerable<object> GetEqualityComponents()
    {
        yield return Amount;
        yield return Currency;
    }
    
    public static Money operator +(Money left, Money right)
    {
        if (left.Currency != right.Currency)
            throw new InvalidOperationException("Cannot add different currencies");
            
        return new Money(left.Amount + right.Amount, left.Currency);
    }
}
```

3. **Aggregates**
   - Cluster of related objects treated as a unit
   - One aggregate root controls access to the cluster

```csharp
public class Order : AggregateRoot<OrderId>
{
    private readonly List<OrderItem> _items = new();
    
    public void Confirm()
    {
        if (_items.Count == 0)
            throw new InvalidOperationException("Cannot confirm an empty order");
            
        Status = OrderStatus.Confirmed;
        AddDomainEvent(new OrderConfirmedEvent(Id, CustomerId));
    }
    
    public void Cancel()
    {
        if (Status == OrderStatus.Shipped)
            throw new InvalidOperationException("Cannot cancel a shipped order");
            
        Status = OrderStatus.Cancelled;
        AddDomainEvent(new OrderCancelledEvent(Id, CustomerId));
    }
}
```

4. **Domain Services**
   - Operations that don't naturally belong to entities or value objects
   - Stateless operations that involve multiple domain objects

```csharp
public class OrderPricingService : IDomainService
{
    public Money CalculateTotal(Order order, ICustomerRepository customerRepository)
    {
        var customer = customerRepository.GetById(order.CustomerId);
        var baseTotal = order.Items.Sum(item => item.Total);
        
        // Apply customer-specific discounts
        var discount = customer.GetDiscountPercentage();
        var discountAmount = baseTotal * (discount / 100);
        
        return baseTotal - discountAmount;
    }
}
```

5. **Domain Events**
   - Something important that happened in the domain
   - Used for decoupling and integration

```csharp
public class OrderConfirmedEvent : DomainEvent
{
    public OrderId OrderId { get; }
    public CustomerId CustomerId { get; }
    public DateTime ConfirmedAt { get; }
    
    public OrderConfirmedEvent(OrderId orderId, CustomerId customerId)
    {
        OrderId = orderId;
        CustomerId = customerId;
        ConfirmedAt = DateTime.UtcNow;
    }
}

// Event handler
public class OrderConfirmedEventHandler : IDomainEventHandler<OrderConfirmedEvent>
{
    private readonly IEmailService _emailService;
    
    public async Task Handle(OrderConfirmedEvent domainEvent)
    {
        await _emailService.SendOrderConfirmationAsync(domainEvent.CustomerId, domainEvent.OrderId);
    }
}
```

**Benefits of DDD:**

1. **Better Communication**: Ubiquitous language improves team communication
2. **Focused Design**: Clear boundaries prevent complexity
3. **Business Alignment**: Software reflects business understanding
4. **Maintainability**: Well-structured domain models are easier to maintain
5. **Testability**: Clear domain logic is easier to test

**When to Use DDD:**

- Complex business domains
- Long-lived applications
- When business logic is the primary concern
- When you have access to domain experts
- When the domain is well-understood

**Challenges of DDD:**

- Requires domain expertise
- Can be overkill for simple applications
- Initial learning curve
- Requires discipline to maintain boundaries
- Can lead to over-engineering if not applied judiciously

---

### 11.2. Explain the difference between Domain, Application, Infrastructure, and Presentation layers in Clean Architecture.

**Answer:**

Clean Architecture (also known as Onion Architecture or Hexagonal Architecture) organizes code into concentric layers with clear dependencies and responsibilities. Each layer has a specific purpose and follows the Dependency Inversion Principle.

**Layer Structure:**

```
┌─────────────────────────────────────┐
│           Presentation              │ ← Controllers, UI, APIs
├─────────────────────────────────────┤
│           Application               │ ← Use Cases, Services
├─────────────────────────────────────┤
│             Domain                  │ ← Business Logic, Entities
├─────────────────────────────────────┤
│          Infrastructure             │ ← Data Access, External Services
└─────────────────────────────────────┘
```

**1. Domain Layer (Core)**

The innermost layer containing business logic and rules. It has no dependencies on other layers.

```csharp
// Domain/Entities/Order.cs
public class Order : AggregateRoot<OrderId>
{
    public OrderId Id { get; private set; }
    public CustomerId CustomerId { get; private set; }
    public OrderStatus Status { get; private set; }
    private readonly List<OrderItem> _items = new();
    
    public void AddItem(ProductId productId, Quantity quantity, Money unitPrice)
    {
        if (Status != OrderStatus.Draft)
            throw new InvalidOperationException("Cannot add items to confirmed order");
            
        _items.Add(new OrderItem(productId, quantity, unitPrice));
    }
    
    public void Confirm()
    {
        if (_items.Count == 0)
            throw new InvalidOperationException("Cannot confirm empty order");
            
        Status = OrderStatus.Confirmed;
        AddDomainEvent(new OrderConfirmedEvent(Id, CustomerId));
    }
}

// Domain/ValueObjects/Money.cs
public class Money : ValueObject
{
    public decimal Amount { get; }
    public string Currency { get; }
    
    public Money(decimal amount, string currency)
    {
        Amount = amount;
        Currency = currency;
    }
}

// Domain/Interfaces/IOrderRepository.cs
public interface IOrderRepository
{
    Task<Order> GetByIdAsync(OrderId id);
    Task SaveAsync(Order order);
    Task DeleteAsync(OrderId id);
}
```

**2. Application Layer**

Contains use cases and application services. Depends only on the Domain layer.

```csharp
// Application/UseCases/CreateOrder/CreateOrderCommand.cs
public record CreateOrderCommand(CustomerId CustomerId, List<OrderItemDto> Items);

// Application/UseCases/CreateOrder/CreateOrderHandler.cs
public class CreateOrderHandler : IRequestHandler<CreateOrderCommand, OrderId>
{
    private readonly IOrderRepository _orderRepository;
    private readonly IProductRepository _productRepository;
    private readonly IUnitOfWork _unitOfWork;
    
    public async Task<OrderId> Handle(CreateOrderCommand request, CancellationToken cancellationToken)
    {
        var order = new Order(request.CustomerId);
        
        foreach (var item in request.Items)
        {
            var product = await _productRepository.GetByIdAsync(item.ProductId);
            var quantity = new Quantity(item.Quantity);
            var unitPrice = new Money(item.UnitPrice, "USD");
            
            order.AddItem(product.Id, quantity, unitPrice);
        }
        
        await _orderRepository.SaveAsync(order);
        await _unitOfWork.CommitAsync();
        
        return order.Id;
    }
}

// Application/Services/OrderApplicationService.cs
public class OrderApplicationService
{
    private readonly IOrderRepository _orderRepository;
    private readonly IOrderPricingService _pricingService;
    
    public async Task<OrderDto> GetOrderDetailsAsync(OrderId orderId)
    {
        var order = await _orderRepository.GetByIdAsync(orderId);
        var total = _pricingService.CalculateTotal(order);
        
        return new OrderDto
        {
            Id = order.Id.Value,
            CustomerId = order.CustomerId.Value,
            Status = order.Status.ToString(),
            Total = total.Amount,
            Items = order.Items.Select(item => new OrderItemDto
            {
                ProductId = item.ProductId.Value,
                Quantity = item.Quantity.Value,
                UnitPrice = item.UnitPrice.Amount
            }).ToList()
        };
    }
}
```

**3. Infrastructure Layer**

Handles external concerns like data persistence, external APIs, and frameworks. Implements interfaces defined in the Domain layer.

```csharp
// Infrastructure/Data/Repositories/OrderRepository.cs
public class OrderRepository : IOrderRepository
{
    private readonly ApplicationDbContext _context;
    
    public async Task<Order> GetByIdAsync(OrderId id)
    {
        var orderEntity = await _context.Orders
            .Include(o => o.Items)
            .FirstOrDefaultAsync(o => o.Id == id.Value);
            
        if (orderEntity == null)
            return null;
            
        return MapToDomain(orderEntity);
    }
    
    public async Task SaveAsync(Order order)
    {
        var orderEntity = MapToEntity(order);
        
        if (_context.Entry(orderEntity).State == EntityState.Detached)
            _context.Orders.Add(orderEntity);
        else
            _context.Orders.Update(orderEntity);
            
        await _context.SaveChangesAsync();
    }
    
    private Order MapToDomain(OrderEntity entity)
    {
        // Mapping logic from entity to domain object
        return new Order(new OrderId(entity.Id))
        {
            CustomerId = new CustomerId(entity.CustomerId),
            Status = Enum.Parse<OrderStatus>(entity.Status)
        };
    }
}

// Infrastructure/Data/ApplicationDbContext.cs
public class ApplicationDbContext : DbContext
{
    public DbSet<OrderEntity> Orders { get; set; }
    public DbSet<OrderItemEntity> OrderItems { get; set; }
    
    protected override void OnModelCreating(ModelBuilder modelBuilder)
    {
        modelBuilder.ApplyConfigurationsFromAssembly(typeof(ApplicationDbContext).Assembly);
    }
}

// Infrastructure/ExternalServices/EmailService.cs
public class EmailService : IEmailService
{
    private readonly SmtpClient _smtpClient;
    
    public async Task SendOrderConfirmationAsync(CustomerId customerId, OrderId orderId)
    {
        // Implementation for sending email
        var message = new MailMessage();
        // ... email logic
        await _smtpClient.SendMailAsync(message);
    }
}
```

**4. Presentation Layer**

Handles user interface and external API concerns. Depends on the Application layer.

```csharp
// Presentation/Controllers/OrdersController.cs
[ApiController]
[Route("api/[controller]")]
public class OrdersController : ControllerBase
{
    private readonly IMediator _mediator;
    private readonly OrderApplicationService _orderService;
    
    [HttpPost]
    public async Task<ActionResult<OrderId>> CreateOrder([FromBody] CreateOrderRequest request)
    {
        var command = new CreateOrderCommand(
            new CustomerId(request.CustomerId),
            request.Items.Select(item => new OrderItemDto
            {
                ProductId = new ProductId(item.ProductId),
                Quantity = item.Quantity,
                UnitPrice = item.UnitPrice
            }).ToList()
        );
        
        var orderId = await _mediator.Send(command);
        return Ok(orderId);
    }
    
    [HttpGet("{id}")]
    public async Task<ActionResult<OrderDto>> GetOrder(int id)
    {
        var order = await _orderService.GetOrderDetailsAsync(new OrderId(id));
        return Ok(order);
    }
}

// Presentation/Models/CreateOrderRequest.cs
public class CreateOrderRequest
{
    public int CustomerId { get; set; }
    public List<OrderItemRequest> Items { get; set; }
}

public class OrderItemRequest
{
    public int ProductId { get; set; }
    public int Quantity { get; set; }
    public decimal UnitPrice { get; set; }
}
```

**Dependency Flow:**

```csharp
// ✅ Correct: Dependencies point inward
Presentation → Application → Domain
Infrastructure → Domain

// ❌ Wrong: Dependencies point outward
Domain → Application → Presentation
Domain → Infrastructure
```

**Key Principles:**

1. **Dependency Inversion**: High-level modules don't depend on low-level modules
2. **Single Responsibility**: Each layer has one reason to change
3. **Interface Segregation**: Depend on abstractions, not concretions
4. **Open/Closed**: Open for extension, closed for modification

**Benefits:**

- **Testability**: Easy to unit test business logic
- **Maintainability**: Clear separation of concerns
- **Flexibility**: Easy to change external dependencies
- **Independence**: Business logic independent of frameworks
- **Reusability**: Domain logic can be reused across applications

**Project Structure:**

```
src/
├── Domain/
│   ├── Entities/
│   ├── ValueObjects/
│   ├── Interfaces/
│   └── Events/
├── Application/
│   ├── UseCases/
│   ├── Services/
│   └── DTOs/
├── Infrastructure/
│   ├── Data/
│   ├── ExternalServices/
│   └── Configuration/
└── Presentation/
    ├── Controllers/
    ├── Models/
    └── Middleware/
```

This architecture ensures that business logic remains pure and independent of external concerns, making the system more maintainable and testable.

---

### 11.3. What are the main building blocks of DDD (Entities, Value Objects, Aggregates, Domain Services)?

**Answer:**

Domain-Driven Design provides several tactical patterns as building blocks to model complex business domains effectively. These patterns help create a rich domain model that accurately represents business concepts.

**1. Entities**

Entities are objects with a distinct identity that persists over time. Their identity is more important than their attributes.

```csharp
public abstract class Entity<TId> where TId : ValueObject
{
    public TId Id { get; protected set; }
    
    protected Entity(TId id)
    {
        Id = id ?? throw new ArgumentNullException(nameof(id));
    }
    
    public override bool Equals(object obj)
    {
        if (obj is not Entity<TId> other) return false;
        if (ReferenceEquals(this, other)) return true;
        return Id.Equals(other.Id);
    }
    
    public override int GetHashCode() => Id.GetHashCode();
}

public class Customer : Entity<CustomerId>
{
    public CustomerName Name { get; private set; }
    public Email Email { get; private set; }
    public CustomerStatus Status { get; private set; }
    private readonly List<OrderId> _orderIds = new();
    
    public IReadOnlyList<OrderId> OrderIds => _orderIds.AsReadOnly();
    
    public Customer(CustomerId id, CustomerName name, Email email) : base(id)
    {
        Name = name ?? throw new ArgumentNullException(nameof(name));
        Email = email ?? throw new ArgumentNullException(nameof(email));
        Status = CustomerStatus.Active;
    }
    
    public void UpdateEmail(Email newEmail)
    {
        if (Status == CustomerStatus.Closed)
            throw new InvalidOperationException("Cannot update email for closed customer");
            
        Email = newEmail;
    }
    
    public void Close()
    {
        if (Status == CustomerStatus.Closed)
            throw new InvalidOperationException("Customer is already closed");
            
        Status = CustomerStatus.Closed;
    }
    
    public void AddOrder(OrderId orderId)
    {
        if (!_orderIds.Contains(orderId))
            _orderIds.Add(orderId);
    }
}
```

**2. Value Objects**

Value objects are defined by their attributes rather than identity. They are immutable and compared by value.

```csharp
public abstract class ValueObject
{
    protected abstract IEnumerable<object> GetEqualityComponents();
    
    public override bool Equals(object obj)
    {
        if (obj == null || obj.GetType() != GetType()) return false;
        
        var other = (ValueObject)obj;
        return GetEqualityComponents().SequenceEqual(other.GetEqualityComponents());
    }
    
    public override int GetHashCode()
    {
        return GetEqualityComponents()
            .Select(x => x?.GetHashCode() ?? 0)
            .Aggregate((x, y) => x ^ y);
    }
}

public class Money : ValueObject
{
    public decimal Amount { get; }
    public string Currency { get; }
    
    public Money(decimal amount, string currency)
    {
        if (amount < 0) throw new ArgumentException("Amount cannot be negative");
        if (string.IsNullOrWhiteSpace(currency)) 
            throw new ArgumentException("Currency is required");
            
        Amount = amount;
        Currency = currency.ToUpperInvariant();
    }
    
    protected override IEnumerable<object> GetEqualityComponents()
    {
        yield return Amount;
        yield return Currency;
    }
    
    public static Money operator +(Money left, Money right)
    {
        if (left.Currency != right.Currency)
            throw new InvalidOperationException("Cannot add different currencies");
            
        return new Money(left.Amount + right.Amount, left.Currency);
    }
    
    public static Money operator -(Money left, Money right)
    {
        if (left.Currency != right.Currency)
            throw new InvalidOperationException("Cannot subtract different currencies");
            
        return new Money(left.Amount - right.Amount, left.Currency);
    }
    
    public static Money operator *(Money money, decimal multiplier)
    {
        return new Money(money.Amount * multiplier, money.Currency);
    }
}

public class Address : ValueObject
{
    public string Street { get; }
    public string City { get; }
    public string State { get; }
    public string ZipCode { get; }
    public string Country { get; }
    
    public Address(string street, string city, string state, string zipCode, string country)
    {
        Street = street ?? throw new ArgumentNullException(nameof(street));
        City = city ?? throw new ArgumentNullException(nameof(city));
        State = state ?? throw new ArgumentNullException(nameof(state));
        ZipCode = zipCode ?? throw new ArgumentNullException(nameof(zipCode));
        Country = country ?? throw new ArgumentNullException(nameof(country));
    }
    
    protected override IEnumerable<object> GetEqualityComponents()
    {
        yield return Street;
        yield return City;
        yield return State;
        yield return ZipCode;
        yield return Country;
    }
}
```

**3. Aggregates**

Aggregates are clusters of related objects treated as a unit for data changes. They have one aggregate root that controls access.

```csharp
public abstract class AggregateRoot<TId> : Entity<TId> where TId : ValueObject
{
    private readonly List<DomainEvent> _domainEvents = new();
    
    public IReadOnlyList<DomainEvent> DomainEvents => _domainEvents.AsReadOnly();
    
    protected AggregateRoot(TId id) : base(id) { }
    
    protected void AddDomainEvent(DomainEvent domainEvent)
    {
        _domainEvents.Add(domainEvent);
    }
    
    public void ClearDomainEvents()
    {
        _domainEvents.Clear();
    }
}

public class Order : AggregateRoot<OrderId>
{
    public CustomerId CustomerId { get; private set; }
    public OrderStatus Status { get; private set; }
    public DateTime CreatedAt { get; private set; }
    public Money Total { get; private set; }
    
    private readonly List<OrderItem> _items = new();
    public IReadOnlyList<OrderItem> Items => _items.AsReadOnly();
    
    public Order(OrderId id, CustomerId customerId) : base(id)
    {
        CustomerId = customerId ?? throw new ArgumentNullException(nameof(customerId));
        Status = OrderStatus.Draft;
        CreatedAt = DateTime.UtcNow;
        Total = new Money(0, "USD");
    }
    
    public void AddItem(ProductId productId, Quantity quantity, Money unitPrice)
    {
        if (Status != OrderStatus.Draft)
            throw new InvalidOperationException("Cannot add items to a confirmed order");
            
        var existingItem = _items.FirstOrDefault(i => i.ProductId == productId);
        if (existingItem != null)
        {
            existingItem.IncreaseQuantity(quantity);
        }
        else
        {
            _items.Add(new OrderItem(productId, quantity, unitPrice));
        }
        
        RecalculateTotal();
    }
    
    public void RemoveItem(ProductId productId)
    {
        if (Status != OrderStatus.Draft)
            throw new InvalidOperationException("Cannot remove items from a confirmed order");
            
        var item = _items.FirstOrDefault(i => i.ProductId == productId);
        if (item != null)
        {
            _items.Remove(item);
            RecalculateTotal();
        }
    }
    
    public void Confirm()
    {
        if (Status != OrderStatus.Draft)
            throw new InvalidOperationException("Order is not in draft status");
            
        if (_items.Count == 0)
            throw new InvalidOperationException("Cannot confirm an empty order");
            
        Status = OrderStatus.Confirmed;
        AddDomainEvent(new OrderConfirmedEvent(Id, CustomerId, Total));
    }
    
    public void Cancel()
    {
        if (Status == OrderStatus.Shipped)
            throw new InvalidOperationException("Cannot cancel a shipped order");
            
        Status = OrderStatus.Cancelled;
        AddDomainEvent(new OrderCancelledEvent(Id, CustomerId));
    }
    
    private void RecalculateTotal()
    {
        Total = _items.Aggregate(new Money(0, "USD"), (sum, item) => sum + item.Total);
    }
}

public class OrderItem : Entity<OrderItemId>
{
    public ProductId ProductId { get; private set; }
    public Quantity Quantity { get; private set; }
    public Money UnitPrice { get; private set; }
    public Money Total => UnitPrice * Quantity.Value;
    
    public OrderItem(ProductId productId, Quantity quantity, Money unitPrice) 
        : base(new OrderItemId(Guid.NewGuid()))
    {
        ProductId = productId ?? throw new ArgumentNullException(nameof(productId));
        Quantity = quantity ?? throw new ArgumentNullException(nameof(quantity));
        UnitPrice = unitPrice ?? throw new ArgumentNullException(nameof(unitPrice));
    }
    
    public void IncreaseQuantity(Quantity additionalQuantity)
    {
        Quantity = new Quantity(Quantity.Value + additionalQuantity.Value);
    }
    
    public void UpdateQuantity(Quantity newQuantity)
    {
        Quantity = newQuantity ?? throw new ArgumentNullException(nameof(newQuantity));
    }
}
```

**4. Domain Services**

Domain services contain business logic that doesn't naturally belong to entities or value objects.

```csharp
public interface IDomainService
{
}

public class OrderPricingService : IDomainService
{
    private readonly ICustomerRepository _customerRepository;
    private readonly IProductRepository _productRepository;
    
    public OrderPricingService(ICustomerRepository customerRepository, IProductRepository productRepository)
    {
        _customerRepository = customerRepository;
        _productRepository = productRepository;
    }
    
    public Money CalculateOrderTotal(Order order)
    {
        var baseTotal = order.Items.Sum(item => item.Total);
        var customer = _customerRepository.GetById(order.CustomerId);
        
        // Apply customer-specific discount
        var discountPercentage = GetCustomerDiscountPercentage(customer);
        var discountAmount = baseTotal * (discountPercentage / 100);
        
        // Apply bulk order discount
        var bulkDiscount = CalculateBulkDiscount(order.Items.Count());
        var bulkDiscountAmount = baseTotal * (bulkDiscount / 100);
        
        var totalDiscount = discountAmount + bulkDiscountAmount;
        return baseTotal - totalDiscount;
    }
    
    private decimal GetCustomerDiscountPercentage(Customer customer)
    {
        return customer.Status switch
        {
            CustomerStatus.VIP => 15m,
            CustomerStatus.Premium => 10m,
            CustomerStatus.Regular => 5m,
            _ => 0m
        };
    }
    
    private decimal CalculateBulkDiscount(int itemCount)
    {
        return itemCount switch
        {
            >= 20 => 10m,
            >= 10 => 5m,
            _ => 0m
        };
    }
}

public class OrderValidationService : IDomainService
{
    public ValidationResult ValidateOrder(Order order, Customer customer)
    {
        var errors = new List<string>();
        
        // Check customer status
        if (customer.Status == CustomerStatus.Suspended)
            errors.Add("Customer account is suspended");
            
        // Check order limits
        if (order.Total.Amount > customer.CreditLimit)
            errors.Add("Order total exceeds customer credit limit");
            
        // Check product availability
        foreach (var item in order.Items)
        {
            if (!IsProductAvailable(item.ProductId, item.Quantity))
                errors.Add($"Product {item.ProductId} is not available in requested quantity");
        }
        
        return new ValidationResult(errors);
    }
    
    private bool IsProductAvailable(ProductId productId, Quantity quantity)
    {
        // Implementation would check inventory
        return true; // Simplified for example
    }
}

public class ValidationResult
{
    public bool IsValid => !Errors.Any();
    public List<string> Errors { get; }
    
    public ValidationResult(List<string> errors)
    {
        Errors = errors ?? new List<string>();
    }
}
```

**Key Characteristics:**

| Building Block | Identity | Mutability | Lifecycle | Responsibility |
|----------------|----------|------------|-----------|----------------|
| **Entity** | Has identity | Mutable | Long-lived | Business logic with identity |
| **Value Object** | No identity | Immutable | Short-lived | Encapsulate values |
| **Aggregate** | Has identity | Mutable | Long-lived | Consistency boundary |
| **Domain Service** | No identity | Stateless | Per operation | Cross-cutting business logic |

**Best Practices:**

1. **Entities**: Focus on identity and business rules
2. **Value Objects**: Make them immutable and comparable
3. **Aggregates**: Keep them small and focused
4. **Domain Services**: Use sparingly, prefer methods on entities
5. **Consistency**: Maintain invariants within aggregates
6. **Encapsulation**: Hide internal state and expose behavior

These building blocks work together to create a rich, expressive domain model that accurately represents business concepts and rules.

---

### 11.4. What is the difference between Entities and Value Objects in DDD?

**Answer:**

Entities and Value Objects are fundamental building blocks in Domain-Driven Design, but they serve different purposes and have distinct characteristics. Understanding their differences is crucial for creating effective domain models.

**Key Differences:**

| Aspect | Entity | Value Object |
|--------|--------|--------------|
| **Identity** | Has unique identity | No identity, defined by attributes |
| **Equality** | Compared by identity | Compared by value |
| **Mutability** | Mutable | Immutable |
| **Lifecycle** | Long-lived, persists over time | Short-lived, can be recreated |
| **Tracking** | Tracked by ID | Not tracked individually |

**1. Entities - Identity Matters**

Entities are objects with a distinct identity that persists over time. Their identity is more important than their attributes.

```csharp
public class Customer : Entity<CustomerId>
{
    public CustomerId Id { get; private set; }
    public string Name { get; private set; }
    public string Email { get; private set; }
    public DateTime CreatedAt { get; private set; }
    
    public Customer(CustomerId id, string name, string email)
    {
        Id = id ?? throw new ArgumentNullException(nameof(id));
        Name = name ?? throw new ArgumentNullException(nameof(name));
        Email = email ?? throw new ArgumentNullException(nameof(email));
        CreatedAt = DateTime.UtcNow;
    }
    
    public void UpdateEmail(string newEmail)
    {
        Email = newEmail ?? throw new ArgumentNullException(nameof(newEmail));
    }
    
    public void ChangeName(string newName)
    {
        Name = newName ?? throw new ArgumentNullException(nameof(newName));
    }
    
    // Identity-based equality
    public override bool Equals(object obj)
    {
        if (obj is not Customer other) return false;
        return Id.Equals(other.Id);
    }
    
    public override int GetHashCode() => Id.GetHashCode();
}

// Usage
var customer1 = new Customer(new CustomerId(1), "John Doe", "john@example.com");
var customer2 = new Customer(new CustomerId(1), "Jane Smith", "jane@example.com");

// These are considered the same entity (same ID)
Console.WriteLine(customer1.Equals(customer2)); // True
Console.WriteLine(customer1 == customer2); // True (if operator overloaded)
```

**2. Value Objects - Value Matters**

Value objects are defined by their attributes rather than identity. They are immutable and compared by value.

```csharp
public class Money : ValueObject
{
    public decimal Amount { get; }
    public string Currency { get; }
    
    public Money(decimal amount, string currency)
    {
        if (amount < 0) throw new ArgumentException("Amount cannot be negative");
        if (string.IsNullOrWhiteSpace(currency)) 
            throw new ArgumentException("Currency is required");
            
        Amount = amount;
        Currency = currency.ToUpperInvariant();
    }
    
    // Value-based equality
    protected override IEnumerable<object> GetEqualityComponents()
    {
        yield return Amount;
        yield return Currency;
    }
    
    public static Money operator +(Money left, Money right)
    {
        if (left.Currency != right.Currency)
            throw new InvalidOperationException("Cannot add different currencies");
            
        return new Money(left.Amount + right.Amount, left.Currency);
    }
    
    public static Money operator *(Money money, decimal multiplier)
    {
        return new Money(money.Amount * multiplier, money.Currency);
    }
}

public class Address : ValueObject
{
    public string Street { get; }
    public string City { get; }
    public string State { get; }
    public string ZipCode { get; }
    public string Country { get; }
    
    public Address(string street, string city, string state, string zipCode, string country)
    {
        Street = street ?? throw new ArgumentNullException(nameof(street));
        City = city ?? throw new ArgumentNullException(nameof(city));
        State = state ?? throw new ArgumentNullException(nameof(state));
        ZipCode = zipCode ?? throw new ArgumentNullException(nameof(zipCode));
        Country = country ?? throw new ArgumentNullException(nameof(country));
    }
    
    protected override IEnumerable<object> GetEqualityComponents()
    {
        yield return Street;
        yield return City;
        yield return State;
        yield return ZipCode;
        yield return Country;
    }
}

// Usage
var money1 = new Money(100, "USD");
var money2 = new Money(100, "USD");
var money3 = new Money(100, "EUR");

Console.WriteLine(money1.Equals(money2)); // True - same value
Console.WriteLine(money1.Equals(money3)); // False - different currency

// Value objects can be recreated
var newMoney = new Money(200, "USD"); // Creates new instance
```

**3. Practical Examples**

**Entity Example - Order:**

```csharp
public class Order : Entity<OrderId>
{
    public OrderId Id { get; private set; }
    public CustomerId CustomerId { get; private set; }
    public Money Total { get; private set; }
    public OrderStatus Status { get; private set; }
    public Address ShippingAddress { get; private set; } // Value Object
    
    private readonly List<OrderItem> _items = new();
    public IReadOnlyList<OrderItem> Items => _items.AsReadOnly();
    
    public Order(OrderId id, CustomerId customerId, Address shippingAddress)
    {
        Id = id;
        CustomerId = customerId;
        ShippingAddress = shippingAddress; // Value Object
        Status = OrderStatus.Draft;
        Total = new Money(0, "USD");
    }
    
    public void AddItem(ProductId productId, Quantity quantity, Money unitPrice)
    {
        // Business logic for adding items
        var item = new OrderItem(productId, quantity, unitPrice);
        _items.Add(item);
        RecalculateTotal();
    }
    
    public void UpdateShippingAddress(Address newAddress)
    {
        // Can replace the entire value object
        ShippingAddress = newAddress;
    }
    
    private void RecalculateTotal()
    {
        Total = _items.Aggregate(new Money(0, "USD"), (sum, item) => sum + item.Total);
    }
}
```

**Value Object Example - OrderItem:**

```csharp
public class OrderItem : ValueObject
{
    public ProductId ProductId { get; }
    public Quantity Quantity { get; }
    public Money UnitPrice { get; }
    public Money Total => UnitPrice * Quantity.Value;
    
    public OrderItem(ProductId productId, Quantity quantity, Money unitPrice)
    {
        ProductId = productId ?? throw new ArgumentNullException(nameof(productId));
        Quantity = quantity ?? throw new ArgumentNullException(nameof(quantity));
        UnitPrice = unitPrice ?? throw new ArgumentNullException(nameof(unitPrice));
    }
    
    protected override IEnumerable<object> GetEqualityComponents()
    {
        yield return ProductId;
        yield return Quantity;
        yield return UnitPrice;
    }
    
    public OrderItem WithIncreasedQuantity(Quantity additionalQuantity)
    {
        // Return new instance instead of mutating
        return new OrderItem(ProductId, new Quantity(Quantity.Value + additionalQuantity.Value), UnitPrice);
    }
}
```

**4. When to Use Each**

**Use Entities when:**
- The object has a distinct identity
- You need to track the object over time
- The object can change its attributes but remains the same
- You need to reference the object from other parts of the system

```csharp
// Customer is an entity - we track them by ID
public class Customer : Entity<CustomerId>
{
    public CustomerId Id { get; private set; }
    public string Name { get; private set; }
    public string Email { get; private set; }
    
    // Customer can change name/email but remains the same customer
    public void UpdateProfile(string newName, string newEmail)
    {
        Name = newName;
        Email = newEmail;
    }
}
```

**Use Value Objects when:**
- The object is defined by its attributes
- The object is immutable
- You don't need to track individual instances
- The object represents a concept or measurement

```csharp
// Money is a value object - defined by amount and currency
public class Money : ValueObject
{
    public decimal Amount { get; }
    public string Currency { get; }
    
    // Money is immutable - operations return new instances
    public Money Add(Money other)
    {
        if (Currency != other.Currency)
            throw new InvalidOperationException("Cannot add different currencies");
            
        return new Money(Amount + other.Amount, Currency);
    }
}
```

**5. Common Mistakes**

**❌ Wrong: Treating Value Objects as Entities**

```csharp
// BAD: Giving identity to something that should be a value object
public class Money : Entity<MoneyId>
{
    public MoneyId Id { get; set; } // Unnecessary identity
    public decimal Amount { get; set; }
    public string Currency { get; set; }
}
```

**❌ Wrong: Making Entities Mutable in Wrong Ways**

```csharp
// BAD: Exposing setters that break encapsulation
public class Customer : Entity<CustomerId>
{
    public CustomerId Id { get; set; } // Should be private set
    public string Name { get; set; }   // Should be private set
    public string Email { get; set; }  // Should be private set
}
```

**✅ Correct: Proper Separation**

```csharp
// GOOD: Entity with proper encapsulation
public class Customer : Entity<CustomerId>
{
    public CustomerId Id { get; private set; }
    public string Name { get; private set; }
    public string Email { get; private set; }
    
    public void UpdateEmail(string newEmail)
    {
        // Business logic for email validation
        if (string.IsNullOrWhiteSpace(newEmail))
            throw new ArgumentException("Email cannot be empty");
            
        Email = newEmail;
    }
}

// GOOD: Value object that's immutable
public class Money : ValueObject
{
    public decimal Amount { get; }
    public string Currency { get; }
    
    public Money(decimal amount, string currency)
    {
        Amount = amount;
        Currency = currency;
    }
    
    // Operations return new instances
    public Money Add(Money other) => new Money(Amount + other.Amount, Currency);
}
```

**Key Takeaways:**

1. **Entities** have identity and are mutable
2. **Value Objects** have no identity and are immutable
3. **Entities** are tracked by ID, **Value Objects** by value
4. **Entities** can change attributes, **Value Objects** are replaced
5. **Entities** are long-lived, **Value Objects** can be recreated
6. Use **Entities** for things that have identity, **Value Objects** for concepts and measurements

---

### 11.5. Explain the concept of Aggregates in DDD and how they maintain consistency.

**Answer:**

Aggregates are one of the most important tactical patterns in Domain-Driven Design. They define consistency boundaries and ensure that business rules are maintained within a cluster of related objects.

**What are Aggregates?**

An Aggregate is a cluster of related objects that are treated as a unit for the purpose of data changes. It has one Aggregate Root that serves as the entry point and controls access to all objects within the aggregate.

**Key Characteristics:**

1. **Consistency Boundary**: All business rules within an aggregate are enforced
2. **Single Entry Point**: Only the aggregate root can be referenced from outside
3. **Transactional Consistency**: Changes to an aggregate are atomic
4. **Invariant Enforcement**: Business rules are maintained within the aggregate

**Example: Order Aggregate**

```csharp
public class Order : AggregateRoot<OrderId>
{
    public OrderId Id { get; private set; }
    public CustomerId CustomerId { get; private set; }
    public OrderStatus Status { get; private set; }
    public Money Total { get; private set; }
    public DateTime CreatedAt { get; private set; }
    
    // Private collection - only accessible through aggregate root
    private readonly List<OrderItem> _items = new();
    public IReadOnlyList<OrderItem> Items => _items.AsReadOnly();
    
    public Order(OrderId id, CustomerId customerId) : base(id)
    {
        Id = id;
        CustomerId = customerId ?? throw new ArgumentNullException(nameof(customerId));
        Status = OrderStatus.Draft;
        Total = new Money(0, "USD");
        CreatedAt = DateTime.UtcNow;
    }
    
    // Business operations that maintain invariants
    public void AddItem(ProductId productId, Quantity quantity, Money unitPrice)
    {
        if (Status != OrderStatus.Draft)
            throw new InvalidOperationException("Cannot add items to a confirmed order");
            
        if (quantity.Value <= 0)
            throw new ArgumentException("Quantity must be positive");
            
        var existingItem = _items.FirstOrDefault(i => i.ProductId == productId);
        if (existingItem != null)
        {
            existingItem.IncreaseQuantity(quantity);
        }
        else
        {
            _items.Add(new OrderItem(productId, quantity, unitPrice));
        }
        
        RecalculateTotal();
    }
    
    public void RemoveItem(ProductId productId)
    {
        if (Status != OrderStatus.Draft)
            throw new InvalidOperationException("Cannot remove items from a confirmed order");
            
        var item = _items.FirstOrDefault(i => i.ProductId == productId);
        if (item != null)
        {
            _items.Remove(item);
            RecalculateTotal();
        }
    }
    
    public void Confirm()
    {
        if (Status != OrderStatus.Draft)
            throw new InvalidOperationException("Order is not in draft status");
            
        if (_items.Count == 0)
            throw new InvalidOperationException("Cannot confirm an empty order");
            
        // Business rule: Minimum order amount
        if (Total.Amount < 10)
            throw new InvalidOperationException("Minimum order amount is $10");
            
        Status = OrderStatus.Confirmed;
        AddDomainEvent(new OrderConfirmedEvent(Id, CustomerId, Total));
    }
    
    public void Cancel()
    {
        if (Status == OrderStatus.Shipped)
            throw new InvalidOperationException("Cannot cancel a shipped order");
            
        Status = OrderStatus.Cancelled;
        AddDomainEvent(new OrderCancelledEvent(Id, CustomerId));
    }
    
    public void Ship()
    {
        if (Status != OrderStatus.Confirmed)
            throw new InvalidOperationException("Only confirmed orders can be shipped");
            
        Status = OrderStatus.Shipped;
        AddDomainEvent(new OrderShippedEvent(Id, CustomerId));
    }
    
    // Private method to maintain consistency
    private void RecalculateTotal()
    {
        Total = _items.Aggregate(new Money(0, "USD"), (sum, item) => sum + item.Total);
    }
}

// OrderItem is part of the Order aggregate
public class OrderItem : Entity<OrderItemId>
{
    public ProductId ProductId { get; private set; }
    public Quantity Quantity { get; private set; }
    public Money UnitPrice { get; private set; }
    public Money Total => UnitPrice * Quantity.Value;
    
    public OrderItem(ProductId productId, Quantity quantity, Money unitPrice) 
        : base(new OrderItemId(Guid.NewGuid()))
    {
        ProductId = productId ?? throw new ArgumentNullException(nameof(productId));
        Quantity = quantity ?? throw new ArgumentNullException(nameof(quantity));
        UnitPrice = unitPrice ?? throw new ArgumentNullException(nameof(unitPrice));
    }
    
    public void IncreaseQuantity(Quantity additionalQuantity)
    {
        if (additionalQuantity.Value <= 0)
            throw new ArgumentException("Additional quantity must be positive");
            
        Quantity = new Quantity(Quantity.Value + additionalQuantity.Value);
    }
    
    public void UpdateQuantity(Quantity newQuantity)
    {
        if (newQuantity.Value <= 0)
            throw new ArgumentException("Quantity must be positive");
            
        Quantity = newQuantity;
    }
}
```

**Consistency Rules and Invariants:**

```csharp
public class Order : AggregateRoot<OrderId>
{
    // Invariant: Order total must always equal sum of item totals
    private void RecalculateTotal()
    {
        Total = _items.Aggregate(new Money(0, "USD"), (sum, item) => sum + item.Total);
    }
    
    // Invariant: Cannot add items to confirmed orders
    public void AddItem(ProductId productId, Quantity quantity, Money unitPrice)
    {
        if (Status != OrderStatus.Draft)
            throw new InvalidOperationException("Cannot add items to a confirmed order");
        // ... rest of implementation
    }
    
    // Invariant: Cannot confirm empty orders
    public void Confirm()
    {
        if (_items.Count == 0)
            throw new InvalidOperationException("Cannot confirm an empty order");
        // ... rest of implementation
    }
    
    // Invariant: Order total must be positive
    private void ValidateTotal()
    {
        if (Total.Amount < 0)
            throw new InvalidOperationException("Order total cannot be negative");
    }
}
```

**Aggregate Boundaries:**

```csharp
// ✅ GOOD: Order and OrderItem are in the same aggregate
public class Order : AggregateRoot<OrderId>
{
    private readonly List<OrderItem> _items = new();
    // OrderItem is part of Order aggregate
}

// ❌ BAD: Order and Customer in the same aggregate
public class Order : AggregateRoot<OrderId>
{
    public Customer Customer { get; set; } // Customer should be separate aggregate
}

// ✅ GOOD: Order references Customer by ID
public class Order : AggregateRoot<OrderId>
{
    public CustomerId CustomerId { get; private set; } // Reference to another aggregate
}
```

**Repository Pattern with Aggregates:**

```csharp
public interface IOrderRepository
{
    Task<Order> GetByIdAsync(OrderId id);
    Task SaveAsync(Order order);
    Task DeleteAsync(OrderId id);
}

public class OrderRepository : IOrderRepository
{
    private readonly ApplicationDbContext _context;
    
    public async Task<Order> GetByIdAsync(OrderId id)
    {
        var orderEntity = await _context.Orders
            .Include(o => o.Items) // Load entire aggregate
            .FirstOrDefaultAsync(o => o.Id == id.Value);
            
        if (orderEntity == null)
            return null;
            
        return MapToDomain(orderEntity);
    }
    
    public async Task SaveAsync(Order order)
    {
        var orderEntity = MapToEntity(order);
        
        // Save entire aggregate as a unit
        if (_context.Entry(orderEntity).State == EntityState.Detached)
            _context.Orders.Add(orderEntity);
        else
            _context.Orders.Update(orderEntity);
            
        await _context.SaveChangesAsync();
    }
    
    private Order MapToDomain(OrderEntity entity)
    {
        var order = new Order(new OrderId(entity.Id), new CustomerId(entity.CustomerId));
        
        foreach (var itemEntity in entity.Items)
        {
            order.AddItem(
                new ProductId(itemEntity.ProductId),
                new Quantity(itemEntity.Quantity),
                new Money(itemEntity.UnitPrice, "USD")
            );
        }
        
        return order;
    }
}
```

**Domain Events in Aggregates:**

```csharp
public class Order : AggregateRoot<OrderId>
{
    public void Confirm()
    {
        if (Status != OrderStatus.Draft)
            throw new InvalidOperationException("Order is not in draft status");
            
        Status = OrderStatus.Confirmed;
        
        // Publish domain event
        AddDomainEvent(new OrderConfirmedEvent(Id, CustomerId, Total));
    }
    
    public void Cancel()
    {
        if (Status == OrderStatus.Shipped)
            throw new InvalidOperationException("Cannot cancel a shipped order");
            
        Status = OrderStatus.Cancelled;
        
        // Publish domain event
        AddDomainEvent(new OrderCancelledEvent(Id, CustomerId));
    }
}

// Domain event
public class OrderConfirmedEvent : DomainEvent
{
    public OrderId OrderId { get; }
    public CustomerId CustomerId { get; }
    public Money Total { get; }
    public DateTime ConfirmedAt { get; }
    
    public OrderConfirmedEvent(OrderId orderId, CustomerId customerId, Money total)
    {
        OrderId = orderId;
        CustomerId = customerId;
        Total = total;
        ConfirmedAt = DateTime.UtcNow;
    }
}
```

**Best Practices for Aggregates:**

1. **Keep Aggregates Small**: Small aggregates are easier to understand and maintain
2. **Single Responsibility**: Each aggregate should have one clear responsibility
3. **Consistency Boundaries**: Define clear boundaries for business rules
4. **Reference by ID**: Reference other aggregates by ID, not by object
5. **Eventual Consistency**: Use domain events for cross-aggregate communication

```csharp
// ✅ GOOD: Small, focused aggregate
public class Order : AggregateRoot<OrderId>
{
    // Only order-related business logic
    public void AddItem(ProductId productId, Quantity quantity, Money unitPrice) { }
    public void Confirm() { }
    public void Cancel() { }
}

// ❌ BAD: Large aggregate with too many responsibilities
public class Order : AggregateRoot<OrderId>
{
    public void AddItem(ProductId productId, Quantity quantity, Money unitPrice) { }
    public void Confirm() { }
    public void Cancel() { }
    public void ProcessPayment() { } // Should be separate aggregate
    public void UpdateInventory() { } // Should be separate aggregate
    public void SendNotification() { } // Should be separate aggregate
}
```

**Key Benefits:**

1. **Consistency**: Business rules are enforced within the aggregate
2. **Encapsulation**: Internal state is protected
3. **Performance**: Can load entire aggregate in one transaction
4. **Simplicity**: Clear boundaries make the system easier to understand
5. **Maintainability**: Changes to business rules are localized

Aggregates are essential for maintaining data consistency and enforcing business rules in complex domains. They provide a clear structure for organizing related objects and ensure that the system remains in a valid state at all times.

---

### 11.6. What are Domain Services and when should you use them?

**Answer:**

Domain Services are stateless services that contain business logic that doesn't naturally belong to entities or value objects. They represent operations that involve multiple domain objects or complex business rules that span across different aggregates.

**When to Use Domain Services:**

1. **Operations involving multiple aggregates**
2. **Complex business logic that doesn't fit in entities**
3. **Domain calculations that require external data**
4. **Business rules that span multiple domain objects**

**Example: Order Pricing Service**

```csharp
public interface IDomainService
{
}

public class OrderPricingService : IDomainService
{
    private readonly ICustomerRepository _customerRepository;
    private readonly IProductRepository _productRepository;
    
    public OrderPricingService(ICustomerRepository customerRepository, IProductRepository productRepository)
    {
        _customerRepository = customerRepository;
        _productRepository = productRepository;
    }
    
    public Money CalculateOrderTotal(Order order)
    {
        var baseTotal = order.Items.Sum(item => item.Total);
        var customer = _customerRepository.GetById(order.CustomerId);
        
        // Apply customer-specific discount
        var customerDiscount = CalculateCustomerDiscount(customer, baseTotal);
        
        // Apply bulk order discount
        var bulkDiscount = CalculateBulkDiscount(order.Items.Count(), baseTotal);
        
        // Apply seasonal discount
        var seasonalDiscount = CalculateSeasonalDiscount(baseTotal);
        
        var totalDiscount = customerDiscount + bulkDiscount + seasonalDiscount;
        return baseTotal - totalDiscount;
    }
    
    private Money CalculateCustomerDiscount(Customer customer, Money baseTotal)
    {
        var discountPercentage = customer.Status switch
        {
            CustomerStatus.VIP => 15m,
            CustomerStatus.Premium => 10m,
            CustomerStatus.Regular => 5m,
            _ => 0m
        };
        
        return baseTotal * (discountPercentage / 100);
    }
    
    private Money CalculateBulkDiscount(int itemCount, Money baseTotal)
    {
        var discountPercentage = itemCount switch
        {
            >= 20 => 10m,
            >= 10 => 5m,
            _ => 0m
        };
        
        return baseTotal * (discountPercentage / 100);
    }
    
    private Money CalculateSeasonalDiscount(Money baseTotal)
    {
        var currentMonth = DateTime.Now.Month;
        var isHolidaySeason = currentMonth == 12 || currentMonth == 1; // December or January
        
        return isHolidaySeason ? baseTotal * 0.05m : new Money(0, baseTotal.Currency);
    }
}
```

**Example: Order Validation Service**

```csharp
public class OrderValidationService : IDomainService
{
    private readonly IInventoryService _inventoryService;
    private readonly ICustomerService _customerService;
    
    public OrderValidationService(IInventoryService inventoryService, ICustomerService customerService)
    {
        _inventoryService = inventoryService;
        _customerService = customerService;
    }
    
    public ValidationResult ValidateOrder(Order order)
    {
        var errors = new List<string>();
        
        // Validate customer
        var customerValidation = ValidateCustomer(order.CustomerId);
        errors.AddRange(customerValidation.Errors);
        
        // Validate inventory
        var inventoryValidation = ValidateInventory(order.Items);
        errors.AddRange(inventoryValidation.Errors);
        
        // Validate business rules
        var businessRuleValidation = ValidateBusinessRules(order);
        errors.AddRange(businessRuleValidation.Errors);
        
        return new ValidationResult(errors);
    }
    
    private ValidationResult ValidateCustomer(CustomerId customerId)
    {
        var customer = _customerService.GetCustomer(customerId);
        var errors = new List<string>();
        
        if (customer == null)
            errors.Add("Customer not found");
        else if (customer.Status == CustomerStatus.Suspended)
            errors.Add("Customer account is suspended");
        else if (customer.Status == CustomerStatus.Closed)
            errors.Add("Customer account is closed");
            
        return new ValidationResult(errors);
    }
    
    private ValidationResult ValidateInventory(IEnumerable<OrderItem> items)
    {
        var errors = new List<string>();
        
        foreach (var item in items)
        {
            var availableQuantity = _inventoryService.GetAvailableQuantity(item.ProductId);
            if (availableQuantity < item.Quantity.Value)
            {
                errors.Add($"Insufficient inventory for product {item.ProductId}. Available: {availableQuantity}, Requested: {item.Quantity.Value}");
            }
        }
        
        return new ValidationResult(errors);
    }
    
    private ValidationResult ValidateBusinessRules(Order order)
    {
        var errors = new List<string>();
        
        // Business rule: Minimum order amount
        if (order.Total.Amount < 10)
            errors.Add("Minimum order amount is $10");
            
        // Business rule: Maximum items per order
        if (order.Items.Count() > 50)
            errors.Add("Maximum 50 items per order");
            
        // Business rule: No orders on weekends for certain products
        if (IsWeekend() && HasRestrictedProducts(order.Items))
            errors.Add("Orders with restricted products cannot be placed on weekends");
            
        return new ValidationResult(errors);
    }
    
    private bool IsWeekend()
    {
        var dayOfWeek = DateTime.Now.DayOfWeek;
        return dayOfWeek == DayOfWeek.Saturday || dayOfWeek == DayOfWeek.Sunday;
    }
    
    private bool HasRestrictedProducts(IEnumerable<OrderItem> items)
    {
        var restrictedProductIds = new[] { "ALCOHOL", "TOBACCO" };
        return items.Any(item => restrictedProductIds.Contains(item.ProductId.Value));
    }
}

public class ValidationResult
{
    public bool IsValid => !Errors.Any();
    public List<string> Errors { get; }
    
    public ValidationResult(List<string> errors)
    {
        Errors = errors ?? new List<string>();
    }
}
```

**Example: Shipping Cost Calculation Service**

```csharp
public class ShippingCostCalculationService : IDomainService
{
    private readonly IShippingRateRepository _shippingRateRepository;
    private readonly IAddressValidationService _addressValidationService;
    
    public ShippingCostCalculationService(
        IShippingRateRepository shippingRateRepository,
        IAddressValidationService addressValidationService)
    {
        _shippingRateRepository = shippingRateRepository;
        _addressValidationService = addressValidationService;
    }
    
    public Money CalculateShippingCost(Order order, Address shippingAddress)
    {
        // Validate address
        if (!_addressValidationService.IsValidAddress(shippingAddress))
            throw new InvalidOperationException("Invalid shipping address");
        
        // Get shipping rates
        var shippingRates = _shippingRateRepository.GetRatesForAddress(shippingAddress);
        
        // Calculate package weight and dimensions
        var packageInfo = CalculatePackageInfo(order.Items);
        
        // Find best shipping option
        var bestRate = FindBestShippingRate(shippingRates, packageInfo);
        
        return bestRate.Cost;
    }
    
    private PackageInfo CalculatePackageInfo(IEnumerable<OrderItem> items)
    {
        var totalWeight = items.Sum(item => item.Product.Weight * item.Quantity.Value);
        var totalVolume = items.Sum(item => item.Product.Volume * item.Quantity.Value);
        
        return new PackageInfo(totalWeight, totalVolume);
    }
    
    private ShippingRate FindBestShippingRate(IEnumerable<ShippingRate> rates, PackageInfo packageInfo)
    {
        var applicableRates = rates.Where(rate => 
            rate.MaxWeight >= packageInfo.Weight && 
            rate.MaxVolume >= packageInfo.Volume);
            
        return applicableRates.OrderBy(rate => rate.Cost.Amount).First();
    }
}

public class PackageInfo
{
    public decimal Weight { get; }
    public decimal Volume { get; }
    
    public PackageInfo(decimal weight, decimal volume)
    {
        Weight = weight;
        Volume = volume;
    }
}
```

**Domain Service vs Application Service:**

```csharp
// Domain Service - contains business logic
public class OrderPricingService : IDomainService
{
    public Money CalculateOrderTotal(Order order)
    {
        // Pure business logic
        var baseTotal = order.Items.Sum(item => item.Total);
        var discount = CalculateDiscount(order);
        return baseTotal - discount;
    }
    
    private Money CalculateDiscount(Order order)
    {
        // Complex business rules for discount calculation
        // This is domain logic, not application logic
    }
}

// Application Service - orchestrates domain operations
public class OrderApplicationService
{
    private readonly IOrderRepository _orderRepository;
    private readonly OrderPricingService _pricingService;
    private readonly IUnitOfWork _unitOfWork;
    
    public async Task<OrderId> CreateOrderAsync(CreateOrderCommand command)
    {
        // Application logic - orchestration
        var order = new Order(command.CustomerId);
        
        foreach (var item in command.Items)
        {
            order.AddItem(item.ProductId, item.Quantity, item.UnitPrice);
        }
        
        // Use domain service for business logic
        var total = _pricingService.CalculateOrderTotal(order);
        order.SetTotal(total);
        
        await _orderRepository.SaveAsync(order);
        await _unitOfWork.CommitAsync();
        
        return order.Id;
    }
}
```

**Best Practices for Domain Services:**

1. **Keep them stateless**: Domain services should not maintain state
2. **Use sparingly**: Prefer methods on entities when possible
3. **Single responsibility**: Each service should have one clear purpose
4. **Pure business logic**: Don't mix infrastructure concerns
5. **Testable**: Should be easy to unit test

```csharp
// ✅ Good: Stateless domain service
public class TaxCalculationService : IDomainService
{
    public Money CalculateTax(Order order, Address shippingAddress)
    {
        // Pure business logic for tax calculation
        var taxRate = GetTaxRateForAddress(shippingAddress);
        return order.Total * taxRate;
    }
    
    private decimal GetTaxRateForAddress(Address address)
    {
        // Business logic for determining tax rate
        return address.State switch
        {
            "CA" => 0.0875m,
            "NY" => 0.08m,
            "TX" => 0.0625m,
            _ => 0.05m
        };
    }
}

// ❌ Bad: Domain service with infrastructure concerns
public class BadTaxCalculationService : IDomainService
{
    private readonly HttpClient _httpClient; // Infrastructure concern
    
    public async Task<Money> CalculateTaxAsync(Order order, Address address)
    {
        // This mixes domain logic with infrastructure
        var response = await _httpClient.GetAsync($"https://tax-api.com/rate/{address.State}");
        var taxRate = await response.Content.ReadAsStringAsync();
        return order.Total * decimal.Parse(taxRate);
    }
}
```

**When NOT to Use Domain Services:**

1. **Simple operations**: Use entity methods instead
2. **Infrastructure concerns**: Use application services
3. **Cross-cutting concerns**: Use application services or middleware
4. **Data access**: Use repositories

```csharp
// ❌ Don't use domain service for simple operations
public class BadOrderService : IDomainService
{
    public void UpdateOrderStatus(Order order, OrderStatus status)
    {
        order.UpdateStatus(status); // This should be a method on Order entity
    }
}

// ✅ Use entity method instead
public class Order : AggregateRoot<OrderId>
{
    public void UpdateStatus(OrderStatus status)
    {
        // Business logic for status update
        if (Status == OrderStatus.Shipped && status == OrderStatus.Draft)
            throw new InvalidOperationException("Cannot revert shipped order to draft");
            
        Status = status;
    }
}
```

**Key Takeaways:**

1. **Domain Services** contain business logic that doesn't belong to entities or value objects
2. **Use them sparingly** - prefer entity methods when possible
3. **Keep them stateless** and focused on business logic
4. **Don't mix infrastructure concerns** - keep them pure
5. **Test them thoroughly** as they contain important business rules

---

### 11.7. What are Domain Events and how do you implement them in .NET?

**Answer:**

Domain Events are a way to capture something important that happened in the domain. They represent business events that other parts of the system might be interested in, enabling loose coupling between different parts of the domain.

**Key Characteristics:**

1. **Business Meaning**: Represent something important that happened
2. **Immutable**: Once created, they cannot be changed
3. **Past Tense**: Named as things that have already happened
4. **Rich Information**: Contain all necessary data for event handlers

**Basic Domain Event Implementation:**

```csharp
public abstract class DomainEvent
{
    public Guid Id { get; }
    public DateTime OccurredOn { get; }
    public string EventType { get; }
    
    protected DomainEvent()
    {
        Id = Guid.NewGuid();
        OccurredOn = DateTime.UtcNow;
        EventType = GetType().Name;
    }
}

// Example domain events
public class OrderConfirmedEvent : DomainEvent
{
    public OrderId OrderId { get; }
    public CustomerId CustomerId { get; }
    public Money Total { get; }
    public List<OrderItem> Items { get; }
    
    public OrderConfirmedEvent(OrderId orderId, CustomerId customerId, Money total, List<OrderItem> items)
    {
        OrderId = orderId;
        CustomerId = customerId;
        Total = total;
        Items = items;
    }
}

public class OrderCancelledEvent : DomainEvent
{
    public OrderId OrderId { get; }
    public CustomerId CustomerId { get; }
    public string Reason { get; }
    
    public OrderCancelledEvent(OrderId orderId, CustomerId customerId, string reason)
    {
        OrderId = orderId;
        CustomerId = customerId;
        Reason = reason;
    }
}

public class PaymentProcessedEvent : DomainEvent
{
    public PaymentId PaymentId { get; }
    public OrderId OrderId { get; }
    public Money Amount { get; }
    public PaymentStatus Status { get; }
    
    public PaymentProcessedEvent(PaymentId paymentId, OrderId orderId, Money amount, PaymentStatus status)
    {
        PaymentId = paymentId;
        OrderId = orderId;
        Amount = amount;
        Status = status;
    }
}
```

**Domain Event Handler Interface:**

```csharp
public interface IDomainEventHandler<in TDomainEvent> where TDomainEvent : DomainEvent
{
    Task Handle(TDomainEvent domainEvent, CancellationToken cancellationToken = default);
}

// Generic handler interface
public interface IDomainEventHandler
{
    Task Handle(DomainEvent domainEvent, CancellationToken cancellationToken = default);
    bool CanHandle(DomainEvent domainEvent);
}
```

**Event Handler Implementations:**

```csharp
public class OrderConfirmedEventHandler : IDomainEventHandler<OrderConfirmedEvent>
{
    private readonly IEmailService _emailService;
    private readonly IInventoryService _inventoryService;
    private readonly ILogger<OrderConfirmedEventHandler> _logger;
    
    public OrderConfirmedEventHandler(
        IEmailService emailService,
        IInventoryService inventoryService,
        ILogger<OrderConfirmedEventHandler> logger)
    {
        _emailService = emailService;
        _inventoryService = inventoryService;
        _logger = logger;
    }
    
    public async Task Handle(OrderConfirmedEvent domainEvent, CancellationToken cancellationToken = default)
    {
        _logger.LogInformation("Processing order confirmation for order {OrderId}", domainEvent.OrderId);
        
        try
        {
            // Send confirmation email
            await _emailService.SendOrderConfirmationAsync(
                domainEvent.CustomerId, 
                domainEvent.OrderId, 
                domainEvent.Total);
            
            // Reserve inventory
            foreach (var item in domainEvent.Items)
            {
                await _inventoryService.ReserveInventoryAsync(
                    item.ProductId, 
                    item.Quantity);
            }
            
            _logger.LogInformation("Successfully processed order confirmation for order {OrderId}", domainEvent.OrderId);
        }
        catch (Exception ex)
        {
            _logger.LogError(ex, "Failed to process order confirmation for order {OrderId}", domainEvent.OrderId);
            throw;
        }
    }
}

public class OrderCancelledEventHandler : IDomainEventHandler<OrderCancelledEvent>
{
    private readonly IEmailService _emailService;
    private readonly IInventoryService _inventoryService;
    private readonly IPaymentService _paymentService;
    
    public async Task Handle(OrderCancelledEvent domainEvent, CancellationToken cancellationToken = default)
    {
        // Send cancellation email
        await _emailService.SendOrderCancellationAsync(
            domainEvent.CustomerId, 
            domainEvent.OrderId, 
            domainEvent.Reason);
        
        // Release reserved inventory
        // Note: This would need to get the order items from somewhere
        // In a real implementation, you might include them in the event
        
        // Process refund if payment was made
        await _paymentService.ProcessRefundAsync(domainEvent.OrderId);
    }
}

public class PaymentProcessedEventHandler : IDomainEventHandler<PaymentProcessedEvent>
{
    private readonly IOrderRepository _orderRepository;
    private readonly IShippingService _shippingService;
    
    public async Task Handle(PaymentProcessedEvent domainEvent, CancellationToken cancellationToken = default)
    {
        if (domainEvent.Status == PaymentStatus.Successful)
        {
            // Update order status
            var order = await _orderRepository.GetByIdAsync(domainEvent.OrderId);
            order.MarkAsPaid();
            await _orderRepository.SaveAsync(order);
            
            // Initiate shipping
            await _shippingService.CreateShipmentAsync(domainEvent.OrderId);
        }
        else
        {
            // Handle failed payment
            var order = await _orderRepository.GetByIdAsync(domainEvent.OrderId);
            order.MarkPaymentFailed();
            await _orderRepository.SaveAsync(order);
        }
    }
}
```

**Domain Event Dispatcher:**

```csharp
public interface IDomainEventDispatcher
{
    Task DispatchAsync(DomainEvent domainEvent, CancellationToken cancellationToken = default);
    Task DispatchAsync(IEnumerable<DomainEvent> domainEvents, CancellationToken cancellationToken = default);
}

public class DomainEventDispatcher : IDomainEventDispatcher
{
    private readonly IServiceProvider _serviceProvider;
    private readonly ILogger<DomainEventDispatcher> _logger;
    
    public DomainEventDispatcher(IServiceProvider serviceProvider, ILogger<DomainEventDispatcher> logger)
    {
        _serviceProvider = serviceProvider;
        _logger = logger;
    }
    
    public async Task DispatchAsync(DomainEvent domainEvent, CancellationToken cancellationToken = default)
    {
        _logger.LogInformation("Dispatching domain event {EventType} with ID {EventId}", 
            domainEvent.EventType, domainEvent.Id);
        
        var handlerType = typeof(IDomainEventHandler<>).MakeGenericType(domainEvent.GetType());
        var handlers = _serviceProvider.GetServices(handlerType);
        
        var tasks = handlers.Select(handler => 
        {
            var handleMethod = handler.GetType().GetMethod("Handle");
            var task = (Task)handleMethod.Invoke(handler, new object[] { domainEvent, cancellationToken });
            return task;
        });
        
        await Task.WhenAll(tasks);
        
        _logger.LogInformation("Successfully dispatched domain event {EventType} with ID {EventId}", 
            domainEvent.EventType, domainEvent.Id);
    }
    
    public async Task DispatchAsync(IEnumerable<DomainEvent> domainEvents, CancellationToken cancellationToken = default)
    {
        var tasks = domainEvents.Select(domainEvent => DispatchAsync(domainEvent, cancellationToken));
        await Task.WhenAll(tasks);
    }
}
```

**Integration with Aggregates:**

```csharp
public abstract class AggregateRoot<TId> : Entity<TId> where TId : ValueObject
{
    private readonly List<DomainEvent> _domainEvents = new();
    
    public IReadOnlyList<DomainEvent> DomainEvents => _domainEvents.AsReadOnly();
    
    protected void AddDomainEvent(DomainEvent domainEvent)
    {
        _domainEvents.Add(domainEvent);
    }
    
    public void ClearDomainEvents()
    {
        _domainEvents.Clear();
    }
}

public class Order : AggregateRoot<OrderId>
{
    public void Confirm()
    {
        if (Status != OrderStatus.Draft)
            throw new InvalidOperationException("Order is not in draft status");
            
        if (_items.Count == 0)
            throw new InvalidOperationException("Cannot confirm an empty order");
            
        Status = OrderStatus.Confirmed;
        
        // Raise domain event
        AddDomainEvent(new OrderConfirmedEvent(Id, CustomerId, Total, _items.ToList()));
    }
    
    public void Cancel(string reason)
    {
        if (Status == OrderStatus.Shipped)
            throw new InvalidOperationException("Cannot cancel a shipped order");
            
        Status = OrderStatus.Cancelled;
        
        // Raise domain event
        AddDomainEvent(new OrderCancelledEvent(Id, CustomerId, reason));
    }
}
```

**Event Publishing in Application Layer:**

```csharp
public class OrderApplicationService
{
    private readonly IOrderRepository _orderRepository;
    private readonly IDomainEventDispatcher _eventDispatcher;
    private readonly IUnitOfWork _unitOfWork;
    
    public async Task<OrderId> ConfirmOrderAsync(OrderId orderId)
    {
        var order = await _orderRepository.GetByIdAsync(orderId);
        if (order == null)
            throw new OrderNotFoundException(orderId);
            
        order.Confirm();
        
        await _orderRepository.SaveAsync(order);
        await _unitOfWork.CommitAsync();
        
        // Dispatch domain events after successful save
        await _eventDispatcher.DispatchAsync(order.DomainEvents);
        order.ClearDomainEvents();
        
        return order.Id;
    }
}
```

**Event Store Implementation:**

```csharp
public interface IEventStore
{
    Task SaveEventsAsync(Guid aggregateId, IEnumerable<DomainEvent> events, int expectedVersion);
    Task<IEnumerable<DomainEvent>> GetEventsAsync(Guid aggregateId);
    Task<IEnumerable<DomainEvent>> GetEventsAsync(Guid aggregateId, int fromVersion);
}

public class EventStore : IEventStore
{
    private readonly ApplicationDbContext _context;
    
    public async Task SaveEventsAsync(Guid aggregateId, IEnumerable<DomainEvent> events, int expectedVersion)
    {
        var eventEntities = events.Select((domainEvent, index) => new DomainEventEntity
        {
            Id = domainEvent.Id,
            AggregateId = aggregateId,
            EventType = domainEvent.EventType,
            EventData = JsonSerializer.Serialize(domainEvent),
            Version = expectedVersion + index + 1,
            OccurredOn = domainEvent.OccurredOn
        });
        
        _context.DomainEvents.AddRange(eventEntities);
        await _context.SaveChangesAsync();
    }
    
    public async Task<IEnumerable<DomainEvent>> GetEventsAsync(Guid aggregateId)
    {
        var eventEntities = await _context.DomainEvents
            .Where(e => e.AggregateId == aggregateId)
            .OrderBy(e => e.Version)
            .ToListAsync();
            
        return eventEntities.Select(DeserializeEvent);
    }
    
    private DomainEvent DeserializeEvent(DomainEventEntity eventEntity)
    {
        var eventType = Type.GetType(eventEntity.EventType);
        return (DomainEvent)JsonSerializer.Deserialize(eventEntity.EventData, eventType);
    }
}

public class DomainEventEntity
{
    public Guid Id { get; set; }
    public Guid AggregateId { get; set; }
    public string EventType { get; set; }
    public string EventData { get; set; }
    public int Version { get; set; }
    public DateTime OccurredOn { get; set; }
}
```

**Best Practices:**

1. **Immutable Events**: Domain events should be immutable
2. **Rich Information**: Include all necessary data for event handlers
3. **Past Tense Naming**: Use past tense for event names
4. **Single Responsibility**: Each event should represent one business occurrence
5. **Async Handling**: Use async/await for event handlers
6. **Error Handling**: Implement proper error handling in event handlers
7. **Idempotency**: Make event handlers idempotent when possible

**Benefits:**

1. **Loose Coupling**: Reduces coupling between different parts of the system
2. **Extensibility**: Easy to add new event handlers without changing existing code
3. **Audit Trail**: Provides a complete history of domain events
4. **Integration**: Enables integration between different bounded contexts
5. **Testing**: Makes it easier to test business logic in isolation

Domain Events are a powerful pattern for creating loosely coupled, extensible systems that can evolve over time while maintaining business integrity.

---

### 11.8. What is the difference between Domain Models and Data Transfer Objects (DTOs)?

**Answer:**

Domain Models and Data Transfer Objects (DTOs) serve different purposes in a software system. Understanding their differences is crucial for maintaining clean architecture and proper separation of concerns.

**Key Differences:**

| Aspect | Domain Models | DTOs |
|--------|---------------|------|
| **Purpose** | Represent business concepts and rules | Transfer data between layers |
| **Business Logic** | Contains business logic and rules | No business logic |
| **Validation** | Domain validation and invariants | Data format validation |
| **Lifecycle** | Long-lived, persistent | Short-lived, transient |
| **Coupling** | Tightly coupled to business domain | Loosely coupled, generic |
| **Immutability** | Can be mutable (entities) or immutable (value objects) | Usually immutable |

**Domain Models:**

Domain models represent business concepts and contain business logic. They are the heart of the domain-driven design.

```csharp
// Domain Model - Order Entity
public class Order : AggregateRoot<OrderId>
{
    public OrderId Id { get; private set; }
    public CustomerId CustomerId { get; private set; }
    public OrderStatus Status { get; private set; }
    public Money Total { get; private set; }
    public DateTime CreatedAt { get; private set; }
    
    private readonly List<OrderItem> _items = new();
    public IReadOnlyList<OrderItem> Items => _items.AsReadOnly();
    
    public Order(OrderId id, CustomerId customerId)
    {
        Id = id;
        CustomerId = customerId;
        Status = OrderStatus.Draft;
        Total = new Money(0, "USD");
        CreatedAt = DateTime.UtcNow;
    }
    
    // Business logic
    public void AddItem(ProductId productId, Quantity quantity, Money unitPrice)
    {
        if (Status != OrderStatus.Draft)
            throw new InvalidOperationException("Cannot add items to a confirmed order");
            
        if (quantity.Value <= 0)
            throw new ArgumentException("Quantity must be positive");
            
        var existingItem = _items.FirstOrDefault(i => i.ProductId == productId);
        if (existingItem != null)
        {
            existingItem.IncreaseQuantity(quantity);
        }
        else
        {
            _items.Add(new OrderItem(productId, quantity, unitPrice));
        }
        
        RecalculateTotal();
    }
    
    public void Confirm()
    {
        if (Status != OrderStatus.Draft)
            throw new InvalidOperationException("Order is not in draft status");
            
        if (_items.Count == 0)
            throw new InvalidOperationException("Cannot confirm an empty order");
            
        // Business rule: Minimum order amount
        if (Total.Amount < 10)
            throw new InvalidOperationException("Minimum order amount is $10");
            
        Status = OrderStatus.Confirmed;
        AddDomainEvent(new OrderConfirmedEvent(Id, CustomerId, Total));
    }
    
    private void RecalculateTotal()
    {
        Total = _items.Aggregate(new Money(0, "USD"), (sum, item) => sum + item.Total);
    }
}

// Domain Model - Value Object
public class Money : ValueObject
{
    public decimal Amount { get; }
    public string Currency { get; }
    
    public Money(decimal amount, string currency)
    {
        if (amount < 0) throw new ArgumentException("Amount cannot be negative");
        if (string.IsNullOrWhiteSpace(currency)) 
            throw new ArgumentException("Currency is required");
            
        Amount = amount;
        Currency = currency.ToUpperInvariant();
    }
    
    protected override IEnumerable<object> GetEqualityComponents()
    {
        yield return Amount;
        yield return Currency;
    }
    
    public static Money operator +(Money left, Money right)
    {
        if (left.Currency != right.Currency)
            throw new InvalidOperationException("Cannot add different currencies");
            
        return new Money(left.Amount + right.Amount, left.Currency);
    }
}
```

**DTOs (Data Transfer Objects):**

DTOs are simple objects used to transfer data between different layers of the application.

```csharp
// DTO for creating an order
public class CreateOrderDto
{
    public int CustomerId { get; set; }
    public List<OrderItemDto> Items { get; set; }
}

public class OrderItemDto
{
    public int ProductId { get; set; }
    public int Quantity { get; set; }
    public decimal UnitPrice { get; set; }
}

// DTO for order response
public class OrderDto
{
    public int Id { get; set; }
    public int CustomerId { get; set; }
    public string Status { get; set; }
    public decimal Total { get; set; }
    public string Currency { get; set; }
    public DateTime CreatedAt { get; set; }
    public List<OrderItemDto> Items { get; set; }
}

// DTO for order summary
public class OrderSummaryDto
{
    public int Id { get; set; }
    public int CustomerId { get; set; }
    public string Status { get; set; }
    public decimal Total { get; set; }
    public DateTime CreatedAt { get; set; }
}
```

**Mapping Between Domain Models and DTOs:**

```csharp
public class OrderMapper
{
    public static OrderDto ToDto(Order order)
    {
        return new OrderDto
        {
            Id = order.Id.Value,
            CustomerId = order.CustomerId.Value,
            Status = order.Status.ToString(),
            Total = order.Total.Amount,
            Currency = order.Total.Currency,
            CreatedAt = order.CreatedAt,
            Items = order.Items.Select(ToItemDto).ToList()
        };
    }
    
    public static OrderItemDto ToItemDto(OrderItem item)
    {
        return new OrderItemDto
        {
            ProductId = item.ProductId.Value,
            Quantity = item.Quantity.Value,
            UnitPrice = item.UnitPrice.Amount
        };
    }
    
    public static Order ToDomain(CreateOrderDto dto)
    {
        var order = new Order(new OrderId(dto.CustomerId), new CustomerId(dto.CustomerId));
        
        foreach (var itemDto in dto.Items)
        {
            order.AddItem(
                new ProductId(itemDto.ProductId),
                new Quantity(itemDto.Quantity),
                new Money(itemDto.UnitPrice, "USD")
            );
        }
        
        return order;
    }
}
```

**Usage in Application Layer:**

```csharp
public class OrderApplicationService
{
    private readonly IOrderRepository _orderRepository;
    private readonly OrderMapper _mapper;
    
    public async Task<OrderDto> CreateOrderAsync(CreateOrderDto createOrderDto)
    {
        // Convert DTO to domain model
        var order = OrderMapper.ToDomain(createOrderDto);
        
        // Business logic is handled by the domain model
        order.Confirm();
        
        // Save domain model
        await _orderRepository.SaveAsync(order);
        
        // Convert back to DTO for response
        return OrderMapper.ToDto(order);
    }
    
    public async Task<OrderDto> GetOrderAsync(int orderId)
    {
        var order = await _orderRepository.GetByIdAsync(new OrderId(orderId));
        if (order == null)
            throw new OrderNotFoundException(orderId);
            
        return OrderMapper.ToDto(order);
    }
    
    public async Task<List<OrderSummaryDto>> GetOrderSummariesAsync(int customerId)
    {
        var orders = await _orderRepository.GetByCustomerIdAsync(new CustomerId(customerId));
        
        return orders.Select(order => new OrderSummaryDto
        {
            Id = order.Id.Value,
            CustomerId = order.CustomerId.Value,
            Status = order.Status.ToString(),
            Total = order.Total.Amount,
            CreatedAt = order.CreatedAt
        }).ToList();
    }
}
```

**API Controller Usage:**

```csharp
[ApiController]
[Route("api/[controller]")]
public class OrdersController : ControllerBase
{
    private readonly OrderApplicationService _orderService;
    
    [HttpPost]
    public async Task<ActionResult<OrderDto>> CreateOrder([FromBody] CreateOrderDto createOrderDto)
    {
        try
        {
            var order = await _orderService.CreateOrderAsync(createOrderDto);
            return CreatedAtAction(nameof(GetOrder), new { id = order.Id }, order);
        }
        catch (InvalidOperationException ex)
        {
            return BadRequest(ex.Message);
        }
    }
    
    [HttpGet("{id}")]
    public async Task<ActionResult<OrderDto>> GetOrder(int id)
    {
        try
        {
            var order = await _orderService.GetOrderAsync(id);
            return Ok(order);
        }
        catch (OrderNotFoundException)
        {
            return NotFound();
        }
    }
    
    [HttpGet("customer/{customerId}")]
    public async Task<ActionResult<List<OrderSummaryDto>>> GetCustomerOrders(int customerId)
    {
        var orders = await _orderService.GetOrderSummariesAsync(customerId);
        return Ok(orders);
    }
}
```

**Validation Differences:**

```csharp
// Domain Model Validation (Business Rules)
public class Order : AggregateRoot<OrderId>
{
    public void Confirm()
    {
        // Business rule validation
        if (Status != OrderStatus.Draft)
            throw new InvalidOperationException("Order is not in draft status");
            
        if (_items.Count == 0)
            throw new InvalidOperationException("Cannot confirm an empty order");
            
        if (Total.Amount < 10)
            throw new InvalidOperationException("Minimum order amount is $10");
            
        Status = OrderStatus.Confirmed;
    }
}

// DTO Validation (Data Format)
public class CreateOrderDto
{
    [Required]
    [Range(1, int.MaxValue, ErrorMessage = "Customer ID must be positive")]
    public int CustomerId { get; set; }
    
    [Required]
    [MinLength(1, ErrorMessage = "Order must have at least one item")]
    public List<OrderItemDto> Items { get; set; }
}

public class OrderItemDto
{
    [Required]
    [Range(1, int.MaxValue, ErrorMessage = "Product ID must be positive")]
    public int ProductId { get; set; }
    
    [Required]
    [Range(1, int.MaxValue, ErrorMessage = "Quantity must be positive")]
    public int Quantity { get; set; }
    
    [Required]
    [Range(0.01, double.MaxValue, ErrorMessage = "Unit price must be positive")]
    public decimal UnitPrice { get; set; }
}
```

**When to Use Each:**

**Use Domain Models when:**
- Representing business concepts
- Implementing business logic and rules
- Maintaining business invariants
- Modeling the core domain

**Use DTOs when:**
- Transferring data between layers
- Exposing data through APIs
- Serializing/deserializing data
- Reducing coupling between layers

**Common Mistakes:**

```csharp
// ❌ BAD: DTO with business logic
public class OrderDto
{
    public int Id { get; set; }
    public string Status { get; set; }
    public decimal Total { get; set; }
    
    public void Confirm() // Business logic in DTO
    {
        if (Status != "Draft")
            throw new InvalidOperationException("Cannot confirm non-draft order");
        Status = "Confirmed";
    }
}

// ❌ BAD: Domain model used as DTO
public class Order : AggregateRoot<OrderId>
{
    public int Id { get; set; } // Should be OrderId
    public int CustomerId { get; set; } // Should be CustomerId
    public string Status { get; set; } // Should be OrderStatus enum
    public decimal Total { get; set; } // Should be Money value object
}

// ✅ GOOD: Proper separation
public class Order : AggregateRoot<OrderId>
{
    public OrderId Id { get; private set; }
    public CustomerId CustomerId { get; private set; }
    public OrderStatus Status { get; private set; }
    public Money Total { get; private set; }
    
    public void Confirm() { /* Business logic */ }
}

public class OrderDto
{
    public int Id { get; set; }
    public int CustomerId { get; set; }
    public string Status { get; set; }
    public decimal Total { get; set; }
    // No business logic
}
```

**Key Takeaways:**

1. **Domain Models** contain business logic and represent business concepts
2. **DTOs** are simple data containers for transferring data between layers
3. **Domain Models** are long-lived and persistent
4. **DTOs** are short-lived and transient
5. **Use mapping** to convert between domain models and DTOs
6. **Keep them separate** to maintain clean architecture
7. **Domain Models** enforce business rules, **DTOs** handle data format validation

---

### 11.9. How do you implement the CQRS (Command Query Responsibility Segregation) pattern?

**Answer:**

CQRS (Command Query Responsibility Segregation) is a pattern that separates read and write operations by using different models for commands (writes) and queries (reads). This allows each side to be optimized independently.

**Core Concepts:**

1. **Commands**: Operations that change state (writes)
2. **Queries**: Operations that read data (reads)
3. **Command Handlers**: Process commands and update the domain
4. **Query Handlers**: Process queries and return data
5. **Separate Models**: Different models for commands and queries

**Basic CQRS Implementation:**

```csharp
// Command and Query base classes
public interface ICommand
{
}

public interface ICommandHandler<in TCommand> where TCommand : ICommand
{
    Task Handle(TCommand command, CancellationToken cancellationToken = default);
}

public interface IQuery<TResult>
{
}

public interface IQueryHandler<in TQuery, TResult> where TQuery : IQuery<TResult>
{
    Task<TResult> Handle(TQuery query, CancellationToken cancellationToken = default);
}

// Mediator interface
public interface IMediator
{
    Task<TResult> Send<TResult>(IQuery<TResult> query, CancellationToken cancellationToken = default);
    Task Send(ICommand command, CancellationToken cancellationToken = default);
}
```

**Command Implementation:**

```csharp
// Commands
public record CreateOrderCommand(CustomerId CustomerId, List<OrderItemDto> Items) : ICommand;

public record ConfirmOrderCommand(OrderId OrderId) : ICommand;

public record CancelOrderCommand(OrderId OrderId, string Reason) : ICommand;

public record AddOrderItemCommand(OrderId OrderId, ProductId ProductId, Quantity Quantity, Money UnitPrice) : ICommand;

// Command Handlers
public class CreateOrderCommandHandler : ICommandHandler<CreateOrderCommand>
{
    private readonly IOrderRepository _orderRepository;
    private readonly IUnitOfWork _unitOfWork;
    private readonly IDomainEventDispatcher _eventDispatcher;
    
    public async Task Handle(CreateOrderCommand command, CancellationToken cancellationToken = default)
    {
        var order = new Order(new OrderId(Guid.NewGuid()), command.CustomerId);
        
        foreach (var item in command.Items)
        {
            order.AddItem(
                new ProductId(item.ProductId),
                new Quantity(item.Quantity),
                new Money(item.UnitPrice, "USD")
            );
        }
        
        await _orderRepository.SaveAsync(order);
        await _unitOfWork.CommitAsync();
        
        // Dispatch domain events
        await _eventDispatcher.DispatchAsync(order.DomainEvents);
        order.ClearDomainEvents();
    }
}

public class ConfirmOrderCommandHandler : ICommandHandler<ConfirmOrderCommand>
{
    private readonly IOrderRepository _orderRepository;
    private readonly IUnitOfWork _unitOfWork;
    private readonly IDomainEventDispatcher _eventDispatcher;
    
    public async Task Handle(ConfirmOrderCommand command, CancellationToken cancellationToken = default)
    {
        var order = await _orderRepository.GetByIdAsync(command.OrderId);
        if (order == null)
            throw new OrderNotFoundException(command.OrderId);
            
        order.Confirm();
        
        await _orderRepository.SaveAsync(order);
        await _unitOfWork.CommitAsync();
        
        // Dispatch domain events
        await _eventDispatcher.DispatchAsync(order.DomainEvents);
        order.ClearDomainEvents();
    }
}

public class CancelOrderCommandHandler : ICommandHandler<CancelOrderCommand>
{
    private readonly IOrderRepository _orderRepository;
    private readonly IUnitOfWork _unitOfWork;
    private readonly IDomainEventDispatcher _eventDispatcher;
    
    public async Task Handle(CancelOrderCommand command, CancellationToken cancellationToken = default)
    {
        var order = await _orderRepository.GetByIdAsync(command.OrderId);
        if (order == null)
            throw new OrderNotFoundException(command.OrderId);
            
        order.Cancel(command.Reason);
        
        await _orderRepository.SaveAsync(order);
        await _unitOfWork.CommitAsync();
        
        // Dispatch domain events
        await _eventDispatcher.DispatchAsync(order.DomainEvents);
        order.ClearDomainEvents();
    }
}
```

**Query Implementation:**

```csharp
// Queries
public record GetOrderQuery(OrderId OrderId) : IQuery<OrderDto>;

public record GetOrdersByCustomerQuery(CustomerId CustomerId) : IQuery<List<OrderSummaryDto>>;

public record GetOrderHistoryQuery(OrderId OrderId) : IQuery<List<OrderHistoryDto>>;

public record SearchOrdersQuery(string SearchTerm, int Page, int PageSize) : IQuery<SearchOrdersResult>;

// Query DTOs
public class OrderDto
{
    public int Id { get; set; }
    public int CustomerId { get; set; }
    public string Status { get; set; }
    public decimal Total { get; set; }
    public string Currency { get; set; }
    public DateTime CreatedAt { get; set; }
    public List<OrderItemDto> Items { get; set; }
}

public class OrderSummaryDto
{
    public int Id { get; set; }
    public int CustomerId { get; set; }
    public string Status { get; set; }
    public decimal Total { get; set; }
    public DateTime CreatedAt { get; set; }
}

public class OrderHistoryDto
{
    public DateTime Timestamp { get; set; }
    public string Action { get; set; }
    public string Description { get; set; }
}

public class SearchOrdersResult
{
    public List<OrderSummaryDto> Orders { get; set; }
    public int TotalCount { get; set; }
    public int Page { get; set; }
    public int PageSize { get; set; }
}

// Query Handlers
public class GetOrderQueryHandler : IQueryHandler<GetOrderQuery, OrderDto>
{
    private readonly IOrderRepository _orderRepository;
    
    public async Task<OrderDto> Handle(GetOrderQuery query, CancellationToken cancellationToken = default)
    {
        var order = await _orderRepository.GetByIdAsync(query.OrderId);
        if (order == null)
            throw new OrderNotFoundException(query.OrderId);
            
        return new OrderDto
        {
            Id = order.Id.Value,
            CustomerId = order.CustomerId.Value,
            Status = order.Status.ToString(),
            Total = order.Total.Amount,
            Currency = order.Total.Currency,
            CreatedAt = order.CreatedAt,
            Items = order.Items.Select(item => new OrderItemDto
            {
                ProductId = item.ProductId.Value,
                Quantity = item.Quantity.Value,
                UnitPrice = item.UnitPrice.Amount
            }).ToList()
        };
    }
}

public class GetOrdersByCustomerQueryHandler : IQueryHandler<GetOrdersByCustomerQuery, List<OrderSummaryDto>>
{
    private readonly IOrderReadRepository _orderReadRepository;
    
    public async Task<List<OrderSummaryDto>> Handle(GetOrdersByCustomerQuery query, CancellationToken cancellationToken = default)
    {
        var orders = await _orderReadRepository.GetByCustomerIdAsync(query.CustomerId);
        
        return orders.Select(order => new OrderSummaryDto
        {
            Id = order.Id,
            CustomerId = order.CustomerId,
            Status = order.Status,
            Total = order.Total,
            CreatedAt = order.CreatedAt
        }).ToList();
    }
}

public class SearchOrdersQueryHandler : IQueryHandler<SearchOrdersQuery, SearchOrdersResult>
{
    private readonly IOrderReadRepository _orderReadRepository;
    
    public async Task<SearchOrdersResult> Handle(SearchOrdersQuery query, CancellationToken cancellationToken = default)
    {
        var result = await _orderReadRepository.SearchAsync(query.SearchTerm, query.Page, query.PageSize);
        
        return new SearchOrdersResult
        {
            Orders = result.Orders.Select(order => new OrderSummaryDto
            {
                Id = order.Id,
                CustomerId = order.CustomerId,
                Status = order.Status,
                Total = order.Total,
                CreatedAt = order.CreatedAt
            }).ToList(),
            TotalCount = result.TotalCount,
            Page = query.Page,
            PageSize = query.PageSize
        };
    }
}
```

**Separate Read and Write Models:**

```csharp
// Write Model (Domain)
public class Order : AggregateRoot<OrderId>
{
    public OrderId Id { get; private set; }
    public CustomerId CustomerId { get; private set; }
    public OrderStatus Status { get; private set; }
    public Money Total { get; private set; }
    public DateTime CreatedAt { get; private set; }
    
    private readonly List<OrderItem> _items = new();
    public IReadOnlyList<OrderItem> Items => _items.AsReadOnly();
    
    // Business logic and invariants
    public void AddItem(ProductId productId, Quantity quantity, Money unitPrice)
    {
        if (Status != OrderStatus.Draft)
            throw new InvalidOperationException("Cannot add items to a confirmed order");
            
        // Business logic...
    }
    
    public void Confirm()
    {
        if (Status != OrderStatus.Draft)
            throw new InvalidOperationException("Order is not in draft status");
            
        if (_items.Count == 0)
            throw new InvalidOperationException("Cannot confirm an empty order");
            
        Status = OrderStatus.Confirmed;
        AddDomainEvent(new OrderConfirmedEvent(Id, CustomerId, Total));
    }
}

// Read Model (Optimized for queries)
public class OrderReadModel
{
    public int Id { get; set; }
    public int CustomerId { get; set; }
    public string CustomerName { get; set; }
    public string Status { get; set; }
    public decimal Total { get; set; }
    public string Currency { get; set; }
    public DateTime CreatedAt { get; set; }
    public DateTime? ConfirmedAt { get; set; }
    public DateTime? ShippedAt { get; set; }
    public string ShippingAddress { get; set; }
    public List<OrderItemReadModel> Items { get; set; }
}

public class OrderItemReadModel
{
    public int ProductId { get; set; }
    public string ProductName { get; set; }
    public int Quantity { get; set; }
    public decimal UnitPrice { get; set; }
    public decimal Total { get; set; }
}

// Read Repository
public interface IOrderReadRepository
{
    Task<OrderReadModel> GetByIdAsync(int orderId);
    Task<List<OrderReadModel>> GetByCustomerIdAsync(int customerId);
    Task<SearchResult<OrderReadModel>> SearchAsync(string searchTerm, int page, int pageSize);
}

public class OrderReadRepository : IOrderReadRepository
{
    private readonly ReadDbContext _context;
    
    public async Task<OrderReadModel> GetByIdAsync(int orderId)
    {
        return await _context.Orders
            .Include(o => o.Items)
            .Where(o => o.Id == orderId)
            .Select(o => new OrderReadModel
            {
                Id = o.Id,
                CustomerId = o.CustomerId,
                CustomerName = o.CustomerName,
                Status = o.Status,
                Total = o.Total,
                Currency = o.Currency,
                CreatedAt = o.CreatedAt,
                ConfirmedAt = o.ConfirmedAt,
                ShippedAt = o.ShippedAt,
                ShippingAddress = o.ShippingAddress,
                Items = o.Items.Select(item => new OrderItemReadModel
                {
                    ProductId = item.ProductId,
                    ProductName = item.ProductName,
                    Quantity = item.Quantity,
                    UnitPrice = item.UnitPrice,
                    Total = item.Total
                }).ToList()
            })
            .FirstOrDefaultAsync();
    }
    
    public async Task<List<OrderReadModel>> GetByCustomerIdAsync(int customerId)
    {
        return await _context.Orders
            .Where(o => o.CustomerId == customerId)
            .OrderByDescending(o => o.CreatedAt)
            .Select(o => new OrderReadModel
            {
                Id = o.Id,
                CustomerId = o.CustomerId,
                CustomerName = o.CustomerName,
                Status = o.Status,
                Total = o.Total,
                Currency = o.Currency,
                CreatedAt = o.CreatedAt,
                ConfirmedAt = o.ConfirmedAt,
                ShippedAt = o.ShippedAt
            })
            .ToListAsync();
    }
}
```

**Event-Driven Updates to Read Model:**

```csharp
// Event handler to update read model
public class OrderConfirmedEventHandler : IDomainEventHandler<OrderConfirmedEvent>
{
    private readonly IOrderReadRepository _orderReadRepository;
    
    public async Task Handle(OrderConfirmedEvent domainEvent, CancellationToken cancellationToken = default)
    {
        // Update read model when domain event occurs
        await _orderReadRepository.UpdateOrderStatusAsync(
            domainEvent.OrderId.Value, 
            "Confirmed", 
            DateTime.UtcNow);
    }
}

public class OrderCancelledEventHandler : IDomainEventHandler<OrderCancelledEvent>
{
    private readonly IOrderReadRepository _orderReadRepository;
    
    public async Task Handle(OrderCancelledEvent domainEvent, CancellationToken cancellationToken = default)
    {
        await _orderReadRepository.UpdateOrderStatusAsync(
            domainEvent.OrderId.Value, 
            "Cancelled", 
            DateTime.UtcNow);
    }
}
```

**API Controller Usage:**

```csharp
[ApiController]
[Route("api/[controller]")]
public class OrdersController : ControllerBase
{
    private readonly IMediator _mediator;
    
    [HttpPost]
    public async Task<ActionResult<OrderId>> CreateOrder([FromBody] CreateOrderCommand command)
    {
        await _mediator.Send(command);
        return Ok();
    }
    
    [HttpPost("{id}/confirm")]
    public async Task<ActionResult> ConfirmOrder(int id)
    {
        var command = new ConfirmOrderCommand(new OrderId(id));
        await _mediator.Send(command);
        return Ok();
    }
    
    [HttpPost("{id}/cancel")]
    public async Task<ActionResult> CancelOrder(int id, [FromBody] CancelOrderRequest request)
    {
        var command = new CancelOrderCommand(new OrderId(id), request.Reason);
        await _mediator.Send(command);
        return Ok();
    }
    
    [HttpGet("{id}")]
    public async Task<ActionResult<OrderDto>> GetOrder(int id)
    {
        var query = new GetOrderQuery(new OrderId(id));
        var order = await _mediator.Send(query);
        return Ok(order);
    }
    
    [HttpGet("customer/{customerId}")]
    public async Task<ActionResult<List<OrderSummaryDto>>> GetCustomerOrders(int customerId)
    {
        var query = new GetOrdersByCustomerQuery(new CustomerId(customerId));
        var orders = await _mediator.Send(query);
        return Ok(orders);
    }
    
    [HttpGet("search")]
    public async Task<ActionResult<SearchOrdersResult>> SearchOrders(
        [FromQuery] string searchTerm, 
        [FromQuery] int page = 1, 
        [FromQuery] int pageSize = 10)
    {
        var query = new SearchOrdersQuery(searchTerm, page, pageSize);
        var result = await _mediator.Send(query);
        return Ok(result);
    }
}
```

**Benefits of CQRS:**

1. **Separation of Concerns**: Commands and queries are handled separately
2. **Optimization**: Each side can be optimized independently
3. **Scalability**: Read and write operations can be scaled separately
4. **Flexibility**: Different models for different use cases
5. **Performance**: Read models can be denormalized for better query performance
6. **Maintainability**: Clear separation makes the code easier to understand and maintain

**When to Use CQRS:**

- Complex domains with different read and write requirements
- High-performance applications with many reads
- Systems where read and write models differ significantly
- Applications that need to scale reads and writes independently
- Systems with complex reporting requirements

**Best Practices:**

1. **Start Simple**: Begin with a single model and separate when needed
2. **Event-Driven Updates**: Use domain events to keep read models in sync
3. **Eventual Consistency**: Accept that read models might be slightly behind
4. **Proper Error Handling**: Handle failures in command and query processing
5. **Testing**: Test commands and queries separately
6. **Documentation**: Document the separation and synchronization strategy

CQRS is a powerful pattern that can significantly improve the performance and maintainability of complex applications when applied appropriately.

---

### 11.10. What is Event Sourcing and how does it relate to DDD?

**Answer:**

Event Sourcing is a pattern where the state of an application is determined by a sequence of events that have occurred, rather than by the current state alone. It's closely related to Domain-Driven Design and provides a powerful way to capture business events and maintain a complete audit trail.

**Core Concepts:**

1. **Events as Source of Truth**: The event store is the primary source of truth
2. **Event Store**: Persistent storage for all domain events
3. **Aggregate Reconstruction**: Rebuild aggregate state by replaying events
4. **Event Stream**: Chronological sequence of events for an aggregate
5. **Snapshots**: Periodic snapshots to optimize reconstruction

**Basic Event Sourcing Implementation:**

```csharp
// Base event class
public abstract class DomainEvent
{
    public Guid Id { get; }
    public Guid AggregateId { get; }
    public int Version { get; }
    public DateTime OccurredOn { get; }
    public string EventType { get; }
    
    protected DomainEvent(Guid aggregateId, int version)
    {
        Id = Guid.NewGuid();
        AggregateId = aggregateId;
        Version = version;
        OccurredOn = DateTime.UtcNow;
        EventType = GetType().Name;
    }
}

// Order events
public class OrderCreatedEvent : DomainEvent
{
    public CustomerId CustomerId { get; }
    public DateTime CreatedAt { get; }
    
    public OrderCreatedEvent(Guid aggregateId, int version, CustomerId customerId, DateTime createdAt)
        : base(aggregateId, version)
    {
        CustomerId = customerId;
        CreatedAt = createdAt;
    }
}

public class OrderItemAddedEvent : DomainEvent
{
    public ProductId ProductId { get; }
    public Quantity Quantity { get; }
    public Money UnitPrice { get; }
    
    public OrderItemAddedEvent(Guid aggregateId, int version, ProductId productId, Quantity quantity, Money unitPrice)
        : base(aggregateId, version)
    {
        ProductId = productId;
        Quantity = quantity;
        UnitPrice = unitPrice;
    }
}

public class OrderConfirmedEvent : DomainEvent
{
    public Money Total { get; }
    public DateTime ConfirmedAt { get; }
    
    public OrderConfirmedEvent(Guid aggregateId, int version, Money total, DateTime confirmedAt)
        : base(aggregateId, version)
    {
        Total = total;
        ConfirmedAt = confirmedAt;
    }
}

public class OrderCancelledEvent : DomainEvent
{
    public string Reason { get; }
    public DateTime CancelledAt { get; }
    
    public OrderCancelledEvent(Guid aggregateId, int version, string reason, DateTime cancelledAt)
        : base(aggregateId, version)
    {
        Reason = reason;
        CancelledAt = cancelledAt;
    }
}
```

**Event-Sourced Aggregate:**

```csharp
public class Order : AggregateRoot<OrderId>
{
    public OrderId Id { get; private set; }
    public CustomerId CustomerId { get; private set; }
    public OrderStatus Status { get; private set; }
    public Money Total { get; private set; }
    public DateTime CreatedAt { get; private set; }
    
    private readonly List<OrderItem> _items = new();
    public IReadOnlyList<OrderItem> Items => _items.AsReadOnly();
    
    // Constructor for creating new orders
    public Order(OrderId id, CustomerId customerId)
    {
        Id = id;
        CustomerId = customerId;
        Status = OrderStatus.Draft;
        Total = new Money(0, "USD");
        CreatedAt = DateTime.UtcNow;
        
        // Raise event
        RaiseEvent(new OrderCreatedEvent(id.Value, 1, customerId, CreatedAt));
    }
    
    // Constructor for rebuilding from events
    private Order()
    {
        // Used by event sourcing
    }
    
    public void AddItem(ProductId productId, Quantity quantity, Money unitPrice)
    {
        if (Status != OrderStatus.Draft)
            throw new InvalidOperationException("Cannot add items to a confirmed order");
            
        var item = new OrderItem(productId, quantity, unitPrice);
        _items.Add(item);
        RecalculateTotal();
        
        // Raise event
        RaiseEvent(new OrderItemAddedEvent(Id.Value, Version + 1, productId, quantity, unitPrice));
    }
    
    public void Confirm()
    {
        if (Status != OrderStatus.Draft)
            throw new InvalidOperationException("Order is not in draft status");
            
        if (_items.Count == 0)
            throw new InvalidOperationException("Cannot confirm an empty order");
            
        Status = OrderStatus.Confirmed;
        
        // Raise event
        RaiseEvent(new OrderConfirmedEvent(Id.Value, Version + 1, Total, DateTime.UtcNow));
    }
    
    public void Cancel(string reason)
    {
        if (Status == OrderStatus.Shipped)
            throw new InvalidOperationException("Cannot cancel a shipped order");
            
        Status = OrderStatus.Cancelled;
        
        // Raise event
        RaiseEvent(new OrderCancelledEvent(Id.Value, Version + 1, reason, DateTime.UtcNow));
    }
    
    private void RecalculateTotal()
    {
        Total = _items.Aggregate(new Money(0, "USD"), (sum, item) => sum + item.Total);
    }
    
    // Event application methods
    private void Apply(OrderCreatedEvent @event)
    {
        Id = new OrderId(@event.AggregateId);
        CustomerId = @event.CustomerId;
        Status = OrderStatus.Draft;
        Total = new Money(0, "USD");
        CreatedAt = @event.CreatedAt;
    }
    
    private void Apply(OrderItemAddedEvent @event)
    {
        var item = new OrderItem(@event.ProductId, @event.Quantity, @event.UnitPrice);
        _items.Add(item);
        RecalculateTotal();
    }
    
    private void Apply(OrderConfirmedEvent @event)
    {
        Status = OrderStatus.Confirmed;
    }
    
    private void Apply(OrderCancelledEvent @event)
    {
        Status = OrderStatus.Cancelled;
    }
}
```

**Event Store Interface and Implementation:**

```csharp
public interface IEventStore
{
    Task SaveEventsAsync(Guid aggregateId, IEnumerable<DomainEvent> events, int expectedVersion);
    Task<IEnumerable<DomainEvent>> GetEventsAsync(Guid aggregateId);
    Task<IEnumerable<DomainEvent>> GetEventsAsync(Guid aggregateId, int fromVersion);
    Task<IEnumerable<DomainEvent>> GetEventsAsync(DateTime from, DateTime to);
}

public class EventStore : IEventStore
{
    private readonly EventStoreDbContext _context;
    private readonly IEventSerializer _eventSerializer;
    
    public async Task SaveEventsAsync(Guid aggregateId, IEnumerable<DomainEvent> events, int expectedVersion)
    {
        var eventEntities = events.Select((domainEvent, index) => new EventEntity
        {
            Id = domainEvent.Id,
            AggregateId = aggregateId,
            EventType = domainEvent.EventType,
            EventData = _eventSerializer.Serialize(domainEvent),
            Version = expectedVersion + index + 1,
            OccurredOn = domainEvent.OccurredOn
        });
        
        _context.Events.AddRange(eventEntities);
        await _context.SaveChangesAsync();
    }
    
    public async Task<IEnumerable<DomainEvent>> GetEventsAsync(Guid aggregateId)
    {
        var eventEntities = await _context.Events
            .Where(e => e.AggregateId == aggregateId)
            .OrderBy(e => e.Version)
            .ToListAsync();
            
        return eventEntities.Select(DeserializeEvent);
    }
    
    public async Task<IEnumerable<DomainEvent>> GetEventsAsync(Guid aggregateId, int fromVersion)
    {
        var eventEntities = await _context.Events
            .Where(e => e.AggregateId == aggregateId && e.Version > fromVersion)
            .OrderBy(e => e.Version)
            .ToListAsync();
            
        return eventEntities.Select(DeserializeEvent);
    }
    
    public async Task<IEnumerable<DomainEvent>> GetEventsAsync(DateTime from, DateTime to)
    {
        var eventEntities = await _context.Events
            .Where(e => e.OccurredOn >= from && e.OccurredOn <= to)
            .OrderBy(e => e.OccurredOn)
            .ToListAsync();
            
        return eventEntities.Select(DeserializeEvent);
    }
    
    private DomainEvent DeserializeEvent(EventEntity eventEntity)
    {
        var eventType = Type.GetType(eventEntity.EventType);
        return (DomainEvent)_eventSerializer.Deserialize(eventEntity.EventData, eventType);
    }
}

public class EventEntity
{
    public Guid Id { get; set; }
    public Guid AggregateId { get; set; }
    public string EventType { get; set; }
    public string EventData { get; set; }
    public int Version { get; set; }
    public DateTime OccurredOn { get; set; }
}
```

**Event-Sourced Repository:**

```csharp
public interface IEventSourcedRepository<TAggregate> where TAggregate : AggregateRoot
{
    Task<TAggregate> GetByIdAsync(Guid id);
    Task SaveAsync(TAggregate aggregate);
}

public class EventSourcedOrderRepository : IEventSourcedRepository<Order>
{
    private readonly IEventStore _eventStore;
    private readonly ISnapshotStore _snapshotStore;
    
    public async Task<Order> GetByIdAsync(Guid id)
    {
        // Try to get from snapshot first
        var snapshot = await _snapshotStore.GetSnapshotAsync<Order>(id);
        var fromVersion = 0;
        
        if (snapshot != null)
        {
            fromVersion = snapshot.Version;
        }
        
        // Get events from the snapshot version
        var events = await _eventStore.GetEventsAsync(id, fromVersion);
        
        // Reconstruct aggregate
        var order = new Order();
        
        // Apply snapshot if available
        if (snapshot != null)
        {
            order.RestoreFromSnapshot(snapshot);
        }
        
        // Apply events
        foreach (var @event in events)
        {
            order.ApplyEvent(@event);
        }
        
        return order;
    }
    
    public async Task SaveAsync(Order aggregate)
    {
        var events = aggregate.GetUncommittedEvents();
        var expectedVersion = aggregate.Version - events.Count();
        
        await _eventStore.SaveEventsAsync(aggregate.Id.Value, events, expectedVersion);
        
        // Create snapshot if needed
        if (ShouldCreateSnapshot(aggregate))
        {
            var snapshot = aggregate.CreateSnapshot();
            await _snapshotStore.SaveSnapshotAsync(aggregate.Id.Value, snapshot);
        }
        
        aggregate.MarkEventsAsCommitted();
    }
    
    private bool ShouldCreateSnapshot(Order aggregate)
    {
        // Create snapshot every 100 events
        return aggregate.Version % 100 == 0;
    }
}
```

**Snapshot Implementation:**

```csharp
public interface ISnapshotStore
{
    Task<TSnapshot> GetSnapshotAsync<TSnapshot>(Guid aggregateId) where TSnapshot : class;
    Task SaveSnapshotAsync<TSnapshot>(Guid aggregateId, TSnapshot snapshot) where TSnapshot : class;
}

public class OrderSnapshot
{
    public Guid AggregateId { get; set; }
    public int Version { get; set; }
    public CustomerId CustomerId { get; set; }
    public OrderStatus Status { get; set; }
    public Money Total { get; set; }
    public DateTime CreatedAt { get; set; }
    public List<OrderItem> Items { get; set; }
    public DateTime SnapshotDate { get; set; }
}

public class Order : AggregateRoot<OrderId>
{
    // ... existing code ...
    
    public OrderSnapshot CreateSnapshot()
    {
        return new OrderSnapshot
        {
            AggregateId = Id.Value,
            Version = Version,
            CustomerId = CustomerId,
            Status = Status,
            Total = Total,
            CreatedAt = CreatedAt,
            Items = _items.ToList(),
            SnapshotDate = DateTime.UtcNow
        };
    }
    
    public void RestoreFromSnapshot(OrderSnapshot snapshot)
    {
        Id = new OrderId(snapshot.AggregateId);
        CustomerId = snapshot.CustomerId;
        Status = snapshot.Status;
        Total = snapshot.Total;
        CreatedAt = snapshot.CreatedAt;
        _items.Clear();
        _items.AddRange(snapshot.Items);
        Version = snapshot.Version;
    }
}
```

**Event Sourcing with CQRS:**

```csharp
// Command side - uses event sourcing
public class CreateOrderCommandHandler : ICommandHandler<CreateOrderCommand>
{
    private readonly IEventSourcedRepository<Order> _orderRepository;
    
    public async Task Handle(CreateOrderCommand command, CancellationToken cancellationToken = default)
    {
        var order = new Order(new OrderId(Guid.NewGuid()), command.CustomerId);
        
        foreach (var item in command.Items)
        {
            order.AddItem(
                new ProductId(item.ProductId),
                new Quantity(item.Quantity),
                new Money(item.UnitPrice, "USD")
            );
        }
        
        await _orderRepository.SaveAsync(order);
    }
}

// Query side - uses read models updated by events
public class OrderReadModelUpdater : IDomainEventHandler<OrderCreatedEvent>
{
    private readonly IOrderReadRepository _readRepository;
    
    public async Task Handle(OrderCreatedEvent domainEvent, CancellationToken cancellationToken = default)
    {
        await _readRepository.CreateOrderAsync(new OrderReadModel
        {
            Id = domainEvent.AggregateId,
            CustomerId = domainEvent.CustomerId.Value,
            Status = "Draft",
            Total = 0,
            CreatedAt = domainEvent.CreatedAt
        });
    }
}

public class OrderItemAddedEventHandler : IDomainEventHandler<OrderItemAddedEvent>
{
    private readonly IOrderReadRepository _readRepository;
    
    public async Task Handle(OrderItemAddedEvent domainEvent, CancellationToken cancellationToken = default)
    {
        await _readRepository.AddOrderItemAsync(domainEvent.AggregateId, new OrderItemReadModel
        {
            ProductId = domainEvent.ProductId.Value,
            Quantity = domainEvent.Quantity.Value,
            UnitPrice = domainEvent.UnitPrice.Amount
        });
    }
}
```

**Benefits of Event Sourcing:**

1. **Complete Audit Trail**: Every change is recorded as an event
2. **Temporal Queries**: Can query the state at any point in time
3. **Debugging**: Easy to understand what happened and when
4. **Compliance**: Meets regulatory requirements for audit trails
5. **Replay Capability**: Can replay events to rebuild state
6. **Integration**: Events can be used for integration between systems
7. **Analytics**: Rich data for business intelligence and analytics

**Challenges of Event Sourcing:**

1. **Complexity**: More complex than traditional CRUD
2. **Event Schema Evolution**: Need to handle changes to event structure
3. **Performance**: Rebuilding aggregates from events can be slow
4. **Storage**: Can require more storage space
5. **Learning Curve**: Team needs to understand the pattern

**When to Use Event Sourcing:**

- Systems requiring complete audit trails
- Complex business domains with rich event models
- Systems where temporal queries are important
- Applications with compliance requirements
- Systems that need to replay events for analysis
- Integration scenarios where events are valuable

**Best Practices:**

1. **Event Design**: Design events to be meaningful and immutable
2. **Snapshot Strategy**: Use snapshots to optimize performance
3. **Event Versioning**: Plan for event schema evolution
4. **Error Handling**: Handle event processing failures gracefully
5. **Testing**: Test event sourcing thoroughly with event replay
6. **Documentation**: Document event schemas and processing logic

Event Sourcing is a powerful pattern that provides significant benefits for complex domains, especially when combined with DDD and CQRS. It's particularly valuable for systems that need complete audit trails and temporal querying capabilities.

---

## 12. DevOps and CI/CD

### 12.1. What is CI/CD and why is it important?

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

### 12.2. Have you worked with Docker? Explain containerization.

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

### 12.3. What is Kubernetes and what problems does it solve?

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

### 12.4. Explain the concept of Infrastructure as Code.

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

### 12.5. What Azure/AWS services have you worked with for .NET applications?

Here's an overview of commonly used cloud services for .NET Core applications:

### 12.6. Azure Services

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

### 12.7. AWS Services

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

## 13. General and Behavioral

### 13.1. How do you stay updated with the latest .NET technologies?

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

### 13.2. Describe a challenging bug you've encountered and how you resolved it.

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

### 13.3. How do you handle technical debt in a project?

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

### 13.4. Explain your code review process and what you look for.

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

### 13.5. How do you mentor junior developers on your team?

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
