<template>
  <div id="app">
    <TwentyTwenty style="width: 700px"
      before="https://tom.imgix.net/conejos1.jpeg?w=700&h=500&fit=crop&auto=format%2Ccompress"
      after="https://tom.imgix.net/PXL_20210526_200459056.MP.jpg?w=700&h=500&fit=crop&auto=format%2Ccompress" 
    />
    <TwentyTwenty style="width: 700px"
      before="https://tom.imgix.net/conejos2.jpeg?w=700&h=500&fit=crop&auto=format%2Ccompress"
      after="https://tom.imgix.net/PXL_20210526_200526187.MP.jpg?w=700&h=500&fit=crop&auto=format%2Ccompress" 
    />
    <TwentyTwenty style="width: 700px"
      before="https://tom.imgix.net/conejos3.jpeg?w=700&h=500&fit=crop&auto=format%2Ccompress"
      after="https://tom.imgix.net/PXL_20210526_200551174.MP.jpg?w=700&h=500&fit=crop&auto=format%2Ccompress" 
    />
    <TwentyTwenty style="width: 700px"
      before="https://tom.imgix.net/conejos4.jpeg?w=700&h=500&fit=crop&auto=format%2Ccompress"
      after="https://tom.imgix.net/PXL_20210526_200635299.MP.jpg?w=700&h=500&fit=crop&auto=format%2Ccompress" 
    />
    <TwentyTwenty style="width: 700px"
      before="https://tom.imgix.net/conejos4.jpg?w=700&h=500&fit=crop&auto=format%2Ccompress"
      after="https://tom.imgix.net/PXL_20210526_200728636.MP.jpg?w=700&h=500&fit=crop&auto=format%2Ccompress" 
    />
    <TwentyTwenty style="width: 700px"
      before="https://tom.imgix.net/conejos6.jpg?w=700&h=500&fit=crop&auto=format%2Ccompress"
      after="https://tom.imgix.net/PXL_20210526_200750835.MP.jpg?w=700&h=500&fit=crop&auto=format%2Ccompress" 
    />
    <TwentyTwenty style="width: 700px"
      before="https://tom.imgix.net/conejos7.jpeg?w=700&h=500&fit=crop&auto=format%2Ccompress"
      after="https://tom.imgix.net/PXL_20210526_200837716.MP.jpg?w=700&h=500&fit=crop&auto=format%2Ccompress" 
    />
    <TwentyTwenty style="width: 700px"
      before="https://tom.imgix.net/conejos8.jpeg?w=700&h=500&fit=crop&auto=format%2Ccompress"
      after="https://tom.imgix.net/PXL_20210526_200923302.MP.jpg?w=700&h=500&fit=crop&auto=format%2Ccompress" 
    />
    <TwentyTwenty style="width: 700px"
      before="https://tom.imgix.net/conejos10.jpeg?w=700&h=500&fit=crop&auto=format%2Ccompress"
      after="https://tom.imgix.net/PXL_20210526_201024267.MP.jpg?w=700&h=500&fit=crop&auto=format%2Ccompress" 
    />
    <TwentyTwenty style="width: 700px"
      before="https://tom.imgix.net/conejos11.jpeg?w=700&h=500&fit=crop&auto=format%2Ccompress"
      after="https://tom.imgix.net/PXL_20210526_201048367.MP.jpg?w=700&h=500&fit=crop&auto=format%2Ccompress" 
    />
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue';
import 'vue-twentytwenty/dist/vue-twentytwenty.css';
import TwentyTwenty from 'vue-twentytwenty';

export default {
  name: 'App',
  components: {
    TwentyTwenty
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  grid-template-columns: repeat(1,minmax(0,1fr));
  grid-gap: 1rem;
  gap: 1rem;
  
  display: grid;
}

@media (min-width: 1470px) {
  #app {
    grid-template-columns: repeat(2,minmax(0,1fr));
  }
}

</style>
