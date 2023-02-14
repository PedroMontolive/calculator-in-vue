<script setup>
import {onMounted, ref} from 'vue';

defineProps(['text', 'value', 'bggcolor']);
</script>

<template>
    <button v-if="bggcolor == 'gray'" class="gray" :value="value" >{{ text }}</button>
    <button v-if="bggcolor == 'dark-gray'" class="dark-gray" :value="value" >{{ text }}</button>
    <button v-if="bggcolor == 'orange'" class="orange" :value="value" >{{ text }}</button>
    <button v-if="bggcolor == 'dark-gray-zero'" class="dark-gray-zero" :value="value" >{{ text }}</button>
</template>

<style src="./style.scss" lang="scss" scoped/>