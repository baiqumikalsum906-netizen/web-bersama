<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Profil BAIQ UMI KALSUM</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: #f0f2f5;
            margin: 0;
            padding: 0;
            color: #333;
        }
        .header {
            background-color: #ffffff;
            padding: 15px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid #ddd;
            box-shadow: 0 2px 5px rgba(0,0,0,0.05);
        }
        .logo {
            font-weight: bold;
            font-size: 24px;
            color: #007bff;
        }
        .nav {
            display: flex;
            gap: 20px;
        }
        .nav a {
            text-decoration: none;
            color: #000;
            font-weight: 600;
            transition: color 0.3s;
        }
        .nav a:hover {
            color: #007bff;
        }
        .profile-container {
            display: flex;
            padding: 20px;
            background-color: #e0e7ef;
            flex-wrap: wrap;
        }
        .profile-info {
            flex: 1;
            min-width: 300px;
            padding: 20px;
        }
        .profile-info h1 {
            font-size: 28px;
            font-weight: bold;
            margin-bottom: 10px;
        }
        .profile-info p {
            margin: 8px 0;
            line-height: 1.5;
        }
        .social-links {
            margin-top: 10px;
            display: flex;
            gap: 12px;
        }
        .social-links a {
            text-decoration: none;
            color: #007bff;
            font-weight: bold;
            font-size: 14px;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #007bff;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 15px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .button:hover {
            background-color: #0056b3;
        }
        .profile-image {
            flex: 1;
            display: flex;
            justify-content: center;
            align-items: center;
            min-width: 250px;
            padding: 10px;
        }
        .profile-image img {
            width: 220px;
            height: 220px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #fff;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .section {
            padding: 20px;
            background-color: #fff;
            margin: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.05);
        }
        .section h2 {
            font-size: 22px;
            font-weight: bold;
            margin-bottom: 15px;
            color: #007bff;
        }
        .education, .experience-list {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
        }
        .edu-item, .exp-item {
            background-color: #f9f9ff;
            padding: 15px;
            border-radius: 8px;
            width: 100%;
            max-width: 320px;
            border-left: 4px solid #007bff;
        }
        .skills {
            display: flex;
            gap: 12px;
            flex-wrap: wrap;
        }
        .skill {
            background-color: #007bff;
            color: #fff;
            padding: 8px 14px;
            border-radius: 20px;
            font-size: 14px;
            font-weight: 500;
        }
        footer {
            background-color: #222;
            color: #fff;
            text-align: center;
            padding: 15px;
            margin-top: 20px;
            font-size: 14px;
        }

        /* Responsif */
        @media (max-width: 768px) {
            .profile-container {
                flex-direction: column;
                align-items: center;
            }
            .profile-image img {
                width: 180px;
                height: 180px;
            }
            .nav {
                flex-direction: column;
                gap: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="header">
        <div class="logo">MY Profile</div>
        <div class="nav">
            <a href="#">Beranda</a>
            <a href="#">Riwayat Pendidikan</a>
            <a href="#">Pengalaman</a>
            <a href="#">Skills</a>
        </div>
    </div>

    <div class="profile-container">
        <div class="profile-info">
            <h1>BAIQ UMI KALSUM</h1>
            <p>📍 kec.Pujut,Diese,Desa Ketara, NTB</p>
            <p>📞 <a href="tel :087790919675" style="color: inherit; text-decoration: none;">087790919675</a></p>
            <p>✉️ <a href="mailto:baiqumikalsum.gmail.com" style="color: inherit; text-decoration: none;">baiqumikalsum906.gmail.com</a></p>
            
            <div class="social-links">
                <a href="https://wa.me/+6285926083377" target="_blank">💬 WhatsApp</a>
                <a href="https://github.com/baiqumikalsum906.gmail.com" target="_blank">🐙 GitHub</a>
                <a href="#" target="_blank">🔗 LinkedIn</a>
            </div>

            <p id="short-desc">Saya adalah Mahasiswa di Universitas Teknologi Mataram dengan homebase Program Studi Sistem Informasi. Memiliki latar belakang teknik Sistem infor dan bersemangat dalam pengembangan perangkat lunak serta pendidikan teknologi.</p>
            <div id="full-desc" style="display: none;">
                <p>Selain mengajar, saya aktif dalam penelitian bidang keamanan informasi, pengembangan aplikasi web, dan teknologi pendidikan. Saya percaya bahwa teknologi harus digunakan untuk memberdayakan masyarakat, terutama di daerah pedesaan seperti Bima.</p>
                <p>Saat ini, saya sedang menempuh studi lanjut di Universitas Mafia (UB) pada Program Studi Ilmu Komputer.</p>
            </div>
            <a id="toggle-btn" class="button">Baca Selengkapnya →</a>
        </div>
        <div class="profile-image">
            <!-- Placeholder foto profil -->
            <img src="c:\Users\DELL\Downloads\WhatsApp Image 2025-11-29 at 13.27.59.jpeg" alt="foto Profil baiqumikalsum">
        </div>
    </div>

    <div class="section">
        <h2>Riwayat Pendidikan</h2>
        <div class="education">
            <div class="edu-item">
                <p><strong>Universitas Teknologi Mataram (UTM)</strong></p>
                <p>Program Studi Rekayasa Perangkat Lunak<br><em>Lulus: 2025</em></p>
            </div>
            <div class="edu-item">
                <p><strong>Universitas teknologi mataram</strong></p>
                <p>Program Studi Teknik Informatika<br><em>Lulus: 2024</em></p>
            </div>
            <div class="edu-item">
                <p><strong>Universitas Brawijaya (UB)</strong></p>
                <p>Program Studi Sistem informasi<br><em>2025 - Sekarang (Studi Lanjut)</em></p>
            </div>
        </div>
    </div>

    <div class="section">
        <h2>Pengalaman Kerja</h2>
        <div class="experience-list">
            <div class="exp-item">
                <p><strong>Dosen Tetap</strong><br>Universitas Teknologi Mataram</p>
                <p><em>2023 – Sekarang</em></p>
                <p>Mengajar mata kuliah: Pemrograman Web, Basis Data, Sistem Informasi Manajemen.</p>
            </div>
            <div class="exp-item">
                <p><strong>Developer Freelance</strong></p>
                <p><em>2020 – 2023</em></p>
                <p>Membangun aplikasi web untuk UMKM dan instansi pendidikan di NTB.</p>
            </div>
        </div>
    </div>

    <div class="section">
        <h2>Skills & Kompetensi</h2>
        <div class="skills">
            <div class="skill">HTML5 & CSS3</div>
            <div class="skill">JavaScript (ES6+)</div>
            <div class="skill">React.js</div>
            <div class="skill">Node.js</div>
            <div class="skill">MySQL & MongoDB</div>
            <div class="skill">Figma</div>
            <div class="skill">Git & GitHub</div>
            <div class="skill">Pengajaran & Pelatihan</div>
        </div>
    </div>

    <footer>
        © 2025 San Sudirman. All Rights Reserved. (ss)
    </footer>

    <script>
        document.getElementById('toggle-btn').addEventListener('click', function() {
            const fullDesc = document.getElementById('full-desc');
            const shortDesc = document.getElementById('short-desc');
            const btn = this;

            if (fullDesc.style.display === 'none' || fullDesc.style.display === '') {
                fullDesc.style.display = 'block';
                shortDesc.style.display = 'none';
                btn.textContent = 'Tutup';
            } else {
                fullDesc.style.display = 'none';
                shortDesc.style.display = 'block';
                btn.textContent = 'Baca Selengkapnya →';
            }
        });
    </script>
</body>
</html>
