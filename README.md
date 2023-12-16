# ID-Attribute

Every HTML element can carry the id attribute. It is used to uniquely identify that element from other elements on the page. Its value should start with a letter or an underscore (not a number or any other character).It is important that no two elements on the same page have the same value for their idattributes (otherwise the value is no longer unique).As you will see when you come to look at CSS in the next section, giving an element a unique identity allows you to style it differently than any other instance of the same element on the page. For example, you might want to assign one paragraph within the page (perhaps a paragraph containing 
a pull quote) a different style than all of the other paragraphs. In the example on the right, the paragraph with the id attribute whose value is pullquote is made uppercase using CSS.If you go on to learn about JavaScript (a language that allows you to add interactivity to your pages), id attributes can be 
used to allow the script to work with that particular element.The id attribute is known as a global attribute because it can be used on any element.

<p>Water and air. So very commonplace are these 
 substances, they hardly attract attention - and 
 yet they vouchsafe our very existence.</p>
<p id="pullquote">Every time I view the sea I feel 
 a calming sense of security, as if visiting my 
 ancestral home; I embark on a voyage of seeing.
</p>
<p>Mystery of mysteries, water and air are right 
 there before us in the sea.</p>

 
