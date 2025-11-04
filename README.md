# BOITE À OUTILS

>*NB : Ce document est la version publique de la boite à outils mise à disposition sur l'intranet du Centre Émile Durkheim. Certains liens et adresses mail ont donc été expurgés pour des raisons de confidentialité.  
La mise à disposition de ce document sur un dépôt public a pour but de faciliter la mise à jour et la diffusion de ces informations à des publics similaires.  
(Et de faciliter l'accès pour les membres du laboratoire qui ont la flemme de se connecter – on vous voit).*

L'objectif n'est pas ici de présenter une liste exhaustive mais plutôt d'orienter vers les principaux outils (et de préciser le cas échéant leur disponibilité au sein du laboratoire).
La [liste](https://digithum.huma-num.fr/ressources/boiteaoutils/) composée par Digit_Hum est toute indiquée pour celles et ceux souhaitant accéder à des ressources complémentaires.
De même, on ne peut que conseiller de jeter un oeil aux outils listés et/ou proposés par le [Medialab](https://medialab.sciencespo.fr/en/tools/).

## Le bureau virtuel

Le bureau virtuel (BV) donne gratuitement accès en ligne à certains outils payants via des machines virtuelles déployées par la DSI de Sciences Po.  
Pour y accéder, contactez Marie-Ange Resano avec la fiche d'information complétée.

## Retranscription automatique

L'une des solutions les plus populaires est [Whisper](https://github.com/openai/whisper) (développée par openAI). Un accès est possible par la plateforme [ShareDocs](https://documentation.huma-num.fr/sharedocs-stockage/) d'[Huma-Num](https://www.huma-num.fr/). La procédure est explicitée dans ce [billet](https://agepouvoir.hypotheses.org/494) et Léo Mignot est disponible pour accompagner à l'usage.  
Si vous souhaitez plutôt faire tourner le tout sur votre machine, [noScribe](https://github.com/kaixxx/noScribe) a de bons retours.  
Pour davantage d'informations, voir également le [billet](https://www.css.cnrs.fr/fr/whisper-pour-retranscrire-des-entretiens2/) du CSS de l'Institut Polytechnique de Paris.

## Analyse de données qualitatives / entretiens

### Logiciels (dont gratuits/libres)

- [Resources for Comparing QDA Tools](https://guides.nyu.edu/QDA/comparison) des NYU Libraries : comparaison des logiciels disponibles, et notamment les [outils gratuits](https://guides.nyu.edu/QDA/FLOSSQDA).
- [Comparison of CAQDAS software](https://en.wikipedia.org/wiki/Computer-assisted_qualitative_data_analysis_software#Free_.2F_open_source_software_for_CAQDAS) : un listing équivalent du côté de Wikipedia.
- Dans les solutions open sources et gratuites, [QualCoder](https://qualcoder.wordpress.com/) et [Taguette](https://www.taguette.org/fr/) reviennent assez régulièrement et sont recommandables, de même que LibreQDA[https://aide.libreqda.org/].

### Principaux logiciels commerciaux

- [Atlas.ti](https://atlasti.com/fr) (disponible sur le bureau virtuel).
- [MaxQDA](https://www.maxqda.com/fr).
- [Nvivo](https://lumivero.com/products/nvivo/) (précédemment disponible sur le bureau virtuel mais en cours de reconfiguration).

## Analyse de données quantitatives

### Code et programmation

- [Python](https://www.python.org/) (souvent associé à [Anaconda](https://www.anaconda.com/) ou [Miniconda](https://docs.conda.io/projects/miniconda/en/latest/) et l'environnement [Jupyter](https://jupyter.org/)).
- [R](https://www.r-project.org/) (souvent associé à [Rstudio](https://www.rstudio.com/categories/rstudio-ide/) et plus récemment à [Positron](https://github.com/posit-dev/positron)).
- Une [comparaison](https://mthh.github.io/presentation-python-r-shs/#/title-slide) des deux langages en SHS.

### Logiciels libres et gratuits

- [Jamovi](https://www.jamovi.org/) (notamment utilisé dans la formation auprès de nos étudiant·e·s).
- Plein d'autres (dont [JASP](https://jasp-stats.org/), [Trideux Cloud](https://trideux.cloud/), etc.).

### Principaux logiciels commerciaux

- [STATA](https://www.stata.com/) (disponible sur le bureau virtuel).
- [XLSTAT](https://www.xlstat.com/fr/) (disponible en salle informatique Victoire).
- [SPAD](https://ia-data-analytics.fr/logiciel-data-mining/analyse-de-donnees/) (disponible sur le bureau virtuel).
- [SPSS](https://www.ibm.com/fr-fr/spss)
- [SAS](https://www.sas.com/fr_fr/home.html)

### Questionnaires en ligne

- Selon votre affiliation, il est possible d'accéder à un Limesurvey maintenu par Sciences Po Bordeaux (demande d'accès auprès de Stéphane Botella) ou par l'Université de Bordeaux (demande d'accès par [ticket GLPI](https://assistance.u-bordeaux.fr/front/helpdesk.public.php)), ainsi que d'avoir accès à Sphinx par l'Université de Bordeaux (idem).
- Librement accessibles, [Kobotoolbox](https://www.kobotoolbox.org/) et [Framaform](https://framaforms.org/abc/fr) peuvent également être intéressants.

## Outils spécifiques / thématiques

Pour des usages spécifiques, on ne peut que recommander d'aller voir du côté des outils proposés par le [Medialab](https://medialab.sciencespo.fr/en/tools/).

### Data visualization

- Python (Plotly, Seaborn, Matplotlib) et R (ggplot2).
- [Rawgraphs](https://www.rawgraphs.io/) : outil en ligne gratuit et open source pour la visualisation de données.
- [Datawrapper](https://www.datawrapper.de/) : en ligne  (nécessite une création de compte).
- [Flourish](https://flourish.studio/) : en ligne  (nécessite une création de compte).
- Et des aides comme [From Data to viz](https://www.data-to-viz.com/), la [Python Graph Gallery](https://python-graph-gallery.com/) et la [R Graph Gallery](https://r-graph-gallery.com/).

### Analyse textuelle

- [Cortext](https://docs.cortext.net/) : plateforme en ligne d'analyse de corpus textuels (maintenue par le [LISIS](http://umr-lisis.fr/cortext/)).
- [Gargantex](https://www.gargantext.org/) : plateforme en ligne de text-mining (maintenue par l'[ISC-PIF](https://iscpif.fr/gargantext/a-propos/)).
- [Iramuteq](https://iramuteq.org/) : logiciel gratuit d'analyse textuelle.
- Python (et un peu moins R) avec les bibliothèques dédiées ([Spacy](https://spacy.io/), [NLTK](https://www.nltk.org/), etc.).

### Analyse de réseaux

- [Gephi](https://gephi.org/) : logiciel d'analyse et de visualisation de réseaux, gratuit et open source. L'un des plus connus.
- [Cytoscape](https://cytoscape.org/) : logiciel libre pour la visualisation de réseaux (à l'origine surtout utilisé en bioinformatique).
- Python et R avec leurs bibliothèques dédiées ([networkX](https://networkx.org/), [ipysigma](https://github.com/medialab/ipysigma), [igraph](https://r.igraph.org/), etc.).
- Et bien [d'autres…](https://project-awesome.org/briatte/awesome-network-analysis)

### Cartographie

- Python et R avec leurs bibliothèques dédiées ([GeoPandas](https://geopandas.org/en/stable/), etc.).
- [Khartis](https://www.sciencespo.fr/cartographie/khartis/) : création de cartes thématiques. Simple, en ligne ou en [local](https://www.sciencespo.fr/cartographie/khartis/#download).
- [Magrit](https://magrit.cnrs.fr/) : application de cartographie thématique open source, en ligne (et aussi en [local](https://magrit.cnrs.fr/download/)).
- [QGIS](https://qgis.org) : logiciel SIG (système d'information géographique) gratuit et open source, TRÈS complet.
- etc.

### Collecte de données web

Le sujet est trop vaste pour être traité ici, mais quelques outils et pistes pour se faire une idée :

- [Minet](https://medialab.sciencespo.fr/outils/minet/) : outil de collecte (bibliothèque Python et ligne de commande) de données en ligne (url, Twitter, Instagram, Telegram, etc.).
- [Hyphe](https://medialab.sciencespo.fr/outils/hyphe/) : logiciel libre pour créer des corpus web.
- [4cat](https://www.4cat.nl/) : logiciel de collecte et d'analyse de données des réseaux sociaux (4chan, telegram, tumblr, reddit, etc.).
- [Social Media Research Toolkit](https://socialmedialab.ca/apps/social-media-research-toolkit-2/) : liste de ressources et outils pour l'analyse des médias sociaux.
- [Extractify](https://github.com/fredericvergnaud/extractify/wiki) : plugin (navigateur Chrome) pour l'extraction de données. Développé par [Frédéric Vergnaud](https://mate-shs.cnrs.fr/actions/tutomate/tuto27-extractify-frederic-vergnaud/).
- Coder une solution personnalisée…

### Stockage des données (drive)

- [sDrive](https://ods.cnrs.fr/sdrive.php) (anciennement Mycore) disponible avec un accès Janus et proposé par le CNRS (100 Go).
- l'[UBcloud](https://ubcloud.u-bordeaux.fr) du côté de l'université de Bordeaux (50 Go + dossiers partagés).
- [Sharedocs](https://documentation.huma-num.fr/sharedocs-stockage/) du côté d'[Huma-Num](https://www.huma-num.fr/).

### Gestion des références bibliographiques

- [Zotero](https://www.zotero.org/).
