<template>
  <div id="app">
    <Header :currentTab="currentTab" @onChangeTab="setTab" />
    <TabsWrapper :currentTab="currentTab" />
  </div>
</template>

<script>
import Header from './components/Header.vue';
import TabsWrapper from './components/TabsWrapper.vue';

export default {
  name: 'App',
  components: {
    Header,
    TabsWrapper,
  },
  data() {
    return {
      currentTab: 'StepZero',
    };
  },
  methods: {
    setTab(newTab) {
      this.currentTab = newTab;
    },
  },
};
</script>

<style>
body {
  background-color: lightgray;
}
</style>
