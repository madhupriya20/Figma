# Ex09 Event Registration Web Application
## Date:24-05-2025

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
Frame 1 – Welcome Page
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sports Day - Welcome</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #29b6b6;
      text-align: center;
      color: white;
      padding: 20px;
    }
    .logo {
      margin-top: 10px;
    }
    .title {
      margin-top: 30px;
      font-size: 22px;
    }
    .button {
      margin: 10px;
      padding: 12px 24px;
      background-color: #000;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 16px;
    }
  </style>
</head>
<body>
  <img class="logo" src="https://yourlogo-link.com" alt="Saveetha Logo" width="200">
  <div class="title">SPORTS DAY<br>EVENT - 2025</div>
  <button class="button">LOGIN</button>
  <button class="button">REGISTER</button>
</body>
</html>
```
Frame 2 – Events Info
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>SEC Warriors - Events</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #29b6b6;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .events {
      margin-top: 20px;
    }
    .event-item {
      font-size: 18px;
      margin: 8px 0;
    }
  </style>
</head>
<body>
  <img src="https://yourlogo-link.com" alt="Saveetha Logo" width="200">
  <h2>GET READY!!<br>sec warriors</h2>
  <div class="events">
    <div class="event-item">Tennis</div>
    <div class="event-item">BasketBall</div>
    <div class="event-item">VolleyBall</div>
    <div class="event-item">Cricket</div>
    <div class="event-item">Kabaddi</div>
  </div>
</body>
</html>
```
Frame 3 – Registration Form
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Register</title>
  <style>
    body {
      background-color: #29b6b6;
      font-family: Arial, sans-serif;
      color: white;
      padding: 20px;
    }
    h2 {
      text-align: center;
    }
    form {
      display: flex;
      flex-direction: column;
    }
    input {
      margin: 10px 0;
      padding: 10px;
      border: none;
      border-radius: 4px;
    }
    .submit-btn {
      background-color: black;
      color: white;
      padding: 12px;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <h2>Event Registration Form</h2>
  <form>
    <input type="text" placeholder="Full Name" required>
    <input type="text" placeholder="Gender" required>
    <input type="number" placeholder="Age" required>
    <input type="tel" placeholder="Mobile Number" required>
    <input type="email" placeholder="Email ID" required>
    <button class="submit-btn">REGISTER NOW</button>
  </form>
</body>
</html>
```
Frame 4 – Thank You Page
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Thank You</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #29b6b6;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .thank-you {
      font-size: 20px;
      margin: 20px 0;
    }
    .contact {
      margin-top: 30px;
      font-size: 16px;
    }
  </style>
</head>
<body>
  <img src="https://yourlogo-link.com" alt="Saveetha Logo" width="200">
  <div class="thank-you">
    Thank you for being a part of our sports event!<br>
    Your energy and enthusiasm made it truly unforgettable!
  </div>
  <img src="https://your-animation-link.com" alt="Celebration" width="120">
  <div class="contact">
    Contact us:<br>
    saveethaengineeringsec@gmail.com<br>
    +91 8939902737
  </div>
</body>
</html>
```


## OUTPUT:
![image](https://github.com/user-attachments/assets/69442aaa-3190-458e-98f0-5a5490123838)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
