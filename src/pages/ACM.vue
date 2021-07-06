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
            <h2 class="title">ACM Leadership</h2>
             <h5 class="description">
              At Santa Clara University, ACM (the Association of Computing Machinery) is the largest club on campus. Its goal is to empower students to aquire practical 
              coding skills and industry knowledge to be able to succeed in the workplace. Naturally I found myself right at home in ACM, and soon decided to apply for a 
              leadership position. 
              <br><br>
              The position I applied for, webmaster, was responsible for the creation and maintenance of ACM's websites. I was chosen over 7 other applicants, and have enjoyed
              both the frontend development and the ability to teach others about programming in the years since.
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
