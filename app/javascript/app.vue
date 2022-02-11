<template>
  <div >
    <p>{{message}}</p>
  </div>
</template>

<script>
import { ref } from 'vue'
export default {
  name: 'HelloWorld',
    setup() {
        const message = ref('Психолог Екатеринбург')

        return {
          message
        }
    }
  // data() {
  //   return {
  //     mes: "ывмывмыв"
  //   }
  // }
}
</script>

<style scoped>
p {
  font-size: 1em;
  text-align: center;
}
</style>
