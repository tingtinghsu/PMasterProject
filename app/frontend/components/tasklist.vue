<template>
  <div :id="tasklist">
    <div class="task-item">
      <div class="task-name">task 1</div>
      <div class="task-person">Mei</div>
      <div class="task-status">done</div>
      <div class="task-timeline">0819-0829</div>
      <div class="task-text">reminder...</div>
    </div>
  </div>
</template>


<script>
export default {
  props: ["tasklist"],  
  data: {
    
  }
}
</script>


<style scoped>

</style>