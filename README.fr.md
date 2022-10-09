
# FreeStyle Libre 3 patch

Ce texte est traduit automatiquement. Vous devriez lire la version anglaise ou allemande pour les dernières mises à jour.

<a href="README.md"><img alt="EN" src="https://user-images.githubusercontent.com/65506676/190852356-073bf576-6e3a-45f3-a658-be1c4a8d7286.png" width="18px" /> Readme en anglais</a>

Repo public pour piloter le développement de Libre 3. Ce repo doit être utilisé pour échanger des informations sur Libre 3. Les objectifs possibles sont le décryptage et la création d'une interface pour Xdrip.

## Avis de non-responsabilité

L'utilisation des informations et des applications de github.com est à vos risques et périls et sans garantie ou support formel d'aucune sorte. Ce projet n'a aucune association avec et n'est pas approuvé par Abbott.

## Solution Juggluco

Un grand merci à [jkaltes](http://jkaltes.byethost16.com/) pour tout le travail. Avec le [nouveau patch FSTL3](http://jkaltes.byethost16.com/Juggluco/libre3/), il y a enfin une solution hors ligne qui ne nécessite pas d'accès root et qui est entièrement intégrée à Xdrip. Vous pouvez trouver les instructions ici : [Instructions pour le patch Libre3 avec Juggluco](./Juggluco-solution/instructions/fr/instructions.md). Ou vous pouvez utiliser le [lien de téléchargement](./Juggluco-solution/versions/latest/Libre-3-patch.apk?raw=1).Veuillez noter : Cette solution est à vos propres risques et sans garantie ou support formel d'aucune sorte. Ce projet n'a aucune association avec Abbott et n'est pas approuvé par ce dernier.

Veuillez noter : Je n'ai pas été impliqué dans le développement de Juggluco et du patch final pour Libre 3, mais j'aime partager tout le travail de développement qui est en cours.

## Autres solutions pour le FSL 3 (nécessitant un root ou une connexion en ligne)

- Libre 3 : Une solution hors ligne -> nécessite un root et quelques connaissances, ne supporte également que les applications Libre 3 jusqu'à la version 3.3.1. [Lien (allemand)](https://insulinclub.de/index.php?thread/33795-free-three-ein-xposed-lsposed-modul-f%C3%BCr-libre-3-aktueller-wert-am-sperrbildschir/)
    ->Téléchargement le plus récent : [Lien](https://mega.nz/file/H51h3ILS#65mfhvDvPbtnbdWSOeXHHNxABDD60nP7iODxaDN_QPk)
- Librelink à Nightscout sideloading : [Github repo](https://github.com/timoschlueter/nightscout-librelink-up)
- Application (LLU Client) pour télécharger les données Linkup et les partager avec Xdrip (source : Libre 2) : [Link (allemand)](https://insulinclub.de/index.php?thread/33987-llu-client/&postID=654144#post654144)
- LinkUpConnect](https://github.com/cmtjk/LinkUpConnect) : une alternative à LLU Client qui est capable d'afficher les BG comme notifications avec Xdrip+.
- Web Follower](https://xdrip.readthedocs.io/en/latest/install/webfollower/) : fonctionnalité dans la version Nightly de Xdrip+ (la calibration n'est pas possible).
- En développement pour iOS : DiaBLE -> essaie de tirer parti des capacités de la FSTL3. [Github repo](https://github.com/gui-dos/DiaBLE)

## État actuel

Le décryptage vient d'être cassé :smiley :. Il y a enfin une solution pour les téléphones non rootés, fonctionnant avec Android et Xdrip.

## Comment contribuer

Si vous avez des informations utiles sur Libre 3, partagez-les dans l'onglet [discussions] (https://github.com/maheini/FreeStyle-Libre-3-patch/discussions).

## Infos sur le cryptage

Les éléments suivants sont connus de l'application Libre 3 : Après le démarrage, l'application est vérifiée s'il y a des modifications. La protection de code WhiteCryption y est utilisée.

### #WeAreNotWaiting