# verbose-doodle
Globally Luxury 
<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="The Order — private access request portal.">
    <title>The Order | Global Observation Node</title><!-- Prototype Tailwind CDN. For production, compile Tailwind locally. -->
<script src="https://cdn.tailwindcss.com"></script>

<!-- Fonts -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@400;700&family=Space+Mono:wght@400&display=swap" rel="stylesheet">

<style>
    :root {
        --gold: #d4af37;
        --gold-soft: rgba(212, 175, 55, 0.45);
        --gold-faint: rgba(212, 175, 55, 0.16);
        --bg: #030303;
        --panel: rgba(3, 3, 3, 0.72);
    }

    * {
        box-sizing: border-box;
    }

    html {
        scroll-behavior: smooth;
    }

    body {
        font-family: 'Space Mono', monospace;
        background:
            radial-gradient(circle at center, rgba(212, 175, 55, 0.055), transparent 35%),
            radial-gradient(circle at top, rgba(212, 175, 55, 0.035), transparent 28%),
            var(--bg);
        color: var(--gold);
        overflow: hidden;
        margin: 0;
    }

    .serif {
        font-family: 'Cinzel', serif;
    }

    .gold-glow {
        text-shadow: 0 0 20px rgba(212, 175, 55, 0.5);
    }

    .gold-box-glow {
        box-shadow:
            0 0 0 1px rgba(212, 175, 55, 0.25),
            0 0 40px rgba(212, 175, 55, 0.08),
            inset 0 0 30px rgba(212, 175, 55, 0.03);
    }

    /* Scanner Line Animation */
    .scanner {
        position: fixed;
        top: -10%;
        left: 0;
        width: 100%;
        height: 2px;
        background: linear-gradient(90deg, transparent, var(--gold), transparent);
        box-shadow: 0 0 10px var(--gold);
        animation: scan 6s infinite linear;
        z-index: 100;
        opacity: 0.2;
        pointer-events: none;
    }

    @keyframes scan {
        0% { top: -10%; }
        100% { top: 110%; }
    }

    /* Background Noise: local CSS fallback instead of relying only on external texture */
    .noise {
        position: fixed;
        inset: 0;
        background-image:
            radial-gradient(circle at 20% 30%, rgba(255,255,255,0.08) 0 1px, transparent 1px),
            radial-gradient(circle at 70% 80%, rgba(255,255,255,0.05) 0 1px, transparent 1px),
            radial-gradient(circle at 45% 55%, rgba(255,255,255,0.04) 0 1px, transparent 1px);
        background-size: 90px 90px, 130px 130px, 170px 170px;
        opacity: 0.22;
        z-index: 1;
        pointer-events: none;
    }

    /* Language Fade Transitions */
    .lang-node,
    .gate-node {
        opacity: 1;
        transform: translateY(0) scale(1);
        transition:
            opacity 0.65s ease,
            transform 0.65s ease,
            filter 0.65s ease;
        will-change: opacity, transform;
    }

    .is-hidden {
        opacity: 0;
        transform: translateY(10px) scale(0.985);
        filter: blur(3px);
        pointer-events: none;
        position: absolute;
        inset: 0;
        width: 100%;
    }

    .is-removed {
        display: none !important;
    }

    /* Interactive Parallax */
    #parallax-layer {
        position: fixed;
        inset: -5%;
        z-index: 0;
        display: flex;
        align-items: center;
        justify-content: center;
        opacity: 0.08;
        transition: transform 0.18s ease-out;
        pointer-events: none;
    }

    input::placeholder {
        color: rgba(212, 175, 55, 0.24);
    }

    input:-webkit-autofill,
    input:-webkit-autofill:hover,
    input:-webkit-autofill:focus {
        -webkit-text-fill-color: var(--gold);
        transition: background-color 9999s ease-in-out 0s;
        caret-color: var(--gold);
    }

    .access-button {
        position: relative;
        isolation: isolate;
        overflow: hidden;
    }

    .access-button::before {
        content: "";
        position: absolute;
        inset: 0;
        background: var(--gold);
        transform: translateX(-101%);
        transition: transform 0.5s ease;
        z-index: -1;
    }

    .access-button:hover::before,
    .access-button:focus-visible::before {
        transform: translateX(0);
    }

    .access-button:hover,
    .access-button:focus-visible {
        color: #050505;
    }

    .focus-ring:focus-visible {
        outline: 1px solid var(--gold);
        outline-offset: 6px;
    }

    .lang-button[aria-pressed="true"] {
        color: #ffffff;
        opacity: 1;
        text-shadow: 0 0 15px rgba(212, 175, 55, 0.6);
    }

    .status-message {
        min-height: 1.25rem;
    }

    @media (max-width: 640px) {
        body {
            overflow: auto;
        }

        nav {
            top: 1.25rem !important;
            gap: 1rem !important;
            letter-spacing: 0.32em !important;
        }

        footer {
            bottom: 1.25rem !important;
        }
    }

    @media (prefers-reduced-motion: reduce) {
        *,
        *::before,
        *::after {
            animation-duration: 0.01ms !important;
            animation-iteration-count: 1 !important;
            scroll-behavior: auto !important;
            transition-duration: 0.01ms !important;
        }

        .scanner {
            display: none;
        }
    }
