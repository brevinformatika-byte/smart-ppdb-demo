<template>
  <section id="home" class="hero">
    <div class="hero-left">
      <span class="eyebrow">SMK AL HUSAIN KELING</span>

      <h1>
        Membangun Generasi Berkarakter, Kompeten, dan Siap Kerja.
      </h1>

      <p>
        Portal digital sekolah modern untuk informasi profil, jurusan, kegiatan,
        prestasi, dan PPDB online dalam satu platform yang rapi dan mudah diakses.
      </p>

      <div class="actions">
        <a href="#ppdb" class="primary">Daftar Sekarang</a>
        <a href="#profil" class="secondary">Lihat Profil</a>
      </div>

      <div class="mini-stats">
        <div><b>1200+</b><span>Siswa</span></div>
        <div><b>50+</b><span>Guru</span></div>
        <div><b>95%</b><span>Lulus Kerja</span></div>
      </div>
    </div>

    <div class="hero-right">
      <div class="ppdb-card">
        <div class="card-head">
          <div class="logo">AH</div>
          <div>
            <h3>Portal PPDB</h3>
            <p>Tahun Ajaran 2026/2027</p>
          </div>
        </div>

        <div class="row"><span>Status</span><b class="open">Dibuka</b></div>
        <div class="row"><span>Gelombang</span><b>Gelombang 1</b></div>
        <div class="row"><span>Akses</span><b>Online 24 Jam</b></div>

        <a href="#ppdb" class="card-btn">Mulai Pendaftaran</a>
      </div>
    </div>
  </section>
</template>

<style scoped>
.hero{
  min-height:100vh;
  display:grid;
  grid-template-columns:58% 42%;
  gap:50px;
  align-items:center;
  padding:150px 8% 90px;
  background:
    linear-gradient(90deg, rgba(2,6,23,.82), rgba(2,6,23,.42)),
    url("https://images.unsplash.com/photo-1562774053-701939374585?q=80&w=1800&auto=format&fit=crop");
  background-size:cover;
  background-position:center;
  color:white;
}

.hero-left{
  max-width:760px;
}

.eyebrow{
  color:#facc15;
  font-weight:900;
  letter-spacing:2px;
  font-size:14px;
}

h1{
  font-size:64px;
  line-height:1.05;
  letter-spacing:-2px;
  margin:22px 0;
}

p{
  font-size:18px;
  line-height:1.8;
  color:#e2e8f0;
  max-width:650px;
}

.actions{
  display:flex;
  gap:14px;
  margin-top:30px;
}

.primary,
.secondary,
.card-btn{
  padding:15px 24px;
  border-radius:999px;
  text-decoration:none;
  font-weight:900;
}

.primary{
  background:#facc15;
  color:#111827;
}

.secondary{
  color:white;
  border:1px solid rgba(255,255,255,.45);
}

.mini-stats{
  display:flex;
  gap:45px;
  margin-top:46px;
}

.mini-stats b{
  display:block;
  color:#facc15;
  font-size:38px;
}

.mini-stats span{
  color:#cbd5e1;
}

.hero-right{
  display:flex;
  justify-content:flex-end;
}

.ppdb-card{
  width:100%;
  max-width:450px;
  background:rgba(255,255,255,.96);
  color:#0f172a;
  padding:34px;
  border-radius:32px;
  box-shadow:0 35px 90px rgba(0,0,0,.32);
}

.card-head{
  display:flex;
  align-items:center;
  gap:15px;
  margin-bottom:26px;
}

.logo{
  width:56px;
  height:56px;
  border-radius:50%;
  display:grid;
  place-items:center;
  font-weight:900;
  color:white;
  background:linear-gradient(135deg,#facc15,#2563eb);
}

.card-head h3{
  font-size:27px;
}

.card-head p{
  color:#64748b;
  font-size:14px;
}

.row{
  display:flex;
  justify-content:space-between;
  padding:17px 0;
  border-bottom:1px solid #e5e7eb;
}

.open{
  color:#16a34a;
}

.card-btn{
  display:block;
  text-align:center;
  background:#2563eb;
  color:white;
  margin-top:25px;
}

@media(max-width:900px){
  .hero{
    grid-template-columns:1fr;
    padding:130px 6% 70px;
  }

  h1{
    font-size:42px;
  }

  .hero-right{
    justify-content:flex-start;
  }

  .mini-stats{
    gap:24px;
    flex-wrap:wrap;
  }
}
</style>