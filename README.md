# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Create a django admin project.


### Step 2:
Create an app.


## Step 3:
Create a  new HTML file in the static folder.


## Step 4:
Write the  HTML code with CSS properties.


## Step 5:
Publish the website in localhost.

```
<html>

<head>
    
    <style>
        .bookpage{

            width: 400px;
            height: 650px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(cover1.jpg);
            background-size: cover;
            background-image: linear-gradient(to bottom right, pink, yellow);
        }
            
        
        .insight{
            color:bisque;
            background-image: linear-gradient(to bottom right, red, yellow);
        
        }
        
        
        .hrstyle{
            width:100px;
            background-image: linear-gradient(to bottom right, red, yellow);
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(212, 212, 22);
            top:280px;
            
            font-family:Georgia;
            font-size: medium;
            background-image: linear-gradient(to bottom right, red, yellow);
        }
        .booktitle{
            color:aqua;
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 25px;
            background-image: linear-gradient(red, yellow);
        
        }
        .id {
            width:400px;
            position: relative;
            top:280px;
            background-image: linear-gradient(to bottom right, red, yellow);
           
        }
        .pub{
            color:cornflowerblue;
            font-size: medium;
            position: relative;
            top:250px;
            left:330px;
            
        }
        .ed{
            color:greenyellow;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:180px;
            background-image: linear-gradient(to bottom right,blue , yellow);
        
        }
        .subtitle{
            color:aquamarine;
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 60px;
            background-image: linear-gradient(to bottom right, red, yellow);
        }
        
        .mypic{
            position: relative;
            top: 275px;
            left: 320px;
            width: 70px;
            height: 80px;
            background-size:contain;
            background-image: linear-gradient(to bottom right, red, yellow);
        }
    
.bookpage{
background-image:url(images\ \(2\).jpeg);
}
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        
        <div class="bookpage">
            <div class="insight">
                COMPUTER
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>FUNDAMENTALS of COMPUTERS</h1></div>
            <div class="subtitle">
                 BEGINNERS CRASH COURSE [Day 1 to Day 100]
                 <br>
                 CODING DATA, PYTHON,ALGORITHMS AND HACKING.
                </div>
            
            <div class="mypic">
                <img src="C:\Users\Admin\OneDrive\Desktop\New folder (2)\IMG-20230816-WA0001 (1).jpg" width="70" height="80" >
            </div>
            <div class="id">
                <hr style="color:rgb(13, 128, 0)">
            </div>
            <div class="author">
               <p><b>Keziah V</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>FIRST EDITION</b>
            </div>
        </div>
        </body>
</html>
```


## Output:

![Screenshot (11)](https://github.com/keziahhhf/cover-page-design/assets/155235704/e6fdfc5b-60a6-4de0-bd77-443286aa3bfd)


## Result:
The program for designing book front cover page using HTML and CSS is completed successfully.
