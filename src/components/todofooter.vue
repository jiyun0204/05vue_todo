<template>
  <div class="clearAllContainer">
    <span class="clearAllBtn" @click="$emit('clearTodo')">
      ClearAll
    </span>
  </div>
</template>

<script>
export default {

}
</script>

<style>

.clearAllContainer {
  width:8rem;
  height: 50px;
  line-height: 50px;
  background: #fff;
  border-radius:5px;
  margin: 0 auto;

}

.clearAllBtn {
    color:maroon;
    display: block;
}


</style>