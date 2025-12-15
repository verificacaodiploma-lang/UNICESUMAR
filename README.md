<!doctype html>

<html lang="pt-BR">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>UniCesumar — Sistema de Verificação de Diplomas</title>
  <style>
    :root {
      --bg: #f4f6fb;
      --card: #ffffff;
      --accent: #7b1fa2; /* Roxo UniCesumar */
      --text: #222;
      --muted: #666;
      --ok: #2e7d32;
    }
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      background: linear-gradient(135deg, #ede7f6, #f4f6fb);
      color: var(--text);
      min-height: 100vh;
      display: grid;
      place-items: center;
    }
    .card {
      width: 100%;
      max-width: 720px;
      background: var(--card);
      border-radius: 16px;
      box-shadow: 0 10px 30px rgba(0,0,0,.12);
      padding: 28px;
    }
    .header {
      display: flex;
      align-items: center;
      gap: 16px;
      border-bottom: 1px solid #eee;
      padding-bottom: 16px;
      margin-bottom: 16px;
    }
    .logo {
      width: 56px;
      height: 56px;
      border-radius: 12px;
      background: var(--accent);
      color: #fff;
      display: grid;
      place-items: center;
      font-weight: 800;
      letter-spacing: .5px;
    }
    .title h1 {
      font-size: 1.3rem;
      margin: 0;
    }
    .title p {
      margin: 4px 0 0;
      color
