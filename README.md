# Ex.06 Book Front Cover Page Design
## Date:04/05/2025

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
<html>
<head>
    
    <style>
        .container {
            position: relative;
            margin-left: 40%;
            margin-right: 60%;
            width: 300px;
            height: 300px;
            
        }

        .expert-insight {
            position: absolute;
            top: 30px;
            left: 40px;
            color: rgb(12, 9, 9);
            font-style: italic;
            font-size: 16px;

        }
        .background-image
        {
            width: 200%;
            height: 270%;
        }

        .main-title {
            position: absolute;
            top: 115px;
            left: 40px;
            color: rgb(6, 6, 6);
            font-style: italic;
            font-size: 36px;
        }
        .photo {
            position: absolute;
            bottom: -440px;
            right: -270px;
            width: 120px;
            height: auto;
        }

        .subtitle {
            position: absolute;
            font-style: italic;
            font-size: 16px;
            top: 300px;
            left: 40px;
            font-weight: lighter;
            color: rgb(9, 8, 8);
        }

        .edition {
            position: absolute;
            bottom: -450px;
            left: 40px;
            color: rgb(13, 6, 6);
            font-style: italic;
            font-size: 20px
        }


        .author {
            position: absolute;
            bottom: -520px;
            left: 40px;
            color: rgb(0, 0, 0);
            font-style: italic;
            font-size: 30px;
            
        }
        .SEC{
            position:absolute;
            bottom: -490px;
            right: -220px;
            font-style: italic ;
            font-size: 16px;
            color: rgb(0, 0, 0);
        }
        
    </style>
</head>
<body>
    <div class="container">
        <img  class="photo" src="c:\Users\admin\Pictures\Screenshots\Screenshot 2025-05-04 132408.png" >
        <img class="background-image" src="c:\Users\admin\Pictures\Screenshots\Screenshot 2025-05-04 132835.png">
        <p class ="expert-insight"> EXPERTS INSIGHT</p>
        <h1 class="main-title" >WEB DEVELOPMENT: A BEGINNERS GUIDE</h1>
        <h2 class="subtitle"> From ZERO to HERO: Step by Step</h2>
        <p class="edition" >First Edition</p>
        <p class="author" >GOKUL S</p>
        <p class="SEC" >SEC</p>
    </div>
</body>
</html>
```

## OUTPUT:

![Screenshot 2025-05-04 133448](https://github.com/user-attachments/assets/66b74e45-4d80-41fa-bd23-4ad3a0a296b2)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
