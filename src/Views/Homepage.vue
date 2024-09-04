<template>
    <Navbar />
    <section id="home" class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8">
        <div class="hero bg-base-200 min-h-screen">
            <div class="hero-content flex-col lg:flex-row">
                <div v-motion-pop :duration="1000" class="avatar">
                    <div class="w-64 rounded-full">
                        <img
                            src="https://scontent.fbkk28-1.fna.fbcdn.net/v/t39.30808-6/333600927_112589845096028_5185621764913389071_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=a5f93a&_nc_ohc=5UySHGQDK3MQ7kNvgEt2QWK&_nc_ht=scontent.fbkk28-1.fna&oh=00_AYDC-q3Y2i9N9ab-Rq59NxaszWVM6RLYClnd2HrgqjizTQ&oe=66DB65B7" />
                    </div>
                </div>
                <div>
                    <h1 v-motion-slide-right :duration="1000" class="text-3xl font-bold">Hello, I'm SOMSAK.</h1>
                    <p v-motion-slide-bottom :duration="1000" class="text-xl py-1">
                        Newbie Developer.
                    </p>
                </div>
            </div>
        </div>
        <!-- <hr> -->
    </section>
    <section id="about" class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8">
        <div class="hero bg-base-200 min-h-screen">
            <div class="hero-content">
                <div class="max-w-4xl">
                    <h1 class="text-3xl font-bold underline underline-offset-2">About me</h1>
                    <p class="text-xl py-6">
                        Now, I'm looking for a role as a Junior Developer to improve my skills and gain experience.<br>
                        Which I will apply to benefit the organization and I committed to giving my best effort in every
                        facet of the job.
                    </p>
                    <h1 class="text-3xl font-bold underline underline-offset-2">Education</h1>
                    <ul class="timeline timeline-snap-icon max-md:timeline-compact timeline-vertical">
                        <li>
                            <div class="timeline-middle">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor"
                                    class="h-5 w-5">
                                    <path fill-rule="evenodd"
                                        d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.857-9.809a.75.75 0 00-1.214-.882l-3.483 4.79-1.88-1.88a.75.75 0 10-1.06 1.061l2.5 2.5a.75.75 0 001.137-.089l4-5.5z"
                                        clip-rule="evenodd" />
                                </svg>
                            </div>
                            <div class="timeline-start mb-10 md:text-end">
                                <time class="font-mono italic">2017</time>
                                <div class="text-lg font-black">Ubonratchathani University</div>
                                Bachelor of Science (B.Sc.) Information Technology
                            </div>
                            <hr />
                        </li>
                        <li>
                            <hr />
                            <div class="timeline-middle">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor"
                                    class="h-5 w-5">
                                    <path fill-rule="evenodd"
                                        d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.857-9.809a.75.75 0 00-1.214-.882l-3.483 4.79-1.88-1.88a.75.75 0 10-1.06 1.061l2.5 2.5a.75.75 0 001.137-.089l4-5.5z"
                                        clip-rule="evenodd" />
                                </svg>
                            </div>
                            <div class="timeline-end mb-10">
                                <time class="font-mono italic">2007</time>
                                <div class="text-lg font-black">Sakaeo World Class Standard School</div>
                                Secondary Education (Science - Mathematics)
                            </div>
                            <hr />
                        </li>
                        <li>
                            <div class="timeline-middle">
                                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor"
                                    class="h-5 w-5">
                                    <path fill-rule="evenodd"
                                        d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.857-9.809a.75.75 0 00-1.214-.882l-3.483 4.79-1.88-1.88a.75.75 0 10-1.06 1.061l2.5 2.5a.75.75 0 001.137-.089l4-5.5z"
                                        clip-rule="evenodd" />
                                </svg>
                            </div>
                            <div class="timeline-start mb-10 md:text-end">
                                <time class="font-mono italic">2004</time>
                                <div class="text-lg font-black">Anubanwat Sakaeo School</div>
                                Primary Education
                            </div>
                        </li>
                    </ul>
                    <h1 class="text-3xl font-bold underline underline-offset-2">Employment</h1>
                    <p class="text-xl py-6">
                        <time class="text-sm">2017 - May 2024</time><br>
                        <span class="text-lg font-black">Datacenter Operation (Printing Support)</span><br>
                        <span class="text-lg font-black">DXC Technology | SCG Site Bangsue</span><br>
                    </p>
                </div>
            </div>
        </div>
        <!-- <hr> -->
    </section>
    <section id="project" class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8">
        <div class="hero bg-base-200 min-h-screen">
            <div class="hero-content">
                <div class="max-w-4xl">
                    <h1 class="text-3xl font-bold underline underline-offset-2 mb-4">My Project</h1>
                    <div class="hero-content flex-col lg:flex-row">
                        <img src="../assets/nrca.png" class="max-w-sm rounded-lg shadow-2xl" />
                        <div class="">
                            <time class="font-mono italic">June 2024</time>
                            <h1 class="text-3xl font-bold">NRCA Web Application</h1>
                            <p>(work in progress)</p>
                            <!-- <p class="py-6">
                                Provident cupiditate voluptatem et in. Quaerat fugiat ut assumenda excepturi
                                exercitationem
                                quasi. In deleniti eaque aut repudiandae et a id nisi.
                            </p> -->
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- <hr> -->
    </section>
    <section id="contact" class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8">
        <div class="hero bg-base-200 min-h-screen">
            <!-- <div class="hero-content flex-col lg:flex-row-reverse"> -->
                <div class="card bg-base-100 w-full max-w-xl shrink-0 shadow-2xl">
                    <form class="card-body">
                        <h1 class="text-3xl font-bold underline underline-offset-2">Contact me</h1>
                        <div class="form-control">
                            <label class="label">
                                <span class="label-text">Email</span>
                            </label>
                            <input type="email" class="input input-bordered" required />
                        </div>
                        <div class="form-control">
                            <label class="label">
                                <span class="label-text">Comment</span>
                            </label>
                            <textarea class="textarea textarea-bordered"></textarea>
                        </div>
                        <div class="form-control mt-6">
                            <button class="btn btn-primary">Send</button>
                        </div>
                    </form>
                </div>
            </div>
        <!-- </div> -->
    </section>
    <Footer />
</template>

<script setup>
import Navbar from '../components/Navbar.vue'
import Footer from '../components/Footer.vue'
</script>

<style scoped></style>