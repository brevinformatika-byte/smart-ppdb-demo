<template>
  <section class="news-section">
    <div class="head">
      <span>Kegiatan & Informasi</span>
      <h2>Aktivitas Sekolah Tampil Lebih Hidup</h2>
      <p>
        Website dapat menjadi pusat informasi untuk menampilkan kegiatan,
        prestasi, pengumuman, dan dokumentasi sekolah secara profesional.
      </p>
    </div>

    <div class="news-grid">
      <article class="big-card">
        <div class="image image-1"></div>
        <div class="content">
          <small>Kegiatan Sekolah</small>
          <h3>Dokumentasi Kegiatan Siswa</h3>
          <p>Kegiatan belajar, praktik, lomba, dan event sekolah dapat ditampilkan lebih rapi.</p>
        </div>
      </article>

      <article>
        <div class="image image-2"></div>
        <div class="content">
          <small>Prestasi</small>
          <h3>Prestasi Siswa</h3>
          <p>Publikasi prestasi membuat citra sekolah terlihat lebih kuat.</p>
        </div>
      </article>

      <article>
        <div class="image image-3"></div>
        <div class="content">
          <small>Pengumuman</small>
          <h3>Informasi PPDB</h3>
          <p>Calon siswa dan orang tua dapat melihat info pendaftaran dari satu tempat.</p>
        </div>
      </article>
    </div>
  </section>
</template>

<style scoped>
.news-section{
  padding:120px 8%;
  background:#f8fafc;
}

.head{
  max-width:850px;
  margin-bottom:60px;
}

.head span{
  display:inline-block;
  background:#facc15;
  color:#111827;
  padding:10px 18px;
  border-radius:999px;
  font-size:13px;
  font-weight:900;
}

.head h2{
  font-size:58px;
  line-height:1.08;
  letter-spacing:-2px;
  margin:25px 0;
  color:#0f172a;
}

.head p{
  color:#64748b;
  font-size:18px;
  line-height:1.8;
}

.news-grid{
  display:grid;
  grid-template-columns:1.3fr .85fr .85fr;
  gap:24px;
}

article{
  background:white;
  border-radius:34px;
  overflow:hidden;
  box-shadow:0 25px 60px rgba(15,23,42,.09);
}

.big-card{
  min-height:520px;
}

.image{
  height:260px;
  background-size:cover;
  background-position:center;
}

.big-card .image{
  height:330px;
}

.image-1{
  background-image:url("https://images.unsplash.com/photo-1523050854058-8df90110c9f1?q=80&w=1400&auto=format&fit=crop");
}

.image-2{
  background-image:url("https://images.unsplash.com/photo-1577896851231-70ef18881754?q=80&w=1200&auto=format&fit=crop");
}

.image-3{
  background-image:url("https://images.unsplash.com/photo-1509062522246-3755977927d7?q=80&w=1200&auto=format&fit=crop");
}

.content{
  padding:28px;
}

.content small{
  color:#2563eb;
  font-weight:900;
}

.content h3{
  font-size:27px;
  margin:12px 0;
  color:#0f172a;
}

.content p{
  color:#64748b;
  line-height:1.7;
}

@media(max-width:900px){
  .news-grid{
    grid-template-columns:1fr;
  }

  .head h2{
    font-size:38px;
  }
}
</style>