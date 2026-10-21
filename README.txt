KOKORO — Application web mobile installable

CONTENU
- Journal quotidien sur un parcours de 120 jours
- Quatre étapes de 30 jours
- Sauvegarde locale dans le navigateur via localStorage
- Export JSON des notes et possibilité de les effacer
- Thème sombre/clair
- Manifest et service worker pour installation PWA

TEST LOCAL
Ouvrir index.html dans un navigateur moderne. La plupart des fonctions marchent sans serveur. Pour tester l'installation PWA et le mode hors ligne, héberger le dossier sur un site HTTPS (ou lancer un serveur local).

INSTALLATION SUR SMARTPHONE
1. Déployer tous les fichiers sur un hébergement HTTPS.
2. Ouvrir l'adresse sur le smartphone.
3. iPhone : Safari > Partager > Sur l’écran d’accueil.
4. Android : Chrome > menu ⋮ > Installer l’application / Ajouter à l’écran d’accueil.

À SAVOIR
Cette version est un prototype fonctionnel, pas une application publiée sur l'App Store ou Google Play. Les notes sont enregistrées dans le navigateur de cet appareil : elles ne sont pas synchronisées et peuvent être perdues si les données du navigateur sont effacées. L'interface utilise Google Fonts en ligne ; pour une version entièrement hors ligne, remplacer les polices web par des polices système ou les héberger localement. Le mode hors ligne nécessite un hébergement HTTPS.
