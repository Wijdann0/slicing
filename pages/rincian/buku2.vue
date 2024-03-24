<template>
  <div class="container">
    <div class="row mt-3">
      <div class="col-lg-6 p-5 d-flex justify-content-center">
        <div class="card">
          <div class="card-body">
            <img src="~/assets/img/cover2.jpg" class="cover" alt="cover1">
          </div>
        </div>
      </div>
      <div class="col-lg-6 p-5 justify-content-center">
        <p>Pengarang : Andrea Hirata</p>
        <p>Genre : Romance</p>
        <p>Bahasa : Indonesia</p>
        <p>Penerbit : Bintang Pusaka (Yogyakarta)</p>
        <p>Tahun Terbit : 2005</p>
        <p>Halaman : 529 Halaman</p>
      </div>
    </div>
    <div class="row mt-5">
      <h2>Sinopsis</h2>
      <p class="mt-3">Ceritanya terjadi di desa Gantung, Belitung Timur. Dimulai ketika sekolah Muhammadiyah terancam akan
        dibubarkan oleh Depdikbud Sumsel
        jikalau tidak mencapai siswa baru sejumlah 10 anak. Ketika itu baru 9 anak yang menghadiri upacara pembukaan, akan
        tetapi tepat ketika Pak Harfan,
        sang kepala sekolah, hendak berpidato menutup sekolah, Harun dan ibunya datang untuk mendaftarkan diri di sekolah
        kecil itu.
        Dari sanalah dimulai cerita mereka. Mulai dari penempatan tempat duduk, pertemuan mereka dengan Pak Harfan,
        perkenalan mereka yang luar biasa
      </p>
    </div>

    <nuxt-link to="/buku">
      <button type="button" class="btn btn-dark mt-5 mb-5">Kembali</button>
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