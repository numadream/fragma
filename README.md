# Concept inédit : **“FRAGMA”**

> *« Construisez un tableau vivant avant que le sablier numérique ne s’écoule »*

### 1. Pitch ultra-court

Puzzle narratif solo où l’on **repère** et **place** à toute vitesse des fragments d’illustration pour compléter des “tableaux” oniriques. Chaque fragment posé déclenche des **effets de combo** (ressources, pouvoirs, nouvelles contraintes) façon engine-building. Objectif : finir le tableau avant la fin du timer et obtenir la note maxi.

### 2. Comment ça transpose les classiques ?

| Source d’inspiration                             | Transposition dans Fragma                                                                                                                                         |
| ------------------------------------------------ |-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Dobble/Jungle Speed** – repérer le bon symbole | Le joueur fait défiler une “rivière” de fragments et doit toucher-glisser ceux qui **partagent exactement 1 élément commun** avec le tableau en cours.            |
| **7 Wonders** – synergies de couleurs/icônes     | Chaque fragment a 1 ou 2 **pictogrammes** : aligner trois “Lune” débloque un pouvoir “ralentir le sablier”, etc. Les combos deviennent de plus en plus profondes. |
| **Dixit** – imagerie poétique                    | Les tableaux sont générés par IA (stable diffusion custom) autour d’un thème (voyage, mythes, souvenirs…), donc **variété infinie** + style français/BD.          |

### 3. Boucle de jeu (≈ 3 mn)

1. **Choix du Tableau** (thème + difficulté).
2. **Phase “Flux” (60–90 s)** :
    * Un ruban horizontal défile ; le joueur repère rapidement les fragments compatibles (pattern-matching).
    * Drag & drop sur le canevas → déclenche combos/bonus.
3. **Phase “Sablier”** : si le tableau n’est pas terminé à temps, le joueur peut **sacrifier** des fragments rares collectés auparavant pour gagner 15 s supplémentaires ; dilemme d’optimisation.
4. **Score & Rareté** : note des combos, vitesse, fragments restants.
5. **Progression roguelite** : les fragments rares rejoignent la collection permanente (deck-building léger). Débloque pouvoirs et nouveaux modes.

### 4. Modes & rejouabilité

| Mode                | Spécificité                                                                                             |
| ------------------- | ------------------------------------------------------------------------------------------------------- |
| **Saga**            | Suite de 7 tableaux liés par un petit texte interactif ; difficulté croissante, sauvegarde automatique. |
| **Défi Journalier** | Un même tableau pour toute la communauté → classement mondial (mais le gameplay reste solo).            |
| **Zen**             | Pas de timer, score basé sur l’esthétique finale (pour les joueurs chill).                              |

### 5. Monétisation & éthique

* **Premium light** (4,99 €) : accès complet au jeu de base, pas de pub.
* **DLC thématiques** (1,99 €) : packs visuels “Art nouveau”, “Pixel rétro”, “Street-art”.
* **Cosmétiques gratuits** en récompense d’events (Halloween, Fête de la Musique) pour garder une dynamique F2C (free-to-collect).

### 6. Tech & UX

* **Unity URP** pour gérer le flux d’assets générés.
* **Tiny LLM on-device** (type Phi-3-mini) pour proposer des intros textuelles uniques sans connexion obligatoire.
* **Haptique subtile** quand un fragment valide est attrapé → ancre les réflexes façon Jungle Speed.
* **Accessibilité** : mode daltonien (icônes de formes distinctes), vitesse réglable.

### 7. Plateformes

Le jeu doit être compatible iOS et Android.
