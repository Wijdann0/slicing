<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <h2 class="text-center my-4">Cari Buku</h2>
        <div class="my-3">
          <input type="search" class="form-control rounded-5" placeholder="Mau baca apa hari ini?">
        </div>
        <div class="my-3 text-muted">menampilkan 3 dari 3</div>
        <div class="row">
          <div class="col-lg-2">
            <nuxt-link to="/rincian/buku1">
              <div class="card mb-3">
                <div class="card-body">
                  <img src="~/assets/img/cover1.jpg" class="cover" alt="cover1">
                </div>
              </div>
            </nuxt-link>
          </div>
          <div class="col-lg-2">
            <nuxt-link to="/rincian/buku2">
              <div class="card mb-3">
                <div class="card-body">
                  <img src="~/assets/img/cover2.jpg" class="cover" alt="cover2">
                </div>
              </div>
            </nuxt-link>
          </div>
          <div class="col-lg-2">
            <nuxt-link to="/rincian/buku3">
              <div class="card mb-3">
                <div class="card-body">
                  <img src="~/assets/img/cover3.jpg" class="cover" alt="cover3">
                </div>
              </div>
            </nuxt-link>
          </div>
        </div>
      </div>
    </div>
    <nuxt-link to="/">
      <button type="button" class="btn btn-dark">Kembali</button>
    </nuxt-link>
  </div>
</template>

<style scoped>
.card-body {
  width: 100%;
  height: 20em;
  padding: 0;
}

.cover {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: 0 30;
}

button {
  width: 100px;
}

</style>