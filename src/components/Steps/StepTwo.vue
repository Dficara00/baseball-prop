<template>
  <div>
    <h1>
      <span>Next step is to cut and prepare the pipe insert and cap</span>
    </h1>
    <h1>
      <span>Cut a 2" length of 1/2" diameter copper pipe</span>
    </h1>
    <div class="pic">
      <img src="@/assets/pipecut.jpg" alt="" />
    </div>
    <h2><span>(Always wear face and eye protection when using cutoff saw)</span></h2>
    <div>
      <h1>
        <span
          >Cut a 1/2" diameter copper pipe cap in half and drill a hole for hex bolt to pass
          through</span
        >
      </h1>
    </div>
    <div>
      <h2>Start with 1/4" drill bit, then 3/8" bit, then finally 1/2" bit</h2>
    </div>
    <div class="pic">
      <img src="@/assets/cap1.jpg" alt="" />
      <img class="multipic" src="@/assets/cap2.jpg" alt="" />
      <img src="@/assets/cap3.jpg" alt="" />
    </div>
    <div>
      <h1>Epoxy the cut and drilled cap to an end of the 2" length of copper pipe</h1>
    </div>
    <div>
      <h2>Set pipe aside and move on to next step while epoxy cures</h2>
    </div>
    <div class="pic">
      <img src="@/assets/capF.jpg" alt="" />
    </div>
  </div>
</template>

<script>
export default {
  name: 'StepTwo',
};
</script>

<style>
h1 {
  display: flex;
  justify-content: center;
  align-items: center;
  font-style: normal;
  font-size: 28px;
  font-weight: 600;
  letter-spacing: 0em;
  font-family: Arial, Helvetica, sans-serif;
  padding: 5px;
  margin: 5px;
}
h2 {
  display: flex;
  justify-content: center;
  align-items: center;
  font-style: normal;
  font-size: 20px;
  font-weight: 600;
  letter-spacing: 0em;
  font-family: Arial, Helvetica, sans-serif;
}
.multipic {
  display: flex;
  justify-content: center;
  padding-left: 15px;
  padding-right: 15px;
}
</style>
