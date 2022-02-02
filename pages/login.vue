<template>
  <div class='h-screen flex justify-center items-center'>
    <div class='shadow-md border-2 rounded-md p-3'>
      <div class='font-black text-3xl flex justify-center gap-1.5 p-3'>
        <img src='/favicon.ico' alt='' width='30' height='20'> Invatator
      </div>
      <div class='text-center text-gray-400 p-3'>Let's start software engineering.</div>
      <div class='text-center text-lg  mt-3 p-3'>Login With</div>

      <social-login-links />
    </div>
  </div>
</template>

<script>
import SocialLoginLinks from '../components/pages/login/SocialLoginLinks'
export default {
  name: 'login',
  components: { SocialLoginLinks },
  head: {
    title: 'Login'
  }
}
</script>

<style scoped>
</style>
