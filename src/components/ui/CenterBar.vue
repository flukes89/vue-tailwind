<template>
      <div class="w-3/5">
            <div class="border-b border-gray-200 border-solid ">
                <h1 class="inline-block mb-2 text-3xl font-extrabold tracking-tight text-gray-900 dark:text-white">Tailwind
                    CSS Input Field - Flowbite</h1>
                <p class="mb-4 text-lg text-gray-500 dark:text-gray-400">Get started with a collection of input fields built
                    with Tailwind CSS to start accepting data from the user based on multiple sizes, variants, and input
                    types</p>



            </div>

            <div class="my-2.5 pt-5">
                <p class="mb-4 text-base text-gray-500 dark:text-gray-400">The input field is an important part of the form
                    element that can be used to
                    create interactive controls to accept data from the user based on multiple input
                    types, such as text, email, number, password, URL, phone number, and more.</p>
                <p class="mb-4 text-base text-gray-500 dark:text-gray-400">The input field is an important part of the form
                    element that can be used to
                    create interactive controls to accept data from the user based on multiple input
                    types, such as text, email, number, password, URL, phone number, and more.</p>

                <h1 class="inline-block mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Input Field
                </h1>
                <p class="mb-4 text-base text-gray-500 dark:text-gray-400">Use this example as a generic form element which
                    includes multiple input fields types such as text, email, password, number, URL, and phone number and
                    use the grid layout to add multiple columns and rows.</p>




                <form class="border border-gray-200 border-solid rounded-xl p-2.5"> 
                    <div class="grid gap-6 mb-6 md:grid-cols-2">

                    </div>
                    <TextField placeholder="BCvvv" label="Email Address 1" @change="change" />

                    <PasswordField placeholder="........" label="Password" @change="change" />


                    <button type="button" v-on:click="getData()"
                        class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-lg text-sm w-full sm:w-auto px-5 py-2.5 text-center dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Submit</button>
                </form>






            </div>



        </div>
</template>



<script>
import TextField from '@/components/fields/TextField.vue';
import PasswordField from '@/components/fields/PasswordField.vue';

export default {
    
    data() {
        return {
            email: null,
            password: null
        }

    },
    components:{
        TextField,
        PasswordField
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