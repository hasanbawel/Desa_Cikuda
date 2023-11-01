<script setup>
import Header from "../components/Header.vue";
import Banner from "../components/Banner.vue";
import Sidebar from "../components/Sidebar.vue";
</script>

<template>
  <Header />
  <Banner />

  <main class="flex">
    <Sidebar />

    <div class="flex-1 p-10">
      <p class="text-3xl font-semibold">Visi & Misi Desa Cikuda</p>
      <p class="text-lg font-semibold">Visi</p>
      <p>
        “Mewujudkan Masyarakat Desa Cikuda Yang Agamis, Kreatif, Mandiri, Sehat, Gotong Royong, Menjunjung Tinggi Kerbersamaan dan Toleransi”
      </p>
      <p class="text-lg font-semibold">Misi</p>
      <ul>
        <li>
          1. Menjaga Nilai-nilai Keraifan Lokal Yang Religius;
        </li>
        <li>
          2. Menggali dan Mengembangkan Ide-Ide Kretif;
        </li>
        <li>
          3. Meningkatkan sararana dan Prasarana Kesehatan;
        </li>
        <li>
          4. Memanfaatkan Sumberdaya Alam;
        </li>
        <li>
          5. Menjaga dan Menjalin kerja sama katif bersama seluruh kelembaga desa dan masyarakat;
        </li>
        <li>
          6. Meningkatkan Kegiatan Gotong Royong;
        </li>
        <li>
          7. Mengedepankan kebersamaan;
        </li>
        <li>
          8. Musyawarah dalem menyelesaikan setiap perbededaan;
        </li>
        <li>         
    </div>
  </main>
</template>

<style>
body {
  background: #f1f1f1;
}
</style>
