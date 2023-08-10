---
utilisation - SCP: Containment Breach - Créateur de cartes Version 2.1'
description: >-
  Manuel d'utilisation - SCP: Containment Breach - Créateur de cartes Version
  2.1
---

# 🇫🇷 Français

## Démarrage

Après avoir démarré le créateur de cartes, vous pouvez soit en créer une entièrement, soit en charger une qui existe déjà et la modifier à votre guise.

Si vous ouvrez le créateur de cartes pour la première fois, vous aurez certainement besoin de sélectionner par vous-même le répertoire des cartes. Cependant, le chemin sera enregistré pour les futures utilisations.

Si vous enregistrez une carte, soyez sûr qu'elle se trouve bien dans le répertoire des cartes (`Map Creator/Maps`). Cette action est très importante, car le jeu cherche les cartes qu'il peut charger dans ce répertoire.

## Comment construire une carte

Avant de créer une carte, il est très important que vous connaissiez les bases de la création de carte pour SCP - Containment Breach.

À gauche, il y a une liste des salles que vous pouvez placer sur la grille. Une courte description -en anglais- de la salle sélectionnée apparaîtra sous cette liste, ainsi qu'une boîte de sélections qui permet de choisir les évènements de la salle (si elle en possède).

Une courte description de l'évènement -également en anglais- apparaîtra sous cette boîte de sélections. La probabilité que l'évènement se produise dans la salle peut être modifiée avec la glissière située sous la description de l'évènement.

* Plus le pourcentage est haut, plus l'évènement aura de chances de se produire. `100%` est la valeur par défaut, l'évènement se produira ainsi à coup sûr.
* Si vous ne souhaitez pas qu'un évènement se produise dans la salle, vous pouvez sélectionner **\[aucun]** dans la boîte de sélections.

Sous la probabilité de l'évènement, il y a une autre boîte de texte montrant les infos de la salle sélectionnée.

La grille à droite sert à placer les salles sur la carte. Les salles peuvent être placées en en sélectionnant simplement une dans la liste de gauche. Vous pouvez cliquer sur une salle déjà placée pour la sélectionner. Vous pouvez alors la tourner en maintenant le clic gauche. La rotation est visible dans le coin inférieur gauche, dans les infos de la salle.

### Note

