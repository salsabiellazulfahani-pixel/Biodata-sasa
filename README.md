# <!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biodata | Salsabiella Zulfahani</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .card {
            background: white;
            border-radius: 24px;
            box-shadow: 0 30px 60px rgba(0, 0, 0, 0.3);
            max-width: 480px;
            width: 100%;
            overflow: hidden;
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .header {
            background: linear-gradient(135deg, #ff6b6b, #ee5a24);
            padding: 35px 25px;
            text-align: center;
            color: white;
        }

        .avatar {
            width: 100px;
            height: 100px;
            background: white;
            border-radius: 50%;
            margin: 0 auto 15px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2.8rem;
            font-weight: 700;
            color: #ee5a24;
            border: 4px solid rgba(255, 255, 255, 0.6);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
        }

        .name {
            font-size: 1.8rem;
            font-weight: 700;
            margin-bottom: 4px;
            letter-spacing: 1px;
        }

        .school {
            font-size: 1rem;
            opacity: 0.95;
            font-weight: 500;
        }

        .body-content {
            padding: 30px 25px;
        }

        .info-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
            margin-bottom: 25px;
        }

        .info-item {
            background: #f8f9fa;
            padding: 15px;
            border-radius: 14px;
            text-align: center;
            transition: all 0.3s ease;
            border: 1px solid #e9ecef;
        }

        .info-item:hover {
            background: #eef0ff;
            border-color: #667eea;
            transform: translateY(-2px);
            box-shadow: 0 6px 15px rgba(102, 126, 234, 0.15);
        }

        .info-label {
            font-size: 0.75rem;
            text-transform: uppercase;
            color: #888;
            letter-spacing: 1px;
            margin-bottom: 6px;
            font-weight: 600;
        }

        .info-value {
            font-size: 1.1rem;
            font-weight: 700;
            color: #2d3436;
        }

        .quote-box {
            background: linear-gradient(135deg, #f8f9fa, #e9ecef);
            padding: 20px 22px;
            border-radius: 16px;
            margin-bottom: 25px;
            text-align: center;
            border-left: 5px solid #ee5a24;
            position: relative;
        }

        .quote-icon {
            font-size: 2rem;
            color: #ee5a24;
            opacity: 0.4;
            margin-bottom: 5px;
        }

        .quote-text {
            font-size: 1rem;
            font-style: italic;
            color: #444;
            line-height: 1.6;
            font-weight: 500;
        }

        .quote-author {
            font-size: 0.85rem;
            color: #888;
            margin-top: 8px;
            font-weight: 600;
        }

        .btn-project {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            width: 100%;
            padding: 16px 20px;
            background: linear-gradient(135deg, #1e3c72, #2a5298);
            color: white;
            border: none;
            border-radius: 14px;
            font-size: 1.1rem;
            font-weight: 600;
            cursor: pointer;
            text-decoration: none;
            transition: all 0.3s ease;
            letter-spacing: 0.5px;
            box-shadow: 0 8px 20px rgba(30, 60, 114, 0.3);
        }

        .btn-project:hover {
            background: linear-gradient(135deg, #2a5298, #1e3c72);
            transform: translateY(-3px);
            box-shadow: 0 14px 28px rgba(30, 60, 114, 0.4);
        }

        .btn-project:active {
            transform: translateY(0);
            box-shadow: 0 6px 15px rgba(30, 60, 114, 0.3);
        }

        .btn-icon {
            font-size: 1.4rem;
        }

        .footer {
            text-align: center;
            padding: 15px;
            color: #aaa;
            font-size: 0.75rem;
            border-top: 1px solid #f0f0f0;
        }

        .badge {
            display: inline-block;
            background: #ee5a24;
            color: white;
            padding: 4px 12px;
            border-radius: 20px;
            font-size: 0.75rem;
            font-weight: 600;
            margin-top: 8px;
        }

        /* Responsif */
        @media (max-width: 480px) {
            .info-grid {
                grid-template-columns: 1fr 1fr;
                gap: 10px;
            }
            .name {
                font-size: 1.5rem;
            }
            .body-content {
                padding: 20px 18px;
            }
            .header {
                padding: 25px 18px;
            }
        }
    </style>
</head>
<body>
    <div class="card">
        <!-- Header -->
        <div class="header">
            <div class="avatar">S</div>
            <div class="name">Salsabiella Zulfahani</div>
            <div class="school">SMAN 15 Jakarta</div>
            <span class="badge">Kelas X5</span>
        </div>

        <!-- Body -->
        <div class="body-content">
            <!-- Info Grid -->
            <div class="info-grid">
                <div class="info-item">
                    <div class="info-label">🎓 Sekolah</div>
                    <div class="info-value">SMAN 15</div>
                </div>
                <div class="info-item">
                    <div class="info-label">📚 Kelas</div>
                    <div class="info-value">X5</div>
                </div>
                <div class="info-item">
                    <div class="info-label">🎂 Usia</div>
                    <div class="info-value">17 Tahun</div>
                </div>
                <div class="info-item">
                    <div class="info-label">📍 Kota</div>
                    <div class="info-value">Jakarta</div>
                </div>
            </div>

            <!-- Quote / Motto -->
            <div class="quote-box">
                <div class="quote-icon">❝</div>
                <p class="quote-text">
                    "Mimpi besar dimulai dari langkah kecil. Percayalah pada dirimu sendiri, karena kamu mampu mencapai lebih dari yang kamu bayangkan."
                </p>
                <p class="quote-author">— Salsabiella Zulfahani</p>
            </div>

            <!-- Tombol Proyek -->
            <a href="https://ats1922.github.io/Monopoli123/" target="_blank" class="btn-project">
                <span class="btn-icon">🚀</span>
                Lihat Proyek Saya
                <span style="font-size: 1.2rem;">↗</span>
            </a>
        </div>

        <!-- Footer -->
        <div class="footer">
            © 2025 Salsabiella Zulfahani • Dibuat dengan ❤️
        </div>
    </div>
</body>
</html>
