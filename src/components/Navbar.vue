<template>
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
</style>
