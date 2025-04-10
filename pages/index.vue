<template>
    <header class="bg-black">
        <div class="mx-auto flex h-20 items-center gap-8 px-8">
            <nuxt-link to="/" class="p-2 font-mono font-extrabold drop-shadow-lg text-4xl tracking-widest text-center text-green-400 uppercase lg:p-2 blur-none w-[215px]">
                <img src="assets/images/logo-light.png">
            </nuxt-link>

            <div class="flex flex-1 items-center justify-between">
                <nav>
                    <ul class="flex items-center gap-12 text-md">
                        <li><nuxt-link class="text-green-300/80 hover:text-green-300" to="/">SaaS</nuxt-link></li>
                        <li><nuxt-link class="text-green-300/80 hover:text-green-300" to="/">EMS</nuxt-link></li>
                        <li><nuxt-link class="text-green-300/80 hover:text-green-300" to="/">DMM</nuxt-link></li>
                        <li><nuxt-link class="text-green-300/80 hover:text-green-300" to="/">CMS</nuxt-link></li>
                    </ul>
                </nav>
                <div class="flex items-center gap-4">
                    <nuxt-link class="block rounded-md cursor-pointer bg-green-400/50 px-5 py-2.5 text-sm font-medium text-white transition hover:shadow-green-400/20 shadow-md duration-300 hover:bg-green-400/70" to="/contact">Contact Us</nuxt-link>
                </div>
            </div>
        </div>
    </header>
</template>

<script setup>

</script>

<style scoped>

</style>