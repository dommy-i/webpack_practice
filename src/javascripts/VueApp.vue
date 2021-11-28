<template>
  <p>{{ message }}</p>
</template>

<script>
export default {
  data:()=>{
    console.log('VUejs is Installed!');
    return{
      message:'Hey! this is Vue!'
    }
  }
}
</script>

<style scoped>
p{
  color:green;
}
</style>
