<script setup>
defineProps({
  title: {
    type: String,
    required: true
  },
  description: {
    type: String,
    required: true
  },
  
})
</script>

<template>
  <div >
    <a href="#">{{ title }}</a>
    <span>{{ description }}</span>
  </div>
</template>

<style scoped>
div {
    width: 50%;
    align-items: flex-start;
    text-align: start;
    padding-bottom: 50px;
}
a {
    
    text-decoration: none;
    font-weight: 500;
    color: #2F568D;
}

</style>
