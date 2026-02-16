# Circle-Blast
<!doctype html>
<html lang="de">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <meta name="theme-color" content="#000000">
  <title>Weiterleitung…</title>

  <!-- Inline CSS sofort anwenden, damit kein Weißblitz erscheint -->
  <style>
    html,body {
      margin:0;
      padding:0;
      width:100%;
      height:100%;
      background:#000000;
      color:#ffffff;
      font-family:system-ui,-apple-system,"Segoe UI",Roboto,Arial;
    }
    /* Optional: zentrierter Hinweis, falls Redirect nicht funktioniert */
    .center {display:flex;align-items:center;justify-content:center;height:100%;}
    a {color:#fff;text-decoration:underline;}
  </style>

  <!-- Meta-Refresh als Fallback (0 Sekunden) -->
  <meta http-equiv="refresh" content="0; url=/game/">
  <script>
    // JS-Redirect mit replace (ersetzt History)
    window.location.replace("/game/");
  </script>
</head>
<body>
  <div class="center">
    <p>Weiterleitung zum Spiel… <a href="/game/">Falls nicht automatisch, hier klicken</a></p>
  </div>
</body>
</html>
