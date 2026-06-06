<template>
  <section id="alur" class="flow">
    <div class="head">
      <span>Alur PPDB Online</span>
      <h2>Pendaftaran Lebih Mudah dalam 4 Langkah</h2>
      <p>Calon siswa dan orang tua dapat memahami proses pendaftaran dengan jelas dari awal sampai akhir.</p>
    </div>

    <div class="timeline">
      <div class="step">
        <b>01</b>
        <h3>Isi Formulir</h3>
        <p>Calon siswa mengisi data diri dan memilih jurusan melalui website.</p>
      </div>

      <div class="step">
        <b>02</b>
        <h3>Kirim Data</h3>
        <p>Data pendaftaran masuk ke sistem sekolah secara digital.</p>
      </div>

      <div class="step">
        <b>03</b>
        <h3>Verifikasi</h3>
        <p>Admin sekolah mengecek data calon siswa dengan lebih rapi.</p>
      </div>

      <div class="step">
        <b>04</b>
        <h3>Pengumuman</h3>
        <p>Informasi hasil pendaftaran dapat disampaikan lebih cepat.</p>
      </div>
    </div>
  </section>
</template>

<style scoped>
.flow{
  padding:120px 8%;
  background:#f8fafc;
}

.head{
  text-align:center;
  max-width:850px;
  margin:0 auto 70px;
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
  margin:24px 0;
  font-size:56px;
  line-height:1.1;
  letter-spacing:-2px;
}

.head p{
  color:#64748b;
  font-size:18px;
  line-height:1.8;
}

.timeline{
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:25px;
}

.step{
  position:relative;
  background:white;
  padding:36px;
  border-radius:32px;
  box-shadow:0 20px 50px rgba(15,23,42,.08);
  border:1px solid #e5e7eb;
}

.step::before{
  content:"";
  position:absolute;
  top:0;
  left:35px;
  width:70px;
  height:6px;
  border-radius:999px;
  background:#2563eb;
}

.step b{
  display:block;
  margin-top:18px;
  font-size:42px;
  color:#facc15;
}

.step h3{
  margin:18px 0 12px;
  font-size:26px;
  color:#0f172a;
}

.step p{
  color:#64748b;
  line-height:1.7;
}

@media(max-width:900px){
  .timeline{
    grid-template-columns:1fr;
  }

  .head h2{
    font-size:38px;
  }
}
</style>    