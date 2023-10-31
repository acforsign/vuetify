<template>
    <v-card>
    <v-layout>
      <VNavigationDrawer
      expand-on-hover
        rail
      >
        <v-list>
          <v-list-item
            prepend-avatar='https://static.vecteezy.com/system/resources/previews/006/541/188/original/bearded-male-cartoon-character-with-sunglasses-minimalist-cartoon-avatar-profile-illustration-free-vector.jpg'
            title="Amirhossein"
            subtitle="khanmohammadi"
          ></v-list-item>
        </v-list>

        <v-divider></v-divider>

        <v-list density="compact" nav>
          <v-list-item prepend-icon="mdi-folder" title="My Files" value="myfiles"></v-list-item>
          <v-list-item prepend-icon="mdi-account-multiple" title="Shared with me" value="shared"></v-list-item>
          <v-list-item prepend-icon="mdi-home" title="Home" value="Home"></v-list-item>
        </v-list>
      </VNavigationDrawer>

      <v-main style="height: 100vh"></v-main>
    </v-layout>
  </v-card>
</template>

<script setup>
import{ ref } from 'vue'

const addReses=ref('https://static.vecteezy.com/system/resources/previews/006/541/188/original/bearded-male-cartoon-character-with-sunglasses-minimalist-cartoon-avatar-profile-illustration-free-vector.jpg');

</script>

<style lang="scss" scoped>

</style>