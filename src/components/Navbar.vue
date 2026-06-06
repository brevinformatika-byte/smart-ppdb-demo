<template>
  <header class="navbar">
    <div class="brand">
      <div class="logo">AH</div>
      <div>
        <h3>SMK AL HUSAIN KELING</h3>
        <span>Digital School Portal</span>
      </div>
    </div>

    <nav class="menu">
      <a href="#home">Beranda</a>
      <a href="#profil">Profil</a>
      <a href="#jurusan">Jurusan</a>
      <a href="#alur">Alur PPDB</a>
      <a href="#ppdb">Daftar</a>
    </nav>

    <a href="#ppdb" class="nav-btn">PPDB Online</a>
  </header>
</template>

<style scoped>
.navbar{
  position:fixed;
  top:20px;
  left:50%;
  transform:translateX(-50%);
  width:86%;
  z-index:1000;
  display:flex;
  justify-content:space-between;
  align-items:center;
  padding:10px 18px;
  background:rgba(255,255,255,.94);
  backdrop-filter:blur(18px);
  border-radius:999px;
  box-shadow:0 18px 45px rgba(15,23,42,.16);
}

.brand{
  display:flex;
  align-items:center;
  gap:12px;
}

.logo{
  width:46px;
  height:46px;
  border-radius:50%;
  display:grid;
  place-items:center;
  font-weight:900;
  color:white;
  background:linear-gradient(135deg,#facc15,#2563eb);
}

.brand h3{
  font-size:14px;
  color:#0f172a;
}

.brand span{
  font-size:12px;
  color:#64748b;
}

.menu{
  display:flex;
  gap:24px;
}

.menu a{
  text-decoration:none;
  color:#334155;
  font-weight:800;
  font-size:14px;
}

.nav-btn{
  background:#0f172a;
  color:white;
  padding:13px 22px;
  border-radius:999px;
  text-decoration:none;
  font-weight:900;
}

@media(max-width:900px){
  .navbar{
    width:94%;
    top:10px;
  }

  .menu,
  .nav-btn{
    display:none;
  }
}
</style>