<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import NavBar from "@/components/NavBar.vue";
import UserPhoto from "@/components/UserPhoto.vue";
import UserInfo from "@/components/UserInfo.vue";
</script>

<template>
  <NavBar/>

  <section class="flex w-4/5 mx-auto justify-center">
    <UserPhoto/>
    <UserInfo/>
  </section>
  <section class="flex w-4/5 mx-auto justify-center">
    <RouterView />
  </section>

</template>