<template>
  <div class="header">
    <header>
      <button
        class="button"
        :class="{ active: currentTab === 'StepZero' }"
        @click="onClickSubTab('StepZero')"
      >
        Home
      </button>
      <button
        class="button"
        :class="{ active: currentTab === 'StepOne' }"
        @click="onClickSubTab('StepOne')"
      >
        Step 1
      </button>
      <button
        class="button"
        :class="{ active: currentTab === 'StepTwo' }"
        @click="onClickSubTab('StepTwo')"
      >
        Step 2
      </button>
      <button
        class="button"
        :class="{ active: currentTab === 'StepThree' }"
        @click="onClickSubTab('StepThree')"
      >
        Step 3
      </button>
      <button
        class="button"
        :class="{ active: currentTab === 'StepFour' }"
        @click="onClickSubTab('StepFour')"
      >
        Step 4
      </button>
      <button
        class="button"
        :class="{ active: currentTab === 'StepFive' }"
        @click="onClickSubTab('StepFive')"
      >
        Step 5
      </button>
      <button
        class="button"
        :class="{ active: currentTab === 'StepSix' }"
        @click="onClickSubTab('StepSix')"
      >
        Step 6
      </button>
    </header>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    currentTab: {
      type: String,
      required: true,
    },
  },
  methods: {
    onClickSubTab(tabName) {
      this.$emit('onChangeTab', tabName);
    },
  },
};
</script>

<style>
button {
  color: black;
  background-color: lightgray;
  padding: 15px 40px;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 24px;
  border: 5px;
  font-weight: 600;
  letter-spacing: 0em;
  font-style: normal;
  margin-top: 5px;
}
button:hover {
  background-color: darkgray;
}

.active {
  transform: translateY(8px);
  /* background-color: darkgray; take out before 1st GH */
}
</style>
