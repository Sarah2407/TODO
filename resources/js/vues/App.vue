<template>
  <div class="container">
    <div class="heading">
      <h2 class="title">TODO LIST</h2>
      <add-item-form/>
    </div>
    <list-view/>
  </div>
</template>

<script>
import addItemForm from './addItemForm.vue'
import ListView from './ListView.vue'

export default {
  components: {addItemForm, ListView}
}
</script>

<style scoped>
  .container{
    width: 250px;
    margin: auto;
  }
  
  .heading{
    background: #e6e6e6;
    padding: 10px;
  }

  .title {
    text-align: center;
  }

</style>