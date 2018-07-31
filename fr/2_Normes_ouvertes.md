[« Page précédente : Introduction](1_Introduction.md) | [Table des matières](../README.md#table-des-mati%C3%A8res) | [Page suivante : Logiciels libres (open source) - Utilisation »](3_Logiciel_libre_Utilisation.md)

## Normes ouvertes

- [Avantages](#avantages)
- [Risques et inconvénients](#risques-et-inconvénients)
- [Pratiques exemplaires pour l'adoption de normes ouvertes](#pratiques-exemplaires-pour-l-adoption-de-normes-ouvertes)
- [Normes ouvertes privilégiées](#normes-ouvertes-privilégiées)
- [Guide numérique du GC](#guide-numérique-du-gc)

Les normes ouvertes sont un ensemble de règles conçues pour faire un travail spécifique dans la technologie. Ils sont également conçus en collaboration et libres d'utilisation. Les normes ouvertes permettent aux logiciels libres et aux logiciels exclusifs de fonctionner ensemble.

### Avantages

#### Interopérabilité

Pour toute organisation, en particulier pour les administrations publiques, les besoins d'interopérabilité se situent à deux niveaux distincts mais qui se chevauchent, soit l'interopérabilité interne avec son propre environnement de la GI/TI et l'interopérabilité avec les environnements de la GI/TI des intervenants externes (autres administrations, le public, les entreprises, les associations), directement ou indirectement, par la disponibilité de données ouvertes.

##### Indépendance et substituabilité

D'un point de vue interne, l'interopérabilité est étroitement liée à la question de l'architecture d'entreprise, en ce sens qu'elle permet de découpler ses diverses composantes tout en restant intégrée. Ainsi, le [Cadre commun d'interopérabilité du gouvernement du Québec](http://www.tresor.gouv.qc.ca/ressources-informationnelles/architecture-dentreprise-gouvernementale/standards-et-normes/cadre-commun-dinteroperabilite/) (CCIGQ) est lié au Cadre de référence de l'architecture intégrée du gouvernement; et la version 2 du document français [Référentiel général d'interopérabilité](http://references.modernisation.gouv.fr/interoperabilite) renvoie au [Cadre commun d'urbanisation du système d'information de l'État](http://references.modernisation.gouv.fr/sites/default/files/Cadre%20Commun%20d%27Urbanisation%20du%20SI%20de%20l%27Etat%20v1.0_0.pdf).

Dans le contexte de l'architecture intégrée entièrement sous votre contrôle, une des options assurant l'intégration des composantes constitue la normalisation, soit des produits directement ou dans une famille de produits généralement offerts par un seul fournisseur. Cette approche peut avoir des avantages fonctionnels (généralement en termes d'intégration harmonieuse entre les produits), mais elle a l'inconvénient de lier la technologie de l'information interne à un système externe ou à un fournisseur particulier. Cette connexion peut devenir à la fois un handicap technique (en écartant l'adoption potentielle de nouvelles solutions plus pertinentes) et un handicap économique (en réduisant les possibilités de négociation et en augmentant les coûts de changement). Dans un scénario idéal d'interopérabilité, cependant, les composantes de base peuvent être substituées; chacune peut être modifiée plus facilement et indépendamment. Cette approche renforce la liberté de choix et rend l'architecture intégrée plus souple, parce que chaque élément de base peut être remplacé par un autre qui a la même fonctionnalité sans avoir d'impact sur le reste des systèmes.

##### Adhésion à l'application - Verrouillage du fournisseur

À l'interne, l'interopérabilité peut être vue en fonction de deux dimensions : La dimension horizontale (entre deux applications distinctes) qui, de par nature, est la dimension en jeu lorsque deux systèmes différents interagissent; et la dimension verticale, qui concerne les composantes d'une seule application. C'est généralement le cas entre l'application elle-même et les composantes de l'infrastructure sous-jacente (p. ex., une application peut nécessiter une base de données particulière qui, elle-même, ne fonctionne que sur un système d'exploitation particulier, sans qu'aucune fonctionnalité n'entre en jeu). C'est là que l'adhésion à l'application entre en ligne de compte, ce qui dépasse la portée de l'interopérabilité même si un certain nombre de principes fondamentaux sont les mêmes.

##### Infonuagique

L'informatique en nuage consiste à fournir des services d'infrastructure et des services d'applications sur demande. Cela est possible grâce à un niveau élevé de virtualisation des composantes matérielles au moyen de logiciels d'infrastructure de service. L'informatique en nuage est basée sur une architecture logicielle complexe qui gère simultanément l'élasticité des ressources (processeurs, mémoire d'accès aléatoire, stockage et réseaux) et la capacité des applications d'utiliser ces ressources de façon optimale.

Sur le plan de l'interopérabilité, il n'y a pas de différence fondamentale entre une infrastructure conventionnelle et un nuage, si ce n'est la complexité de ce dernier et la nécessité de normaliser beaucoup plus les composantes verticales et horizontales. En particulier, toute impartition d'une infrastructure ou d'applications à un nuage public doit tenir compte de la capacité de l'organisation privée ou tierce d'appliquer des normes qui permettent le changement de fournisseur ou le rétablissement d'un certain nombre de services, au besoin. Dans ce contexte, l'absence d'un cadre d'interopérabilité et de normes ouvertes acceptées par le fournisseur pose un risque important pour la durabilité de la solution.

En ce qui concerne le déploiement d'un nuage privé, l'interopérabilité favorise la concurrence entre les fournisseurs en ce qui concerne le matériel et les logiciels, ainsi que la capacité de développer davantage l'infrastructure au fil du temps. En effet, l'utilisation de normes, par l'entremise des interfaces de programmation (API) par exemple, accroît l'indépendance par rapport aux différents moteurs propres aux composants matériels, et elle rend ces services d'infrastructure indépendants du logiciel déployé.

La mise en œuvre d'une approche infonuagique en premier est une occasion unique de normaliser ces processus et de s'entendre sur un cadre commun. L'utilisation d'un cadre d'interopérabilité et de normes ouvertes facilite et rend moins coûteuse l'impartition d'une partie de l'infrastructure à un organisme tiers, ou la migration vers Services partagés Canada, dans une solution hybride.

#### Logiciel libre

Le [Logiciel libre](3_Logiciel_libre_Utilisation.md) (LL) est un moyen de développer et de distribuer des logiciels. Le code est souvent écrit en collaboration, et il peut être téléchargé, utilisé et modifié par n'importe qui.

Le LL utilise habituellement ou contribue à définir les normes ouvertes et les spécifications accessibles au public. Les produits de logiciel libre sont, de par leur nature, des spécifications accessibles au public, et la disponibilité de leur code source favorise un débat ouvert et démocratique sur leurs spécifications, ce qui les rend à la fois plus robustes et interopérables. Du point de vue de la conception, l'interopérabilité et les logiciels libres sont clairement distincts, tout comme les logiciels libres et les normes ouvertes. Toutefois, du point de vue culturel et historique, il existe des liens solides entre ces concepts. Cela peut s'expliquer par la « collectivité des valeurs » - en raison de leur nature ouverte, les modèles économiques de logiciels libres sont fondés moins sur des stratégies de verrouillage de l'utilisateur et plus sur l'interopérabilité au profit de l'utilisateur. L'utilisation de normes ouvertes est nécessaire pour assurer l'interopérabilité entre les produits ou les systèmes.

### Pratiques exemplaires pour l'adoption de normes ouvertes

#### Définir les principes de sélection des normes ouvertes

- Principes utilisés pour évaluer des normes ouvertes spécifiques et exiger leur utilisation, le cas échéant
- Veiller à ce que les normes sélectionnées permettent l'interopérabilité des logiciels via des protocoles ouverts et l'échange de données entre les logiciels et les dépôts de données

#### Identifier les normes ouvertes à utiliser au GC

- Cadre d'interopérabilité qui répertorie les normes ouvertes obligatoires et recommandées
- Alignement et collaboration possible avec [Open Standards Board du Royaume-Uni](https://www.gov.uk/government/groups/open-standards-board) sur la sélection de normes ouvertes pour le gouvernement

#### Formation et soutien

La formation et le soutien à la migration vers l'adoption de normes ouvertes sont similaires aux [Pratiques exemplaires en matière de formation et de soutien à l'utilisation des logiciels libres](3_Logiciel_libre_Utilisation.md#formation-et-soutien).

#### Conversion des formats

- Faire un effort significatif afin de veiller à ce que les formats de fichiers et de données fermés peuvent être convertis en normes ouvertes
- Ne pas oublier que la conversion des documents, par exemple entre Microsoft Office et LibreOffice, est une tâche qui peut exiger beaucoup de ressources humaines pour tous les documents complexes, surtout lorsqu'ils comprennent un formatage précis ou des macros.

### Normes ouvertes privilégiées

La [Norme sur l'interopérabilité du Web du GC](https://www.tbs-sct.gc.ca/pol/doc-fra.aspx?id=25875) rend les normes ouvertes suivantes obligatoires pour les sites Web du GC.

- **Langue de balisage** : [HTML5](https://www.w3.org/TR/html5/)
- **Codage du caractère** : [UTF-8](https://tools.ietf.org/html/rfc3629)
- **Données HTML et vocabulaire de données** : [RDFa Lite](https://www.w3.org/TR/rdfa-lite/), [Schema.org](http://schema.org/)
- **Fil Web** : [Format de syndication Atom](https://tools.ietf.org/html/rfc4287)

La [Norme sur l'accessibilité des sites Web du GC](https://www.tbs-sct.gc.ca/pol/doc-fra.aspx?id=23601) rend la norme ouverte suivante obligatoire pour les sites Web du GC.

- [Règles sur l'accessibilité des contenus Web (WCAG) 2.0](https://www.w3.org/TR/WCAG20/)

#### Autres normes ouvertes au GC

Bibliothèque et Archives Canada (BAC) [Lignes directrices sur les formats de fichier à utiliser pour transférer des ressources documentaires](http://www.bac-lac.gc.ca/fra/services/gestion-ressources-documentaires-gouvernement/lignes-directrices/Pages/lignes-directrices-formats-fichier-transferers-ressources-documentaires.aspx) énumèrent les formats recommandés pour les textes, présentations, courriels, images fixes, audio, vidéo, géospatial, la conception assistée par ordinateur (CAO) et les jeux de données. Le rapport de Patrimoine Canadien sur les [Éléments d'un cadre d'interopérabilité technique](https://wiki.gccollab.ca/%C3%89l%C3%A9ments_pour_un_cadre_d%27interop%C3%A9rabilit%C3%A9_technique_pour_Patrimoine_Canadien), le [Cadre commun d'interopérabilité du gouvernement du Québec](http://www.tresor.gouv.qc.ca/fileadmin/PDF/ressources_informationnelles/architecture_entreprise_gouvernementale/AEG_3.1-CCIGQinteroperabilite.pdf) du Québec et le [Référentiel Général d'interopérabilité](http://references.modernisation.gouv.fr/sites/default/files/Referentiel_General_Interoperabilite_V2.pdf) de la France identifient plusieurs des mêmes normes ouvertes recommandées.

[Les principes des données ouvertes du GC](https://ouvert.canada.ca/fr/principes-de-donnees-ouvertes) indique que « l'utilisation de formats communs » est l'un des principes des données ouvertes, de sorte que les jeux de données diffusés par le gouvernement du Canada soient dans des formats de fichier librement accessibles le plus souvent possible.

Services publics et Approvisionnement Canada (SPAC) a mis à l'essai le [Standard de données sur la commande publique ouverte](http://standard.open-contracting.org/latest/fr/) afin de démontrer l'utilisation de la norme en établissant des liens entre les phases du processus d'approvisionnement à l'aide des données provenant des approvisionnements effectués par SPAC au nom des ministères et organismes gouvernementaux. ([source](https://achatsetventes.gc.ca/donnees-sur-l-approvisionnement/projet-pilote-norme-relative-aux-donnees-sur-la-passation-de-marches-ouverts)).

#### Normes ouvertes pour le gouvernement du Royaume Uni

Le [Conseil des normes ouvertes du Royaume-Uni](https://www.gov.uk/government/groups/open-standards-board) sélectionne un ensemble de normes ouvertes pour être utilisé dans la technologie gouvernementale. L'objectif est de les appliquer uniformément à l'ensemble des organismes gouvernementaux, afin d'améliorer les services aux utilisateurs. Les normes ouvertes sont sélectionnées après une période d'examen par les pairs et de commentaires du public par l'entremise du [Centre des normes](https://github.com/alphagov/open-standards). Ce qui suit sont les [Normes ouvertes pour le gouvernement](https://www.gov.uk/government/publications/open-standards-for-government) approuvées.

- **Consulter les documents gouvernementaux** : [HTML5](https://w3.org/TR/html5/) [Format/archivage de documents portables (PDF/A) 1](https://www.iso.org/standard/38920.html) [Format/archivage de documents portables (PDF/A) 2](https://www.iso.org/standard/50655.html)
- **Partage ou collaboration en lien avec des documents gouvernementaux** : [Format de document ouvert (FDO)](https://www.iso.org/standard/66363.html)
- **Profil d'encodage de caractères multiplateforme** : [Unicode 6.2](http://www.unicode.org/versions/Unicode6.2.0/), [UTF-8](https://tools.ietf.org/html/rfc3629)
- **Données contractuelles ouvertes** : [Standard de données sur la commande publique ouverte](http://standard.open-contracting.org/latest/fr/)
- **Codes de pays** : [ISO 3166-1:2013](https://www.iso.org/fr/standard/63545.html)
- **Codes de langues** : [ISO 639-1:2002](https://www.iso.org/fr/standard/22109.html)
- **Données sur le développement international** : [IATI](http://iatistandard.org/202/)
- **Publication des postes vacants** : [JobPosting - Schema.org](http://schema.org/JobPosting)
- **Échange de points de localisation** : [Système européen de référence terrestre (ETRS) 89](http://etrs89.ensg.ign.fr/), [Système géodésique mondial (WGS) 84)](https://www.nga.mil/ProductsServices/GeodesyandGeophysics/Pages/WorldGeodeticSystem.aspx)
- **Identificateurs persistants et résolubles** : [Protocole de transfert hypertexte (HTTP) 1.1](https://tools.ietf.org/html/rfc2616), [Identificateur uniforme des ressources (URI)](https://tools.ietf.org/html/rfc3986)
- **Échange de coordonnées** : [vCard](https://tools.ietf.org/html/rfc6350)
- **Échange d'événements du calendrier** : [iCalendar](https://tools.ietf.org/html/rfc5545)

### Guide numérique du GC

- [Utiliser des normes et des solutions ouvertes](https://canada-ca.github.io/digital-playbook-guide-numerique/views-vues/standards-normes/fr/6-utiliser-normes-solutions-ouvertes.html)
