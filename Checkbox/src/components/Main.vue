<template>
  <div class="checkbox">
    <div class="checkbox-header"></div>
    <div class="checkbox-main">
      <div v-for="(data, index) in datas" :key="index" class="checkbox-main-div"></div>
    </div>
  </div>
</template>
<style scoped>
.checkbox {
  margin: 20px;
  width: 20vw;
  height: 30vw;
  background: whitesmoke;
}

.checkbox:hover {
  box-shadow: 0 2px 12px 0 rgba(0,0,0,.1);
}

.checkbox-header {
  width: 100%;
  height: 10%;
  border-bottom: 1px solid white;
}
</style>
<script>
export default {
  data () {
    return {
      data: [{}, {}, {}]
    }
  }
}
</script>
