<template>
<main>
    <nav class="flex justify-between py-6 px-4">
        <span class="font-bold text-2xl">Login/Register</span>
        <span>Logo here(Din Din)</span>
    </nav>
    <section class="flex justify-center">
        <section class="flex items-center space-y-4 flex-col w-full md:w-1/3 p-4">
            <p class="font-bold text-2xl">Enter your mobile number</p>
            <p class="text-gray-600 text-center">A one-time password (OTP) will be sent to your mobile number</p>
            <VuePhoneNumberInput class="shadow p-2 border-transparent w-10/12"/>
            
            <button class="btn-tube w-full">Next</button>
        </section>
    </section>
    
</main>
    
</template>
<script>
import VuePhoneNumberInput from "vue-phone-country-code";

export default {
    components : {
        VuePhoneNumberInput
    },
    setup() {
        
    },
}
</script>