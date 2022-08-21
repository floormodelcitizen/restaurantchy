<!-- https://www.udemy.com/course/the-nuxt-3-bootcamp-the-complete-developer-guide/learn/lecture/31554694#overview -->

<template>
  <div>
    <Nav />
    <div class="container">
      <h1>Welcome to Restaurantchy</h1>
      <NuxtLink to="/restaurants">Go to restaurants</NuxtLink>
    </div>
  </div>
</template>

<style>
  .container {
    text-align: center;
    margin-top: 5rem;
  }
</style>
