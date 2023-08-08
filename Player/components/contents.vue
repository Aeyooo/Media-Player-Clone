<template>
    <div class="hi w-full grid grid-rows-[20%,80%] lg:grid-rows-[100%]">
        <div class="media-play-cont lg:hidden">
            <div class="svg">

            </div>
            <div class="media-player">Media Player</div>            
        </div>
        <div class="real-stuff w-full grid justify-items-center h-full ">
            <div class="media-container grid w-[90%] mt-[20px] lg:mt-[35px] ">
                <div class="headings grid grid-cols-[30%,70%] lg:grid-cols-[20%,80%]">
                    <div class="section-title text-5xl">Music</div>
                    <div class="options grid justify-self-end gap-x-2.5 lg:justify-self-start lg:ml-[0px] grid-cols-[1fr,1fr,1fr]">
                        <div class="first self-center">Songs</div>
                        <div class="second self-center">Albums</div>
                        <div class="third self-center">Artists</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup lang="ts">

</script>

<style scoped>

</style>