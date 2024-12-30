<template>
      <div class="container mx-auto p-4">
        <h1 class="text-2xl font-bold mb-4">Register</h1>
        <form @submit.prevent="register">
          <div class="mb-4">
            <label class="block text-gray-700">Username</label>
            <input type="text" v-model="username" class="border p-2 w-full" required>
          </div>
          <div class="mb-4">
            <label class="block text-gray-700">Email</label>
            <input type="email" v-model="email" class="border p-2 w-full" required>
          </div>
          <div class="mb-4">
            <label class="block text-gray-700">Password</label>
            <input type="password" v-model="password" class="border p-2 w-full" required>
          </div>
          <button type="submit" class="bg-blue-500 text-white p-2">Register</button>
        </form>
      </div>
    </template>

    <script>
    export default {
      data() {
        return {
          username: '',
          email: '',
          password: ''
        }
      },
      methods: {
        register() {
          // Handle registration logic here
        }
      }
    }
    </script>
