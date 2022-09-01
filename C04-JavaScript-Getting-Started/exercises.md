# Getting Started w/ JavaScript

**Read before starting**
In your `Code-Labs` folder, create a new folder called class-4. You will be working in the class-4 folder for today.

## Exercise 1: Your unique animation!

- Create a folder inside of class-4 called exercise-1
- Inside exercise-1, create a file called index.html
- Create an animation! Use HTML and CSS to accomplish this.

Here is a [resource](https://www.w3schools.com/css/css3_animations.asp).

---

---

## Exercise 2: Create a multi-page site!

- Create a folder inside of class-4 called exercise-2
- Inside exercise-2, create a file called home.html, school.html and park.html.
- Inside of home.html, school.html, and park.html, copy and paste the following:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body>
    <nav>
      <ul>
        <li><a href="./home.html">Home</a></li>
        <li><a href="./park.html">Park</a></li>
      </ul>
    </nav>
  </body>
</html>
```

- In `home.html` and `park.html`, make sure each have a heading element with the a title corresponding to their file name
- A list of things you see at home or at the park.
- An image of a house and the park.

- Create an additional <a></a>, formally known as the anchor element, that is for school.html.
- Give school a heading element, a list of things you see at school and an image.

---

---

## Exercise 3: Bootstrap, the CSS Framework that makes your life easier.

- Create a folder inside of class-4 called exercise-3
- Inside exercise-1, create a file called index.html
- In Index.html, include the following in the head element:

```html
<link
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
  rel="stylesheet"
  integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC"
  crossorigin="anonymous"
/>
<script
  src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
  integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
  crossorigin="anonymous"
></script>
```

These are bootstrap cdn links which means, by providing these in your index.html file, you will be given a group of CSS classes defined for you. Copy the following into your index.html.

```html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dropdown
          </a>
          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">Disabled</a>
        </li>
      </ul>
      <form class="d-flex">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>
```

Once you have done that, try resizing the browser to see what happens. You should see the navbar change.

- Take a second to through the Bootstrap [documentation](https://getbootstrap.com/docs/5.0/components/accordion/).  Try copying the code their and paste it into the index.html. See what you can come up with!

---

---

## Exercise 4: Hello World!

- Create a folder inside of class-4 called exercise-4
- Inside exercise-4, create a file called index.html.
- Print to the console `Hello World!`. 

Follow this [resource](https://www.w3schools.com/jsref/met_console_log.asp) as a guide. 

Be sure to open your `dev tools` in your browser to see the printed statement. 

---

---

## Exercise #5

**Aim**: Create a folder inside of class-4 called exercise 5 (with only an HTML file) that uses JavaScript to change the color of a Heading element.

- Create new folder with HTML file
- Add a Heading Element with text inside
- Create a `<script></script>` tag at the bottom of the page
- Write the logic to select a heading and change its color

---

---

## Exercise #6:

**Aim**: Create a new folder inside of class-4 called exercise 6 (with an HTML and JavaScript) that uses JavaScript to change the color of a Heading element on a button click.
