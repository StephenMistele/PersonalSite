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
            <h5 class="description">
              Hackathons are pretty much my favorite thing to do, and I could
              talk about them all day. Hack for Humanity 2021 was a highlight of
              my Sophomore year. Here was our pitch.
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
            <h5 class="description">
              <br />
              And here's a link to our devpost
            </h5>
            <a href="https://devpost.com/software/quick-bites">
              <button type="button" class="btn btn-round btn-primary btn-lg">
                <!---->Hackathon 2021 Devpost<!---->
              </button>
            </a>
            <br />
            <br />
            <h3 class="title">Hack for Humanity 2020</h3>
            <h5 class="description">
              Hack for Humanity 2020 was a real breakthrough for my coding
              confidence. It helped me learn real world skills, and it was my
              first time using frontend languages and frameworks. It definitely
              helps show how far I've come!
            </h5>
            <center>
              <div class="video-wrap">
                <div class="video-container">
                  <img
                    src="img/team.jpg"
                    alt="Thumbnail Image"
                    class="box img-fluid img-raised group"
                  />
                </div>
              </div>
            </center>
            <h5 class="description">
              <br />
              And of course, the devpost
            </h5>
            <a href="https://devpost.com/software/saferides-t7hqnf">
              <button type="button" class="btn btn-round btn-primary btn-lg">
                <!---->Hackathon 2020 Devpost<!---->
              </button>
            </a>
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
