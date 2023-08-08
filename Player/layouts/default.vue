<template>
    <div class=" h-screen grid w-screen h-screen grid-rows-[85%,15%] lg:grid-cols-[320px,auto] grid-cols-[60px,auto]">
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
                <li class="grid grid-rows-[1fr,1fr,1fr,1fr,1fr] mt-[40px] h-[200px]">
                    <NuxtLink to="/" class="grid grid-cols-[100%] place-items-center lg:grid-cols-[10%,90%]">
                        <div class="svg-container grid place-items-center rounded-md hover:bg-[#272727ff] w-[80%] h-[40px]">
                            <svg xmlns="http://www.w3.org/2000/svg"  class="" width="24" height="24" viewBox="0 0 24 24"><path fill="currentColor" d="M11.03 2.59a1.501 1.501 0 0 1 1.94 0l7.5 6.363a1.5 1.5 0 0 1 .53 1.144V19.5a1.5 1.5 0 0 1-1.5 1.5h-5.75a.75.75 0 0 1-.75-.75V14h-2v6.25a.75.75 0 0 1-.75.75H4.5A1.5 1.5 0 0 1 3 19.5v-9.403c0-.44.194-.859.53-1.144ZM12 3.734l-7.5 6.363V19.5h5v-6.25a.75.75 0 0 1 .75-.75h3.5a.75.75 0 0 1 .75.75v6.25h5v-9.403Z"/></svg>
                            
                        </div>
                        <div class="text hidden lg:block self-center">Home</div>
                    </NuxtLink>
                    <NuxtLink to="/library" class="grid grid-cols-[100%] place-items-center lg:grid-cols-[10%,90%] ">
                        <div class="svg-container grid place-items-center rounded-md hover:bg-[#272727ff] w-[80%] h-[40px]">
                            <svg xmlns="http://www.w3.org/2000/svg" class="justify-self-center" width="24" height="24" viewBox="0 0 24 24"><g fill="none" stroke="currentColor" stroke-linecap="round"><circle cx="6" cy="18" r="3" stroke-linejoin="round"/><path stroke-linejoin="round" d="M9 18V5"/><path d="M21 3L9 5m12 2L9 9"/><circle cx="18" cy="16" r="3" stroke-linejoin="round"/><path stroke-linejoin="round" d="M21 16V3"/></g></svg>

                        </div>
                        <div class="text hidden  lg:block self-center">Library</div>
                    </NuxtLink>
                    <NuxtLink to="/videos" class="grid grid-cols-[100%]  place-items-center lg:grid-cols-[10%,90%] border-b-2 border-[#272727ff]">
                        <div class="svg-container grid place-items-center rounded-md hover:bg-[#272727ff] w-[80%] h-[40px]">

                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><g fill="none" stroke="currentColor" stroke-linejoin="round"><path stroke-linecap="round" d="M7 21a2 2 0 0 1-2-2V3h9l5 5v11a2 2 0 0 1-2 2H7Z"/><path d="M13 3v6h6m-5 5.5l-3 1.732v-3.464l3 1.732Z"/></g></svg>
                        </div>
                        <div class="text hidden  lg:block self-center">Videos</div>
                    </NuxtLink>
                    <NuxtLink to="/queue" class="grid grid-cols-[100%] place-items-center lg:grid-cols-[10%,90%]">
                        <div class="svg-container grid place-items-center rounded-md hover:bg-[#272727ff] w-[80%] h-[40px]">
                            <svg xmlns="http://www.w3.org/2000/svg"  width="24" height="24" viewBox="0 0 256 256"><path fill="currentColor" d="M36 64a4 4 0 0 1 4-4h176a4 4 0 0 1 0 8H40a4 4 0 0 1-4-4Zm100 60H40a4 4 0 0 0 0 8h96a4 4 0 0 0 0-8Zm0 64H40a4 4 0 0 0 0 8h96a4 4 0 0 0 0-8Zm108-28a4 4 0 0 1-1.88 3.39l-64 40a4 4 0 0 1-2.12.61a4.06 4.06 0 0 1-1.94-.5A4 4 0 0 1 172 200v-80a4 4 0 0 1 6.12-3.39l64 40A4 4 0 0 1 244 160Zm-11.55 0L180 127.22v65.56Z"/></svg>

                        </div>
                        <div class="text hidden  lg:block self-center">Queue</div>
                    </NuxtLink>
                    <NuxtLink to="/playlist" class="grid grid-cols-[100%] place-items-center lg:grid-cols-[10%,90%]">
                        <div class="svg-container grid place-items-center rounded-md hover:bg-[#272727ff] w-[80%] h-[40px]">
                            <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 256 256"><path fill="currentColor" d="M36 64a4 4 0 0 1 4-4h176a4 4 0 0 1 0 8H40a4 4 0 0 1-4-4Zm4 68h120a4 4 0 0 0 0-8H40a4 4 0 0 0 0 8Zm72 56H40a4 4 0 0 0 0 8h72a4 4 0 0 0 0-8Zm131.83-62.85a4 4 0 0 1-5 2.68L204 117.38V192a28 28 0 1 1-8-19.57V112a4 4 0 0 1 5.15-3.83l40 12a4 4 0 0 1 2.68 4.98ZM196 192a20 20 0 1 0-20 20a20 20 0 0 0 20-20Z"/></svg>

                        </div>
                        <div class="text hidden  lg:block self-center">Playlist</div>
                    </NuxtLink>
                </li>
            </ul>
                <NuxtLink to="/settings" class="self-end grid grid-cols-[100%] place-items-center  lg:grid-cols-[10%,90%]">
                    <div class="svg-container grid place-items-center rounded-md hover:bg-[#272727ff] w-[80%] h-[40px]">
                        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path fill="currentColor" d="m19.59 15.5l-1.82-1.3c.3-1.08.32-2.25 0-3.42l1.82-1.28L18.14 7l-2.03.92c-.79-.8-1.79-1.42-2.96-1.71L12.95 4h-2.9l-.2 2.21c-1.17.29-2.17.91-2.96 1.71L4.86 7L3.41 9.5l1.82 1.28c-.32 1.17-.3 2.34 0 3.42l-1.82 1.3L4.86 18l2.03-.93c.79.79 1.79 1.39 2.96 1.7l.2 2.23h2.9l.2-2.23c1.17-.31 2.17-.91 2.96-1.7l2.03.93l1.45-2.5M13.5 3c.27 0 .5.2.5.46l.18 2.04c.76.28 1.44.69 2.05 1.18l1.85-.87c.23-.12.52-.04.66.19l2 3.5c.14.21.06.5-.16.65l-1.67 1.17c.13.8.12 1.59 0 2.36l1.67 1.17c.22.15.3.44.16.65l-2 3.5c-.14.21-.43.29-.66.17l-1.85-.86c-.61.49-1.29.89-2.05 1.19l-.18 2c0 .29-.23.5-.5.5h-4a.5.5 0 0 1-.5-.5l-.18-2c-.76-.3-1.44-.7-2.05-1.19l-1.85.86c-.23.12-.52.04-.66-.17l-2-3.5c-.14-.21-.06-.5.16-.65l1.67-1.17c-.12-.77-.13-1.56 0-2.36l-1.67-1.17c-.22-.15-.3-.44-.16-.65l2-3.5c.14-.23.43-.31.66-.19l1.85.87c.61-.49 1.29-.9 2.05-1.18L9 3.46c0-.26.23-.46.5-.46h4m-2 6a3.5 3.5 0 0 1 3.5 3.5a3.5 3.5 0 0 1-3.5 3.5A3.5 3.5 0 0 1 8 12.5A3.5 3.5 0 0 1 11.5 9m0 1A2.5 2.5 0 0 0 9 12.5a2.5 2.5 0 0 0 2.5 2.5a2.5 2.5 0 0 0 2.5-2.5a2.5 2.5 0 0 0-2.5-2.5Z"/></svg>

                    </div>
                    <div class="text hidden  lg:block self-center">settings</div>
                </NuxtLink>
        </aside>
        <div class="contents col-start-2 col-end-3 bg-[#272727ff]">
        <div class="slot bg-[#272727ff] text-[white]">
            <slot/>
        </div>
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