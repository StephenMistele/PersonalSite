<template>
  <div>
    <div class="page-header page-header-small">
      <parallax
        class="page-header-image"
        style="background-image: url('img/hackathonimg.jpg')"
      >
      </parallax>
      <div class="content-center">
        <div class="container">
          <h1 class="title">Hackathon Projects</h1>
        </div>
      </div>
    </div>
    <div class="section section-about-us">
      <div class="container">
        <div class="row">
          <div class="col-md-8 ml-auto mr-auto text-center">
            <h2 class="title">I LOVE Hackathons</h2>
            <button type="button" class="btn btn-round btn-primary"><!---->Hackathon 2021 Devpost<!----></button>
            <h5 class="description">
              Hack for Humanity 2021 was definitely a highlight of my Sophomore year
            </h5>
            <h5 class="description">
              Hack for Humanity 2020 was a real breakthrough for my coding confidence. It helped me learn real world skills, and it was my first time using 
              frontend languages and frameworks. The first project we came up with didn't <br/> Check out some of my projects!
              <!-- PANTERIX Founder&CEO. API+Backend Engineer. Published Author.
              Website Developer. Pantent Holder. Cloud Database Engineer.
              Teacher. Mobile App Developer. Project Manager. -->
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
