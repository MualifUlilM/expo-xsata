<template>
    <!-- Logo start -->
    <div class=" flex justify-center items-center max-w-screen max-h-screen">
        <!-- logo -->
        <div class=" mt- ml-44 mr-20 grid grid-cols-2 gap-10">
            <img class=" h-60 mt-16 hover:scale-110 transition-all" src="./assets/smk.png" alt="expo">
            <img class=" h-96 hover:scale-110 transition-all" src="./assets/logoka.png" alt="expo">
        </div>
    </div>
    <!-- logo end -->
    <div class=" flex justify-center mt-20 ml-20 mr-20 mb-7">
        <p class=" font-semibold text-center">
            Web ini dibuat oleh jurusan coding Karir Anak. Website ini juga berisi karya-karya dari beberapa jurusan di
            karir anak seperti jurusan Illustrasi, Presentasi, 3 Dimensi, dan yang terakhir Programming (coding).
        </p>
    </div>
    <!-- start -->
    <div class="flex max-w-screen justify-center pb-14">
        <!-- menu -->
        <ul class="flex flex-row gap-x-40 m-14 text-2xl font-extrabold text-black">
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
        </ul>
    </div>
    <!-- end -->
    <!-- Team -->
    <div class="flex justify-center pb-16 pt-14">
        <p class=" text-4xl font-semibold">
            Our Team 
        </p>
    </div>
    <div class="flex justify-center ml-7 pb-12">
        <div class="grid grid-cols-3 gap-16 pb-10">
            <!-- orang 1 -->
            <div class="flex flex-row">
                <div class=" bg-gray-300 rounded-full w-16 h-16 overflow-hidden">
                    <img class="object-cover" src="" alt="">
                </div>
                <div class=" flex flex-col justify-center pl-3">
                    <p class=" font-semibold text-base">
                        Raihan/Frontend
                    </p>
                    <p class=" font-light">
                        @raihanatllh
                    </p>
                </div>
            </div>
            <!-- orang 2 -->
            <div class="flex flex-row">
                <div class=" bg-gray-300 rounded-full w-16 h-16 overflow-hidden">
                    <img class="object-cover" src="" alt="">
                </div>
                <div class=" flex flex-col justify-center pl-3">
                    <p class=" font-semibold text-base">
                        Hanif/Frontend
                    </p>
                    <p class=" font-light">
                        @hadanur17
                    </p>
                </div>
            </div>
            <!-- orang 3 -->
            <div class="flex flex-row">
                <div class=" bg-gray-300 rounded-full w-16 h-16 overflow-hidden">
                    <img class="object-cover" src="" alt="">
                </div>
                <div class=" flex flex-col justify-center pl-3">
                    <p class=" font-semibold text-base">
                        Erwin/Frontend
                    </p>
                    <p class=" font-light">
                        @erwin_setiyo_aji
                    </p>
                </div>
            </div>
            <!-- orang 4 -->
            <div class="flex flex-row">
                <div class=" bg-gray-300 rounded-full w-16 h-16 overflow-hidden">
                    <img class="object-cover" src="" alt="">
                </div>
                <div class=" flex flex-col justify-center pl-3">
                    <p class=" font-semibold text-base">
                        Bagas/Backend
                    </p>
                    <p class=" font-light">
                        @ba.gasss_
                    </p>
                </div>
            </div>
            <!-- orang 5 -->
            <div class="flex flex-row">
                <div class=" bg-gray-300 rounded-full w-16 h-16 overflow-hidden">
                    <img class="object-cover" src="" alt="">
                </div>
                <div class=" flex flex-col justify-center pl-3">
                    <p class=" font-semibold text-base">
                        Alan/Backend
                    </p>
                    <p class=" font-light">
                        @arimaa97
                    </p>
                </div>
            </div>
            <!-- orang 6 -->
            <div class="flex flex-row">
                <div class=" bg-gray-300 rounded-full w-16 h-16 overflow-hidden">
                    <img class="object-cover" src="" alt="">
                </div>
                <div class=" flex flex-col justify-center pl-3">
                    <p class=" font-semibold text-base">
                        Ridzwan/Frontend
                    </p>
                    <p class=" font-light">
                        @ridzwan_gh
                    </p>
                </div>
            </div>
            <!-- end orang -->
        </div>
    </div>
</template>