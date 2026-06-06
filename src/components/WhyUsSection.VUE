<template>

<section class="why">

<div class="title">

<span>Mengapa Website?</span>

<h2>
Transformasi Digital
Sekolah Modern
</h2>

</div>

<div class="grid">

<div class="item">
<h3>PPDB Online</h3>
<p>Pendaftaran lebih mudah dan cepat.</p>
</div>

<div class="item">
<h3>Promosi Sekolah</h3>
<p>Informasi sekolah lebih profesional.</p>
</div>

<div class="item">
<h3>Dashboard Admin</h3>
<p>Data pendaftar lebih rapi.</p>
</div>

<div class="item">
<h3>Responsive</h3>
<p>Bisa dibuka dari HP maupun laptop.</p>
</div>

</div>

</section>

</template>

<style scoped>

.why{
padding:120px 8%;
background:white;
}

.title{
text-align:center;
margin-bottom:60px;
}

.title span{
background:#facc15;
padding:10px 18px;
border-radius:999px;
font-weight:900;
}

.title h2{
margin-top:25px;
font-size:58px;
}

.grid{
display:grid;
grid-template-columns:repeat(4,1fr);
gap:20px;
}

.item{
padding:35px;
border-radius:30px;
background:#f8fafc;

transition:.3s;
}

.item:hover{
transform:translateY(-10px);
}

.item h3{
font-size:28px;
margin-bottom:10px;
color:#2563eb;
}

.item p{
color:#64748b;
}

</style>