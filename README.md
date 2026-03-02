# Ramdev-Enterprises
"Shop &amp; Repair - Mobile phones and repair services"
<!DOCTYPE html>
<html lang="en">
<head>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <title>Ramdev Enterprises | Shop & Repair</title>
</head>
<body class="bg-gray-100 font-sans">

    <nav class="bg-slate-900 text-white p-3 flex items-center gap-4 sticky top-0 z-50">
        <div class="text-2xl font-bold px-4 text-orange-400">Ramdev Enterprises</div>
        <div class="flex-grow flex bg-white rounded-md overflow-hidden">
            <input type="text" placeholder="Search S25 Ultra, iPhone 17, or Repair Services..." class="w-full p-2 text-black outline-none px-4">
            <button class="bg-orange-400 px-5 text-slate-900 hover:bg-orange-500">
                <i class="fa-solid fa-magnifying-glass"></i>
            </button>
        </div>
        <div class="flex gap-6 px-4 text-sm">
            <div class="cursor-pointer">Returns<br><span class="font-bold text-base">& Orders</span></div>
            <div class="cursor-pointer font-bold text-base mt-2"><i class="fa-solid fa-cart-shopping mr-1"></i> Cart</div>
        </div>
    </nav>

    <div class="bg-slate-800 text-white text-sm p-2 flex gap-6 px-8 shadow-md">
        <a href="#phones" class="hover:text-orange-300">New Mobile Phones</a>
        <a href="#services" class="hover:text-orange-300">Repair Services</a>
        <a href="#" class="hover:text-orange-300">Accessories</a>
        <a href="#" class="hover:text-orange-300">Used Devices</a>
    </div>

    <div class="bg-gray-200 h-80 flex items-center justify-center overflow-hidden relative">
        <div class="absolute text-center">
            <h1 class="text-5xl font-extrabold text-slate-800">THE 2026 FLAGSHIP COLLECTION</h1>
            <p class="text-xl text-slate-600 mt-2">iPhone 17 Pro & Galaxy S25 Ultra - In Stock Now</p>
        </div>
    </div>

    <main class="max-w-7xl mx-auto -mt-16 relative z-10 px-4">
        <h2 id="phones" class="text-2xl font-bold mb-4">Latest Launches (2025-2026)</h2>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-12">
            <div class="bg-white p-6 shadow-md rounded">
                <img src="https://via.placeholder.com/300x300?text=Galaxy+S25+Ultra" class="w-full h-48 object-contain mb-4">
                <h3 class="font-bold text-lg">Samsung Galaxy S25 Ultra</h3>
                <p class="text-sm text-gray-600 mb-4 italic">"The AI Powerhouse with Titanium build."</p>
                <div class="text-2xl font-bold text-red-700">₹1,07,890</div>
                <button class="w-full mt-4 bg-yellow-400 py-2 rounded-full font-semibold hover:bg-yellow-500">Add to Cart</button>
            </div>
            <div class="bg-white p-6 shadow-md rounded">
                <img src="https://via.placeholder.com/300x300?text=iPhone+17+Pro+Max" class="w-full h-48 object-contain mb-4">
                <h3 class="font-bold text-lg">iPhone 17 Pro Max</h3>
                <p class="text-sm text-gray-600 mb-4 italic">"Pro Cameras. Pro Performance. Pro Design."</p>
                <div class="text-2xl font-bold text-red-700">₹1,59,900</div>
                <button class="w-full mt-4 bg-yellow-400 py-2 rounded-full font-semibold hover:bg-yellow-500">Add to Cart</button>
            </div>
             <div class="bg-white p-6 shadow-md rounded">
                <img src="https://via.placeholder.com/300x300?text=Google+Pixel+10+Pro" class="w-full h-48 object-contain mb-4">
                <h3 class="font-bold text-lg">Google Pixel 10 Pro</h3>
                <p class="text-sm text-gray-600 mb-4 italic">"The world's smartest smartphone AI."</p>
                <div class="text-2xl font-bold text-red-700">₹1,24,999</div>
                <button class="w-full mt-4 bg-yellow-400 py-2 rounded-full font-semibold hover:bg-yellow-500">Add to Cart</button>
            </div>
        </div>

        <h2 id="services" class="text-2xl font-bold mb-4">Professional Repair Services</h2>
        <div class="bg-white p-8 shadow-md rounded-lg mb-12 border-l-8 border-orange-500">
            <div class="grid md:grid-cols-2 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4 text-slate-800">Book a Fast Service</h3>
                    <ul class="space-y-4">
                        <li class="flex items-center gap-3"><i class="fa-solid fa-check text-green-600"></i> **Display Replacement:** Grade-A OLED/LCD Panels.</li>
                        <li class="flex items-center gap-3"><i class="fa-solid fa-check text-green-600"></i> **Charging Board:** Fix charging & mic issues.</li>
                        <li class="flex items-center gap-3"><i class="fa-solid fa-check text-green-600"></i> **Battery Replacement:** 100% Original health.</li>
                    </ul>
                </div>
                <div class="bg-gray-50 p-6 rounded border">
                    <h4 class="font-bold mb-2">Request Service Callback</h4>
                    <input type="text" placeholder="Your Phone Model (e.g. iPhone 15)" class="w-full mb-3 p-2 border rounded">
                    <input type="tel" placeholder="Mobile Number" class="w-full mb-3 p-2 border rounded">
                    <button class="w-full bg-slate-900 text-white py-2 rounded hover:bg-slate-700">Get Free Quote</button>
                </div>
            </div>
        </div>
    </main>

</body>
</html>
