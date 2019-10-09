# Semantic HTML Layout

Another goal of WTv2 is to make the HTML more semantic so as to be more accessable to those using screen readers, and online robots and content clippers. This will put the use of our HTML elements closer to that of the w3c HTML5 spec.

https://schema.org/

https://html.spec.whatwg.org/multipage/

https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/itemprop

    - Usage of the `itemprop` attribute is not required for Hand-written things, but could be added by a Static Site Generator

classes will be used to define what purpose an element will be serving.

The WT format will be converted to more of that of a framework to be used in building other applications. Since it already mostly conforms to semantic layout structures, this isn't as important as refactoring the CSS and implementing CSS Vars for all colors

## Blog Post (https://schema.org/BlogPosting)

<article>
    <header>
        <h1> Title </h1>
        <div> metadata </div>
    </header>
    <p> Blah Blah... </p>
    <section>
        <h2> Comments </h2>
        <article>
            <p> comment here </p>
        </article>
    </section>
</article>

## ARticle Preview on a landing page

<article>
    <header>
        <h1> Title </h1>
        <div> metadata </div>
    </header>
    <p> Some Blah Blah... </p>
    <div> Read More </div>
</article>

