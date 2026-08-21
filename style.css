# RedlineLaunch — style.css

```css
/* =========================================
   REDLINELAUNCH
   Main stylesheet
   ========================================= */

:root {
    --red: #e50914;
    --red-bright: #ff1a26;
    --red-dark: #a8060e;

    --black: #050505;
    --dark: #0a0a0a;
    --dark-2: #101010;
    --dark-3: #161616;

    --white: #ffffff;
    --gray-100: #f4f4f4;
    --gray-300: #c4c4c4;
    --gray-500: #858585;
    --gray-700: #444444;

    --border: rgba(255, 255, 255, 0.09);

    --container: 1180px;
    --radius: 16px;
    --transition: 0.3s ease;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
    scroll-padding-top: 90px;
}

body {
    font-family: "Inter", sans-serif;
    background: var(--black);
    color: var(--white);
    line-height: 1.6;
    overflow-x: hidden;
}

a {
    color: inherit;
    text-decoration: none;
}

button {
    font: inherit;
}

.container {
    width: min(var(--container), calc(100% - 40px));
    margin: 0 auto;
}


/* =========================================
   NAVIGATION
   ========================================= */

.navbar {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 76px;
    z-index: 1000;

    background: rgba(5, 5, 5, 0.82);
    backdrop-filter: blur(18px);
    -webkit-backdrop-filter: blur(18px);

    border-bottom: 1px solid var(--border);
}

.nav-container {
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.logo {
    display: flex;
    align-items: center;
    gap: 10px;

    font-size: 18px;
    font-weight: 800;
    letter-spacing: -0.6px;
}

.logo-mark {
    width: 32px;
    height: 32px;

    display: grid;
    place-items: center;

    background: var(--red);
    color: white;

    font-size: 16px;
    font-weight: 900;

    border-radius: 7px;

    box-shadow: 0 0 24px rgba(229, 9, 20, 0.25);
}

.logo-accent {
    color: var(--red);
}

.nav-links {
    display: flex;
    align-items: center;
    gap: 34px;
}

.nav-links a {
    color: var(--gray-300);
    font-size: 13px;
    font-weight: 600;

    transition: var(--transition);
}

.nav-links a:hover {
    color: var(--white);
}

.nav-button {
    padding: 10px 18px;

    border: 1px solid rgba(229, 9, 20, 0.5);
    border-radius: 8px;

    background: rgba(229, 9, 20, 0.08);
    color: white;

    font-size: 13px;
    font-weight: 700;

    transition: var(--transition);
}

.nav-button:hover {
    background: var(--red);
    border-color: var(--red);
    transform: translateY(-1px);
}

.menu-toggle {
    display: none;

    width: 42px;
    height: 42px;

    background: transparent;
    border: 1px solid var(--border);
    border-radius: 8px;

    cursor: pointer;
}

.menu-toggle span {
    display: block;
    width: 19px;
    height: 2px;
    margin: 4px auto;

    background: white;

    transition: var(--transition);
}


/* =========================================
   HERO
   ========================================= */

.hero {
    min-height: 100vh;
    position: relative;

    display: flex;
    align-items: center;

    padding-top: 76px;

    overflow: hidden;

    background:
        radial-gradient(
            circle at 75% 45%,
            rgba(229, 9, 20, 0.13),
            transparent 30%
        ),
        var(--black);
}

.hero-grid {
    position: absolute;
    inset: 0;

    opacity: 0.25;

    background-image:
        linear-gradient(rgba(255,255,255,0.035) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255,255,255,0.035) 1px, transparent 1px);

    background-size: 70px 70px;

    mask-image: linear-gradient(
        to bottom,
        black,
        transparent 90%
    );
}

.hero-content {
    position: relative;
    z-index: 2;

    padding: 100px 0;
}

.hero-badge {
    display: inline-flex;
    align-items: center;
    gap: 9px;

    padding: 7px 12px;

    border: 1px solid var(--border);
    border-radius: 100px;

    background: rgba(255,255,255,0.025);

    color: var(--gray-300);

    font-size: 11px;
    font-weight: 700;
    letter-spacing: 0.5px;
    text-transform: uppercase;

    animation: fadeUp 0.8s ease both;
}

.status-dot {
    width: 7px;
    height: 7px;

    border-radius: 50%;

    background: var(--red);

    box-shadow: 0 0 12px var(--red);

    animation: pulse 2s infinite;
}

.hero h1 {
    max-width: 900px;

    margin-top: 28px;

    font-size: clamp(58px, 9vw, 112px);
    line-height: 0.92;
    letter-spacing: -6px;
    font-weight: 900;

    animation: fadeUp 0.8s 0.1s ease both;
}

.hero h1 span {
    display: block;
    color: var(--red);
}

.hero-text {
    max-width: 600px;

    margin-top: 32px;

    color: var(--gray-300);

    font-size: 17px;
    line-height: 1.8;

    animation: fadeUp 0.8s 0.2s ease both;
}

.hero-buttons {
    display: flex;
    gap: 12px;

    margin-top: 34px;

    animation: fadeUp 0.8s 0.3s ease both;
}

.button {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 12px;

    min-height: 48px;
    padding: 0 22px;

    border-radius: 8px;

    font-size: 13px;
    font-weight: 800;

    transition: var(--transition);
}

.button-primary {
    background: var(--red);
    color: white;

    box-shadow: 0 12px 35px rgba(229, 9, 20, 0.18);
}

.button-primary:hover {
    background: var(--red-bright);
    transform: translateY(-3px);
    box-shadow: 0 18px 45px rgba(229, 9, 20, 0.28);
}

.button-secondary {
    border: 1px solid var(--border);
    background: rgba(255,255,255,0.025);
    color: var(--gray-100);
}

.button-secondary:hover {
    border-color: rgba(255,255,255,0.2);
    background: rgba(255,255,255,0.06);
    transform: translateY(-3px);
}

.hero-stats {
    display: flex;
    align-items: center;
    gap: 22px;

    margin-top: 80px;

    animation: fadeUp 0.8s 0.4s ease both;
}

.stat {
    display: flex;
    flex-direction: column;
    gap: 2px;
}

.stat strong {
    color: var(--red);
    font-size: 12px;
}

.stat span {
    color: var(--gray-500);

    font-size: 11px;
    font-weight: 700;

    text-transform: uppercase;
    letter-spacing: 1px;
}

.stat-line {
    width: 45px;
    height: 1px;

    background: var(--border);
}

.hero-glow {
    position: absolute;

    right: -15%;
    top: 20%;

    width: 650px;
    height: 650px;

    border-radius: 50%;

    background: rgba(229, 9, 20, 0.07);

    filter: blur(100px);

    pointer-events: none;
}


/* =========================================
   GENERAL SECTIONS
   ========================================= */

.section {
    padding: 130px 0;
}

.section-label {
    display: flex;
    align-items: center;
    gap: 12px;

    color: var(--gray-500);

    font-size: 10px;
    font-weight: 800;

    letter-spacing: 1.5px;
    text-transform: uppercase;
}

.section-label span {
    color: var(--red);
}

.section-heading {
    max-width: 700px;
    margin-top: 28px;
}

.section-heading.centered {
    margin-left: auto;
    margin-right: auto;
    text-align: center;
}

.section-heading h2,
.about h2 {
    font-size: clamp(40px, 5vw, 68px);
    line-height: 1;
    letter-spacing: -3px;
    font-weight: 900;
}

.section-heading h2 span,
.about h2 span {
    display: block;
    color: var(--red);
}

.section-heading p {
    max-width: 540px;

    margin-top: 22px;

    color: var(--gray-500);

    font-size: 15px;
}


/* =========================================
   ABOUT
   ========================================= */

.about {
    border-top: 1px solid var(--border);
    background: var(--dark);
}

.about-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 100px;

    margin-top: 65px;
}

.about-copy {
    max-width: 530px;
}

.about-copy p {
    margin-bottom: 22px;

    color: var(--gray-300);

    font-size: 16px;
    line-height: 1.85;
}

.text-link {
    display: inline-flex;
    gap: 12px;

    margin-top: 12px;

    color: white;

    font-size: 13px;
    font-weight: 800;

    transition: var(--transition);
}

.text-link span {
    color: var(--red);
    transition: var(--transition);
}

.text-link:hover span {
    transform: translateX(5px);
}


/* =========================================
   SERVICES
   ========================================= */

.services {
    background: var(--black);
}

.service-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 12px;

    margin-top: 60px;
}

.service-card {
    min-height: 360px;

    position: relative;

    display: flex;
    flex-direction: column;

    padding: 28px;

    border: 1px solid var(--border);
    border-radius: var(--radius);

    background: var(--dark);

    overflow: hidden;

    transition: var(--transition);
}

.service-card:hover {
    transform: translateY(-7px);
    border-color: rgba(229, 9, 20, 0.35);
}

.service-card.featured {
    background:
        linear-gradient(
            145deg,
            rgba(229,9,20,0.13),
            rgba(255,255,255,0.015)
        ),
        var(--dark);
}

.service-number {
    color: var(--gray-700);

    font-size: 11px;
    font-weight: 800;
}

.service-icon {
    margin-top: 45px;

    color: var(--red);

    font-size: 27px;
}

.service-card h3 {
    margin-top: 20px;

    font-size: 18px;
    letter-spacing: -0.5px;
}

.service-card p {
    margin-top: 12px;

    color: var(--gray-500);

    font-size: 13px;
    line-height: 1.7;
}

.service-card a {
    margin-top: auto;

    color: var(--gray-300);

    font-size: 11px;
    font-weight: 800;

    transition: var(--transition);
}

.service-card a:hover {
    color: var(--red);
}


/* =========================================
   PROCESS
   ========================================= */

.process {
    border-top: 1px solid var(--border);
    background: var(--dark);
}

.process-grid {
    display: grid;
    grid-template-columns: 1fr auto 1fr auto 1fr;
    align-items: start;

    margin-top: 70px;
}

.process-step {
    text-align: center;
}

.process-circle {
    width: 70px;
    height: 70px;

    display: grid;
    place-items: center;

    margin: 0 auto;

    border: 1px solid rgba(229,9,20,0.4);
    border-radius: 50%;

    background: rgba(229,9,20,0.06);

    color: var(--red);

    font-size: 12px;
    font-weight: 900;
}

.process-step h3 {
    margin-top: 22px;

    font-size: 18px;
}

.process-step p {
    max-width: 240px;

    margin: 10px auto 0;

    color: var(--gray-500);

    font-size: 13px;
    line-height: 1.7;
}

.process-connector {
    width: 100px;
    height: 1px;

    margin-top: 35px;

    background: linear-gradient(
        90deg,
        transparent,
        rgba(229,9,20,0.5),
        transparent
    );
}


/* =========================================
   CTA
   ========================================= */

.cta-section {
    padding: 100px 0;
    background: var(--black);
}

.cta-box {
    position: relative;

    padding: 100px 40px;

    text-align: center;

    border: 1px solid rgba(229,9,20,0.2);
    border-radius: 22px;

    background:
        radial-gradient(
            circle at 50% 100%,
            rgba(229,9,20,0.15),
            transparent 45%
        ),
        var(--dark);

    overflow: hidden;
}

.cta-box .section-label {
    justify-content: center;
}

.cta-box h2 {
    position: relative;

    margin-top: 25px;

    font-size: clamp(42px, 6vw, 76px);
    line-height: 0.95;
    letter-spacing: -4px;
    font-weight: 900;
}

.cta-box h2 span {
    display: block;
    color: var(--red);
}

.cta-box p {
    position: relative;

    max-width: 500px;

    margin: 25px auto 30px;

    color: var(--gray-500);

    font-size: 15px;
}

.button-light {
    position: relative;

    background: white;
    color: black;
}

.button-light:hover {
    background: var(--red);
    color: white;
    transform: translateY(-3px);
}

.cta-glow {
    position: absolute;

    width: 300px;
    height: 300px;

    left: 50%;
    bottom: -240px;

    transform: translateX(-50%);

    background: var(--red);

    filter: blur(100px);
    opacity: 0.18;
}


/* =========================================
   FOOTER
   ========================================= */

.footer {
    border-top: 1px solid var(--border);
    background: var(--black);
}

.footer-container {
    padding: 50px 0 25px;
}

.footer-brand p {
    margin-top: 12px;

    color: var(--gray-700);

    font-size: 12px;
}

.footer-links {
    display: flex;
    gap: 25px;

    margin-top: 35px;
}

.footer-links a {
    color: var(--gray-500);

    font-size: 12px;
    font-weight: 600;

    transition: var(--transition);
}

.footer-links a:hover {
    color: white;
}

.footer-bottom {
    display: flex;
    justify-content: space-between;

    margin-top: 45px;
    padding-top: 20px;

    border-top: 1px solid var(--border);

    color: var(--gray-700);

    font-size: 10px;
}


/* =========================================
   ANIMATIONS
   ========================================= */

@keyframes fadeUp {
    from {
        opacity: 0;
        transform: translateY(25px);
    }

    to {
        opacity: 1;
        transform: translateY(0);
    }
}

@keyframes pulse {
    0%, 100% {
        opacity: 1;
        transform: scale(1);
    }

    50% {
        opacity: 0.45;
        transform: scale(0.75);
    }
}


/* =========================================
   RESPONSIVE
   ========================================= */

@media (max-width: 950px) {

    .nav-links {
        position: absolute;

        top: 76px;
        left: 20px;
        right: 20px;

        display: none;
        flex-direction: column;
        align-items: stretch;

        padding: 15px;

        border: 1px solid var(--border);
        border-radius: 12px;

        background: rgba(10,10,10,0.98);
    }

    .nav-links.active {
        display: flex;
    }

    .nav-links a {
        padding: 12px;
    }

    .nav-button {
        display: none;
    }

    .menu-toggle {
        display: block;
    }

    .service-grid {
        grid-template-columns: repeat(2, 1fr);
    }

    .process-grid {
        grid-template-columns: 1fr;
        gap: 35px;
    }

    .process-connector {
        width: 1px;
        height: 40px;

        margin: 0 auto;
    }

}


@media (max-width: 700px) {

    .container {
        width: min(var(--container), calc(100% - 28px));
    }

    .hero h1 {
        font-size: clamp(52px, 16vw, 82px);
        letter-spacing: -4px;
    }

    .hero-text {
        font-size: 15px;
    }

    .hero-buttons {
        flex-direction: column;
        align-items: stretch;
    }

    .hero-buttons .button {
        width: 100%;
    }

    .hero-stats {
        margin-top: 55px;
    }

    .about-grid {
        grid-template-columns: 1fr;
        gap: 40px;
    }

    .service-grid {
        grid-template-columns: 1fr;
    }

    .service-card {
        min-height: 300px;
    }

    .section {
        padding: 90px 0;
    }

    .cta-section {
        padding: 70px 0;
    }

    .cta-box {
        padding: 75px 22px;
    }

    .footer-bottom {
        flex-direction: column;
        gap: 8px;
    }

}
```
