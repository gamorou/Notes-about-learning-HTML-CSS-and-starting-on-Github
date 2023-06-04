# About
This is the code that I am doing while learning HTML and related languages., it is the part 1 of these learnings which I expect more to come.

Here is also my notes on many things, not everything is perfectly accurate, but it is written in a way that I myself can understand.

# Notes

## Cmd:
-Cd "folder path"; it is a command to put the current directory of action in the cmd to the one of where you are operating, you should copy the path of the file explorer and paste on the folder path part.

## Github:

 ### Commands:
-git init; starts github.
-git config --global ; Put the name of the user with the addition of: user.name ""; email with: user.email "".
-git pull; Its the command that if the folder is connected to github, it will pull the most recent branch of it.
-git pull ""; Its the code utilized to pull and download a git directory from its https link into the folder. You have to be in a directory on the powershell for that work.  Put the link inside the "".
-git fetch; Gets the information of the directory uploaded on github, which can be used to compare with the actual code for example.
-git diff; its the code utilized to see the differences between the actual code and the one on github, you have to add the prefix "--staged" if you had already saved the   alterations on the folder.
-git status; Shows the branch status.
-git push; it is the command to push the changes on the directory that is connected to github, to the actual page of github, you can also do "Git push 'filename'" to push just  the file you want.
-git branch *branch name*; creates a new branch with the designed name.
-git checkout *branch name*; changes the branch to the branch of the designed name.
-git log --oneline --decorate; Shows informations about the HEAD.
-git merge *branch name*; Merge the current branch with the designed branch.

 ### Others:
-A code file named .gitignore can be made with the files to be ignored by the github upload.
-Different branches can keep different progress, you can make different branches and go to different times of work.

## HTML:

 ### Commands:
`<html lang="">` Put the language of use in your HTML inside the quotation marks "" part as in short names (like 'en' for English, 'pt-br' for Portuguese), this part used by  accesibility options, so put the proper language.

`<meta http-equiv="X-UA-Compatible"  content="IE=edge">` Adds comptability to the browser Internet explorer, not much use other than that.

`<meta name="viewport" content="width=device-width, initial-scale=1.0">` Viewport means the area where images and elements are rendered in the website. the content part   matches the width of the device of the user. The initial-scale has the scale of the objects multiplied by its value, which the default is 1.

`<meta charset="UTF-8">` Means the character form, things needed if you want to use special characters such as Kanji, arabic, cylliric, etc.

`<title>` Is an element to define the name of your tab

`<p>` It is an element. Writes plainly inside your tab, by using two separate instances you create the phrases in different lines, it will never create paragraphs within the  same instance unless it has a <br> between it.

`<br>` It is a non-closed tag to breakdown lines inside `<p>`.

`<b>` It is an inline that turns whatever text inside it into Bold. `<strong>` is an alternative that works the same way.

`<i>` It is an inline that turns whatever text inside it into Italic. `<em>` is an alternative that works the same way.

`<u>` It is an inline that turns whatever text inside it into underlined. It is outdated by its CSS equivalent.

`<s>` It is an inline that turns whatever text inside it into strikethrough.

`<mark>` It is inline that turns whatever text inside it into highlighted words.

`<span>` It is the CSS equivalent that can work inline to change whatever text into something different.

`<pre>` It is an element that turns whatever words inside it into pre-formated text (The kind of text code is written as).

`<code>` It is an inline. It does the same as `<pre>` but it works inline.

`<blockquote>` It is an element that separates a block to the text written on it.

`<sup>` It is an inline turns whatever text inside it into a small text on the half above of the regular text (normally used to do things like 2^10 have the 10 being small at  the side of the 10).

`<sub>` It is an inline turns whatever text inside it into a small text on the half below of the regular text (normally used to do things chemical elements).

`<div>` It is an element. It creates a new block section of the HTML.

`<header>` It is an element made to refer to the structure that stays on top of the page, the difference is semantics for code structure.

`<main>` It is an element made to refer to the main contents of the page, the difference is semantics.

`<footer>` It is an element made to refer to the structure that stays on the bottom of the page, the difference is semantics for code structure.

`<aside>` It is an element made to refer to the structure that stays on the side of the page, the difference is semantics for code structure.

`<nav>` It is is an element that implements a navegation bar, a bar that works like a lateral list on the top of a website.

