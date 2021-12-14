<template>
  <hello-world/>
  <hr/>
  <counter/>
</template>

<script>
import HelloWorld from "@/components/First_HelloWorld"
import Counter from "@/components/Second_SimpleCounter"

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Counter,
  }
}
</script>

