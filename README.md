<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Roy Otieno | Renewable Energy & E-Mobility Engineer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#f0fdfa',
                            100: '#ccfbf1',
                            500: '#14b8a6',
                            600: '#0d9488',
                            700: '#0f766e',
                            900: '#134e4a',
                        },
                        accent: {
                            500: '#3b82f6',
                            600: '#2563eb',
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', '-apple-system', 'BlinkMacSystemFont', 'Segoe UI', 'Roboto', 'Helvetica Neue', 'Arial', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap');
        body {
            font-family: 'Inter', sans-serif;
        }
        .gradient-text {
            background-clip: text;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .bg-pattern {
            background-image: radial-gradient(#e5e7eb 1px, transparent 1px);
            background-size: 20px 20px;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-brand-500 selection:text-white">

    <!-- Navigation -->
    <nav class="fixed w-full bg-white/80 backdrop-blur-md z-50 border-b border-slate-200">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16 items-center">
                <div class="flex-shrink-0 font-bold text-xl tracking-tighter text-slate-900">
                    RO<span class="text-brand-600">.</span>
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#about" class="text-sm font-medium text-slate-600 hover:text-brand-600 transition-colors">About</a>
                    <a href="#skills" class="text-sm font-medium text-slate-600 hover:text-brand-600 transition-colors">Tech Stack</a>
                    <a href="#work" class="text-sm font-medium text-slate-600 hover:text-brand-600 transition-colors">Featured Work</a>
                    <a href="#contact" class="text-sm font-medium text-slate-600 hover:text-brand-600 transition-colors">Contact</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="relative pt-32 pb-20 lg:pt-48 lg:pb-32 overflow-hidden bg-pattern">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="text-center max-w-3xl mx-auto">
                <div class="inline-flex items-center px-3 py-1 rounded-full bg-brand-50 text-brand-700 text-sm font-semibold mb-6 border border-brand-100">
                    <span class="flex h-2 w-2 rounded-full bg-brand-500 mr-2 animate-pulse"></span>
                    Available for collaborations
                </div>
                <h1 class="text-5xl md:text-6xl font-extrabold tracking-tight text-slate-900 mb-6">
                    Hi 👋, I'm <span class="bg-gradient-to-r from-brand-600 to-accent-600 gradient-text">Roy Otieno</span>
                </h1>
                <p class="text-xl md:text-2xl text-slate-600 mb-8 leading-relaxed">
                    Engineer building sustainable energy systems and electric mobility infrastructure in Africa.
                </p>
                <div class="flex flex-col sm:flex-row justify-center gap-4">
                    <a href="#work" class="px-8 py-3 rounded-lg bg-slate-900 text-white font-medium hover:bg-slate-800 transition-colors shadow-lg shadow-slate-900/20">
                        View My Work
                    </a>
                    <a href="mailto:royokola3@gmail.com" class="px-8 py-3 rounded-lg bg-white text-slate-900 border border-slate-200 font-medium hover:border-slate-300 hover:bg-slate-50 transition-colors">
                        Get in Touch
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-3xl font-bold text-slate-900 mb-6">About Me</h2>
                    <div class="space-y-4 text-lg text-slate-600 leading-relaxed">
                        <p>
                            I am an <strong>Agricultural and Biosystems Engineer</strong> based in Nairobi, Kenya 🇰🇪—a rapidly growing hub for e-mobility and green energy innovation in East Africa.
                        </p>
                        <p>
                            I focus on the critical intersection of <strong>renewable energy systems and electric mobility infrastructure</strong>, applying core engineering principles to build robust, scalable, and environmentally sustainable physical systems.
                        </p>
                        <p>
                            <strong>My Mission:</strong> Developing innovative solutions that bridge the gap between legacy power grids and modern energy infrastructure. My goal is to facilitate a seamless transition to electric transport and renewable power generation by building systems that are both economically viable and ecologically sound.
                        </p>
                    </div>
                </div>
                <div class="bg-slate-50 rounded-2xl p-8 border border-slate-100 shadow-sm">
                    <h3 class="text-xl font-bold text-slate-900 mb-4 flex items-center">
                        <i class="fa-solid fa-bolt text-brand-500 mr-3"></i> Core Focus Areas
                    </h3>
                    <ul class="space-y-4 text-slate-600">
                        <li class="flex items-start">
                            <i class="fa-solid fa-check text-brand-500 mt-1 mr-3"></i>
                            <span>End-to-end solar energy integration & PV System Design</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa-solid fa-check text-brand-500 mt-1 mr-3"></i>
                            <span>Developing smart EV charging networks (CPMS)</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa-solid fa-check text-brand-500 mt-1 mr-3"></i>
                            <span>Productive Use of Energy (Solar Water Pumping)</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fa-solid fa-check text-brand-500 mt-1 mr-3"></i>
                            <span>Architecting sustainable mobility data systems</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Tech Stack Section -->
    <section id="skills" class="py-20 bg-slate-50">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-2xl mx-auto mb-16">
                <h2 class="text-3xl font-bold text-slate-900 mb-4">Tech Stack & Focus Areas</h2>
                <p class="text-lg text-slate-600">A blend of robust physical engineering tools and modern software development frameworks.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Engineering Card -->
                <div class="bg-white rounded-2xl p-8 shadow-sm border border-slate-100 hover:shadow-md transition-shadow">
                    <div class="h-12 w-12 rounded-xl bg-brand-50 text-brand-600 flex items-center justify-center mb-6">
                        <i class="fa-solid fa-solar-panel text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 mb-4">Engineering & Infrastructure</h3>
                    <div class="space-y-4">
                        <div>
                            <h4 class="font-semibold text-slate-800">Energy Systems Design</h4>
                            <p class="text-slate-600 text-sm mt-1">PVsyst, AutoCAD, Homer Pro, SketchUp for sizing, 3D modeling, and yield forecasting.</p>
                        </div>
                        <div>
                            <h4 class="font-semibold text-slate-800">Electric Mobility</h4>
                            <p class="text-slate-600 text-sm mt-1">EVSE hardware integration, OCPP implementation, dynamic load management.</p>
                        </div>
                        <div>
                            <h4 class="font-semibold text-slate-800">Electrical Engineering</h4>
                            <p class="text-slate-600 text-sm mt-1">Single-line diagrams, cable sizing, protective device coordination, energy auditing.</p>
                        </div>
                    </div>
                </div>

                <!-- Software Card -->
                <div class="bg-white rounded-2xl p-8 shadow-sm border border-slate-100 hover:shadow-md transition-shadow">
                    <div class="h-12 w-12 rounded-xl bg-accent-50 text-accent-600 flex items-center justify-center mb-6">
                        <i class="fa-solid fa-code text-2xl"></i>
                    </div>
                    <h3 class="text-xl font-bold text-slate-900 mb-4">Software & Tools</h3>
                    <div class="space-y-4">
                        <div>
                            <h4 class="font-semibold text-slate-800">Languages & Frameworks</h4>
                            <p class="text-slate-600 text-sm mt-1">Python (data processing, automation), JavaScript, Next.js (dashboards & internal tools).</p>
                        </div>
                        <div>
                            <h4 class="font-semibold text-slate-800">Data & Analytics</h4>
                            <p class="text-slate-600 text-sm mt-1">Pandas, NumPy, SQL for mobility patterns, grid reliability, and solar production data.</p>
                        </div>
                        <div>
                            <h4 class="font-semibold text-slate-800">Version Control</h4>
                            <p class="text-slate-600 text-sm mt-1">Git, GitHub, and CI/CD workflows for collaborative engineering.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Featured Work Section -->
    <section id="work" class="py-20 bg-white">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="mb-16">
                <h2 class="text-3xl font-bold text-slate-900 mb-4">Featured Work</h2>
                <p class="text-lg text-slate-600">Projects bridging the gap between hardware and software.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="group bg-slate-50 rounded-2xl overflow-hidden border border-slate-100 hover:shadow-lg transition-all duration-300 transform hover:-translate-y-1">
                    <div class="h-48 bg-gradient-to-br from-brand-500 to-brand-700 flex items-center justify-center p-6">
                        <i class="fa-solid fa-charging-station text-6xl text-white/80 group-hover:scale-110 transition-transform duration-300"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-slate-900 mb-2">Electric Mobility Infrastructure</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Engineering integrated systems supporting large-scale EV charging networks. Includes feasibility studies, power distribution architectures, and integrating telemetry data to monitor charger uptime.
                        </p>
                    </div>
                </div>

                <!-- Project 2 -->
                <div class="group bg-slate-50 rounded-2xl overflow-hidden border border-slate-100 hover:shadow-lg transition-all duration-300 transform hover:-translate-y-1">
                    <div class="h-48 bg-gradient-to-br from-amber-400 to-orange-500 flex items-center justify-center p-6">
                        <i class="fa-solid fa-sun text-6xl text-white/80 group-hover:scale-110 transition-transform duration-300"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-slate-900 mb-2">Renewable Energy Systems</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Designing and deploying grid-tied and off-grid solar projects. Focused on "Productive Use of Energy" via optimized solar water pumping systems that increase agricultural yields.
                        </p>
                    </div>
                </div>

                <!-- Project 3 -->
                <div class="group bg-slate-50 rounded-2xl overflow-hidden border border-slate-100 hover:shadow-lg transition-all duration-300 transform hover:-translate-y-1">
                    <div class="h-48 bg-gradient-to-br from-accent-500 to-indigo-600 flex items-center justify-center p-6">
                        <i class="fa-solid fa-laptop-code text-6xl text-white/80 group-hover:scale-110 transition-transform duration-300"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold text-slate-900 mb-2">Engineering Tools</h3>
                        <p class="text-slate-600 text-sm leading-relaxed">
                            Developing bespoke technical scripts supporting energy design. Creating automated workflows for yield calculations, financial feasibility (LCOE), and real-time monitoring.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer / Contact -->
    <footer id="contact" class="bg-slate-900 py-16 text-white border-t border-slate-800">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-3xl font-bold mb-4">Let's build the future.</h2>
                    <p class="text-slate-400 mb-8 max-w-md">
                        Always eager to connect with fellow engineers, developers, and sustainability advocates working on climate tech, e-mobility, and renewable energy.
                    </p>
                    <div class="flex space-x-4">
                        <a href="mailto:royokola3@gmail.com" class="h-12 w-12 rounded-full bg-slate-800 flex items-center justify-center hover:bg-brand-500 hover:text-white transition-colors duration-300">
                            <i class="fa-regular fa-envelope text-xl"></i>
                        </a>
                        <a href="#" class="h-12 w-12 rounded-full bg-slate-800 flex items-center justify-center hover:bg-brand-500 hover:text-white transition-colors duration-300">
                            <i class="fa-brands fa-x-twitter text-xl"></i>
                        </a>
                        <a href="#" class="h-12 w-12 rounded-full bg-slate-800 flex items-center justify-center hover:bg-brand-500 hover:text-white transition-colors duration-300">
                            <i class="fa-brands fa-github text-xl"></i>
                        </a>
                    </div>
                </div>
                <div class="md:text-right">
                    <div class="inline-flex items-center space-x-2 text-slate-300 bg-slate-800 px-4 py-2 rounded-lg">
                        <i class="fa-solid fa-location-dot text-brand-500"></i>
                        <span>Nairobi, Kenya (Open to global collabs)</span>
                    </div>
                    <div class="mt-8 text-slate-500 text-sm">
                        &copy; <span id="year"></span> Roy Otieno. Engineered for a sustainable future.
                    </div>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Set current year in footer
        document.getElementById('year').textContent = new Date().getFullYear();
    </script>
</body>
</html>
