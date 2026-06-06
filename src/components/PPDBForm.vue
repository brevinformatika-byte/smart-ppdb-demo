<template>
  <section id="ppdb" class="ppdb-section">
    <div class="left">
      <span class="badge">Form PPDB Online</span>

      <h2>
        Pendaftaran Siswa Baru Kini Bisa Dilakukan dari Smartphone.
      </h2>

      <p>
        Calon siswa dapat mengisi formulir pendaftaran secara online. Untuk versi
        asli, data dapat disimpan ke database dan dikelola melalui dashboard admin.
      </p>

      <div class="points">
        <div>✓ Form pendaftaran online</div>
        <div>✓ Pilihan jurusan otomatis</div>
        <div>✓ Integrasi WhatsApp</div>
        <div>✓ Rekap data pendaftar</div>
      </div>
    </div>

    <form class="form-card">
      <h3>Form Pendaftaran</h3>

      <input type="text" placeholder="Nama Lengkap" />
      <input type="text" placeholder="Asal Sekolah" />
      <input type="text" placeholder="Nomor WhatsApp" />

      <select>
        <option>Pilih Jurusan</option>
        <option>TJKT</option>
        <option>AKL</option>
        <option>MPLB</option>
        <option>TKR</option>
      </select>

      <textarea placeholder="Alamat Lengkap"></textarea>

      <button type="button">
        Kirim Pendaftaran
      </button>
    </form>
  </section>
</template>

<style scoped>
.ppdb-section{
  padding:120px 8%;
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:65px;
  align-items:center;
  background:linear-gradient(135deg,#eff6ff,#ffffff);
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
  font-size:58px;
  line-height:1.08;
  letter-spacing:-2px;
  margin:25px 0;
  color:#0f172a;
}

p{
  color:#475569;
  line-height:1.8;
  font-size:18px;
}

.points{
  margin-top:30px;
  display:grid;
  gap:14px;
}

.points div{
  background:white;
  padding:16px 20px;
  border-radius:18px;
  font-weight:800;
  color:#0f172a;
  box-shadow:0 15px 35px rgba(15,23,42,.07);
}

.form-card{
  background:white;
  padding:36px;
  border-radius:34px;
  box-shadow:0 30px 80px rgba(15,23,42,.13);
}

.form-card h3{
  font-size:32px;
  margin-bottom:25px;
}

input,
select,
textarea{
  width:100%;
  padding:16px;
  margin-bottom:15px;
  border:1px solid #d1d5db;
  border-radius:16px;
  font-size:15px;
  font-family:inherit;
}

textarea{
  min-height:110px;
  resize:none;
}

button{
  width:100%;
  background:#2563eb;
  color:white;
  border:none;
  padding:17px;
  border-radius:16px;
  font-weight:900;
  cursor:pointer;
}

@media(max-width:900px){
  .ppdb-section{
    grid-template-columns:1fr;
  }

  h2{
    font-size:38px;
  }
}
</style>