</style>

</head>
<body class="min-h-screen flex flex-col items-center justify-center">
    <div class="scanner" aria-hidden="true"></div>
    <div class="noise" aria-hidden="true"></div><div id="parallax-layer" aria-hidden="true">
    <svg width="800" height="800" viewBox="0 0 100 100" fill="none" stroke="currentColor">
        <circle cx="50" cy="50" r="45" stroke-width="0.1" />
        <path d="M50 5 L95 80 L5 80 Z" stroke-width="0.1" />
        <path d="M50 95 L5 20 L95 20 Z" stroke-width="0.1" />
        <circle cx="50" cy="50" r="15" stroke-width="0.1" />
        <path d="M50 5 L50 95 M5 50 L95 50" stroke-width="0.05" stroke-dasharray="1 1" />
    </svg>
</div>

<nav class="fixed top-10 w-full flex justify-center gap-8 z-50 text-[9px] tracking-[0.6em] uppercase opacity-50" aria-label="Language selector">
    <button type="button" data-lang="en" class="lang-button focus-ring hover:text-white transition" aria-pressed="true">English</button>
    <button type="button" data-lang="es" class="lang-button focus-ring hover:text-white transition" aria-pressed="false">Español</button>
    <button type="button" data-lang="fr" class="lang-button focus-ring hover:text-white transition" aria-pressed="false">Français</button>
</nav>

<main class="relative z-20 text-center px-6 w-full max-w-xl" aria-live="polite">
    <section class="relative min-h-[430px] flex flex-col justify-center rounded-2xl px-4 py-10 sm:px-8 gold-box-glow bg-[rgba(3,3,3,0.28)] backdrop-blur-sm">
        <div class="mb-10 opacity-80" aria-hidden="true">
            <svg width="70" height="70" viewBox="0 0 100 100" class="mx-auto gold-glow">
                <path d="M50 15 L85 85 L15 85 Z" stroke="currentColor" stroke-width="1.5" fill="none" />
                <circle cx="50" cy="62" r="8" stroke="currentColor" stroke-width="1" />
                <circle cx="50" cy="62" r="2" fill="currentColor" class="animate-ping" style="animation-duration: 4s;" />
            </svg>
        </div>

        <div id="lang-en" class="lang-node" data-panel="language">
            <h1 class="serif text-3xl md:text-5xl mb-4 tracking-[0.4em] uppercase gold-glow">Initium</h1>
            <p class="text-[10px] md:text-xs text-gray-500 mb-10 tracking-[0.2em] leading-loose uppercase">
                Protocol: Active <br>
                Encryption: Enabled <br>
                System: Seeking the Architects of Order
            </p>
            <button type="button" data-open-gate class="access-button focus-ring px-12 py-4 border border-[#d4af37] text-[10px] tracking-[0.5em] uppercase transition-colors duration-500">
                Request Access
            </button>
        </div>

        <div id="lang-es" class="lang-node is-hidden is-removed" data-panel="language" lang="es">
            <h1 class="serif text-3xl md:text-5xl mb-4 tracking-[0.4em] uppercase gold-glow">Initium</h1>
            <p class="text-[10px] md:text-xs text-gray-500 mb-10 tracking-[0.2em] leading-loose uppercase">
                Protocolo: Activo <br>
                Cifrado: Activado <br>
                Sistema: Buscando a los Arquitectos del Orden
            </p>
            <button type="button" data-open-gate class="access-button focus-ring px-12 py-4 border border-[#d4af37] text-[10px] tracking-[0.5em] uppercase transition-colors duration-500">
                Solicitar Acceso
            </button>
        </div>

        <div id="lang-fr" class="lang-node is-hidden is-removed" data-panel="language" lang="fr">
            <h1 class="serif text-3xl md:text-5xl mb-4 tracking-[0.4em] uppercase gold-glow">Initium</h1>
            <p class="text-[10px] md:text-xs text-gray-500 mb-10 tracking-[0.2em] leading-loose uppercase">
                Protocole: Actif <br>
                Chiffrement: Activé <br>
                Système: À la recherche des Architectes de l'Ordre
            </p>
            <button type="button" data-open-gate class="access-button focus-ring px-12 py-4 border border-[#d4af37] text-[10px] tracking-[0.5em] uppercase transition-colors duration-500">
                Demander l'Accès
            </button>
        </div>

        <div id="inquiry-gate" class="gate-node is-hidden is-removed">
            <h2 class="serif text-xl mb-4 tracking-[0.3em] gold-glow uppercase">Candidate Scan</h2>
            <p id="gate-copy" class="text-[10px] text-gray-500 mb-9 tracking-[0.18em] leading-loose uppercase">
                Submit your signal. Verification is manual. Access is not guaranteed.
            </p>

            <form id="submission-form" class="flex flex-col gap-7 max-w-xs mx-auto" novalidate>
                <div>
                    <label for="identity" class="sr-only">Identification String</label>
                    <input
                        id="identity"
                        name="identity"
                        type="text"
                        required
                        minlength="2"
                        autocomplete="name"
                        placeholder="IDENTIFICATION STRING"
                        class="w-full bg-transparent border-b border-gray-900 py-2 focus:border-[#d4af37] outline-none text-center text-[10px] tracking-widest uppercase transition-all"
                    >
                </div>

                <div>
                    <label for="email" class="sr-only">Secure Channel Email</label>
                    <input
                        id="email"
                        name="email"
                        type="email"
                        required
                        autocomplete="email"
                        placeholder="SECURE CHANNEL (EMAIL)"
                        class="w-full bg-transparent border-b border-gray-900 py-2 focus:border-[#d4af37] outline-none text-center text-[10px] tracking-widest uppercase transition-all"
                    >
                </div>

                <!-- Honeypot field: leave hidden. Helps reduce simple bot submissions. -->
                <div class="hidden" aria-hidden="true">
                    <label for="website">Website</label>
                    <input id="website" name="website" type="text" tabindex="-1" autocomplete="off">
                </div>

                <button id="submit-button" type="submit" class="focus-ring text-[9px] tracking-[0.8em] text-gray-500 hover:text-[#d4af37] transition-all uppercase">
                    Establish Link
                </button>

                <button type="button" id="back-button" class="focus-ring text-[8px] tracking-[0.45em] text-gray-700 hover:text-gray-400 transition-all uppercase">
                    Return to Node
                </button>

                <p id="form-status" class="status-message text-[9px] tracking-[0.24em] text-gray-500 uppercase" role="status"></p>
            </form>
        </div>
    </section>
