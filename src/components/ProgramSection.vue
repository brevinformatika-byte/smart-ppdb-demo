<template>
  <section id="jurusan" class="program-section">

    <span class="badge">
      Program Keahlian
    </span>

    <h2>
      Pilih Jurusan Sesuai Minat dan Karier Masa Depan
    </h2>

    <p class="subtitle">
      Program keahlian yang dirancang sesuai kebutuhan industri
      dan perkembangan teknologi saat ini.
    </p>

    <div class="program-grid">

      <div class="card">
        <div class="number">01</div>

        <h3>TJKT</h3>

        <p>
          Teknik Jaringan Komputer dan Telekomunikasi
        </p>

        <span>Networking • Server • Cyber Security</span>
      </div>

      <div class="card">
        <div class="number">02</div>

        <h3>AKL</h3>

        <p>
          Akuntansi dan Keuangan Lembaga
        </p>

        <span>Finance • Accounting • Tax</span>
      </div>

      <div class="card">
        <div class="number">03</div>

        <h3>MPLB</h3>

        <p>
          Manajemen Perkantoran dan Layanan Bisnis
        </p>

        <span>Administration • Office • Service</span>
      </div>

      <div class="card">
        <div class="number">04</div>

        <h3>TKR</h3>

        <p>
          Teknik Kendaraan Ringan Otomotif
        </p>

        <span>Engine • Automotive • Workshop</span>
      </div>

    </div>

  </section>
</template>

<style scoped>

.program-section{
  padding:120px 8%;
  background:#020617;
  text-align:center;
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
  color:white;
  font-size:58px;
  max-width:900px;
  margin:25px auto;
  line-height:1.1;
  letter-spacing:-2px;
}

.subtitle{
  max-width:700px;
  margin:auto;
  color:#94a3b8;
  line-height:1.8;
}

.program-grid{
  margin-top:70px;

  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:25px;
}

.card{
  background:white;
  padding:35px;
  border-radius:30px;
  text-align:left;

  transition:.3s;

  box-shadow:
  0 20px 50px
  rgba(0,0,0,.15);
}

.card:hover{
  transform:
  translateY(-12px);
}

.number{
  font-size:40px;
  font-weight:900;
  color:#facc15;
}

.card h3{
  margin-top:15px;
  font-size:32px;
  color:#2563eb;
}

.card p{
  margin-top:15px;
  color:#475569;
  line-height:1.7;
}

.card span{
  display:block;
  margin-top:20px;
  color:#64748b;
  font-size:14px;
  font-weight:700;
}

@media(max-width:900px){

.program-grid{
grid-template-columns:1fr;
}

h2{
font-size:38px;
}

}
</style>