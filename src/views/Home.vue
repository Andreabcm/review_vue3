<template>
  <hello-world/>
  <hr/>
  <counter/>
  <hr/>
  <reactive-counter/>
</template>

<script>
import HelloWorld from "@/components/First_HelloWorld"
import Counter from "@/components/Second_SimpleCounter"
import ReactiveCounter from "@/components/Third_ReactiveCounter"

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Counter,
    ReactiveCounter,
  }
}
</script>

