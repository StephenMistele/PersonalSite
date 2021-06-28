<template>
  <div>
    <div class="page-header page-header-small">
      <parallax
        class="page-header-image"
        style="background-image: url('img/hackathonimg111.jpg')"
      >
      </parallax>
      <div class="content-center">
        <div class="container">
          <h1 class="title">Internships</h1>
          <div class="text-center">
            <a
              href="https://inrix.com/most-dangerous-roads/"
              class="btn btn-primary btn-round"
              target="_blank"
            >
              <b>Check out some of my work at INRIX</b>
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
            <h2 class="title">Full Stack Developer and PM</h2>
            <h5 class="description">
              When developing <a href="#/Panterix">PANTERIX</a>, we needed accident data to build our product. I managed to secure this by 
              building a partnership with <a href="" target="_blank">INRIX</a> to supply the data. While negotiating for this accident data,
              INRIX was so interested in our idea that they wanted to develop a similar danger product for themselves. We offered to build it, and
              they hired myself and the rest of PANTERIX as interns. At INRIX, I worked on everything from parsing through millions of 
              rows of data in an AWS RDS PostgreSQL DB - to developing the danger algorithm itself - to distributing this data through ASP DOTNET REST API's
              in C#.
              <br>
              <br>
              More recently I was given a return offer from INRIX to lead the next team of 15+ interns in continuing developing for 
              their various <a href="" target="_blank">SaaS modules</a> as a technical PM. I'm hoping to use this opportunity to 
              continue building my leadership skills and honing my coding abilities.
              <br>
              <br>
              In the past I've also interned for the Discovery Institute to build a mobile app in React Native and taught as a full-time instructor for 
              <a href="" target="_blank">Coding With Kids</a>.
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
