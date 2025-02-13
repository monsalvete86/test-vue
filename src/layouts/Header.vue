<script setup>
    import { ref } from 'vue';

    let mobileNav = ref(false);
</script>

<template>
    <!-- Navbar Start -->
    <div class="container mx-auto px-5">
        <header class="flex justify-between py-12 items-center">
            <div class="uppercase bg-gray-200 text-black  shadow-md cursor-pointer">
              <a href="#download-section" v-smooth-scroll>Dealer Uploaded</a>
            </div>
            
            <nav class="flex justify-end flex-col md:flex-row">
                <!-- Desktop Menu -->
                <ul class="space-x-10 font-theme-heading font-medium items-center hidden md:flex  flex-col space-y-7 md:space-y-0 md:flex-row">                   
                    <li
                      class="uppercase hover:text-theme-secondary transition duration-200"
                    >
                      <span>Ask us about our special offers!</span>
                    </li>
                    <li class="uppercase bg-black px-6 py-2 text-white cursor-pointer border-2">
                        <a href="#download-section" v-smooth-scroll>Download</a>
                    </li>
                </ul>
            </nav>
        </header>        
    </div>
    <!-- Navbar End -->
</template>