<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cartão de Visitas Digital | Engenharia e Gestão</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #1a365d; /* Azul Marinho Profissional */
            --secondary-color: #2d3748; /* Cinza Escuro */
            --accent-color: #3182ce; /* Azul Brilhante para Destaque */
            --bg-color: #f7fafc;
            --text-color: #2d3748;
            --white: #ffffff;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            display: flex;
            justify-content: center;
            align-items: flex-start;
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            width: 100%;
            max-width: 400px;
            background: var(--white);
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.1);
            overflow: hidden;
            text-align: center;
            padding-bottom: 30px;
        }

        .header {
            background: var(--primary-color);
            padding: 40px 20px;
            color: var(--white);
        }

        .profile-img {
            width: 110px;
            height: 110px;
            border-radius: 50%;
            border: 4px solid var(--white);
            margin-bottom: 15px;
            object-fit: cover;
        }

        h1 {
            font-size: 1.5rem;
            margin-bottom: 5px;
        }

        .subtitle {
            font-size: 0.9rem;
            opacity: 0.9;
            font-weight: 400;
        }

        .location {
            font-size: 0.8rem;
            margin-top: 8px;
            display: block;
        }

        .content {
            padding: 20px;
        }

        .section-title {
            font-size: 0.85rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            color: var(--accent-color);
            margin: 20px 0 15px;
            font-weight: 700;
            text-align: left;
            border-bottom: 1px solid #edf2f7;
            padding-bottom: 5px;
        }

        .btn-container {
            display: grid;
            gap: 12px;
        }

        .btn {
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 12px;
            border-radius: 10px;
            text-decoration: none;
            font-weight: 600;
            transition: transform 0.2s, background 0.2s;
            gap: 10px;
        }

        .btn-primary {
            background-color: var(--primary-color);
            color: var(--white);
        }

        .btn-secondary {
            background-color: #edf2f7;
            color: var(--secondary-color);
        }

        .btn:active {
            transform: scale(0.98);
        }

        .specialties {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
            justify-content: flex-start;
        }

        .badge {
            background: #e2e8f0;
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 0.75rem;
            font-weight: 600;
        }

        .footer {
            margin-top: 20px;
            font-size: 0.75rem;
            color: #a0aec0;
        }

        /* Simulação de interatividade */
        .card-info {
            text-align: left;
            background: #f8fafc;
            padding: 15px;
            border-radius: 12px;
            margin-top: 10px;
            font-size: 0.9rem;
            line-height: 1.5;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="header">
        <img src="https://via.placeholder.com/150" alt="Foto de Perfil" class="profile-img">
        <h1>[Seu Nome Completo]</h1>
        <p class="subtitle">Engenheiro Mecânico | Facilities & Manutenção</p>
        <span class="location"><i class="fas fa-map-marker-alt"></i> Bauru e Região, SP</span>
    </div>

    <div class="content">
        <div class="section-title">Contato Imediato</div>
        <div class="btn-container">
            <a href="https://wa.me/5514999999999" class="btn btn-primary">
                <i class="fab fa-whatsapp"></i> Conversar no WhatsApp
            </a>
            <a href="mailto:seu-email@dominio.com" class="btn btn-secondary">
                <i class="far fa-envelope"></i> Enviar E-mail
            </a>
            <a href="#" class="btn btn-secondary">
                <i class="fab fa-linkedin"></i> Perfil Profissional
            </a>
            <a href="#" class="btn btn-secondary" style="background: var(--accent-color); color: white;">
                <i class="fas fa-user-plus"></i> Salvar na Agenda (.VCF)
            </a>
        </div>

        <div class="section-title">Especialidades Técnicas</div>
        <div class="specialties">
            <span class="badge">Retrofit de Chillers (CAG)</span>
            <span class="badge">Sistemas HVAC (400-450 TR)</span>
            <span class="badge">Eficiência Energética</span>
            <span class="badge">Norma NBR 7256</span>
            <span class="badge">Gestão de Contratos</span>
            <span class="badge">Automação de Processos</span>
        </div>

        <div class="section-title">Projetos & Consultoria</div>
        <div class="card-info">
            <strong>Gestão de Ativos:</strong> Planejamento e execução de manutenção preventiva e corretiva para plantas de grande porte.<br><br>
            <strong>Engenharia de Aplicação:</strong> Implementação de planos de ação para CAG e substituição de equipamentos York/Similares.
        </div>

        <div class="section-title">Agendar Reunião</div>
        <div class="btn-container">
            <a href="#" class="btn btn-secondary">
                <i class="far fa-calendar-alt"></i> Ver Disponibilidade (Calendly)
            </a>
        </div>

        <div class="footer">
            &copy; 2026 • Engenharia Mecânica de Alta Performance
        </div>
    </div>
</div>

</body>
</html>
