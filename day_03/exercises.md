## Knowledge Based

- Student can explain what happens to elements when `float` is applied to it.

#### Questions

1. Name any reasons why an element should be floated.
2. How does changing the value of `float` property from `left` to `right` affect the behavior of an element?
3. How do the properties `clear` and `float` work together to affect the page layout?

## Skill Based

- Student can use floats to arrange page elements into a column layout.

#### Exercise 1

In the following example, have students decide which element should be cleared to move the `.content` element below the row of buttons.

```html
<section class="clearfix">
  <div class="buttons">
    <button>One</button>
    <button>Two</button>
    <button>Three</button>
  </div>
  <div class="content">
    <p>This should appear below the three buttons, not to the right of it.</p>
  </div>
</section>
```

```css
button {
  float: left;
  margin: 5px;
}
```

#### Exercise 2

Using [this screenshot](https://tiy-learn-content.s3.amazonaws.com/f7ebc7ac-columns.png) and the HTML below, add the CSS needed to make the `.product` elements align in three columns.

```html
<!DOCTYPE html>
<html>
<head>
  <title>Cool Products</title>
</head>
<body>
  <div class="products">
    <div class="product">
      <img class="product-image" src="http://placehold.it/200x200" alt="My Cool Product">
      <h3 class="product-name">My Cool Product</h3>
      <p class="product-price">$100</p>
    </div>
    <div class="product">
      <img class="product-image" src="http://placehold.it/200x200" alt="My Cool Product">
      <h3 class="product-name">My Cool Product</h3>
      <p class="product-price">$100</p>
    </div>
    <div class="product">
      <img class="product-image" src="http://placehold.it/200x200" alt="My Cool Product">
      <h3 class="product-name">My Cool Product</h3>
      <p class="product-price">$100</p>
    </div>
  </div>
</body>
</html>
```

#### Exercise 3

Copy the following HTML & CSS into a new project and fix the problems caused by floating some of the elements. It should look like [this](https://tiy-learn-content.s3.amazonaws.com/ea8a7096-clear-floats.jpg) when complete.

> Instructor Hint: the `.product-image` needs some margining and the `.product-description` needs to clear the floats.


```html
<!DOCTYPE html>
<html>
<head>
  <title>Cool Products</title>
</head>
<body>
  <div class="product-info">
    <img class="product-image" src="http://placehold.it/200x200" alt="My Cool Product" />
    <div class="product-details">
      <h2>My Cool Product</h2>
      <p class="product-price">$100</p>
    </div>
    <div class="product-description">
      <h3>Product Description</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quia blanditiis debitis ea, ipsa fugit quis incidunt itaque, nulla sunt dolorem odit. Sint eos reiciendis amet ad vero cupiditate, ratione debitis.</p>
    </div>
  </div>
</body>
</html>
```

```css
.product-info {
  width: 450px;
  background-color: #67C67E;
}
.product-image {
  float: left;
}
.product-details {
  float: left;
  color: #FFFFFF;
}

.product-description {
  padding: 10px;
  background-color: #7DADEA;
  color: #FFFFFF;
}
```