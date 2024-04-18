<script setup lang="ts"></script>
<template>
  <div
    class="p-6 sm:p-12 md:p-24 flex flex-col items-center justify-center min-h-screen bg-gradient-to-r from-pink-300 to-purple-400 rounded border-4 border-pink-500 shadow-lg"
  >
    <div class="flex justify-center items-center mb-8">
      <img
        src="./assets/izyansyazani.jpg"
        class="w-32 h-32 rounded-full mb-4 shadow-lg border-4 border-white object-cover"
        alt="Profile Picture"
      />
    </div>
    <div class="text-center text-white">
      <h1 class="text-4xl font-bold mb-4">Nur Izyan Syazani</h1>
      <p class="text-lg text-gray-100">Student ID: 22FTT1518</p>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8 mt-8">
        <div class="bg-pink-200 rounded p-4">
          <h2 class="text-2xl font-semibold mb-4 text-pink-900">
            Currently studying
          </h2>
          <ul class="text-lg text-gray-900">
            <li>WADT</li>
            <li>IPI</li>
            <li>MWE</li>
            <li>PMGT</li>
            <li>AWEP</li>
          </ul>
        </div>
        <div class="bg-purple-200 rounded p-4">
          <h2 class="text-2xl font-semibold mb-4 text-purple-900">Hobbies</h2>
          <ul class="text-lg text-gray-900">
            <li>Reading Books</li>
            <li>Listening to Music</li>
            <li>Sleeping</li>
          </ul>
        </div>
      </div>
      <h2 class="text-2xl font-semibold mt-8">Contact</h2>
      <ul class="text-lg text-gray-100">
        <li>Website: www.example.com</li>
      </ul>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style lang="css">
@import "tailwindcss/base";
@import "tailwindcss/components";
@import "tailwindcss/utilities";

/* Additional customization */
body {
  font-family: Inter, system-ui, Avenir, Helvetica, Arial, sans-serif;
  line-height: 1.5;
  font-weight: 400;
}

a {
  font-weight: 500;
  color: #646cff;
  text-decoration: inherit;
}

a:hover {
  color: #535bf2;
}

button {
  border-radius: 8px;
  border: 1px solid transparent;
  padding: 0.6em 1.2em;
  font-size: 1em;
  font-weight: 500;
  font-family: inherit;
  background-color: #1a1a1a;
  cursor: pointer;
  transition: border-color 0.25s;
}

button:hover {
  border-color: #646cff;
}

button:focus,
button:focus-visible {
  outline: 4px auto -webkit-focus-ring-color;
}

.card {
  padding: 2em;
}

#app {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;
  text-align: center;
}

@media (prefers-color-scheme: light) {
  body {
    color: #213547;
    background-color: #ffffff;
  }

  a:hover {
    color: #747bff;
  }

  button {
    background-color: #f9f9f9;
  }
}
</style>
