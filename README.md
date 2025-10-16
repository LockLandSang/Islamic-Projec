<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Golden Age of Islam Contributions</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        amber: {
                            50: '#fffbeb',
                            100: '#fef3c7',
                            200: '#fde68a',
                            300: '#fcd34d',
                            400: '#fbbf24',
                            500: '#f59e0b',
                            600: '#d97706',
                            700: '#b45309',
                            800: '#92400e',
                            900: '#78350f',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Open+Sans:wght@300;400;600&display=swap');
        
        body {
            font-family: 'Open Sans', sans-serif;
            background: linear-gradient(to bottom, #fffbeb, #cffafe);
        }
        
        h1, h2, h3 {
            font-family: 'Playfair Display', serif;
        }
        
        .section-icon {
            transition: transform 0.3s ease;
        }
        
        .section-icon:hover {
            transform: scale(1.1);
        }
        
        .source-link {
            transition: all 0.2s ease;
        }
        
        .source-link:hover {
            transform: translateX(5px);
        }
    </style>
</head>
<body class="min-h-screen">
    <!-- Header Section -->
    <header class="relative py-20 px-4 text-center">
        <div class="absolute inset-0 bg-cover bg-center opacity-20" style="background-image: url('https://images.unsplash.com/photo-1505228395891-9a51e7e86bf6?auto=format&fit=crop')"></div>
        <div class="relative z-10 max-w-4xl mx-auto">
            <h1 class="text-4xl md:text-6xl font-bold text-amber-900 mb-6">
                Golden Age of Islam Contributions
            </h1>
            <p class="text-lg md:text-xl text-amber-800 max-w-3xl mx-auto">
                Exploring the remarkable scientific and mathematical achievements of Islamic scholars 
                during the Golden Age (8th-13th centuries) that laid the foundation for modern knowledge.
            </p>
        </div>
    </header>

    <main class="max-w-6xl mx-auto px-4 py-12 space-y-16">
        <!-- Algebra Section -->
        <section>
            <div class="border-2 border-amber-200 bg-white/80 backdrop-blur-sm shadow-lg rounded-xl overflow-hidden">
                <div class="p-6 md:p-8">
                    <div class="flex items-center gap-3 mb-6">
                        <i class="fas fa-square-root-alt text-amber-600 text-3xl section-icon"></i>
                        <h2 class="text-3xl text-amber-900 font-bold">Algebra</h2>
                    </div>
                    <div class="grid md:grid-cols-2 gap-8 items-center">
                        <div>
                            <p class="text-gray-700 mb-4">
                                The word "algebra" comes from the Arabic "al-jabr" meaning "reunion of broken parts". 
                                Muhammad ibn Musa al-Khwarizmi, a 9th-century Persian mathematician, wrote 
                                "The Compendious Book on Calculation by Completion and Balancing" which established 
                                algebra as a distinct mathematical discipline.
                            </p>
                            <p class="text-gray-700 mb-4">
                                Al-Khwarizmi introduced systematic methods for solving linear and quadratic equations, 
                                moving away from geometric approaches to purely algebraic ones. His work was translated 
                                into Latin and became the primary mathematics textbook in European universities for 
                                centuries.
                            </p>
                            <p class="text-gray-700">
                                Other Islamic mathematicians like Omar Khayyam further developed algebraic geometry, 
                                while Sharaf al-Din al-Tusi found algebraic solutions to cubic equations. These 
                                contributions were fundamental to the later development of calculus and modern mathematics.
                            </p>
                        </div>
                        <div class="flex justify-center">
                            <div class="bg-gray-200 border-2 border-dashed border-amber-300 rounded-xl w-full h-64 md:h-80 flex items-center justify-center">
                                <span class="text-amber-700 font-medium">Algebraic Equations Visualization</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Medicine Section -->
        <section>
            <div class="border-2 border-rose-200 bg-white/80 backdrop-blur-sm shadow-lg rounded-xl overflow-hidden">
                <div class="p-6 md:p-8">
                    <div class="flex items-center gap-3 mb-6">
                        <i class="fas fa-heartbeat text-rose-600 text-3xl section-icon"></i>
                        <h2 class="text-3xl text-rose-900 font-bold">Medicine</h2>
                    </div>
                    <div class="grid md:grid-cols-2 gap-8 items-center">
                        <div class="md:order-2">
                            <p class="text-gray-700 mb-4">
                                Islamic physicians revolutionized medical practice through comprehensive encyclopedias, 
                                hospitals with separate wards, and rigorous medical education. The Persian polymath 
                                Ibn Sina (Avicenna) wrote "The Canon of Medicine", a 14-volume encyclopedia that 
                                became the standard medical text in Europe and the Islamic world for 600 years.
                            </p>
                            <p class="text-gray-700 mb-4">
                                Islamic hospitals (bimaristans) were among the first to have separate wards for 
                                different diseases, pharmacies, and medical schools. Physicians like Al-Razi (Rhazes) 
                                made significant advances in clinical medicine, distinguishing between smallpox and measles, 
                                and conducting clinical trials.
                            </p>
                            <p class="text-gray-700">
                                Surgeons like Al-Zahrawi (Abulcasis) pioneered surgical techniques and instruments, 
                                many of which are still in use today. Islamic physicians also emphasized the importance 
                                of diet, hygiene, and mental health in treatment - concepts that are fundamental to 
                                modern medicine.
                            </p>
                        </div>
                        <div class="flex justify-center md:order-1">
                            <div class="bg-gray-200 border-2 border-dashed border-rose-300 rounded-xl w-full h-64 md:h-80 flex items-center justify-center">
                                <span class="text-rose-700 font-medium">Medical Instruments Illustration</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Astronomy Section -->
        <section>
            <div class="border-2 border-indigo-200 bg-white/80 backdrop-blur-sm shadow-lg rounded-xl overflow-hidden">
                <div class="p-6 md:p-8">
                    <div class="flex items-center gap-3 mb-6">
                        <i class="fas fa-star text-indigo-600 text-3xl section-icon"></i>
                        <h2 class="text-3xl text-indigo-900 font-bold">Astronomy</h2>
                    </div>
                    <div class="grid md:grid-cols-2 gap-8 items-center">
                        <div>
                            <p class="text-gray-700 mb-4">
                                Islamic astronomers made groundbreaking observations and calculations that corrected 
                                and expanded upon Greek astronomical knowledge. Al-Battani improved the accuracy of 
                                the solar year calculation, while Al-Sufi (Azophi) created detailed star charts and 
                                identified the Andromeda Galaxy.
                            </p>
                            <p class="text-gray-700 mb-4">
                                The invention of numerous astronomical instruments, including improved astrolabes, 
                                quadrants, and celestial globes, enabled more precise observations. The observatory 
                                at Maragheh, founded by Nasir al-Din al-Tusi, became a major center of astronomical 
                                research and influenced later European observatories.
                            </p>
                            <p class="text-gray-700">
                                Islamic astronomers like Ibn al-Shatir developed mathematical models that were later 
                                adopted by Copernicus. Their work preserved and enhanced ancient knowledge while 
                                introducing new methods of observation and calculation that were crucial to the 
                                Scientific Revolution.
                            </p>
                        </div>
                        <div class="flex justify-center">
                            <div class="bg-gray-200 border-2 border-dashed border-indigo-300 rounded-xl w-full h-64 md:h-80 flex items-center justify-center">
                                <span class="text-indigo-700 font-medium">Celestial Map Illustration</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- Sources Section -->
    <section class="max-w-4xl mx-auto px-4 py-12">
        <div class="border-2 border-emerald-200 bg-white/80 backdrop-blur-sm shadow-lg rounded-xl overflow-hidden">
            <div class="p-6 md:p-8">
                <h2 class="text-3xl text-emerald-900 font-bold mb-6">Sources & Further Reading</h2>
                <ul class="space-y-4">
                    <li>
                        <a href="https://www.britannica.com/biography/al-Khwarizmi" target="_blank" 
                           class="source-link flex items-start text-gray-700 hover:text-emerald-700">
                            <i class="fas fa-external-link-alt text-emerald-600 mt-1 mr-3"></i>
                            <span><strong>Al-Khwarizmi - Britannica</strong> - Biography and contributions to algebra</span>
                        </a>
                    </li>
                    <li>
                        <a href="https://www.britannica.com/biography/Avicenna" target="_blank" 
                           class="source-link flex items-start text-gray-700 hover:text-emerald-700">
                            <i class="fas fa-external-link-alt text-emerald-600 mt-1 mr-3"></i>
                            <span><strong>Avicenna (Ibn Sina) - Britannica</strong> - Medical contributions and "The Canon of Medicine"</span>
                        </a>
                    </li>
                    <li>
                        <a href="https://www.britannica.com/biography/Abd-al-Rahman-al-Sufi" target="_blank" 
                           class="source-link flex items-start text-gray-700 hover:text-emerald-700">
                            <i class="fas fa-external-link-alt text-emerald-600 mt-1 mr-3"></i>
                            <span><strong>Al-Sufi (Azophi) - Britannica</strong> - Astronomical observations and star catalogues</span>
                        </a>
                    </li>
                    <li>
                        <a href="https://www.islamicity.org/6573/the-golden-age-of-islam/" target="_blank" 
                           class="source-link flex items-start text-gray-700 hover:text-emerald-700">
                            <i class="fas fa-external-link-alt text-emerald-600 mt-1 mr-3"></i>
                            <span><strong>Islamicity.org</strong> - Comprehensive overview of the Golden Age of Islam</span>
                        </a>
                    </li>
                    <li>
                        <a href="https://www.history.com/topics/inventions/history-of-medicine" target="_blank" 
                           class="source-link flex items-start text-gray-700 hover:text-emerald-700">
                            <i class="fas fa-external-link-alt text-emerald-600 mt-1 mr-3"></i>
                            <span><strong>History.com</strong> - History of medicine including Islamic contributions</span>
                        </a>
                    </li>
                    <li>
                        <a href="https://plato.stanford.edu/entries/al-khwarizmi/" target="_blank" 
                           class="source-link flex items-start text-gray-700 hover:text-emerald-700">
                            <i class="fas fa-external-link-alt text-emerald-600 mt-1 mr-3"></i>
                            <span><strong>Stanford Encyclopedia of Philosophy</strong> - Detailed analysis of Al-Khwarizmi's mathematical work</span>
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </section>

    <footer class="py-8 text-center text-amber-800 border-t border-amber-200 mt-8">
        <p>© <span id="currentYear"></span> Golden Age of Islam Contributions</p>
        <p class="text-sm mt-2 text-amber-600">Educational resource highlighting historical scientific achievements</p>
    </footer>

    <script>
        // Set current year in footer
        document.getElementById('currentYear').textContent = new Date().getFullYear();
    </script>
</body>
</html>