`<section id="">` It is an element made to refer to the sections inside a page.

`<article>` It is an element, you can use all semantic tags inside of it with it being separated from the main code.

`<!--  -->` Is the commentary function in HTML, on VSCode you can use ctrl+/ to easily form comments.

`<h1>` to `<h6>` It is an element and level of headers you can have, you have from 1 to 6, with all numbers between them, the higher the number, the smaller it is.

`<a href="">` It is an element to implement links, you put the link between the brackets and inside the element you write the text you want to have referencing to that link as  a hyperlink. 
It has the configurations: `target=""` Which you can put the following between the brackets to do the following things: `"_blank"` creates a new tab to enter the link, `"_self"` it is the default configuration which goes from the website into the link without changing tabs.
 By putting "/" it will always go back to the main page.
 You can use the element `<img src="" alt="">` inside it to refer to a clickeable image that will go to the desired link.
 
`<img src="" alt="">` It is an exception to the rule of having to close the tag. It creates an image in your tab.
 
 You can put the following configs inside it: 
 
 `src=""` requests the directory/source and name of the image, where you put the directory and image file you plan to put in, alternatively you can paste the link of   the  image from the internet directly inside the src and it will work the same, write everything inside the quotations. 
 `alt=""` is a description of the image you  uploaded. 
 
 Extra configurations: 
 
 `width=""` is the width size in pixels of your image, you must write the numbers of the pixels inside the quotations, if the height is not specified it will automatically  match the width in proportions, alternatively you can also utilize percentage of the header that the image will use as space, like "10%".
 `height="" `works exactly like the width, but for height. By defining both height and width the image files will have the desired pixel size regardless of proportions.
 
`<figure>` It is an element that is normally used in code structure to put the element `<img src="" alt="">` inside and have a clearer code.

`<figcaption>` It is an element that is normally used in code structure to add captions to images inside the `<figure>` element.

`<ul>` It is an element that creates a list that is numbered, to insert items in it you have to utilize the element `<li>`.

`<ol>` It is an element that creates a list that is numbered, to insert items in it you have to utilize the element `<li>`.

`<li>` It is an element that is utilized in lists to be elements of the list, inside this element you can write what should appear in the list.

`<table>` It is an element that serves to form a table of contents. 

 You can put the following configs inside of it: 
 `border =""` it is a config that adds a border around the table with a different style based on the number put inside the "".
 
 
`<thead>` It is an element utilized to serve as the head of the `<table>` element.

`<tbody>` It is an element utilized to serve as the body of the `<table>` element.

`<tr>` It is an element that creates a row inside the parts of a `<table>` element.

`<th>` It is an element defines the name of the row inside `<tr>` element that is inside of a `<thead>`.

`<form>` It is an element that is utilized to create forms. 

 You can put the following configs inside of it: 
 `action=""` its the action done when submited, when left empty it refreshes the page.
 `method=""`
 
`<input id="">` It is a non-closed tag that creates field to be filled by the user with many different configurations. 

 You can put the following configs inside of it:
 `type=""` defines the types are to be put in, the following types can be used: "text", "password", "email", "number", "date", "time", "file", "url", "checkbox", "color",  "range" (scroll), "radio" (single choice checkbox), "reset" (clears all other letterboxes), "submit" 
 `placeholder=""` puts a grey text for when the letterbox isn't being utilized, commonly used to indicate what should be written inside by the user.
 
`<label>` It is an element that is used to apply labels to other elements, what's written inside of it that will be applied.

 You can put the following configs inside of it:
 `for=""` Refers to which element the label will be applied to, put the id of the element you want inside the "".
 `value=""` Already sets a initial text inside the letterbox.
 
`<textarea>` It is an element that creates a big area to text to be put in, they have rows and columns that are configurable.

`<select>` It is a tag to give a list that will give options to the user to select. Utilize `<option>` inside it to put the options.

`<option>` It is utilized to details the options inside something. Value inside of it works similar to ID.

 You can put the following configs inside of it:
 `disabled` You can put to grey out the option and put an option that can't be selected, you can also use: disabled selected; to make it be the default answer.
 
`<Style>` It is an element that works exactly as its CSS equivalent.

`<link>` Links to a .css file that will be utilized.

 ### Others:
-HTML must have these three in order `<HTML>`,`<Head>`, and `<Body>`.

