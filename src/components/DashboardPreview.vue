<template>
  <section class="dashboard-section">

    <div class="left">

      <span class="badge">
        Dashboard Admin
      </span>

      <h2>
        Semua Data Pendaftar
        Dalam Satu Tampilan
      </h2>

      <p>
        Admin sekolah dapat melihat jumlah pendaftar,
        status verifikasi, jurusan favorit,
        dan statistik PPDB secara realtime.
      </p>

      <div class="feature-list">

        <div>
          ✓ Data Pendaftar
        </div>

        <div>
          ✓ Verifikasi Berkas
        </div>

        <div>
          ✓ Export Excel
        </div>

        <div>
          ✓ Statistik PPDB
        </div>

      </div>

    </div>

    <div class="dashboard">

      <div class="topbar">

        <div>
          Dashboard PPDB
        </div>

        <div class="online">
          Online
        </div>

      </div>

      <div class="stats">

        <div class="stat">
          <small>Total</small>
          <h3>128</h3>
        </div>

        <div class="stat">
          <small>Verifikasi</small>
          <h3>42</h3>
        </div>

        <div class="stat">
          <small>Diterima</small>
          <h3>86</h3>
        </div>

      </div>

      <table>

        <thead>
          <tr>
            <th>Nama</th>
            <th>Jurusan</th>
            <th>Status</th>
          </tr>
        </thead>

        <tbody>

          <tr>
            <td>Ahmad</td>
            <td>TJKT</td>
            <td>
              <span class="success">
                Diterima
              </span>
            </td>
          </tr>

          <tr>
            <td>Siti</td>
            <td>AKL</td>
            <td>
              <span class="pending">
                Verifikasi
              </span>
            </td>
          </tr>

          <tr>
            <td>Rama</td>
            <td>TKR</td>
            <td>
              <span class="success">
                Diterima
              </span>
            </td>
          </tr>

        </tbody>

      </table>

    </div>

  </section>
</template>

<style scoped>

.dashboard-section{
  padding:120px 8%;
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:60px;
  align-items:center;

  background:#020617;
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

.left h2{
  margin:25px 0;
  color:white;
  font-size:60px;
  line-height:1.05;
  letter-spacing:-2px;
}

.left p{
  color:#cbd5e1;
  line-height:1.8;
}

.feature-list{
  display:grid;
  gap:14px;
  margin-top:30px;
}

.feature-list div{
  background:rgba(255,255,255,.08);
  color:white;
  padding:16px;
  border-radius:16px;
}

.dashboard{
  background:white;
  border-radius:35px;
  padding:30px;

  box-shadow:
  0 35px 90px
  rgba(0,0,0,.3);
}

.topbar{
  display:flex;
  justify-content:space-between;
  margin-bottom:25px;
}

.online{
  background:#dcfce7;
  color:#15803d;
  padding:8px 14px;
  border-radius:999px;
  font-size:13px;
  font-weight:800;
}

.stats{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:15px;
  margin-bottom:25px;
}

.stat{
  background:#eff6ff;
  padding:18px;
  border-radius:18px;
}

.stat small{
  color:#64748b;
}

.stat h3{
  font-size:34px;
  color:#2563eb;
}

table{
  width:100%;
  border-collapse:collapse;
}

th,td{
  text-align:left;
  padding:14px;
  border-bottom:1px solid #e5e7eb;
}

.success{
  background:#dcfce7;
  color:#15803d;
  padding:6px 12px;
  border-radius:999px;
  font-size:12px;
  font-weight:800;
}

.pending{
  background:#fef3c7;
  color:#92400e;
  padding:6px 12px;
  border-radius:999px;
  font-size:12px;
  font-weight:800;
}

@media(max-width:900px){

.dashboard-section{
grid-template-columns:1fr;
}

.left h2{
font-size:38px;
}

.stats{
grid-template-columns:1fr;
}

}
</style>