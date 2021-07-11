# Define an HTML Table  
The table tag defines an HTML table.  
Each table row is defined with a tr tag. Each table header is defined with a th tag. Each table data/cell is defined with a td tag.  
By default, the text in th elements are bold and centered.  
By default, the text in td elements are regular and left-aligned.  

![table](https://i.imgur.com/uIwzEfS.png)

### Chapter Summary  
+ Use the HTML table element to define a table  
+ Use the HTML tr element to define a table row  
+ Use the HTML td element to define a table data  
+ Use the HTML th element to define a table heading  
+ Use the HTML caption element to define a table caption  
+ Use the CSS border property to define a border  
+ Use the CSS border-collapse property to collapse cell borders  
+ Use the CSS padding property to add padding to cells  
+ Use the CSS text-align property to align cell text  
+ Use the CSS border-spacing property to set the spacing between cells   
+ Use the colspan attribute to make a cell span many columns    
+ Use the rowspan attribute to make a cell span many rows  
+ Use the id attribute to uniquely define one table  


# JavaScript Object Methods  
In a function definition, this refers to the owner of the function.  
In the example above, this is the person object that "owns" the fullName function  
In other words, this.firstName means the firstName property of this object.  
Read more about the this keyword at JS this Keyword.  

### JavaScript Methods  
+ JavaScript methods are actions that can be performed on objects.  
+ A JavaScript method is a property containing a function definition.

![method](https://dmitripavlutin.com/static/d0597f7819971bf2b124b653b673eb29/05127/cover-2.png
)

# Functions  
+ Generally speaking, a function is a subprogram that can be called by code external (or internal in the case of recursion) to the function. Like the program itself, a function is composed of a sequence of statements called the function body. Values can be passed to a function, and the function will return a value.  
In JavaScript, functions are first-class objects, because they can have properties and methods just like any other object. What distinguishes them from other objects is that functions can be called. In brief, they are Function objects.

![functions](https://s3.ap-south-1.amazonaws.com/s3.studytonight.com/tutorials/uploads/pictures/1587882057-1.png)  

# Description  
Every function in JavaScript is a Function object. See Function for information on properties and methods of Function objects.  
To return a value other than the default, a function must have a return statement that specifies the value to return. A function without a return statement will return a default value. In the case of a constructor called with the new keyword, the default value is the value of its this parameter. For all other functions, the default return value is undefined.  
The parameters of a function call are the function's arguments. Arguments are passed to functions by value. If the function changes the value of an argument, this change is not reflected globally or in the calling function. However, object references are values, too, and they are special: if the function changes the referred object's properties, that change is visible outside the function.


