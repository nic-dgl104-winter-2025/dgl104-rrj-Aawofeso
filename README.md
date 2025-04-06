[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MMj2nZMu)
# Research and Reflection Journal
Research and Reflection Journal for DGL 104 course
## Week 8

## What I Learned This Week

### Functional Requirements and User Stories
This week, I explored the concepts of functional requirements and user stories in software development. Key takeaways include:

- **User Stories**: These are written in natural language to describe user interactions with a system. They are great for team communication but often lack technical details.
- **Technical Design Documents (TDD)**: Used to address technical concerns and provide a high-level design context. They help align the team on architecture and technologies early in the development process.
- **Functional Requirements**: These describe software features on an input-output basis, similar to programming functions. They provide clear specifications for app features and are often derived from user stories.

Understanding these concepts helps in balancing user experience with technical implementation, ensuring robust and user-friendly applications.

## Research on Haskell

### Overview
Haskell is a purely functional programming language known for its strong static typing and lazy evaluation. It emphasizes immutability and mathematical precision, making it a favorite among those who appreciate clean and reliable code.

### Applications
1. **Academic Research**: Used for teaching functional programming concepts.
2. **Financial Systems**: Employed by companies like Standard Chartered for reliable financial software.
3. **Web Development**: Frameworks like Yesod and Servant leverage Haskell's strengths for building web services.
4. **Data Analysis**: Suitable for handling large datasets and complex computations.
5. **Compiler Development**: Ideal for developing compilers and interpreters due to its support for abstract syntax trees.

### Users
- Academic Researchers
- Financial Software Developers
- Web Developers
- Data Analysts
- Compiler Engineers

### Useful Resources
1. **Learn You a Haskell for Great Good!**: A fun and approachable online book for beginners.
2. **Haskell.org**: The official site with comprehensive documentation and tutorials.
3. **Hackage**: A central package archive for discovering and sharing Haskell libraries.
4. **Stack Overflow**: A platform for solving specific problems and learning best practices in the Haskell community.

## User Stories

**User Story 1: Purchasing a Bus Ticket**

As a commuter, I want to buy a bus ticket online to secure my seat without visiting the station.

**Acceptance Criteria:**
1. Select departure/arrival locations, date, and time.
2. View available bus services.
3. Choose a bus and pay online (credit card, PayPal, etc.).
4. Receive a confirmation email with ticket details.
5. Download or print the ticket from the email or app.

**User Story 2: Checking Bus Schedule**

As a passenger, I want to check bus schedules to plan my trip.

**Acceptance Criteria:**
1. Enter departure/arrival locations without logging in.
2. View schedules for today and tomorrow, including times and prices.
3. Filter results by time, price, or provider.

**User Story 3: Managing Bookings**

As a user, I want to view, cancel, or modify my bookings easily.

**Acceptance Criteria:**
1. Log in to view current and past bookings.
2. Cancel or modify bookings (change date/time/seat).
3. See available options for modifications.
4. Receive confirmation and refund details for cancellations.
5. Get a new confirmation email for modifications.
6. Be informed of any extra charges or refunds.


#### CHOOSE A LANGUAGE FOR COMMUNITY CODE:

