# Ex-08-Book-Cover-Design
## AIM:
To design a static web site for a book cover page.
## DESIGN STEPS:
## Step 1:

Create a new Django project and app.
## Step 2:

Create a static file directory and mention the changes in settings.
## Step 3:

Make a new folder templates inside your app and create a html and map them using views and url.
## Step 4:

Write down the code for book cover using HTML and CSS.
## Step 5:

Add images and other contents using CSS record a screenshot of it.

## CODE :

<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #bbe432;
            color:rgb(190, 139, 139);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/wave2.png);
            background-size:600px;
        }
            

        .toptext{
            color:rgb(79, 101, 121);

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: rgb(21, 19, 12);
            display: inline;
            position: relative;
            color:rgb(33, 195, 119);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
            font-size: larger;
            text-align: center;
            position: relative;
            color:rgb(165, 23, 130);
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .edition{
            color:rgb(36, 184, 78);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-size: large;
            text-align: center;
            position: relative;
            top:40px;
            color:rgb(95, 18, 18);
        }
        .photo{
            position: relative;
            top: 135px;
            left: 200px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            <div class="tophr">
                <hr style="color: rgb(57, 38, 151);">
            </div>
            <div class="booktitle">
                <h1>Responsive Web Design With HTML5 and CSS</h1></div>
            <div class="subtitle">
                Develop future-proof  responsive  websites  using  the  latest  HTML5  and  CSS  Techniques
            </div>
            <div>
        
            <div class="photo">
                <img src="c:\Users\admin\OneDrive\Pictures\images (1).jpeg" width="175" height="140" alt="ben">
            </div>
            <div class="id">
                <hr style="color: rgb(23, 21, 15);">
            </div>
            <div class="author">
               <p><b>JOHN PAUL J</b></p>
            </div>
            <div class="publisher">
                Packt>
            </div>
            <div class="edition">
                <b>THIRD EDITION</b>
            </div>
            
        </div>
    </body>
</html>


## OUTPUT:
![Screenshot 2023-12-25 203038](https://github.com/JOHNSUBIK/Ex-06-Book-Cover-Design/assets/150279319/3f030f6a-9c75-457d-ad85-afb7d00d91cb)



## Result:
  Thus the program to develop a website to display the cover page design of a book is done.
