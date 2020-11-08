<template>
  <div class="button-section">
    <button class="btn btn-primary" @click="$emit('klik-button')"> 
      {{titleBtn}}
    </button>
  </div>
</template>

<script>
export default {
  props: {
    titleBtn: {
      type: '',
      default: 'submit',
    }
  }
}
</script>

<style>
.btn {
  border-radius: 5px;
}
</style>