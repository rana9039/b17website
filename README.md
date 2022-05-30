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
 - `index.html`
   - header section (navigation bar) 
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

   - hero section (here we make a class name contair that hold the whole page in it 2 classes the first one) :
    -`"col-lg-6 d-flex flex-column justify-content-center"` that hold the left part of the page.
    -`"col-lg-6 hero-img"` that hold the right part of the page.
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

> ## Chp3 (registration)
> ## Chp4 (Getting to start)
