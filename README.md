# SmallPyramide

Le but est de pouvoir créer un fichier avec une forme (pyramide, cone, ...) sous forme de nuage de points.
![2025-05-22_00h48_48](https://github.com/user-attachments/assets/170dd05f-cfb0-445b-8656-3cb35de295f6)
Cela permet d'ajouter un élément de contrôle dans les fichiers Recap ou autre et de s'assurer que le nuage de points inserer soie toujours à la bonne place dans la maquette.

## Pourquoi
Début 2025, je me suis rendu compte que nous utilisons de plus en plus de nuage de points. Mais il y a eu plusieurs soucis qui m'on pourri la vie lors de leur utilisation.
Un bug sur Revit qui fait que le nuage de points décide de ce déplacer une fois inserer. Et le nuage de points qui n'est plus à sa place.
Si le nuage de point est au coordonnées suisse MN95, Revit ne gère par vraiment bien des coordoonées aussi éloignées
Et pour finir, ont est jamais à l'abris d'une mauvaise manipulation de l'utilisateur ou un fichier mal positionné.

Pour toutes ces raisons, je me suis fait la reflexion de comment pouvoir controler que le nuage de points est bien à la bonne place tout au long du projet.
Il m'est venu a l'idée d'avoir une pyramide sous forme de points dans recap qui nous permet de controler en permanance avec les pyramides de projet. Et j'ai codé un petit programme pour créer un nuage de points.
Je l'ai déjà utilisé dans une 10 aine de nuage de points. Et ca fonctionne assez bien.
Je vous propose gratuitement une version un peu améliorée ci-dessous.

## Capture d'écran

![2025-05-22_00h35_37](https://github.com/user-attachments/assets/f2afa6d8-a950-42fa-88cf-ade1f3cd1341)
Aspect de l'interface
![2025-05-22_00h36_24](https://github.com/user-attachments/assets/30eb7636-9938-4984-8aa0-6c66de723e8f)
Aspect de la pyramide de points dans Recap
![2025-05-22_00h42_20](https://github.com/user-attachments/assets/bc86ff27-7a0b-4d1d-a924-e57fe0588a54)



## Telechargement
Windows: [https://github.com/Darkkrynn/SmallPyramide/archive/refs/tags/Windows.zip](https://github.com/user-attachments/files/20400195/SmallPyramide.2.0.1.zip)

Mac:

Linux: Si cela vous interesse, demandez-moi et je vous prépare l'application

## Code source


## Historique
2.0.1 Correction de bug.
- [x] Supprimer les espaces et ' dans les champs
- [x] Correction du chemin des images

2.0.0  Ajout d'une nouvelle interface et de nouvelle forme. Correction de bug.
- [x] Ajout de diverses formes
- [x] Nouvelle interface
- [x] Création d'icon pour l'application
- [x] Site web (Github)

1.0.0  Que la forme pyramidale
- [x] Pyramide et export fichier XYZ

## Roadmap
Liste des prochaines améliorarions


## Licence et tarif
C'est gratuit.
Toutes aide est la bienvenue
Toutes proposition est aussi la bienvenue
