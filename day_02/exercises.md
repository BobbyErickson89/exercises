## Knowledge Based

- Student can explain the box model and how height/width, border, margin, and padding effect it.
- Student can explain why coding for accessibility is important
- Student can identify common accessibility strategies when producing HTML pages


#### Questions

1. Why is accessibility an important thing to keep in mind as you develop a website?
2. What is the Box Model when referring to CSS and how can it affect our layout?
3. Given the standard Box Model, what properties add together to calculate the "total" height and width of a page element?


## Skill Based

- Student can use child selectors for targeted styling of sequential content
- Student can apply font styles to elements such as size, color, family, style, and decoration.
- Student can calculate “total” dimensions of an HTML element using the standard box model


#### Exercise 1

Create an `index.html` file and add the following HTML inside of the `body` tag and then apply the styles to it found in [this screenshot](https://tiy-learn-content.s3.amazonaws.com/ae050ba1-first_website.png).

Here are the colors:

- Header Background: `#343e3d`
- Header Font Color: `#cfffe4`
- Header Border Color: `#617466`
- Body Font Color: `#28261c`

```html
<header>
  <h1>My First Website</h1>
</header>
<section>
  <article>
    <img src="http://placehold.it/600x200" alt="Picture Description">
    <h2>Article Title</h2>
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. In optio nam doloremque ad necessitatibus consectetur quia laudantium expedita libero natus fugiat, nihil perspiciatis laborum, fuga, aliquam porro modi eaque doloribus!</p>
  </article>
</section>
```

#### Exercise 2

Given the following HTML, please fix the errors and change some of the tags to make use of the better semantic tags that HTML provides.

```html
<body>
<div class="container">
  <div class="header">
    <img src="http://placehold.it/100x50">
  </div>
  <div class="content-section">
    <h1>Blog Post Title</h1>
    <div class="article">
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam...</p>
      <h1>Sub Title</h1>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
      tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam...</p>
    </div>
  </div>
  <div class="footer">
    Copyright 2016 | All Rights Reserved
  </div>
</div>
```

#### Exercise 3

Calculate the "total height" and "total width" of each styled element, e.g. `.hero-unit`, `.sidebar`, `header`.

```css
.hero-unit {
  height: 400px;
  width: 900px;
  padding: 25px;
  margin-bottom: 15px;
  border: 2px solid rgb(158, 123, 254);
}

.sidebar {
  height: 130px;
  width: 320px;
  padding: 25px 15px;
  margin: 5px;
  border-right: 1px solid red;
  border-bottom: 2px solid green;
}

header {
  height: 90px;
  width: 800px;
  padding: 12px 32px;
  margin: 12px 10px 20px 15px; 
  border-right: 1px solid red;
  border-left: 2px solid red;
  border-bottom: 4px solid green;
}
```







