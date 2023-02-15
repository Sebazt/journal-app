<template>
  <div class="entry-container mb-3 pointer p-2">
    <!-- title -->

    <div class="entry-title d-flex">
      <span class="text-success fs-5 fw-bold">08</span>
      <span class="mx-1 fs-5">Febrero</span>
      <span class="mx-1 fs-5 fw-light">2023</span>
    </div>

    <div class="entry-description">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum, porro? Officiis dignissimos, soluta aperiam pariatur rerum aliquid id sapiente iusto quos, vel obcaecati excepturi consequuntur, unde nesciunt adipisci qui modi.
    </div>
  </div>
</template>

<style scoped>
  .entry-container{
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;
  }

  .entry-container:hover{
    background-color: rgba(128, 128, 128, 0.377);
    transition: 0.2s all ease-in;

  }

  .entry-description{
    font-size: 12px;
  }
</style>
