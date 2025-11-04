<template>
  <div>
    <!-- 반응형 카드 -->
    <section class="p-6 max-w-6xl">
      <h2 class="text-3xl font-bold text-center mb-8 text-blue-600">상품카드</h2>
      <div class="grid grid-cols-1 lg:grid-3 sm:grid-cols-2">
        <div v-for="(cat, i) in cats" :key="i" class="bg-white p-6 rounded-2xl shadow-md text-center">
          <img :src="cat.img" alt="cat.desc" class="rounded-lg mb-4 w-[200px]" />
          <h3 class="text-xl font-bold text-gray-800 mb-2">{{ cat.title }}</h3>
          <p class="text-gray-600 mb-3">{{ cat.desc }}</p>
          <button class="bg-blue-500 text-white px-4 py-2 rounded-lg hover:bg-blue-600">자세히 보기</button>
        </div>
      </div>
      <img src="/public/images/25231.png" alt="123" class="w-24 h-24 rounded-full shadow-ml bg-amber-300 hover:scale-120 transition">
    </section>
  </div>
</template>
<script setup>
const cats = [
  {
    img: "/public/images/25231.png",
    title: "귀여운 고양이",
    desc: "포근한 털이 매력적이에요 🐾",
  },
  {
    img: "/public/images/25231.png",
    title: "졸린 고양이",
    desc: "자는 모습이 너무 귀여워요 😴",
  },
  {
    img: "/public/images/25231.png",
    title: "활발한 고양이",
    desc: "장난꾸러기예요 🧶",
  },
];
</script>

<style scoped></style>
