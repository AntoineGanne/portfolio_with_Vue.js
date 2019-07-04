<template>
    <div>
        <md-card>
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
        </md-card>
    </div>
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
            }
        }
    }
</script>

<style scoped>
    .md-card {
        width: 320px;
        margin: 4px;
        display: inline-block;
        vertical-align: top;
    }

    .md-card-enter-active {
        transition: all .3s ease-in-out;
    }

    .md-card-enter {
        transform: translateY(-10px);
        opacity: 10;
    }
</style>
