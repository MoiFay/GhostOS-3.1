# 👻 GhostOS — Darknet Investigation Game

> *Un jeu de simulation d'OS darknet dans le navigateur. Infiltrez THE CORPORATION, collectez des preuves, gérez vos menaces — et ne vous faites pas tracer.*

![GhostOS](https://img.shields.io/badge/GhostOS-v3.1-00ff41?style=flat-square&labelColor=000000)
![Langage](https://img.shields.io/badge/Stack-HTML%20%2F%20CSS%20%2F%20JS-00ff41?style=flat-square&labelColor=000000)
![Taille](https://img.shields.io/badge/Taille-Single%20File-00ff41?style=flat-square&labelColor=000000)
![Durée](https://img.shields.io/badge/Durée-~25%20min-00ff41?style=flat-square&labelColor=000000)

---

## 🎮 Présentation

**GhostOS** est un jeu de navigateur en fichier HTML unique qui simule un système d'exploitation fictif de hacker. Le joueur navigue sur un réseau darknet pour collecter des preuves contre une organisation criminelle internationale, tout en gérant des menaces en temps réel.

**Pas d'installation. Pas de serveur. Ouvrez le fichier — jouez.**

---

## 📖 Histoire

Trois hommes — **Elias**, **Aurel** et **Emree** — ont tout perdu à cause de **THE CORPORATION**, une organisation criminelle internationale dirigée par **MAMADOUSTAR** et son co-fondateur **TWEKAAZ**.

Leurs femmes ont été enlevées et vendues. Leurs organes prélevés de force. Leurs vies détruites.

Ils vous financent via un intermédiaire codename **SPECTR3**. Votre mission : infiltrer les systèmes de THE CORPORATION, constituer un dossier de preuves irréfutables, et soumettre aux autorités avant qu'il soit trop tard.

---

## 🎯 Objectif

Collecter **15 preuves sur 23 disponibles** et soumettre le dossier en moins de **25 minutes réelles** (= 12 heures système).

---

## ⚙️ Mécaniques de jeu

### 🔍 Collecte de preuves
- Les 23 preuves sont distribuées **aléatoirement** à chaque partie dans 3 types d'emplacements :
  - **Pages darknet** — bouton `[ 🔒 SÉCURISER LA PREUVE ]` visible dans le contenu
  - **Code source HTML** — via l'outil Inspecter (clic droit), cherchez les éléments jaunes
  - **Téléchargements** — certains fichiers contiennent des données exploitables (d'autres sont infectés)
- Chaque collecte déclenche un **scan de 5 secondes** obligatoire
- **30% de chance d'intrusion** lors du scan — un mini-jeu s'ouvre :
  - ✅ Victoire → preuve sécurisée
  - ❌ Échec → preuve perdue + **une preuve de votre dossier est effacée**

### 🎯 Missions clients
- SPECTR3 transmet des missions de clients privés toutes les **~7 minutes**
- Missions **auto-acceptées** — vous avez **3 minutes** pour ouvrir le mail et lancer le hack
- 3 types de mini-jeux :
  - 🧩 **Séquence** — mémorisez et reproduisez 4 symboles
  - 🗺️ **Routage réseau** — tracez un chemin sur une grille
  - 🔓 **Décodage** — reconstituez un mot de passe lettre par lettre
- 10 clients possibles avec 7 types de missions différents

### ⚠️ Système de strikes
- Ignorer une mission ou échouer le mini-jeu = **STRIKE**
- **3 strikes = VIRÉ = FIN DE PARTIE**
- Compteur `● ● ●` visible dans la barre des tâches

### 🛡️ Antivirus — gestion critique
- SPECTR3 envoie des **codes PIN** par mail toutes les ~4-5 minutes
- Chaque licence dure **5 minutes**
- Procédure : copier le PIN → app Antivirus → ACTIVER LICENCE
- **Licence expirée + virus actif = BSOD = mort**

### 📈 Traçage
- Chaque collecte de preuve augmente le traçage
- À **100%** → agents localisés → fin de partie
- Gérez-le avec : purge cache TOR, nœuds proxy, GhostCloak, logiciels boutique

### 🔐 Pages verrouillées
- 3 pages aléatoires par partie sont protégées par chiffrement de niveau 5
- Pour débloquer : naviguer sur la page → acheter le **Crackeur (120 💰)** en boutique
- Le Crackeur est inactif si vous n'êtes pas sur la page verrouillée

### 😱 Screamers
- 5 intrusions psychologiques aléatoires de THE CORPORATION par partie
- Pas d'impact gameplay — uniquement pour déstabiliser le joueur

---

## 🗺️ Le réseau darknet

Plus de **30 pages** à explorer, organisées en réseaux :

| Réseau | Pages | Contenu |
|--------|-------|---------|
| `d4rkf0rum.onion` | Forum, leak, surveillance | Intelligence et rumeurs |
| `c0rp-1nt3rn4l.onion` | Finance, RH, mémos, exec | Documents internes CORP |
| `0ffsh0r3.onion` | Shell companies, comptes | Blanchiment d'argent |
| `m4rk3t.onion` | Armes, drogues, labo | Trafics |
| `bl4ckm41l.onion` | Politique, judiciaire | Chantage |
| `sh4d0w.onion` | Exec, surveillance, coup | Opérations classifiées |
| `0rg4n-m4rk3t.onion` | Organes | Trafic humain |
| `h-tr4d3.onion` | Victimes, traite | Trafic humain |
| `4rm5-c4t4log.onion` | Armement lourd | Catalogue & acheteurs |
| `sp3ctr3.onion` | Dead drop | Contact SPECTR3 |

---

## 🧰 Contre-mesures disponibles

| Outil | Effet | Source |
|-------|-------|--------|
| 🧹 **Purge cache TOR** | -6% traçage | Barre des tâches (cooldown 2 min) |
| 📡 **20 nœuds proxy TOR** | -12% traçage chacun | Texte cyan cliquable dans les pages et les sources |
| 👻 **GhostCloak** | 45s sans traçage | Boutique (140 💰, cooldown 3 min) |
| 🔐 **GhostVPN** | -15% vitesse traçage | Boutique (120 💰) |
| 🛡️ **TraceBlocker Pro** | -25% vitesse traçage | Boutique (180 💰, cumulable) |
| ⚡ **PurgeTurbo** | Cooldown purge → 1 min | Boutique (90 💰) |
| 🧹 **Purge Massive** | -18% traçage direct | Boutique (100 💰) |
| 🔧 **Kit d'urgence** | Supprime un virus sans licence AV | Boutique (160 💰) |

---

## 🔊 Système audio

Tous les sons sont **générés dynamiquement** via Web Audio API — aucun fichier audio externe.

- 🎵 **Musique de fond** — drone ambiant sombre, mélodie pentatonique mineure, percussions graves
- 17 effets sonores distincts (navigation, collecte, virus, licences, mini-jeux, victoire/défaite...)
- 🔊 **Contrôle de volume** via slider dans la barre des tâches

---

## 💀 Conditions de défaite

| Condition | Cause |
|-----------|-------|
| **Tracé** | Traçage atteint 100% |
| **BSOD** | Virus actif + licence AV expirée |
| **Temps écoulé** | 12h système épuisées (~25 min réelles) |
| **Viré** | 3 strikes accumulés |

---

## 🏆 Condition de victoire

Collecter 15 preuves → ouvrir l'app **📂 Dossier** → cliquer **[ ✅ SOUMETTRE LE DOSSIER ]**

---

## 🚀 Lancer le jeu

```bash
# Option 1 — Ouvrir directement dans le navigateur
open darknet_os_game.html

# Option 2 — Via un serveur local
python3 -m http.server 8080
# puis ouvrir http://localhost:8080/darknet_os_game.html
```

**Navigateurs supportés :** Chrome, Firefox, Edge (dernières versions)  
**Requis :** JavaScript activé, Web Audio API (supporté par tous les navigateurs modernes)

---

## 🛠️ Stack technique

- **100% HTML / CSS / JS vanilla** — aucune dépendance, aucun framework
- **Fichier unique** (`darknet_os_game.html`) — tout le jeu est dedans
- **Web Audio API** — génération sonore procédurale
- **Canvas API** — animation matrix de fond
- Fenêtres draggables/resizables natives en JS pur

---

## 📁 Structure du projet

```
darknet_os_game.html    ← Le jeu complet (fichier unique)
README.md               ← Ce fichier
```

---

## 🎨 Lore & personnages

| Personnage | Rôle |
|------------|------|
| **MAMADOUSTAR** | Fondateur / PDG de THE CORPORATION |
| **TWEKAAZ** | Co-fondateur, coordination des opérations terrain |
| **SPECTR3** | Intermédiaire mystérieux, ex-employé de THE CORPORATION |
| **Elias** | Client — rein prélevé, épouse vendue (LOT A-2047-FR-447) |
| **Aurel** | Client — deux reins prélevés, dialyse à vie, épouse vendue |
| **Emree** | Client — rein prélevé, maison saisie, épouse vendue |

---

## ⚠️ Avertissement

Ce jeu est une **fiction** à but ludique. Il simule un univers cyberpunk fictif. Tout personnage, organisation et événement sont entièrement inventés.

---

*GhostOS v3.1 — CLASSIFIED BUILD — 2049.dark*
