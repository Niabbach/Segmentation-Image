# Segmentation-Image

Ce projet contient deux scripts Python pour la segmentation d'image : un utilisant l'algorithme GrabCut et l'autre utilisant l'algorithme de coupe de graphe (Graph Cuts). Ces scripts vous permettent de dessiner un rectangle sur une image, puis d'effectuer la segmentation pour isoler les objets d'intérêt.

# Prérequis

Assurez-vous d'avoir les bibliothèques Python suivantes installées :

    OpenCV
    NumPy
    NetworkX (pour le script Graph Cuts)
    Matplotlib

Vous pouvez installer ces bibliothèques en utilisant la commande suivante :

        pip install opencv-python numpy matplotlib networkx

# Utilisation

    GrabCut : Exécutez le script grabcut_segmentation.ipynb.
    Graph Cuts : Exécutez le script graph_cut_segmentation.ipybn.
    Dessinez un rectangle sur l'image affichée en utilisant le bouton gauche de la souris.
    Appuyez sur la touche espace (Espace) pour effectuer la segmentation de l'image en utilisant le rectangle dessiné.
    Appuyez sur la touche escape (Esc) pour quitter.
    Le résultat segmenté sera affiché à l'aide de Matplotlib.

# Scripts

    grabcut_segmentation.ipynb : Ce script utilise l'algorithme GrabCut pour la segmentation d'image. Il crée une région d'intérêt basée sur le rectangle dessiné par l'utilisateur et applique ensuite GrabCut pour isoler les objets d'intérêt.

    graph_cut_segmentation.ipynb : Ce script utilise l'algorithme de coupe de graphe (Graph Cuts) pour la segmentation d'image. Il crée un graphe basé sur l'image et le rectangle dessiné, puis applique l'algorithme de coupe minimale pour séparer les objets du premier plan et du fond.


# Auteur

Channel NIANGA
