<template>
  <nuxt-link to="/pages" class="bi bi-arrow-left">
  </nuxt-link>
  <div class="container">
    <div class="row d-flex justify-content-center ">
      <div class="col-lg-8">
        <h2 class="text-center my-4">ISI BUKU KUNJUNGAN</h2>
        <form>
          <div class="mb-3">
            <input type="text" class="form-control form-control-lg rounded-5 bg-primary" placeholder="NAMA">
          </div>
          <div class="mb-3">
            <select class="form-control form-control-lg form-select rounded-5 bg-primary">
              <option value="">KEANGGOTAAN</option>
              <option value="Siswa">Siswa</option>
              <option value="Guru">Guru</option>
              <option value="Staf">Staf</option>
              <option value="Umum">Umum</option>
            </select>
          </div>
          <div class="mb-3">
            <div class="row">
              <div class="col-md-4">
                <select class="form-control form-control-lg form-select rounded-5 mb-2 bg-primary">
                  <option value="">TINGKAT</option>
                  <option value="X">X</option>
                  <option value="XI">XI</option>
                  <option value="XII">XII</option>
                </select>
              </div>
              <div class="col-md-4">
                <select class="form-control form-control-lg form-select rounded-5 mb-2 bg-primary">
                  <option value="">JURUSAN</option>
                  <option value="PPLG">PPLG</option>
                  <option value="TJKT">TJKT</option>
                  <option value="TSM">TSM</option>
                  <option value="DKV">DKV</option>
                  <option value="TOI">TOI</option>
                </select>
              </div>
              <div class="col-md-4">
                <select class="form-control form-control-lg form-select rounded-5 mb-2 bg-primary">
                  <option value="">KELAS</option>
                  <option value="1">1</option>
                  <option value="2">2</option>
                  <option value="3">3</option>
                  <option value="4">4</option>
                </select>
              </div>
            </div>
          </div>
          <div class="mb-3">
            <select class="form-control form-control-lg form-select rounded-5 bg-primary">
              <option value="">KEPERLUAN</option>
              <option value="baca">Baca Buku</option>
              <option value="pinjam">Pinjam Buku</option>
              <option value="kembalikan">Kembalikan Buku</option>
            </select>
          </div>
          <div class="d-flex justify-content-center">
            <button type="submit" class="btn btn-secondary btn-lg rounded-5 px-5 text-white">Kirim</button>
          </div>
        </form>
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

.bg-primary{
  background-color: #D9D9D9 !important;
}
</style>