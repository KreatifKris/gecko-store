
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gecko Store</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #1b3a2f, #2e7d32);
            color: #fff;
        }

        .container {
            min-height: 100vh;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        h1 {
            margin-bottom: 30px;
            letter-spacing: 2px;
        }

        .gallery {
            width: 100%;
            max-width: 1100px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
            gap: 25px;
            margin-bottom: 40px;
        }

        .card {
            background: rgba(255, 255, 255, 0.1);
            border-radius: 16px;
            overflow: hidden;
            text-align: center;
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-6px);
        }

        /* FOTO KEDUA AGAK KE BAWAH */
        .gallery .card:nth-child(2) {
            margin-top: 40px;
        }

        .card img {
            width: 100%;
            display: block;
        }

        .card h3 {
            margin: 12px 0;
            font-size: 18px;
            letter-spacing: 1px;
        }

        .card a {
            text-decoration: none;
            color: white;
        }

        .order-button {
            padding: 16px 36px;
            background-color: #25D366;
            color: white;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            border-radius: 40px;
        }

        .order-button:hover {
            background-color: #1ebe5d;
        }

        /* OPSIONAL: agar tetap rapi di HP */
        @media (max-width: 600px) {
            .gallery .card:nth-child(2) {
                margin-top: 20px;
            }
        }
    </style>
</head>
<body>

<div class="container">

    <h1>GECKO STORE</h1>

    <div class="gallery">

        <div class="card">
            <a href="https://wa.me/6285655002016?text=saya%20mau%20order%20Blizzard" target="_blank">
                <img src="blizz..jpeg" alt="Blizzard Gecko">
                <h3>Blizzard</h3>
            </a>
        </div>

        <div class="card">
            <a href="https://wa.me/6285655002016?text=saya%20mau%20order%20Mack%20Snow" target="_blank">
                <img src="mack.jpeg" alt="Mack Snow Gecko">
                <h3>Mack Snow</h3>
            </a>
        </div>

        <div class="card">
            <a href="https://wa.me/6285655002016?text=saya%20mau%20order%20Tremper%20Albino" target="_blank">
                <img src="tremper.jpeg" alt="Tremper Albino Gecko">
                <h3>Tremper Albino</h3>
            </a>
        </div>

    </div>

    <a 
        class="order-button" 
        href="https://wa.me/6285655002016?text=saya%20mau%20order%20min"
        target="_blank">
        Order via WhatsApp
    </a>

</div>

</body>

