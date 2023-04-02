# Meika Ponnan - Portfolio

## Links
Below are the links to my: 

Website:

https://meikaponnancoderportfolio.netlify.app/

GiHub Repo:

https://github.com/MeikaPonnan/MeikaPonnan_T1A2

Presentation:


## Overview
The purpose of my portfolio website is to showcase my ability with html and css, as well as my personaliy and creativity. I wanted to use a range of HTML and CSS components that i had learned to make my website interactive and easy to use.

Here are some of the funtionalities/features found on my website:

### 1. Header
The header helps you navigate the page and has the details for the website. Below is the a preview of the header.

```html
 <header>
        <nav>
        <div class="logo-name">
            <a href="../index.html">
                <img src="../images/mplogo.png" alt="Website Logo" id="logo">
            </a> 
            <a href="../pages/about.html" class="name">MEIKA PONNAN</a>
        </div>
        </nav>
        <nav class="nav-items">
            <a href="./about.html">About</a>
            <a href="./services.html">Services</a>
            <a href="./blogs.html">Blogs</a>
            <a href="./contact.html">Contact Me</a>
        </nav>
    </header>
```

### 2. Footer
The Footer contains links to my social media where you get to know me and see my work.
```
<footer>
        <h4>Connect With Me</h4>
        <div class="newsletter">
            <form>
                <input type="email" name="email" id="email" placeholder="Enter your Email">
                <input type="submit" name="Submit" value="Submit">
            </form>
        </div>
        <div class="social-media">
            <a href="https://github.com/MeikaPonnan" target="_blank"><i class="fa-brands fa-github"></i></a>
            <a href="https://www.linkedin.com/in/meikaponnan/" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
            <a href="https://instagram.com" target="_blank"><i class="fa-brands fa-instagram"></i></a>
        </div>
    </footer>
```
### 3. About Page:

The About page has a brief summary on me and also includes a button to a link of a pdf copy of my resume.
```
 <main>
            <div class="heading">
                <h1>About Me</h1>
            </div>
            <div class="description">
                <p>Hello world! My name is <b>Meika Ponnan</b>. I am a web developper living in Sydney. I love problem solving and designing websites. Some of my favourite programming languages are Python, Javascript and Kotlin.</p>
                <p>Lorem ipsum </p>
                <p>If you want a more in-depth detail of my work, please view my resume below.</p>
                <a href="../documents/resumedoc.pdf" target="_blank"><button id="download">Click here to download my resume</button></a>
            </div>
        </main>
```
### 4. Services page
This page contains some of the services i provide. It is divided in sections with headings and images.

```
 <main>
        <article>
            <section>
                <img class="services1-img" src="../images/web-development.jpg" alt="Image of a Laptop"/>
            </section>
            <section>
                <h3>Web Development</h3>
            </section>
        </article>

        <article>
            <section>
                <img class="services2-img" src="../images/webdesign.jpg" alt="Image of design progress"/>
            </section>
            <section>
                <h3>Web Designing</h3>
            </section>
        </article> 
        
        <article>
            <section>
                <img class="services3-img" src="../images/mobileappdesign.jpg" alt="Image of a phone screen"/>
            </section>
            <section>
                <h3>Mobile App Development</h3>
            </section>
        </article>
    </main>
```


### 5. Blogs Page
The blog page contains a list of blogs i created. They all link to a blog content page where it will direct you to the specific part of the page. It contains articles, sections, headings, paragraphs, divs, images and links.
```
 <main>
        <div class="heading">
            <h2>Blogs</h2>
        </div>
        <article>

            <section>
                <img class="blog1-img" src="../images/python.jpg" alt="Python language"/>
                <a href="./blogcontent.html#blogcontent1" target="_blank"><h3>Learning Python</h3></a>
                <p>Date published: 15 May 2022</p>
            </section>

        </article>

        <article>

            <section>
                <img class="blog2-img" src="../images/htmlimg.jpg" alt="Learning html"/>
                <a href="./blogcontent.html#blogcontent2" target="_blank"><h3>Getting started with HTML</h3></a>
                <p>Date published: 19 June 2022</p>
            </section>

        </article> 
        
        <article>

            <section>
                    <img class="blog3-img" src="../images/javascript.jpg" alt="Javascript"/>
                <a href="./blogcontent.html#blogcontent3" target="_blank"><h3>Cracking Javascript</h3></a>
                <p>Date published: 11 March 2021</p>
            </section>

        </article>

        <article>

            <section>
                <img class="blog4-img" src="../images/cssimg.jpg" alt="CSS"/>
                <a href="./blogcontent.html#blogcontent4" target="_blank"><h3>Style with CSS</h3></a>
                <p>Date published: 12 May 2020</p>
            </section>

        </article> 

        <article>

            <section>
                <img class="blog5-img" src="../images/projectideas.jpg" alt="Learning html"/>
                <a href="./blogcontent.html#blogcontent5" target="_blank"><h3>Project Ideas</h3></a>
                <p>Date published: 22 May 2022</p>
            </section>

        </article> 

    </main>
```
### Contact Page
The contact page has all my contact information. It contains a form with different inputs that can be filled out and a submit button that changes color and size when the cursor is on top of it.

