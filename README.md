🌿 Green Earth – Environmental Awareness Website

Green Earth is a responsive environmental awareness website built using HTML5 and CSS3.
It promotes sustainability, climate action, and eco-friendly initiatives through a modern and user-friendly design.
📌 Features

🌍 Clean and modern UI design

📱 Fully responsive (desktop, tablet, mobile)

🧭 Fixed navigation bar with search option

🌱 Hero section with call-to-action buttons

🎯 Mission, Projects, and Resources sections

✉ Contact form layout

🔗 Footer with social media icons

🎨 CSS hover animations and transitions

🛠 Technologies Used

HTML5 – Page structure

CSS3 – Styling and responsiveness

You said:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GREEN EARTH</title>
    <link rel="stylesheet" href="index.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css">

</head>
<body>

<header>
    <!-- Navigation bar -->
    <a href="#" class="logo">🌿Green Earth<span></span></a>

    <nav class="navbar">
        <a href="#home">HOME</a>
        <a href="#about">ABOUT</a>
        <a href="#projects">PROJECTS</a>
        <a href="#resources">RESOURCES</a>
        <a href="#contact">CONTACT</a>


        <div class="search">
            <input class="srch" type="search" placeholder="Type to Search...">
            <button class="btn">Search</button>
        </div>
    </nav>
</header>
<!-- HERO SECTION -->
<section class="hero" id="home">
    <div class="hero-content">
        <h1>Protecting Nature for Future Generations</h1>
        <p>we promote sustainable living, conservation <br>and climate action to protect our Earth</p>
        <a href="#projects" class="hero-btn"><span></span>Explore More</a>
        <a href="#projects" class="hero-btn"><span></span>Join Us</a>
    </div>
</section>
<!-- MISSION SECTION -->
<section class="mission" id="mission">
    <h1 class="heading">Our Mission</h1>

    <div class="mission-container">
        <div class="mission-box">
            <h3>🌱 Protect Nature</h3>
            <p>
                We aim to conserve forests, wildlife, and natural ecosystems
                for future generations.
            </p>
        </div>

        <div class="mission-box">
            <h3>♻ Reduce Pollution</h3>
            <p>
                Promoting recycling, reducing plastic waste,
                and encouraging clean energy.
            </p>
        </div>

        <div class="mission-box">
            <h3>🌍 Sustainable Living</h3>
            <p>
                Inspiring eco-friendly lifestyles to create a greener planet.
            </p>
        </div>
    </div>
</section>
<!-- PROJECTS SECTION -->
<section class="projects" id="projects">
    <h1 class="heading">Our Projects</h1>
    <div class="projects-container">
        <div class="project-box">
            <h3>🎤 Youth Climate Meetup</h3>
            <p>
             Connect, discuss, and plan real environmental actions.   
            </p>
        </div>

        <div class="project-box">
            <h3>♻ Refuse the Plastic</h3>
            <p>
                Raising awareness to reduce single-use plastic and promote recycling.
            </p>
        </div>

        <div class="project-box">
            <h3>💧 Clean Water Initiative</h3>
            <p>
                Providing clean drinking water and protecting water resources.
            </p>
        </div>

        <div class="project-box">
            <h3>🌞 Solar Energy Program</h3>
            <p>
                Promoting renewable energy to reduce carbon footprint.
            </p>
        </div>
    </div>
</section>
<!-- RESOURCES SECTION -->
<section class="resources" id="resources">
    <h1 class="heading">Resources</h1>

    <div class="resources-container">
        <div class="resource-box">
            <h3>📘 Climate Change Guide</h3>
            <p>
                Learn the basics of climate change and how it affects our planet.
            </p>
            <a href="#" class="resource-btn"><span></span>Read More</a>
        </div>

        <div class="resource-box">
            <h3>♻ Recycling Handbook</h3>
            <p>
                Practical tips for reducing waste and recycling effectively.
            </p>
            <a href="#" class="resource-btn"><span></span>Download</a>
        </div>

        <div class="resource-box">
            <h3>🌍 Sustainability Tips</h3>
            <p>
                Simple actions you can take to live a more eco-friendly life.
            </p>
            <a href="#" class="resource-btn"><span></span>View Tips</a>
        </div>

        <div class="resource-box">
            <h3>🎥 Environmental Videos</h3>
            <p>
                Watch educational videos about nature and conservation.
            </p>
            <a href="#" class="resource-btn">Watch Now</a>
        </div>
    </div>
