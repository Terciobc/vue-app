<template>
    <button :class="`px-3 ml-1 py-2 border self-center rounded-md border-none ${bgColor} hover:opacity-70`">
       <slot name="title"> {{ title }} </slot> 
    </button>
</template>

<script setup>
    const props = defineProps({
        title: String,
        bgColor: String,
    })
</script>