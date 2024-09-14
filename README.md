# Lab 5.0.9

**Learning Objectives**

- Understand the concept and importance of String methods in Java development.
- Learn how to implement common String methods in Java.
- Explore practical applications of String methods in real-world Java projects.
- Identify common pitfalls and best practices when working with String methods.
- Gain hands-on experience with a complete Java example that demonstrates various String methods.

**Prerequisites**

- Basic understanding of Java programming.
- Familiarity with variable declaration and basic data types in Java.

**What You'll Achieve**

- Develop a solid understanding of String methods in Java.
- Implement practical examples that can be applied in real-world scenarios.
- Enhance your skills in string manipulation and text processing.

**Assignment Details**

1. Open the provided `StringMethodsExplorer.java` file in your preferred Java development environment.
2. In the `main` method, you'll find a String variable named `originalString` with the value "Hello, World!".
3. Implement the following String methods to manipulate and analyze the originalString:
   - Use `length()` to print the length of the string.
   - Use `toUpperCase()` to convert the string to uppercase and print the result.
   - Use `toLowerCase()` to convert the string to lowercase and print the result.
   - Use `charAt()` to print the character at index 7.
   - Use `substring()` to extract and print the substring "World".
   - Use `contains()` to check if the string contains "Hello" and print the result.
   - Use `replace()` to replace "World" with your name and print the result.
4. You'll find another String variable named `stringWithSpaces` with the value "   Java Programming   " (with leading and trailing spaces).
5. Use the `trim()` method to remove the leading and trailing spaces from `stringWithSpaces`, and print the result.
6. Use the `split()` method to split the original "Hello, World!" string into an array of words, and print each word on a new line.

**Example Output**

```
Original string: Hello, World!
Length: 13
Uppercase: HELLO, WORLD!
Lowercase: hello, world!
Character at index 7: W
Substring: World
Contains "Hello": true
Replaced: Hello, Alice!

Original string with spaces:    Java Programming   
Trimmed string: Java Programming

Split string:
Hello,
World!
```

**Starter Code**

The `StringMethodsExplorer.java` file contains the following starter code:

```java
package academy.javapro.lab;

public class StringMethodsExplorer {
    public static void main(String[] args) {
        String originalString = "Hello, World!";
        String stringWithSpaces = "   Java Programming   ";
    }
}

```

**Hints**

- Remember that String methods in Java do not modify the original string. They return a new string with the changes applied.
- When using `charAt()`, remember that string indices start at 0.
- For the `substring()` method, you'll need to provide the start and end indices. The end index is exclusive.
- When using `split()`, consider what character you want to split on (in this case, the space character).

**Submission Instructions**

1. Fork the repository
2. Clone your fork
3. Navigate into the repository
4. Implement the required loops in the main method
5. Test your implementation with various inputs
6. Git add, commit, and push to your fork
7. Submit a pull request
    - Set the title of the pull request to your first name and last name
    - In the comment, briefly explain your implementation approach and any challenges you faced

Remember, the goal is to learn and have fun! Don't hesitate to ask for help if you get stuck.