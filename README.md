======================================================================
     TUTORIEL COMPLET : DRAGON-NEXUS-ORBIS & GITHUB (FW 14.02)
======================================================================

1. PRESENTATION DU PROJET ET CE QUI A ETE AJOUTE
----------------------------------------------------------------------
Ton hébergeur "Dragon-Nexus-Orbis" regroupe les exploits et payloads PS4 
de manière centralisée, de la version 5.05 jusqu'aux firmwares récents 
comme le firmware 14.02.

Ce qui a été configuré et ajouté :
- Le design visuel "Dragon-Nexus-Orbis" : Thème sombre, cartes de firmwares 
  épurées, logo du dragon et indicateurs dynamiques de navigation.
- Le dossier et les scripts de la version 14.02 :
  * index.html & jb.html : Pages d'entrée pour déclencher l'exploit 
    WebKit et charger l'environnement.
  * Moteurs Afterglow (afterglow.js, launch.js, jb.js, core.js, mem.js, 
    int64.js, ps4_offsets.js, rpc_worker.js) : Briques logicielles 
    permettant l'allocation mémoire et le contournement des sécurités 
    du navigateur de la PS4.
  * Fichiers binaires : patchset-14.02.bin et goldhen.bin pour l'injection 
    des charges utiles (payloads) et le lancement des homebrews.


2. COMMENT ACCEDER A VOTRE HEBERGEUR EN LIGNE
----------------------------------------------------------------------
Une fois configuré sur GitHub Pages, ton site est accessible 
publiquement à l'adresse officielle suivante :
-> https://wolf-mika.github.io/ps4/

Il te suffit de taper cette URL directement dans le navigateur 
internet de ta console PS4 pour charger ton hébergeur.


3. GUIDE : METTRE A JOUR LE PROJET SUR GITHUB (VIA GITHUB DESKTOP)
----------------------------------------------------------------------
Chaque fois que tu modifies, ajoutes ou améliores des fichiers dans 
ton dossier local (sur ton PC / XAMPP), tu dois synchroniser tes 
changements pour mettre à jour le site web en ligne :

Étape 1 : Ouvrir GitHub Desktop
- Lance l'application et vérifie que ton dépôt "ps4" est bien sélectionné 
  en haut à gauche.
- Clique sur l'onglet "Changes" sur le panneau de gauche pour voir la 
  liste de tes fichiers modifiés.

Étape 2 : Valider les changements (Commit)
- En bas à gauche de la fenêtre, dans la zone "Summary", écris un 
  court message décrivant ton ajout (ex: "Mise à jour patchset 14.02").
- Clique sur le bouton bleu "Commit to main".

Étape 3 : Envoyer en ligne (Push)
- Tout en haut à droite de l'application, clique sur le bouton 
  "Push origin" (ou sur la flèche de synchronisation).
- Attends que la barre de progression se termine.

Étape 4 : Actualiser le site web
- Attends environ 30 secondes (le temps que GitHub Pages reconstruise 
  la page).
- Rends-toi sur ton lien https://wolf-mika.github.io/ps4/ et fais un 
  rafraîchissement forcé (Ctrl + F5 sur PC ou recharge la page sur ta PS4).
  Les modifications s'afficheront instantanément.
======================================================================
