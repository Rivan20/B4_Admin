
<template>
  
 <div class="layer"></div>
<!-- ! Body -->
<a class="skip-link sr-only" href="#skip-target">Skip to content</a>
<div class="page-flex">
  <!-- ! Sidebar -->
  <SideBarAdmin/>
  <div class="main-wrapper">
    <!-- ! Main nav -->
    <NavbarCompVue/>

    <!-- ! Main -->
    <MainAdminVue/>
    <!-- ! Footer -->
    <FooterAdmin/>
  </div>
</div>
</template>

<script>
import NavbarCompVue from './components/NavbarComp.vue';
import SideBarAdmin from './components/SideBarAdmin.vue';
import FooterAdmin from './components/FooterAdmin.vue';
import MainAdminVue from './components/MainAdmin.vue';
export default {
  name: 'App',
  components: {
    NavbarCompVue,
    MainAdminVue,
    SideBarAdmin,
    FooterAdmin
  }
}
</script>