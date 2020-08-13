<template>
  <div>Button示例</div>
  <h1>示例1</h1>
  <div>
    <button @click="onClick" @focus="" @mouseover="">你好</button>
  </div>
</template>
<script lang="ts">
import Button from "../lib/Button.vue";
export default {
  components: { Button },
  setup(){
    const onClick =  () => {
        
    }
    return {onClick}
  }
};
</script>