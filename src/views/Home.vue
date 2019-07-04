<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <ProjectCard title="Titre Stylax" illustration="logo" summary="sommaire" ></ProjectCard>
    <ProjectCard title="PROJEEEEET" illustration="2euro" summary="Parceque c'est notre Projet!" ></ProjectCard>
    <ProjectCard title="Pac-man" illustration="yugi" summary="pac-man AI revolutionnary" ></ProjectCard>
  </div>
</template>

<script>
  // @ is an alias to /src
  import HelloWorld from '@/components/HelloWorld.vue'
  import ProjectCard from "@/components/ProjectCard";

  export default {
  name: 'home',
  components: {
    ProjectCard,
    HelloWorld
  }
}
</script>
