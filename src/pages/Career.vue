<template>
  <div>
    <div class="page-header page-header-small">
      <parallax
        class="page-header-image"
        style="background-image: url('img/1speech.png')"
      >
      </parallax>
      <div class="content-center">
        <div class="container">
          <h1 class="title">Career Development</h1>
          <div class="text-center">
            <a
              href="https://webpages.scu.edu/ftp/smistele/"
              class="btn btn-primary btn-round"
              target="_blank"
            >
              <b>Visit My Website</b>
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="separator separator-primary"></div>
    <div class="section section-about-us">
      <div class="container">
        <div class="row">
          <div class="col-md-8 ml-auto mr-auto text-center">
            <h2 class="title">A Passion for Teaching</h2>
            <h5 class="description">
              Starting in high school when I joined 'Coding With Kids', I've found a passion for sharing my techincal knowledge with others. 
              I spent years as a lead instructor teaching students of all ages how to code, and even started teaching some of my own
               programming camps independently during summers. Since then I've continued to pursue this passion through educating my fellow peers about 
               internship opportunities, resume tips, and personal projects. 
               <br>
               <br>
               This is what inspired me to make a 'Career Development' site that helps fellow students interested in computers find resources to 
               succeed in the workplace.
               <br>
               <br>
               Check out my Site!
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
