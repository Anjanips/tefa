<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-2">
        <div class="card mb-3">
          <div class="card-body">
            <img src="assets/img/bulan.jpg" class="bulan" alt="bulan">
          </div>
        </div>
      </div>
      <div class="col-lg-6">
        <div class="col p-5"><h1 style="font-size: 40px;">BULAN</h1></div>
        <h4>Penulis: Tere Liye</h4>
        <h4>Penerbit: PT Gramedia Pustaka Utama</h4>
        <h4>Tahun Terbit: 2015</h4>
        <h4>Deskripsi: Novel ini menceritakan mengenai persahabatan Rain, Selu, Alu, yang diajak oleh Miss Selena dan Av guna melakukan sebuah diplomasi dengan klan matahari. 
          Hal itu bertujuan supaya mereka bisa membuka portal yang sudah ribuan tahun lalu lamanya tertutup secara rapat. 
          Mereka juga waspada pada tamus dan juga pasukannya yang masih berusaha keluar dari sebuah penjara kegelapan.
          Petualangan mereka dimulai saat mereka sampai di klan matahari yang ternyata saat itu bertepatan dengan festival bunga matahari. 
          Festival itu diikuti oleh Raib beserta dengan kawan lainnya. </h4>
      </div>
      <nuxt-link to="../buku">
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
  margin-left: 20px;
}
img {
  height: 300px;
  width: 200px;
}
</style>