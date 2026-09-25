# zano-travels
ZANO TRAVELS official website 
ZANO TRAVELS FREE WEBSITE
=========================
Files:
- index.html = complete responsive website

FREE HOSTING:
1. Create a free GitHub account.
2. Create a new PUBLIC repository, e.g. zano-travels.
3. Upload index.html.
4. Repository Settings -> Pages -> Deploy from branch -> main -> /root.
5. Save. GitHub will provide a free pages address.

The website already includes ZANO TRAVELS green branding, WhatsApp, phone, email,
services, Umrah, tours, visa and contact sections.
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ZANO TRAVELS | Travel • Umrah • Visa • Flights</title>
<meta name="description" content="ZANO TRAVELS - Flights, Umrah packages, tours and visa services in Karachi, Pakistan.">
<style>
:root{--green:#087f5b;--dark:#07533f;--light:#f1fbf7;--gold:#d6a83b;--text:#18352d}
*{box-sizing:border-box}body{margin:0;font-family:Arial,Helvetica,sans-serif;color:var(--text);background:#fff;line-height:1.6}
header{background:linear-gradient(135deg,var(--dark),var(--green));color:white;position:sticky;top:0;z-index:10;box-shadow:0 3px 15px #0002}
.nav{max-width:1150px;margin:auto;padding:14px 20px;display:flex;align-items:center;justify-content:space-between;gap:20px}
.logo{font-size:27px;font-weight:900;letter-spacing:2px}.logo span{color:#ffe28a}
nav a{color:white;text-decoration:none;margin-left:18px;font-weight:600;font-size:14px}
.hero{background:linear-gradient(135deg,#eafff7,#fff);padding:75px 20px}
.hero-inner{max-width:1150px;margin:auto;display:grid;grid-template-columns:1.3fr .7fr;gap:35px;align-items:center}
.badge{display:inline-block;background:#d9f5ea;color:var(--dark);padding:7px 13px;border-radius:30px;font-weight:bold}
h1{font-size:52px;line-height:1.08;margin:18px 0 15px;color:var(--dark)}h1 span{color:var(--green)}
.hero p{font-size:19px;max-width:650px}
.btn{display:inline-block;padding:13px 21px;border-radius:8px;text-decoration:none;font-weight:bold;margin:7px 6px 7px 0}
.primary{background:var(--green);color:#fff}.secondary{border:2px solid var(--green);color:var(--green)}
.hero-card{background:white;border-radius:18px;padding:28px;box-shadow:0 12px 35px #087f5b22;border-top:5px solid var(--gold)}
section{padding:65px 20px}.container{max-width:1150px;margin:auto}
.section-title{text-align:center;font-size:34px;color:var(--dark);margin:0 0 10px}.sub{text-align:center;color:#58736b;margin:0 auto 35px}
.grid{display:grid;grid-template-columns:repeat(4,1fr);gap:18px}.card{padding:25px;border-radius:15px;background:white;border:1px solid #dcece6;box-shadow:0 7px 22px #00000008}.card h3{color:var(--dark);margin-top:8px}.icon{font-size:34px}
.alt{background:var(--light)}
.package{display:flex;flex-direction:column}.price{font-size:24px;color:var(--green);font-weight:bold;margin:10px 0}.package a{margin-top:auto}
.contact{display:grid;grid-template-columns:1fr 1fr;gap:25px}.contact-box{background:var(--dark);color:#fff;padding:32px;border-radius:18px}.contact-box a{color:#fff}
footer{background:#04382d;color:#d9eee8;text-align:center;padding:28px 20px}
.small{font-size:13px;color:#6a817a}.whatsapp{position:fixed;right:20px;bottom:20px;background:#25D366;color:#fff;border-radius:50px;padding:14px 19px;text-decoration:none;font-weight:bold;box-shadow:0 5px 18px #0003;z-index:20}
@media(max-width:800px){nav{display:none}.hero-inner,.contact{grid-template-columns:1fr}h1{font-size:39px}.grid{grid-template-columns:1fr 1fr}}
@media(max-width:500px){.grid{grid-template-columns:1fr}.hero{padding:50px 18px}section{padding:48px 18px}}
</style>
</head>
<body>
<header>
<div class="nav">
<div class="logo">ZANO <span>TRAVELS</span></div>
<nav><a href="#home">Home</a><a href="#services">Services</a><a href="#umrah">Umrah</a><a href="#tours">Tours</a><a href="#visa">Visa</a><a href="#contact">Contact</a></nav>
</div>
</header>

<main>
<section class="hero" id="home">
<div class="hero-inner">
<div>
<span class="badge">✈️ Travel with confidence</span>
<h1>Your Journey,<br><span>Our Responsibility.</span></h1>
<p>ZANO TRAVELS — Flights, Umrah Packages, International Tours & Visa Services from Karachi.</p>
<a class="btn primary" href="https://wa.me/923132523059">WhatsApp Us</a>
<a class="btn secondary" href="#services">Explore Services</a>
</div>
<div class="hero-card">
<h2>🌍 ZANO TRAVELS</h2>
<p>Complete travel solutions for individuals, families and groups.</p>
<p>✈️ Airline Tickets<br>🕋 Umrah Packages<br>🛂 Visa Services<br>🏨 Hotels & Tours</p>
<a class="btn primary" href="#contact">Get a Quote</a>
</div>
</div>
</section>

<section id="services">
<div class="container">
<h2 class="section-title">Our Services</h2><p class="sub">Everything you need for a smooth international journey.</p>
<div class="grid">
<div class="card"><div class="icon">✈️</div><h3>Airline Tickets</h3><p>Domestic and international flight booking with multiple airline options.</p></div>
<div class="card"><div class="icon">🕋</div><h3>Umrah Packages</h3><p>Hotel, visa, flights, transport and ziyarat packages.</p></div>
<div class="card"><div class="icon">🛂</div><h3>Visa Services</h3><p>Tourist visa assistance for selected destinations worldwide.</p></div>
<div class="card"><div class="icon">🌍</div><h3>Tour Packages</h3><p>Customized and group tours for families and travelers.</p></div>
</div>
</div>
</section>

<section class="alt" id="umrah">
<div class="container">
<h2 class="section-title">🕋 Umrah Packages</h2><p class="sub">Ask us for current rates, dates and hotel availability.</p>
<div class="grid">
<div class="card package"><h3>Economy Umrah</h3><p>Hotel + Umrah visa + flights + transport.</p><div class="price">Get Latest Price</div><a class="btn primary" href="https://wa.me/923132523059?text=Assalam-o-Alaikum%20ZANO%20TRAVELS%2C%20I%20want%20Umrah%20package%20details.">Ask on WhatsApp</a></div>
<div class="card package"><h3>Family Umrah</h3><p>Family-friendly hotel and private transport options.</p><div class="price">Get Latest Price</div><a class="btn primary" href="https://wa.me/923132523059?text=I%20want%20Family%20Umrah%20package%20details.">Ask on WhatsApp</a></div>
<div class="card package"><h3>Premium Umrah</h3><p>Premium hotels and convenient transport options.</p><div class="price">Get Latest Price</div><a class="btn primary" href="https://wa.me/923132523059?text=I%20want%20Premium%20Umrah%20package%20details.">Ask on WhatsApp</a></div>
<div class="card package"><h3>Custom Package</h3><p>Choose your dates, hotels, flights and room type.</p><div class="price">Customized</div><a class="btn primary" href="https://wa.me/923132523059?text=I%20want%20a%20custom%20Umrah%20package.">Get Quote</a></div>
</div>
</div>
</section>

<section id="tours">
<div class="container">
<h2 class="section-title">🌍 International Tours</h2><p class="sub">Customized travel packages available.</p>
<div class="grid">
<div class="card"><h3>🇹🇷 Turkey</h3><p>Istanbul and customized Turkey tours.</p></div>
<div class="card"><h3>🇹🇭 Thailand</h3><p>Bangkok, Pattaya and family/group options.</p></div>
<div class="card"><h3>🇦🇿 Azerbaijan</h3><p>Baku packages and group tours.</p></div>
<div class="card"><h3>🇯🇵 Japan</h3><p>Tokyo, Kyoto and customized itineraries.</p></div>
</div>
</div>
</section>

<section class="alt" id="visa">
<div class="container">
<h2 class="section-title">🛂 Visa Services</h2><p class="sub">Visa assistance for tourism and selected destinations. Approval is subject to the relevant embassy/immigration authority.</p>
<div class="grid">
<div class="card"><h3>🇬🇧 UK Visa</h3><p>Visit visa application assistance and document guidance.</p></div>
<div class="card"><h3>🇺🇸 USA Visa</h3><p>Visit visa application guidance and appointment assistance.</p></div>
<div class="card"><h3>🇪🇺 Schengen</h3><p>Tourist visa documentation and application assistance.</p></div>
<div class="card"><h3>🌏 Asia & More</h3><p>Malaysia, Thailand, Azerbaijan, China, Japan and other destinations.</p></div>
</div>
</div>
</section>

<section id="contact">
<div class="container">
<h2 class="section-title">Contact ZANO TRAVELS</h2><p class="sub">Send us your travel requirements and we will guide you.</p>
<div class="contact">
<div class="contact-box"><h2>📞 Get in Touch</h2><p><b>Phone / WhatsApp:</b><br><a href="tel:+923132523059">0313 2523059</a></p><p><b>Email:</b><br><a href="mailto:zanotravel1@gmail.com">zanotravel1@gmail.com</a></p><p><b>Office:</b><br>Central Information Cooperative Housing Society, Karachi, Pakistan</p></div>
<div class="card"><h3>Quick WhatsApp</h3><p>For flight fares, Umrah packages, tours or visa information, message us directly.</p><a class="btn primary" href="https://wa.me/923132523059?text=Assalam-o-Alaikum%20ZANO%20TRAVELS%2C%20I%20need%20travel%20information.">Chat on WhatsApp</a><p class="small">Prices and availability may change according to airline fares, hotel availability and government/visa policies.</p></div>
</div>
</div>
</section>
</main>

<a class="whatsapp" href="https://wa.me/923132523059">💬 WhatsApp</a>
<footer>© 2026 ZANO TRAVELS. All Rights Reserved.</footer>
</body>
</html>