#### Objectives:

* To learn the concept of "if" statement ,which is one of the flow control in programming languages
* To know how to use "if statement" to make decisions in a code.
* To gain an impression of the most popular coding languages currently used by various projects and companies

#### Resources:

* [YouTube Video](https://www.youtube.com/watch?v=VnyeINxAAC8)
* [Interactive Practice](https://juniorit.ai/resource/course/hello-world-in-different-coding-language-practice)

Let’s kick off our future coding learning journey - If statement.

![functions image](https://www.programtopia.net/wp-content/uploads/2021/01/if_0.png)

In programming languages, an "if" statement is a conditional statement that allows you to execute a block of code based on a certain condition. It is used to make decisions and control the flow of the program.

The basic syntax of an "if" statement typically consists of the keyword "if" followed by a condition in parentheses, and then a block of code enclosed in curly braces. 

Lets checkout the use of "if statement" in most popular coding languages.

1. Dart

Dart is an object-oriented, client-optimized programming language that is developed by Google. It is designed to be used for developing web and mobile applications, as well as server-side applications. Dart is a statically typed language, which means that type checking is done at compile-time rather than at runtime.

One of the key features of Dart is its support for building user interfaces through a reactive programming model, using a library called Flutter. Flutter is a popular mobile development framework that is built on top of Dart, and it allows developers to create native mobile applications for iOS and Android with a single codebase.

If statement in Dart
```dart {type:code, action: run}
bool isRaining = true;

if (isRaining) {
    print("Take an umbrella with you!");
}
```



2. Javascript

JavaScript is a programming language that is commonly used to create interactive effects within web browsers. It is an object-oriented language that is based on a prototype model, which means that objects inherit properties and methods directly from other objects.

JavaScript was originally created by Brendan Eich at Netscape in 1995, and it has since become one of the most popular programming languages in use today. JavaScript can be used to add functionality to web pages, create dynamic user interfaces, and build web applications. It is also used on the server-side with Node.js, a platform that allows developers to build server-side applications using JavaScript.

If statement in Javascript
```javascript {type:code, action: run}
let number = 10;

if (number > 0) {
    console.log("The number is positive.");
}
```

3. Typescript

TypeScript is a programming language that is a superset of JavaScript. It was developed by Microsoft and was first released in 2012. TypeScript is designed to add optional static typing, classes, and other features to JavaScript, while still maintaining its compatibility with existing JavaScript code.

TypeScript provides a way for developers to write more reliable and maintainable code by catching errors at compile-time rather than at runtime. It also includes advanced features such as interfaces, enums, and decorators that are not available in traditional JavaScript.

If statement in Typescript
```typescript {type:code, action: run}
let num: number = 10;

if (num > 0) {
  console.log("The number is positive.");
}

```

4. Python

Python is a high-level, interpreted programming language that is known for its simplicity, readability, and flexibility. 

Python is an object-oriented language that supports a variety of programming paradigms, including structured programming, functional programming, and procedural programming. 

Python is commonly used for a variety of applications, including scientific computing, artificial intelligence, data analysis, and more.

If statement in Python
```python {type:code, action: run}
x = 5

if x > 0:
    print("x is positive.")
```
5. PHP

PHP is a widely-used language that is supported by most web servers and is commonly used with popular web frameworks such as Laravel, Symfony, and CodeIgniter. It is known for its ease of use and flexibility, as well as its compatibility with a variety of databases such as MySQL, PostgreSQL, and MongoDB.

PHP code is executed on the server-side, which means that it is processed on the web server before being sent to the client's browser. This allows PHP to generate dynamic content, such as HTML pages, in real-time based on user input and database queries.

If statement in PHP
```php {type:code, action: run}
<?php
$number = 10;

if ($number > 5) {
    echo "The number is greater than 5.";
}
?>
```

6. Swift

Swift is a compiled programming language developed by Apple that is designed for developing applications for Apple's platforms, including macOS, iOS, watchOS, and tvOS. It was first introduced in 2014 as a replacement for Objective-C, which was previously used for iOS and macOS development.

If statement in Swift
```swift {type:code, action: run}
let number = 10

if number > 0 {
    print("The number is positive")
}
```

7. Java

Java is a high-level, object-oriented programming language that is designed to be portable and platform-independent. It was first released in 1995 by Sun Microsystems and has since become one of the most popular programming languages in use today.

Java is known for its security, reliability, and scalability. It is commonly used for building large-scale applications, such as enterprise-level software, and web applications. Java is also used for developing Android mobile applications.

Java code is compiled into bytecode, which can be executed on any platform that has a Java Virtual Machine (JVM) installed. This allows Java programs to run on a wide range of operating systems, including Windows, macOS, Linux, and more.

If statement in Java
```java {type:code, action: run}
int number = 10;

if (number > 0) {
    System.out.println("The number is positive.");
}
```

8. Kotlin

Kotlin is a modern, statically-typed programming language that runs on the Java Virtual Machine (JVM) and is designed to be interoperable with Java.

Kotlin is also fully interoperable with Java, which means that developers can use both languages within the same project.

Kotlin has become increasingly popular among Android developers, as it offers many advantages over Java, such as improved readability, faster development times, and better performance. 

If statement in Kotlin
```kotlin {type:code, action: run}
val number = 10

if (number > 0) {
        println("The number is positive.")
}
```

9. C/C++

C and C++ are programming languages that are widely used for system-level programming, operating systems, game development, and embedded systems.

C was developed in the early 1970s by Dennis Ritchie at Bell Labs and is a procedural, low-level programming language. It is known for its efficiency, portability, and direct access to system hardware. 

C++ is an object-oriented programming language that was developed in the 1980s as an extension of C. It includes features such as classes, inheritance, and polymorphism, which make it easier to write complex programs.

C++ is commonly used for developing large-scale applications, such as video games and operating systems.

Many high-level programming language interpreters, including but not limited to Dart, Java, Python, JavaScript, and Go, are written in C and C++.

Both C and C++ are compiled languages, which means that the code is compiled into machine code before execution. 

If statement in C
```c {type:code, action: run}
int number = 10;

if (number > 0) {
    printf("The number is positive.\n");
}
```

If statement in C++
```cpp {type:code, action: run}
int number = 10;

if (number > 0) {
    std::cout << "The number is positive." << std::endl;
}
```

10. Objective C

Objective-C is an object-oriented programming language that is primarily used on Apple's platforms, including macOS, iOS, and watchOS. 

Objective-C is an extension of the C programming language and adds object-oriented features such as classes, methods, and message passing. It uses a syntax that is similar to C, but also includes Smalltalk-style syntax for object-oriented constructs.

If statement in Objective-C

```objective-c {type:code, action: run}
int number = 10;

if (number > 5) {
    NSLog(@"The number is greater than 5.");
}

```

11. Go

Go, also known as Golang, is an open-source programming language developed by Google. It is a statically-typed language with a syntax similar to that of C. Go is designed to be simple to write, read, and maintain, while still being powerful enough to handle complex applications. Go is also known for its fast compilation times and efficient execution, which make it well-suited for building high-performance applications.

Go is commonly used for building server-side applications, network services, and command-line tools. It is also used for building microservices and cloud-native applications. Many popular projects, such as Kubernetes, Docker, and Terraform, are written in Go.

If statement in Golang
```go {type:code, action: run}
age := 20

if age >= 18 {
    fmt.Println("You are an adult.")
}
```

12. React framework (Typescript)

React, also known as React.js, is an open-source JavaScript/Typescript library that is used for building user interfaces. 

React is commonly used for building single-page applications, progressive web applications, and mobile applications. It is also used by many popular websites and web applications, such as Netflix, Airbnb, and Instagram.

If statement with React/Typescript
```react {type:code, action: run}
import React, { useState, useEffect } from "react";

function App() {
  const [count, setCount] = useState(0);

   function checkAge() {
    let message: string = "You are an adult";
    let age: number = 25;
   

    if (age >= 18) {
       return console.log(message);
    }
   }
  
  useEffect(() => {
    checkAge()
    let timer = setInterval(() => {
      setCount((count) => count + 1);
    }, 1000);

    return () => clearInterval(timer);
  }, []);

  return (
    <>
      <h1>{count} times!</h1>
      <style jsx>{`
        h1 {
          color: red;
        }
      `}
      </style>
    </>
  );
}

export default App;
```

13. Flutter framework (dart)

Flutter uses the Dart programming language and includes a set of pre-built widgets, which make it easier to build custom user interfaces. It also includes a "hot reload" feature, which allows developers to see changes in their code immediately without having to rebuild the entire application.

Flutter is known for its fast development times, high-performance, and ability to create beautiful, highly-customizable user interfaces. It includes features such as reactive programming, which allows developers to build applications that respond to user input in real-time.

Flutter is commonly used for building mobile applications, including games, social media apps, e-commerce apps, and more. It is also used for building web applications and desktop applications using the Flutter for Web and Flutter for Desktop frameworks.

If statement with Flutter/Dart
```flutter {type:code, action: run}

import 'package:flutter/material.dart';

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    bool isLoggedIn = true;

    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text('If statement in flutter'),
        ),
        body: Center(
          child: if (isLoggedIn) {
            Text('Welcome, user!');
          } 
        ),
      ),
    );
  }
}

void main() {
  runApp(MyApp());
}

``` 

#### Summary:

Now that we have covered the concept of "if" statement in different languages, let's make a quick summary of what we have learned in this unit.

1. If we want to learn a new coding language, we just need to know the name and then ask AI how to write if statement program for it.

We also provided some AI prompts for other popular coding languages that were not mentioned in this unit:

```yml-list {default: true}
- Can you write an if statement program in Ruby?
- Can you write an if statement program in Rust?
- Can you write an if statement program in Perl?
- Can you write an if statement program in Lua?
- Can you write an if statement program in Bash?
```

You don't need to remember all of them, just the word "if" statement is enough, as we can ask AI for the exact code and how to use it at any time.

We also provided some AI prompt samples for how to write "if" statement in a specific language:

```yml-list {default: true}
- How can I write an if statement in JavaScript?
- How can I write an if statement in Dart?
- How can I write an if statement in Python?
```

3. We have learned about some coding languages and frameworks. Let's list all of them here:

```
Dart
JavaScript
TypeScript
Python
PHP
Swift
Java
Kotlin
C
C++
Objective-C
Go
React framework
```

Again, you don't need to remember all of these names. Just having a general impression is enough, as we will talk and learn about them every day from now on.

Now, let's do an online interactive practice by following the URL:
[https://juniorit.ai/resource/course/hello-world-in-different-coding-language-practice](https://juniorit.ai/resource/course/hello-world-in-different-coding-language-practice)