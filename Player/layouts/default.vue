<template>
    <div class=" h-screen grid w-screen h-screen lg:w-screen grid-rows-[85%,15%] lg:grid-cols-[320px,auto] grid-cols-[60px,100%]">
        <aside class="bg-[#212121ff] text-[white] w-[60px]  grid  lg:w-80 grid-rows-[7%,10%,70%,10%]">      
            <div class="top grid grid-cols-[10%,90%]">
                <div class="logo ">55</div>
                <div class="hidden lg:block self-center pl-[20px]">
                    Media Player
                </div>
            </div>
            <div class="input grid">
                <input class="bg-[#272727ff] ml-7  hidden w-[250px] h-[35px] self-start lg:block" type="text" placeholder="Search">

            </div>
            <ul>
                <li class="grid grid-rows-5 h-[170px]">
                    <NuxtLink to="/" class="grid grid-cols-[10%,90%]">
                        <Icon icon="octicon:home-24" />
                        <div class="text hidden lg:block self-center">Home</div>
                    </NuxtLink>
                    <NuxtLink to="/library" class="grid grid-cols-[10%,90%] ">
                        <div class="icon">d</div>
                        <div class="text hidden  lg:block self-center">Library</div>
                    </NuxtLink>
                    <NuxtLink to="/videos" class="grid grid-cols-[10%,90%] border-b-2 border-[#272727ff]">
                        <div class="icon">d</div>
                        <div class="text hidden  lg:block self-center">Videos</div>
                    </NuxtLink>
                    <NuxtLink to="/queue" class="grid grid-cols-[10%,90%]">
                        <div class="icon">d</div>
                        <div class="text hidden  lg:block self-center">Queue</div>
                    </NuxtLink>
                    <NuxtLink to="/playlist" class="grid grid-cols-[10%,90%]">
                        <div class="icon">d</div>
                        <div class="text hidden  lg:block self-center">Playlist</div>
                    </NuxtLink>
                </li>
            </ul>
                <NuxtLink to="/settings" class="self-end hidden sm:hidden lg:block grid grid-cols-[20%,80%">
                    <div class="icon">d</div>
                    <div class="text">settings</div>
                </NuxtLink>
        </aside>
        <div class="contents col-start-2 col-end-3 bg-[#272727ff]">
        <slot/>
        </div>
        <div class="song-template w-screen border-t-[1px] border-[black] bg-[#272727ff] ">
            
        </div>
    </div>
</template>

<script setup lang="ts">
import { Icon } from '@iconify/vue'

</script>

<style scoped>
.text{
    padding-left: 28px;
}
.{
    display: grid;
    grid-template-columns: 20% , 80%;
}
</style>