<template>
    <div class=jumbo>
        <img src="https://picsum.photos/600/400" alt="foto_random">
    </div>
</template>

<script>
export default {
  name: 'HeroJumbotron',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
    img{
        filter: drop-shadow(2px 4px 6px black);
        border-radius: 20px;
    }
</style>
    
