<template>
  <div>
    <div class="h-auto pb-5 bg-dark-1 md:px-[150px] sm:px-4">
      <div class="mb-[40px] pt-3">
        <button class="bg-btn-red px-3 py-2 rounded-sm text-white">logo</button>
      </div>
      <form>
        <div class="bg-dark-2 p-4 rounded-sm w-[100%]">
          <input
            type="text"
            placeholder="Search for characters"
            class="md:w-[92.7%] sm:w-[80%] h-[48px] rounded-sm bg-dark-3 outline-none text-white gap-4 mr-4 pl-4"
          />
          <button class="bg-btn-red md:w-[98px]  h-[48px] rounded-sm text-white">
            Search
          </button>
        </div>
      </form>
    </div>
    <div class="px-[150px] pt-[64px]">
      <slot />
    </div>
  </div>
</template>

<script setup lang="ts">
</script>

<style>
</style>