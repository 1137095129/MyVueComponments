<template>
  <div id="app">
    <tableComponent>
      <tr slot="name"><td>测试1</td><td>测试2</td></tr>
      <tr slot="id"><td>测试1</td><td>测试2</td></tr>
    </tableComponent>
  </div>
</template>

<script>
import tableComponent from "./components/tableComponent"
export default {
  name: 'App',
  components:{
    tableComponent
  }
}
</script>

<style>

</style>
