# Corrections – All Exercises

> Your solution can differ and still be correct. What matters is that it works and looks like the request.

---
# PART 1 – HTML

## Exercise 1
```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>My First Page</title>
</head>
<body>
  Hello, World!
</body>
</html>
```
`<title>` goes in `<head>` (browser tab); visible content goes in `<body>`.

## Exercise 2
```html
<h1>About Me</h1>
<p>Hi, my name is Sam and I am learning web development.</p>
<h2>My hobbies</h2>
<p>I like reading, cycling and cooking.</p>
```

## Exercise 3
```html
<p>
  HTML is <b>really</b> fun to <i>learn</i> and <u>practice</u>.<br>
  This sentence is on a new line.
</p>
<hr>
```
(`<strong>` and `<em>` are also good choices for bold and italic.)

## Exercise 4
```html
<ul>
  <li>Apple</li>
  <li>Banana</li>
  <li>Orange</li>
  <li>Strawberry</li>
</ul>

<ol>
  <li>Boil the water</li>
  <li>Put the tea bag in the cup</li>
  <li>Pour the water and wait 3 minutes</li>
</ol>
```

## Exercise 5
```html
<a href="https://www.wikipedia.org">Visit Wikipedia</a><br>
<a href="https://www.wikipedia.org" target="_blank">Visit Wikipedia (new tab)</a><br>
<a href="mailto:hello@example.com">Send me an email</a>
```

## Exercise 6
```html
<a href="https://www.wikipedia.org">
  <img src="cat.jpg" width="300" alt="A cat sitting on a sofa">
</a>
```

## Exercise 7
```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
    <th>City</th>
  </tr>
  <tr>
    <td>Anna</td>
    <td>25</td>
    <td>Paris</td>
  </tr>
  <tr>
    <td>Tom</td>
    <td>30</td>
    <td>London</td>
  </tr>
  <tr>
    <td>Lea</td>
    <td>22</td>
    <td>Berlin</td>
  </tr>
</table>
```

## Exercise 8
```html
<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name"><br><br>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br><br>

  <label for="pwd">Password:</label>
  <input type="password" id="pwd" name="pwd"><br><br>

  <input type="radio" id="yes" name="answer" value="yes">
  <label for="yes">Yes</label>
  <input type="radio" id="no" name="answer" value="no">
  <label for="no">No</label><br><br>

  <input type="checkbox" id="terms" name="terms">
  <label for="terms">I agree to the terms</label><br><br>

  <button type="submit">Send</button>
</form>
```
Both radio buttons must share the same `name` so only one can be chosen.

## Exercise 9
```html
<body>
  <header>
    <h1>My Website</h1>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>

  <main>
    <article>
      <h2>Welcome</h2>
      <p>This is my first article.</p>
    </article>
  </main>

  <footer>
    <p>&copy; 2026 My Website</p>
  </footer>
</body>
```

## Exercise 10 (example)
```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>CV - Sam Martin</title>
</head>
<body>
  <h1>Sam Martin</h1>
  <img src="photo.jpg" width="150" alt="Photo of Sam">
  <p>Motivated beginner developer who loves building websites.</p>

  <h2>Skills</h2>
  <ul>
    <li>HTML</li>
    <li>Teamwork</li>
    <li>English</li>
  </ul>

  <h2>Education</h2>
  <table border="1">
    <tr><th>Year</th><th>Diploma</th><th>School</th></tr>
    <tr><td>2024</td><td>High School</td><td>Central High</td></tr>
    <tr><td>2026</td><td>Web Course</td><td>Online Academy</td></tr>
  </table>

  <p>Contact: <a href="mailto:sam@example.com">sam@example.com</a></p>
</body>
</html>
```

---
# PART 2 – CSS (all in `style.css`)

## Exercise 1
```css
h1 {
  color: red;
}
p {
  color: navy;
}
body {
  background-color: #f0f0f0;
}
```

## Exercise 2
```css
body {
  font-family: Arial, sans-serif;
}
h1 {
  text-align: center;
  font-size: 40px;
}
p {
  font-size: 18px;
  line-height: 1.6;
}
a {
  text-decoration: none;
}
```

## Exercise 3
```css
.intro {
  color: green;
  font-weight: bold;
}
#special {
  color: orange;
  font-style: italic;
}
li {
  color: purple;
}
```
`.` selects a class, `#` selects an id, no symbol selects a tag.

## Exercise 4
```css
.box {
  width: 200px;
  height: 100px;
  border: 2px solid black;
  padding: 20px;
  margin: 30px;
  background-color: lightyellow;
}
```

## Exercise 5
```css
.box {
  border-radius: 15px;
  box-shadow: 4px 4px 10px rgba(0, 0, 0, 0.3);
}
```

## Exercise 6
```css
a:hover {
  color: red;
}
.box:hover {
  background-color: lightblue;
}
```

## Exercise 7
```css
ul {
  list-style: none;
  padding: 0;
}
li {
  margin-bottom: 10px;
  color: blue;
  border-left: 4px solid blue;
  padding-left: 10px;
}
```

## Exercise 8
```css
.box {
  width: 200px;
  margin: 30px auto;
}
```
`auto` for the left/right margin only works if the element has a width.

