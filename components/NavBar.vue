<template>
    <header class="flex items-center">
        <div style="height: 54px" class="pr-5">
            <img src="/logo.svg" alt="logo" class="h-full" />
        </div>
        <ul class="flex items-center">
            <li>
                <nuxt-link
                    class="hover:text-teal-500 px-4 py-3 text-lg text-white"
                    to="/"
                    >Home</nuxt-link
                >
            </li>
            <li>
                <a
                    class="hover:text-teal-500 px-4 py-3 text-lg text-white"
                    href="#"
                    >Project</a
                >
            </li>
            <li>
                <a
                    class="hover:text-teal-500 px-4 py-3 text-lg text-white"
                    href="#"
                    >Features</a
                >
            </li>
            <li>
                <a
                    class="hover:text-teal-500 px-4 py-3 text-lg text-white"
                    href="#"
                    >Success Stories</a
                >
            </li>
        </ul>
        <ul class="flex items-center mt-2 ml-auto">
            <li>
                <nuxt-link
                    to="/register"
                    class="
                        hover:bg-white hover:bg-opacity-25
                        inline-block
                        w-40
                        px-6
                        py-1
                        mr-4
                        text-lg
                        font-light
                        text-center text-white
                        bg-transparent
                        border border-white
                        rounded-full
                    "
                >
                    Sign Up
                </nuxt-link>
            </li>
            <li>
                <nuxt-link
                    to="/login"
                    class="
                        inline-block
                        bg-transparent
                        border-white border
                        hover:bg-white hover:bg-opacity-25
                        text-white
                        font-light
                        w-40
                        text-center
                        px-6
                        py-1
                        text-lg
                        rounded-full
                    "
                >
                    My Account
                </nuxt-link>
            </li>
        </ul>
    </header>
</template>
