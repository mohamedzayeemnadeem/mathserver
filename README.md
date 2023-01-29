# Design a Website for Server Side Processing

## AIM:
To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:
# Step 1:
Desing your website for calculation using wireframe work.

Step 2:
Then to execute the wireframe work desing use html,css

# Step 3:
Use views.py to execute the coding in serverside.

# Step 4:
Mention the path of the website in urls.py.

# Step 5:
Publish the website in the given URL'yogabharathi3.student.saveetha.in'

# Step 6:
Publish the website in the given URL.

# PROGRAM :
math.py
<!DOCTYPE html>
<html>
<head>
    <meta charset='utf-8'>
    <meta http-equiv='X-UA-Compatible' content='IE=edge'>
    <title>Page Title</title>
    <meta name='viewport' content='width=device-width, initial-scale=1'>
    
</head>
<style>
    body {
  background-color: yellow;
}
    .container{
    width: 1080px;
    height: 440px;
    margin-top: 100px;
    margin-left: auto;
    margin-right: auto;
    border-width: 2px 2px 2px 2px;
    border-style: solid;
    box-shadow: 15px 15px 8px yellow;
    
}
    .heading{
        text-align: center;
    }
    .element{
        padding-top: 20px;
        padding-bottom: 20px;
        padding-left: 20px;
        padding-right:20px;
        text-align: center;
        font-size: 20px;
        background-color:darkgreen;
        
    }
    .footer{
        display: block;
        width: 100%;
        height: 35px;
        background-color:lemonchiffon;
        color: black;
        text-align: center;
        padding-top: 7px;
        font-size: large;
        
        }
</style>

<body>
     
    <div class="container">
        <div class="element", backgroung color="white">
        <h1  class="heading">AREA OF A RECTANGLE</h1>
        </div>
        <form method="POST">
            {% csrf_token %}
            <div class="element"> 
                Length=<input type="text" name="length" value={{length}}></input><br/>
            </div>
            <div class="element">
                Breadth=<input type="text" name="breadth" value={{breath}}></input><br/>
            </div>
            <div class="element">
                <input type="submit" value="AREA OF RECTANGLE"></input><br/>
            </div>
            <div class="element">
                Area=<input type="text" name="area" value={{area}}></input>
            </div>
            <div class="footer">
                    Developed by YOGABHARATHI.S
            </div>
        </form>
    </div>
    
</body>
</html>



## OUTPUT:


![zayeem server](https://user-images.githubusercontent.com/119476069/215305887-6ed1f4b7-430f-418d-afdf-4738ba38e873.png)


## Result:
Thus math sever is successfully executed
