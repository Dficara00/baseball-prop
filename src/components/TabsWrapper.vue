<template>
  <div>
    <br />
    <component :is="currentTab"></component>
  </div>
</template>

<script>
import StepZero from './Steps/StepZero.vue';
import StepOne from './Steps/StepOne.vue';
import StepTwo from './Steps/StepTwo.vue';
import StepThree from './Steps/StepThree.vue';
import StepFour from './Steps/StepFour.vue';
import StepFive from './Steps/StepFive.vue';
import StepSix from './Steps/StepSix.vue';

export default {
  name: 'TabWrapper',
  components: {
    StepZero,
    StepOne,
    StepTwo,
    StepThree,
    StepFour,
    StepFive,
    StepSix,
  },
  data() {
    return {};
  },
  props: {
    currentTab: {
      type: String,
      required: true,
    },
  },
  methods: {},
};
</script>

<style></style>
