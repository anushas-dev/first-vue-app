<template>
  <div class="about">
    <h1>ABOUT</h1>
    <p>This is a static about page.</p>
    <br />
  </div>
  <div class="left-content">
    <h1>LEFT</h1>
    <p>This is a left aligned component of the about section.</p>
    <br />
  </div>
  <div class="right-content">
    <h1>RIGHT</h1>
    <p>This is a right aligned component of the about section.</p>
    <br />
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 50vh;
    align-items: center;
  }
  .left-content {
    align-items: left;
  }
  .right-content {
    align-items: right;
  }
}
</style>
