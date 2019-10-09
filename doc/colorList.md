# Complete List of Colors used in WebTemplate 

This is a complete list of colors used in WT. This was compiled to help with re-organizing colors into CSS Variables

## article.css

article h1: `#2682A6`
    - Title Link for an article
    - Link always stays this color
    :hover: `#82c7e3`

article .info: `#333`
    - Inforamtion/metadata for an article

article .tag: 
    - Tags for an article
    - @background: `#F0F7D4`
    - @box-shadow: `#777`
    - @color: `black`

    .green:
        - @background: `#dcf28d`
    .red:
        - @background: `#ff8a80`
    .blue:
        - @background: `#97d1e7`
    .orange:
        - @background: `#fecc81`
    :hover
        - @color: `#333`
        - @box-shadow: `#999`

article .continue:
    - "Continue Reading" Button at bottom of article
    - @color: `black`
    - @background: `#ccc`
    :hover
        - @background: `#eee`
        - @color: `#333`
    
## cards.css

- This file contains the flashcards (full screen height), and titlecards (half screen height)
- Flashcards are implemented as `<section>` tags.

section.flashcard
    - @background: `#111`
    - @color: `white`

    .rainbow : `rgb(255,35,15); background: linear-gradient(146deg, rgba(255,35,15,1) 0%, rgba(38,130,166,1) 50%, rgba(187,229,36,1) 100%);`
        - I think these are the 3 main Accent Colors
    .red-orange
        - `rgba(255,81,0,1)`, `rgba(255,35,15,1)`
    .blue-green
        - `rgba(187,229,36,1)`, `rgba(38,130,166,1)`
    .grayscale
        - `rgba(51,51,68,1)`, `rgba(153,153,170,1)`
        - This is blue-baised gray
    .grayscale-light
        - `rgba(255,255,255,1)`, `rgba(159,159,159,1)`
    .garnet
        - `rgba(36,0,0,1)`, `rgba(115,0,10,1)`, `rgba(161,119,119,1)`
        - This doesn't match the existing color scheme
    
## content.css

## footer.css

## form.css

## header.css

## main.css

## print.css

## sharebar.css