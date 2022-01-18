<template>
  <div>
    <div>
      <h1>First step is to gather all required tools, safety gear, and project materials</h1>
      <div class="pic">
        <img src="@/assets/materials2.jpg" alt="" />
      </div>
      <div class="mats">
        <h3>
          <u>Materials</u>
        </h3>
        <ul>
          <li>1 Baseball</li>
          <li>1 Copper pipe - 1/2" diameter</li>
          <li>1 Copper pipe cap - 1/2" diameter</li>
          <li>1 Hex head bolt - 2" long - 1/2" diameter</li>
          <li>1 Spring - 1 3/4" long - 7/16" diameter</li>
          <li>Wire/Cotter Pin</li>
        </ul>
        <h3 class="mid">
          <u>Tools</u>
        </h3>
        <ul>
          <li>Drill</li>
          <li>Saw</li>
          <li>5/8" Forstner bit</li>
          <li>3/32" drill bit</li>
          <li>1/4" drill bit</li>
          <li>3/8" drill bit</li>
          <li>1/2" drill bit</li>
          <li>Epoxy</li>
        </ul>
        <h3>
          <u>Safety</u>
        </h3>
        <ul>
          <li>Faceshield</li>
          <li>Safety Glasses</li>
          <li>Gloves</li>
        </ul>
      </div>
      <div class="pic">
        <img src="@/assets/safety.jpg" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'StepOne',
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
}
.mats {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 12px;
}
.pic {
  display: flex;
  justify-content: center;
  padding: 5px;
}
</style>
