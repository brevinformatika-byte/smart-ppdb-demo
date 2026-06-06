<template>
  <footer class="footer">
    <div class="footer-logo">AH</div>

    <h2>SMK AL HUSAIN KELING</h2>

    <p>
      Demo Website Sekolah & PPDB Online
    </p>

    <span>
      Developed by Alfathir Brevy
    </span>

    <a class="wa-float" href="https://wa.me/6288228988088" target="_blank">
      WhatsApp
    </a>
  </footer>
</template>

<style scoped>
.footer{
  position:relative;
  background:#020617;
  color:white;
  text-align:center;
  padding:70px 20px;
}

.footer-logo{
  width:64px;
  height:64px;
  border-radius:50%;
  margin:0 auto 20px;
  display:grid;
  place-items:center;
  font-weight:900;
  color:white;
  background:linear-gradient(135deg,#facc15,#2563eb);
}

h2{
  font-size:30px;
}

p{
  color:#cbd5e1;
  margin:12px 0;
}

span{
  color:#facc15;
  font-weight:900;
}

.wa-float{
  position:fixed;
  right:24px;
  bottom:24px;
  z-index:999;
  background:#22c55e;
  color:white;
  padding:15px 22px;
  border-radius:999px;
  text-decoration:none;
  font-weight:900;
  box-shadow:0 18px 40px rgba(34,197,94,.35);
}

@media(max-width:900px){
  .wa-float{
    right:14px;
    bottom:14px;
    padding:13px 18px;
  }
}
</style>