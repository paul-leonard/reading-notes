# Paul's Reading Notes

## Code 201

### Class 3: HTML Lists, CSS Boxes, JS Control Flow

**Reading Material for the Assignment**
1. Duckett: HTML & CSS
- Chapter 3: Lists (pages 62-73)
- Chapter 13: Boxes (pages 300-329)
2. Duckett: JavaScript & jQuery
- Chapter 4: Decisions and Loops (pages 162-182)



#### Duckett: HTML & CSS

##### Chapter 3: Lists (pages 62-73)
There are three types of lists available in HTML.  A definition list would be perfect for listing them out if we were writing notes in HTML.
- *Unordered List*: list with bullets in front
- *Ordered List*: list with ascending numbers in front
- *Definition Lists*: List of terms with an indented and below definition of each.  Think glossary.

Lists can be nested inside of each other.

##### Chapter 13: Boxes (pages 300-329)
It is good practice to think of each HTML element as being in its own box.  These boxes have properities that can be affected by CSS.  CSS can control many aspects of the box including dimensions, borders, margins, and padding.  It is even possible to change block-level HTML boxes into in-line elements and vice versa.  It is also possible to hide block elements entirely.  All of this comes together to create a visually appealing and legible website.

There are three main properities of a box:
- *border*: every box has a border, even if 0 pixels wide.  It is the actual box
- *margin*: the closest that another box element's border can get to your box element's border
- *padding*: distance from the border to the closest content within the box element


#### Duckett: JavaScript & jQuery

##### Chapter 4: Decisions and Loops (pages 162-182)
**If..Else Statements** check for a condition and based on its truthfulness, execute one of two blocks of code.  They are made up of four parts:
- conditional statement (syntax for the if...else statement)
- condition (to check)
- if code block (to run if condition was true)
- else code block (to run if condition was not true)

**Switch Statements** provide better functionality than a series of if...else statements.  They are both more readable to humans and also make for faster running scripts.  They run faster because if...else statements will continue to check all following statements, even if one was found to be true.  On the other hand, once a Switch Statement conditional is found to be true, the rest of the code in the Switch Statement is ignored.  Like the else clause for the if statement, a default can also be defined for the situation where no listed cases match.  Because of how Switch Statements work, it is better to have your more probable condition be located near the top of the cases.

###### Loops
Loops check a condition and continuously run a section of code until the conditon is no longer met.
- **For Loops** execute their code a certain number of times and increment their counter each time they execute the code.
- **While loops** execute their code while certain, usually external, conditions are true.
- **Do while loops** are similar to While loops, but guarantee the code will be executed at least once.  Even if the conditional statement is not true.

*Key Parts of a Loop*
Name | Code
--- | ---
initialization | 'var i = 0;'
condition | 'i < 10;'
update | 'i++'

*'i++' increments the counter by one*

*Examples of Where to Use Which Loops*
Example   |  Best Loop
---   |   ---
Ensuring user has entered a numeric value | While
Restricting access until a correct password is entered | While
Showing each of the products in a shopping cart | For
Displaying all the books on a digital bookshelf | For



[Return to Table of Contents for Paul's Reading Notes](https://paul-leonard.github.io/reading-notes/ "Go back to find more notes!")



---



Thank you for visiting my page of notes.  I hope they were helpful to you.  Please also check out [my GitHub portfolio page](https://github.com/paul-leonard "Paul's GitHub Portfolio").