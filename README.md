# Ex09 Event Registration Web Application
## Date:

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
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sports Day Events</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body class="home">
  <header>
    <h1>SPORTS DAY EVENTS!!</h1>
    <h2>Saveetha Engineering College</h2>
    <p>(Approved by AICTE & Affiliated to Anna University)</p>
  </header>
  <main>
    <div class="buttons">
      <a href="login.html" class="btn">Login</a>
      <a href="register.html" class="btn">Register</a>
    </div>
    <img src="sports-illustration.png" alt="Students playing sports" />
  </main>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Sport Events Ahead</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body class="events">
  <header>
    <h1>Sport Events Ahead !!!</h1>
  </header>
  <main>
    <ul class="event-list">
      <li>Cricket</li>
      <li>Basketball</li>
      <li>Volleyball</li>
      <li>100 MTS</li>
      <li>Badminton</li>
      <li>Tennis</li>
    </ul>
    <img src="sports-silhouettes.png" alt="Silhouettes of sports" />
  </main>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Event Registration</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body class="register">
  <header>
    <h1>EVENT REGISTRATION FORM</h1>
  </header>
  <main>
    <form>
      <label>Full Name: <input type="text" name="name" required /></label>
      <label>Gender:
        <select name="gender">
          <option>Male</option>
          <option>Female</option>
          <option>Other</option>
        </select>
      </label>
      <label>Age: <input type="number" name="age" required /></label>
      <label>Mobile Number: <input type="tel" name="mobile" required /></label>
      <label>Event to Register:
        <select name="event">
          <option>Cricket</option>
          <option>Basketball</option>
          <option>Volleyball</option>
          <option>100 MTS</option>
          <option>Badminton</option>
          <option>Tennis</option>
        </select>
      </label>
      <button type="submit">Submit</button>
    </form>
    <img src="sports-equipment.png" alt="Sports equipment background" />
  </main>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Thank You</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body class="thankyou">
  <header>
    <h1>THANK YOU!!!</h1>
  </header>
  <main>
    <p>We are eagerly waiting for your participation in our parent event!!!</p>
    <p>Email: <a href="mailto:saveethaengineering@gmail.com">saveethaengineering@gmail.com</a></p>
    <p>Phone: <a href="tel:1234567890">1234567890</a></p>
    <img src="thankyou-sports.png" alt="Thank you with sports equipment" />
  </main>
</body>
</html>
```
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 20px;
  text-align: center;
  background-color: #f5f5f5;
}

header {
  background-color: #004080;
  color: white;
  padding: 20px 0;
}

h1 {
  margin: 0;
  font-size: 2em;
}

h2 {
  margin: 10px 0;
}

main {
  margin-top: 20px;
}

.btn {
  display: inline-block;
  margin: 10px;
  padding: 10px 20px;
  background-color: #0080ff;
  color: white;
  text-decoration: none;
  border-radius: 5px;
}

.event-list {
  list-style: none;
  padding: 0;
  font-size: 1.2em;
}

form {
  display: flex;
  flex-direction: column;
  gap: 15px;
  max-width: 400px;
  margin: auto;
}

form label {
  display: flex;
  flex-direction: column;
  text-align: left;
}

form button {
  padding: 10px;
  background-color: #004080;
  color: white;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

img {
  margin-top: 20px;
  max-width: 100%;
  height: auto;
}
```


## OUTPUT:





## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
