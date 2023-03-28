## Three pillars of HTML/CSS

The three fundamental pillars of writing good HTML and CSS are Responsive design, Making sure your code is easy to maintain and scale, How well your code performs.

## Behind the secens

When we open our browser and load up a web page the browser does a lot of things in the background. Loading our code, making HTTP requests, parsing our code, and bulding the dom.

## How CSS is parsed

The process of combining different stylesheets and resolving the conflicts between them is called cascading.

There are three types of styles that are being applied to the web page when we load in the browser:

- The author styles are which are loaded from the website's stylesheet

- The user styles are loaded if the user has set different styling in the browser such as a theme or font size.

- The browsers default styling called the user-agent styles like the default lists and anchor links.

These styles sometimes conflict with each other and are resolved through a process that consists of three steps. The first step in cascading CSS rules is the importance of how and where the CSS rule is declared.

Rules having the **!Important** keyword is applied first.User and Author rules are applied after this. The second step looks at the specificity of rules which starts from inline-styles, IDs, classes and pseudo-classes, attributes, and finally elements and pseudo elements.

The third step is the order of declaration, if the specificity is the same the last declared rule will be applied.

## Reusability

Always make sure that your code can be reused in the future, write meaningful class names, and structure your markup efficiently. 

Break your markup and styles into small-independent components that can be used anywhere in the project and later on in future projects. 

Naming conventions give extra meaning to your class names and can help you and other developers in reading the code if you ever use it again.

A popular naming convention that many people use is called block element modifier or B.E.M for short which specifies that each component is a block and the markup inside the block is called an element and specific elements that are different from the other have a modifier at the end of their class names.

## Seven to one rule

An efficient way to write CSS code is by using a design pattern, the 7-1 design pattern is a commonly used design pattern that divides the styles into seven different parts and then combines them into one main file.which includes only the import statements of the other files.

Each folder contains partial styles that are then imported into the main SASS file which compiles it into a CSS file

