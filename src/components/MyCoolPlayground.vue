<template>
<div class="wrapper">
  <h2>Customization with CSS Variables</h2>
  <SfAddToCart class="custom"></SfAddToCart>
  <br/>
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

<style>
.custom {
    /* CUSTOMIZATION WITH CSS VARIABLES PER COMPONENT */
    --button-font-weight: 700;
    --button-background: red;
    --button-width: 12rem;
    --input-margin: 0 0.5rem;
}

.wrapper {
  max-width: 20rem;
  margin: 0 auto;
}

</style>
