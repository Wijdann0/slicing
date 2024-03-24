<template>
  <div class="container">
    <div class="row mt-3 d-flex">
      <div class="col-lg-6 p-5 d-flex justify-content-center">
        <div class="card">
          <div class="card-body">
            <img src="~/assets/img/cover1.jpg" width="220px" height="340px" class="cover" alt="cover1">
          </div>
        </div>
      </div>
      <div class="col-6 p-5 justify-content-center">
        <p>Pengarang : Jonathan Black</p>
        <p>Genre : Sejarah</p>
        <p>Bahasa : Indonesia</p>
        <p>Penerbit : Alfa Beta</p>
        <p>Tahun Terbit : 14 Mei 2015</p>
        <p>Halaman : 529 Halaman</p>
      </div>
    </div>
    <div class="row mt-5">
      <h2>Sinopsis</h2>
      <p class="mt-3">Banyak orang mengatakan bahwa sejarah ditulis oleh para pemenang. Hal ini sama sekali tak
        mengejutkan alias wajar
        belaka. Tetapi, bagaimana jika sejarah atau apa yang kita ketahui sebagai sejarah ditulis oleh orang yang salah?
        Bagaimana jika semua yang telah kita ketahui hanyalah bagian dari cerita yang salah tersebut? Dalam buku
        kontroversial yang sangat tersohor ini, Jonathan Black mengupas secara tajam penelusurannya yang brilian tentang
        misteri sejarah dunia. Dari mitologi Yunani dan Mesir kuno sampai cerita rakyat Yahudi, dari kultus Kristiani
        sampai Freemason, dari Karel </p>
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