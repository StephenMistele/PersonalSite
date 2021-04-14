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
              href="https://dl.acm.org/doi/abs/10.1145/3411170.3411269"
              class="btn btn-primary btn-round"
              target="_blank"
            >
              <b>But you can check out my research paper!</b>
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
