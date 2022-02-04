<template>
  <div class='flex justify-center gap-5'>
    <a href='http://192.168.0.103:8000/auth/redirect?provider=google' :class='googleLinkClass'><i class="fab fa-google"></i></a>
    <a href='http://192.168.0.103:8000/auth/redirect?provider=linkedin' :class='linkedinLinkClass'><i class="fab fa-linkedin"></i></a>
    <a href='http://192.168.0.103:8000/auth/redirect?provider=github' :class='githubLinkClass'><i class="fab fa-github-square"></i></a>
  </div>
</template>

<script>
export default {
  name: 'SocialLoginLinks',
  data() {
    return {
      googleLinkClass: 'border-b-4 hover:border-red-400 text-3xl text-red-400 pt-0.5',
      linkedinLinkClass: 'border-b-4 hover:border-blue-500 text-4xl text-blue-500',
      githubLinkClass: 'border-b-4 hover:border-black text-4xl',
    }
  }
}
</script>

<style scoped>

</style>
