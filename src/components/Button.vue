<template>
  <div>
    <section>
      <h2 class="text-3xl font-bold text-indigo-700 mb-6">Tailwind 버튼 효과 💡</h2>
      <div class="bg-linear-to-b from-indigo-100 to-blue-400 flex flex-col sm:flex-row gap-4 justify-center">
        <button class="bg-pink-500 px-6 py3 rounded-lg text-center hover:bg-pink-400 transition">기본버튼</button>
        <button class="px-6 py3 rounded-full bg-pink-300 hover:shadow-2xl hover:scale-110 transition">둥근버튼</button>
        <button class="border-2 border-pink-500 px-6 py-3 rounded0-lg hover:bg-pink-700 hover:text-white trasition">테두리버튼</button>
      </div>
    </section>
  </div>
</template>
<script setup></script>

<style scoped></style>
