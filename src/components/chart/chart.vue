<template>
  <div class="smt-myChart">
    <PureVueChart  v-bind="$attrs"
    ></PureVueChart>
  </div>
</template>

<script>
  import PureVueChart from 'pure-vue-chart';

  export default {
    name: "chart",
    components: {
      PureVueChart
    },
    data() {
      return {

      }
    },
    mounted(){
      console.log("my-chart");
    },
    props:{

    }

  }
</script>
