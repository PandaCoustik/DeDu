# DeDu — Desktop Dungeon

Un jeu de bureau développé par **PandaCoustik** : un personnage en papier découpé, des greffes à récupérer et à équiper, des combats de timing et un monde à explorer, directement sur le bureau Windows.

Ce dépôt rassemble les **versions à télécharger**, les informations du jeu et les retours des testeurs. Le code source n’est pas publié pour le moment.

## Télécharger et jouer

**[Télécharger l’Alpha 0.0.1 optimisée](https://github.com/PandaCoustik/DeDu/releases/tag/v0.0.1-alpha-optimise)**

1. Dans la section **Assets** de la release, télécharger `DesktopDungeon-Alpha-0.0.1-optimise.exe`.
2. Placer le fichier dans le dossier de son choix et le lancer.
3. Suivre le tutoriel intégré, à partir du bouton **Se réveiller**.

Le jeu tient dans un seul exécutable : aucun Godot, Python ou environnement de développement à installer. Les archives automatiques « Source code » de GitHub contiennent uniquement la documentation de ce dépôt ; ce ne sont pas les fichiers à télécharger pour jouer.

### Configuration

- Windows x86-64 ; version testée sur Windows 11.
- Pilote graphique compatible OpenGL 3.3.
- Windows PowerShell disponible pour l’intégration au bureau.
- Exécutable non signé : sa reconnaissance par Windows et les antivirus peut varier.

Cette version ne fournit pas de client macOS ou Linux. La compatibilité avec d’autres configurations Windows reste à tester.

## Dans cette alpha

- Personnage composé de greffes et équipements à récupérer et à gérer.
- Combats de timing : appuyer sur la touche affichée au bon moment.
- Carnet avec inventaire, carte, quêtes et bestiaire.
- Exploration, trajets, rencontres, donjons et services dans les lieux visités.
- Sauvegardes locales, réglages et export de diagnostics pour les retours de bugs.

Les interactions se font à la souris. **Espace** permet d’avancer les dialogues sans choix multiple et de confirmer les résultats. Le tutoriel présente les touches de combat au fil de la progression.

## Version optimisée

L’Alpha 0.0.1 optimisée pèse **155,6 Mo**, contre 289,3 Mo pour le premier export, soit **46,2 % de moins**.

Les textures sont compressées à haute qualité, en conservant leurs dimensions et leur transparence. Les scripts, les sons et les données de jeu sont inchangés. La compression comporte une légère perte sur les couleurs ; les comparaisons réalisées n’ont pas montré de dégradation gênante aux tailles examinées.

Il s’agit d’une **préversion de test**. Les contrôles automatisés, le démarrage vierge, la reprise de sauvegarde et plusieurs comparaisons visuelles ont été effectués. Les essais manuels et les tests sur d’autres machines se poursuivent ; cela ne constitue pas une validation exhaustive du jeu.

## Sauvegardes

Les sauvegardes et diagnostics sont créés dans :

```text
%APPDATA%\Desktop Dungeon Alpha
```

La version optimisée utilise le même dossier et le même format que l’Alpha 0.0.1 précédente. Elle reprend donc la partie existante. Pour conserver un point de retour avant des essais, copier ce dossier lorsque le jeu est fermé.

## Signaler un problème

Ouvrir une **[issue](https://github.com/PandaCoustik/DeDu/issues/new/choose)** en précisant la version, les étapes pour reproduire le problème, le résultat attendu et le résultat observé. Une capture du jeu et la configuration Windows peuvent aider.

Dans le jeu, **Options → Diagnostic → Exporter les logs** permet de produire un ZIP à joindre si nécessaire. Aucun diagnostic n’est envoyé automatiquement. Relire les informations avant de les partager sur une issue publique ; ne pas joindre de sauvegarde personnelle par défaut.

Les crédits et informations sur les composants tiers sont accessibles dans les options du jeu. Ce dépôt ne concède pas de licence open source sur le jeu ou ses ressources.