## Exercise 9
HTML:
```html
<div class="container">
  <div class="box">One</div>
  <div class="box">Two</div>
  <div class="box">Three</div>
</div>
```
CSS:
```css
.container {
  display: flex;
  gap: 20px;
  justify-content: space-evenly;
}
```

## Exercise 10 (example)
HTML:
```html
<div class="card">
  <h2>Card title</h2>
  <p>Some short text inside the card.</p>
  <a href="#">Read more</a>
</div>
```
CSS:
```css
.card {
  background-color: white;
  border-radius: 12px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.2);
  padding: 20px;
  max-width: 300px;
  margin: 40px auto;
  transition: transform 0.2s;
}
.card:hover {
  transform: translateY(-5px);
}
```

---
# PART 3 – HTML + CSS together

## Exercise 1
HTML:
```html
<div class="card">
  <h1>Sam Martin</h1>
  <p>Web Developer</p>
  <p>sam@example.com</p>
</div>
```
CSS:
```css
body {
  font-family: Arial, sans-serif;
  background-color: #eee;
}
.card {
  width: 300px;
  margin: 50px auto;
  padding: 20px;
  border: 2px solid #333;
  border-radius: 10px;
  background-color: white;
  text-align: center;
}
```

## Exercise 2
HTML:
```html
<nav>
  <ul>
    <li><a href="#">Home</a></li>
    <li><a href="#">About</a></li>
    <li><a href="#">Services</a></li>
    <li><a href="#">Contact</a></li>
  </ul>
</nav>
```
CSS:
```css
nav {
  background-color: #222;
}
nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
}
nav a {
  display: block;
  color: white;
  text-decoration: none;
  padding: 15px 20px;
}
nav a:hover {
  background-color: #555;
}
```

## Exercise 3
HTML:
```html
<div class="gallery">
  <img src="1.jpg" alt="Picture 1">
  <img src="2.jpg" alt="Picture 2">
  <img src="3.jpg" alt="Picture 3">
</div>
```
CSS:
```css
.gallery {
  display: flex;
  gap: 15px;
}
.gallery img {
  width: 200px;
  border: 3px solid #333;
  border-radius: 10px;
}
```

## Exercise 4
HTML:
```html
<table>
  <tr><th>Product</th><th>Price</th><th>Stock</th></tr>
  <tr><td>Pen</td><td>$1</td><td>120</td></tr>
  <tr><td>Notebook</td><td>$3</td><td>45</td></tr>
  <tr><td>Backpack</td><td>$25</td><td>10</td></tr>
</table>
```
CSS:
```css
table {
  border-collapse: collapse;
  width: 100%;
}
th, td {
  border: 1px solid #ccc;
  padding: 10px;
  text-align: left;
}
th {
  background-color: #2a7ae2;
  color: white;
}
tr:nth-child(even) {
  background-color: #f2f2f2;
}
```

## Exercise 5
HTML:
```html
<form class="contact">
  <label for="name">Name</label>
  <input type="text" id="name">

  <label for="email">Email</label>
  <input type="email" id="email">

  <label for="msg">Message</label>
  <textarea id="msg" rows="5"></textarea>

  <button type="submit">Send</button>
</form>
```
CSS:
```css
.contact {
  max-width: 400px;
  margin: 30px auto;
}
.contact label {
  display: block;
  margin-top: 15px;
}
.contact input,
.contact textarea {
  width: 100%;
  padding: 8px;
  border: 1px solid #aaa;
  border-radius: 6px;
  box-sizing: border-box;
}
.contact button {
  margin-top: 15px;
  padding: 10px 20px;
  background-color: #2a7ae2;
  color: white;
  border: none;
  border-radius: 6px;
  cursor: pointer;
}
.contact button:hover {
  background-color: #1b5bb0;
}
```

## Exercise 6 (example solution)
HTML:
```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Sam - Landing Page</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h2>Sam Martin</h2>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Hi, I'm Sam</h1>
    <p>I am learning to build websites.</p>
  </section>

  <section id="about" class="about">
    <img src="photo.jpg" width="200" alt="Photo of Sam">
    <p>I love creating things on the web. I started learning HTML and CSS this year.</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <ul class="badges">
      <li>HTML</li>
      <li>CSS</li>
      <li>Teamwork</li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2026 Sam Martin</p>
  </footer>
</body>
</html>
```
CSS:
```css
body {
  margin: 0;
  font-family: Arial, sans-serif;
}
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px 30px;
  background-color: #222;
  color: white;
}
header a {
  color: white;
  text-decoration: none;
  margin-left: 15px;
}
header a:hover {
  color: #ffcc00;
}
.hero {
  background-color: #2a7ae2;
  color: white;
  text-align: center;
  padding: 80px 20px;
}
.about {
  display: flex;
  align-items: center;
  gap: 30px;
  padding: 40px;
}
#skills {
  padding: 0 40px;
}
.badges {
  list-style: none;
  padding: 0;
  display: flex;
  gap: 10px;
}
.badges li {
  background-color: #ffcc00;
  padding: 8px 16px;
  border-radius: 20px;
}
footer {
  margin-top: 40px;
  padding: 20px;
  text-align: center;
  background-color: #222;
  color: white;
}
```
