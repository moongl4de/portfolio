<template>
  <div id="app">
    
    <v-vanta id="vanta"
      style="background-color: red !important"
      effect="net"
      :options="options"
    ></v-vanta>
    <section id="topSection"
      class="hero-area overlay"
      style="background-image: url('images/banner/hero-area.jpg')"
    >
      <!-- <video autoplay muted loop class="hero-video">
		<source src="images/banner/hero-video.mp4" type="video/mp4">
	</video> -->
      <div class="block" id="nameBox">
        <h1 class="">
          <span style="color: #1594f3 !important">Alex</span>Gignilliat
        </h1>

        <p data-aos="fade-in" class="tagline" style="letter-spacing: 4px">
          <span style="color: #1594f3 !important; letter-spacing: 4px">
            UI Engineer 
          </span>
          | Blockchain Evangelist
        </p>
        <!-- 
        <hr /> -->
        <a data-scroll href="#about" class=""
          ><button
            style="border-radius: 0px; min-width: 10%"
            class="btn portfolioButton hvr-underline-from-left"
          >
            <span style="color: #1594f3 !important">About </span> Me
          </button></a
        >
      </div>
    </section>
    <section
      class="sectionDiv"
      id="about"
      style="height: 100vh; background-color: #171c21; padding-top: 15%"
    >
      <!-- <video autoplay muted loop class="hero-video">
        asda
		<source src="images/banner/hero-video.mp4" type="video/mp4">
	</video> -->

      <h2
        data-aos-easing="ease-in-out"
        data-aos-duration="1000"
        data-aos="fade-in"
        style="color: white"
      >
        Specialize in developing
        <span style="color: #1594f3">
          clean user interfaces & seamless user experiences</span
        >.
      </h2>
      <h2
        data-aos-easing="ease-in-out"
        data-aos-duration="1000"
        data-aos="fade-in"
        style="color: white"
        data-aos-delay="1000"
      >
        Passionate about the role of
        <span style="color: #1594f3"> web apps in financial technology</span>.
      </h2>
      <h2
        data-aos-easing="ease-in-out"
        data-aos-duration="1000"
        data-aos="fade-in"
        style="color: white"
        data-aos-delay="2000"
      >
        Dedicated to enabling the
        <span style="color: #1594f3"> internet of value</span>.
      </h2>
      <a
        data-scroll
        href="#technologies"
        class=""
        data-aos-easing="ease-in-out"
        data-aos-duration="1000"
        data-aos="fade-in"
        style="color: white"
        data-aos-delay="3000"
        ><button
          style="border-radius: 0px; min-width: 10%"
          class="btn portfolioButton hvr-underline-from-left"
        >
          Technologies I Use
        </button></a
      >
    </section>
    <section
      class="sectionDiv"
      id="technologies"
      style="height: 120vh; background-color: #171c21; padding-top: 1%"
    >
      <div class="container">
        <div class="row d-flex justify-content-between">
          <div         data-aos-easing="ease-in-out"
        data-aos-duration="800"
        data-aos="fade-in" class="col-md-2 col-sm-2 col-xs-2" style="margin: 0 auto">
            <i
              style="color: #f0db4f; "
              class="fab fa-js fa-8x"
            ></i>
          </div>
          <div         data-aos-easing="ease-in-out"
        data-aos-duration="1500"
        data-aos="fade-in" class="col-md-2 col-sm-2 col-xs-2" style="margin: 0 auto">
            <i
              style="color: #3fb27f; "
              class="fab fa-vuejs fa-8x"
            ></i>
          </div>
          <div         data-aos-easing="ease-in-out"
        data-aos-duration="2000"
        data-aos="fade-in" class="col-md-2 col-sm-2 col-xs-2" style="margin: 0 auto">
            <i
              style="color: #7fc728; "
              class="fab fa-node fa-8x"
            ></i>
          </div>

          <!-- <div class="col-2" style="height: 100px">
            <i
              style="color: #f08d03"
              class="fas fa-database fa-10x mx-auto"
            ></i>
            <p style="margin: 8px; color: white">
              FileMaker<br />Mongo<br />MySQL
            </p>
          </div> -->
        </div>
        <hr />
        <div class="row">
          <div         data-aos-easing="ease-in-out"
          data-aos-delay="600"
        data-aos-duration="2000"
        data-aos="fade-in" class="col-md-4 col-xs-2 mx-auto">
            <h1 style="color: #1594f3; text-align: left; margin: 20px">
              Technologies
            </h1>
            <p class="technologyHeaders" style="color: white; text-align: left; max-width: 500px">
              While I have used a myriad of technologies in my developer career,
              I have found myself mainly using <span style="color: #F0DB4F">JavaScript (ES6)</span>, <span style="color: #3FB27F">Vue</span> and <span style="color: #7FC728">Node</span>. I
              also have experience with:
              <ul>
                <li>Express</li>
                <li>Bootstrap</li>
                <li>jQuery</li>
                <li>React</li>
                <li>MySQL</li>
                <li>MongoDB</li>
                <li>FileMaker Pro</li>
                
              </ul>
            </p>
          </div>
          <br />
          <hr id="techLine"/>
          <div          data-aos-easing="ease-in-out"
          data-aos-delay="800"
        data-aos-duration="2000"
        data-aos="fade-in" class="col-md-4 col-xs-2 mx-auto">
            <h1 style="color: #1594f3; text-align: left; margin: 20px">
              Tools
            </h1>
            <p style="color: white; text-align: left; max-width: 500px">
              While developing, I use quite a few tools to get help get the job done. Outside of frameworks, libraries, etc, here few of my most utilized tools are:
              <ul> 
                <li>Git</li>
                <li>GitHub</li>
              <li>Postman</li>
              <li>Chrome Dev Tools</li>
              <li>VS Code</li>
              <li>NPM</li>
              <li>Bash</li>
            
              
              </ul>
            </p>
          </div>
          
        </div>
        <br/>
              <a
        data-scroll
        href="#portfolio"
        class=""
        data-aos-easing="ease-in-out"
        data-aos-duration="1000"
        data-aos="fade-in"
        style="color: white; margin-top: 10px; position: relative; top: -20px;"
        data-aos-delay="1500"
  
        ><button
          style="border-radius: 0px; min-width: 30%"
          class="btn portfolioButton hvr-underline-from-left"
        >
          View My Work
        </button></a
      >
      </div>
      <!-- <video autoplay muted loop class="hero-video">
        asda
		<source src="images/banner/hero-video.mp4" type="video/mp4">
	</video> -->
    </section>
        <section
      class="sectionDiv"
      id="portfolio"
      style="height: 240vh; background-color: #171c21; padding-top: 10%; margin-bottom: 0px"
    >
    
    <h1 data-aos-easing="ease-in-out" id="projectHeader"
    style="font-size: 100px;"
          data-aos-delay="0"
        data-aos-duration="2000"
        data-aos="fade-in"> Projects</h1>
        <p style="">Always building. Always learning.</p>
