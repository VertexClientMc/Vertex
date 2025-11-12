# 🧩 Vertex Client – Modules (Minecraft 1.8.9)

Ce dépôt contient les différentes **explications** du mod *Vertex Client*, un ensemble de modules développés pour **Minecraft Forge 1.8.9**.  
Chaque module fonctionne de manière indépendante et peut être activé ou désactivé via le **menu principal du mod (GUI)**.

---

## 🔧 Liste des modules

### 🩹 PatchCrumbs
Affiche une **box** indiquant l’emplacement exact où un tir de canon TNT va exploser.  
Le module trace également un **faisceau** montrant la trajectoire du tir et affiche les **coordonnées** de l’impact.  
Utile pour visualiser et bloquer la trajectoire des canons TNT.

---

### 💥 Explosion Boxes
Affiche l’**explosion d’une TNT** sous forme d’un cube (box) à l’emplacement de l’explosion.  
Permet de visualiser précisément l’emplacement des explosions.

---

### 📦 Dispenser Check
Analyse automatiquement les **dispensers** lorsqu’ils sont ouverts :  
- Les dispensers contenant de la TNT sont surlignés en **vert**  
- Les vides ou incomplets s’affichent en **rouge**  
Le module referme l’interface quasi instantanément, ce qui permet de vérifier rapidement les stocks lors d’un pillage ou d’un check automatique.

---

### ⚡ No Lag
Réduit considérablement les **baisses de FPS** en désactivant certains effets lourds.  
Optimise le rendu des entités, des particules et limite les mises à jour hors champ de vision.  
Idéal pour les farms ou les pc moins puissantes.

---

### 💧 Clear Liquid
Rend l'intérieur **liquides (eau et lave)** totalement transparents afin d’améliorer la visibilité.  
Très utile pour voir dans l’eau et dans la lave.

---

### 🧱 Chunk Borders
Affiche les **bordures des chunks (16×16 blocs)** en jeu.  
Permet de visualiser clairement les limites de génération, utile pour :  
- La redstone  
- Le build organisé  
- Le repérage précis des transitions de chunks  

---

### 💡 FullBright
Force la **luminosité maximale** dans toutes les conditions.  
Remplace l’éclairage dynamique du jeu, idéal pour les grottes ou les zones non éclairées.

---

### 🧊 Block Outline
Affiche un **contour 3D personnalisable** autour du bloc visé.  
Possibilité de modifier la couleur, l’épaisseur et la transparence via le GUI.  
Améliore la précision de placement ou de sélection en Build.

---

### 🔓 Bypass Captcha (Hadaria)
- Automatise la **résolution des captchas Hadaria** (clic sur la lettre cible).
- **Délais min/max** configurables (en secondes).
- **Cooldown** entre deux résolutions (en minutes) pour éviter le spam.
- **Sécurités** : désactivation auto si **MP** ou **TP** détectés (+ option **alerte sonore**).
- **Webhook Discord** : champs **URL** + **Test**, mention utilisateur/role optionnelle.

---

### 🎃 Script Citrouille
Permet de **farmer automatiquement les citrouilles** sur des coordonnées configurées.  
- Supporte plusieurs “home” configurables  
- Active un **boost de clic** pour casser plus vite une rangée complète  

---

### 🌿 Script Verrue
Permet de **farmer automatiquement les verrues** sur des coordonnées configurées.  
- Supporte plusieurs “home” configurables 
- Compatible avec différents layouts de farms

---

### 🎥 Recorder
Enregistre les **séquences de jeu** (positions, actions, mouvements de caméra).  
- Sauvegarde locale dans un format lisible  
- Peut être déclenché plusieurs fois ou en boucle infinie  
- Parfait pour farmer ou repeter une actions enregistré

---

### 🎣 AutoFish
Détecte le moment exact où un poisson mord à l’hameçon, puis clique automatiquement pour récupérer la prise.  
Répète ensuite le lancer pour une **pêche 100% automatisée**.  
Prend en charge la durabilité restante.

---

### 🖱️ AutoClick
Simule des **clics automatiques** configurables :  
- Activation sur clic maintenu
- Filtrage selon l’objet tenu (épée, outil, etc.)  
Utilisé pour le **PvP**, le **farming** ou les **actions répétitives**.

---

### 🎯 AimAssist
Aide la visée sur les **joueurs ennemis proches du réticule**.  
Le comportement est entièrement paramétrable :  
- Distance maximale  
- Angle de détection  
- Vitesse horizontale / verticale  
- Mode “click-only” ou “sword-only”  
Inclut un **lissage (smoothing)** des mouvements de caméra pour un rendu naturel.

---

### 👁️ Focus
Permet de **verrouiller une cible** (joueur ou faction entière) et de la voir, même à travers les foules ou les blocs.  
Idéal pour le **tracking en event**, le **repérage en pillage** ou la **surveillance de joueurs**.

---

### ⏱️ TickLock
Active automatiquement la **parade (block)** pendant 1 seconde dès qu’un coup ou dégât est détecté.  
Permet d’éviter les resets en event totem.  

---

### 🪶 Fly Boost
Augmente la **vitesse de vol** du joueur en fly. 
Réglable dynamiquement depuis le GUI pour s’adapter à la vitesse.

---

### 🛰️ FreeCam
Détache la caméra du corps du joueur pour une **exploration libre**.  
Permet de voler à travers les murs ou d’observer des zones sans se déplacer réellement.  
Utile pour la **reconnaissance**, la **cinématique** ou la **surveillance**.

---

### 🧭 StashFinder
Analyse les **chunks chargés** pour détecter des **coffres ou entités de stockage cachées**.  
- Envoi automatique des coordonnées dans le chat ou via **webhook Discord** configurable  
- Outil puissant pour les joueurs explorant ou pillant des sky/droppers

---

### 📡 Near Detector
Surveille en permanence la **présence de joueurs proches**.  
- Alerte via **webhook Discord**  
- Peut déclencher un **Alt+F4 automatique** ou **désactiver tous les modules Vertex** si un joueur blacklisté est détecté  
Très utile pour detecter des staffs.

---

### 🎥 Freelook
Permet de **regarder autour de soi librement** sans modifier la direction réelle du joueur.  
Reproduit une **vue à 360°** fluide, parfaite pour observer les alentours sans bouger.

---

## 🧠 Remarques

- Tous les modules fonctionnent sur **Minecraft Forge 1.8.9**.  
- Les configurations sont sauvegardées automatiquement et restaurées au prochain lancement.  
- Chaque `module` est **indépendant** et activable individuellement via le **GUI Vertex**.

---

© 2025 – Vertex Client 
