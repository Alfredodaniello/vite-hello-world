<script>
    import AppTitle from 
    './AppTitle.vue';
    export default {
        name: 'AppHero',
        components: {
          AppTitle
        }
  }
</script>

<template>
    <container>
        <h1><AppTitle></AppTitle></h1>
        <div class="img_container">
            <img src="../assets/img/dusan.jpg" alt="">
        </div>
    </container>
    
</template>

<style scoped>
 container {
    text-align: center;
 }
</style>