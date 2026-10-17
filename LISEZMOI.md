<!--
  Nom      : LISEZMOI.md
  Objet    : Présentation du dépôt policy (politiques de confidentialité Android et outils GitHub)
  Auteur   : Eric PERRET
  Date     : 2026-10-17
  Licence  : GPL v3
-->

# 🔏 Policy

🇬🇧 [English version: README.md](README.md)

Ce dépôt héberge, par GitHub Pages, les politiques de confidentialité de mes applications Android (adresses publiques déclarées dans les fiches des applications), les fichiers APK correspondants, et quatre petits outils de gestion de mes dépôts GitHub. Pages en français (politique SUN NORTH SAT : multilingue).

> Les noms des pages de politique ne doivent pas changer : leurs adresses sont référencées par les fiches des applications.

## Politiques de confidentialité

| Application | Page | Capture |
|---|---|---|
| SUN NORTH SAT & HD QRA Finder | ▶️ [policy.html](https://ericperret.github.io/policy/policy.html) | [voir](captures/policy.png) |
| Morse Flash Light RX/TX | ▶️ [policy-cw.html](https://ericperret.github.io/policy/policy-cw.html) | [voir](captures/policy-cw.png) |
| Mini Puzzle | ▶️ [puzzle.html](https://ericperret.github.io/policy/puzzle.html) | [voir](captures/puzzle.png) |
| SSTV TX Robot 36 | ▶️ [sstv_privacy_policy.html](https://ericperret.github.io/policy/sstv_privacy_policy.html) | [voir](captures/sstv_privacy_policy.png) |

## Applications Android (APK)

| Fichier | Application |
|---|---|
| `app-release.apk-sun` | SUN NORTH SAT & HD QRA Finder |
| `app-release.apk-sstv` | SSTV TX Robot 36 |
| `app-release.apk-minipuzzle` | Mini Puzzle |
| `app-release.apk` | version de publication sans suffixe |

Pour installer un APK à suffixe, le renommer en `.apk` après téléchargement.

## Outils GitHub

![GitHub Pages Activator](captures/github-pages-activator.png)

| Outil | Lancer | Rôle |
|---|---|---|
| GitHub Pages Activator | ▶️ [github-pages-activator.html](https://ericperret.github.io/policy/github-pages-activator.html) | Active GitHub Pages sur un dépôt, ou sur tous |
| GitHub Topics Updater | ▶️ [github-topics-updater.html](https://ericperret.github.io/policy/github-topics-updater.html) | Met à jour les sujets (topics) et les descriptions des dépôts |
| Index Generator | ▶️ [index-generator.html](https://ericperret.github.io/policy/index-generator.html) | Analyse un dépôt et génère un `index.html` listant ses pages HTML |
| README Injector | ▶️ [readme-injector.html](https://ericperret.github.io/policy/readme-injector.html) | Dépose un fichier (README…) dans un dépôt choisi |

Ces outils appellent l'API GitHub directement depuis le navigateur avec un jeton personnel (droit `public_repo`) saisi sur la page : le jeton n'est envoyé qu'à l'API GitHub. Le révoquer après usage.

## Déploiement

GitHub Pages est publié par le workflow `.github/workflows/static.yml` à chaque envoi sur `main`.

## Historique

| Version | Évolution |
|---|---|
| 2026-10-17 | `readme-injector (3).html` renommé `readme-injector.html`, cartouches, README / LISEZMOI créés, captures |

## Licence

[GPL v3](LICENSE)

## Auteur

**Eric PERRET** — [GitHub](https://github.com/ericperret)
