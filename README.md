# InterMap Data

Source publique de test compatible avec **InterMap Distribution Protocol v1**.

> TEST / PRERELEASE — NOT AN OFFICIAL TRUSTED DISTRIBUTION

Ce dépôt héberge uniquement les petits fichiers statiques du protocole :

- `intermap-source.json` : point d’entrée de la source ;
- `catalogue-v2.json` : catalogue des communes et liens vers les paquets ;
- `DATA_LICENSE.md` : attribution et licence des données.

Les archives `.intermap.zip` ne sont pas committées dans Git. Elles sont
publiées comme assets d’une prerelease GitHub. GitHub n’est ici qu’un serveur
de fichiers HTTP(S) : l’application InterMap ne consomme ni l’API GitHub ni un
format spécifique à GitHub.

Cette source sert à valider le téléchargement réel de Versailles et du
Chesnay-Rocquencourt. Elle n’est pas signée et son `source_id` n’est pas une
preuve cryptographique de l’identité de son opérateur.

Point d’entrée public :
[`intermap-source.json`](https://raw.githubusercontent.com/Comedqn/InterMap-Data/main/intermap-source.json)

Le code de l’application InterMap n’est pas couvert par la licence des données
décrite dans `DATA_LICENSE.md`.
