

<template>
    <div class="mb-6 flex max-w-xl md:mx-auto">
        <div class="w-full" data-style="clean">
            <div class="relative h-full">
                <div class="absolute inset-y-0 left-0 flex items-center pl-4 pointer-events-none">
                    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true"
                        class="w-5 h-5 text-gray-500 dark:text-gray-400">
                        <path d="M2.003 5.884L10 9.882l7.997-3.998A2 2 0 0016 4H4a2 2 0 00-1.997 1.884z"></path>
                        <path d="M18 8.118l-8 4-8-4V14a2 2 0 002 2h12a2 2 0 002-2V8.118z"></path>
                    </svg>
                </div>
                <input type="email" id="member_email" name="email_address"
                    class="block w-full px-3 py-4 text-base text-gray-900 bg-white border border-gray-200 rounded-l-xl formkit-input focus:ring-blue-500 focus:border-blue-500 dark:bg-gray-700 dark:border-gray-600  dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                    :placeholder="placeholder" required @change="$event => $emit('change', $event)">
            </div>
        </div>
        <div>
            <input type="submit" data-element="submit" id="member_submit"
                class="formkit-submit formkit-submit w-full px-4 py-4 text-base font-medium text-center text-white bg-blue-600 border border-blue-600 cursor-pointer rounded-r-xl formkit-submit hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-600 focus:border-blue-600"
                value="Subscribe">
        </div>
    </div>
</template>
<script>
export default {
    props: ['placeholder'],
    emits: ['change'],
    data() {
        return {

        }
    },
}
</script>
