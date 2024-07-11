# landingpage

Project Description:

This project is a responsive and visually appealing landing page designed using HTML and CSS. The landing page is created to provide an engaging and informative introduction to a product, service, or business. It showcases essential features, benefits, and a call-to-action to capture user interest and drive conversions.

Key Features:

Responsive Design: Ensures the landing page is fully responsive and looks great on devices of all sizes, including desktops, tablets, and smartphones.

Modern Layout: Utilizes modern web design principles to create a clean, professional, and aesthetically pleasing layout.

Custom CSS Styling: Implements custom CSS to enhance the visual appeal and user experience of the page.

Footer Section: Provides a footer with additional information, social media links, and contact details.

Technologies Used:

HTML5: Structured the content of the landing page using semantic HTML5 elements.

CSS3: Styled the landing page with custom CSS3 for layout, design, and responsiveness.

Project Structure:

landingpage.html: Contains the HTML structure and content of the landing page.

landingpage.css: Contains the custom CSS styles for the landing page.

## page.html:

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Niteesh Technologies - Where Ideas Become Realtiy</title>
    <link rel="stylesheet" href="page.css" />
  </head>
  <body>
    <div class="one">
      <center>
        <br>
        <h1>NITEESH TECHNOLOGIES</h1>
        <header>
          <nav>
            <ul>
              <li><a href="#Home">Home | </a></li>
              <li><a href="#Courses">Features | </a></li>
              <li><a href="#About Us">About Us | </a></li>
              <li><a href="#Contact">Contact | </a></li>
            </ul>
          </nav>
        </header>
      </center>

      <section id="hero">
        <div class="hero-content">
          <h2>Welcome to Our Business</h2>
          <p>Where Ideas Become Reality</p>
          <a href="#contact" class="hero-button">Get in Touch</a>
        </div>
      </section>

      <section class="mum">
        <div class="features">
          <h2 style="color: rgb(52, 12, 196)">ClassRoom Training</h2>
          <p>
            We focus on a requirement based approach that leads to majesty. Our
            teaching philosopy is based on three key element - concept,
            application and strategy
          </p>
        </div>
        <div class="features">
          <h2 style="color: rgb(52, 12, 196)">College Training</h2>
          <p>
            With technology covering most of the industries today under its huge
            umbrella, it has become mandatory for future brains to be skilled in
            the trending technology.
          </p>
        </div>
      </section>
      <section class="dad">
        <div class="feature">
          <h2 style="color: rgb(52, 12, 196)">Certification Domains</h2>
          <p>
            Certifications give you a professional edge by providing globally
            recognised industry endorsed evidence of skills mastery.
          </p>
        </div>
        <div class="feature">
          <h2 style="color: rgb(52, 12, 196)">Placements</h2>
          <p>
            Selection refers to picking up individuals with the right
            qualifications, the right experience and most importantly the right
            attitude for a particular position.
          </p>
        </div>
      </section>

      <section id="me">
        <h2>About Us</h2>
        <p>
          We are a dedicated team with over 10 years of experience in business
          development and management. Our mission is to provide high-quality
          services tailored to each client's unique needs.
        </p>
      </section>

      <section id="mi">
        <h2>Contact</h2>
        <p>Phone: 6384217575</p>
        <p>Email: niteeshtechnologies@gmail.com</p>
      </section>

      <footer>
        <p>© 2024 Small Business. All rights reserved.</p>
      </footer>
    </div>
  </body>
</html>
```

## page.css:

```

.one{
    background-color:rgb(68, 126, 144); /* Vibrant purple header */
    height:200px ;
    background-size: cover;
   

}
h1,h4{
    color: rgb(64, 224, 28);
}
    
    header {
        padding-top: none;
        margin-top: 20px;
        background-color:rgb(68, 126, 144);
        background-size: cover;
        /* Vibrant purple header */
    }
    
    header nav ul {
        padding: 0;
    }
    
    header nav ul li {
        display: inline;
    }
    
    header nav ul li a {
        font-weight: bold;
        color: white;
    }
    .two{
        border-color: black;
        padding-top:20px;
        margin: 0 15px;
        text-align: center;
        p{
            margin-bottom: 0px;
        }
    }

    #hero {
        background-image: url('https://tse1.mm.bing.net/th?id=OIP.htqJjM8lNtFJgDZOXdauYwHaEx&pid=Api&P=0&h=180://peepstrategy.com/wp-content/uploads/2021/08/group-multiethnic-creative-business-people-working-project-having-brainstorming-meeting-team-work-brainstorming-https://i.pinimg.com/originals/f3/ca/be/f3cabed2f26b9cca3996613f593fa9a1.jpg-1.jpg'); 
        background-size: cover;
        background-position: center;
        height: 400px;
        display: flex;
        align-items: center;
        justify-content: center;
        text-align: center;
        color: white;
    }
    
    .hero-content {
        background-color: rgba(0, 0, 0, 0.5);
        padding: 20px;
    }
    
    .hero-button {
        display: inline-block;
        margin-top: 20px;
        padding: 10px 20px;
        background-color: #cb3310;
        color: white;
        text-decoration: none;
        border-radius: 5px;
        transition: background-color 0.3s;
    }
    
    .hero-button:hover {
        background-color: #d64b2a;
    }
    
    .two{
        display: flex;
        align-items: center;
        justify-content: center;
        background-color: rgba(0, 0, 0, 0.5);
        padding: 20px;
    }

    .mum{
        display: flex;
        justify-content: center;
        padding: 20px;
    }

    .features{
        padding: 20px;
        width: calc((100% / 3) - 40px); /* Adjust for 3 products per row */
        box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
        text-align: center;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .dad{
        display: flex;
        justify-content: center;
        padding: 20px;
    }
    .feature{
        margin: 10px;
    padding: 20px;
    width: calc((100% / 3) - 40px); /* Adjust for 3 products per row */
    box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
    text-align: center;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    #me{
        background-color: #f0f0f0;
        padding: 20px;
        text-align: center;

    }
    #me h2{
        color: green;
        margin-bottom: 15px;
    }

    #mi h2{
        color: green;
        margin-bottom: 15px;
        
    }
    #mi p{
        margin-bottom: 15px;
    }
    #mi{
        background-color: #fff;
        padding: 20px;
        text-align: center;
    }
    footer {
        background-color: rgb(68, 126, 144);
        color: white;
        text-align: center;
        padding: 10px 0;
    }


```

## OUTPUT:

![Screenshot 2024-07-11 210916](https://github.com/Niteeshmohan/landingpage/assets/119575445/0065ff1e-08e9-477e-a56a-cc4474912df6)


![Screenshot 2024-07-11 210934](https://github.com/Niteeshmohan/landingpage/assets/119575445/3f7c8b5e-7d4d-4c75-bb6f-d7fc8784de47)
