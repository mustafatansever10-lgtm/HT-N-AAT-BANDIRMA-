<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>HT İNŞAAT BANDIRMA</title>
  <style>
    html { scroll-behavior: smooth; }
    .fade-in { opacity: 0; transform: translateY(30px); animation: fadeInUp 1s forwards; }
    @keyframes fadeInUp { to { opacity: 1; transform: translateY(0); }}

    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f2f2f2;
    }
    header {
      background: #1f2937;
      color: #fff;
      padding: 30px;
      text-align: center;
      font-size: 32px;
      font-weight: bold;
    }
    nav {
      position: sticky;
      top: 0;
      z-index: 9999;
      background: linear-gradient(90deg, #0d0d0d, #1a1a1a);
      padding: 15px;
      text-align: center;
      border-bottom: 3px solid gold;
      box-shadow: 0 3px 15px rgba(255,215,0,0.4);
    }
    nav a {
      color: gold;
      margin: 0 20px;
      text-decoration: none;
      font-size: 20px;
      font-weight: bold;
      letter-spacing: 1.2px;
      transition: all 0.3s ease;
    }
    .hero {
      background: url('https://picsum.photos/1200/500?construction') center/cover no-repeat;
      height: 420px;
      display: flex;
      justify-content: center;
      align-items: center;
      color: white;
      font-size: 40px;
      font-weight: bold;
      text-shadow: 2px 2px 10px rgba(0,0,0,0.8);
    }
    .container {
      max-width: 1000px;
      margin: 40px auto;
      background: #fff;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
    }
    h2 {
      margin-top: 0;
      color: #1f2937;
    }
    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .project-card {
      background: #fafafa;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.08);
    }
    nav a:hover {
      color: white;
      text-shadow: 0 0 12px gold, 0 0 25px gold;
      transform: scale(1.15);
    }

    project-card:hover { transform: scale(1.07); box-shadow: 0 0 30px rgba(255,215,0,0.4); }

    footer {
      margin-top: 50px;
      background: #1f2937;
      color: white;
      padding: 20px;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    <object data="/mnt/data/ht inşaat logo.pdf" type="application/pdf" width="120" height="120"></object>
    <div>HT İNŞAAT BANDIRMA</div>
  </header>

  <nav>
    <a href="#hakkimizda">Hakkımızda</a>
    <a href="#projeler">Projeler</a>
    <a href="#iletisim">İletişim</a>
  </nav>

  <section class="hero" style="position: relative; height: 520px; border-radius: 0 0 20px 20px; overflow: hidden; display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center;">
    <video autoplay muted loop playsinline style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; filter: brightness(45%);">
      <source src="/mnt/data/VIDEO-2025-03-08-10-05-52.mp4" type="video/mp4">
    </video>
    <div style="position: relative; z-index: 2; color: gold; font-size: 48px; font-weight: bold; text-shadow: 0 0 15px rgba(0,0,0,0.9);">
      HT İNŞAAT BANDIRMA
    </div>
    <div style="position: relative; z-index: 2; font-size: 26px; margin-top: 15px; color: white; font-weight: normal; text-shadow: 0 0 12px rgba(255,215,0,0.9); letter-spacing: 1px;">
      Güvenle Yükselen Modern Yapılar
    </div>
    <a href="#iletisim" style="position: relative; z-index: 2; margin-top: 25px; background: gold; color: black; padding: 12px 25px; border-radius: 8px; font-size: 20px; text-decoration: none; font-weight: bold; box-shadow: 0 0 12px rgba(255,215,0,0.8); transition: 0.3s;">Hemen İletişim</a>
  </section>

  <div class="container fade-in" id="hakkimizda" style="background: #111; color: white; border-left: 5px solid gold; border-right: 5px solid gold; box-shadow: 0 0 20px rgba(255,215,0,0.3);">
    <h2 style="color: gold; font-size: 32px; text-align: center; letter-spacing: 1px;">Hakkımızda</h2>
    <p style="font-size: 18px; line-height: 1.7; text-align: center; color: #e5e5e5;">
      HT İNŞAAT BANDIRMA, modern ve lüks yaşam alanları inşa eden profesyonel bir firmadır.<br><br>
      Kalite, güven ve estetik tasarım ilkeleriyle projelerimizi hayata geçiriyoruz. Müşteri memnuniyeti bizim için her zaman ön plandadır.
    </p>
    <div style="display: flex; justify-content: space-around; margin-top: 30px; text-align: center;">
      <div>
        <h3 style="color: gold;">15+ Yıl Tecrübe</h3>
        <p style="color: #ccc;">Sektörde güçlü bir birikim</p>
      </div>
      <div>
        <h3 style="color: gold;">50+ Proje</h3>
        <p style="color: #ccc;">Tamamlanmış modern yapılar</p>
      </div>
      <div>
        <h3 style="color: gold;">%100 Güven</h3>
        <p style="color: #ccc;">Müşteri memnuniyeti odaklı</p>
      </div>
    </div>
  </div>

  <div class="container fade-in" id="projeler">
    <h2>Projelerimiz</h2>
    <div class="projects" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 25px; margin-top: 30px;">

      <div class="project-card" style="background: #111; border: 2px solid gold; padding: 20px; border-radius: 15px; box-shadow: 0 0 20px rgba(255,215,0,0.15); transition: 0.3s; text-align: center;">
        <h3 style="color: gold; font-size: 24px;">Rezidans Projesi</h3>
        <p style="color: #ccc;">Modern mimari, yüksek güvenlik ve lüks yaşam alanları.</p>
      </div>

      <div class="project-card" style="background: #111; border: 2px solid gold; padding: 20px; border-radius: 15px; box-shadow: 0 0 20px rgba(255,215,0,0.15); transition: 0.3s; text-align: center;">
        <h3 style="color: gold; font-size: 24px;">Villa Sitesi</h3>
        <p style="color: #ccc;">Doğa ile iç içe premium villa yaşamı.</p>
      </div>

      <div class="project-card" style="background: #111; border: 2px solid gold; padding: 20px; border-radius: 15px; box-shadow: 0 0 20px rgba(255,215,0,0.15); transition: 0.3s; text-align: center;">
        <h3 style="color: gold; font-size: 24px;">Ticari Plaza</h3>
        <p style="color: #ccc;">İş dünyası için modern ofis çözümleri.</p>
      </div>

    </div>
      <div class="project-card">
        <h3>Vila Sitesi</h3>
        <p>Doğa ile iç içe premium villa yaşamı.</p>
      </div>
      <div class="project-card">
        <h3>Ticari Plaza</h3>
        <p>İş dünyası için modern ofis çözümleri.</p>
      </div>
    </div>
  </div>

  <div class="container fade-in" id="iletisim">
    <h2>İletişim</h2>
    <p><strong>Telefon:</strong> 0532 445 8326</p>
    <p><strong>Email:</strong> msmyapibandirma@gmail.com</p>
    <p><strong>Adres:</strong> Paşabayır Mahallesi, Ordu Caddesi No:8/B, Bandırma / Balıkesir</p>
  </div>

  <footer style="background: #000; color: gold; padding: 40px 20px; text-align: center; border-top: 3px solid gold; box-shadow: 0 -5px 25px rgba(255,215,0,0.3); letter-spacing: 1px;">
    <h3 style="margin: 0; font-size: 26px; color: gold;">HT İNŞAAT BANDIRMA</h3>
    <p style="color: #ccc; margin-top: 10px; font-size: 16px;">Güven, kalite ve modern yapı çözümleri</p>
    <div style="margin-top: 20px;">
      <span style="margin: 0 15px; color: gold;">Telefon: 0532 445 8326</span>
      <span style="margin: 0 15px; color: gold;">Email: msmyapibandirma@gmail.com</span>
      <span style="margin: 0 15px; color: gold;">Bandırma / Balıkesir</span>
    </div>
    <p style="margin-top: 25px; color: #777; font-size: 14px;">© 2025 HT İNŞAAT BANDIRMA – Tüm Hakları Saklıdır.</p>
  </footer>
  <a href="https://wa.me/905324458326" target="_blank" style="position: fixed; bottom: 20px; right: 20px; background: #25D366; color: white; padding: 15px 20px; border-radius: 50px; font-size: 20px; font-weight: bold; text-decoration: none; box-shadow: 0 0 15px rgba(0,0,0,0.3); z-index: 999;">WhatsApp</a>

</body>
</html>