<div class="container" style="margin: 5% auto;">
        <div class="row ">

                    <div class="col-md-12 portfolioCard" style="background-color: #313131">
            <div class="row">
                                      <div data-aos-easing="ease-in-out"
          data-aos-delay="0"
        data-aos-duration="1000"
        data-aos="fade-in" class="col-md-6 col-sm-12" >
              <h1 style="color: #1594f3;; font-size: 3rem; margin: 1%; text-align: left;">PI Legal</h1>
            
            <p style="color: white; text-align: left;"><i style='font-size: 13px;'>A case management application for law firms to log payments, generate documents and monitor the progress of cases</i><br/><br/>PI Legal is a robust case management application currently being used by Cambre & Associates in Atlanta, Georgia. <br/><br/> Some of the most recent features I've implemented are report generation, an in-house API for client data retrieval, negotiation offer/demand tracking, statute of limitation alerts, an automated e-mail notification system.</p></div>

            <div class="col-md-6 col-xs-12">
            <img data-aos-easing="ease-in-out"
          data-aos-delay="100"
        data-aos-duration="1400"
        data-aos="fade-in" class="portfolioImg " src="../src/assets/PIscreenshot1.png"/>
            </div>

           
            <hr style="border-top: 1px solid white; margin: 20px"/>
                     
             <div data-aos-easing="ease-in-out"
          data-aos-delay="0"
        data-aos-duration="2000"
        data-aos="fade-in" class="col-12 d-flex justify-content-center" style="color: white"><h6><i>Proprietary Application / Private Repo</i></h6></div>
      
          </div>

          
          </div>

          <p style="margin: 20px;"></p>

                    <div data-aos-easing="ease-in-out"
          data-aos-delay="0"
        data-aos-duration="1000"
        data-aos="fade-in" class="col-md-12 portfolioCard" style="background-color: #0D0D0D">
            <div class="row">

            <div class="col-md-6 col-xs-12">
            <img data-aos-easing="ease-in-out"
          data-aos-delay="100"
        data-aos-duration="1000"
        data-aos="fade-in" class="portfolioImg " src="https://raw.githubusercontent.com/alexgignilliat/Digital-Asset-Monitor/master/DAM2ss.png"/>
            </div>
                        <div data-aos-easing="ease-in-out"
          data-aos-delay="0"
        data-aos-duration="1000"
        data-aos="fade-in" class="col-md-6 col-sm-12" >
              <h1 style="color: #1594f3;; font-size: 3rem; margin: 1%; text-align: left;">Digital Asset Monitor</h1>
            
            <p style="color: white; text-align: left;"><i style='font-size: 13px;'>A minimalist approach to tracking the price action and news for the top three digital assets.</i><br/><br/>Digital Asset Monitor provides users with prices, news articles and latest tweets for the top three cryptocurrencies by market cap.</p></div>
           
            <hr style="border-top: 1px solid white; margin: 20px"/>
                     
             <div data-aos-easing="ease-in-out"
          data-aos-delay="0"
        data-aos-duration="1000"
        data-aos="fade-in" class="col-12 d-flex justify-content-center" style="color: white"><h3><a target="_blank" href="https://github.com/alexgignilliat/bandwagon"><i class="fab fa-github"></i> GitHub</a></h3></div>
      
          </div>

          
          </div>

                              <p style="margin: 20px;"></p>
          
          <div class="col-md-12 portfolioCard">
            <div class="row">
            <div data-aos-easing="ease-in-out"
          data-aos-delay="0"
        data-aos-duration="1000"
        data-aos="fade-in" class="col-md-6 col-sm-12" >
              <h1 style="color: #1594f3;; font-size: 3rem; margin: 1%; text-align: left;">Bandwagon</h1>
            
            <p style="color: white; text-align: left;"><i style='font-size: 13px;'>A digital music streaming platform designed with listeners and artists in mind.</i><br/><br/>Users are allotted a number of tokens based on their subscription plan. Every time a user streams a song, a microtransaction takes place sending a fraction of a token directly to the artist. This model completely removes middlemen cutting into the artists' profits. <br/><br/> Future development roadmap entails utilizing <span class="blueSpan">XRP</span> instead of the Bandwagon token.</p></div>
            <div class="col-md-6 col-xs-12">
            <img data-aos-easing="ease-in-out"
          data-aos-delay="100"
        data-aos-duration="1400"
        data-aos="fade-in" class="portfolioImg " src="https://raw.githubusercontent.com/alexgignilliat/bandwagon/master/client/src/img/bandwagon-listener.png"/>
            </div>
           
            <hr style="border-top: 1px solid white; margin: 20px"/>
                     
             <div data-aos-easing="ease-in-out"
          data-aos-delay="0"
        data-aos-duration="2000"
        data-aos="fade-in" class="col-12 d-flex justify-content-center" style="color: white"><h3><a target="_blank" href="https://github.com/alexgignilliat/bandwagon"><i class="fab fa-github"></i> GitHub</a></h3></div>
      
          </div>

          
          </div>

          

          
         
            
             
          </div>
           
        </div>
  
      <!-- <video autoplay muted loop class="hero-video">
        asda
		<source src="images/banner/hero-video.mp4" type="video/mp4">
	</video> -->
    </section>
    <section id="contact" style="background-color: #171c21; padding-top: 2%; padding-bottom: 10%; !important;" class='container'>
      <div class="row">
               <div class="mx-auto ">
                             
                                            <h6 data-aos-easing="ease-in-out"
          data-aos-delay="0"
        data-aos-duration="2000"
        data-aos="fade-in" class=" col-12"  id="build" style="text-align: center !important; color: white; font-size: 22px;">Let's <span class="blueSpan">build</span> something.</h6>
                                  
                                  <br/>
                                        <form data-aos-easing="ease-in-out"
          data-aos-delay="1500"
        data-aos-duration="2000"
        data-aos="fade-in" style=""
                                            method="post" action="https://formspree.io/mbjodlrz"
                                            data-form-title="CONTACT">
                                            <input type="hidden" data-form-email="true">
                                            <div class="form-group">
                                                <input type="text" class=" form-control"
                                                    name="name" required="" placeholder="Name*" data-form-field="Name">
                                            </div>
                                            <div class="form-group">
                                                <input type="email" class=" form-control"
                                                    name="email" required="" placeholder="Email*"
                                                    data-form-field="Email">
                                            </div>
                                            <div class="form-group">
                                                <input type="tel" class=" form-control"
                                                    name="phone" placeholder="Phone" data-form-field="Phone">
                                            </div>
                                            <div class="form-group">
                                                <textarea style="border-radius: 0px;" class="wow zoomIn form-control fadeInLeftBig"
                                                    name="message" placeholder="Message" rows="7"
                                                    data-form-field="Message"></textarea>
                                            </div>
                                            <button  id="button" style="margin: 0 auto;" type="submit"
                                                class="btn btn-lg btn-dark col-sm-12 wow zoomIn">submit</button>
                                                
                                        </form>
                               
                                    </div>
                                    </div>
    </section>

  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld.vue";
