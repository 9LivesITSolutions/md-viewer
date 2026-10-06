# md-viewer

> Éditeur Markdown épuré, sans dépendance, avec aperçu en direct — un seul fichier HTML, aucune étape de build.

![HTML](https://img.shields.io/badge/HTML-single--file-orange?logo=html5)
![No dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Version](https://img.shields.io/badge/version-1.0.0-green)

[English version](README.md)

Un éditeur Markdown autonome avec aperçu en direct — pas de build, pas de serveur, aucune dépendance à installer. Ouvrez `md-viewer.html` dans un navigateur récent et commencez à écrire.

![md-viewer screenshot](https://github.com/user-attachments/assets/5d395cd6-a790-4e50-9139-9c0525b3b899)

---

## Fonctionnalités

- **Aperçu en temps réel** — le rendu se met à jour à chaque frappe
- **Glisser-déposer** — déposez un fichier `.md` / `.markdown` / `.txt` sur le panneau d'édition
- **Défilement synchronisé** — l'éditeur et l'aperçu défilent ensemble (activable/désactivable)
- **Panneaux redimensionnables** — faites glisser la séparation pour ajuster la répartition éditeur/aperçu (20 %–80 %)
- **Export PDF** — ouvre une page prête à imprimer via la boîte de dialogue d'impression du navigateur
- **Copier le HTML** — copie le HTML généré dans le presse-papiers en un clic
- **Coloration syntaxique** — blocs de code rendus avec highlight.js (thème GitHub)
- **Support GFM** — tableaux, listes de tâches, texte barré, sauts de ligne (marked.js v9)

---

## Utilisation

Aucune installation requise.

```
# Cloner
git clone https://github.com/9LivesITSolutions/md-viewer.git
cd md-viewer

# Ouvrir
open md-viewer.html          # macOS
start md-viewer.html         # Windows
xdg-open md-viewer.html      # Linux
```

Ou téléchargez simplement `md-viewer.html` et ouvrez-le directement dans votre navigateur.

---

## Raccourcis et commandes

| Action                | Commande                                       |
| --------------------- | ---------------------------------------------- |
| Ouvrir un fichier     | Cliquer sur **Open file** ou glisser-déposer   |
| Vider l'éditeur       | Cliquer sur **Clear**                          |
| Copier le HTML rendu  | Cliquer sur **Copy HTML**                      |
| Export / impression PDF | Cliquer sur **Export PDF**                   |
| Défilement synchronisé | Interrupteur dans l'en-tête                   |

---

## Pile technique

| Composant            | Bibliothèque / Source                                           |
| -------------------- | --------------------------------------------------------------- |
| Analyseur Markdown   | [marked.js](https://marked.js.org/) v9.1.6 — GFM activé         |
| Coloration syntaxique | [highlight.js](https://highlightjs.org/) v11.9.0 — thème GitHub |
| Polices              | Inter · Merriweather · Fira Code (Google Fonts)                 |
| Build                | Aucun — un seul fichier HTML autonome                           |

Les ressources CDN sont chargées depuis `cdnjs.cloudflare.com` et `fonts.googleapis.com`. L'outil fonctionne hors ligne si ces ressources sont en cache dans le navigateur.

---

## Navigateurs supportés

Fonctionne avec tous les navigateurs modernes : Chrome 90+, Firefox 88+, Safari 14+, Edge 90+.

---

## Contribuer

1. Forker le dépôt
2. Créer une branche (`git checkout -b feature/ma-fonctionnalite`)
3. Commiter (`git commit -m 'feat: add ma-fonctionnalite'`)
4. Pousser la branche (`git push origin feature/ma-fonctionnalite`)
5. Ouvrir une Pull Request

Merci de suivre les [Conventional Commits](https://www.conventionalcommits.org/) pour les messages de commit.

---

## Licence

Ce projet est distribué sous licence MIT. Voir le fichier [LICENSE](LICENSE).

---

Maintenu par **9 Lives IT Solutions** — Informatique de santé & automatisation d'infrastructure.