-You can just type HTML and press tab on VSCode to get the presets, you can also just type `!` to do the same.

-All elements must end with an equivalent `</element>`, it is noticeable that all details and configurations of the element, stay just in the first part.

-Shift+alt+down arrow = Duplicates the line to the line below.

-If you type just `element*number` and press tab, it will create the desired number of element.

-Inline are codes that are formated like elements, but are meant to be written inside elements, they do things like change the text inside the elements.

-None of the elements require an: `id =""` but it is good to always give them ids so they can be reffered to by other elements.

-To elements be identified by javascript, you need to add: `name=""` to the element.

-You can put: `class""` inside the elements to define classes on the tags and elements.

## CSS:

### Others:
 On CSS, different from HTML, remember to always add ";" at the end of the commands.

 Hexadecimal colors works like this: The first two digits represent the red, the second the green, the third the blue, instead of numbers, for a stronger color you can use letters from A to F in the hexadecimal, with FF being the full color, always the first digit of a color pair is the one that has to have the stronger tone.

 To work with classes in CSS, you have to add a "." on the start of them when writing them down, otherwise it will only work with elements.

 You can utilize "*" like a configurable class to change things in CSS itself.

 You can utilize "," to refer to many classes, just like doing normal classes, but adding the comma and the new element to the side.

 You can utilize .class element; to refer solely to the element inside this class.

 More than a single h1 can give conflicts on the search engines.

 You can utilize a blank div with established width and height to create space.

 Elements needs to have the display:inline-block configuration to fit at the side of each other, images have that configuration by default.

 `element.class` is a semantic utilized to search an element whose the class is the class put in, the reverse of `class element`.

 General size definitions with the "n" being the desired number and the space being something that should be ignored: n px (where px is the number of pixels), n rem (rem is a   size that considers the size of the :root as a base, with  the number in it being the multiplier of that original number), n em (It ignores the root and takes whatever are     the  new base value), n vh/n vw (Is the size full based on the user configuration, note that the number works in percentage in  this case, vh is for height and vw is for  width), n fr(is a flexible unit, that will work depending on the space the other elements at its side occupy).

 `calc()` is the way to make values become calculus, you can do things like (100vh - 7rem) and the result is the number that will be applied, you use that on options  that   requires numbers, you can utilize extra parenthesis inside of it to make extra calculus like (100 - (7 * 2rem)).

 To reference ids utilize "#id" without the quotations, much like ".class".

 To reference to (data-placholdername ="") for attributes, utilize [data-placeholdername =""], you can also select all of the attributes inside the tag with the following syntax: [data-placeholdername] .

## Configurations of css:
 ### General configs:
 
 `style=""` You can use the following configurations inside style or make a CSS with the following.

`width:` defines the width of the element, you can input the number of pixels like "100px", or you can put the percentage of the element you want displayed like "100%" do note that normaly putting both width and height in 100%  makes the an image invisible.

`height:` defines the height of the element you can input the number of pixels like "100px", or you can put the percentage of the element you want displayed like "100%", do note that normaly putting both width and height in 100% makes the an image invisible.

 `min-width:` Defines the minimum width which can be increased by other properties, such as writing a longer text than the box can fit.

`min-height:` Defines the minimum height which can be increased by other properties, such as writing a longer text than the box can fit.

 `color:` Defines the color of the text or element.

 `opacity:` Defines the opacity of the element, the default is 1. The main difference between opacity 0 and visibility:hidden, is that opacity 0 elements remains interative.
 
` visibility:` Defines the visibility of the element.

 `margin:` Defines the size of the margins in your element (can be used inside the "*").

 `:root` is a pseudo-class that will give configs that will be based by other classes.

 `a:visited` Applies the desired changes inside the brackets to the link once it is visited.

 `a:hover` Applies the desired changes inside the brackets to the link once the mouse hovers over it, must always be put after the link and after the visited setting.

 `*insert config here*:first-child` Applies the config to the first element, this must be put with a config first on it, on the insert a config here part.

`*insert config here*:nth-child()` Inside of it the () you can utilize the variable "n", where the default base of n 0, each of the elements in your config are numbered from 0  and counting, the n will affect all elements the count on it  reaches, you can also just use numbers without the n to affect only the element of the number.

 `border: ` You can create a border on the element, with the first value being how thick it is, and the being its state, for it to show regurlaly put it as: solid; and the third is its color.

