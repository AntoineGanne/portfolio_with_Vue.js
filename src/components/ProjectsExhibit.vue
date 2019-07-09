<template>
<div class="md-elevation-10 exhibit">
    <md-tabs>
        <md-tab id="tab-Java" md-label="Java" to="" exact>
            <ProjectCard title="Titre Stylax" illustration="logo" summary="sommaire" ></ProjectCard>
            <ProjectCard title="PROJEEEEET" illustration="2euro" summary="Parceque c'est notre Projet!" ></ProjectCard>
            <ProjectCard title="Pac-man" illustration="yugi" summary="pac-man AI revolutionnary" ></ProjectCard>
        </md-tab>
        <md-tab id="tab-pages" md-label="Pages" to="">
            <p>Unde provident nemo reiciendis officia, possimus repellendus. Facere dignissimos dicta quis rem. Aliquam aspernatur dolor atque nisi id deserunt laudantium quam repellat.</p>
            <ProjectCard title="Titre Stylax" illustration="logo" summary="sommaire" ></ProjectCard>
        </md-tab>

        <md-tab id="tab-posts" md-label="Posts" to="">
            Posts tab
            <p>Qui, voluptas repellat impedit ducimus earum at ad architecto consectetur perferendis aspernatur iste amet ex tempora animi, illum tenetur quae assumenda iusto.</p>
        </md-tab>

        <md-tab id="tab-favorites" md-label="Favorites" to="">
            Favorites tab
            <p>Maiores, dolorum. Beatae, optio tempore fuga odit aperiam velit, consequuntur magni inventore sapiente alias sequi odio qui harum dolorem sunt quasi corporis.</p>
        </md-tab>
    </md-tabs>
</div>
</template>

<script>
    import ProjectCard from "@/components/ProjectCard";

    export default {
        name: "ProjectsExhibit",
        components:{
            ProjectCard
        }
    }
</script>

<style scoped>
    md-tab{
        width: inherit;
    }

    .exhibit{
        width: 90%;
        display: block;
        margin-left: auto;
        margin-right: auto;
    }
</style>
