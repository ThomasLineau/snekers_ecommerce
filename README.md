<a name="readme-top"></a>

<br />
<div align="center">
  <h3 align="center">Wix Automation Tools</h3>
  <p align="center">
    Automatiser l'importation et la gestion des produits dans Wix à partir de l'API des sneakers
    <br />
    <a href="https://github.com/your_username/repo_name"><strong>Explorer la documentation »</strong></a>
    <br />
    <br />
  </p>
</div>

## À propos du projet

Ce repository propose une série de scripts conçus pour automatiser et simplifier la gestion des produits dans Wix, en utilisant des données récupérées depuis des APIs externes. Les scripts incluent des validations, un nettoyage de données et des optimisations pour s'assurer que seuls des produits de haute qualité sont importés dans votre boutique Wix.

### Fonctionnalités principales

- **Récupération des produits depuis une API externe :** Collectez des données produit en masse grâce à une pagination efficace.
- **Validation avancée :** 
  - Vérifie la disponibilité et la validité des images.
  - Supprime les produits sans prix ou image.
  - Gère automatiquement les doublons.
- **Exportation prête à Wix :** Les données traitées sont exportées dans un fichier CSV compatible Wix pour un import rapide.
- **Journalisation détaillée :** Un fichier log est généré pour suivre les produits rejetés et les raisons associées.

<p align="right">(<a href="#readme-top">retour en haut</a>)</p>

## Fichiers inclus

### Importation et traitement des produits
- **`fetch_and_process_products.py`**  
  Importe les produits d'une API, les valide, et génère un fichier CSV prêt à être téléversé sur Wix.

### Nettoyage des produits
- **Suppression des produits sans prix :** Identifie et supprime tous les produits sans prix valide.
- **Suppression des produits sans image :** Filtre les produits sans image associée pour améliorer la qualité visuelle.
- **Suppression des doublons :** Élimine les produits avec des SKU en double ou des noms identiques.

<p align="right">(<a href="#readme-top">retour en haut</a>)</p>

## Démarrage

Suivez ces étapes pour exécuter le projet sur votre machine locale.

### Prérequis

- **Python 3.8 ou plus récent** : Assurez-vous que Python est installé sur votre système.
- Installez les bibliothèques nécessaires :
  ```sh
  pip install pandas requests
