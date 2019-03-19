<html>
<h1>LO2:Programming Fundamentals</h1>
<h3><b>LO 2: Understand the fundamental set of instructions involved in all programs and how to use them to construct programs to solve problems</b>
</h3><hr/> 
<section class="toggle">
<b>1. What is Java and state the function of the compiler and the interpreter in the Java programming language </b>
<div class="toggle-content">
<p>Java is a high-level programming language originally developed by Sun Microsystems and released in 1995. Java runs on a variety of platforms, such as Windows, Mac OS, and the various versions of UNIX.
Java is compiled to an intermediate "byte code" at compilation time. This is in contrast to a language like C that is compiled to machine language at compilation time. The Java byte code cannot be directly executed on hardware the way that compiled C code can. 
Instead the byte code must be interpreted by the JVM (Java Virtual Machine) at runtime in order to be executed. </p>
</div>
</section>
<section class="toggle">
<b>2. Explain the concept of 'platform independence' and/or architectural neutrality .What are the supported platforms by Java Programming Language?</b>
<div class="toggle-content">
<p>Java  is said to be platform independent or architectural neutral as a Java program do not depend
 upon the operating system or hardware it is running on.
Java runs on a variety of platforms, such as Windows, Mac OS, and the various versions of UNIX/Linux like HP-Unix, Sun Solaris, Redhat Linux, Ubuntu, CentOS, etc.</p>
</div>
</section>
<section class="toggle">
<b> 3. Define what is meant by the term 'computer program'  List any five features of a Java Program?</b>
<div class="toggle-content">
<p>A computer program is a collection of instructions[1] that performs a specific task when executed by a computer. A computer requires programs to function,
 and typically executes the program's instructions in a central processing unit.
Some features include Object Oriented, Platform Independent, Robust, Interpreted, Multi-threaded</p>
</div>
</section>

<section class="toggle">
<b>4. What is the  Java Virtual Machine. Define JRE i.e. Java Runtime Environment </b>
<div class="toggle-content">
<p>When Java is compiled, it is not compiled into platform specific machine, rather into platform independent byte code. This byte code is distributed over the web and interpreted by virtual Machine (JVM) on whichever platform it is being run.
Java Runtime Environment is an implementation of the Java Virtual Machine which executes Java programs. It provides the minimum requirements for executing a Java application.</p> 
</div>
</section>
<section class="toggle">
<b>5. Define what is meant by the term 'software design' </b>
<div class="toggle-content">
<p>Software design is the process of defining software methods, functions, objects, and the overall structure and interaction of your code so that the resulting
 functionality will satisfy your users requirements.</p>
</div>
</section>
<section class="toggle">
<b>6. State the purpose of a program algorithm </b>
<div class="toggle-content">
<p>Think of an algorithm as a recipe that describes the exact steps needed to solve a problem or reach a goal
A programming algorithm describes how to do something, and your computer will do it exactly that way every time. (Well, it will once you convert your algorithm into a language it understands!)
A programming algorithm is not computer code. It's written in simple English.
</p>
</div>
</section>
<section class="toggle">
<b>7. Differentiate between the syntax and semantics of an object programming language. </b>
<div class="toggle-content">
<p> Syntax is the required grammar and punctuation of the language ie,Compile-time errors are syntax errors.
   Semantics is all about meaning,what the statements do, what the programs do ie,
   Logic errors are semantic errors
</p>
</div>
</section>

<section class="toggle">
<b>8. Distinguish between user generated source code and object/machine code. What is the extension name of a Java source code file?</b>
<div class="toggle-content">
<p>Source Code is the High Level Language that you have written or written by the programmer. 
The program that is submitted to the Compiler.  The source code is often transformed by a 
compiler program into low-level machine code understood by the computer.
 The machine code might then be stored for execution at a later time. The extension is .java</p> 
</div>
</section>
<hr/> 

<h1>LO3:Object Oriented Concepts</h1>
<h3><b>LO 3: Demonstrate a knowledge of basic OOP constructs</b> </h3>
<hr/>
<section class="toggle">
<b>9. Define what is meant by the term 'object oriented programming'. What is the difference between object oriented programming language and object based programming</b>
<div class="toggle-content">
<p>Object-oriented programming (OOP) is a programming language model organized around objects rather than "actions" and data rather than logic. Historically, a program has been viewed as a logical procedure that takes input data, 
processes it, and produces output data.
Object based programming languages follow all the features of OOPs except Inheritance. JavaScript is an example of object based programming languages.
</p> 
</div>
</section>
<section class="toggle">
<b>10. Explain the rationale behind object design.</b>
<div class="toggle-content">
<p>Object is a runtime entity and it's  state is stored in fields and behaviour is shown via methods. Methods operate on an object's internal state and serve as the primary mechanism for object-to-object communication.</p> 
</div>
</section>

