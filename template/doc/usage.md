Notes:

Features listed here shouldn't be used yet, as they are not finalized and debugged.

Header ".abs" for ".oneline" still needs finalizing
Header ".sidebar" still needs finalizing

# Available Stylings
There are stylings for light and dark settings. Light is for a Light Background, and Dark is for a Dark Background.

All stylings are done by using CSS classes. By adding a class to an element, different styles can be achieved.

## Text sizes
Text in certain areas should have a set size.

### Site-wide title
Site-wide titles, as appearing in the div#title tag should be _5rem_

Article and Page titles, as appearing in titlecards and such should be _4rem_

## A word on being Mobile-friendly
In order to be more mobile-friendly, if the viewport has less than _767px_ of width, it will be switched over to the mobile format.

## Color Names and Definitions
All Colors are defined in the main.css file as CSS variables. These names are designated by purpose, and look of the color. This is done so that colors may be changed easily later on.

### Main Color Scheme
`#F0F7D4` - Off-white
`#BBE524` - Greenish
`#FF230F` - Red
`#2682A6` - Light Blueish
`#002C3D` - Dark Blue - Menu
Various Shades of Black, White, and Grey

### Colors Found
`#81a013` - Link Color

### Variable Names and Definitions
Note: [MDN Documentation on CSS Variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables)

Name (not including "--") - Value

off-white - `#F0F7D4`
green - `#BBE524`
red - `#FF230F`
light-blue - `#2682A6`
dark-blue - `#002C3D`
grey-1 - `#111`
grey-3 - `#333`
grey-80 - `#808080`
grey-e - `#eee`


## Title and Header
The Header can be configured to be a 2-lined bar at the top of the page, a single, transparent bar on the first element (useful if the first element is a flashcard or titlecard), or a sidebar.

This is done by making the `<header>` element a member of one of the following classes:

`.oneline` - Makes the Entire header into one line. Also has `.light` and `.dark` classes as well to help it blend in with the background

`.abs` - Positions the header bar on the first element (useful for flashcards or titlecards)

`.sidebar` - Positions the header bar as a sidebar. Be sure to make the `<main>` and `<footer>` tags a member of `.sidebar` as well to position them correctly.



### Title
Text here for h1 is large, as it is the title.
Text for p is smaller, as it is like a subtitle.

Use `<h1>` for the Actual Title Content, so the text is big.

Use `<p>` for the Subtitle

`.subtitle` - Small Grey Text for a subtitle

`.garnet` - Garnet colored text

`.blue` - Blue Text

`.black` - Black Text (Default)

### Menu Formatting
The menu can be configured to be a 2-lined bar at the top of the page, a single, transparent bar on the first element (useful if the first element is a flashcard or titlecard), or a sidebar.

## Content

### Navigation Bar
This goes below the titlecard, or title of the page. This contains a list of all links that go to each section of the article.

### Images and Figures
Images are automatically resized to fill the width of the part of the page that they are in. Optionally, a figure may also be added to describe an image.

For the Figure:

`<span class="figure"> Figure Name </span>` is the best way to name a figure, as the text will come out as grey.

### Link Styling
Links may be styled in the default way, where the text is green, and highlights when moused over, or they can be displayed as a button with rounded edges.

For Rounded Edges:

`a.button` -> Makes link a grey button. Can be colored...

`a.button.garnet` - Makes button Garnet

`a.button.acm-blue` - Makes button the ACM shade of Blue.

## Titlecards and Flashcards

Cards.css contains all styling for cards and such. By default, they will both be `#111` Grey. If an image is desired for the background, use the `.img` class, and specify the image in the tag styling in the document.

For Background Images: There are styles of `.light` and `.dark` to style the text to be clearer on top of the image.

## Flashcards
Flashcards take up a full viewport. 

## Titlecards
Titlecards take up a half viewport.

## Footer
Since the old layout used a table, the new one has moved to use a series of div elements. This makes it easier to write for mobile devices.

## Text Sections
Useful Sections to put text in. These can be used to add an announcement to just a page, or display an error or warning.

These can be found in `content.css`

### Usage

A Text section is only available in `<main>`. It should be the following:

```
<div class="ts">
  ... Content Here ...
</div>
```

Styling is available for a Header `<h1>`

### Other Text Sections

The Following Classes can be added to change the Text Section Style:

`.note` - A Green-styled Text Section that would be useful for adding a note.

`.warn` - Useful for displaying Warnings

`.err` - Useful for Displaying a Severe Warning or Error


