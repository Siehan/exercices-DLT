## Exercices Distributed Ledger Technology


Un arbre de merkle nécessite une paire de hashes pour produire un nouveau hash parent.
Il faut donc absolument que le nombre de transactions qui produiront le Merkle root soit pair.
Comment est géré le cas où le nombre de transactions dans le Block à valider est impair pour générer un Merlke root ?

* Dans le cas où le nombre d'empreintes à combiner est impair, on combine la dernière empreinte avec elle-même.

-----------------

Dans le réseau bitcoin, comment un nouveau noeud arrive-t-il à retrouver ses pairs et ainsi rejoindre le réseau ?
Expliquer le processus avec vos propres mots.

* Au lieu de compter sur une partie tierce pour négocier des échanges, les nœuds membres d’un réseau blockchain (les mineurs) utilisent un protocole de consensus, intégrant haches cryptographiques et signatures numériques pour assurer l’intégrité et l’authenticité des transactions.

-----------------

Pouvez-vous nommer au moins une personne qui a ou aurait pu influencer directement ou indirectement la création de Bitcoin par ses travaux (une personne qui n'a pas été nommée dans le cours)?

* Hal Finney est une personnalité extrêmement importante de l'histoire du Bitcoin.
Il fut l'un des premiers mineurs de la blockchain Bitcoin, en minant l'un des 70 premiers blocs.
* Il est également connu pour avoir été le premier destinataire d'une transaction Bitcoin, d'un montant de 10 BTC envoyé par Satoshi Nakatomo en personne.
Suite à cela, Hal Finney et Satoshi entretiendront des conversations par email, dans lesquelles Hal signalait des bugs qu'il trouvait sur Bitcoin et Satoshi les corrigeait.
* Dans l'éternelle quête sur l'identité de Satoshi Nakamoto, Hal Finney était pour certains un candidat de choix.
Suite à sa disparition (décès), le mystère reste entier. Cependant, Satoshi ou pas, Hal Finney restera l'une des figures paternelles du Bitcoin.
Plus que cela, il restera un cryptographe de renom dont les travaux n'ont cessé d'inspirer les jeunes générations d'informaticiens qui lui ont succédé.

-----------------

Avec vos propres recherches et grâce aux compétences acquises en cours pouvez-vous expliquer comment une Blockchain crée un lien entre ses différents Blocs?

* La blockchain, ou chaîne de blocs, désigne originellement la structure de données utilisée par Bitcoin pour lister l'ensemble des transactions réalisées par ses utilisateurs depuis son commencement : les transactions sont regroupées dans des blocs chaînés entre eux, et des blocs sont rajoutés à la chaîne au cours du temps. Ce registre est partagé entre les membres d'un réseau, d'où le fait qu'on parle parfois de registre distribué.
* Depuis 2015, la blockchain désigne également la technologie de consensus décentralisé remise au goût du jour par Bitcoin.
Cette technologie désigne donc l'ensemble des méthodes permettant aux participants d'un réseau distribué de se mettre d'accord sans recourir à un tiers de confiance.

-----------------

Quelle structure de données informatiques peut représenter le mieux cette chaine de Blocs: (https://en.wikipedia.org/wiki/List_of_data_structures) ?

Un arbre de Merkle, ou arbre de hachage, est un concept mathématique inventé en 1979 par le cryptographe Ralph Merkle.
Il s'agit d'un modèle de structure de données contenant un résumé d'information d'un volume de données, généralement grand.

Les arbres de Merkle se basent sur une fonction de hachage.

-----------------

Si je souhaite modifier une transaction de 10 bitcoin que j'ai effectué il y a 6 mois en une transaction de 1 Bitcoin,
que dois-je modifier dans la Blockchain et que dois-je mettre en oeuvre pour que cette modification persiste ?

Est-ce possible selon vous ? : Non

* Une fois qu'une transaction Bitcoin est effectuée et ajoutée à la blockchain, il est pratiquement impossible de l'inverser ou de la modifier.
* De plus, les annulations ou les remboursements ne sont pas disponibles dans ce système, une fois la transaction effectuée.
Ce qui génère un grand avantage dans divers domaines de l'économie et de la finance.