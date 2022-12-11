<template>
  <div>
    <div class="w3-content w3-margin-top w3-max-width">
      <div class="w3-row-padding">
        <div class="w3-third">
          <SideBar/>
          <br />
        </div>
        <div class="w3-twothird">
          <ExperienceMain/>
          <EducationMain/>
        </div>
      </div>
    </div>
    <FootMain />
  </div>
</template>

<script>
import FootMain from "./components/FootMain.vue";
import SideBar from "./components/SideBar.vue";
import ExperienceMain from "./components/ExperienceMain.vue";
import EducationMain from "./components/EducationMain.vue";

export default {
  name: "App",
  components: {
    FootMain,
    SideBar,
    ExperienceMain,
    EducationMain
  },
};
</script>

<style>
html,
body,
h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Roboto", sans-serif;
}
.w3-max-width{
  max-width: 1400px
}
</style>
