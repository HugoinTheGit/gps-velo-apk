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

<sub>Version <!-- version -->0.1.31<!-- /version --> · gratuit · sans compte · sans publicité</sub>

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

## Nouveautés de la version <!-- version -->0.1.31<!-- /version -->

<!-- notes:start -->
- Nouveau widget « Compteur » pour l'accueil (dans Ajouter un widget) : un second bouton Démarrer qui ouvre un compteur de vitesse, distance et durée, actif dès l'ouverture, sans rien enregistrer. Quand tu quittes la page, les chiffres sont gardés 1 minute (tu peux revenir sans rien perdre), puis tout est remis à zéro. Les widgets du compteur ne se déplacent pas mais leur apparence se règle par un appui long. Pas disponible pendant une sortie enregistrée.
- Widget Musique refait : petits formats sans texte (pochette plein widget avec un gros bouton lecture, ou pochette carrée et bouton lecture sur les bandes), grands formats avec titre et artiste et des boutons beaucoup plus gros, à l'échelle du widget.
- Fin de trajet : « Enregistrer » ou « Supprimer » (avec confirmation) à la place de « Fermer ». Si tu quittes sans choisir, la sortie est enregistrée quand même.
- Le bouton Reprendre clignote doucement sur l'accueil quand une sortie est en cours.
- Graphique de vitesse : plus de pic faux au départ (GPS pas encore stable), la courbe ne dépasse jamais ta vitesse max réelle.
- Profil d'altitude : la pente locale en % s'affiche à côté des mètres quand tu glisses le doigt.
- Mes dispositions : les aperçus de pages reprennent la vraie couleur de chaque widget.
- Sonnette et klaxon : sortie forcée sur le haut-parleur du téléphone, même avec des écouteurs (si le problème persiste sur ton téléphone, dis-le moi).
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
