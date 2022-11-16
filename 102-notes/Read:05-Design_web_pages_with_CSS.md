# Design Web Pages with CSS
CSS is Cascasding style sheets. It is used for styling your HTML.  There are many different attritubes you can use to style your HTML.
It is a perferred method to use external CSS (separate file) instead of using inline(CSS and HTML written together) CSS. External CSS require
a HTML `<link rel= "stylesheet" href="mystyle.css">` tag. When styling your CSS it is considered best practice to first use the
 selector of the element you want to style then add your styling one line at a time. There are more complex selectors but the basic ones used are
class name, html element, and id. Creating a selector is the first step in adding some style to your web page. Once you have selected something you want
to style you can then add some properties based on the look you are trying to achieve. Now the only thing left is to add values to those
properties as the style will change depending on the type of property and value assigned to it.
```
p { 
  color: blue;
  background-color: purple;
  height: 50px;
  width: 50px;
}
```

## Selector Cheat Cheat
*Basic selectors:*
- Universal selector *
- Type selector elementname
- Class selector .classname
- ID selector #idname
- Attribute selector [attr=value]

*Grouping selectors:* 

`Selector list A, B`

*Combinators:*

  Adjacent sibling combinator A + B
  
  Specifies that the elements selected by both A and B

*General sibling combinator* A ~ B

  Specifies that the elements selected by both A and B share the same parent

*Child combinator* A > B

  Specifies that the element selected by B is the direct child of the element selected by A

*Descendant combinator* A B

  Specifies that the element selected by B is a descendant of the element selected by A, but is not necessarily a direct child.

*Pseudo*

  Pseudo classes :
  
  Specifies a special state of the selected element(s).

  Pseudo elements ::
  
  Represents entities that are not included in HTML.

## Things I Want to Know 
- I would like to know about Reset CSS
