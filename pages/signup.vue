<script setup>
// TODO: Import the supabase client

// TODO: add the email and password variables

// TODO: add error handling variables (not as important for our uses)

// TODO: Add the sign up function that will send the data to the server
</script>

<template>
  <main>
    <h1>Sign Up</h1>
    <!-- TODO: Add a function called signUp that will send the information to the database when the form is filled out and submitted -->
    <form @submit.prevent="signUp">
      <label for="email">
        Email:
        <!-- TODO: create a variable for email -->
        <input type="email" v-model="email" />
      </label>
      <label for="password">
        Password:
        <!-- TODO: create a variable for password -->
        <input type="password" v-model="password" />
      </label>
      <button @click="signUp">Sign Up</button>
    </form>
  </main>
</template>
