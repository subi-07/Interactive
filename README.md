# Ex.08 Design of Interactive Image Gallery
## Date:02/05/2025

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Image Gallery</title>
    <link rel="stylesheet" href="style.css">
</head>
<body bgcolor="grey">
    <header>
        <h1 align="center">🤍SHINCHAN🤍</h1>
    </header>
    <div class="gallery1">
        <div class="" onclick="openModal(this)">
            <img src="img1.png" >
        </div>
        <div class="gallery-item" onclick="openModal(this)">
            <img src="img2.png"  >
        </div>
    </div>
        <div class="gallery2">
            <div class="gallery-item" onclick="openModal(this)">
                <img src="img3.png" >
            </div>
            <div class="gallery-item" onclick="openModal(this)">
                <img src="img4.png" >
            </div>
        </div>

    <div id="modal" class="modal">
        <span class="close" onclick="closeModal()">&times;</span>
        <img class="modal-content" id="modalImage">
        <div id="caption"></div>
    </div>

    <script src="style.js"></script>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2025-05-11 191617.png>)
![alt text](<Screenshot 2025-05-11 191649.png>) 
![alt text](<Screenshot 2025-05-11 191636.png>) 

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
