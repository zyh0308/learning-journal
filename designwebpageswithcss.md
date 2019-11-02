# Design web pages with CSS

- The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.
- CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.

**CSS Associate style rules with HTML elements**

CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a **selector and a declaration**.

**􏰋􏰍CSS properties affect how elements are displayed**
CSS declarations sit inside curly brackets and each is made up of two parts: **a property and a value**, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon.

**CSS Selectors**

- There are many different types of CSS selector that allow you to target rules to specific elements in an HTML document.
- CSS selectors are case sensitive, so they must match element names and attribute values exactly.

**How CSS rules cascade?**

If there are two or more rules that apply to the same element, it is important to understand which will take precedence.

-􏰉􏰁􏰍􏰅 **􏰄􏰓􏰉􏰀LAST RULE** : If the two selectors are identical, the latter of the two will take precedence. Here you can see the second i selector takes precedence over the first.

- **􏰍􏰈􏰀Specificity** : If one selector is more specific than the others, the more specific rule will take precedence over more general ones. In this example:
h1 is more specific than *
p b is more specific than p p#intro is more specific than p

- **􏰇Important** : You can add !important after any property value to indicate that it should be considered more important than other rules that apply to the same element.

Understanding how CSS rules cascade means you can write simpler style sheets because you can create generic rules that apply to most elements and then override the properties on individual elements that need to appear differently.

**Inheritance** 

- If you specify the font-family or color properties on the <body> element, they will apply to most child elements. This is because the value of the font-family property is inherited by child elements. It saves you from having to apply these properties to as many elements (and results in simpler style sheets).
  
- You can compare this withthe background-color or border properties; they are not inherited by child elements. If these were inherited by all child elements then the page could look quite messy.

- You can force a lot of properties to inherit values from their parent elements by using inherit for the value of the properties. In this example, the <div> element with a class called page inherits the padding size from the CSS rule that applies to the <body> element.
  
### Color ###
- Color not only brings your site to life, but also helps convey the mood and evokes reactions.
- There are three ways to specify colors in CSS: RGB values, hex codes, and color names.
- Color pickers can help you find the color you want.
- It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).
- CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.
- CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.
