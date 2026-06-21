<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EarnCryptoLive - Premium Earning Hub</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Hind+Siliguri:wght@400;600;700&display=swap');
        body { font-family: 'Hind Siliguri', sans-serif; }
    </style>
</head>
<body class="bg-[#0f172a] text-slate-200 antialiased">

    <!-- Top Bar Notice -->
    <div class="bg-gradient-to-r from-amber-500 to-orange-600 text-slate-950 py-2 px-4 text-center text-xs md:text-sm font-bold tracking-wide">
        <i class="fa-solid fa-circle-check animate-pulse mr-1"></i> সতর্কবার্তা: আমাদের ভেরিফাইড লিংক ছাড়া অন্য কোথাও অ্যাকাউন্টের তথ্য দেবেন না।
    </div>

    <!-- Navigation -->
    <header class="bg-[#1e293b]/80 backdrop-blur-md border-b border-slate-800 sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <div class="flex items-center gap-3">
                <div class="bg-amber-500 text-slate-950 p-2 rounded-xl font-black text-xl shadow-lg shadow-amber-500/20">
                    <i class="fa-solid fa-bolt"></i>
                </div>
                <div>
                    <span class="text-xl font-black text-white tracking-tight">EarnCrypto<span class="text-amber-500">Live</span></span>
                    <p class="text-[10px] text-slate-400 -mt-1 tracking-widest uppercase font-bold">Your Trusted Earning Guide</p>
                </div>
            </div>
            <a href="#offers" class="bg-gradient-to-r from-amber-500 to-orange-500 hover:from-amber-400 hover:to-orange-400 text-slate-950 px-5 py-2.5 rounded-xl font-bold shadow-lg shadow-orange-500/20 transition text-sm flex items-center gap-2">
                আজকের অফার <i class="fa-solid fa-arrow-trend-up"></i>
            </a>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative overflow-hidden py-16 md:py-24 text-center px-4 border-b border-slate-800 bg-[radial-gradient(ellipse_at_top,_var(--tw-gradient-stops))] from-slate-800 via-[#0f172a] to-[#0f172a]">
        <div class="container mx-auto max-w-3xl">
            <span class="inline-flex items-center gap-1.5 py-1.5 px-3 rounded-full text-xs font-medium bg-amber-500/10 text-amber-500 mb-4 border border-amber-500/20">
                <span class="w-1.5 h-1.5 rounded-full bg-amber-500 animate-ping"></span> ১০০% ভেরিফাইড আর্নিং প্ল্যাটফর্ম
            </span>
            <h2 class="text-3xl md:text-6xl font-black text-white leading-tight mb-6">স্মার্টফোনেই শুরু হোক আপনার <span class="text-transparent bg-clip-text bg-gradient-to-r from-amber-400 to-orange-500">ক্রিপ্টো ইনকাম</span></h2>
            <p class="text-slate-400 text-sm md:text-lg max-w-xl mx-auto mb-8 leading-relaxed">কোনো ইনভেস্টমেন্ট ছাড়াই প্রতিদিন ফ্রি বিটকয়েন, লাইটকয়েন এবং এয়ারড্রপ থেকে ইনকাম করুন। লাইভ রেট দেখে সঠিক সময়ে উইথড্র নিন।</p>
        </div>
    </section>

    <!-- Live Crypto Tracker -->
    <section class="container mx-auto px-4 -mt-8 relative z-10">
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
            <!-- BTC -->
            <div class="bg-[#1e293b] p-5 rounded-2xl border border-slate-800/80 shadow-xl flex justify-between items-center transition hover:border-orange-500/40">
                <div>
                    <span class="text-xs font-bold text-slate-400 uppercase tracking-wider">Bitcoin Price</span>
                    <p id="btc-price" class="text-2xl font-bold text-white mt-1">로드 হচ্ছে...</p>
                </div>
                <div class="w-12 h-12 rounded-xl bg-orange-500/10 flex items-center justify-center text-orange-500 text-2xl"><i class="fa-brands fa-bitcoin"></i></div>
            </div>
            <!-- LTC -->
            <div class="bg-[#1e293b] p-5 rounded-2xl border border-slate-800/80 shadow-xl flex justify-between items-center transition hover:border-blue-500/40">
                <div>
                    <span class="text-xs font-bold text-slate-400 uppercase tracking-wider">Litecoin Price</span>
                    <p id="ltc-price" class="text-2xl font-bold text-white mt-1">로드 হচ্ছে...</p>
                </div>
                <div class="w-12 h-12 rounded-xl bg-blue-500/10 flex items-center justify-center text-blue-400 text-2xl"><i class="fa-solid fa-coins"></i></div>
            </div>
            <!-- ETH -->
            <div class="bg-[#1e293b] p-5 rounded-2xl border border-slate-800/80 shadow-xl flex justify-between items-center transition hover:border-purple-500/40">
                <div>
                    <span class="text-xs font-bold text-slate-400 uppercase tracking-wider">Ethereum Price</span>
                    <p id="eth-price" class="text-2xl font-bold text-white mt-1">로드 হচ্ছে...</p>
                </div>
                <div class="w-12 h-12 rounded-xl bg-purple-500/10 flex items-center justify-center text-purple-400 text-2xl"><i class="fa-brands fa-ethereum"></i></div>
            </div>
        </div>
    </section>

    <!-- Main Offers Grid -->
    <section id="offers" class="container mx-auto px-4 py-16">
        <div class="flex items-center justify-between mb-8">
            <div>
                <h3 class="text-2xl font-bold text-white">সক্রিয় ইনকাম লিংকসমূহ</h3>
                <p class="text-sm text-slate-400">নিচের যেকোনো একটি প্রজেক্ট বেছে নিয়ে কাজ শুরু করুন</p>
            </div>
            <span class="text-xs text-amber-500 font-bold bg-amber-500/10 py-1 px-3 rounded-md border border-amber-500/20">Total: 02 Active</span>
        </div>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
            
            <!-- Item 1 -->
            <div class="bg-[#1e293b] rounded-2xl border border-slate-800 overflow-hidden flex flex-col justify-between group hover:border-slate-700 transition">
                <div class="p-6">
                    <div class="flex justify-between items-start gap-2">
                        <span class="bg-emerald-500/10 text-emerald-400 text-[10px] px-2.5 py-1 rounded-md font-bold uppercase tracking-wider border border-emerald-500/20">Instant Withdraw</span>
                    </div>
                    <h4 class="text-xl font-bold text-white mt-4 group-hover:text-amber-400 transition">ফ্রি লাইটকয়েন মাইনিং বোট ও সাইট</h4>
                    <p class="text-slate-400 text-sm mt-2 leading-relaxed">সম্পূর্ণ ফ্রিতে প্রতি ১ ঘন্টা পর পর ক্লেইম করুন। পেমেন্ট সরাসরি ট্রাস্ট ওয়ালেট বা বাইন্যান্স অ্যাকাউন্টে নিতে পারবেন। কোনো রেফার লাগবে না।</p>
                </div>
                <div class="p-6 pt-0">
                    <!-- EDITABLE LINK -->
                    <a href="https://your-link-1.com" target="_blank" class="block text-center bg-slate-800 hover:bg-amber-500 hover:text-slate-950 text-white font-bold py-3 rounded-xl transition-all duration-300 text-sm">
                        জয়েন করুন <i class="fa-solid fa-arrow-up-right-from-square ml-1 text-xs"></i>
                    </a>
                </div>
            </div>

            <!-- Item 2 -->
            <div class="bg-[#1e293b] rounded-2xl border border-slate-800 overflow-hidden flex flex-col justify-between group hover:border-slate-700 transition">
                <div class="p-6">
                    <div class="flex justify-between items-start gap-2">
                        <span class="bg-amber-500/10 text-amber-400 text-[10px] px-2.5 py-1 rounded-md font-bold uppercase tracking-wider border border-amber-500/20">New Airdrop</span>
                    </div>
                    <h4 class="text-xl font-bold text-white mt-4 group-hover:text-amber-400 transition">টেলিগ্রাম নতুন ধামাকা মাইনিং প্রজেক্ট</h4>
                    <p class="text-slate-400 text-sm mt-2 leading-relaxed">লিংকে ক্লিক করে বট চালু করুন এবং টোকেন আর্ন করা শুরু করুন। খুব দ্রুত এই টোকেনটি বড় বড় এক্সচেঞ্জারে লিস্ট হতে যাচ্ছে।</p>
                </div>
                <div class="p-6 pt-0">
                    <!-- EDITABLE LINK -->
                    <a href="https://your-link-2.com" target="_blank" class="block text-center bg-slate-800 hover:bg-amber-500 hover:text-slate-950 text-white font-bold py-3 rounded-xl transition-all duration-300 text-sm">
                        জয়েন করুন <i class="fa-solid fa-arrow-up-right-from-square ml-1 text-xs"></i>
                    </a>
                </div>
            </div>

        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-[#0b0f19] border-t border-slate-900 py-8 text-center text-xs text-slate-500">
        <p class="mb-2">&copy; 2026 EarnCryptoLive. All Rights Reserved.</p>
        <p>Powered by Real-time Crypto API</p>
    </footer>

    <!-- JavaScript for API -->
    <script>
        async function fetchCryptoPrices() {
            try {
                const response = await fetch('https://api.coingecko.com/api/v3/simple/price?ids=bitcoin,litecoin,ethereum&vs_currencies=usd');
                const data = await response.json();
                
                document.getElementById('btc-price').innerText = $${data.bitcoin.usd.toLocaleString()};
                document.getElementById('ltc-price').innerText = $${data.litecoin.usd.toLocaleString()};
                document.getElementById('eth-price').innerText = $${data.ethereum.usd.toLocaleString()};
            } catch (error) {
                console.log("Error fetching prices:", error);
                document.getElementById('btc-price').innerText = "Network Error";
                document.getElementById('ltc-price').innerText = "Network Error";
                document.getElementById('eth-price').innerText = "Network Error";
            }
        }
        fetchCryptoPrices();
        setInterval(fetchCryptoPrices, 40000);
    </script>
</body>
</html>