</section>
<!-- CONTACT SECTION -->
<section class="contact" id="contact">
    <h1 class="heading">Contact Us</h1>

    <div class="contact-container">
        <form action="" method="post">
            <input type="text" name="name" placeholder="Your Name" class="input-box" required>

            <input type="email" name="email" placeholder="Your Email" class="input-box" required>

            <textarea name="message" placeholder="Your Message" class="input-box" required></textarea>

            <button type="submit" class="contact-btn">
                Send Message
            </button>
        </form>
    </div>
</section>
<!-- FOOTER SECTION -->
<footer class="footer">
    <div class="footer-container">

        <!-- About -->
        <div class="footer-box">
            <h3>🌿 Green Earth</h3>
            <p>
                Working together to protect nature and create a
                sustainable future for coming generations.
            </p>
        </div>

        <div class="footer-box">
            <h3>Contact</h3>
            <p>Email: greenearth@email.com</p>
            <p>Phone: +92 300 1234567</p>
            <p>Location: Pakistan</p>

            <div class="social-icons"><p>follow us</p>
                <a href="#"><i class="fab fa-facebook-f"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-linkedin-in"></i></a>
            </div>
        </div>

    </div>

    <div class="footer-bottom">
        <p>© 2025 Green Earth | Every Action Counts 🌍</p>
    </div>
</footer>


</body>
</html>
ChatGPT said:
Your HTML is correct and well-structured 👍
What’s missing now is a proper index.css to make everything look clean, responsive, and professional.

Below is a complete index.css that matches your HTML exactly (navbar, hero, sections, footer, social icons, buttons, etc.).
Just create index.css and paste this inside 👇

✅ index.css
/* RESET */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

/* ROOT COLORS */
:root {
    --green: #2e7d32;
    --dark-green: #1b5e20;
    --light-bg: #f4f9f4;
    --white: #ffffff;
}

/* HEADER */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 18px 60px;
    background: var(--white);
    position: sticky;
    top: 0;
    z-index: 1000;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.logo {
    font-size: 24px;
    font-weight: bold;
    color: var(--dark-green);
    text-decoration: none;
}

.navbar {
    display: flex;
    align-items: center;
    gap: 20px;
}

.navbar a {
    text-decoration: none;
    color: #333;
    font-weight: 600;
}

.navbar a:hover {
    color: var(--green);
}

/* SEARCH */
.search {
    display: flex;
    gap: 5px;
}

.srch {
    padding: 6px 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

.btn {
    padding: 6px 12px;
    background: var(--green);
    border: none;
    color: white;
    border-radius: 4px;
    cursor: pointer;
}

.btn:hover {
    background: var(--dark-green);
}

/* HERO */
.hero {
    height: 90vh;
    background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)),
                url("https://images.unsplash.com/photo-1501004318641-b39e6451bec6") center/cover no-repeat;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: white;
}

.hero-content h1 {
    font-size: 48px;
    margin-bottom: 15px;
}

.hero-content p {
    font-size: 18px;
    margin-bottom: 25px;
}

.hero-btn {
    display: inline-block;
    padding: 12px 25px;
    background: var(--green);
    color: white;
    text-decoration: none;
    border-radius: 30px;
    margin: 5px;
}

.hero-btn:hover {
    background: var(--dark-green);
}

/* COMMON SECTION */
section {
    padding: 80px 60px;
}

.heading {
    text-align: center;
    font-size: 36px;
    color: var(--dark-green);
    margin-bottom: 50px;
}

/* MISSION */
.mission-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
}

.mission-box {
    background: var(--light-bg);
    padding: 30px;
    border-radius: 10px;
    text-align: center;
}

/* PROJECTS */
.projects-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
}

.project-box {
    background: white;
    padding: 25px;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.1);
}

/* RESOURCES */
.resources-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
}

.resource-box {
    background: var(--light-bg);
    padding: 25px;
    border-radius: 10px;
}

.resource-btn {
    display: inline-block;
    margin-top: 15px;
    padding: 8px 18px;
    background: var(--green);
    color: white;
    text-decoration: none;
    border-radius: 20px;
}

.resource-btn:hover {
    background: var(--dark-green);
}

/* CONTACT */
.contact-container {
    max-width: 600px;
    margin: auto;
}

.input-box {
    width: 100%;
    padding: 12px;
    margin-bottom: 15px;
    border-radius: 6px;
    border: 1px solid #ccc;
}

.contact-btn {
    width: 100%;
    padding: 12px;
    background: var(--green);
    color: white;
    border: none;
    border-radius: 6px;
    cursor: pointer;
}

.contact-btn:hover {
    background: var(--dark-green);
}