`display:` Change how the element occupies the space, block (is the default for most including divs, makes it occupy the entire width where it is not letting other elements stay at its side).

Configs for `display:` :

`inline-block`(allows other elements to stay at its side as long as the width fits without entering the div) 

`inline`(allows other elements to stay at it side and it gets pushed out of screen by the other elements if they are too big) 

`"none"` removes the visual of the element and any space it occupies 

`"flex"` (changes it to the default configurations of the flex display, you can use flex-wrap to adjust its settings)

`grid` (Enters in grid mode, which like flex, has many unique options and   configs, it also changes the organization slightly). Note that sometimes that can change the position of the element.


 `padding: ` Put the quantity of padding you want in the image, padding grows the element and creates distance between things inside of it as well, such as texts inside divs.

`margin:` Distances the element from everything by the amount put into it. You can also use the option: auto (for automatic margin from the corner of the screen).

 `border-radius: ` Cut the edges of the border by the amount put inside of it.

`box-sizing:` Changes the size of the boxes and fixes them, very useful to correct padding. You can use the config:border-box; to set it to the exact borders of the box.

 `position:`  Defines the position of the element. `absolute` (ignores any space restrictions and puts the element where it is initially expected to be), `relative` (puts the element in a relative position to its surroundings), `static` (it is not affected by pushing of `top`, `bottom`, etc, it is the default), `fixed` (makes the element be fixed on the  screen and follows the scroll), `stick` (makes the element fixed from the stablished direction), `flex` (It makes the space being occupied to be modular, by default it will have all elements inside it to fix in one line).

`float:` is an outdated alternative to position, it works the same way.

 `top: ` `left`  `right`  `bottom` : All of them pushes the element from the toward the set direction by the set amount, position can't be `static` for it to work.
 
`z-index: ` defines the priority of the element. In case the element is `sticky`, it will tell how the element will stick to the screen.
 
` gap: ` Is utilized to define the size of the gap between elements, the first number is height, the second is width.

` order: ` Changes the order of the element, normally utilized with nth-child to select a specific element among many. Input the number where you want the element in, if you put a non-utilized negative number the
element will become first. You have to define the order of each element individualy as the default of all of them is 0.

 `transform:` Changes the element with properties, such as: `scale()` Multiplies the scale of the element by the number inside, `rotate` Rotates the element by the number inside, `translateY` Moves the amount in Y, `translateX` same thing but X.

 transition: ; Animates the transition of states of an element, must be put in the entire element, put first the seconds (you can write it as 1s for example) and then the       transition animation of choice, you can also put the characteristic you want to change in the first space to change only that specific characteristic.

 `minmax(minNumber, maxNumber)` Can be used in cases where numbers are input to dictate their minimum and maximum.

 `repeat(numberOfRepeats, input)` Repeats the input for the next elements based on the number of repeats, ex: repeat(3, 30px) will make the next 3 elements have 30px of size.

### Font configs:
`font-size:`  Size of the font in pixels.

`font-weight:`  Makes the font as thick as the number of the input.

`font-style:`  Puts your font in the desired style like Italic for example, this does not change your font to another font type.

 `text-decoration:`  Can add new details to your text, such as strikethrough, underline, and many others.
 
 `text-transform: ` Can be utilized to turn the entire text into Uppercase, Lowercase, or even automatically Capitalize letters as they should.
 
`text-align:` Changes the position of your text, such as `"center"`,`"left"`,`"right"`,`"justify"`.

 `text-family:` Changes the family of the font to the one asigned, Such as `"Arial"`, `"Times New Roman"`, etc. 
 
 You can put commas and add other fonts to put options of fonts that  will be searched in the computer in case the first font is not found. 
You can put more fonts by linking them in the original HTML with `<link rel="preconnect" href="" crossorigin>` where you insert the url of the font in the href. 


You can find these line of commands automatically on  Google  Fonts https://fonts.google.com. These links must  be put inside the `<head>`.
 
 text-indent: ; Creates a space between the left side and the first word of the text, used normally to start new paragraphs. The size is measured in pixels.


