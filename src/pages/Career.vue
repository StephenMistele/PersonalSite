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
          <h1 class="title">This page is currently under maintinence</h1>
          <div class="text-center">
            <a
              href="https://webpages.scu.edu/ftp/smistele/"
              class="btn btn-primary btn-round"
              target="_blank"
            >
              <b>But you can visit my site!</b>
            </a>
          </div>
        </div>
      </div>
    </div>
    <div class="separator separator-primary"></div>
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
