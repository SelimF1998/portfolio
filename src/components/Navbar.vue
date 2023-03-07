<template lang="">
  <div>
    <nav class="text-2xl py-2">
      <div class="container mx-auto flex justify-between items-center">
        <div class="flex gap-6">
          <h1 class="cursor-pointer text-gray-500 font-bold">Work</h1>
          <h1 class="cursor-pointer text-gray-500 font-bold">About</h1>
        </div>
        <div class="">
          <div class="avatar flex justify-center">
            <div
              class="w-10 rounded-full ring ring-primary ring-offset-base-100 ring-offset-2"
            >
              <img src="/images/stock/photo-1534528741775-53994a69daeb.jpg" />
            </div>
          </div>
          <div>
            <h1 class="text-gray-700 font-extrabold text-center text-3xl">Jack Dempsy</h1>
          </div>
          <div>
            <h1 class="text-gray-500 font-bold text-center text-xl">Software Developer</h1>
          </div>
        </div>
        <div class="flex gap-6">
          <h1 class="cursor-pointer text-gray-500 font-bold">Contact</h1>
          <h1 class="cursor-pointer text-gray-500 font-bold">Resume</h1>
        </div>
      </div>
    </nav>
  </div>
</template>
<script>
export default {
  name: "Navbar",
  setup() {
    return {};
  },
};
</script>
<style lang=""></style>