* En sélectionnant une salle sur la carte, vous désélectionnez la salle dans la liste. Vous devez alors double-cliquer dessus pour la re-sélectionner dans la liste. Si un plus apparaît en survolant la grille de la souris, alors vous pouvez placer votre salle.
* La salle "start" (chambre de confinement de SCP-173 après l'introduction) a toujours une rotation de 180° et ne peut être tournée. La raison, est que le jeu a besoin que cette salle soit orientée de cette façon pour que les scripts s'éxecutent correctement.
* Les salles checkpoints (passages entre les zones) ont une rotation par défaut de 180° pour qu'elles soient orientées correctement. Vous pouvez cependant, elles peuvent être tournées, contrairement à la salle "start".
* La salle "start" (chambre de SCP-173) et l'évènement "alarm" sont nécessaires au bon fonctionnement du jeu.
* L'option "**Sélectionner un évènement par défaut pour les salles**" détermine si une salle doit avoir un évènement assigné automatiquement lorsqu'elle est placée sur la grille (la plupart du temps, le premier évènement de la boîte de sélection est choisi).
* L'option "Placer les portes adjacentes dans la vue 3D" détermine si les portes entre les salles doivent être affichées dans la visionneuse 3D ou non. Cette option est utile pour déterminer dans quelle zone se situe une salle.
* Les "**Options de la carte**" vous permettent de modifier la taille des zones. Cliquez sur "**Appliquer**" afin d'appliquer les changements et sur "Réinitialiser" pour revenir aux paramètres par défaut.
* Vous pouvez modifier le nom de l'auteur et la description de la carte en cliquant sur "**Modifier l'auteur et la description**". Cette option se sauvegarde automatiquement quand vous fermez la fenêtre.
* Il y a trois types de grilles sur lesquelles vous pouvez placer des salles : le site, la forêt et les tunnels de maintenance. Le site est la grille par défaut où vous pouvez placer vos salles et régler leurs évènements. La grille forêt est réservée à SCP-860-1.
  * Notez que pour utiliser la forêt, vous devez placer la salle "room860" et régler la probabilité de son évènement à `100%`. Idem pour les tunnels de maintenance avec la salle "room2tunnel" et son évènement.
  * Notez également que quand vous changez de grille, la liste des salles change aussi. Les grilles de SCP-860-1 et des tunnels de maintenance peuvent aussi être visitées avec la visionneuse 3D.

Vous pouvez supprimer une salle avec un clic droit sur son icône sur la grille. En maintenant le clic droit et en balayant la grille de la souris, vous pouvez supprimer plusieurs salles à la fois.

Cliquer sur la molette de la souris désélectionne la carte actuellement sélectionnée.

De plus, vous pouvez chercher une salle en tapant son nom dans la barre de recherche au-dessus de la liste des salles. Vous pouvez effacer le contenu de la barre en cliquant sur le bouton "**X**" à côté.

**Important :** Quand vous sauvegardez une carte, vous pouvez choisir de l'enregistrer sous les formats "`cbmap`" ou "`cbmap2`". Le format "`cbmap`" est obsolète (il reste cependant compatible) et "`cbmap2`" est la nouvelle version, permettant de sauvegarder le nom de l'auteur, la description, la taille des zones, ainsi que la forêt et les tunnels de maintenance.

## Options de la visionneuse 3D

Cette version du créateur de cartes possède une visionneuse 3D. Vous pouvez y accéder en cliquant simplement sur le bouton "**3D / Visionneuse**" au-dessus de la liste des salles juste à côté du bouton "**2D / Éditeur**". Le bouton "**2D / Éditeur**" vous permet ainsi de retourner sur la grille d'édition de la carte.

Les options de la visionneuse 3D sont situées dans "**Options** -> **Modifier la caméra**" :

* **Couleur du brouillard** : Cette option change la couleur du fond de la visionneuse 3D. La couleur par défaut est le noir (R=0, G=0, B=0).
* **Couleur du curseur** : Change la couleur du curseur visible en mode libre de la visionneuse 3D. La couleur par défaut est le rouge (R=255, G=0, B=0).
* **Distance de rendu** : Détermine la distance à laquelle une salle sera visible dans la visionneuse 3D. La valeur par défaut est `50`. Notez que plus cette valeur est haut, plus il y aura de salles visibles à la fois. Une valeur trop élevée pourrait causer des problèmes de performance.
* **Sync. verticale** : Détermine si la fréquence de rendu devrait être synchronisée avec celle de votre écran.
* **Afficher IPS** : Détermine si la fréquence d'images doit être affichée en mode libre.

## Contrôles de la visionneuse 3D

Lorsque vous sélectionnez une salle, puis que vous passez en vue 3D, la caméra apparaîtra dans la salle en question. Si vous ne souhaitez pas que ça arrive, désélectionnez toutes les salles avant de passer en vue 3D

Vous pouvez activer le mode libre avec un clic droit une fois en vue 3D. Utilisez les touches Z/Q/S/D pour les claviers AZERTY et W/A/S/D pour les claviers QWERTY pour déplacer la caméra. Les salles peuvent être mises en surbrillance en les visant avec le curseur en mode libre. De plus, vous pouvez voir le nom, les coordonnées X et Z, ainsi que l'évènement assigné à la salle visée et sa probabilité.

Vous pouvez sélectionner une salle dans la visionneuse 3D en mode libre, avec un clic gauche, la salle sera également sélectionnée dans la grille 2D, permettant de facilement modifier une salle sur la grille si nécessaire.
