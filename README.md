<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Bonusowe Aplikacje</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f7f9fc;
      margin: 0;
      padding: 0;
      color: #333;
    }
    header {
      background: #007bff;
      color: white;
      padding: 20px 10px;
      text-align: center;
    }
    header h1 {
      margin: 0 0 10px;
    }
    header p {
      margin: 0;
      font-size: 1.1em;
    }
    main {
      max-width: 900px;
      margin: 30px auto;
      padding: 0 20px;
    }
    .app-list {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .app-card {
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      width: 260px;
      padding: 15px;
      text-align: center;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    .app-card img {
      max-width: 100%;
      height: 140px;
      object-fit: contain;
      margin-bottom: 15px;
    }
    .app-card h3 {
      margin: 0 0 10px;
    }
    .app-card p {
      font-size: 0.9em;
      flex-grow: 1;
      margin-bottom: 15px;
    }
    .btn-download {
      background: #28a745;
      color: white;
      border: none;
      padding: 12px;
      border-radius: 6px;
      font-weight: bold;
      cursor: pointer;
      text-decoration: none;
      display: inline-block;
    }
    .btn-download:hover {
      background: #218838;
    }
    .bonus-info {
      background: #fffbcc;
      border: 1px solid #ffe066;
      padding: 15px;
      border-radius: 6px;
      margin: 30px 0;
      text-align: center;
      font-weight: bold;
      color: #856404;
    }
    footer {
      background: #333;
      color: #ddd;
      text-align: center;
      padding: 15px 10px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bonusowe Aplikacje</h1>
    <p>Znajdź apki, w których otrzymasz ekstra bonusy!</p>
  </header>
  <main>
    <div class="bonus-info">
      Pobierz jedną z naszych aplikacji i odbierz specjalny bonus powitalny!
    </div>

    <div class="app-list">
      <div class="app-card">
        <img src="https://via.placeholder.com/140x140?text=Apka+1" alt="Apka 1" />
        <h3>Apka SuperBonus</h3>
        <p>Odbierz 50 zł bonusu za rejestrację i korzystaj z wielu promocji.</p>
        <a href="#" class="btn-download">Pobierz</a>
      </div>
      <div class="app-card">
        <img src="https://via.placeholder.com/140x140?text=Apka+2" alt="Apka 2" />
        <h3>Bonusowy Portfel</h3>
        <p>Zyskaj darmowe środki na start i korzystaj z wyjątkowych ofert.</p>
        <a href="#" class="btn-download">Pobierz</a>
      </div>
      <div class="app-card">
        <img src="https://via.placeholder.com/140x140?text=Apka+3" alt="Apka 3" />
        <h3>Premia24</h3>
        <p>Ekskluzywne bonusy dostępne tylko dla użytkowników tej aplikacji.</p>
        <a href="#" class="btn-download">Pobierz</a>
      </div>
    </div>
  </main>
  <footer>
    Kontakt: kontakt@bonusoweaplikacje.pl | &copy; 2025 Bonusowe Aplikacje
  </footer>
</body>
</html>
