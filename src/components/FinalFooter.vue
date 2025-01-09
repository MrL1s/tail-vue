<template>
    <section class="flex flex-col gap-y-12 py-16">
        <div class="container max-w-screen-sm mx-auto">
            <h2 class="text-4xl font-bold text-center">Stay Update</h2>
            <p class="text-lg text-center text-gray-600 mt-2">Subscribe to our newsletter</p>
        </div>
        <div class="">
            <form class="flex justify-center gap-x-2">
                <input type="email" placeholder="Your email" class="px-6 py-2 border border-gray-300 rounded-lg shadow-sm focus:border-indigo-600">
                <button type="submit" class="px-6 py-2 font-semibold rounded-lg bg-indigo-600 text-white hover:bg-indigo-700">Subscribe</button>
            </form>
        </div>
    </section>
    <footer class="bg-indigo-900 pt-10 pb-8">
        <div class="container flex flex-col gap-y-8">
            <div class="flex ">
                <div class="mr-auto max-w-80">
                    <a href="#" class="flex items-center gap-x-2 ">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
                            stroke="currentColor" class="size-12 -rotate-6 text-white">
                        <path stroke-linecap="round" stroke-linejoin="round"
                            d="M17.25 6.75 22.5 12l-5.25 5.25m-10.5 0L1.5 12l5.25-5.25m7.5-3-4.5 16.5" />
                        </svg>
                        <span class="font-black text-white text-2xl">Code Editor</span>
                    </a>

                    <p class="text-indigo-200 mt-4">Unlock your potential VS Code</p>
                </div>
                <div class="flex gap-x-16">
                    <div class="flex flex-col gap-y-4">
                        <h3 class="font-semibold text-sm uppercase tracking-wider text-white">Popular Playlist</h3>
                        <ul class="flex flex-col gap-y-2">
                            <li class="">
                                <a href="#" class="text-indigo-200 hover:text-white">Prettier</a>
                            </li>
                            <li class="">
                                <a href="#" class="text-indigo-200 hover:text-white">Gitleens</a>
                            </li>
                            <li class="">
                                <a href="#" class="text-indigo-200 hover:text-white">Live Share</a>
                            </li>
                        </ul>
                    </div>
                    <div class="flex flex-col gap-y-4">
                        <h3 class="font-semibold text-sm uppercase tracking-wider text-white">Configurations</h3>
                        <ul class="flex flex-col gap-y-2">
                            <li class="">
                                <a href="#" class="text-indigo-200 hover:text-white">Setings</a>
                            </li>
                            <li class="">
                                <a href="#" class="text-indigo-200 hover:text-white">Keyboard</a>
                            </li>
                            <li class="">
                                <a href="#" class="text-indigo-200 hover:text-white">Code sneapets</a>
                            </li>
                        </ul>
                    </div>
                    <div class="flex flex-col gap-y-4">
                        <h3 class="font-semibold text-sm uppercase tracking-wider text-white">Social</h3>
                        <ul class="flex flex-col gap-y-2">
                            <li class="">
                                <a href="#" class="text-indigo-200 hover:text-white">YouTube</a>
                            </li>
                            <li class="">
                                <a href="#" class="text-indigo-200 hover:text-white">Telegram</a>
                            </li>
                            <li class="">
                                <a href="#" class="text-indigo-200 hover:text-white">GitHub</a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="border-t border-indigo-600 mt-4 pt-8 text-center text-sm text-indigo-200">
                &copy: 2025 Code Editor. All rights reserved
            </div>
        </div>
    </footer>
</template>