<template>
  <div class="flex bg-[#0F1C2E] h-screen font-mitr">
    <div class="m-auto">
      <div
        class="p-9 bg-linear-65 from-[#1F3A5F] to-[#4d648d] rounded-lg shadow-2xl"
      >
        <h1 class="text-3xl text-center text-[#acc2ef] font-semibold mb-5">
          สมัครสมาชิก
        </h1>
        <p class="text-lg text-gray-600"></p>
        <div class="mt-3">
          <input
            class="text-sm custom-input w-full px-4 py-2 border border-gray-300 rounded-lg shadow-sm transition duration-300 ease-in-out transform focus:-translate-y-1 focus:outline-blue-300 hover:shadow-lg hover:border-blue-300 bg-gray-100"
            type="text"
            id="unique-input"
            placeholder="Username"
          />
        </div>
        <div class="mt-3">
          <input
            class="text-sm custom-input w-full px-4 py-2 border border-gray-300 rounded-lg shadow-sm transition duration-300 ease-in-out transform focus:-translate-y-1 focus:outline-blue-300 hover:shadow-lg hover:border-blue-300 bg-gray-100"
            type="password"
            id="unique-input"
            placeholder="Password"
          />
        </div>
        <div class="mt-3">
          <input
            v-models="asd"
            class="text-sm custom-input w-full px-4 py-2 border border-gray-300 rounded-lg shadow-sm transition duration-300 ease-in-out transform focus:-translate-y-1 focus:outline-blue-300 hover:shadow-lg hover:border-blue-300 bg-gray-100"
            type="password"
            id="unique-input"
            placeholder="Confirm Password"
          />
        </div>

        <div class="flex justify-center mt-5">
          <button
            class="flex-1 cursor-pointer transition-all bg-[#1f2b3e] text-white px-6 py-2 rounded-lg border-[#0F1C2E] border-b-[4px] hover:brightness-110 hover:-translate-y-[1px] hover:border-b-[6px] active:border-b-[2px] active:brightness-90 active:translate-y-[2px]"
          >
            สมัคร
          </button>
        </div>
        <div class="flex mt-3">
          <NuxtLink
            to="/login"
            class="ml-auto cursor-pointer text-[#FFFFFF] hover:text-[#acc2ef]"
            >มีบัญชีอยู่แล้ว?</NuxtLink
          >
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { NuxtLink } from '#components';
</script>

<style lang="scss" scoped></style>
