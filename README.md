<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>ZANO TRAVELS | Flights • Umrah • Visa • Tours</title>

<meta name="description"
content="ZANO TRAVELS Karachi - Airline Tickets, Umrah Packages, International Tours, Hotels and Visa Assistance.">

<style>
:root{
  --green:#087f5b;
  --dark:#064b39;
  --deep:#03382b;
  --light:#effbf6;
  --gold:#d6a83b;
  --white:#ffffff;
  --text:#18352d;
  --muted:#60766f;
  --border:#d9ebe4;
}

*{
  box-sizing:border-box;
  margin:0;
  padding:0;
}

html{
  scroll-behavior:smooth;
}

body{
  font-family:Arial,Helvetica,sans-serif;
  color:var(--text);
  background:#fff;
  line-height:1.6;
}

header{
  position:sticky;
  top:0;
  z-index:100;
  background:linear-gradient(135deg,var(--dark),var(--green));
  box-shadow:0 4px 18px #0003;
}

.nav{
  max-width:1180px;
  margin:auto;
  padding:14px 20px;
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:20px;
}

.logo{
  color:#fff;
  font-size:28px;
  font-weight:900;
  letter-spacing:2px;
  text-decoration:none;
}

.logo span{
  color:#ffe28a;
}

nav{
  display:flex;
  gap:20px;
}

nav a{
  color:#fff;
  text-decoration:none;
  font-size:14px;
  font-weight:700;
}

nav a:hover{
  color:#ffe28a;
}

