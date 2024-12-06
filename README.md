<a name="readme-top"></a>

<br />
<div align="center">
  <h3 align="center">Automatisation de l'importation des sneakers dans Wix</h3>
  <p align="center">
    <br />
    <a href="https://github.com/your_username/repo_name"><strong>Explorer la documentation »</strong></a>
    <br />
    <br />
  </p>
</div>

<details>
  <summary>Table des matières</summary>
  <ol>
    <li>
      <a href="#à-propos-du-projet">À propos du projet</a>
      <ul>
        <li><a href="#construit-avec">Construit avec</a></li>
      </ul>
    </li>
    <li>
      <a href="#démarrage">Démarrage</a>
      <ul>
        <li><a href="#prérequis">Prérequis</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
  </ol>
</details>

## À propos du projet

Ce projet simplifie l'importation de produits dans Wix à partir d'une API externe. Le script inclut une validation robuste et un traitement des images, des prix, des SKU en double, etc., pour garantir que seules des données de haute qualité sont importées. Un fichier CSV propre est généré pour un téléversement facile dans Wix.

### Fonctionnalités principales
- Récupération et traitement des produits par lots depuis l'API.
- Validation des images des produits pour garantir leur disponibilité.
- Suppression des produits sans prix ou images valides.
- Élimination des produits avec des SKU en double.
- Génération d'un journal détaillé pour les produits rejetés.

<p align="right">(<a href="#readme-top">retour en haut</a>)</p>

### Construit avec

- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Requests](https://docs.python-requests.org/)

<p align="right">(<a href="#readme-top">retour en haut</a>)</p>

## Démarrage

Suivez les étapes ci-dessous pour configurer et exécuter le script sur votre machine locale.

### Prérequis

Assurez-vous d'avoir Python 3.8+ et les bibliothèques nécessaires installées :
* Installer les bibliothèques requises :
  ```sh
  pip install pandas requests
