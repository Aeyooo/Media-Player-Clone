<template>
    <div class="hi w-full grid grid-rows-[20%,80%] lg:grid-rows-[100%]">
        <div class="media-play-cont lg:hidden">
            <div class="svg">

            </div>
            <div class="media-player">Media Player</div>            
        </div>
        <div class="real-stuff w-full grid justify-items-center h-full ">
            <div class="media-container grid w-[90%] mt-[20px] gap-y-5 lg:mt-[35px] grid-rows-[1fr,1fr]">
                <div class="headings grid grid-cols-[30%,70%] lg:grid-cols-[20%,80%]">
                    <div class="section-title text-5xl">Music</div>
                    <div class="options grid justify-self-end gap-x-2.5 lg:justify-self-start lg:ml-[0px] grid-cols-[1fr,1fr,1fr]">
                        <div class="first self-center">Songs</div>
                        <div class="second self-center">Albums</div>
                        <div class="third self-center">Artists</div>
                    </div>
                </div>
                <div class="second-container grid grid-cols-[1fr,1fr]">
                    <div class="btn-cont">
                        <button class="bg-[#E97931ff] w-[160px] hover:opacity-90 rounded-md h-[35px] pointer text-[black]">Shuffle and play</button>

                    </div>
                    <div class="sort-cont grid grid-cols-[1fr,1fr]">
                        <div class="first-one flex-box justify-self-end">
                            <div class="sore text-center self-center pointer rounded-md items-center hover:bg-[#323232ff] h-[40px] w-[130px] ">
                                Sort by:
                                <span style="color:#E97931ff">A - Z</span>
                            </div>

                        </div>
                        <div class="second justify-self-end items-center">
                            <div class="genre text-center pointer rounded-md hover:bg-[#323232ff] h-[40px] w-[130px]">
                                Genre: 
                                <span style="color:hsl(23, 81%, 55%)">All Genres</span>
    
                            </div>

                        </div>
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