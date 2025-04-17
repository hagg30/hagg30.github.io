/* ------------------------------------------------------------------
   Global Design Tokens (Purple & Space Theme)
------------------------------------------------------------------ */
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Noto+Sans+KR:wght@400;500;700&display=swap');

:root {
  /* Primary Brand Colour */
  --color-primary: #9B5DE5;                /* Bright Purple */
  --color-primary-hover: #854fd1;

  /* Neutral Palette */
  --color-bg: #FFFFFF;
  --color-bg-alt: #F6F5FF;
  --color-text: #222222;
  --color-text-muted: #5E6E76;
  --color-border: #E2E8F0;

  /* Dark‑space gradient (for hero/sections) */
  --space-gradient: radial-gradient(circle at 50% 100%, #322d6c 0%, #1e1b4b 70%, #14132d 100%);

  /* Typography */
  --font-sans: 'Inter', 'Noto Sans KR', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
  --line-height-base: 1.65;
  --font-size-base: 1rem;
  --font-size-sm: 0.875rem;
  --font-size-lg: 1.125rem;
  --font-size-h1: clamp(2.1rem, 1.9rem + 1vw, 2.8rem);
  --font-size-h2: clamp(1.6rem, 1.5rem + .6vw, 2.1rem);
  --font-size-h3: clamp(1.35rem, 1.3rem + .3vw, 1.6rem);

  /* Layout */
  --container-max: 70rem;
  --spacing-1: 0.25rem;
  --spacing-2: 0.5rem;
  --spacing-3: 0.75rem;
  --spacing-4: 1rem;
  --spacing-5: 1.5rem;
  --radius-sm: 4px;
  --radius-md: 8px;
  --shadow-sm: 0 1px 2px rgba(0,0,0,.05);
  --shadow-md: 0 4px 12px rgba(0,0,0,.08);
}

/* ------------------------------------------------------------------
   Base Reset & Typography
------------------------------------------------------------------ */
* { box-sizing: border-box; }

html { font-size: 100%; scroll-behavior: smooth; }

body {
  margin: 0;
  font-family: var(--font-sans);
  font-size: var(--font-size-base);
  line-height: var(--line-height-base);
  color: var(--color-text);
  background: var(--color-bg);
}

/* Subtle vector star overlay */
body::before {
  content: "";
  position: fixed;
  inset: 0;
  pointer-events: none;
  background-image:
    radial-gradient(1px 1px at 25% 40%, rgba(255,255,255,.12) 0, transparent 100%),
    radial-gradient(1px 1px at 70% 80%, rgba(255,255,255,.08) 0, transparent 100%),
    radial-gradient(1px 1px at 10% 75%, rgba(255,255,255,.05) 0, transparent 100%);
  background-size: 600px 600px;
  z-index: -1;
}

h1, h2, h3, h4, h5, h6 {
  color: var(--color-text);
  line-height: 1.25;
  font-weight: 700;
  margin: 0 0 var(--spacing-3) 0;
}

h1 { font-size: var(--font-size-h1); }
h2 { font-size: var(--font-size-h2); }
h3 { font-size: var(--font-size-h3); }
h4 { font-size: 1.15rem; }
h5 { font-size: 1rem; }
h6 { font-size: 0.875rem; }

p, ul, ol { margin: 0 0 var(--spacing-4) 0; }
ul, ol { padding-left: 1.25rem; }

/* ------------------------------------------------------------------
   Links & Interactive
------------------------------------------------------------------ */
a {
  color: var(--color-primary);
  text-decoration: none;
  transition: color .15s ease;
}

a:hover, a:focus {
  color: var(--color-primary-hover);
  text-decoration: underline;
}

button, .btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  gap: var(--spacing-2);
  padding: var(--spacing-2) var(--spacing-4);
  font-size: var(--font-size-sm);
  font-weight: 500;
  color: #fff;
  background: var(--color-primary);
  border: none;
  border-radius: var(--radius-sm);
  cursor: pointer;
  transition: background .15s ease, transform .1s ease;
}

button:hover, .btn:hover { background: var(--color-primary-hover); }
button:active, .btn:active { transform: translateY(1px); }

/* ------------------------------------------------------------------
   Layout Helpers
------------------------------------------------------------------ */
.container { max-width: var(--container-max); margin-inline: auto; padding-inline: var(--spacing-4); }
.section { padding-block: var(--spacing-5) calc(var(--spacing-5) * 1.5); }
.section--alt { background: var(--color-bg-alt); }
.section--space { background: var(--space-gradient); color: #E2E8F0; }

/* ------------------------------------------------------------------
   Components
------------------------------------------------------------------ */
.card {
  background: #fff;
  border: 1px solid var(--color-border);
  border-radius: var(--radius-md);
  padding: var(--spacing-4);
  box-shadow: var(--shadow-sm);
  transition: box-shadow .2s ease;
}
.card:hover { box-shadow: var(--shadow-md); }
.card img { border-radius: var(--radius-sm); }

img, video { max-width: 100%; height: auto; display: block; }

pre, code {
  font-family: 'Fira Code', Menlo, monospace;
  background: #F3F4F6;
  color: #1F2937;
  border-radius: var(--radius-sm);
}
pre { padding: var(--spacing-4); overflow-x: auto; }

/* ------------------------------------------------------------------
   Dark Mode
------------------------------------------------------------------ */
@media (prefers-color-scheme: dark) {
  :root {
    --color-bg: #14132d;
    --color-bg-alt: #1b1a38;
    --color-text: #E4E7EB;
    --color-text-muted: #A0AEC0;
    --color-border: #2A2B4B;
  }
  pre, code { background: #1e1d3a; color: #E4E7EB; }
  .card { background: #1b1a38; }
}
