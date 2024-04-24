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
Name : Praveen D
Reg.No : 212222240076
```
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8"/>
        <meta name="viewport" content="width=device=width, initial-scale=1.0"/>
        <title>Document</title>
        <style>
            .bookpage{
                height:680px;
                width:600px;
                margin-left:35%;
                background-image: url(WDimg.jpeg);
                padding:10px;
                background-size: cover;
            }
            .hr1{
                width:200px

            }
            .booktitle{
                margin-top: 10px;
                color:black;
                padding:5px;
                font-size: xx-large;
            }
            .subtitle{
                color:white;
                font-size: large;
            }
            
            .mypic{
                position: relative;
                top:90px;
                left:470px;
                height: 100px;
                width: 70px;
            }
            .hr2{
                padding-top: 130px;
            
            }
            *{
                color: black;
            }
            .ed{
                position:relative;
                top: 110px;
            }
            .author{
                font-family: 'Trebuchet MS';
                font-size: large;
            }
            .pb{
                position: relative;
                left:420px;
                top:-50px;
                font-size: x-large;
            }
        </style>
    </head>
    <body>
        <div class="bookpage">
            <div style="color:black">INSIGHT </div>
            <div class="hr1"><hr ></div>
            <div class="booktitle"><h1>Beginning CSS Web Development</h1></div>
            <div class="subtitle">This Consist Of Many Examples</div>
            <div class="mypic"><img src="Myimage.jpg" height="140px" ></div>
            <div class="ed">SPECIAL EDITION</div>
            <div class="hr2"><hr ></div>
            <div class="author"> PRAVEEN D </div>
            <div class="pb"> <h2>SEC</h2></div>

</body>
</html>
```

## OUTPUT:

![Ex6 WD](https://github.com/praveenmax55/cover/assets/113497509/fb59eef0-8411-43b2-bbb6-bf51e08c6f4e)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