<section class="toggle">
<b>11. Define a class as a blueprint for an object </b>
<div class="toggle-content">
<p>A class is a blue print from which individual objects are created. A class can contain fields and methods to describe the behaviour of an object.</p>
</div>
</section>
<section class="toggle">
<b>12. State the purpose of class libraries and packages </b>
<div class="toggle-content">
<p>Packages are used in Java in-order to prevent naming conflicts, to control access, to make searching/locating and usage of classes, 
interfaces, enumerations and annotations, etc., easier.A class declared as private cannot be accessed outside it's package.
</p>
</div>
</section>

<section class="toggle">
<b>13. Which method can be defined only once in a program? What is the return type of a method that does not returns any value?
What's the difference between constructors and other methods?</b>
<div class="toggle-content">
<p> main() method can be defined only once in a program. Program execution begins from the main() method by java’s run time system.
Void. Return type of an method must be made void if it is not returning any value.
Constructors must have the same name as the class and can not return a value. They are only called once while regular methods could be called many times.</p> 
</div>
</section>
<section class="toggle">
<b>14. Where import statement is used in a Java program? Is there any need to import java.lang package?</b>
<div class="toggle-content">
<p>Import statement is allowed at the beginning of the program file after package statement.
No, there is no need to import this package. It is by default loaded internally by the JVM.</p> 
</div>
</section>

<section class="toggle">
<bl>15. What is dot operator? List the three steps for creating an Object for a class</b>
<div class="toggle-content">
<p>The dot operator(.) is used to access the instance variables and methods of class objects.It is also used to access classes and sub-packages from a package.
An Object is first declared, then instantiated and then it is initialized.</p> 
</div>
</section>

<section class="toggle">
<b>16. What kind of variables a class can consist of? Describe these.</b>
<div class="toggle-content">
<p>A class consist of Local variable, instance variables and class variables.
Variables defined inside methods, constructors or blocks are called local variables. The variable will be declared and initialized within the method and it will be destroyed when the method has completed.
Instance variables are variables within a class but outside any method. These variables are instantiated when the class is loaded.
Class  variables are declared with in a class, outside any method, with the static keyword.</p> 
</div>
</section>

<section class="toggle">
<b>17. What is a  Constructor? Explain the usage of this() with constructors? 
What is the purpose of default constructor?</b>
<div class="toggle-content">
<p>Constructor gets invoked when a new object is created. Every class has a constructor. If we do not explicitly write a constructor for a class the java compiler builds a default constructor for that class.
It is used with variables or methods and used to call constructor of same class.
The Java compiler creates a default constructor only if there is no constructor in the class.
</p>
</div>
</section>

<section class="toggle">
<b>18. Define Inheritance? When super keyword is used?</b>
<div class="toggle-content">
<p>It is the process where one object acquires the properties of another. With the use of inheritance the information is made manageable in a hierarchical order.
If the method overrides one of its superclass's methods, overridden method can be invoked through the use of the keyword super. It can be also used to refer to a hidden field.</p>
</div>
</section>

<section class="toggle">
<b>19. What is Abstraction?</b>
<div class="toggle-content">
<p>It refers to the ability to make a class abstract in OOP. It helps to reduce the complexity and also improves the maintainability of the system.</p>
</div>
</section>

<section class="toggle">
<b>20. What is Encapsulation? What is the primary benefit of Encapsulation?
 If a variable is declared as private, where may the variable be accessed?</b>
<div class="toggle-content">
<p>It is the technique of making the fields in a class private and providing access to the fields via public methods. If a field is declared private, it cannot be accessed by anyone outside the class, thereby hiding the fields within the class. Therefore encapsulation is also referred to as data hiding.
The main benefit of encapsulation is the ability to modify our implemented code without breaking the code of others who use our code. With this Encapsulation gives maintainability, flexibility and extensibility to our code.
A private variable may only be accessed within the class in which it is declared.</p>
</div>
</section>

<section class="toggle">
<b>21. Explain the following line used under Java Program &minus;
<p>public static void main (String args[ ])</p></b>
<div class="toggle-content">
<p>The following shows the explanation individually &minus;</p>
<ul class="list">
<li><p>public &minus; it is the access specifier.</p></li>
<li><p>static &minus; it allows main() to be called without instantiating a particular instance of a class.</p></li>
<li><p>void &minus; it affirns the compiler that no value is returned by main().</p></li>
<li><p>main() &minus; this method is called at the beginning of a Java program.</p></li>
<li><p>String args[ ] &minus; args parameter is an instance array of class String</p></li>
</ul>
</div>
</section>

		


</html>
