# Review

## HTML

One of the better examples so far. A bit claustrophobic, however. Without going overboard, let's use a bit of whitespace to make it more readable. Also, be careful about indentation. If you are *inside* another element, then indent an additional two spaces. Examples:

```html
<header>
<h2>Article title 1 </h2>
</header>
```

Should be:

```html
<header>
  <h2>Article title 1</h2>
</header>
```

Note: no need to space between tag and content.

In one article you have this:

```html
<p> This is the first paragraph of the first article. </p>
```

And in another, this:

```html
<p>
This is the first paragraph of the second article.
</p>
```

It should be either this:

```html
<p>This is the first paragraph of the first article.</p>
```

(No space between tag and content.) Or this:

```html
<p>
  This is the first paragraph of the second article.
</p>
```

(Content indented two spaces.)

And what happened to your opening `<footer>` tag on line 49?

Also, let's give your CSS some room to breath by turning this:

```css
<style type="text/css" media="all">
  p {color: rgb(17, 38, 84);
  font-family: "helvetica", sans-serif;}
  h1 {font-family: bold, "helvetica", sans-serif;
  color: black;
  border: 4px groove rgba(22, 106, 106, 0.8);
  }
</style>
```

Into this:

```css
<style type="text/css" media="all">
  p {
    color: rgb(17, 38, 84);
    font-family: Helvetica, sans-serif;
  }

  h1 {
    font-family: Helvetica, sans-serif;
    font-weight: bold;
    color: black;
    border: 4px groove rgba(22, 106, 106, 0.8);
  }
</style>
```

Pretty impressive CSS, by the way. Have you done this before?

## Accessibility

Looks good. Any questions?

## Usability

Nicely done.

## Empathy

What is the other book you're reading?

Don't be too sure that mindfulness is all that easy! :-)

Overall, outstanding work, Keep it up.

Please clean up the HTML and commit your changes. Thanks!