### Background configs:
`background-color:` defines the color of the background.
 
 `background-image url('')` Utilized to put images on the background from the following url, you can use the command without url to put images from the directory.
 
 `background-size:` Changes the size of the image, normally needs to be used to fit in the defined width and height. Certain commands can be used with it like: `"cover"` (which will automatically resize the image, but in case the proportion of the image does fit the width and height, it will cut the image), `"contain"` (will always displays the images on the proportionate size that fit in, but it will also always repeat them to fit the blank space unless prompted to not do so).
 
 `background-repeat: no-repeat` Turns off the repeat of images on uses like "contain".

 `background-position:`  Positions your background on the desired place, such as "center".

 `background-attachment: ` Attaches the background so it will always be displayed in some way, it can be configured in many ways such as `"fixed"` .


### Table configs:
`border-collapse: ""` Changes the type of the border, there is other types such as `Separate`, `Collapse`, etc.


### List configs:
 `padding-*insert direction*:` Defines the amount of pixels from the list markers, important because some markers are too close.

 `list-style:` Replaces the markers that stays at the left side of the list. `none`(Removes all markers but maintains padding-left), `circle` (changes them for a circle), `decimal-leading-zero` (adds a zero to the start of two digit numbers in ordened lists), `roman` (changes the list numbers to Roman numbers in ordered lists).


### @media configs:
 `@media` Refers to which properties/situations/devices will have special conditions, such as when printing the page with @media print.

 `@media screen` can be utilized with additionals after putting an "and" like: (min-width) [To influence in the minimum width of screen].
 
 `@media print` refers to the situation when the page is being printed.


 Button configs:
`<button>` Tag of button, you can put configs like: `onClick=()` [To define what happens on click, you can put a function in ReactJS]

 `cursor:` Defines the cursor hovering over the button.

 
### Animation configs:
 `@keyframe` Refers to animations, the name after it will be the name utilized by `Animation:` put inside of it the properties that it will diplay through the animation in percentage, like `0%{}` for start and `100%{}` to the end, put things inside the brackets like regular.
 
 `animation:` Controls the animations, use it like this: keyframeName secondsOfTheAnimation numberOfLoop. Must be put on the main element and not one of its states.

`animation-fill-mode:`

 `animation-direction:` Tells the direction the animation will follow, such as: alternate(Will alternate between the animation going towards the 100% or the 0%).


### Grid configs:
`grid-template-columns:` It chooses a template pattern for the columns, such things can also be values. Each value that is input is the values that will that will dictate the  each amount each  will occupy, inputing none will leave the default. It also sets the quantity if the number of rows wasn't set before it.

`grid-template-rows:` It chooses a template pattern for the rows, such things can also be values. Each value that is input is the values that will dictate the each amount each will occupy, inputing none will leave the default. It also sets the quantity if the number of columns wasn't set before it.

 `grid-area: insertName` To assign the ID of a grid area to an element, put it inside of an element, replace the name

`grid-template-areas:`  By writing the quantity of lines in it (blank by writing just rows with "") 

You define the amount of lines there is it, by utilizing the following configuration: 

`grid-template-areas-nameOfArea` (Where the name of the area was set in grid-area). To address to areas with `grid-template-areas:` inside of it, put the rows in order of apparence you want from top to down, and write from left to right the name of the `grid-area` defined before between them, such as `area1 area2 area3`,  you can also use a `.` to give a blank space, the `.` has a default flexible value, but by using gap in the same class you will define the amount of gap from the `.`, these define the amount of space each element in it occupy in display. 
 
 The number of all collumns and rows must be the same throughout all the lines defined by it. 
 Elements in the rows also can't reappear once they are gone in one of the rows.


 `row-gap:`  Specifies the gap size between rows of the grid.

`column-gap:`  Specifies the gap size between columns of the grid.


### flex configs:
`flex-wrap:` Utilized with position or display flex, with position it adjusts the element to be able to break lines, with display, it can be used to make a flex display that needs configuration. 
 
 You can use configurations such as: 
 
 `wrap` (Adjusts so the elements only wrap when the display by the user is small enough to require wrapping, which means that the elements only break lines when the user has a small enough display) 
 
