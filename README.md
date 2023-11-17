# Ex.06 Book Front Cover Page Design
## Date: 28/10/2023

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
```html
<!DOCTYPE html>
<html>
    <head>
        <title>Font ex1</title>
        <style>
            body {
                background-image: url('samp.png');
                background-size: 500px 750px;
                background-repeat: no-repeat;
            }
            p{
                font-family: Arial;
                margin-top: 0;
                margin-bottom: 0;
            }

            div{
                text-align: center;
            }

            .T1{
                font-weight: bold;
                color: rgb(13, 115, 179);
                font-size:17px;
                margin-top: 30px;
                margin-right: -830px;
                

            }
            .l1{
                width: 20%;
                margin-left: -10px;
            }
            .T2{
                font-weight: bold;
                color: rgb(13, 115, 179);
                font-size:45px;
                margin-top:70px;
                margin-left: 65px;
                
            }

            .T3{
                font-weight: bold;
                font-size:20px;
                margin-top: 480px;
                color: rgb(13, 115, 179);
                margin-right: 600px;

            }
            .l2{
                width: 20%;
                margin-left: -10px;
            }
            .i1{
                filter: grayscale(100%);
                height: 100px;
                margin-left: 410px;
                margin-top: -180px;
            }
        </style>
    </head>
    <body>
        <p class="T1">
            First Edition
        </p>
        <hr class="l1" color="gray">
        
        <p class="T2">
            Intro to C
        </p>
        
        <p class="T3">
            Murali
        </p>
        
        <hr class="l2">
        <img src="prof.jpg" class="i1" style="vertical-align:bottom">
        
        
    </body>
</html>
```

## OUTPUT:
![image](https://github.com/Muralikrishnan13/cover/assets/130058615/d47641c2-6e96-457f-8fc9-228d66530fe5)
![image](https://github.com/Muralikrishnan13/cover/assets/130058615/5ad47b00-bea0-4af8-b498-958cd76e5091)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
