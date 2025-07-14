<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV Celena Joseph</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background-color: #f5f5f5;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .cv-container {
            background-color: white;
            width: 800px;
            max-width: 100%;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            overflow: hidden;
            display: flex;
            flex-direction: column;
        }

        .header {
            background-color: #8B7355;
            color: white;
            padding: 40px;
            text-align: left;
        }

        .header h1 {
            font-size: 2.5em;
            font-weight: normal;
            margin-bottom: 10px;
            letter-spacing: 1px;
        }

        .header h2 {
            font-size: 1.2em;
            font-weight: 300;
            opacity: 0.9;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .content {
            display: flex;
            min-height: 600px;
        }

        .sidebar {
            background-color: #D4C4B0;
            width: 35%;
            padding: 40px 30px;
            color: #333;
        }

        .main-content {
            flex: 1;
            padding: 40px;
            background-color: white;
        }

        .section {
            margin-bottom: 35px;
        }

        .section h3 {
            color: #8B7355;
            font-size: 1.1em;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 15px;
            border-bottom: 2px solid #8B7355;
            padding-bottom: 5px;
        }

        .sidebar h3 {
            color: #5a4a3a;
            border-bottom: 2px solid #5a4a3a;
        }

        .contact-info {
            list-style: none;
            line-height: 1.8;
        }

        .contact-info li {
            margin-bottom: 8px;
            font-size: 0.9em;
        }

        .experience-item, .education-item {
            margin-bottom: 25px;
            padding-bottom: 20px;
            border-bottom: 1px solid #eee;
        }

        .experience-item:last-child, .education-item:last-child {
            border-bottom: none;
        }

        .job-title {
            font-weight: bold;
            color: #8B7355;
            font-size: 1.1em;
            margin-bottom: 5px;
        }

        .company {
            font-weight: 600;
            color: #333;
            margin-bottom: 3px;
        }

        .date {
            color: #666;
            font-size: 0.9em;
            font-style: italic;
            margin-bottom: 10px;
        }

        .description {
            color: #555;
            line-height: 1.6;
            font-size: 0.9em;
        }

        .skills-list {
            list-style: none;
            line-height: 1.8;
        }

        .skills-list li {
            margin-bottom: 8px;
            font-size: 0.9em;
            padding-left: 15px;
            position: relative;
        }

        .skills-list li:before {
            content: "•";
            color: #8B7355;
            font-weight: bold;
            position: absolute;
            left: 0;
        }

        .profile-text {
            line-height: 1.7;
            color: #555;
            font-size: 0.95em;
            text-align: justify;
        }

        .seminar-item {
            margin-bottom: 15px;
            padding-bottom: 15px;
            border-bottom: 1px solid #ddd;
        }

        .seminar-item:last-child {
            border-bottom: none;
        }

        .seminar-title {
            font-weight: 600;
            color: #5a4a3a;
            margin-bottom: 5px;
        }

        .seminar-details {
            font-size: 0.85em;
            color: #666;
            line-height: 1.5;
        }

        .icon-placeholder {
            width: 40px;
            height: 40px;
            background-color: #5a4a3a;
            margin-bottom: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 1.2em;
        }
    </style>
</head>
<body>
    <div class="cv-container">
        <div class="header">
            <h1>CELENA JOSEPH</h1>
            <h2>SPÉCIALISTE EN GESTION HÔTELIÈRE</h2>
        </div>

        <div class="content">
            <div class="sidebar">
                <div class="icon-placeholder">
                    📧
                </div>
                
                <div class="section">
                    <h3>CONTACT</h3>
                    <ul class="contact-info">
                        <li>Email disponible sur demande</li>
                        <li>Téléphone sur demande</li>
                        <li>Port-au-Prince, Haïti</li>
                    </ul>
                </div>

                <div class="section">
                    <h3>COMPÉTENCES</h3>
                    <ul class="skills-list">
                        <li>Service client excellence</li>
                        <li>Gestion de réception</li>
                        <li>Communication interpersonnelle</li>
                        <li>Tâches administratives</li>
                        <li>Accueil professionnel</li>
                        <li>Organisation et polyvalence</li>
                        <li>Gestion hôtelière</li>
                    </ul>
                </div>

                <div class="section">
                    <h3>SÉMINAIRES</h3>
                    <div class="seminar-item">
                        <div class="seminar-title">Prise de parole en public</div>
                        <div class="seminar-details">
                            Nov 2017 - Centre professionnel et universitaire (CRISA)
                        </div>
                    </div>
                    <div class="seminar-item">
                        <div class="seminar-title">Sommet droit des affaires</div>
                        <div class="seminar-details">
                            Déc 2020 - Acfis du Canada
                        </div>
                    </div>
                </div>
            </div>

            <div class="main-content">
                <div class="section">
                    <h3>PROFIL</h3>
                    <p class="profile-text">
                        Diplômée en Gestion Hôtelière, avec une expérience professionnelle en service client et en réception. Organisée, polyvalente et dotée d'un excellent sens du relationnel, je suis capable de gérer efficacement les tâches administratives tout en assurant un accueil chaleureux. Désireuse de contribuer à la performance d'une structure dynamique, je mets à profit mes compétences en communication, gestion et service client pour offrir une expérience de qualité.
                    </p>
                </div>

                <div class="section">
                    <h3>EXPÉRIENCE PROFESSIONNELLE</h3>
                    
                    <div class="experience-item">
                        <div class="job-title">Service Client</div>
                        <div class="company">Juvena's House Garden</div>
                        <div class="date">Novembre 2023 - Poste actuel</div>
                        <div class="description">
                            Assurer un service client de qualité et maintenir la satisfaction clientèle dans un environnement hôtelier dynamique.
                        </div>
                    </div>

                    <div class="experience-item">
                        <div class="job-title">Réceptionniste</div>
                        <div class="company">Alpha Distribution</div>
                        <div class="date">Mai 2022 - Juillet 2023</div>
                        <div class="description">
                            Gestion de l'accueil, traitement des demandes clients et coordination des tâches administratives de réception.
                        </div>
                    </div>
                </div>

                <div class="section">
                    <h3>FORMATION</h3>
                    
                    <div class="education-item">
                        <div class="job-title">BTS Gestion Hôtelière</div>
                        <div class="company">École hôtelière d'Haïti (EHH)</div>
                        <div class="date">2019 - 2021</div>
                        <div class="description">
                            Formation professionnelle spécialisée en management hôtelier et service client.
                        </div>
                    </div>

                    <div class="education-item">
                        <div class="job-title">Baccalauréat</div>
                        <div class="company">Institution Mixte St Joseph de Pétion Ville</div>
                        <div class="date">Bac 1 - Bac 2</div>
                        <div class="description">
                            Formation académique générale avec spécialisation progressive.
                        </div>
                    </div>
                </div>

                <div class="section">
                    <h3>RÉFÉRENCES</h3>
                    <p class="profile-text">Disponibles sur demande</p>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
