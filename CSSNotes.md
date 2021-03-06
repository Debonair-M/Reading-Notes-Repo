# CSS Notes  

* CSS is a language for specifying how documents are presented to users 

CSS (Cascading Style Sheets) allows you to create great-looking web pages

Using CSS you can control exactly how HTML elements look in the browser

CSS can be used for very basic document text styling-
CSS properties have different allowable values, depending on which property is being specified. 

CSS stylesheet-
h1 {
    color: red;
    font-size: 5em;
}

p {
    color: black;
}
There are three ways of inserting a style sheet:

* External CSS- 
With an external style sheet, you can change the look of an entire website by changing just one file!
Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.

* Internal CSS-
An internal style sheet may be used if one single HTML page has a unique style.
The internal style is defined inside the <style> element, inside the head section.

* Inline CSS-
An inline style may be used to apply a unique style for a single element.
To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property. 

* CSS Comments-
Comments are used to explain the code, and may help when you edit the source code at a later date.
Comments are ignored by browsers.
A CSS comment is placed inside the <style> element, and starts with /* and ends with */
are not displayed in the browser, but they can help document your source code.

* CSS Colors-
body {
  color: red;
}

h1 {
  color: #00ff00;
}

p.ex {
  color: rgb(0,0,255);
}
Colors are specified using predefined color names, or RGB, HEX, HSL, RGBA, HSLA values.
<h1 style="color:Tomato;">Hello World</h1>
<p style="color:DodgerBlue;">Lorem ipsum...</p>
<p style="color:MediumSeaGreen;">Ut wisi enim...</p>

* Important Property-
The !important rule in CSS is used to add more importance to a property/value than normal.
In fact, if you use the !important rule, it will override ALL previous styling rules for that specific property on that element!