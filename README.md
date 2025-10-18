# India-tour-connect-
It's travel company 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>India Tour Connect</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://cdn.jsdelivr.net/npm/emailjs-com@2.6.4/dist/email.min.js"></script>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>India Tour Connect</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#trips">Trips</a>
            <a href="#hotels">Hotels</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Slider -->
    <section id="home" class="slider">
        <img src="images/slider1.jpg" alt="Ayodhya" class="active">
        <img src="images/slider2.jpg" alt="Varanasi">
        <img src="images/slider3.jpg" alt="Himachal">
    </section>

    <!-- Trip Packages -->
    <section id="trips">
        <h2>Our Trip Packages</h2>
        <div class="search-bar">
            <input type="text" id="searchInput" placeholder="Search Destination...">
        </div>
        <div class="trip-cards">
            <div class="trip-card" data-destination="Ayodhya">
                <h3>Ayodhya - 2 Days / 1 Night</h3>
                <p>Price: ₹8000 for 5 persons</p>
            </div>
            <div class="trip-card" data-destination="Varanasi">
                <h3>Varanasi - 3 Days / 2 Nights</h3>
                <p>Price: ₹12000 for 5 persons</p>
            </div>
            <div class="trip-card" data-destination="Himachal">
                <h3>Himachal - 5 Days / 4 Nights</h3>
                <p>Price: ₹20000 for 5 persons</p>
            </div>
        </div>
    </section>

    <!-- Hotel Registration -->
    <section id="hotels">
        <h2>Hotel Registration (Free)</h2>
        <form>
            <input type="text" placeholder="Hotel Name" required>
            <input type="text" placeholder="Location" required>
            <input type="number" placeholder="Contact Number" required>
            <button type="submit">Register</button>
        </form>
    </section>

    <!-- Contact / Booking -->
    <section id="contact">
        <h2>Book Your Trip</h2>
        <form id="bookingForm">
            <input type="text" name="user_name" placeholder="Your Name" required>
            <input type="email" name="user_email" placeholder="Email" required>
            <input type="number" name="persons" placeholder="Number of Persons" required>
            <select name="trip_package">
                <option>Select Trip Package</option>
                <option>Ayodhya - 2 Days / 1 Night</option>
                <option>Varanasi - 3 Days / 2 Nights</option>
                <option>Himachal - 5 Days / 4 Nights</option>
            </select>
            <button type="submit">Book Now</button>
        </form>

        <div class="payment-methods">
            <h3>Payment Options:</h3>
            <a href="upi://pay?pa=yourupiid@okhdfcbank&pn=IndiaTourConnect&am=8000&cu=INR" target="_blank">
                <img src="images/upi.png" alt="UPI Payment" title="Pay via UPI">
            </a>
            <a href="https://pay.google.com/gp/p/u/0/pay?pa=yourupiid@okhdfcbank&pn=IndiaTourConnect&am=8000&cu=INR" target="_blank">
                <img src="images/gpay.png" alt="GPay" title="Pay via Google Pay">
            </a>
        </div>
        <p>Founder: Yug Srivastav</p>
    </section>

    <footer>
        <p>&copy; 2025 India Tour Connect. All Rights Reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>India Tour Connect</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://cdn.jsdelivr.net/npm/emailjs-com@2.6.4/dist/email.min.js"></script>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>India Tour Connect</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#trips">Trips</a>
            <a href="#hotels">Hotels</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Slider -->
    <section id="home" class="slider">
        <img src="images/slider1.jpg" alt="Ayodhya" class="active">
        <img src="images/slider2.jpg" alt="Varanasi">
        <img src="images/slider3.jpg" alt="Himachal">
    </section>

    <!-- Trip Packages -->
    <section id="trips">
        <h2>Our Trip Packages</h2>
        <div class="search-bar">
            <input type="text" id="searchInput" placeholder="Search Destination...">
        </div>
        <div class="trip-cards">
            <div class="trip-card" data-destination="Ayodhya">
                <h3>Ayodhya - 2 Days / 1 Night</h3>
                <p>Price: ₹8000 for 5 persons</p>
            </div>
            <div class="trip-card" data-destination="Varanasi">
                <h3>Varanasi - 3 Days / 2 Nights</h3>
                <p>Price: ₹12000 for 5 persons</p>
            </div>
            <div class="trip-card" data-destination="Himachal">
                <h3>Himachal - 5 Days / 4 Nights</h3>
                <p>Price: ₹20000 for 5 persons</p>
            </div>
        </div>
    </section>

    <!-- Hotel Registration -->
    <section id="hotels">
        <h2>Hotel Registration (Free)</h2>
        <form>
            <input type="text" placeholder="Hotel Name" required>
            <input type="text" placeholder="Location" required>
            <input type="number" placeholder="Contact Number" required>
            <button type="submit">Register</button>
        </form>
    </section>

    <!-- Contact / Booking -->
    <section id="contact">
        <h2>Book Your Trip</h2>
        <form id="bookingForm">
            <input type="text" name="user_name" placeholder="Your Name" required>
            <input type="email" name="user_email" placeholder="Email" required>
            <input type="number" name="persons" placeholder="Number of Persons" required>
            <select name="trip_package">
                <option>Select Trip Package</option>
                <option>Ayodhya - 2 Days / 1 Night</option>
                <option>Varanasi - 3 Days / 2 Nights</option>
                <option>Himachal - 5 Days / 4 Nights</option>
            </select>
            <button type="submit">Book Now</button>
        </form>

        <div class="payment-methods">
            <h3>Payment Options:</h3>
            <a href="upi://pay?pa=yourupiid@okhdfcbank&pn=IndiaTourConnect&am=8000&cu=INR" target="_blank">
                <img src="images/upi.png" alt="UPI Payment" title="Pay via UPI">
            </a>
            <a href="https://pay.google.com/gp/p/u/0/pay?pa=yourupiid@okhdfcbank&pn=IndiaTourConnect&am=8000&cu=INR" target="_blank">
                <img src="images/gpay.png" alt="GPay" title="Pay via Google Pay">
            </a>
        </div>
        <p>Founder: .Yug Srivastav</p>
    </section>

    <footer>
        <p>&copy; 2025 India Tour Connect. All Rights Reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
