<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <ProjectsExhibit></ProjectsExhibit>
  </div>
</template>

<script>
  // @ is an alias to /src
  import HelloWorld from '@/components/HelloWorld.vue'
  import ProjectsExhibit from "@/components/ProjectsExhibit";

  export default {
  name: 'home',
  components: {
    ProjectsExhibit,
    HelloWorld
  }
}
</script>
