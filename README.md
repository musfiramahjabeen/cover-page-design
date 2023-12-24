# Cover Page Design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Fork your the repository to your repository 
### Step 2:
Now using the command "django-admin startproject myproj" start a django project named myproj
### Step 3:
Now make sure to adjust the settings.py folder properly by adding "import os" in line 14 and STATCFILES_DIRS line at last
### Step 4:
Now create a folder called static within this create another folder called html and within this create a html file named index.html
### Step 5:
Now create your book cover design using html and css
### Step 6:
Using the command runserver, run your server and then access the static and html folder to access the index.html file

## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:red;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(pexels-alex-conchillos-3648850.jpg);
            background-size: cover;
        }
            

        .insight{
            color: black;

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: red;
            top:190px;
            
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
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color: blue;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body >
        <div class="bookpage">
            <div class="insight" style="color: #fff;">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1 style="font-family: Arial; font-size: 2rem; color: palevioletred;">Fundamentals of Web Application Development</h1></div>
            <div class="subtitle" style="font-family: Arial sans-serif; text-align: center; color: white;">
                HTML and CSS Combined with Django Architecture
            </div>
            <div class="mypic">
                <img src="c:\Users\admin\Pictures\fira photo to be crop(1).jpg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
               <p style="color: #fff; font-size: 1.5rem; font-weight: 100;"><b>MUSFIRA MAHJABEEN</b></p>
            </div>
            <div class="pub" style="color: palevioletred;">
                SEC
            </div>
            <div class="ed" style="font-family: Arial; font-style: italic; color: palevioletred;">
                <b>Seventh Edition</b>
            </div>
        </div>
    </body>
</html>
```

## Output:
![Screenshot 2023-12-24 141547](https://github.com/musfiramahjabeen/cover-page-design/assets/138971008/0d6c3711-c9c1-4b14-9d89-f04857645b4f)




## Result:
Successfully the Cover page of the book is designed using HTML and CSS.
