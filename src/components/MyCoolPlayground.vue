<template>
<div class="wrapper">
  <h2>Easy theming</h2>
  <SfAddToCart></SfAddToCart>
  <br />
  <h2>Customization with CSS Variables</h2>
  <SfAddToCart class="custom"></SfAddToCart>
  <br/>
  <!-- CUSTOMIZATION WITH SLOTS -->
  <h2>Customization with slots</h2>
  <SfAddToCart>
    <template #quantity-select-input>
      🔥
    </template>
  </SfAddToCart>

</div>
</template>

<script>
import { SfAddToCart } from "@storefront-ui/vue";

export default {
  name: 'App',
  components: {
    SfAddToCart
  }
}
</script>

<style lang="scss">
.custom {
    /* CUSTOMIZATION WITH CSS VARIABLES PER COMPONENT */
    --button-font-weight: 700;
    --button-font-family: 'Arial Narrow', sans-serif;
    --button-background: #c9192e;
    --button-width: 12rem;
    --input-color: #c9192e;
    --input-margin: 0 0.5rem;
}

.wrapper {
  max-width: 20rem;
  margin: 0 auto;
}

</style>
