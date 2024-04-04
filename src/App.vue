<template>
  <div class="container-fluid">
            <div class="row">
                <div class="col-md-12 top"></div>
            </div>
            <div class="row">
                <div class="col-md-12">
                    <div class="hamburger-menu mobile">
                        <div class="mobile-logo text-center">
                            <img :src="require('@/assets/images/jen-logo.png')" alt="jen-logo">
                        </div>
                        <div class="button_container" id="toggle"><span class="top"></span><span class="middle"></span><span class="bottom"></span></div>
                        <div class="overlay" id="overlay">
                            <nav class="overlay-menu">
                                <ul>
                                    <li><a href="#home">HOME</a></li>
                                    <li><a href="#about">ABOUT Me</a></li>
                                    <li><a href="#gallery">GALLERY</a></li>
                                    <li><a href="#contact">CONTACT ME!</a></li>
                                </ul>
                            </nav>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="row menu top-nav align-items-center desktop">
                <div class="col-md-5 left-menu">
                   <ul class="navigation">
                        <li>
                            <a href="#home">HOME</a>
                        </li>
                        <li>
                            <a href="#about">ABOUT ME</a>
                        </li>
                   </ul>
                </div>
                <div class="col-md-2 logo-container" >
                  <img :src="require('@/assets/images/jen-logo.png')" alt="jen-logo">
                </div>
                <div class="col-md-5 right-menu">
                    <ul class="navigation">
                        <li>
                            <a href="#gallery">GALLERY</a>
                        </li>
                        <li>
                            <a href="#contact">CONTACT ME</a>
                        </li>
                   </ul>
                </div>
            </div>
            <div class="row align-items-center text-center bg-container" id="home">
                <div class="col-md-12">
                    <h1>JENNIFER'S</h1>
                    <div class="separator"></div>
                    <h1>PORTFOLIO</h1>
                </div>
            </div>
            <div class="row"  id="about">
                <div class="col-md-12 green-content-separator"></div>
            </div>
            <div class="row align-items-center text-center bg-title team">
                <div class="bg-overlay"></div>
                <div class="col-md-12">
                    <h1>ABOUT ME</h1>
                </div>
            </div>
            <div class="row about-box-content team-box">
                <h1></h1>
                <div class="col-md-6 col-sm-12 text-right">
                    <div class="box">
                        <a class="" data-bs-toggle="modal" data-bs-target="#exampleModal1">Jennifer Repala</a>
                        <span>BSIT 3A</span>
                        <div class="social">
                            <ul>
                                <li>
                                    <a href="https://www.facebook.com/jennifer.repala.75?mibextid=ZbWKwL" target="_blank">
                                        <i class="fa-brands fa-facebook"></i>
                                    </a>
                                </li>
                        
                                <li>
                                    <a href="mailto:jenniferrepala@gmail.com">
                                        <i class="fa-brands fa-google"></i>
                                    </a>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-sm-12 about-content">
                    <p>
                        Welcome to my corner of the internet! My name is Jennifer Repala, and I'm thrilled to have you here. I believe in the power of connection, which is why I've created this space to share a little piece of myself with you.  I aim to offer a glimpse into my world and the experiences that have shaped me as a person and a servant of God.
                    </p>
                    <p>
                        “What you are is God's gift to you, what you become is your gift to God.” so we must embrace it and love ourselves because God made us with his love.
                    </p>
                </div>
            </div>
            <div class="row" id="gallery">
                <div class="col-md-12 content-separator"></div>
            </div>
            <div class="row align-items-center text-center bg-title gallery-head">
                <div class="bg-overlay"></div>
                <div class="col-md-12">
                    <h1>GALLERY</h1>
                </div>
            </div>
            <div class="row gallery">
                <div class="col-md-4 box">
                    <div class="box-img">
                        <img :src="require('@/assets/images/Jennifer.png')" alt="fp-logo">
                    </div>
                </div>
                <div class="col-md-4 box">
                    <div class="box-img">
                        <img :src="require('@/assets/images/Jennifer-1.jpg')" alt="fp-logo">
                    </div>
                </div>
                <div class="col-md-4 box">
                    <div class="box-img">
                        <img :src="require('@/assets/images/Jennifer-2.jpeg')" alt="fp-logo">
                    </div>
                </div>
                <div class="col-md-4 box">
                    <div class="box-img">
                        <img :src="require('@/assets/images/Jennifer-3.jpg')" alt="fp-logo">
                    </div>
                </div>
                <div class="col-md-4 box">
                    <div class="box-img">
                        <img :src="require('@/assets/images/Jennifer-4.jpeg')" alt="fp-logo">
                    </div>
                </div>
                <div class="col-md-4 box">
                    <div class="box-img">
                        <img :src="require('@/assets/images/Jennifer-5.webp')" alt="fp-logo">
                    </div>
                </div>
            </div>
             <div class="row" id="contact">
                <div class="col-md-12 green-content-separator"></div>
            </div>
            <div class="row align-items-center text-center bg-title contact">
                <div class="bg-overlay"></div>
                <div class="col-md-12">
                    <h1>CONTACT ME</h1>
                </div>
            </div>
            <div class="row contact-container">
                <div class="col-md-12">
                    <div class="row contact-box align-items-center">
                        <div class="col-md-4 contact-info">
                            <div class="contact-info-box">
                                <h1>Connect with me</h1>
                                <span><i class="fa-brands fa-facebook"></i><a href="">Jennifer Repala</a></span>
                                <span><i class="fa fa-envelope"></i><a href="">jenniferrepala@gmail.com</a></span>
                                <span><i class="fa fa-phone"></i><a href="">09639023665</a></span>
                            </div>
                        </div>
                        <div class="col-md-8 form text-center">
                            <h1>Get in Touch!</h1>
                            <span>Feel free to drop us a line below</span>
                            <form action="">
                                <input type="text" name="" id="" placeholder="Your Full Name">
                                <input type="text" name="" id="" placeholder="Your Email">
                                <textarea name="" id="" cols="30" rows="10" placeholder="Type here your concerns"></textarea>
                                <button>Submit</button>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row footer align-items-center">
                <div class="col-md-12 text-center">
                    <p>Copyright 2023. All Rights Reserved</p>
                </div>
            </div>
        </div>
</template>

<script>
export default {
  name: 'App',
  mounted() {
    $('#toggle').click(function() {
      $(this).toggleClass('active');
      $('#overlay').toggleClass('open');
    });
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
