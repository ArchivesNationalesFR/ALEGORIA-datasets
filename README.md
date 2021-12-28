# ALEGORIA-datasets


Les jeux de données produits par les Archives nationales dans le cadre du projet ANR ALEGORIA

Ces jeux de données décrivent les séries de photographies aériennes conservées aux Archives nationales et retenues puis traitées dans le cadre du projet ANR [ALEGORIA](https://www.alegoria-project.fr).

Ces jeux de données sont au format RDF/XML. La principale ontologie de référence est [Records in Contexts - Ontology (RiC-O)](https://www.ica.org/standards/RiC/ontology). Le segment de base des IRI (valeur de l'attribut xml:base de l'élément racine rdf:RDF de chaque fichier) est http://data.alegoria-project.fr/id/anf/. 

Ces jeux de données sont publiés dans l'application suivante dotée d'un SPARQL endpoint : [http://data.alegoria-project.fr/](http://data.alegoria-project.fr/). L'interface de recherche et de consultation de cette application est actuellement en construction. Voir aussi à ce sujet la page [https://www.alegoria-project.fr/en/Metadata](https://www.alegoria-project.fr/en/Metadata), qui présente l'ensemble des jeux de données RDF/RiC-O produites dans le cadre du projet ALEGORIA.

## Licence

Ces métadonnées étant des informations publiques, l'usager dispose d'un droit non exclusif et gratuit de libre « réutilisation » à des fins commerciales ou non, dans le monde entier et pour une durée illimitée. Il doit accompagner chaque rediffusion des informations de l'indication précise de l'origine des métadonnées : « Archives nationales (France) », date des métadonnées (mai 2021), nom du référentiel (fourni dans le fichier Excel qui en donne la liste). Voir à ce sujet la page : https://www.archives-nationales.culture.gouv.fr/fr/web/guest/reutilisation-des-donnees-publiques.

## Contenu

Le dossier agents contient 4 fichiers, chacun décrivant un organisme :
- le fichier FRAN_Agent_005061.rdf décrit les Archives nationales, qui conservent les photographies aériennes décrites ;
- le fichier FRAN_Agent_052067.rdf décrit l'entreprise Lapie, qui a produit les albums de photographies aériennes décrits dans le dossier Lapie ;
- les notices FRAN_Agent_006392.rdf et FRAN_Agent_006393.rdf décrivent respectivement la Division des travaux topographiques (1944-1994) du Ministère de la Reconstruction et de l'Urbanisme et le Service technique de l'Urbanisme, qui ont produit les photographies aériennes décrites dans le dossier MRU.


Ces fichiers ont été produits à partir des notices d'autorité en XML/EAC-CPF décrivant les mêmes entités dans le référentiel des producteurs des Archives nationales. Ces notices d'autorité sont disponibles dans le dépôt GitHub consacré aux référentiels des Archives nationales (voir le dossier [https://github.com/ArchivesNationalesFR/Referentiels/tree/main/agents/producteurs/eac-cpf](https://github.com/ArchivesNationalesFR/Referentiels/tree/main/agents/producteurs/eac-cpf)). Elles sont aussi interrogeables et consultables dans la salle des inventaires virtuelle. Ainsi, par exemple, pour consulter dans la SIV la notice descriptive des applications photographiques d'industrie et d'édition (entreprise Lapie), taper [https://www.siv.archives-nationales.culture.gouv.fr/siv/NP/FRAN_NP_052067](https://www.siv.archives-nationales.culture.gouv.fr/siv/NP/FRAN_NP_052067).

Le dossier Lapie contient actuellement la description en RDF de 85 des 158 albums de tirages couleur du fonds Lapie conservés aux Archives nationales sous les cotes 1/PH/C/1 à 1/PH/C/158, soit plus de 14000 tirages décrits individuellement. Ces données ont été produites automatiquement à partir d'un instrument de recherche archivistique qui sera consultable dans la salle des inventaires virtuelle des Archives nationales vers le deuxième trimestre 2022.

Le dossier MRU contient actuellement la description en RDF de près de 10000 vues (essentiellement des films négatifs noir et blanc) petit format, produites entre 1948 et 1970, dans le cadre d'environ 1200 missions aériennes. Ces données ont été produites automatiquement à partir d'un instrument de recherche archivistique qui est consultable depuis peu dans la salle des inventaires virtuelle des Archives nationales, ainsi que les images numériques des photos aériennes décrites : voir cet instrument de recherche à l'adresse [https://www.siv.archives-nationales.culture.gouv.fr/siv/IR/FRAN_IR_050605](https://www.siv.archives-nationales.culture.gouv.fr/siv/IR/FRAN_IR_050605), et plus précisément la partie consacrée aux vues aériennes à axe oblique : [https://www.siv.archives-nationales.culture.gouv.fr/siv/UD/FRAN_IR_050605/c-5zb450vq1--frw5mhf8pesh](https://www.siv.archives-nationales.culture.gouv.fr/siv/UD/FRAN_IR_050605/c-5zb450vq1--frw5mhf8pesh). Depuis les pages web citées, on peut aussi télécharger l'instrument de recherche au format XML/EAD.

## Autres jeux de données liés

Les jeux de données ALEGORIA référencent des types de supports, des types de documents, des mots-matières (objets figurant sur les photos) et surtout des lieux photographiés (instances de la classe rico:Place) décrits dans les référentiels des Archives nationales. Vous trouverez ces référentiels dans le dépôt GitHub consacré aux référentiels des Archives nationales ([https://github.com/ArchivesNationalesFR/Referentiels](https://github.com/ArchivesNationalesFR/Referentiels)). Ces référentiels sont également publiés et interrogeables dans l'application  [http://data.alegoria-project.fr/](http://data.alegoria-project.fr/) ; pour les besoins du projet ALEGORIA, le segment de base des IRI des entités décrites dans ces référentiels des Archives nationales (valeur de l'attribut xml:base de l'élément racine rdf:RDF de chaque fichier) a juste été changé, on lui a donné la valeur http://data.alegoria-project.fr/id/anf/. 

## Pour plus d'informations

Vous pouvez contacter par courriel le Lab des Archives nationales de France, à l'adresse suivante :  <le-lab.archives-nationales@culture.gouv.fr>.
