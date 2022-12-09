<template>
  <div>
    <h2>About</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi architecto
      ratione quia consequatur reiciendis similique, facilis quae unde?
      Assumenda, laboriosam?
    </p>
    <p>api response:</p>
    <div>{{ data }}</div>
  </div>
</template>

<script setup>
// const { data } = await useFetch("/api/ninja?name=mike");
// const { data } = await useFetch("/api/ninja?name=supermike", {
//   method: "post",
//   body: { age: 30 },
// });

const { data } = await useFetch("/api/ninja");
</script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
p {
  margin: 20px 0;
}
</style>