.hero{
  background:
  radial-gradient(circle at top right,#d9f8eb,transparent 45%),
  linear-gradient(135deg,#effff8,#ffffff);
  padding:90px 20px 75px;
}

.hero-inner{
  max-width:1180px;
  margin:auto;
  display:grid;
  grid-template-columns:1.25fr .75fr;
  gap:45px;
  align-items:center;
}

.badge{
  display:inline-block;
  background:#d8f5e9;
  color:var(--dark);
  padding:8px 15px;
  border-radius:30px;
  font-weight:800;
}

h1{
  font-size:56px;
  line-height:1.08;
  color:var(--dark);
  margin:20px 0;
}

h1 span{
  color:var(--green);
}

.hero-text{
  font-size:19px;
  color:#506a62;
  max-width:680px;
  margin-bottom:20px;
}

.btn{
  display:inline-block;
  padding:13px 22px;
  border-radius:8px;
  text-decoration:none;
  font-weight:800;
  margin:6px 5px 6px 0;
  transition:.2s;
}

.btn:hover{
  transform:translateY(-2px);
}

.primary{
  background:var(--green);
  color:#fff;
}

.secondary{
  border:2px solid var(--green);
  color:var(--green);
  background:#fff;
}

.hero-card{
  background:#fff;
  border-radius:22px;
  padding:32px;
  box-shadow:0 15px 45px #087f5b25;
  border-top:6px solid var(--gold);
}

.hero-card h2{
  color:var(--dark);
  margin-bottom:12px;
}

.hero-card p{
  margin:10px 0;
}

.quick{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:10px;
  margin:20px 0;
}

.quick div{
  background:var(--light);
  padding:12px;
  border-radius:10px;
  font-weight:700;
}

section{
  padding:70px 20px;
}

.alt{
  background:var(--light);
}

.container{
  max-width:1180px;
  margin:auto;
}

.section-title{
  text-align:center;
  font-size:36px;
  color:var(--dark);
  margin-bottom:8px;
}

.sub{
  text-align:center;
  color:var(--muted);
  max-width:700px;
  margin:0 auto 38px;
}

.grid{
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:20px;
}

.card{
  background:#fff;
  border:1px solid var(--border);
  border-radius:17px;
  padding:25px;
  box-shadow:0 8px 25px #00000008;
  transition:.2s;
}

.card:hover{
  transform:translateY(-4px);
  box-shadow:0 12px 30px #087f5b18;
}

.icon{
  font-size:38px;
}

.card h3{
  color:var(--dark);
  margin:10px 0 8px;
}

.card p{
  color:#5e756e;
}

.package{
  display:flex;
  flex-direction:column;
}

.price{
  color:var(--green);
  font-size:21px;
  font-weight:900;
  margin:15px 0;
}

.package .btn{
  margin-top:auto;
  text-align:center;
}

.destination{
  text-align:center;
}

.destination .flag{
  font-size:45px;
}

.visa-note{
  background:#fff8df;
  border-left:5px solid var(--gold);
  padding:16px;
  border-radius:10px;
  margin-bottom:25px;
  color:#66511c;
}

.contact{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:25px;
}

.contact-box{
  background:linear-gradient(135deg,var(--dark),var(--green));
  color:#fff;
  padding:35px;
  border-radius:20px;
}

.contact-box h2{
  margin-bottom:20px;
}

.contact-box p{
  margin:15px 0;
}

.contact-box a{
  color:#fff;
}

.contact-card{
  background:#fff;
  border:1px solid var(--border);
  border-radius:20px;
  padding:35px;
}

.contact-card h3{
  color:var(--dark);
  margin-bottom:10px;
}

footer{
  background:var(--deep);
  color:#d8eee7;
  text-align:center;
  padding:32px 20px;
}

.footer-logo{
  color:#fff;
  font-size:24px;
  font-weight:900;
  letter-spacing:2px;
  margin-bottom:8px;
}

.footer-logo span{
  color:#ffe28a;
}

.small{
  font-size:13px;
  color:#78918a;
  margin-top:15px;
}

.whatsapp{
  position:fixed;
  right:20px;
  bottom:20px;
  z-index:200;
  background:#25D366;
  color:#fff;
  padding:14px 20px;
  border-radius:50px;
  text-decoration:none;
  font-weight:900;
  box-shadow:0 6px 20px #0004;
}

@media(max-width:900px){

  nav{
    gap:10px;
  }

  nav a{
    font-size:12px;
  }

  .hero-inner{
    grid-template-columns:1fr;
  }

  h1{
    font-size:45px;
  }

  .grid{
    grid-template-columns:1fr 1fr;
  }

  .contact{
    grid-template-columns:1fr;
  }
}

@media(max-width:600px){

  .nav{
    padding:12px 15px;
  }

  .logo{
    font-size:22px;
  }

  nav{
    display:none;
  }

  .hero{
    padding:60px 18px;
  }

  h1{
    font-size:38px;
  }

  .hero-text{
    font-size:17px;
  }

  section{
    padding:50px 18px;
  }

  .section-title{
    font-size:29px;
  }

  .grid{
    grid-template-columns:1fr;
  }

  .quick{
    grid-template-columns:1fr;
  }

  .whatsapp{
    right:12px;
    bottom:12px;
    padding:12px 16px;
  }
}
</style>
</head>

<body>

<header>
  <div class="nav">

    <a class="logo" href="#home">
      ZANO <span>TRAVELS</span>
    </a>

    <nav>
      <a href="#home">Home</a>
      <a href="#services">Services</a>
      <a href="#flights">Flights</a>
      <a href="#umrah">Umrah</a>
      <a href="#tours">Tours</a>
      <a href="#visa">Visa</a>
      <a href="#contact">Contact</a>
    </nav>

  </div>
</header>

<main>

<!-- HERO -->

<section class="hero" id="home">

  <div class="hero-inner">

    <div>

      <span class="badge">✈️ Travel with Confidence</span>

      <h1>
        Your Journey,<br>
        <span>Our Responsibility.</span>
      </h1>

      <p class="hero-text">
        ZANO TRAVELS provides complete travel solutions from Karachi —
        Airline Tickets, Umrah Packages, International Tours, Hotels
        and Visa Assistance.
      </p>

      <a class="btn primary"
         href="https://wa.me/923132523059?text=Assalam-o-Alaikum%20ZANO%20TRAVELS%2C%20I%20need%20travel%20information.">
        💬 WhatsApp Us
      </a>

      <a class="btn secondary" href="#services">
        Explore Services
      </a>

    </div>

    <div class="hero-card">

      <h2>🌍 ZANO TRAVELS</h2>

      <p>
        Complete travel solutions for individuals,
        families and groups.
      </p>

      <div class="quick">
        <div>✈️ Flights</div>
        <div>🕋 Umrah</div>
        <div>🛂 Visa</div>
        <div>🌍 Tours</div>
      </div>

      <a class="btn primary" href="#contact">
        Get a Quote
      </a>

    </div>

  </div>

</section>


<!-- SERVICES -->

<section id="services">

  <div class="container">

    <h2 class="section-title">Our Services</h2>

    <p class="sub">
      Everything you need for a smooth and comfortable journey.
    </p>

    <div class="grid">

      <div class="card">
        <div class="icon">✈️</div>
        <h3>Airline Tickets</h3>
        <p>
          Domestic and international flight booking
          with multiple airline options.
        </p>
      </div>

      <div class="card">
        <div class="icon">🕋</div>
        <h3>Umrah Packages</h3>
        <p>
          Umrah visa, hotels, flights, transport
          and Ziyarat options.
        </p>
      </div>

      <div class="card">
        <div class="icon">🛂</div>
        <h3>Visa Services</h3>
        <p>
          Tourist visa assistance and documentation
          guidance for selected destinations.
        </p>
      </div>

      <div class="card">
        <div class="icon">🌍</div>
        <h3>Tour Packages</h3>
        <p>
          Customized and group tours for families,
          couples and travelers.
        </p>
      </div>

    </div>

  </div>

</section>


<!-- FLIGHTS -->

<section class="alt" id="flights">

  <div class="container">

    <h2 class="section-title">✈️ Flight Booking</h2>

    <p class="sub">
      Domestic and international flight fares available.
      Contact us for current fare and availability.
    </p>

    <div class="grid">

      <div class="card">
        <h3>🇵🇰 Domestic Flights</h3>
        <p>
          Karachi, Islamabad, Lahore, Peshawar,
          Quetta and other destinations.
        </p>

        <a class="btn primary"
        href="https://wa.me/923132523059?text=I%20want%20Domestic%20Flight%20fare%20details.">
        Check Fare
        </a>
      </div>

      <div class="card">
        <h3>🇸🇦 Saudi Arabia</h3>
        <p>
          Jeddah, Riyadh, Dammam, Madinah and
          other Saudi destinations.
        </p>

        <a class="btn primary"
        href="https://wa.me/923132523059?text=I%20want%20Saudi%20flight%20fare%20details.">
        Check Fare
        </a>
      </div>

      <div class="card">
        <h3>🇦🇪 UAE</h3>
        <p>
          Dubai, Abu Dhabi, Sharjah and other
          UAE flight options.
        </p>

        <a class="btn primary"
        href="https://wa.me/923132523059?text=I%20want%20UAE%20flight%20fare%20details.">
        Check Fare
        </a>
      </div>

      <div class="card">
        <h3>🌍 International</h3>
        <p>
          International flights to Asia, Europe,
          Middle East and other destinations.
        </p>

        <a class="btn primary"
        href="https://wa.me/923132523059?text=I%20want%20International%20flight%20fare%20details.">
        Check Fare
        </a>
      </div>

    </div>

  </div>

</section>


<!-- UMRAH -->

<section id="umrah">

  <div class="container">

    <h2 class="section-title">🕋 Umrah Packages</h2>

    <p class="sub">
      Ask us for current rates, dates, hotel availability
      and flight options.
    </p>

    <div class="grid">

      <div class="card package">

        <h3>Economy Umrah</h3>

        <p>
          Hotel + Umrah visa + flights +
          transport options.
        </p>

        <div class="price">
          Get Latest Price
        </div>

        <a class="btn primary"
        href="https://wa.me/923132523059?text=Assalam-o-Alaikum%20ZANO%20TRAVELS%2C%20I%20want%20Economy%20Umrah%20package%20details.">
        Ask on WhatsApp
        </a>

      </div>


      <div class="card package">

        <h3>Family Umrah</h3>

        <p>
          Family-friendly hotels and
          transport options.
        </p>

        <div class="price">
          Get Latest Price
        </div>

        <a class="btn primary"
        href="https://wa.me/923132523059?text=I%20want%20Family%20Umrah%20package%20details.">
        Ask on WhatsApp
        </a>

      </div>


      <div class="card package">

        <h3>Premium Umrah</h3>

        <p>
          Premium hotel options and
          convenient transport.
        </p>

        <div class="price">
          Get Latest Price
        </div>

        <a class="btn primary"
        href="https://wa.me/923132523059?text=I%20want%20Premium%20Umrah%20package%20details.">
        Ask on WhatsApp
        </a>

      </div>


      <div class="card package">

        <h3>Custom Umrah</h3>

        <p>
          Choose your dates, hotels,
          flights and room type.
        </p>

        <div class="price">
          Customized
        </div>

        <a class="btn primary"
        href="https://wa.me/923132523059?text=I%20want%20a%20Custom%20Umrah%20package.">
        Get Quote
        </a>

      </div>

    </div>

  </div>

</section>


<!-- TOURS -->

<section class="alt" id="tours">

  <div class="container">

    <h2 class="section-title">🌍 International Tours</h2>

    <p class="sub">
      Customized travel packages and group tours available.
    </p>

    <div class="grid">

      <div class="card destination">
        <div class="flag">🇹🇷</div>
        <h3>Turkey</h3>
        <p>
          Istanbul and customized Turkey tours.
        </p>
      </div>

      <div class="card destination">
        <div class="flag">🇹🇭</div>
        <h3>Thailand</h3>
        <p>
          Bangkok, Pattaya and family/group tours.
        </p>
      </div>

      <div class="card destination">
        <div class="flag">🇦🇿</div>
        <h3>Azerbaijan</h3>
        <p>
          Baku packages and group tours.
        </p>
      </div>

      <div class="card destination">
        <div class="flag">🇯🇵</div>
        <h3>Japan</h3>
        <p>
          Tokyo, Kyoto and customized itineraries.
        </p>
      </div>

    </div>

  </div>

</section>


<!-- VISA -->

<section id="visa">

  <div class="container">

    <h2 class="section-title">🛂 Visa Services</h2>

    <p class="sub">
      Visa assistance for tourism and selected destinations.
      Approval is subject to the relevant embassy or immigration authority.
    </p>

    <div class="visa-note">
      <strong>Important:</strong>
      Visa approval is not guaranteed. Final decisions are made
      by the relevant embassy, consulate or immigration authority.
    </div>

    <div class="grid">

      <div class="card">
        <h3>🇬🇧 UK Visa</h3>
        <p>
          Visit visa application assistance and
          document guidance.
        </p>

        <a class="btn primary"
        href="https://wa.me/923132523059?text=I%20want%20UK%20Visit%20Visa%20details.">
        Visa Inquiry
        </a>
      </div>


      <div class="card">
        <h3>🇺🇸 USA Visa</h3>
        <p>
          Visit visa application guidance and
          appointment assistance.
        </p>

        <a class="btn primary"
        href="https://wa.me/923132523059?text=I%20want%20USA%20Visit%20Visa%20details.">
        Visa Inquiry
        </a>
      </div>


      <div class="card">
        <h3>🇪🇺 Schengen</h3>
        <p>
          Tourist visa documentation and
          application assistance.
        </p>

        <a class="btn primary"
        href="https://wa.me/923132523059?text=I%20want%20Schengen%20Visa%20details.">
        Visa Inquiry
        </a>
      </div>


      <div class="card">
        <h3>🌏 Asia & More</h3>
        <p>
          Malaysia, Thailand, Azerbaijan, China,
          Japan and other destinations.
        </p>

        <a class="btn primary"
        href="https://wa.me/923132523059?text=I%20want%20Asia%20Visa%20details.">
        Visa Inquiry
        </a>
      </div>

    </div>

  </div>

</section>


<!-- CONTACT -->

<section class="alt" id="contact">

  <div class="container">

    <h2 class="section-title">
      Contact ZANO TRAVELS
    </h2>

    <p class="sub">
      Send us your travel requirements and
      our team will guide you.
    </p>

    <div class="contact">

      <div class="contact-box">

        <h2>📞 Get in Touch</h2>

        <p>
          <strong>Phone / WhatsApp:</strong><br>
          <a href="tel:+923132523059">
            0313 2523059
          </a>
        </p>

        <p>
          <strong>Email:</strong><br>
          <a href="mailto:zanotravel1@gmail.com">
            zanotravel1@gmail.com
          </a>
        </p>

        <p>
          <strong>Office:</strong><br>
          Central Information Cooperative Housing Society,
          Karachi, Pakistan
        </p>

      </div>


      <div class="contact-card">

        <h3>💬 Quick WhatsApp</h3>

        <p>
          For flight fares, Umrah packages,
          international tours or visa information,
          message ZANO TRAVELS directly.
        </p>

        <br>

        <a class="btn primary"
        href="https://wa.me/923132523059?text=Assalam-o-Alaikum%20ZANO%20TRAVELS%2C%20I%20need%20travel%20information.">
        Chat on WhatsApp
        </a>

        <p class="small">
          Prices and availability may change according
          to airline fares, hotel availability and
          government/visa policies.
        </p>

      </div>

    </div>

  </div>

</section>

</main>


<!-- FLOATING WHATSAPP -->

<a class="whatsapp"
href="https://wa.me/923132523059?text=Assalam-o-Alaikum%20ZANO%20TRAVELS%2C%20I%20need%20travel%20information."
aria-label="WhatsApp ZANO TRAVELS">
💬 WhatsApp
</a>


<!-- FOOTER -->

<footer>

  <div class="footer-logo">
    ZANO <span>TRAVELS</span>
  </div>

  <p>
    Flights • Umrah • Visa • International Tours
  </p>

  <p class="small">
    © 2026 ZANO TRAVELS. All Rights Reserved.
  </p>

</footer>

</body>
</html>