# Exercises - just for practise

## Basic_CSS_Exercises


### Breaking the flow

1. Create an empty box with the class of `halloworld`. The box should have a width and height of 200px. Inside the box, add the text "Hallo World" and change the background color to orange.

2. Center the `halloword` box in the middle of the screen.

3. Move the `halloworld` box 5 pixels to the left and 7 pixels down from the center position.
**Hint**: For centering elements in HTML try using the margin property. 

4. Add another square box with the class of `box1`. The box should have a width and height of 200px and a red background color. Position the box at the bottom-left of the screen.

5. Add another square box with the class of `box2`. The box should have a background color of rgb(0, 255, 85) and a height and width of 200px. This box should be positioned at the bottom-left of the screen, but should be 10px higher and 10px more to the right than `box1`.

6. Add a third box with a class of `box3`. It should have a background color of rgb(0, 183, 255). It should be positioned at the bottom-left of the window, but should be 10px higher and 10px further right than `box2`. 
![reference-image](/Exercises/UIB-layout-break-out-the-flow/images/reference-image1.png)

7. Place `box3` **behind** `box2`.
![reference-image](/Exercises/UIB-layout-break-out-the-flow/images/reference-image2.png)


Created: 21.07.2020

<hr>

### Flexbox: Responsive Navigation Bar

Create a page with a navigation bar at the top that is horizontal and right-aligned on screens larger than 800px, horizontal and evenly spaced on screens between 500px and 800px, and laid out in a column on smaller screens.

Created: 20.07.2020

<hr>

NOT finished

### Movie Genres (UIB layout out of ordinary)

1.  Create a section with the class `genres`. Make it a flex-container.
2.  Inside the flex-container, create 6 sections with the following content and background-colors. They should be created in the following order:
    - Action → dodgerblue
    - Thriller → rgb(190, 178, 178)
    - Comedy → rgb(255, 214, 30)
    - Horror → black
    - Drama → darkgrey
    - Romance → red
3.  For each section, center the font.
4.  Each flex-item should have a basic width of 500px and a fixed height of 100px. By default, each flex-item should take up all extra space.
5.  Now, make an exception for "thriller" and "comedy", Both sections should take up 10 times the amount of extra-space of their adjacent element.
    
**Hint**: Consider using flex-wrap.

![reference-gif](/Exercises/UIB_layout_out_of_ordinary/images/example.gif)

Created: 20.07.2020

<hr>

### Layout Planning  (without computer)

* Create a **rough** pen and paper layout for mobile, tablet and desktop for the same site. 

* The site must include: 
    - A header
    - A nav bar 
    - Cards containing info 
    - Footer  

Created: 20.07.2020


<hr>

### Let's make a webpage! (berlin)

The image assets you need to create the page below can be found in the <a href="assets">assets directory</a>.

Website:

![reference-png](/Exercises/berlin/big.png)

## Working with the browser developer tools

