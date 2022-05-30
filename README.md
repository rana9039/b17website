# b17website
> ## Chp1 (Introduction)
 Here is an overview about the website folders and the purpose of each one;
   - **b17** {Get started folder}
     - `index.html`  landing page which consider the start and the first page the visitor will see
     - `blog.html`  homepage after the visitor get to sign in 
   - **css** {a stylings folders}
   - **img** {contain all the images used in the code}
   - **js** {contain files written by javascripte language to implement complex features}
   - **node_modules** {save all downloaded packages from npm}
   - `register.html` {registeration page for sign up or login}
   - `login.html` {login page if you already have an account}
   - `forgot-password.html` {reset password page incase user forget the password in login process}
   - `setting.html` {setting page for changing any personal data}
   - `change-password.html` {for changing passowrd from setting page}
   - `user_profile.html` {profile page for signed individual user} 
   - `org_prof.html` {profile page for signed organizations}
   - `messages.html` {message chats page}

  ![project_all](https://user-images.githubusercontent.com/100317841/170894084-433713e6-cbbd-4645-8a34-1899772f0ad7.png)

> ## Chp2 (Landing page)
 > ### `index.html`
  #### header section (navigation bar) 
  ```html
<header id="header" class="header fixed-top">
    <div class="container-fluid container-xl d-flex align-items-center justify-content-between">
      <a href="index.html" class="logo d-flex align-items-center">
        <img src="assets/img/B2-0١.png" alt="">
        <span>17</span>
      </a>
      <nav id="navbar" class="navbar">
        <ul>
          <li><a class="nav-link scrollto active" href="#hero">Main</a></li>
          <li><a class="nav-link scrollto" href="#about">About</a></li>
          <li><a class="nav-link scrollto" href="#services">Services</a></li>
          <li><a href="blog.html">Homepage</a></li>
          <li><a class="nav-link scrollto" href="#contact">Contact</a></li>
          <li><a class="getstarted scrollto" href="#getstarted">Get Started</a></li>
        </ul>
        <i class="bi bi-list mobile-nav-toggle"></i>
      </nav>
    </div>
  </header>
  ```
  #### hero section 
   here we make a class name `"container"` that hold the whole page, containing 2 classes in it, the first one is `"col-lg-6 d-flex flex-column justify-content-center"` class that hold the left part of the page, `"col-lg-6 hero-img"` class that hold the right part of the page.
   ```html
  <section id="hero" class="hero d-flex align-items-center">

    <div class="container">
      <div class="row">
        <div class="col-lg-6 d-flex flex-column justify-content-center">
          <h1 data-aos="fade-up">We offer modern solutions to Enhance Your Knowledge </h1>
          <h2 data-aos="fade-up" data-aos-delay="400">We are a team of talented developers who can help you</h2>
          <div data-aos="fade-up" data-aos-delay="600">
            <div class="text-center text-lg-start">
              <a href="#about" class="btn-get-started scrollto d-inline-flex align-items-center justify-content-center align-self-center">
                <span>Get Started</span>
                <i class="bi bi-arrow-right"></i>
              </a>
            </div>
          </div>
        </div>
        <div class="col-lg-6 hero-img" data-aos="zoom-out" data-aos-delay="200">
          <img src="assets/img/1.png" class="img-fluid" alt="">
        </div>
      </div>
    </div>
  </section>

```
  #### About section
  this section can be accessed by scrolling down or click on About button on navbar
  ```html
<section id="about" class="about">
      <div class="container" data-aos="fade-up">
        <div class="row gx-0">
          <div class="col-lg-6 d-flex flex-column justify-content-center" data-aos="fade-up" data-aos-delay="200">
            <div class="content">
              <h3>Who Are We?!</h3>
              <h2> Group of Students Majouring in MIS </h2>
              <p> We are launching an application that connects companies with relevant student volunteers or participants who are mainly looking to gain more experience in their fields of interest while offering the companies a semi-professional recruitment process to choose the perfect participants for their CSR program's activities so both of them would benefit while contributing to the SDGs and enviromental development. So to answer your question, yes you did the partially right!.</p>
            </div>
          </div>
          <div class="col-lg-6 d-flex align-items-center" data-aos="zoom-out" data-aos-delay="200">
            <img src="assets/img/2.jpg" class="img-fluid" alt="">
          </div>
        </div>
      </div>
    </section>
```
#### our value section
  here its divided to 3 containers in each one we use an `<img>` and `<p>` to add an image and a paragraph to it
  ```html
<section id="values" class="values">
      <div class="container" data-aos="fade-up">
        <header class="section-header">
          <h2>Our Values</h2>
          <p>Achieving a better and sustainable future for students</p>
        </header>
        <div class="row">
          <div class="col-lg-4" data-aos="fade-up" data-aos-delay="200">
            <div class="box">
              <img src="assets/img/1 copy.jpg" class="img-fluid" alt="">
              <h3>Learn More About SDG</h3>
              <p>Educating the students through word and practice by contributing in SDGs goals</p>
            </div>
          </div>
          <div class="col-lg-4 mt-4 mt-lg-0" data-aos="fade-up" data-aos-delay="400">
            <div class="box">
              <img src="assets/img/2 (2) copy.jpg" class="img-fluid" alt="">
              <h3>Become a part of CSR</h3>
              <p>Minimizing organization's efforts in applying CSR programs</p>
            </div>
          </div>
          <div class="col-lg-4 mt-4 mt-lg-0 " data-aos="fade-up" data-aos-delay="600">
            <div class="box">
              <img src="assets/img/3.jpg" class="img-fluid" alt="">
              <h3>Earn Your Reward</h3>
              <p>Personalized reward system through educating & contributing studnts to SDGs by neglected sectors </p>
            </div>
          </div>
        </div>
      </div>
    </section>
```
#### featurs section
  here its divided to 3 containers; the fisrt ne is `"section-header"` for the tittle 
 ```html
<header class="section-header">
          <h2>Features</h2>
          <p> Get To Know Some Of Our Features</p>
        </header>
```
  second one is `"row"` that is divide to two part one contining the right side of the pages that contains the checked boxes and the left side that contains the image
 ```html
 <div class="row">
          <div class="col-lg-6">
            <img src="assets/img/4.jpg" class="img-fluid" alt="">
          </div>
          <div class="col-lg-6 mt-5 mt-lg-0 d-flex">
            <div class="row align-self-center gy-4">
              <div class="col-md-6" data-aos="zoom-out" data-aos-delay="200">
                <div class="feature-box d-flex align-items-center">
                  <i class="bi bi-check"></i>
                  <h3>Responsive Design</h3>
                </div>
              </div>
              <div class="col-md-6" data-aos="zoom-out" data-aos-delay="300">
                <div class="feature-box d-flex align-items-center">
                  <i class="bi bi-check"></i>
                  <h3>Profiles for both the organizations and users </h3>
                </div>
              </div>
              <div class="col-md-6" data-aos="zoom-out" data-aos-delay="400">
                <div class="feature-box d-flex align-items-center">
                  <i class="bi bi-check"></i>
                  <h3>Posts feature to post the need for volunteer students, the tasks involved, and the specific skills needed for the task</h3>
                </div>
              </div>
              <div class="col-md-6" data-aos="zoom-out" data-aos-delay="500">
                <div class="feature-box d-flex align-items-center">
                  <i class="bi bi-check"></i>
                  <h3>Create agreement feature to save all the agreement contract details</h3>
                </div>
              </div>
              <div class="col-md-6" data-aos="zoom-out" data-aos-delay="600">
                <div class="feature-box d-flex align-items-center">
                  <i class="bi bi-check"></i>
                  <h3>Categories including all 17 SDGs in the form of tags to clarify what job contributes to what goal</h3>
                </div>
              </div>
              <div class="col-md-6" data-aos="zoom-out" data-aos-delay="700">
                <div class="feature-box d-flex align-items-center">
                  <i class="bi bi-check"></i>
                  <h3>Feedback system to review both the students’ skills and the organizations’ program</h3>
                </div>
              </div>
            </div>
          </div>
        </div>
```
  third one is `"row feture-tabs"` that is divided to 3 conatinersby the name `"tab-pane fade show " but differ in the `id=` attribute 
 ```html
<div class="row feture-tabs" data-aos="fade-up">
          <div class="col-lg-6">
            <h3>What Do We Aim?</h3>
            <!-- Tabs -->
            <ul class="nav nav-pills mb-3">
              <li>
                <a class="nav-link active" data-bs-toggle="pill" href="#tab1">Abstract</a>
              </li>
              <li>
                <a class="nav-link" data-bs-toggle="pill" href="#tab2">Aspiration</a>
              </li>
              <li>
                <a class="nav-link" data-bs-toggle="pill" href="#tab3">Background</a>
              </li>
            </ul><!-- End Tabs -->
            <!-- Tab Content -->
            <div class="tab-content">
              <div class="tab-pane fade show active" id="tab1">
                <p>This project focuses on some of the key trends and movements in our economy like adopting the sustainability mindset and contributing to the SDGs.

The main idea of the project is to create a mobile application that facilitates contributing to achieving a sustainable future on the students-level through linking the students acts, skills and services to some organizations CSR programs, so that the organizations could benefit from the specific students’ skills in contributing to one or more of the SDG goals while offering their program and budget both of which would help the student learn and practice more and create a moral return system tailored for the students’ interest found on the app.
</p>
                <div class="d-flex align-items-center mb-2">
                </div> 
                <div class="d-flex align-items-center mb-2">                  
                </div>                
              </div><!-- End Tab 1 Content -->
              <div class="tab-pane fade show" id="tab2">
                <p>We are currently looking for interested organizations to create a sort of partnership with to launch the App where we will post their needs or requests for their CSR program and match it with the students of the most appropriate skills needed for the task at hand.
                  All we need from said organizations is their support of the idea, mainly through trusting us with recruiting the right students for their CSR project and with creating a fair return system that fits the student’s interests.
                  </p>
                <div class="d-flex align-items-center mb-2">                  
                </div>               
                <div class="d-flex align-items-center mb-2">
                </div>       
              </div><!-- End Tab 2 Content -->
              <div class="tab-pane fade show" id="tab3">
                <p>This project is the work of a group of students in The faculty of commerce, English section, MIS major, as the graduation project for the final semester, the project is supervised by Prof. Ghada El Khayat.</p>
                <div class="d-flex align-items-center mb-2">
                </div>
                <div class="d-flex align-items-center mb-2">
                </div>
              </div><!-- End Tab 3 Content -->
            </div>
          </div>
          <div class="col-lg-6">
            <img src="assets/img/5.jpg" class="img-fluid" alt="">
          </div>
        </div>
```
#### F.A.Q section
  it is divided to 2 containars (which is the lits) one at the right and one at the left, in each one it is divided to 3 containers the we use a `<buton>` with a tittle of the FAQ question in each one of them
 ```html
<section id="faq" class="faq">
      <div class="container" data-aos="fade-up">
        <header class="section-header">
          <h2>F.A.Q</h2>
          <p>Frequently Asked Questions</p>
        </header>
        <div class="row">
          <div class="col-lg-6">
            <!-- F.A.Q List 1-->
            <div class="accordion accordion-flush" id="faqlist1">
              <div class="accordion-item">
                <h2 class="accordion-header">
                  <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#faq-content-1">
                   how can i offer my recommendtion for the app?
                  </button>
                </h2>
                <div id="faq-content-1" class="accordion-collapse collapse" data-bs-parent="#faqlist1">
                  <div class="accordion-body">
                    Dolor sit amet consectetur adipiscing elit pellentesque habitant morbi. Id interdum velit laoreet id donec ultrices
                  </div>
                </div>
              </div>
              <div class="accordion-item">
                <h2 class="accordion-header">
                  <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#faq-content-2">
                    what is the age range for students?
                  </button>
                </h2>
                <div id="faq-content-2" class="accordion-collapse collapse" data-bs-parent="#faqlist1">
                  <div class="accordion-body">
                    Dolor sit amet consectetur adipiscing elit pellentesque habitant morbi. Id interdum velit laoreet id donec ultrices. Fringilla phasellus faucibus scelerisque eleifend donec pretium. Est pellentesque elit ullamcorper dignissim. Mauris ultrices eros in cursus turpis massa tincidunt dui.
                  </div>
                </div>
              </div>
              <div class="accordion-item">
                <h2 class="accordion-header">
                  <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#faq-content-3">
                    Can i review the events?
                  </button>
                </h2>
                <div id="faq-content-3" class="accordion-collapse collapse" data-bs-parent="#faqlist1">
                  <div class="accordion-body">
                    Eleifend mi in nulla posuere sollicitudin aliquam ultrices sagittis orci. Faucibus pulvinar elementum integer enim. Sem nulla pharetra diam sit amet nisl suscipit. Rutrum tellus pellentesque eu tincidunt. Lectus urna duis convallis convallis tellus. Urna molestie at elementum eu facilisis sed odio morbi quis
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-6">
            <!-- F.A.Q List 2-->
            <div class="accordion accordion-flush" id="faqlist2">
              <div class="accordion-item">
                <h2 class="accordion-header">
                  <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#faq2-content-1">
                    Ac odio tempor orci dapibus. Aliquam eleifend mi in nulla?
                  </button>
                </h2>
                <div id="faq2-content-1" class="accordion-collapse collapse" data-bs-parent="#faqlist2">
                  <div class="accordion-body">
                    Dolor sit amet consectetur adipiscing elit pellentesque habitant morbi. Id interdum velit laoreet id donec ultrices. Fringilla phasellus faucibus scelerisque eleifend donec pretium. Est pellentesque elit ullamcorper dignissim. Mauris ultrices eros in cursus turpis massa tincidunt dui.
                  </div>
                </div>
              </div>
              <div class="accordion-item">
                <h2 class="accordion-header">
                  <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#faq2-content-2">
                    Tempus quam pellentesque nec nam aliquam sem et tortor consequat?
                  </button>
                </h2>
                <div id="faq2-content-2" class="accordion-collapse collapse" data-bs-parent="#faqlist2">
                  <div class="accordion-body">
                    Molestie a iaculis at erat pellentesque adipiscing commodo. Dignissim suspendisse in est ante in. Nunc vel risus commodo viverra maecenas accumsan. Sit amet nisl suscipit adipiscing bibendum est. Purus gravida quis blandit turpis cursus in
                  </div>
                </div>
              </div>
              <div class="accordion-item">
                <h2 class="accordion-header">
                  <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#faq2-content-3">
                    Varius vel pharetra vel turpis nunc eget lorem dolor?
                  </button>
                </h2>
                <div id="faq2-content-3" class="accordion-collapse collapse" data-bs-parent="#faqlist2">
                  <div class="accordion-body">
                    Laoreet sit amet cursus sit amet dictum sit amet justo. Mauris vitae ultricies leo integer malesuada nunc vel. Tincidunt eget nullam non nisi est sit amet. Turpis nunc eget lorem dolor sed. Ut venenatis tellus in metus vulputate eu scelerisque. Pellentesque diam volutpat commodo sed egestas egestas fringilla phasellus faucibus. Nibh tellus molestie nunc non blandit massa enim nec.
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
```
####  Recent Blog Posts Section section (getstarted)
  here it is consist of one container holding 2 other containers one for the student access abd the other for the organization 
 ```html
<section id="getstarted">
<section id="recent-blog-posts" class="recent-blog-posts"> 
  <div class="container" data-aos="fade-up">
    <header class="section-header">
      <h2>GET STARTED</h2>
      <p>CHOOSE YOUR ACCOUNT TYPE</p>
    </header>   
    <div class="row d-flex justify-content-center">
      <div class="col-lg-4">
        <div class="post-box">
          <div class="post-img"><img src="assets/img/13651.jpg" class="img-fluid" alt=""></div>         
          <h3 class="post-title">ORGANIZATION</h3>
          <a href="blog-single.html" class="readmore stretched-link mt-auto"><span>Get Started</span></a>
        </div>
      </div>    
      <div class="col-lg-4">
        <div class="post-box">
          <div class="post-img"><img src="assets/img/st.jpg" class="img-fluid" alt=""></div>       
          <h3 class="post-title">STUDENT </h3>
          <a href="blog-single.html" class="readmore stretched-link mt-auto"><span>Get Started</span></a>         
      </div>     
    </div>    
  </div>
</section>
 </section>
```
 ####  Contact section
 it is divided to 2 containers, the right one like a form container and the left one consist of 4 boxes 
 ```html
<section id="contact" class="contact">
      <div class="container" data-aos="fade-up">
        <header class="section-header">
          <h2>Contact</h2>
          <p>Contact Us</p>
        </header>
        <div class="row gy-4">
          <div class="col-lg-6">
            <div class="row gy-4">
              <div class="col-md-6">
                <div class="info-box">
                  <i class="bi bi-geo-alt"></i>
                  <h3>Address</h3>
                  <p>A108 Adam Street,<br>New York, NY 535022</p>
                </div>
              </div>
              <div class="col-md-6">
                <div class="info-box">
                  <i class="bi bi-telephone"></i>
                  <h3>Call Us</h3>
                  <p>+1 5589 55488 55<br>+1 6678 254445 41</p>
                </div>
              </div>
              <div class="col-md-6">
                <div class="info-box">
                  <i class="bi bi-envelope"></i>
                  <h3>Email Us</h3>
                  <p>info@example.com<br>contact@example.com</p>
                </div>
              </div>
              <div class="col-md-6">
                <div class="info-box">
                  <i class="bi bi-clock"></i>
                  <h3>Open Hours</h3>
                  <p>Monday - Friday<br>9:00AM - 05:00PM</p>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-6">
            <form action="forms/contact.php" method="post" class="php-email-form">
              <div class="row gy-4">
                <div class="col-md-6">
                  <input type="text" name="name" class="form-control" placeholder="Your Name" required>
                </div>
                <div class="col-md-6 ">
                  <input type="email" class="form-control" name="email" placeholder="Your Email" required>
                </div>
                <div class="col-md-12">
                  <input type="text" class="form-control" name="subject" placeholder="Subject" required>
                </div>
                <div class="col-md-12">
                  <textarea class="form-control" name="message" rows="6" placeholder="Message" required></textarea>
                </div>
                <div class="col-md-12 text-center">
                  <div class="loading">Loading</div>
                  <div class="error-message"></div>
                  <div class="sent-message">Your message has been sent. Thank you!</div>
                  <button type="submit">Send Message</button>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>
``` 
####  footer section
it consist of 2 containers above each other; the upper one consist of 3 continers ; the left one for the Slog , the miidle for the intro to go to another pages by using `href` attribute in `<a>` , the right one for the contact us by using `<strong>`
```html
 <div class="footer-top">
      <div class="container">
        <div class="row gy-4">
          <div class="col-lg-5 col-md-12 footer-info">
            <a href="index.html" class="logo d-flex align-items-center">
              <img src="assets/img/B2-0١.png" alt="">
              <span>B17</span>
            </a>
            <p>There is no limit when it comes to hard work, together we might achive all the 17 goals.</p>
            <div class="social-links mt-3">
              <a href="#" class="twitter"><i class="bi bi-twitter"></i></a>
              <a href="#" class="facebook"><i class="bi bi-facebook"></i></a>
              <a href="#" class="instagram"><i class="bi bi-instagram"></i></a>
              <a href="#" class="linkedin"><i class="bi bi-linkedin"></i></a>
            </div>
          </div>
          <div class="col-lg-2 col-6 footer-links">
            <h4>Intro</h4>
            <ul>
              <li><i class="bi bi-chevron-right"></i> <a href="#">Home</a></li>
              <li><i class="bi bi-chevron-right"></i> <a href="#">About us</a></li>
              <li><i class="bi bi-chevron-right"></i> <a href="#">Services</a></li>
              <li><i class="bi bi-chevron-right"></i> <a href="#">Terms of service</a></li>
              <li><i class="bi bi-chevron-right"></i> <a href="#">Privacy policy</a></li>
            </ul>
          </div>
          <div class="col-lg-3 col-md-12 footer-contact text-center text-md-start">
            <h4>Contact Us</h4>
            <p>             
              <strong>Location:</strong> Alexandria, Eg<br> <br>  
              <strong>Phone:</strong> +20 151 282 3030<br>
              <strong>Email:</strong> B17@gmail.com<br>
            </p>
          </div>
        </div>
      </div>
    </div>
```
the lower one 
```html
<div class="container">
      <div class="copyright">
        &copy; Copyright <strong><span>B17</span></strong>. All Rights Reserved
      </div>
 ```

> ## Chp3 (registration)
> ## Chp4 (Getting to start)
