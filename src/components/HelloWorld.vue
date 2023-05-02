<script setup lang="ts">

const props = defineProps<{
  msg: string
}>()


function foo() {
  const props = 3

  return props
}
</script>

<script lang="ts">
export default {
  name: 'HelloWorld',
}
</script>

<template>
  <h1 class="greetings">
    Text
  </h1>
</template>
