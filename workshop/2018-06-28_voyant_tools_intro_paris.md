> Ce document a pour base une version française mise à jour et modifiée d’un bref [tutoriel disponible sur le site Hermeneuti.ca](http://hermeneuti.ca/intro-workshop) et la [documentation anglaise en cours de révision](https://voyant-tools.org/docs/# !/guide/tutorial). Il contient la structure et les matériaux d’un atelier francophone d’introduction à Voyant Tools de trois heures.

![](../images/voyant-see.png)


# Introduction à Voyant Tools

[Voyant Tools](http://voyant-tools.org/) est un environnement de lecture et d’analyse de textes numériques. Cette plateforme fait partie d’un projet plus vaste, présenté dans ce livre : Rockwell Geoffrey et Sinclair Stéfan, *[Hermeneutica](http://hermeneuti.ca/). Computer-Assisted Interpretation in the Humanities*, Cambridge, Massachusetts, MIT Press, 2016.

<img src="../images/hermeneutica_cover.jpg" width="300"/>

---


## Programme de l’atelier ![](../images/voyant-logo_0.png)

1. À propos de Voyant Tools
2. Distances de lecture
3. Tour de l’atelier numérique
4. Explorez vos corpus
5. Et ensuite ?

---


## 0. Préparatifs

1. Je vous recommande vivement d’installer la version serveur de Voyant Tools sur votre machine, en suivant ces consignes : <https://github.com/sgsinclair/VoyantServer/wiki/VoyantServer-Desktop>. Cette version vous permettra de faire fonctionner la plateforme localement, et donc sans besoin d’une connexion Internet, sans partage de données automatique ou subreptice, et surtout plus vite et plus souplement.

Il s’agit simplement de télécharger et décompresser le dossier « VoyantServer2_4-M7.zip » dans le dossier où vous mettez vos applications (prenez la dernière version, quel que soit son numéro), de lancer l’application en double-cliquant sur le fichier « VoyantServer.jar » et d’attendre que votre navigateur s’ouvre à l’adresse locale par défaut, http://127.0.0.1:8888/ (appuyer sur le bouton « Open Web » a le même effet).

2. Si vous souhaitez explorer un corpus qui vous est familier, il vous suffira de disposer d’un ou de plusieurs fichiers dans un format courant (texte brut de préférence, éventuellement HTML ou XML, voire PDF), ou bien de connaître l’URL d’une page où le texte est accessible librement.

Vous pouvez faire des essais avant l’atelier pour vous assurer que votre version locale fonctionne aussi bien que la version en ligne, <http://voyant.tools.huma-num.fr> (miroir de <https://voyant-tools.org>).


## 1. À propos de Voyant Tools

* dates du projet (*Voyeur*)
* visée et esprit
* Voyant Tools et moi
    * Stéfan S., Day of DH 2010 (?) : HN anglophones
    * enseignement : initiation à l’analyse textuelle (pastiches savants, toucher du doigt les limites)
    * traduction française de l’interface, après une discussion sur la liste « [Digital Humanities](https://groupes.renater.fr/sympa/info/dh) »
    * production de *stopwords* pour le grec et le latin
* tension entre outil unique, à tout faire, et l’acquisition d’une culture computationnelle donnant accès à des outils spécialisés (encodage, transformation, analyse textuelle, réseaux, etc.)
    * Voyant Tools résout cette tension par la modularité et l’évolutivité
    * bientôt aussi des *notebooks* (Spyral)
* vers une culture numérique et statistique mieux partagée (analyse et publication des résultats) ?


## 2. Distances de lecture

`Cirrus`

Observez ce [nuage de mots](http://voyant-tools.org/tool/Cirrus/?corpus=frankenstein&toolFlow=contexts).

* Que représente à votre avis ce nuage ?
* Quelles caractéristiques sont issues d’une quantification du texte ? Comment les autres propriétés du nuage sont-elles générées ?
* Quels sont les mots qui manquent ?

Manipulez ce nuage à votre tour. <!-- Ou bien essayez avec ce corpus de [Shakespeare](http://voyant-tools.org/tool/Cirrus/?corpus=shakespeare&stopList=stop.en.taporware.txt&toolFlow=contexts). -->

`Termes`/`Terms`

* tables
* *sparklines*

`Lecteur`/`Reader`

* … et fonctions de requête

`Contextes`/`Contexts`

* … concordance


## 3. Tour de l’atelier numérique

Maintenant, observez cet [environnement de travail complet](http://voyant-tools.org/?corpus=frankenstein&stopList=stop.en.taporware.txt) de Voyant. Il s’agit de l’apparence par défaut. Elle combine un ensemble d’outils, ou modules, qui sont complémentaires et coordonnés. Pour l’utiliser, vous devez comprendre quelques principes de fonctionnement d’une **vue** :

* À chaque **outil** correspond un **panneau**, que vous pouvez réduire ou agrandir.
* Pour chaque panneau, des options sont disponibles.
* Chaque panneau peut être manipulé ou exploré d’une façon qui lui est propre.
* Chaque panneau peut modifier le contenu d’autres panneaux.

Voyant Tools propose actuellement 24 outils en ligne (voir la [documentation](http://voyant-tools.org/docs/#!/guide/tools)). Certains sont traditionnels dans la linguistique de corpus ou la linguistique computationnelle, certains font en ce moment florès dans les humanités numériques, certains sont plus expérimentaux ou artistiques. D’autres outils sont en préparation (par exemple un outil de cartographie lié à une fonction de reconnaissance des entités nommées).

Les fonctions d’export dépendent de l’outil concerné :
* une nouvelle URL
* une image
* une référence bibliographique
* un code pour intégrer le panneau ou la vue à une page HTML (dans un *iframe*)

Il est parfois utile d’ouvrir plusieurs interfaces et de comparer des corpus (par exemple avec ou sans lemmatisation).

Faites des essais dans l’environnement par défaut de Voyant avec un texte unique, puis avec le [corpus de Shakespeare](http://voyant-tools.org/?corpus=shakespeare). Remarquez que des panneaux supplémentaires sont présents lorsque vous travaillez sur une collection de textes.

`Résumé`/`Summary`

`Documents`

`Syntagmes`/`Phrases`

`Tendances`/`Trends`

`Corrélations`/`Correlations`

`Collocations`/`Collocates`

`Liens`/`Links`

`Nuage de points`/`Scatter plot`

`Thèmes`/`Topics`


## 4. Explorez vos corpus

### Charger un corpus (démo)

Vous êtes maintenant prêts à charger vos propres corpus dans Voyant. Utilisez la version locale que vous avez installée sur votre ordinateur, ou bien l’un des serveurs suivants :

* avec une interface dans la langue de votre navigateur : [http://voyant.tools.huma-num.fr](http://voyant.tools.huma-num.fr) ou [https://voyant-tools.org](https://voyant-tools.org/)
* avec l’interface française : [http://voyant.tools.huma-num.fr/?lang=fr](http://voyant.tools.huma-num.fr/?lang=fr) ou [https://voyant-tools.org/?lang=fr](https://voyant-tools.org/?lang=fr)
* avec l’interface anglaise : [http://voyant.tools.huma-num.fr/?lang=en](http://voyant.tools.huma-num.fr/?lang=en) ou [https://voyant-tools.org/?lang=en](https://voyant-tools.org/?lang=en)

Voyant vous permet de charger un texte de plusieurs manières :

* Vous pouvez **copier-coller** du texte.
* Vous pouvez saisir une **URL** que Voyant ira visiter pour récupérer du texte. Par exemple, nous pourrions utiliser Voyant pour observer le contenu du blog de Geoffrey Rockwell, [theoreti.ca](http://theoreti.ca/), ou bien celui de François Bon, [Le Tiers Livre](http://www.tierslivre.net/).
* Vous pouvez **charger** un texte à partir d’un fichier.
* Vous pouvez **ouvrir** l’un des corpus qui sont disponibles par défaut, au moyen du bouton `Ouvrir`.

#### Corpus de démonstration
* français – via URL
    * Lautréamont, [*Les Chants de Maldoror*](http://athena.unige.ch/athena/lautreamont/laut_mal.html) <!-- stopwords, « yeux » et « corps », pas de modification de la tokénisation (« n’est » et « l’homme ») -->
    * Rabelais, [*Pantagruel*](http://athena.unige.ch/athena/rabelais/rabelais_pantagruel.html) <!-- pas de stopwords adaptés, distribution du nom de Pantagruel -->
        * intégration à une page HTML : [exemple 1](https://aurelienberra.org/temp/voyant.html) et [code](https://github.com/aurelberra/aurelienberra/blob/master/static/temp/voyant.html)
        * intégration à une page HTML : [exemple 2](http://voyant-tools.org/docs/#!/guide/search), la page documentant les modes de requête
* allemand – via URL
    * Goethe, [*Faust I*](http://beta.faustedition.net/print/faust1.all)
* latin – via fichiers
    * César, *La Guerre des Gaules*, texte du PHI5 nettoyé <!-- sélectionner liste de stopwords, pas de lemmatisation -->
    * César, *La Guerre des Gaules*, texte lemmatisé <!-- avec le CLTK --> puis un peu nettoyé
    <!-- (erreurs comme « ito » pour « iter », « itaque », « item »… ; rectifié « edo » pour « sum », « reor » pour « res », « bellus » pour « bellum », « neo » pour « ne », « dius » pour « dies », et quelques autres formes ; lemmatisé les entités nommées « Gallia », « Caesar » et « Romani/Romanus ») -->
    <!-- « con » est la trace des choix du lemmatiseur (« con- ») -->
* français + espagnol, médias Web ou réseaux sociaux – via fichiers HTML + via fichiers XML <!-- exclu 4 fichiers XML car erreur de lecture de certains nœuds -->
    * [Digital Humanities Quarterly 12.1](http://www.digitalhumanities.org/dhq/vol/12/1/) : humanités numériques hispanophones et francophones <!-- liste de stopwords « multilingue », édition des listes (enlever par exemple « digital http humanities dhq university ») -->

<!-- Travailler avec des corpus pérennes : l’interaction avec le serveur via l’URL et la durée de conservation des corpus ne sont apparemment pas mentionnées dans la documentation. -->

### Travail en groupes

Formez des groupes. Chaque groupe choisit un corpus et explore quelques outils.

Chaque groupe partage ensuite :
* ses résultats ?
* ses remarques
* ses questions

#### Corpus des participants

* Époques
    * textes hagiographiques médiévaux
    * textes hagiographiques
    * édition critique d’un texte de Christine de Pizan <!-- édition critique / texte brut -->
    * texte didactique de Christine de Pizan
    * textes en ancien et moyen français
    * partition musicale (MS Turin Biblioteca Nazionale T.III.2) <!-- encodage ? -->
    * commentaires humanistes latins sur l’*Art poétique* d’Horace
    * manuscrits du XVIe siècle
    * 200.000 vers de poésie du XVIe siècle (corpus XML, en partie lemmatisé) <!-- lemmatisation -->
    * chroniques missionnaires
    * journaux du XVIIIe siècle <!-- orthographe, OCR -->
    * corpus de textes esthétique allemande deuxième moitié du XIXe siècle
    * Zola, *Les Rougon-Macquart*
    * Maeterlinck
    * ouvrages d’historiographie imprimés
    * romans du XXe siècle 
    * 100 œuvres de littérature de l’imaginaire pour jeunes adultes à succès
    * texte ultra-contemporain de François Bon <!-- le blog de FB comme corpus : http://www.tierslivre.net/ + wget -->
    * corpus de pages Facebook
    * corpus bruts Youtube <!-- commentaires ? -->
    * corpus de flux RSS « print » et « Web » <!-- VT ? -->

* Types
    * corpus philosophique (Leibniz, Hume, Quine, Goodman, Putnam, Searle, Davidson, Kripke, etc.)
    * documents juridiques <!-- VT ? -->
    * nouvelles de médias en ligne et messages de réseaux sociaux numériques <!-- accès libre ? -->
    * corpus d’entretiens

* Langues
    * allemand
    * anglais
    * français (ancien)
    * français (moyen)
    * français (moderne)
    * français (contemporain)
    * latin

* Médias
    * images de manuscrits
    * images d’imprimés
    * textes numériques <!-- VT texto-centrique -->
    * textes et images


## 5. Et ensuite ? ![](../images/voyant-logo_0.png)

Outre la version française, <https://voyant-tools.org/?lang=fr>, des versions dans d’[autres langues](http://voyant-tools.org/docs/#!/guide/languages) sont mises en ligne à mesure que des collègues traduisent l’interface.

[Hermeneutica](http://hermeneuti.ca/) montre de quelle manière on peut intégrer des panneaux de Voyant dans des essais en ligne.

Le manuel de Voyant est disponible à cette adresse : <http://voyant-tools.org/docs/#!/guide/start> (licence CC-BY).

Le code de Voyant Tools est publié en *open source* : <https://github.com/sgsinclair/Voyant> (licence GPL).

La version serveur de Voyant Tools peut être téléchargée sur <https://github.com/sgsinclair/VoyantServer/#voyant-server>. Elle vous permet de faire fonctionner localement la plateforme.

Un tutoriel destiné à server de base pour l’organisation d’ateliers ou de formations est en cours de rédaction : <https://voyant-tools.org/docs/#!/guide/tutorial>.

Vous pouvez contacter les concepteurs : Geoffrey Rockwell (<geoffrey.rockwell@ualberta.ca>) et Stéfan Sinclair (<stefan.sinclair@mcgill.ca>). En ce qui concerne la version francophone, n’hésitez pas à écrire à Aurélien Berra (<aurelien.berra@parisnanterre.fr>).

Voyant a un compte sur Twitter, [@VoyantTools](https://twitter.com/VoyantTools), qui vous fera découvrir les usages que d’autres utilisateurs font de la plateforme.

![fantôme](../images/voyant-logo_0.png)
