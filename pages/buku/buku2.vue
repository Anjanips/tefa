<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-2">
        <div class="card mb-3">
          <div class="card-body">
            <img src="~/assets/img/sagaras.jpeg" class="sagaras" alt="sagaras">
          </div>
        </div>
      </div>
      <div class="col-lg-6">
        <div class="col p-5"><h1 style="font-size: 40px;">SAGARAS</h1></div>
        <h4>Penulis: Tere Liye</h4>
        <h4>Penerbit: Sabakgrip</h4>
        <h4>Tahun Terbit: 2022</h4>
        <h4>Deskripsi: Buku ini menceritakan tentang petualangan Ali, Raib, dan Seli. 
          Ali bertahun tahun mencoba memecahkan misteri siapa ayah dan ibu kandungnya. 
          Beberapa percobaan dia lakukan. Hingga pada pencobaan terakhir Ali, akhirnya dia menemukan jejak akhir dari keberadaan kedua orang tuanya. 
          Setelah itu Ali memutuskan untuk pergi ke SagaraS, tempat terakhir ayah dan ibunya berada.</h4>
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