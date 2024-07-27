# Houd_HDA
All my HDA tools for houdini : 


## Custom box

a simple box tools who align the box with the ground.

<image src="WIkiHoudini/customBox.jpg" width= 500>
  
  ## Breackdown tool
  
  Function to translate each piece of a mesh if their pack, with a bounding box 
  
  <image src="WIkiHoudini/breackDown.jpg" width= 500>
  
  ## File loop 
  
  This is a solaris OBJ context tools to prepare usd file variation,  it take all the file inside a folder, and place it on the center of the world, you can align all the mesh fo a better preview, it give you a perfect input for the next tools : BuildUsd
  
  <image src="WIkiHoudini/fileLoop.jpg" width= 500>
  
  ## BuildUSD
  
  this is a solaris Stage context tool, it take all the mesh inside a input, set all the variation of material and geo, create an asset gallery with vignet, and save in the folder of your choise the usd geo/variation/material and asset
  
   <image src="WIkiHoudini/buildUsd.jpg" width= 500>
  
## usd converter

**Nom de l'outil :** Convertisseur 3D en USD

**Description :**
Le Convertisseur 3D en USD est un outil puissant et intuitif conçu pour simplifier la conversion de fichiers 3D en format USD (Universal Scene Description). En entrant simplement le chemin d'accès du dossier contenant tous vos fichiers 3D, cet outil automatise le processus de conversion en attribuant toutes les géométries, matériaux et textures dans un fichier USD consolidé. Une fois la conversion effectuée, vous pouvez sauvegarder ce fichier USD et l'ajouter facilement à votre bibliothèque d'assets, facilitant ainsi la gestion et l'intégration de vos ressources 3D dans divers projets.

**Fonctionnalités :**
- **Conversion Automatique :** Transformez automatiquement tous les fichiers 3D d'un dossier en un seul fichier USD.
- **Attribution Intelligente :** Gérez les géométries, matériaux et textures de manière cohérente et précise.
- **Sauvegarde Facile :** Enregistrez le fichier USD généré pour une utilisation future.
- **Gestion des Assets :** Intégrez le fichier USD à votre bibliothèque d'assets pour une organisation et une accessibilité optimisées.

**Utilisation :**
1. Entrez le chemin d'accès du dossier contenant vos fichiers 3D.
2. Laissez l'outil attribuer automatiquement toutes les géométries, matériaux et textures.
3. Sauvegardez le fichier USD généré.
4. Ajoutez le fichier USD à votre bibliothèque d'assets pour une utilisation ultérieure.
