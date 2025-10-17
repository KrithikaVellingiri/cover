# Ex.06 Book Front Cover Page Design
## Date:16.10.25

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
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <link rel="sylesheet" href="styles.css">
           <title>Book Cover</title>
    </head>
    <body>
        <h1 align="center">Krithika v(25017985)</h1>
        <div class="bookpage">
            <div class="insight">
                18th Edition
            </div>
            <div class="hrstyle">
                <hr style="color: yellow;">
            </div>
            <div class="booktitle">
                <h1> Computer statistical studies</h1>
            </div>
            <div class="subtitle">
                Dive into computer statistics with personalized content and smart search engines.
            </div>
            <div class="mypic">
                <img src="me.jpeg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
               <p><b>Krithika V</b></p>
            </div>
            <div class="pub">
               
                <br>Student at SEC
            </div>
            <div class="ed">
                <br>
                    Published by
                </br>
                
            </div>
        </div>
    </body>
</html>

styles.html

        .bookpage{
            width: 450px;
            height: 800px;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(cover.jpg);
            background-size: cover;
        }
            

        .insight{
            color: rgb(240, 233, 233);

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:red;
            top: 260px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: -5px;
        
        }
        .id {
            width:400px;
            position: relative;
            top: 300px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:230px;
            left:300px;
        }
        .ed{
            color:purple;
            font-size: small;
            font-family: Verdana;
            position:relative;
            top:160px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 250px;
            left: 260px;
            width: 80px;
            height: 100px;
            background-size: cover;
        }
      
```

## OUTPUT:
![alt text](<Screenshot (832)-1.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
