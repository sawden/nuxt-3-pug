<!--<template>-->
<!--  <NuxtLink class="logo" to="/">-->
<!--    <img :style="{ maxWidth: props.maxWidth + 'px' }"-->
<!--         src="/img/logo.svg"-->
<!--         alt="Logo">-->
<!--  </NuxtLink>-->
<!--</template>-->

<template lang="pug" src="./AppLogo.pug"/>

<script setup lang="ts">
interface IProps {
  maxWidth: number;
}
const props = defineProps<IProps>();
</script>

<style src="./AppLogo.scss" scoped/>