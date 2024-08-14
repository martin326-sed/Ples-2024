<!DOCTYPE html>
<html lang="sk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ples pre Mládež 2024</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: #fff;
            padding: 10px 20px;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            max-width: 900px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h2 {
            color: #333;
        }
        .form-group {
            margin-bottom: 15px;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
        }
        .form-group input, .form-group textarea {
            width: 100%;
            padding: 8px;
            box-sizing: border-box;
        }
        .form-group button {
            padding: 10px 15px;
            background-color: #333;
            color: #fff;
            border: none;
            cursor: pointer;
        }
        .form-group button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ples pre Mládež 2024</h1>
    </header>

    <nav>
        <a href="#home">Domov</a>
        <a href="#program">Program</a>
        <a href="#vstupenky">Vstupenky</a>
        <a href="#kontakt">Kontakt</a>
    </nav>

    <div class="container" id="home">
        <h2>Vitajte na plese pre mládež!</h2>
        <p>Príďte zažiť nezabudnuteľný večer plný hudby, tanca a zábavy. Rezervujte si svoje miesto na Plese pre Mládež 2024!</p>
    </div>

    <div class="container" id="program">
        <h2>Program Plesu</h2>
        <ul>
            <li>19:00 - 19:30: Privítanie hostí</li>
            <li>19:30 - 20:00: Otvorenie plesu, úvodné slovo</li>
            <li>20:00 - 21:00: DJ vystúpenie a voľná zábava</li>
            <li>21:00 - 21:30: Súťaž o najkrajšiu masku</li>
            <li>21:30 - 22:00: Živá hudba (vystúpenie miestnej kapely)</li>
            <li>22:00 - 23:00: Tombola</li>
            <li>23:00 - 01:00: DJ a voľná zábava, súťaže</li>
            <li>01:00 - 02:00: Ukončenie plesu</li>
        </ul>
    </div>

    <div class="container" id="vstupenky">
        <h2>Kúpiť Vstupenky</h2>
        <form action="https://example.com/platba" method="POST">
            <div class="form-group">
                <label for="name">Meno a priezvisko:</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="email">E-mail:</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="tickets">Počet vstupeniek:</label>
                <input type="number" id="tickets" name="tickets" required>
            </div>
            <div class="form-group">
                <button type="submit">Zakúpiť Vstupenky</button>
            </div>
        </form>
    </div>

    <div class="container" id="kontakt">
        <h2>Kontakt</h2>
        <p>Pre viac informácií nás kontaktujte na: <a href="mailto:info@plesmladez2024.sk">info@plesmladez2024.sk</a></p>
    </div>
</body>
</html>
