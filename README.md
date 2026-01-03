
# primeclean<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PrimeClean Auto Detailing</title>
<style>
body {margin:0; font-family: Arial, sans-serif; background:#f4f4f4; color:#222;}
header {background:#0b3c91; color:white; text-align:center; padding:25px 15px;}
header img {width:140px; display:block; margin:0 auto 15px;}
section {padding:30px 15px; max-width:900px; margin:auto;}
h2 {color:#0b3c91; text-align:center; margin-bottom:20px;}
.card {background:white; padding:20px; border-radius:8px; margin-bottom:20px;}
button {background:#0b3c91; color:white; border:none; padding:15px; width:100%; font-size:16px; border-radius:6px; cursor:pointer;}
button:hover {background:#555;}
footer {background:#0b3c91; color:white; text-align:center; padding:20px;}
table {width:100%; border-collapse:collapse; margin:0 auto;}
th, td {padding:12px; font-size:1em; text-align:left;}
th {background:#333; color:white;}
tr {border-bottom:1px solid #ccc;}
/* GALERIA PO */
.after-gallery {max-width:1000px; margin:50px auto; text-align:center;}
.after-gallery img {width:100%; height:auto; border-radius:10px; box-shadow:0 4px 10px rgba(0,0,0,0.2);}
.caption {padding:10px 15px; background:#f5f5f5; text-align:center;}
.caption h3 {margin:5px 0; font-size:20px;}
.caption p {margin:0; font-size:16px; color:#555;}
/* PAKIETY */
.pakiety {display:flex; flex-wrap:wrap; gap:20px; justify-content:center;}
.pakiet-card {flex:1 1 280px; background:#f9f9f9; border-radius:10px; padding:30px; box-shadow:0 4px 10px rgba(0,0,0,0.1); transition: transform 0.3s, box-shadow 0.3s;}
.pakiet-card:hover {transform:translateY(-10px); box-shadow:0 8px 20px rgba(0,0,0,0.2);}
@media(max-width:600px){.pakiety{flex-direction:column;}}
</style>
</head>
<body>

<header>
  <img src="logo.png.PNG" alt="PrimeClean Logo">
  <h1>PrimeClean Auto Detailing</h1>
  <p>Profesjonalny detailing samochodowy</p>
</header>

<section>
  <h2>Usługi</h2>
  <div class="card">Mycie detailingowe</div>
  <div class="card">Czyszczenie wnętrza</div>
  <div class="card">Pranie tapicerki</div>
  <div class="card">Polerowanie i wosk</div>
</section>

<section>
  <h2>Cennik usług detailingu</h2>
  <table>
    <tr><th>Usługa</th><th>Cena</th></tr>
    <tr><td>Mycie zewnętrzne auta</td><td>100 zł</td></tr>
    <tr><td>Detailing wnętrza</td><td>150 zł</td></tr>
    <tr><td>Woskowanie lakieru</td><td>200 zł</td></tr>
    <tr><td>Renowacja reflektorów</td><td>120 zł</td></tr>
    <tr><td>Pełny pakiet detailingowy</td><td>500 zł</td></tr>
  </table>
  <p style="margin-top:10px; color:#666; font-size:0.9em;">* Ceny mogą się różnić w zależności od wielkości auta i zakresu usług.</p>
</section>

<section id="o-nas">
  <h2>O nas</h2>
  <p>W naszym detailingu w Bielsko-Białej pasja spotyka się z perfekcją. Każde auto traktujemy jak własne – przywracamy blask lakierowi, dbamy o wnętrze i sprawiamy, że Twój samochód wygląda jak nowy.</p>
  <p>Niezależnie od tego, czy chcesz błyszczące auto na weekend, czy pełen pakiet renowacyjny – u nas Twój samochód jest w najlepszych rękach!</p>
</section>

<section id="rezerwacja" style="background:#f9f9f9;">
  <h2>Zarezerwuj wizytę</h2>
  <p>Wypełnij formularz, a my skontaktujemy się z Tobą, aby potwierdzić termin i dopasować usługę do potrzeb.</p>
  <form action="https://formspree.io/f/mnqwnzkw" method="POST" style="display:flex; flex-direction:column; gap:15px;">
    <input type="text" name="name" placeholder="Imię i nazwisko" required>
    <input type="email" name="email" placeholder="E-mail" required>
    <input type="tel" name="phone" placeholder="Numer telefonu" required>
    <select name="service" required>
      <option value="">Wybierz usługę</option>
      <option value="mycie">Mycie zewnętrzne auta</option>
      <option value="wnetrze">Detailing wnętrza</option>
      <option value="woskowanie">Woskowanie lakieru</option>
      <option value="reflektory">Renowacja reflektorów</option>
      <option value="pelny-pakiet">Pełny pakiet detailingowy</option>
    </select>
    <input type="date" name="date" required>
    <textarea name="message" placeholder="Dodatkowe informacje (opcjonalnie)" rows="4"></textarea>
    <button type="submit">ZAREZERWUJ TERAZ</button>
  </form>
</section>

<section style="text-align:center; margin:30px auto; max-width:800px; padding:15px; border:2px dashed #222; border-radius:10px; background:#fefefe;">
  <h3>Pakiety dla firm</h3>
  <p>Prowadzisz firmę lub flotę samochodów? Oferujemy specjalne pakiety detailingowe dla firm – możliwość regularnej obsługi, atrakcyjne rabaty i faktury dla firm. Skontaktuj się z nami, aby dopasować usługę do potrzeb Twojej floty.</p>
</section>

<section id="pakiety" style="background:#fff;">
  <h2>Promocje i Pakiety</h2>
  <div class="pakiety">
    <div class="pakiet-card">
      <h3>Basic</h3>
      <p>Idealny dla szybkiego odświeżenia auta. Mycie + wosk ochronny.</p>
      <p><strong>150 zł</strong></p>
      <button>Zarezerwuj</button>
    </div>
    <div class="pakiet-card">
      <h3>Premium</h3>
      <p>Kompleksowy detailing wnętrza i zewnątrz. Mycie, woskowanie, odkurzanie i czyszczenie tapicerki.</p>
      <p><strong>300 zł</strong></p>
      <button>Zarezerwuj</button>
    </div>
    <div class="pakiet-card">
      <h3>Full</h3>
      <p>Pełny pakiet premium – detailing auta od A do Z. Mycie, woskowanie, polerowanie, czyszczenie tapicerki, renowacja reflektorów.</p>
      <p><strong>500 zł</strong></p>
      <button>Zarezerwuj</button>
    </div>
  </div>
</section>

<section class="after-gallery">
  <h2>Nasze realizacje</h2>
  <p>Ford Focus MK2 – efekt detailingu</p>
  <div class="after-container">
    <img src="ford focus mk2 po.jpg.JPG" alt="Ford Focus MK2 po detailingu">
    <div class="caption">
      <h3>Ford Focus MK2</h3>
      <p>Pełne czyszczenie z zewnątrz</p>
    </div>
  </div>
</section>

<footer>
  © 2026 PrimeClean Auto Detailing
</footer>

</body>
</html>
