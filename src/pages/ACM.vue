<template>
  <div>
    <div class="page-header page-header-small">
      <parallax
        class="page-header-image"
        style="background-image: url('img/webdesign.jfif')"
      >
      </parallax>
      <div class="content-center">
        <div class="container">
          <h1 class="title">Websites</h1>
          <div class="text-center">
            <a
              href="http://hackforhumanity.io/"
              class="btn btn-primary btn-round"
              target="_blank"
            >
              <b>Visit the hackathon site</b>
            </a>
            &#8203;&#8203;&#8203;
            <a
              href="http://acm.engr.scu.edu/"
              class="btn btn-primary btn-round"
              target="_blank"
            >
              <b>Visit the ACM main site</b>
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="separator separator-primary"></div>
    <div class="section section-about-us">
      <div class="container">
        <div class="row">
          <div class="col-md-10 ml-auto mr-auto text-center">
            <h2 class="title">The Process</h2>
             <h5 class="description">
              After <a href="https://devpost.com/software/saferides-t7hqnf" target=_blank>Hack For Humanity 2020</a>, 
              I decided to pitch the 'dangerous roads' project to my CS professor. He liked the idea and we started
              a research project as part of 
              <a href="https://www.scu.edu/engineering/faculty/shaghaghi-navid/epic-lab/" target="_blank">Epic labs</a> 
              with the intention of spreading awareness about traffic fatalities and the technologies that can help mitigate them. 
              Being passionate about the project, one way we thought to improve visibility on this issue was to write an academic
              research paper. This process ran parallel to the work on <a href="#/Panterix">PANTERIX</a>, and consisted of things like the methodology
              behind our algorithm, product ideas, and findings regarding the types of roads that are most dangerous. 
              <br>
              <br>
              Together we co-authored and published the research paper by submitting it to the 
              <a href="https://goodtechs.eai-conferences.org/2020/" target="_blank">Goodtechs Tech Conference</a>. 
              The team elected myself and another to present our project - check it out!  
              <br><br>
            </h5>
            <center>
              <div class="video-wrap">
                <div class="video-container">
                  <iframe
                    src="https://www.youtube.com/embed/d4Ib1GSBP0E"
                  ></iframe>
                </div>
              </div>
            </center>
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