import "bootstrap/dist/css/bootstrap.css";
import VVanta from "vue-vanta";
import "bootstrap/dist/css/bootstrap.css";
import "bootstrap-vue/dist/bootstrap-vue.css";
import AOS from "aos";
import "aos/dist/aos.css";

export default {
  components: { VVanta },
  created() {
    AOS.init();
    document.title = "Alex Gignilliat";
  },
  mounted() {
    this.headerChange();
  },
  data() {
    return {
      introHeader: "",
      colorVanta: "rgb(24, 154, 243)",
      backgroundColorVanta: "red",
      options: {
        mouseControls: true,
        touchControls: true,
        gyroControls: false,
        minHeight: 900.0,
        minWidth: 100.0,
        scale: 1.0,
        scaleMobile: 1.0,
        points: 5.0,
        spacing: 18.0,
        color: "#1594f3",
        backgroundColor: "#171C21",
      },
      methods: {
        headerChange: function () {
          this.introHeader = "hehrhsdjkfhs";
        },
      },
    };
  },

  name: "App",
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@300&display=swap");
html {
  scroll-behavior: smooth;
  max-width: 100%;
  background-color: #171c21;
}

.blueSpan {
  color: #1594f3;
}

@media only screen and (max-width: 600px) {
  html,
  body {
    background-color: #171c21;
    padding: 0;
  }

  #vanta {
    margin-bottom: 10%;
  }

  #projectHeader {
    font-size: 80px !important;
  }
  .sectionDiv {
    padding: 20px 10px;
    margin-top: 10%;
    z-index: 100;
  }

  #technologies {
    margin: 0;
    margin-bottom: 10%;
  }

  #portfolio {
    margin-top: 1000px;
    margin-bottom: 800px;
  }

  h1 {
    font-size: 40px !important;
  }

  h2 {
    font-size: 20px;
    margin: 10%;
  }

  .tagline {
    font-size: 14px !important;
  }

  .fa-js,
  .fa-node,
  .fa-vuejs {
    font-size: 100px !important;
    text-align: center;
    display: inline-block;
    justify-content: center;
  }

  .technologyHeaders {
    padding: 10px;
  }

  #techLine {
    border-top: 1px solid white;
  }

  #topSection {
    position: relative;
    top: -100px;
  }

  #about {
    margin-top: 20%;
  }

  .portfolioCard {
    border-radius: 8px;
  }

  #contact {
    margin-bottom: 10%;
    margin-top: 500px;
    height: 80vh;
  }
}