```
<main>
        <div class="contact-info">
            <h3>My contact Info:</h3>
            <p> Reach me on: 0400004440</p>
            <p>Address: 45 Contact Street, Sydney, NSW, Australia</p>
        </div>
        
       <h2>Get in Touch</h2>

       <form>
            <div class="form-elements">
                <label>Name: </label>
                <input class="form-input">
            </div>

            <div class="form-elements">
                <label>Email: </label>
                <input class="form-input">
            </div>

            <div class="form-elements">
                <label>Subject: </label>
                <input class="form-input">
            </div>

            <div class="form-elements">
                <label>Message: </label>
                <textarea rows="2" class="form-input form-message"></textarea>
            </div>

            <div class="button-form">
                <button id="submit">Send</button>
            </div>
        

        </form>
    </main>
```

Nav:
The 'nav' is a navigation bar that helps navigate the different pages of the website. It includes the About page, Services page, Blogs Page and Contact page. It also has the home page via the logo icon.

Links- a:
There are many links that 

## Sitemap
This is the sitemap i created:

Overview:
<img src="./images/sitemapoverview.png" alt="sitemap overview">


Home Page:
<img src="./images/sitemaphomepage.png" alt="sitemap homepage">
<img src="./images/figmahomepage.png">

About me:
<img src="./images/sitemapaboutme.png" alt="sitemap about me">
<img src="./images/figmaaboutme.png">

Services:
<img src="./images/sitemapservices.png" alt="sitemap services">
<img src="./images/figmaservices.png">

Blogs:
<img src="./images/sitemapblogs.png" alt="sitemap blogs">
<img src="./images/figmablogs.png">

Blog content:
<img src="./images/sitemapblogtocontent.png" alt="sitemap blog to content">

Contact:
<img src="./images/sitemapcontact.png" alt="contact sitemap">
<img src="./images/figmacontact.png">

## Screenshots
Here are some screenshots of my website:

Home Page Desktop View:
<img src="./images/homepagelaptop.png">
Home Page mobile View:
<img src="./images/homepagemobile.png">
About Me Desktop View:
<img src="./images/aboutmelaptop.png">
About Me Mobile View:
<img src="./images/aboutmemobbile.png">

Services Desktop View:
<img src="./images/serviceslaptop.png">
Services Desktop Hover:
<img src="./images/serviceslaptophover.png">
Services Mobile View:
<img src="./images/servicesmobile.png">

Blog Desktop View:
<img src="./images/blogpagelaptop.png">
Blog Desktop Hover:
<img src="./images/blogpagelaptophover.png">
Blog Mobile View:
<img src="./images/blogpagemobile.png">


Blog content:
<img src="./images/blogcontentlaptop2.png">
<img src="./images/blogcontentlaptop3.png">
Mobile View blog content:
<img src="./images/blogcontentmobile2.png">


Contact Desktop View:
<img src="./images/contactpagelaptop.png">
Contact Desktop form:
<img src="./images/contactinfoform.png">
Contact Mobile View:
<img src="./images/contactpagemobile.png">

## Target Audience
This website is aimed at potential employers who's looking for a passionate web developer that displays an array of skills.

## Tech stacks
This is what i used to make my website:
1. HTML
2. CSS
3. GitHub
4. Netlify
5. draw.io
6. Figma

