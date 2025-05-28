# Ex09 Event Registration Web Application
## Date: 20/05/25


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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Event Registration</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: url('https://images.unsplash.com/photo-1549924231-f129b911e442?auto=format&fit=crop&w=1400&q=80') no-repeat center center fixed;
      background-size: cover;
      margin: 0;
      padding: 0;
    }

    .container {
      max-width: 500px;
      margin: 50px auto;
      background: rgba(255, 255, 255, 0.95);
      border-radius: 12px;
      padding: 30px;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.3);
    }

    h1 {
      text-align: center;
      color: #2575fc;
    }

    p {
      text-align: center;
      margin-bottom: 25px;
    }

    .registration-form label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
    }

    .registration-form input,
    .registration-form select {
      width: 100%;
      padding: 10px;
      margin-top: 8px;
      border-radius: 6px;
      border: 1px solid #ccc;
      font-size: 16px;
    }

    button {
      margin-top: 20px;
      width: 100%;
      background-color: #2575fc;
      color: white;
      padding: 12px;
      border: none;
      border-radius: 6px;
      font-size: 16px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #1a56d9;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Sports Fest 2025</h1>
    <p>Register now and be part of thrilling sports events and competitions!</p>
    <form action="#" method="post" class="registration-form">
      <label for="name">Full Name:</label>
      <input type="text" id="name" name="name" required>

      <label for="email">Email Address:</label>
      <input type="email" id="email" name="email" required>

      <label for="phone">Phone Number:</label>
      <input type="tel" id="phone" name="phone" required>

      <label for="event">Choose Sport:</label>
      <select id="event" name="event">
        <option value="football">Football</option>
        <option value="basketball">Basketball</option>
        <option value="cricket">Cricket</option>
        <option value="athletics">Athletics</option>
        <option value="badminton">Badminton</option>
      </select>

      <button type="submit">Register Now</button>
    </form>
  </div>
</body>
</html>

```


## OUTPUT:
![image](https://github.com/user-attachments/assets/8c870275-3ab0-420e-9399-7fb08aed29c5)



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
