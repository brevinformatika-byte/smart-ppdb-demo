<template>
  <section class="stats">
    <div class="stat-card">
      <span>01</span>
      <h2>1.200+</h2>
      <p>Siswa Aktif</p>
    </div>

    <div class="stat-card">
      <span>02</span>
      <h2>50+</h2>
      <p>Guru & Staff</p>
    </div>

    <div class="stat-card">
      <span>03</span>
      <h2>4</h2>
      <p>Program Keahlian</p>
    </div>

    <div class="stat-card">
      <span>04</span>
      <h2>95%</h2>
      <p>Lulusan Siap Kerja</p>
    </div>
  </section>
</template>

<style scoped>
.stats{
  position:relative;
  z-index:5;
  margin-top:-80px;
  padding:0 8% 90px;
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:22px;
}

.stat-card{
  background:rgba(255,255,255,.95);
  backdrop-filter:blur(18px);
  padding:35px;
  border-radius:30px;
  box-shadow:0 25px 60px rgba(15,23,42,.12);
  border:1px solid rgba(255,255,255,.7);
}

.stat-card span{
  color:#94a3b8;
  font-weight:900;
}

.stat-card h2{
  font-size:46px;
  color:#2563eb;
  margin:12px 0;
}

.stat-card p{
  color:#64748b;
  font-weight:700;
}

@media(max-width:900px){
  .stats{
    margin-top:0;
    grid-template-columns:1fr;
    padding-top:40px;
  }
}
</style>