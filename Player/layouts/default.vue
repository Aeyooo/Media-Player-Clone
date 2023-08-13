<template>
    <div class=" h-screen grid w-screen h-screen grid-rows-[85%,15%] lg:grid-cols-[320px,auto] grid-cols-[60px,auto]">
        <Sidebar/>
        <div class="slot bg-[#272727ff] text-[white]">
            <slot/>
        </div>
        <div class="song-template w-screen border-t-[1px] border-[black] bg-[#272727ff] "></div>
    </div>
</template>

<script setup lang="ts">
import { Icon } from '@iconify/vue'

</script>

<style scoped>
.text{
    padding-left: 28px;
}
.slot{
    grid-column: 2 / 3;
}
.sss:active{
    background-color: red;
}
</style>