What are the four principles of OOP?
1. Encapsulation = the mechanism of hiding data implementation by restricting access to public methods.
   Instance variables are kept private and accessor methods are made public to achieve this. 
   This keeps the declared variables encapsulated inside the method and can not be reached by any other
   classes.
   
2. Abstraction = its like encapsulation because it hides certain properties and methods from the outside
   code to make the interface of the objects simpler.
   
3. Inheritance = extends the functionality of existing classes to eliminate repetitive code. By defining the methods and 
   properties in one generic main object and then all objects that follow it are subclasses. The
   generic main object is the super class.
   
4. Polymorphism = means many forms or shapes. it refers to the ability of an interface or an abstract class
   to take many forms via its implemented derived classes.Example, a Cat interface or class will have multiple 
   derived classes like lion, cheetah, and/or tiger. The cat interface would have a method
   called scream and that method would print a cat specific scream for each of the derived classes as long as 
   the interface is implemented.
   
What information is captured in a class?
   A Java class may contain a mix of data (variables) and actions (methods). Grouping variables and operations
   on these variables into Java classes makes it easier to structure.
   
What is JDK?
   Java Development Kit allows developers to create Java programs that can be executed and ran 
   by the JVM and JRE.
   
What is JRE?
   Java Runtime Environment creates the JVM and ensures dependencies are available to your Java
   project.
   
What is JVM?
   Java Virtual Machine a engine that manages system memory and provides a portable execution environment for
   Java-based applications.
   
What are some differences between Junit4 and Junit5?
   JUnit4 has everything bundled into a single jar file while JUnit5 is composed of three subprojects
   JUnit Platform, JUnit Jupiter and JUnit Vintage.
   JUnit4 requires Java 5 or higher.
   JUnit5 requires Java 8 or higher.
   JUnit4 has no integration support for third party plugins and IDE's.
   JUnit5 has a dedicated sub-project for this purpose-JUnit Platform. It defines the 
   TestEngine API for developing a testing framework that runs on the platform.
