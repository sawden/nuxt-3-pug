<!--<template>-->
<!--  <button class="button"-->
<!--          :class="props.variant">-->
<!--    <slot/>-->
<!--  </button>-->
<!--</template>-->

<template lang="pug" src="./AppButton.pug"/>

<script setup lang="ts">
interface IProps {
  variant?: string;
}
const props = defineProps<IProps>();
</script>

<style src="./AppButton.scss" scoped/>