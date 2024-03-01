<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <h2 class="text-center my-4">RIWAYAT KUNJUNGAN</h2>
        <div class="my-3">
          <input type="search" class="form control form-control-lg rounded-5" placeholder="Filter...">
        </div>
        <div class="my-3 text-muted">Menampilkan 3 dari 3</div>
        <table class="table">
          <thead>
            <tr>
              <td>No</td>
              <td>NAMA</td>
              <td>KATEGORI</td>
              <td>WAKTU</td>
              <td>KEPERLUAN</td>
            </tr>
          </thead>
          <tbody>
            <tr>
            <td>1.</td>
            <td>Anjani</td>
            <td>Siswa</td>
            <td>26 Februari 2024, 13.00</td>
            <td>Baca</td>
          </tr>
          </tbody>
          <tbody>
            <tr>
            <td>2.</td>
            <td>Yuliana</td>
            <td>Siswa</td>
            <td>20 Februari 2024, 10.00</td>
            <td>Meminjam Buku</td>
          </tr>
          </tbody>
          <tbody>
            <tr>
            <td>3.</td>
            <td>Rike</td>
            <td>Siswa</td>
            <td>18 Februari 2024, 15.00</td>
            <td>Mengembalikan Buku</td>
          </tr>
          </tbody>
        </table>
        <nuxt-link to="../pengunjung/tambah">
          <button type="submit" class="btn btn-secondary btn-lg rounded-5 px-5" style="margin-left: 90.5%;">KEMBALI</button>
        </nuxt-link>
      </div>
    </div>
  </div>
</template>