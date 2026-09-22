<template>
  <div class="contact-page">

    <section class="hero">
      <h1>Hubungi Kami</h1>
      <p>
        Silakan hubungi kami jika mau bertanya atau membutuhkan
        informasi lebih lanjut.
      </p>
    </section>

    <section class="contact-container">

      <div class="contact-info">
        <h2>Info Kontak</h2>

        <div class="info-item">
          <span>📍</span>
          <div>
            <h3>Alamat</h3>
            <p>Jl. mangga No. 123</p>
          </div>
        </div>

        <div class="info-item">
          <span>📞</span>
          <div>
            <h3>Telepon</h3>
            <p>+62 888 1111 2222</p>
          </div>
        </div>

        <div class="info-item">
          <span>✉️</span>
          <div>
            <h3>Email</h3>
            <p>alpanganteng@gmail.com</p>
          </div>
        </div>
        
    
      </div>

      <div class="contact-form">
        <h2>Kirim Pesan</h2>

        <form>
          <div class="form-group">
            <label for="name">Nama</label>
            <input
              type="text"
              id="name"
              placeholder="Masukkan nama"
            />
          </div>

          <div class="form-group">
            <label for="email">Email</label>
            <input
              type="email"
              id="email"
              placeholder="Masukkan email"
            />
          </div>

          <div class="form-group">
            <label for="message">Pesan</label>
            <textarea
              id="message"
              placeholder="Tulis pesan kamu..."
            ></textarea>
          </div>

          <button type="submit">
            Kirim
          </button>
        </form>
      </div>

    </section>
  </div>
</template>

<style scoped>

.contact-page {
  background-color: #8de7f7;
  padding-bottom: 10px;
}

.hero {
  text-align: center;
  padding: 50px 20px;
  background-color: #8de7f7;
}

.hero h1 {
  margin: 0 0 10px;
  color: #000000;
  font-size: 2.5rem;
}

.contact-container {
  max-width: 1000px;
  margin: 40px auto;
  padding: 0 20px;

  display: flex;
  gap: 30px;
}

.contact-info,
.contact-form {
  flex: 1;
  background-color: rgb(255, 255, 255);
  padding: 30px;
  border-radius: 16px;
}

.info-item {
  display: flex;
  gap: 15px;
  align-items: flex-start;
  margin-bottom: 25px;
}

.info-item h3 {
  margin: 0 0 5px;
  color: #333;
}


input,
textarea {
  width: 100%;
  padding: 12px;



  border: 1px solid #000000;
  border-radius: 10px;

  font-size: 15px;
    transition: border-color 0.3s;
}

</style>
