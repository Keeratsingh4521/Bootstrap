<!-- # Bootstrap -->
<div style="text-align: center;">
  <h1>Bootstrap</h1>
</div>


<div style="text-align: center;">
<img src="bt.png" alt="alt text">
</div>


## Table of Content

- [Table of Content](#table-of-content)
- [Introduction](#introduction)
- [Installation](#installation)
- [Containers](#containers)
- [Text Colors](#text-colors)
- [Basic Table](#basic-table)
- [Bootstrap 5 Typography](#bootstrap-5-typography)
- [Bootstrap 5 Images](#bootstrap-5-images)
- [Bootstrap 5 Jumbotron](#bootstrap-5-jumbotron)
- [Bootstrap 5 Buttons](#bootstrap-5-buttons)
- [Bootstrap 5 Alerts](#bootstrap-5-alerts)
- [Bootstrap 5 Navbars](#bootstrap-5-navbars)
- [Bootstrap 5 Dark Mode](#bootstrap-5-dark-mode)
- [Bootstrap 5 Tooltip](#bootstrap-5-tooltip)
- [Bootstrap 5 Popover](#bootstrap-5-popover)
- [Bootstrap 5 Forms](#bootstrap-5-forms)
- [Bootstrap Breakpoints](#bootstrap-breakpoints)
- [Conclusion](#conclusion)
- [Referance](#referance)













## Introduction
 Bootstrap 5 is a free front-end framework for faster and easier web development.
    Bootstrap includes HTML and CSS based design templates for typography, forms, buttons, tables, navbar, image as well as optional JavaScript plugins.
    Bootstrap 5 also gives you the ability to easily create responsive web designs.


## Installation

Install bootstrap using **npm** (node package manager).

**npm** is a package manager for the javascript programing language.
**npm** allows to install packages and manage dependencies.

```bash
npm install bootstrap@5.3.3
```

Install bootstrap using **CDN** (content delivery network).

**CDN** is like a distirbuted network of servers spread across different places that helps in the delivery of the content(images,videos,photos) to the users more easily and quickly.


```bash
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
```
```bash
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>
```



## Containers
   
   Containers are the building block of Bootstrap that contain, pad, and align your content within a given device or viewport.

   The **.container** class provides a responsive fixed width container.

   

   The **.container-fluid** class provides a full width container.

  ![alt text](<Screenshot from 2024-07-29 12-38-12.png>)

  **Default container**

  **.container** class is a responsive, fixed-width container

  ```bash
<div class="container">
  <!-- Content here -->
</div>
 ```
  **Responsive** **containers**

  ```bash
<div class="container-sm">Hundred percent wide until small breakpoint</div>
<div class="container-md">Hundred percent wide until medium breakpoint</div>
<div class="container-lg">Hundred percent wide until large breakpoint</div>
<div class="container-xl">Hundred percent wide until extra large breakpoint</div>
<div class="container-xxl">Hundred percent wide until extra extra large breakpoint</div>
 ```
   **Fluid containers**

   .container-fluid for a full width container, spanning the entire width of the viewport.

```bash
<div class="container-fluid">
  ...
</div>
```

##  Text Colors

   Bootstrap 5 has some contextual classes that can be used to provide "meaning through colors".

   The classes for text colors are:
   - .text-muted, 
   - .text-primary, 
   - .text-success, 
   - .text-info,
   - .text-warning, 
   - .text-danger, 
   - .text-secondary, 
   - .text-white, 
   - .text-dark, 
   - .text-body (default body color/often black)

  ```bash
  <!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<div class="container mt-3">
  
  <p class="text-muted">Hi! everyone</p>
  <p class="text-primary">Hi! everyone</p>
  <p class="text-success">Hi! everyone</p>
  <p class="text-info">Hi! everyone</p>
  <p class="text-warning">Hi! everyone</p>
  <p class="text-danger">Hi! everyone</p>
  <p class="text-secondary">Hi! everyone</p>
  <p class="text-dark">Hi! everyone</p>
  <p class="text-body">Hi! everyone</p>
  <p class="text-light">Hi! everyone</p>
  <p class="text-white">Hi! everyone</p>
</div>

</body>
</html>


  ```


   ![alt text](<Screenshot from 2024-07-29 12-57-46.png>)

## Basic Table
 
 A basic Bootstrap 5 table has a light padding and horizontal dividers.
The **.table** class adds basic styling to a table.

```bash
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Table</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<div class="container mt-3">
              
  <table class="table">
    <thead>
      <tr>
        <th>Firstname</th>
        <th>Lastname</th>
        <th>Email</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Keerat</td>
        <td>Singh</td>
        <td>keerat@gmail.com</td>
      </tr>
      <tr>
        <td>Jaskaran</td>
        <td>Singh</td>
        <td>jas@gmail.com</td>
      </tr>
      <tr>
        <td>Kanwal</td>
        <td>Singh</td>
        <td>ks@gmail.com</td>
      </tr>
    </tbody>
  </table>
</div>

</body>
</html>

```

   ![alt text](<Screenshot from 2024-07-31 11-15-09.png>)


The .**table-bordered** class adds borders on all sides of the table and cells.
   
The .**table-hover** class adds a hover effect (grey background color) on table rows.

The .**table-dark** class adds a black background to the table.

## Bootstrap 5 Typography

   Bootstrap 5 uses a default font-size of 1rem (16px by default), and its line-height is 1.5.
   In addition, all `"<p>"` elements have **margin-top: 0** and **margin-bottom: 1rem** (16px by default).

## Bootstrap 5 Images

   **Image Shapes**

   - Rounded Corners

   The **.rounded** class adds rounded corners to an image.
```bash
    <img src="bt.png" class="rounded" alt=""> 
```

```bash
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Round Image</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<div class="container mt-3">
  <h2>Rounded Corners</h2>
  <p>The .rounded class adds rounded corners to an image:</p>            
  <img src="bt.png" class="rounded" alt="image" width="304" height="236"> 
</div>

</body>
</html>

```

 ![alt text](<Screenshot from 2024-08-17 14-27-48.png>)





   - Circle

The .rounded-circle class shapes the image to a circle.

```bash
 <img src="bt.png" class="rounded-circle" alt=""> 
```
```bash
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Circle Image</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<div class="container mt-3">
  <h2>Circle</h2>
  <p>The .rounded-circle class shapes the image to a circle:</p>            
  <img src="bt.png" class="rounded-circle" alt="image" width="304" height="236"> 
</div>

</body>
</html>


```
 ![alt text](<Screenshot from 2024-08-17 13-57-44.png>)


## Bootstrap 5 Jumbotron

  A jumbotron was introduced in Bootstrap 3 as a big padded box for calling extra attention to some special content or information.

  Jumbotrons are no longer supported in Bootstrap 5. However, you can use a **div** element and add special helper classes together with a color class to achieve the same effect.


```bash
<!DOCTYPE html>
<html>
<head>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<div class="container mt-3">
 
  <div class="mt-4 p-5 bg-primary text-white rounded">
    <h1>Hello World</h1> 
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat..</p> 
  </div>
</div>

</body>
</html>

```

![alt text](<Screenshot from 2024-07-29 15-18-43.png>)

## Bootstrap 5 Buttons

**Button Styles**

Bootstrap 5 provides different styles of buttons:

```bash
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Buttons</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<div class="container mt-3">
  <h2>Button Styles</h2>
  <button type="button" class="btn">Basic</button>
  <button type="button" class="btn btn-primary">Primary</button>
  <button type="button" class="btn btn-secondary">Secondary</button>
  <button type="button" class="btn btn-success">Success</button>
  <button type="button" class="btn btn-info">Info</button>
  <button type="button" class="btn btn-warning">Warning</button>
  <button type="button" class="btn btn-danger">Danger</button>
  <button type="button" class="btn btn-dark">Dark</button>
  <button type="button" class="btn btn-light">Light</button>
  <button type="button" class="btn btn-link">Link</button>      
</div>

</body>
</html>


```


![alt text](<Screenshot from 2024-07-29 16-22-08.png>)

## Bootstrap 5 Alerts

Bootstrap 5 provides an easy way to create predefined alert messages:

- .alert
- .alert-success
- .alert-info
- .alert-warning
- .alert-danger
- .alert-primary
- .alert-primary
- .alert-light
- .alert-dark

```bash
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Alerts</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<div class="container mt-3">
  <h2>Alerts</h2>

  <div class="alert alert-success">
    <strong>Success!</strong> 
  </div>
  <div class="alert alert-info">
    <strong>Info!</strong> 
  </div>
  <div class="alert alert-warning">
    <strong>Warning!</strong> 
  </div>
  <div class="alert alert-danger">
    <strong>Danger!</strong> 
  </div>
  <div class="alert alert-primary">
    <strong>Primary!</strong> 
  </div>
  <div class="alert alert-secondary">
    <strong>Secondary!</strong> 
  </div>
  <div class="alert alert-dark">
    <strong>Dark!</strong> 
  </div>
  <div class="alert alert-light">
    <strong>Light!</strong> 
  </div>
</div>

</body>
</html>


```


![alt text](<Screenshot from 2024-07-30 17-24-56.png>)

## Bootstrap 5 Navbars

A navigation bar is a navigation header that is placed at the top of the page.


```bash
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Navbar</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<nav class="navbar navbar-expand-sm navbar-dark bg-dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="javascript:void(0)">Logo</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#mynavbar">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="mynavbar">
      <ul class="navbar-nav me-auto">
        <li class="nav-item">
          <a class="nav-link" href="javascript:void(0)">Link</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="javascript:void(0)">Link</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="javascript:void(0)">Link</a>
        </li>
      </ul>
      <form class="d-flex">
        <input class="form-control me-2" type="text" placeholder="Search">
        <button class="btn btn-primary" type="button">Search</button>
      </form>
    </div>
  </div>
</nav>

<div class="container-fluid mt-3">
  <h3>Navbar Forms</h3>
  <p>You can also include forms inside the navigation bar.</p>
</div>

</body>
</html>



```



![alt text](<Screenshot from 2024-07-29 16-41-13.png>)


## Bootstrap 5 Dark Mode

By default, bootstrap pages have a white (light) background color.

If you want to change the whole page to a darker color, you can add `data-bs-theme="dark"` to the html element:

```bash
<table class="table" data-bs-theme="dark">
```

![alt text](<Screenshot from 2024-07-30 15-07-09.png>)

```bash
<!DOCTYPE html>
<html lang="en" data-bs-theme="dark">
<head>
  <title>Dark Theme</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<div class="container mt-3">
  <h1>My Page</h1>
  <p>hello</p>
 </div>

</body>
</html>

```


## Bootstrap 5 Tooltip

The Tooltip component is small pop-up box that appears when the user moves the mouse pointer over an element.

```bash
<button type="button" class="btn btn-primary" data-bs-toggle="tooltip" title="Hello!">Hover over me!</button>
```

```bash
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<div class="container mt-3">
  <h3>Tooltip Example</h3>
  
  <button type="button" class="btn btn-primary" data-bs-toggle="tooltip" title="Hello!">
    Hover over me!
  </button>
</div>

<script>
// Initialize tooltips
var tooltipTriggerList = [].slice.call(document.querySelectorAll('[data-bs-toggle="tooltip"]'))
var tooltipList = tooltipTriggerList.map(function (tooltipTriggerEl) {
  return new bootstrap.Tooltip(tooltipTriggerEl)
})
</script>

</body>
</html>


```

![alt text](<Screenshot from 2024-07-30 15-31-00.png>)

## Bootstrap 5 Popover

The Popover component is similar to tooltips, it is a pop-up box that appears when the user clicks on an element. The difference is that the popover can contain much more content.

**How To Create a Popover**

To create a popover, add the `data-bs-toggle="popover"` attribute to an element.

Use the title attribute to specify the header text of the popover, and use the `data-bs-content` attribute to specify the text that should be displayed inside the popover's body.

```bash
<button type="button" class="btn btn-primary" data-bs-toggle="popover" title="Popover Header" data-bs-content="Some content inside the popover">Toggle popover</button>
```


**Note:** Popovers must be initialized with JavaScript to work.


```bash
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<div class="container mt-3">
  <h3>Popover Example</h3>
  
  <button type="button" class="btn btn-primary" data-bs-toggle="popover" title="Popover Header" data-bs-content="Some content inside the popover">
    Toggle popover
  </button>
</div>

<script>
var popoverTriggerList = [].slice.call(document.querySelectorAll('[data-bs-toggle="popover"]'))
var popoverList = popoverTriggerList.map(function (popoverTriggerEl) {
  return new bootstrap.Popover(popoverTriggerEl)
})
</script>

</body>
</html>

```
![alt text](<Screenshot from 2024-08-17 14-37-53.png>)

## Bootstrap 5 Forms

A Bootstrap form is just an HTML form that uses Bootstrap to make it look better and work well on all devices. It comes with ready-made styles and a grid system, so the form looks neat and consistent. With Bootstrap, you can easily arrange the form, add custom styles, and show validation messages, making it more user-friendly.

```bash
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<div class="container mt-3">
  <form>
    <div class="mb-3 mt-3">
      <label for="email">Email:</label>
      <input type="email" class="form-control" id="email" placeholder="Enter email" name="email">
    </div>
    <div class="mb-3">
      <label for="pwd">Password:</label>
      <input type="password" class="form-control" id="pwd" placeholder="Enter password" name="pswd">
    </div>
    <div class="form-check mb-3">
      <label class="form-check-label">
        <input class="form-check-input" type="checkbox" name="remember"> Remember me
      </label>
    </div>
    <button type="submit" class="btn btn-primary">Submit</button>
  </form>
</div>

</body>
</html>


```
![alt text](<Screenshot from 2024-07-30 16-57-02.png>)



## Bootstrap Breakpoints

Bootstrap includes six default breakpoints, for building responsively. These breakpoints can be customized if you’re using source Sass files.

```bash
Breakpoint    	Classinfix 	      Dimensions

X-Small 	      None 	              <576px
Small 	          sm 	              ≥576px
Medium 	          md 	              ≥768px
Large 	          lg 	              ≥992px
Extra           large xl 	          ≥1200px
Extra         extra large xxl 	    ≥1400px

```

## Conclusion

By using Bootstrap, developers can reduce the time and effort required to build and maintain high-quality websites. Bootstraps simplifies the development of responsive websites.

## Referance

- [Bootstrap wikipedia](https://en.wikipedia.org/wiki/Bootstrap_(front-end_framework))
- [Bootstrap Tutorials](https://getbootstrap.com/)
