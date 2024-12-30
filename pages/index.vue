<template>
      <div class="container mx-auto p-4">
        <h1 class="text-2xl font-bold mb-4">Timeline</h1>
        <div v-for="post in posts" :key="post.id" class="mb-4">
          <p class="text-gray-800">{{ post.content }}</p>
          <small class="text-gray-600">{{ post.author }}</small>
        </div>
      </div>
    </template>

    <script>
    export default {
      data() {
        return {
          posts: [
            { id: 1, content: 'Hello, world!', author: 'User1' },
            { id: 2, content: 'This is a test post.', author: 'User2' },
          ]
        }
      }
    }
    </script>
