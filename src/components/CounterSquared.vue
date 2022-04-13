<template>
  <div class="counter-squard">
    {{ $store.state.counter }}
    <sup>2</sup> =
     {{ $store.getters.counterSquared }}
    </div>
</template>

<script>
export default {

}
</script>

<style>

</style>