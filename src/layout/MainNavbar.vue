<template>
  <navbar
    position="fixed"
    type="primary"
    :transparent="transparent"
    :color-on-scroll="colorOnScroll"
    menu-classes="ml-auto"
  >
    <template>
      <router-link v-popover:popover1 class="navbar-brand" to="/">
        <b>Home</b>
      </router-link>
    </template>
    <!-- <template>
      <b class="text-center">Stephen's Site</b>
    </template> -->
    <template slot="navbar-menu">
      <drop-down
              tag="li"
              title="Pages"
              class="nav-item"
      >
        <nav-link to="/">
          Home
        </nav-link>
        <nav-link to="/Hackathon">
          Hackathon Projects
        </nav-link>
        <nav-link to="/Panterix">
          Panterix
        </nav-link>
        <nav-link to="/Career">
          Career Development
        </nav-link>
        <nav-link to="/Papers">
          Research Papers
        </nav-link>
        <nav-link to="/ACM">
          ACM Sites
        </nav-link>
        <nav-link to="/Internships">
          Patents
        </nav-link>
      </drop-down>
    </template>
  </navbar>
</template>

<script>
import { DropDown, Navbar, NavLink } from '@/components';
import { Popover } from 'element-ui';
export default {
  name: 'main-navbar',
  props: {
    transparent: Boolean,
    colorOnScroll: Number
  },
  components: {
    DropDown,
    Navbar,
    NavLink,
    [Popover.name]: Popover
  }
};
</script>

<style scoped></style>
