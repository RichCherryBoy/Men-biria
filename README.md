<!doctype html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Los Costalitos — Menú Digital</title>
<style>
:root{
  --cream:#fff8e9; --paper:#fffdf7; --brown:#4d2e16;
  --red:#b8171d; --gold:#e59a08; --muted:#6e6256;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  margin:0;background:var(--cream);color:#17120e;
  font-family:Arial,Helvetica,sans-serif;
}
.page{
  width:min(760px,92vw); margin:0 auto; padding:18px 0 48px;
}
.hero{text-align:center;padding:10px 0 8px}
.logo{width:270px;max-width:72vw;height:auto;display:block;margin:0 auto 4px}
.tagline{
  color:var(--red);font-weight:800;font-size:19px;
  font-family:Arial,Helvetica,sans-serif;margin:0 0 18px;
}
.subtitle{font-size:16px;color:#5b5148;margin-bottom:28px}
.divider{
  height:3px;border:0;border-top:3px dashed var(--gold);
  width:62%;margin:0 auto 25px;
}
.section-title{
  color:var(--red);font-size:25px;font-weight:900;
  text-align:center;margin:0 0 18px;
}
.card{
  position:relative;background:var(--paper);border:2px solid var(--brown);
  border-radius:19px;padding:28px 20px 17px;margin:0 0 14px;
  box-shadow:5px 5px 0 rgba(90,55,25,.13);
}
.card:before{
  content:"";position:absolute;left:18px;top:-10px;width:34px;height:20px;
  background:#e6a20c;border:2px solid var(--brown);border-radius:4px;
  transform:rotate(-3deg);
}
.item{display:flex;justify-content:space-between;gap:18px;border-bottom:1px dotted #cfc5b8;padding:0 0 10px;margin:0 0 10px}
.item:last-child{border-bottom:0;margin-bottom:0;padding-bottom:0}
.name{font-size:18px;font-weight:800}
.desc{font-size:14px;color:#4f4740;margin-top:5px;line-height:1.35}
.price{color:var(--red);font-size:18px;font-weight:900;white-space:nowrap}
.qrbox{
  background:var(--paper);border:2px solid var(--brown);border-radius:19px;
  padding:20px;text-align:center;margin-top:42px;box-shadow:5px 5px 0 rgba(90,55,25,.13)
}
.qrbox img{width:260px;max-width:70vw;height:auto;image-rendering:pixelated}
.qrtitle{color:var(--red);font-weight:900;font-size:18px;margin:10px 0}
.small{color:#62584f;font-size:14px}
.contact{text-align:center;margin:22px 0 12px;line-height:1.6;font-size:15px}
.contact strong{font-size:18px}
.notice{
  background:#fffdf7;border:1px solid #d9cdbd;border-radius:15px;
  padding:22px 28px;margin-top:20px;
}
.notice h3{text-align:center;color:var(--red);margin:0 0 14px;font-size:17px}
.notice li{margin:9px 0;line-height:1.35;font-size:14px}
.footer{text-align:center;font-weight:700;margin-top:18px;color:#4e3a28}
@media(max-width:560px){
  .page{width:92vw}
  .card{padding-left:17px;padding-right:17px}
  .item{gap:10px}
  .name,.price{font-size:16px}
  .section-title{font-size:23px}
}
</style>
</head>
<body>
<main class="page">
  <header class="hero">
    <img class="logo" src="los_costalitos_logo.png" alt="Los Costalitos">
    <p class="tagline">Sazón que canta, sabor que se queda</p>
    <div class="subtitle">Menú digital</div>
    <hr class="divider">
  </header>

  <h1 class="section-title">Deliciosa Birria</h1>

  <section class="card">
    <div class="item">
      <div><div class="name">Birria</div><div class="desc">Guisada a fuego lento, receta de la casa</div></div>
    </div>
    <div class="item"><div class="name">1/2 litro</div><div class="price">$60</div></div>
    <div class="item"><div class="name">1 litro</div><div class="price">$150</div></div>
  </section>

  <section class="card">
    <div class="item">
      <div><div class="name">Tacos de Birria</div><div class="desc">Orden, tortilla de maíz recién hecha</div></div>
      <div class="price">$35</div>
    </div>
    <div class="item">
      <div><div class="name">Quesabirria</div><div class="desc">Con queso derretido y consomé</div></div>
      <div class="price">$45</div>
    </div>
  </section>

  <!-- Agrega aquí el resto de tus productos siguiendo el mismo formato. -->

  <section class="qrbox">
    <img src="menu_qr.png" alt="Código QR del menú">
    <div class="qrtitle">Escanea y comparte el menú</div>
    <div class="small">Guárdalo en tu celular para consultarlo cuando quieras</div>
  </section>

  <div class="contact">
    <div style="color:var(--red);font-weight:900;font-size:17px">¡Te esperamos viernes de 8 a 4!</div>
    <div>📍 <strong>Av. Guadalupe I. Ramírez 280, San Marcos, Xochimilco, 16050 CDMX</strong></div>
    <div>🕘 Viernes de 8:00 am a 4:00 pm &nbsp; · &nbsp; 📞 55 1883 9130</div>
  </div>

  <section class="notice">
    <h3>Aviso al consumidor</h3>
    <ul>
      <li>Precios expresados en pesos mexicanos (MXN) e incluyen IVA.</li>
      <li>Precios sujetos a cambio sin previo aviso.</li>
      <li>La propina es voluntaria y no está incluida en el precio de los alimentos y bebidas.</li>
      <li>Prohibida la venta de bebidas alcohólicas a menores de edad; se podrá solicitar identificación oficial.</li>
      <li>Si tienes alguna alergia o restricción alimentaria, coméntalo con tu mesero antes de ordenar.</li>
      <li>Establecimiento libre de humo, conforme a la Ley General para el Control del Tabaco.</li>
    </ul>
  </section>

  <div class="footer">Los Costalitos · Café Karaoke Bar · Xochimilco, CDMX</div>
</main>
</body>
</html>
