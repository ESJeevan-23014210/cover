# Ex.06 Book Front Cover Page Design


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
    <title>Book Cover Design</title>
    <style> 
        .wrapper {
            background-color: rgb(21, 0, 71);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .bookpage{
            width: 400px;
            height: 600px;
            color: black;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(bg.png);
            background-size: cover;
        }
            
        
        .insight{
            color: azure;
        
        }
        
        
        .hrstyle{
            width: 100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: cornflowerblue;
            top: 270px;
            font-family: Georgia;
            font-size: medium;
        }
        .booktitle{
            color: rgb(251, 151, 0);
            font-family: 'Courier New', Courier, monospace, bold;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width: 400px;
            position: relative;
            top: 280px;
            
        }
        .pub{
            color: azure;
            font-size: medium;
            position: relative;
            top: 235px;
            left: 330px;
        }
        .ed{
            color: azure;
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 190px;
        
        }
        .subtitle{
            color: rgb(255, 97, 97);
            font-family: unicorn;
            font-size: larger;
            position: relative;
            top: 15px;
        }
        .subtitle2{
            color: rgb(255, 242, 188);
            font-family: Arial, Helvetica, sans-serif;
            font-size: small;
            position: relative;
            top: 250px;
        }
        .mypic{
            position: relative;
            top: 250px;
            left: 300px;
            width: 90px;
            height: 80px;
            background-size: contain;
        }
    </style>
</head>
<body>
    <div class="wrapper">
        <div class="bookpage">
            <div class="insight">
                <b>QUANTUM COMPUTING</b>
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1><b>QUANTUM COMPUTING</b></h1></div>
            <div class="subtitle">
                 <b>AND ITS EFFECTS</b> 
            <div class="subtitle2">
                <b>>> A basic beginner Book</b><br>
                <b>>> Deep quantum concepts</b><br>
                <b>>> User friendly interface</b><br>
            </div>     
            </div>
            <div class="mypic">
                <img src="Jeevan ES .jpg" width="100" height="100" >
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>Jeevan ES</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
        </div>
    </div>
</body>
</html>

```
## OUTPUT:

![Screenshot 2024-11-13 213024](https://github.com/user-attachments/assets/78a66e63-d066-44ea-a0b2-77a1f827787d)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
