<template>
  <div class="flex flex-column align-start align-self-start justify-start">
    <h1>Bem vindo ao dashboard</h1>
    <p>Voce esta logado em  {{ $nuxt.$fire.auth.currentUser.email }}</p>
    <v-btn @click="$router.push('/auth/signout')">Logout</v-btn>
    <v-btn @click="$router.push('/home')">home</v-btn>
  </div>
</template>

<script>

export default {
  
}
</script>
