# **_Functions_ in Programming**

![functions image](https://www.sentinelone.com/wp-content/uploads/2019/10/23130933/A_cloud_with_the_word_function_signifying_google_cloud_functions.png)

## Objectives:

- To Compare the common features and differences in function syntax among the following languages: JavaScript, TypeScript, Dart, PHP, Java, Kotlin, C, C++, Objective-C, Swift, and Golang.
- Information about function syntax, parameters, reference/value parameters, return values, and other relevant details.
- Learn the use of functions using a real world example

## Contents :

1. [What are functions](#what-are-functions)
2. [JavaScript](#javascript)
3. [Typecript](#typescript)
4. [Dart](#dart)
5. [PHP](#php)
6. [Java](#java)
7. [Kotlin](#kotlin)
8. [C, C++, Objective C](#c-c-objective-c)
9. [Swift](#swift)
10. [Golang](#golang)

## **What are functions ?**

- In programming, functions can be thought of as self-contained units of code that perform _specific tasks_ or _operations_. They are like _mini-programs_ within a larger program, designed to carry out a particular function or set of operations.

- Imagine a function as a specialized worker or a machine that you can call upon whenever you need a specific job done. You provide the function with some input (if required), it performs a series of instructions or computations, and then it produces an output (if necessary) that you can use or further process.

- When using functions, you typically define them with a name and specify any inputs **_(known as parameters or arguments)_** they require. These inputs can be values, variables, or even other functions. Within the function, you write the instructions or algorithms necessary to perform the desired operations. This can involve calculations, data manipulation, conditionals (if-else statements), loops, and more.

- Once the function is defined, you can **_"call"_** or **_"invoke"_** it from different parts of your program. This means you can trigger the function to run and provide the necessary inputs. The function then executes its instructions, processes the data, and potentially produces an output. The output can be a value, a modified variable, or even a new data structure.

> **Tip :** By using functions, you can avoid repeating the same code multiple times. Instead, you write the code once inside a function and reuse it whenever needed. This saves time and effort, promotes code efficiency, and reduces the chances of errors or inconsistencies.

## Functions syntax in different languages :

When it comes to programming languages, functions play a crucial role in organizing and structuring code. In this blog post, we'll explore the common features and differences in function syntax among several popular languages, including **_JavaScript, TypeScript, Dart, PHP, Java, Kotlin, C, C++, Objective-C, Swift, and Golang_**. We'll also demonstrate the use of functions in a real-world problem for each language.

### **JavaScript**

In **_JavaScript_**, functions can be declared using the _function_ keyword followed by the function name and parameters. Let's consider a real-world problem of calculating the average of an array of numbers in JavaScript:

**_Javascript_**

```js
function calculateAverage(numbers) {
  let sum = 0;
  for (let i = 0; i < numbers.length; i++) {
    sum += numbers[i];
  }
  return sum / numbers.length;
}
```

### **TypeScript**

TypeScript, being a superset of JavaScript, offers similar function syntax. However, it adds the ability to specify the return type. Let's solve the same average calculation problem in

**_TypeScript_**:

```ts
function calculateAverage(numbers: number[]): number {
  let sum = 0;
  for (let i = 0; i < numbers.length; i++) {
    sum += numbers[i];
  }
  return sum / numbers.length;
}
```

### **Dart**

In Dart, functions are declared with the return type followed by the function name and parameters. Let's calculate the average of an array of numbers in Dart:

**_Dart_**:

```dart
double calculateAverage(List<int> numbers) {
  double sum = 0;
  for (int i = 0; i < numbers.length; i++) {
    sum += numbers[i];
  }
  return sum / numbers.length;
}

```

### **PHP**

PHP functions are declared using the function keyword, followed by the function name and parameters. Let's find the average of an array of numbers in PHP:

**_PHP_**:

```php
function calculateAverage($numbers) {
  $sum = 0;
  foreach ($numbers as $number) {
    $sum += $number;
  }
  return $sum / count($numbers);
}
```

### **Java**

In Java, functions are declared with the return type, followed by the function name and parameters. Let's solve the average calculation problem in Java:

**_Java_**:

```java
public static double calculateAverage(int[] numbers) {
  double sum = 0;
  for (int number : numbers) {
    sum += number;
  }
  return sum / numbers.length;
}
```

### **Kotlin**

Kotlin offers a concise syntax for function declaration, with the fun keyword followed by the function name and parameters. Let's calculate the average of an array of numbers in Kotlin:

**_Kotlin_**:

```kotlin

fun calculateAverage(numbers: IntArray): Double {
  var sum = 0.0
  for (number in numbers) {
    sum += number
  }
  return sum / numbers.size
}
```

### **C, C++, Objective-C**

In C, C++, and Objective-C, functions are declared with the return type, followed by the function name and parameters. Let's find the average of an array of numbers in C:

**C, C++, Objective-C**:

```c
double calculateAverage(int numbers[], int size) {
  int sum = 0;
  for (int i = 0; i < size; i++) {
    sum += numbers[i];
  }
  return (double)sum / size;
}
```

### **Swift**

In Swift, functions are declared using the func keyword, followed by the function name and parameters. Let's solve the average calculation problem in Swift:

**Swift**:

```swift
func calculateAverage(numbers: [Int]) -> Double {
  var sum = 0
  for number in numbers {
    sum += number
  }
  return Double(sum) / Double(numbers.count)
}

```

### **Golang**

In Golang, functions are declared with the func keyword, followed by the function name, parameters, and return type. Let's calculate the average of an array of numbers in Golang

**Golang**:

```golang
func calculateAverage(numbers []int) float64 {
  sum := 0
  for _, number := range numbers {
    sum += number
  }
  return float64(sum) / float64(len(numbers))
}


```

---

_This comparison gives you an overview of the common features and differences in function syntax among several programming languages. Functions are versatile and enable you to solve a wide range of real-world problems efficiently. Whether you're calculating averages, processing data, or building complex algorithms, functions are the building blocks that help you organize and structure your code effectively._
