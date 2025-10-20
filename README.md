<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>World Workers Hub — We Build Your Dreams</title>
  <meta name="description" content="World Workers Hub — Interior design & Banquet Hall construction in Delhi. Book via WhatsApp."/>
  <style>
    :root{
      --primary:#0f172a; /* dark navy */
      --accent:#ff6b6b;
      --muted:#6b7280;
      --card:#ffffff;
      --glass: rgba(255,255,255,0.06);
      font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,#f8fafc 0%, #eef2ff 100%);color:var(--primary);line-height:1.45}
    header{background:var(--primary);color:white;padding:18px 20px;display:flex;align-items:center;justify-content:space-between;gap:12px}
    .brand{display:flex;align-items:center;gap:12px}
    .brand img{height:58px;width:58px;object-fit:contain;border-radius:8px;background:#000}
    .brand .title{font-weight:700;font-size:18px}
    .brand .tag{font-size:12px;color:#c7d2fe;margin-top:2px}

    nav{display:flex;gap:12px;align-items:center}
    nav a{color:rgba(255,255,255,0.9);text-decoration:none;padding:8px 10px;border-radius:8px}
    nav a:hover{background:rgba(255,255,255,0.06)}

    .container{max-width:1100px;margin:28px auto;padding:0 18px}

    .hero{display:grid;grid-template-columns:1fr;gap:18px;align-items:center}
    .hero-card{background:white;border-radius:14px;padding:22px;box-shadow:0 6px 30px rgba(16,24,40,0.06);display:flex;flex-direction:column;gap:12px}

    .hero-top{display:flex;gap:18px;align-items:center}
    .hero-top img{height:140px;width:140px;object-fit:contain;border-radius:12px;background:#000}
    .hero-top h1{margin:0;font-size:22px}
    .hero-top p{margin:0;color:var(--muted)}

    .cta{display:flex;gap:12px;flex-wrap:wrap}
    .btn{display:inline-flex;align-items:center;gap:10px;padding:10px 14px;border-radius:10px;font-weight:600;text-decoration:none}
    .btn-primary{background:var(--accent);color:white}
    .btn-outline{border:1px solid var(--accent);color:var(--primary);background:transparent}

    .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:18px}
    .card{background:white;border-radius:12px;padding:16px;box-shadow:0 6px 20px rgba(16,24,40,0.04)}
    .card h3{margin:0 0 8px 0}
    .muted{color:var(--muted);font-size:14px}

    .gallery{display:grid;grid-template-columns:repeat(3,1fr);gap:10px}
    .gallery img{width:100%;height:180px;object-fit:cover;border-radius:8px}

    footer{margin-top:28px;padding:22px;background:#0b1220;color:#dbeafe;border-radius:12px}
    .contact{display:flex;flex-wrap:wrap;gap:12px;align-items:center}
    .contact a{color:#fff;text-decoration:none}

    /* WhatsApp floating */
    .whatsapp-fixed{position:fixed;right:18px;bottom:18px;background:#25D366;color:white;border-radius:999px;padding:12px 14px;box-shadow:0 8px 24px rgba(16,24,40,0.18);display:flex;gap:10px;align-items:center;text-decoration:none}

    /* Responsive */
    @media (max-width:900px){
      .grid{grid-template-columns:repeat(2,1fr)}
      .gallery{grid-template-columns:repeat(2,1fr)}
      .hero-top img{height:110px;width:110px}
    }
    @media (max-width:600px){
      header{padding:12px}
      .hero{grid-template-columns:1fr}
      .grid{grid-template-columns:1fr}
      .gallery{grid-template-columns:1fr}
      .hero-top{flex-direction:row;gap:12px}
      .hero-card{padding:14px}
    }

    /* small helper */
    .small{font-size:13px;color:var(--muted)}
  </style>
</head>
<body>
  <!--
    NOTES:
    - This is a single-file responsive HTML template for "World Workers Hub".
    - The logo & gallery images are referenced below with the exact filenames that you uploaded
      to the container during our chat. If you host this on a server, place your images in the
      same folder and update the paths if needed.

    Provided image paths used in this file (replace if your hosting path is different):
      /mnt/data/1000257113.jpg  -> logo image
      /mnt/data/1000039750.jpg  -> gallery image 1
      /mnt/data/1000039752.jpg  -> gallery image 2
  -->

  <header>
    <div class="brand">
      <img src="/mnt/data/1000257113.jpg" alt="World Workers Hub logo">
      <div>
        <div class="title">World Workers Hub</div>
        <div class="tag">We Build Your Dreams • Delhi</div>
      </div>
    </div>
    <nav>
      <a href="#services">Services</a>
      <a href="#gallery">Gallery</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main class="container">
    <section class="hero">
      <div class="hero-card">
        <div class="hero-top">
          <img src="/mnt/data/1000257113.jpg" alt="logo large">
          <div>
            <h1>World Workers Hub — Interior Design & Banquet Hall Experts</h1>
            <p class="muted">Designing & building premium banquet halls and interiors across Delhi. From concept to completion — we deliver beautiful, functional spaces.</p>
            <div style="margin-top:10px" class="small">Email: <strong>worldwerkershub@gmail.com</strong></div>
            <div style="margin-top:6px" class="small">Phones: <strong>+91 88812 53887</strong> • <strong>+91 90454 03696</strong> • <strong>+91 98106 12589</strong></div>
          </div>
        </div>

        <div class="cta">
          <!-- WhatsApp link points to primary phone. Modify text param as needed. -->
          <a class="btn btn-primary" href="https://wa.me/918881253887?text=Hi%20World%20Workers%20Hub%2C%20I%20would%20like%20to%20book%20a%20service%20%26%20know%20more." target="_blank" rel="noopener noreferrer">Book via WhatsApp</a>
          <a class="btn btn-outline" href="#contact">Get a Quote</a>
        </div>

        <div class="grid" style="margin-top:14px">
          <div class="card">
            <h3>Interior Designing</h3>
            <p class="muted">Residential and commercial interior design — concept, 3D visualization, execution and finishing.</p>
          </div>
          <div class="card">
            <h3>Banquet Hall Construction</h3>
            <p class="muted">Turnkey banquet halls: structural work, décor, lighting and acoustic solutions tailored to your needs.</p>
          </div>
          <div class="card">
            <h3>Event Services</h3>
            <p class="muted">Event-ready halls with decorations, seating plans, technical support and on-site management.</p>
          </div>
        </div>
      </div>

      <!-- Optional: Add a second column image or testimonial later -->
    </section>

    <section id="gallery" style="margin-top:18px">
      <h2>Project Gallery</h2>
      <p class="muted">Recent banquet hall projects — click images to enlarge.</p>
      <div class="gallery" style="margin-top:12px">
        <img src="/mnt/data/1000039750.jpg" alt="Gallery 1" onclick="openLightbox(this.src)">
        <img src="/mnt/data/1000039752.jpg" alt="Gallery 2" onclick="openLightbox(this.src)">
        <!-- You can add more images here -->
        <div style="background:#f1f5f9;border-radius:8px;display:flex;align-items:center;justify-content:center;padding:14px" class="small">Add more photos here</div>
      </div>
    </section>

    <section id="contact" style="margin-top:18px">
      <h2>Contact & Booking</h2>
      <div style="display:flex;gap:18px;flex-wrap:wrap;margin-top:10px">
        <div style="flex:1;min-width:240px" class="card">
          <h3>Contact Info</h3>
          <p class="small">Email: <a href="mailto:worldwerkershub@gmail.com">worldwerkershub@gmail.com</a></p>
          <p class="small">Phone: <a href="tel:+918881253887">+91 88812 53887</a></p>
          <p class="small">Alternate: <a href="tel:+919045403696">+91 90454 03696</a>, <a href="tel:+919810612589">+91 98106 12589</a></p>
          <p class="small">Location: Delhi, India</p>
        </div>

        <div style="flex:1;min-width:260px" class="card">
          <h3>Quick Booking (via WhatsApp)</h3>
          <p class="muted">Click the button below to start a WhatsApp chat and share details: event date, guest count, and service required.</p>
          <a class="btn btn-primary" href="https://wa.me/918881253887?text=Hello%20World%20Workers%20Hub%2C%20I%20want%20to%20book%20a%20banquet%20hall%20on%20this%20date%3A%20" target="_blank" rel="noopener noreferrer">Message on WhatsApp</a>
        </div>
      </div>
    </section>

    <footer style="margin-top:22px">
      <div style="display:flex;justify-content:space-between;align-items:center;flex-wrap:wrap;gap:12px">
        <div>
          <strong>World Workers Hub</strong>
          <div class="small" style="margin-top:6px">We Build Your Dreams • Delhi</div>
        </div>
        <div class="small">© <span id="year"></span> World Workers Hub — All rights reserved.</div>
      </div>
    </footer>
  </main>

  <a class="whatsapp-fixed" href="https://wa.me/918881253887?text=Hi%20World%20Workers%20Hub%2C%20I%20would%20like%20to%20book%20a%20service." target="_blank" rel="noopener noreferrer">
    <svg xmlns="http://www.w3.org/2000/svg" width="18" height="18" viewBox="0 0 24 24" fill="none" aria-hidden>
      <path d="M20.5 3.5v17a1.5 1.5 0 0 1-1.6 1.5c-3.2-.2-5.8-1.7-7.7-3.6-1.9-1.9-3.4-4.5-3.6-7.7A1.5 1.5 0 0 1 8.5 9h17" fill="none"></path>
    </svg>
    <span style="font-weight:700">WhatsApp</span>
  </a>

  <!-- Lightbox script -->
  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
    function openLightbox(src){
      const div = document.createElement('div');
      div.style.position='fixed';div.style.inset=0;div.style.background='rgba(0,0,0,0.8)';div.style.display='flex';div.style.alignItems='center';div.style.justifyContent='center';div.style.zIndex=9999;
      const img = document.createElement('img');img.src=src;img.style.maxWidth='90%';img.style.maxHeight='90%';img.style.borderRadius='8px';
      div.appendChild(img);
      div.addEventListener('click',()=>div.remove());
      document.body.appendChild(div);
    }
  </script>
</body>
</html>
