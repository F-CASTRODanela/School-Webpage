<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sunnydale School</title>
    <style>
        /* Enhance the Page Title */
        h1 {
            font-size: 24px;
            font-weight: bold;
            color: #1E90FF; /* Blue */
        }

        /* Customize Fonts and Section Colors */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9; /* Light Gray */
            color: #333; /* Dark Gray Text */
        }

        h2 {
            font-size: 20px;
            padding-bottom: 10px;
        }

        /* Mission Statement Section */
        #mission {
            color: #32CD32; /* Green for Mission Statement */
        }

        /* Upcoming Events Section */
        #upcoming-events {
            color: #FFA07A; /* Light Salmon for Upcoming Events */
            background-color: #FFFFE0; /* Light Yellow */
            padding: 15px;
        }

        /* Contact Us Section */
        #contact-us {
            color: #20B2AA; /* Light Sea Green for Contact Us */
        }

        /* Style for Outdoor Events */
        .outdoor {
            background-color: #AFEEEE; /* Pale Turquoise */
            padding: 5px;
            border: 1px solid #B0E0E6; /* Light Blue Border */
        }

        /* Style the Contact Info Box */
        .section {
            background-color: #f8f3f3; /* Light Gray Background */
            padding: 10px;
            margin-top: 20px;
            border-radius: 8px;
        }

        /* Style for Links and Interactive Elements */
        a {
            text-decoration: none;
            color: #1E90FF; /* Blue for Links */
        }

        a:hover {
            text-decoration: underline;
        }

        /* Upcoming Events Styling (Dates) */
        .event-date {
            font-weight: bold;
            color: red; /* Red for Event Dates */
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to Sunnydale School!</h1>
    </header>

    <section id="mission">
        <h2>Our Mission</h2>
        <p>At Sunnydale School, we are committed to fostering a positive and inspiring learning environment that encourages academic excellence, personal growth, and community involvement.</p>
    </section>

    <section id="upcoming-events">
        <h2>Upcoming Events</h2>
        <ul>
            <li data-event-type="indoor" title="Event Type: Indoor">Science Fair - <span class="event-date">June 10</span></li>
            <li class="outdoor" data-event-type="outdoor" title="Event Type: Outdoor">Art Exhibition - <span class="event-date">June 15</span></li>
            <li class="outdoor" data-event-type="outdoor" title="Event Type: Outdoor">Sports Day - <span class="event-date">June 20</span></li>
        </ul>
    </section>

    <section id="contact-us" class="section">
        <h2>Contact Us</h2>
        <div>
            <p>Email: <a href="mailto:contact@sunnydaleschool.com" title="Click to copy email">contact@sunnydaleschool.com</a></p>
            <p>Phone: <a href="tel:+1234567890" title="Click to copy phone number">+1 (234) 567-890</a></p>
        </div>
        <!-- Imagine clicking here shows a message: 'Thanks for reaching out!' -->
    </section>

</body>
</html>
