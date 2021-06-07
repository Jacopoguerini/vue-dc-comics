<template>
  <main>

      <div class="container">
          <h2>Content goes here</h2>
      </div>
      
  </main>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    @import '../style/variables.scss';

    main {
        height: 120px;
        background-color: $brandColor;
        position: relative;
    }

    h2 {
        color: white;
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
    }

</style>