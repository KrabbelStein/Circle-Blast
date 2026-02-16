# Circle-Blast
<!doctype html>
<html lang="de">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <meta name="theme-color" content="#000000">
  <title>Weiterleitung…</title>

  <style>
    /* Muss inline stehen und so minimal wie möglich sein */
    html,body {
      margin:0;
      padding:0;
      width:100%;
      height:100%;
      background:#000000 !important;
      color:#ffffff;
      -webkit-font-smoothing:antialiased;
      -moz-osx-font-smoothing:grayscale;
    }
    /* Verhindert weißen Hintergrund durch default body background in manchen Browsern */
    body { background-color:#000000 !important; }
    /* Optional: zentrierter Hinweis, falls Redirect fehlschlägt */
    .center { display:flex; align-items:center; justify-content:center; height:100%; }
    a { color:#fff; text-decoration:underline; }
  </style>

  <!-- Meta-Refresh als Fallback -->
  <meta http-equiv="refresh" content="0; url=/game/">
  <script>
    // JS-Redirect so früh wie möglich, ersetzt History
    try { window.location.replace("/game/"); } catch(e) {}
  </script>
</head>
<body>
  <div class="center">
    <p>Weiterleitung zum Spiel… <a href="/game/">Falls nicht automatisch, hier klicken</a></p>
  </div>
  <noscript>
    <div style="background:#000;color:#fff;height:100vh;display:flex;align-items:center;justify-content:center;">
      <p>JavaScript deaktiviert. <a href="/game/" style="color:#fff;text-decoration:underline;">Zum Spiel</a></p>
    </div>
  </noscript>
</body>
</html>
