<template>
  <q-layout view="hHh lpR fFf">

    <q-header bordered class="bg-black navbar text-white">
      <q-toolbar>
        <q-toolbar-title>
          <q-avatar>
            <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-white.svg">
          </q-avatar>
          Title
        </q-toolbar-title>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

  </q-layout>
</template>
 <script>
import { defineComponent } from "@vue/runtime-core";

 export default defineComponent({

 })
 </script>

<style scoped>
  .navbar{ 
    z-index: 99;
  }
</style>
