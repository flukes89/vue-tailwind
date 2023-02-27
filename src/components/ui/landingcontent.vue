<template>
   <div class="px-4 mx-auto max-w-8xl lg:px-4 lg:text-center mt-8">

      <h2
         class="mb-4 text-2xl font-bold tracking-tight text-gray-900 lg:font-extrabold lg:text-4xl lg:leading-snug dark:text-white lg:text-center 2xl:px-48">
         Tailwind CSS Components</h2>
      <p class="mb-10 text-lg font-normal text-gray-500 dark:text-gray-400 lg:text-center lg:text-xl lg:px-64 lg:mb-16">
         Explore the whole collection of over 54 open-source UI components and interactive elements built with the utility
         classes from Tailwind CSS and Flowbite.</p>


      <div class="grid grid-cols-1 gap-6 sm:grid-cols-2 xl:grid-cols-3">

         <a href="#"
            class="h-64 bg-white rounded-lg border border-gray-100 hover:border-white dark:border-gray-700 dark:hover:border-gray-600 hover:shadow-lg dark:hover:shadow-lg-light dark:bg-gray-900">
            <div
               class="bg-gray-50 dark:bg-gray-700 rounded-t-md py-2.5 px-5 flex justify-between items-center border-b border-gray-200 dark:border-gray-700">
               <span class="text-base font-medium text-gray-900 dark:text-white">Alerts</span>
               <span class="text-gray-500 dark:text-gray-400">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2"
                     stroke="currentColor" aria-hidden="true" class="w-5 h-5">
                     <path stroke-linecap="round" stroke-linejoin="round"
                        d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path>
                  </svg>
               </span>
            </div>
            <div class="flex justify-center items-center h-52">
               <div class="relative h-4/6  w-56">
                  <span
                     style="box-sizing: border-box; display: block; overflow: hidden; width: initial; height: initial; background: none; opacity: 1; border: 0px; margin: 0px; padding: 0px; position: absolute; inset: 0px;">

                     <img src="src/assets/images/alert.png">

                  </span>

               </div>

            </div>
         </a>


         <a href="#"
            class="h-64 bg-white rounded-lg border border-gray-100 hover:border-white dark:border-gray-700 dark:hover:border-gray-600 hover:shadow-lg dark:hover:shadow-lg-light dark:bg-gray-900">
            <div
               class="bg-gray-50 dark:bg-gray-700 rounded-t-md py-2.5 px-5 flex justify-between items-center border-b border-gray-200 dark:border-gray-700">
               <span class="text-base font-medium text-gray-900 dark:text-white">Accordion</span>
               <span class="text-gray-500 dark:text-gray-400">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2"
                     stroke="currentColor" aria-hidden="true" class="w-5 h-5">
                     <path stroke-linecap="round" stroke-linejoin="round"
                        d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path>
                  </svg>
               </span>
            </div>
            <div class="flex justify-center items-center h-52">
               <div class="relative h-4/6  w-56">
                  <span
                     style="box-sizing: border-box; display: block; overflow: hidden; width: initial; height: initial; background: none; opacity: 1; border: 0px; margin: 0px; padding: 0px; position: absolute; inset: 0px;">

                     <img src="src/assets/images/acc.png">

                  </span>

               </div>

            </div>
         </a>
         <a href="#"
            class="h-64 bg-white rounded-lg border border-gray-100 hover:border-white dark:border-gray-700 dark:hover:border-gray-600 hover:shadow-lg dark:hover:shadow-lg-light dark:bg-gray-900">
            <div
               class="bg-gray-50 dark:bg-gray-700 rounded-t-md py-2.5 px-5 flex justify-between items-center border-b border-gray-200 dark:border-gray-700">
               <span class="text-base font-medium text-gray-900 dark:text-white">Avatar</span>
               <span class="text-gray-500 dark:text-gray-400">
                  <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2"
                     stroke="currentColor" aria-hidden="true" class="w-5 h-5">
                     <path stroke-linecap="round" stroke-linejoin="round"
                        d="M10 6H6a2 2 0 00-2 2v10a2 2 0 002 2h10a2 2 0 002-2v-4M14 4h6m0 0v6m0-6L10 14"></path>
                  </svg>
               </span>
            </div>
            <div class="flex justify-center items-center h-52">
               <div class="relative h-4/6  w-56">
                  <span
                     style="box-sizing: border-box; display: block; overflow: hidden; width: initial; height: initial; background: none; opacity: 1; border: 0px; margin: 0px; padding: 0px; position: absolute; inset: 0px;">

                     <img src="src/assets/images/yuu.png">

                  </span>

               </div>

            </div>
         </a>

      </div>





   </div>


   <div class="px-4 mx-auto max-w-8xl lg:px-4 lg:text-center mt-8 py-16 bg-gray-50">

      <h2
         class="mb-4 text-4xl font-bold tracking-tight text-gray-900 md:font-extrabold lg:leading-none dark:text-white md:text-center lg:mb-7">
         Sign up for our newsletter</h2>
      <p class="mb-4 text-base text-gray-500 md:mb-6 dark:text-gray-400 md:text-center md:text-xl lg:px-20 xl:px-56">Do you
         want to get notified when a new component is added to Flowbite? Sign up for our newsletter and you will be among
         the first to find out about new features, components, versions, and tools.</p>

      <EnteryourEmail placeholder="Enter Your Email" @change="change" />

   </div></template>

<script>
import EnteryourEmail from '../fields/EnteryourEmail.vue';

export default {

   components: {
      EnteryourEmail
   },
   methods: {
        getData() {
            console.warn("value:", this.email, this.password);
        },
        change(e) {

            console.warn("changed", e);
        }
    },


}




</script>
