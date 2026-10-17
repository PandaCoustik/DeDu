# DeDu — Desktop Dungeon

Un jeu de bureau développé par **PandaCoustik** : un personnage en papier découpé, des greffes à récupérer et à équiper, des combats de timing et un monde à explorer, directement sur le bureau Windows.

Ce dépôt rassemble les **versions à télécharger**, les informations du jeu et les retours des testeurs. Le code source n’est pas publié pour le moment.

## Télécharger et jouer

**[Télécharger l’Alpha 0.0.2 optimisée](https://github.com/PandaCoustik/DeDu/releases/tag/v0.0.2-alpha-optimise)**

1. Dans la section **Assets** de la release, télécharger `DesktopDungeon-Alpha-0.0.2-optimise.exe`.
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

L’Alpha 0.0.2 optimisée pèse **155,6 Mo**. Elle conserve la compression haute qualité des textures, leurs dimensions et leur transparence. Cette mise à jour corrige notamment les clics au démarrage, ajoute le récapitulatif des récompenses de quêtes et ajuste les interactions. Voir le [journal des versions](CHANGELOG.md).

Il s’agit d’une **préversion de test**. Le clic Windows au réveil, le démarrage vierge, la reprise d’une sauvegarde 0.0.1 et les contrôles automatisés du paquet ont été vérifiés. Les essais sur d’autres machines se poursuivent.

## Sauvegardes

Les sauvegardes et diagnostics sont créés dans :

```text
%APPDATA%\Desktop Dungeon Alpha
```

La version 0.0.2 conserve le dossier de sauvegardes de l’Alpha 0.0.1. Elle reprend donc la partie existante. Pour conserver un point de retour avant des essais, copier ce dossier lorsque le jeu est fermé.

## Signaler un problème

Ouvrir une **[issue](https://github.com/PandaCoustik/DeDu/issues/new/choose)** en précisant la version, les étapes pour reproduire le problème, le résultat attendu et le résultat observé. Une capture du jeu et la configuration Windows peuvent aider.

Dans le jeu, **Options → Diagnostic → Exporter les logs** permet de produire un ZIP à joindre si nécessaire. Aucun diagnostic n’est envoyé automatiquement. Relire les informations avant de les partager sur une issue publique ; ne pas joindre de sauvegarde personnelle par défaut.

Les crédits et informations sur les composants tiers sont accessibles dans les options du jeu. Ce dépôt ne concède pas de licence open source sur le jeu ou ses ressources.
