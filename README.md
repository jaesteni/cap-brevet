# Cap Brevet — PWA individuelle, locale et hors ligne

Application de révision conçue pour **un seul élève sur son téléphone**. Aucun compte ni serveur applicatif ne sont nécessaires.

## Fonctionnalités
- Fiches de révision, QCM corrigés et flashcards
- Progression globale et par matière
- Checklist de préparation à l’oral
- Progression enregistrée localement dans le navigateur
- Export/import de sauvegarde JSON
- Installation PWA et cache hors ligne après le premier chargement

## Lancer en local
Les fonctions PWA nécessitent HTTPS ou localhost. Depuis ce dossier, lancez `python -m http.server 8000`, puis ouvrez `http://localhost:8000`.

## Installer sur téléphone
Déployez les fichiers sur un hébergement HTTPS. Sur Android, ouvrez l’adresse avec Chrome puis choisissez « Installer l’application » ou « Ajouter à l’écran d’accueil ». Sur iPhone, ouvrez l’adresse dans Safari, puis Partager → Sur l’écran d’accueil.

## Données et confidentialité
Aucun compte n’est créé et la progression n’est pas envoyée à un serveur. Les données restent dans le stockage local du navigateur. Exportez régulièrement une sauvegarde depuis l’écran Progression, surtout avant de changer de téléphone ou de navigateur. L’effacement des données du navigateur peut supprimer la progression.

## Limites
Il s’agit d’une première base pédagogique, pas encore d’une couverture exhaustive de tous les programmes et sujets officiels du DNB. Vérifiez les programmes et modalités de la session concernée auprès des sources officielles.
