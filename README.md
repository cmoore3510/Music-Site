# Music-Site
CSCI 3000 Project
# Index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dahlonega Music Shoppe</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Dahlonega Music Shoppe</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="instruments.html">Instruments</a></li>
                <li><a href="lessons.html">Lessons</a></li>
            </ul>
        </nav>
    </header>
    <section class="main-content">
        <h2>About Us</h2>
        <p>Welcome to Dahlonega Music Shoppe, your one-stop destination for all things music! We've been serving musicians since 2014, providing high-quality instruments, expert advice, and top-notch lessons.</p>
        <p>At Dahlonega Music Shoppe, we believe that everyone should have the opportunity to experience the joy of music. Whether you're a beginner or a seasoned pro, we're here to help you on your musical journey.</p>
        <img src="store interior.jpg" alt="Store Exterior" width="400">
        <img src="guitars.jpg" alt="Instruments Display" width="400">
    </section>
    <section class="additional-info">
        <h2>Additional Information</h2>
        <p>Store Hours:</p>
        <p>Monday - Friday: 10:00 AM - 8:00 PM</p>
        <p>Saturday: 10:00 AM - 6:00 PM</p>
        <p>Sunday: Closed</p>
        <p>Location:</p>
        <address>
            123 Music Street<br>
            Dahlonega, GA 30597<br>
        </address>
        <p>Contact Us:</p>
        <p>Phone: 706-330-7890</p>
        <p>Email: info@dahlonegamusicshoppe.com</p>
    </section>
    <footer>
        <p>&copy; 2024 Dahlonega Music Shoppe</p>
    </footer>
</body>
</html>

# instruments.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dahlonega Music Shoppe - Instruments</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Dahlonega Music Shoppe - Instruments</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="instruments.html">Instruments</a></li>
                <li><a href="lessons.html">Lessons</a></li>
            </ul>
        </nav>
    </header>
    <section class="instrument-list">
        <h2>Available Instruments</h2>
        <div class="instrument">
            <img src="acoustic guitar.jpg" alt="Acoustic Guitar" width="200">
            <h3>Acoustic Guitar</h3>
            <p>Price: $300</p>
        </div>
        <div class="instrument">
            <img src="electric guitar.jpeg" alt="Electric Guitar" width="200">
            <h3>Electric Guitar</h3>
            <p>Price: $400</p>
        </div>
        <div class="instrument">
            <img src="bass guitars.jpg" alt="Bass Guitar" width="200">
            <h3>Bass Guitar</h3>
            <p>Price: $350</p>
        </div>
        <div class="instrument">
            <img src="folk instruments.jpg" alt="Acoustic Guitar" width="200">
            <h3>Folk Instruments</h3>
            <p>Price: $200</p>
        </div>
        <div class="instrument">
            <img src="effects and pedals.jpg" alt="Acoustic Guitar" width="200">
            <h3>Effects and Pedals</h3>
            <p>Price: $250</p>
        </div>
        <!-- Add more instruments here -->
        
    </section>
    <footer>
        <p>&copy; 2024 Dahlonega Music Shoppe</p>
    </footer>
</body>
</html>

# lessons.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dahlonega Music Shoppe - Lessons</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Dahlonega Music Shoppe - Lessons</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="instruments.html">Instruments</a></li>
                <li><a href="lessons.html">Lessons</a></li>
            </ul>
        </nav>
    </header>
    <section class="lesson-booking">
        <h2>Book a Lesson</h2>
        <p>At Dahlonega Music Shoppe, we think that personalized, one-on-one music lessons are the best way to learn a new instrument, hone your musical skills, break out of a rut, or just expand your musical horizons. And it is never too late to learn!</p>
        <p>The program is simple and flexible. All lessons cost $30 per half hour lesson, per person, once per week.</p>
        <p>Guitar, bass, piano, voice, banjo, mandolin, brass, woodwinds … if you want to learn it, there is a good chance we have an expert instructor who can offer you a lesson program tailored to your needs and learning style. All lessons take place right here in our shop in one of our six dedicated lesson studios.</p>
        <p>To enroll, just call or email us at the shop. We will find a day and time that works for you and your chosen instructor, and that becomes your time slot every week. No long-term commitments. Your time slot is reserved until you tell us that you need to change it or cancel. And, besides the tailored, expert instruction, you will also get the opportunity to show off your skills at one of our recitals, camps or performances.</p>
        <p>Check in with us today to take your musical journey to the next level!</p>

        <h2>Our Instructors</h2>
        <div class="instructor-list">
            <div class="instructor">
                <img src="instructor1.jpeg" alt="Instructor 1">
                <h3>John Smith</h3>
                <p>Instruments: Guitar, Bass</p>
            </div>
            <div class="instructor">
                <img src="instructor2.png" alt="Instructor 2">
                <h3>Will Smith</h3>
                <p>Instruments: Piano, Voice</p>
            </div>
            <!-- Add more instructors here -->
        </div>
    </section>
    <footer>
        <p>&copy; 2024 Dahlonega Music Shoppe</p>
    </footer>
</body>
</html>


# /* styles.css */

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 20px;
}

header h1 {
    margin: 0;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

a {
    color: #fff;
    text-decoration: none;
}

.main-content {
    padding: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}
