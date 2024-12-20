# Ex.06 Book Front Cover Page Design
## Date:05/12/24

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
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
.bookpage {
    width: 420px;
    height: 620px;
    color: rgb(50, 50, 50);
    margin: 20px auto;
    padding: 25px;
    font-family: 'Arial', 'Verdana', sans-serif;
    background-image: url('back ground.web .jpg');
    background-size: cover;
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.5);
    border-radius: 15px;
    position: relative;
}

.insight {
    color: navy;
    font-weight: bold;
    font-size: larger;
    margin-bottom: 15px;
}

.hrstyle {
    width: 80%;
    margin: 10px auto;
    border: 1px solid #ccc;
}
.booktitle {
    font-family: 'Times New Roman', serif;
    color: darkblue;
    font-size: larger;
    text-align: center;
    margin-top: 40px;
    line-height: 1.5;
}

.subtitle {
    font-family: 'Verdana', sans-serif;
    font-size: medium;
    color: darkgreen;
    text-align: center;
    margin-top: 20px;
}

.mypic {
    position: absolute;
    bottom: 20px;
    right: 20px;
}

.mypic img {
    width: 100px;
    height: 100px;
    border: 2px solid #000;
    object-fit: cover;
}

.ed {
    color: darkgreen;
    font-size: medium;
    text-align: left;
    font-style: italic;
    margin-top: 30px;
    position: relative; 
    bottom: -150px;   
}

.pub {
    font-size: medium;
    text-align: right;
    color: #000000;
    position: relative;
    bottom: -285px;
}
.author {
    position: relative;
    top:130px;
    width: 100px;
    color: darkred;
    font-family: 'Georgia', serif;
    font-size: medium;
}

.booktitle {
    position: relative;
    relativ
}

</style>
<title>Custom Cover Page</title>
</head>
<body>
<div class="bookpage">
    <div class="insight">EXPLORE TECHNOLOGY</div>
    <div class="booktitle">
        <h1>MODERN WEB DEVELOPMENT ESSENTIALS</h1>
    </div>
    <div class="subtitle">MASTERING HTML, CSS, AND JAVASCRIPT</div>
    <div class="id">
        <hr class="hrstyle">
    </div>
    
    <div class="end">
        
    </div>
    <div class="ed"><b>First Edition</b></div>
    <div class=""></div>
    <div class="mypic">
        <img src="image.png" alt="Author's Picture">
    </div>
    <div class="pub">SEC Publications</div>

    <div class="author"><b> WRITTEN BY M KRISHNAKUMARAN</b></div>

</div>
</body>
</html>

```



## OUTPUT:
![alt text](<Screenshot (33).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
