<!doctype html>
<html lang="en"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>AdvenTrip - Explore the World</title> 
  <link rel="stylesheet" href="styles.css"> 
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"> 
 </head> 
 <body> 
   <style>/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

a {
    text-decoration: none;
    color: inherit;
}

/* Navbar Styles */
.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1rem;
    background-color: #2c3e50;
}

.navbar-left a {
    font-size: 1.5rem;
    color: white;
    font-weight: bold;
}

.navbar-right a, .sign-up {
    color: white;
    margin: 0 1rem;
    font-size: 1rem;
    transition: color 0.3s;
}

.navbar-right a:hover, .sign-up:hover {
    color: #3498db;
}

.sign-up {
    background-color: #3498db;
    border: none;
    padding: 0.5rem 1rem;
    cursor: pointer;
}

.navbar-right.active {
    display: block;
}

/* Hero Section */
.hero {
    display: flex;
    justify-content: space-between;
    padding: 4rem;
    background-color: #f3f3f3;
}

.hero-text h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero-text p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
}

.cta-buttons button {
    padding: 0.7rem 1.5rem;
    border: none;
    margin-right: 1rem;
    cursor: pointer;
    transition: background-color 0.3s;
}

.book-now {
    background-color: #3498db;
    color: white;
}

.play-video {
    background-color: #2c3e50;
    color: white;
}

.book-now:hover, .play-video:hover {
    background-color: #2980b9;
}

/* Statistics Section */
.statistics {
    display: flex;
    justify-content: space-around;
    padding: 2rem;
    background-color: #ecf0f1;
}

.stat-box h2 {
    font-size: 2rem;
    color: #2c3e50;
}

.stat-box p {
    color: #7f8c8d;
}

/* Services Section */
.services {
    text-align: center;
    padding: 4rem;
    background-color: #fff;
}

.service-cards {
    display: flex;
    justify-content: space-around;
}

.service-card {
    padding: 1.5rem;
    border: 1px solid #bdc3c7;
    width: 20%;
    transition: box-shadow 0.3s;
}

.service-card:hover {
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.service-card .icon {
    font-size: 2rem;
    margin-bottom: 1rem;
}

/* Doctors Section */
.doctors {
    text-align: center;
    padding: 4rem;
    background-color: #ecf0f1;
}

.doctor-cards {
    display: flex;
    justify-content: space-around;
}

.doctor-card {
    padding: 1.5rem;
    border: 1px solid #bdc3c7;
    width: 20%;
    transition: transform 0.3s;
}

.doctor-card:hover {
    transform: translateY(-10px);
}

/* Footer Section */
footer {
    background-color: #2c3e50;
    color: white;
    padding: 2rem;
}

.footer-top {
    display: flex;
    justify-content: space-between;
}

.footer-logo {
    font-size: 1.5rem;
}

.footer-links ul {
    list-style: none;
    padding: 0;
}

.footer-links a {
    color: white;
    transition: color 0.3s;
}

.footer-links a:hover {
    color: #3498db;
}

/* Mobile Responsiveness */
@media (max-width: 768px) {
    .hero {
        flex-direction: column;
        align-items: center;
    }

    .service-cards, .doctor-cards {
        flex-direction: column;
        align-items: center;
    }

    .service-card, .doctor-card {
        width: 80%;
        margin-bottom: 1rem;
    }

    .navbar-right {
        display: none;
    }

    .navbar-right.active {
        display: flex;
        flex-direction: column;
        position: absolute;
        top: 60px;
        right: 0;
        background-color: #2c3e50;
        width: 100%;
        text-align: center;
        padding: 1rem 0;
    }

    .menu-toggle {
        display: block;
        color: white;
        cursor: pointer;
    }
}/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Arial', sans-serif;
  line-height: 1.6;
}

/* Navbar */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  background: #f4f4f4;
}

.navbar-left .logo {
  font-size: 1.5rem;
  font-weight: bold;
  text-decoration: none;
  color: black;
}

.navbar-right a, .navbar-right .sign-up {
  margin-left: 20px;
  text-decoration: none;
  color: black;
  font-size: 1rem;
}