/* FOOTER */
.footer {
    background: #0f3d0f;
    color: white;
    padding: 50px 60px 20px;
}

.footer-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
}

.footer-box h3 {
    margin-bottom: 15px;
}

.social-icons {
    margin-top: 15px;
}

.social-icons a {
    color: white;
    margin-right: 12px;
    font-size: 18px;
}

.social-icons a:hover {
    color: #a5d6a7;
}

.footer-bottom {
    text-align: center;
    margin-top: 30px;
    border-top: 1px solid rgba(255,255,255,0.2);
    padding-top: 15px;
    font-size: 14px;
}

/* RESPONSIVE */
@media (max-width: 768px) {
    header {
        flex-direction: column;
        gap: 10px;
    }

    .hero-content h1 {
        font-size: 36px;
    }
}
✅ What you now have
✔ Clean navbar with search
✔ Modern hero section
✔ Responsive grid layout
✔ Styled footer with social media icons
✔ Mobile-friendly design

If you want next:

🌐 Make navbar responsive (hamburger menu)

🎨 Add animations

🚀 Deploy to GitHub Pages

🧪 Form validation with JavaScript

Just tell me 👍

You said:
:root {
    --green: #2b912b;
}

/* RESET */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    text-decoration: none;
    transition: 0.2s linear;
}

html {
    font-size: 62.5%;
}

/* HEADER */
header {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    background: #2a853c;
    padding: 2rem 9%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    z-index: 1000;
}

/* LOGO */
.logo {
    font-size: 2.2rem;
    font-weight: bold;
    color: #000;
}

/* NAVBAR */
.navbar {
    display: flex;
    align-items: center;
    gap: 1.5rem;
}

.navbar a {
    font-size: 1.4rem;
    color: #000;
}

.navbar a:hover {
    color: #fff;
}

/* SEARCH */
.search {
    display: flex;
}

.srch {
    width: 180px;
    height: 36px;
    border: 1px solid #000;
    padding: 0 1rem;
}

.btn {
    height: 36px;
    padding: 0 1.5rem;
    background: #000;
    color: #fff;
    cursor: pointer;
    border: none;
}

/* HERO SECTION */
.hero {
    height: 100vh;
    background:
        linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)),
        url("istockphoto.jpg")
        no-repeat center center / cover;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 0 9%;
}

/* HERO TEXT */
.hero-content h1 {
    font-size: 4.5rem;
    color: #fff;
    margin-bottom: 1rem;
}

.hero-content p {
    font-size: 1.6rem;
    color: #f1f1f1;
    margin-bottom: 2rem;
}

.hero-btn {
    padding: 1.2rem 3rem;
    margin: 30px 20px;
    border-radius: 30px;
    font-weight: bold;
    border: 2px solid #1f6d1f;
    background: transparent;
    color: #fff;
    cursor: pointer;
    position: relative;
    overflow: hidden;
    z-index: 1;
    display: inline-block;
    text-align: center;
}

/* hover background animation */
.hero-btn span {
    position: absolute;
    left: 0;
    bottom: 0;
    width: 0%;
    height: 100%;
    background: #1f6d1f;
    border-radius: 30px;
    z-index: -1;
    transition: 0.5s;
}

.hero-btn:hover span {
    width: 100%;
}

.hero-btn:hover {
    border-color: #1f6d1f;
}

/* MISSION SECTION */
.mission {
    padding: 8rem 9%;
    background: #fff;
    text-align: center;
}

.heading {
    font-size: 4rem;
    color: var(--green);
    margin-bottom: 4rem;
}

.mission-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 3rem;
}

.mission-box {
    background: #fff;
    padding: 3rem 2rem;
    border-radius: 1.2rem;
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.973);
    transition: transform 0.3s ease;
}

.mission-box:hover {
    transform: translateY(-10px);
}

.mission-box h3 {
    font-size: 2rem;
    margin-bottom: 1rem;
}

.mission-box p {
    font-size: 1.4rem;
    color: #333;
}
/* PROJECTS SECTION */
.projects {
    padding: 8rem 9%;
    background: #f9fafa;
    text-align: center;
}

.projects-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 3rem;
}

.project-box {
    background: #f4f9f4;
    padding: 3rem 2rem;
    border-radius: 1.2rem;
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.925);
    transition: transform 0.3s ease;
}

.project-box:hover {
    transform: translateY(-10px);
}

.project-box h3 {
    font-size: 2rem;
    margin-bottom: 1rem;
    color: var(--green);
}

.project-box p {
    font-size: 1.4rem;
    color: #333;
}
/* RESOURCES SECTION */
.resources {
    padding: 8rem 9%;
    background: #f4f9f4;
    text-align: center;
}

