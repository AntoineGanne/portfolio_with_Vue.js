<template>

        <md-card :class="'md-elevation-'+elevation">
            <div @mouseover="elevation=15"
                 @mouseleave="elevation=2"
            >
                <md-card-media-cover md-solid>
                    <md-card-media md-ratio="4:3">
                        <img :src="require('@/assets/'+ illustration + '.png')" alt="Illustration pic">

                    </md-card-media>

                    <md-card-area>
                        <md-card-header>
                            <span class="md-title">{{title}}</span>
                            <span class="md-subhead">{{summary}}</span>
                        </md-card-header>
                    </md-card-area>

                </md-card-media-cover>
            </div>
        </md-card>

</template>

<script>
    export default {
        name: "ProjectCard",
        props: {
            title: String,
            illustration: String,
            summary: String
        },
        data() {
            return {
                elevation: 2
            }
        },
        methods: {
        }
    }
</script>

<style lang="scss" scoped>
    .md-card {
        width: 30%;
        margin: 4px;
        display: inline-block;
    }

    .md-card:hover{
        width: 31%;
    }


    .md-card-enter-active {
        transition: all .3s ease-in-out;
    }

    .md-card-enter {
        transform: translateY(-10px);
        opacity: 10;
    }
</style>