`wrap-reverse` (Inverts the order of the rows), `nowrap` (Its the default, which makes so there is no line break and instead it makes the elements create a scroll when they don't fit), `flex-end`(Pushes all items the most to the right of the screen),.

 `flex-direction:` Makes so you can change the element in the direction your want, there is config such as: `column` (Extends through the entire screen width), `column-reverse` (like the logic of the wrap-reverse, it works like columns, but it reverses the order of the elements), `row-reverse` (Elements are displayed from right to left), `flex-end` (Pushes all items the to the most right side of the screen), flex-start(Pushes all items to the most left of the screen), etc.

 `flex-flow:`  Combines the use of flex-wrap and flex-direction, with the first input being of flex-wrap, and the second being of flex-direction.

 `flex-basis:`  Modifies the space the elements take in the display. Input the amount in the desired quantity.

 `flex:`  Makes the elements occupy all space available with the weight of the number typed.

`justify-items:`  Will adjust the position of the items based on the position you choose on the configs and your configuration on flex-flow/direction/wrap, such as: `Center, left, flex-end`(Pushes all items the most to the right of the screen), flex-start(Pushes all items to the most left of the screen), etc.

`justify-content:`  Will adjust the position of the contents based on the position you choose on the configs and your configuration on flex-flow/direction/wrap, such  as: `Center, left, flex-end`(Pushes all items the most to the right of the screen), etc. This works on the main axis.

`align-items:`  Align the items to occupy the designed space, Configs such as: Center, etc. This affects on the secondary axis. Can be used to correct flex-flow.

`align-content` Align the content to occupy the designed space, Configs such as: Center, etc. This affects on the secondary axis. Can be used to correct flex-flow.

## Javascript:

### Commands:
 `let VarName = ` defines the value of the variable.


## ReactJS:

### Other:
 `npm create vite` You can create a new ReactJS project by using the command in the powershell on visual studio code.
 
 `npm run dev` Executes the project and gives you the URL to access the project
 
 You can open the file easily by browsin the folder, or by utilizing "code ." on the powershell for the Visual Studio code do it automatically.
 
 The folder "Node Modules" has all the dependencies of your project.
 
 The folder "public" has the .svg for the logo of Vite.
 
 The folder "src" is where the source code is.
 
 "main.jsx" is the entry point of the project, if it has a import that does not exist anymore it will break the project.
 
 The project comes automatically with two `.css` for styling, you can delete them and make your own or just delete their contents.
 
 "assets" is the folder inside src where most of you code will be.
 
 React.js works like a mix of Javascript and HTML, where there is functions and classes, but its contents and commands can work with HTML, remember that the first letter  should be uppercase.
 
 You can create components like tags in HTML `<InsertNameHere />` and then you can call them by using `InsertNameHere` on functions and such.
 
 It is a good pratice to always create only one component by archive.
 
 To export your functions to be used by other archives do "export default FunctionName" in the end of the file out of the bracket.
 
 To import files, write import on the very start of the file, just like in c#.
 
 To create properties, attribute first a name for the main root where the properties will be like `function FunctionName(rootName)`, then access them inside the function by utilizing `(rootName.propertyName)`.
 
 You can modify properties by utilizing `<ComponentName property='value' />`.
 
 You have to import the useState to update constants, the command is: `import { use state } from 'react'`. You also need to export your function in the start of the file.
 
On ReactJS, one way to do the if in a simple manner is like this: `{ varName > number ? element/action : whatHappensIfElse}` in this everything before the `?` is the condition, and everything after is what happens when these conditions are fulfilled, and after `:` is the if else, in these ifs you also don't use `>=` `<=` but just `>` and `<`.
 
To put a list, you can use `<li>` but attributing ids to it, or to use functions, you attribute ids and values in it,values being the content and ids being their dentification.
 
Collateral effects are: Hooking information from website, filtering information, executing a functions in a certain time or each certain time.
 
To compare variables you have to do: var1.valuevar1.toLowerCase().includes.(var2.toLowerCase()), you can do if and else as normal too.

### Commands:
 `<input>` Commands:
 
 `<input>` it is a tag that defines that everything inside is an input to be recognized by the system.
 
`value={variableOfTheInput}` Defines the value of the input, must be defined to be used by onChange, you should define the variable before as `const [variableOfTheInput,  setVariableOfTheInput] = ''`.
 
`onChange={(e) => setVariableOfTheInput (e.target.value)}` gets what is written by the function that inputs value and puts it in the variable, you need to set the value before  it, the "e" supposedly can have any name.
 
 `variable.toLowerCase` Changes everything to lower case.
 
`variable.toUpperCase` Changes everything to upper case.

 `useEffect{()}`  Use the "() => {}" to equal what will happens with use as a function, in the end of it add the value that must be called back.