</main>

<footer class="fixed bottom-10 w-full text-center z-50 opacity-25 text-[8px] tracking-[0.5em] uppercase">
    <a href="/privacy" class="mx-3 hover:text-white transition focus-ring">Privacy Protocol</a>
    <a href="/terms" class="mx-3 hover:text-white transition focus-ring">Terms of Order</a>
</footer>

<script>
    const state = {
        lang: 'en',
        gateOpen: false,
        isTransitioning: false
    };

    const copy = {
        en: {
            gate: 'Submit your signal. Verification is manual. Access is not guaranteed.',
            success: 'Signal transmitted. Awaiting verification.',
            invalid: 'Transmission failed. Verify all required fields.',
            bot: 'Transmission rejected.',
            submit: 'Establish Link'
        },
        es: {
            gate: 'Envía tu señal. La verificación es manual. El acceso no está garantizado.',
            success: 'Señal transmitida. Esperando verificación.',
            invalid: 'Transmisión fallida. Verifica todos los campos requeridos.',
            bot: 'Transmisión rechazada.',
            submit: 'Establecer Enlace'
        },
        fr: {
            gate: 'Transmettez votre signal. La vérification est manuelle. L’accès n’est pas garanti.',
            success: 'Signal transmis. En attente de vérification.',
            invalid: 'Transmission échouée. Vérifiez tous les champs requis.',
            bot: 'Transmission rejetée.',
            submit: 'Établir le Lien'
        }
    };

    const languageButtons = document.querySelectorAll('.lang-button');
    const languagePanels = document.querySelectorAll('[data-panel="language"]');
    const gate = document.getElementById('inquiry-gate');
    const gateCopy = document.getElementById('gate-copy');
    const submitButton = document.getElementById('submit-button');
    const backButton = document.getElementById('back-button');
    const form = document.getElementById('submission-form');
    const formStatus = document.getElementById('form-status');
    const parallaxLayer = document.getElementById('parallax-layer');

    function revealElement(element) {
        element.classList.remove('is-removed');
        requestAnimationFrame(() => {
            element.classList.remove('is-hidden');
        });
    }

    function hideElement(element) {
        element.classList.add('is-hidden');
        window.setTimeout(() => {
            element.classList.add('is-removed');
        }, 650);
    }

    function getActiveLanguagePanel() {
        return document.getElementById('lang-' + state.lang);
    }

    function updateLanguageCopy() {
        gateCopy.textContent = copy[state.lang].gate;
        submitButton.textContent = copy[state.lang].submit;
    }

    function updateLanguageButtons() {
        languageButtons.forEach(button => {
            const isActive = button.dataset.lang === state.lang;
            button.setAttribute('aria-pressed', String(isActive));
        });
    }

    function setLang(lang) {
        if (!copy[lang] || state.isTransitioning) return;

        state.lang = lang;
        document.documentElement.lang = lang;
        updateLanguageButtons();
        updateLanguageCopy();
        formStatus.textContent = '';

        if (state.gateOpen) return;

        state.isTransitioning = true;

        languagePanels.forEach(panel => {
            if (!panel.classList.contains('is-removed')) {
                hideElement(panel);
            }
        });

        window.setTimeout(() => {
            revealElement(getActiveLanguagePanel());
            state.isTransitioning = false;
        }, 680);
    }

    function showInquiry() {
        if (state.isTransitioning || state.gateOpen) return;

        state.isTransitioning = true;
        state.gateOpen = true;
        formStatus.textContent = '';
        updateLanguageCopy();

        const activePanel = getActiveLanguagePanel();
        hideElement(activePanel);

        window.setTimeout(() => {
            revealElement(gate);
            document.getElementById('identity').focus();
            state.isTransitioning = false;
        }, 680);
    }

    function returnToNode() {
        if (state.isTransitioning || !state.gateOpen) return;

        state.isTransitioning = true;
        state.gateOpen = false;
        formStatus.textContent = '';
        hideElement(gate);

        window.setTimeout(() => {
            revealElement(getActiveLanguagePanel());
            state.isTransitioning = false;
        }, 680);
    }

    languageButtons.forEach(button => {
        button.addEventListener('click', () => setLang(button.dataset.lang));
    });

    document.querySelectorAll('[data-open-gate]').forEach(button => {
        button.addEventListener('click', showInquiry);
    });

    backButton.addEventListener('click', returnToNode);

    document.addEventListener('keydown', event => {
        if (event.key === 'Escape' && state.gateOpen) {
            returnToNode();
        }
    });

    // Parallax Interaction, disabled automatically for touch-first devices and reduced-motion users.
    const canUseMotion = !window.matchMedia('(prefers-reduced-motion: reduce)').matches;
    const hasFinePointer = window.matchMedia('(pointer: fine)').matches;

    if (canUseMotion && hasFinePointer) {
        document.addEventListener('mousemove', event => {
            const moveX = (window.innerWidth / 2 - event.pageX) / 40;
            const moveY = (window.innerHeight / 2 - event.pageY) / 40;
            parallaxLayer.style.transform = `translate(${moveX}px, ${moveY}px)`;
        });
    }

    form.addEventListener('submit', async event => {
        event.preventDefault();
        formStatus.textContent = '';

        const formData = new FormData(form);
        const honeypot = String(formData.get('website') || '').trim();

        if (honeypot) {
            formStatus.textContent = copy[state.lang].bot;
            return;
        }

        if (!form.checkValidity()) {
            formStatus.textContent = copy[state.lang].invalid;
            form.reportValidity();
            return;
        }

        const payload = {
            identity: String(formData.get('identity') || '').trim(),
            email: String(formData.get('email') || '').trim(),
            language: state.lang,
            submittedAt: new Date().toISOString()
        };

        submitButton.disabled = true;
        submitButton.classList.add('opacity-40', 'cursor-not-allowed');

        try {
            // Replace this URL with your real endpoint, webhook, CRM form URL, or serverless function.
            // Example: await fetch('https://your-domain.com/api/access-request', { ... });
            const endpoint = '';

            if (endpoint) {
                const response = await fetch(endpoint, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });

                if (!response.ok) {
                    throw new Error('Submission failed');
                }
            } else {
                console.info('Access request payload:', payload);
            }

            form.reset();
            formStatus.textContent = copy[state.lang].success;

            // Insert your analytics or conversion event here.
            // Example:
            // gtag('event', 'access_request', { language: state.lang });
            // fbq('track', 'Lead');
        } catch (error) {
            formStatus.textContent = copy[state.lang].invalid;
            console.error(error);
        } finally {
            submitButton.disabled = false;
            submitButton.classList.remove('opacity-40', 'cursor-not-allowed');
        }
    });
</script>

</body>
</html>
