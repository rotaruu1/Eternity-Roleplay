<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eternity Romania - FiveM</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        body {
            background-color: #e8f5e9;
            color: #333;
            text-align: center;
        }
        header {
            background: #2e7d32;
            padding: 20px;
            color: white;
            font-size: 2.5rem;
            font-weight: bold;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        .container {
            padding: 50px 20px;
            max-width: 900px;
            margin: auto;
        }
        .btn {
            display: inline-block;
            margin: 15px;
            padding: 15px 30px;
            background: #43a047;
            color: white;
            text-decoration: none;
            font-size: 1.2rem;
            border-radius: 8px;
            transition: transform 0.3s, background 0.3s;
        }
        .btn:hover {
            background: #388e3c;
            transform: scale(1.05);
        }
        .staff {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .staff-card {
            background: white;
            padding: 20px;
            margin: 10px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s;
        }
        .staff-card:hover {
            transform: translateY(-5px);
        }
    </style>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            const buttons = document.querySelectorAll(".btn");
            buttons.forEach(btn => {
                btn.addEventListener("mouseenter", () => btn.style.opacity = "0.8");
                btn.addEventListener("mouseleave", () => btn.style.opacity = "1");
            });
        });
    </script>
</head>
<body>
    <header>Eternity Romania</header>
    <div class="container">
        <p>Bine ai venit pe serverul nostru de FiveM! Distracție garantată!</p>
        <a href="regulament.html" class="btn">Vezi Regulamentul</a>
        <a href="https://discord.gg/yourlink" class="btn" target="_blank">Intră pe Discord</a>
        <div class="staff">
            <div class="staff-card">
                <h3>Admin1</h3>
                <p>Administrator</p>
            </div>
            <div class="staff-card">
                <h3>Mod1</h3>
                <p>Moderator</p>
            </div>
            <div class="staff-card">
                <h3>Helper1</h3>
                <p>Helper</p>
            </div>
        </div>
    </div>
</body>
</html>
