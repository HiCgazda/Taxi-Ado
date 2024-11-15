<!DOCTYPE html>
<html lang="bs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Taxi Ado - Pouzdana taxi usluga na Aerodromu Tuzla, dostupna 24/7">
    <title>Taxi Ado | Aerodrom Tuzla</title>
    <style>
        /* Osnovni stilovi */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }

        /* Navigacija */
        .navbar {
            background-color: #004aad;
            color: white;
            padding: 1rem;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .navbar h1 {
            margin: 0;
            font-size: 2rem;
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        /* Banner */
        .banner {
            width: 100%;
            height: 200px;
            background-color: #cfe2ff;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #004aad;
            font-size: 2rem;
            font-weight: bold;
            text-transform: uppercase;
        }

        /* Sekcija usluga */
        .services {
            padding: 2rem;
            background-color: #ffffff;
            text-align: center;
        }

        .services h2 {
            color: #004aad;
            font-size: 2.5rem;
            margin-bottom: 1rem;
            border-bottom: 2px solid #004aad;
            display: inline-block;
            padding-bottom: 0.5rem;
        }

        .service-list {
            display: flex;
            justify-content: space-around;
            margin-top: 1rem;
            gap: 1rem;
        }

        .service {
            flex: 1;
            margin: 1rem;
            padding: 1.5rem;
            background-color: #e9ecef;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s ease;
        }

        .service:hover {
            transform: scale(1.05);
        }

        .service h3 {
            font-size: 1.8rem;
            color: #004aad;
            margin-bottom: 0.5rem;
        }

        .service p {
            font-size: 1rem;
            color: #333;
        }

        /* Kontakt sekcija */
        .contact {
            background-color: #004aad;
            color: white;
            padding: 2rem;
            text-align: center;
        }

        .contact h2 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .contact-info p {
            font-size: 1.2rem;
        }

        .social-icons a {
            margin: 0.5rem;
            font-size: 1.5rem;
            color: white;
            text-decoration: none;
        }

        .social-icons a:hover {
            color: #ffd700;
        }

        /* Footer */
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            font-size: 0.9rem;
        }

        /* Responzivnost */
        @media (max-width: 768px) {
            .service-list {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

    <!-- Navigacija -->
    <div class="navbar">
        <h1>Taxi Ado - Aerodrom Tuzla</h1>
    </div>

    <!-- Banner -->
    <div class="banner">
        <span>Vaš partner za pouzdanu vožnju</span>
    </div>

    <!-- Sekcija usluga -->
    <section class="services">
        <h2>Naše usluge</h2>
        <div class="service-list">
            <div class="service">
                <h3>Radimo 24/7</h3>
                <p>Uvijek smo dostupni za vašu sigurnu i ugodnu vožnju, bez obzira na doba dana ili noći.</p>
            </div>
            <div class="service">
                <h3>Profesionalni vozači</h3>
                <p>Naši vozači su iskusni, ljubazni i uvijek spremni da vam pruže najbolju uslugu.</p>
            </div>
            <div class="service">
                <h3>Pristupačne cijene</h3>
                <p>Pružamo visokokvalitetnu uslugu po konkurentnim cijenama.</p>
            </div>
        </div>
    </section>

    <!-- Kontakt sekcija -->
    <section class="contact">
        <h2>Kontaktirajte nas</h2>
        <div class="contact-info">
            <p>Telefon: +387 61 704 225</p>
            <p>Email: info@taxiado.com</p>
        </div>
        <div class="social-icons">
            <a href="https://wa.me/38761704225" target="_blank">WhatsApp</a>
            <a href="https://m.me/TaxiAdo" target="_blank">Messenger</a>
            <a href="https://facebook.com/taxiado" target="_blank">Facebook</a>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2023 Taxi Ado. Sva prava zadržana.</p>
    </footer>

</body>
</html>
