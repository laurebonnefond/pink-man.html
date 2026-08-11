# 🎀 Pink-Man — Le Labyrinthe de la Prévention

> **Un jeu d'arcade rétro dédié à la prévention du cancer du sein — Octobre Rose**

![HTML5](https://img.shields.io/badge/HTML5-Canvas-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?logo=javascript&logoColor=black)
![Licence](https://img.shields.io/badge/Licence-MIT-green)
![Responsive](https://img.shields.io/badge/Responsive-Mobile%20%2B%20Desktop-ff6090)

---

## 🎮 Jouer

👉 **[Jouer maintenant](https://laurebonnefond.github.io/PreventIA-LaB/pink-man.html)**

Aucune installation requise — fonctionne directement dans le navigateur (PC, tablette, smartphone).

---

## 📖 Concept

**Pink-Man** est un mini-jeu arcade inspiré de Pac-Man, entièrement repensé pour sensibiliser au **dépistage du cancer du sein** dans le cadre d'**Octobre Rose**.

Le joueur incarne **Pink-Man**, un petit personnage rose qui parcourt un labyrinthe en forme de jardin pour collecter des **gestes de prévention** tout en évitant les **facteurs de risque** personnifiés en méchants comiques.

### Objectif pédagogique

Chaque partie transmet des **messages clés** issus des recommandations officielles (INCa, HAS, INRS, CIRC) :

- Dépistage organisé gratuit entre 50 et 74 ans
- Impact de l'activité physique (−25 % de risque)
- Rôle de l'alimentation, de l'alcool, du tabac
- Travail de nuit comme facteur de risque reconnu (CIRC 2A)
- Autopalpation entre deux mammographies
- Chiffres clés : 61 000 cas/an, 90 % de guérison si détecté tôt

---

## 👹 Les Méchants — Facteurs de Risque

| Personnage | Facteur | Accessoire visuel |
|---|---|---|
| 🔴 ALCOOL | Consommation d'alcool | Bouteille de vin + cigarette |
| 🔵 TABAC | Tabagisme | Cigarette au bec + fumée |
| 🟢 SÉDENTARITÉ | Inactivité physique | ZZZ flottants + mini fauteuil |
| 🟠 SURPOIDS | Mauvaise alimentation | Burger flottant |
| 🟣 NUIT | Travail de nuit | Croissant de lune + étoiles |

Chaque méchant envoie des **répliques comiques** liées à son facteur de risque pour interpeler le joueur.

---

## 🎁 Items Santé & Récompenses

| Item | Points | Bonus |
|---|---|---|
| 🎀 Ruban Rose | 150 | +50 |
| 🩺 Mammographie | 300 | +100 |
| ❤️ Consultation | 200 | +70 |
| 👟 Baskets (activité physique) | 100 | +40 |
| 🥦 Brocoli | 80 | +30 |
| 🍎 Pomme | 80 | +30 |

Chaque collecte déclenche un **jingle de récompense**, une **pluie d'étoiles dorées** et un **message de prévention** bien visible.

---

## 🎀 Power-Up : Ruban Rose Magique

Les 4 rubans roses géants dans les coins du labyrinthe activent le **Mode Ruban Rose** pendant 8 secondes :
- Les méchants deviennent apeurés (bleus)
- Pink-Man peut les chasser et les éliminer
- Chaque élimination = message de prévention + points bonus

---

## 🕹️ Contrôles

| Plateforme | Contrôle |
|---|---|
| 🖥️ PC | Flèches directionnelles / WASD / ZQSD |
| 📱 Mobile | Joystick tactile (d-pad) |

---

## 🏗️ Architecture technique

- **Fichier unique** HTML + CSS + JavaScript — aucune dépendance externe
- **Canvas 2D** avec support Retina (`devicePixelRatio`)
- **Sprites procéduraux** — tout le pixel-art est dessiné par code
- **Web Audio API** — sons synthétisés sans fichier audio externe
- **Responsive** — redimensionnement automatique sur tout écran
- **60 FPS** — boucle optimisée via `requestAnimationFrame`
- **localStorage** — sauvegarde du meilleur score

---

## 📊 Chiffres clés affichés en fin de partie

15 messages rotatifs avec statistiques officielles :
- Taux de survie à 5 ans (87 %)
- Incidence annuelle (61 000 cas)
- Efficacité du dépistage précoce (90 % de guérison)
- Impact des facteurs de risque modifiables
- Gratuité du programme de dépistage organisé

---

## 🚀 Installation locale

```bash
# Cloner le repo
git clone https://github.com/laurebonnefond/PreventIA-LaB.git

# Ouvrir le jeu
open pink-man.html
# ou
python3 -m http.server 8000
# puis naviguer vers http://localhost:8000/pink-man.html
```

---

## 📁 Intégration dans PréventIA-LaB

Ce jeu fait partie de la suite **[PréventIA-LaB](https://laurebonnefond.github.io/PreventIA-LaB/)**, une collection d'outils numériques pour la prévention et la santé au travail.

Section : **Apprendre en s'amusant**

---

## 👩‍⚕️ Autrice

**Laure Bonnefond**
- IDE-ST & Préventrice — SPSTI 23/87
- Créatrice de PréventIA-LaB
- Passionnée par l'IA appliquée à la prévention santé

---

## 📄 Licence

MIT — Libre d'utilisation, modification et distribution.

Réalisé avec ❤️ pour **Octobre Rose** et la prévention du cancer du sein.

---

## 🔗 Sources scientifiques

- [INCa — Institut National du Cancer](https://www.e-cancer.fr/)
- [HAS — Dépistage du cancer du sein](https://www.has-sante.fr/)
- [INRS — Travail de nuit](https://www.inrs.fr/)
- [CIRC — Monographies](https://monographs.iarc.who.int/)
