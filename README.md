# HTML-CSS7-1flex-active

html Explanation:
<!DOCTYPE html>: Declares the document type and version of HTML.
<html lang="en">: Defines the root element of the HTML document with the "en" language attribute.
<head>: Contains metadata and links to external resources for the web page.
<meta charset="UTF-8">: Specifies the character encoding for the document as UTF-8.
<meta name="viewport" content="width=device-width, initial-scale=1.0">: Sets the viewport properties for responsive design.
<title>Document</title>: Sets the title of the web page displayed in the browser tab.
<link rel="stylesheet" href="styles.css">: Links an external CSS stylesheet to style the page.
<body>: Contains the visible content of the web page.
<main>: Represents the main content section of the page.
<nav>: Defines a navigation section within the page.
<div class="alignCenter">: A div container with a class for centering its contents.
<img class="profilePic" src="..." alt="">: An image element for displaying a profile picture.
<h4 class="margin0">Name Surname</h4>: Heading level 4 with a class for styling and text "Name Surname."
<h5 class="margin0">Pro Member</h5>: Heading level 5 with a class for styling and text "Pro Member."
<div class="alignleft">: A div container with a class for left-aligning its contents.
<div class="display marginx">: A div container with classes for styling.
<img src="" alt="icon">: An image element for displaying an icon.
<h3 class="margin0">Streams</h3>: Heading level 3 with a class for styling and text "Streams."
<section>: Defines a section within the page.
<h1 class="position">Active Games</h1>: Heading level 1 with a class for positioning and text "Active Games."
<div class="avgall"></div>: A div container with a class for styling.
<div class="display bg2">: A div container with classes for styling.
<img class="imggame" src="" alt="img">: An image element for displaying a game image.
<h1>Assassins Creed Valhalla</h1>: Heading level 1 with text "Assassins Creed Valhalla."
<h4>PS5 Version</h4>: Heading level 4 with text "PS5 Version."
<h6 class="avgall percent"></h6>: Heading level 6 with classes for styling.
<h1>60%</h1>: Heading level 1 with text "60%."

css explanation-
body: Styles applied to the entire document's body.

margin: 0;: Removes any default margin.
background-color: #c8f3ea;: Sets the background color to a light blue-green shade.
box-sizing: border-box;: Ensures padding and borders are included in element size calculations.
*: Styles applied to all elements.

margin: 0;: Removes default margin for all elements.
main: Styles applied to the main content section.

display: flex;: Uses flexbox layout.
color: rgb(75, 143, 143);: Sets text color to a shade of teal.
nav: Styles applied to the navigation section.

width: 20vw;: Sets the width to 20% of the viewport width.
background-color: #e5fffb;: Sets the background color to a pale teal shade.
min-height: 100vh;: Sets a minimum height of 100% of the viewport height.
border-radius: 35px;: Rounds the corners with a 35px radius.
display: flex;: Uses flexbox layout.
flex-direction: column;: Stacks child elements vertically.
justify-content: space-around;: Distributes child elements evenly with space around.
align-items: center;: Centers child elements horizontally.
.profilePic: Styles applied to profile pictures.

height: 6rem; width: 6rem;: Sets a fixed height and width.
border-radius: 50%;: Rounds the image into a circle.
.alignCenter: Styles applied to elements for center alignment.

text-align: center;: Centers text content horizontally.
.margin0: Styles applied to elements to remove margins.

margin: 0;: Removes any margin.
.display: Styles applied to elements for display and layout.

display: flex;: Uses flexbox layout.
gap: 1rem;: Adds a 1rem gap between child elements.
justify-content: left;: Aligns child elements to the left.
margin: 1rem;: Sets a 1rem margin around the element.
.maxwidth: Styles applied to elements for maximum width.

max-width: 40%;: Limits the maximum width to 40% of the parent container.
align-items: center;: Centers child elements vertically.
.imgsize: Styles applied to image elements for a fixed size.

width: 30%;: Sets a fixed width of 30%.
.bg: Styles applied to elements with a background color.

background-color: rgb(150, 246, 246);: Sets the background color to a light teal shade.
border-radius: 8px;: Rounds the corners with an 8px radius.
section: Styles applied to the main content section.

width: 75vw;: Sets the width to 75% of the viewport width.
display: flex;: Uses flexbox layout.
flex-direction: column;: Stacks child elements vertically.
gap: 1rem;: Adds a 1rem gap between child elements.
margin-top: 4rem; margin-left: 7%;: Sets top and left margins.
.position: Styles applied to elements for text positioning.

font-size: 2.5rem;: Sets the font size to 2.5rem.
font-weight: 900;: Sets the font weight to 900 (bold).
.avgall: Styles applied to elements for an average display.

background-color: #e5fffb;: Sets the background color to a pale teal shade.
height: 1.5rem; width: 20rem;: Sets fixed height and width.
border-radius: 12px;: Rounds the corners with a 12px radius.
margin-bottom: 10%;: Sets a bottom margin of 10%.
.bg2: Styles applied to elements with a background color and layout.

width: 80%;: Sets the width to 80% of the parent container.
background-color: #e5fffb;: Sets the background color to a pale teal shade.
padding: 1.5%;: Adds 1.5% padding.
border-radius: 12px;: Rounds the corners with a 12px radius.
gap: 0%;: No gap between child elements.
justify-content: space-between;: Distributes child elements evenly with space between.
align-items: top;: Aligns child elements to the top.
.imggame: Styles applied to game images.

width: 3.5rem; height: 3.5rem;: Sets a fixed width and height.
background-color: rgb(23, 2, 2);: Sets a dark background color.
.percent: Styles applied to elements displaying percentages.

width: 100%;: Sets the width to 100%.
background-color: #89f8e0;: Sets the background color to a light green shade.
margin: 4%;: Sets a 4% margin.
.marginx: Styles applied to elements with top and bottom margins.

margin-top: 4rem; margin-bottom: 4rem;: Sets top and bottom margins of 4rem each.
