<template>
  <div clas="text-center">
    <h2 class="text-3xl font-bold mt-4">{{ text }}</h2>
    <div class="text-2xl mt-4 mb-10">
        {{ timestamp }}
    </div>
  </div>
</template>

<script>
  import moment from 'moment';

  export default {
    name: 'DataTitle',
    props: ['text', 'dataDate'],
    computed: {
      timestamp() {
        return moment(this.dataDate).format('MMMM Do YYYY, h:mm:ss a')
      }
    }
  }
</script>