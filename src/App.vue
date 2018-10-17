<template>
  <div id="app">
    <b-card no-body>
      <b-tabs pills  vertical>
        <b-tab title="Tab 1" active>
          <img src="./assets/logo.png" >
        </b-tab>
        <b-tab title="Tab 2">
          Tab Contents 2
        </b-tab>
        <b-tab title="Tab 3">
          Tab Contents 3
        </b-tab>
      </b-tabs>
    </b-card>
    <router-view/>
  </div>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'

export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
