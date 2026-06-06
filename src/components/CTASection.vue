<template>
  <section class="cta">
    <div class="overlay">
      <span>Website Sekolah & PPDB Online</span>

      <h2>
        Siap Menghadirkan Website Sekolah yang Lebih Modern?
      </h2>

      <p>
        Demo ini dapat disesuaikan dengan identitas sekolah, kebutuhan fitur,
        warna branding, jurusan, konten, dan sistem PPDB yang diinginkan.
      </p>

      <div class="actions">
        <a href="#ppdb">Lihat Form PPDB</a>
        <a class="whatsapp" href="https://wa.me/6288228988088" target="_blank">
          Konsultasi WhatsApp
        </a>
      </div>
    </div>
  </section>
</template>

<style scoped>
.cta{
  margin:90px 8%;
  border-radius:44px;
  overflow:hidden;
  background:
    linear-gradient(135deg,rgba(37,99,235,.92),rgba(2,6,23,.95)),
    url("https://images.unsplash.com/photo-1571260899304-425eee4c7efc?q=80&w=1600&auto=format&fit=crop");
  background-size:cover;
  background-position:center;
  color:white;
}

.overlay{
  padding:90px 50px;
  text-align:center;
}

span{
  display:inline-block;
  background:#facc15;
  color:#111827;
  padding:10px 18px;
  border-radius:999px;
  font-size:13px;
  font-weight:900;
}

h2{
  max-width:900px;
  margin:25px auto;
  font-size:58px;
  line-height:1.08;
  letter-spacing:-2px;
}

p{
  max-width:760px;
  margin:0 auto;
  color:#dbeafe;
  font-size:18px;
  line-height:1.8;
}

.actions{
  margin-top:35px;
  display:flex;
  justify-content:center;
  gap:15px;
}

a{
  background:#facc15;
  color:#111827;
  padding:16px 26px;
  border-radius:999px;
  text-decoration:none;
  font-weight:900;
}

.whatsapp{
  background:white;
}

@media(max-width:900px){
  .cta{
    margin:50px 5%;
  }

  .overlay{
    padding:60px 25px;
  }

  h2{
    font-size:36px;
  }

  .actions{
    flex-direction:column;
  }
}
</style>