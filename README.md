# Ex.06 Book Front Cover Page Design
## Name: Pranav K
## Reg no: 212224040240
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
book.html

<style>
    .bookpage{
        width: 400px;
        height: 630px;
        color:rgb(161, 47, 85);
        margin-left: auto;
        margin-right: auto;
        padding: 20px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        background-image: url(bg.png);
        background-size: cover;
    }
        
    
    .insight{
        color: paleturquoise;
    
    }
    
    
    .hrstyle{
        width:170px;
    }
    .author{
    
        display: inline;
        position: relative;
        color: cyan;
        top:270px;
        
        font-family:Georgia;
        font-size: medium;
    }
    .booktitle{
        font-family: 'Courier New', Courier, monospace;
        font-size: larger;
        text-align: center;
        position: relative;
        top: 30px;
    
    }
    .id {
        width:400px;
        position: relative;
        top:280px;
        
    }
    .pub{
        color: rgb(102, 51, 67);
        font-size: medium;
        position: relative;
        top:235px;
        left:350px;
    }
    .ed{
        color: red;
        font-size: medium;
        font-family: Verdana;
        position:relative;
        top:185px;
    
    }
    .subtitle{
        color:rgb(255, 140, 0);
        font-family:Tahoma;
        font-size: large;
        position: relative;
        top:40px;
    }
    .mypic{
        position: relative;
        top: 230px;
        left: 260px;
        width: 100px;
        height: 90px;
        background-size: cover;
    }
    </style>
    <title>Book Cover Page</title>
    </head>
    <body>
    <div class="bookpage">
        <div class="insight">
            HANDS ON  EXPERIENCE
        </div>
        <div class="hrstyle">
            <hr style="color: rgb(142, 27, 63);">
        </div>
        <div class="booktitle">
            <h1>UI AND UX DESIGNING</h1></div>
        <div class="subtitle">
            Focus on the visual elements and interactions of a product. Main goal is to create a visually appealing and user-friendly interface. 
        </div>
        <div class="mypic">
            <img src="A.jpg" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: rgb(218, 32, 85);">
        </div>
        <div class="author">
           <p><b>PRANAV K</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>FOURTH Edition</b>
        </div>
    </div>
    </body>
```
## OUTPUT:
![alt text](<Screenshot (52).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.