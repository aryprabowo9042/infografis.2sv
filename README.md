# infografis.2sv
Batas waktu penggunaan 2sv pada akun belajar.id untuk semua akun admin dan akun guru
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Infografis: Wajib Aktivasi Verifikasi 2 Langkah (2SV) Akun Belajar.id</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;900&display=swap" rel="stylesheet">
    <!-- Color Palette: Brilliant Blues -->
    <!-- Narrative Plan: Hook with deadline -> Explain 'Why' -> Detail 'Who' -> Emphasize 'When' -> Compare 'How' (Methods) -> List 'What' (Obligations) -> Provide 'Help'. -->
    <!-- Visualization Choices: -->
    <!-- 1. Countdown Timer (Change/Inform): JavaScript. Creates urgency. NO SVG. -->
    <!-- 2. Security Method Comparison (Compare/Rank): Horizontal Bar Chart with Chart.js. Visually ranks recommended methods. NO SVG. -->
    <!-- 3. Diagrams/Icons (Inform): Styled HTML and Unicode characters. NO SVG. -->
    <!-- Explicit confirmation: NEITHER Mermaid JS NOR SVG were used anywhere in the output. -->
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #E1E2E2;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            height: 320px;
            max-height: 400px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 400px;
            }
        }
        .countdown-item {
            background-color: #004AAD;
            color: #FFFFFF;
        }
    </style>
