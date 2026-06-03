<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Resmi Sekolah</title>
    <!-- Menggunakan Tailwind CSS untuk tampilan modern -->
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
</head>
<body class="bg-gray-50 font-sans text-gray-800">

    <!-- 1. NAVIGATION BAR -->
    <nav class="bg-emerald-700 text-white shadow-md sticky top-0 z-50">
        <div class="max-w-6xl mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <span class="text-xl font-bold tracking-wider">SD K SANTA MARIA</span>
            </div>
            <div class="hidden md:flex space-x-6 font-medium">
                <a href="#beranda" class="hover:text-emerald-200 transition">Beranda</a>
                <a href="#profil" class="hover:text-emerald-200 transition">Profil</a>
                <a href="#galeri" class="hover:text-emerald-200 transition">Galeri</a>
                <a href="ppdb.html" class="hover:text-emerald-200 transition">PPDB</a>
                <a href="login.html" class="bg-white text-emerald-700 px-4 py-1.5 rounded-full font-semibold hover:bg-emerald-100 transition shadow">Login Sistem</a>
            </div>
        </div>
    </nav>

    <!-- 2. HERO SECTION / BANNER UTAMA -->
    <header id="beranda" class="bg-gradient-to-r from-emerald-600 to-teal-700 text-white py-20 px-4 text-center">
        <div class="max-w-4xl mx-auto">
            <h1 class="text-4xl md:text-5xl font-extrabold mb-4">Selamat Datang di Website Resmi Sekolah</h1>
            <p class="text-lg md:text-xl text-emerald-100 mb-8">Membentuk Generasi Cerdas, Berkarakter, dan Berbudaya.</p>
            <a href="ppdb.html" class="bg-yellow-400 text-emerald-900 px-8 py-3 rounded-lg font-bold text-lg hover:bg-yellow-300 transition shadow-lg">Daftar PPDB Online 2026</a>
        </div>
    </header>

    <!-- 3. SAMBUTAN KEPALA SEKOLAH & PROFIL (FITUR 1) -->
    <section id="profil" class="max-w-6xl mx-auto px-4 py-16">
        <div class="grid md:grid-cols-3 gap-12 items-center">
            <div class="md:col-span-1 text-center bg-white p-6 rounded-2xl shadow-sm border border-gray-100">
                <div class="w-40 h-40 bg-gray-300 rounded-full mx-auto mb-4 border-4 border-emerald-500 overflow-hidden flex items-center justify-center text-gray-500">[ Foto Kepsek ]</div>
                <h3 class="text-xl font-bold">MG. Ika Ayuningsih, S.P., S.Pd.</h3>
                <p class="text-emerald-600 font-medium text-sm">Kepala Sekolah</p>
            </div>
            <div class="md:col-span-2">
                <h2 class="text-3xl font-bold text-emerald-800 mb-4">Sambutan Kepala Sekolah</h2>
                <p class="text-gray-600 leading-relaxed mb-4">
                    Puji syukur kami panjatkan kepada Tuhan Yang Maha Esa atas terwujudnya website resmi sekolah ini. Di era digital saat ini, website ini hadir sebagai jembatan informasi dan komunikasi antara pihak sekolah, guru, siswa, orang tua, masyarakat, dan instansi terkait secara transparan dan akurat.
                </p>
                <p class="text-gray-600 leading-relaxed">
                    Kami berkomitmen untuk terus meningkatkan mutu pendidikan, layanan administrasi, dan transparansi pelaporan demi masa depan putra-putri kita yang lebih gemilang.
                </p>
            </div>
        </div>
    </section>

    <!-- 4. GALERI KEGIATAN (FITUR 2) -->
    <section id="galeri" class="bg-white py-16 border-t border-b border-gray-100">
        <div class="max-w-6xl mx-auto px-4">
            <h2 class="text-3xl font-bold text-center text-emerald-800 mb-10">Galeri Kegiatan Sekolah</h2>
            <div class="grid sm:grid-cols-2 md:grid-cols-3 gap-6">
                <!-- Foto 1 -->
                <div class="bg-gray-50 rounded-xl overflow-hidden shadow-sm border border-gray-200">
                    <div class="h-48 bg-emerald-100 flex items-center justify-center text-emerald-700 font-medium">[ Foto Kegiatan 1 ]</div>
                    <div class="p-4"><p class="font-semibold">Upacara Hari Kemerdekaan</p></div>
                </div>
                <!-- Foto 2 -->
                <div class="bg-gray-50 rounded-xl overflow-hidden shadow-sm border border-gray-200">
                    <div class="h-48 bg-emerald-100 flex items-center justify-center text-emerald-700 font-medium">[ Foto Kegiatan 2 ]</div>
                    <div class="p-4"><p class="font-semibold">Kegiatan Ekstrakurikuler Pramuka</p></div>
                </div>
                <!-- Foto 3 -->
                <div class="bg-gray-50 rounded-xl overflow-hidden shadow-sm border border-gray-200">
                    <div class="h-48 bg-emerald-100 flex items-center justify-center text-emerald-700 font-medium">[ Foto Kegiatan 3 ]</div>
                    <div class="p-4"><p class="font-semibold">Rapat Parenting Wali Murid</p></div>
                </div>
            </div>
        </div>
    </section>

    <!-- 5. FOOTER -->
    <footer class="bg-gray-900 text-gray-400 py-8 px-4 text-center border-t border-gray-800">
        <p>&copy; 2026 Website Resmi Sekolah. All Rights Reserved.</p>
    </footer>

</body>
</html>
