<template>
  <h1>這是前台</h1>
  <nav>
    <RouterLink to="/">首頁</RouterLink> |
    <RouterLink to="/about">關於</RouterLink> |
    <RouterLink to="/products">產品列表</RouterLink> |
    <RouterLink to="/cart">購物車</RouterLink> |
    <RouterLink to="/login">登入</RouterLink> |
    <RouterLink to="/admin/products">後台 購物車列表</RouterLink>
  </nav>
  <RouterView></RouterView>
</template>
