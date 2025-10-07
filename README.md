# Ex.06 Book Front Cover Page Design
## Date:07/10/2025

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

<html>
    <head>
        <title>MyBook
        </title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="page">
            
            <div class="insights">
                SEC Insights
            </div>
            <div class="hr">
                <hr>
            </div>
            <div class="title">
               THE DIGITAL MIND 
            </div>
            <div class="subtitle">
              HOW TECHNOLOGY SHAPES OUR THOUGHT AND FUTURE.<br>
              Top Seller of 2025
            </div>
            <div class="edit">
             LIMITED EDITION
             </div>
             <br><hr>
              <div class="name">
                SUMAIYA.S
                </div>
                <div class="bottom">
                    SEC
                </div>
            <div class="pic">
            </div> 
        </div>
    </body>
</html>

style.css

body{
    display: flex;
    justify-content:center;
    align-items: center;
    height: 100vh;
}
.page{
    width: 500px;
    height: 700px;
    background-image: url(background.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    border: 20px solid pink (4, 118, 232, 0.626);
    padding:20px;
    box-sizing:border-box;
    background-clip: padding-box;
    position: relative;
       
}

.insights{
   color: #5b86a6;
    font-size: 18px;
   font-weight: bold;
   margin-bottom: 10px;
}
.hr{
    color: orange (66, 100, 249);
    width: 120px;
    right: 200%;
    

}
.title{
    color: #3b2099;
    font-size: 45px;
     margin: 13px 0 15px 0;
    
   font-weight: bold;
    text-align: center;
    
}
.subtitle{
    color: #392b99;
    font-size: 18px;
    margin-bottom: 40px;
}
.edit{
    color: #24b8fc;
    font-size: 18px;
    font-weight: bold;
    margin-top: 200px;
}
.name{
    color: #360a0a;
    font-size: 16px;
    font-weight: bold;
    margin-top: 5px;
   
}
.bottom{
    color: #050e16;
    position: absolute;
    bottom: 40px;
    right: 60px;
    font-weight: bold;
}
.pic{
    position: absolute;
    bottom:90px;
    left: 75%;
    width: 100px;
    height:100px;
    background: url(mypic.jpg) no-repeat;
    background-size: 80px;

}

```

## OUTPUT:
![alt text](<Screenshot 2025-10-07 225207.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
