<template>
  <div class="dataview">
  </div>
</template>

<script>
export default {
  name: "DataView",
  data() {
    return {
      data: []
    }
  }
};
</script>

<style scoped>
.dataview {
  width: 100%;
  color: white;
  margin-left: 4px;
  height: 47%;
  overflow: auto;
  background: white;
}

</style>
