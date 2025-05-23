# Ex.06 Book Front Cover Page Design
## Date:09.05.2025

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Book Cover</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body, html {
      height: 100%;
      font-family: 'Georgia', serif;
    }

    .book-cover {
      position: relative;
      height: 100vh;
      width: 100%;
      background: url('https://images.unsplash.com/photo-1506744038136-46273834b3fb') center/cover no-repeat;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      color: white;
    }

    .overlay {
      position: absolute;
      top: 0;
      left: 0;
      height: 100%;
      width: 100%;
      background: rgba(0, 0, 50, 0.4);
    }

    .content {
      position: relative;
      z-index: 1;
      padding: 20px;
    }

    .title {
      font-size: 3rem;
      font-weight: bold;
      text-transform: uppercase;
      letter-spacing: 2px;
    }

    .subtitle {
      font-size: 1.5rem;
      font-style: italic;
      margin-top: 10px;
    }

    .author {
      font-size: 1.2rem;
      margin-top: 30px;
    }

    .author-photo {
      margin-top: 15px;
      width: 100px;
      height: 100px;
      border-radius: 50%;
      object-fit: cover;
      border: 3px solid white;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div class="overlay"></div>
    <div class="content">
      <h1 class="title">The Sky Beneath</h1>
      <h2 class="subtitle">A Journey Through Dreams</h2>
      <p class="author">by Thamizh Writer</p>
      <img class="author-photo" src="suit pic_00.png" alt="Author Photo">
    </div>
  </div>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot 2025-05-09 113447.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
