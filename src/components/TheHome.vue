<template>
    <div>
        <TheNavbar />
        <span class="mx-2"></span>
        <div class="container mx-auto bg-white rounded-lg">
            <div
                class="w-full p-4 text-center bg-white border border-gray-200 rounded-lg shadow sm:p-8 dark:bg-gray-800 dark:border-gray-700">

                <h1
                    class="mb-4 text-4xl font-extrabold leading-none tracking-tight text-gray-900 md:text-5xl lg:text-6xl dark:text-white">
                    Let's grow together with <span class="text-green-400 dark:text-blue-500">DISPENDUKCAPIL</span></h1>
                <p class="text-lg font-normal text-gray-500 lg:text-xl dark:text-gray-400">Kami hadir berupaya dalam
                    membantu untuk mengatur data penduduk di wilayah Sidoarjo dan Surabaya secara cepat,efisien, dan mudah digunakan
                    oleh petugas dan karyawan.</p>

            </div>
        </div>
        <span class="mx-2"></span>
        <div class="container mx-auto bg-white rounded-lg">
            <div
                class="w-full p-4 text-center bg-white border border-gray-200 rounded-lg shadow sm:p-8 dark:bg-gray-800 dark:border-gray-700">
                <h5 class="mb-2 text-5xl font-extrabold text-gray-900 dark:text-white">MEET WITH OUR TEAM</h5>
                <p class="mb-5 text-base text-gray-500 sm:text-lg dark:text-gray-400">We are a group of young people as
                    the designers behind this web.</p>
                <div>
                    <div class="items-center justify-center space-y-4 sm:flex sm:space-y-0 sm:space-x-4">
                        <a href="#"
                            class="flex flex-col items-center bg-white border border-gray-200 rounded-lg shadow md:flex-row md:max-w-xl hover:bg-gray-100 dark:border-gray-700 dark:bg-gray-800 dark:hover:bg-gray-700">
                            <img class="object-cover w-full rounded-t-lg h-96 md:h-auto md:w-48 md:rounded-none md:rounded-l-lg"
                                src="../assets/angger.jpg" alt="">
                            <div class="flex flex-col justify-between p-4 leading-normal">
                                <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">ANGGER
                                    FAJAR WIRAYUDHA</h5>
                                <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Saya adalah Mahasiswa IT
                                    Telkom Surabaya jurusan Teknik Komputer Angkatan 2020. Didalam pengembangan Web ini
                                    saya bekerja dibagian Backend dan Frontend.</p>
                            </div>
                        </a>
                        <a href="#"
                            class="flex flex-col items-center bg-white border border-gray-200 rounded-lg shadow md:flex-row md:max-w-xl hover:bg-gray-100 dark:border-gray-700 dark:bg-gray-800 dark:hover:bg-gray-700">
                            <img class="object-cover w-full rounded-t-lg h-96 md:h-auto md:w-48 md:rounded-none md:rounded-l-lg"
                                src="../assets/alif.jpg" alt="">
                            <div class="flex flex-col justify-between p-4 leading-normal">
                                <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">ALIF
                                    ANDIKA AMIN</h5>
                                <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Saya adalah Mahasiswa IT
                                    Telkom Surabaya jurusan Teknik Komputer Angkatan 2020. Didalam pengembangan Web ini
                                    saya bekerja dibagian Frontend.</p>
                            </div>
                        </a>
                    </div>
                    <span class="mx-2"></span>
                    <div>
                        <div class="items-center justify-center space-y-4 sm:flex sm:space-y-0 sm:space-x-4">
                            <a href="#"
                                class="flex flex-col items-center bg-white border border-gray-200 rounded-lg shadow md:flex-row md:max-w-xl hover:bg-gray-100 dark:border-gray-700 dark:bg-gray-800 dark:hover:bg-gray-700">
                                <img class="object-cover w-full rounded-t-lg h-96 md:h-auto md:w-48 md:rounded-none md:rounded-l-lg"
                                    src="../assets/sirojul.jpg" alt="">
                                <div class="flex flex-col justify-between p-4 leading-normal">
                                    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
                                        MUHAMMAD SIROJUL MUNIR</h5>
                                    <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Saya adalah Mahasiswa
                                        IT Telkom Surabaya jurusan Teknik Komputer Angkatan 2020. Didalam pengembangan
                                        Web ini saya bekerja dibagian Frontend.</p>
                                </div>
                            </a>
                            <a href="#"
                                class="flex flex-col items-center bg-white border border-gray-200 rounded-lg shadow md:flex-row md:max-w-xl hover:bg-gray-100 dark:border-gray-700 dark:bg-gray-800 dark:hover:bg-gray-700">
                                <img class="object-cover w-full rounded-t-lg h-96 md:h-auto md:w-48 md:rounded-none md:rounded-l-lg"
                                    src="../assets/amoss.jpg" alt="">
                                <div class="flex flex-col justify-between p-4 leading-normal">
                                    <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">
                                        AMOS JOSEPH CHRISTIAN</h5>
                                    <p class="mb-3 font-normal text-gray-700 dark:text-gray-400">Saya adalah Mahasiswa
                                        IT Telkom Surabaya jurusan Teknik Komputer Angkatan 2021. Didalam pengembangan
                                        Web ini saya bekerja dibagian Backend.</p>
                                </div>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>


    </div>
</template>

<script>
import TheNavbar from './TheNavbar.vue';
export default {
    nama: "TheHome",
    components: {
        TheNavbar
    }
}
</script>