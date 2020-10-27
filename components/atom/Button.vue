<template>
  <div class="container">
    <button class="btn btn-primary" @click="$emit('klik-button')"> 
      {{title}}
    </button>
  </div>
</template>

<script>
export default {
  props: {
    title: {
      type: '',
      default: 'submit',
    }
  }

}
</script>

<style>
  .btn {
    /* background-color: #4FA5BD; */
    border-radius: 10px;
  }
</style>