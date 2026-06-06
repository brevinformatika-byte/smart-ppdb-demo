<template>
  <section id="profil" class="about">
    <div class="text">
      <span class="badge">Profil Sekolah</span>

      <h2>
        Pendidikan yang Mengutamakan
        Karakter, Kompetensi, dan Masa Depan.
      </h2>

      <p>
        SMK Al Husain Keling berkomitmen mencetak generasi yang berakhlak,
        disiplin, terampil, dan siap bersaing di dunia kerja maupun pendidikan
        lanjutan.
      </p>

      <div class="features">
        <div>✓ Pembelajaran berbasis praktik</div>
        <div>✓ Lingkungan religius dan disiplin</div>
        <div>✓ Jurusan sesuai kebutuhan industri</div>
        <div>✓ Informasi sekolah mudah diakses</div>
      </div>
    </div>

    <div class="visual">
      <div class="main-image"></div>
      <div class="mini-card">
        <h3>Digital School</h3>
        <p>Profil, kegiatan, prestasi, dan PPDB dalam satu platform.</p>
      </div>
    </div>
  </section>
</template>

<style scoped>
.about{
  padding:110px 8%;
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:70px;
  align-items:center;
  background:#f8fafc;
}

.badge{
  display:inline-block;
  background:#facc15;
  color:#111827;
  padding:10px 18px;
  border-radius:999px;
  font-size:13px;
  font-weight:900;
}

h2{
  font-size:56px;
  line-height:1.08;
  letter-spacing:-2px;
  margin:25px 0;
  color:#0f172a;
}

p{
  color:#475569;
  font-size:18px;
  line-height:1.8;
}

.features{
  margin-top:30px;
  display:grid;
  gap:14px;
}

.features div{
  background:white;
  padding:16px 20px;
  border-radius:18px;
  font-weight:800;
  color:#0f172a;
  box-shadow:0 15px 35px rgba(15,23,42,.07);
}

.visual{
  position:relative;
  min-height:520px;
}

.main-image{
  position:absolute;
  inset:0 70px 70px 0;
  border-radius:38px;
  background:
    linear-gradient(rgba(37,99,235,.12), rgba(15,23,42,.18)),
    url("https://images.unsplash.com/photo-1523050854058-8df90110c9f1?q=80&w=1400&auto=format&fit=crop");
  background-size:cover;
  background-position:center;
  box-shadow:0 35px 90px rgba(15,23,42,.18);
}

.mini-card{
  position:absolute;
  right:0;
  bottom:0;
  width:290px;
  padding:28px;
  border-radius:28px;
  background:#0f172a;
  color:white;
  border:8px solid white;
  box-shadow:0 30px 70px rgba(15,23,42,.25);
}

.mini-card h3{
  color:#facc15;
  font-size:26px;
  margin-bottom:10px;
}

.mini-card p{
  color:#cbd5e1;
  font-size:15px;
}

@media(max-width:900px){
  .about{
    grid-template-columns:1fr;
  }

  h2{
    font-size:38px;
  }

  .visual{
    min-height:360px;
  }

  .main-image{
    inset:0;
  }

  .mini-card{
    position:relative;
    width:100%;
    margin-top:25px;
    border:0;
  }
}
</style>