<template>

  <h2 class="hero">Tentang Kami</h2>

  <div class="about">
    <div class="cerita">
      <div class="teks">
        <h1>Cerita Kami</h1>

        <p>
          Toko kami dibuat untuk membantu orang mendapatkan
          barang yang mereka butuhkan dengan mudah.
        </p>

        <p>
          Kami berusaha menyediakan produk yang bagus dengan
          harga yang terjangkau. Kami juga selalu berusaha
          memberikan pelayanan yang ramah kepada pelanggan.
        </p>
      </div>

      <div class="gambar">
        <div class="placeholder">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR8t06fu1Jx3x6ifoFnHDLeEP4CD1nNn3WF1zHXUOww1nZmg2TvCGLWqvQ&s=10" alt="Deskripsi" width="400">
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.about {
  padding: 50px;
}

.cerita {
  display: flex;
  align-items: center;
  gap: 30px;
}

.teks,
.gambar {
  height: 200px;
}

h1 {
  font-size: 30px;
  margin-bottom: 20px;
  
}

.hero {
  text-align: center;
  background-color: #7dddf5;
  color: #020202;

}
</style>
