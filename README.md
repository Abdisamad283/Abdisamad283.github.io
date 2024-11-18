# Abdisamad283.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abdisamad's portfolio!</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="mediaqueries.css">
</head>
<body>

    <nav id="desktop-nav">
        <div class="logo">My Portfolio</div>
        <div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>
    <nav id="hamburger-nav">
        <div class="logo">Abdisamad Daud</div>
        <div class="hamburger-menu">
            <div class="hamburger-icon" onclick="toggleMenu()">
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="menu-links">
                <li><a href="#about" onclick="toggleMenu()">About</a></li>
                <li><a href="#experience" onclick="toggleMenu()">Experience</a></li>
                <li><a href="#projects" onclick="toggleMenu()">Projects</a></li>
                <li><a href="#contact" onclick="toggleMenu()">Contact</a></li>
            </div>
        </div>
    </nav>
    <section id="profile">
        <div class="section__pic-container">
            <img src="./assets/blankpfp.jpg" alt="Abdisamad's profile picture">
        </div>
        <div class="section__text">
            <p class="section__text__p1">"Hello, I'm</p>
            <h1 class="title">Abdisamad</h1>
            <p class="section__text__p2">Full time student</p>
            <div class="btn-container">
                <button class="btn btn-colour-2" onclick="window.open('./assets/Abdisamad_CV_2.docx')">Download CV</button>
                <button class="btn btn-colour-1" onclick="location.href='./#contact'">Contact info</button>
            </div>
            <div id="socials-container">
                <img src="./assets/linkedin.png" alt="My Linkedin profile"
                class="icon" onclick="location.href='https://www.linkedin.com/in/abdisamad-daud-166281291'">
                <img src="./assets/github.png" alt="My GitHub profile"
                class="icon" onclick="location.href='https://github.com/Abdisamad283'">
            </div>
        </div>
    </section>
    <section id="about">
        <p class="section__text__p1">Get To Know More</p>
        <h1 class="title">About me</h1>
        <div class="section-container">
            <div class="section__pic-container">
                <img src="./assets/schoolLogo.jpg" alt="Profile picture"
                class="about-pic">
            </div>
            <div class="about-details-container">
                <div class="about-containers">
                    <div class="details-container">
                        
                        <h3>Experience</h3>
                        <p>Things I've done line 73 <br>Full Time Student</p>
                    </div>
                    <div class="details-container">
                    
                        <h3>Education</h3>
                        <p>GCSE results: <br>Maths-8 <br>English Language-7 <br>English Literature-7 <br>Biology-7 <br>Chemistry-7 <br>Physics-8 <br>Computer Science-6 <br>Geography-7 <br>French-4 <br>Drama-L2P</p>
                    </div>
                </div>
                <div class="text-container">
                    <p>Currently taking A-levels</p>
                </div>
            </div>
        </div>
        <img src="./assets/arrow.png" alt="Arrow icon"  class="icon arrow"
        onclick="location.href='./#experience'"
        />
    </section>
    <section id="experience">
        <p class="section__text__p1">Explore my</p>
        <h1 class="title">Experience</h1>
        <div class="experience-details-container">
            <div class="about-containers">
                <div class="details-container">
                    <h2 class="experience-sub-title">Line 95</h2>
                    <div class="article-container">
                        <article>
                            <img src="./assets/checkmark.png" alt="Experience icon"class="icon"/>
                            <div>
                                <h3>line 100</h3>
                                <p>Experienced</p>
                            </div>

                        </article>
                        <article>
                            <img src="./assets/checkmark.png" alt="Experience icon"class="icon"/>
                            <div>
                                <h3>Java</h3>
                                <p>Basic</p>
                            </div>

                    </div>
                </div>
                <div class="details-container">
                    <h2 class="experience-sub-title">Line 95</h2>
                    <div class="article-container">
                        <article>
                            <img src="./assets/checkmark.png" alt="Experience icon"class="icon"/>
                            <div>
                                <h3>other details container 153</h3>
                                <p>intermediate</p>
                            </div>

                        </article>
                        <article>
                            <img src="./assets/checkmark.png" alt="Experience icon"class="icon"/>
                            <div>
                                <h3>Java</h3>
                                <p>Basic</p>
                            </div>

                        </article>
                    </div>
                </div>
            </div>
        </div>
        <img src="./assets/arrow.png" alt="Arrow icon"  class="icon arrow"
        onclick="location.href='./#projects'"
        />
    </section>
    <section id="contact">
        <p class="section__text__p1">Get in touch</p>
        <h1 class="title">Contact Me</h1>
        <div class="contact-info-upper-container">
            <div class="contact-info-container">
                <img src="./assets/email.png" alt="Email icon" class="icon contact-icon email-icon">
                <p><a href="mailto:abdidaud2006@gmail.com">abdidaud2006</a></p>
            </div>
            <div class="contact-info-container">
                <img src="./assets/linkedin.png" alt="Linkedin icon" class="icon contact-icon">
                <p><a href="https://www.linkedin.com/in/abdisamad-daud-166281291">Linkedin</a></p>
            </div>
        </div>
    </section>
    <footer>
        <nav>
            <div class="nav-links-container">
                <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul></div>
        </nav>
        <p>Copyright &#169; 2024 Abdisamad Daud. All Rights Reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
