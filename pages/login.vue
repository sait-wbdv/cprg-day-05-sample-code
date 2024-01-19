<script setup>
// TODO: Set up the supabase client

// TODO: set up input variables

// TODO: create sign in function

// TODO: access the logged in user and show the users information
</script>
<template>
  <main>
    <h1>Login Page</h1>
    <section>
      <label for="email">
        email
        <input type="email" v-model="email" />
      </label>
      <label for="password">
        password
        <input type="password" v-model="password" />
      </label>

      <button @click="signIn">Sign In with E-Mail</button>
    </section>
    <section>
      <h1>Active user information</h1>
      <!-- Show user information -->
    </section>
  </main>
</template>
