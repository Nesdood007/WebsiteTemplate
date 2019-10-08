# Requirements for MArkdown PReprocessing

Since all documents will be written in MArkdown, there are stylings that are not available in Markdown, and would require writing pretty much the entire document in HTML. Also, It's hard to make a Table of Contents for that automatically. In the interest of keeping things neat and eliminating weird fuckiness, we need to extend Markdown, perhaps using a Python Library.

All features should be implemented as a series of Plugins that can modify the Markdown AST Tree. Documentation should also be provided to make this easy to translate to another Markdown Platform.

Be sure to also include Static HTML Example Files to show how to generate the page correctly. We don't ever want to leave them in the dark with only a pile of CSS to go off on.

## Table Of Contents

This is a method to list Headings in the Document, and be able to generate Links somewhere in compliance with the Website Template.

## HTML Classes and things

A Way to insert things that aren't in the Markdown Spec. In the case of this template, this would be the Gradient Titlecards and Flashcards, TextSections, etc.
