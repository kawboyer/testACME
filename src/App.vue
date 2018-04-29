<!--App.vue (Parent component)-->
<template>
    <div id="app">
        <navbar></navbar>
        <div class="container">
            <page-heading></page-heading>
            <staff-list></staff-list>
        </div>
    </div>
</template>

<script>
import PageHeading from "./PageHeading.vue";
import StaffList from "./StaffList.vue";
import Navbar from "./Navbar.vue";
export default {
  name: "app",
  components: { Navbar, PageHeading, StaffList } //Register other components
};
</script>

<style scoped>

</style>
