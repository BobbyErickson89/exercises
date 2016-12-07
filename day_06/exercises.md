## Knowledge Based

- Student can explain the terms “DOM” and “Node”
- Student can explain how the Document Object Model maps to HTML
- Student can explain how the Window object is connected to all JavaScript objects in an active web page


#### Questions

1. What does the acronym DOM stand for?
2. Explain the term **Node** as it relates to the DOM.
3. How does the DOM help us select and manipulate things in our HTML?
4. What is the window object?
5. How does the window object help connect everything together?


## Skill Based

- Student can use jQuery to select elements of a page using the same CSS selectors listed in the CSS section
- Students can use built in jQuery functions to edit the state of existing HTML elements


#### Exercise 1

Using the HTML below, write the jQuery code to select the following items. Also, make sure to store each selection in a variable and `console.log` out results.

1. Select the element with a class of `container`.
2. Select the `h1` tag
3. Select the element with a class of `site-text`.

```html
<!DOCTYPE html>
<html>
<head>
  <title>First jQuery Project</title>
</head>
<body>
  <div class="container">
    <h1>Hello jQuery</h1>
    <p class="site-text">Lorem ipsum dolor sit amet, consectetur...</p>
  </div>
</body>
</html>
```

#### Exercise 2

Using the HTML from Exercise 1, select the `h1` element and using the `.css` jQuery method, apply a background color to that element.

#### Exercise 3

Copy the following HTML & CSS to a project and then preform the following steps.

1. Select the element with a class of `color-change`
2. Add a _click event_ listener to it 
3. When clicked, change the background color of the `box` element to red.


```html
<!DOCTYPE html>
<html>
<head>
  <title>Color Change</title>
</head>
<body>
  <div class="container">
    <div class="box"></div>
    <button class="color-change">Change Color</button>
  </div>
</body>
</html>
```

```css
.box {
  background-color: blue;
  width: 200px;
  height: 200px;
  margin-bottom: 15px;
}
```


#### Exercise 4 (Hard)

Using the following HTML & CSS, write the JavaScript (jQuery) to make all the boxes change background color when any other box is hovered. For instance, if you hover the box with a `data-color` of `orange` then all boxes will be come orange. When you hover off of it, then you all the boxes will go back to being `black`.

Here is a screenshot of what this looks like:

![](https://tiy-learn-content.s3.amazonaws.com/db867853-boxes.gif)

```html
<!DOCTYPE html>
<html>
<head>
  <title>Color Boxes</title>
</head>
<body>
  <div class="container">
    <div class="box-area">
      <div class="box" data-color="green"></div>
      <div class="box" data-color="red"></div>
      <div class="box" data-color="blue"></div>
      <div class="box" data-color="orange"></div>
      <div class="box" data-color="grey"></div>
    </div>
  </div>
</body>
</html>
```

```css
.box {
  width: 100px;
  height: 100px;
  float: left;
  margin: 5px;
  background-color: black;
}

.box-green { background-color: green; }
.box-red { background-color: red; }
.box-blue { background-color: blue; }
.box-orange { background-color: orange; }
.box-grey { background-color: grey; }
```
