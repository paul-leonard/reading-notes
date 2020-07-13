# Paul's Reading Notes

## Code 201

### Class 6: JS Object Literals; The DOM

**Reading Material for the Assignment**
1. [Understanding the problem domain is the hardest part of programming](https://simpleprogrammer.com/understanding-the-problem-domain-is-the-hardest-part-of-programming)
2. Duckett: JavaScript & jQuery
- Chapter #3: Object Literals (pages 100-105)
- Chapter #5: Document Object Model (pages 183-242)



#### Article:  Understanding the problem domain is the hardest part of programming
Often the hardest part of programming is figuring out what the true problem you are trying to solve is.  Focusing down the problem statement and clearly identifying it can make writing code to fix or address the problem significantly easier.

John Sonmez recommends making programming easier by making the problem domain easier.  He recommends narrowing your focus and constraining the problem into groupings.  Second, make sure you understand the problem by spending time on it and communicating clearly with your information sources.



#### Duckett: JavaScript & jQuery

##### Chapter #3: Object Literals (pages 100-105)
Objects are contained in a variable.  Objects have properties and methods.  Properties are like variables that are stored in the object.  Methods are like functions that live in the object.  Each are part of a *key-value pair*.  Name/value pairs are common in programming.

**Literal notation** is the most common and simplist way to define objects.  The syntax begins with:
'var objectName = {
  property1: 'value',
  method1: function() {
    //do things
  }
};'

Objects are accessed by using **dot notation**.
'var x = objectname.property1;
var x = objectname.method1;'

You can alternatively use square brackets around the property or method instead of the dot notation.


##### Chapter #5: Document Object Model (pages 183-242)
Each browser consumes the HTML, CSS, and JS and uses the code to construct the Document Object Model.  A *DOM tree* is used to structure the webpage and contain four types of nodes: document, element, attribute, and text.  As programmers, we can access these nodes in multiple ways.  Most importantly, JavaScript can be used to modify these nodes and thereby change the appearance and content of the website.  Older browsers are not consistent, but use of jQuery helps identify which portions of the DOM to change.



[Return to Table of Contents for Paul's Reading Notes](https://paul-leonard.github.io/reading-notes/ "Go back to find more notes!")



---



Thank you for visiting my page of notes.  I hope they were helpful to you.  Please also check out [my GitHub portfolio page](https://github.com/paul-leonard "Paul's GitHub Portfolio").