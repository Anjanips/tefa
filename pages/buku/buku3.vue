<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col-lg-2">
        <div class="card mb-3">
          <div class="card-body">
            <img src="assets/img/lautbercerita.png" class="lautbercerita" alt="lautbercerita">
          </div>
        </div>
      </div>
      <div class="col-lg-6">
        <div class="col p-5"><h1 style="font-size: 40px;">LAUT BERCERITA</h1></div>
        <h4>Penulis: Leila S.Chudori</h4>
        <h4>Penerbit: (KPG) Kepustakaan Popular Gramedia</h4>
        <h4>Tahun Terbit: 2017</h4>
        <h4>Deskripsi: Bertutur tentang kisah keluarga yang kehilangan, sekumpulan sahabat yang merasakan kekosongan di dada, 
          sekelompok orang yang gemar menyiksa dan lancar berkhianat, sejumlah keluarga yang mencari kejelasan makam anaknya, 
          dan tentang cinta yang tak akan luntur.</h4>
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