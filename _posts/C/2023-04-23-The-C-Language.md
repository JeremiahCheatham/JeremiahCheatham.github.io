---
type: post
title: The C Programming Language
categories: [C, Introduction to C]
page: 1
---
## Introduction to C

![Desktop View](/posts/20230423/C-logo2.png){: .w-50 .left}
The C language was created by Dennis Ritche at Bell Labs for use with the Unix operating system. The Unix kernel was rewritten in C. Today every major commerical and open source operating systems kernel is written primarily in C. This list includes Windows, OSX, Linux, Android, IOS, BSD, Playstation, Xbox, Nintendo, Smart TVs, Smart Speakers, Smart Watches and many more.

C is a strongly typed, low-level, imperitive language. This means that variables are explicitly given a datatype when declared. Being low-level C has direct access to memory and system resources. C programs exectute code imparitively as a sequence statements.

C programs are compiled to machine code and executed directly by the CPU, which makes it a very fast and efficient language. C is often used as a benchmark for other languages, as it sets the standard for speed of execution. Other languages being 1 to 100 times slower than C is a common.

C lacks many features of modern languages such as Object Orientated Programming. Lacking classes makes larger or more complex structured code harder to manage, understand or debug. C is also missing a string type and instead uses null terminated character arrays. This makes working with strings very clums and difficult.

C is not type safe, meaning it does not check a variable is used correctly for it's type. It also doesn't do bounds checking on allocated memory or arrays. C allows direct access to memmory though pointers and has no garbage collector, for freeing memory allocated on the heap. C instead leaves this up to manually manage memory allocation and deallocation in order to avoid memory leaks and other errors.

> Dennis Ritchie originally created the B language as a simplified version of the BCPL language for the Multics operating system. He later created a successor to B with additional features and improvements called New B or NB, which was later changed to C.
{: .prompt-info }

## Pros of the C Language

- Super-fast execution time compared to most programming languages.
- Efficient and compact code, with low memory usage.
- Compiled to machine code that runs directly on the CPU.
- Procedure programming language, statments are executed in sequence.
- Easy to learn with a small number of reserved keywords and constructs.
- Simple and straightforward syntax.
- Direct hardware access and memory management through pointers.
- Middle-level language that combines high-level and low-level features.
- Widely used in system programming, embedded systems, and other low-level applications.
- Mature language with a large community and ecosystem of libraries and tools.

## Cons of the C Language

- Lacks modern features such as Object-Oriented Programming and automatic memory management.
- Not type-safe, it does not check whether a variable is used correctly for its type.
- No built-in support for handling strings, requiring the use of character arrays instead.
- Limited standard library compared to other languages.
- No built-in support for exception handling.
- Pointers can be difficult to work with and require careful management to avoid memory leaks and other errors.
- Can be more verbose and require more manual memory management than higher-level languages.
- A steeper learning curve than some other languages, due to its low-level nature and lack of modern features.
- Multi-threading can be more difficult to implement compared to languages.
- Debugging can be more challenging compared to more modern languages.
