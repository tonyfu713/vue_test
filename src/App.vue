<script>
// import apple from ""
export default {
components:{

},
  data() {
    return{
      A:1,
      temp:666
    

    }
  },
  methods: {
    changeAValue(){
      this.A = this.temp;
    }
    
  },
  mounted(){

  }
}

</script>

<template>
  <h1>123123</h1>
  <div class="text-area">
    <h2>V-model</h2>
    <h2>V-on</h2>
    <h3>A:{{ A }}</h3>
    <p>temp:{{ temp }}</p>
    <input type="number" v-model="temp">
    <button type="button" v-on:click="changeAValue">update</button>

  </div>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
