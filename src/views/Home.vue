<template>
  <section class="home">
    <h2>Home!</h2>

  </section>
</template>

<style lang="scss">
  section {
    display: flex;
    flex-direction: column;
    // justify-content: center;
    align-items: center;
  }

  svg {
    width: 70vw;
    height: 70vh;
    // margin: auto;

    circle:first-child {
      fill: rgba(100, 255, 53, 0.5);
    }

    circle {
      fill: rgba(53, 56, 255, 0.2);

    }

    circle:last-child {
      fill: rgba(197, 146, 216, 0.7);
    }

  }
</style>

<script>

// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    // HelloWorld
  }
};
</script>
