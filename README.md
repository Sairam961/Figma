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
Home page:

     <!DOCTYPE html>
     <html lang="en">
     <head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>Sports Day Events</title>
     <link rel="stylesheet" href="style.css">
     </head>
     <body>
     <div class="phone-frame">
        <div class="header">E
            <img src="https://via.placeholder.com/80x80?text=Logo" alt="College Logo" class="logo">
            <h2>SAVEETHA ENGINEERING COLLEGE</h2>
            <p class="tagline">BE THE BEST</p>
        </div>

        <div class="content">
            <h1 class="main-title">SPORTS DAY EVENTS</h1>
            <div class="sports-icon">⚽🏸🏐</div>
            
            <div class="button-group">
                <a href="#" class="btn btn-login">LOGIN</a>
                <a href="registration.html" class="btn btn-register">REGISTER</a>
            </div>
        </div>

        <div class="footer-text">
            <p>"BORN TO WIN"</p>
        </div>
    </div>
    </body>
    </html>

Events Page:

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Events List</title>
    <link rel="stylesheet" href="style.css">
    </head>
    <body>
    <div class="phone-frame">
        <div class="header-small">
            <h2>SPORTS DAY EVENTS</h2>
        </div>

        <div class="events-list">
            <h3>SPORTS DAY EVENTS</h3>
            
            <ul class="event-items">
                <li>★ CRICKET</li>
                <li>★ BADMINTON</li>
                <li>★ VOLLEY BALL</li>
                <li>★ 100 MTS</li>
                <li>★ 200MTS</li>
                <li>★ 400MTS</li>
                <li>★ 4+100 RELAY</li>
            </ul>

            <div class="illustration">
                <p>🏃‍♂️ 🏃‍♀️ 🎉</p>
            </div>
        </div>
    </div>
    </body>
    </html>

Registration page:

     <!DOCTYPE html>
     <html lang="en">
     <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Registration</title>
    <link rel="stylesheet" href="style.css">
    </head>
    <body>
    <div class="phone-frame">
        <div class="header-small">
            <h2>EVENT REGISTRATION FORM</h2>
            <p>Fill the details</p>
        </div>

        <div class="form-container">
            <form id="regForm" onsubmit="submitForm(event)">
                <input type="text" placeholder="Full Name" required>
                <input type="text" placeholder="Gender" required>
                <input type="number" placeholder="Age" required>
                <input type="text" placeholder="Register Number" required>
                <input type="text" placeholder="Department" required>
                <input type="tel" placeholder="Mobile Number" required>
                <input type="email" placeholder="Email ID" required>
                <input type="text" placeholder="Events To Register" required>
                
                <button type="submit" class="btn btn-register">REGISTER</button>
            </form>

            <div class="player-icon">🏸</div>
        </div>
    </div>

    <script>
        function submitForm(e) {
            e.preventDefault();
            alert('Registration Successful!');
            window.location.href = 'thankyou.html';
        }
    </script>
    </body>
    </html>


Thank You page:

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thank You</title>
    <link rel="stylesheet" href="style.css">
    </head>
    <body>
    <div class="phone-frame">
        <div class="header-small">
            <img src="https://via.placeholder.com/80x80?text=Logo" alt="College Logo" class="logo">
            <h2>SAVEETHA ENGINEERING COLLEGE</h2>
        </div>

        <div class="thankyou-content">
            <h1>THANK YOU</h1>
            <p>We are all eagerly waiting<br>for your participation in<br>the sports events</p>
            
            <div class="sports-emoji">🏀 🎾</div>

            <div class="contact-info">
                <h3>Contact Us</h3>
                <p>saveethaengineeringcollege@gmail.com</p>
                <p>📞 6383843394</p>
                <p>📞 6383643394</p>
            </div>
        </div>
    </div>
    </body>
    </html>

## OUTPUT:


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
