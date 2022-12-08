<template>
  <div>
    <header>
      <nav>
        <NuxtLink to="/">Nuxt Dojo</NuxtLink>
        <ul>
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink to="/products">Merch</NuxtLink></li>
        </ul>
        <a href="/">normal link -- about page</a>
      </nav>
    </header>
    <h2>Home</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Id minus rem
      dolor. Ex molestiae esse tenetur eveniet ratione temporibus illum!
    </p>
    <p>
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Numquam,
      laboriosam itaque tempore aperiam exercitationem asperiores.
    </p>
  </div>
</template>

<script setup></script>

<style scoped>
h2 {
  margin-bottom: 20px;
  font-size: 36px;
}
p {
  margin: 20px 0;
}
</style>