.navbar-right .sign-up {
  background-color: black;
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

/* Hero Section */
.hero {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 50px;
  background-color: #e8f5fe;
}

.hero-text h1 {
  font-size: 2.5rem;
}

.hero-text p {
  margin-top: 20px;
  font-size: 1.2rem;
}

.cta-buttons {
  margin-top: 20px;
}

.cta-buttons .book-now, .cta-buttons .play-video {
  padding: 10px 20px;
  border: none;
  background: black;
  color: white;
  cursor: pointer;
  margin-right: 10px;
}

/* Statistics Section */
.statistics {
  display: flex;
  justify-content: space-between;
  padding: 50px;
  background-color: #f9f9f9;
}

.stat-box h2 {
  font-size: 2.5rem;
  color: #333;
}

/* Services Section */
.services {
  text-align: center;
  padding: 50px;
  background-color: #fff;
}

.services h2 {
  margin-bottom: 20px;
}

.service-cards {
  display: flex;
  justify-content: space-between;
}

.service-card {
  text-align: center;
  width: 22%;
  padding: 20px;
  background-color: #f4f4f4;
}

.service-card h3 {
  margin-top: 10px;
}

.service-card .icon {
  font-size: 2rem;
  color: #333;
}

/* Doctors Section */
.doctors {
  text-align: center;
  padding: 50px;
  background-color: #f9f9f9;
}

.doctor-cards {
  display: flex;
  justify-content: space-between;
}

.doctor-card {
  width: 22%;
  background-color: #fff;
  padding: 20px;
  text-align: center;
}

.doctor-card img {
  width: 100%;
  border-radius: 50%;
}

/* Footer Section */
footer {
  background-color: #333;
  color: white;
  padding: 50px;
}

.footer-top {
  display: flex;
  justify-content: space-between;
}

.footer-links ul {
  list-style: none;
}

.footer-links ul li {
  margin-bottom: 10px;
}

.footer-bottom {
  text-align: center;
  margin-top: 20px;
}

/* Responsive Design */
@media (max-width: 768px) {
  .navbar-right a, .navbar-right .sign-up {
    display: none;
  }

  .hero {
    flex-direction: column;
    text-align: center;
  }

  .statistics {
    flex-direction: column;
  }</style>
   <!-- Navbar --> 
  <nav class="navbar"> 
   <div class="navbar-left"> <a href="#" class="logo"><strong>Adven</strong>Trip</a> 
   </div> 
   <div class="navbar-right"> <a href="#">Home</a> <a href="#">Destinations</a> <a href="#">Packages</a> <a href="#">Guides</a> <a href="#">About Us</a> <a href="#">Log In</a> <button class="sign-up">Sign Up</button> 
   </div> 
  </nav> <!-- Main Banner Section --> 
  <section class="hero"> 
   <div class="hero-text"> 
    <h1>Discover the <br> World with Us</h1> 
    <p>Experience unforgettable adventures in the most stunning locations.</p> 
    <div class="cta-buttons"> <button class="book-now">Book Now</button> <button class="play-video">Watch Tour</button> 
    </div> 
   </div> 
   <div class="hero-image"> 
    <img src="mountain_hiking.jpg" alt="Adventure in the Mountains"> 
   </div> 
  </section> <!-- Statistics Section --> 
  <section class="statistics"> 
   <div class="stat-box"> 
    <h2>98%</h2> 
    <p>Customer Satisfaction</p> 
   </div> 
   <div class="stat-box"> 
    <h2>100+</h2> 
    <p>Destinations Worldwide</p> 
   </div> 
   <div class="stat-box"> 
    <h2>10,000+</h2> 
    <p>Happy Adventurers</p> 
   </div> 
   <div class="stat-box"> 
    <h2>5,000+</h2> 
    <p>Successful Tours</p> 
   </div> 
  </section> <!-- Services Section --> 
  <section class="services"> 
   <h2>Our Top Travel Services</h2> 
   <div class="service-cards"> 
    <div class="service-card"> 
     <div class="icon">
      <i class="fa fa-globe"></i>
     </div> 
     <h3>Global Destinations</h3> 
     <p>Explore top adventure spots around the world.</p> 
    </div> 
    <div class="service-card"> 
     <div class="icon">
      <i class="fa fa-heartbeat"></i>
     </div> 
     <h3>Safety First</h3> 
     <p>Your safety is our top priority during all trips.</p> 
    </div> 
    <div class="service-card"> 
     <div class="icon">
      <i class="fa fa-plane"></i>
     </div> 
     <h3>All-Inclusive Packages</h3> 
     <p>Travel hassle-free with our comprehensive trip packages.</p> 
    </div> 
    <div class="service-card"> 
     <div class="icon">
      <i class="fa fa-comments"></i>
     </div> 
     <h3>24/7 Support</h3> 
     <p>Get support anytime, anywhere during your adventures.</p> 
    </div> 
   </div> 
  </section> <!-- Guides Section --> 
  <section class="guides"> 
   <h2>Meet Our Expert Guides</h2> 
   <div class="guide-cards"> 
    <div class="guide-card"> 
     <img src="guide_image.jpg" alt="Adventure Guide"> 
     <h3>John Smith</h3> 
     <p>Expert in Mountain Hiking</p> 
    </div> 
    <div class="guide-card"> 
     <img src="guide_image.jpg" alt="Adventure Guide"> 
     <h3>Emily Jones</h3> 
     <p>Specialist in Scuba Diving</p> 
    </div> 
    <div class="guide-card"> 
     <img src="guide_image.jpg" alt="Adventure Guide"> 
     <h3>David Lee</h3> 
     <p>Safari and Wildlife Expert</p> 
    </div> 
   </div> 
  </section> <!-- Footer Section --> 
  <footer> 
   <div class="footer-top"> 
    <div class="footer-logo"> <strong>Adven</strong>Trip 
    </div> 
    <div class="footer-links"> 
     <h3>Explore</h3> 
     <ul> 
      <li><a href="#">Destinations</a></li> 
      <li><a href="#">Packages</a></li> 
     </ul> 
    </div> 
    <div class="footer-links"> 
     <h3>Contact Us</h3> 
     <ul> 
      <li><a href="#">Email</a></li> 
      <li><a href="#">Phone</a></li> 
     </ul> 
    </div> 
   </div> 
   <div class="footer-bottom">
     © 2024 Designed by AdvenTrip 
   </div> 
  </footer> 
 </body>
 <script >
   // JavaScript for AdvenTrip Website

// Smooth Scroll for Navbar Links
document.querySelectorAll('nav a').forEach(anchor => {
    anchor.addEventListener('click', function(e) {
        e.preventDefault();
        document.querySelector(this.getAttribute('href')).scrollIntoView({
            behavior: 'smooth'
        });
    });
});

// Testimonials - Auto Rotate
let testimonialIndex = 0;
const testimonials = document.querySelectorAll('.testimonial-card');
const rotateTestimonials = () => {
    testimonials.forEach((testimonial, index) => {
        testimonial.style.display = (index === testimonialIndex) ? 'block' : 'none';
    });
    testimonialIndex = (testimonialIndex + 1) % testimonials.length;
};
setInterval(rotateTestimonials, 5000);  // Change testimonial every 5 seconds

// Newsletter Subscription Form Validation and Submission
const newsletterForm = document.querySelector('.newsletter-form');
newsletterForm.addEventListener('submit', function(e) {
    e.preventDefault();
    const emailInput = this.querySelector('input[type="email"]').value;

    // Simple Email Validation
    const emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
    if (!emailPattern.test(emailInput)) {
        alert('Please enter a valid email address');
        return;
    }

    // Simulate Newsletter Subscription Success
    alert('Thank you for subscribing to our newsletter!');
    this.reset();  // Clear the form after submission
});

// Book Now Button Click Event
document.querySelector('.book-now').addEventListener('click', () => {
    alert('Redirecting to the booking page...');
    // Simulate redirect (could use window.location.href in a real implementation)
});

// Play Video Button Click Event (Assuming there is a video modal)
document.querySelector('.play-video').addEventListener('click', () => {
    alert('Playing the promotional video...');
    // Simulate video playback (could open a modal or video player in a real implementation)
});

// Guides - Hover Effect (Show more info on hover)
document.querySelectorAll('.guide-card').forEach(card => {
    card.addEventListener('mouseenter', () => {
        card.style.transform = 'scale(1.05)';
        card.style.transition = 'transform 0.3s ease';
    });
    card.addEventListener('mouseleave', () => {
        card.style.transform = 'scale(1)';
    });
});

// Add Sticky Navbar
window.addEventListener('scroll', () => {
    const navbar = document.querySelector('nav');
    navbar.classList.toggle('sticky', window.scrollY > 0);
});

// Show and Hide Blog Cards (Example of Dynamic Content)
const blogCards = document.querySelectorAll('.blog-card');
let blogIndex = 3;
document.querySelector('.show-more-blogs').addEventListener('click', () => {
    blogIndex = Math.min(blogIndex + 3, blogCards.length);
    for (let i = 0; i < blogIndex; i++) {
        blogCards[i].style.display = 'block';
    }
    if (blogIndex === blogCards.length) {
        document.querySelector('.show-more-blogs').style.display = 'none';
    }
});  
 </script>
</html>