@media only screen and (max-width: 360px) {
  #portfolio {
    margin-top: 1000px;
    margin-bottom: 1000px;
  }

  #contact {
    height: 87vh;
  }
}

body {
  padding: 0;
  margin: 0;
  scroll-behavior: smooth;
  max-width: 100%;
}

.portfolioImg {
  width: 100%;
  margin: 0 auto;
  border-radius: 20px;
}

.portfolioCard {
  overflow: hidden;
  width: 100%;
  display: flex;
  justify-content: center;
  background-color: #313131;
  padding: 10px;
}

#nameBox {
  background: rgba(255, 255, 255, 0.13);
  box-shadow: 10px 10px 10px rgba(221, 213, 213, 0.014);
  backdrop-filter: blur(10px);
  -webkit-backdrop-filter: blur(1px);
  border-radius: 5px;
  width: 100%;
  /* border-radius: 22px; */
  border: 3px solid rgba(255, 255, 255, 0.116);
  background-clip: padding-box;
  padding: 15px;

  border-top: 3px rgba(255, 255, 255, 0.199) solid;
}
#app {
  font-family: "Inter", sans-serif;

  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  width: 100%;
  background-color: #171c21;
  height: 100vh;
}

.portfolioButton {
  background-color: rgba(255, 255, 255, 0.61);
  margin: 30px;
}
.portfolioButton:hover {
  background-color: rgb(255, 255, 255);
}

