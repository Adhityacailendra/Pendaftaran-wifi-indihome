<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registrasi IndiHome</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet"/>
</head>
<body class="bg-gray-100 font-roboto">
    <div class="max-w-md mx-auto p-4">
        
        <!-- Logo IndiHome -->
        <div class="flex justify-center mb-4">
            <img src="Logo_indiHome.png" alt="Logo IndiHome" class="w-32 h-auto">
        </div>

        <h1 class="text-center text-2xl font-bold text-gray-800 mb-4">
            Kirim Link Registrasi Customer
        </h1>

        <div class="bg-blue-900 text-white p-4 rounded-lg mb-4">
            <!-- Logo dalam informasi layanan -->
            <div class="flex justify-center mb-2">
                <img src="Logo_indiHome.png" alt="Logo IndiHome" class="w-24 h-auto">
            </div>
            <p>Formulir pendaftaran & verifikasi pelanggan, lengkapi persyaratan berikut:</p>
            <ul class="list-disc list-inside ml-4">
                <li>Foto KTP</li>
                <li>Foto Rumah</li>
            </ul>
            <p class="mt-2">Untuk layanan internet IndiHome di wilayah Baturaja dan sekitarnya, mohon hubungi petugas <strong>082281512603</strong> untuk konfirmasi pemasangan.</p>
        </div>

        <form>
            <div class="mb-4">
                <label class="block text-gray-700 mb-2" for="nama">Nama Pelanggan</label>
                <input class="w-full p-2 border border-gray-300 rounded" id="nama" placeholder="Nama lengkap pelanggan" type="text"/>
            </div>
            <div class="mb-4">
                <label class="block text-gray-700 mb-2" for="email">Email Pelanggan</label>
                <input class="w-full p-2 border border-gray-300 rounded" id="email" placeholder="Alamat email pelanggan" type="email"/>
            </div>
            <div class="mb-4">
                <label class="block text-gray-700 mb-2" for="phone">No. Handphone</label>
                <input class="w-full p-2 border border-gray-300 rounded" id="phone" placeholder="No. handphone pelanggan" type="tel"/>
            </div>

            <!-- Informasi IndiHome -->
            <div class="text-center mb-4">
                <div class="bg-red-500 text-white py-2 px-4 rounded-full inline-block">
                    IndiHome by Telkomsel
                </div>
            </div>

            <button class="w-full bg-blue-900 text-white py-2 rounded-full hover:bg-blue-800">
                Kirim Link Verifikasi
            </button>
        </form>
    </div>
</body>
</html>