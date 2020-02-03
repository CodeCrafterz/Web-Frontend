<template>
  <div id="app">
    
    <!-- ==============================================
    PRELOADER
    =============================================== -->

    <div class="preloader-holder">
        <div class="loading">
            <div class="finger finger-1">
                <div class="finger-item">
                    <span></span><i></i>
                </div>
            </div>
            <div class="finger finger-2">
                <div class="finger-item">
                    <span></span><i></i>
                </div>
            </div>
            <div class="finger finger-3">
                <div class="finger-item">
                    <span></span><i></i>
                </div>
            </div>
            <div class="finger finger-4">
                <div class="finger-item">
                    <span></span><i></i>
                </div>
            </div>
            <div class="last-finger">
                <div class="last-finger-item"><i></i></div>
            </div>
        </div>
    </div>

    <!-- ==============================================
    HEADER
    =============================================== -->

    <header id="home">

        <!-- /// Navbar /// -->

        <nav class="navbar navbar-expand-lg fixed-top">
            <div class="container">
                <!-- // Brand // -->

                <a class="navbar-brand" href="#">CODE<span>CRAFT</span>ERZ</a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation"><i class="material-icons">menu</i></button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <!-- / NavLinks / -->

                    <ul class="nav navbar-nav ml-auto">
                        <li class="nav-item">
                            <a class="nav-link page-scroll" href="#home">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link page-scroll" href="#services">Services</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link page-scroll" href="#features">Features</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link page-scroll" href="#prices">Prices</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link page-scroll" href="#team">Team</a>
                        </li>
                        <li>
                            <a class="nav-link page-scroll" href="#contact">
                            <button class="btn btn-primary">
                                Let's talk
                            </button>
                            </a>
                        </li>
                    </ul>

                </div>
            </div>
        </nav>

        <!-- /// BANNER /// -->
        <div class="banner">
            <div class="container">
                <div class="row">
                    <div class="col-md-8 offset-md-2">
                        <!-- // Caption // -->
                        <div class="caption">
                            <h1>Craft the future with CODECRAFTERZ.</h1>
                            <p class="sub">A passionate software development company.</p>
                            <br />
                            <!-- <a class="btn btn-primary" href="#">Download Now</a> -->
                            <!-- / Macbook IMG / -->
                            <!-- <img class="img-fluid mx-auto wow fadeInUp" data-wow-duration="1s" data-wow-delay=".3s" src="imgs/macbook.png" alt="macbook"> -->
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>

    <!-- ==============================================
    ABOUT 
    =============================================== -->

    <section id="about">
        <div class="container">
            <div class="row">
                <div class="col-md-4 wow bounceIn" data-wow-duration=".5s" data-wow-delay=".2s">
                    <!-- /// Icon /// -->
                    <i data-vi="layers" data-vi-size="70" data-vi-primary="#1992ec" data-vi-accent="#daeffd" data-vi-prop="#CEFAFF"></i>
                    <!-- // Title // -->
                    <h4>Creative Designs</h4>
                    <!-- / Caption / -->
                    <p>CODECRAFTERZ is always ready to create stunning designs for your business ideas.</p>
                </div>
                <div class="col-md-4 wow bounceIn" data-wow-duration=".5s" data-wow-delay=".4s">
                    <!-- /// Icon /// -->
                    <i data-vi="website" data-vi-size="70" data-vi-primary="#1992ec" data-vi-accent="#daeffd" data-vi-prop="#CEFAFF"></i>
                    <!-- // Title // -->
                    <h4>Fully Responsive Apps</h4>
                    <!-- / Caption / -->
                    <p>CODECRAFTERZ will create attractive application which would interact with you in the best way possible.</p>
                </div>
                <div class="col-md-4 wow bounceIn" data-wow-duration=".5s" data-wow-delay=".6s">
                    <!-- /// Icon /// -->
                    <i data-vi="chat" data-vi-size="70" data-vi-primary="#1992ec" data-vi-accent="#daeffd" data-vi-prop="#CEFAFF"></i>
                    <!-- // Title // -->
                    <h4>Unlimited Support</h4>
                    <!-- / Caption / -->
                    <p>CODECRAFTERZ is always here to help you with friendly services while you focus on your business.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==============================================
    SERVICES 
    =============================================== -->

    <section id="services">
        <div class="container">
            <div class="row">
                <div class="col-md-5 wow fadeInLeft" data-wow-duration=".5s" data-wow-delay=".2s">
                    <h3>Providing services to develop a long term relationship.</h3>
                    <p>CODECRAFTERZ will provide you services that would make you put us on the top of your friends list for the results you would get.</p>
                    <ul class="list-unstyled">
                        <li><i data-vi="check" data-vi-size="40" data-vi-primary="#1992ec" data-vi-accent="#daeffd" data-vi-prop="#CEFAFF"></i> <span>Web applications</span></li>
                        <li><i data-vi="check" data-vi-size="40" data-vi-primary="#1992ec" data-vi-accent="#daeffd" data-vi-prop="#CEFAFF"></i> <span>Android applications</span></li>
                        <li><i data-vi="check" data-vi-size="40" data-vi-primary="#1992ec" data-vi-accent="#daeffd" data-vi-prop="#CEFAFF"></i> <span>Desktop applications</span></li>
                    </ul>
                </div>
                <div class="col-md-7 wow fadeInRight" data-wow-duration=".5s" data-wow-delay=".5s">
                    <div class="img-table">
                        <img src="imgs/table.png" class="img-fluid" alt="table">
                    </div>
                </div>
            </div>
            <div class="row seconde">
                <div class="col-md-7 wow fadeInLeft" data-wow-duration=".5s" data-wow-delay=".2s">
                    <img src="imgs/updates.jpg" class="img-fluid" alt="update">
                </div>
                <div class="col-md-5 wow fadeInRight" data-wow-duration=".5s" data-wow-delay=".5s">
                    <div class="caption">
                        <h3>Whatever technologies you want to develop your applications with.</h3>
                        <p>Technology dosen't matter for the CODECRAFTERZ's experienced developers. We have got it in one place for you.</p>
                        <ul class="list-unstyled">
                            <li><i data-vi="check" data-vi-size="40" data-vi-primary="#1992ec" data-vi-accent="#daeffd" data-vi-prop="#CEFAFF"></i> <span>JavaScript</span></li>
                            <li><i data-vi="check" data-vi-size="40" data-vi-primary="#1992ec" data-vi-accent="#daeffd" data-vi-prop="#CEFAFF"></i> <span>Python</span></li>
                            <li><i data-vi="check" data-vi-size="40" data-vi-primary="#1992ec" data-vi-accent="#daeffd" data-vi-prop="#CEFAFF"></i> <span>Low and hi-fi mockups.</span></li>                        
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>


    <!-- ==============================================
    FEATURES 
    =============================================== -->

    <section id="features">
        <div class="container">
            <!-- /// Title /// -->
            <div class="row">
                <div class="col-md-6 col-sm-offset-2 text-center mx-auto">
                    <h2 class="section-title">Problem Solving</h2>
                    <p>Our experienced backend developers are here to help you provide your business idea the best, fast and secure solution through program development.</p>
                </div>
            </div>
            <!-- /// Features /// -->
            <div class="row">
                <div class="col-md-4 feature wow bounceIn" data-wow-duration=".5s" data-wow-delay=".2s">
                    <div class="feature-icon">
                        <i data-vi="doc" data-vi-primary="#60b6f4" data-vi-accent="#cfecff" data-vi-prop="#CEFAFF"></i>
                    </div>
                    <h4>UI/UX Design</h4>
                    <p>To plan things before is always benificial. Hence, take feedback from the user that how would they prefer things before risking your money in the final product.</p>
                    <p>Contact us to order your business product design.</p>
                </div>
                <div class="col-md-4 feature wow bounceIn" data-wow-duration=".5s" data-wow-delay=".4s">
                    <div class="feature-icon">
                        <i data-vi="newspaper" data-vi-primary="#60b6f4" data-vi-accent="#cfecff" data-vi-prop="#CEFAFF"></i>
                    </div>
                    <h4>Web App Development</h4>
                    <p>The best way to spread your voice is through a website. To find you on a World Wide Web is easy and less time consuming than installing your application on a mobile phone.</p>
                    <p>Contact us to negotiate your requirements with us.</p>
                </div>
                <div class="col-md-4 feature wow bounceIn" data-wow-duration=".5s" data-wow-delay=".8s">
                    <div class="feature-icon">
                        <i data-vi="controller" data-vi-primary="#60b6f4" data-vi-accent="#cfecff" data-vi-prop="#CEFAFF"></i>
                    </div>
                    <h4>Android App Development</h4>
                    <p>It is certain that if your business is vast that you can not depend on third party browser for your services then you need your own application for this.</p>
                    <p>Contact us, we'll help you get on with this problem.</p>
                </div>
                <div class="col-md-4 feature wow bounceIn" data-wow-duration=".5s" data-wow-delay=".6s">
                    <div class="feature-icon">
                        <i data-vi="processor" data-vi-primary="#cfecff" data-vi-accent="#60b6f4" data-vi-prop="#CEFAFF"></i>
                    </div>
                    <h4>Deskotp App Development</h4>
                    <p>Separate softwares on a PC that makes your business flow easy and fast can play an essential role in the success of your busineess.</p>
                    <p>Contact us to play that important role efficiently in your success.</p>
                </div>
                <div class="col-md-4 feature wow bounceIn" data-wow-duration=".5s" data-wow-delay="1.2s">
                    <div class="feature-icon">
                        <i data-vi="cloud" data-vi-primary="#60b6f4" data-vi-accent="#60b6f4" data-vi-prop="#CEFAFF"></i>
                    </div>
                    <h4>Script Writing</h4>
                    <p>Solving problems has got lot more easier with the help of Machine Learning, Computer Vision and other libraries in scripting languages.</p>
                    <p>Contact us to tell your problem and we'll write a script for your problem.</p>
                </div>
                <!-- <div class="col-md-4 feature wow bounceIn" data-wow-duration=".5s" data-wow-delay="1.2s">
                    <div class="feature-icon">
                        <i data-vi="cloud" data-vi-primary="#60b6f4" data-vi-accent="#60b6f4" data-vi-prop="#CEFAFF"></i>
                    </div>
                    <h4>Data Management</h4>
                    <p>It is unarguable that the data is one of the most precious asset a company owns and it needs the hands of experts to get the most out of it.</p>
                    <p>Contact us if you want to manage it or to put some machine learning on it.</p>
                </div> -->
                <div class="col-md-4 feature wow bounceIn" data-wow-duration=".5s" data-wow-delay="1s">
                    <div class="feature-icon">
                        <i data-vi="user" data-vi-primary="#cfecff" data-vi-accent="#60b6f4" data-vi-prop="#CEFAFF"></i>
                    </div>
                    <h4>Social Media Management</h4>
                    <p>Social Media, is the most important middleware in this era and can sit side-by-side your other applications to achieve your business goals.</p>
                    <p>Contact us to get our computer brains on your social accounts management.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ==============================================
    TESTIMONIALS 
    =============================================== -->

    <!-- <section id="testimonials">
        <div class="container">
            <div class="row">
                <div class="col-md-8 col-sm-offset-2 carousel-container">
                    <div id="owl-testimonials" class="owl-carousel owl-theme">
                        <div class="item">
                            <div class="testi-icon">
                                <i data-vi="bullhorn" data-vi-primary="#cfecff" data-vi-accent="#60b6f4" data-vi-prop="#CEFAFF"></i>
                            </div>
                            <p class="quote">" Curabitur ullamcorper ultricies nisi. Nam eget dui. Etiam rhoncus. Maecenas tempus, tellus eget condimentum rhoncus, sem quam semper libero, sit amet adipiscing sem neque sed ipsum. Nam quam nunc, blandit vel, luctus pulvinar, hendrerit id, lorem. "</p>
 -->
                            <!-- <img src="imgs/1.png" class="img-fluid" alt="1">
                            <h4>PERSON</h4>
                            <span>CEO Founder</span> -->
                        <!-- </div>
                        <div class="item">
                            <div class="testi-icon">
                                <i data-vi="bullhorn" data-vi-primary="#cfecff" data-vi-accent="#60b6f4" data-vi-prop="#CEFAFF"></i>
                            </div>
                            <p class="quote">" Curabitur ullamcorper ultricies nisi. Nam eget dui. Etiam rhoncus. Maecenas tempus, tellus eget condimentum rhoncus, sem quam semper libero, sit amet adipiscing sem neque sed ipsum. Nam quam nunc, blandit vel, luctus pulvinar, hendrerit id, lorem. "</p>
                            <img src="imgs/2.png" class="img-fluid" alt="2">
                            <h4>Nadine Tores</h4>
                            <span>Project Manager</span>
                        </div>
                        <div class="item">
                            <div class="testi-icon">
                                <i data-vi="bullhorn" data-vi-primary="#cfecff" data-vi-accent="#60b6f4" data-vi-prop="#CEFAFF"></i>
                            </div>
                            <p class="quote">" Curabitur ullamcorper ultricies nisi. Nam eget dui. Etiam rhoncus. Maecenas tempus, tellus eget condimentum rhoncus, sem quam semper libero, sit amet adipiscing sem neque sed ipsum. Nam quam nunc, blandit vel, luctus pulvinar, hendrerit id, lorem ".</p>
                            <img src="imgs/3.png" class="img-fluid" alt="3">
                            <h4>James Doe</h4>
                            <span>CEO Founder</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section> -->

    <!-- ==============================================
    PRICING 
    =============================================== -->

    <section id="prices">
        <div class="container">
            <div class="row">
                <!-- /// Title /// -->
                <div class="col-md-6 col-sm-offset-2 col-md-offset-3 text-center mx-auto">
                    <h2 class="section-title">Our Plans And Pricing:</h2>
                    <p>Following are the basic plans, the prices will he higher for more complex designs and problems.</p>
                </div>
            </div>
            <!-- /// Pricing Tables /// -->
            <div class="row">
                <!--// First Table // -->
                <div class="col-lg-4 wow fadeInLeft" data-wow-duration=".5s" data-wow-delay=".2s">
                    <div class="price-table">
                        <div class="header">
                            <h5 class="title">Basic</h5>
                            <div class="price">0$</div>
                            <h4>Free</h4>
                        </div>
                        <ul>
                            <li>Wordpress Theme</li>
                            <li>50GB Disk Space</li>
                            <li>50 Email Accounts</li>
                            <li>High Speed Internet</li>
                            <li>Free Theme Installation</li>
                        </ul>
                        <button class="btn btn-transparent" type="button">Sign Up</button>
                    </div>
                </div>
                <!--// First Table // -->
                <div class="col-lg-4 wow bounceIn" data-wow-duration=".5s" data-wow-delay=".4s">
                    <div class="price-table">
                        <div class="header">
                            <h5 class="title">Pro</h5>
                            <div class="price">10$</div>
                            <h4>Per Month</h4>
                        </div>
                        <ul>
                            <li>Wordpress Theme</li>
                            <li>50GB Disk Space</li>
                            <li>50 Email Accounts</li>
                            <li>High Speed Internet</li>
                            <li>Free Theme Installation</li>
                        </ul>
                        <button class="btn btn-primary" type="button">Sign Up</button>
                    </div>
                </div>
                <!--// First Table // -->
                <div class="col-lg-4 wow fadeInRight" data-wow-duration=".5s" data-wow-delay=".2s">
                    <div class="price-table">
                        <div class="header">
                            <h5 class="title">Ultimate Plan</h5>
                            <div class="price">50$</div>
                            <h4>Per Year</h4>
                        </div>
                        <ul>
                            <li>Wordpress Theme</li>
                            <li>50GB Disk Space</li>
                            <li>50 Email Accounts</li>
                            <li>High Speed Internet</li>
                            <li>Free Theme Installation</li>
                        </ul>
                        <button class="btn btn-transparent" type="button">Sign Up</button>
                    </div>
                </div>
            </div>
        </div>
    </section>



    <!-- ==============================================
    APP SCREENSHOTS 
    =============================================== -->

    <!-- <section id="screenshots">
        <div class="container">
            <div class="row">
                <div class="col-md-6 col-sm-offset-2 col-md-offset-3 text-center title-container"> -->
                    <!-- /// Title /// -->
                    <!-- <h2 class="section-title">App Screenshots:</h2>
                    <p>But I must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born.</p>
                </div>
            </div>
            <div class="row">
                <div id="owl-screenshots">
                    <div class="item"><img src="imgs/screenshots/1.png" class="img-fluid" alt="screen-1"></div>
                    <div class="item"><img src="imgs/screenshots/2.png" class="img-fluid" alt="screen-2"></div>
                    <div class="item"><img src="imgs/screenshots/3.png" class="img-fluid" alt="screen-3"></div>
                    <div class="item"><img src="imgs/screenshots/1.png" class="img-fluid" alt="screen-1"></div>
                    <div class="item"><img src="imgs/screenshots/2.png" class="img-fluid" alt="screen-2"></div>
                    <div class="item"><img src="imgs/screenshots/3.png" class="img-fluid" alt="screen-3"></div>
                    <div class="item"><img src="imgs/screenshots/1.png" class="img-fluid" alt="screen-1"></div>
                    <div class="item"><img src="imgs/screenshots/2.png" class="img-fluid" alt="screen-2"></div>
                </div>
            </div>
        </div>
    </section> -->

    <!-- ==============================================
    VIDEO POP UP 
    =============================================== -->

    <!-- <div id="video-popup">
        <div class="container">
            <div class="row">
                <div class="col-xs-12 col-sm-8 col-sm-offset-2 video-box">
                    <img src="imgs/video-bg.png" class="img-fluid wow rotateIn" data-wow-duration=".5s" data-wow-delay=".2s" alt="popup">
                    <div class="play-button">
                        <a class="bla-2 wow flipInY" data-wow-duration=".5s" data-wow-delay=".4s" href="https://www.youtube.com/watch?v=3qyhgV0Zew0"><i class="material-icons">play_arrow</i></a>
                        <div class="waves-block">
                            <div class="waves wave-1"></div>
                            <div class="waves wave-2"></div>
                            <div class="waves wave-3"></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div> -->

    <!-- ==============================================
    TEAM
    =============================================== -->

    <section id="team">
        <div class="container">
            <div class="row">
                <div class="col-xs-12 col-md-6 col-sm-offset-2 col-md-offset-3 text-center title-container">
                    <!-- /// Title /// -->
                    <h2 class="section-title">Our Team Of Experts:</h2>
                    <p>CODECRAFTERZ is an initiative taken by seven members of brillient students to mark their experties in the application development market.</p>
                </div>
            </div>
            <div class="row">
                <!-- /// TEAM MEMBERS /// -->
                <div class="col-md-4 member wow fadeInLeft" data-wow-duration=".5s" data-wow-delay=".2s">
                    <div class="member-img">
                        <img src="imgs/team/team1.png" class="img-fluid" alt="team-1">
                    </div>
                    <h4>PERSON 1</h4>
                    <p>CEO Founder</p>
                    <ul class="social-media">
                        <li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
                        <li><a href="#"><i class="fab fa-twitter"></i></a></li>
                        <li><a href="#"><i class="fab fa-google-plus-g"></i></a></li>
                        <li><a href="#"><i class="fab fa-linkedin-in"></i></a></li>
                    </ul>
                </div>
                <div class="col-md-4 member wow bounceIn" data-wow-duration=".5s" data-wow-delay=".4s">
                    <div class="member-img">
                        <img src="imgs/team/team-2.png" class="img-fluid" alt="team-2">
                    </div>
                    <h4>PERSON 2</h4>
                    <p>web designer</p>
                    <ul class="social-media">
                        <li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
                        <li><a href="#"><i class="fab fa-twitter"></i></a></li>
                        <li><a href="#"><i class="fab fa-google-plus-g"></i></a></li>
                        <li><a href="#"><i class="fab fa-linkedin-in"></i></a></li>
                    </ul>
                </div>
                <div class="col-md-4 member wow fadeInRight" data-wow-duration=".5s" data-wow-delay=".2s">
                    <div class="member-img">
                        <img src="imgs/team/team-3.png" class="img-fluid" alt="team-3">
                    </div>
                    <h4>PERSON 3</h4>
                    <p>web developer</p>
                    <ul class="social-media">
                        <li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
                        <li><a href="#"><i class="fab fa-twitter"></i></a></li>
                        <li><a href="#"><i class="fab fa-google-plus-g"></i></a></li>
                        <li><a href="#"><i class="fab fa-linkedin-in"></i></a></li>
                    </ul>
                </div>
            </div>
            <div class="row">
                <!-- /// TEAM MEMBERS /// -->
                <div class="col-md-4 member wow fadeInLeft" data-wow-duration=".5s" data-wow-delay=".2s">
                    <div class="member-img">
                        <img src="imgs/team/team1.png" class="img-fluid" alt="team-1">
                    </div>
                    <h4>PERSON 1</h4>
                    <p>CEO Founder</p>
                    <ul class="social-media">
                        <li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
                        <li><a href="#"><i class="fab fa-twitter"></i></a></li>
                        <li><a href="#"><i class="fab fa-google-plus-g"></i></a></li>
                        <li><a href="#"><i class="fab fa-linkedin-in"></i></a></li>
                    </ul>
                </div>
                <div class="col-md-4 member wow bounceIn" data-wow-duration=".5s" data-wow-delay=".4s">
                    <div class="member-img">
                        <img src="imgs/team/team-2.png" class="img-fluid" alt="team-2">
                    </div>
                    <h4>PERSON 2</h4>
                    <p>web designer</p>
                    <ul class="social-media">
                        <li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
                        <li><a href="#"><i class="fab fa-twitter"></i></a></li>
                        <li><a href="#"><i class="fab fa-google-plus-g"></i></a></li>
                        <li><a href="#"><i class="fab fa-linkedin-in"></i></a></li>
                    </ul>
                </div>
                <div class="col-md-4 member wow fadeInRight" data-wow-duration=".5s" data-wow-delay=".2s">
                    <div class="member-img">
                        <img src="imgs/team/team-3.png" class="img-fluid" alt="team-3">
                    </div>
                    <h4>PERSON 3</h4>
                    <p>web developer</p>
                    <ul class="social-media">
                        <li><a href="#"><i class="fab fa-facebook-f"></i></a></li>
                        <li><a href="#"><i class="fab fa-twitter"></i></a></li>
                        <li><a href="#"><i class="fab fa-google-plus-g"></i></a></li>
                        <li><a href="#"><i class="fab fa-linkedin-in"></i></a></li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- ==============================================
    BRAND
    =============================================== -->

    <!-- <section id="brands">
        <div class="container">
            <div class="row">
                <div class="col-xs-12 col-sm-8 col-md-6 col-sm-offset-2 col-md-offset-3 text-center title-container"> -->
                    <!-- /// Title /// -->
                    <!-- <h2 class="section-title">We Are Trusted By:</h2>
                    <p>But I must explain to you how all this mistaken idea of denouncing pleasure and praising pain was born.</p>
                </div>
            </div>
            <div class="row">
                <div id="owl-brands">
                    <div class="item"><img src="imgs/brands/brand-1.png" class="img-fluid" alt="brand-1"></div>
                    <div class="item"><img src="imgs/brands/brand-2.png" class="img-fluid" alt="brand-1"></div>
                    <div class="item"><img src="imgs/brands/brand-3.png" class="img-fluid" alt="brand-3"></div>
                    <div class="item"><img src="imgs/brands/brand-1.png" class="img-fluid" alt="brand-1"></div>
                    <div class="item"><img src="imgs/brands/brand-2.png" class="img-fluid" alt="brand-2"></div>
                    <div class="item"><img src="imgs/brands/brand-3.png" class="img-fluid" alt="brand-3"></div>
                </div>
            </div>
        </div>
    </section> -->

    <!-- ==============================================
    FOOTER
    =============================================== -->

    <section id="contact">
        <div class="container">
            <div class="row">
                <div class="col-xs-12 col-sm-8 col-md-6 col-sm-offset-2 col-md-offset-3 text-center title-container">
                    <!-- /// Title /// -->
                    <h2 class="section-title">Don't Be Shy, Send a Message:</h2>
                    <p>"There's a first time for everything."</p>
                    <p>So let's talk. We're sure, you'll not be disappointed.</p>
                </div>
            </div>

            <!-- /// CONTACT FORMS /// -->

            <form>
                <div class="form-row">
                    <div class="form-group col-xs-12 col-sm-4">
                        <label>Name:</label>
                        <input type="text" class="form-control" id="inputName4">
                    </div>
                    <div class="form-group col-xs-12 col-sm-4">
                        <label for="inputPassword4">Email:</label>
                        <input type="email" class="form-control" id="inputPassword4">
                    </div>
                    <div class="form-group col-xs-12 col-sm-4">
                        <label>Phone:</label>
                        <input type="text" class="form-control" id="inputPhone">
                    </div>
                </div>
                <div class="form-group">
                    <label>Subject:</label>
                    <input type="text" class="form-control" id="inputSubject">
                </div>
                <div class="form-group">
                    <label>Message:</label>
                    <textarea id="form-message" cols="30" rows="5" class="form-control"></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Send Message</button>
            </form>
            <p>&copy; CODECRAFTERZ All Right Reserved</p>
        </div>
    </section>
  </div>
</template>

<script>
import anime from 'animejs/lib/anime.es.js';
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>
