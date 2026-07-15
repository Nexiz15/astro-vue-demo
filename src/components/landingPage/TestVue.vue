<script setup lang="ts">
import {ref} from "vue";

const props = defineProps<{type: string}>()

const prop = `VUE "${props.type}"`
const counter = ref(0)

function increase() {
  counter.value++
}
</script>

<template>
  <div id="vue">
    <h1>Vue Component</h1>
    <p>{{ prop }}</p>
    <span>{{counter}}</span>
    <button @click="increase()">UP UP UP</button>
  </div>
</template>

<style>
  #vue {
    background: rgb(57 255 31 / 0.31);
  }
</style>
