<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ed - TECH | Enterprise Networking, CCNA, Cybersecurity, Linux & AI Learning</title>
    <meta name="description" content="Ed - TECH offers live online classes (₹15,000–₹35,000/month), 15-day free offline classroom demos, and a 24/7 AI Technical Mentor for Networking, Software Testing, CCNA, Cybersecurity, CCVP, CCIP, and Linux. Call 8094161377.">
    <meta name="keywords" content="Ed - TECH, Networking courses, CCNA training, Cybersecurity institute, Linux administration, Software Testing, CCVP, CCIP, 15 days offline demo class, online IT courses">
    <meta name="robots" content="index, follow">
    <meta name="theme-color" content="#070d1f">

    <!-- Open Graph / Google Search Rich Snippet Metadata -->
    <meta property="og:title" content="Ed - TECH | Master Networking, Cybersecurity, CCNA & Linux">
    <meta property="og:description" content="Join live online IT classes, book a 15-day free offline classroom demo, and ask our AI Mentor anything about Networking, Testing, CCNA, Cybersecurity, CCVP, CCIP & Linux.">
    <meta property="og:type" content="website">

    <!-- Schema.org EducationalOrganization Structured Data for Google Indexing -->
    <script type="application/ld+json">
    {
      "@context": "https://schema.org",
      "@type": "EducationalOrganization",
      "name": "Ed - TECH",
      "description": "High-speed technical education platform offering Online Classes, 15-Day Free Offline Classroom Demos, and AI-assisted training in Networking, Software Testing, CCNA, Cybersecurity, CCVP, CCIP, and Linux.",
      "telephone": "+91-8094161377",
      "offers": {
        "@type": "AggregateOffer",
        "priceCurrency": "INR",
        "lowPrice": "15000",
        "highPrice": "35000",
        "offerCount": "3"
      },
      "hasCourse": [
        { "@type": "Course", "name": "Enterprise Networking" },
        { "@type": "Course", "name": "Software Testing & QA Automation" },
        { "@type": "Course", "name": "Cisco CCNA Certification" },
        { "@type": "Course", "name": "Cybersecurity & Ethical Hacking" },
        { "@type": "Course", "name": "Cisco CCVP Voice & Collaboration" },
        { "@type": "Course", "name": "Cisco CCIP Service Provider" },
        { "@type": "Course", "name": "Linux System Administration" }
      ]
    }
    </script>

    <!-- Google Fonts: Inter & JetBrains Mono -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=JetBrains+Mono:wght@400;500;600&display=swap" rel="stylesheet">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                        mono: ['JetBrains Mono', 'monospace'],
                    },
                    colors: {
                        navy: {
                            950: '#060a16',
                            900: '#0b1226',
                            800: '#121d3d',
                        },
                        skybrand: {
                            400: '#38bdf8',
                            500: '#0ea5e9',
                            600: '#0284c7',
                        }
                    },
                    boxShadow: {
                        'pill': '0 12px 32px -4px rgba(6, 10, 22, 0.25)',
                        'dashboard': '0 28px 70px -12px rgba(6, 10, 22, 0.32)',
                        'card': '0 10px 30px -5px rgba(15, 23, 42, 0.06)',
                    }
                }
            }
        }
    </script>

    <style>
        /* High-speed CSS variables & custom circuit/gradient styling inspired by reference visuals */
        .hero-bg {
            background: radial-gradient(circle at 75% 25%, rgba(14, 165, 233, 0.35) 0%, rgba(2, 132, 199, 0.15) 35%, transparent 65%),
                        linear-gradient(155deg, #060a16 0%, #0b1633 48%, #0284c7 100%);
        }

        .circuit-grid {
            background-image: 
                radial-gradient(rgba(56, 189, 248, 0.22) 1.25px, transparent 1.25px),
                linear-gradient(to right, rgba(56, 189, 248, 0.06) 1px, transparent 1px),
                linear-gradient(to bottom, rgba(56, 189, 248, 0.06) 1px, transparent 1px);
            background-size: 36px 36px, 72px 72px, 72px 72px;
        }

        @keyframes pulseGlow {
            0%, 100% { opacity: 0.65; transform: scale(1); }
            50% { opacity: 1; transform: scale(1.04); }
        }

        .glow-orb {
            animation: pulseGlow 6s ease-in-out infinite;
        }

        /* Custom sleek scrollbar for AI chat & code blocks */
        .chat-scroll::-webkit-scrollbar {
            width: 6px;
        }
        .chat-scroll::-webkit-scrollbar-track {
            background: transparent;
        }
        .chat-scroll::-webkit-scrollbar-thumb {
            background: #cbd5e1;
            border-radius: 9999px;
        }
        .chat-scroll::-webkit-scrollbar-thumb:hover {
            background: #94a3b8;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-900 font-sans antialiased selection:bg-sky-500 selection:text-white overflow-x-hidden">

    <!-- ==================== FLOATING PILL HEADER & NAVIGATION ==================== -->
    <header class="fixed top-4 inset-x-0 z-50 px-3 sm:px-6 transition-all duration-300">
        <nav aria-label="Primary Navigation" class="max-w-6xl mx-auto bg-white/95 backdrop-blur-md border border-slate-200/80 rounded-full shadow-pill px-4 sm:px-6 py-2.5 flex items-center justify-between">
            
            <!-- Brand Logo -->
            <a href="#" class="flex items-center gap-2.5 group focus:outline-none">
                <div class="w-9 h-9 rounded-full bg-gradient-to-tr from-navy-900 to-sky-500 flex items-center justify-center text-white font-extrabold text-sm shadow-sm group-hover:scale-105 transition-transform">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 3v1.5M4.5 8.25H3m18 0h-1.5M4.5 12H3m18 0h-1.5m-15 3.75H3m18 0h-1.5M8.25 19.5V21M12 3v1.5m0 15V21m3.75-18v1.5m0 15V21m-9-1.5h10.5a2.25 2.25 0 002.25-2.25V6.75a2.25 2.25 0 00-2.25-2.25H6.75A2.25 2.25 0 004.5 6.75v10.5a2.25 2.25 0 002.25 2.25zm.75-12h9v9h-9v-9z" />
                    </svg>
                </div>
                <div class="flex flex-col">
                    <span class="font-extrabold text-base sm:text-lg tracking-tight text-navy-950 leading-none">Ed - <span class="text-sky-600">TECH</span></span>
                    <span class="text-[10px] font-medium text-slate-500 tracking-wider uppercase hidden sm:inline">IT & Cloud Academy</span>
                </div>
            </a>

            <!-- Desktop Navigation Links -->
            <div class="hidden lg:flex items-center gap-7 text-sm font-medium text-slate-600">
                <a href="#courses" class="hover:text-sky-600 transition-colors">Courses</a>
                <a href="#offline-demo" class="hover:text-sky-600 transition-colors flex items-center gap-1.5">
                    <span>15-Day Offline Demo</span>
                    <span class="px-1.5 py-0.5 text-[10px] font-bold bg-emerald-100 text-emerald-700 rounded-full">FREE</span>
                </a>
                <a href="#ai-mentor" class="hover:text-sky-600 transition-colors">AI Mentor</a>
                <a href="#pricing" class="hover:text-sky-600 transition-colors">Pricing</a>
                <a href="#support" class="hover:text-sky-600 transition-colors">Support</a>
            </div>

            <!-- Right Actions: Support Phone & Mobile Menu Toggle -->
            <div class="flex items-center gap-2 sm:gap-3">
                <a href="tel:8094161377" class="hidden sm:inline-flex items-center gap-2 px-3.5 py-2 rounded-full bg-slate-100 hover:bg-sky-50 text-slate-800 hover:text-sky-700 text-xs font-semibold transition-colors border border-slate-200/80" title="Call Ed - TECH Online Support">
                    <span class="w-2 h-2 rounded-full bg-emerald-500 animate-pulse"></span>
                    <span>8094161377</span>
                </a>

                <a href="#offline-demo" class="px-4 sm:px-5 py-2 rounded-full bg-navy-950 hover:bg-sky-600 text-white text-xs sm:text-sm font-semibold transition-all shadow-sm">
                    Book Demo
                </a>

                <!-- Mobile Hamburger Button -->
                <button id="mobile-menu-btn" type="button" aria-label="Toggle Menu" class="lg:hidden p-2 rounded-full text-slate-700 hover:bg-slate-100 focus:outline-none">
                    <svg class="w-5 h-5" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" d="M4 6h16M4 12h16M4 18h16" />
                    </svg>
                </button>
            </div>
        </nav>

        <!-- Mobile Dropdown Drawer -->
        <div id="mobile-menu" class="hidden lg:hidden max-w-6xl mx-auto mt-2 bg-white rounded-3xl shadow-xl border border-slate-200 p-5 space-y-3">
            <a href="#courses" class="block px-4 py-2.5 rounded-xl text-sm font-semibold text-slate-700 hover:bg-slate-50">Courses (Networking, CCNA, Cyber, Linux...)</a>
            <a href="#offline-demo" class="block px-4 py-2.5 rounded-xl text-sm font-semibold text-emerald-700 bg-emerald-50/70">15-Day Free Offline Class Demo</a>
            <a href="#ai-mentor" class="block px-4 py-2.5 rounded-xl text-sm font-semibold text-slate-700 hover:bg-slate-50">Ed-TECH AI Technical Mentor</a>
            <a href="#pricing" class="block px-4 py-2.5 rounded-xl text-sm font-semibold text-slate-700 hover:bg-slate-50">Online Subscription Plans (₹15k–₹35k/mo)</a>
            <div class="pt-2 border-t border-slate-100 flex items-center justify-between px-2">
                <span class="text-xs text-slate-500 font-medium">24/7 Support Line:</span>
                <a href="tel:8094161377" class="inline-flex items-center gap-1.5 text-sm font-bold text-sky-600">
                    <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z"/></svg>
                    8094161377
                </a>
            </div>
        </div>
    </header>

    <!-- ==================== HERO SECTION & FLOATING SAAS DASHBOARD ==================== -->
    <section class="relative hero-bg pt-28 sm:pt-36 pb-12 text-white overflow-hidden">
        <!-- Circuit Grid & Glowing Accents (Inspired by Reference #3 & #1) -->
        <div class="absolute inset-0 circuit-grid pointer-events-none"></div>
        <div class="glow-orb absolute -top-24 -right-24 w-96 h-96 bg-sky-400/20 rounded-full blur-3xl pointer-events-none"></div>
        <div class="glow-orb absolute top-1/3 -left-24 w-80 h-80 bg-blue-600/25 rounded-full blur-3xl pointer-events-none"></div>

        <!-- Decorative Circuit SVG Nodes on Right -->
        <svg class="hidden xl:block absolute right-8 top-32 w-72 h-72 text-sky-400/25 pointer-events-none" viewBox="0 0 200 200" fill="none">
            <rect x="65" y="65" width="70" height="70" rx="14" stroke="currentColor" stroke-width="2"/>
            <rect x="78" y="78" width="44" height="44" rx="8" stroke="currentColor" stroke-width="1.5" stroke-dasharray="4 4"/>
            <path d="M100 20V65M100 135V180M20 100H65M135 100H180M45 45L68 68M132 132L155 155M155 45L132 68M68 132L45 155" stroke="currentColor" stroke-width="1.5"/>
            <circle cx="100" cy="20" r="4" fill="currentColor"/>
            <circle cx="100" cy="180" r="4" fill="currentColor"/>
            <circle cx="20" cy="100" r="4" fill="currentColor"/>
            <circle cx="180" cy="100" r="4" fill="currentColor"/>
        </svg>

        <div class="relative max-w-6xl mx-auto px-4 sm:px-6 text-center">
            <!-- Top Social Proof Pill -->
            <div class="inline-flex items-center gap-2.5 px-4 py-1.5 rounded-full bg-white/10 backdrop-blur-md border border-white/15 text-xs sm:text-sm font-medium text-sky-100 mb-6">
                <span class="flex -space-x-2">
                    <span class="w-6 h-6 rounded-full bg-sky-500 border-2 border-navy-900 flex items-center justify-center text-[10px] font-bold">CC</span>
                    <span class="w-6 h-6 rounded-full bg-indigo-500 border-2 border-navy-900 flex items-center justify-center text-[10px] font-bold">LX</span>
                    <span class="w-6 h-6 rounded-full bg-emerald-500 border-2 border-navy-900 flex items-center justify-center text-[10px] font-bold">AI</span>
                </span>
                <span>4,200+ Network & Security Engineers Trained • 15-Day Free Offline Demo</span>
            </div>

            <!-- Hero Headline -->
            <h1 class="text-3xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight leading-[1.12] max-w-4xl mx-auto">
                Master Enterprise <span class="text-transparent bg-clip-text bg-gradient-to-r from-sky-300 via-cyan-200 to-white">Networking, Cybersecurity</span> & Cloud Infrastructure
            </h1>

            <!-- Hero Subheadline -->
            <p class="mt-5 text-base sm:text-lg text-slate-200/90 max-w-2xl mx-auto leading-relaxed">
                Access live interactive online classes (<strong class="text-white">₹15,000–₹35,000/mo</strong>), test-drive physical hardware racks with our <strong class="text-sky-300">15-Day Free Offline Class Demo</strong>, and get instant answers from our specialized <strong class="text-white">Ed - TECH AI Mentor</strong>.
            </p>

            <!-- Dual Hero CTAs (Inspired by Reference #1 & #2) -->
            <div class="mt-8 flex flex-col sm:flex-row items-center justify-center gap-3.5 sm:gap-4">
                <a href="#offline-demo" class="w-full sm:w-auto px-7 py-3.5 rounded-full bg-white text-navy-950 hover:bg-sky-50 font-bold text-sm sm:text-base shadow-lg transition-all flex items-center justify-center gap-2">
                    <span>Book 15-Day Free Offline Demo</span>
                    <svg class="w-4 h-4 text-sky-600" fill="none" stroke="currentColor" stroke-width="2.5" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M13.5 4.5L21 12m0 0l-7.5 7.5M21 12H3"/></svg>
                </a>
                <a href="#ai-mentor" class="w-full sm:w-auto px-7 py-3.5 rounded-full bg-navy-950/75 hover:bg-navy-950 text-white border border-white/25 backdrop-blur-md font-semibold text-sm sm:text-base transition-all flex items-center justify-center gap-2">
                    <span class="w-2 h-2 rounded-full bg-sky-400 animate-ping"></span>
                    <span>Ask Ed - TECH AI Mentor</span>
                </a>
            </div>

            <!-- ==================== OVERLAPPING FLOATING SAAS DASHBOARD UI PREVIEW ==================== -->
            <div class="mt-12 sm:mt-16 max-w-5xl mx-auto text-left relative z-20">
                <div class="bg-white rounded-3xl shadow-dashboard border border-slate-200/90 overflow-hidden text-slate-800">
                    <!-- Dashboard Window Top Bar -->
                    <div class="bg-slate-50/90 border-b border-slate-200/80 px-4 sm:px-6 py-3.5 flex flex-wrap items-center justify-between gap-3">
                        <div class="flex items-center gap-3">
                            <div class="flex items-center gap-1.5">
                                <span class="w-3 h-3 rounded-full bg-rose-400"></span>
                                <span class="w-3 h-3 rounded-full bg-amber-400"></span>
                                <span class="w-3 h-3 rounded-full bg-emerald-400"></span>
                            </div>
                            <span class="h-4 w-px bg-slate-200"></span>
                            <span class="text-xs font-bold text-navy-950 tracking-tight">Ed - TECH Cloud Lab & Learning Console</span>
                        </div>

                        <!-- Interactive Quick AI Input inside Dashboard Preview -->
                        <div class="flex-1 max-w-md hidden md:flex items-center bg-white border border-slate-200 rounded-full px-3.5 py-1.5 text-xs">
                            <svg class="w-3.5 h-3.5 text-sky-500 mr-2 shrink-0" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M21 21l-5.197-5.197m0 0A7.5 7.5 0 105.196 5.196a7.5 7.5 0 0010.607 10.607z"/></svg>
                            <input id="hero-quick-ai-input" type="text" placeholder="Quick ask AI: e.g. What is BGP in CCIP or Linux chmod?" class="w-full bg-transparent focus:outline-none text-slate-700 placeholder-slate-400">
                            <button onclick="sendFromHeroDashboard()" class="ml-2 px-2.5 py-0.5 rounded-full bg-sky-600 text-white font-semibold hover:bg-sky-700 transition-colors">Ask</button>
                        </div>

                        <div class="flex items-center gap-2 text-xs">
                            <span class="px-2.5 py-1 rounded-full bg-emerald-50 text-emerald-700 font-semibold border border-emerald-200/70">● Live Rack Online</span>
                            <a href="tel:8094161377" class="px-2.5 py-1 rounded-full bg-sky-50 text-sky-700 font-semibold hover:bg-sky-100 transition-colors">Help: 8094161377</a>
                        </div>
                    </div>

                    <!-- Dashboard Body Grid -->
                    <div class="grid grid-cols-1 lg:grid-cols-12">
                        <!-- Left Sidebar (Mimicking Reference #1 & #2) -->
                        <div class="hidden lg:flex lg:col-span-3 bg-slate-50/60 border-r border-slate-100 p-5 flex-col justify-between">
                            <div class="space-y-1.5">
                                <div class="text-[11px] font-bold uppercase tracking-wider text-slate-400 px-3 mb-2">Tracks & Labs</div>
                                <a href="#courses" class="flex items-center justify-between px-3 py-2 rounded-xl bg-sky-600 text-white text-xs font-semibold shadow-sm">
                                    <span>Active Curriculum</span>
                                    <span class="bg-white/20 px-1.5 py-0.5 rounded-md text-[10px]">7</span>
                                </a>
                                <a href="#offline-demo" class="flex items-center justify-between px-3 py-2 rounded-xl text-slate-600 hover:bg-slate-100 text-xs font-medium">
                                    <span>15-Day Offline Lab</span>
                                    <span class="text-emerald-600 font-bold text-[10px]">OPEN</span>
                                </a>
                                <a href="#ai-mentor" class="flex items-center justify-between px-3 py-2 rounded-xl text-slate-600 hover:bg-slate-100 text-xs font-medium">
                                    <span>AI Packet Mentor</span>
                                    <span class="text-sky-600 font-bold text-[10px]">24/7</span>
                                </a>
                                <a href="#pricing" class="flex items-center justify-between px-3 py-2 rounded-xl text-slate-600 hover:bg-slate-100 text-xs font-medium">
                                    <span>Subscriptions</span>
                                    <span class="text-slate-400 text-[10px]">₹15k+</span>
                                </a>
                            </div>

                            <!-- Upgrade / Demo Card inside Sidebar -->
                            <div class="mt-6 p-4 rounded-2xl bg-gradient-to-br from-navy-900 to-sky-700 text-white">
                                <div class="text-xs font-bold">15-Day Offline Trial</div>
                                <p class="text-[11px] text-sky-100 mt-1 leading-relaxed">Experience real Cisco routers, firewalls & Linux servers free for 15 days.</p>
                                <a href="#offline-demo" class="mt-3 block text-center py-1.5 rounded-xl bg-white text-navy-950 text-xs font-bold hover:bg-sky-50 transition-colors">Reserve Seat</a>
                            </div>
                        </div>

                        <!-- Main Dashboard Metrics & Live Course Telemetry -->
                        <div class="lg:col-span-9 p-5 sm:p-6 space-y-5">
                            <!-- Top 4 KPI Cards -->
                            <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 sm:gap-4">
                                <div class="p-3.5 rounded-2xl bg-slate-50 border border-slate-100">
                                    <div class="text-[11px] font-medium text-slate-500">Core Specializations</div>
                                    <div class="mt-1 flex items-baseline justify-between">
                                        <span class="text-xl sm:text-2xl font-extrabold text-navy-950">7 Tracks</span>
                                        <span class="text-[11px] font-semibold text-emerald-600">CCNA–CCIP</span>
                                    </div>
                                </div>
                                <div class="p-3.5 rounded-2xl bg-slate-50 border border-slate-100">
                                    <div class="text-[11px] font-medium text-slate-500">Offline Class Demo</div>
                                    <div class="mt-1 flex items-baseline justify-between">
                                        <span class="text-xl sm:text-2xl font-extrabold text-sky-600">15 Days</span>
                                        <span class="text-[11px] font-semibold text-emerald-600">₹0 Free</span>
                                    </div>
                                </div>
                                <div class="p-3.5 rounded-2xl bg-slate-50 border border-slate-100">
                                    <div class="text-[11px] font-medium text-slate-500">Online Subscription</div>
                                    <div class="mt-1 flex items-baseline justify-between">
                                        <span class="text-lg sm:text-xl font-extrabold text-navy-950">₹15k–35k</span>
                                        <span class="text-[11px] font-medium text-slate-500">/month</span>
                                    </div>
                                </div>
                                <div class="p-3.5 rounded-2xl bg-slate-50 border border-slate-100">
                                    <div class="text-[11px] font-medium text-slate-500">Lab Uptime & AI</div>
                                    <div class="mt-1 flex items-baseline justify-between">
                                        <span class="text-xl sm:text-2xl font-extrabold text-emerald-600">99.9%</span>
                                        <span class="text-[11px] font-semibold text-sky-600">Instant</span>
                                    </div>
                                </div>
                            </div>

                            <!-- Bottom Split: Live Course Status & Weekly Lab Activity Chart -->
                            <div class="grid grid-cols-1 md:grid-cols-12 gap-4">
                                <!-- Active Tracks Table -->
                                <div class="md:col-span-7 p-4 rounded-2xl border border-slate-100 bg-white">
                                    <div class="flex items-center justify-between mb-3">
                                        <h2 class="text-xs font-bold uppercase tracking-wider text-slate-500">Live & Offline Cohort Status</h2>
                                        <span class="text-[11px] font-semibold text-sky-600">Updated Live</span>
                                    </div>
                                    <div class="space-y-2.5 text-xs">
                                        <div class="flex items-center justify-between p-2 rounded-xl bg-slate-50">
                                            <div class="flex items-center gap-2.5">
                                                <span class="w-7 h-7 rounded-lg bg-sky-100 text-sky-700 font-bold flex items-center justify-center">CN</span>
                                                <div>
                                                    <div class="font-bold text-slate-800">CCNA & Enterprise Networking</div>
                                                    <div class="text-[11px] text-slate-500">OSPF, BGP, VLANs, Switching</div>
                                                </div>
                                            </div>
                                            <span class="px-2 py-0.5 rounded-full bg-emerald-100 text-emerald-700 font-semibold text-[10px]">15-Day Demo</span>
                                        </div>
                                        <div class="flex items-center justify-between p-2 rounded-xl bg-slate-50">
                                            <div class="flex items-center gap-2.5">
                                                <span class="w-7 h-7 rounded-lg bg-indigo-100 text-indigo-700 font-bold flex items-center justify-center">CS</span>
                                                <div>
                                                    <div class="font-bold text-slate-800">Cybersecurity & Linux Hardening</div>
                                                    <div class="text-[11px] text-slate-500">SOC, Firewalls, Bash, Pen-Testing</div>
                                                </div>
                                            </div>
                                            <span class="px-2 py-0.5 rounded-full bg-sky-100 text-sky-700 font-semibold text-[10px]">Online Live</span>
                                        </div>
                                        <div class="flex items-center justify-between p-2 rounded-xl bg-slate-50">
                                            <div class="flex items-center gap-2.5">
                                                <span class="w-7 h-7 rounded-lg bg-amber-100 text-amber-700 font-bold flex items-center justify-center">CV</span>
                                                <div>
                                                    <div class="font-bold text-slate-800">CCVP, CCIP & Software Testing</div>
                                                    <div class="text-[11px] text-slate-500">VoIP, MPLS Core, Selenium QA</div>
                                                </div>
                                            </div>
                                            <span class="px-2 py-0.5 rounded-full bg-purple-100 text-purple-700 font-semibold text-[10px]">Pro Track</span>
                                        </div>
                                    </div>
                                </div>

                                <!-- Lab Utilization Bar Visual (Inspired by Reference #1 & #2 Charts) -->
                                <div class="md:col-span-5 p-4 rounded-2xl border border-slate-100 bg-white flex flex-col justify-between">
                                    <div>
                                        <div class="flex items-center justify-between">
                                            <h2 class="text-xs font-bold uppercase tracking-wider text-slate-500">Practical Lab Ratio</h2>
                                            <span class="text-xs font-extrabold text-sky-600">85% Hands-On</span>
                                        </div>
                                        <p class="text-[11px] text-slate-400 mt-0.5">Router racks, Linux VMs & QA test suites</p>
                                    </div>

                                    <!-- Clean Visual Bar Chart -->
                                    <div class="mt-4 flex items-end justify-between gap-2 h-28 pt-4 px-1">
                                        <div class="flex-1 flex flex-col items-center gap-1">
                                            <div class="w-full bg-sky-100 rounded-t-lg h-16 relative overflow-hidden">
                                                <div class="absolute bottom-0 inset-x-0 bg-sky-500 h-12 rounded-t-lg"></div>
                                            </div>
                                            <span class="text-[10px] font-semibold text-slate-500">Net</span>
                                        </div>
                                        <div class="flex-1 flex flex-col items-center gap-1">
                                            <div class="w-full bg-sky-100 rounded-t-lg h-20 relative overflow-hidden">
                                                <div class="absolute bottom-0 inset-x-0 bg-navy-900 h-16 rounded-t-lg"></div>
                                            </div>
                                            <span class="text-[10px] font-semibold text-slate-500">CCNA</span>
                                        </div>
                                        <div class="flex-1 flex flex-col items-center gap-1">
                                            <div class="w-full bg-sky-100 rounded-t-lg h-24 relative overflow-hidden">
                                                <div class="absolute bottom-0 inset-x-0 bg-sky-500 h-20 rounded-t-lg"></div>
                                            </div>
                                            <span class="text-[10px] font-semibold text-slate-500">Cyber</span>
                                        </div>
                                        <div class="flex-1 flex flex-col items-center gap-1">
                                            <div class="w-full bg-sky-100 rounded-t-lg h-20 relative overflow-hidden">
                                                <div class="absolute bottom-0 inset-x-0 bg-indigo-500 h-16 rounded-t-lg"></div>
                                            </div>
                                            <span class="text-[10px] font-semibold text-slate-500">Linux</span>
                                        </div>
                                        <div class="flex-1 flex flex-col items-center gap-1">
                                            <div class="w-full bg-sky-100 rounded-t-lg h-16 relative overflow-hidden">
                                                <div class="absolute bottom-0 inset-x-0 bg-emerald-500 h-14 rounded-t-lg"></div>
                                            </div>
                                            <span class="text-[10px] font-semibold text-slate-500">QA</span>
                                        </div>
                                        <div class="flex-1 flex flex-col items-center gap-1">
                                            <div class="w-full bg-sky-100 rounded-t-lg h-20 relative overflow-hidden">
                                                <div class="absolute bottom-0 inset-x-0 bg-sky-600 h-16 rounded-t-lg"></div>
                                            </div>
                                            <span class="text-[10px] font-semibold text-slate-500">CCIP</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Smooth Curved Wave Transition (Inspired by Reference #3) -->
        <div class="relative mt-8 -mb-12 pointer-events-none">
            <svg viewBox="0 0 1440 90" fill="none" xmlns="http://www.w3.org/2000/svg" class="w-full h-12 sm:h-20 preserve-3d">
                <path d="M0 45C320 95 540 -10 880 35C1160 72 1320 55 1440 30V90H0V45Z" fill="#f8fafc"/>
            </svg>
        </div>
    </section>

    <!-- ==================== TRUSTED PROTOCOLS & TECH STACK STRIP ==================== -->
    <section class="pt-10 pb-8 bg-slate-50 border-b border-slate-200/60">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 text-center">
            <p class="text-xs font-bold uppercase tracking-widest text-slate-400 mb-5">Industry-Aligned Labs & Certifications Covered at Ed - TECH</p>
            <div class="flex flex-wrap items-center justify-center gap-6 sm:gap-12 text-slate-500 font-bold text-sm sm:text-base">
                <span class="flex items-center gap-2"><span class="w-2 h-2 rounded-full bg-sky-500"></span>CISCO CCNA / CCVP / CCIP</span>
                <span class="flex items-center gap-2"><span class="w-2 h-2 rounded-full bg-emerald-500"></span>RED HAT & UBUNTU LINUX</span>
                <span class="flex items-center gap-2"><span class="w-2 h-2 rounded-full bg-indigo-500"></span>SOC & CYBERSECURITY</span>
                <span class="flex items-center gap-2"><span class="w-2 h-2 rounded-full bg-amber-500"></span>AUTOMATION & MANUAL TESTING</span>
                <span class="flex items-center gap-2"><span class="w-2 h-2 rounded-full bg-rose-500"></span>ENTERPRISE NETWORKING</span>
            </div>
        </div>
    </section>

    <!-- ==================== CORE SPECIALIZATION TRACKS (ALL 7 DOMAINS) ==================== -->
    <section id="courses" class="py-16 sm:py-24 bg-slate-50">
        <div class="max-w-6xl mx-auto px-4 sm:px-6">
            <div class="text-center max-w-3xl mx-auto">
                <span class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full bg-sky-100 text-sky-700 text-xs font-bold uppercase tracking-wider">
                    ★ Career-Ready Tracks
                </span>
                <h2 class="mt-3 text-3xl sm:text-4xl font-extrabold text-navy-950 tracking-tight">
                    Specialized Online & Offline Courses
                </h2>
                <p class="mt-3 text-slate-600 text-sm sm:text-base">
                    Every course includes live instructor-led online classes, a <strong>15-day free offline classroom demo</strong>, and 24/7 AI technical troubleshooting.
                </p>
            </div>

            <!-- Interactive Category Filter Pills -->
            <div class="mt-8 flex flex-wrap items-center justify-center gap-2" id="course-filters">
                <button data-filter="all" class="filter-btn active px-4 py-2 rounded-full text-xs sm:text-sm font-semibold bg-navy-950 text-white shadow-sm transition-all">All 7 Tracks</button>
                <button data-filter="cisco" class="filter-btn px-4 py-2 rounded-full text-xs sm:text-sm font-semibold bg-white text-slate-600 hover:bg-slate-100 border border-slate-200 transition-all">Cisco (CCNA, CCVP, CCIP)</button>
                <button data-filter="security" class="filter-btn px-4 py-2 rounded-full text-xs sm:text-sm font-semibold bg-white text-slate-600 hover:bg-slate-100 border border-slate-200 transition-all">Cybersecurity & Linux</button>
                <button data-filter="qa" class="filter-btn px-4 py-2 rounded-full text-xs sm:text-sm font-semibold bg-white text-slate-600 hover:bg-slate-100 border border-slate-200 transition-all">Networking & Testing</button>
            </div>

            <!-- Course Cards Grid -->
            <div id="courses-grid" class="mt-10 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Cards populated dynamically by clean JS for speed & maintainability -->
            </div>
        </div>
    </section>

    <!-- ==================== 15-DAY FREE OFFLINE CLASS DEMO SECTION ==================== -->
    <section id="offline-demo" class="py-16 sm:py-24 bg-white border-y border-slate-200/70">
        <div class="max-w-6xl mx-auto px-4 sm:px-6">
            <div class="rounded-3xl bg-gradient-to-br from-navy-950 via-navy-900 to-sky-900 text-white p-6 sm:p-10 lg:p-12 shadow-xl relative overflow-hidden">
                <div class="absolute inset-0 circuit-grid opacity-40 pointer-events-none"></div>

                <div class="relative grid grid-cols-1 lg:grid-cols-12 gap-8 lg:gap-12 items-center">
                    <!-- Left Info Column -->
                    <div class="lg:col-span-6 space-y-5">
                        <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-emerald-500/20 border border-emerald-400/30 text-emerald-300 text-xs font-bold uppercase tracking-wider">
                            Zero-Risk Classroom Experience
                        </div>
                        <h2 class="text-3xl sm:text-4xl font-extrabold tracking-tight leading-tight">
                            Try Our Offline Classes Free for <span class="text-sky-300">15 Full Days</span>
                        </h2>
                        <p class="text-slate-300 text-sm sm:text-base leading-relaxed">
                            Experience our physical hardware labs, configure live Cisco routers & switches, test Linux servers, and attend in-person mentor sessions for 15 days before committing to any plan.
                        </p>

                        <ul class="space-y-3 text-sm text-slate-200 pt-2">
                            <li class="flex items-start gap-3">
                                <span class="w-5 h-5 rounded-full bg-sky-500/30 text-sky-300 flex items-center justify-center shrink-0 mt-0.5 font-bold text-xs">✓</span>
                                <span><strong>15 Days Physical Lab Access:</strong> Hands-on practice on enterprise routers, firewalls, VoIP gateways, and Linux workstations.</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <span class="w-5 h-5 rounded-full bg-sky-500/30 text-sky-300 flex items-center justify-center shrink-0 mt-0.5 font-bold text-xs">✓</span>
                                <span><strong>All 7 Tracks Eligible:</strong> Networking, Testing, CCNA, Cybersecurity, CCVP, CCIP, and Linux.</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <span class="w-5 h-5 rounded-full bg-sky-500/30 text-sky-300 flex items-center justify-center shrink-0 mt-0.5 font-bold text-xs">✓</span>
                                <span><strong>Direct Support Desk:</strong> Need batch timings or campus directions? Call <a href="tel:8094161377" class="underline font-bold text-sky-300 hover:text-white">8094161377</a>.</span>
                            </li>
                        </ul>
                    </div>

                    <!-- Right Interactive Demo Booking Card -->
                    <div class="lg:col-span-6">
                        <div class="bg-white text-slate-900 rounded-3xl p-6 sm:p-8 shadow-2xl">
                            <h3 class="text-xl font-extrabold text-navy-950">Reserve Your 15-Day Offline Demo</h3>
                            <p class="text-xs text-slate-500 mt-1">Instant seat confirmation • No upfront fee required</p>

                            <form id="demo-booking-form" class="mt-5 space-y-4">
                                <div>
                                    <label for="demo-name" class="block text-xs font-bold text-slate-700 mb-1">Full Name</label>
                                    <input id="demo-name" type="text" required placeholder="e.g. Aarav Sharma" class="w-full px-4 py-2.5 rounded-xl border border-slate-200 text-sm focus:outline-none focus:ring-2 focus:ring-sky-500">
                                </div>

                                <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                    <div>
                                        <label for="demo-phone" class="block text-xs font-bold text-slate-700 mb-1">Mobile Number</label>
                                        <input id="demo-phone" type="tel" required placeholder="+91 98765 43210" class="w-full px-4 py-2.5 rounded-xl border border-slate-200 text-sm focus:outline-none focus:ring-2 focus:ring-sky-500">
                                    </div>
                                    <div>
                                        <label for="demo-track" class="block text-xs font-bold text-slate-700 mb-1">Select Course Track</label>
                                        <select id="demo-track" class="w-full px-4 py-2.5 rounded-xl border border-slate-200 text-sm bg-white focus:outline-none focus:ring-2 focus:ring-sky-500">
                                            <option value="CCNA">CCNA (Routing & Switching)</option>
                                            <option value="Networking">Enterprise Networking</option>
                                            <option value="Cybersecurity">Cybersecurity & SOC</option>
                                            <option value="Linux">Linux Administration</option>
                                            <option value="Software Testing">Software Testing (Manual & Auto)</option>
                                            <option value="CCVP">CCVP (Voice & Collaboration)</option>
                                            <option value="CCIP">CCIP (Service Provider)</option>
                                        </select>
                                    </div>
                                </div>

                                <div>
                                    <label for="demo-batch" class="block text-xs font-bold text-slate-700 mb-1">Preferred Offline Batch Timing</label>
                                    <select id="demo-batch" class="w-full px-4 py-2.5 rounded-xl border border-slate-200 text-sm bg-white focus:outline-none focus:ring-2 focus:ring-sky-500">
                                        <option value="Morning Batch (9:00 AM - 11:30 AM)">Morning Batch (9:00 AM – 11:30 AM)</option>
                                        <option value="Afternoon Batch (2:00 PM - 4:30 PM)">Afternoon Batch (2:00 PM – 4:30 PM)</option>
                                        <option value="Evening Batch (6:00 PM - 8:30 PM)">Evening Batch (6:00 PM – 8:30 PM)</option>
                                        <option value="Weekend Intensive Lab">Weekend Intensive Lab (Sat & Sun)</option>
                                    </select>
                                </div>

                                <button type="submit" class="w-full py-3 rounded-xl bg-sky-600 hover:bg-sky-700 text-white font-bold text-sm shadow-md transition-all">
                                    Confirm 15-Day Free Offline Demo Pass
                                </button>
                            </form>

                            <!-- Confirmation Banner (Hidden until submitted) -->
                            <div id="demo-confirmation" class="hidden mt-4 p-4 rounded-2xl bg-emerald-50 border border-emerald-200 text-emerald-900 text-xs space-y-1.5">
                                <div class="font-extrabold text-sm flex items-center gap-1.5">
                                    <span>✅ 15-Day Offline Demo Pass Reserved!</span>
                                </div>
                                <p id="demo-confirmation-text" class="leading-relaxed"></p>
                                <p class="font-semibold pt-1">Coordinator Helpline: <a href="tel:8094161377" class="underline text-emerald-700">8094161377</a></p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== ED - TECH AI TECHNICAL MENTOR (GEMINI API) ==================== -->
    <section id="ai-mentor" class="py-16 sm:py-24 bg-slate-50">
        <div class="max-w-5xl mx-auto px-4 sm:px-6">
            <div class="text-center max-w-3xl mx-auto">
                <span class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full bg-indigo-100 text-indigo-700 text-xs font-bold uppercase tracking-wider">
                    ⚡ Powered by Ed - TECH Neural Engine
                </span>
                <h2 class="mt-3 text-3xl sm:text-4xl font-extrabold text-navy-950 tracking-tight">
                    24/7 AI Technical Mentor
                </h2>
                <p class="mt-3 text-slate-600 text-sm sm:text-base">
                    Ask any technical question, CLI command, subnetting problem, or interview prep query across <strong>Networking, Testing, CCNA, Cybersecurity, CCVP, CCIP, and Linux</strong>.
                </p>
            </div>

            <!-- AI Chat Container -->
            <div class="mt-10 bg-white rounded-3xl shadow-card border border-slate-200/90 overflow-hidden">
                <!-- AI Top Header -->
                <div class="bg-navy-950 text-white px-5 sm:px-6 py-4 flex flex-wrap items-center justify-between gap-3">
                    <div class="flex items-center gap-3">
                        <div class="w-10 h-10 rounded-2xl bg-gradient-to-tr from-sky-500 to-indigo-500 flex items-center justify-center font-bold text-white shadow-sm">
                            AI
                        </div>
                        <div>
                            <div class="font-bold text-sm sm:text-base flex items-center gap-2">
                                <span>Ed - TECH Specialist AI</span>
                                <span class="px-2 py-0.5 text-[10px] rounded-full bg-emerald-500/20 text-emerald-300 border border-emerald-400/30">ONLINE</span>
                            </div>
                            <div class="text-xs text-slate-400">Trained on Networking • Testing • CCNA • Cybersecurity • CCVP • CCIP • Linux</div>
                        </div>
                    </div>
                    <button id="clear-chat-btn" type="button" class="text-xs text-slate-300 hover:text-white px-3 py-1.5 rounded-full bg-white/10 hover:bg-white/15 transition-colors">
                        Reset Chat
                    </button>
                </div>

                <!-- Quick Suggested Prompt Chips -->
                <div class="bg-slate-50 border-b border-slate-200/80 px-4 sm:px-6 py-3 flex items-center gap-2 overflow-x-auto">
                    <span class="text-[11px] font-bold text-slate-400 uppercase shrink-0">Try asking:</span>
                    <button type="button" onclick="askPresetQuestion('Compare OSPF vs EIGRP routing protocols for CCNA exam prep.')" class="shrink-0 px-3 py-1.5 rounded-full bg-white hover:bg-sky-50 text-slate-700 hover:text-sky-700 border border-slate-200 text-xs font-medium transition-colors">
                        OSPF vs EIGRP (CCNA)
                    </button>
                    <button type="button" onclick="askPresetQuestion('Give me the top 10 essential Linux networking and troubleshooting commands with examples.')" class="shrink-0 px-3 py-1.5 rounded-full bg-white hover:bg-sky-50 text-slate-700 hover:text-sky-700 border border-slate-200 text-xs font-medium transition-colors">
                        Top 10 Linux Commands
                    </button>
                    <button type="button" onclick="askPresetQuestion('Explain SIP call flow and gateway architecture in Cisco CCVP.')" class="shrink-0 px-3 py-1.5 rounded-full bg-white hover:bg-sky-50 text-slate-700 hover:text-sky-700 border border-slate-200 text-xs font-medium transition-colors">
                        CCVP SIP Call Flow
                    </button>
                    <button type="button" onclick="askPresetQuestion('How does MPLS Layer 3 VPN work in Cisco CCIP service provider networks?')" class="shrink-0 px-3 py-1.5 rounded-full bg-white hover:bg-sky-50 text-slate-700 hover:text-sky-700 border border-slate-200 text-xs font-medium transition-colors">
                        CCIP MPLS L3VPN
                    </button>
                    <button type="button" onclick="askPresetQuestion('What is the difference between Smoke Testing, Sanity Testing, and Regression Testing?')" class="shrink-0 px-3 py-1.5 rounded-full bg-white hover:bg-sky-50 text-slate-700 hover:text-sky-700 border border-slate-200 text-xs font-medium transition-colors">
                        Software Testing Types
                    </button>
                    <button type="button" onclick="askPresetQuestion('Explain the 5 phases of ethical hacking and penetration testing in Cybersecurity.')" class="shrink-0 px-3 py-1.5 rounded-full bg-white hover:bg-sky-50 text-slate-700 hover:text-sky-700 border border-slate-200 text-xs font-medium transition-colors">
                        Cybersecurity Pen-Testing
                    </button>
                </div>

                <!-- Chat Messages Viewport -->
                <div id="ai-chat-messages" class="p-5 sm:p-6 h-96 overflow-y-auto chat-scroll space-y-4 bg-white">
                    <!-- Welcome Message -->
                    <div class="flex items-start gap-3">
                        <div class="w-8 h-8 rounded-full bg-sky-100 text-sky-700 font-bold text-xs flex items-center justify-center shrink-0 mt-0.5">AI</div>
                        <div class="bg-slate-100 text-slate-800 rounded-2xl rounded-tl-none px-4 py-3 text-sm max-w-2xl leading-relaxed">
                            Hello! I am the <strong>Ed - TECH Technical Mentor</strong>. Ask me anything about <strong>Networking, Software Testing, CCNA, Cybersecurity, CCVP, CCIP, or Linux</strong>—including router configs, Linux shell commands, subnetting, or course guidance!
                        </div>
                    </div>
                </div>

                <!-- Chat Input Bar -->
                <form id="ai-chat-form" class="p-4 bg-slate-50 border-t border-slate-200/80 flex items-center gap-3">
                    <input id="ai-user-input" type="text" required placeholder="Type your technical question (e.g., How to configure VLAN trunking on Cisco switch?)..." class="flex-1 px-4 py-3 rounded-2xl bg-white border border-slate-200 text-sm focus:outline-none focus:ring-2 focus:ring-sky-500">
                    <button id="ai-send-btn" type="submit" class="px-5 py-3 rounded-2xl bg-navy-950 hover:bg-sky-600 text-white font-semibold text-sm transition-all flex items-center gap-2 shrink-0">
                        <span>Ask AI</span>
                        <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M6 12L3.269 3.126A59.768 59.768 0 0121.485 12 59.77 59.77 0 013.27 20.876L5.999 12zm0 0h7.5"/></svg>
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- ==================== ONLINE CLASS SUBSCRIPTION PRICING (₹15,000 - ₹35,000/MONTH) ==================== -->
    <section id="pricing" class="py-16 sm:py-24 bg-white border-t border-slate-200/70">
        <div class="max-w-6xl mx-auto px-4 sm:px-6">
            <div class="text-center max-w-3xl mx-auto">
                <span class="inline-flex items-center gap-1.5 px-3 py-1 rounded-full bg-sky-100 text-sky-700 text-xs font-bold uppercase tracking-wider">
                    Transparent Monthly Plans
                </span>
                <h2 class="mt-3 text-3xl sm:text-4xl font-extrabold text-navy-950 tracking-tight">
                    Online Class Subscriptions
                </h2>
                <p class="mt-3 text-slate-600 text-sm sm:text-base">
                    Flexible monthly subscriptions ranging from <strong>₹15,000 to ₹35,000 per month</strong> with live mentor sessions, cloud lab racks, and 24/7 AI support.
                </p>
            </div>

            <div class="mt-12 grid grid-cols-1 lg:grid-cols-3 gap-7 items-stretch">
                <!-- Plan 1: ₹15,000 / month -->
                <div class="rounded-3xl bg-slate-50 border border-slate-200/90 p-7 sm:p-8 flex flex-col justify-between hover:shadow-card transition-shadow">
                    <div>
                        <div class="flex items-center justify-between">
                            <span class="text-sm font-bold text-slate-700">Foundation Online</span>
                            <span class="px-2.5 py-0.5 rounded-full bg-slate-200/80 text-slate-700 text-xs font-semibold">Core Track</span>
                        </div>
                        <div class="mt-4 flex items-baseline gap-1">
                            <span class="text-4xl font-extrabold text-navy-950">₹15,000</span>
                            <span class="text-sm font-medium text-slate-500">/ month</span>
                        </div>
                        <p class="mt-2 text-xs text-slate-500 leading-relaxed">
                            Ideal for students starting with Networking fundamentals, Linux administration, or Manual/Automation Testing.
                        </p>

                        <ul class="mt-6 space-y-3 text-sm text-slate-700">
                            <li class="flex items-center gap-2.5"><span class="text-sky-600 font-bold">✓</span> Live Online Classes (5 Days/Week)</li>
                            <li class="flex items-center gap-2.5"><span class="text-sky-600 font-bold">✓</span> Choice of 1 Core Track (Networking, Linux, or Testing)</li>
                            <li class="flex items-center gap-2.5"><span class="text-sky-600 font-bold">✓</span> 24/7 Ed - TECH AI Technical Mentor</li>
                            <li class="flex items-center gap-2.5"><span class="text-sky-600 font-bold">✓</span> HD Class Recordings & Study Notes</li>
                            <li class="flex items-center gap-2.5"><span class="text-sky-600 font-bold">✓</span> 15-Day Offline Classroom Demo Included</li>
                        </ul>
                    </div>

                    <button onclick="openEnrollModal('Foundation Online Plan', '₹15,000 / month')" class="mt-8 w-full py-3 rounded-full bg-white hover:bg-navy-950 text-navy-950 hover:text-white border border-slate-300 font-bold text-sm transition-all">
                        Subscribe at ₹15,000/mo
                    </button>
                </div>

                <!-- Plan 2: ₹25,000 / month (Highlighted) -->
                <div class="rounded-3xl bg-navy-950 text-white p-7 sm:p-8 flex flex-col justify-between shadow-2xl relative border-2 border-sky-400 lg:-translate-y-2">
                    <div class="absolute -top-3.5 right-6 px-3.5 py-1 rounded-full bg-gradient-to-r from-sky-400 to-cyan-300 text-navy-950 text-xs font-extrabold uppercase tracking-wider shadow">
                        Most Popular
                    </div>

                    <div>
                        <div class="flex items-center justify-between">
                            <span class="text-sm font-bold text-sky-300">Professional Engineer</span>
                            <span class="px-2.5 py-0.5 rounded-full bg-white/10 text-sky-200 text-xs font-semibold">Dual Track</span>
                        </div>
                        <div class="mt-4 flex items-baseline gap-1">
                            <span class="text-4xl font-extrabold text-white">₹25,000</span>
                            <span class="text-sm font-medium text-slate-400">/ month</span>
                        </div>
                        <p class="mt-2 text-xs text-slate-300 leading-relaxed">
                            Built for CCNA, Cybersecurity, and Cloud Automation engineers needing dedicated remote lab racks & mentor reviews.
                        </p>

                        <ul class="mt-6 space-y-3 text-sm text-slate-200">
                            <li class="flex items-center gap-2.5"><span class="text-sky-400 font-bold">✓</span> Live Online Classes + Weekend Doubt Clinics</li>
                            <li class="flex items-center gap-2.5"><span class="text-sky-400 font-bold">✓</span> Any 2 Tracks (e.g., CCNA + Cybersecurity or Linux)</li>
                            <li class="flex items-center gap-2.5"><span class="text-sky-400 font-bold">✓</span> Dedicated 24/7 Remote Cisco & Security Rack</li>
                            <li class="flex items-center gap-2.5"><span class="text-sky-400 font-bold">✓</span> Unlimited AI Mentor + Mock Certification Exams</li>
                            <li class="flex items-center gap-2.5"><span class="text-sky-400 font-bold">✓</span> 15-Day Offline Hardware Lab Demo Pass</li>
                        </ul>
                    </div>

                    <button onclick="openEnrollModal('Professional Engineer Plan', '₹25,000 / month')" class="mt-8 w-full py-3.5 rounded-full bg-sky-500 hover:bg-sky-400 text-navy-950 font-extrabold text-sm shadow-lg transition-all">
                        Subscribe at ₹25,000/mo
                    </button>
                </div>

                <!-- Plan 3: ₹35,000 / month -->
                <div class="rounded-3xl bg-slate-50 border border-slate-200/90 p-7 sm:p-8 flex flex-col justify-between hover:shadow-card transition-shadow">
                    <div>
                        <div class="flex items-center justify-between">
                            <span class="text-sm font-bold text-slate-700">Enterprise Architect</span>
                            <span class="px-2.5 py-0.5 rounded-full bg-indigo-100 text-indigo-700 text-xs font-semibold">All-Access</span>
                        </div>
                        <div class="mt-4 flex items-baseline gap-1">
                            <span class="text-4xl font-extrabold text-navy-950">₹35,000</span>
                            <span class="text-sm font-medium text-slate-500">/ month</span>
                        </div>
                        <p class="mt-2 text-xs text-slate-500 leading-relaxed">
                            Complete mastery across CCVP, CCIP, Cybersecurity, Linux, and Full-Stack Testing with 1-on-1 placement mentorship.
                        </p>

                        <ul class="mt-6 space-y-3 text-sm text-slate-700">
                            <li class="flex items-center gap-2.5"><span class="text-sky-600 font-bold">✓</span> Unlimited Access to All 7 Specialization Tracks</li>
                            <li class="flex items-center gap-2.5"><span class="text-sky-600 font-bold">✓</span> Advanced CCVP Voice & CCIP Service Provider Labs</li>
                            <li class="flex items-center gap-2.5"><span class="text-sky-600 font-bold">✓</span> 1-on-1 Weekly Architecture & Resume Mentorship</li>
                            <li class="flex items-center gap-2.5"><span class="text-sky-600 font-bold">✓</span> Direct Job Placement & Interview Guarantee</li>
                            <li class="flex items-center gap-2.5"><span class="text-sky-600 font-bold">✓</span> Priority Hotline Support (8094161377)</li>
                        </ul>
                    </div>

                    <button onclick="openEnrollModal('Enterprise Architect Plan', '₹35,000 / month')" class="mt-8 w-full py-3 rounded-full bg-navy-950 hover:bg-sky-600 text-white font-bold text-sm transition-all">
                        Subscribe at ₹35,000/mo
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== FOOTER & ONLINE SUPPORT ==================== -->
    <footer id="support" class="bg-navy-950 text-slate-300 pt-16 pb-10 border-t border-white/10">
        <div class="max-w-6xl mx-auto px-4 sm:px-6">
            <div class="grid grid-cols-1 md:grid-cols-12 gap-10 pb-12 border-b border-white/10">
                <!-- Brand Column -->
                <div class="md:col-span-5 space-y-4">
                    <div class="flex items-center gap-2.5">
                        <div class="w-9 h-9 rounded-full bg-sky-500 flex items-center justify-center text-white font-extrabold text-sm">Ed</div>
                        <span class="font-extrabold text-xl text-white tracking-tight">Ed - <span class="text-sky-400">TECH</span></span>
                    </div>
                    <p class="text-sm text-slate-400 leading-relaxed max-w-sm">
                        Next-generation IT education combining live online classes, 15-day free offline hardware lab demos, and an intelligent AI Technical Mentor.
                    </p>
                    <div class="p-4 rounded-2xl bg-white/5 border border-white/10 inline-block">
                        <div class="text-[11px] uppercase tracking-wider text-sky-300 font-bold">24/7 Online Student Support Number</div>
                        <a href="tel:8094161377" class="mt-1 flex items-center gap-2 text-xl font-extrabold text-white hover:text-sky-300 transition-colors">
                            <svg class="w-5 h-5 text-emerald-400" fill="none" stroke="currentColor" stroke-width="2.2" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" d="M2.25 6.75c0 8.284 6.716 15 15 15h2.25a2.25 2.25 0 002.25-2.25v-1.372c0-.516-.351-.966-.852-1.091l-4.423-1.106c-.44-.11-.902.055-1.173.417l-.97 1.293c-.282.376-.769.542-1.21.38a12.035 12.035 0 01-7.143-7.143c-.162-.441.004-.928.38-1.21l1.293-.97c.363-.271.527-.734.417-1.173L6.963 3.102a1.125 1.125 0 00-1.091-.852H4.5A2.25 2.25 0 002.25 4.5v2.25z"/></svg>
                            <span>8094161377</span>
                        </a>
                    </div>
                </div>

                <!-- Courses Links -->
                <div class="md:col-span-4 space-y-3">
                    <h3 class="text-xs font-bold uppercase tracking-wider text-white">Specialization Tracks</h3>
                    <ul class="space-y-2 text-sm text-slate-400">
                        <li><a href="#courses" class="hover:text-sky-400 transition-colors">Enterprise Networking & Subnetting</a></li>
                        <li><a href="#courses" class="hover:text-sky-400 transition-colors">Cisco CCNA (200-301) Certification</a></li>
                        <li><a href="#courses" class="hover:text-sky-400 transition-colors">Cybersecurity & Ethical Hacking</a></li>
                        <li><a href="#courses" class="hover:text-sky-400 transition-colors">Linux Server & Shell Administration</a></li>
                        <li><a href="#courses" class="hover:text-sky-400 transition-colors">Software Testing (Manual & Selenium)</a></li>
                        <li><a href="#courses" class="hover:text-sky-400 transition-colors">Cisco CCVP & CCIP Advanced Tracks</a></li>
                    </ul>
                </div>

                <!-- Quick Actions -->
                <div class="md:col-span-3 space-y-3">
                    <h3 class="text-xs font-bold uppercase tracking-wider text-white">Admissions & Portal</h3>
                    <ul class="space-y-2 text-sm text-slate-400">
                        <li><a href="#offline-demo" class="hover:text-sky-400 transition-colors">15-Day Free Offline Demo</a></li>
                        <li><a href="#pricing" class="hover:text-sky-400 transition-colors">Online Plans (₹15,000–₹35,000/mo)</a></li>
                        <li><a href="#ai-mentor" class="hover:text-sky-400 transition-colors">Ask Ed - TECH AI Mentor</a></li>
                        <li><a href="tel:8094161377" class="hover:text-sky-400 transition-colors">Call Support: 8094161377</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-6 flex flex-col sm:flex-row items-center justify-between gap-4 text-xs text-slate-500">
                <p>© 2026 Ed - TECH Educational Academy. All rights reserved.</p>
                <p>Online Support Desk: <a href="tel:8094161377" class="text-slate-300 font-semibold hover:text-sky-400">8094161377</a></p>
            </div>
        </div>
    </footer>

    <!-- ==================== FLOATING SUPPORT PILL WIDGET ==================== -->
    <div class="fixed bottom-5 right-5 z-40 flex items-center gap-2">
        <a href="tel:8094161377" class="flex items-center gap-2.5 px-4 py-3 rounded-full bg-navy-950 hover:bg-sky-600 text-white text-xs sm:text-sm font-bold shadow-xl border border-white/15 transition-all">
            <span class="w-2.5 h-2.5 rounded-full bg-emerald-400 animate-ping"></span>
            <span>Support: 8094161377</span>
        </a>
    </div>

    <!-- ==================== SUBSCRIPTION ENROLLMENT MODAL ==================== -->
    <div id="enroll-modal" class="hidden fixed inset-0 z-50 bg-navy-950/70 backdrop-blur-sm flex items-center justify-center p-4">
        <div class="bg-white rounded-3xl max-w-md w-full p-6 sm:p-8 shadow-2xl relative">
            <button onclick="closeEnrollModal()" aria-label="Close modal" class="absolute top-5 right-5 w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 flex items-center justify-center text-slate-600 font-bold">✕</button>
            <span class="px-3 py-1 rounded-full bg-sky-100 text-sky-700 text-xs font-bold">Online Class Subscription</span>
            <h3 id="modal-plan-title" class="mt-3 text-xl font-extrabold text-navy-950">Professional Engineer Plan</h3>
            <p id="modal-plan-price" class="text-sm font-bold text-sky-600 mt-0.5">₹25,000 / month</p>

            <form id="modal-enroll-form" class="mt-5 space-y-4">
                <div>
                    <label class="block text-xs font-bold text-slate-700 mb-1">Student Name</label>
                    <input type="text" required placeholder="Enter your full name" class="w-full px-4 py-2.5 rounded-xl border border-slate-200 text-sm focus:outline-none focus:ring-2 focus:ring-sky-500">
                </div>
                <div>
                    <label class="block text-xs font-bold text-slate-700 mb-1">Phone / WhatsApp Number</label>
                    <input type="tel" required placeholder="Enter mobile number" class="w-full px-4 py-2.5 rounded-xl border border-slate-200 text-sm focus:outline-none focus:ring-2 focus:ring-sky-500">
                </div>
                <div>
                    <label class="block text-xs font-bold text-slate-700 mb-1">Primary Course Focus</label>
                    <select class="w-full px-4 py-2.5 rounded-xl border border-slate-200 text-sm bg-white focus:outline-none focus:ring-2 focus:ring-sky-500">
                        <option>CCNA & Networking</option>
                        <option>Cybersecurity</option>
                        <option>Linux Administration</option>
                        <option>Software Testing</option>
                        <option>CCVP (Voice)</option>
                        <option>CCIP (Service Provider)</option>
                    </select>
                </div>
                <button type="submit" class="w-full py-3 rounded-xl bg-navy-950 hover:bg-sky-600 text-white font-bold text-sm transition-all">
                    Request Enrollment & Payment Link
                </button>
            </form>

            <div id="modal-success" class="hidden mt-4 p-4 rounded-2xl bg-emerald-50 border border-emerald-200 text-emerald-900 text-xs leading-relaxed">
                <strong>Application Received!</strong> Our academic advisor will contact you shortly. For immediate activation, call <strong>8094161377</strong>.
            </div>
        </div>
    </div>

    <!-- ==================== INTERACTIVE APPLICATION LOGIC & GEMINI AI ==================== -->
    <script>
        // 1. Course Catalog Data (All 7 Requested Specializations)
        const coursesData = [
            {
                id: 'networking',
                title: 'Enterprise Networking',
                category: 'qa',
                badge: 'Core Foundation',
                badgeColor: 'bg-sky-100 text-sky-700',
                desc: 'Master OSI & TCP/IP models, IPv4/IPv6 subnetting, VLANs, STP, NAT, DHCP, and enterprise LAN/WAN architecture.',
                highlights: ['Live Packet Tracer & GNS3 Labs', '15-Day Free Offline Demo', 'Online: ₹15,000–₹25,000/mo']
            },
            {
                id: 'ccna',
                title: 'Cisco CCNA (200-301)',
                category: 'cisco',
                badge: 'Most In-Demand',
                badgeColor: 'bg-emerald-100 text-emerald-700',
                desc: 'Complete Cisco Certified Network Associate training covering OSPF routing, wireless controllers, ACLs, and network automation.',
                highlights: ['Real Cisco 2900/4300 Router Racks', '15-Day Free Offline Demo', 'Exam Prep + AI Troubleshooting']
            },
            {
                id: 'cybersecurity',
                title: 'Cybersecurity & SOC',
                category: 'security',
                badge: 'High Growth',
                badgeColor: 'bg-rose-100 text-rose-700',
                desc: 'Defend enterprise networks with ethical hacking, SIEM monitoring, firewall policies, cryptography, and vulnerability assessment.',
                highlights: ['Kali Linux & Firewall Sandboxes', '15-Day Free Offline Demo', 'Incident Response Labs']
            },
            {
                id: 'linux',
                title: 'Linux System Administration',
                category: 'security',
                badge: 'Cloud Essential',
                badgeColor: 'bg-amber-100 text-amber-700',
                desc: 'Command-line mastery in Red Hat & Ubuntu Linux, Bash scripting, permissions, LVM storage, systemd, and server hardening.',
                highlights: ['RHCSA-Aligned Practical Labs', '15-Day Free Offline Demo', '24/7 Cloud VM Access']
            },
            {
                id: 'testing',
                title: 'Software Testing & QA',
                category: 'qa',
                badge: 'Job Ready',
                badgeColor: 'bg-purple-100 text-purple-700',
                desc: 'End-to-end Manual Testing, SDLC/STLC, API testing with Postman, and automated browser suites using Selenium & Java/Python.',
                highlights: ['Live Web & API Test Projects', '15-Day Free Offline Demo', 'CI/CD Pipeline Integration']
            },
            {
                id: 'ccvp',
                title: 'Cisco CCVP (Voice & Collab)',
                category: 'cisco',
                badge: 'Specialist Track',
                badgeColor: 'bg-indigo-100 text-indigo-700',
                desc: 'Deploy enterprise VoIP, Cisco Unified Communications Manager (CUCM), SIP trunks, QoS voice policies, and gateways.',
                highlights: ['Dedicated IP Telephony Lab', '15-Day Free Offline Demo', 'Enterprise Architect Tier']
            },
            {
                id: 'ccip',
                title: 'Cisco CCIP (Service Provider)',
                category: 'cisco',
                badge: 'ISP Core Track',
                badgeColor: 'bg-cyan-100 text-cyan-800',
                desc: 'Architect carrier-grade networks with advanced BGP routing, MPLS Layer 2/3 VPNs, IS-IS, and high-availability QoS.',
                highlights: ['ISP Backbone Simulation Racks', '15-Day Free Offline Demo', 'Enterprise Architect Tier']
            }
        ];

        // Render Course Cards
        const coursesGrid = document.getElementById('courses-grid');
        function renderCourses(filter = 'all') {
            const filtered = filter === 'all' ? coursesData : coursesData.filter(c => c.category === filter);
            coursesGrid.innerHTML = filtered.map(course => `
                <article class="bg-white rounded-3xl p-6 border border-slate-200/80 shadow-card hover:-translate-y-1 transition-all flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between gap-2">
                            <span class="px-3 py-1 rounded-full text-xs font-bold ${course.badgeColor}">${course.badge}</span>
                            <span class="text-xs font-semibold text-slate-400">Online + Offline</span>
                        </div>
                        <h3 class="mt-4 text-xl font-extrabold text-navy-950">${course.title}</h3>
                        <p class="mt-2 text-sm text-slate-600 leading-relaxed">${course.desc}</p>
                        <ul class="mt-4 space-y-2 text-xs font-medium text-slate-700 border-t border-slate-100 pt-4">
                            ${course.highlights.map(item => `<li class="flex items-center gap-2"><span class="text-sky-600 font-bold">●</span>${item}</li>`).join('')}
                        </ul>
                    </div>
                    <div class="mt-6 pt-4 border-t border-slate-100 flex items-center gap-2">
                        <a href="#offline-demo" onclick="selectDemoTrack('${course.title}')" class="flex-1 text-center py-2.5 rounded-full bg-navy-950 hover:bg-sky-600 text-white text-xs font-bold transition-colors">
                            15-Day Free Demo
                        </a>
                        <button onclick="askPresetQuestion('Give me a roadmap and key topics to master ${course.title} at Ed - TECH.')" class="px-3.5 py-2.5 rounded-full bg-slate-100 hover:bg-sky-100 text-slate-700 hover:text-sky-700 text-xs font-bold transition-colors" title="Ask AI about this course">
                            Ask AI
                        </button>
                    </div>
                </article>
            `).join('');
        }
        renderCourses();

        // Filter Button Interactivity
        document.querySelectorAll('.filter-btn').forEach(btn => {
            btn.addEventListener('click', () => {
                document.querySelectorAll('.filter-btn').forEach(b => {
                    b.classList.remove('bg-navy-950', 'text-white', 'shadow-sm');
                    b.classList.add('bg-white', 'text-slate-600', 'border', 'border-slate-200');
                });
                btn.classList.add('bg-navy-950', 'text-white', 'shadow-sm');
                btn.classList.remove('bg-white', 'text-slate-600', 'border', 'border-slate-200');
                renderCourses(btn.dataset.filter);
            });
        });

        // Pre-select course in 15-day offline demo form
        function selectDemoTrack(courseTitle) {
            const select = document.getElementById('demo-track');
            for (let i = 0; i < select.options.length; i++) {
                if (courseTitle.toLowerCase().includes(select.options[i].value.toLowerCase())) {
                    select.selectedIndex = i;
                    break;
                }
            }
        }

        // Mobile Navigation Toggle
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // 15-Day Offline Demo Form Submission
        document.getElementById('demo-booking-form').addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('demo-name').value.trim();
            const phone = document.getElementById('demo-phone').value.trim();
            const track = document.getElementById('demo-track').value;
            const batch = document.getElementById('demo-batch').value;

            const confirmBox = document.getElementById('demo-confirmation');
            const confirmText = document.getElementById('demo-confirmation-text');
            confirmText.innerHTML = `Welcome, <strong>${escapeHtml(name)}</strong>! Your <strong>15-Day Free Offline Classroom Demo</strong> for <strong>${escapeHtml(track)}</strong> (${escapeHtml(batch)}) is registered under <strong>${escapeHtml(phone)}</strong>.`;
            confirmBox.classList.remove('hidden');
            this.reset();
        });

        // Subscription Enrollment Modal Controls
        const enrollModal = document.getElementById('enroll-modal');
        function openEnrollModal(planName, price) {
            document.getElementById('modal-plan-title').textContent = planName;
            document.getElementById('modal-plan-price').textContent = price;
            document.getElementById('modal-success').classList.add('hidden');
            enrollModal.classList.remove('hidden');
        }
        function closeEnrollModal() {
            enrollModal.classList.add('hidden');
        }
        document.getElementById('modal-enroll-form').addEventListener('submit', function(e) {
            e.preventDefault();
            document.getElementById('modal-success').classList.remove('hidden');
            this.reset();
        });

        // ==================== GEMINI AI TECHNICAL MENTOR INTEGRATION ====================
        const chatMessages = document.getElementById('ai-chat-messages');
        const aiForm = document.getElementById('ai-chat-form');
        const aiInput = document.getElementById('ai-user-input');
        const aiSendBtn = document.getElementById('ai-send-btn');

        const SYSTEM_INSTRUCTION = `You are the official AI Technical Mentor for "Ed - TECH", an advanced IT educational institute. 
Your expertise covers:
1. Enterprise Networking (OSI/TCP-IP, Subnetting, VLANs, Routing, Switching)
2. Software Testing (Manual Testing, SDLC/STLC, Selenium, API Testing, QA Automation)
3. Cisco CCNA (200-301, OSPF, EIGRP, ACLs, NAT, Wireless)
4. Cybersecurity (Ethical Hacking, Firewalls, SOC, SIEM, Cryptography, Pen-Testing)
5. Cisco CCVP (Voice over IP, CUCM, SIP, Gateways, QoS)
6. Cisco CCIP (Service Provider, BGP, MPLS VPNs, IS-IS)
7. Linux Administration (Ubuntu/RHEL, Bash scripting, chmod/chown, networking commands, systemd)

Provide clear, accurate, concise, and practical technical answers with CLI commands or step-by-step explanations where helpful. If asked about Ed - TECH admissions, mention our online class subscriptions (₹15,000–₹35,000/month), our 15-day free offline classroom demo, and our support helpline 8094161377.`;

        function escapeHtml(text) {
            const div = document.createElement('div');
            div.textContent = text;
            return div.innerHTML;
        }

        function formatAIResponse(text) {
            // Safely escape HTML first, then apply clean formatting for code blocks and bold text
            let safe = escapeHtml(text);
            safe = safe.replace(/```([\s\S]*?)```/g, '<pre class="my-2 p-3 rounded-xl bg-navy-950 text-sky-200 font-mono text-xs overflow-x-auto"><code>$1</code></pre>');
            safe = safe.replace(/`([^`]+)`/g, '<code class="px-1.5 py-0.5 rounded bg-slate-200/80 text-navy-950 font-mono text-xs">$1</code>');
            safe = safe.replace(/\*\*([^*]+)\*\*/g, '<strong>$1</strong>');
            safe = safe.replace(/\n/g, '<br>');
            return safe;
        }

        function appendMessage(sender, text, isLoading = false) {
            const wrapper = document.createElement('div');
            if (sender === 'user') {
                wrapper.className = 'flex items-start justify-end gap-3';
                wrapper.innerHTML = `
                    <div class="bg-navy-950 text-white rounded-2xl rounded-tr-none px-4 py-3 text-sm max-w-2xl leading-relaxed shadow-sm">
                        ${escapeHtml(text)}
                    </div>
                `;
            } else {
                wrapper.className = 'flex items-start gap-3';
                wrapper.innerHTML = `
                    <div class="w-8 h-8 rounded-full bg-sky-100 text-sky-700 font-bold text-xs flex items-center justify-center shrink-0 mt-0.5">AI</div>
                    <div class="bg-slate-100 text-slate-800 rounded-2xl rounded-tl-none px-4 py-3 text-sm max-w-2xl leading-relaxed">
                        ${isLoading ? '<span class="inline-flex items-center gap-1.5 text-slate-500"><span class="w-2 h-2 rounded-full bg-sky-500 animate-bounce"></span>Analyzing protocol & lab knowledge...</span>' : formatAIResponse(text)}
                    </div>
                `;
            }
            chatMessages.appendChild(wrapper);
            chatMessages.scrollTop = chatMessages.scrollHeight;
            return wrapper;
        }

        async function callGeminiWithBackoff(userPrompt) {
            const apiKey = ""; // Provided automatically at runtime
            const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-3-flash-preview:generateContent?key=${apiKey}`;

            const payload = {
                contents: [{ parts: [{ text: userPrompt }] }],
                systemInstruction: {
                    parts: [{ text: SYSTEM_INSTRUCTION }]
                }
            };

            const delays = [1000, 2000, 4000, 8000];
            for (let attempt = 0; attempt <= delays.length; attempt++) {
                try {
                    const response = await fetch(apiUrl, {
                        method: 'POST',
                        headers: { 'Content-Type': 'application/json' },
                        body: JSON.stringify(payload)
                    });

                    if (!response.ok) {
                        if (response.status === 429 && attempt < delays.length) {
                            await new Promise(res => setTimeout(res, delays[attempt]));
                            continue;
                        }
                        throw new Error(`HTTP ${response.status}`);
                    }

                    const result = await response.json();
                    const replyText = result?.candidates?.[0]?.content?.parts?.[0]?.text;
                    if (replyText) return replyText;
                    throw new Error('Empty response');
                } catch (err) {
                    if (attempt < delays.length) {
                        await new Promise(res => setTimeout(res, delays[attempt]));
                    } else {
                        return "I'm currently experiencing high traffic on our lab servers. Please try your technical question again in a moment, or call our live engineering support desk at **8094161377** for immediate help!";
                    }
                }
            }
        }

        async function handleAskAI(question) {
            if (!question.trim()) return;
            appendMessage('user', question);
            aiInput.value = '';
            aiSendBtn.disabled = true;
            aiSendBtn.classList.add('opacity-60');

            const loadingBubble = appendMessage('ai', '', true);
            const answer = await callGeminiWithBackoff(question);
            loadingBubble.remove();
            appendMessage('ai', answer);

            aiSendBtn.disabled = false;
            aiSendBtn.classList.remove('opacity-60');
        }

        aiForm.addEventListener('submit', (e) => {
            e.preventDefault();
            handleAskAI(aiInput.value);
        });

        function askPresetQuestion(promptText) {
            document.getElementById('ai-mentor').scrollIntoView({ behavior: 'smooth' });
            handleAskAI(promptText);
        }

        function sendFromHeroDashboard() {
            const heroInput = document.getElementById('hero-quick-ai-input');
            const q = heroInput.value.trim() || 'Explain how CCNA, Cybersecurity, and Linux labs work at Ed - TECH.';
            heroInput.value = '';
            askPresetQuestion(q);
        }

        document.getElementById('clear-chat-btn').addEventListener('click', () => {
            chatMessages.innerHTML = `
                <div class="flex items-start gap-3">
                    <div class="w-8 h-8 rounded-full bg-sky-100 text-sky-700 font-bold text-xs flex items-center justify-center shrink-0 mt-0.5">AI</div>
                    <div class="bg-slate-100 text-slate-800 rounded-2xl rounded-tl-none px-4 py-3 text-sm max-w-2xl leading-relaxed">
                        Chat reset! Ask me any question on <strong>Networking, Testing, CCNA, Cybersecurity, CCVP, CCIP, or Linux</strong>.
                    </div>
                </div>
            `;
        });
    </script>
</body>
</html>
