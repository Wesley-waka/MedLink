<template>
    <Navbar />

    <nav class="bg-custom-image bg-cover bg-center h-[620px] w-full text-white bg-transparent mycol  p-4">

        <!-- done -->

        <div class="flex items-center justify-center flex-grow pt-24">
            <div class="text-center px-4 md:px-8">
                <h1 class="text-2xl md:text-4xl font-bold mb-4">Contact Us</h1>
                <p class="text-base md:text-lg">Get to discover our products and services tailored just for you.</p>
            </div>
        </div>
    </nav>

    <div class="flex md:flex-row flex-col md:space-y-0 space-y-8 md:space-x-6 my-10 max-w-[800px] mx-auto items-center">
        <div
            class="flex flex-col my-auto bg-white border shadow-sm rounded-xl dark:bg-neutral-100 md:h-[400px] h-[300px] md:w-[500px] w-[250px] dark:border-neutral-300 dark:shadow-neutral-50/70">
            <div class="p-4 md:p-10  mx-auto my-auto">
                <div class="flex flex-col space-y-2 items-center">
                    <img src="/contact-us.svg" class="w-[80px] " alt="" srcset="">
                    <h3 class="text-[40px] font-bold text-gray-700 ">
                        Call us
                    </h3>
                </div>
                <p class="mt-2 text-gray-600 text-[20px] dark:text-neutral-400 text-center">
                    ++1(917) 6094-597
                </p>

            </div>
        </div>

        <div
            class="flex flex-col my-auto bg-white border shadow-sm rounded-xl dark:bg-neutral-100  md:h-[400px] h-[300px] md:w-[500px] w-[250px] dark:border-neutral-300 dark:shadow-neutral-50/70">
            <div class="p-4 md:p-10  mx-auto my-auto">
                <div class="flex flex-col space-y-2 items-center">
                    <img src="/location.svg" class="w-[80px] " alt="" srcset="">
                    <h3 class="text-[40px] font-bold text-gray-700 ">
                        Visit us
                    </h3>
                </div>
                <p class="mt-2 text-gray-600 text-[20px] dark:text-neutral-400 text-center">
                    USA, NewYork
                </p>

            </div>
        </div>

        <div
            class="flex flex-col my-auto bg-white border shadow-sm rounded-xl dark:bg-neutral-100  md:h-[400px] h-[300px] md:w-[500px] w-[250px] dark:border-neutral-300 dark:shadow-neutral-50/70">
            <div class="p-4 md:p-10  mx-auto my-auto">
                <div class="flex flex-col space-y-2 items-center">
                    <img src="/whatsapp.svg" class="w-[80px] " alt="" srcset="">
                    <h3 class="text-[40px] font-bold text-gray-700 ">
                        Text us
                    </h3>
                </div>
                <p class="mt-2 text-gray-600 text-[20px] dark:text-neutral-400 text-center">
                    +1(917) 6094-597
                </p>

            </div>
        </div>



    </div>


    <footer class="mycol text-white p-4 flex justify-center">
        <div class="container mx-auto flex flex-wrap flex-col md:flex-row justify-between items-center">
            <!-- Existing section: Footer text and links -->
            <div class="text-center md:text-left mb-4 md:mb-0">
                <p class="text-sm mb-2">&copy; 2024 Zemy-Group.com. All rights reserved.</p>
                <p class="text-sm">
                    <a href="#" class="hover:text-gray-400">Privacy Policy</a> |
                    <a href="#" class="hover:text-gray-400">Terms of Service</a>
                </p>
            </div>

            <!-- New section: Get in Touch -->
            <div class="text-center md:text-left mb-4 md:mb-0">
                <h4 class="text-lg font-semibold mb-2">Get in Touch</h4>
                <p class="text-sm mb-2">147 W 35th St, New York, NY 10001</p>
                <p class="text-sm mb-2">+1 (917) 6094-597</p>
                <p class="text-sm">
                    <a href="mailto:info@zemy-group.com" class="hover:text-gray-400">info@zemy-group.com</a>
                </p>
            </div>

            <!-- Existing section: Social Media Icons -->
            <div class="flex justify-center md:justify-end space-x-4">
                <a href="#" class="text-white hover:text-gray-400"><i class="fab fa-facebook-f"></i></a>
                <a href="#" class="text-white hover:text-gray-400"><i class="fab fa-twitter"></i></a>
                <a href="#" class="text-white hover:text-gray-400"><i class="fab fa-linkedin-in"></i></a>
                <a href="#" class="text-white hover:text-gray-400"><i class="fab fa-instagram"></i></a>
            </div>
        </div>
    </footer>
</template>


<script setup>
import Navbar from '~/layouts/navbar.vue'

</script>


<style >
.mybg {
    background-color: rgb(193, 216, 212);
}

.bg-custom-image {
    background-image: url('/about-2.jpg');
}

.mycol {
    background-color: rgb(158, 40, 41);
}
</style>