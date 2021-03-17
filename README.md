<p align="center"><img src="https://user-images.githubusercontent.com/34022590/111512760-c3654d80-8758-11eb-99a6-982af6fa9e9c.png" width="150px"></p>

<h1 align="center">
    <strong>Java</strong>
</h1>
<h3 align="center">
    <p>Java Programming Language</p>
</h3>

## Contents
- [About Java](#about-java)
- [Installing Java](#installing-java)
- [Running Java Code](#running-java-code)
- [About Java](#about-java)
- [Java IDEs](#java-ides)
- [Java in VSCode](#java-in-vscode)
- [Variables](#variables)

## About Java
* Author    - Java was developed by James Gosling in 1995
* Originally it was called 'Oak' after oak three
* Name 'Java' came from Java coffee
* That's why Java logo looks like coffee cup

There are 4 types of java:
* Standard Edition (SE)   - Core Java platform
* Enterprise Edition (EE) - For very large scale systems with extra libraries
* Micro Edition (ME)      - For mobile devices
* Java Card               - For smart cards

## Installing Java
https://www.java.com/en/

1. Download and install Java JDK (Java Development Kit)
* Java JDK  - https://www.oracle.com/java/technologies/javase-downloads.html

## Running Java code
javac   - Java compiler\
.java is java class extension. For example 'Hello.java'\
To compile this class to bytecode type in Terminal
```
javac Hello.java
```
This will create 'Hello.class'
To run the cod writ on the Terminal
```
jaba Hello
```

## Java IDEs
* Eclipse         - https://www.eclipse.org/ide/
A dedicated Java IDE, Eclipse gets listed as one of the big three of Java IDEs. The modern integrated development environment is available in both desktop and cloud editions. The cloud edition of the Eclipse, named Eclipse Che, allows programmers to develop apps via a web browser.
Both editions of the Eclipse IDE equips with required/additional functionality utilizing plugins. There is an array of plugins available for the IDE on the Eclipse Marketplace. To facilitate the incremental compilation of Java code, Eclipse comes with a custom compiler.
For Java programmers looking to develop specific functionality for Eclipse, a PDE (Plugin Development Environment) is available. To help Java developers hasten the application development, Eclipse flaunts powerful tools for charting, modelling, reporting, and testing.
Eclipse supports application development in several programming languages via plugins. C, C++, Clojure, Groovy, Haskell, JavaScript, Julia, Perl, PHP, Ruby, Rust, and Scala are some of the various programming languages supported by Eclipse.

* NetBeans        - https://netbeans.apache.org/download/index.html
Another name in the big three of Java IDEs is NetBeans. It is also free java ide. NetBeans is the official IDE for Java 8. The open-source IDE facilitates Java programmers to build desktop, mobile, and web applications by offering a range of potent tools and features.
In addition to being available for a variety of platforms, NetBeans also comes in a feature-limited OS-independent version. Each novel version of the NetBeans boasts an improved and reworked Java editor.
By highlighting Java code syntactically and semantically, it makes it easier for Java programmers to build custom software apps. Inbuilt tools in NetBeans makes it possible to refactor the code as well as writing bug-free code.
To design and develop GUIs for Java SE, a GUI Builder is put on offer by NetBeans. The dedicated Java IDE is available in 28 different languages. NetBeans has extensions available for working in C, C++, HTML5, JavaScript, PHP, and other programming languages.

* IntelliJ IDEA   - https://www.jetbrains.com/idea/
IntelliJ IDEA is one of the big three of Java IDEs. It is available in 2 different editions, an Apache 2 Licensed community edition, and a proprietary commercial edition. To allow developers to dive deeper into the Java code, IntelliJ IDEA boasts cross-language refactoring and data flow analysis features.
Other features offered by IntelliJ IDEA that eases the life of a Java developer are chain completion, language injection, smart completion, and static member completion.
In addition to supporting Java and a galore of Java frameworks, IntelliJ IDEA also provides support for other JVM-based programming languages, such as Kotlin.

## Java in VSCode
https://code.visualstudio.com/docs/languages/java

1. Download and install Java Coding Pack: https://aka.ms/vscode-java-installer-win
2. If you are an existing VS Code user, you can also add Java support by installing Java Extension Pack:\
https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack \
which includes these extensions:
*    Language Support for Java(TM) by Red Hat
*    Debugger for Java
*    Java Test Runner
*    Maven for Java
*    Project Manager for Java

3. Create file 'Hello.java', add public class with main function and following code
```
public class Hello {

    public static void main(String[] args) {
        System.out.println("Hello World!");
    }
}
```

4. Run the code and in Terminal will display
```
Hello World!
```

## Variables

* String - stores text, such as "Hello". String values are surrounded by double quotes
* int - stores integers (whole numbers), without decimals, such as 123 or -123
* float - stores floating point numbers, with decimals, such as 19.99 or -19.99
* char - stores single characters, such as 'a' or 'B'. Char values are surrounded by single quotes
* boolean - stores values with two states: true or false

