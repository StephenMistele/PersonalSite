<template>
  <navbar
    position="fixed"
    type="primary"
    :transparent="transparent"
    :color-on-scroll="colorOnScroll"
    menu-classes="ml-auto"
  >
    <template>
      <!-- <li class="nav-item">
        <a
          class="nav-link"
          href="#/"
        >
          <p>Stephen's Site</p>
        </a>
      </li> -->
      <router-link v-popover:popover1 class="navbar-brand" to="/">
        Stephen's Site
      </router-link>
    </template>
    
    <template slot="navbar-menu">
      <li class="nav-item">
        <a
          class="nav-link"
          href="#/Hackathon"
        >
          <i class="now-ui-icons arrows-1_cloud-download-93"></i>
          <p>Hackathons</p>
        </a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          href="#/Panterix"
        >
          <i class="now-ui-icons arrows-1_cloud-download-93"></i>
          <p>PANTERIX</p>
        </a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          href="#/Career"
        >
          <i class="now-ui-icons arrows-1_cloud-download-93"></i>
          <p>Career Development</p>
        </a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          href="#/Papers"
        >
          <i class="now-ui-icons arrows-1_cloud-download-93"></i>
          <p>Papers</p>
        </a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          href="#/ACM"
        >
          <i class="now-ui-icons arrows-1_cloud-download-93"></i>
          <p>ACM Sites</p>
        </a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          href="#/Internships"
        >
          <i class="now-ui-icons arrows-1_cloud-download-93"></i>
          <p>Internships</p>
        </a>
      </li>
    </template>
  </navbar>
</template>

<script src="https://kit.fontawesome.com/517c44607b.js" crossorigin="anonymous"></script>
<script>
import { Navbar } from '@/components';
import { Popover } from 'element-ui';
export default {
  name: 'main-navbar',
  props: {
    transparent: Boolean,
    colorOnScroll: Number
  },
  components: {
    Navbar,
    [Popover.name]: Popover
  }
};
</script>

<style scoped></style>