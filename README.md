# EX01 Developing a Simple Webserver
## Date:   05/09/2025

## AIM:
To develop a simple webserver to serve html pages and display the Device Specifications of your Laptop.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Import the necessary modules.

### Step 5:
Start an HTTP server on a specific port.

### Step 7:
Run the Python script to serve web pages.

### Step 8:
Serve the HTML pages.

### Step 9:
Start the server script and check for errors.

### Step 10:
Open a browser and navigate to http://127.0.0.1:8000 (or the assigned port).

## PROGRAM:
```

<!DOCTYPE html>
<html>
    <style>
        .a1{
            text-align: center;
            color:black;
            background-color: burlywood;
        }
    </style>
    <head>
        <title>device</title>
    </head>
    <body>
       <h1 style="text-align: center;">Device Specifications </h1>
                   <h1 style="color: blue;text-align: center;">    VISHWA S  </h1>
                 <h1  style="text-align: center;">REF.NO:25012636</h1></pre>
        <center>
        <table border="4"  width="400" height="300" style="margin-left: 40px; border-collapse: collapse; ">
        </center>
            <tr class="a1">
                <th>s.no.</th>
                <th>Device specification</th>
                <th>Description</th>
            </tr>
            <tr class="a1">
                <td>1</td>
                <td>storage</td>
                <td>512 GB</td>
            </tr>
            <tr class="a1">
                <td>2</td>
                <td>Ram</td>
                <td>16</td>
            </tr>
            <tr class="a1">
                <td>3</td>
                <td>processer</td>
                <td>intel core i5 ultra</td>
            </tr>
           
        </table>
        <hr>
    </body>
</html>
            

```

## OUTPUT:
![alt text](<Screenshot (11).png>)


## RESULT:
The program for implementing simple webserver is executed successfully.
