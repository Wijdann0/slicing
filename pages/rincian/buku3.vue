<template>
  <div class="container">
    <div class="row mt-3">
      <div class="col-lg-6 p-5 d-flex justify-content-center">
        <div class="card">
          <div class="card-body">
            <img src="~/assets/img/cover3.jpg" width="220px" height="340px" class="cover" alt="cover1">
          </div>
        </div>
      </div>
      <div class="col-lg-6 p-5 justify-content-center">
        <p>Pengarang : Pinto Augrah</p>
        <p>Genre : Romance</p>
        <p>Bahasa : Indonesia</p>
        <p>Penerbit : Bintang Pusaka (Yogyakarta)</p>
        <p>Tahun Terbit : 2021</p>
        <p>Halaman : 529 Halaman</p>
      </div>
    </div>
    <div class="row mt-5">
      <h2>Sinopsis</h2>
      <p class="mt-3">Rabiah ingin mematahkan mitos yang beredar selama ini, bahwa garis keturunan keluarga bangsawan
        Minangkabau akan putus pada generasi ketujuh.
        Apa pun siap dia lakukan demi mendapatkan anak perempuan pembawa nama keluarga, termasuk menjadi istri kelima
        seorang lelaki yang terkenal
        mampu memberikan anak perempuan.
        Tidak disangka, penghalang utama Rabiah justru kakak kesayangannya, Magek. Setelah bergabung dengan Kaum Padri
        dari utara,
        Magek justru mengacungkan pedangnya ke arah Rubiah, siap menghancurkan semua yang dimilikinya: harta, adat,
        keluarga, dan masa lalu.
      </p>
    </div>

    <nuxt-link to="/buku">
      <button type="button" class="btn btn-dark mt-5 mb-5 ">Kembali</button>
    </nuxt-link>
  </div>
</template>


<style scoped>
.cover {
  width: 255px;
  height: 370px;
  box-shadow: 1px 10px 50px rgb(0, 0, 0,.5);
}
.card{
  border: none !important;
}
</style>