<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p>
    <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
    </ul>


      <div class="md-layout md-gutter md-alignment-center">
          <div class="md-layout-item md-medium-size-33 md-small-size-50 md-xsmall-size-100">
              <span>Always Show</span>
          </div>

          <div class="md-layout-item md-medium-size-33 md-small-size-50 md-xsmall-size-100">
              <span>Always Show</span>
          </div>

          <div class="md-layout-item md-medium-size-33 md-small-size-50 md-xsmall-size-100">
              <span>Always Show</span>
          </div>

          <div class="md-layout-item md-medium-size-50 md-small-size-50 md-xsmall-hide">
              <span>Hide Xsmall</span>
          </div>

          <div class="md-layout-item md-medium-size-50 md-small-hide">
              <span>Hide Small</span>
          </div>

          <div class="md-layout-item md-medium-hide">
              <span>Hide Medium</span>
          </div>
      </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

@import "~vue-material/dist/theme/engine";
.md-layout-item {
    height: 40px;
    margin-top: 8px;
    margin-bottom: 8px;

    span {
        width: 100%;
        height: 100%;
        padding: 8px;
        display: block;
        background: md-get-palette-color(pink, 200);
    }
}
</style>
