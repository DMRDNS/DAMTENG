<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DANISH Bliss Soap</title>
    <style>
        /* Gaya CSS */
        body {
            font-family: cursive, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #8c66ff;
            margin-bottom: 10px;
        }
        p {
            color: #666;
        }
        .tab {
            overflow: hidden;
            background-color: #f6f6f6#;
        }
        .tab button {
            background-color: transparent;
            border: none;
            outline: none;
            cursor: pointer;
            padding: 10px 20px;
            font-size: 16px;
            transition: 0.3s;
        }
        .tab button:hover {
            background-color: #8c66ff;
            color: white;
        }
        .tab button.active {
            background-color: #8c66ff;
            color: white;
        }
        .tabcontent {
            display: none;
            padding: 20px;
            border-top: 1px solid #ddd;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Selamat Datang di <span style="color: #8c66ff;">DANISH</span> Bliss Soap</h1>
        <img class="lavender-image" src="gambar-lavender.jpg" alt="Gambar Lavender">
        <p>Rasakan relaksasi yang luar biasa dengan <span style="color: #8c66ff;">DANISH Bliss Soap</span> yang mewah. Sabun kami dirancang dengan cermat untuk memberikan Anda pengalaman spa langsung di kamar mandi Anda.</p>

        <!-- Tab-fitur yang Didesain Ulang -->
        <div class="tab">
            <button class="tablinks" onclick="openTab(event, 'features')" id="defaultOpen">Fitur Utama</button>
            <button class="tablinks" onclick="openTab(event, 'usage')">Cara Penggunaan</button>
            <button class="tablinks" onclick="openTab(event, 'meaning')">Makna</button>
        </div>

        <!-- Konten Tab-fitur -->
        <div id="features" class="tabcontent">
            <h2>Fitur Utama:</h2>
            <ul>
                <li>Aroma yang Menenangkan</li>
                <li>Pembersihan Lembut</li>
                <li>Pengalaman Spa yang Tak Tertandingi</li>
                <li>Kualitas Premium</li>
            </ul>
        </div>

        <div id="usage" class="tabcontent">
            <h2>Cara Penggunaan:</h2>
            <ol>
                <li>Basahi tubuh Anda dengan air hangat.</li>
                <li>Oleskan <span style="color: #8c66ff;">DANISH Bliss Soap</span> pada kulit Anda dengan lembut.</li>
                <li>Nikmati aroma menenangkan saat Anda menghasilkan busa.</li>
                <li>Bilas dengan air bersih untuk merasakan kesegaran.</li>
            </ol>
        </div>
        
        <div id="meaning" class="tabcontent">
            <h2>Makna Nama "DANISH":</h2>
            <p>Nama "DANISH" adalah nama saya yang diambil dari Danishwara.</p>
        </div>

        <script>
            function openTab(evt, tabName) {
                var i, tabcontent, tablinks;
                tabcontent = document.getElementsByClassName("tabcontent");
                for (i = 0; i < tabcontent.length; i++) {
                    tabcontent[i].style.display = "none";
                }
                tablinks = document.getElementsByClassName("tablinks");
                for (i = 0; i < tablinks.length; i++) {
                    tablinks[i].className = tablinks[i].className.replace(" active", "");
                }
                document.getElementById(tabName).style.display = "block";
                evt.currentTarget.className += " active";
            }
            // Buka tab pertama secara otomatis
            document.getElementById("defaultOpen").click();
        </script>

        <p>Terima kasih telah mengunjungi kami. Untuk pemesanan, silakan hubungi kami.</p>
    </div>
</body>
</html>
