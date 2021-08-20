### Ch 3 Lists
There are three types of lists in HTML (ordered, unordered, and definition), and you can nest lists within "<li>" elements.
### Ch 13 Boxes
The visual box model is really helpful in remembering the difference between padding, border and margin. The chapter covered the different ways you can use CSS to display boxes on a page.

### Ch 2 Basic JavaScript Instructions (pp.70-73)
Arrays are a type of variable, which store lists of values. While it's common to store values of the same data type, the values in an array can be different types from each other. Items within an array are accessed like a numbered list, where the first item is stored at 0. You can use the indexes within an array to access specific items, like:
 array[1] = 'updated item'
 This would replace the second item in the given array to the string 'updated item'.

### Ch 4 Decisions and Loops from switch statements (pp.162-182)
- if/else statements check for conditions, if the first condition resolves to True the corresponding code block gets executed. If it resolves to False, the next if statement, or the Else statement is executed.
- switch statements set a default option that is run if none of it's cases match
- type coercion happens when JS sees a data type it didn't expect, it doesn't error and updated the data type to what it assumes that needs to be. This is why we use strong typing (like using === instead of == to compare values), so that we're verifying if both the value and data types match.
- type coercion is the reason every value can be reduced to its truthy or falsey-ness
- loops (for, while, and do...while) repeat a set of commands/statements a number of times until it's conditions are met, or it's set to stop.
