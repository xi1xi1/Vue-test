<template>
  <div id="app">
    <!-- <h1 id="title">{{ message }}</h1> -->
    <!-- <test-button></test-button> -->
    <!-- <use-vue></use-vue> -->
    <!-- <question-vue></question-vue> -->
    <router-view></router-view>
  </div>
</template>

<script>
// import QuestionVue from "./views/elment/QuestionVue.vue";
// import TestButton from './views/elment/TestButton.vue';
// import UseVue from './views/elment/UseVue.vue';
export default {
  // components: { QuestionVue },
  data() {
    return {
      message: "hello vue",
      // num:1
    };
  },
  methods: {},
};
</script>

<style>
#title {
  color: red;
}
</style>
