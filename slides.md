---
theme: default
title: Atelier Claude - analyse des ventes
info: Atelier d'une heure. De l'export brut à une analyse que Claude refait tous les mois.
layout: cover
transition: slide-left
mdc: true
duration: 60min
---

# Atelier Claude

De l'export brut à une analyse qu'on relance chaque mois

<div class="abs-bl m-6 text-sm opacity-60">1 heure · Claude desktop · Claude in Chrome</div>

---
layout: two-cols-header
---

# Avant de commencer

::left::

### 1. Installer Claude desktop

<a href="https://claude.com/download" target="_blank" class="big-link">claude.com/download</a>

Connectez-vous avec votre compte, puis ouvrez l'application.

### 2. Installer Claude in Chrome

<a href="https://claude.com/chrome" target="_blank" class="big-link">claude.com/chrome</a>

::right::

### 3. Télécharger les fichiers de l'atelier

<a href="LIEN_GOOGLE_DRIVE" target="_blank" class="big-link">Dossier Google Drive</a>

- `ventes_web_brutes_juin_juil_aout_25_26.xlsx`<br><span class="note">Export Sage des ventes web</span>
- `prix_lancement_shopify.csv`<br><span class="note">Export Shopify des prix de lancement</span>
- `ventes-sport-heros.skill`<br><span class="note">Le skill de la fin</span>

Rangez-les dans un même dossier, on s'en sert pour le projet.

<style>
.big-link { display: inline-block; font-size: 1.4rem; font-weight: 600; margin: .25rem 0 .5rem; }
li code { font-size: .7em; white-space: nowrap; }
.note { font-size: .85em; opacity: .65; }
</style>

---

# Le déroulé

<v-clicks>

1. **Configurer Claude.** Créer un projet et y déposer les deux fichiers.
2. **Installer l'extension.** Claude in Chrome, pour aller chercher les données là où elles sont.
3. **Collecter les données.** Export Sage des ventes, export Shopify des prix de lancement.
4. **Nettoyer.** Avoirs, lignes à zéro, orthographes des sports héros.
5. **Vérifier.** Contrôles, prix non trouvés, CA couvert.
6. **Analyser.** N vs N-1 par sport héros : CA, quantités, PVM, taux de marque.
7. **En faire un skill.** Même analyse, n'importe quels mois, en une phrase.

</v-clicks>

---

# Pour aller plus loin

- Installer le skill `ventes-sport-heros.skill`<br>Claude desktop → Paramètres → Capacités → Skills → importer
- Puis demander : *« Refais l'analyse sport héros pour septembre-octobre, 2026 vs 2025 »*
- D'autres skills d'analyse de données pour Excel :
  <a href="https://github.com/nimrodfisher/data-analytics-skills" target="_blank">github.com/nimrodfisher/data-analytics-skills</a>

---
layout: end
---

# Merci
