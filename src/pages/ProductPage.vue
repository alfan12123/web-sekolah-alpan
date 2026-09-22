<script setup>
import ProductCard from '../components/ProductCard.vue'
const daftarProduk = [
 { id: 1, nama: 'Sepatu Futsal TRUCO IV Unisex', harga: 539000, gambar:
'https://images.puma.com/image/upload/f_auto,q_auto,b_rgb:fafafa,w_2000,h_2000/global/108845/03/sv01/fnd/IDN/fmt/png/Sepatu-Futsal-TRUCO-IV-Unisex' },

{ id: 2, nama: 'Sepatu Futsal FUTURE 8 PLAY IT Unisex', harga: 899000, gambar:
'https://images.puma.com/image/upload/f_auto,q_auto,b_rgb:fafafa,w_2000,h_2000/global/108606/03/sv01/fnd/IDN/fmt/png/Sepatu-Futsal-FUTURE-8-PLAY-IT-Unisex' },
{ id: 3, nama: 'Sepatu Futsal ULTRA MATCH IT Unisex', harga: 1050000, gambar:
'https://www.static-src.com/wcsstore/Indraprastha/images/catalog/full//catalog-image/106/MTA-133349479/puma_sepatu_futsal_puma_ultra_match_it_original_107221_03_full01_da2d5fbf.jpg' },
{ id: 4, nama: 'Sepatu Futsal Puma Ultra Match IT', harga: 499999, gambar:
'https://www.static-src.com/wcsstore/Indraprastha/images/catalog/full//catalog-image/87/MTA-132139103/puma_sepatu_futsal_puma_ultra_match_it_original_107522_01_full01_0feb4cab.jpg    ' },
]//
</script>
<template>
 <main>
<h2 class="hero">Produk alfan shopp</h2>
 <div class="grid">
 <ProductCard
 v-for="produk in daftarProduk"
 :key="produk.id"
 :nama="produk.nama"
 :harga="produk.harga"
 :gambar="produk.gambar"
 />
 </div>
 </main>
</template>
<style scoped>
.grid {
 display: flex;
 gap: 16px;
 flex-wrap: wrap;
}
 
 h2.hero {
 text-align: center;
  padding: 10px ;
  background-color: #7dddf5;
  color: #020202;
 
} 
</style>
