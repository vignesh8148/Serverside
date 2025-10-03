# Ex.05 Design a Website for Server Side Processing
## Date:29-09-2025

## AIM:
 To design a website to calculate the power of a lamp filament in an incandescent bulb in the server side. 


## FORMULA:
bmi=w/h2
w-->weight(in kgs)
h-->height(in cms)

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
html
<!DOCTYPE html>
<html>
<head>
    <title>BMI Calculator</title>
</head>
<body>
    <form method="POST">
  {% csrf_token %}
  <label>Height (cm):</label>
  <input type="text" name="height"><br>
  <label>Weight (kg):</label>

  <input type="text" name="weight"><br>

  <button type="submit">Calculate</button>
</form>

{% if BMI %}
  <h3>Your BMI is: {{ BMI }}</h3>
{% endif %}
</body>
</html>
```


## SERVER SIDE PROCESSING:
![alt text](bmi/code.png)

## HOMEPAGE:
![alt text](bmi/output.png)

## RESULT:
The program for performing server side processing is completed successfully.
