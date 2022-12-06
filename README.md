## 403.- 50 Projects 50 Days - Rotating Navigation

### What was the project about?

The project is part of the 50 Projects in 50 Days with Brad Travesy via Udemy. The course is a code-a-long to further cement skills used within HTML, CSS, and Vanilla JavaScript.

This particular project was making a roating navigation. When the user clicks the hamburger icon, the content rotates at an angle, and the navigation menu transitions into place. It is an extremely cool effect.

[Rotating Navigation](https://totallysly.github.io/403.-50PROJECTS50DAYS--rotating-navigation/)

### What did I learn?

This project was more CSS heavy with very minimal JavaScript.

#### CSS

This project implemented a lot of rotation and transitional properties to the CSS. Of which I have used before and I have an understanding of how these work. This quick cheetsheet help as a reference point.

[Transition and Rotation](https://codesandbox.io/s/css-transform-rotate-translate-forked-rh2v9k?file=/style.css)

An important takeaway from the video was:

    transform-origin: top left;

Instead of just rotating the content, this rotated everything. It is easier to see when placed in practive. But in essence, not only does the content move, it rotates everything. Think of it as putting a piece of paper on the table, your thumb on the top left, and rotating it to your stated degree.

The biggest takeaway from this project is that I need to read up more on selector specificity. I tend to add a class or ID to each element I am looking to style. This works. But it can create a messy looking HTML and CSS structure.

[W3 Schools - CSS Selectors](https://www.w3schools.com/cssref/css_selectors.php)

In future I will use this reference sheet and try to create styling using the different methods of selecting elements, rather than just giving them a class name. Thus, removing anything that is unnecessary within the HTML. Also, it will make the layout of the CSS much more clearer and in clearer sections.

#### JavaScript

The only JavaScript required was to add, and remove, a _classList_ on the container when the user clicks the hamburger, or close, icon.

> Written with [StackEdit](https://stackedit.io/).
