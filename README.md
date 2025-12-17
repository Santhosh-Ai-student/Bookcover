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
cover.html
{% load static %}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>John Cena – The Struggle Story</title>
    <link rel="stylesheet" href="{% static 'bookapp/style.css' %}">
</head>
<body>

<div class="book-cover">

    <h1 class="book-title">
        Rise Through Struggle
    </h1>

    <h2 class="book-subtitle">
        The Untold Journey of John Cena
    </h2>

    <div class="image-box">
        <img src="{% static 'bookapp/images/johncena.webp' %}" alt="John Cena">

    </div>

    <p class="description">
        This book explores the hardships, failures, and relentless determination
        of John Cena, who rose from rejection and financial struggle to become
        one of the greatest professional wrestlers in history.
    </p>

    <p class="author">
        Written by <span>Santhosh</span>
    </p>

</div>

</body>
</html>

style.css
body {
    margin: 0;
    padding: 0;
    background: linear-gradient(135deg, #1e130c, #9a8478);
    font-family: 'Georgia', serif;
}

.book-cover {
    width: 450px;
    height: 650px;
    margin: 30px auto;
    background: #111;
    color: #ffffff;
    padding: 30px;
    text-align: center;
    border-radius: 12px;
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.6);
}

.book-title {
    font-size: 34px;
    color: #f5c542;
    margin-bottom: 5px;
}

.book-subtitle {
    font-size: 16px;
    font-style: italic;
    color: #ccc;
    margin-bottom: 25px;
}

.image-box img {
    width: 220px;
    height: auto;
    border-radius: 10px;
    border: 3px solid #f5c542;
    margin-bottom: 25px;
}

.description {
    font-size: 15px;
    line-height: 1.6;
    color: #eaeaea;
    margin-bottom: 40px;
}

.author {
    font-size: 14px;
    color: #aaa;
}

.author span {
    color: #f5c542;
    font-weight: bold;
}
```


## OUTPUT:
![alt text](<book/bookapp/static/bookapp/Screenshot 2025-12-17 200111.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
