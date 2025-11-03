<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Escala da Biju do Ser Mulher</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #fce7f3 0%, #fbcfe8 100%);
            min-height: 100vh;
            padding: 20px;
            color: #333;
        }

        .container {
            max-width: 480px;
            margin: 0 auto;
        }

        header {
            background: linear-gradient(135deg, #ec4899 0%, #db2777 100%);
            color: white;
            padding: 30px 20px;
            border-radius: 20px;
            text-align: center;
            margin-bottom: 25px;
            box-shadow: 0 10px 30px rgba(236, 72, 153, 0.3);
        }

        .header-title {
            font-size: 24px;
            font-weight: 700;
            margin-bottom: 10px;
            letter-spacing: 0.5px;
        }

        .header-subtitle {
            font-size: 14px;
            opacity: 0.95;
        }

        .decorative-icons {
            font-size: 24px;
            margin: 15px 0;
            letter-spacing: 8px;
        }

        .info-cards {
            display: grid;
            grid-template-columns: 1fr;
            gap: 15px;
            margin-bottom: 30px;
        }

        .card {
            background: white;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(236, 72, 153, 0.15);
            border-left: 5px solid #ec4899;
        }

        .card-icon {
            font-size: 28px;
            margin-bottom: 10px;
        }

        .card-title {
            font-size: 16px;
            font-weight: 600;
            color: #ec4899;
            margin-bottom: 8px;
        }

        .card-description {
            font-size: 13px;
            color: #666;
            line-height: 1.5;
        }

        .schedule-section {
            margin-bottom: 30px;
        }

        .section-title {
            font-size: 18px;
            font-weight: 700;
            color: #333;
            margin-bottom: 15px;
            padding-left: 10px;
            border-left: 4px solid #ec4899;
        }

        .schedule-card {
            background: white;
            margin-bottom: 12px;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(236, 72, 153, 0.1);
        }

        .schedule-header {
            background: linear-gradient(135deg, #ec4899 0%, #db2777 100%);
            color: white;
            padding: 15px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .schedule-date {
            font-size: 18px;
            font-weight: 700;
        }

        .day-badge {
            background: rgba(255, 255, 255, 0.3);
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 12px;
            font-weight: 600;
        }

        .schedule-content {
            padding: 15px;
        }

        .schedule-item {
            margin-bottom: 15px;
        }

        .schedule-item:last-child {
            margin-bottom: 0;
        }

        .item-label {
            font-size: 12px;
            font-weight: 600;
            color: #ec4899;
            margin-bottom: 8px;
            text-transform: uppercase;
        }

        .person-item {
            background: #fce7f3;
            padding: 10px;
            margin-bottom: 6px;
            border-radius: 8px;
            font-size: 14px;
            color: #333;
        }

        .person-item:last-child {
            margin-bottom: 0;
        }

        .notes-section {
            background: white;
            padding: 20px;
            border-radius: 15px;
            margin-bottom: 30px;
            box-shadow: 0 4px 15px rgba(236, 72, 153, 0.1);
        }

        .notes-title {
            font-size: 16px;
            font-weight: 700;
            color: #ec4899;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .notes-list {
            list-style: none;
        }

        .notes-list li {
            padding: 10px 0;
            padding-left: 25px;
            position: relative;
            font-size: 13px;
            color: #555;
            line-height: 1.6;
        }

        .notes-list li:before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #ec4899;
            font-weight: bold;
        }

        footer {
            background: linear-gradient(135deg, #ec4899 0%, #db2777 100%);
            color: white;
            padding: 30px 20px;
            border-radius: 20px;
            text-align: center;
            box-shadow: 0 10px 30px rgba(236, 72, 153, 0.3);
        }

        .footer-title {
            font-size: 22px;
            font-weight: 700;
            margin-bottom: 10px;
        }

        .footer-decorative {
            font-size: 20px;
            margin: 12px 0;
            letter-spacing: 6px;
        }

        .footer-subtitle {
            font-size: 14px;
            opacity: 0.95;
        }

        @media (max-width: 380px) {
            header {
                padding: 25px 15px;
            }

            .header-title {
                font-size: 20px;
            }

            .schedule-header {
                padding: 12px;
            }

            .schedule-date {
                font-size: 16px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="header-title">ESCALA DA BIJU DO SER MULHER</div>
            <div class="header-subtitle">Novembro/2025</div>
            <div class="decorative-icons">✨ 🌸 ✨</div>
        </header>

        <div class="info-cards">
            <div class="card">
                <div class="card-icon">🚪</div>
                <div class="card-title">Abertura</div>
                <div class="card-description">3 pessoas responsável por receber e acolher</div>
            </div>

            <div class="card">
                <div class="card-icon">🔒</div>
                <div class="card-title">Fechamento</div>
                <div class="card-description">2 pessoas responsáveis por encerrar e organizar</div>
            </div>
        </div>

        <div class="schedule-section">
            <div class="section-title">📅 Plantões</div>

            <div class="schedule-card">
                <div class="schedule-header">
                    <span class="schedule-date">26/11</span>
                    <span class="day-badge">Quarta-feira</span>
                </div>
                <div class="schedule-content">
                    <div class="schedule-item">
                        <div class="item-label">Abertura</div>
                        <div class="person-item">Rosemarie</div>
                        <div class="person-item">Jordana</div>
                        <div class="person-item">Maria Soledade</div>
                    </div>
                    <div class="schedule-item">
                        <div class="item-label">Fechamento</div>
                        <div class="person-item">Daniela</div>
                        <div class="person-item">Isis</div>
                    </div>
                </div>
            </div>

            <div class="schedule-card">
                <div class="schedule-header">
                    <span class="schedule-date">29/11</span>
                    <span class="day-badge">Último Sábado</span>
                </div>
                <div class="schedule-content">
                    <div class="schedule-item">
                        <div class="item-label">Abertura</div>
                        <div class="person-item">Kel</div>
                        <div class="person-item">Carla</div>
                        <div class="person-item">Balbina</div>
                    </div>
                    <div class="schedule-item">
                        <div class="item-label">Fechamento</div>
                        <div class="person-item">Presidenta Cibele</div>
                        <div class="person-item">Cris</div>
                    </div>
                </div>
            </div>
        </div>

        <div class="notes-section">
            <div class="notes-title">📌 Observações Importantes</div>
            <ul class="notes-list">
                <li>Abertura: 3 pessoas em horário de cultos</li>
                <li>Fechamento: 2 pessoas responsáveis por encerrar e organizar</li>
                <li>Equipes diferentes entre quartas e sábados</li>
                <li>Última quarta-feira (26/11): Rosemarie, Jordana e Maria Soledade</li>
                <li>Último sábado (29/11): Kel, Carla e Balbina na abertura</li>
                <li>Fechamento de sábado: Presidenta Cibele e Cris</li>
            </ul>
        </div>

        <footer>
            <div class="footer-title">Ser Mulher - Que Deus Abençoe!</div>
            <div class="footer-decorative">💕 🌸 💕</div>
        </footer>
    </div>
</body>
</html>
