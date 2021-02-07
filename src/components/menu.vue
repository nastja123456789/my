<template>
  <div>
    {{data}}

  </div>
</template>

<script>
export default {
name: "menu",
  data() {
  return {
    data: [],
  pairs: {
    1: {
      "begin": "09:00",
      "end": "10:20"
    },
    2: {
      "begin": "10:20",
      "end": "11:50"
    },
    3: {
      "begin": "11:50",
      "end": "13:30"
    },
    4: {
      "begin": "13:30",
      "end": "15:00"
    },
    5: {
      "begin": "15:00",
      "end": "16:30"
    },
    6: {
      "begin": "16:30",
      "end": "18:00"
    },
    7: {
      "begin": "18:00",
      "end": "19:30"
    },
    8: {
      "begin": "19:30",
      "end": "21:00"
    }
  }

  }
  },
  /*mounted() {
    axios
        .get('https://api.hseapp.ru/gateway/ruz/rooms/2211')
        .then(response => (this.data = response))
  },*/
  }
</script>

<style>

</style>