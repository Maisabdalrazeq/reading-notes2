# Welcome To the Read07 page ..

**How to create tables in HTML?**

*HTML table allows you to arrange data into rows and columns. They are commonly used to display tabular data like product listings, customer's details, financial reports, and so on.*

*You can create a table using the <'table'> element. Inside the <'table'> element, you can use the <'tr'> elements to create rows, and to create columns inside a row you can use the <'td'> elements. You can also define a cell as a header for a group of table cells using the <'th'> element.*

**Examples:**

![img](https://pristinetechschool.com/wp-content/uploads/2018/08/1.png)

`<table>
    <tr>
        <th>No.</th>
        <th>Name</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>1</td>
        <td>Peter Parker</td>
        <td>16</td>
    </tr>
    <tr>
        <td>2</td>
        <td>Clark Kent</td>
        <td>34</td>
    </tr>
</table>`





**What is the Objects in JavaScript?**

*Objects in JavaScript, just as in many other programming languages, can be compared to objects in real life. The concept of objects in JavaScript can be understood with real life, tangible objects.*

*In JavaScript, an object is a standalone entity, with properties and type. Compare it with a cup, for example. A cup is an object, with properties. A cup has a color, a design, weight, a material it is made of, etc. The same way, JavaScript objects can have properties, which define their characteristics.*

**Example:**

`var myCar = {
    make: 'Ford',
    model: 'Mustang',
    year: 1969
};`


**Creating and Initializing Objects: Constructors ..**

*A Java class defines what objects of the class know (attributes) and what they can do (behaviors). Each class has constructors like World() and Turtle(habitat) which are used to initialize the attributes in a newly created object.*

*A new object is created with the new keyword followed by the class name (new Class()). When this code executes, it creates a new object of the specified class and calls a constructor, which has the same name as the class. For example, new World() creates and initializes a new object of the World class, and new Turtle(habitat) creates and initializes a new Turtle object in the World habitat.*


**Add or delete a property of an object in JavaScript..**

**Example:**

`const baseObject = {
  firstName: "Joe",
  lastName: "Doe",
  age: 23,
};

// Adding a property called company to an object
baseObject.company = "Microsoft";

// Deleting the property age of the object
delete baseObject.age;`


**What is THIS Keyword in Java?**

***The various usages of 'THIS' keyword in Java are as follows:***

-  It can be used to refer instance variable of current class
-  It can be used to invoke or initiate current class constructor
-  It can be passed as an argument in the method call
-  It can be passed as argument in the constructor call
-  It can be used to return the current class instance