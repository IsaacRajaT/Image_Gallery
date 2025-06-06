# Ex.08 Design of Interactive Image Gallery
# Date: 20/05/2025
## AIM
  To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS

## Step 1:

Clone the github repository and create Django admin interface

## Step 2:

Change settings.py file to allow request from all hosts.

## Step 3:

Use CSS for positioning and styling.

## Step 4:

Write JavaScript program for implementing interactivit

## Step 5:

Validate the HTML and CSS code

## Step 6:

Publish the website in the given URL.

## PROGRAM
image.html
```
<html>
<head>
    <title>Interactive Image Gallery</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Anton&family=Bebas+Neue&family=Edu+AU+VIC+WA+NT+Arrows:wght@400..700&family=Josefin+Sans:ital,wght@0,100..700;1,100..700&family=Montserrat:ital,wght@0,100..900;1,100..900&family=Raleway:ital,wght@0,100..900;1,100..900&family=Shadows+Into+Light&display=swap" rel="stylesheet">
</head>
<body>
    <div class="first">
    <h1 class="heading">
        Music Director Image Gallery
    </h1>
    </div>
    <div>
        <center>
        <img src="Ilaiyaraaja-1.avif" class="img">
        <h3>Ilaiyaraaja</h3>
        </center>
    </div>
    <div>
        <center>
            <img src="A.R.-Rahman-Young-Rare_3-2.webp" class="img">
        <h3>AR Rahman</h3>
        </center>
    </div>
    <div>
        <center>
            <img src="yuvan.jpg" class="img">
        <h3>yuvan</h3>
        </center>
    </div>
    <div>
        <center>
            <img src="imman.jpg" class="img">
        <h3>D imman</h3>
        </center>
    </div>
    <div>
        <center>
            <img src="sandy.jpg" class="img">
        <h3>Santhosh Narayan</h3>
        </center>
    </div>
    <div>
        <center>
            <img src="gv.png" class="img">
        <h3>GV Prakash</h3>
        </center>
    </div>
    <div>
        <center>
            <img src="anirudh.webp" class="img">
        <h3>Anirudh Ravichander</h3>
        </center>
    </div>
    <div>
        <center>
            <img src="adhi.jpg" class="img">
        <h3>Hip Hop Adhi</h3>
        </center>
    </div>
    <div>
        <center>
            <img src="abhyankkar.webp" class="img">
        <h3>Sai Abhyankkar</h3>
        </center>
    </div>
    <div class="action">
        <img src="" alt="" class="action-image">
        <button class="btn">X</button>
    </div>
    <footer>
        Designed and Developed by TisaacRaja &reg;
    </footer>
    <script>
        const action = document.querySelector('.action');
        const actionImage = document.querySelector('.action-image');
        const closeButton = document.querySelector('.btn');
        const images = document.querySelectorAll('.img');

        images.forEach((image) => {
            image.addEventListener('click', () => {
                actionImage.src = image.src;
                action.classList.add('visible'); 
            });
        });

        closeButton.addEventListener('click', () => {
            action.classList.remove('visible'); 
        });

       action.addEventListener('click', (e) => {
            if (e.target === action) {
                action.classList.remove('visible'); 
            }
        });
    </script>
</body>
</html>
```


## OUTPUT
![alt text](<Screenshot 2025-05-21 003448.png>) 
![alt text](<Screenshot 2025-05-21 003501.png>)
![alt text](<Screenshot 2025-05-21 003512.png>)

## RESULT
  The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
