# Reading Notes Class 03

1. When should you use an unordered list in your HTML document? You should use this when you are creaing a navigation menu i.e Home, About, and Contact list. The reason that you would use an unordered list is because this above list has no numeric vaules associated with them. 
2. How do you change the bullet style of unordered list items? You have to go into the CSS in order to change the style of the bullet point, the command list-stlye-type
3. When should you use an ordered list vs an unorder list in your HTML document? and orderlist is some things that need to be put in order, which sounds obvious, but for the html when you have something in a numerical value it is best to give that order so the user will see it displayed in its proper context. For things that don't need to be in a certain order you can use an unordered list. 
4. Describe two ways you can change the numbers on list items provided by an ordered list? You can change them in CSS with list-style-type and you can also change it with letter or roman numerals. you cna do letters by starting the type "a" or "A" and roman numerals and "i" or "I"

5. List and describe the four parts of an HTML elements box as referred to by the box model.
    - Content box: The area where your content is displayed; size it using properties like inline-size and block-size or width and height.
    - Padding box: The padding sits around the content as white space; size it using padding and related properties.
    - Border box: The border box wraps the content and any padding; size it using border and related properties.
    - Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin         and related properties.

6. What data types can you store inside of an Array? They can store all types of data; string, numbers, lists, etc.

7. Read the code below and evaluate the last expression and explain what the result would be and why.
  - let a = 10;
  - let b = 'dog';
  - let c = false;

  - // evaluate this
  - (a + c) + b;
  The code is tring to read that 10 + false + dog, the issue it that this whole cod will either fail or not work at all beause that value of C = false and there is no set equal to this eqaution. It is just adding 3 values but given no output for them.
8. Describe a real world example of when a conditional statement should be used in a JavaScript program. You should use this type of statement when you are wanting someong to put in previously know information, username and passwords. That way fi the correct condition is met they will gain access, if they dont then no access is gained. 
    
9.Give an example of when a Loop is useful in JavaScript. Same example as above except you get a finite amount of tries to enter in the correct information or you will be restricted from gaining the access you seek.
