<template>
  <div class="home">
    <img class="homepageLogo" src ="https://www.iosicongallery.com/icons/weather-2017-06-19/512.png"/>
    <SearchBar/>
   
    <Weather/>
  </div>
</template>

<script>
import Weather from '@/components/Weather.vue'
import SearchBar from '@/components/SearchBar.vue'


export default {
  name: 'home',
  components: {
    Weather,
    SearchBar,
   
  },
  mounted(){
  }
}
</script>
<style scoped lang="scss">
.homepageLogo {
  padding-top: 2%;
  width: 10%;
}
</style>

