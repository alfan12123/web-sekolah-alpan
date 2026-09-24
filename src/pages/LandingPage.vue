<template>
  <main class="landing">
    <div class="content">

      <h1>Alfan Shop</h1>
      <p>
        Belanja Sepatu futsal dengan mudah
        cepat dan murah.
      </p>
      
      <RouterLink to="/product" class="btn-primary"><button>Meluncur🛫</button></RouterLink>
      
    </div>
  </main>
  <video controls width="1200" loop>
  <source src="https://www.w3schools.com/html/mov_bbb.mp4" type="video/mp4" />
  Browser kamu tidak mendukung pemutaran video.
</video>


<section class="features">
   
  <div class="card">
    <div class="icon">💖</div>
      <h3>Produk Berkualitas</h3>
      <p>kami menyediakan produk yang berkualitas dan nyaman dipakai</p>
    </div>

  <div class="card">
    <div class="icon">🤑</div>
      <h3>harga terjangkau</h3>
      <p>kami menyediakan harga yang terjangkau untuk semua produk</p>
    </div>

    <div class="card">
    <div class="icon">😍</div>
      <h3>layanan pelanggan</h3>
      <p>kami menyediakan layanan pelanggan yang terbaik</p>
    </div>

</section>

</template>

<style scoped>
.landing {
  min-height: 80vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background: linear-gradient(149deg, #fdfdfd,#7dddf5);
  border-radius: 10px;
}

.content {
  text-align: center;
}

h1 {
  font-size: 50px;
  color: #222;
  margin-bottom: 10px;
}

p {
  color: #000000;
  font-size: 18px;
  margin-bottom: 30px;
}

button {
  padding: 12px 30px;
  border: none;
  border-radius: 30px;
  background: #eb2525;
  color: rgb(255, 255, 255);
  font-size: 16px;
  cursor: pointer;
  transition: 0.3s;
}

button:hover {
  background: #1d4ed8;
  transform: translateY(-3px);
}

.features {
  display: flex;
  justify-content: space-around;
 padding: 50px;
  gap: 20px;
  flex-wrap: wrap;
}

.card {
  background-color: #7dddf5;
  border-radius: 10px;
  padding: 20px;
  width: 300px;
  text-align: center;
  box-shadow: 0 4px 6px rgb(97, 237, 255);
 transition: transform 0.3s ease, box-shadow 0.3s ease;
 
}

.card:hover {
  transform: translateY(-10px);
}

.icon {
  font-size: 40px;
  margin-bottom: 10px;
}
</style>