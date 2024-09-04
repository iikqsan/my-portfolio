<template>
    <Navbar />
    <section id="home" class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8">
        <div class="hero bg-base-200 min-h-screen">
            <div class="hero-content flex-col lg:flex-row">
                <div v-motion-pop :duration="1000" class="avatar">
                    <div class="w-64 rounded-full">
                        <img src="https://scontent.fbkk28-1.fna.fbcdn.net/v/t39.30808-6/333600927_112589845096028_5185621764913389071_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=a5f93a&_nc_ohc=5UySHGQDK3MQ7kNvgEt2QWK&_nc_ht=scontent.fbkk28-1.fna&oh=00_AYDC-q3Y2i9N9ab-Rq59NxaszWVM6RLYClnd2HrgqjizTQ&oe=66DB65B7" />
                    </div>
                </div>
                <div>
                    <h1 v-motion-slide-right :duration="1000" class="text-3xl font-bold">Hello, I'm SOMSAK.</h1>
                    <p v-motion-slide-bottom :duration="1000" class="py-1">
                        Newbie Developer.
                    </p>
                </div>
            </div>
        </div>
    </section>
    <section id="home" class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8">
        <div class="hero bg-base-200 min-h-screen">
            <div class="hero-content flex-col lg:flex-row">
                <motion is="p" preset="slideVisibleLeft" :duration="2000" class="avatar">
                    <div class="w-64 rounded-full">
                        <img src="https://scontent.fbkk28-1.fna.fbcdn.net/v/t39.30808-6/333600927_112589845096028_5185621764913389071_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=a5f93a&_nc_ohc=5UySHGQDK3MQ7kNvgEt2QWK&_nc_ht=scontent.fbkk28-1.fna&oh=00_AYDC-q3Y2i9N9ab-Rq59NxaszWVM6RLYClnd2HrgqjizTQ&oe=66DB65B7" />
                    </div>
                </motion>
                <motion is="p" preset="slideVisibleRight" :duration="2000">
                    <h1 class="text-3xl font-bold">I'm a CAT.</h1>
                    <p class="py-1">
                        and i like to Scream "MEOW" every Time!!
                    </p>
                </motion>
            </div>
        </div>
    </section>
    <Footer />
</template>

<script setup>
import Navbar from '../components/Navbar.vue'
import Footer from '../components/Footer.vue'
</script>

<style></style>