# Cap Brevet — PWA individuelle, locale et hors ligne

Application de révision conçue pour **un seul élève sur son téléphone**. Aucun compte ni serveur applicatif ne sont nécessaires.

## Fonctionnalités
- Fiches de révision, QCM corrigés avec explications et flashcards dans les matières principales
- Contenus élargis en français, mathématiques, histoire-géographie, EMC, sciences (physique-chimie, SVT, technologie), anglais et oral du brevet
- Repères historiques, méthodes de rédaction et de résolution, formules, notions scientifiques et entraînement linguistique
- Progression globale et par matière
- Planning personnalisé sur 7 jours selon la date du brevet, le temps quotidien et les matières à renforcer
- Séances du planning cochables, avec suivi local
- Recherche rapide par matière, notion, fiche, question de QCM ou flashcard
- Mémorisation des questions ratées et mode « Réviser mes erreurs » pour les retravailler
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

## Mise à jour
Remplacez les fichiers du dépôt par ceux de cette version. Le cache du service worker a été versionné pour forcer le rechargement des fichiers modifiés. Les anciennes données locales sont conservées ; les questions ratées continuent d’être suivies.

## Limites
Cette version couvre largement les principaux thèmes et méthodes de 3e, mais ne peut garantir à elle seule l’exhaustivité de chaque progression de classe, œuvre étudiée ou notion choisie par les enseignants. Les programmes et les modalités du DNB évoluent : vérifiez ceux de votre session auprès du ministère et de vos professeurs. Les exercices sont des entraînements originaux, pas des sujets officiels.
