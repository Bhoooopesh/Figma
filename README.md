# Ex09 Event Registration Web Application

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
screen 1

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Login/Register</title>
    <style>
        .screen1 {
            width: 390px;
            height: 844px;
            background-color: #9370A3; /* Purple/Mauve color */
            padding: 20px;
            box-sizing: border-box;
            color: white;
            font-family: Arial, sans-serif;
            margin: 0 auto;
            text-align: center;
        }
        .header-box {
            background-color: #6C5182;
            padding: 15px 10px;
            margin-bottom: 50px;
            text-align: left;
            font-size: 10px;
        }
        .title {
            font-size: 24px;
            font-weight: bold;
            margin-bottom: 80px;
            letter-spacing: 1px;
        }
        .button {
            background-color: #2E406D;
            color: white;
            padding: 15px 0;
            margin: 20px auto;
            width: 60%;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
        }
        .logo {
            width: 150px;
            height: auto;
            margin: 30px 0;
        }
    </style>
</head>
<body>

<div class="screen1">
    <div class="header-box">
        SAVEETHA AUTONOMOUS <br> ENGINEERING COLLEGE 1216
    </div>
    
    <div class="logo">
        
    </div>

    <div class="title">PONGAL EVENTS</div>
    
    <div class="button">LOGIN</div>
    <div class="button">REGISTER</div>
</div>

</body>
</html>
```

```
screen 2

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Events List</title>
    <style>
        .screen2 {
            width: 390px;
            height: 844px; 
            background-color: #F8F8F8; /* Light Gray/White background */
            padding: 20px;
            box-sizing: border-box;
            font-family: 'Times New Roman', serif;
            margin: 0 auto;
            border-radius: 35px;
            border: 5px solid black; 
            overflow: hidden;
            color: black;
        }
        .events-title {
            text-align: center;
            font-size: 28px;
            font-weight: bold;
            margin-top: 50px;
            margin-bottom: 40px;
            color: #333;
        }
        .event-list {
            list-style: none;
            padding: 0 30px;
            font-size: 20px;
            text-align: left;
        }
        .event-list li {
            margin-bottom: 25px;
            padding: 5px 0;
        }
        .event-list li::before {
            content: "★ "; 
            color: #4A90E2; 
            font-size: 1.2em;
            margin-right: 15px;
        }
    </style>
</head>
<body>

<div class="screen2">
    <div style="height: 30px; background: black; width: 150px; margin: 0 auto; border-bottom-left-radius: 10px; border-bottom-right-radius: 10px;"></div>
    
    <div class="dynamic-content">
        <div class="events-title">PONGAL EVENTS</div>
        <ul class="event-list">
            <li>URIYAADI</li>
            <li>RANGOLI</li>
            <li>FOLK DANCE</li>
            <li>JALLIKATTU</li>
            <li>MUSICAL CHAIR</li>
            <li>KABADDI</li>
        </ul>
        <div style="text-align: center; margin-top: 50px;">
            <span style="background-color: #007bff; color: white; padding: 12px 24px; border-radius: 8px;">Register for Event</span>
        </div>
    </div>
</div>

</body>
</html>
```



```
screen 3

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Registration Form</title>
    <style>
        .screen3 {
            width: 390px;
            height: 844px;
            background-color: #9370A3; /* Purple/Mauve color */
            padding: 20px;
            box-sizing: border-box;
            color: white;
            font-family: Arial, sans-serif;
            margin: 0 auto;
            text-align: center;
        }
        .form-title {
            color: #333;
            font-size: 20px;
            font-weight: bold;
            margin-top: 50px;
            margin-bottom: 30px;
            letter-spacing: 1px;
            text-shadow: 1px 1px 0 white;
        }
        .form-input {
            width: 80%;
            margin: 10px auto;
            padding: 10px;
            background-color: #EEE; 
            border: none;
            border-radius: 5px;
            display: block;
            box-sizing: border-box;
            text-transform: uppercase;
        }
        .register-button {
            background-color: #C07979; /* Maroon/Reddish-Brown color */
            color: white;
            padding: 15px 0;
            margin: 40px auto;
            width: 60%;
            border-radius: 5px;
            cursor: pointer;
            font-size: 18px;
            font-weight: bold;
        }
    </style>
</head>
<body>

<div class="screen3">
    <div class="form-title">EVENT REGISTER FORM</div>
    
    <form>
        <input type="text" class="form-input" placeholder="FULL NAME" required>
        <input type="number" class="form-input" placeholder="AGE" required>
        <input type="text" class="form-input" placeholder="GENDER" required>
        <input type="text" class="form-input" placeholder="REGISTER NO" required>
        <input type="text" class="form-input" placeholder="DEPARTMENT" required>
        <input type="tel" class="form-input" placeholder="MOBILE NO" required>
        <input type="email" class="form-input" placeholder="EMAIL ID" required>

        <div class="register-button">REGISTER</div>
    </form>
</div>

</body>
</html>
```


```
screen 4

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Thank You/Contact</title>
    <style>
        .screen4 {
            width: 390px;
            height: 844px; 
            background-color: #B4D3E6; /* Light Blue color */
            padding: 20px;
            box-sizing: border-box;
            color: #333;
            font-family: 'Times New Roman', serif;
            margin: 0 auto;
            text-align: center;
        }
        .thank-you {
            font-size: 36px;
            font-weight: bold;
            margin-top: 150px;
            margin-bottom: 100px;
            color: #333;
            text-shadow: 1px 1px 0 white;
            letter-spacing: 2px;
        }
        .contact-section {
            margin-top: 50px;
            font-size: 18px;
            line-height: 1.6;
        }
        .contact-section div {
            margin-bottom: 15px;
        }
        .college-name {
            font-size: 14px;
            opacity: 0.8;
            margin-top: 5px;
        }
    </style>
</head>
<body>

<div class="screen4">
    <div class="thank-you">THANK YOU</div>
    
    <div class="contact-section">
        <div style="font-weight: bold; font-size: 24px;">CONTACT US</div>
        <div class="college-name">SAVEETHA ENGINEERING COLLEGE</div>
        
        <div style="margin-top: 30px;">
            PHONE <br>
            7305562835
        </div>
    </div>
</div>

</body>
</html>

```
## OUTPUT:
<img width="1838" height="899" alt="image" src="https://github.com/user-attachments/assets/030e6b93-a5c6-4258-9053-60d3d2f02508" />


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
