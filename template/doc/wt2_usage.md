# WT2 Usage

Since there are some changes to how WT works for v2, here is how to use it.

## Main Changes

Improvements to the CSS Framework can be categorized as follows:

- Modularity

    * the CSS files were refactored

    * `main.css` had some features moved to other files to make it better serve the purpose of being a boilerplate file.

- Clean

    * Code Quality has been improved

    * Unused Features have been removed

- Simplify

    * Some of the original HTML Tag requirements have been revised, allowing for an easier, painless scaffolding of apps and websites using the style framework.

## Files and Features

### main.css

- boilerplate
    - HTML Tags, including: h1-h6, p, a, etc.
        - All Headers can have a Vertical Bar or a Horizontal bar by using `.vbar` and `.hbar` respectively
    - Core CSS classes:
        - .container : A responsive margin for the content on the page. Resizes depending on screen size
        - .accent-1 - .accent-4 : Colors the text with the associated Accent Color
        - .invert : Swaps the foreground and background colors for a header. Can work with the .accent-X classes
        - .hide-for-print : Hides the element when printing
    - Color Variables
        - accent-1 : Accent Color 1
        - accent-2 : Accent Color 2
        - accent-3 : Accent Color 3
        - accent-4 : Accent Color 4
        - light-color : A Light Color
        - dark-color: A Dark Color
        Other Purpose variables are also here, serving as an organized way to set colors for Elements, Dark Mode, etc.