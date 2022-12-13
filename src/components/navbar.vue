<template>
    <!-- Navbar start -->
    <div class="flex max-w-screen justify-between py-2">
        <!-- LOGO -->
        <router-link to="/">
            <div class="absolute flex-row flex">
                <img class="h-10 my-5 ml-14" src="../components/assets/smk.png" alt="">
                <img class="h-20 my- ml-8" src="../components/assets/logoka.png" alt="">
            </div>
        </router-link>
        <!-- Left menu -->
        <ul class="flex flex-row gap-x-8 mr-14 my-6 text-lg font-semibold">
            <li class=" hover:text-[#56d5d0]">
                <RouterLink to="/programing">Programming</RouterLink>
            </li>
            <li class=" hover:text-[#56d5d0]">
                <RouterLink to="/3D">3D</RouterLink>
            </li>
            <li class=" hover:text-[#56d5d0]">
                <RouterLink to="/ilustrasi">Ilustrasi</RouterLink>
            </li>
            <li class=" hover:text-[#56d5d0]">
                <RouterLink to="/presentasi">Presentasi</RouterLink>
            </li>
            <li class=" hover:text-[#56d5d0]">
                <RouterLink to="/about">About</RouterLink>
            </li>
            <li class=" hover:text-[#56d5d0]">
                <RouterLink to="/gallery">Gallery</RouterLink>
            </li>
        </ul>
    </div>
    <!-- navbar end -->
</template>