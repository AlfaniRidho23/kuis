<template>
    <!--banner image-->
  
    <div class="banner-image w-100 vh-100 d-flex justify-content-center align-items-center">
      <div  class="images">
        <div class="profile">
        <img src="../assets/logo.png (2).jpeg" class="rounded-circle"
             height="300px" width="300px">
      </div>
      <div class="content text-center">
        <h1 class="text-white">M. Ridho Alfani</h1>
        <h2>Mahasiswa uin suska riau</h2>
        <h3>Selamat datang di website saya</h3>
      </div>
      </div>
    </div>
  
  
  </template>
  
  <script>
  export default {
    name: 'App',
    components: {
      // HelloWorld
    }
  }
  </script>
  
  <style>
  .text-center{
    margin-top: 50px;
  }
  .images {
    margin-top: -100px;
  }
  .banner-image{
    background: #3df46b;
    background-size: cover;
  }
  
  
  </style>
  