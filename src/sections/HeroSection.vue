<script setup></script>

<template>
    <!-- Hero Section Start -->
    <div class="container mx-auto px-5 overflow-x-hidden lg:overflow-x-visible">
        <section class="grid grid-cols-none lg:grid-cols-2 pb-16 pt-8 items-center">
            <div class="lg:w-5/6 order-2 lg:order-none">
              <section class="py-16">
                <h4 class="text-sm tracking-widest uppercase text-center text-white font-theme-heading">35,000+ Already Joined</h4>
                <h2 class="text-3xl md:text-4xl font-medium text-center text-white mt-9 mb-10 font-theme-heading">S</h2>

                <form>
                    <div class="relative flex flex-col items-center justify-center lg:space-x-3">
                        <div class="relative w-full lg:mb-0 font-theme-content">
                            <input class="w-full py-3 px-5 text-sm text-white-600 border-0 shadow-md rounded focus:ring-4 focus:ring-blue-300" type="text" name="newsletter_email" placeholder="Enter your email address" />
                        </div>        
                        <Button class="" type="submit" btn-type="primary">Submit</Button>                
                    </div>

                </form>
            </section>
            </div>
            <div class="relative order-1 lg:order-none mb-20 lg:mt-0 lg:mb-0 lg:-mr-10">
                <img class="z-10 w-full" src="/images/illustration-hero.svg" />
                <div class="-z-10 bg-theme-primary h-52 w-full sm:h-80 sm:w-full rounded-l-full absolute -right-28 md:-right-48 -bottom-8"></div>
            </div>
        </section>
    </div>
    <!-- Hero Section End -->
</template>
