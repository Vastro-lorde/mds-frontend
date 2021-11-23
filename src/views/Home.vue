<template>
    <img id="logo" alt="Mater Dei logo" src="../assets/logo.png">
    <HelloWorld msg="Mater Dei College"/>
    <div class="card text-center">
      <p class="card-header">School Anthem</p>
      <audio controls preload="metadata" loop>
          <source src="../assets/audio/mater.aac" type="audio/aac">
      </audio>
      <p class="card-body text-muted">Little king so fair and sweet
        see us gather round thy feet
        be the monarch of our school
        it shall prosper neath thy rule
        we will be the subject true
        brave to suffer brave to do
        all our heart to thee we bring
        take them keep them little king</p>
    </div>
    <div class="card text-center">
      <p class="card-header">School Pledge</p>
      <audio controls preload="metadata" loop>
          <source src="../assets/audio/mater.aac" type="audio/aac">
      </audio>
      <p class="card-body text-muted">Oh Mater Dei,
        my Queen, my mother
        I give myself entirely to thee
        and to show my devotion to thee
        I consecrate to thee this day
        My eyes, my ears, my mouth, my heart
        my whole being without reserve
        therefore good Mother
        as I'm thine, keep me
        guide me as thy property and possesion.
        Amen</p>
    </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
  
}
</script>
<style scoped>
  .card{
    margin: auto;
    text-align: justify;
    width: 40%;
  }
</style>