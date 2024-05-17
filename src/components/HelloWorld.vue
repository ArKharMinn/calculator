<template>
  <div>
    <div class="p-3 rounded shadow-sm bg-dark d-inline-block">
      <input type="" class="text-end p-2" v-model="inPut" placeholder="0" disabled/>
      <div class="my-3">
        <button class="rounded shadow-sm btn btn-secondary">7</button>
        <button class="rounded mx-3 shadow-sm btn btn-secondary">8</button>
        <button class="rounded shadow-sm btn btn-secondary">9</button>
        <button class="rounded ms-3 shadow-sm btn btn-secondary">+</button>
      </div>
      <div>
        <button class="rounded shadow-sm btn btn-secondary">4</button>
        <button class="rounded mx-3 shadow-sm btn btn-secondary">5</button>
        <button class="rounded shadow-sm btn btn-secondary">6</button>
        <button class="rounded ms-3 shadow-sm btn btn-secondary">-</button>
      </div>
      <div class="my-3">
        <button class="rounded shadow-sm btn btn-secondary">1</button>
        <button class="rounded mx-3 shadow-sm btn btn-secondary">2</button>
        <button class="rounded shadow-sm btn btn-secondary">3</button>
        <button class="rounded ms-3 shadow-sm btn btn-secondary">x</button>
      </div>
      <div>
        <button @click="clear()" class="rounded shadow-sm btn btn-danger">AC</button>
        <button class="rounded mx-2 shadow-sm btn btn-secondary">0</button>
        <button class="rounded shadow-sm btn btn-secondary">=</button>
        <button class="rounded ms-3 shadow-sm btn btn-secondary">/</button>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
    data () {
      return {
        inPut : 0
      }
    },
    methods: {
      clear () {
       this.inPut = 0;
      },
      operation(){
        
      }
    }
  }
</script>

<style lang="stylus" scoped>

</style>
