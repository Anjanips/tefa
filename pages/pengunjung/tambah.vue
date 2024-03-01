<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-12">
        <h2 class="text-center my-4">ISI BUKU KUNJUNGAN</h2>
        <form>
          <div class="mb-3">
            <input type="text" class="form-control form-control-lg rounded-5" placeholder="NAMA...">
          </div>
          <div class="mb-3">
            <select class="form-control form-control-lg form-select rounded-5">
              <option value="">KATEGORI</option>
              <option value="Siswa">Siswa</option>
              <option value="Guru">Guru</option>
              <option value="Staf">Staf</option>
              <option value="Umum">Umum</option>
            </select>
          </div>
              <div class="mb-3">
                <select class="form-control form-control-lg form-select rounded-5">
                  <option value="">KELAS</option>
                  <option value="X">X</option>
                  <option value="XI">XI</option>
                  <option value="XII">XII</option>
                </select>
              </div>
           <div class="mb-3">
            <select class="form-control form-control-lg form-select rounded-5">
              <option value="">KEPERLUAN</option>
                  <option value="baca">Baca Buku</option>
                  <option value="pinjam">Pinjam Buku</option>
                  <option value="kembalikan">Kembalikan Buku</option>
            </select>
           </div>
           <nuxt-link to="../pengunjung"><button type="submit" class="btn btn-primary btn-lg rounded-5 px-5">KIRIM</button></nuxt-link>
           <nuxt-link to="../"><button type="button" class="btn btn-secondary btn-lg rounded-5 px-5" style="margin-left: 82.5%;">KEMBALI</button></nuxt-link>
        </form>
      </div>
    </div>
  </div>
</template>

