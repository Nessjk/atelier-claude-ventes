---
theme: default
title: Atelier Claude - analyse des ventes
info: Atelier d'une heure. De l'export brut à une analyse que Claude refait tous les mois.
colorSchema: light
transition: slide-left
mdc: true
duration: 60min
fonts:
  sans: Inter
  serif: Fraunces
  mono: JetBrains Mono
layout: cover
class: cover-dark
---

<div class="kicker">Atelier · 1 heure</div>

# De l'export brut à l'analyse qui se refait toute seule

<p class="text-lg opacity-75 max-w-200">Claude desktop, Claude in Chrome et Claude Code, sur de vraies ventes web.</p>

<div class="abs-bl m-10 flex gap-3 text-sm">
  <span class="px-3 py-1 rounded-full bg-white/10"><ph-desktop-duotone class="inline mr-1" />Claude desktop</span>
  <span class="px-3 py-1 rounded-full bg-white/10"><ph-browser-duotone class="inline mr-1" />Claude in Chrome</span>
  <span class="px-3 py-1 rounded-full bg-white/10"><ph-terminal-window-duotone class="inline mr-1" />Claude Code</span>
</div>

---

<div class="kicker">Avant de commencer</div>

# Trois choses à préparer

<div class="grid grid-cols-[1fr_1fr_1.45fr] gap-5">

<div class="card">
  <div class="flex items-center gap-2 mb-2"><span class="badge">1</span><strong>Claude desktop</strong></div>
  <p class="text-sm text-[var(--muted)]">Installez l'application, puis connectez-vous avec votre compte.</p>
  <a class="chip-link" href="https://claude.com/download" target="_blank"><ph-download-simple-bold />claude.com/download</a>
</div>

<div class="card">
  <div class="flex items-center gap-2 mb-2"><span class="badge">2</span><strong>Claude in Chrome</strong></div>
  <p class="text-sm text-[var(--muted)]">L'extension qui laisse Claude lire et naviguer dans vos onglets.</p>
  <a class="chip-link" href="https://claude.com/chrome" target="_blank"><ph-puzzle-piece-bold />claude.com/chrome</a>
</div>

<div class="card">
  <div class="flex items-center gap-2 mb-2"><span class="badge">3</span><strong>Fichiers de l'atelier</strong></div>
  <div class="file"><ph-microsoft-excel-logo-duotone class="text-xl text-[var(--teal)]" /><div><code>ventes_web_brutes_juin_juil_aout_25_26.xlsx</code><small>Export Sage des ventes web</small></div></div>
  <div class="file"><ph-file-csv-duotone class="text-xl text-[var(--teal)]" /><div><code>prix_lancement_shopify.csv</code><small>Export Shopify des prix de lancement</small></div></div>
  <div class="file"><ph-sparkle-duotone class="text-xl text-[var(--accent)]" /><div><code>ventes-sport-heros.skill</code><small>Le skill de la fin</small></div></div>
  <a class="chip-link" href="https://drive.google.com/drive/folders/1FjCK7nBCLfPyuM8hZVUQKPMW0Uvik2UN?usp=sharing" target="_blank"><ph-google-drive-logo-bold />Dossier Google Drive</a>
</div>

</div>

---

<div class="kicker">Le déroulé</div>

# Dix étapes, trois outils

<div class="grid grid-cols-3 gap-5 steps">

<div v-click class="card col setup">
  <div class="col-head"><ph-gear-six-duotone />Mise en place</div>
  <div class="step"><span class="badge">1</span>Installer Claude desktop et se connecter</div>
  <div class="step"><span class="badge">2</span>Configurer les connecteurs</div>
  <div class="step"><span class="badge">3</span>Installer l'extension Chrome</div>
</div>

<div v-click class="card col chrome">
  <div class="col-head"><ph-browser-duotone />Claude in Chrome</div>
  <div class="step"><span class="badge">4</span>Collecter des données : scraper un site web en exemple</div>
</div>

<div v-click class="card col code">
  <div class="col-head"><ph-terminal-window-duotone />Claude Code</div>
  <div class="step"><span class="badge">5</span>Créer un projet</div>
  <div class="step"><span class="badge">6</span>Ajouter les fichiers</div>
  <div class="step"><span class="badge">7</span>Nettoyer et vérifier</div>
  <div class="step"><span class="badge">8</span>Importer un skill de nettoyage</div>
  <div class="step"><span class="badge">9</span>Analyser</div>
  <div class="step"><span class="badge">10</span>Créer un skill</div>
</div>

</div>

<style>
.steps .col { padding-top: .9rem; }
.col-head {
  display: flex; align-items: center; gap: .5rem;
  font-weight: 700; font-size: .8rem; letter-spacing: .08em; text-transform: uppercase;
  padding-bottom: .6rem; margin-bottom: .3rem; border-bottom: 2px solid currentColor;
}
.col-head svg { font-size: 1.3rem; }
.step { display: flex; align-items: center; gap: .65rem; padding: .42rem 0; font-size: .92rem; line-height: 1.25; }
.setup .col-head { color: var(--gold); }
.setup .badge { background: var(--gold-soft); color: var(--gold); }
.chrome .col-head { color: var(--teal); }
.chrome .badge { background: var(--teal-soft); color: var(--teal); }
.code .col-head { color: var(--accent); }
</style>

---

<div class="kicker">Pour aller plus loin</div>

# Refaire l'analyse, n'importe quel mois

<div class="grid grid-cols-2 gap-5">

<div class="card">
  <div class="flex items-center gap-2 mb-2"><ph-sparkle-duotone class="text-2xl text-[var(--accent)]" /><strong>Installer le skill</strong></div>
  <p class="text-sm text-[var(--muted)] mb-3">Claude desktop → Paramètres → Capacités → Skills → importer <code>ventes-sport-heros.skill</code></p>
  <div class="prompt">« Refais l'analyse sport héros pour septembre-octobre, 2026 vs 2025 »</div>
</div>

<div class="card">
  <div class="flex items-center gap-2 mb-2"><ph-github-logo-duotone class="text-2xl" /><strong>Skills d'analyse de données</strong></div>
  <p class="text-sm text-[var(--muted)]">Audit qualité (<code>data-quality-audit</code>), EDA, cohortes, séries temporelles, synthèse pour la direction.</p>
  <a class="chip-link" href="https://github.com/nimrodfisher/data-analytics-skills" target="_blank"><ph-arrow-square-out-bold />nimrodfisher/data-analytics-skills</a>
</div>

</div>

<style>
.prompt {
  font-family: 'Fraunces', serif; font-style: italic; font-size: 1.05rem;
  padding: .8rem 1rem; border-left: 3px solid var(--accent);
  background: var(--accent-soft); border-radius: 0 10px 10px 0;
}
</style>

---
layout: center
class: cover-dark text-center
---

# Merci

<p class="opacity-70">Questions, cas d'usage, prochaines analyses.</p>
