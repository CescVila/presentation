<template>
      <nav class="flex justify-between navbar">
    <div class="w-12">
      <img class="w-8 h-9 pt-2" alt="">
    </div>
    <h1 class="font-bold text-2xl pt-2">Welcome to your Tasksboard</h1>
    <div>
      <h2 class="font-bold text-2xl pt-2">Hello {{name[0]}}</h2>
    </div>
    <button @click="signOut" class="inline-block px-5 py-1 bg-green-600 text-white font-medium text-xs leading-tight uppercase rounded shadow-md hover:bg-green-600 hover:shadow-lg focus:bg-green-400 focus:shadow-lg focus:outline-none focus:ring-0 active:bg-green-500 active:shadow-lg transition duration-150 ease-in-out">Log out</button>
    
</template>


<script>

</script>

<style scoped>
.navbar{
  background: rgb(242, 250, 240);
  padding: 1px 280px;
}
</style>