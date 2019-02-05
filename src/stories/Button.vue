<template>
  <button class="{ rounded: rounded }"><slot></slot></button>
</template>

<script>
export default {
	name: 'MyButton',
  props: {
    rounded: {
      type: Boolean,
      default: false
    }
  }
}
</script>

<style>
.rounded {
  border-radius: 5px;
}
</style>