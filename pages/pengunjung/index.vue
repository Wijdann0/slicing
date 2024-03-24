<template>
  <div class="container ">
    <div class="row">
      <div class="col-lg-12">
        <h2 class="text-center my-4">Riwayat Kunjungan</h2>
        <div class="my-3">
          <input type="search" class="form-control form-control-lg rounded-5" placeholder="Filter...">
        </div>
        <div class="my-3 text-muted">menampilkan 1 dari 1</div>
        <table class="table">
          <thead>
            <tr>
              <td>NO</td>
              <td>NAMA</td>
              <td>KEANGGOTAAN</td>
              <td>WAKTU</td>
              <td>KEPERLUAN</td>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td>1.</td>
              <td>Wijdan Fathu Rohman</td>
              <td>Murid</td>
              <td>XI</td>
              <td>PPLG</td>
              <td>4</td>
              <td>24 Februari 2024, 12.22.00</td>
              <td>Baca</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <nuxt-link to="/">
      <button type="button" class="btn btn-dark bck mt-5">Kembali</button>
    </nuxt-link>
  </div>
</template>

<style scoped>
.bck {
  width: 100px;
}
</style>