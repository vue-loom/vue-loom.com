<script setup>
    import {Head, Link} from '@inertiajs/vue3';

    defineProps({
        canLogin: Boolean,
        canRegister: Boolean,
        laravelVersion: String,
        phpVersion: String,
    });
</script>

<template>
    <Head title="Coming Soon"/>

    <div class="min-h-screen bg-gray-200">
        <div class="flex justify-center pt-14">
            <div class="relative">
                <img src="/vue-loom.png" width="300">

                <h1 class="font-bold text-center absolute -top-10 -left-3 -rotate-12 text-black rounded-xl p-2" style="background-color: #57B3F1;">Coming soon!</h1>
            </div>
        </div>

        <p class="mt-10 text-black leading-relaxed text-lg px-10">
            Crafted with Vue.js, Typescript, and Tailwind CSS, our component library seamlessly integrates with
            Vue applications. Offering reusable, responsive components, it empowers developers to build modern
            interfaces.
            <br>
            <br>
            With a focus on Vue's strengths, Typescript's benefits, and Tailwind's utility-first
            styling, the library ensures a flexible and consistent development experience.
        </p>
    </div>
</template>