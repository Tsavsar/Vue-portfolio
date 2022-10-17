<script setup>
import { ref, computed } from "vue";
import aboutVue from "./routes/about.vue";
import uidesignVue from "./routes/uidesign.vue";
import uxresearchVue from "./routes/uxresearch.vue";
import frontendVue from "./routes/frontend.vue";
import experienceVue from "./routes/experience.vue";

const routes = {
  "/": aboutVue,
  "/uidesign": uidesignVue,
  "/uxresearch": uxresearchVue,
  "/frontend": frontendVue,
  "/experience": experienceVue
};

const currentPath = ref(window.location.hash);

window.addEventListener("hashchange", () => {
  currentPath.value = window.location.hash;
});

const currentView = computed(() => {
  return routes[currentPath.value.slice(1) || "/"] || NotFound;
});
const nav = ref(false);

function toggle() {
  nav.value = !nav.value;
}
</script>

<template>
  <div class="bar">
    <Transition name="slide-fade">
      <div class="tpbar" v-if="nav">
        <a href="#/">ABOUT</a>
        <a href="#/uidesign">UI DESIGN</a>
        <a href="#/uxresearch">UX RESEARCH</a>
        <a href="#/frontend">FRONT-END DEVELOPMENT</a>
        <a href="#/experience">EXPERIENCE</a>
      </div>
    </Transition>
  </div>

  <div class="but" @click="toggle()">
    <svg xmlns="http://www.w3.org/2000/svg" class="dots" viewBox="0 0 128 512">
      <!--! Font Awesome Pro 6.2.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
      <path
        d="M64 360c30.9 0 56 25.1 56 56s-25.1 56-56 56s-56-25.1-56-56s25.1-56 56-56zm0-160c30.9 0 56 25.1 56 56s-25.1 56-56 56s-56-25.1-56-56s25.1-56 56-56zM120 96c0 30.9-25.1 56-56 56S8 126.9 8 96S33.1 40 64 40s56 25.1 56 56z"
      />
    </svg>
  </div>
  <Transition name="slide-fade">
    <component :is="currentView" />
  </Transition>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&family=Lato:ital,wght@0,100;0,300;0,400;0,700;0,900;1,100;1,300;1,400;1,700;1,900&display=swap");

.bar {
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: row;
  gap: 10px;
  justify-content: space-around;
}

.row {
  display: flex;
  flex-direction: row;
}

/* .but{
  margin-top: 100%;
} */

.dots {
  width: 16px;
  height: 55px;
  bottom: 0;
}

a {
  color: inherit;
  text-decoration: none;
  margin-right: 30px;
}
.tpbar {
  font-family: "Lato";
  font-style: normal;
  font-weight: 800;
  font-size: 25px;
  line-height: 30px;
  color: #000000;
}

body {
  margin: 0;
  width: 100%;
  height: 100%;
  padding: 20px;
  z-index: 0;
}

.slide-fade-enter-active {
  transition: all 0.8s ease-out;
}

.slide-fade-leave-active {
  transition: all 0s cubic-bezier(1, 0.5, 0.8, 1);
}

.slide-fade-enter-from,
.slide-fade-leave-to {
  transform: translateX(20px);
  opacity: 0;
}
</style>
