# Cover Page Design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Create a new Django project and app.

### Step 2:
Create a static file directory and mention the changes in settings.

### Step 3:
Make a new folder templates inside your app and create a html and map them using views and url.

### Step 4:
Write down the code for book cover using HTML and CSS.

### Step 5:
Add images and other contents using CSS record a screenshot of it.

## Code:
```html
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage
        {
            width: 500px;
            height: 700px;
            background-color: black;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 30px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image:url(/static/img/image.jpg);
            background-size:600px 800px;
            background-position: center;
            background-repeat: no-repeat;
        }
            
        .toptext
        {
            color:whitesmoke;
            font-size: 20px;
        }

        .tophr
        {
            width:200px;
        } 

        .title
        {
            font-family:Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
            font-size: 50px;
            color:whitesmoke;
            text-align: left;
            position: relative;
            top:10px;
        }

        .subtitle1
        {
             position: absolute;
             top: 265px;
             display:inline;
             color: whitesmoke;
             font-size: x-large;
             font-family: impact; 
        }

        .subtitle2
        {
             position: absolute;
             top: 290px;
             display: inline;
             color: whitesmoke;
             font-size: x-large;
             font-family: impact; 
        }

        .edition
        {
            position: absolute;
             bottom: 110px;
             left: 520px;
             display: inline;
             color: #00CD82;;
             font-size: 35px;
             font-family: tahoma; 
             
        }

        .photo
        {
            position: relative;
            top: 255px;
            left: 375px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }

        .downhr
        {
            position: absolute;
            width:500px;
            bottom: 100px;
        }

        .author
        {
            position:absolute;
            display:inline;
            left: 520px;
            bottom: 20px;
            font-family: Tahoma;
        }

        .publisher
        {
            position:absolute;
            display:inline;
            right: 520px;
            bottom: 20px;
            font-family: Tahoma;
        }

        </style>
        <title>Book Cover Page</title>
    </head>
    <body bgcolor="grey">
        <div class="bookpage">
            <div class="toptext">
               EXPERT INSIGHT
            </div>
            
            <div class="tophr">
                <hr style="color: #00CD82;">
            </div>

            <div class="title">
            Python Programming
            </div>
            <div class="title">
                Tips and Tricks
            </div>
                
            <div class="title">
             For Beginners
            </div> 

            <div class="subtitle1">
                <p>The ultimate beginners guide</p>
            </div>
            
            <div class="subtitle2">
                <p>with step by step guidance </p> 
            </div>

             <div class="edition">
                <b>Third Edition</b>
            </div>

             <div class="photo">
                <img src="/static/img/photo.jpg" width="130" height="145" alt="">
            </div>
            
            <div class="downhr">
                <hr style="color: #00CD82">
            </div>

            <div class="author">
                <h1>Prajeeth K T</h1>
            </div>

            <div class="publisher">
                <h1><u>Packt></u> </h1>
            </div>
            
        </div>
    </body>
</html>
```

## Client Output:
![cop](/img/cop.png)

## Server Output:
![sop](/img/sop.jpg)

## Result:
The program for designing book cover page using HTML and CSS is executed successfully.