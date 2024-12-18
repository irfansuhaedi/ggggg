# ggggg
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="PT TAL Sarana Logistik - Solusi Logistik Profesional">
    <title>PT TAL Sarana Logistik</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Montserrat:wght@500;800&display=swap');

        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            background: url('https://www.distri.id/wp-content/uploads/sites/2/2024/09/Manajemen-Logistik-Adalah-Arti-Fungsi-Manfaat-dan-Komponen.jpg') no-repeat center center/cover;
            background-attachment: fixed;
        }
        header {
            background: rgba(0, 64, 128, 0.7);
            color: white;
            padding: 40px 20px;
            text-align: center;
            position: relative;
        }
        header img, header h1, header p {
            position: relative;
            z-index: 2;
        }
        header img {
            max-width: 150px;
            height: auto;
            margin-bottom: 10px;
        }
        header h1 {
            font-family: 'Montserrat', sans-serif;
            font-weight: 800;
            font-size: 2.5rem;
            margin: 0;
        }
        header p {
            font-family: 'Roboto', sans-serif;
            font-weight: 400;
            font-size: 1.2rem;
            margin-top: 10px;
        }
        nav {
            background-color: #00264d;
            padding: 10px 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-family: 'Montserrat', sans-serif;
            font-weight: 500;
            font-size: 1rem;
            transition: color 0.3s ease;
        }
        nav ul li a:hover {
            color: #ffcc00;
        }
        section {
            padding: 40px 20px;
            text-align: center;
            background: rgba(255, 255, 255, 0.9);
            margin: 20px auto;
            border-radius: 8px;
            max-width: 1000px;
        }
        section h2 {
            font-family: 'Montserrat', sans-serif;
            font-weight: 800;
            font-size: 2rem;
            margin-bottom: 20px;
            color: #004080;
        }
        section p {
            font-family: 'Roboto', sans-serif;
            font-weight: 400;
            font-size: 1.1rem;
            color: #555;
        }
        footer {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .floating-links {
            position: fixed;
            left: 10px;
            bottom: 50px;
            display: flex;
            flex-direction: column;
            gap: 10px;
            z-index: 1000;
        }
        .floating-links a {
            display: flex;
            align-items: center;
            gap: 10px;
            background-color: #25D366;
            color: white;
            padding: 10px 15px;
            border-radius: 50px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
            font-size: 1.2rem;
            text-align: center;
            text-decoration: none;
            font-family: 'Montserrat', sans-serif;
            font-weight: 700;
            transition: background-color 0.3s ease;
        }
        .floating-links a.linkedin {
            background-color: #0077b5;
        }
        .floating-links a:hover {
            background-color: #128C7E;
        }
        .floating-links a.linkedin:hover {
            background-color: #005582;
        }
        .floating-links img {
            width: 24px;
            height: 24px;
        }
        .camera-section {
            margin-top: 20px;
        }
        #camera-container {
            margin: 20px auto;
            max-width: 600px;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 10px;
        }
        #camera-container video {
            width: 100%;
            border-radius: 8px;
            border: 2px solid #004080;
        }
        #start-camera {
            padding: 10px 20px;
            background-color: #004080;
            color: white;
            border: none;
            border-radius: 5px;
            font-family: 'Montserrat', sans-serif;
            font-size: 1rem;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        #start-camera:hover {
            background-color: #00264d;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://sdn.signalhire.co/storage/company/dbc5/4407/6174/8730/e5bf/1531/be05/c047.webp" alt="Logo PT TAL Sarana Logistik">
        <h1>IRFAN SUHAEDI</h1>
        <p>Solusi Logistik Profesional untuk Bisnis Anda</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">Tentang Kami</a></li>
            <li><a href="#services">Layanan</a></li>
            <li><a href="#contact">Kontak</a></li>
        </ul>
    </nav>

    <section id="about">
        <h2>Tentang Kami</h2>
        <p>PT TAL Sarana Logistik adalah perusahaan yang menyediakan layanan logistik terintegrasi untuk mendukung kebutuhan bisnis Anda. Dengan pengalaman bertahun-tahun, kami berkomitmen memberikan layanan terbaik untuk memastikan barang Anda tiba tepat waktu dan aman.</p>
    </section>

    <section class="camera-section">
        <h2>Akses Kamera</h2>
        <div id="camera-container">
            <video id="camera" autoplay></video>
            <button id="start-camera">Mulai Kamera</button>
        </div>
    </section>

    <div class="floating-links">
        <a href="https://wa.me/+6289502702764" target="_blank">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp"> WhatsApp
        </a>
        <a href="https://www.linkedin.com/in/irfan-suhaedi" target="_blank" class="linkedin">
            <img src="https://upload.wikimedia.org/wikipedia/commons/e/e9/Linkedin_icon.svg" alt="LinkedIn"> LinkedIn
        </a>
    </div>

    <footer>
        <p>&copy; 2024 PT TAL Sarana Logistik. Semua Hak Dilindungi.</p>
    </footer>

    <script>
        const startCameraButton = document.getElementById('start-camera');
        const camera = document.getElementById('camera');

        startCameraButton.addEventListener('click', async () => {
            try {
                const stream = await navigator.mediaDevices.getUserMedia({ video: true });
                camera.srcObject = stream;
            } catch (error) {
                alert('Kamera tidak dapat diakses: ' + error.message);
            }
        });
    </script>
</body>
</html>
