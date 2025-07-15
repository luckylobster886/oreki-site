<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Oreki - Like HiAnime | Watch Anime Online Free</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Rubik:wght@400;500;600;700&display=swap');
        
        :root {
            --primary: #e63946;
            --secondary: #0d1b2a;
            --accent: #ff8500;
            --dark: #0a0a0a;
            --light: #f8f9fa;
        }
        
        body {
            font-family: 'Rubik', sans-serif;
            background-color: var(--dark);
            color: white;
            min-height: 100vh;
        }
        
        .strawhat-logo {
            width: 44px;
            height: 44px;
            background-image: url('https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/929551fa-14f3-45b8-9f99-9885122d1812.png');
            background-size: contain;
            background-repeat: no-repeat;
            margin-right: 10px;
            position: relative;
            border-radius: 50%;
            filter: drop-shadow(0 0 6px rgba(255, 133, 0, 0.5));
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        
        .navbar {
            background-color: rgba(13, 27, 42, 0.95);
            backdrop-filter: blur(5px);
            border-bottom: 1px solid rgba(255, 133, 0, 0.2);
        }
        
        .content-card {
            transition: all 0.3s ease;
            background: #141a25;
            border-radius: 6px;
            overflow: hidden;
            border: 1px solid rgba(255,255,255,0.05);
        }
        
        .content-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(230, 57, 70, 0.2);
            border-color: var(--primary);
        }
        
        .search-container {
            background: #141a25;
            border: 1px solid rgba(255, 133, 0, 0.3);
        }
        
        .tab-indicator {
            bottom: -3px;
            height: 3px;
            background: var(--accent);
            transition: all 0.3s ease;
        }
        
        .active-tab {
            color: var(--accent) !important;
        }
        
        .category-tag {
            padding: 3px 8px;
            border-radius: 4px;
            font-size: 11px;
            font-weight: 600;
            text-transform: uppercase;
        }
        
        .anime-tag {
            background-color: rgba(230, 57, 70, 0.15);
            color: #ff6b6b;
        }
        
        .manga-tag {
            background-color: rgba(0, 150, 255, 0.15);
            color: #48dbfb;
        }
        
        .manhwa-tag {
            background-color: rgba(0, 206, 201, 0.15);
            color: #00d2d3;
        }
        
        .novel-tag {
            background-color: rgba(255, 107, 129, 0.15);
            color: #ff6b81;
        }
        
        .blog-tag {
            background-color: rgba(29, 209, 161, 0.15);
            color: #1dd1a1;
        }
        
        .dropdown-menu {
            background: #1c2a3e;
            border: 1px solid rgba(255, 133, 0, 0.2);
        }
        
        .hero-section {
            background: linear-gradient(rgba(10, 10, 10, 0.7), rgba(10, 10, 10, 0.9)), 
                        url('https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/8cdabb18-84f8-4682-b9ec-4cb4d89a1d4d.png') center/cover;
            height: 70vh;
            min-height: 500px;
        }
        
        .trending-badge {
            position: absolute;
            top: 10px;
            right: 10px;
            background: linear-gradient(45deg, #e63946, #ff8500);
            color: white;
            padding: 3px 8px;
            border-radius: 3px;
            font-size: 10px;
            font-weight: 700;
        }
        
        .episode-badge {
            position: absolute;
            bottom: 10px;
            left: 10px;
            background: rgba(13, 27, 42, 0.9);
            color: var(--accent);
            padding: 3px 8px;
            border-radius: 3px;
            font-size: 11px;
        }
        
        .slider-container {
            scrollbar-width: none;
        }
        
        .slider-container::-webkit-scrollbar {
            display: none;
        }
    </style>
</head>
<body>
    <!-- HiAnime-style Navbar -->
    <header class="navbar fixed w-full top-0 z-50 shadow-lg">
        <nav class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center">
                <div class="strawhat-logo" title="Oreki Straw Hat Logo"></div>
                <h1 class="text-2xl font-bold text-white">Oreki</h1>
            </div>
            
            <div class="hidden lg:flex items-center space-x-6">
                <a href="#" class="text-gray-300 hover:text-white transition">Home</a>
                <div class="dropdown relative">
                    <button class="text-gray-300 hover:text-white transition flex items-center">
                        Browse <i class="fas fa-chevron-down ml-1 text-xs"></i>
                    </button>
                    <div class="dropdown-menu absolute hidden left-0 mt-2 w-48 rounded-md shadow-lg z-50 py-1">
                        <a href="#" class="block px-4 py-2 text-sm hover:bg-gray-700 text-gray-300">
                            <span class="anime-tag mr-2">Anime</span> Series
                        </a>
                        <a href="#" class="block px-4 py-2 text-sm hover:bg-gray-700 text-gray-300">
                            <span class="manga-tag mr-2">Manga</span> Library
                        </a>
                        <a href="#" class="block px-4 py-2 text-sm hover:bg-gray-700 text-gray-300">
                            <span class="manhwa-tag mr-2">Manhwa</span> Collection
                        </a>
                        <a href="#" class="block px-4 py-2 text-sm hover:bg-gray-700 text-gray-300">
                            <span class="novel-tag mr-2">Novels</span> Archive
                        </a>
                    </div>
                </div>
                <a href="#" class="text-gray-300 hover:text-white transition">Popular</a>
                <a href="#" class="text-gray-300 hover:text-white transition active-tab">New Releases</a>
                <a href="#" class="text-gray-300 hover:text-white transition">Blog</a>
            </div>
            
            <div class="flex items-center space-x-4">
                <div class="relative hidden lg:block">
                    <i class="fas fa-search absolute left-3 top-1/2 transform -translate-y-1/2 text-gray-400"></i>
                    <input type="text" placeholder="Search..." class="bg-gray-800 border border-gray-700 rounded-full py-2 pl-10 pr-4 text-sm focus:outline-none focus:border-orange-500 w-48">
                </div>
                <a href="#" class="bg-orange-500 hover:bg-orange-600 text-white px-4 py-2 rounded-full text-sm font-medium transition">
                    <i class="fas fa-sign-in-alt mr-2"></i> Login
                </a>
                <button class="lg:hidden text-gray-300">
                    <i class="fas fa-bars text-xl"></i>
                </button>
            </div>
        </nav>
    </header>

    <!-- HiAnime-style Hero Section -->
    <section class="hero-section flex items-center justify-center pt-16">
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold mb-6 text-white"><span class="text-orange-500">Oreki</span> - Unlimited Anime & Manga</h1>
            <p class="text-lg md:text-xl text-gray-300 mb-8 max-w-3xl mx-auto">HD Streaming • Latest Episodes • No Ads • Free Downloads</p>
            
            <!-- Enhanced HiAnime-style Search Bar -->
            <div class="max-w-3xl mx-auto bg-gray-900 rounded-lg p-1 shadow-2xl border-2 border-orange-500/30 flex">
                <input type="text" placeholder="Find anime, manga, novels..." class="flex-grow bg-transparent border-none text-white px-4 py-3 focus:outline-none placeholder-gray-400">
                <select class="bg-gray-800 text-white border-l border-gray-700 px-3 focus:outline-none text-sm">
                    <option value="all">All</option>
                    <option value="anime">Anime</option>
                    <option value="manga">Manga</option>
                    <option value="manhwa">Manhwa</option>
                    <option value="novel">Novels</option>
                    <option value="blog">Blogs</option>
                </select>
                <button class="bg-gradient-to-r from-orange-500 to-red-500 hover:from-orange-600 hover:to-red-600 text-white px-6 py-3 rounded-r-lg transition font-medium flex items-center">
                    <i class="fas fa-search mr-2"></i> Search
                </button>
            </div>
            
            <div class="mt-8 flex flex-wrap justify-center gap-3">
                <span class="text-xs bg-orange-500/10 text-orange-400 px-3 py-1 rounded-full border border-orange-500/20">
                    <i class="fas fa-bolt mr-1"></i> TRENDING
                </span>
                <span class="text-xs bg-blue-500/10 text-blue-400 px-3 py-1 rounded-full border border-blue-500/20">
                    <i class="fas fa-tv mr-1"></i> SUBBED
                </span>
                <span class="text-xs bg-green-500/10 text-green-400 px-3 py-1 rounded-full border border-green-500/20">
                    <i class="fas fa-ad mr-1"></i> NO ADS
                </span>
                <span class="text-xs bg-purple-500/10 text-purple-400 px-3 py-1 rounded-full border border-purple-500/20">
                    <i class="fas fa-robot mr-1"></i> AI RECOMMEND
                </span>
            </div>
        </div>
    </section>

    <!-- Main Content -->
    <main class="container mx-auto px-4 py-8 bg-gray-900">
        <!-- Trending Now Section -->
        <section class="mb-12">
            <div class="flex justify-between items-center mb-6 border-b border-gray-700 pb-3">
                <h2 class="text-2xl font-bold text-white flex items-center">
                    <i class="fas fa-fire text-orange-500 mr-3 animate-pulse"></i> 
                    <span class="bg-gradient-to-r from-orange-500 to-red-500 bg-clip-text text-transparent">
                        Popular This Week
                    </span>
                </h2>
                <a href="#" class="text-sm text-gray-400 hover:text-orange-500 transition flex items-center">
                    View All <i class="fas fa-chevron-right ml-1 text-xs"></i>
                </a>
            </div>
            
            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-4">
                <!-- Item 1 -->
                <div class="content-card group relative">
                    <div class="trending-badge">TRENDING</div>
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/1cddd3f5-f062-485a-b9aa-e7adcf8eea0e.png" alt="Attack on Titan anime poster showing Eren Yeager in attack stance against cloudy sky" class="w-full h-64 object-cover">
                    <div class="p-3">
                        <h3 class="text-white font-medium mb-1 truncate">Attack on Titan</h3>
                        <div class="flex justify-between items-center text-xs text-gray-400">
                            <span class="anime-tag">ANIME</span>
                            <span><i class="fas fa-star text-yellow-400 mr-1"></i> 9.8</span>
                        </div>
                    </div>
                </div>
                
                <!-- Item 2 -->
                <div class="content-card group relative">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/e7566567-2817-45ef-bdf1-81e8c42ce71c.png" alt="Jujutsu Kaisen anime poster featuring Yuji Itadori with intense red background" class="w-full h-64 object-cover">
                    <div class="episode-badge">EP 24</div>
                    <div class="p-3">
                        <h3 class="text-white font-medium mb-1 truncate">Jujutsu Kaisen</h3>
                        <div class="flex justify-between items-center text-xs text-gray-400">
                            <span class="anime-tag">ANIME</span>
                            <span><i class="fas fa-star text-yellow-400 mr-1"></i> 9.5</span>
                        </div>
                    </div>
                </div>
                
                <!-- Item 3 -->
                <div class="content-card group relative">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/59c37790-e1c1-4b7c-91cb-5cb004b9a294.png" alt="Solo Leveling manhwa cover featuring Sung Jin-Woo with dark fantasy atmosphere" class="w-full h-64 object-cover">
                    <div class="p-3">
                        <h3 class="text-white font-medium mb-1 truncate">Solo Leveling</h3>
                        <div class="flex justify-between items-center text-xs text-gray-400">
                            <span class="manhwa-tag">MANHWA</span>
                            <span><i class="fas fa-star text-yellow-400 mr-1"></i> 9.9</span>
                        </div>
                    </div>
                </div>
                
                <!-- Item 4 -->
                <div class="content-card group relative">
                    <div class="trending-badge">HOT</div>
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/d5625ffd-b25f-40d5-adb0-1666e7f98222.png" alt="Chainsaw Man anime poster with Denji in chainsaw form against chaotic background" class="w-full h-64 object-cover">
                    <div class="p-3">
                        <h3 class="text-white font-medium mb-1 truncate">Chainsaw Man</h3>
                        <div class="flex justify-between items-center text-xs text-gray-400">
                            <span class="anime-tag">ANIME</span>
                            <span><i class="fas fa-star text-yellow-400 mr-1"></i> 9.7</span>
                        </div>
                    </div>
                </div>
                
                <!-- Item 5 -->
                <div class="content-card group relative">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/7b425123-fa37-4a77-8caf-d3d67d7e4e57.png" alt="Berserk manga cover featuring Guts with Dragonslayer sword in dark fantasy setting" class="w-full h-64 object-cover">
                    <div class="p-3">
                        <h3 class="text-white font-medium mb-1 truncate">Berserk</h3>
                        <div class="flex justify-between items-center text-xs text-gray-400">
                            <span class="manga-tag">MANGA</span>
                            <span><i class="fas fa-star text-yellow-400 mr-1"></i> 10.0</span>
                        </div>
                    </div>
                </div>
                
                <!-- Item 6 -->
                <div class="content-card group relative">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/058503e0-38df-4d5d-aaa8-f8e0cea683ae.png" alt="Mushoku Tensei light novel cover featuring Rudeus Greyrat in fantasy landscape" class="w-full h-64 object-cover">
                    <div class="p-3">
                        <h3 class="text-white font-medium mb-1 truncate">Mushoku Tensei</h3>
                        <div class="flex justify-between items-center text-xs text-gray-400">
                            <span class="novel-tag">NOVEL</span>
                            <span><i class="fas fa-star text-yellow-400 mr-1"></i> 9.6</span>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- More Sections would follow here (Recent Releases, Popular Manga, etc.) -->
        <!-- AI Search Section -->
        <section class="mb-12 bg-gray-800 rounded-xl p-6 border border-gray-700">
            <h2 class="text-2xl font-bold text-white mb-4 flex items-center">
                <i class="fas fa-robot text-orange-500 mr-3"></i> AI-Powered Discovery
            </h2>
            <p class="text-gray-300 mb-6">Our advanced AI understands what you like and recommends perfect matches across anime, manga, manhwa and novels.</p>
            
            <div class="grid md:grid-cols-3 gap-6">
                <div class="bg-gray-700 p-4 rounded-lg border-l-4 border-orange-500">
                    <h3 class="text-white font-medium mb-2">Smart Search</h3>
                    <p class="text-gray-300 text-sm">Describe what you're looking for and our AI will find the best matches across all categories.</p>
                </div>
                <div class="bg-gray-700 p-4 rounded-lg border-l-4 border-red-500">
                    <h3 class="text-white font-medium mb-2">Personalized Recs</h3>
                    <p class="text-gray-300 text-sm">Get recommendations tailored to your unique tastes based on your viewing history.</p>
                </div>
                <div class="bg-gray-700 p-4 rounded-lg border-l-4 border-blue-500">
                    <h3 class="text-white font-medium mb-2">Cross-Platform</h3>
                    <p class="text-gray-300 text-sm">Find anime-manga pairs, novel sources, and all related content in one place.</p>
                </div>
            </div>
            
            <button class="mt-6 bg-gradient-to-r from-orange-500 to-red-500 hover:from-orange-600 hover:to-red-600 text-white px-6 py-3 rounded-md font-medium transition">
                Try AI Search Now
            </button>
        </section>
    </main>

    <footer class="bg-gray-900 border-t border-gray-800 py-8">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between">
                <div class="mb-8 md:mb-0">
                    <div class="flex items-center mb-4">
                        <div class="strawhat-logo" title="Oreki Straw Hat Logo"></div>
                        <h2 class="text-xl font-bold text-white">Oreki</h2>
                    </div>
                    <p class="text-gray-400 text-sm max-w-xs">Your premier destination for anime, manga, manhwa and light novels with AI-enhanced discovery.</p>
                </div>
                
                <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
                    <div>
                        <h3 class="text-white font-medium mb-4">Categories</h3>
                        <ul class="space-y-2">
                            <li><a href="#" class="text-gray-400 hover:text-orange-500 transition text-sm">Anime</a></li>
                            <li><a href="#" class="text-gray-400 hover:text-orange-500 transition text-sm">Manga</a></li>
                            <li><a href="#" class="text-gray-400 hover:text-orange-500 transition text-sm">Manhwa</a></li>
                            <li><a href="#" class="text-gray-400 hover:text-orange-500 transition text-sm">Light Novels</a></li>
                        </ul>
                    </div>
                    <div>
                        <h3 class="text-white font-medium mb-4">Legal</h3>
                        <ul class="space-y-2">
                            <li><a href="#" class="text-gray-400 hover:text-orange-500 transition text-sm">Terms of Service</a></li>
                            <li><a href="#" class="text-gray-400 hover:text-orange-500 transition text-sm">Privacy Policy</a></li>
                            <li><a href="#" class="text-gray-400 hover:text-orange-500 transition text-sm">DMCA</a></li>
                            <li><a href="#" class="text-gray-400 hover:text-orange-500 transition text-sm">Contact</a></li>
                        </ul>
                    </div>
                    <div>
                        <h3 class="text-white font-medium mb-4">Community</h3>
                        <ul class="space-y-2">
                            <li><a href="#" class="text-gray-400 hover:text-orange-500 transition text-sm">Discord</a></li>
                            <li><a href="#" class="text-gray-400 hover:text-orange-500 transition text-sm">Forum</a></li>
                            <li><a href="#" class="text-gray-400 hover:text-orange-500 transition text-sm">Blog</a></li>
                            <li><a href="#" class="text-gray-400 hover:text-orange-500 transition text-sm">Contribute</a></li>
                        </ul>
                    </div>
                    <div>
                        <h3 class="text-white font-medium mb-4">Connect</h3>
                        <div class="flex space-x-4">
                            <a href="#" class="text-gray-400 hover:text-orange-500 transition"><i class="fab fa-discord"></i></a>
                            <a href="#" class="text-gray-400 hover:text-orange-500 transition"><i class="fab fa-twitter"></i></a>
                            <a href="#" class="text-gray-400 hover:text-orange-500 transition"><i class="fab fa-facebook"></i></a>
                            <a href="#" class="text-gray-400 hover:text-orange-500 transition"><i class="fab fa-reddit"></i></a>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-8 pt-6 text-center text-gray-500 text-sm">
                <p>© 2023 Oreki. All content is property of their respective owners.</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        document.querySelector('.fa-bars').addEventListener('click', function() {
            // Implementation for mobile menu toggle
            console.log('Mobile menu clicked');
        });
        
        // AI Search functionality
        document.querySelector('.fa-robot').parentElement.addEventListener('click', function() {
            // Implementation for AI search
            console.log('AI Search clicked');
        });
    </script>
</body>
</html>
