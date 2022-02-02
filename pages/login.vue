<template>
  <div class='h-screen flex justify-center items-center'>
    <div class='shadow-md border-2 rounded-md p-3'>
      <div class='font-black text-3xl text-center p-3'>
        Invatator
      </div>
      <div class='text-center p-3'>
        Let's start software engineering.
      </div>
      <div class='text-center mt-3 p-3'>
        Login With
      </div>
      <div class='flex justify-center gap-3'>
        <a href='http://127.0.0.1:8000/' class='text-2xl text-red-400 pt-0.5'><i class="fab fa-google"></i></a>
        <a href='http://127.0.0.1:8000/' class='text-2xl text-blue-500 pt-0.5'><i class="fab fa-facebook-f"></i></a>
        <a href='http://127.0.0.1:8000/' class='text-3xl'><i class="fab fa-github-square"></i></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'login'
}
</script>

<style scoped>
</style>
