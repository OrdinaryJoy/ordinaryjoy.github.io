<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>App Support - Ordinary Joy</title>

  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif;
      background: #f5f7fa;
      color: #222;
      line-height: 1.6;
    }

    .container {
      max-width: 760px;
      margin: 60px auto;
      padding: 0 20px;
    }

    .card {
      background: #ffffff;
      border-radius: 16px;
      padding: 42px;
      box-shadow: 0 8px 30px rgba(0, 0, 0, 0.06);
    }

    .logo {
      width: 48px;
      height: 48px;
      border-radius: 12px;
      background: #111;
      color: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 22px;
      font-weight: bold;
      margin-bottom: 22px;
    }

    h1 {
      margin: 0 0 8px;
      font-size: 30px;
    }

    .subtitle {
      color: #666;
      margin-bottom: 32px;
    }

    h2 {
      font-size: 18px;
      margin-top: 30px;
      margin-bottom: 12px;
    }

    .contact-box {
      background: #f7f8fa;
      padding: 18px 20px;
      border-radius: 12px;
      margin-top: 15px;
    }

    .contact-item {
      margin: 8px 0;
      word-break: break-word;
    }

    a {
      color: #1677ff;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    ul {
      padding-left: 22px;
      color: #555;
    }

    .button {
      display: inline-block;
      margin-top: 18px;
      padding: 11px 20px;
      background: #111;
      color: #fff;
      border-radius: 9px;
      text-decoration: none;
      transition: all 0.2s ease;
    }

    .button:hover {
      opacity: 0.85;
      text-decoration: none;
      transform: translateY(-1px);
    }

    footer {
      text-align: center;
      color: #999;
      font-size: 13px;
      margin-top: 25px;
    }

    @media (max-width: 600px) {
      .container {
        margin: 25px auto;
      }

      .card {
        padding: 28px 22px;
      }

      h1 {
        font-size: 26px;
      }
    }
  </style>
</head>

<body>

  <div class="container">

    <div class="card">

      <div class="logo">OJ</div>

      <h1>App Support</h1>

      <div class="subtitle">
        Ordinary Joy Tech Limited
      </div>

      <p>
        Thank you for using our app.
      </p >

      <p>
        If you encounter any issues, have questions, or would like to provide
        feedback or feature suggestions, please feel free to contact us.
      </p >

      <h2>Contact Us</h2>

      <div class="contact-box">

        <div class="contact-item">
          <strong>Email:</strong>
          <a href=" ">
            ordinaryjoy2023@gmail.com
          </a >
        </div>

        <div class="contact-item">
          <strong>Phone:</strong>
          <a href="tel:+8613261817001">
            +86 132 6181 7001
          </a >
        </div>

        <div class="contact-item">
          <strong>Developer:</strong>
          Ordinary Joy Tech Limited
        </div>

      </div>

      <a
        class="button"
        href="mailto:ordinaryjoy2023@gmail.com?subject=App%20Support"
      >
        Contact Support
      </a >

      <h2>How We Can Help</h2>

      <ul>
        <li>Technical issues</li>
        <li>Gameplay questions</li>
        <li>Bug reports</li>
        <li>App-related questions</li>
        <li>Feedback and feature suggestions</li>
      </ul>

      <p>
        We will review your message and respond as soon as possible.
      </p >

    </div>

    <footer>
      © <span id="year"></span> Ordinary Joy Tech Limited. All rights reserved.
    </footer>

  </div>

  <script>
    document.getElementById("year").textContent =
      new Date().getFullYear();
  </script>

</body>
</html>