As you check what your HTML looks like when the browser renders it, familiarize yourself with the browser's developer tools. They allow you to inspect your HTML and CSS and try out changes! If you're using Chrome, you can learn more about its dev tools [here](https://developers.google.com/web/tools/chrome-devtools/inspect-styles/?utm_source=dcc&utm_medium=redirect&utm_campaign=2016q3).

## BONUS: Part 2

As a next step let's make our webpage display nicely on phones.

<img src="mini.png" alt="webpage">

**_NOTA BENE_**: Try do not use `display: flex` or `display: grid` for this project. We will discuss Flexbox and Grid in due course. For now, please stick to the techniques discussed [here](https://www.w3schools.com/css/css_positioning.asp).

Created: 16.07.2020


<hr>

### Flex (UIB layout flex)

* 01: Use flexbox to align all divs in a row. Use wrap so that the divs appear on multiple rows. Center the rows in the container
* 02: Use flexbox to align the divs in a row. Reverse the order of the divs.
* 03: Use flexbox to display all divs in a column in reverse order on the center of the page. 
* 04: Use flexbox to display all divs in a row at the bottom of the container. Make the divs only take up one line.
* 05: Use flexbox to display the divs on one row in the center of the container.
* 06: Use flexbox to display all divs in one column in the center of the page.

**Note**: Instructions can also be found in the css file for each exercise. 

Created: 14.07.2020

<hr>

### What's your background? (UIB boxmodel backgroundimages)

**Note**: The task starting files can be found in the corresponding folder names. Each task folder contains the necessary assets.

* Task 1: Add the `background.jpg` in the assets folder as a background image to the header. Set the size to contain and make sure the image repeats across the header. 

![task1-reference](./Exercises/UIB-boxmodel-backgroundimages/images/task1.png)

* Task 2: Add the background images in the assets folder to each of the sections with the classes of `info-1`, `info-2` and `info-3` (make sure to use a different image for each section). Set the size of the background to cover the whole section element. Make sure that the background does not repeat and that the position is set to bottom. Make sure that you **DRY**.  

**Bonus for task 2**: 
* Add padding to the sections. 
* Make the sections appear side-by-side. 
* Add a border radius to the sections.

![task1-reference](./Exercises/UIB-boxmodel-backgroundimages/images/task2.png)

Created: 14.07.2020


<hr>


### Design Mockup (piano page)

Use the given images, create a page that looks like the design-mockup:

![reference-task1](./Exercises/piano_page/images/design-mockup.png)

Created: 14.07.2020

<hr>

NOT Finished 

### They see me scrolling (UIB boxmodel flow)

**Task 1**
* The sections with the class `esports-info` need to be styled. 
* First of all, give each section a set height and width.
* Give each section a border. 
* Set the size of the images. 
* Allow the user to scroll through the information on each section. 
![reference-task1](./Exercises/UIB-boxmodel-flow/images/reference-task1.png)

**Task 2**
* Make the image and paragraphs in the section with the class `esports-tournaments` appear side-by-side using float. 
![reference-task2](./Exercises/UIB-boxmodel-flow/images/reference-task2.png)

![reference-task](./Exercises/UIB-boxmodel-flow/images/reference.png)

Created: 13.07.2020


<hr>

### Model the Boxes (UIB boxmodel modellingboxes)

1. Create `html` and `css` files. Work from there.

2.  Create the layout shown in the image below:
   
    ![mockup](/Exercises/UIB-boxelmodel-modellingboxes/mockup.png)


3.  Use `<header>`, `<main>`, `<footer>`, `<aside>` to structure the html page.

Created: 13.07.2020

<hr>

### Contain Yourself (UIB boxmodel containing)

* Style the header so that is takes up 100% of the viewport height. 
* Add the `container.jpg` image from the [images folder](/Exercises/UIB-boxmodel-containing/images/) to the `img` tag found in the header.
* Style the image to take up 100% width and height of the header. 
![header-mock](/Exercises/UIB-boxmodel-containing/images/header.png)
* Give the `main` element a class of `container`. 
* Choose a font from google fonts and apply it to the page.
* Select the `container` class. Give it a width of 80% and center it in the middle of the page.
![main-mock](/Exercises/UIB-boxmodel-containing/images/main.png)


Created: 13.07.2020

<hr>

### Block vs. Inline:

    Create an index.html file with 3 paragraphs, each containing the words “This is a paragraph”.
    Draw a border around each element.
    In one of the paragraphs, enclose one word in <em> tags and another one in <strong> tags.
    Inspect a paragraph in DevTools. Change its width and height.
    Inspect the <em> element in DevTools.  Try to change its width and height.  What do you notice?
    Now set the display property of the <em> element to “block” and try again to change its width and height.  What do you notice?
    Change the display property of the paragraphs to “inline”.
    Inspect a paragraph with DevTools and try to change margin and padding.  What changed?
    Undo the changes to the display properties.
    Wrap all elements in a <main> element and give <main> a width of 80%.
    What can you infer about the default width of block-level elements like paragraphs?
    Change the display property of the <em> and <strong> elements to “block”.  Change their margin and padding.  Now change the display property to “inline-block”.  How does this differ from “display: block” and “display: inline”?
    Give the <em> and <strong> elements a display property of “inline” and the paragraphs a display property of “block”.
    Give a paragraph a width of 300px and a padding of 20px.  Inspect the result with DevTools.  Which of the boxes associated with this paragraph  (content-box, padding-box, border-box, margin-box) has a width of 300px?
    (Bonus) Ensure that, for any (current or future) element on this page, width applies to the border-box.

Created: 13.07.2020

<hr>

### Exercise: CSS Selectors 1

1. Select all h3 elements and change the elements' color to blue.
2. Select list items 3-5 in task 2 using classes. Change the elements' color to red.
3. Select the sibling of the first image using a combinator. Give the image a border.
4. Select the link ending in .com with an attribute selector. Give it a yellow background color.
5. Give "Task 5" (_this_) list item an id and change the color of the text.

![alt-text](/Exercises/css_selectors_1/image/reference-image.png "Reference Image")


Created: 7.7.2020

<hr>

### Descendant Selectors

1. Modify the given page to make it look like the mockup.

![alt-text](/Exercises/descendant-selectors/mockup.png "Reference Image")

Created: 6.7.2020

#### Used:

classname em
div .classname:first-of-type em
p:nth-child()
div:nth-child(odd)
div:nth-child(even)


<hr>

### CSS Pseudo Classes

1.  Create an empty HTML page with charset, title, etc.
2.  Add buttons for 3 search engines of your choice, using different colors.
3.  Add a list of links to 3 articles about web stuff that you like. Make sure that the articles open up in a new tab.
4.  Use the pseudo classes for all elements, to enhance usability.
5.  Add some additional styling to your page e.g. background colors.

![alt-text](/Exercises/css_pseudo_classes/image/reference-image.png "Reference Image")

Created: 6.7.2020

#### Used:

CSS:<br>
<br>
color<br>
background<br>
border-color<br>
text-decoration<br>
background-color<br>
text-align<br>
margin-top<br>
font-family<br>

.class {}<br>
a:hover {}<br>
a:visited {}<br>
a:link {}<br>
body {}<br>
body button {}<br>
input[tpye=button] {}<br>
h1, h2 {} 

<br>
HTML:<br>
p<br>
button<br>
class<br>
links<br>
link target (_blank)<br>
article<br>
cursor

Created: 6.7.2020

<hr>

### Assignment pseudo_classes (assignment 06072020)

    1. all paragraphs with a class of “dull” 
    2. all elements that have both a “todo” class and an “urgent” class
    3. all elements with a “todo” class or an “urgent” class or both
    4. all first paragraphs within <article> tags
    5. all links that have been visited
    6. the first line of any paragraph in any article element
    7. the first line of the first paragraph in any article element
    8. all paragraphs inside articles in the body
    9. all paragraphs inside elements with class “box”
    10. all paragraphs that are children of article elements
    11. all images that immediately follow paragraphs
    12. all images that are siblings of paragraphs
    13. all list items with class attribute “special” that are children of unordered lists

Created: 6.7.2020


<hr>

### table of contents

1. Add a unique id to each heading tag in the page, make the id as descriptive as possible.

2. Wrap the text in the table of contents in an ordered list so that each main heading and its sub headings are in the same list.

3. In each list item under the main heading text, add another **nested** ordered list so that each sub heading is wrapped in a list item.

4. For each of the list items in the table of contents, add an anchor link that wraps around the text. when the link is clicked, the page should scroll to that heading.

5. At the end of each section in the text, before the next sub heading, add a "Back to top" link, that scrolls the page back to the top.

6. Change the nested list numbering to roman numerals.

Created: 30.6.2020

<hr>

### git practise 1+2 

in linux

not much to see, but it was: <br>
general terminal commands<br>
adding files<br>
remote add<br>
add<br>
commit<br>
push<br>
status<br>
log<br>
deleting files<br>
hiding files with .gitignore

Created: Juni 2020

