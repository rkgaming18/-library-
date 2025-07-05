#অসীম library
<!DOCTYPE html>
<html lang="as">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>অসীম Library</title>

  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #fff;
      color: #222;
    }

    /* Header */
    .top-bar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px 20px;
      background: #ffffff;
      border-bottom: 1px solid #ccc;
    }

    .logo-container {
      display: flex;
      align-items: center;
    }

    .logo {
      width: 50px;
      height: 50px;
      margin-right: 10px;
    }

    .site-name h1 {
      margin: 0;
      font-size: 20px;
      color: #d32f2f;
    }

    .site-name p {
      margin: 0;
      font-size: 12px;
      color: #666;
    }

    .social-icons a img {
      width: 20px;
      margin-left: 10px;
    }

    /* Quote Section */
    .quote-banner {
      background: #f0f0f0;
      padding: 12px;
      font-size: 16px;
      text-align: center;
      font-weight: bold;
    }

    /* Main content */
    .content {
      padding: 20px;
    }

    .content h2 {
      color: #4caf50;
    }

    .content ul {
      list-style: none;
      padding-left: 0;
    }

    .content li {
      padding: 5px 0;
    }

    .content a {
      text-decoration: none;
      color: #0066cc;
    }

    .content a:hover {
      text-decoration: underline;
    }

    /* Responsive */
    @media (max-width: 600px) {
      .logo {
        width: 40px;
        height: 40px;
      }

      .site-name h1 {
        font-size: 18px;
      }
    }
  </style>
</head>
<body>

  <!-- 🔷 Top Header -->
  <header class="top-bar">
    <div class="logo-container">
      <img src="asim-logo.png" alt="অসীম Library Logo" class="logo">
      <div class="site-name">
        <h1>অসীম Library</h1>
        <p>Connecting Learners</p>
      </div>
    </div>
    <nav class="social-icons">
      <a href="#"><img src="facebook.svg" alt="Facebook"></a>
      <a href="#"><img src="twitter.svg" alt="Twitter"></a>
      <a href="#"><img src="youtube.svg" alt="YouTube"></a>
    </nav>
  </header>

  <!-- ❤️ মহতবাণী Section -->
  <section class="quote-banner">
    ❤️ শিক্ষাই হৈছে আটাইতকৈ শক্তিশালী অস্ত্ৰ — <strong>ড° ভূপেন হাজৰিকা</strong>
  </section>

  <!-- 📚 Content Sections -->
  <main class="content">
    <section>
      <h2>English Medium Solutions</h2>
      <ul>
        <li><a href="#">Class 10 Science</a></li>
        <li><a href="#">Class 12 Physics</a></li>
      </ul>
    </section>

    <section>
      <h2>অসমীয়া মাধ্যম</h2>
      <ul>
        <li><a href="#">দশম শ্ৰেণীৰ গণিত</a></li>
        <li><a href="#">দ্বাদশ শ্ৰেণীৰ সাহিত্য</a></li>
      </ul>
    </section>
  </main>

</body>
</html>
