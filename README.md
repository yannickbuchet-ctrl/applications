# Applications

Logiciels gratuits pour Windows 10 et 11 (64 bits), en français. Ils fonctionnent entièrement sur votre ordinateur :
vos photos et vos documents ne sont jamais envoyés sur Internet.

| Application | À quoi elle sert | Version | Installateur | Portable |
|---|---|---|---|---|
| **Calendrier Photo** | Créer un calendrier avec vos photos, prêt à imprimer | 1.2 | [Installer](https://github.com/yannickbuchet-ctrl/applications/releases/download/calendrier-photo-v1.2/Calendrier-Photo-Installation-1.2.exe) | [Calendrier Photo.exe](https://github.com/yannickbuchet-ctrl/applications/releases/download/calendrier-photo-v1.2/Calendrier-Photo.exe) |
| **PDF Toolkit 2** | Modifier, assembler, comparer, signer et protéger vos PDF ; lire le texte des scans ; photos d'identité | 1.5 | [Installer](https://github.com/yannickbuchet-ctrl/applications/releases/download/pdf-toolkit-2-v1.5/PDF-Toolkit-2-Installation-1.5.exe) | [PDF Toolkit 2.exe](https://github.com/yannickbuchet-ctrl/applications/releases/download/pdf-toolkit-2-v1.5/PDF-Toolkit-2.exe) |

Toutes les versions sont sur la page [Releases](https://github.com/yannickbuchet-ctrl/applications/releases).

**Sans rien installer**, dans le navigateur, sur ordinateur, tablette ou téléphone (voir plus bas) :
[Calendrier Photo Web](https://yannickbuchet-ctrl.github.io/calendrier-photo-web/),
[PDF Toolkit Web](https://yannickbuchet-ctrl.github.io/pdf-toolkit-web/) et
[Typon](https://yannickbuchet-ctrl.github.io/typon/), pour les fichiers de fabrication de circuits imprimés.

## Quelle version choisir ?

- **Installateur** (recommandé) : il installe l'application pour vous, sans droits d'administrateur, avec un
  raccourci dans le menu Démarrer. Pour la retirer : Paramètres → Applications. C'est la version la moins souvent
  bloquée par les antivirus.
- **Portable** : un seul fichier `.exe` à lancer directement, sans rien installer. Pratique sur une clé USB.

## Au premier lancement

- Windows peut afficher « Windows a protégé votre ordinateur », car les fichiers ne sont pas signés numériquement :
  cliquez sur **Informations complémentaires**, puis sur **Exécuter quand même**.
- Si votre antivirus bloque le fichier (fausse alerte), autorisez-le ou ajoutez-le à ses exclusions.

## Calendrier Photo

Créez un calendrier personnalisé avec vos photos, puis exportez-le en PDF prêt à imprimer.

- **Couverture et 12 mois**, au format A4 ou A3, en portrait ou en paysage.
- **Une à quatre photos par page** : une photo, deux côte à côte, une grande et deux petites, ou une mosaïque.
- **Remplissage automatique** : sélectionnez toutes vos photos d'un coup ; elles sont rangées mois par mois selon
  leur date de prise de vue, chacune dans un cadre adapté (portrait ou paysage).
- **Recadrage** de chaque photo (zoom et position), ou photo entière.
- **Jours fériés** et **vacances scolaires** françaises (zones A, B et C), numéros de semaine, week-ends en couleur,
  choix de la police et des couleurs.
- **Anniversaires et événements**, avec l'âge pour les anniversaires. La liste s'enregistre dans un fichier ouvrable
  avec Excel, pour la reprendre d'une année sur l'autre.
- **Vue d'ensemble** des 13 pages, annuler et rétablir, **sauvegarde automatique** et récupération après une
  fermeture imprévue. Un avertissement s'affiche si une photo est déjà utilisée dans le calendrier.
- **Export PDF** en haute définition (300 dpi) et **impression**.

![Calendrier Photo : réglages, photos des mois et aperçu de la page](captures/calendrier-photo.png)

### Calendrier Photo Web : sans rien installer

**Ouvrir : <https://yannickbuchet-ctrl.github.io/calendrier-photo-web/>**

Le même calendrier, dans le navigateur, sur ordinateur, tablette ou téléphone : mêmes pages, même remplissage
automatique, mêmes fichiers d'anniversaires que la version Windows.

- **Vos photos ne sont jamais envoyées** : elles sont mises en page et le PDF est créé dans votre navigateur. Le
  calendrier en cours est gardé sur votre appareil, et le site fonctionne hors ligne une fois ouvert.
- **Le fichier de projet emporte ses photos** : un calendrier enregistré se rouvre sur n'importe quel appareil.
- Pour essayer sans vos photos : « Essayer avec les photos modèles ».

Code source : [github.com/yannickbuchet-ctrl/calendrier-photo-web](https://github.com/yannickbuchet-ctrl/calendrier-photo-web)
(licence MIT).

## PDF Toolkit 2

Un éditeur de PDF simple et en français.

- **Modifier le texte** d'un PDF directement sur la page, en gardant sa police d'origine quand c'est possible. Si la
  police n'est pas installée sur l'ordinateur, l'application donne tout ce qu'il faut pour la retrouver (nom exact,
  éditeur, licence) et la rechercher sur Internet.
- **Rechercher et remplacer** un mot dans tout le document.
- **Assembler** plusieurs PDF en un seul ; **organiser** les pages : les déplacer, les faire pivoter, les supprimer.
- **Remplir les formulaires** (zones de texte, cases à cocher, listes de choix), **insérer une image ou une
  signature** scannée, dont le fond blanc devient transparent.
- **Protéger par mot de passe** (chiffrement AES 256 bits) et **compresser** pour l'envoi par e-mail.
- **Lire le texte des documents scannés** (reconnaissance de texte, OCR, nouveau en 1.4) : un PDF scanné devient
  cherchable, et son texte se sélectionne et se copie, sans changer d'aspect. Français et anglais, sans connexion.
  Le texte reconnu s'affiche ensuite dans une fenêtre où chercher un mot (nouveau en 1.5).
- **Photos d'iPhone** (HEIC) et WebP acceptées pour les images, signatures et photos d'identité (nouveau en 1.4).
- **Comparer deux PDF** : les différences entre deux versions d'un document s'affichent côte à côte
  ou superposées (ce qui a disparu en rouge, ce qui est nouveau en vert), avec la liste des différences et un rapport
  PDF. Un réglage « Plan technique » compare finement les plans et les circuits imprimés, au centième de millimètre.
- **Photos d'identité** : à partir d'une photo, une planche aux formats officiels (France, Union
  européenne, Royaume-Uni, États-Unis…), qui s'imprime à la taille exacte des photos.
- **Annuler et rétablir** chaque opération, zoom à la Ctrl + molette, impression.

![PDF Toolkit 2 : recherche et remplacement dans un document](captures/pdf-toolkit-2.png)

PDF Toolkit 2 est un logiciel libre sous licence GNU AGPL v3 : son code source est disponible sur
[github.com/yannickbuchet-ctrl/pdf-toolkit-2](https://github.com/yannickbuchet-ctrl/pdf-toolkit-2).

### PDF Toolkit Web : sans rien installer

**Ouvrir : <https://yannickbuchet-ctrl.github.io/pdf-toolkit-web/>**

La même boîte à outils PDF, dans le navigateur (Chrome, Edge, Firefox, Safari), sur ordinateur, tablette ou
téléphone : modifier le texte, annoter, signer, remplir, organiser, fusionner, comparer, protéger, compresser, lire le
texte des scans (OCR), photos d'identité. Les photos d'iPhone (HEIC) sont acceptées.

- **Rien n'est envoyé sur Internet** : le site s'exécute entièrement dans votre navigateur, vos PDF restent sur votre
  appareil. Il fonctionne aussi hors ligne une fois ouvert.
- **Aucun programme à installer** : pratique sur un ordinateur qui n'autorise pas l'installation de logiciels.
- **L'installer comme une application** (facultatif) : avec Chrome ou Edge, cliquez sur l'icône « Installer » à
  droite de la barre d'adresse. PDF Toolkit apparaît alors dans le menu Démarrer et dans « Ouvrir avec » pour les PDF.

Code source : [github.com/yannickbuchet-ctrl/pdf-toolkit-web](https://github.com/yannickbuchet-ctrl/pdf-toolkit-web)
(licence GNU AGPL v3).

## Typon : fichiers de circuits imprimés

**Ouvrir : <https://yannickbuchet-ctrl.github.io/typon/>**

Pour les concepteurs électroniques : une visionneuse et un comparateur de fichiers de fabrication, dans le navigateur.

- **Lit** les Gerber (RS-274D, RS-274X, X2, X3), les perçages Excellon et XNC, les fichiers de job, l'**ODB++** et
  l'**IPC-2581**, en fichiers séparés, en archive ZIP ou TGZ, ou en dossier.
- **Affiche** chaque couche (dessus, dessous, couleurs, opacité), et donne au clic l'ouverture, le net, le composant et
  la broche d'un élément ; mesure les distances.
- **Met en forme l'ODB++ et l'IPC-2581** : couches, composants, nomenclature, nets et perçages en tableaux,
  exportables en CSV pour Excel.
- **Montre la carte en 3D** : plaque découpée à son épaisseur, cuivre, vernis, sérigraphie, trous et boîtiers des
  composants.
- **Vérifie la fabricabilité (DFM)** : largeur des pistes, isolements, courts-circuits, anneaux, perçages, cuivre au
  bord, vernis et sérigraphie, avec des profils de fabricants (JLCPCB, PCBWay, Eurocircuits…) et un rapport PDF.
- **Surligne un net** et mesure la longueur de ses pistes.
- **Met la carte en panneau** (rainures en V ou languettes perforées, bords, mires) et l'exporte en Gerber.
- **Produit une fiche PDF** de description de la carte : vues 2D et 3D, caractéristiques, empilage, perçages,
  composants, nomenclature.
- **Compare deux versions**, même dans des formats différents : superposition (ce qui a disparu en rouge, ce qui est
  apparu en vert), côte à côte ou en alternance, zones de différence listées, composants ajoutés ou retirés, rapport
  PDF.
- **En français ou en anglais**, au choix.
- **Rien n'est envoyé** : tout est calculé dans le navigateur, et le site fonctionne hors ligne.

![Typon : comparaison de deux révisions d'une carte](captures/typon.png)

Code source : [github.com/yannickbuchet-ctrl/typon](https://github.com/yannickbuchet-ctrl/typon) (licence MIT).

## Crédits

Applications écrites par **Claude Code** sous la direction de **Yannick Buchet**.
