<template>
  <div class="login-background bg-cover bg-no-repeat bg-fixed">
    <div class="flex justify-center">
      <div
        class="w-11/12 p-10 bg-white rounded-lg shadow-xl mt-40 flex flex-col justify-center lg:flex-row"
      >
        <div class="flex flex-col justify-center px-10 lg:w-3/5 ">
          <label
            class="text-right text-2xs text-gray-700 my-4 mr-3"
            for="username"
            >نام کاربری</label
          >
          <input
            id="username"
            class="h-12 text-2xl border-2 px-2 text-right outline-none bg-indigo-100 border-indigo-300 rounded-lg text-gray-700 focus:border-indigo-400 focus:bg-indigo-500 focus:text-white"
            type="text"
          />

          <label
            class="text-right text-2xs text-gray-700 mt-8 my-4 mr-3"
            for="password"
            >رمز عبور
          </label>
          <input
            id="password"
            class="h-12 text-2xl border-2 px-2 text-right outline-none bg-indigo-100 border-indigo-300 rounded-lg text-gray-700 focus:border-indigo-400 focus:bg-indigo-500 focus:text-white"
            type="text"
          />

          <input
            class="bg-indigo-500 border-2 border-indigo-500 w-1/5 rounded-lg py-3 outline-none mt-10 text-white font-bold hover:bg-white hover:text-indigo-500"
            type="submit"
            value="ورود"
          />
        </div>

        <div class="pt-24 lg:order-first lg:h-auto">
          <img class="" src="/icons/5.svg" alt="" />
        </div>
      </div>
    </div>

    <div class="bottom-0 mt-24 text-gray-500">www.pooloshi.ir</div>
  </div>
</template>

<script>
import { defineComponent } from "vue";

export default defineComponent({});
</script>

<style></style>
