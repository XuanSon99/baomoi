<template>
  <header>
    <div class="container flex">
      <div class="menu">
        <router-link to="/" class="border-gradient">Trang chủ</router-link>
        <router-link to="/about" class="border-gradient"
          >Giới thiệu</router-link
        >
      </div>
      <div class="search flex">
        <input type="text" placeholder="Tìm kiếm" />
        <img src="../assets/icons/search.svg" alt="" />
      </div>
    </div>
  </header>
</template>

<script>
export default {};
</script>