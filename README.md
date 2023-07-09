# list-of-design-patterns-

Certainly! Here's a list of design patterns commonly used in Java applications, along with brief examples of each:
1. Singleton Pattern: - Example: Java's `java.lang.Runtime` class, which represents the runtime environment of the Java application, follows the Singleton pattern.
2. Factory Pattern:    - Example: `java.util.Calendar`, which provides methods to create instances of `java.util.Date` based on different parameters, is an implementation of the Factory pattern.
4. Builder Pattern: - Example: `StringBuilder` in Java provides a builder-like approach to create and manipulate strings efficiently.
5. Prototype Pattern:  - Example: `java.lang.Object#clone()` method, which creates a copy of an object, is an implementation of the Prototype pattern.
9. Strategy Pattern:- Example: `java.util.Comparator` interface in Java is an example of the Strategy pattern. It allows multiple algorithms for comparing objects to be implemented.
12. Iterator Pattern:  Example: The `java.util.Iterator` interface in Java's standard library is an implementation of the Iterator pattern, allowing traversal of collections.
15. DAO (Data Access Object) Pattern: - Example: In Java's Spring Framework, the `org.springframework.jdbc.core.JdbcTemplate` class provides a data access object for interacting with databases.
11. Composite Pattern:    - Example: The `java.awt.Container` class, which represents a component that can contain other components, follows the Composite pattern.
                        •	Spring provides composite annotations like @RestController and @RequestMapping, which simplify the creation of RESTful APIs by composing smaller handler methods.


3. Abstract Factory Pattern:  Example: `javax.xml.parsers.DocumentBuilderFactory` provides an abstract factory for creating different types of XML parsers.
6. Adapter Pattern:  Example: `java.util.Arrays#asList()` method, which allows an array to be viewed as a List, is an example of the Adapter pattern. 
7. Decorator Pattern:  Example: `java.io.BufferedInputStream` and `java.io.BufferedOutputStream` classes in Java's I/O library use the Decorator pattern to add buffering functionality.
8. Observer Pattern:- Example: The `java.util.Observable` class and `java.util.Observer` interface in Java's standard library provide an implementation of the Observer pattern.
10. Template Method Pattern:  Example: The `javax.servlet.http.HttpServlet` class in Java's Servlet API uses the Template Method pattern to define the lifecycle of a servlet.
13. Proxy Pattern: Example: The `java.lang.reflect.Proxy` class in Java allows the creation of dynamic proxy objects, which can intercept and delegate method calls.
14. MVC (Model-View-Controller) Pattern:  Example: Java's Swing GUI framework follows the MVC pattern. For example, the `javax.swing.JTable` class represents the view, while the `javax.swing.table.TableModel` interface represents the model.



These examples illustrate the application of various design patterns in real-world Java libraries and frameworks. Understanding and applying these patterns can enhance code organization, maintainability, and extensibility in Java applications.
