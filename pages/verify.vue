<template>
  <main>
    <nav class="flex justify-between py-6 px-4">
      <span class="font-bold text-2xl">Login/Register</span>
      <span>Logo here(Din Din)</span>
    </nav>
    <section class="flex justify-center">
      <section class="flex items-center space-y-4 flex-col w-full md:w-1/3 p-4">
        <p class="font-bold text-2xl">Enter OTP</p>
        <p class="text-gray-600 text-center">
          Please enter OTP we sent to your mobile number via SMS
        </p>
        <div class="flex w-full justify-between">
          <p>+65776788657</p>
          <button class="text-blue-400">Resend OTP</button>
        </div>
        <section class="flex h-10 space-x-3">
          <input class="verify-input" />
          <input class="verify-input" />
          <input class="verify-input" />
          <input class="verify-input" />
          <input class="verify-input" />
          <input class="verify-input" />
        </section>
        <button disabled class="btn-tube w-full">Next</button>
        <button>Go back</button>
      </section>
    </section>
  </main>
</template>
<script>
export default {
  components: {},
  setup() {},
}
</script>