For my community coding project, My group  decided to focus on PHP for both the front end and back end. My experience with PHP is limited, but I'm eager to learn more about it. We chose PHP because it's a versatile language that powers many websites and applications, making it ideal for developing dynamic and interactive web pages. PHP is widely used for server-side scripting, and its integration with databases like MySQL makes it perfect for building robust web applications. Additionally, PHP has a large and supportive community, which is beneficial for beginners seeking guidance and resources. [Learn more about PHP](https://www.php.net/manual/en/intro-whatis.php)



## Week 9
### Summary of Design Patterns

**Overview:**
Design patterns are established solutions to common problems in software design, particularly within the object-oriented programming paradigm. They were popularized by a group of four authors known as the "Gang of Four" in their book "Design Patterns: Elements of Reusable Object-Oriented Software," published in the early 1990s. This summary outlines key principles, types of design patterns, and specific examples discussed in the transcript.

**Key Principles:**
1. **Program to an Interface, Not an Implementation:** This principle encourages developers to define interfaces that specify expected behaviors without dictating how those behaviors should be implemented. This promotes flexibility and reduces dependencies between classes.
   
2. **Favor Object Composition Over Class Inheritance:** Instead of relying solely on inheritance to create complex behaviors, this principle advocates for composing objects from smaller, simpler components. This approach can lead to more maintainable and less brittle code.

**Categories of Design Patterns:**
Design patterns are typically classified into three main categories based on their purpose:
1. **Creational Patterns:** These patterns deal with object creation mechanisms, aiming to create objects in a manner suitable to the situation. An example is the Singleton pattern, which ensures a class has only one instance and provides a global point of access to it.
   
2. **Structural Patterns:** These patterns focus on how classes and objects are composed to form larger structures. They help ensure that if one part of a system changes, the entire system doesn't need to change. 

3. **Behavioral Patterns:** These patterns are concerned with algorithms and the assignment of responsibilities between objects. They help define how objects interact and communicate with one another.

**Examples of Design Patterns:**
- **Singleton Pattern:** This creational pattern restricts a class to a single instance and provides a global access point to that instance. It is useful for managing shared resources, such as database connections.
  
- **Observer Pattern:** This behavioral pattern allows a subject to notify multiple observers about state changes, facilitating a one-to-many dependency. This is particularly useful in user interface design, where changes in one part of the system need to be reflected in others.

**Resources for Further Learning:**
- Wikipedia provides a comprehensive list of design patterns, including those not covered by the Gang of Four.
- Refactoring Guru offers approachable explanations and graphics related to design patterns.
- "Learning JavaScript Design Patterns" by Addy Osmani is a recommended resource for understanding design patterns in JavaScript.

**Conclusion:**
While design patterns provide valuable solutions to common programming challenges, they are not one-size-fits-all solutions. Developers should be aware of the context in which they apply these patterns and consider the potential for over-engineering or creating complex dependencies. Understanding both design patterns and their anti-patterns can lead to better software design practices.


Got it! Here’s a revised version of the README that maintains the structure you provided but presents the content in a different way:



### HOW TO CONTRIBUTE TO OPEN SOURCE

I recently learned that contributing to open source projects is accessible to everyone, not just those with advanced coding skills. There are numerous ways to get involved, such as helping with event organization, enhancing design elements, writing documentation, managing project issues, facilitating discussions, and reviewing code contributions. This realization was a relief for me, as I often doubted my coding abilities. I also discovered valuable resources like [First Contributions](https://firstcontributions.github.io/), [First Timers Only](https://www.firsttimersonly.com/), and [Up For Grabs](https://up-for-grabs.net/#/), which are excellent starting points for newcomers seeking welcoming projects. It’s crucial to choose a project that is genuinely open source, active, and supportive of beginners.

Before diving into this world, I hesitated to contribute because I felt inexperienced. However, I now recognize that open source is inclusive and offers opportunities for everyone, including those who excel in writing, design, or translation. The guide I explored helped me identify tasks that align with my skills and interests, which was incredibly motivating. It shifted my perspective from believing that only seasoned developers could contribute to understanding that open source is a space for all—writers, designers, translators, and even those just starting their coding journey. Moreover, open source extends beyond software; it encompasses everything from educational materials to creative projects, broadening the scope for contributions. This newfound understanding has opened my eyes to the vast possibilities within the open source community.

#### Finding a Project to Contribute To

One project that caught my attention was the Guess Game created by Prateek Kalra, which can be found [here](https://github.com/prateekkalra/guess-game). I focused on setting appropriate ranges for different difficulty levels and ensuring that players received clear messages if they entered numbers outside those ranges. By tackling these challenges, I helped enhance the game's functionality and overall player experience.

#### Reflection

Searching for the right project to contribute to was a bit challenging. I explored platforms like Good First Issue, Up for Grabs, and CodeTriage to find suitable opportunities. I had specific criteria in mind, and it took considerable time to identify a project that met my expectations. Additionally, sifting through various issues in the project to find one I could effectively address added to the complexity of the process.


## Week 10 
### Learning MV Architectural Patterns  

This week, I explored MV (Model-View) architectural patterns, which are widely used in UI development. These patterns structure applications by separating data, user interface, and logic, making them more maintainable and scalable (Django Project, 2025; Android Developers, 2025).  



### Key Concepts of MV Patterns 

The MVfamily includes several architectural patterns that all share the Model (M) and View (V) components but differ in their third part. The most commonly used ones are:    

- ### MVC (Model-View-Controller)  
 MVC is one of the oldest and most well-known UI architectural patterns and is a long-standing and widely adopted pattern. . It separates concerns into three distinct parts:  

1. Model – Manages application data and business logic.  
2. View – Displays data to the user but does not modify it.  
3. Controller – Acts as an intermediary, processing user input and updating the Model accordingly.

- ### MVVM (Model-View-ViewModel) 

MVVM is an evolution of MVC and is often used in modern mobile and web development (Android Developers, 2025). It helps separate concerns even further:  

1. Model – Represents the application data and logic.  
2. View – Displays information to the user.  
3. ViewModel – Acts as an intermediary, preparing data for the View while keeping the Model unaware of UI logic.

- ### MVP (Model-View-Presenter) 

MVP is a variation of MVC, where the Presenter takes full responsibility for UI logic instead of the Controller. It is commonly used in Android development (Android Developers, 2025). 

- ### MVI (Model-View-Intent) and Unidirectional Data Flow  

MVI is a relatively newer pattern that enforces unidirectional data flow to make applications more predictable. It is particularly useful in state management frameworks (JetBrains, 2025).  

### Evolution of MVC in Different Platforms
Different platforms have adapted MVC in unique ways:    

- iOS Development: Initially relied heavily on MVC, but with the introduction of SwiftUI, it has shifted toward MVVM.  
- Android Development: Originally used MVC and MVP, but now prefers MVVM and Jetpack Compose.  
- Web Development: MVC remains prevalent in frameworks such as Django, Ruby on Rails, Angular, and Vue.  

### Separation of Concerns and Why It Matters 

A key takeaway from learning MV patterns is the importance of separating data, user interface, and logic. This improves:  

- Testability – Independent modules are easier to test.  
- Scalability – Reduces complexity as applications grow.  
- Maintainability – Makes debugging and future updates easier.  


### Applying MVC to Software Development  

This week, I learned that MVC remains a foundational UI architecture. While newer trends like MVVM are growing in popularity, MVC still plays a critical role in modern applications (Django Project, 2025; Swift.org, 2025).  

### How I Applied My Learning:  
 1. Examined how MVC structures function in different programming environments. 
 2. Analyzed real-world implementations in web frameworks like Django and Ruby on Rails.
 3. Researched how MVVM builds upon MVC in mobile app development.**  

---

### Reflection

As I wrote this section, I found MVC easy to understand since it is widely used, but MVI was more complex because of its strict data flow rules. MVVM felt like the most balanced approach, and I can see why it is becoming a popular choice for modern applications.  

Adding code examples for each pattern helped me grasp their differences. While writing, I made sure to keep explanations clear so that someone new to architectural patterns can follow along easily.  


### References

1. Vue.js. (2025). Introduction to Vue.js framework. Retrieved from [https://vuejs.org/guide/introduction.html](https://vuejs.org/guide/introduction.html)  
2. JetBrains. (2025). Kotlin and MVI: Best practices for state management. Retrieved from [https://blog.jetbrains.com/kotlin-mvi](https://blog.jetbrains.com/kotlin-mvi)  
3. Android Developers. (2025). Understanding MVVM in Android applications. Retrieved from [https://developer.android.com/jetpack/guide](https://developer.android.com/jetpack/guide)  
4. Django Project. (2025). MVC in web frameworks. Retrieved from [https://docs.djangoproject.com/en/4.0/mvc-overview](https://docs.djangoproject.com/en/4.0/mvc-overview)  
5. Swift.org. (2025). MVVM in SwiftUI: The future of iOS architecture. Retrieved from [https://swift.org/mvvm-guide](https://swift.org/mvvm-guide)  


## Week 11
### Object-Oriented Programming (OOP) Concepts and Application 

During  this week, I explored Object-Oriented Programming (OOP) extensively with special focus on key OOP principles and SOLID design principles and how they are used in practice. Below is a systematic outline of what I learned with examples, what it was like to apply OOP on a team programming assignment, and what I learned about our choice of programming language.


### Understanding Object-Oriented Programming (OOP)  

OOP is a programming paradigm that organizes code into objects, making it modular, reusable, and scalable. This approach is widely used in modern software development due to its efficiency and maintainability (TechTarget, 2024).  

OOP consists of four fundamental principles which are :  

### 1. Encapsulation 
Encapsulation restricts direct access to an object’s data and allows controlled access through methods. This ensures data protection and prevents unintended modifications.  

### 2. Abstraction 
Abstraction hides the implementation details and only exposes necessary functionalities.  

### 3. Inheritance  
Inheritance allows a class to reuse properties and methods from another class, enabling code reusability and hierarchical relationships between objects.  

### 4. Polymorphism  
Polymorphism allows a single method to be used in different ways depending on the object.  

### SOLID Principles and OOP Best Practices  

To enhance code maintainability and flexibility, we also learned about the SOLID design principles  

### 1. Single Responsibility Principle (SRP)  
A class should have only one reason to change.

### 2. Open-Closed Principle (OCP) 
Classes should be open for extension but closed for modification.  


### 3. Interface Segregation Principle (ISP)  
Clients should not be forced to depend on interfaces they do not use.  

### Applying OOP to Our Group Programming Assignment 

### How OOP Will Be Used in Our Project 
For our group programming assignment, we will apply OOP principles to ensure our project would be modular, maintainable, and reusable.  

Example: Implementing OOP for a User Management System 
- `User` (Base class): Stores user details.  
- `AdminUser` (Child class): Extends `User` with additional permissions.  
- `GuestUser` (Child class): Extends `User` with limited access.  
- `AuthenticationManager or Leader` (Encapsulation): Manages user login without exposing sensitive data.  

By structuring our code this way, we separate responsibilities and reduce complexity, making future modifications easier.  

---

### Is Our Chosen Programming Language OOP-Capable?  

### Chosen Language: Python 
Python is fully OOP-capable, supporting encapsulation, inheritance, polymorphism, and abstraction.  

### Does Python support other paradigms?  
Yes! Besides OOP, Python also supports:  
- Procedural Programming (using functions without objects)  
- Functional Programming (using lambda functions and higher-order functions like `map()`, `reduce()`, and `filter()`)  

### Why is Python a good choice?  
- It allows multiple paradigms (OOP, procedural, and functional).  
- It has easy-to-use syntax, making it beginner-friendly.  
- It has strong community support for best practices.  

Example of Python’s OOP Support: 

```python
class User:
    def __init__(self, name, email):
        self.name = name
        self.email = email

    def display_info(self):
        print(f"User: {self.name}, Email: {self.email}")

class AdminUser(User):
    def __init__(self, name, email, admin_level):
        super().__init__(name, email)
        self.admin_level = admin_level

admin = AdminUser("Alice", "alice@example.com", "SuperAdmin")
admin.display_info()
```

### Final Thoughts
OOP is a powerful paradigm that makes code structured, reusable, and scalable. Using OOP principles and SOLID design in our group project ensures that our code is easy to maintain, extend, and debug. Python’s full OOP support, combined with its ability to support multiple paradigms, makes it an ideal language for our project.  



### References  

1. Martin, R. C. (2014). The Single Responsibility Principle. Clean Coder Blog. Retrieved from [https://blog.cleancoder.com/uncle-bob/2014/05/08/SingleReponsibilityPrinciple.html](https://blog.cleancoder.com/uncle-bob/2014/05/08/SingleReponsibilityPrinciple.html)  
2. Martin, R. C. (2014). The Open-Closed Principle. Clean Coder Blog. Retrieved from [https://blog.cleancoder.com/uncle-bob/2014/05/12/TheOpenClosedPrinciple.html](https://blog.cleancoder.com/uncle-bob/2014/05/12/TheOpenClosedPrinciple.html)  
3. Wikipedia. (2025). Interface Segregation Principle. Retrieved from [https://en.wikipedia.org/wiki/Interface_segregation_principle](https://en.wikipedia.org/wiki/Interface_segregation_principle) 
4. TechTarget. (2024). OOP Explained. Retrieved from https://www.techtarget.com/searchapparchitecture/definition/object-oriented-programming-OOP
5. Dev.to. (2024). Combining OOP and Functional Programming. Retrieved from https://dev.to/adityabhuyan/combining-object-oriented-and-functional-programming 
6. Gee CS Oswego. (2024). CS Resources on OOP Principles. Retrieved from [https://gee.cs.oswego.edu/dl/groups](https://gee.cs.oswego.edu/dl/groups)
7. Stack Overflow. (2024). How do you design object-oriented projects?. Retrieved from [https://stackoverflow.com/questions/1100819/how-do-you-design-object-oriented-projects](https://stackoverflow.com/questions/1100819/how-do-you-design-object-oriented-projects)


## Week 12
### Functional Programming

### What I Learned This Week

This week, we were taught Functional Programming and how it fits within the Declarative Programming Paradigm. At first, it felt abstract, especially coming from an object-oriented background. However, the examples and real-life use cases helped me grasp why functional programming is valuable—especially in modern development environments.

I learned that functional programming is all about writing predictable, clean, and testable codes using functions that don’t alter program state. Functional programming treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data (Wazner, 2023). What stood out to me most was the idea of pure functions, higher-order functions, and recursion.


 Key Concepts of Functional Programming

  Imperative vs Declarative
- Imperative programming focuses on how to perform tasks (step-by-step), using loops and control flows.
- Declarative programming focuses on what the result should be, hiding the control flow under the hood (Kumar, 2022).

 Pure Functions
Pure functions always return the same result for the same inputs and don’t cause side effects.

```javascript
// Pure Function
function square(x) {
  return x * x;
}
```

Unlike functions that modify external variables or states, this function’s output depends solely on its input.


 Higher-Order Functions
A function that can accept another function as an argument or return one.

```javascript
function calculate(x, y, operation) {
  return operation(x, y);
}

const add = (a, b) => a + b;
console.log(calculate(2, 3, add)); // Output: 5
```

Higher-order functions are essential in libraries like React, Vue, and Lodash (MDN, 2024).

### Recursion
Functional programming prefers recursion over loops. A function calls itself until a base case is met.

```python
def factorial(n):
    if n == 0:
        return 1
    return n * factorial(n-1)

print(factorial(5))  # Output: 120
```

This recursive function avoids mutation and aligns with FP principles (Thompson, 2021).

---

### Working with Collections

Functional languages often work with collections (like arrays, lists) using built-in methods like `map`, `filter`, and `reduce`.

###  Filter Example
```kotlin
val numbers = listOf(-2, -1, 0, 1, 2, 3)
val positives = numbers.filter { it > 0 }
println(positives) // Output: [1, 2, 3]
```

###  Map Example
```kotlin
val result = numbers.map { it * 2 }
println(result) // Output: [-4, -2, 0, 2, 4, 6]
```

These methods are shorter, easier to read, and don’t alter the original data structures, supporting the immutability principle.

---

### Side Effects and State Changes

One of the most important benefits I learned is that funcctional programming helps avoid side effects. In traditional OOP code, modifying shared states can lead to bugs. Functional programming avoids this by treating data as immutable and state changes as isolated computations (Paul, 2020).



### Real-World Usage of Functional Programming

Programming languages like Haskell and Elm are purely functional, but most modern languages like JavaScript, Python, Swift, and Kotlin support FP features. These languages are multi-paradigm, which means we can mix functional programming with OOP styles depending on the use case (Wikipedia, 2024).

### Kotlin Collection Example

```kotlin
val evenNumbers = (1..10).filter { it % 2 == 0 }
println(evenNumbers) // Output: [2, 4, 6, 8, 10]
```

This method is functional and declarative and reduces the chance of bugs.

---

### Reflection

I found functional programming challenging a bit in the beginning, especially since I’m more familiar with object-oriented logic. But learning about pure functions, higher-order functions, and recursion helped me see how functional programming enables a clean, testable, and reliable code.

I wouldn't mind using more functional programming tools in projects. I can now understand that even though we use object-oriented languages such as Kotlin or Swift, we can still write functional-style codes that are more maintainable and less error-prone.

---

### References

1. Paul, A. (2020). Functional programming: A different way of thinking about software. IBM Developer. Retrived from [https://developer.ibm.com/articles/why-functional-programming-matters] (https://developer.ibm.com/articles/why-functional-programming-matters) 
2. Kumar, A. (2022). Imperative vs Declarative Programming. GeeksForGeeks. Retrived from [https://www.geeksforgeeks.org/difference-between-imperative-and-declarative-programming/] (https://www.geeksforgeeks.org/difference-between-imperative-and-declarative-programming/)  
3. MDN Web Docs. (2024). Higher-order functions. Mozilla Developer Network. Retrived from [https://developer.mozilla.org/en-US/docs/Glossary/Higher-order_function] (https://developer.mozilla.org/en-US/docs/Glossary/Higher-order_function)  
4. Thompson, S. (2021). Haskell: The Craft of Functional Programming (4th ed.). Pearson Education.  
5. Wazner, J. (2023). Pure Functions and Side Effects in Functional Programming. FreeCodeCamp. Retrived from [https://www.freecodecamp.org/news/pure-functions-and-side-effects-in-functional-programming] (https://www.freecodecamp.org/news/pure-functions-and-side-effects-in-functional-programming)  
6. Wikipedia. (2024). Comparison of multi-paradigm programming languages. Retrived from [https://en.wikipedia.org/wiki/Comparison_of_multi-paradigm_programming_languages] (https://en.wikipedia.org/wiki/Comparison_of_multi-paradigm_programming_languages)  
