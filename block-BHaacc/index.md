- Create a layout according to the design shown below.

![Backgrounds and gradient Assignment level 1](https://raw.githubusercontent.com/suraj122/AC-STYLE-images/master/adding-media/ex-1.png)

- Video link: https://www.youtube.com/watch?v=AqcjdkPMPJA#action=share

- Using CSS resets is necessary.

- Use semantic tags and keep the nesting and indentation proper.
<!--Content-->
<!DOCTYPE html>
<html lang="en">
 <head>
    <meta charset="UTF-8">
    <title>Document</title>
    <!--CSS-->
    <link rel="stylesheet" href="assets/stylesheet/style.css">
    <!--Font Awesome-->
    <script src="https://kit.fontawesome.com/f98f63fd9d.js" crossorigin="anonymous"></script>
    <!--Google font-->
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Slab:wght@100;200;300;400;500;   600;700;800;900&display=swap" rel="stylesheet">

 </head>
 <body>
    <header class="header">
        <div class="container flex">
            <a class="logo" href="#">Hydro</a>
            <nav class="nav decoration">
                <ul class="flex">
                    <li>
                        <a href="#">Home</a>
                    </li>
                    <li>
                        <a href="#">About</a>
                    </li>
                    <li>
                        <a href="#">Blog</a>
                    </li>
                    <li>
                        <a href="#">Our Work</a>
                    </li>
                    <li>
                        <a href="#">Contacts</a>
                    </li>
                </ul>
            </nav>
            <nav class="social-nav">
                <ul class="flex">
                    <li>
                        <i class="fab fa-facebook-square"></i>
                    </li>
                    <li>
                        <i class="fab fa-twitter"></i>
                    </li>
                    <li>
                        <i class="fab fa-instagram"></i>
                    </li>
                    <button class="btn btn-header">Sign in / join</button>
                </ul>
            </nav>
        </div>
    </header>
    <main>
      <section class="hero">
      
        <div class="container flex align-item">
            <div class="home">
               <h1>We make beautiful <br>
                   website for all people</h1>
                <div class="hero-information  flex">
                   <button class="btn btn-hero">
                        Start a project
                   </button>
                   <p class=" para hero-para">CALL US (+66) 010-020-0340 <br>
                      For any inquiry</p>
                </div>
            </div>
            <div>
                <iframe width="560" height="315" src="https://www.youtube.com/embed/AqcjdkPMPJA" frameborder="0" allow="accelerometer; autoplay; clipboard-write;   encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
        </div>
      </section>
      <section class="utility-section ">
        <div class="container flex alignment align-item">
            <div class="col-1">
                <h2>
                    Let us introduce
                   
                </h2>
               
                <p class="paragraph">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ipsum officiis unde eligendi, totam repellendus facilis repudiandae maxime</p>

                <p class="paragraph"> necessitatibus molestiae consequuntur cum tenetur quod earum distinctio similique </p>
            </div>
            <div class="utility">
                <p class="design">Web Design </p>
                <p class="design">photography</p>
                <p class="design">content marketing</p>
                <p class="design">cms admin</p>
            </div>
            <div>
                <img class="img" src="assets/media/about-image.jpg" alt="loading error">
            </div>
        </div>
      </section>
      <section class="blog-section">
        <div class="container ">
            <h3>Our Blog</h3>
              <div class="flex wrap padding">
                <div class="blog-container col-2 flex">
                    <div>
                      <img class="blog-img" src="assets/media/blog-image1.jpg" alt="loading error">
                    </div> 
                    <div class="blog-info">
                        <i class="far fa-clock"></i>
                        <span>December 22,2017</span>
                        <h4>how to find out beautiful workspace. </h4>
                        <p class="paragraph">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Impedit.</p>
                        <button class="btn blog-btn">Read article</button>
                    </div>
                </div>
                <div class="blog-container col-2 flex">
                    <div>   
                       <img class="blog-img" src="assets/media/blog-image2.jpg" alt="loading error">
                    </div> 
                    <div class="blog-info">
                      <i class="far fa-clock"></i>
                      <span>December 18,2017</span>
                      <h4>how to find out beautiful workspace. </h4>
                      <p class="paragraph">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Impedit.</p>
                      <button class="btn blog-btn">Read article</button>
                    </div>
                </div>
                <div class="blog-container col-2 flex">
                    <div>   
                       <img class="blog-img" src="assets/media/blog-image3.jpg" alt="loading error">
                    </div> 
                    <div class="blog-info">
                      <i class="far fa-clock"></i>
                      <span>December 14,2017</span>
                      <h4>how to find out beautiful workspace. </h4>
                      <p class="paragraph">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Impedit.</p>
                      <button class="btn blog-btn">Read article</button>
                    </div>
                </div>
                <div class="blog-container col-2 flex">
                    <div>   
                       <img class="blog-img" src="assets/media/blog-image4.jpg" alt="loading error">
                    </div> 
                    <div class="blog-info">
                      <i class="far fa-clock"></i>
                      <span>December 10,2017</span>
                      <h4>how to find out beautiful workspace. </h4>
                      <p class="paragraph">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Impedit.</p>
                      <button class="btn blog-btn">Read article</button>
                    </div>
                </div>
            
              </div>
        </div>
      </section>
      <section class=" gallery">
        <div class="container">
            <h3>Our work</h3>
            <div class="flex">
              <div class="gallery">
                <img class="gallery-img" src="assets/media/work-image1.jpg" alt="Loading error">
                <img class="gallery-img" src="assets/media/work-image2.jpg" alt="Loading error">
                <img class="gallery-img" src="assets/media/work-image3.jpg" alt="Loading error">
                <img class="gallery-img" src="assets/media/work-image4.jpg" alt="Loading error">
              </div>
            </div>
        </div>
      </section>
      <section class="contact-section">
        <div class="container">
            <h3>contact us</h3>
            <div class="flex">
              <div class=" col-3 ">
                 <form>
                    <div class="form">
                       <input class="form-container" type="text" placeholder="Full Name">
                       <input class="form-container" type="text"placeholder=" Your Email">
                    </div>
                    <div>
                        <input class="form-container" type="text"placeholder=" Your Phone">
                        <input class="form-container" type="text" placeholder=" Budget Level">
                    </div>
                    <div>
                        <textarea class="message" rows="8" placeholder="Message"></textarea>
                        <button class="btn btn-header">Send Message</button>
                    </div>
                 </form>
              </div>
              <div class="map ">
                 <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3375.919515571293!2d76.35140991450203!3d32.206399320168714!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x391b530e24726e0d%3A0x71ff0cae0784712d!2sAltCampus%20Services%20Pvt.%20Ltd!5e0!3m2!1sen!2sin!4v1612428808085!5m2!1sen!2sin" width="400" height="300" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
              </div>
            </div>
        </div>
      </section>
    </main>
    <footer class="footer padding ">
      <div class="container">
        <div class="flex">
          <div class="col-4">
            <h5>hydro company</h5>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Totam accusantium itaque iusto? Aspernatur .</p>
          </div>
          <div>
            <h5>company</h5>
            <p>About us<br>
              join our team<br>
              Read blog<br>
              press
            </p>
          </div>
          <div>
            <h5>services</h5>
            <p>pricing<br>
              documentation<br>
              support
            </p>
          </div>
          <div>
            <h5>Find us</h5>
            <p>123 grand rama ix<br>
              krung thep maha nakhan 10400
            </p>
          </div>
        </div>
        <hr>
        <div class=" copyright flex">
            <small>copyright &copy; 2017 your company</small>
            <p>call us (+66) 010-020-0340</p>
            <ul class=" footer-social flex alignment align-item ">
               <li>
                  <i class="fab fa-facebook-square"></i>
               </li>
               <li>
                 <i class="fab fa-twitter"></i>
               </li>
               <li>
                  <i class="fab fa-instagram"></i>
               </li>
            </ul>
        </div>
      </div>
    </footer>
  </body>
</html>