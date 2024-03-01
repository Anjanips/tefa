<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-2">
        <div class="card mb-3">
          <div class="card-body">
            <img src="~assets/img/dikta&hukum.jpg" class="dikta&hukum" alt="dikta&hukum">
          </div>
        </div>
      </div>
      <div class="col-lg-6">
        <div class="col p-5"><h1 style="font-size: 40px;">DIKTA DAN HUKUM</h1></div>
        <h4>Penulis: Dhia'an Farah</h4>
        <h4>Penerbit: Asoka Aksara x Loveable</h4>
        <h4>Tahun Terbit: 2021</h4>
        <h4>Deskripsi: Novel Dikta dan Hukum bercerita tentang Dikta, seorang mahasiswa hukum yang cerdas, kaya, baik hati, pekerja keras, perhatian, dan tampan. 
          Dikta bertunangan dengan Nadhira, seorang siswa kelas 12 yang memiliki kepribadian pemalas dan pemalas. 
          Sifat Nadhira sangat berbanding terbalik dengan sifat Dikta.</h4>
      </div>
      <nuxt-link to="/buku">
          <button type="button" class="btn btn-secondary btn-lg rounded-5 px-5" style="margin-left: 90.5%;">KEMBALI</button>
        </nuxt-link>
    </div>
  </div>
</template>

<style scoped>
.cover {
  height: 300px;
  width: 200px;
}
.card.mb-3 {
  margin-top: 50px;
  margin-left: 20px;
  height: 340px;
  width: 235px;
}
h3 {
  margin-top: 50px;
  margin-right: 20px;
}
img {
  height: 300px;
  width: 200px;
}
</style>