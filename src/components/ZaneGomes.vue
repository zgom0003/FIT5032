<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
<h1 class="green">{{ msg }}</h1>
    <p>
      Hi, my name is <b>{{ msg }}</b>. As someone who uses reactjs, I find this
      very interesting...
    </p>
</template>
