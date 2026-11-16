<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AM Joy Wedding & Event | Donde tus sueños se convierten en momentos inolvidables</title>
  <meta name="description" content="AM Joy Wedding & Event - Planificación, organización, coordinación y decoración de bodas y eventos de lujo en Santo Domingo y toda República Dominicana." />
  <meta name="keywords" content="Wedding Planner en República Dominicana, Organización de bodas en Santo Domingo, Decoración de bodas en República Dominicana, Wedding Decor Dominican Republic, Event Planner Santo Domingo, AM Joy Wedding & Event" />
  <meta property="og:title" content="AM Joy Wedding & Event | Luxury Wedding & Event Planner" />
  <meta property="og:description" content="Donde tus sueños se convierten en momentos inolvidables. Planificación y decoración de eventos exclusivos en República Dominicana." />
  <meta property="og:type" content="website" />

  <!-- Google Fonts: Cormorant Garamond & Plus Jakarta Sans -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;0,600;0,700;1,400;1,600&family=Plus+Jakarta+Sans:wght@300;400;500;600;700&display=swap" rel="stylesheet" />

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            ivory: '#FFFDF9',
            champagne: '#F7EFE5',
            beige: '#E6D5B8',
            gold: {
              DEFAULT: '#C5A059',
              light: '#D4AF37',
              dark: '#A6823C',
            },
            espresso: '#2C2420',
            taupe: '#6E6259',
          },
          fontFamily: {
            serif: ['"Cormorant Garamond"', 'Georgia', 'serif'],
            sans: ['"Plus Jakarta Sans"', 'sans-serif'],
          },
          boxShadow: {
            luxury: '0 20px 50px -12px rgba(44, 36, 32, 0.08)',
            gold: '0 10px 30px -5px rgba(197, 160, 89, 0.25)',
          },
        },
      },
    };
  </script>

  <!-- Lucide Icons -->
  <script src="https://unpkg.com/lucide@latest"></script>

  <!-- Structured Data SEO (JSON-LD) -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "EventPlanner",
    "name": "AM Joy Wedding & Event",
    "slogan": "Donde tus sueños se convierten en momentos inolvidables",
    "description": "Empresa especializada en planificación, organización, coordinación y decoración de bodas y eventos especiales en República Dominicana.",
    "areaServed": {
      "@type": "Country",
      "name": "Dominican Republic"
    },
    "address": {
      "@type": "PostalAddress",
      "addressLocality": "Santo Domingo",
      "addressCountry": "DO"
    }
  }
  </script>

  <style>
    body {
      background-color: #FFFDF9;
      color: #2C2420;
      font-family: 'Plus Jakarta Sans', sans-serif;
    }
    h1, h2, h3, h4, .font-serif-luxury {
      font-family: 'Cormorant Garamond', Georgia, serif;
    }
    .glass-nav {
      background: rgba(255, 253, 249, 0.92);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
    }
    .gold-gradient {
      background: linear-gradient(135deg, #C5A059 0%, #D4AF37 50%, #B38E46 100%);
    }
    .champagne-gradient {
      background: linear-gradient(180deg, #FFFDF9 0%, #F7EFE5 100%);
    }
    .fade-in {
      animation: fadeIn 0.5s ease-out forwards;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }
    /* Custom scrollbar */
    ::-webkit-scrollbar { width: 8px; }
    ::-webkit-scrollbar-track { background: #F7EFE5; }
    ::-webkit-scrollbar-thumb { background: #C5A059; border-radius: 9999px; }
  </style>
</head>
<body class="antialiased selection:bg-gold/20 selection:text-espresso">

  <!-- Toast / Message Notification Container (Replaces alert) -->
  <div id="toast-container" class="fixed top-24 right-4 z-[100] flex flex-col gap-3 max-w-sm w-full pointer-events-none"></div>

  <!-- ===================================================================== -->
  <!-- 1. NAVIGATION BAR                                                     -->
  <!-- ===================================================================== -->
  <header class="fixed top-0 inset-x-0 z-50 glass-nav border-b border-beige/60 transition-all duration-300">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex items-center justify-between h-20">
        <!-- Brand Logo -->
        <a href="#inicio" class="flex items-center gap-3 group">
          <div class="w-10 h-10 rounded-full border border-gold flex items-center justify-center bg-champagne/60 group-hover:bg-gold group-hover:text-white transition-colors">
            <span class="font-serif text-xl font-bold tracking-wider text-gold group-hover:text-white">AM</span>
          </div>
          <div>
            <span class="font-serif text-xl sm:text-2xl font-bold tracking-wide text-espresso block leading-none">AM Joy</span>
            <span class="text-[10px] uppercase tracking-[0.25em] text-gold font-semibold block mt-0.5">Wedding & Event</span>
          </div>
        </a>

        <!-- Desktop Navigation -->
        <nav class="hidden xl:flex items-center gap-6 text-sm font-medium text-espresso/85">
          <a href="#inicio" data-i18n="nav.home" class="hover:text-gold transition-colors">Inicio</a>
          <a href="#nosotros" data-i18n="nav.about" class="hover:text-gold transition-colors">Sobre Nosotros</a>
          <a href="#servicios" data-i18n="nav.services" class="hover:text-gold transition-colors">Servicios</a>
          <a href="#galeria" data-i18n="nav.gallery" class="hover:text-gold transition-colors">Galería</a>
          <a href="#portafolio" data-i18n="nav.portfolio" class="hover:text-gold transition-colors">Portafolio</a>
          <a href="#herramientas" data-i18n="nav.tools" class="hover:text-gold transition-colors">Herramientas</a>
          <a href="#blog" data-i18n="nav.blog" class="hover:text-gold transition-colors">Blog</a>
          <a href="#cotizar" data-i18n="nav.quote" class="hover:text-gold transition-colors">Cotizar</a>
        </nav>

        <!-- Action Controls -->
        <div class="flex items-center gap-2 sm:gap-3">
          <!-- Language Toggle -->
          <button id="lang-toggle" onclick="toggleLanguage()" class="px-3 py-1.5 rounded-full border border-beige bg-champagne/50 hover:border-gold text-xs font-semibold tracking-wider text-espresso transition-all flex items-center gap-1.5" title="Cambiar Idioma / Switch Language">
            <i data-lucide="globe" class="w-3.5 h-3.5 text-gold"></i>
            <span id="lang-label">EN</span>
          </button>

          <!-- Wishlist Button -->
          <button onclick="openModal('wishlist-modal')" class="relative p-2.5 rounded-full border border-beige bg-ivory hover:border-gold text-espresso transition-all" title="Lista de Deseos / Wishlist">
            <i data-lucide="heart" class="w-4 h-4 text-gold"></i>
            <span id="wishlist-badge" class="absolute -top-1 -right-1 w-4 h-4 rounded-full bg-gold text-white text-[10px] font-bold flex items-center justify-center">0</span>
          </button>

          <!-- Client Portal Button -->
          <button onclick="openModal('client-portal-modal')" class="hidden sm:inline-flex items-center gap-1.5 px-3.5 py-2 rounded-full border border-gold/60 text-xs font-semibold text-espresso hover:bg-champagne transition-all">
            <i data-lucide="sparkles" class="w-3.5 h-3.5 text-gold"></i>
            <span data-i18n="nav.clientPortal">Portal Clientes</span>
          </button>

          <!-- Admin Button -->
          <button onclick="openModal('admin-modal')" class="p-2.5 rounded-full border border-beige bg-ivory hover:border-gold text-espresso transition-all" title="Panel de Administración">
            <i data-lucide="shield-check" class="w-4 h-4 text-taupe hover:text-gold"></i>
          </button>

          <!-- Mobile Menu Button -->
          <button id="mobile-menu-btn" onclick="toggleMobileMenu()" class="xl:hidden p-2.5 rounded-xl border border-beige text-espresso hover:bg-champagne">
            <i data-lucide="menu" class="w-5 h-5"></i>
          </button>
        </div>
      </div>
    </div>

    <!-- Mobile Drawer -->
    <div id="mobile-menu" class="hidden xl:hidden bg-ivory border-b border-beige px-4 pt-3 pb-6 space-y-2 shadow-luxury">
      <a href="#inicio" onclick="toggleMobileMenu()" data-i18n="nav.home" class="block py-2 px-3 rounded-xl hover:bg-champagne font-medium">Inicio</a>
      <a href="#nosotros" onclick="toggleMobileMenu()" data-i18n="nav.about" class="block py-2 px-3 rounded-xl hover:bg-champagne font-medium">Sobre Nosotros</a>
      <a href="#servicios" onclick="toggleMobileMenu()" data-i18n="nav.services" class="block py-2 px-3 rounded-xl hover:bg-champagne font-medium">Nuestros Servicios</a>
      <a href="#galeria" onclick="toggleMobileMenu()" data-i18n="nav.gallery" class="block py-2 px-3 rounded-xl hover:bg-champagne font-medium">Galería de Eventos</a>
      <a href="#portafolio" onclick="toggleMobileMenu()" data-i18n="nav.portfolio" class="block py-2 px-3 rounded-xl hover:bg-champagne font-medium">Portafolio Real</a>
      <a href="#herramientas" onclick="toggleMobileMenu()" data-i18n="nav.tools" class="block py-2 px-3 rounded-xl hover:bg-champagne font-medium">Calculadora, Agenda & Herramientas</a>
      <a href="#testimonios" onclick="toggleMobileMenu()" data-i18n="nav.testimonials" class="block py-2 px-3 rounded-xl hover:bg-champagne font-medium">Testimonios</a>
      <a href="#blog" onclick="toggleMobileMenu()" data-i18n="nav.blog" class="block py-2 px-3 rounded-xl hover:bg-champagne font-medium">Blog de Inspiración</a>
      <a href="#faq" onclick="toggleMobileMenu()" data-i18n="nav.faq" class="block py-2 px-3 rounded-xl hover:bg-champagne font-medium">Preguntas Frecuentes</a>
      <div class="pt-2 flex gap-2">
        <button onclick="toggleMobileMenu(); openModal('client-portal-modal')" class="flex-1 py-2.5 px-4 rounded-xl border border-gold text-center text-sm font-semibold text-espresso">
          <span data-i18n="nav.clientPortal">Portal Clientes</span>
        </button>
        <a href="#cotizar" onclick="toggleMobileMenu()" class="flex-1 py-2.5 px-4 rounded-xl gold-gradient text-white text-center text-sm font-semibold shadow-gold">
          <span data-i18n="nav.quoteBtn">Cotizar</span>
        </a>
      </div>
    </div>
  </header>

  <!-- ===================================================================== -->
  <!-- 2. HERO SECTION (INICIO)                                              -->
  <!-- ===================================================================== -->
  <section id="inicio" class="relative pt-20 min-h-[92vh] flex items-center overflow-hidden">
    <!-- Background Image with Luxury Warm Overlay -->
    <div class="absolute inset-0 z-0">
      <img
        src="https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&w=2000&q=85"
        onerror="this.src='https://placehold.co/1920x1080/F7EFE5/2C2420?text=AM+Joy+Wedding+%26+Event'"
        alt="AM Joy Wedding & Event Luxury Wedding"
        class="w-full h-full object-cover object-center scale-105 transition-transform duration-1000"
      />
      <div class="absolute inset-0 bg-gradient-to-r from-ivory/95 via-ivory/80 to-ivory/35"></div>
    </div>

    <div class="relative z-10 max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-16 lg:py-24 w-full">
      <div class="max-w-2xl fade-in">
        <div class="inline-flex items-center gap-2 px-4 py-1.5 rounded-full bg-champagne/90 border border-gold/40 mb-6">
          <i data-lucide="crown" class="w-4 h-4 text-gold"></i>
          <span class="text-xs uppercase tracking-[0.2em] font-semibold text-espresso" data-i18n="hero.badge">
            República Dominicana • Luxury Event Design
          </span>
        </div>

        <h1 class="font-serif text-4xl sm:text-6xl lg:text-7xl font-semibold text-espresso leading-[1.08] mb-6">
          AM Joy <span class="italic font-normal text-gold">Wedding & Event</span>
        </h1>

        <p class="font-serif italic text-2xl sm:text-3xl text-espresso/90 mb-5 leading-snug" data-i18n="hero.slogan">
          “Donde tus sueños se convierten en momentos inolvidables”
        </p>

        <p class="text-base sm:text-lg text-taupe leading-relaxed mb-8 max-w-xl" data-i18n="hero.subtitle">
          Planificación integral, coordinación impecable y diseño floral de alta costura para bodas exclusivas y celebraciones memorables en Santo Domingo y toda la República Dominicana.
        </p>

        <div class="flex flex-col sm:flex-row gap-4">
          <a href="#cotizar" class="inline-flex items-center justify-center gap-2 px-8 py-4 rounded-full gold-gradient text-white font-semibold text-sm tracking-wide shadow-gold hover:opacity-95 transition-all">
            <span data-i18n="hero.ctaQuote">Solicitar Cotización Personalizada</span>
            <i data-lucide="arrow-right" class="w-4 h-4"></i>
          </a>
          <a href="#herramientas" class="inline-flex items-center justify-center gap-2 px-8 py-4 rounded-full bg-ivory/90 border border-gold/60 text-espresso font-semibold text-sm tracking-wide hover:bg-champagne transition-all">
            <i data-lucide="calculator" class="w-4 h-4 text-gold"></i>
            <span data-i18n="hero.ctaCalc">Calcular Presupuesto</span>
          </a>
        </div>

        <!-- Trust Indicators -->
        <div class="grid grid-cols-3 gap-6 mt-12 pt-8 border-t border-beige/80 max-w-lg">
          <div>
            <p class="font-serif text-3xl font-bold text-gold">Desde $150</p>
            <p class="text-xs text-taupe uppercase tracking-wider mt-1" data-i18n="hero.stat1">Experiencias a Medida</p>
          </div>
          <div>
            <p class="font-serif text-3xl font-bold text-gold">RD</p>
            <p class="text-xs text-taupe uppercase tracking-wider mt-1" data-i18n="hero.stat2">Cobertura Nacional</p>
          </div>
          <div>
            <p class="font-serif text-3xl font-bold text-gold">5★</p>
            <p class="text-xs text-taupe uppercase tracking-wider mt-1" data-i18n="hero.stat3">Atención Exclusiva</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- 3. SOBRE NOSOTROS (ESENCIA, MISIÓN Y VISIÓN BILINGÜE)                 -->
  <!-- ===================================================================== -->
  <section id="nosotros" class="py-20 lg:py-28 bg-ivory">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="grid lg:grid-cols-12 gap-12 items-center">
        <!-- Visual Collage -->
        <div class="lg:col-span-5 relative">
          <div class="rounded-3xl overflow-hidden shadow-luxury border border-beige">
            <img
              src="https://images.unsplash.com/photo-1511285560929-80b456fea0bc?auto=format&fit=crop&w=1000&q=80"
              onerror="this.src='https://placehold.co/800x1000/E6D5B8/2C2420?text=AM+Joy+Esencia'"
              alt="Decoración romántica de boda"
              class="w-full h-[460px] object-cover"
            />
          </div>
          <div class="hidden sm:block absolute -bottom-6 -right-6 bg-champagne border border-gold/40 rounded-2xl p-6 max-w-xs shadow-luxury">
            <p class="font-serif italic text-xl text-espresso leading-snug" data-i18n="about.quoteCard">
              “Cada detalle cuenta una historia de amor, elegancia y perfección.”
            </p>
            <p class="text-xs uppercase tracking-widest text-gold font-semibold mt-3">AM Joy Wedding & Event</p>
          </div>
        </div>

        <!-- Essence, Mission & Vision -->
        <div class="lg:col-span-7 space-y-6">
          <span class="text-xs uppercase tracking-[0.25em] text-gold font-semibold" data-i18n="about.eyebrow">Nuestra Esencia</span>
          <h2 class="font-serif text-4xl sm:text-5xl font-semibold text-espresso leading-tight" data-i18n="about.title">
            Transformamos emociones en escenarios inolvidables
          </h2>
          <p class="text-taupe leading-relaxed text-base sm:text-lg" data-i18n="about.essence">
            En <strong>AM Joy Wedding & Event</strong> somos una firma especializada en la planificación, organización, coordinación y decoración de bodas y eventos especiales. Nacimos con la vocación de acompañar a cada pareja y anfitrión con sensibilidad artística, rigor logístico y un gusto refinado por el detalle, asegurando que disfruten cada instante sin preocupaciones.
          </p>

          <div class="grid sm:grid-cols-2 gap-6 pt-4">
            <!-- Misión -->
            <div class="p-6 rounded-2xl bg-champagne/60 border border-beige hover:border-gold/60 transition-colors">
              <div class="w-10 h-10 rounded-full bg-ivory border border-gold/40 flex items-center justify-center mb-4">
                <i data-lucide="heart-handshake" class="w-5 h-5 text-gold"></i>
              </div>
              <h3 class="font-serif text-2xl font-semibold text-espresso mb-2" data-i18n="about.missionTitle">Nuestra Misión</h3>
              <p class="text-sm text-taupe leading-relaxed" data-i18n="about.missionText">
                Brindar asesoría integral, diseño exclusivo y coordinación impecable en cada boda y evento social o corporativo, superando las expectativas de nuestros clientes mediante un servicio cálido, transparente y altamente profesional.
              </p>
            </div>

            <!-- Visión -->
            <div class="p-6 rounded-2xl bg-champagne/60 border border-beige hover:border-gold/60 transition-colors">
              <div class="w-10 h-10 rounded-full bg-ivory border border-gold/40 flex items-center justify-center mb-4">
                <i data-lucide="gem" class="w-5 h-5 text-gold"></i>
              </div>
              <h3 class="font-serif text-2xl font-semibold text-espresso mb-2" data-i18n="about.visionTitle">Nuestra Visión</h3>
              <p class="text-sm text-taupe leading-relaxed" data-i18n="about.visionText">
                Consolidarnos como la empresa referente de planificación y decoración de bodas y eventos de lujo en la República Dominicana, siendo reconocidos por nuestra excelencia creativa, confianza y capacidad de convertir sueños en recuerdos eternos.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- 4. NUESTROS SERVICIOS, BODAS Y EVENTOS SOCIALES/CORPORATIVOS          -->
  <!-- ===================================================================== -->
  <section id="servicios" class="py-20 lg:py-28 champagne-gradient border-y border-beige/60">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center max-w-3xl mx-auto mb-16">
        <span class="text-xs uppercase tracking-[0.25em] text-gold font-semibold" data-i18n="services.eyebrow">Excelencia en Cada Etapa</span>
        <h2 class="font-serif text-4xl sm:text-5xl font-semibold text-espresso mt-2 mb-4" data-i18n="services.title">
          Nuestros Servicios Exclusivos
        </h2>
        <p class="text-taupe text-base sm:text-lg" data-i18n="services.subtitle">
          Desde la conceptualización estética hasta la coordinación minuto a minuto, diseñamos experiencias a la altura de tus sueños.
        </p>
      </div>

      <!-- Services Grid -->
      <div id="services-grid" class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Rendered dynamically from state so Admin edits reflect immediately -->
      </div>

      <!-- Dedicated Highlight Banner: Weddings vs Social & Corporate -->
      <div class="mt-16 grid lg:grid-cols-2 gap-8">
        <!-- Bodas -->
        <div class="rounded-3xl bg-ivory border border-beige p-8 sm:p-10 shadow-luxury flex flex-col justify-between">
          <div>
            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-champagne text-gold text-xs font-semibold uppercase tracking-wider mb-4">
              <i data-lucide="rings" class="w-3.5 h-3.5"></i>
              <span data-i18n="weddings.tag">Especialidad Principal</span>
            </div>
            <h3 class="font-serif text-3xl font-semibold text-espresso mb-3" data-i18n="weddings.title">Bodas de Ensueño</h3>
            <p class="text-taupe text-sm sm:text-base leading-relaxed mb-6" data-i18n="weddings.desc">
              Ceremonias religiosas, bodas civiles, bodas destino en playa o hacienda y recepciones de gala. Cuidamos la armonía floral, iluminación arquitectónica, protocolo y experiencia de tus invitados.
            </p>
            <ul class="space-y-2.5 text-sm text-espresso/90 mb-8">
              <li class="flex items-center gap-2.5"><i data-lucide="check-circle-2" class="w-4 h-4 text-gold shrink-0"></i> <span data-i18n="weddings.b1">Diseño escenográfico y ambientación floral personalizada</span></li>
              <li class="flex items-center gap-2.5"><i data-lucide="check-circle-2" class="w-4 h-4 text-gold shrink-0"></i> <span data-i18n="weddings.b2">Gestión integral de suplidores, catering y locación</span></li>
              <li class="flex items-center gap-2.5"><i data-lucide="check-circle-2" class="w-4 h-4 text-gold shrink-0"></i> <span data-i18n="weddings.b3">Coordinación completa del ensayo y el gran día</span></li>
            </ul>
          </div>
          <a href="#cotizar" onclick="preselectEventType('Boda')" class="inline-flex items-center justify-center gap-2 w-full py-3.5 rounded-full border border-gold text-espresso font-semibold text-sm hover:bg-gold hover:text-white transition-all">
            <span data-i18n="weddings.cta">Planificar Mi Boda</span>
            <i data-lucide="arrow-right" class="w-4 h-4"></i>
          </a>
        </div>

        <!-- Eventos Sociales y Corporativos -->
        <div class="rounded-3xl bg-ivory border border-beige p-8 sm:p-10 shadow-luxury flex flex-col justify-between">
          <div>
            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-champagne text-gold text-xs font-semibold uppercase tracking-wider mb-4">
              <i data-lucide="champagne" class="w-3.5 h-3.5"></i>
              <span data-i18n="social.tag">Experiencias Íntimas, Sociales & Corporativas</span>
            </div>
            <h3 class="font-serif text-3xl font-semibold text-espresso mb-3" data-i18n="social.title">Cenas Románticas, Sorpresas y Eventos</h3>
            <p class="text-taupe text-sm sm:text-base leading-relaxed mb-6" data-i18n="social.desc">
              Desde cenas románticas privadas para dos, decoraciones sorpresa en habitación o villa y servicio de chef privado, hasta cumpleaños íntimos, baby showers y eventos corporativos desde $150 USD.
            </p>
            <ul class="space-y-2.5 text-sm text-espresso/90 mb-8">
              <li class="flex items-center gap-2.5"><i data-lucide="check-circle-2" class="w-4 h-4 text-gold shrink-0"></i> <span data-i18n="social.b1">Cenas románticas, propuestas y decoración sorpresa en habitación o playa</span></li>
              <li class="flex items-center gap-2.5"><i data-lucide="check-circle-2" class="w-4 h-4 text-gold shrink-0"></i> <span data-i18n="social.b2">Servicio de chef privado, cumpleaños íntimos y baby showers</span></li>
              <li class="flex items-center gap-2.5"><i data-lucide="check-circle-2" class="w-4 h-4 text-gold shrink-0"></i> <span data-i18n="social.b3">Ambientación social y corporativa adaptada a cada presupuesto</span></li>
            </ul>
          </div>
          <a href="#cotizar" onclick="preselectEventType('Cena Romántica / Decoración Sorpresa')" class="inline-flex items-center justify-center gap-2 w-full py-3.5 rounded-full border border-gold text-espresso font-semibold text-sm hover:bg-gold hover:text-white transition-all">
            <span data-i18n="social.cta">Cotizar Experiencia Íntima o Evento</span>
            <i data-lucide="arrow-right" class="w-4 h-4"></i>
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- 5. GALERÍA INTERACTIVA POR CATEGORÍAS + WISHLIST                      -->
  <!-- ===================================================================== -->
  <section id="galeria" class="py-20 lg:py-28 bg-ivory">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex flex-col md:flex-row md:items-end justify-between gap-6 mb-12">
        <div>
          <span class="text-xs uppercase tracking-[0.25em] text-gold font-semibold" data-i18n="gallery.eyebrow">Inspiración Visual</span>
          <h2 class="font-serif text-4xl sm:text-5xl font-semibold text-espresso mt-2" data-i18n="gallery.title">
            Galería de Eventos
          </h2>
        </div>
        <p class="text-sm text-taupe max-w-md" data-i18n="gallery.hint">
          Explora por categoría, amplía cada fotografía o guárdala en tu Lista de Deseos para compartir tu estilo ideal con nuestro equipo.
        </p>
      </div>

      <!-- Category Filter Pills -->
      <div id="gallery-filters" class="flex flex-wrap gap-2.5 mb-10">
        <!-- Populated via JS -->
      </div>

      <!-- Gallery Grid -->
      <div id="gallery-grid" class="grid sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <!-- Populated via JS -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- 6. PORTAFOLIO DE EVENTOS REALES (FICHAS INDIVIDUALES)                 -->
  <!-- ===================================================================== -->
  <section id="portafolio" class="py-20 lg:py-28 bg-champagne/50 border-y border-beige/60">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center max-w-3xl mx-auto mb-14">
        <span class="text-xs uppercase tracking-[0.25em] text-gold font-semibold" data-i18n="portfolio.eyebrow">Curaduría & Diseño</span>
        <h2 class="font-serif text-4xl sm:text-5xl font-semibold text-espresso mt-2 mb-4" data-i18n="portfolio.title">
          Portafolio de Eventos Reales
        </h2>
        <p class="text-taupe" data-i18n="portfolio.subtitle">
          Descubre el concepto creativo, paleta cromática y producción detrás de nuestras celebraciones más emblemáticas.
        </p>
      </div>

      <div id="portfolio-grid" class="grid md:grid-cols-3 gap-8">
        <!-- Populated via JS -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- 7. SUITE DE HERRAMIENTAS INTERACTIVAS PARA NOVIOS Y CLIENTES          -->
  <!-- ===================================================================== -->
  <section id="herramientas" class="py-20 lg:py-28 bg-ivory">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center max-w-3xl mx-auto mb-12">
        <span class="text-xs uppercase tracking-[0.25em] text-gold font-semibold" data-i18n="tools.eyebrow">Experiencia Digital Exclusiva</span>
        <h2 class="font-serif text-4xl sm:text-5xl font-semibold text-espresso mt-2 mb-4" data-i18n="tools.title">
          Herramientas de Planificación
        </h2>
        <p class="text-taupe" data-i18n="tools.subtitle">
          Estima tu inversión, consulta disponibilidad en tiempo real, organiza tu checklist nupcial y diseña tu invitación digital.
        </p>
      </div>

      <!-- Interactive Tool Tabs -->
      <div class="flex flex-wrap justify-center gap-3 mb-10">
        <button onclick="switchToolTab('calc')" id="tab-btn-calc" class="tool-tab-btn px-5 py-3 rounded-full text-sm font-semibold transition-all gold-gradient text-white shadow-gold flex items-center gap-2">
          <i data-lucide="calculator" class="w-4 h-4"></i>
          <span data-i18n="tools.tabCalc">Calculadora de Presupuesto</span>
        </button>
        <button onclick="switchToolTab('calendar')" id="tab-btn-calendar" class="tool-tab-btn px-5 py-3 rounded-full text-sm font-semibold transition-all bg-champagne text-espresso border border-beige hover:border-gold flex items-center gap-2">
          <i data-lucide="calendar-check" class="w-4 h-4 text-gold"></i>
          <span data-i18n="tools.tabCal">Agenda de Disponibilidad</span>
        </button>
        <button onclick="switchToolTab('checklist')" id="tab-btn-checklist" class="tool-tab-btn px-5 py-3 rounded-full text-sm font-semibold transition-all bg-champagne text-espresso border border-beige hover:border-gold flex items-center gap-2">
          <i data-lucide="list-checks" class="w-4 h-4 text-gold"></i>
          <span data-i18n="tools.tabCheck">Checklist de Boda</span>
        </button>
        <button onclick="switchToolTab('invites')" id="tab-btn-invites" class="tool-tab-btn px-5 py-3 rounded-full text-sm font-semibold transition-all bg-champagne text-espresso border border-beige hover:border-gold flex items-center gap-2">
          <i data-lucide="mail-open" class="w-4 h-4 text-gold"></i>
          <span data-i18n="tools.tabInv">Invitaciones Digitales</span>
        </button>
      </div>

      <!-- TAB 1: BUDGET CALCULATOR -->
      <div id="tool-panel-calc" class="tool-panel rounded-3xl bg-champagne/40 border border-beige p-6 sm:p-10 shadow-luxury">
        <div class="grid lg:grid-cols-12 gap-10 items-start">
          <div class="lg:col-span-7 space-y-6">
            <div>
              <h3 class="font-serif text-3xl font-semibold text-espresso" data-i18n="calc.heading">Calculadora Orientativa desde $150 USD</h3>
              <p class="text-sm text-taupe mt-1" data-i18n="calc.desc">Selecciona desde una cena romántica o sorpresa para 2 personas hasta grandes bodas y eventos corporativos.</p>
            </div>

            <div class="grid sm:grid-cols-2 gap-5">
              <!-- Tipo de Evento -->
              <div>
                <label class="block text-xs font-semibold uppercase tracking-wider text-espresso mb-2" data-i18n="calc.eventType">Tipo de Experiencia / Evento</label>
                <select id="calc-type" onchange="calculateBudget()" class="w-full px-4 py-3 rounded-xl bg-ivory border border-beige focus:border-gold outline-none text-sm">
                  <option value="romantic">Cena Romántica Privada / Propuesta (Desde $150)</option>
                  <option value="surprise">Decoración Sorpresa Habitación / Villa / Playa (Desde $150)</option>
                  <option value="chef">Servicio de Chef Privado & Catering Íntimo (Desde $180)</option>
                  <option value="social">Cumpleaños Íntimo / Aniversario / Baby Shower (Desde $250)</option>
                  <option value="corporate">Evento Corporativo & Social (Desde $450)</option>
                  <option value="intimate">Boda Íntima / Elopement (Desde $650)</option>
                  <option value="wedding">Boda Completa & Diseño Integral (Desde $1,500)</option>
                </select>
              </div>

              <!-- Cantidad de Invitados -->
              <div>
                <label class="block text-xs font-semibold uppercase tracking-wider text-espresso mb-2">
                  <span data-i18n="calc.guests">Cantidad de Personas / Invitados:</span>
                  <span id="calc-guests-val" class="text-gold font-bold ml-1">2</span>
                </label>
                <input type="range" id="calc-guests" min="2" max="300" step="1" value="2" oninput="calculateBudget()" class="w-full accent-[#C5A059] cursor-pointer mt-2" />
                <div class="flex justify-between text-[11px] text-taupe mt-1">
                  <span>2 (Pareja)</span><span>50</span><span>150</span><span>300+</span>
                </div>
              </div>

              <!-- Nivel de Decoración -->
              <div>
                <label class="block text-xs font-semibold uppercase tracking-wider text-espresso mb-2" data-i18n="calc.decorLevel">Tipo de Decoración</label>
                <select id="calc-decor" onchange="calculateBudget()" class="w-full px-4 py-3 rounded-xl bg-ivory border border-beige focus:border-gold outline-none text-sm">
                  <option value="intimate" selected>Detalle Íntimo / Romántico (Velas, Pétalos, Mesa para 2) (+$0)</option>
                  <option value="essential">Esencial Elegante (+$120)</option>
                  <option value="floral">Floral & Romántico (+$350)</option>
                  <option value="luxury">Lujo & Alta Costura (+$850)</option>
                </select>
              </div>

              <!-- Lugar del Evento -->
              <div>
                <label class="block text-xs font-semibold uppercase tracking-wider text-espresso mb-2" data-i18n="calc.venue">Lugar del Evento</label>
                <select id="calc-venue" onchange="calculateBudget()" class="w-full px-4 py-3 rounded-xl bg-ivory border border-beige focus:border-gold outline-none text-sm">
                  <option value="private" selected>Habitación / Suite / Villa Privada (+$0)</option>
                  <option value="garden">Jardín / Terraza / Restaurante (+$80)</option>
                  <option value="beach">Playa Privada / Resort (+$180)</option>
                  <option value="salon">Salón de Eventos / Iglesia (+$250)</option>
                </select>
              </div>

              <!-- Fecha Estimada -->
              <div class="sm:col-span-2">
                <label class="block text-xs font-semibold uppercase tracking-wider text-espresso mb-2" data-i18n="calc.date">Fecha Estimada</label>
                <input type="date" id="calc-date" onchange="calculateBudget()" class="w-full px-4 py-3 rounded-xl bg-ivory border border-beige focus:border-gold outline-none text-sm" />
              </div>
            </div>

            <!-- Servicios Adicionales -->
            <div>
              <label class="block text-xs font-semibold uppercase tracking-wider text-espresso mb-3" data-i18n="calc.extras">Servicios Adicionales (Opcionales)</label>
              <div class="grid sm:grid-cols-2 gap-3">
                <label class="flex items-center gap-3 p-3 rounded-xl bg-ivory border border-beige cursor-pointer hover:border-gold">
                  <input type="checkbox" value="chef" onchange="calculateBudget()" class="calc-extra accent-[#C5A059] w-4 h-4" />
                  <span class="text-sm" data-i18n="calc.ex1">Chef Privado (Menú 3 tiempos) (+$120)</span>
                </label>
                <label class="flex items-center gap-3 p-3 rounded-xl bg-ivory border border-beige cursor-pointer hover:border-gold">
                  <input type="checkbox" value="music" onchange="calculateBudget()" class="calc-extra accent-[#C5A059] w-4 h-4" />
                  <span class="text-sm" data-i18n="calc.ex2">Violín / Saxofón en Vivo (+$150)</span>
                </label>
                <label class="flex items-center gap-3 p-3 rounded-xl bg-ivory border border-beige cursor-pointer hover:border-gold">
                  <input type="checkbox" value="photo_mini" onchange="calculateBudget()" class="calc-extra accent-[#C5A059] w-4 h-4" />
                  <span class="text-sm" data-i18n="calc.ex3">Sesión de Fotografía Mini 1h (+$130)</span>
                </label>
                <label class="flex items-center gap-3 p-3 rounded-xl bg-ivory border border-beige cursor-pointer hover:border-gold">
                  <input type="checkbox" value="cake" onchange="calculateBudget()" class="calc-extra accent-[#C5A059] w-4 h-4" />
                  <span class="text-sm" data-i18n="calc.ex4">Pastel / Postres Personalizados (+$65)</span>
                </label>
                <label class="flex items-center gap-3 p-3 rounded-xl bg-ivory border border-beige cursor-pointer hover:border-gold">
                  <input type="checkbox" value="invites" onchange="calculateBudget()" class="calc-extra accent-[#C5A059] w-4 h-4" />
                  <span class="text-sm" data-i18n="calc.ex5">Invitaciones Digitales RSVP (+$45)</span>
                </label>
                <label class="flex items-center gap-3 p-3 rounded-xl bg-ivory border border-beige cursor-pointer hover:border-gold">
                  <input type="checkbox" value="coord" onchange="calculateBudget()" class="calc-extra accent-[#C5A059] w-4 h-4" />
                  <span class="text-sm" data-i18n="calc.ex6">Coordinación Día del Evento (+$200)</span>
                </label>
                <label class="flex items-center gap-3 p-3 rounded-xl bg-ivory border border-beige cursor-pointer hover:border-gold sm:col-span-2">
                  <input type="checkbox" value="photo_full" onchange="calculateBudget()" class="calc-extra accent-[#C5A059] w-4 h-4" />
                  <span class="text-sm" data-i18n="calc.ex7">Fotografía y Video Profesional Completo (+$450)</span>
                </label>
              </div>
            </div>
          </div>

          <!-- Estimate Result Card -->
          <div class="lg:col-span-5 bg-ivory rounded-3xl border border-gold/50 p-7 sm:p-8 shadow-luxury">
            <div class="flex items-center justify-between border-b border-beige pb-4 mb-5">
              <span class="text-xs uppercase tracking-widest text-gold font-semibold" data-i18n="calc.resultTag">Estimación Orientativa</span>
              <span class="text-xs px-2.5 py-1 rounded-full bg-champagne text-espresso font-medium">Desde $150 USD</span>
            </div>

            <div class="mb-6">
              <p class="text-xs text-taupe mb-1" data-i18n="calc.rangeLabel">Rango de inversión estimado:</p>
              <p id="calc-result-range" class="font-serif text-4xl sm:text-5xl font-bold text-espresso">$150 – $180</p>
            </div>

            <div class="p-4 rounded-2xl bg-champagne/70 border border-beige text-xs text-taupe leading-relaxed mb-6">
              <strong class="text-espresso block mb-1" data-i18n="calc.disclaimerTitle">Nota Importante:</strong>
              <span data-i18n="calc.disclaimer">
                Nuestras experiencias comienzan desde $150 USD. Este cálculo es orientativo según las tarifas base configuradas y no constituye una cotización definitiva; ajustamos cada propuesta a tu presupuesto y deseos.
              </span>
            </div>

            <button onclick="transferEstimateToQuote()" class="w-full py-4 px-6 rounded-full gold-gradient text-white font-semibold text-sm shadow-gold hover:opacity-95 transition-all flex items-center justify-center gap-2">
              <span data-i18n="calc.sendToQuote">Solicitar Cotización Exacta con Estos Datos</span>
              <i data-lucide="send" class="w-4 h-4"></i>
            </button>
          </div>
        </div>
      </div>

      <!-- TAB 2: AVAILABILITY CALENDAR -->
      <div id="tool-panel-calendar" class="tool-panel hidden rounded-3xl bg-champagne/40 border border-beige p-6 sm:p-10 shadow-luxury">
        <div class="grid lg:grid-cols-12 gap-10">
          <div class="lg:col-span-7">
            <div class="flex items-center justify-between mb-6">
              <div>
                <h3 class="font-serif text-3xl font-semibold text-espresso" data-i18n="cal.heading">Agenda de Disponibilidad</h3>
                <p class="text-sm text-taupe" data-i18n="cal.desc">Selecciona una fecha disponible para pre-reservarla sujeta a confirmación.</p>
              </div>
              <div class="flex items-center gap-2">
                <button onclick="changeCalendarMonth(-1)" class="p-2 rounded-full bg-ivory border border-beige hover:border-gold"><i data-lucide="chevron-left" class="w-4 h-4"></i></button>
                <span id="cal-month-label" class="font-serif text-xl font-semibold min-w-[140px] text-center">Noviembre 2026</span>
                <button onclick="changeCalendarMonth(1)" class="p-2 rounded-full bg-ivory border border-beige hover:border-gold"><i data-lucide="chevron-right" class="w-4 h-4"></i></button>
              </div>
            </div>

            <!-- Legend -->
            <div class="flex flex-wrap gap-4 text-xs mb-4">
              <span class="flex items-center gap-1.5"><span class="w-3 h-3 rounded-full bg-ivory border border-gold"></span> <span data-i18n="cal.avail">Disponible</span></span>
              <span class="flex items-center gap-1.5"><span class="w-3 h-3 rounded-full bg-amber-200 border border-amber-500"></span> <span data-i18n="cal.pending">Pendiente de Confirmación</span></span>
              <span class="flex items-center gap-1.5"><span class="w-3 h-3 rounded-full bg-rose-200 border border-rose-500"></span> <span data-i18n="cal.booked">Reservada / No Disponible</span></span>
            </div>

            <!-- Calendar Grid -->
            <div class="bg-ivory rounded-2xl border border-beige p-4">
              <div class="grid grid-cols-7 text-center text-xs font-semibold text-taupe pb-3 border-b border-beige">
                <div>Dom</div><div>Lun</div><div>Mar</div><div>Mié</div><div>Jue</div><div>Vie</div><div>Sáb</div>
              </div>
              <div id="calendar-days-grid" class="grid grid-cols-7 gap-1.5 pt-3">
                <!-- Populated by JS -->
              </div>
            </div>
          </div>

          <!-- Date Request Form -->
          <div class="lg:col-span-5 bg-ivory rounded-3xl border border-beige p-7">
            <h4 class="font-serif text-2xl font-semibold text-espresso mb-2" data-i18n="cal.formTitle">Solicitar Fecha de Evento</h4>
            <p class="text-xs text-taupe mb-5" data-i18n="cal.formSub">Para evitar duplicados, ninguna fecha queda bloqueada definitivamente hasta que nuestro equipo confirme tu solicitud.</p>

            <form onsubmit="submitDateRequest(event)" class="space-y-4">
              <div>
                <label class="block text-xs font-semibold uppercase text-espresso mb-1" data-i18n="cal.selectedDate">Fecha Seleccionada</label>
                <input type="text" id="req-cal-date" readonly required placeholder="Haz clic en un día del calendario" class="w-full px-4 py-2.5 rounded-xl bg-champagne/60 border border-gold/50 text-sm font-semibold text-espresso outline-none" />
              </div>
              <div>
                <label class="block text-xs font-semibold uppercase text-espresso mb-1" data-i18n="form.name">Nombre Completo</label>
                <input type="text" id="req-cal-name" required class="w-full px-4 py-2.5 rounded-xl bg-ivory border border-beige focus:border-gold text-sm outline-none" />
              </div>
              <div>
                <label class="block text-xs font-semibold uppercase text-espresso mb-1">WhatsApp / Teléfono</label>
                <input type="tel" id="req-cal-phone" required placeholder="+1 (809) 000-0000" class="w-full px-4 py-2.5 rounded-xl bg-ivory border border-beige focus:border-gold text-sm outline-none" />
              </div>
              <div>
                <label class="block text-xs font-semibold uppercase text-espresso mb-1" data-i18n="form.eventType">Tipo de Evento</label>
                <select id="req-cal-type" class="w-full px-4 py-2.5 rounded-xl bg-ivory border border-beige focus:border-gold text-sm outline-none">
                  <option value="Boda">Boda</option>
                  <option value="Cumpleaños / Gala">Cumpleaños / Gala</option>
                  <option value="Baby Shower">Baby Shower</option>
                  <option value="Evento Corporativo">Evento Corporativo</option>
                </select>
              </div>
              <button type="submit" class="w-full py-3.5 rounded-full gold-gradient text-white font-semibold text-sm shadow-gold hover:opacity-95 transition-all">
                <span data-i18n="cal.submit">Solicitar Bloqueo de Fecha</span>
              </button>
            </form>
          </div>
        </div>
      </div>

      <!-- TAB 3: WEDDING CHECKLIST -->
      <div id="tool-panel-checklist" class="tool-panel hidden rounded-3xl bg-champagne/40 border border-beige p-6 sm:p-10 shadow-luxury">
        <div class="flex flex-col md:flex-row md:items-center justify-between gap-4 mb-8">
          <div>
            <h3 class="font-serif text-3xl font-semibold text-espresso" data-i18n="check.heading">Lista de Tareas para Organizar tu Boda</h3>
            <p class="text-sm text-taupe" data-i18n="check.desc">Marca tus avances por categoría y agrega tus propios pendientes personalizados.</p>
          </div>
          <div class="bg-ivory px-5 py-3 rounded-2xl border border-beige min-w-[220px]">
            <div class="flex justify-between text-xs font-semibold mb-1.5">
              <span data-i18n="check.progress">Progreso General</span>
              <span id="checklist-percent" class="text-gold">0%</span>
            </div>
            <div class="w-full h-2 bg-champagne rounded-full overflow-hidden">
              <div id="checklist-bar" class="h-full gold-gradient transition-all duration-300" style="width: 0%"></div>
            </div>
          </div>
        </div>

        <!-- Add Custom Task -->
        <form onsubmit="addChecklistTask(event)" class="flex flex-col sm:flex-row gap-3 mb-8">
          <select id="new-task-cat" class="px-4 py-3 rounded-xl bg-ivory border border-beige text-sm outline-none focus:border-gold">
            <option value="Vestido">Vestido & Attire</option>
            <option value="Lugar">Lugar / Venue</option>
            <option value="Invitaciones">Invitaciones</option>
            <option value="Decoración">Decoración</option>
            <option value="Fotografía">Fotografía & Video</option>
            <option value="Música">Música & Entretenimiento</option>
            <option value="Banquete">Banquete & Pastel</option>
            <option value="Ceremonia">Ceremonia</option>
            <option value="Otros">Otros Detalles</option>
          </select>
          <input type="text" id="new-task-text" required placeholder="Ej: Prueba de maquillaje y peinado..." class="flex-1 px-4 py-3 rounded-xl bg-ivory border border-beige text-sm outline-none focus:border-gold" />
          <button type="submit" class="px-6 py-3 rounded-xl gold-gradient text-white font-semibold text-sm shadow-gold whitespace-nowrap">
            + <span data-i18n="check.addBtn">Agregar Tarea</span>
          </button>
        </form>

        <div id="checklist-container" class="grid md:grid-cols-3 gap-6">
          <!-- Populated via JS -->
        </div>
      </div>

      <!-- TAB 4: DIGITAL INVITATIONS DESIGNER -->
      <div id="tool-panel-invites" class="tool-panel hidden rounded-3xl bg-champagne/40 border border-beige p-6 sm:p-10 shadow-luxury">
        <div class="grid lg:grid-cols-12 gap-10 items-center">
          <div class="lg:col-span-6 space-y-4">
            <span class="text-xs uppercase tracking-widest text-gold font-semibold" data-i18n="inv.tag">Papelería Digital de Lujo</span>
            <h3 class="font-serif text-3xl font-semibold text-espresso" data-i18n="inv.heading">Diseñador de Invitaciones Digitales</h3>
            <p class="text-sm text-taupe" data-i18n="inv.desc">Personaliza una vista previa en tiempo real para tus invitados con confirmación de asistencia integrada.</p>

            <div class="grid sm:grid-cols-2 gap-4 pt-2">
              <div>
                <label class="block text-xs font-semibold uppercase text-espresso mb-1" data-i18n="inv.couple">Nombres de Novios / Anfitrión</label>
                <input type="text" id="inv-couple" value="Camila & Alejandro" oninput="updateInvitationPreview()" class="w-full px-4 py-2.5 rounded-xl bg-ivory border border-beige text-sm outline-none focus:border-gold" />
              </div>
              <div>
                <label class="block text-xs font-semibold uppercase text-espresso mb-1" data-i18n="inv.guestName">Nombre del Invitado</label>
                <input type="text" id="inv-guest" value="Sr. y Sra. Mendoza" oninput="updateInvitationPreview()" class="w-full px-4 py-2.5 rounded-xl bg-ivory border border-beige text-sm outline-none focus:border-gold" />
              </div>
              <div>
                <label class="block text-xs font-semibold uppercase text-espresso mb-1" data-i18n="inv.date">Fecha y Hora</label>
                <input type="text" id="inv-date" value="Sábado, 12 de Diciembre 2026 • 5:00 PM" oninput="updateInvitationPreview()" class="w-full px-4 py-2.5 rounded-xl bg-ivory border border-beige text-sm outline-none focus:border-gold" />
              </div>
              <div>
                <label class="block text-xs font-semibold uppercase text-espresso mb-1" data-i18n="inv.venue">Ubicación</label>
                <input type="text" id="inv-venue" value="Villa Casa de Campo, La Romana, RD" oninput="updateInvitationPreview()" class="w-full px-4 py-2.5 rounded-xl bg-ivory border border-beige text-sm outline-none focus:border-gold" />
              </div>
            </div>

            <div class="pt-3 flex flex-wrap gap-3">
              <a href="#cotizar" onclick="preselectEventType('Diseño de Invitaciones Digitales')" class="px-6 py-3 rounded-full gold-gradient text-white text-sm font-semibold shadow-gold">
                <span data-i18n="inv.orderBtn">Solicitar Diseño Personalizado</span>
              </a>
            </div>
          </div>

          <!-- Live Invitation Card Preview -->
          <div class="lg:col-span-6 flex justify-center">
            <div class="w-full max-w-md rounded-[2rem] bg-ivory border-2 border-gold/60 p-8 sm:p-10 text-center shadow-luxury relative overflow-hidden">
              <div class="absolute inset-3 border border-beige rounded-[1.5rem] pointer-events-none"></div>
              <p class="text-[11px] uppercase tracking-[0.3em] text-gold font-semibold mb-3" data-i18n="inv.cardHeader">Tenemos el honor de invitar a</p>
              <p id="prev-inv-guest" class="font-serif italic text-xl text-espresso mb-5">Sr. y Sra. Mendoza</p>
              <p class="text-xs uppercase tracking-widest text-taupe mb-2" data-i18n="inv.cardCelebrate">A celebrar la unión de</p>
              <h4 id="prev-inv-couple" class="font-serif text-4xl sm:text-5xl font-semibold text-espresso my-4 leading-tight">Camila & Alejandro</h4>
              <div class="w-16 h-px bg-gold mx-auto my-5"></div>
              <p id="prev-inv-date" class="text-sm font-medium text-espresso mb-1">Sábado, 12 de Diciembre 2026 • 5:00 PM</p>
              <p id="prev-inv-venue" class="text-xs text-taupe mb-7">Villa Casa de Campo, La Romana, RD</p>
              <button onclick="showToast('¡Confirmación de asistencia (RSVP) registrada en la vista previa!', 'success')" class="relative z-10 px-6 py-2.5 rounded-full bg-champagne border border-gold text-xs font-semibold uppercase tracking-wider text-espresso hover:bg-gold hover:text-white transition-all">
                <span data-i18n="inv.rsvpBtn">Confirmar Asistencia (RSVP)</span>
              </button>
              <p class="text-[10px] text-taupe/70 mt-5 tracking-widest uppercase">Diseño por AM Joy Wedding & Event</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- 8. TESTIMONIOS AUTORIZADOS                                            -->
  <!-- ===================================================================== -->
  <section id="testimonios" class="py-20 lg:py-28 champagne-gradient border-y border-beige/60">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center max-w-3xl mx-auto mb-14">
        <span class="text-xs uppercase tracking-[0.25em] text-gold font-semibold" data-i18n="testi.eyebrow">Historias Reales</span>
        <h2 class="font-serif text-4xl sm:text-5xl font-semibold text-espresso mt-2 mb-3" data-i18n="testi.title">
          Palabras de Nuestros Clientes
        </h2>
        <p class="text-sm text-taupe" data-i18n="testi.subtitle">
          Testimonios auténticos y autorizados de parejas y familias que confiaron en nuestro equipo.
        </p>
      </div>

      <div id="testimonials-grid" class="grid md:grid-cols-3 gap-8">
        <!-- Populated via JS -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- 9. BLOG DE INSPIRACIÓN SEO                                            -->
  <!-- ===================================================================== -->
  <section id="blog" class="py-20 lg:py-28 bg-ivory">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center max-w-3xl mx-auto mb-14">
        <span class="text-xs uppercase tracking-[0.25em] text-gold font-semibold" data-i18n="blog.eyebrow">Guía Nupcial & Tendencias</span>
        <h2 class="font-serif text-4xl sm:text-5xl font-semibold text-espresso mt-2 mb-3" data-i18n="blog.title">
          Blog de Inspiración
        </h2>
        <p class="text-taupe" data-i18n="blog.subtitle">
          Consejos expertos sobre bodas en República Dominicana, paletas de colores, locaciones y diseño de eventos.
        </p>
      </div>

      <div id="blog-grid" class="grid md:grid-cols-3 gap-8">
        <!-- Populated via JS -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- 10. PREGUNTAS FRECUENTES (FAQ)                                        -->
  <!-- ===================================================================== -->
  <section id="faq" class="py-20 bg-champagne/40 border-t border-beige/60">
    <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center mb-12">
        <span class="text-xs uppercase tracking-[0.25em] text-gold font-semibold">FAQ</span>
        <h2 class="font-serif text-4xl font-semibold text-espresso mt-2" data-i18n="faq.title">Preguntas Frecuentes</h2>
      </div>
      <div id="faq-container" class="space-y-4">
        <!-- Populated via JS -->
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- 11. SOLICITAR COTIZACIÓN Y CONTACTO                                   -->
  <!-- ===================================================================== -->
  <section id="cotizar" class="py-20 lg:py-28 bg-ivory border-t border-beige">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="grid lg:grid-cols-12 gap-12">
        <!-- Contact & Brand Info -->
        <div class="lg:col-span-5 space-y-6">
          <span class="text-xs uppercase tracking-[0.25em] text-gold font-semibold" data-i18n="contact.eyebrow">Comencemos a Soñar</span>
          <h2 class="font-serif text-4xl sm:text-5xl font-semibold text-espresso leading-tight" data-i18n="contact.title">
            Solicita tu Cotización Personalizada
          </h2>
          <p class="text-taupe leading-relaxed" data-i18n="contact.desc">
            Cuéntanos los detalles de tu celebración. Nuestro equipo preparará una propuesta exclusiva adaptada a tu visión, fecha y estilo.
          </p>

          <div class="space-y-4 pt-2">
            <div class="flex items-start gap-4 p-4 rounded-2xl bg-champagne/50 border border-beige">
              <i data-lucide="map-pin" class="w-5 h-5 text-gold shrink-0 mt-0.5"></i>
              <div>
                <p class="text-xs font-semibold uppercase tracking-wider text-espresso" data-i18n="contact.locLabel">Ubicación</p>
                <p id="contact-address-display" class="text-sm text-taupe">Santo Domingo, República Dominicana (Servicio en todo el país)</p>
              </div>
            </div>
            <div class="flex items-start gap-4 p-4 rounded-2xl bg-champagne/50 border border-beige">
              <i data-lucide="phone" class="w-5 h-5 text-gold shrink-0 mt-0.5"></i>
              <div>
                <p class="text-xs font-semibold uppercase tracking-wider text-espresso">WhatsApp & Teléfono</p>
                <p id="contact-phone-display" class="text-sm text-taupe">+1 (809) 555-0199</p>
              </div>
            </div>
            <div class="flex items-start gap-4 p-4 rounded-2xl bg-champagne/50 border border-beige">
              <i data-lucide="mail" class="w-5 h-5 text-gold shrink-0 mt-0.5"></i>
              <div>
                <p class="text-xs font-semibold uppercase tracking-wider text-espresso" data-i18n="contact.emailLabel">Correo Electrónico</p>
                <p id="contact-email-display" class="text-sm text-taupe">contacto@amjoywedding.com</p>
              </div>
            </div>
          </div>

          <!-- Social Integration -->
          <div class="pt-2">
            <p class="text-xs font-semibold uppercase tracking-wider text-espresso mb-3" data-i18n="contact.follow">Síguenos en Redes Sociales</p>
            <div class="flex gap-3">
              <a href="https://instagram.com" target="_blank" rel="noopener" class="inline-flex items-center gap-2 px-4 py-2.5 rounded-full bg-champagne border border-beige hover:border-gold text-xs font-semibold text-espresso transition-all">
                <i data-lucide="instagram" class="w-4 h-4 text-gold"></i> Instagram
              </a>
              <a href="https://facebook.com" target="_blank" rel="noopener" class="inline-flex items-center gap-2 px-4 py-2.5 rounded-full bg-champagne border border-beige hover:border-gold text-xs font-semibold text-espresso transition-all">
                <i data-lucide="facebook" class="w-4 h-4 text-gold"></i> Facebook
              </a>
            </div>
          </div>

          <!-- Voluntary Newsletter Subscription -->
          <div class="p-6 rounded-2xl bg-champagne border border-gold/40">
            <h4 class="font-serif text-xl font-semibold text-espresso mb-1" data-i18n="news.title">Novedades & Tendencias Nupciales</h4>
            <p class="text-xs text-taupe mb-3" data-i18n="news.desc">Suscríbete voluntariamente para recibir ideas exclusivas y disponibilidad de temporada.</p>
            <form onsubmit="subscribeNewsletter(event)" class="flex gap-2">
              <input type="email" id="newsletter-email" required placeholder="tu@correo.com" class="flex-1 px-3.5 py-2.5 rounded-xl bg-ivory border border-beige text-sm outline-none focus:border-gold" />
              <button type="submit" class="px-4 py-2.5 rounded-xl gold-gradient text-white text-xs font-semibold shadow-gold">
                <span data-i18n="news.btn">Suscribirme</span>
              </button>
            </form>
          </div>
        </div>

        <!-- Professional Quote Form -->
        <div class="lg:col-span-7 bg-champagne/40 border border-beige rounded-3xl p-7 sm:p-10 shadow-luxury">
          <form id="quote-form" onsubmit="submitQuoteForm(event)" class="space-y-5">
            <div class="grid sm:grid-cols-2 gap-5">
              <div>
                <label class="block text-xs font-semibold uppercase tracking-wider text-espresso mb-1.5" data-i18n="form.name">Nombre Completo *</label>
                <input type="text" id="q-name" required class="w-full px-4 py-3 rounded-xl bg-ivory border border-beige focus:border-gold text-sm outline-none" />
              </div>
              <div>
                <label class="block text-xs font-semibold uppercase tracking-wider text-espresso mb-1.5" data-i18n="form.email">Correo Electrónico *</label>
                <input type="email" id="q-email" required class="w-full px-4 py-3 rounded-xl bg-ivory border border-beige focus:border-gold text-sm outline-none" />
              </div>
              <div>
                <label class="block text-xs font-semibold uppercase tracking-wider text-espresso mb-1.5">WhatsApp *</label>
                <input type="tel" id="q-whatsapp" required placeholder="+1 (809) 000-0000" class="w-full px-4 py-3 rounded-xl bg-ivory border border-beige focus:border-gold text-sm outline-none" />
              </div>
              <div>
                <label class="block text-xs font-semibold uppercase tracking-wider text-espresso mb-1.5" data-i18n="form.eventType">Tipo de Evento *</label>
                <select id="q-type" class="w-full px-4 py-3 rounded-xl bg-ivory border border-beige focus:border-gold text-sm outline-none">
                  <option value="Cena Romántica Privada / Propuesta">Cena Romántica Privada / Propuesta (Desde $150)</option>
                  <option value="Decoración Sorpresa (Habitación / Villa / Playa)">Decoración Sorpresa (Habitación / Villa / Playa)</option>
                  <option value="Servicio de Chef Privado & Catering Íntimo">Servicio de Chef Privado & Catering Íntimo</option>
                  <option value="Cumpleaños Íntimo / Aniversario / Baby Shower">Cumpleaños Íntimo / Aniversario / Baby Shower</option>
                  <option value="Evento Corporativo & Social">Evento Corporativo & Social</option>
                  <option value="Boda Íntima / Elopement">Boda Íntima / Elopement</option>
                  <option value="Boda Completa & Diseño Integral">Boda Completa & Diseño Integral</option>
                  <option value="Diseño de Invitaciones Digitales">Diseño de Invitaciones Digitales</option>
                </select>
              </div>
              <div>
                <label class="block text-xs font-semibold uppercase tracking-wider text-espresso mb-1.5" data-i18n="form.date">Fecha del Evento</label>
                <input type="date" id="q-date" class="w-full px-4 py-3 rounded-xl bg-ivory border border-beige focus:border-gold text-sm outline-none" />
              </div>
              <div>
                <label class="block text-xs font-semibold uppercase tracking-wider text-espresso mb-1.5" data-i18n="form.venue">Lugar / Ciudad</label>
                <input type="text" id="q-venue" placeholder="Ej: Habitación, Villa, Santo Domingo, Punta Cana" class="w-full px-4 py-3 rounded-xl bg-ivory border border-beige focus:border-gold text-sm outline-none" />
              </div>
              <div>
                <label class="block text-xs font-semibold uppercase tracking-wider text-espresso mb-1.5" data-i18n="form.guests">Cantidad de Personas / Invitados</label>
                <input type="number" id="q-guests" min="2" placeholder="2" class="w-full px-4 py-3 rounded-xl bg-ivory border border-beige focus:border-gold text-sm outline-none" />
              </div>
              <div>
                <label class="block text-xs font-semibold uppercase tracking-wider text-espresso mb-1.5" data-i18n="form.budget">Presupuesto Aproximado (USD)</label>
                <input type="text" id="q-budget" placeholder="Desde $150 USD" class="w-full px-4 py-3 rounded-xl bg-ivory border border-beige focus:border-gold text-sm outline-none" />
              </div>
            </div>

            <div>
              <label class="block text-xs font-semibold uppercase tracking-wider text-espresso mb-1.5" data-i18n="form.details">Descripción de lo que deseas *</label>
              <textarea id="q-details" rows="4" required placeholder="Cuéntanos sobre tu estilo, colores favoritos, servicios que necesitas..." class="w-full px-4 py-3 rounded-xl bg-ivory border border-beige focus:border-gold text-sm outline-none"></textarea>
            </div>

            <div class="flex items-center gap-2 text-xs text-taupe">
              <input type="checkbox" id="q-include-wishlist" checked class="accent-[#C5A059]" />
              <label for="q-include-wishlist" data-i18n="form.attachWishlist">Adjuntar mis ideas guardadas de la Lista de Deseos (<span id="form-wishlist-count">0</span>)</label>
            </div>

            <button type="submit" class="w-full py-4 rounded-full gold-gradient text-white font-semibold text-sm tracking-wide shadow-gold hover:opacity-95 transition-all flex items-center justify-center gap-2">
              <span data-i18n="form.submit">Enviar Solicitud de Cotización</span>
              <i data-lucide="sparkles" class="w-4 h-4"></i>
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- ===================================================================== -->
  <!-- FOOTER                                                                -->
  <!-- ===================================================================== -->
  <footer class="bg-espresso text-ivory/85 py-14 border-t border-gold/30">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="grid md:grid-cols-3 gap-10 pb-10 border-b border-ivory/10">
        <div>
          <span class="font-serif text-3xl font-bold text-ivory">AM Joy <span class="text-gold italic font-normal">Wedding & Event</span></span>
          <p class="font-serif italic text-lg text-beige mt-2" data-i18n="hero.slogan">
            “Donde tus sueños se convierten en momentos inolvidables”
          </p>
          <p class="text-xs text-ivory/60 mt-3 leading-relaxed">
            Wedding Planner en República Dominicana • Organización de bodas en Santo Domingo • Decoración de bodas y eventos de lujo.
          </p>
        </div>
        <div>
          <h4 class="text-xs uppercase tracking-widest text-gold font-semibold mb-4" data-i18n="footer.links">Enlaces Rápidos</h4>
          <ul class="space-y-2 text-sm text-ivory/75">
            <li><a href="#nosotros" class="hover:text-gold transition-colors" data-i18n="nav.about">Sobre Nosotros</a></li>
            <li><a href="#servicios" class="hover:text-gold transition-colors" data-i18n="nav.services">Nuestros Servicios</a></li>
            <li><a href="#galeria" class="hover:text-gold transition-colors" data-i18n="nav.gallery">Galería de Eventos</a></li>
            <li><a href="#herramientas" class="hover:text-gold transition-colors" data-i18n="nav.tools">Calculadora & Agenda</a></li>
          </ul>
        </div>
        <div>
          <h4 class="text-xs uppercase tracking-widest text-gold font-semibold mb-4" data-i18n="footer.access">Accesos Exclusivos</h4>
          <div class="space-y-3">
            <button onclick="openModal('client-portal-modal')" class="block text-sm text-ivory/80 hover:text-gold transition-colors">
              → <span data-i18n="nav.clientPortal">Portal para Clientes Confirmados</span>
            </button>
            <button onclick="openModal('admin-modal')" class="block text-sm text-ivory/80 hover:text-gold transition-colors">
              → <span data-i18n="footer.admin">Panel de Administración & Supabase SEO</span>
            </button>
          </div>
        </div>
      </div>
      <div class="pt-8 flex flex-col sm:flex-row items-center justify-between text-xs text-ivory/50 gap-4">
        <p>© 2026 AM Joy Wedding & Event. Todos los derechos reservados.</p>
        <p>Santo Domingo, República Dominicana</p>
      </div>
    </div>
  </footer>

  <!-- ===================================================================== -->
  <!-- FLOATING WHATSAPP BUTTON                                              -->
  <!-- ===================================================================== -->
  <button
    onclick="openWhatsApp()"
    aria-label="Contactar por WhatsApp"
    class="fixed bottom-6 right-6 z-40 flex items-center gap-2.5 px-5 py-3.5 rounded-full bg-[#25D366] text-white font-semibold text-sm shadow-xl hover:scale-105 transition-transform"
  >
    <svg class="w-5 h-5 fill-current" viewBox="0 0 24 24"><path d="M12.031 6.172c-3.181 0-5.767 2.586-5.768 5.766-.001 1.298.38 2.27 1.019 3.287l-.582 2.128 2.182-.573c.978.58 1.911.928 3.145.929 3.178 0 5.767-2.587 5.768-5.766.001-3.187-2.575-5.77-5.764-5.771zm3.392 8.244c-.144.405-.837.774-1.17.824-.299.045-.677.063-1.092-.069-.252-.08-.575-.187-.988-.365-1.739-.751-2.874-2.502-2.961-2.617-.087-.116-.708-.94-.708-1.793s.448-1.273.607-1.446c.159-.173.346-.217.462-.217l.332.006c.106.005.249-.04.39.298.144.347.491 1.2.534 1.287.043.087.072.188.014.304-.058.116-.087.188-.173.289l-.26.304c-.087.086-.177.18-.076.354.101.174.449.741.964 1.201.662.591 1.221.774 1.394.86s.274.072.376-.043c.101-.116.433-.506.549-.68.116-.173.231-.145.39-.087s1.011.477 1.184.564.289.13.332.202c.045.072.045.419-.1.824z"/></svg>
    <span class="hidden sm:inline">WhatsApp</span>
  </button>

  <!-- ===================================================================== -->
  <!-- MODALS (LIGHTBOX, PORTFOLIO, BLOG, WISHLIST, CLIENT PORTAL, ADMIN)    -->
  <!-- ===================================================================== -->

  <!-- 1. LIGHTBOX MODAL -->
  <div id="lightbox-modal" class="fixed inset-0 z-50 hidden bg-espresso/85 backdrop-blur-sm flex items-center justify-center p-4">
    <div class="bg-ivory rounded-3xl max-w-4xl w-full overflow-hidden shadow-2xl border border-gold/40">
      <div class="relative">
        <img id="lb-img" src="" alt="" class="w-full max-h-[65vh] object-cover" />
        <button onclick="closeModal('lightbox-modal')" class="absolute top-4 right-4 w-10 h-10 rounded-full bg-ivory/90 text-espresso flex items-center justify-center hover:bg-gold hover:text-white transition-colors">
          <i data-lucide="x" class="w-5 h-5"></i>
        </button>
      </div>
      <div class="p-6 flex flex-col sm:flex-row sm:items-center justify-between gap-4">
        <div>
          <span id="lb-cat" class="text-xs uppercase tracking-widest text-gold font-semibold"></span>
          <h3 id="lb-title" class="font-serif text-2xl font-semibold text-espresso"></h3>
        </div>
        <div class="flex gap-3">
          <button id="lb-wish-btn" class="px-4 py-2.5 rounded-full border border-gold text-xs font-semibold text-espresso hover:bg-champagne flex items-center gap-1.5">
            <i data-lucide="heart" class="w-4 h-4 text-gold"></i> <span>Guardar Idea</span>
          </button>
          <button onclick="shareCurrentItem()" class="px-4 py-2.5 rounded-full gold-gradient text-white text-xs font-semibold flex items-center gap-1.5">
            <i data-lucide="share-2" class="w-4 h-4"></i> <span>Compartir</span>
          </button>
        </div>
      </div>
    </div>
  </div>

  <!-- 2. PORTFOLIO PROJECT DETAIL MODAL -->
  <div id="portfolio-modal" class="fixed inset-0 z-50 hidden bg-espresso/80 backdrop-blur-sm flex items-center justify-center p-4 overflow-y-auto">
    <div class="bg-ivory rounded-3xl max-w-3xl w-full overflow-hidden shadow-2xl border border-beige my-8">
      <div class="relative h-72 sm:h-80">
        <img id="pm-img" src="" alt="" class="w-full h-full object-cover" />
        <button onclick="closeModal('portfolio-modal')" class="absolute top-4 right-4 w-10 h-10 rounded-full bg-ivory/90 text-espresso flex items-center justify-center hover:bg-gold hover:text-white">
          <i data-lucide="x" class="w-5 h-5"></i>
        </button>
      </div>
      <div class="p-6 sm:p-8 space-y-5">
        <div class="flex flex-wrap items-center justify-between gap-2">
          <span id="pm-location" class="text-xs uppercase tracking-widest text-gold font-semibold"></span>
          <div id="pm-colors" class="flex items-center gap-2"></div>
        </div>
        <h3 id="pm-title" class="font-serif text-3xl font-semibold text-espresso"></h3>
        <p id="pm-concept" class="text-sm text-taupe leading-relaxed"></p>
        <div class="p-4 rounded-2xl bg-champagne/60 border border-beige">
          <p class="text-xs font-semibold uppercase tracking-wider text-espresso mb-2">Servicios & Decoración Utilizados:</p>
          <ul id="pm-services" class="grid sm:grid-cols-2 gap-2 text-xs text-espresso/90"></ul>
        </div>
        <div class="flex justify-end gap-3 pt-2">
          <button onclick="shareCurrentItem()" class="px-5 py-2.5 rounded-full border border-beige text-xs font-semibold hover:border-gold">Compartir Proyecto</button>
          <a href="#cotizar" onclick="closeModal('portfolio-modal')" class="px-6 py-2.5 rounded-full gold-gradient text-white text-xs font-semibold shadow-gold">Solicitar Estilo Similar</a>
        </div>
      </div>
    </div>
  </div>

  <!-- 3. BLOG ARTICLE READER MODAL -->
  <div id="blog-modal" class="fixed inset-0 z-50 hidden bg-espresso/80 backdrop-blur-sm flex items-center justify-center p-4 overflow-y-auto">
    <div class="bg-ivory rounded-3xl max-w-3xl w-full overflow-hidden shadow-2xl border border-beige my-8">
      <div class="relative h-64">
        <img id="bm-img" src="" alt="" class="w-full h-full object-cover" />
        <button onclick="closeModal('blog-modal')" class="absolute top-4 right-4 w-10 h-10 rounded-full bg-ivory/90 text-espresso flex items-center justify-center">
          <i data-lucide="x" class="w-5 h-5"></i>
        </button>
      </div>
      <div class="p-6 sm:p-10 space-y-4">
        <span id="bm-tag" class="text-xs uppercase tracking-widest text-gold font-semibold"></span>
        <h3 id="bm-title" class="font-serif text-3xl sm:text-4xl font-semibold text-espresso"></h3>
        <div id="bm-body" class="text-sm sm:text-base text-taupe leading-relaxed space-y-4"></div>
      </div>
    </div>
  </div>

  <!-- 4. WISHLIST MODAL -->
  <div id="wishlist-modal" class="fixed inset-0 z-50 hidden bg-espresso/75 backdrop-blur-sm flex items-center justify-center p-4">
    <div class="bg-ivory rounded-3xl max-w-2xl w-full p-6 sm:p-8 shadow-2xl border border-beige max-h-[85vh] flex flex-col">
      <div class="flex items-center justify-between border-b border-beige pb-4 mb-4">
        <div>
          <h3 class="font-serif text-2xl font-semibold text-espresso">Tu Lista de Deseos e Inspiración</h3>
          <p class="text-xs text-taupe">Guarda tus estilos favoritos de la galería para adjuntarlos a tu cotización.</p>
        </div>
        <button onclick="closeModal('wishlist-modal')" class="p-2 rounded-full hover:bg-champagne"><i data-lucide="x" class="w-5 h-5"></i></button>
      </div>
      <div id="wishlist-items-container" class="flex-1 overflow-y-auto space-y-3 pr-1">
        <!-- Populated via JS -->
      </div>
      <div class="pt-4 border-t border-beige mt-4 flex justify-between items-center">
        <button onclick="clearWishlist()" class="text-xs text-taupe hover:text-rose-600">Vaciar lista</button>
        <a href="#cotizar" onclick="closeModal('wishlist-modal')" class="px-6 py-3 rounded-full gold-gradient text-white text-xs font-semibold shadow-gold">
          Cotizar con estas Ideas
        </a>
      </div>
    </div>
  </div>

  <!-- 5. CONFIRMED CLIENT PORTAL MODAL -->
  <div id="client-portal-modal" class="fixed inset-0 z-50 hidden bg-espresso/80 backdrop-blur-sm flex items-center justify-center p-4 overflow-y-auto">
    <div class="bg-ivory rounded-3xl max-w-3xl w-full p-6 sm:p-8 shadow-2xl border border-gold/50 my-8">
      <div class="flex items-center justify-between border-b border-beige pb-4 mb-6">
        <div class="flex items-center gap-2.5">
          <i data-lucide="sparkles" class="w-5 h-5 text-gold"></i>
          <h3 class="font-serif text-2xl font-semibold text-espresso">Portal Exclusivo para Clientes</h3>
        </div>
        <button onclick="closeModal('client-portal-modal')" class="p-2 rounded-full hover:bg-champagne"><i data-lucide="x" class="w-5 h-5"></i></button>
      </div>

      <!-- Login View -->
      <div id="client-login-view" class="max-w-md mx-auto py-6 text-center space-y-4">
        <p class="text-sm text-taupe">Ingresa tu código privado de evento para consultar el avance de planificación, servicios contratados y fechas clave.</p>
        <div class="p-3 rounded-xl bg-champagne/70 border border-beige text-xs text-espresso">
          Código de demostración disponible: <strong class="text-gold tracking-wider">BODA2026</strong>
        </div>
        <form onsubmit="loginClientPortal(event)" class="space-y-3">
          <input type="text" id="client-access-code" required placeholder="Ej: BODA2026" class="w-full px-4 py-3 rounded-xl bg-ivory border border-beige text-center font-semibold uppercase tracking-widest outline-none focus:border-gold" />
          <button type="submit" class="w-full py-3.5 rounded-full gold-gradient text-white font-semibold text-sm shadow-gold">Acceder a Mi Evento</button>
        </form>
      </div>

      <!-- Authenticated Client Dashboard View -->
      <div id="client-dashboard-view" class="hidden space-y-6">
        <div class="p-5 rounded-2xl bg-champagne border border-gold/40 flex flex-col sm:flex-row sm:items-center justify-between gap-4">
          <div>
            <span class="text-xs uppercase tracking-widest text-gold font-semibold">Evento Confirmado</span>
            <h4 class="font-serif text-3xl font-semibold text-espresso">Boda Camila & Alejandro</h4>
            <p class="text-xs text-taupe mt-0.5">Fecha: 12 de Diciembre, 2026 • Villa Casa de Campo, La Romana</p>
          </div>
          <div class="text-left sm:text-right">
            <span class="text-xs font-semibold text-espresso block">Avance de Planificación</span>
            <span class="font-serif text-3xl font-bold text-gold">78%</span>
          </div>
        </div>

        <div class="grid sm:grid-cols-2 gap-5">
          <div class="p-5 rounded-2xl border border-beige bg-ivory">
            <h5 class="font-serif text-xl font-semibold text-espresso mb-3">Servicios Contratados</h5>
            <ul class="space-y-2 text-xs text-taupe">
              <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-gold"></i> Wedding Planning & Coordinación Integral</li>
              <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-gold"></i> Diseño Floral de Alta Costura (Ceremonia y Recepción)</li>
              <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-gold"></i> Iluminación Arquitectónica & Mobiliario Champagne</li>
              <li class="flex items-center gap-2"><i data-lucide="check" class="w-4 h-4 text-gold"></i> Invitaciones Digitales Personalizadas con RSVP</li>
            </ul>
          </div>
          <div class="p-5 rounded-2xl border border-beige bg-ivory">
            <h5 class="font-serif text-xl font-semibold text-espresso mb-3">Próximas Fechas Importantes</h5>
            <ul class="space-y-2.5 text-xs">
              <li class="flex justify-between border-b border-beige pb-1.5"><span class="font-semibold">Degustación de Menú</span><span class="text-gold">24 Nov 2026</span></li>
              <li class="flex justify-between border-b border-beige pb-1.5"><span class="font-semibold">Prueba Final de Mesa Modelo</span><span class="text-gold">02 Dic 2026</span></li>
              <li class="flex justify-between"><span class="font-semibold">Ensayo General Ceremonia</span><span class="text-gold">11 Dic 2026</span></li>
            </ul>
          </div>
        </div>

        <div class="flex justify-between items-center pt-2">
          <button onclick="logoutClientPortal()" class="text-xs text-taupe hover:text-espresso underline">Cerrar sesión de cliente</button>
          <button onclick="openWhatsApp('Hola equipo AM Joy, soy cliente confirmada (BODA2026) y deseo consultar un detalle de mi evento.')" class="px-5 py-2.5 rounded-full gold-gradient text-white text-xs font-semibold">Contactar a mi Wedding Planner</button>
        </div>
      </div>
    </div>
  </div>

  <!-- 6. PRIVATE ADMIN PANEL MODAL (WITH SUPABASE SCHEMA & SEO EXPORT) -->
  <div id="admin-modal" class="fixed inset-0 z-50 hidden bg-espresso/85 backdrop-blur-sm flex items-center justify-center p-4 overflow-y-auto">
    <div class="bg-ivory rounded-3xl max-w-5xl w-full p-6 sm:p-8 shadow-2xl border border-gold/50 my-6 max-h-[90vh] flex flex-col">
      <div class="flex items-center justify-between border-b border-beige pb-4 mb-5">
        <div class="flex items-center gap-2.5">
          <i data-lucide="shield-check" class="w-5 h-5 text-gold"></i>
          <h3 class="font-serif text-2xl font-semibold text-espresso">Panel Privado de Administración — AM Joy</h3>
        </div>
        <button onclick="closeModal('admin-modal')" class="p-2 rounded-full hover:bg-champagne"><i data-lucide="x" class="w-5 h-5"></i></button>
      </div>

      <!-- Admin Login -->
      <div id="admin-login-view" class="max-w-md mx-auto py-8 space-y-4">
        <p class="text-sm text-taupe text-center">Área exclusiva para el propietario del negocio. Gestiona precios, agenda, cotizaciones, galería, testimonios y configuración SEO/Supabase.</p>
        <div class="p-3 rounded-xl bg-champagne border border-beige text-xs text-center text-espresso">
          Credenciales Demo: Usuario <strong>admin</strong> • Contraseña <strong>amjoy2026</strong>
        </div>
        <form onsubmit="loginAdmin(event)" class="space-y-3">
          <input type="text" id="admin-user" required placeholder="Usuario (admin)" class="w-full px-4 py-3 rounded-xl bg-ivory border border-beige text-sm outline-none focus:border-gold" />
          <input type="password" id="admin-pass" required placeholder="Contraseña (amjoy2026)" class="w-full px-4 py-3 rounded-xl bg-ivory border border-beige text-sm outline-none focus:border-gold" />
          <button type="submit" class="w-full py-3.5 rounded-full gold-gradient text-white font-semibold text-sm shadow-gold">Iniciar Sesión Administrativa</button>
        </form>
      </div>

      <!-- Admin Authenticated Workspace -->
      <div id="admin-dashboard-view" class="hidden flex-1 overflow-y-auto pr-1 space-y-6">
        <!-- Admin Sub-nav -->
        <div class="flex flex-wrap gap-2 border-b border-beige pb-3">
          <button onclick="switchAdminTab('quotes')" class="admin-tab px-3.5 py-2 rounded-xl text-xs font-semibold bg-gold text-white">Cotizaciones & Clientes</button>
          <button onclick="switchAdminTab('dates')" class="admin-tab px-3.5 py-2 rounded-xl text-xs font-semibold bg-champagne text-espresso">Agenda & Reservas</button>
          <button onclick="switchAdminTab('pricing')" class="admin-tab px-3.5 py-2 rounded-xl text-xs font-semibold bg-champagne text-espresso">Tarifas & WhatsApp</button>
          <button onclick="switchAdminTab('content')" class="admin-tab px-3.5 py-2 rounded-xl text-xs font-semibold bg-champagne text-espresso">Galería & Testimonios</button>
          <button onclick="switchAdminTab('tech')" class="admin-tab px-3.5 py-2 rounded-xl text-xs font-semibold bg-champagne text-espresso">Supabase SQL & SEO</button>
        </div>

        <!-- ADMIN TAB 1: QUOTES & SUBSCRIBERS -->
        <div id="admin-panel-quotes" class="admin-panel space-y-5">
          <div class="flex items-center justify-between">
            <h4 class="font-serif text-xl font-semibold">Solicitudes de Cotización Recibidas</h4>
            <span id="admin-quotes-count" class="text-xs px-3 py-1 rounded-full bg-champagne font-semibold">0 solicitudes</span>
          </div>
          <div id="admin-quotes-list" class="space-y-3"></div>

          <div class="pt-4 border-t border-beige">
            <h4 class="font-serif text-xl font-semibold mb-2">Suscriptores Voluntarios al Boletín</h4>
            <div id="admin-subscribers-list" class="flex flex-wrap gap-2 text-xs"></div>
          </div>
        </div>

        <!-- ADMIN TAB 2: DATE REQUESTS MANAGEMENT -->
        <div id="admin-panel-dates" class="admin-panel hidden space-y-4">
          <h4 class="font-serif text-xl font-semibold">Gestión de Fechas y Reservas</h4>
          <p class="text-xs text-taupe">Confirma o rechaza solicitudes de fecha. Las fechas confirmadas bloquean automáticamente el calendario público.</p>
          <div id="admin-dates-list" class="space-y-3"></div>
        </div>

        <!-- ADMIN TAB 3: PRICING, WHATSAPP & CONTACT CONFIG -->
        <div id="admin-panel-pricing" class="admin-panel hidden space-y-5">
          <h4 class="font-serif text-xl font-semibold">Configuración de Tarifas Base (Desde $150 USD), WhatsApp y Contacto</h4>
          <form onsubmit="saveAdminSettings(event)" class="grid sm:grid-cols-2 lg:grid-cols-3 gap-4">
            <div>
              <label class="block text-xs font-semibold uppercase mb-1">Cena Romántica / Propuesta (USD)</label>
              <input type="number" id="cfg-base-romantic" class="w-full px-3.5 py-2.5 rounded-xl border border-beige text-sm" />
            </div>
            <div>
              <label class="block text-xs font-semibold uppercase mb-1">Decoración Sorpresa (USD)</label>
              <input type="number" id="cfg-base-surprise" class="w-full px-3.5 py-2.5 rounded-xl border border-beige text-sm" />
            </div>
            <div>
              <label class="block text-xs font-semibold uppercase mb-1">Servicio de Chef Privado (USD)</label>
              <input type="number" id="cfg-base-chef" class="w-full px-3.5 py-2.5 rounded-xl border border-beige text-sm" />
            </div>
            <div>
              <label class="block text-xs font-semibold uppercase mb-1">Cumpleaños / Baby Shower (USD)</label>
              <input type="number" id="cfg-base-social" class="w-full px-3.5 py-2.5 rounded-xl border border-beige text-sm" />
            </div>
            <div>
              <label class="block text-xs font-semibold uppercase mb-1">Evento Corporativo (USD)</label>
              <input type="number" id="cfg-base-corporate" class="w-full px-3.5 py-2.5 rounded-xl border border-beige text-sm" />
            </div>
            <div>
              <label class="block text-xs font-semibold uppercase mb-1">Boda Íntima / Elopement (USD)</label>
              <input type="number" id="cfg-base-intimate" class="w-full px-3.5 py-2.5 rounded-xl border border-beige text-sm" />
            </div>
            <div>
              <label class="block text-xs font-semibold uppercase mb-1">Boda Completa Integral (USD)</label>
              <input type="number" id="cfg-base-wedding" class="w-full px-3.5 py-2.5 rounded-xl border border-beige text-sm" />
            </div>
            <div>
              <label class="block text-xs font-semibold uppercase mb-1">Costo por Invitado Extra (USD)</label>
              <input type="number" id="cfg-per-guest" class="w-full px-3.5 py-2.5 rounded-xl border border-beige text-sm" />
            </div>
            <div>
              <label class="block text-xs font-semibold uppercase mb-1">Número WhatsApp Oficial</label>
              <input type="text" id="cfg-whatsapp" class="w-full px-3.5 py-2.5 rounded-xl border border-beige text-sm" />
            </div>
            <div>
              <label class="block text-xs font-semibold uppercase mb-1">Teléfono Visible en Web</label>
              <input type="text" id="cfg-phone-display" class="w-full px-3.5 py-2.5 rounded-xl border border-beige text-sm" />
            </div>
            <div>
              <label class="block text-xs font-semibold uppercase mb-1">Correo Oficial</label>
              <input type="email" id="cfg-email" class="w-full px-3.5 py-2.5 rounded-xl border border-beige text-sm" />
            </div>
            <div>
              <label class="block text-xs font-semibold uppercase mb-1">Dirección / Cobertura</label>
              <input type="text" id="cfg-address" class="w-full px-3.5 py-2.5 rounded-xl border border-beige text-sm" />
            </div>
            <div class="sm:col-span-2 lg:col-span-3">
              <button type="submit" class="px-6 py-3 rounded-full gold-gradient text-white text-xs font-semibold shadow-gold">Guardar Configuración y Actualizar Precios</button>
            </div>
          </form>
        </div>

        <!-- ADMIN TAB 4: GALLERY & TESTIMONIALS MANAGER -->
        <div id="admin-panel-content" class="admin-panel hidden space-y-6">
          <!-- Add Photo -->
          <div class="p-4 rounded-2xl bg-champagne/50 border border-beige">
            <h4 class="font-serif text-xl font-semibold mb-3">Agregar Nueva Fotografía a la Galería</h4>
            <form onsubmit="adminAddPhoto(event)" class="grid sm:grid-cols-3 gap-3">
              <input type="text" id="new-photo-title" required placeholder="Título del montaje" class="px-3.5 py-2.5 rounded-xl bg-ivory border border-beige text-xs" />
              <select id="new-photo-cat" class="px-3.5 py-2.5 rounded-xl bg-ivory border border-beige text-xs">
                <option value="Cenas románticas">Cenas románticas</option>
                <option value="Decoraciones sorpresa">Decoraciones sorpresa</option>
                <option value="Chef privado">Chef privado</option>
                <option value="Cumpleaños">Cumpleaños</option>
                <option value="Baby showers">Baby showers</option>
                <option value="Bodas elegantes">Bodas elegantes</option>
                <option value="Bodas al aire libre">Bodas al aire libre</option>
                <option value="Decoración de iglesias">Decoración de iglesias</option>
                <option value="Recepciones">Recepciones</option>
                <option value="Eventos corporativos">Eventos corporativos</option>
                <option value="Decoraciones especiales">Decoraciones especiales</option>
              </select>
              <input type="url" id="new-photo-url" required placeholder="URL de imagen (https://...)" class="px-3.5 py-2.5 rounded-xl bg-ivory border border-beige text-xs" />
              <button type="submit" class="sm:col-span-3 py-2.5 rounded-xl gold-gradient text-white text-xs font-semibold">Publicar Fotografía</button>
            </form>
          </div>

          <!-- Add Authorized Testimonial -->
          <div class="p-4 rounded-2xl bg-champagne/50 border border-beige">
            <h4 class="font-serif text-xl font-semibold mb-3">Publicar Testimonio Autorizado</h4>
            <form onsubmit="adminAddTestimonial(event)" class="grid sm:grid-cols-3 gap-3">
              <input type="text" id="new-testi-author" required placeholder="Nombre del cliente autorizado" class="px-3.5 py-2.5 rounded-xl bg-ivory border border-beige text-xs" />
              <input type="text" id="new-testi-event" required placeholder="Evento y fecha (Ej: Boda, Oct 2026)" class="px-3.5 py-2.5 rounded-xl bg-ivory border border-beige text-xs" />
              <input type="text" id="new-testi-text" required placeholder="Comentario auténtico del cliente..." class="px-3.5 py-2.5 rounded-xl bg-ivory border border-beige text-xs" />
              <button type="submit" class="sm:col-span-3 py-2.5 rounded-xl gold-gradient text-white text-xs font-semibold">Publicar Testimonio</button>
            </form>
          </div>
        </div>

        <!-- ADMIN TAB 5: SUPABASE SQL, SITEMAP.XML & ROBOTS.TXT -->
        <div id="admin-panel-tech" class="admin-panel hidden space-y-5">
          <div>
            <h4 class="font-serif text-xl font-semibold mb-1">Esquema SQL para Supabase (PostgreSQL + RLS)</h4>
            <p class="text-xs text-taupe mb-2">Listo para ejecutar en tu proyecto Supabase para producción con dominio propio (Namecheap):</p>
            <pre class="p-4 rounded-2xl bg-espresso text-champagne text-[11px] overflow-x-auto leading-relaxed">
-- Tablas principales AM Joy Wedding & Event
create table quotes (
  id uuid default gen_random_uuid() primary key,
  full_name text not null,
  email text not null,
  whatsapp text not null,
  event_type text not null,
  event_date date,
  venue text,
  guests integer,
  approx_budget text,
  description text,
  wishlist_items jsonb default '[]'::jsonb,
  created_at timestamptz default now()
);

create table availability_bookings (
  id uuid default gen_random_uuid() primary key,
  event_date date unique not null,
  client_name text not null,
  phone text not null,
  event_type text not null,
  status text check (status in ('pending', 'confirmed', 'rejected')) default 'pending',
  created_at timestamptz default now()
);

create table gallery_items (
  id uuid default gen_random_uuid() primary key,
  title text not null,
  category text not null,
  image_url text not null,
  created_at timestamptz default now()
);

create table testimonials (
  id uuid default gen_random_uuid() primary key,
  author text not null,
  event_label text not null,
  quote text not null,
  authorized boolean default true,
  created_at timestamptz default now()
);

-- Habilitar Row Level Security (RLS)
alter table quotes enable row level security;
create policy "Public can insert quotes" on quotes for insert with check (true);
create policy "Only authenticated admins view quotes" on quotes for select using (auth.role() = 'authenticated');
            </pre>
          </div>

          <div class="grid sm:grid-cols-2 gap-4">
            <div>
              <h5 class="text-xs font-semibold uppercase text-espresso mb-1">sitemap.xml (SEO Google)</h5>
              <pre class="p-3 rounded-xl bg-champagne border border-beige text-[11px] overflow-x-auto">&lt;?xml version="1.0" encoding="UTF-8"?&gt;
&lt;urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9"&gt;
  &lt;url&gt;&lt;loc&gt;https://amjoywedding.com/&lt;/loc&gt;&lt;priority&gt;1.0&lt;/priority&gt;&lt;/url&gt;
  &lt;url&gt;&lt;loc&gt;https://amjoywedding.com/#servicios&lt;/loc&gt;&lt;priority&gt;0.9&lt;/priority&gt;&lt;/url&gt;
  &lt;url&gt;&lt;loc&gt;https://amjoywedding.com/#galeria&lt;/loc&gt;&lt;priority&gt;0.8&lt;/priority&gt;&lt;/url&gt;
  &lt;url&gt;&lt;loc&gt;https://amjoywedding.com/#cotizar&lt;/loc&gt;&lt;priority&gt;0.9&lt;/priority&gt;&lt;/url&gt;
&lt;/urlset&gt;</pre>
            </div>
            <div>
              <h5 class="text-xs font-semibold uppercase text-espresso mb-1">robots.txt</h5>
              <pre class="p-3 rounded-xl bg-champagne border border-beige text-[11px] overflow-x-auto">User-agent: *
Allow: /
Sitemap: https://amjoywedding.com/sitemap.xml</pre>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- ===================================================================== -->
  <!-- JAVASCRIPT APPLICATION LOGIC                                          -->
  <!-- ===================================================================== -->
  <script>
    // -----------------------------------------------------------------------
    // 1. TRANSLATIONS DICTIONARY (SPANISH / ENGLISH)
    // -----------------------------------------------------------------------
    let currentLang = 'es';

    const i18n = {
      es: {
        'nav.home': 'Inicio',
        'nav.about': 'Sobre Nosotros',
        'nav.services': 'Servicios',
        'nav.gallery': 'Galería',
        'nav.portfolio': 'Portafolio',
        'nav.tools': 'Herramientas',
        'nav.blog': 'Blog',
        'nav.quote': 'Cotizar',
        'nav.quoteBtn': 'Cotizar',
        'nav.clientPortal': 'Portal Clientes',
        'nav.testimonials': 'Testimonios',
        'nav.faq': 'Preguntas Frecuentes',
        'hero.badge': 'República Dominicana • Luxury Event Design',
        'hero.slogan': '“Donde tus sueños se convierten en momentos inolvidables”',
        'hero.subtitle': 'Planificación integral, coordinación impecable y diseño floral de alta costura para bodas exclusivas y celebraciones memorables en Santo Domingo y toda la República Dominicana.',
        'hero.ctaQuote': 'Solicitar Cotización Personalizada',
        'hero.ctaCalc': 'Calcular Presupuesto',
        'hero.stat1': 'Experiencias a Medida',
        'hero.stat2': 'Cobertura Nacional',
        'hero.stat3': 'Atención Exclusiva',
        'about.eyebrow': 'Nuestra Esencia',
        'about.title': 'Transformamos emociones en escenarios inolvidables',
        'about.quoteCard': '“Cada detalle cuenta una historia de amor, elegancia y perfección.”',
        'about.essence': 'En <strong>AM Joy Wedding & Event</strong> somos una firma especializada en la planificación, organización, coordinación y decoración de bodas y eventos especiales. Nacimos con la vocación de acompañar a cada pareja y anfitrión con sensibilidad artística, rigor logístico y un gusto refinado por el detalle, asegurando que disfruten cada instante sin preocupaciones.',
        'about.missionTitle': 'Nuestra Misión',
        'about.missionText': 'Brindar asesoría integral, diseño exclusivo y coordinación impecable en cada boda y evento social o corporativo, superando las expectativas de nuestros clientes mediante un servicio cálido, transparente y altamente profesional.',
        'about.visionTitle': 'Nuestra Visión',
        'about.visionText': 'Consolidarnos como la empresa referente de planificación y decoración de bodas y eventos de lujo en la República Dominicana, siendo reconocidos por nuestra excelencia creativa, confianza y capacidad de convertir sueños en recuerdos eternos.',
        'services.eyebrow': 'Excelencia en Cada Etapa',
        'services.title': 'Nuestros Servicios Exclusivos',
        'services.subtitle': 'Desde cenas románticas y decoraciones sorpresa desde $150 USD hasta bodas de gala y eventos corporativos a gran escala.',
        'weddings.tag': 'Especialidad Principal',
        'weddings.title': 'Bodas de Ensueño',
        'weddings.desc': 'Ceremonias religiosas, bodas civiles, bodas íntimas (elopements), bodas destino en playa o hacienda y recepciones de gala. Cuidamos la armonía floral, iluminación arquitectónica y protocolo.',
        'weddings.b1': 'Diseño escenográfico y ambientación floral personalizada',
        'weddings.b2': 'Gestión integral de suplidores, catering y locación',
        'weddings.b3': 'Coordinación completa del ensayo y el gran día',
        'weddings.cta': 'Planificar Mi Boda',
        'social.tag': 'Experiencias Íntimas, Sociales & Corporativas',
        'social.title': 'Cenas Románticas, Sorpresas y Eventos',
        'social.desc': 'Desde cenas románticas privadas para dos, decoraciones sorpresa en habitación o villa y servicio de chef privado, hasta cumpleaños íntimos, baby showers y eventos corporativos desde $150 USD.',
        'social.b1': 'Cenas románticas, propuestas y decoración sorpresa en habitación o playa',
        'social.b2': 'Servicio de chef privado, cumpleaños íntimos y baby showers',
        'social.b3': 'Ambientación social y corporativa adaptada a cada presupuesto',
        'social.cta': 'Cotizar Experiencia Íntima o Evento',
        'gallery.eyebrow': 'Inspiración Visual',
        'gallery.title': 'Galería de Eventos',
        'gallery.hint': 'Explora por categoría, amplía cada fotografía o guárdala en tu Lista de Deseos para compartir tu estilo ideal con nuestro equipo.',
        'portfolio.eyebrow': 'Curaduría & Diseño',
        'portfolio.title': 'Portafolio de Eventos Reales',
        'portfolio.subtitle': 'Descubre el concepto creativo, paleta cromática y producción detrás de nuestras celebraciones íntimas y de gala.',
        'tools.eyebrow': 'Experiencia Digital Exclusiva',
        'tools.title': 'Herramientas de Planificación',
        'tools.subtitle': 'Estima tu inversión desde $150 USD, consulta disponibilidad en tiempo real, organiza tu checklist y diseña tu invitación digital.',
        'tools.tabCalc': 'Calculadora de Presupuesto',
        'tools.tabCal': 'Agenda de Disponibilidad',
        'tools.tabCheck': 'Checklist de Boda',
        'tools.tabInv': 'Invitaciones Digitales',
        'calc.heading': 'Calculadora Orientativa desde $150 USD',
        'calc.desc': 'Selecciona desde una cena romántica o sorpresa para 2 personas hasta grandes bodas y eventos corporativos.',
        'calc.eventType': 'Tipo de Experiencia / Evento',
        'calc.guests': 'Cantidad de Personas / Invitados:',
        'calc.decorLevel': 'Tipo de Decoración',
        'calc.venue': 'Lugar del Evento',
        'calc.date': 'Fecha Estimada',
        'calc.extras': 'Servicios Adicionales (Opcionales)',
        'calc.ex1': 'Chef Privado (Menú 3 tiempos) (+$120)',
        'calc.ex2': 'Violín / Saxofón en Vivo (+$150)',
        'calc.ex3': 'Sesión de Fotografía Mini 1h (+$130)',
        'calc.ex4': 'Pastel / Postres Personalizados (+$65)',
        'calc.ex5': 'Invitaciones Digitales RSVP (+$45)',
        'calc.ex6': 'Coordinación Día del Evento (+$200)',
        'calc.ex7': 'Fotografía y Video Profesional Completo (+$450)',
        'calc.resultTag': 'Estimación Orientativa',
        'calc.rangeLabel': 'Rango de inversión estimado:',
        'calc.disclaimerTitle': 'Nota Importante:',
        'calc.disclaimer': 'Nuestras experiencias comienzan desde $150 USD. Este cálculo es orientativo según las tarifas base configuradas y no constituye una cotización definitiva; ajustamos cada propuesta a tu presupuesto y deseos.',
        'calc.sendToQuote': 'Solicitar Cotización Exacta con Estos Datos',
        'cal.heading': 'Agenda de Disponibilidad',
        'cal.desc': 'Selecciona una fecha disponible para pre-reservarla sujeta a confirmación.',
        'cal.avail': 'Disponible',
        'cal.pending': 'Pendiente de Confirmación',
        'cal.booked': 'Reservada / No Disponible',
        'cal.formTitle': 'Solicitar Fecha de Evento',
        'cal.formSub': 'Para evitar duplicados, ninguna fecha queda bloqueada definitivamente hasta que nuestro equipo confirme tu solicitud.',
        'cal.selectedDate': 'Fecha Seleccionada',
        'cal.submit': 'Solicitar Bloqueo de Fecha',
        'check.heading': 'Lista de Tareas para Organizar tu Boda',
        'check.desc': 'Marca tus avances por categoría y agrega tus propios pendientes personalizados.',
        'check.progress': 'Progreso General',
        'check.addBtn': 'Agregar Tarea',
        'inv.tag': 'Papelería Digital de Lujo',
        'inv.heading': 'Diseñador de Invitaciones Digitales',
        'inv.desc': 'Personaliza una vista previa en tiempo real para tus invitados con confirmación de asistencia integrada.',
        'inv.couple': 'Nombres de Novios / Anfitrión',
        'inv.guestName': 'Nombre del Invitado',
        'inv.date': 'Fecha y Hora',
        'inv.venue': 'Ubicación',
        'inv.orderBtn': 'Solicitar Diseño Personalizado',
        'inv.cardHeader': 'Tenemos el honor de invitar a',
        'inv.cardCelebrate': 'A celebrar la unión de',
        'inv.rsvpBtn': 'Confirmar Asistencia (RSVP)',
        'testi.eyebrow': 'Historias Reales',
        'testi.title': 'Palabras de Nuestros Clientes',
        'testi.subtitle': 'Testimonios auténticos y autorizados de parejas y familias que confiaron en nuestro equipo.',
        'blog.eyebrow': 'Guía Nupcial & Tendencias',
        'blog.title': 'Blog de Inspiración',
        'blog.subtitle': 'Consejos expertos sobre cenas románticas, bodas en República Dominicana, paletas de colores y diseño de eventos.',
        'faq.title': 'Preguntas Frecuentes',
        'contact.eyebrow': 'Comencemos a Soñar',
        'contact.title': 'Solicita tu Cotización Personalizada',
        'contact.desc': 'Cuéntanos los detalles de tu celebración íntima o gran evento. Nuestro equipo preparará una propuesta exclusiva adaptada a tu visión y presupuesto.',
        'contact.locLabel': 'Ubicación',
        'contact.emailLabel': 'Correo Electrónico',
        'contact.follow': 'Síguenos en Redes Sociales',
        'news.title': 'Novedades & Tendencias Nupciales',
        'news.desc': 'Suscríbete voluntariamente para recibir ideas exclusivas y disponibilidad de temporada.',
        'news.btn': 'Suscribirme',
        'form.name': 'Nombre Completo *',
        'form.email': 'Correo Electrónico *',
        'form.eventType': 'Tipo de Evento *',
        'form.date': 'Fecha del Evento',
        'form.venue': 'Lugar / Ciudad',
        'form.guests': 'Cantidad de Personas / Invitados',
        'form.budget': 'Presupuesto Aproximado (USD)',
        'form.details': 'Descripción de lo que deseas *',
        'form.attachWishlist': 'Adjuntar mis ideas guardadas de la Lista de Deseos',
        'form.submit': 'Enviar Solicitud de Cotización',
        'footer.links': 'Enlaces Rápidos',
        'footer.access': 'Accesos Exclusivos',
        'footer.admin': 'Panel de Administración & Supabase SEO'
      },
      en: {
        'nav.home': 'Home',
        'nav.about': 'About Us',
        'nav.services': 'Services',
        'nav.gallery': 'Gallery',
        'nav.portfolio': 'Portfolio',
        'nav.tools': 'Planning Tools',
        'nav.blog': 'Blog',
        'nav.quote': 'Get a Quote',
        'nav.quoteBtn': 'Quote',
        'nav.clientPortal': 'Client Portal',
        'nav.testimonials': 'Testimonials',
        'nav.faq': 'FAQ',
        'hero.badge': 'Dominican Republic • Luxury Event Design',
        'hero.slogan': '“Where your dreams become unforgettable moments”',
        'hero.subtitle': 'Full-service planning, seamless coordination, and haute couture floral design for intimate experiences and memorable celebrations in Santo Domingo and across the Dominican Republic.',
        'hero.ctaQuote': 'Request Custom Quote',
        'hero.ctaCalc': 'Estimate Budget',
        'hero.stat1': 'Starting at $150',
        'hero.stat2': 'Nationwide Service',
        'hero.stat3': 'Exclusive Care',
        'about.eyebrow': 'Our Essence',
        'about.title': 'We transform emotions into unforgettable settings',
        'about.quoteCard': '“Every detail tells a story of love, elegance, and perfection.”',
        'about.essence': 'At <strong>AM Joy Wedding & Event</strong>, we are a boutique firm specializing in the planning, organization, coordination, and decoration of weddings and special events. We accompany each couple and host with artistic sensitivity, logistical precision, and refined taste so you can savor every moment worry-free.',
        'about.missionTitle': 'Our Mission',
        'about.missionText': 'To provide comprehensive guidance, exclusive design, and flawless coordination for every wedding, social, or corporate event, exceeding expectations through warm, transparent, and deeply professional service.',
        'about.visionTitle': 'Our Vision',
        'about.visionText': 'To be the leading luxury wedding and event planning and design firm in the Dominican Republic, recognized for creative excellence, trust, and turning dreams into timeless memories.',
        'services.eyebrow': 'Excellence at Every Stage',
        'services.title': 'Our Exclusive Services',
        'services.subtitle': 'From romantic dinners and surprise room setups starting at $150 USD to full-scale gala weddings and corporate events.',
        'weddings.tag': 'Signature Specialty',
        'weddings.title': 'Dream Weddings',
        'weddings.desc': 'Religious ceremonies, civil weddings, intimate elopements, beachfront or estate destination weddings, and gala receptions. We curate floral harmony, architectural lighting, and protocol.',
        'weddings.b1': 'Bespoke scenography and custom floral styling',
        'weddings.b2': 'End-to-end vendor, catering, and venue management',
        'weddings.b3': 'Full rehearsal and wedding-day coordination',
        'weddings.cta': 'Plan My Wedding',
        'social.tag': 'Intimate, Social & Corporate Experiences',
        'social.title': 'Romantic Dinners, Surprises & Events',
        'social.desc': 'From private romantic dinners for two, surprise room or villa decor, and private chef services, to intimate birthdays, baby showers, and corporate events starting at $150 USD.',
        'social.b1': 'Romantic dinners, proposals & surprise room or beach styling',
        'social.b2': 'Private chef service, intimate birthdays & baby showers',
        'social.b3': 'Social and corporate styling tailored to every budget',
        'social.cta': 'Inquire for Intimate Experience or Event',
        'gallery.eyebrow': 'Visual Inspiration',
        'gallery.title': 'Event Gallery',
        'gallery.hint': 'Browse by category, enlarge any photograph, or save it to your Wishlist to share your ideal aesthetic with our team.',
        'portfolio.eyebrow': 'Curation & Design',
        'portfolio.title': 'Real Events Portfolio',
        'portfolio.subtitle': 'Discover the creative concept, color palette, and production behind our intimate and gala celebrations.',
        'tools.eyebrow': 'Exclusive Digital Suite',
        'tools.title': 'Planning Tools',
        'tools.subtitle': 'Estimate your investment starting at $150 USD, check real-time date availability, organize your checklist, and preview your digital invitation.',
        'tools.tabCalc': 'Budget Calculator',
        'tools.tabCal': 'Availability Calendar',
        'tools.tabCheck': 'Wedding Checklist',
        'tools.tabInv': 'Digital Invitations',
        'calc.heading': 'Event Budget Estimator Starting at $150 USD',
        'calc.desc': 'Select anything from an intimate romantic dinner or surprise for 2 up to grand weddings and corporate events.',
        'calc.eventType': 'Experience / Event Type',
        'calc.guests': 'Guests / People Count:',
        'calc.decorLevel': 'Decor Tier',
        'calc.venue': 'Event Venue',
        'calc.date': 'Estimated Date',
        'calc.extras': 'Additional Services (Optional)',
        'calc.ex1': 'Private Chef (3-Course Menu) (+$120)',
        'calc.ex2': 'Live Violin / Saxophone (+$150)',
        'calc.ex3': 'Mini Photo Session 1h (+$130)',
        'calc.ex4': 'Custom Cake / Desserts (+$65)',
        'calc.ex5': 'Digital RSVP Invitations (+$45)',
        'calc.ex6': 'Event-Day Coordination (+$200)',
        'calc.ex7': 'Full Professional Photo & Video (+$450)',
        'calc.resultTag': 'Orientative Estimate',
        'calc.rangeLabel': 'Estimated investment range:',
        'calc.disclaimerTitle': 'Important Note:',
        'calc.disclaimer': 'Our experiences start at $150 USD. This calculation is orientative based on configurable base rates and does not constitute a final quote; we tailor every proposal to your budget and wishes.',
        'calc.sendToQuote': 'Request Exact Quote with These Details',
        'cal.heading': 'Availability Calendar',
        'cal.desc': 'Select an available date to request a provisional hold subject to confirmation.',
        'cal.avail': 'Available',
        'cal.pending': 'Pending Confirmation',
        'cal.booked': 'Booked / Unavailable',
        'cal.formTitle': 'Request Event Date',
        'cal.formSub': 'To prevent double bookings, no date is permanently locked until our team confirms your request.',
        'cal.selectedDate': 'Selected Date',
        'cal.submit': 'Request Date Hold',
        'check.heading': 'Wedding Planning Checklist',
        'check.desc': 'Track your progress by category and add custom tasks.',
        'check.progress': 'Overall Progress',
        'check.addBtn': 'Add Task',
        'inv.tag': 'Luxury Digital Stationery',
        'inv.heading': 'Digital Invitation Designer',
        'inv.desc': 'Customize a live preview for your guests with built-in RSVP confirmation.',
        'inv.couple': 'Couple / Host Names',
        'inv.guestName': 'Guest Name',
        'inv.date': 'Date & Time',
        'inv.venue': 'Location',
        'inv.orderBtn': 'Order Custom Design',
        'inv.cardHeader': 'We have the honor of inviting',
        'inv.cardCelebrate': 'To celebrate the wedding of',
        'inv.rsvpBtn': 'Confirm Attendance (RSVP)',
        'testi.eyebrow': 'Real Stories',
        'testi.title': 'Words From Our Clients',
        'testi.subtitle': 'Authentic, authorized testimonials from couples and families who trusted our team.',
        'blog.eyebrow': 'Bridal Guide & Trends',
        'blog.title': 'Inspiration Blog',
        'blog.subtitle': 'Expert advice on romantic dinners, Dominican Republic weddings, color palettes, and luxury event styling.',
        'faq.title': 'Frequently Asked Questions',
        'contact.eyebrow': 'Let’s Begin Dreaming',
        'contact.title': 'Request Your Custom Quote',
        'contact.desc': 'Share the details of your intimate celebration or grand event. Our team will craft an exclusive proposal tailored to your vision and budget.',
        'contact.locLabel': 'Location',
        'contact.emailLabel': 'Email Address',
        'contact.follow': 'Follow Us',
        'news.title': 'Bridal News & Trends',
        'news.desc': 'Voluntarily subscribe to receive exclusive inspiration and seasonal availability.',
        'news.btn': 'Subscribe',
        'form.name': 'Full Name *',
        'form.email': 'Email Address *',
        'form.eventType': 'Event Type *',
        'form.date': 'Event Date',
        'form.venue': 'Venue / City',
        'form.guests': 'Estimated People / Guests',
        'form.budget': 'Approximate Budget (USD)',
        'form.details': 'Describe your vision *',
        'form.attachWishlist': 'Attach saved ideas from my Wishlist',
        'form.submit': 'Submit Quote Request',
        'footer.links': 'Quick Links',
        'footer.access': 'Exclusive Access',
        'footer.admin': 'Admin Panel & Supabase SEO'
      }
    };

    function toggleLanguage() {
      currentLang = currentLang === 'es' ? 'en' : 'es';
      document.getElementById('lang-label').textContent = currentLang === 'es' ? 'EN' : 'ES';
      document.documentElement.lang = currentLang;

      document.querySelectorAll('[data-i18n]').forEach(el => {
        const key = el.getAttribute('data-i18n');
        if (i18n[currentLang][key]) {
          el.innerHTML = i18n[currentLang][key];
        }
      });

      renderServices();
      renderGalleryFilters();
      renderGallery();
      renderPortfolio();
      renderTestimonials();
      renderBlog();
      renderFAQ();
      renderChecklist();
      showToast(currentLang === 'es' ? 'Idioma cambiado a Español' : 'Language switched to English', 'info');
    }

    // -----------------------------------------------------------------------
    // 2. PERSISTENT STATE (SIMULATING SUPABASE BACKEND IN LOCALSTORAGE)
    // -----------------------------------------------------------------------
    const DEFAULT_STATE = {
      settings: {
        baseRomantic: 150,
        baseSurprise: 150,
        baseChef: 180,
        baseSocial: 250,
        baseCorporate: 450,
        baseIntimate: 650,
        baseWedding: 1500,
        perGuest: 12,
        whatsappNumber: '18095550199',
        phoneDisplay: '+1 (809) 555-0199',
        email: 'contacto@amjoywedding.com',
        address: 'Santo Domingo, República Dominicana (Servicio en todo el país)'
      },
      services: [
        {
          id: 'srv-1',
          icon: 'flame',
          priceTagEs: 'Desde $150 USD',
          priceTagEn: 'From $150 USD',
          titleEs: 'Cena Romántica Privada & Propuestas',
          titleEn: 'Romantic Private Dinner & Proposals',
          descEs: 'Montaje íntimo para dos con velas, pétalos de rosas, cristalería fina, música ambiental y opción de menú gourmet en villa, terraza o playa.',
          descEn: 'Intimate setup for two with candlelight, rose petals, fine crystalware, ambient music, and gourmet menu options in a villa, terrace, or beach.'
        },
        {
          id: 'srv-2',
          icon: 'gift',
          priceTagEs: 'Desde $150 USD',
          priceTagEn: 'From $150 USD',
          titleEs: 'Decoración Sorpresa (Habitación, Villa o Playa)',
          titleEn: 'Surprise Room, Villa or Beach Decor',
          descEs: 'Ambientación personalizada para aniversarios, cumpleaños, pedidas de mano o escapadas románticas con globos orgánicos, flores y detalles memorables.',
          descEn: 'Custom styling for anniversaries, birthdays, proposals, or romantic getaways with organic balloons, fresh florals, and memorable details.'
        },
        {
          id: 'srv-3',
          icon: 'utensils',
          priceTagEs: 'Desde $180 USD',
          priceTagEn: 'From $180 USD',
          titleEs: 'Servicio de Chef Privado & Catering Íntimo',
          titleEn: 'Private Chef & Intimate Dining',
          descEs: 'Experiencia gastronómica exclusiva en la comodidad de tu hogar, villa o Airbnb con menú de autor de 3 tiempos y servicio de mesa personalizado.',
          descEn: 'Exclusive culinary experience in the comfort of your home, villa, or Airbnb featuring a 3-course signature menu and personalized table service.'
        },
        {
          id: 'srv-4',
          icon: 'cake',
          priceTagEs: 'Desde $250 USD',
          priceTagEn: 'From $250 USD',
          titleEs: 'Cumpleaños Íntimos, Aniversarios & Baby Showers',
          titleEn: 'Intimate Birthdays, Anniversaries & Baby Showers',
          descEs: 'Celebraciones privadas y familiares diseñadas con estética champagne y dorado, estaciones temáticas, mesa de dulces y mobiliario elegante.',
          descEn: 'Private and family celebrations styled in champagne and gold aesthetics, themed stations, dessert tables, and elegant furniture.'
        },
        {
          id: 'srv-5',
          icon: 'briefcase',
          priceTagEs: 'Desde $450 USD',
          priceTagEn: 'From $450 USD',
          titleEs: 'Eventos Corporativos & Sociales',
          titleEn: 'Corporate & Social Events',
          descEs: 'Cenas empresariales, lanzamientos de marca, cócteles ejecutivos y reuniones privadas con puntualidad, protocolo y ambientación profesional.',
          descEn: 'Corporate dinners, brand launches, executive cocktails, and private gatherings delivered with punctuality, protocol, and refined styling.'
        },
        {
          id: 'srv-6',
          icon: 'heart',
          priceTagEs: 'Desde $650 USD',
          priceTagEn: 'From $650 USD',
          titleEs: 'Bodas Íntimas & Elopements',
          titleEn: 'Intimate Weddings & Elopements',
          descEs: 'Ceremonias civiles o simbólicas de formato reducido con arco floral, decoración de recepción íntima, brindis y coordinación completa.',
          descEn: 'Micro-weddings and civil or symbolic ceremonies with floral arch, intimate reception styling, toast setup, and full coordination.'
        },
        {
          id: 'srv-7',
          icon: 'crown',
          priceTagEs: 'Desde $1,500 USD',
          priceTagEn: 'From $1,500 USD',
          titleEs: 'Boda Completa & Diseño Integral',
          titleEn: 'Full Wedding Planning & Luxury Design',
          descEs: 'Planificación maestra de principio a fin, diseño floral de alta costura, iluminación arquitectónica y coordinación integral del gran día.',
          descEn: 'End-to-end master planning, haute couture floral design, architectural lighting, and full wedding-day coordination.'
        }
      ],
      gallery: [
        { id: 'g9', title: 'Cena Romántica bajo las Estrellas (2 Personas)', category: 'Cenas románticas', url: 'https://images.unsplash.com/photo-1529634806980-85c3dd6d34ac?auto=format&fit=crop&w=900&q=80' },
        { id: 'g10', title: 'Decoración Sorpresa Suite Romántica & Pétalos', category: 'Decoraciones sorpresa', url: 'https://images.unsplash.com/photo-1518199266791-5375a83190b7?auto=format&fit=crop&w=900&q=80' },
        { id: 'g11', title: 'Experiencia Gastronómica Chef Privado', category: 'Chef privado', url: 'https://images.unsplash.com/photo-1414235077428-338989a2e8c0?auto=format&fit=crop&w=900&q=80' },
        { id: 'g5', title: 'Celebración Cumpleaños Íntimo Dorado', category: 'Cumpleaños', url: 'https://images.unsplash.com/photo-1530103862676-de8c9debad1d?auto=format&fit=crop&w=900&q=80' },
        { id: 'g6', title: 'Baby Shower Marfil & Champagne', category: 'Baby showers', url: 'https://images.unsplash.com/photo-1527529482837-4698179dc6ce?auto=format&fit=crop&w=900&q=80' },
        { id: 'g1', title: 'Recepción Gala Champagne & Oro', category: 'Bodas elegantes', url: 'https://images.unsplash.com/photo-1519225421980-715cb0215aed?auto=format&fit=crop&w=900&q=80' },
        { id: 'g2', title: 'Ceremonia Jardín al Atardecer', category: 'Bodas al aire libre', url: 'https://images.unsplash.com/photo-1465495976277-4387d4b0b4c6?auto=format&fit=crop&w=900&q=80' },
        { id: 'g3', title: 'Pasillo Nupcial Floral en Iglesia', category: 'Decoración de iglesias', url: 'https://images.unsplash.com/photo-1519741497674-611481863552?auto=format&fit=crop&w=900&q=80' },
        { id: 'g4', title: 'Mesa Imperial con Candelabros', category: 'Recepciones', url: 'https://images.unsplash.com/photo-1507504031003-b417219a0fde?auto=format&fit=crop&w=900&q=80' },
        { id: 'g7', title: 'Cena de Gala Corporativa', category: 'Eventos corporativos', url: 'https://images.unsplash.com/photo-1511795409834-ef04bbd61622?auto=format&fit=crop&w=900&q=80' },
        { id: 'g8', title: 'Instalación Floral Aérea', category: 'Decoraciones especiales', url: 'https://images.unsplash.com/photo-1478146896981-b80fe463b330?auto=format&fit=crop&w=900&q=80' }
      ],
      portfolio: [
        {
          id: 'p0',
          titleEs: 'Cena Romántica Privada & Propuesta en Terraza',
          titleEn: 'Private Romantic Dinner & Terrace Proposal',
          location: 'Santo Domingo, RD',
          conceptEs: 'Experiencia íntima para 2 personas con sendero de velas, arreglo floral en tonos marfil y champagne, y menú privado de 3 tiempos.',
          conceptEn: 'Intimate experience for 2 featuring a candlelit pathway, ivory and champagne florals, and a private 3-course dinner.',
          colors: ['#FFFDF9', '#E6D5B8', '#C5A059'],
          services: ['Montaje Romántico Privado', 'Servicio de Chef Privado', 'Velas & Pétalos Naturales', 'Música Ambiental'],
          url: 'https://images.unsplash.com/photo-1529634806980-85c3dd6d34ac?auto=format&fit=crop&w=1000&q=80'
        },
        {
          id: 'p1',
          titleEs: 'Boda Real en Zona Colonial',
          titleEn: 'Royal Wedding in Zona Colonial',
          location: 'Santo Domingo, RD',
          conceptEs: 'Una fusión romántica entre arquitectura histórica de piedra coralina, miles de velas cálidas y rosas blancas jardín.',
          conceptEn: 'A romantic fusion of historic coral-stone architecture, warm candlelight, and white garden roses.',
          colors: ['#FFFDF9', '#E6D5B8', '#C5A059'],
          services: ['Full Wedding Planning', 'Diseño Floral & Candelabros', 'Iluminación Arquitectónica', 'Coordinación Protocolar'],
          url: 'https://images.unsplash.com/photo-1519225421980-715cb0215aed?auto=format&fit=crop&w=1000&q=80'
        },
        {
          id: 'p2',
          titleEs: 'Celebración Sorpresa & Cumpleaños Privado en Villa',
          titleEn: 'Surprise Celebration & Private Villa Birthday',
          location: 'Punta Cana / La Romana, RD',
          conceptEs: 'Decoración sorpresa en villa privada con mesa imperial íntima, detalles personalizados en dorado y cena preparada por chef en sitio.',
          conceptEn: 'Surprise private villa setup with an intimate imperial table, custom gold accents, and an on-site private chef dinner.',
          colors: ['#F7EFE5', '#D4AF37', '#2C2420'],
          services: ['Decoración Sorpresa en Villa', 'Chef Privado en Sitio', 'Mesa Temática & Pastel', 'Fotografía Mini'],
          url: 'https://images.unsplash.com/photo-1530103862676-de8c9debad1d?auto=format&fit=crop&w=1000&q=80'
        }
      ],
      testimonials: [
        {
          id: 't0',
          author: 'Carlos & Daniela M.',
          event: 'Cena Romántica & Propuesta • 2026',
          textEs: '“Contraté una cena romántica sorpresa con chef privado y decoración de velas. Por un precio súper accesible lograron un montaje de revista que mi prometida jamás olvidará.”',
          textEn: '“I booked a surprise romantic dinner with a private chef and candle decor. At a very accessible rate, they created a magazine-worthy setup my fiancée will never forget.”'
        },
        {
          id: 't1',
          author: 'Valeria & Sebastián R.',
          event: 'Boda en Santo Domingo • 2026',
          textEs: '“AM Joy superó cada una de nuestras expectativas. Entrar al salón y ver nuestro sueño hecho realidad en cada flor y cada vela fue mágico. Pudimos disfrutar nuestra boda al 100%.”',
          textEn: '“AM Joy exceeded every single expectation. Walking into the ballroom and seeing our dream come alive in every flower and candle was pure magic.”'
        },
        {
          id: 't2',
          author: 'Dra. Carolina Méndez',
          event: 'Cumpleaños Íntimo & Cena Familiar • 2026',
          textEs: '“Nos encantó que se adaptaran exactamente al tamaño de nuestra reunión familiar con la misma elegancia y dedicación de un gran evento.”',
          textEn: '“We loved how they adapted to our intimate family gathering with the exact same elegance and dedication as a grand event.”'
        }
      ],
      bookings: [
        { id: 'b1', date: '2026-11-21', client: 'Reserva Confirmada', phone: '***', type: 'Boda', status: 'confirmed' },
        { id: 'b2', date: '2026-12-12', client: 'Camila & Alejandro', phone: '+1 809-555-0144', type: 'Boda', status: 'confirmed' },
        { id: 'b3', date: '2026-12-19', client: 'Sofía Martínez', phone: '+1 809-555-0188', type: 'Cena Romántica', status: 'pending' }
      ],
      quotes: [],
      subscribers: ['invitada.vip@ejemplo.com'],
      wishlist: [],
      checklist: [
        { id: 'c1', cat: 'Lugar', text: 'Definir fecha tentativa y visitar locaciones en Santo Domingo / Playa', done: true },
        { id: 'c2', cat: 'Decoración', text: 'Elegir paleta de colores (Champagne, Marfil, Dorado) y estilo floral', done: true },
        { id: 'c3', cat: 'Vestido', text: 'Primera cita de selección de vestido de novia y accesorios', done: false },
        { id: 'c4', cat: 'Ceremonia', text: 'Confirmar reserva de iglesia o juez civil y requisitos legales', done: false },
        { id: 'c5', cat: 'Invitaciones', text: 'Diseñar invitaciones digitales con pase personalizado y RSVP', done: false },
        { id: 'c6', cat: 'Fotografía', text: 'Contratar fotografía editorial y cinematografía de boda', done: false },
        { id: 'c7', cat: 'Banquete', text: 'Degustación de menú, coctelería de autor y diseño de pastel', done: false },
        { id: 'c8', cat: 'Música', text: 'Definir música de ceremonia, hora loca y primer baile', done: false },
        { id: 'c9', cat: 'Otros', text: 'Confirmar cronograma maestro con AM Joy Wedding & Event', done: false }
      ]
    };

    let appState = loadState();

    function loadState() {
      try {
        const saved = localStorage.getItem('amjoy_luxury_state_v2');
        if (saved) {
          const parsed = JSON.parse(saved);
          return {
            ...DEFAULT_STATE,
            ...parsed,
            settings: { ...DEFAULT_STATE.settings, ...(parsed.settings || {}) }
          };
        }
      } catch (e) {
        console.warn('Storage fallback active', e);
      }
      return JSON.parse(JSON.stringify(DEFAULT_STATE));
    }

    function saveState() {
      try {
        localStorage.setItem('amjoy_luxury_state_v2', JSON.stringify(appState));
      } catch (e) {
        console.warn('Could not persist state', e);
      }
    }

    // -----------------------------------------------------------------------
    // 3. UI HELPERS (TOAST NOTIFICATIONS & MODALS)
    // -----------------------------------------------------------------------
    function showToast(message, type = 'success') {
      const container = document.getElementById('toast-container');
      const toast = document.createElement('div');
      const borderColor = type === 'error' ? 'border-rose-400' : 'border-gold';
      toast.className = `pointer-events-auto bg-ivory border ${borderColor} rounded-2xl p-4 shadow-luxury flex items-start gap-3 fade-in`;
      toast.innerHTML = `
        <i data-lucide="${type === 'error' ? 'alert-circle' : 'sparkles'}" class="w-5 h-5 text-gold shrink-0 mt-0.5"></i>
        <p class="text-xs sm:text-sm text-espresso font-medium leading-snug">${message}</p>
      `;
      container.appendChild(toast);
      lucide.createIcons();
      setTimeout(() => {
        toast.style.opacity = '0';
        toast.style.transition = 'opacity 0.3s ease';
        setTimeout(() => toast.remove(), 300);
      }, 4200);
    }

    function openModal(id) {
      document.getElementById(id).classList.remove('hidden');
      if (id === 'wishlist-modal') renderWishlistModal();
      if (id === 'admin-modal') renderAdminPanels();
      lucide.createIcons();
    }

    function closeModal(id) {
      document.getElementById(id).classList.add('hidden');
    }

    function toggleMobileMenu() {
      document.getElementById('mobile-menu').classList.toggle('hidden');
    }

    function openWhatsApp(customMessage) {
      const defaultMsg = currentLang === 'es'
        ? 'Hola, estoy interesado/a en los servicios de AM Joy Wedding & Event. Me gustaría recibir información sobre sus paquetes y disponibilidad'
        : 'Hello, I am interested in the services of AM Joy Wedding & Event. I would like to receive information about your packages and availability';
      const text = encodeURIComponent(customMessage || defaultMsg);
      const phone = appState.settings.whatsappNumber.replace(/\D/g, '');
      window.open(`https://wa.me/${phone}?text=${text}`, '_blank', 'noopener');
    }

    // -----------------------------------------------------------------------
    // 4. RENDER DYNAMIC SECTIONS (SERVICES, GALLERY, PORTFOLIO, TESTIMONIALS)
    // -----------------------------------------------------------------------
    function renderServices() {
      const grid = document.getElementById('services-grid');
      grid.innerHTML = appState.services.map(srv => `
        <div class="p-8 rounded-3xl bg-ivory border border-beige hover:border-gold/70 shadow-luxury transition-all group flex flex-col justify-between">
          <div>
            <div class="flex items-center justify-between mb-6">
              <div class="w-12 h-12 rounded-2xl bg-champagne border border-gold/40 flex items-center justify-center group-hover:bg-gold group-hover:text-white transition-colors">
                <i data-lucide="${srv.icon}" class="w-6 h-6 text-gold group-hover:text-white"></i>
              </div>
              <span class="px-3 py-1 rounded-full bg-champagne border border-gold/30 text-xs font-bold text-espresso">
                ${currentLang === 'es' ? (srv.priceTagEs || 'Desde $150 USD') : (srv.priceTagEn || 'From $150 USD')}
              </span>
            </div>
            <h3 class="font-serif text-2xl font-semibold text-espresso mb-3">
              ${currentLang === 'es' ? srv.titleEs : srv.titleEn}
            </h3>
            <p class="text-sm text-taupe leading-relaxed">
              ${currentLang === 'es' ? srv.descEs : srv.descEn}
            </p>
          </div>
          <div class="pt-6 mt-6 border-t border-beige/60">
            <a href="#cotizar" onclick="preselectEventType('${srv.titleEs}')" class="inline-flex items-center gap-1.5 text-xs font-semibold uppercase tracking-wider text-gold hover:text-espresso transition-colors">
              <span>${currentLang === 'es' ? 'Solicitar información' : 'Inquire Now'}</span>
              <i data-lucide="arrow-up-right" class="w-4 h-4"></i>
            </a>
          </div>
        </div>
      `).join('');
      lucide.createIcons();
    }

    let selectedGalleryCat = 'Todas';
    const GALLERY_CATEGORIES = [
      'Todas',
      'Cenas románticas',
      'Decoraciones sorpresa',
      'Chef privado',
      'Cumpleaños',
      'Baby showers',
      'Bodas elegantes',
      'Bodas al aire libre',
      'Decoración de iglesias',
      'Recepciones',
      'Eventos corporativos',
      'Decoraciones especiales'
    ];

    function renderGalleryFilters() {
      const container = document.getElementById('gallery-filters');
      container.innerHTML = GALLERY_CATEGORIES.map(cat => {
        const active = selectedGalleryCat === cat;
        const label = (cat === 'Todas' && currentLang === 'en') ? 'All Categories' : cat;
        return `
          <button onclick="filterGallery('${cat}')" class="px-4 py-2 rounded-full text-xs font-semibold transition-all ${
            active ? 'gold-gradient text-white shadow-gold' : 'bg-champagne/70 text-espresso border border-beige hover:border-gold'
          }">
            ${label}
          </button>
        `;
      }).join('');
    }

    function filterGallery(cat) {
      selectedGalleryCat = cat;
      renderGalleryFilters();
      renderGallery();
    }

    function renderGallery() {
      const grid = document.getElementById('gallery-grid');
      const items = selectedGalleryCat === 'Todas'
        ? appState.gallery
        : appState.gallery.filter(item => item.category === selectedGalleryCat);

      grid.innerHTML = items.map(item => {
        const isSaved = appState.wishlist.some(w => w.id === item.id);
        return `
          <div class="group relative rounded-3xl overflow-hidden bg-champagne border border-beige shadow-luxury aspect-[4/5]">
            <img
              src="${item.url}"
              onerror="this.src='https://placehold.co/600x750/F7EFE5/2C2420?text=AM+Joy+Gallery'"
              alt="${item.title}"
              onclick="openLightbox('${item.id}')"
              class="w-full h-full object-cover cursor-pointer group-hover:scale-105 transition-transform duration-700"
            />
            <div class="absolute inset-0 bg-gradient-to-t from-espresso/85 via-espresso/20 to-transparent opacity-90 sm:opacity-0 sm:group-hover:opacity-100 transition-opacity duration-300 flex flex-col justify-between p-5">
              <div class="flex justify-end gap-2">
                <button onclick="toggleWishlist('${item.id}')" class="w-9 h-9 rounded-full bg-ivory/95 flex items-center justify-center shadow hover:scale-105 transition-transform" title="Guardar en Lista de Deseos">
                  <i data-lucide="heart" class="w-4 h-4 ${isSaved ? 'fill-gold text-gold' : 'text-espresso'}"></i>
                </button>
                <button onclick="openLightbox('${item.id}')" class="w-9 h-9 rounded-full bg-ivory/95 flex items-center justify-center shadow hover:scale-105 transition-transform" title="Ampliar">
                  <i data-lucide="maximize-2" class="w-4 h-4 text-espresso"></i>
                </button>
              </div>
              <div onclick="openLightbox('${item.id}')" class="cursor-pointer">
                <span class="text-[10px] uppercase tracking-widest text-beige block mb-1">${item.category}</span>
                <h4 class="font-serif text-xl text-white font-semibold leading-snug">${item.title}</h4>
              </div>
            </div>
          </div>
        `;
      }).join('');
      lucide.createIcons();
    }

    let currentSharedTitle = '';

    function openLightbox(id) {
      const item = appState.gallery.find(g => g.id === id);
      if (!item) return;
      currentSharedTitle = item.title;
      document.getElementById('lb-img').src = item.url;
      document.getElementById('lb-cat').textContent = item.category;
      document.getElementById('lb-title').textContent = item.title;
      document.getElementById('lb-wish-btn').onclick = () => toggleWishlist(item.id);
      openModal('lightbox-modal');
    }

    function toggleWishlist(id) {
      const item = appState.gallery.find(g => g.id === id);
      if (!item) return;
      const idx = appState.wishlist.findIndex(w => w.id === id);
      if (idx > -1) {
        appState.wishlist.splice(idx, 1);
        showToast('Eliminado de tu Lista de Deseos', 'info');
      } else {
        appState.wishlist.push(item);
        showToast('¡Guardado en tu Lista de Deseos!', 'success');
      }
      saveState();
      updateWishlistBadges();
      renderGallery();
    }

    function updateWishlistBadges() {
      const count = appState.wishlist.length;
      document.getElementById('wishlist-badge').textContent = count;
      document.getElementById('form-wishlist-count').textContent = count;
    }

    function renderWishlistModal() {
      const container = document.getElementById('wishlist-items-container');
      if (appState.wishlist.length === 0) {
        container.innerHTML = `<p class="text-sm text-taupe text-center py-10">Aún no has guardado fotografías de la galería. Haz clic en el corazón de cualquier montaje para agregarlo aquí.</p>`;
        return;
      }
      container.innerHTML = appState.wishlist.map(item => `
        <div class="flex items-center justify-between gap-4 p-3 rounded-2xl bg-champagne/50 border border-beige">
          <div class="flex items-center gap-3">
            <img src="${item.url}" class="w-14 h-14 rounded-xl object-cover" />
            <div>
              <p class="font-serif text-lg font-semibold text-espresso leading-tight">${item.title}</p>
              <span class="text-xs text-gold">${item.category}</span>
            </div>
          </div>
          <button onclick="toggleWishlist('${item.id}'); renderWishlistModal();" class="p-2 text-taupe hover:text-rose-600">
            <i data-lucide="trash-2" class="w-4 h-4"></i>
          </button>
        </div>
      `).join('');
      lucide.createIcons();
    }

    function clearWishlist() {
      appState.wishlist = [];
      saveState();
      updateWishlistBadges();
      renderWishlistModal();
      renderGallery();
    }

    function renderPortfolio() {
      const grid = document.getElementById('portfolio-grid');
      grid.innerHTML = appState.portfolio.map(proj => `
        <article class="rounded-3xl bg-ivory border border-beige overflow-hidden shadow-luxury flex flex-col justify-between group">
          <div>
            <div class="h-64 overflow-hidden relative">
              <img src="${proj.url}" alt="${proj.titleEs}" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700" />
              <span class="absolute bottom-3 left-3 px-3 py-1 rounded-full bg-ivory/90 text-[11px] font-semibold text-espresso">${proj.location}</span>
            </div>
            <div class="p-6">
              <div class="flex items-center gap-1.5 mb-3">
                <span class="text-[11px] text-taupe mr-1">Paleta:</span>
                ${proj.colors.map(c => `<span class="w-4 h-4 rounded-full border border-espresso/20" style="background:${c}"></span>`).join('')}
              </div>
              <h3 class="font-serif text-2xl font-semibold text-espresso mb-2">${currentLang === 'es' ? proj.titleEs : proj.titleEn}</h3>
              <p class="text-sm text-taupe line-clamp-3">${currentLang === 'es' ? proj.conceptEs : proj.conceptEn}</p>
            </div>
          </div>
          <div class="px-6 pb-6">
            <button onclick="openPortfolioModal('${proj.id}')" class="w-full py-3 rounded-full border border-gold text-xs font-semibold uppercase tracking-wider text-espresso hover:bg-gold hover:text-white transition-all">
              ${currentLang === 'es' ? 'Ver Ficha del Evento' : 'View Event Case Study'}
            </button>
          </div>
        </article>
      `).join('');
    }

    function openPortfolioModal(id) {
      const proj = appState.portfolio.find(p => p.id === id);
      if (!proj) return;
      currentSharedTitle = proj.titleEs;
      document.getElementById('pm-img').src = proj.url;
      document.getElementById('pm-location').textContent = proj.location;
      document.getElementById('pm-title').textContent = currentLang === 'es' ? proj.titleEs : proj.titleEn;
      document.getElementById('pm-concept').textContent = currentLang === 'es' ? proj.conceptEs : proj.conceptEn;
      document.getElementById('pm-colors').innerHTML = proj.colors.map(c => `<span class="w-5 h-5 rounded-full border border-espresso/20" style="background:${c}"></span>`).join('');
      document.getElementById('pm-services').innerHTML = proj.services.map(s => `<li class="flex items-center gap-1.5"><i data-lucide="check" class="w-3.5 h-3.5 text-gold"></i> ${s}</li>`).join('');
      openModal('portfolio-modal');
    }

    function shareCurrentItem() {
      const shareText = `Mira este diseño de AM Joy Wedding & Event: ${currentSharedTitle} - ${window.location.href}`;
      const tempInput = document.createElement('input');
      tempInput.value = shareText;
      document.body.appendChild(tempInput);
      tempInput.select();
      document.execCommand('copy');
      document.body.removeChild(tempInput);
      showToast('Enlace del evento copiado al portapapeles para compartir.', 'success');
    }

    function renderTestimonials() {
      const grid = document.getElementById('testimonials-grid');
      grid.innerHTML = appState.testimonials.map(t => `
        <div class="p-8 rounded-3xl bg-ivory border border-beige shadow-luxury flex flex-col justify-between">
          <div>
            <div class="flex gap-1 text-gold mb-4">
              ★★★★★
            </div>
            <p class="font-serif italic text-xl text-espresso leading-relaxed mb-6">
              ${currentLang === 'es' ? t.textEs : (t.textEn || t.textEs)}
            </p>
          </div>
          <div class="pt-4 border-t border-beige/70">
            <p class="font-semibold text-sm text-espresso">${t.author}</p>
            <p class="text-xs text-gold mt-0.5">${t.event}</p>
          </div>
        </div>
      `).join('');
    }

    const BLOG_POSTS = [
      {
        id: 'blog1',
        tag: 'Tendencias de Bodas RD',
        titleEs: 'Tendencias de Bodas de Lujo en República Dominicana para 2026',
        titleEn: 'Luxury Wedding Trends in the Dominican Republic for 2026',
        excerptEs: 'Iluminación cálida con candelabros, paletas champagne-marfil y ceremonias íntimas al aire libre marcan la pauta esta temporada.',
        excerptEn: 'Warm candlelight chandeliers, champagne-ivory palettes, and intimate outdoor ceremonies lead this season.',
        bodyEs: '<p>Las bodas en Santo Domingo, La Romana y Punta Cana evolucionan hacia experiencias sensoriales altamente personalizadas. La tendencia principal combina estructuras florales orgánicas con tonos champagne, blanco marfil y acentos en dorado cepillado.</p><p>Asimismo, las parejas priorizan la comodidad de sus invitados mediante estaciones gastronómicas de autor, iluminación arquitectónica cálida y papelería digital interactiva con confirmación RSVP en tiempo real.</p>',
        url: 'https://images.unsplash.com/photo-1511285560929-80b456fea0bc?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: 'blog2',
        tag: 'Paletas & Decoración',
        titleEs: 'Cómo Combinar Champagne, Marfil y Dorado sin Recargar el Espacio',
        titleEn: 'How to Pair Champagne, Ivory & Gold Without Overwhelming the Venue',
        excerptEs: 'El equilibrio entre texturas nobles como el lino, la cristalería fina y follajes suaves es la clave de la elegancia atemporal.',
        excerptEn: 'Balancing noble textures like linen, fine crystal, and soft foliage is the secret to timeless elegance.',
        bodyEs: '<p>La paleta champagne y marfil aporta luminosidad y romanticismo inmediato tanto en salones clásicos como en jardines tropicales. El secreto de nuestros diseñadores en AM Joy Wedding & Event consiste en jugar con distintas alturas de centros de mesa y mezclar textiles vaporosos con detalles metálicos sutiles.</p>',
        url: 'https://images.unsplash.com/photo-1507504031003-b417219a0fde?auto=format&fit=crop&w=900&q=80'
      },
      {
        id: 'blog3',
        tag: 'Consejos de Planificación',
        titleEs: 'Guía para Elegir el Lugar Perfecto para tu Boda en Santo Domingo',
        titleEn: 'Guide to Choosing the Perfect Wedding Venue in Santo Domingo',
        excerptEs: 'Factores clave de logística, clima, acústica y capacidad que debes evaluar antes de firmar el contrato de tu locación.',
        excerptEn: 'Key logistics, weather, acoustics, and capacity factors to evaluate before signing your venue contract.',
        bodyEs: '<p>Antes de reservar la locación de tus sueños, evalúa el flujo entre la ceremonia y la recepción, las opciones de plan B ante lluvia en eventos al aire libre y las facilidades de montaje para decoración e iluminación. Contar con una Wedding Planner desde esta etapa te ahorrará costos imprevistos.</p>',
        url: 'https://images.unsplash.com/photo-1465495976277-4387d4b0b4c6?auto=format&fit=crop&w=900&q=80'
      }
    ];

    function renderBlog() {
      const grid = document.getElementById('blog-grid');
      grid.innerHTML = BLOG_POSTS.map(post => `
        <article class="rounded-3xl bg-champagne/40 border border-beige overflow-hidden flex flex-col justify-between hover:border-gold/60 transition-all">
          <div>
            <img src="${post.url}" alt="${post.titleEs}" class="w-full h-52 object-cover" />
            <div class="p-6">
              <span class="text-[11px] uppercase tracking-widest text-gold font-semibold">${post.tag}</span>
              <h3 class="font-serif text-2xl font-semibold text-espresso mt-1.5 mb-2.5 leading-snug">
                ${currentLang === 'es' ? post.titleEs : post.titleEn}
              </h3>
              <p class="text-sm text-taupe leading-relaxed">
                ${currentLang === 'es' ? post.excerptEs : post.excerptEn}
              </p>
            </div>
          </div>
          <div class="px-6 pb-6">
            <button onclick="openBlogModal('${post.id}')" class="text-xs font-semibold uppercase tracking-wider text-espresso hover:text-gold flex items-center gap-1.5">
              <span>${currentLang === 'es' ? 'Leer Artículo Completo' : 'Read Full Article'}</span>
              <i data-lucide="arrow-right" class="w-3.5 h-3.5 text-gold"></i>
            </button>
          </div>
        </article>
      `).join('');
      lucide.createIcons();
    }

    function openBlogModal(id) {
      const post = BLOG_POSTS.find(b => b.id === id);
      if (!post) return;
      document.getElementById('bm-img').src = post.url;
      document.getElementById('bm-tag').textContent = post.tag;
      document.getElementById('bm-title').textContent = currentLang === 'es' ? post.titleEs : post.titleEn;
      document.getElementById('bm-body').innerHTML = post.bodyEs;
      openModal('blog-modal');
    }

    const FAQ_ITEMS = [
      {
        qEs: '¿Con cuánta anticipación debemos contratar la planificación de nuestra boda?',
        qEn: 'How far in advance should we book our wedding planning?',
        aEs: 'Lo ideal es entre 8 y 14 meses antes de la fecha deseada para asegurar las mejores locaciones y suplidores. Sin embargo, también contamos con paquetes acelerados para bodas íntimas o eventos en menor plazo.',
        aEn: 'Ideally 8 to 14 months ahead to secure top venues and vendors, though we also offer streamlined planning for intimate weddings on shorter timelines.'
      },
      {
        qEs: '¿Realizan eventos fuera de Santo Domingo?',
        qEn: 'Do you plan events outside of Santo Domingo?',
        aEs: 'Sí, cubrimos toda la República Dominicana: Punta Cana, Casa de Campo (La Romana), Samaná, Santiago, Jarabacoa y bodas destino en playa o montaña.',
        aEn: 'Yes, we serve the entire Dominican Republic including Punta Cana, Casa de Campo (La Romana), Samaná, Santiago, and Jarabacoa.'
      },
      {
        qEs: '¿Puedo contratar únicamente el servicio de decoración o coordinación del día?',
        qEn: 'Can I book decor styling or day-of coordination only?',
        aEs: 'Por supuesto. Adaptamos nuestras propuestas según tus necesidades: planificación integral, diseño y decoración floral exclusiva, o coordinación profesional del día del evento.',
        aEn: 'Absolutely. We tailor proposals to your needs: full planning, bespoke floral decor, or professional day-of coordination.'
      }
    ];

    function renderFAQ() {
      const container = document.getElementById('faq-container');
      container.innerHTML = FAQ_ITEMS.map((item, idx) => `
        <details class="group rounded-2xl bg-ivory border border-beige p-5 open:border-gold/60 transition-all" ${idx === 0 ? 'open' : ''}>
          <summary class="flex items-center justify-between cursor-pointer font-serif text-xl font-semibold text-espresso list-none">
            <span>${currentLang === 'es' ? item.qEs : item.qEn}</span>
            <i data-lucide="chevron-down" class="w-5 h-5 text-gold group-open:rotate-180 transition-transform"></i>
          </summary>
          <p class="text-sm text-taupe leading-relaxed mt-3 pt-3 border-t border-beige/60">
            ${currentLang === 'es' ? item.aEs : item.aEn}
          </p>
        </details>
      `).join('');
      lucide.createIcons();
    }

    // -----------------------------------------------------------------------
    // 5. INTERACTIVE TOOLS (CALCULATOR, CALENDAR, CHECKLIST, INVITATIONS)
    // -----------------------------------------------------------------------
    function switchToolTab(tab) {
      document.querySelectorAll('.tool-panel').forEach(p => p.classList.add('hidden'));
      document.getElementById(`tool-panel-${tab}`).classList.remove('hidden');

      document.querySelectorAll('.tool-tab-btn').forEach(btn => {
        btn.className = 'tool-tab-btn px-5 py-3 rounded-full text-sm font-semibold transition-all bg-champagne text-espresso border border-beige hover:border-gold flex items-center gap-2';
      });
      const activeBtn = document.getElementById(`tab-btn-${tab}`);
      activeBtn.className = 'tool-tab-btn px-5 py-3 rounded-full text-sm font-semibold transition-all gold-gradient text-white shadow-gold flex items-center gap-2';
    }

    function calculateBudget() {
      const type = document.getElementById('calc-type').value;
      const guests = parseInt(document.getElementById('calc-guests').value, 10) || 2;
      const decor = document.getElementById('calc-decor').value;
      const venue = document.getElementById('calc-venue').value;

      document.getElementById('calc-guests-val').textContent = guests;

      const s = appState.settings;
      const baseRates = {
        romantic: Number(s.baseRomantic) || 150,
        surprise: Number(s.baseSurprise) || 150,
        chef: Number(s.baseChef) || 180,
        social: Number(s.baseSocial) || 250,
        corporate: Number(s.baseCorporate) || 450,
        intimate: Number(s.baseIntimate) || 650,
        wedding: Number(s.baseWedding) || 1500
      };

      const decorAddons = {
        intimate: 0,
        essential: 120,
        floral: 350,
        luxury: 850
      };

      const venueAddons = {
        private: 0,
        garden: 80,
        beach: 180,
        salon: 250
      };

      let extrasTotal = 0;
      document.querySelectorAll('.calc-extra:checked').forEach(chk => {
        if (chk.value === 'chef') extrasTotal += 120;
        if (chk.value === 'music') extrasTotal += 150;
        if (chk.value === 'photo_mini') extrasTotal += 130;
        if (chk.value === 'cake') extrasTotal += 65;
        if (chk.value === 'invites') extrasTotal += 45;
        if (chk.value === 'coord') extrasTotal += 200;
        if (chk.value === 'photo_full') extrasTotal += 450;
      });

      // Base includes up to 2 guests (so romantic dinner / surprise for 2 starts exactly at $150)
      const extraGuests = Math.max(0, guests - 2);
      const perGuestRate = Number(s.perGuest) || 12;
      const extraGuestCost = extraGuests * perGuestRate;

      const lowEstimate = Math.max(150, Math.round(baseRates[type] + extraGuestCost + decorAddons[decor] + venueAddons[venue] + extrasTotal));
      const highEstimate = Math.round(lowEstimate * 1.2);

      document.getElementById('calc-result-range').textContent = `$${lowEstimate.toLocaleString()} – $${highEstimate.toLocaleString()}`;
    }

    function transferEstimateToQuote() {
      const range = document.getElementById('calc-result-range').textContent;
      const guests = document.getElementById('calc-guests').value;
      const date = document.getElementById('calc-date').value;
      const typeLabel = document.getElementById('calc-type').selectedOptions[0].text;

      document.getElementById('q-budget').value = range;
      document.getElementById('q-guests').value = guests;
      if (date) document.getElementById('q-date').value = date;
      document.getElementById('q-details').value = `Estimación generada en calculadora para ${typeLabel} (${guests} personas). Rango orientativo: ${range}.`;

      document.getElementById('cotizar').scrollIntoView({ behavior: 'smooth' });
      showToast('Datos de la calculadora transferidos al formulario de cotización.', 'success');
    }

    // Calendar Logic
    let calYear = 2026;
    let calMonth = 10; // 0-indexed: 10 = November 2026

    function changeCalendarMonth(delta) {
      calMonth += delta;
      if (calMonth > 11) { calMonth = 0; calYear++; }
      if (calMonth < 0) { calMonth = 11; calYear--; }
      renderCalendar();
    }

    function renderCalendar() {
      const monthNamesEs = ['Enero', 'Febrero', 'Marzo', 'Abril', 'Mayo', 'Junio', 'Julio', 'Agosto', 'Septiembre', 'Octubre', 'Noviembre', 'Diciembre'];
      document.getElementById('cal-month-label').textContent = `${monthNamesEs[calMonth]} ${calYear}`;

      const firstDay = new Date(calYear, calMonth, 1).getDay();
      const daysInMonth = new Date(calYear, calMonth + 1, 0).getDate();
      const grid = document.getElementById('calendar-days-grid');

      let html = '';
      for (let i = 0; i < firstDay; i++) {
        html += `<div></div>`;
      }

      for (let d = 1; d <= daysInMonth; d++) {
        const isoDate = `${calYear}-${String(calMonth + 1).padStart(2, '0')}-${String(d).padStart(2, '0')}`;
        const booking = appState.bookings.find(b => b.date === isoDate);

        let btnClass = 'bg-ivory border-beige hover:border-gold text-espresso cursor-pointer';
        let disabledAttr = '';
        if (booking) {
          if (booking.status === 'confirmed') {
            btnClass = 'bg-rose-100 border-rose-300 text-rose-800 cursor-not-allowed opacity-80';
            disabledAttr = 'disabled';
          } else if (booking.status === 'pending') {
            btnClass = 'bg-amber-100 border-amber-400 text-amber-900 cursor-not-allowed';
            disabledAttr = 'disabled';
          }
        }

        html += `
          <button type="button" ${disabledAttr} onclick="selectCalendarDate('${isoDate}')" class="h-11 rounded-xl border text-xs font-semibold transition-all flex items-center justify-center ${btnClass}">
            ${d}
          </button>
        `;
      }
      grid.innerHTML = html;
    }

    function selectCalendarDate(isoDate) {
      document.getElementById('req-cal-date').value = isoDate;
      showToast(`Fecha ${isoDate} seleccionada. Completa tus datos para solicitar el bloqueo.`, 'info');
    }

    function submitDateRequest(e) {
      e.preventDefault();
      const date = document.getElementById('req-cal-date').value;
      if (!date) {
        showToast('Por favor selecciona un día disponible en el calendario.', 'error');
        return;
      }
      const exists = appState.bookings.some(b => b.date === date && (b.status === 'confirmed' || b.status === 'pending'));
      if (exists) {
        showToast('Esta fecha ya tiene una solicitud activa o está reservada.', 'error');
        return;
      }

      appState.bookings.push({
        id: 'bk-' + Date.now(),
        date,
        client: document.getElementById('req-cal-name').value,
        phone: document.getElementById('req-cal-phone').value,
        type: document.getElementById('req-cal-type').value,
        status: 'pending'
      });
      saveState();
      renderCalendar();
      e.target.reset();
      showToast('¡Solicitud de fecha enviada! Queda en estado pendiente hasta confirmación del administrador.', 'success');
    }

    // Checklist Logic
    function renderChecklist() {
      const categories = ['Vestido', 'Lugar', 'Invitaciones', 'Decoración', 'Fotografía', 'Música', 'Banquete', 'Ceremonia', 'Otros'];
      const container = document.getElementById('checklist-container');

      const total = appState.checklist.length;
      const done = appState.checklist.filter(t => t.done).length;
      const pct = total ? Math.round((done / total) * 100) : 0;
      document.getElementById('checklist-percent').textContent = `${pct}%`;
      document.getElementById('checklist-bar').style.width = `${pct}%`;

      container.innerHTML = categories.map(cat => {
        const tasks = appState.checklist.filter(t => t.cat === cat);
        return `
          <div class="p-5 rounded-2xl bg-ivory border border-beige">
            <h4 class="font-serif text-xl font-semibold text-espresso border-b border-beige pb-2 mb-3 flex items-center justify-between">
              <span>${cat}</span>
              <span class="text-xs font-sans text-gold">${tasks.filter(t => t.done).length}/${tasks.length}</span>
            </h4>
            <ul class="space-y-2.5">
              ${tasks.map(t => `
                <li class="flex items-start gap-2.5 text-xs">
                  <input type="checkbox" ${t.done ? 'checked' : ''} onchange="toggleChecklistTask('${t.id}')" class="mt-0.5 accent-[#C5A059] cursor-pointer" />
                  <span class="${t.done ? 'line-through text-taupe/60' : 'text-espresso'}">${t.text}</span>
                </li>
              `).join('')}
            </ul>
          </div>
        `;
      }).join('');
    }

    function toggleChecklistTask(id) {
      const task = appState.checklist.find(t => t.id === id);
      if (task) {
        task.done = !task.done;
        saveState();
        renderChecklist();
      }
    }

    function addChecklistTask(e) {
      e.preventDefault();
      const cat = document.getElementById('new-task-cat').value;
      const text = document.getElementById('new-task-text').value;
      appState.checklist.push({ id: 'chk-' + Date.now(), cat, text, done: false });
      saveState();
      renderChecklist();
      e.target.reset();
      showToast('Tarea agregada a tu checklist nupcial.', 'success');
    }

    // Digital Invitation Live Preview
    function updateInvitationPreview() {
      document.getElementById('prev-inv-couple').textContent = document.getElementById('inv-couple').value || 'Novios';
      document.getElementById('prev-inv-guest').textContent = document.getElementById('inv-guest').value || 'Invitado Especial';
      document.getElementById('prev-inv-date').textContent = document.getElementById('inv-date').value;
      document.getElementById('prev-inv-venue').textContent = document.getElementById('inv-venue').value;
    }

    // -----------------------------------------------------------------------
    // 6. QUOTE FORM, NEWSLETTER & CLIENT PORTAL
    // -----------------------------------------------------------------------
    function preselectEventType(val) {
      const sel = document.getElementById('q-type');
      for (let opt of sel.options) {
        if (opt.value.toLowerCase().includes(val.toLowerCase())) {
          sel.value = opt.value;
          break;
        }
      }
    }

    function submitQuoteForm(e) {
      e.preventDefault();
      const attachWish = document.getElementById('q-include-wishlist').checked;
      const quoteRecord = {
        id: 'qt-' + Date.now(),
        name: document.getElementById('q-name').value,
        email: document.getElementById('q-email').value,
        whatsapp: document.getElementById('q-whatsapp').value,
        type: document.getElementById('q-type').value,
        date: document.getElementById('q-date').value || 'Por definir',
        venue: document.getElementById('q-venue').value || 'Por definir',
        guests: document.getElementById('q-guests').value || 'N/A',
        budget: document.getElementById('q-budget').value || 'A consultar',
        details: document.getElementById('q-details').value,
        wishlist: attachWish ? appState.wishlist.map(w => w.title) : [],
        createdAt: new Date().toLocaleDateString()
      };

      appState.quotes.unshift(quoteRecord);
      saveState();
      e.target.reset();
      showToast('¡Solicitud recibida! Nuestro equipo se pondrá en contacto contigo muy pronto.', 'success');
    }

    function subscribeNewsletter(e) {
      e.preventDefault();
      const email = document.getElementById('newsletter-email').value;
      if (!appState.subscribers.includes(email)) {
        appState.subscribers.push(email);
        saveState();
      }
      e.target.reset();
      showToast('¡Gracias por suscribirte a las novedades de AM Joy Wedding & Event!', 'success');
    }

    function loginClientPortal(e) {
      e.preventDefault();
      const code = document.getElementById('client-access-code').value.trim().toUpperCase();
      if (code === 'BODA2026' || code === 'AMJOY') {
        document.getElementById('client-login-view').classList.add('hidden');
        document.getElementById('client-dashboard-view').classList.remove('hidden');
        lucide.createIcons();
        showToast('Bienvenidos a su Portal Exclusivo de Evento.', 'success');
      } else {
        showToast('Código inválido. Prueba con el código demo: BODA2026', 'error');
      }
    }

    function logoutClientPortal() {
      document.getElementById('client-dashboard-view').classList.add('hidden');
      document.getElementById('client-login-view').classList.remove('hidden');
    }

    // -----------------------------------------------------------------------
    // 7. PRIVATE ADMIN PANEL LOGIC
    // -----------------------------------------------------------------------
    function loginAdmin(e) {
      e.preventDefault();
      const u = document.getElementById('admin-user').value.trim();
      const p = document.getElementById('admin-pass').value.trim();
      if (u === 'admin' && p === 'amjoy2026') {
        document.getElementById('admin-login-view').classList.add('hidden');
        document.getElementById('admin-dashboard-view').classList.remove('hidden');
        renderAdminPanels();
        showToast('Acceso administrativo concedido.', 'success');
      } else {
        showToast('Credenciales incorrectas (Usa admin / amjoy2026)', 'error');
      }
    }

    function switchAdminTab(tabName) {
      document.querySelectorAll('.admin-panel').forEach(p => p.classList.add('hidden'));
      document.getElementById(`admin-panel-${tabName}`).classList.remove('hidden');

      document.querySelectorAll('.admin-tab').forEach(btn => {
        btn.className = 'admin-tab px-3.5 py-2 rounded-xl text-xs font-semibold bg-champagne text-espresso';
      });
      event.target.className = 'admin-tab px-3.5 py-2 rounded-xl text-xs font-semibold bg-gold text-white';
    }

    function renderAdminPanels() {
      // Quotes
      document.getElementById('admin-quotes-count').textContent = `${appState.quotes.length} solicitudes`;
      const qList = document.getElementById('admin-quotes-list');
      qList.innerHTML = appState.quotes.length === 0
        ? '<p class="text-xs text-taupe">Aún no hay nuevas solicitudes de cotización registradas.</p>'
        : appState.quotes.map(q => `
          <div class="p-4 rounded-2xl bg-champagne/40 border border-beige text-xs space-y-1">
            <div class="flex justify-between font-semibold text-espresso">
              <span>${q.name} — ${q.type}</span>
              <span class="text-gold">${q.date}</span>
            </div>
            <p class="text-taupe">WhatsApp: ${q.whatsapp} | Email: ${q.email} | Invitados: ${q.guests} | Presupuesto: ${q.budget}</p>
            <p class="text-espresso/90 pt-1">${q.details}</p>
            ${q.wishlist && q.wishlist.length ? `<p class="text-gold pt-1">Wishlist adjunta: ${q.wishlist.join(', ')}</p>` : ''}
          </div>
        `).join('');

      // Subscribers
      document.getElementById('admin-subscribers-list').innerHTML = appState.subscribers.map(s => `
        <span class="px-3 py-1 rounded-full bg-champagne border border-beige">${s}</span>
      `).join('');

      // Bookings
      const dList = document.getElementById('admin-dates-list');
      dList.innerHTML = appState.bookings.map(b => `
        <div class="p-4 rounded-2xl bg-champagne/40 border border-beige flex flex-col sm:flex-row sm:items-center justify-between gap-3 text-xs">
          <div>
            <span class="font-bold text-espresso text-sm">${b.date}</span> — <span>${b.client} (${b.type})</span>
            <span class="ml-2 px-2.5 py-0.5 rounded-full font-semibold ${
              b.status === 'confirmed' ? 'bg-emerald-100 text-emerald-800' : 'bg-amber-100 text-amber-800'
            }">${b.status.toUpperCase()}</span>
          </div>
          <div class="flex gap-2">
            <button onclick="updateBookingStatus('${b.id}', 'confirmed')" class="px-3 py-1.5 rounded-lg bg-emerald-600 text-white font-semibold">Confirmar</button>
            <button onclick="updateBookingStatus('${b.id}', 'rejected')" class="px-3 py-1.5 rounded-lg bg-rose-600 text-white font-semibold">Rechazar / Liberar</button>
          </div>
        </div>
      `).join('');

      // Settings Inputs
      const s = appState.settings;
      document.getElementById('cfg-base-romantic').value = s.baseRomantic ?? 150;
      document.getElementById('cfg-base-surprise').value = s.baseSurprise ?? 150;
      document.getElementById('cfg-base-chef').value = s.baseChef ?? 180;
      document.getElementById('cfg-base-social').value = s.baseSocial ?? 250;
      document.getElementById('cfg-base-corporate').value = s.baseCorporate ?? 450;
      document.getElementById('cfg-base-intimate').value = s.baseIntimate ?? 650;
      document.getElementById('cfg-base-wedding').value = s.baseWedding ?? 1500;
      document.getElementById('cfg-per-guest').value = s.perGuest ?? 12;
      document.getElementById('cfg-whatsapp').value = s.whatsappNumber;
      document.getElementById('cfg-phone-display').value = s.phoneDisplay;
      document.getElementById('cfg-email').value = s.email;
      document.getElementById('cfg-address').value = s.address;
    }

    function updateBookingStatus(id, status) {
      if (status === 'rejected') {
        appState.bookings = appState.bookings.filter(b => b.id !== id);
      } else {
        const bk = appState.bookings.find(b => b.id === id);
        if (bk) bk.status = status;
      }
      saveState();
      renderCalendar();
      renderAdminPanels();
      showToast('Estado de fecha actualizado en la agenda.', 'success');
    }

    function saveAdminSettings(e) {
      e.preventDefault();
      appState.settings.baseRomantic = Number(document.getElementById('cfg-base-romantic').value);
      appState.settings.baseSurprise = Number(document.getElementById('cfg-base-surprise').value);
      appState.settings.baseChef = Number(document.getElementById('cfg-base-chef').value);
      appState.settings.baseSocial = Number(document.getElementById('cfg-base-social').value);
      appState.settings.baseCorporate = Number(document.getElementById('cfg-base-corporate').value);
      appState.settings.baseIntimate = Number(document.getElementById('cfg-base-intimate').value);
      appState.settings.baseWedding = Number(document.getElementById('cfg-base-wedding').value);
      appState.settings.perGuest = Number(document.getElementById('cfg-per-guest').value);
      appState.settings.whatsappNumber = document.getElementById('cfg-whatsapp').value;
      appState.settings.phoneDisplay = document.getElementById('cfg-phone-display').value;
      appState.settings.email = document.getElementById('cfg-email').value;
      appState.settings.address = document.getElementById('cfg-address').value;

      // Sync visible price badges on service cards
      const priceMap = {
        'srv-1': appState.settings.baseRomantic,
        'srv-2': appState.settings.baseSurprise,
        'srv-3': appState.settings.baseChef,
        'srv-4': appState.settings.baseSocial,
        'srv-5': appState.settings.baseCorporate,
        'srv-6': appState.settings.baseIntimate,
        'srv-7': appState.settings.baseWedding
      };
      appState.services.forEach(srv => {
        if (priceMap[srv.id] !== undefined) {
          srv.priceTagEs = `Desde $${priceMap[srv.id].toLocaleString()} USD`;
          srv.priceTagEn = `From $${priceMap[srv.id].toLocaleString()} USD`;
        }
      });

      saveState();
      applyContactSettings();
      renderServices();
      calculateBudget();
      showToast('Tarifas desde $150 USD, WhatsApp e información de contacto actualizados.', 'success');
    }

    function updateBookingStatus(id, status) {
      if (status === 'rejected') {
        appState.bookings = appState.bookings.filter(b => b.id !== id);
      } else {
        const bk = appState.bookings.find(b => b.id === id);
        if (bk) bk.status = status;
      }
      saveState();
      renderCalendar();
      renderAdminPanels();
      showToast('Estado de fecha actualizado en la agenda.', 'success');
    }

    function saveAdminSettings(e) {
      e.preventDefault();
      appState.settings.baseWedding = Number(document.getElementById('cfg-base-wedding').value);
      appState.settings.perGuest = Number(document.getElementById('cfg-per-guest').value);
      appState.settings.whatsappNumber = document.getElementById('cfg-whatsapp').value;
      appState.settings.phoneDisplay = document.getElementById('cfg-phone-display').value;
      appState.settings.email = document.getElementById('cfg-email').value;
      appState.settings.address = document.getElementById('cfg-address').value;
      saveState();
      applyContactSettings();
      calculateBudget();
      showToast('Tarifas, WhatsApp e información de contacto actualizados.', 'success');
    }

    function applyContactSettings() {
      document.getElementById('contact-phone-display').textContent = appState.settings.phoneDisplay;
      document.getElementById('contact-email-display').textContent = appState.settings.email;
      document.getElementById('contact-address-display').textContent = appState.settings.address;
    }

    function adminAddPhoto(e) {
      e.preventDefault();
      appState.gallery.unshift({
        id: 'g-' + Date.now(),
        title: document.getElementById('new-photo-title').value,
        category: document.getElementById('new-photo-cat').value,
        url: document.getElementById('new-photo-url').value
      });
      saveState();
      renderGallery();
      e.target.reset();
      showToast('Nueva fotografía publicada en la galería.', 'success');
    }

    function adminAddTestimonial(e) {
      e.preventDefault();
      const txt = document.getElementById('new-testi-text').value;
      appState.testimonials.unshift({
        id: 't-' + Date.now(),
        author: document.getElementById('new-testi-author').value,
        event: document.getElementById('new-testi-event').value,
        textEs: `“${txt}”`,
        textEn: `“${txt}”`
      });
      saveState();
      renderTestimonials();
      e.target.reset();
      showToast('Testimonio autorizado publicado.', 'success');
    }

    // -----------------------------------------------------------------------
    // 8. INITIALIZATION ON WINDOW LOAD
    // -----------------------------------------------------------------------
    window.addEventListener('DOMContentLoaded', () => {
      applyContactSettings();
      renderServices();
      renderGalleryFilters();
      renderGallery();
      renderPortfolio();
      renderTestimonials();
      renderBlog();
      renderFAQ();
      calculateBudget();
      renderCalendar();
      renderChecklist();
      updateWishlistBadges();
      lucide.createIcons();
    });
  </script>
</body>
</html>
