<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="home-section">
        <h1>Welcome to Olawale's Portfolio</h1>
        <p>Hello! I'm Ayeni Olawale, a web developer.</p>
        <button><a href="#projects">See My Work</a></button>
    </section>

    <section id="about" class="about-section">
        <h2>About Me</h2>
        <p> Hi I'm Ayeni Olawale, a passionate web developer with a knack for creating seamless and dynamic websites. With a strong foundation in [HTML, CSS, JavaScript, and other relevant technologies], I specialize in developing responsive and user-friendly web applications that deliver optimal performance across all devices.
I am driven by the challenge of solving problems through code and enjoy staying up-to-date with the latest trends in web development. Whether it's building a website from scratch or optimizing an existing one, I bring a keen eye for detail and a commitment to creating clean, efficient code.
My goal is to help businesses and individuals bring their online presence to life with custom, innovative solutions. I believe in collaborating closely with clients to understand their vision, ensuring the end product exceeds expectations.
Thank you for visiting my portfolio! I look forward to connecting and exploring how I can contribute to your next project. </p>
    </section>

    <section id="projects" class="projects-section">
        <h2>My Projects</h2>
        <div class="project-gallery">
            <div class="project-card">
                <h3>Project 1</h3>
                <p>< Web Application for a Healthcare Provider

Overview
Design and develop a web application for a healthcare provider to manage patient information, appointments, and medical records.

Features
1. Patient Portal: Create a patient portal for patients to access their medical records, appointment schedules, and billing information.
2. Appointment Scheduling: Implement an appointment scheduling feature for patients to schedule appointments online.
3. Medical Records: Allow healthcare providers to manage patient medical records, including lab results, prescriptions, and medical history.
4. Billing and Insurance: Implement a billing and insurance feature to manage patient billing and insurance information.
5. Secure Messaging: Provide a secure messaging feature for patients to communicate with healthcare providers.
6. Admin Dashboard: Create an admin dashboard for healthcare providers to manage patient information, appointments, and medical records.

Technologies
1. Front-end: HTML5, CSS3, JavaScript, React or Angular
2. Back-end: Node.js, Express.js, MongoDB or MySQL
3. Security: Implement HIPAA-compliant security measures to protect patient data./p>
            </div>
            <div class="project-card">
                <h3>Project 2</h3>
                <p>E-commerce Website for an Online RetailerOverview
Design and develop an e-commerce website for an online retailer that sells clothing, accessories, and home goods. The website should provide a seamless user experience, easy navigation, and a secure checkout.

Features
1. Responsive Design: Ensure the website is responsive and works well on various devices, including desktops, laptops, tablets, and mobile phones.
2. Product Catalog: Create a product catalogue that allows users to browse and search for products by category, price, brand, and other relevant filters.
3. Shopping Cart: Implement a shopping cart that allows users to add, remove, and update products.
4. Secure Checkout: Integrate a secure payment gateway to process transactions.
5. User Accounts: Users can create accounts to save payment and shipping information.
6. Order Tracking: Provide users with order tracking information.
7. Admin Dashboard: Create an admin dashboard for the online retailer to manage products, orders, and customer information.

Technologies
1. Front-end: HTML5, CSS3, JavaScript, React or Angular
2. Back-end: Node.js, Express.js, MongoDB or MySQL
3. Payment Gateway: Stripe, PayPal, or (link unavailable)</p>
            </div>
            <div class="project-card">
                <h3>Project 3</h3>
                <p>Social Media Platform for a Niche Community

Overview
Design and develop a social media platform for a niche community of photographers. The platform should allow users to share their photos, connect with other photographers, and participate in discussions.

Features

1. User Profiles: Allow users to create profiles to showcase their photos and connect with other users.
2. Photo Sharing: Implement a photo sharing feature that allows users to upload and share their photos.
3. Discussion Forums: Create discussion forums for users to participate in discussions related to photography.
4. Groups: Allow users to create and join groups based on their interests.
5. Events: Implement an events feature to allow users to create and attend photography events.
6. Notifications: Provide users with notifications for new comments, likes, and mentions.
7. Admin Dashboard: Create an admin dashboard to manage users, groups, and events.

Technologies
1. Front-end: HTML5, CSS3, JavaScript, React or Angular
2. Back-end: Node.js, Express.js, MongoDB or MySQL
3. Image Processing: ImageMagick or GraphicsMagick.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact-section">
        <h2>Contact Me</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 </p>
    </footer>
</body>
</html>
