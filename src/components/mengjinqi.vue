<template>
  <div>
    <h1>mengjinqilalllalalal{{a}}</h1>
    <button @click="add">jiay1</button>
  </div>
</template>

<script>
export default {
  data(){
    return{
      a:100
    }
  },
  methods:{
    add(){
      this.a++
    }
  }

}
</script>


<style>

</style>
