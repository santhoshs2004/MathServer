# Ex.05 Design a Website for Server Side Processing
## Date:

## AIM:
To design a website to find total surface area of a square prism in server side.

## FORMULA:
![image](https://github.com/selvasachein/MathServer/assets/120453887/8ecc8d12-b9a9-43df-be0b-711f299d796d)

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<html>
<head>
<meta charset='utf-8'>
<meta http-equiv='X-UA-Compatible' content='IE=edge'>
<title> TOTAL SURFACE AREA OF SQUARE PRISM</title>
<meta name='viewport' content='width=device-width, initial-scale=1'>
<style type="text/css">
body 
{
background-color:darkblue;
}
.edge {
width: 1440px;
margin-left: auto;
margin-right: auto;
padding-top: 250px;
padding-left: 300px;
}
.box {
display:block;
border: Thick dashed white;
width: 500px;
min-height: 300px;
font-size: 20px;
background-color:yellow;
}
.formelt{
color:orange;
text-align: center;
margin-top: 7px;
margin-bottom: 6px;
}
h1
{
color:white;
text-align: center;
padding-top: 20px;
}
</style>
</head>
<body>
<div class="edge">
<div class="box">
<h1>TOTAL SURFACE AREA OF SQUARE PRISM</h1>
<form method="POST">
{% csrf_token %}
<div class="formelt">
BASE : <input type="text" name="length" value="{{l}}"></input>(in m)<br/>
</div>
<div class="formelt">
HEIGHT : <input type="text" name="breadth" value="{{b}}"></input>(in m)<br/>
</div>
<div class="formelt">
<input type="submit" value="Calculate"></input><br/>
</div>
<div class="formelt">
SURAFE AREA : <input type="text" name="area" value="{{area}}"></input>m<sup>2</sup><br/>
</div>
</form>
</div>
</div>
</body>
</html>




```


## SERVER SIDE PROCESSING:
![image](https://github.com/rizwanrayyan/MathServer/assets/121215820/1ca5f5c3-cc3e-45e9-9bf4-887674ee7e0f)



## HOMEPAGE:
![image](https://github.com/rizwanrayyan/MathServer/assets/121215820/ac17b4d6-71d3-4141-8f8e-1855de3f57e2)


## RESULT:
The program for performing server side processing is completed successfully.
