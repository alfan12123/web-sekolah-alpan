<!-- <template>
  <nav>
    <h1>alfan - Onlineshop <span style="font-size: 40px;">🛒</span></h1>

 <hr />
    <RouterLink to="/">Landing</RouterLink>   |
    <RouterLink to="/product">Product</RouterLink>   |
    <RouterLink to="/about">About</RouterLink>   |
    <RouterLink to="/contact">Contact</RouterLink> 
    </nav>

 
</template>

<style scoped>
nav {
  display: flex;
  align-items: center;
  padding: 1rem;
  background-color: #ffffff;
  color: var(--color-text);
  border-radius: 10px;
  gap: 5px;
} 
.atas{
background-color: #0d3b97;
  color: #fffdfd;
  padding: 10px;
  border-radius: 10px;
}   
h3 {
  color: #fdfeff;
  padding: 10px;
  
}
</style> -->

<template>
  <header class="navbar">
    <div class="logo">alfan - onlineshop</div>
    <nav class="nav-links">
      <RouterLink to="/" class="nav-item">Landing</RouterLink>
      <RouterLink to="/product" class="nav-item">Product</RouterLink>
      <RouterLink to="/about" class="nav-item">About</RouterLink>
      <RouterLink to="/contact" class="nav-item">Contact</RouterLink>
    </nav>
  </header>
  <hr />

</template>
<style scoped>
/* .atas{
text-align: center;
} */

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 0;
  margin-bottom: 20px;
  background: linear-gradient(to right, #ffffff, #7dddf5);
}

.nav-links {
  display: flex;
  gap: 20px;
}

.logo {
  font-weight: 700;
  font-size: 24px;
  color: #000000;
}

.nav-item {
  text-decoration: none;
  color: #fd0000;
  font-size: 15px;
}

.nav-item.active, .nav-item:hover {
  color: #0004ff;
  font-weight: 700;
}

</style>