</head>
<body class="text-[#242F40]">

    <div class="container mx-auto p-4 md:p-8 max-w-5xl">
        <header class="text-center mb-12">
            <h1 class="text-4xl md:text-5xl font-extrabold text-[#004AAD] mb-4">Wajib Aktivasi Verifikasi 2 Langkah (2SV)</h1>
            <p class="text-lg md:text-xl text-[#242F40]">Untuk Seluruh Admin Akun Belajar.id Demi Keamanan Data Pendidikan</p>
        </header>

        <section id="countdown-section" class="mb-12 bg-white rounded-2xl shadow-lg p-6 md:p-8 text-center">
            <h2 class="text-2xl font-bold text-[#004AAD] mb-4">Batas Akhir Aktivasi</h2>
            <p class="text-5xl font-black text-[#242F40] mb-6">23 September 2025</p>
            <div id="countdown" class="flex justify-center space-x-2 md:space-x-4">
                <div class="countdown-item p-4 rounded-lg w-20 md:w-28">
                    <span id="days" class="text-4xl font-bold">0</span>
                    <span class="block text-xs">Hari</span>
                </div>
                <div class="countdown-item p-4 rounded-lg w-20 md:w-28">
                    <span id="hours" class="text-4xl font-bold">0</span>
                    <span class="block text-xs">Jam</span>
                </div>
                <div class="countdown-item p-4 rounded-lg w-20 md:w-28">
                    <span id="minutes" class="text-4xl font-bold">0</span>
                    <span class="block text-xs">Menit</span>
                </div>
                <div class="countdown-item p-4 rounded-lg w-20 md:w-28">
                    <span id="seconds" class="text-4xl font-bold">0</span>
                    <span class="block text-xs">Detik</span>
                </div>
            </div>
             <p class="mt-6 text-sm text-gray-600">Kegagalan aktivasi sebelum tenggat waktu akan berdampak pada akses login Anda.</p>
        </section>

        <main class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <div class="md:col-span-2 bg-white rounded-2xl shadow-lg p-6 md:p-8">
                <h2 class="text-3xl font-bold text-[#004AAD] mb-4">🛡️ Mengapa 2SV Penting?</h2>
                <p class="text-base text-gray-700 leading-relaxed">Verifikasi 2 Langkah (2SV) adalah lapisan keamanan esensial yang melindungi akun Anda dari akses tidak sah. Bahkan jika kata sandi Anda terungkap, peretas tidak dapat masuk tanpa langkah verifikasi kedua dari perangkat Anda. Ini secara drastis mengurangi risiko peretasan, penyalahgunaan akun, dan kebocoran data sensitif di lingkungan pendidikan.</p>
            </div>

            <div class="bg-white rounded-2xl shadow-lg p-6 md:p-8">
                <h2 class="text-3xl font-bold text-[#004AAD] mb-4">👥 Siapa yang Wajib Aktivasi?</h2>
                <p class="mb-6 text-base text-gray-700">Kebijakan ini berlaku untuk semua pengguna yang memiliki peran sebagai admin di ekosistem Belajar.id.</p>
                <ul class="space-y-4">
                    <li class="flex items-start p-4 bg-blue-50 rounded-lg">
                        <span class="text-2xl mr-4">1.</span>
                        <div>
                            <h3 class="font-semibold">Admin Akun Belajar.id</h3>
                            <p class="text-sm text-gray-600">Semua akun dengan domain @admin.[jenjang].belajar.id.</p>
                        </div>
                    </li>
                    <li class="flex items-start p-4 bg-blue-50 rounded-lg">
                        <span class="text-2xl mr-4">2.</span>
                        <div>
                            <h3 class="font-semibold">Guru & Pendidik Admin</h3>
                            <p class="text-sm text-gray-600">Akun @guru atau @pendidik yang memiliki peran admin.</p>
                        </div>
                    </li>
                    <li class="flex items-start p-4 bg-blue-50 rounded-lg">
                        <span class="text-2xl mr-4">3.</span>
                         <div>
                            <h3 class="font-semibold">Admin Non-Satuan Pendidikan</h3>
                            <p class="text-sm text-gray-600">Akun lain dengan akses ke Google Admin Console.</p>
                        </div>
                    </li>
                </ul>
            </div>

            <div class="bg-white rounded-2xl shadow-lg p-6 md:p-8">
                 <h2 class="text-3xl font-bold text-[#004AAD] mb-4">📋 Kewajiban Anda</h2>
                 <p class="mb-6 text-base text-gray-700">Sebagai admin, Anda wajib melakukan langkah-langkah berikut untuk memastikan keamanan akun.</p>
                 <ul class="space-y-4">
                    <li class="flex items-center">
                        <span class="text-green-500 text-2xl mr-3">✅</span>
                        <span>Aktifkan 2SV sebelum 23 September 2025.</span>
                    </li>
                    <li class="flex items-center">
                        <span class="text-green-500 text-2xl mr-3">✅</span>
                        <span>Gunakan metode verifikasi yang paling aman.</span>
                    </li>
                    <li class="flex items-center">
                        <span class="text-green-500 text-2xl mr-3">✅</span>
                        <span>Pastikan info kontak (telepon & email) valid.</span>
                    </li>
                    <li class="flex items-center">
                        <span class="text-green-500 text-2xl mr-3">✅</span>
                        <span>Simpan kode cadangan di tempat yang aman.</span>
                    </li>
                </ul>
            </div>
            
            <div class="md:col-span-2 bg-white rounded-2xl shadow-lg p-6 md:p-8">
                <h2 class="text-3xl font-bold text-[#004AAD] text-center mb-2">Perbandingan Metode Aktivasi 2SV</h2>
                <p class="text-center text-base text-gray-700 mb-6">Grafik ini menunjukkan tingkat keamanan relatif untuk setiap metode aktivasi. Metode yang lebih tinggi direkomendasikan untuk perlindungan maksimal. Pilihlah metode yang paling sesuai dan aman untuk Anda.</p>
                <div class="chart-container">
                    <canvas id="securityMethodsChart"></canvas>
                </div>
            </div>

            <div class="md:col-span-2 bg-white rounded-2xl shadow-lg p-6 md:p-8">
                <h2 class="text-3xl font-bold text-[#004AAD] mb-4">❓ Butuh Bantuan?</h2>
                <p class="mb-6 text-base text-gray-700">Jika Anda mengalami kendala atau memiliki pertanyaan selama proses aktivasi, jangan ragu untuk mencari bantuan melalui kanal resmi berikut.</p>
                <div class="flex flex-col md:flex-row md:space-x-4 space-y-4 md:space-y-0">
                    <a href="https://pusatinformasi.belajar.id/" target="_blank" class="flex-1 text-center bg-[#009FFD] text-white font-bold py-3 px-6 rounded-lg hover:bg-[#007ACC] transition duration-300">
                        Kunjungi Pusat Bantuan
                    </a>
                    <a href="https://wa.me/6281218040427" target="_blank" class="flex-1 text-center bg-[#25D366] text-white font-bold py-3 px-6 rounded-lg hover:bg-[#1DA851] transition duration-300">
                        Hubungi via WhatsApp (081218040427)
                    </a>
                </div>
            </div>

        </main>

        <footer class="text-center mt-12 text-sm text-gray-500">
            <p>Infografis ini dibuat berdasarkan Surat Pemberitahuan No. 20130/A.J1/TI.02.01/2025.</p>
            <p>&copy; 2025 Kementerian Pendidikan Dasar dan Menengah. Hak Cipta Dilindungi.</p>
        </footer>

    </div>

    <script>
        const countdown = () => {
            const countDate = new Date('September 23, 2025 00:00:00').getTime();
            const now = new Date().getTime();
            const gap = countDate - now;

            const second = 1000;
            const minute = second * 60;
            const hour = minute * 60;
            const day = hour * 24;

            const textDay = Math.floor(gap / day);
            const textHour = Math.floor((gap % day) / hour);
            const textMinute = Math.floor((gap % hour) / minute);
            const textSecond = Math.floor((gap % minute) / second);
            
            if (gap < 0) {
                 document.getElementById('countdown').innerHTML = '<div class="text-center w-full text-2xl font-bold text-red-600">Tenggat Waktu Telah Berakhir!</div>';
                 clearInterval(countdownInterval);
                 return;
            }

            document.getElementById('days').innerText = textDay;
            document.getElementById('hours').innerText = textHour;
            document.getElementById('minutes').innerText = textMinute;
            document.getElementById('seconds').innerText = textSecond;
        };

        let countdownInterval = setInterval(countdown, 1000);

        const wrapLabel = (label, maxLength) => {
            if (label.length <= maxLength) {
                return label;
            }
            const words = label.split(' ');
            const lines = [];
            let currentLine = '';
            words.forEach(word => {
                if ((currentLine + word).length > maxLength) {
                    lines.push(currentLine.trim());
                    currentLine = '';
                }
                currentLine += word + ' ';
            });
            lines.push(currentLine.trim());
            return lines;
        };
        
        const ctx = document.getElementById('securityMethodsChart').getContext('2d');
        const labels = [
            'Kunci Keamanan (Paling Aman)', 
            'Perintah/Dialog Google', 
            'Aplikasi Authenticator', 
            'Kode Verifikasi via SMS/Telepon'
        ].map(label => wrapLabel(label, 16));

        const securityMethodsChart = new Chart(ctx, {
            type: 'bar',
            data: {
                labels: labels,
                datasets: [{
                    label: 'Tingkat Keamanan (Relatif)',
                    data: [100, 85, 70, 40],
                    backgroundColor: [
                        '#004AAD',
                        '#009FFD',
                        '#50B3FE',
                        '#94D0FF'
                    ],
                    borderColor: [
                        '#004AAD',
                        '#009FFD',
                        '#50B3FE',
                        '#94D0FF'
                    ],
                    borderWidth: 1
                }]
            },
            options: {
                indexAxis: 'y',
                responsive: true,
                maintainAspectRatio: false,
                scales: {
                    x: {
                        beginAtZero: true,
                         max: 100,
                        title: {
                            display: true,
                            text: 'Skor Keamanan Relatif'
                        }
                    },
                    y: {
                        ticks: {
                           font: {
                               size: 10
                           }
                        }
                    }
                },
                plugins: {
                    legend: {
                        display: false
                    },
                    tooltip: {
                        callbacks: {
                            title: function(tooltipItems) {
                                const item = tooltipItems[0];
                                let label = item.chart.data.labels[item.dataIndex];
                                if (Array.isArray(label)) {
                                  return label.join(' ');
                                } else {
                                  return label;
                                }
                            }
                        }
                    }
                }
            }
        });
    </script>
</body>
</html>
