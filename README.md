<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Resmi Kelas 8B</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
        }
        .glass-card {
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.3);
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased min-h-screen flex flex-col">

    <!-- Navigation Bar -->
    <nav class="sticky top-0 z-50 bg-indigo-600 text-white shadow-lg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <div class="flex items-center space-x-3">
                    <span class="p-2 bg-indigo-700 rounded-lg text-xl"><i class="fa-solid font-bold fa-graduation-cap"></i></span>
                    <span class="font-bold text-xl tracking-wide">Kelas 8B</span>
                </div>
                
                <!-- Desktop Menu -->
                <div class="hidden md:flex space-x-6 font-medium text-sm">
                    <a href="#home" class="hover:text-indigo-200 transition">Beranda</a>
                    <a href="#pengumuman" class="hover:text-indigo-200 transition">Pengumuman</a>
                    <a href="#jadwal" class="hover:text-indigo-200 transition">Jadwal</a>
                    <a href="#struktur" class="hover:text-indigo-200 transition">Pengurus</a>
                    <a href="#siswa" class="hover:text-indigo-200 transition">Siswa</a>
                    <a href="#galeri" class="hover:text-indigo-200 transition">Galeri</a>
                    <a href="#keuangan" class="hover:text-indigo-200 transition">Kas Kelas</a>
                </div>

                <!-- Mobile Menu Button -->
                <button id="mobile-menu-btn" class="md:hidden text-2xl focus:outline-none">
                    <i class="fa-solid fa-bars"></i>
                </button>
            </div>
        </div>

        <!-- Mobile Dropdown Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-indigo-700 px-4 pt-2 pb-4 space-y-2">
            <a href="#home" class="block py-2 hover:bg-indigo-600 rounded px-2">Beranda</a>
            <a href="#pengumuman" class="block py-2 hover:bg-indigo-600 rounded px-2">Pengumuman</a>
            <a href="#jadwal" class="block py-2 hover:bg-indigo-600 rounded px-2">Jadwal</a>
            <a href="#struktur" class="block py-2 hover:bg-indigo-600 rounded px-2">Pengurus</a>
            <a href="#siswa" class="block py-2 hover:bg-indigo-600 rounded px-2">Siswa</a>
            <a href="#galeri" class="block py-2 hover:bg-indigo-600 rounded px-2">Galeri</a>
            <a href="#keuangan" class="block py-2 hover:bg-indigo-600 rounded px-2">Kas Kelas</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="relative bg-gradient-to-r from-indigo-500 to-purple-600 text-white py-20 px-4 text-center">
        <div class="max-w-4xl mx-auto space-y-4">
            <h1 class="text-4xl md:text-6xl font-extrabold tracking-tight">Selamat Datang di Website Resmi Kelas 8B</h1>
            <p class="text-indigo-100 text-lg md:text-xl font-light">Wadah komunikasi, informasi, dan dokumentasi kebersamaan keluarga besar Kelas 8B MTs. DDI Kel. Baru.</p>
            <div class="pt-4 flex justify-center space-x-4">
                <a href="#jadwal" class="bg-white text-indigo-600 font-semibold px-6 py-3 rounded-full shadow hover:bg-indigo-50 transition transform hover:-translate-y-0.5">Lihat Jadwal</a>
                <a href="#galeri" class="bg-indigo-700 text-white font-semibold px-6 py-3 rounded-full shadow hover:bg-indigo-800 transition transform hover:-translate-y-0.5">Galeri Kenangan</a>
            </div>
        </div>
    </section>

    <!-- Main Content Wrapper -->
    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10 space-y-16 flex-grow">

        <!-- Section Pengumuman -->
        <section id="pengumuman" class="scroll-mt-20">
            <div class="flex items-center space-x-3 mb-6">
                <div class="p-3 bg-red-100 text-red-600 rounded-xl"><i class="fa-solid fa-bullhorn text-2xl"></i></div>
                <div>
                    <h2 class="text-2xl font-bold">Pengumuman Penting</h2>
                    <p class="text-slate-500 text-sm">Informasi terbaru mengenai kegiatan kelas & sekolah</p>
                </div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-100 border-l-4 border-l-indigo-500 hover:shadow-md transition">
                    <span class="text-xs font-semibold uppercase tracking-wider text-indigo-500">Akademik</span>
                    <h3 class="text-lg font-bold mt-1">Ujian Tengah Semester (UTS)</h3>
                    <p class="text-slate-600 text-sm mt-2">Pelaksanaan UTS akan dimulai tanggal 15 September. Diharapkan seluruh siswa melunasi administrasi dan mempersiapkan diri.</p>
                    <div class="mt-4 text-xs text-slate-400"><i class="fa-regular fa-clock mr-1"></i> Diposting: 2 Hari yang lalu</div>
                </div>

                <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-100 border-l-4 border-l-emerald-500 hover:shadow-md transition">
                    <span class="text-xs font-semibold uppercase tracking-wider text-emerald-500">Kegiatan</span>
                    <h3 class="text-lg font-bold mt-1">Kerja Bakti & Dekorasi Kelas</h3>
                    <p class="text-slate-600 text-sm mt-2">Sabtu ini akan diadakan pembersihan dan penataan ulang mading kelas. Harap membawa peralatan kebersihan masing-masing.</p>
                    <div class="mt-4 text-xs text-slate-400"><i class="fa-regular fa-clock mr-1"></i> Diposting: Kemarin</div>
                </div>
            </div>
        </section>

        <!-- Section Jadwal Pelajaran -->
        <section id="jadwal" class="scroll-mt-20">
            <div class="flex items-center space-x-3 mb-6">
                <div class="p-3 bg-blue-100 text-blue-600 rounded-xl"><i class="fa-solid fa-calendar-days text-2xl"></i></div>
                <div>
                    <h2 class="text-2xl font-bold">Jadwal Pelajaran</h2>
                    <p class="text-slate-500 text-sm">Jadwal mata pelajaran mingguan Kelas 8B</p>
                </div>
            </div>

            <!-- Tab Hari -->
            <div class="bg-white p-4 rounded-2xl shadow-sm border border-slate-100">
                <div class="flex overflow-x-auto space-x-2 pb-2 mb-4 border-b text-sm font-medium" id="day-tabs">
                    <button onclick="switchDay('senin')" class="day-tab px-4 py-2 rounded-lg bg-indigo-600 text-white font-semibold transition" data-day="senin">Senin</button>
                    <button onclick="switchDay('selasa')" class="day-tab px-4 py-2 rounded-lg hover:bg-slate-100 text-slate-600 transition" data-day="selasa">Selasa</button>
                    <button onclick="switchDay('rabu')" class="day-tab px-4 py-2 rounded-lg hover:bg-slate-100 text-slate-600 transition" data-day="rabu">Rabu</button>
                    <button onclick="switchDay('kamis')" class="day-tab px-4 py-2 rounded-lg hover:bg-slate-100 text-slate-600 transition" data-day="kamis">Kamis</button>
                    <button onclick="switchDay('jumat')" class="day-tab px-4 py-2 rounded-lg hover:bg-slate-100 text-slate-600 transition" data-day="jumat">Jumat</button>
                </div>

                <!-- Content Jadwal -->
                <div id="schedule-content" class="space-y-3">
                    <!-- JavaScript akan mengisi bagian ini -->
                </div>
            </div>
        </section>

        <!-- Section Pengurus Kelas -->
        <section id="struktur" class="scroll-mt-20">
            <div class="flex items-center space-x-3 mb-6">
                <div class="p-3 bg-purple-100 text-purple-600 rounded-xl"><i class="fa-solid fa-sitemap text-2xl"></i></div>
                <div>
                    <h2 class="text-2xl font-bold">Struktur Organisasi Kelas</h2>
                    <p class="text-slate-500 text-sm">Pengurus dan penanggung jawab Kelas 8B</p>
                </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-6">
                <!-- Wali Kelas -->
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-100 text-center hover:shadow-md transition">
                    <div class="w-24 h-24 mx-auto mb-4 rounded-full overflow-hidden bg-slate-200 border-2 border-indigo-500">
                        <img src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?auto=format&fit=crop&q=80&w=300" alt="Wali Kelas Ibu Nuriana" class="w-full h-full object-cover">
                    </div>
                    <span class="text-xs font-semibold px-3 py-1 bg-indigo-100 text-indigo-600 rounded-full">Wali Kelas</span>
                    <h3 class="font-bold text-lg mt-2">Ibu Nuriana</h3>
                    <p class="text-slate-500 text-xs mt-1">Guru Pembimbing</p>
                </div>

                <!-- Ketua Kelas -->
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-100 text-center hover:shadow-md transition">
                    <div class="w-24 h-24 mx-auto mb-4 rounded-full overflow-hidden bg-slate-200 border-2 border-blue-500">
                        <img src="https://images.unsplash.com/photo-1539571696357-5a69c17a67c6?auto=format&fit=crop&q=80&w=300" alt="Ketua Kelas Virgiawan" class="w-full h-full object-cover">
                    </div>
                    <span class="text-xs font-semibold px-3 py-1 bg-blue-100 text-blue-600 rounded-full">Ketua Kelas</span>
                    <h3 class="font-bold text-lg mt-2">Virgiawan</h3>
                    <p class="text-slate-500 text-xs mt-1">Siswa Kelas 8B</p>
                </div>

                <!-- Wakil Ketua -->
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-100 text-center hover:shadow-md transition">
                    <div class="w-24 h-24 mx-auto mb-4 rounded-full overflow-hidden bg-slate-200 border-2 border-emerald-500">
                        <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&q=80&w=300" alt="Wakil Ketua Reza" class="w-full h-full object-cover">
                    </div>
                    <span class="text-xs font-semibold px-3 py-1 bg-emerald-100 text-emerald-600 rounded-full">Wakil Ketua</span>
                    <h3 class="font-bold text-lg mt-2">Reza</h3>
                    <p class="text-slate-500 text-xs mt-1">Siswa Kelas 8B</p>
                </div>

                <!-- Bendahara -->
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-100 text-center hover:shadow-md transition">
                    <div class="w-24 h-24 mx-auto mb-4 rounded-full overflow-hidden bg-slate-200 border-2 border-amber-500">
                        <img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1?auto=format&fit=crop&q=80&w=300" alt="Bendahara Nur Alya" class="w-full h-full object-cover">
                    </div>
                    <span class="text-xs font-semibold px-3 py-1 bg-amber-100 text-amber-600 rounded-full">Bendahara</span>
                    <h3 class="font-bold text-lg mt-2">Nur Alya</h3>
                    <p class="text-slate-500 text-xs mt-1">Siswa Kelas 8B</p>
                </div>
            </div>
        </section>

        <!-- Section Anggota Siswa -->
        <section id="siswa" class="scroll-mt-20">
            <div class="flex flex-col md:flex-row md:items-center md:justify-between mb-6 gap-4">
                <div class="flex items-center space-x-3">
                    <div class="p-3 bg-amber-100 text-amber-600 rounded-xl"><i class="fa-solid fa-users text-2xl"></i></div>
                    <div>
                        <h2 class="text-2xl font-bold">Daftar Siswa</h2>
                        <p class="text-slate-500 text-sm">Anggota Kelas 8B</p>
                    </div>
                </div>
                <!-- Search Box -->
                <div class="relative w-full md:w-64">
                    <input type="text" id="search-student" onkeyup="filterStudents()" placeholder="Cari nama siswa..." class="w-full pl-10 pr-4 py-2 rounded-xl border border-slate-200 focus:outline-none focus:ring-2 focus:ring-indigo-500 text-sm">
                    <i class="fa-solid fa-magnifying-glass absolute left-3 top-3 text-slate-400 text-sm"></i>
                </div>
            </div>

            <!-- List Siswa -->
            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-6 gap-4" id="student-grid">
                <!-- Data siswa akan di-render menggunakan JavaScript -->
            </div>
        </section>

        <!-- Section Galeri Foto (Diperbarui) -->
        <section id="galeri" class="scroll-mt-20">
            <div class="flex items-center space-x-3 mb-6">
                <div class="p-3 bg-pink-100 text-pink-600 rounded-xl"><i class="fa-solid fa-images text-2xl"></i></div>
                <div>
                    <h2 class="text-2xl font-bold">Galeri Foto</h2>
                    <p class="text-slate-500 text-sm">Dokumentasi momen seru kegiatan sekolah & MATSAMA TA 2025/2026</p>
                </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">
                <!-- Foto 1 -->
                <div class="group relative overflow-hidden rounded-2xl shadow-md bg-slate-200 aspect-square flex flex-col border border-slate-100">
                    <img src="1001472914.jpg" alt="Suasana Kelas Pembukaan MATSAMA" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/20 to-transparent opacity-90 group-hover:opacity-100 transition p-4 flex flex-col justify-end">
                        <span class="text-amber-300 text-xs font-semibold mb-1"><i class="fa-regular fa-calendar-check mr-1"></i> 14 Juli 2025</span>
                        <h4 class="text-white font-bold text-sm">Suasana Ruang Kelas</h4>
                        <p class="text-slate-200 text-xs mt-1">Pembukaan MATSAMA TA 2025/2026 MTs. DDI Kel. Baru</p>
                    </div>
                </div>

                <!-- Foto 2 -->
                <div class="group relative overflow-hidden rounded-2xl shadow-md bg-slate-200 aspect-square flex flex-col border border-slate-100">
                    <img src="1001472912.jpg" alt="Foto Bersama Siswa Putra & Dewan Guru" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/20 to-transparent opacity-90 group-hover:opacity-100 transition p-4 flex flex-col justify-end">
                        <span class="text-amber-300 text-xs font-semibold mb-1"><i class="fa-regular fa-calendar-check mr-1"></i> 14 Juli 2025</span>
                        <h4 class="text-white font-bold text-sm">Foto Bersama Siswa Putra</h4>
                        <p class="text-slate-200 text-xs mt-1">Siswa Putra & Dewan Guru pada Pembukaan MATSAMA</p>
                    </div>
                </div>

                <!-- Foto 3 -->
                <div class="group relative overflow-hidden rounded-2xl shadow-md bg-slate-200 aspect-square flex flex-col border border-slate-100">
                    <img src="1001472910.jpg" alt="Foto Bersama Siswa Putri & Dewan Guru" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent opacity-90 group-hover:opacity-100 transition p-4 flex flex-col justify-end">
                        <span class="text-amber-300 text-xs font-semibold mb-1"><i class="fa-regular fa-calendar-check mr-1"></i> 14 Juli 2025</span>
                        <h4 class="text-white font-bold text-sm">Foto Bersama Siswa Putri</h4>
                        <p class="text-slate-200 text-xs mt-1">Siswa Putri & Dewan Guru pada Pembukaan MATSAMA</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section Transparansi Uang Kas -->
        <section id="keuangan" class="scroll-mt-20">
            <div class="flex items-center space-x-3 mb-6">
                <div class="p-3 bg-emerald-100 text-emerald-600 rounded-xl"><i class="fa-solid fa-wallet text-2xl"></i></div>
                <div>
                    <h2 class="text-2xl font-bold">Laporan Kas Kelas</h2>
                    <p class="text-slate-500 text-sm">Transparansi pemasukan dan pengeluaran uang kas</p>
                </div>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-6">
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-100 text-center">
                    <span class="text-slate-500 text-xs font-semibold uppercase">Total Kas Terkumpul</span>
                    <p class="text-2xl font-bold text-indigo-600 mt-2">Rp 1.250.000</p>
                </div>
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-100 text-center">
                    <span class="text-slate-500 text-xs font-semibold uppercase">Total Pengeluaran</span>
                    <p class="text-2xl font-bold text-red-500 mt-2">Rp 450.000</p>
                </div>
                <div class="bg-white p-6 rounded-2xl shadow-sm border border-slate-100 text-center">
                    <span class="text-slate-500 text-xs font-semibold uppercase">Sisa Saldo Kas</span>
                    <p class="text-2xl font-bold text-emerald-500 mt-2">Rp 800.000</p>
                </div>
            </div>
        </section>

        <!-- Section Pesan & Kesan (Buku Tamu Interaktif) -->
        <section class="bg-indigo-50 p-8 rounded-3xl border border-indigo-100">
            <h2 class="text-2xl font-bold mb-2">Buku Pesan Kelas</h2>
            <p class="text-slate-600 text-sm mb-6">Tinggalkan pesan, saran, atau kesanmu untuk kelas ini!</p>

            <form id="message-form" onsubmit="submitMessage(event)" class="space-y-4 mb-8">
                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                    <input type="text" id="sender-name" placeholder="Nama Kamu" required class="w-full p-3 rounded-xl border border-slate-200 focus:outline-none focus:ring-2 focus:ring-indigo-500 text-sm">
                    <select id="sender-role" class="w-full p-3 rounded-xl border border-slate-200 focus:outline-none focus:ring-2 focus:ring-indigo-500 text-sm">
                        <option value="Siswa">Siswa</option>
                        <option value="Alumni">Alumni</option>
                        <option value="Guru">Guru</option>
                    </select>
                </div>
                <textarea id="sender-message" rows="3" placeholder="Tuliskan pesanmu di sini..." required class="w-full p-3 rounded-xl border border-slate-200 focus:outline-none focus:ring-2 focus:ring-indigo-500 text-sm"></textarea>
                <button type="submit" class="bg-indigo-600 text-white font-semibold px-6 py-2.5 rounded-xl hover:bg-indigo-700 transition text-sm">Kirim Pesan</button>
            </form>

            <!-- List Pesan -->
            <div id="messages-container" class="space-y-3">
                <div class="bg-white p-4 rounded-2xl shadow-sm">
                    <div class="flex justify-between items-center mb-1">
                        <span class="font-bold text-sm">Reza <span class="text-xs font-normal text-slate-400">(Siswa)</span></span>
                        <span class="text-xs text-slate-400">10 Menit yang lalu</span>
                    </div>
                    <p class="text-slate-600 text-sm">Semoga Kelas 8B tetap solid dan terus kompak!</p>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-slate-900 text-slate-400 py-8 text-center text-sm border-t border-slate-800">
        <p>© 2026 Kelas 8B MTs. DDI Kel. Baru - Dibuat dengan ❤️ oleh Pengurus Kelas.</p>
    </footer>

    <!-- Script Logic -->
    <script>
        // Data Jadwal Pelajaran
        const scheduleData = {
            senin: [
                { time: "07:00 - 08:00", subject: "Upacara Bendera", room: "Lap. Utama" },
                { time: "08:00 - 09:30", subject: "Matematika", room: "R. 8B" },
                { time: "09:30 - 10:00", subject: "Istirahat", room: "-" },
                { time: "10:00 - 12:00", subject: "IPA", room: "Lab IPA" }
            ],
            selasa: [
                { time: "07:15 - 09:15", subject: "IPS", room: "R. 8B" },
                { time: "09:15 - 09:45", subject: "Istirahat", room: "-" },
                { time: "09:45 - 11:45", subject: "Bahasa Indonesia", room: "R. 8B" }
            ],
            rabu: [
                { time: "07:15 - 09:15", subject: "Bahasa Inggris", room: "R. 8B" },
                { time: "09:15 - 09:45", subject: "Istirahat", room: "-" },
                { time: "09:45 - 11:45", subject: "Seni Budaya", room: "R. 8B" }
            ],
            kamis: [
                { time: "07:15 - 09:15", subject: "Prakarya", room: "R. 8B" },
                { time: "09:15 - 09:45", subject: "Istirahat", room: "-" },
                { time: "09:45 - 11:45", subject: "PPKn", room: "R. 8B" }
            ],
            jumat: [
                { time: "07:15 - 08:30", subject: "Pendidikan Agama", room: "R. 8B" },
                { time: "08:30 - 09:30", subject: "PJOK", room: "Lap. Olahraga" },
                { time: "09:30 - 10:00", subject: "Istirahat", room: "-" }
            ]
        };

        // Data Siswa
        const students = [
            "Virgiawan", 
            "Reza", 
            "Nur Alya", 
            "Azizah Fitriani", 
            "Hajra Anggaraini", 
            "Rizky Kurnia", 
            "Hafiza Arman", 
            "Sri Ningsih", 
            "Wisda Yanti", 
            "Zahira", 
            "Sakina", 
            "Siti Patima", 
            "Aniska", 
            "Arif Idris", 
            "Aiman Jo", 
            "Faisal", 
            "Fauzi", 
            "Ridwan", 
            "Sofyan", 
            "Bintang", 
            "Akram"
        ];

        // Switch Day Schedule
        function switchDay(day) {
            const tabs = document.querySelectorAll('.day-tab');
            tabs.forEach(tab => {
                if(tab.getAttribute('data-day') === day) {
                    tab.classList.add('bg-indigo-600', 'text-white', 'font-semibold');
                    tab.classList.remove('hover:bg-slate-100', 'text-slate-600');
                } else {
                    tab.classList.remove('bg-indigo-600', 'text-white', 'font-semibold');
                    tab.classList.add('hover:bg-slate-100', 'text-slate-600');
                }
            });

            const container = document.getElementById('schedule-content');
            container.innerHTML = '';

            scheduleData[day].forEach(item => {
                const isBreak = item.subject === "Istirahat";
                container.innerHTML += `
                    <div class="flex items-center justify-between p-3 rounded-xl ${isBreak ? 'bg-amber-50 text-amber-800' : 'bg-slate-50 border border-slate-100'}">
                        <div class="flex items-center space-x-3">
                            <span class="text-xs font-semibold px-2 py-1 rounded ${isBreak ? 'bg-amber-200' : 'bg-indigo-100 text-indigo-600'}">${item.time}</span>
                            <span class="font-medium text-sm">${item.subject}</span>
                        </div>
                        <span class="text-xs text-slate-400">${item.room}</span>
                    </div>
                `;
            });
        }

        // Render Siswa
        function renderStudents(list) {
            const grid = document.getElementById('student-grid');
            grid.innerHTML = '';
            list.forEach((name) => {
                // Mencari nomor absen asli dari array students
                const originalIndex = students.indexOf(name) + 1;
                grid.innerHTML += `
                    <div class="bg-white p-3 rounded-xl border border-slate-100 text-center shadow-sm hover:shadow transition">
                        <div class="w-12 h-12 bg-indigo-50 text-indigo-600 rounded-full flex items-center justify-center font-bold mx-auto mb-2 text-sm">
                            ${name.charAt(0)}
                        </div>
                        <h4 class="font-medium text-xs truncate" title="${name}">${name}</h4>
                        <span class="text-[10px] text-slate-400">Absen ${originalIndex}</span>
                    </div>
                `;
            });
        }

        // Filter Siswa (Search)
        function filterStudents() {
            const query = document.getElementById('search-student').value.toLowerCase();
            const filtered = students.filter(name => name.toLowerCase().includes(query));
            renderStudents(filtered);
        }

        // Submit Pesan Baru
        function submitMessage(e) {
            e.preventDefault();
            const name = document.getElementById('sender-name').value;
            const role = document.getElementById('sender-role').value;
            const msg = document.getElementById('sender-message').value;

            const container = document.getElementById('messages-container');
            const newMessage = document.createElement('div');
            newMessage.className = "bg-white p-4 rounded-2xl shadow-sm border border-indigo-100 animate-fade-in";
            newMessage.innerHTML = `
                <div class="flex justify-between items-center mb-1">
                    <span class="font-bold text-sm">${name} <span class="text-xs font-normal text-slate-400">(${role})</span></span>
                    <span class="text-xs text-slate-400">Baru saja</span>
                </div>
                <p class="text-slate-600 text-sm">${msg}</p>
            `;
            container.prepend(newMessage);

            // Reset Form
            document.getElementById('message-form').reset();
        }

        // Mobile Menu Toggle
        document.getElementById('mobile-menu-btn').addEventListener('click', () => {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });

        // Initialize Default View
        window.onload = () => {
            switchDay('senin');
            renderStudents(students);
        };
    </script>
</body>
</html>