.resources-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 3rem;
}

.resource-box {
    background: #ffffff;
    padding: 3rem 2rem;
    border-radius: 1.2rem;
    box-shadow: 0 0 15px rgba(0, 0, 0, 0.897);
    transition: transform 0.3s ease;
}

.resource-box:hover {
    transform: translateY(-10px);
}

.resource-box h3 {
    font-size: 2rem;
    margin-bottom: 1rem;
    color: var(--green);
}

.resource-box p {
    font-size: 1.4rem;
    color: #333;
    margin-bottom: 2rem;
}

.resource-btn{
     padding: 1.2rem 3rem;
    margin: 30px 20px;
    border-radius: 30px;
    font-weight: bold;
    border: 2px solid #1f201e;
    background: transparent;
    color: #141313;
    cursor: pointer;
    position: relative;
    overflow: hidden;
    z-index: 1;
    display: inline-block;
    text-align: center;
}
.resourcebtn span {
    position: absolute;
    left: 0;
    bottom: 0;
    width: 0%;
    height: 100%;
    background: #1f6d1f;
    border-radius: 30px;
    z-index: -1;
    transition: 0.5s;
}
.resource-btn:hover span {
    width: 100%;
}

.resource-btn:hover {
    background: #4d964d;
}

/* Contact SECTION */
.contact {
    padding: 80px 20px;
    background: #f4f9f4;
    text-align: left;   
}

.contact .heading {
    font-size: 36px;
    color: #1b5e20;
    margin-bottom: 40px;
    margin-left: 40px; 
}

.contact-container {
    max-width: 600px;
    margin-left: 40px; 
    background: #fff;
    padding: 40px;
    border-radius: 12px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.1);
}

.input-box {
    width: 100%;
    padding: 12px;
    margin-bottom: 20px;
    border: 1px solid #080808;
    border-radius: 6px;
}

.contact-btn {
    background: #ade7b6;
    color: #0a0a0a;
    border: none;
    padding: 12px 30px;
    border-radius: 25px;
    cursor: pointer;
}

.contact-btn:hover{
    background: #4d964d;
    color: #fff;
}
/*FOOTER*/
.footer {
    background: #0c0e0c;
    color: #ffffff;
    padding-top: 40px;
}

.footer-container {
    display: flex;
    justify-content: space-between;
    gap: 40px;
    padding: 0 40px;
    flex-wrap: wrap;
}

.footer-box {
    flex: 1;
    min-width: 220px;
}

.footer-box h3 {
    margin-bottom: 15px;
    font-size: 20px;
    color: #ade7b6;
}

.footer-box p {
    font-size: 14px;
    line-height: 1.6;
}

.footer-bottom {
    text-align: center;
    padding: 15px;
    margin-top: 30px;
    background: #144d1a;
    font-size: 14px;
}


.social-icons { 
    margin-top: 15px;
}

.social-icons a {
    display: inline-block;
    margin-right: 10px;
    color: #0c0c0c;
    background: #e2e6e2;
    width: 35px;
    height: 35px;
    line-height: 35px;
    text-align: center;
    border-radius: 50%;
    transition: 0.3s ease;
    font-size: 16px;
}

.social-icons a:hover {
    background: #2e7238;
    color: #fcfffc;
}


/* TABLET */
@media (max-width: 990px) {
    header {
        padding: 1.5rem 6%;
    }

    .srch {
        width: 150px;
    }
}

/* MOBILE */
@media (max-width: 768px) {
    header {
        flex-direction: column;
        align-items: flex-start;
        gap: 1.5rem;
    }

    .navbar {
        flex-direction: column;
        width: 100%;
    }

    .search,
    .srch {
        width: 100%;
    }
      .footer-container {
        flex-direction: column;
        text-align: left;
}}

/* SMALL MOBILE */
@media (max-width: 480px) {
    .logo {
        font-size: 1.8rem;
    }

    .navbar a {
        font-size: 1.3rem;
    }

    .btn {
        font-size: 1.2rem;
    }
}
ChatGPT said:
Good work 👍 Your CSS is mostly correct, but there are a few real issues + improvements that will affect layout and effects. I’ll explain what’s wrong, why, and then give you fixed CSS snippets (not rewriting everything).

🔴 1. Header is position: fixed → content hides under it
Because your header is fixed, the hero section goes under the navbar.

✅ Fix (important)
Add top padding to the body or hero:

body {
    padding-top: 90px;
}
OR (better for hero only):

