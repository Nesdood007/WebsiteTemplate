# WebsiteTemplate
This is a Template for a Website that I am designing for both myself and the ACM Chapter at USC

## Sources

Fonts: League Mono - https://github.com/theleagueof/league-mono

Icons: Open Iconic - https://github.com/iconic/open-iconic

Color Palette Source - https://www.w3schools.com/colors/colors_compound.asp
    - Note that the original Color Palette isn't exactly what is the default, but it was similar

## The WT2 Update

I have changed a number of things to make this template more modular and malleable into different workflows. This is done with the following:

Moving Core Components into `main.css`, such as:

* CSS Variables for Colors

* Fonts

* Boilerplate, such as styling for all basic HTML Elements

* Changed Sizing of Certain Elements

Making the other stylesheets Modular:

* Preventing Conflicts by using CSS classes for everything, making styles more compatible in the HTML Implementation

* Reducing the number of extraneous files to import for certain functionality