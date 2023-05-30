- As label elements are inline by default, to make them block, 
    - To make them appear on separate lines : display: block
    - to separate them from each other : margin:0.5rem 0
- To handle the form submission, add an input element with the type attribute set to submit and the value attribute set to Submit.
- regex- With type="password" you can use the pattern attribute to define a regular expression.
- for input element with the 'number' type, we can set min and max to control the values.
-  To give textarea an initial size, we can add the rows and cols attributes.
- With form submissions, it is useful, and good practice, to provide each submittable element with a name attribute.
- With a display of block the element sits flush against the left edge of its parent. To center this element
    - input[type="submit"] {
        display: block;
        width: 60vw;
        margin: 0 auto;
    }
- To change the margin property we can include value(1em) on the top and bottom, while leaving the right and left margins set to autoor any other value