.hero-area {
  background-size: cover;
  height: 100vh;
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
}

.hero-area .block {
  text-align: center;
  z-index: 99;
}

.hero-area .block .video-button a {
  background: #fff;
  display: inline-block;
  height: 60px;
  width: 60px;
  border-radius: 50px;
  line-height: 60px;
  font-size: 20px;
  margin-left: 3px;
  color: #57cbcc;
}

.hero-area .block h1 {
  font-size: 90px;
  color: #fff;
  text-transform: capitalize;
  font-weight: 700;
  margin-bottom: 20px;
}

.hero-area .block p {
  color: #fff;
  font-size: 20px;
  width: 70%;
  margin: 0 auto;
}

.hero-area .block .btn-transparent {
  margin-top: 40px;
  border-color: #fff;
  padding: 14px 50px;
  font-size: 18px;
  font-size: 16px;
  font-weight: bold;
  letter-spacing: 1px;
}

.hero-video {
  left: 50%;
  min-height: 100%;
  min-width: 100%;
  position: absolute;
  top: 50%;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
}

.hvr-underline-from-left {
  display: inline-block;
  vertical-align: middle;
  -webkit-transform: perspective(1px) translateZ(0);
  transform: perspective(1px) translateZ(0);
  box-shadow: 0 0 1px rgba(0, 0, 0, 0);
  position: relative;
  overflow: hidden;
}
.hvr-underline-from-left:before {
  content: "";
  position: absolute;
  z-index: -1;
  left: 0;
  right: 100%;
  bottom: 0;
  background: #1494f3;
  height: 4px;
  -webkit-transition-property: right;
  transition-property: right;
  -webkit-transition-duration: 0.3s;
  transition-duration: 0.3s;
  -webkit-transition-timing-function: ease-out;
  transition-timing-function: ease-out;
}
.hvr-underline-from-left:hover:before,
.hvr-underline-from-left:focus:before,
.hvr-underline-from-left:active:before {
  right: 0;
}

@media (max-width: 480px) {
  .hero-area .block h1 {
    font-size: 60px;
  }
}

h1 {
  margin: 0;
  color: white;
}
</style>
