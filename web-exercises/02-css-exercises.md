# Part 2 – CSS Exercises (Absolute Beginner)

**Setup:** Use this starter `index.html` for all exercises (keep it, only edit `style.css`):

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>CSS Practice</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>My Title</h1>
  <p class="intro">This is the introduction paragraph.</p>
  <p>This is a normal paragraph.</p>
  <p id="special">This is a special paragraph.</p>
  <ul>
    <li>Item one</li>
    <li>Item two</li>
    <li>Item three</li>
  </ul>
  <a href="#">A link</a>
  <div class="box">I am a box</div>
</body>
</html>
```

Create an empty `style.css` next to it. Solutions are in `04-corrections.md`.

---

## Exercise 1 – Colors
- Make the `h1` red.
- Make every `p` dark blue (`navy`).
- Give the whole page a light gray background (`#f0f0f0`).

## Exercise 2 – Fonts and text
- Change the font of the whole page to `Arial, sans-serif`.
- Make the `h1` centered and 40px big.
- Make the paragraphs 18px with a line height of 1.6.
- Make the link have no underline.

## Exercise 3 – Selectors
- Make the paragraph with class `intro` green and bold.
- Make the paragraph with id `special` orange and italic.
- Make all `li` items purple.

## Exercise 4 – The box model
Style the `.box`:
- width 200px, height 100px
- 2px solid black border
- 20px padding
- 30px margin
- background color `lightyellow`

## Exercise 5 – Rounded corners and shadows
Add to `.box`: rounded corners of 15px and a soft shadow (`box-shadow`).

## Exercise 6 – Hover effects
- Make the link turn red when the mouse is over it.
- Make the `.box` change its background to `lightblue` on hover.

## Exercise 7 – Lists
- Remove the bullets of the list.
- Add 10px spacing under each `li`.
- Make the list items blue with a left border of 4px.

## Exercise 8 – Centering a box
Center the `.box` horizontally on the page (hint: `margin` and `auto`).

## Exercise 9 – Flexbox (first steps)
Change the HTML: put three `<div class="box">` inside a `<div class="container">`.
- Make `.container` use `display: flex`.
- Space the boxes evenly with a 20px gap.

## Exercise 10 – Mini project: Style a card
Create a "card" (a `div` with an `h2`, a paragraph and a link). Give it a white background, a border radius, a shadow, padding, a maximum width of 300px, and a hover effect that makes it lift slightly.
