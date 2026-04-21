
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assistance - Listy</title>
    <style>
        :root {
            --main-blue: #BFECFA;
            --dark-blue: #2c3e50;
            --text-color: #34495e;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: #f9f9f9;
            color: var(--text-color);
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: var(--main-blue);
            padding: 40px 20px;
            text-align: center;
            border-bottom: 1px solid rgba(0,0,0,0.05);
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
            color: var(--dark-blue);
        }

        header p {
            margin: 10px 0 0;
            font-size: 1.1rem;
            opacity: 0.8;
        }

        .container {
            max-width: 800px;
            margin: -30px auto 50px;
            background: white;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 10px 25px rgba(0,0,0,0.05);
        }

        h2 {
            color: var(--dark-blue);
            border-bottom: 2px solid var(--main-blue);
            padding-bottom: 10px;
            margin-top: 30px;
        }

        .contact-card {
            background-color: #f0f7f9;
            padding: 20px;
            border-radius: 8px;
            border-left: 5px solid var(--main-blue);
            margin: 20px 0;
        }

        .faq-item {
            margin-bottom: 20px;
        }

        .faq-question {
            font-weight: bold;
            color: var(--dark-blue);
            display: block;
            margin-bottom: 5px;
        }

        .footer {
            text-align: center;
            font-size: 0.9rem;
            color: #95a5a6;
            margin-bottom: 40px;
        }

        a {
            color: #2980b9;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        @media (max-width: 600px) {
            .container {
                margin: 0 auto;
                border-radius: 0;
                padding: 20px;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Listy</h1>
    <p>Centre d'Assistance & Support</p>
</header>

<div class="container">
    <h2>Besoin d'aide ?</h2>
    <p>Si vous rencontrez un problème avec l'application ou si vous avez des suggestions pour l'améliorer, notre équipe est à votre écoute.</p>

    <div class="contact-card">
        <strong>📧 Contactez-nous par e-mail :</strong><br>
        <a href="mailto:ton-email@exemple.com">ton-email@exemple.com</a>
        <p style="margin: 5px 0 0; font-size: 0.85rem; color: #7f8c8d;">Nous répondons généralement sous 24h à 48h.</p>
    </div>

    <h2>Questions Fréquentes (FAQ)</h2>
    
    <div class="faq-item">
        <span class="faq-question">Comment synchroniser mes listes ?</span>
        <p>Vos listes sont automatiquement sauvegardées sur votre compte Cloud. Connectez-vous simplement avec le même identifiant sur un autre appareil pour retrouver vos données en temps réel.</p>
    </div>

    <div class="faq-item">
        <span class="faq-question">L'application fonctionne-t-elle hors connexion ?</span>
        <p>Pour le moment, une connexion internet active est nécessaire pour chaque modification afin de garantir la synchronisation. Une version hors-ligne est en cours de développement.</p>
    </div>

    <div class="faq-item">
        <span class="faq-question">Comment supprimer mon compte et mes données ?</span>
        <p>Allez dans les réglages de l'application, puis sélectionnez "Supprimer mon compte". Cette action supprimera définitivement vos listes de nos serveurs conformément au RGPD.</p>
    </div>

    <div class="faq-item">
        <span class="faq-question">Un bug à signaler ?</span>
        <p>Veuillez nous envoyer une capture d'écran et une description du problème par e-mail afin que nous puissions le corriger rapidement.</p>
    </div>
</div>

<div class="footer">
    &copy; 2026 Listy - Tous droits réservés.
</div>

</body>
</html>