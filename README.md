# InterMap Data

Source officielle bêta compatible avec **InterMap Distribution Protocol v1**.

Ce dépôt héberge uniquement les petits fichiers statiques du protocole :

- `intermap-source.json` : point d’entrée de la source ;
- `catalogue-v2.json` : catalogue des communes et liens vers les paquets ;
- `DATA_LICENSE.md` : attribution et licence des données.

Les archives `.intermap.zip` ne sont pas committées dans Git. Elles sont
publiées comme assets d’une version GitHub. GitHub n’est ici qu’un serveur
de fichiers HTTP(S) : l’application InterMap ne consomme ni l’API GitHub ni un
format spécifique à GitHub.

Le catalogue distribue actuellement Buc, Versailles et Le
Chesnay-Rocquencourt. Le descripteur et le catalogue sont signés avec deux
rôles Ed25519 distincts ; chaque archive est ensuite contrôlée par sa taille et
son empreinte SHA-256 authentifiées par le catalogue.

Point d’entrée public :
[`intermap-source.json`](https://raw.githubusercontent.com/Comedqn/InterMap-Data/main/intermap-source.json)

Le code de l’application InterMap n’est pas couvert par la licence des données
décrite dans `DATA_LICENSE.md`.
