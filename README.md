# Ex.06 Book Front Cover Page Design
## Date:6.5.2025

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
'''
<html>
    <head>
        <meta name="viewport"
        content="width=device-width, initial-scale=1.0">
        <style>
            .bookpage{
                width: 400px;
                height: 600px;
                color: white;
                margin-left: auto;
                margin-right:auto;
                padding: 20px;
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                background-image: url(bookback.jpg);
                background-size: cover;
            }
            .insight{
                color:rgb(12, 149, 241);
                
            }
            .hr
            {
                width: 120px;
                
            }
            .head
            {
                font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
                font-size: larger;
                color:rgb(11, 226, 169);
                text-align: center;
                padding-top: 65px;
            }
            .sub
            {
                font-family: 'Times New Roman', Times, serif;
                font-size:medium;
                top:230px;
                left:30px;
                padding-top: 0.1px;
                padding-left: 30px;
                color:rgb(232, 233, 238);
            }
            .down
            {
                color: orange;
                font-family: Arial, Helvetica, sans-serif;
                font-size: 10px;
                position: relative;
                top: -100px;
                left: 7px;
            }
            .img
            {
                position: relative;
                top: 40px;
                left:300px;
                width: 100px;
                height: 100px;
                background-size: cover;
            }
            .hr2
            {
                padding-top:40px;
            }
            .author
            {
                position: relative;
                top:0px;
                left:295px;
                color: rgb(210, 240, 9);
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                font-size: small;
            }
        </style>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                EXPERT INSIGHT
            </div>
            <div class="hr">
                <hr style="color: rgb(240, 228, 11);">
            </div>
            <div class="head">
                <h1>Responsive Web <BR>Design with<BR> HTML5 and CSS</h1>
                    <hr>
            </div>
            <div class="sub">
                <h3>Develop future-proof responsive websites <br>using the latest HTML5 and CSS techniques</h3>
            </div>
            <div>
             <image  src="ben frain.jpg" class="img" width="100" height="110" alt="" ></image>
             <br>
             
            </div>
            <div class="hr2">
                <hr>
            </div>
            <div class="author">
                <h1>Ben Frain</h1>
            </div>
            <div class="down">
                <h1>Third edition</h1>
            </div>
            

        </div>
    </body>
</html>
## OUTPUT:
![alt text](<Screenshot 2025-05-06 212203.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
