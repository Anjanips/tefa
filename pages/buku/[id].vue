<template>
  <h2 class="text-start my-4">{{ buku.judul }}</h2>
    <div class="row">
      <div class="col-md-3">
        <img :src="buku.cover" class="cover" alt="cover buku" style="height: 400px;">
      </div>
    <div class="col-md-6">
    <ul class="list-group list-grup-flush">
      <li class="list-group-item">Penulis : {{ buku.penulis }}</li>
      <li class="list-group-item">Penerbit : {{ buku.penerbit }}</li>
      <li class="list-group-item">Tahun Terbit : {{ buku.tahun_terbit }}</li>
      <li class="list-group-item">{{ buku.deskripsi }}</li>
      <li class="list-group-item">
          <span v-if="buku.kategori"> Kategori : {{ buku.kategori.nama }}</span>
          <span v-else>loading...</span>
      </li>
    </ul>
  </div>
  <nuxt-link to="./">
          <button type="button" class="btn btn-secondary btn-lg rounded-5 px-5" style="margin-left: 90.5%;">KEMBALI</button>
        </nuxt-link>
  </div>

</template>



<script setup>
const supabase = useSupabaseClient()

const route = useRoute()
const buku = ref([])
useHead({ title: "detail buku", 
meta: [{ name: "description", content: "detail buku"}]})

const getBooksById = async () => {
  const { data, error } = await supabase.from('buku').select(`*, kategori(*)`)
  .eq('id', route.params.id)
  if(data) buku.value = data [0]
} 

onMounted(() => {
  getBooksById()
})
</script>