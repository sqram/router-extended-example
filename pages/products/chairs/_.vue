<template>
  <div>    
    <h2>Chair type: <u>{{ id }}</u></h2>    

    <br><br> 

    Desired generated file would be, ie,  `/products/bench/index.html`
    <br> <br>

    Instead it's `/products/chairs/bench/index.html`
  </div>
</template>


<router>
  {
    path: '/products/:id',    
  }
</router>


<script>


export default {  
  asyncData({ params }) {    
    return { id: params.id}
  },

  data () {
    return {
      id: ''
    }
  }
}
</script>