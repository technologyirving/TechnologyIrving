<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Irving Technology | Deep Learning & Espectrometría</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        darkBg: '#0b0f19',
                        cardBg: '#111827',
                        accentBlue: '#3b82f6',
                        accentCyan: '#06b6d4',
                    }
                }
            }
        }
    </script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body { font-family: 'Inter', sans-serif; }
        .glow-effect {
            box-shadow: 0 0 25px rgba(6, 182, 212, 0.15);
        }
        .glow-effect:hover {
            box-shadow: 0 0 35px rgba(59, 130, 246, 0.3);
        }
    </style>
</head>
<body class="bg-darkBg text-slate-100 antialiased selection:bg-accentCyan selection:text-darkBg">

    <header class="fixed top-0 left-0 right-0 z-50 bg-darkBg/80 backdrop-blur-md border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
            <a href="#inicio" class="flex items-center space-x-3 group">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-tr from-accentCyan to-accentBlue flex items-center justify-center glow-effect transition-transform group-hover:scale-105">
                    <i class="fa-solid fa-microchip text-darkBg text-xl font-bold"></i>
                </div>
                <span class="text-xl font-extrabold tracking-tight bg-gradient-to-r from-white via-slate-200 to-accentCyan bg-clip-text text-transparent">
                    Irving<span class="text-accentCyan">Technology</span>
                </span>
            </a>
            
            <nav class="hidden md:flex items-center space-x-8 text-sm font-medium text-slate-300">
                <a href="#inicio" class="hover:text-accentCyan transition-colors">Inicio</a>
                <a href="#investigacion" class="hover:text-accentCyan transition-colors">Espectrometría & IA</a>
                <a href="#proyectos" class="hover:text-accentCyan transition-colors">Proyectos Web</a>
                <a href="#contacto" class="px-5 py-2.5 rounded-full bg-gradient-to-r from-accentCyan to-accentBlue text-darkBg font-semibold hover:opacity-90 transition-all shadow-lg shadow-cyan-500/20">
                    Contacto
                </a>
            </nav>

            <button id="menu-btn" class="md:hidden text-slate-300 focus:outline-none text-2xl">
                <i class="fa-solid fa-bars"></i>
            </button>
        </div>

        <div id="mobile-menu" class="hidden md:hidden bg-cardBg border-b border-slate-800 px-6 py-4 space-y-3">
            <a href="#inicio" class="block text-slate-300 hover:text-accentCyan">Inicio</a>
            <a href="#investigacion" class="block text-slate-300 hover:text-accentCyan">Espectrometría & IA</a>
            <a href="#proyectos" class="block text-slate-300 hover:text-accentCyan">Proyectos Web</a>
            <a href="#contacto" class="block text-accentCyan font-semibold">Contacto</a>
        </div>
    </header>

    <section id="inicio" class="relative pt-32 pb-20 md:pt-44 md:pb-32 overflow-hidden">
        <div class="absolute inset-0 bg-[radial-gradient(ellipse_at_top,_var(--tw-gradient-stops))] from-blue-900/20 via-darkBg to-darkBg pointer-events-none"></div>
        <div class="max-w-7xl mx-auto px-6 relative z-10">
            <div class="max-w-3xl mx-auto text-center space-y-8">
                <div class="inline-flex items-center space-x-2 px-3.5 py-1.5 rounded-full bg-slate-900/80 border border-slate-700/60 text-xs font-semibold text-accentCyan">
                    <span class="flex h-2 w-2 rounded-full bg-accentCyan animate-pulse"></span>
                    <span>Innovación Científica y Desarrollo Tecnológico</span>
                </div>
                
                <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight leading-tight">
                    El futuro de la Espectrometría impulsada por <span class="bg-gradient-to-r from-accentCyan to-accentBlue bg-clip-text text-transparent">Deep Learning</span>
                </h1>
                
                <p class="text-lg sm:text-xl text-slate-400 font-normal leading-relaxed max-w-2xl mx-auto">
                    En <strong>Irving Technology</strong> fusionamos la investigación avanzada en análisis espectral con modelos de aprendizaje profundo y desarrollo web de alto rendimiento.
                </p>
                
                <div class="flex flex-col sm:flex-row items-center justify-center gap-4 pt-4">
                    <a href="#contacto" class="w-full sm:w-auto px-8 py-4 rounded-xl bg-gradient-to-r from-accentCyan to-accentBlue text-darkBg font-bold hover:opacity-90 transition-all shadow-lg shadow-cyan-500/20 text-center">
                        Iniciar Colaboración <i class="fa-solid fa-arrow-right ml-2"></i>
                    </a>
                    <a href="#investigacion" class="w-full sm:w-auto px-8 py-4 rounded-xl bg-slate-900 border border-slate-800 text-slate-200 font-bold hover:bg-slate-800 transition-all text-center">
                        Conocer Investigación
                    </a>
                </div>
            </div>
        </div>
    </section>

    <section id="investigacion" class="py-24 bg-slate-950/50 border-t border-slate-800/50">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center max-w-2xl mx-auto mb-16 space-y-4">
                <h2 class="text-3xl sm:text-4xl font-bold tracking-tight">Investigación & Tecnología</h2>
                <p class="text-slate-400">Soluciones de vanguardia diseñadas para resolver problemas complejos en entornos industriales y científicos.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="p-8 rounded-2xl bg-cardBg border border-slate-800 glow-effect transition-all group">
                    <div class="w-14 h-14 rounded-xl bg-accentCyan/10 text-accentCyan flex items-center justify-center text-2xl mb-6 group-hover:bg-accentCyan group-hover:text-darkBg transition-colors">
                        <i class="fa-solid fa-brain"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Deep Learning Avanzado</h3>
                    <p class="text-slate-400 text-sm leading-relaxed">
                        Implementación de arquitecturas neuronales profundas capaces de identificar patrones ocultos, clasificar datos complejos y optimizar procesos automatizados.
                    </p>
                </div>

                <div class="p-8 rounded-2xl bg-cardBg border border-slate-800 glow-effect transition-all group">
                    <div class="w-14 h-14 rounded-xl bg-accentBlue/10 text-accentBlue flex items-center justify-center text-2xl mb-6 group-hover:bg-accentBlue group-hover:text-white transition-colors">
                        <i class="fa-solid fa-wave-square"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Investigación en Espectrometría</h3>
                    <p class="text-slate-400 text-sm leading-relaxed">
                        Análisis espectral de alta precisión, deconvolución de señales moleculares y modelos predictivos para laboratorios e industria química.
                    </p>
                </div>

                <div class="p-8 rounded-2xl bg-cardBg border border-slate-800 glow-effect transition-all group">
                    <div class="w-14 h-14 rounded-xl bg-purple-500/10 text-purple-400 flex items-center justify-center text-2xl mb-6 group-hover:bg-purple-500 group-hover:text-white transition-colors">
                        <i class="fa-solid fa-code"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Desarrollo Web Tecnológico</h3>
                    <p class="text-slate-400 text-sm leading-relaxed">
                        Creación de plataformas web escalables, paneles de control en tiempo real y arquitecturas backend seguras para procesar flujos masivos de datos.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <section id="proyectos" class="py-24">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center max-w-2xl mx-auto mb-16 space-y-4">
                <h2 class="text-3xl sm:text-4xl font-bold tracking-tight">Nuestros Proyectos Web</h2>
                <p class="text-slate-400">Plataformas interactivas desarrolladas bajo estándares modernos de experiencia de usuario y rendimiento.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="rounded-2xl bg-cardBg border border-slate-800 overflow-hidden group">
                    <div class="h-48 bg-slate-900 relative overflow-hidden flex items-center justify-center border-b border-slate-800">
                        <div class="absolute inset-0 bg-gradient-to-tr from-accentBlue/10 to-transparent"></div>
                        <i class="fa-solid fa-chart-line text-5xl text-slate-700 group-hover:text-accentCyan transition-colors duration-300"></i>
                    </div>
                    <div class="p-8 space-y-4">
                        <div class="flex items-center space-x-2 text-xs font-semibold text-accentCyan">
                            <span class="px-2.5 py-1 rounded-md bg-accentCyan/10">Plataforma Web SaaS</span>
                            <span class="px-2.5 py-1 rounded-md bg-slate-800 text-slate-300">Dashboard Espectral</span>
                        </div>
                        <h3 class="text-xl font-bold">Irving Spectra Analytics</h3>
                        <p class="text-slate-400 text-sm leading-relaxed">
                            Sistema web de visualización de datos espectrales en tiempo real, permitiendo a los investigadores interactuar con gráficos de alta densidad de forma fluida.
                        </p>
                    </div>
                </div>

                <div class="rounded-2xl bg-cardBg border border-slate-800 overflow-hidden group">
                    <div class="h-48 bg-slate-900 relative overflow-hidden flex items-center justify-center border-b border-slate-800">
                        <div class="absolute inset-0 bg-gradient-to-tr from-accentCyan/10 to-transparent"></div>
                        <i class="fa-solid fa-network-wired text-5xl text-slate-700 group-hover:text-accentBlue transition-colors duration-300"></i>
                    </div>
                    <div class="p-8 space-y-4">
                        <div class="flex items-center space-x-2 text-xs font-semibold text-accentBlue">
                            <span class="px-2.5 py-1 rounded-md bg-accentBlue/10">Portal API Cloud</span>
                            <span class="px-2.5 py-1 rounded-md bg-slate-800 text-slate-300">Deep Learning Hub</span>
                        </div>
                        <h3 class="text-xl font-bold">Neural Core Portal</h3>
                        <p class="text-slate-400 text-sm leading-relaxed">
                            Interfaz web conectada a modelos neuronales alojados en la nube para el procesamiento automático de muestras y generación de reportes analíticos.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="contacto" class="py-24 bg-slate-950/50 border-t border-slate-800/50">
        <div class="max-w-7xl mx-auto px-6">
            <div class="max-w-xl mx-auto bg-cardBg border border-slate-800 p-8 sm:p-12 rounded-3xl glow-effect space-y-8">
                <div class="text-center space-y-2">
                    <h2 class="text-2xl sm:text-3xl font-bold tracking-tight">Inicia un Proyecto con Nosotros</h2>
                    <p class="text-slate-400 text-sm">Completa el formulario y nos pondremos en contacto a la brevedad.</p>
                </div>

                <form onsubmit="event.preventDefault(); showSuccess();" class="space-y-6">
                    <div>
                        <label class="block text-xs font-semibold uppercase tracking-wider text-slate-400 mb-2">Nombre</label>
                        <input type="text" required class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-slate-100 focus:outline-none focus:border-accentCyan transition-colors text-sm" placeholder="Tu nombre">
                    </div>
                    <div>
                        <label class="block text-xs font-semibold uppercase tracking-wider text-slate-400 mb-2">Correo Electrónico</label>
                        <input type="email" required class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-slate-100 focus:outline-none focus:border-accentCyan transition-colors text-sm" placeholder="tu@correo.com">
                    </div>
                    <div>
                        <label class="block text-xs font-semibold uppercase tracking-wider text-slate-400 mb-2">Mensaje</label>
                        <textarea rows="4" required class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-slate-100 focus:outline-none focus:border-accentCyan transition-colors text-sm" placeholder="¿Cómo podemos ayudarte en tu startup o investigación?"></textarea>
                    </div>
                    <button type="submit" class="w-full py-4 rounded-xl bg-gradient-to-r from-accentCyan to-accentBlue text-darkBg font-bold hover:opacity-90 transition-all shadow-lg shadow-cyan-500/20 text-sm">
                        Enviar Mensaje
                    </button>
                </form>

                <div id="success-box" class="hidden p-4 rounded-xl bg-cyan-950/50 border border-accentCyan/30 text-accentCyan text-center text-sm">
                    ¡Mensaje enviado con éxito! Irving Technology se comunicará contigo pronto.
                </div>
            </div>
        </div>
    </section>

    <footer class="border-t border-slate-800/80 py-12 bg-darkBg">
        <div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-6 text-sm text-slate-400">
            <div class="flex items-center space-x-3">
                <div class="w-8 h-8 rounded-lg bg-gradient-to-tr from-accentCyan to-accentBlue flex items-center justify-center">
                    <i class="fa-solid fa-microchip text-darkBg text-sm font-bold"></i>
                </div>
                <span class="font-bold text-slate-200">Irving Technology</span>
                <span>&copy; 2026. Todos los derechos reservados.</span>
            </div>
            
            <div class="flex space-x-6 text-lg">
                <a href="#" class="hover:text-accentCyan transition-colors"><i class="fa-brands fa-github"></i></a>
                <a href="#" class="hover:text-accentCyan transition-colors"><i class="fa-brands fa-linkedin"></i></a>
                <a href="#" class="hover:text-accentCyan transition-colors"><i class="fa-brands fa-x-twitter"></i></a>
            </div>
        </div>
    </footer>

    <script>
        const menuBtn = document.getElementById('menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');

        menuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        mobileMenu.querySelectorAll('a').forEach(link => {
            link.addEventListener('click', () => {
                mobileMenu.classList.add('hidden');
            });
        });

        function showSuccess() {
            const box = document.getElementById('success-box');
            box.classList.remove('hidden');
            setTimeout(() => box.classList.add('hidden'), 5000);
        }
    </script>
</body>
</html>