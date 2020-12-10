
# Projet de l'UE HMIN339M
## Structure du Code

Dans ce dossier nous avons les fichiers de code suivants:
```
0_construction_données_rgb.ipynb
1_processing_data.ipynb
2_first_classifications.ipynb
```
- le premier fichier, le `0_construction_données_rgb.ipynb` nous avons le code qui manipule les images tiff afin de lire et pickleiser les bandes composantes (RGB + NIR).
- le `1_processing_data.ipynb` nous avons le code qui lis en entree ces bandes composantes et à partir de cela, crée des jeu de données train:test de proportions differents.
- le `2_first_classifications.ipynb` effectue les premiers analyses du projet afin d'avoir une idée de la performence des modeles 'classiques' de machine learning (c'est à dire les modeles qui ne sont pas les reseaux de neurons).
