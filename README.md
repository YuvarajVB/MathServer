# Ex.05 Design a Website for Server Side Processing
## Date:

## AIM:
To design a website to find surface area of a Right Cylinder in server side.

## FORMULA:
Surface Area = 2Πrh + 2Πr<sup>2</sup>
<br>r --> Radius of Right Cylinder
<br>h --> Height of Right Cylinder

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
math.html
<html>
<head>
<meta charset='utf-8'>
<meta http-equiv='X-UA-Compatible' content='IE=edge'>
<title>Area of Surface</title>
<meta name='viewport' content='width=device-width, initial-scale=1'>
<style type="text/css">
body {
    background-image: url('https://images.unsplash.com/photo-1520038569969-98da7959fcbd?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxleHBsb3JlLWZlZWR8MTR8fHxlbnwwfHx8fHw%3D'); 
    background-size: cover;
    background-attachment: fixed;
    background-position: center;
    font-family: Arial, sans-serif;
}

.edge {
    width: 100%;
    padding-top: 180px;
    text-align: center;
}

.box {
    display: inline-block;
    border: thick dashed #1a7c74;
    width: 500px;
    min-height: 300px;
    font-size: 20px;
    background-color: rgba(9, 192, 253, 0.8); /* Semi-transparent to blend with background */
    border-radius: 15px;
}

.formelt {
    color: black;
    text-align: center;
    margin-top: 8px;
    margin-bottom: 6px;
}

h1 {
    color: #FFFFFF;
    padding-top: 20px;
}

h3 {
    color: #FFFFFF;
    margin-top: -10px;
}
</style>
</head>
<body>
<div class="edge">
    <div class="box">
        <h1>SURFACE AREA OF RIGHT CYLINDER</h1>
        <h3>YUVARAJ V 212223230252</h3>
        <form method="POST">
            {% csrf_token %}
            <div class="formelt">
                Radius: <input type="text" name="radius" value="{{r}}">m<br/>
            </div>
            <div class="formelt">
                Height: <input type="text" name="height" value="{{h}}">m<br/>
            </div>
            <div class="formelt">
                <input type="submit" value="Calculate"><br/>
            </div>
            <div class="formelt">
                Area: <input type="text" name="area" value="{{area}}">m<sup>2</sup><br/>
            </div>
        </form>
    </div>
</div>
</body>
</html>

```


## SERVER SIDE PROCESSING:



## HOMEPAGE:


## RESULT:
The program for performing server side processing is completed successfully.
