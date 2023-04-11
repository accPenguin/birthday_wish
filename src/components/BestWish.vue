<script lang="ts" setup>

withDefaults(defineProps<{
  name: string
  msg: string
  art: string
}>(), {
  name: 'my friend',
  msg: 'Happy Birthday!',
  art: 'Life advice: Donot rely on anyone, do what you want to do, cherish relationships between people, donot be afraid of embarrassment, start from imperfection, control imperfection, make unimportant things imperfect, and believe that you are fully prepared,think before you think,do dome execise on monday night',
})
</script>

<template>
   <meta charset="UTF-8">
  <div class="wish transition animate-slow animate-fadeIn" text="center">
    <h1 text="3xl" font="light" m="2">
      {{ name }}
    </h1>
    <h2 text="3xl" font="normal">
      {{ msg }}
    </h2>
    <h3 text="3xl" font="normal">
      {{ art }}
    </h3>
  </div>
</template>

<style lang="scss">
.wish{
  color: #8b6a60;
  font-family: "Lato", "Roboto" sans-serif;
}
</style>
