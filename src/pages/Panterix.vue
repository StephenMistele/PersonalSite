<template>
  <div>
    <div class="page-header page-header-small">
      <parallax
        class="page-header-image"
        style="background-image: url('img/panterixhome.png')"
      >
      </parallax>
      <div class="content-center">
        <div class="container">
          <h1 class="title">Panterix</h1>
          <div class="text-center">
            <a
              href="http://panterix.com/"
              class="btn btn-primary btn-round"
              target="_blank"
            >
              <b>Visit Panterix.com</b>
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="section section-about-us">
      <div class="container">
        <div class="row">
          <div class="col-md-8 ml-auto mr-auto text-center">
            <h2 class="title">Our Journey</h2>
            <h5 class="description">
              Panterix started as a hackathon project during <a href="https://devpost.com/software/saferides-t7hqnf" target="_blank"> Hack for Humanity 2020. </a>
              The idea was to aggregate traffic accident data to see if any roads had an unusually high number of accidents. From here, our 'dangerous roads' database
              could be used in everything from helping governments prioritize road repair to helping insurance companies customize rates.
            </h5>
            <br/>
            <center>
              <div class="video-wrap">
                <div class="video-container">
                  <img
                    src="img/panpitch.png"
                    alt="Thumbnail Image"
                    class="box img-fluid img-raised group"
                  />
                </div>
              </div>
            </center>
            <h5 class="description">
              After the hackathon, I pitched the project to one of my professors. We started a research project as part of 
              <a href="https://www.scu.edu/engineering/faculty/shaghaghi-navid/epic-lab/" target="_blank">Epic labs</a> 
              with the intention of one day turning this idea into a buisness. 
            </h5>
            <h5 class="description">
              Those dreams quickly became reality when we applied to Santa Clara's <a href="https://www.scu.edu/cioccacenter/bronco-ventures/bronco-venture-accelerator/" 
              target="_blank">Bronco Venture Accelerator</a>.
              It was a very difficult and competitive application process, but against all odds we 
              <a href="https://airtable.com/shr2lLkVBKWiiuCnc/tblu7ghpgXFqkQrU4" target="_blank">got in</a>!
              At the end of the 10-week course we got to present our idea to hundreds of venture capitalist investors. Here was our pitch.
            </h5>
            <center>
              <div class="video-wrap">
                <div class="video-container">
                  <iframe
                    src="https://www.youtube.com/embed/9yMidKiC3V8"
                  ></iframe>
                </div>
              </div>
            </center>
            <br/>
            <br/>
            <h2 class="title">Where we are now</h2>
            <h5 class="description">
              We've already completed our 'Danger Database' and implemented various API's to distribute the data. We're currently finishing our danger-based
              routing product (it allows users to choose routes based on speed <i>and</i> danger) as well as continuing talks with potential investors to 
              take the buisness to the next level.
            </h5>
          </div>
        </div>
        <div class="separator separator-primary"></div>
      </div>
    </div>
  </div>
</template>
<script>
import { Button, FormGroupInput } from "@/components";
export default {
  name: "landing",
  bodyClass: "landing-page",
  components: {
    [Button.name]: Button,
    [FormGroupInput.name]: FormGroupInput,
  },
  data() {
    return {
      form: {
        firstName: "",
        email: "",
        message: "",
      },
    };
  },
};
</script>
<style></style>
