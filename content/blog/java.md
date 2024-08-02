+++
title = "Java - Introduction"
date = 2020-01-25

[taxonomies]
categories = [ "java" ]

[extra]
author = "Thomas Wehmöller"
cover = "/img/java.jpg"
excerpt = "Java is a object oriented programming language that is widely adopted in the industry..."
+++

### What is Java ?

Java is a **object oriented** programming language that is widely adopted in the industry. Unlike other Programming languages like C, Java uses a so called **garbage collector** for memory management. This means that you cannot directly access adresses like in C++ with Pointers. The Syntax of Java is very similar to C++. Additionally Java doesn't compile down to machine code but to so called **bytecode** that you can recognize by the **.class** ending. This Bytecode can then be executed by the **JVM**(Java Virtual Machine). If you haven't understood everything above, that is no problem everything will make more sense when you actually use java. But if you are curious about the different topics feel free to google it.

### Hello World

When learning a new Programming Language it is tradition to write a first programm wich prints out **Hello World** to the terminal. So that is what we will be doing next.

```java
public class FirstProgram {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```

Now i will go through this Code step by step and explain every bit of it. In the first line we say `public class FirstProgram` which means that we have a public object of the name FirstProgram. **Public** means that you can access this class from everywhere, but that is not important now. Remember that Java is object oriented ? Great, so we have to write every Code we have inside so called **classes**. Let me make a short analogy to make things clearer. A Class is similar to a toolbox. You can have a toolbox of wood-tools where you have maybe a bunch of different saws. In Java you would now write `public class WoodTools`, but what if i now actually want to saw ? Now we get to the next line in our code, `public static void main(String[] args)`. This is a so called method where we can make complex calculations or well print "Hello World". As before public handles the access and `static` declares that there is only one instance of our main program, if you dont exactly understand static that is for now no problem just remember to write it before youre main method. The next keyword is `void` this is the **return type** of our method, so in this case we have no return value. The name `main` declares that this is where all the logic is executed. For now we will skip the `String[] args` part and look at our final line. `System.out.println("Hello World")` this is the only line that is executed in our program and really is self explanatory, we print the line "Hello World" to our terminal.

### Using IntelliJ to Compile our Code

There are many IDE that you can use to compile your Java Code and execute it, but in my opinion IntelliJ is the best one out there at the moment. IntelliJ is free and open source and can be installed on all the major platforms. For a basic overview on how to use IntelliJ, i suggest watching the following video.

<br>
<iframe width="560" height="315" src="https://www.youtube.com/embed/c0efB_CKOYo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>

### Summary

#### Java

- object oriented
- uses a garbage collector
- compiles down to bytecode, .class ending
  - can be executed by JVM

#### Hello World

- Public: Handles Access
- Objects are called classes
- static: only one instance in the whole program
- void: return type, nothing is returned
- `System.out.println()`: prints to the terminal