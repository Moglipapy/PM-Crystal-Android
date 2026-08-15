# Pokémon Cristal — Port Android portrait

Ce dépôt distribue une version Android de Pokémon Cristal adaptée aux écrans de téléphone.

Le jeu original reste autoritaire pour les combats, les scripts, les événements, les sauvegardes, l’inventaire, l’équipe et la progression. La présentation Android ajoute notamment un affichage vertical, un overworld étendu, des commandes tactiles et un menu QoL natif.

Le launcher permet de choisir la version anglaise ou française. Les profils et sauvegardes restent séparés par langue et sont compatibles avec les précédentes versions de l’application.

La version 23 conserve le launcher **PM CRYSTAL**, la couverture complète des 388 cartes, les sauvegardes d’état sûres et les transitions de combat plein écran déjà validées. Le Multi-EXP mobile se règle directement avec trois grands boutons **OFF / 50 % / 100 %** et s'applique immédiatement à la session, même si Android refuse temporairement l'écriture du fichier QoL. Le menu affiche aussi le résultat du dernier K.O. pour confirmer clairement si les réservistes étaient éligibles et si la distribution a abouti.

À 100 %, les réservistes passent dans la boucle d'EXP originale de Pokémon Cristal : le jeu affiche lui-même le message de gain, anime la barre d'EXP et gère niveaux, capacités et évolutions. La v23 reconnaît correctement la représentation interne des Œufs de Crystal : l'Œuf reste exclu de l'EXP sans faire rejeter toute l'équipe. Des combats réels à deux Pokémon, déclenchés par le même chemin que l'interface mobile et avec une sauvegarde QoL volontairement impossible, valident les gains EN `265 / 265` et FR `274 / 274` ; le test EN/FR inclut désormais aussi un véritable Œuf de Togepi.

## Installation sur Android

1. Téléchargez [`PM-Crystal-Android.apk`](./PM-Crystal-Android.apk). Sur GitHub, ouvrez le fichier puis utilisez **Download raw file**.
2. Ouvrez l’APK depuis l’application **Fichiers** ou depuis la notification de téléchargement.
3. Si Android bloque l’installation, autorisez temporairement **Installer des applications inconnues** pour votre navigateur ou votre gestionnaire de fichiers.
4. Installez directement cette version par-dessus l’ancienne. **Ne désinstallez pas l’application**, afin de conserver ses profils et sauvegardes.
5. Lancez `PM_CRYSTAL`, choisissez **English** ou **Français**, sélectionnez un profil puis vérifiez la ROM correspondante lorsque le launcher le demande.

L’APK cible les appareils Android ARM 64 bits (`arm64-v8a`). Son identifiant, sa signature, son logo et ses chemins de sauvegarde restent ceux de l’application précédente.

> Projet non officiel, sans affiliation avec Nintendo, Game Freak ou The Pokémon Company. Vous devez posséder une ROM compatible issue de votre propre cartouche.