.hero {
    min-height: calc(100vh - 90px);
}
🔴 2. Logo color invisible on dark header
Your header background is dark green, but logo text is black.

❌ Current
.logo {
    color: #000;
}
✅ Fix
.logo {
    color: #fff;
}
🔴 3. Resource button hover animation NOT working (class typo)
You wrote .resourcebtn span but your button class is .resource-btn

❌ Wrong
.resourcebtn span {
✅ Correct
.resource-btn span {
    position: absolute;
    left: 0;
    bottom: 0;
    width: 0%;
    height: 100%;
    background: #1f6d1f;
    border-radius: 30px;
    z-index: -1;
    transition: 0.5s;
}
✔ This fixes the animation instantly

🔴 4. Box-shadow values are too strong (UI looks harsh)
Example:

box-shadow: 0 0 15px rgba(0, 0, 0, 0.973);
That’s almost pure black shadow.

✅ Better (professional look)
box-shadow: 0 8px 20px rgba(0,0,0,0.15);
Apply to:

.mission-box

.project-box

.resource-box

🔴 5. Social icons color mismatch
Icons are dark on light background → OK
But hover background is dark green → good
However footer background is very dark → icons should be brighter by default

✅ Improvement
.social-icons a {
    color: #144d1a;
}
🟢 6. Mobile navbar UX improvement (optional but recommended)
On mobile, links stack but stay left-aligned.

✅ Optional enhancement
@media (max-width: 768px) {
    .navbar {
        align-items: flex-start;
    }

    .navbar a {
        padding: 5px 0;
    }
}
✅ Summary of FIXES you MUST apply
✔ Add top padding for fixed header
✔ Change logo color to white
✔ Fix .resourcebtn → .resource-btn
✔ Reduce shadow darkness
✔ Improve mobile spacing

Your project is very good for a beginner–intermediate level 🌱
If you want next:

☰ Hamburger menu

🎬 Scroll animations

🌍 GitHub Pages deployment

⚡ JS form validation

Just tell me what you want next 😊

You said:
create a read me of this coding
ChatGPT said:
Here is a clean, professional README.md you can directly use for your project 👇
(Perfect for GitHub submission / portfolio)

🌿 Green Earth – Environmental Awareness Website
Green Earth is a responsive environmental awareness website built using HTML5 and CSS3.
It promotes sustainability, climate action, and eco-friendly initiatives through a modern and user-friendly design.

📌 Features
🌍 Clean and modern UI design

📱 Fully responsive (desktop, tablet, mobile)

🧭 Fixed navigation bar with search option

🌱 Hero section with call-to-action buttons

🎯 Mission, Projects, and Resources sections

✉ Contact form layout

🔗 Footer with social media icons

🎨 CSS hover animations and transitions

🛠 Technologies Used
HTML5 – Page structure

CSS3 – Styling and responsiveness

Font Awesome – Social media icons

📂 Project Structure
Green-Earth/
│
├── index.html        # Main HTML file
├── index.css         # Styling file
├── istockphoto.jpg   # Hero background image
└── README.md         # Project documentation
📸 Sections Overview
🔹 Header
Logo and navigation menu

Search bar

Fixed position for easy navigation

🔹 Hero Section
Full-screen background image

Main headline and description

Call-to-action buttons

🔹 Mission Section
Protect Nature

Reduce Pollution

Promote Sustainable Living

🔹 Projects Section
Youth Climate Meetup

Refuse the Plastic Campaign

Clean Water Initiative

Solar Energy Program

🔹 Resources Section
Climate Change Guide

Recycling Handbook

Sustainability Tips

Environmental Videos

🔹 Contact Section
Name, email, and message input fields

Styled submit button

🔹 Footer
About Green 

Contact details

Social media links


Font Awesome – Social media icons

▶️ How to Run the Project

1. Download or clone the repository  
   ```bash
   git clone https://github.com/your-username/green-earth.git
   Open the project folder

Open index.html in any modern web browser

🚀 Future Enhancements

Add JavaScript form validation

Implement hamburger menu for mobile

Add scroll-based animations

Deploy live version using GitHub Pages

👩‍💻 Author

Husna Shiekh
Frontend Developer (HTML & CSS)

📄 License

This project is open-source and available for educational and learning purposes.

---

### ✅ This README is:
✔ Professional  
✔ GitHub-ready  
✔ Suitable for portfolio & college  
✔ Clean and readable  

If you want, I can also:
- Add **GitHub Pages live demo section**
- Shorten it for **college submission**
- Add **screenshots section**
- Improve it for **job portfolio**

Just tell me 🌱







