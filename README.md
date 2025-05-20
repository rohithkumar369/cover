# Ex.06 Book Front Cover Page Design
## Date:

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
book.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Book Cover Template</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: url('background.jpg') no-repeat center center;
      background-size: cover;
      font-family: 'Georgia', serif;
      background-color: #f8f8e7; /* fallback color */
    }

    .overlay {
      background: rgba(255, 255, 255, 0.85);
      width: 12cm;
      height: 18cm;
      padding: 2cm;
      box-sizing: border-box;
      border-radius: 20px;
      text-align: center;
      display: flex;
      flex-direction: column;
      justify-content: center;
      position: relative;
      color: #222;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
      position: relative;
    }

    .tagline {
      font-size: 1.2em;
      margin-bottom: 1em;
      font-style: italic;
    }

    .book-title {
      font-size: 2.8em;
      margin: 0.3em 0;
      line-height: 1.1;
      font-weight: bold;
      text-transform: uppercase;
    }

    .series-info {
      font-size: 1.1em;
      margin-top: 1em;
      font-weight: bold;
      letter-spacing: 1px;
    }

    .author-name {
      margin-top: 2em;
      font-size: 1.5em;
      letter-spacing: 2px;
      font-weight: bold;
    }

    .author-photo {
      position: absolute;
      bottom: 20px;
      right: 20px;
      width: 4cm;
      height: 4cm;
      border-radius: 10px;
      object-fit: cover;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
    }
  </style>
</head>
<body>

<div class="overlay">
  <div class="tagline">Knowledge is Wisdom</div>
  <div class="book-title">
    ETERNAL FLAME<br>
  </div>
  <div class="series-info">The Forgotten Tomes • Book One</div>
  <div class="author-name"> Sir Francis Bacon</div>
  
  <!-- Embedded Author Photo -->
  <img src="author.png" alt="Author Photo" class="author-photo">
</div>

</body>
</html>

```
## OUTPUT:
![Screenshot (126)](https://github.com/user-attachments/assets/1654b5ef-9f70-4ec8-ad58-5827fa745e38)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
