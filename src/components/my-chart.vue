<template>
  <div>
    <PureVueChart  v-bind="$attrs"
    ></PureVueChart>
  </div>
</template>

<script>
  import PureVueChart from 'pure-vue-chart';

  export default {
    name: "my-chart",
    components: {
      PureVueChart
    },
    data() {
      return {

      }
    }
  }
</script>
