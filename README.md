<div align="center">

<img src="images/icon.png" width="112" alt="Icône de Compteur Vélo">

# Compteur Vélo

**Le compteur GPS pour le vélo, lisible d'un coup d'œil, les mains sur le guidon.**

[![Dernière version](https://img.shields.io/github/v/release/HugoinTheGit/gps-velo-apk?label=version&style=flat-square&color=0E0F12)](https://github.com/HugoinTheGit/gps-velo-apk/releases/latest)
[![Téléchargements](https://img.shields.io/github/downloads/HugoinTheGit/gps-velo-apk/total?label=t%C3%A9l%C3%A9chargements&style=flat-square&color=565A64)](https://github.com/HugoinTheGit/gps-velo-apk/releases)
![Android](https://img.shields.io/badge/Android-APK-565A64?style=flat-square&logo=android&logoColor=white)

<a href="https://github.com/HugoinTheGit/gps-velo-apk/releases/latest/download/compteur-velo.apk">
  <img src="https://img.shields.io/badge/T%C3%A9l%C3%A9charger-l'APK%20Android-0E0F12?style=for-the-badge&logo=android&logoColor=white" height="52" alt="Télécharger l'APK Android">
</a>

<sub>Version <!-- version -->0.1.25<!-- /version --> · gratuit · sans compte · sans publicité</sub>

</div>

<!-- screenshots:start -->
<div align="center"><table><tr><td><img src="images/screen-1-accueil.png" width="200" alt=""></td><td><img src="images/screen-2-widgets.png" width="200" alt=""></td><td><img src="images/screen-3-carte.png" width="200" alt=""></td><td><img src="images/screen-4-recap.png" width="200" alt=""></td></tr></table></div>
<!-- screenshots:end -->

## Ce que fait l'app

- **Enregistrement GPS précis** : vitesse, distance, durée, temps en mouvement, moyenne, vitesse max et dénivelé, avec un filtrage du bruit GPS.
- **Altitude réelle** au-dessus du niveau de la mer, corrigée par le modèle de géoïde EGM96.
- **Accueil en tuiles personnalisable** : appui long pour déplacer et redimensionner les tuiles, et ajouter des widgets (distance, graphique, records, objectif du mois, dernière sortie, heure).
- **Carte vélo CyclOSM** avec recherche de lieu, en thème clair ou sombre.
- **Historique et statistiques** par semaine, mois, année ou au total, avec les records.
- **Export GPX** de chaque sortie, ou de toutes, dans le dossier Téléchargements.
- **Mises à jour intégrées** : l'app propose elle-même chaque nouvelle version.

## Nouveautés de la version <!-- version -->0.1.25<!-- /version -->

<!-- notes:start -->
- Modification des écrans : le widget se prend après 0,5 s d'appui, comme l'appui long qui lance l'édition (retour vibration et widget soulevé).
- À l'accueil, la grille ne se rétrécit plus en passant en mode modification.
- Poubelle façon Android : une ombre avec une icône de corbeille apparaît en bas ; on y glisse un widget (sous la grille) pour le retirer. Même geste pour supprimer une page dans la vue des pages (plus de bouton).
- Deux widgets de même taille s'échangent quand on glisse l'un sur l'autre (à moitié ou plus) : le widget visé est surligné avec une icône d'échange.
- Écran d'enregistrement : nouvelle grille de 3 colonnes × 8 rangées. Tes pages existantes sont converties automatiquement ; les dispositions prédéfinies sont refaites pour cette grille.
- Lampe torche et klaxon : plusieurs par page, mais un seul de chaque mode (statique, clignotant) ou de chaque son par page ; le bouton de réglage change le mode ou le son.
- Klaxon : le son passe par le haut-parleur du téléphone même quand une musique joue dans les écouteurs (le volume suit désormais celui des sons du système).
- Pente : calculée par régression sur environ 250 m d'altitude filtrée et lissée ; elle affiche 0 % sur le plat au lieu de sauts à ±5 %.
<!-- notes:end -->

## Installation

1. Sur ton téléphone Android, touche **Télécharger l'APK** ci-dessus.
2. Ouvre le fichier téléchargé. Si Android le demande, autorise l'installation depuis ton navigateur ou ton gestionnaire de fichiers.
3. Lance **Compteur Vélo** et autorise la localisation pour enregistrer tes sorties.

Les versions suivantes s'installent depuis l'app : une pop-up te propose chaque nouvelle version.

## Données et confidentialité

- Tes sorties restent sur ton téléphone. Il n'y a ni compte, ni serveur, ni statistiques d'usage.
- L'app accède à Internet uniquement pour afficher la carte (OpenStreetMap / CyclOSM), rechercher un lieu (Photon) et vérifier les mises à jour (GitHub).

## Crédits

Carte © contributeurs [OpenStreetMap](https://www.openstreetmap.org/copyright), style [CyclOSM](https://www.cyclosm.org) · Recherche [Photon](https://photon.komoot.io) par komoot · Géoïde EGM96 (NGA) · Polices Big Shoulders Display et Barlow (SIL Open Font License).

<sub>Toutes les versions sont dans [Releases](https://github.com/HugoinTheGit/gps-velo-apk/releases). Le code source de l'app est privé.</sub>
