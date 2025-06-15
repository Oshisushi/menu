<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Oshi Sushi Menu</title>
  <style>
    * {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      min-height: 100vh;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #111;
      color: #fff;
      text-align: center;
    }
    .header {
      background-image: url('https://i.postimg.cc/yxhLLVdm/Untitled-2-01.jpg');
      background-repeat: no-repeat;
      background-position: center;
      background-size: cover;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #e0d8c3;
      padding: 20px;
    }
    .header h1 {
      background-color: rgba(0, 0, 0, 0.6);
      padding: 20px 40px;
      border-radius: 12px;
      font-size: 40px;
      letter-spacing: 2px;
    }
    .section {
      background-color: rgba(0, 0, 0, 0.75);
      margin: 30px auto;
      padding: 30px;
      border-radius: 16px;
      max-width: 1000px;
      width: 90%;
      box-shadow: 0 0 25px rgba(0, 0, 0, 0.4);
    }
    h2 {
      color: #f5f5dc;
      font-size: 26px;
      margin-bottom: 20px;
    }
    a.button {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      padding: 14px 30px;
      margin: 10px;
      background-color: #222;
      color: #f5f5dc;
      text-decoration: none;
      border-radius: 10px;
      font-size: 18px;
      transition: all 0.3s ease;
      flex-wrap: nowrap;
    }
    a.button:hover {
      background-color: #444;
    }
    a.button img {
      width: 22px;
      height: 22px;
    }
    @media (max-width: 768px) {
      .header {
        min-height: 60vh;
        background-size: cover;
      }
      .header h1 {
        font-size: 28px;
        padding: 15px 20px;
      }
      h2 {
        font-size: 22px;
      }
      a.button {
        padding: 12px 20px;
        font-size: 16px;
        flex-direction: row;
      }
    }
  </style>
</head>
<body>

<div class="header">
  <h1>Oshi Sushi Menu<br /><span style='font-size: 18px; display: block; margin-top: 10px;'>Discover the Art of Sushi</span></h1>
</div>

<div class="section">
  <h2>📄 Food Menu</h2>
  <a class="button" href="https://drive.google.com/file/d/1SndZcR7eCBOQ6hZtfWYMMTNboSFsdfkI/view" target="_blank">View Food Menu</a>
</div>

<div class="section">
  <h2>🥤 Drinks Menu</h2>
  <a class="button" href="https://drive.google.com/file/d/12mxQ94gGYojYrIMFp949rAEe4qHdLYlF/view" target="_blank">View Drinks Menu</a>
</div>

<div class="section">
  <h2>📱 Contact Us</h2>
  <a class="button" href="https://wa.me/201050990997" target="_blank">WhatsApp</a>
  <a class="button" href="tel:01050990997">Call Us</a>
</div>

<div class="section">
  <h2>🛵 Order on Talabat</h2>
  <p style="color: #f5f5dc; font-size: 18px;">We are available on <strong>Talabat App</strong>. Search for "Oshi Sushi" and order now!</p>
  <a class="button" href="https://www.talabat.com/egypt" target="_blank">Open Talabat</a>
</div>

<div class="section">
  <h2>📍 Location</h2>
  <a class="button" href="https://g.co/kgs/oVGmhry" target="_blank">Open on Maps</a>
</div>

<div class="section">
  <h2>Follow Us</h2>
  <a class="button" href="https://www.instagram.com/oshi.sushi.eg?igsh=ZDhhN3lkZDFkcXYw" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png" alt="Instagram" />Instagram
  </a>
  <a class="button" href="https://www.tiktok.com/@oshi.sushi.eg?_t=ZS-8xE8a3vlilt&amp;_r=1" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/3046/3046122.png" alt="TikTok" />TikTok
  </a>
  <a class="button" href="https://www.facebook.com/share/1GLm1aJWXZ/" target="_blank">
    <img src="https://cdn-icons-png.flaticon.com/512/733/733547.png" alt="Facebook" />Facebook
  </a>
</div>

</body>
</html>
