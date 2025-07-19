<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jhabua Youth - हिन्दू युवाओं का एकता और उत्थान</title>
    
    <!-- Tailwind CSS for styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Poppins for a clean, modern look -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&family=Teko:wght@500;700&display=swap" rel="stylesheet">
    
    <!-- Font Awesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <style>
        /* Custom styles for the website */
        body {
            font-family: 'Poppins', sans-serif;
        }
        h1, h2, h3, .teko-font {
            font-family: 'Teko', sans-serif;
        }
        /* Saffron color theme */
        .bg-saffron { background-color: #FF9933; }
        .text-saffron { color: #FF9933; }
        .border-saffron { border-color: #FF9933; }
        
        /* Subtle pattern for background */
        .hero-bg {
            background-color: #fff8f0;
            background-image:
                linear-gradient(rgba(255, 255, 255, 0.8), rgba(255, 255, 255, 0.8)),
                url("https://www.transparenttextures.com/patterns/gplay.png");
        }

        /* Smooth scroll behavior */
        html {
            scroll-behavior: smooth;
        }

        /* Custom button style */
        .btn-saffron {
            @apply bg-saffron text-white font-bold py-3 px-8 rounded-lg shadow-lg transform hover:scale-105 transition-transform duration-300;
        }

        /* === ANIMATION ADDED HERE === */
        .animated-gradient-text {
            background: linear-gradient(90deg, #FF671F, #FFFFFF, #046A38, #FF671F); /* Saffron, White, Green */
            background-size: 200% auto;
            -webkit-background-clip: text;
            background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: shine 4s linear infinite;
        }

        @keyframes shine {
            to {
                background-position: 200% center;
            }
        }
    </style>
</head>
<body class="bg-gray-50">

    <!-- Header and Navigation -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-3 flex justify-between items-center">
            <a href="#home" class="teko-font text-3xl font-bold text-saffron flex items-center">
                <!-- === LOGO UPDATED HERE === -->
                <img src="https://res.cloudinary.com/dtjjgiitl/image/upload/q_auto:good,f_auto,fl_progressive/v1752920986/zo0pd6yxstg4itilm06d.jpg" alt="Jhabua Youth Logo" class="mr-3 h-10 w-10 sm:h-12 sm:w-12 object-contain">
                Jhabua Youth
            </a>
            <div class="hidden md:flex space-x-8">
                <a href="#home" class="text-gray-700 hover:text-saffron font-semibold">होम</a>
                <a href="#about" class="text-gray-700 hover:text-saffron font-semibold">हमारे बारे में</a>
                <a href="#join" class="text-gray-700 hover:text-saffron font-semibold">हमसे जुड़ें</a>
                <a href="#contact" class="text-gray-700 hover:text-saffron font-semibold">संपर्क</a>
            </div>
            <div class="md:hidden">
                <button id="mobile-menu-button" class="text-gray-700 focus:outline-none">
                    <i class="fas fa-bars text-2xl"></i>
                </button>
            </div>
        </nav>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white py-2">
            <a href="#home" class="block px-6 py-2 text-gray-700 hover:bg-saffron hover:text-white">होम</a>
            <a href="#about" class="block px-6 py-2 text-gray-700 hover:bg-saffron hover:text-white">हमारे बारे में</a>
            <a href="#join" class="block px-6 py-2 text-gray-700 hover:bg-saffron hover:text-white">हमसे जुड़ें</a>
            <a href="#contact" class="block px-6 py-2 text-gray-700 hover:bg-saffron hover:text-white">संपर्क</a>
        </div>
    </header>

    <main>
        <!-- Section 1: Hero (Landing Page) -->
        <section id="home" class="hero-bg min-h-screen flex items-center justify-center text-center py-20 px-4">
            <div class="container mx-auto">
                <!-- === ANIMATION CLASS ADDED TO H1 TAG & FONT SIZE ADJUSTED FOR MOBILE === -->
                <h1 class="text-5xl sm:text-6xl md:text-8xl font-bold text-gray-800 drop-shadow-lg animated-gradient-text">Jhabua Youth</h1>
                <p class="teko-font text-2xl sm:text-3xl md:text-4xl text-saffron mt-4 tracking-wider">हिन्दू युवाओं का एकता और उत्थान</p>
                <p class="mt-6 max-w-2xl mx-auto text-gray-600 text-base sm:text-lg">
                    हम झाबुआ के हिन्दू युवाओं का एक सशक्त समूह हैं, जो धर्म, संस्कृति और समाज की सेवा के लिए समर्पित है। हमारा लक्ष्य युवाओं को संगठित कर एक सकारात्मक बदलाव लाना है।
                </p>
                <a href="#join" class="mt-10 inline-block btn-saffron teko-font text-xl sm:text-2xl">
                    <i class="fab fa-whatsapp mr-2"></i> अभी जुड़ें!
                </a>
            </div>
        </section>

        <!-- Section 2: About Us -->
        <section id="about" class="py-20 bg-white">
            <div class="container mx-auto px-6">
                <h2 class="text-3xl sm:text-4xl md:text-5xl font-bold text-center text-gray-800">हमारे बारे में</h2>
                <div class="w-24 h-1 bg-saffron mx-auto mt-4 mb-12"></div>
                
                <div class="grid md:grid-cols-2 gap-12 items-center">
                    <div>
                        <h3 class="text-2xl sm:text-3xl font-bold text-saffron mb-4">हमारा उद्देश्य और दृष्टिकोण</h3>
                        <p class="text-gray-600 mb-4">
                            "Jhabua Youth" का मुख्य उद्देश्य हिन्दू युवाओं में सामाजिक और धार्मिक जागरूकता फैलाना है। हम मानते हैं कि संगठित युवा ही समाज और राष्ट्र की नींव को मजबूत कर सकते हैं।
                        </p>
                        <ul class="space-y-3 text-gray-700">
                            <li class="flex items-start"><i class="fas fa-om text-saffron mt-1 mr-3"></i><span><b>धर्म रक्षा:</b> अपनी संस्कृति और मूल्यों का संरक्षण और संवर्धन करना।</span></li>
                            <li class="flex items-start"><i class="fas fa-users text-saffron mt-1 mr-3"></i><span><b>समाज सेवा:</b> रक्तदान, स्वच्छता अभियान और जरूरतमंदों की मदद करना।</span></li>
                            <li class="flex items-start"><i class="fas fa-hand-holding-heart text-saffron mt-1 mr-3"></i><span><b>युवा सशक्तिकरण:</b> युवाओं को कौशल और नेतृत्व के लिए प्रेरित करना।</span></li>
                        </ul>
                    </div>
                    <div>
                        <img src="https://placehold.co/600x400/FF9933/FFFFFF?text=हमारी+टीम" alt="Group of Jhabua Youth members" class="rounded-lg shadow-xl w-full h-auto">
                    </div>
                </div>

                <!-- Past Events Gallery -->
                <div class="mt-20">
                    <h3 class="text-2xl sm:text-3xl font-bold text-center text-saffron mb-8">हमारी गतिविधियाँ</h3>
                    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
                        <div class="bg-gray-50 p-6 rounded-lg shadow-md text-center">
                            <img src="https://placehold.co/400x300/f0f0f0/333?text=रक्तदान+शिविर" alt="Blood Donation Camp" class="rounded-lg mb-4 w-full h-auto">
                            <h4 class="text-xl font-bold text-gray-800">रक्तदान शिविर</h4>
                            <p class="text-gray-600 mt-2">समाज के लिए जीवनदान का महायज्ञ।</p>
                        </div>
                        <div class="bg-gray-50 p-6 rounded-lg shadow-md text-center">
                            <img src="https://placehold.co/400x300/f0f0f0/333?text=सांस्कृतिक+कार्यक्रम" alt="Cultural Event" class="rounded-lg mb-4 w-full h-auto">
                            <h4 class="text-xl font-bold text-gray-800">सांस्कृतिक कार्यक्रम</h4>
                            <p class="text-gray-600 mt-2">अपनी गौरवशाली परंपराओं का उत्सव।</p>
                        </div>
                        <div class="bg-gray-50 p-6 rounded-lg shadow-md text-center">
                            <img src="https://placehold.co/400x300/f0f0f0/333?text=जागरूकता+अभियान" alt="Awareness Campaign" class="rounded-lg mb-4 w-full h-auto">
                            <h4 class="text-xl font-bold text-gray-800">जागरूकता अभियान</h4>
                            <p class="text-gray-600 mt-2">युवाओं को सामाजिक मुद्दों पर जागरूक करना।</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Section 3: Join Us Form -->
        <section id="join" class="py-20 hero-bg">
            <div class="container mx-auto px-6">
                <h2 class="text-3xl sm:text-4xl md:text-5xl font-bold text-center text-gray-800">हमसे जुड़ें</h2>
                <div class="w-24 h-1 bg-saffron mx-auto mt-4 mb-12"></div>
                <p class="text-center text-gray-600 max-w-2xl mx-auto mb-10">
                    यदि आप भी Jhabua Youth का हिस्सा बनकर धर्म और समाज की सेवा करना चाहते हैं, तो नीचे दिया गया फॉर्म भरें और सीधे हमारे व्हाट्सएप ग्रुप से जुड़ें।
                </p>
                <div class="max-w-xl mx-auto bg-white p-8 rounded-xl shadow-2xl">
                    <form id="join-form">
                        <div class="mb-5">
                            <label for="name" class="block mb-2 font-bold text-gray-700">पूरा नाम</label>
                            <input type="text" id="name" name="name" placeholder="आपका पूरा नाम" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-saffron" required>
                        </div>
                        <div class="mb-5">
                            <label for="age" class="block mb-2 font-bold text-gray-700">आयु</label>
                            <input type="number" id="age" name="age" placeholder="आपकी उम्र" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-saffron" required>
                        </div>
                        <div class="mb-5">
                            <label for="whatsapp" class="block mb-2 font-bold text-gray-700">व्हाट्सएप नंबर</label>
                            <input type="tel" id="whatsapp" name="whatsapp" placeholder="10 अंकों का व्हाट्सएप नंबर" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-saffron" required pattern="[0-9]{10}">
                        </div>
                        <div class="mb-8">
                            <label for="location" class="block mb-2 font-bold text-gray-700">स्थान (शहर/गांव)</label>
                            <input type="text" id="location" name="location" placeholder="आपका शहर या गांव" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-saffron" required>
                        </div>
                        <button type="submit" class="w-full btn-saffron teko-font text-2xl">
                            <i class="fab fa-whatsapp"></i> Join Now
                        </button>
                    </form>
                    <div id="form-message" class="mt-4 text-center"></div>
                </div>
            </div>
        </section>

        <!-- Section 4: Contact Us -->
        <footer id="contact" class="bg-gray-800 text-white pt-16 pb-8">
            <div class="container mx-auto px-6 text-center">
                <h2 class="text-3xl sm:text-4xl font-bold">संपर्क करें</h2>
                <p class="mt-4 max-w-md mx-auto">
                    किसी भी प्रश्न या सुझाव के लिए, हमसे संपर्क करने में संकोच न करें।
                </p>
                <div class="mt-8 flex justify-center space-x-6">
                    <a href="#" class="text-white hover:text-saffron text-3xl transition-colors duration-300"><i class="fab fa-whatsapp"></i></a>
                    <a href="#" class="text-white hover:text-saffron text-3xl transition-colors duration-300"><i class="fab fa-instagram"></i></a>
                    <a href="#" class="text-white hover:text-saffron text-3xl transition-colors duration-300"><i class="fab fa-facebook"></i></a>
                    <a href="#" class="text-white hover:text-saffron text-3xl transition-colors duration-300"><i class="fas fa-envelope"></i></a>
                </div>
                <div class="mt-12 border-t border-gray-700 pt-8">
                    <p>&copy; <span id="year"></span> Jhabua Youth. All Rights Reserved.</p>
                    <p class="text-sm text-gray-400 mt-2">Designed with <i class="fas fa-heart text-red-500"></i> for a united cause.</p>
                </div>
            </div>
        </footer>
    </main>

    <script>
        // --- FIX: Wrap all JS code in DOMContentLoaded event listener ---
        document.addEventListener('DOMContentLoaded', function() {
            // --- Mobile Menu Toggle ---
            const mobileMenuButton = document.getElementById('mobile-menu-button');
            const mobileMenu = document.getElementById('mobile-menu');
            if (mobileMenuButton) {
                mobileMenuButton.addEventListener('click', () => {
                    mobileMenu.classList.toggle('hidden');
                });
            }

            // --- Set current year in footer ---
            const yearSpan = document.getElementById('year');
            if (yearSpan) {
                yearSpan.textContent = new Date().getFullYear();
            }

            // --- Join Form Submission and WhatsApp Redirect ---
            const joinForm = document.getElementById('join-form');
            const formMessage = document.getElementById('form-message');

            if (joinForm) {
                joinForm.addEventListener('submit', function(event) {
                    event.preventDefault(); // Prevent the default form submission

                    // --- === WHATSAPP LINK UPDATED HERE === ---
                    const whatsappGroupLink = 'https://whatsapp.com/channel/0029Vb5tRWx4tRs2UP0zBb3V';

                    // Get form values
                    const name = document.getElementById('name').value.trim();
                    const age = document.getElementById('age').value.trim();
                    const whatsapp = document.getElementById('whatsapp').value.trim();
                    const location = document.getElementById('location').value.trim();
                    
                    // Simple validation
                    if (!name || !age || !whatsapp || !location) {
                        formMessage.textContent = 'कृपया सभी फ़ील्ड भरें।';
                        formMessage.className = 'mt-4 text-center text-red-500 font-semibold';
                        return;
                    }

                    if (whatsapp.length !== 10 || !/^\d{10}$/.test(whatsapp)) {
                        formMessage.textContent = 'कृपया 10 अंकों का सही व्हाट्सएप नंबर दर्ज करें।';
                        formMessage.className = 'mt-4 text-center text-red-500 font-semibold';
                        return;
                    }
                    
                    // If validation passes
                    formMessage.textContent = 'सफलतापूर्वक सबमिट किया गया! आपको व्हाट्सएप पर रीडायरेक्ट किया जा रहा है...';
                    formMessage.className = 'mt-4 text-center text-green-500 font-semibold';

                    // NOTE FOR ADMIN: 
                    // The form data is NOT saved anywhere with this code.
                    // To save data, you can use services like Formspree, Netlify Forms,
                    // or a custom backend API to which you can send this data.
                    // For now, the primary action is to redirect to WhatsApp.

                    // Redirect to WhatsApp after a short delay
                    setTimeout(() => {
                        window.open(whatsappGroupLink, '_blank');
                    }, 1500); // 1.5-second delay
                });
            }
        });
    </script>

</body>
</html>
