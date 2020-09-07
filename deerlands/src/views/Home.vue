<template>
  <div class="bg-purple-600 h-screen">
    <div class="bg-white h-24 shadow-sm flex items-center justify-between">
      <img class="h-24" src="icons/deer.svg" />
      <div
        class="mr-8 bg-purple-600 px-4 py-2 content-center rounded-lg text-gray-300"
      >
        <a href="/login" class="cursor-pointer hover:text-gray-500 ">ورود</a>
        |

        <a href="/register" class="cursor-pointer hover:text-gray-500 "
          >ثبت نام</a
        >
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Home"
});
</script>
