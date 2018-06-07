[« Page précédente : Introduction](1_Introduction.md) | [Table des matières](../README.md#table-des-mati%C3%A8res) | [Page suivante : Logiciels libres (open source) »](3_Logiciel_libre.md)

## Normes ouvertes

- [Définition](#definition)
- [Interopérabilité](#interopérabilité)
- [Normes ouvertes privilégiées](#normes-ouvertes-privilégiées)
- [Exemples](#examples)

Le [Logiciel libre](3_Logiciel_libre.md) utilise habituellement ou contribue à définir les normes ouvertes et les spécifications accessibles au public. Les produits de logiciel libre sont, de par leur nature, des spécifications accessibles au public, et la disponibilité de leur code source favorise un débat ouvert et démocratique sur leurs spécifications, ce qui les rend à la fois plus robustes et interopérables. Du point de vue de la conception, l'interopérabilité et les logiciels libres sont clairement distincts, tout comme les logiciels libres et les normes ouvertes. Toutefois, du point de vue culturel et historique, il existe des liens solides entre ces concepts. Cela peut s'expliquer par la « collectivité des valeurs » - en raison de leur nature ouverte, les modèles économiques de logiciels libres sont fondés moins sur des stratégies de verrouillage de l'utilisateur et plus sur l'interopérabilité au profit de l'utilisateur. L'utilisation de normes ouvertes est nécessaire pour assurer l'interopérabilité entre les produits ou les systèmes.

### Interopérabilité

Pour toute organisation, en particulier pour les administrations publiques, les besoins d'interopérabilité se situent à deux niveaux distincts mais qui se chevauchent, soit l'interopérabilité interne avec son propre environnement de la GI/TI et l'interopérabilité avec les environnements de la GI/TI des intervenants externes (autres administrations, le public, les entreprises, les associations), directement ou indirectement, par la disponibilité de données ouvertes.

#### Interopérabilité interne

L'interopérabilité interne est beaucoup plus axée sur la dimension technique. Il faut porter une attention particulière à sa définition pour veiller à ce qu'elle reflète fidèlement les attentes associées au terme, particulièrement en termes d'indépendance - le terme souveraineté est parfois utilisé - et de neutralité.

Les anciens systèmes constituent un obstacle majeur à l'interopérabilité. Historiquement, les applications et les systèmes d'information des administrations publiques ont été développés de façon ascendante, en essayant de résoudre des problèmes locaux et spécifiques au domaine. Il en est résulté une GI/TI fragmentée qui est difficile à interopérer. En raison de la taille de l'administration publique et de la fragmentation des solutions de GI/TI, la pléthore de systèmes existants crée un obstacle supplémentaire à l'interopérabilité dans la couche technique.

L'interopérabilité technique devrait être assurée, dans la mesure du possible, par l'utilisation de normes ouvertes.

##### Indépendance et substituabilité

D'un point de vue interne, l'interopérabilité est étroitement liée à la question de l'architecture intégrée, en ce sens qu'elle permet de découpler ses diverses composantes tout en restant intégrée. Ainsi, le [Cadre commun d'interopérabilité du gouvernement du Québec](http://www.tresor.gouv.qc.ca/ressources-informationnelles/architecture-dentreprise-gouvernementale/standards-et-normes/cadre-commun-dinteroperabilite/) (CCIGQ) est lié au Cadre de référence de l'architecture intégrée du gouvernement; et la version 2 du document français [Référentiel général d'interopérabilité](http://references.modernisation.gouv.fr/interoperabilite) renvoie au [Cadre commun d'urbanisation du système d'information de l'État](http://references.modernisation.gouv.fr/sites/default/files/Cadre%20d%27Urbanisation%20du%20SI%20de%20l%20l Etat%27v1.0_0.pdf).

Dans le contexte de l'architecture intégrée entièrement sous votre contrôle, une des options assurant l'intégration des composantes constitue la normalisation, soit des produits directement ou dans une famille de produits généralement offerts par un seul fournisseur. Cette approche peut avoir des avantages fonctionnels (généralement en termes d'intégration harmonieuse entre les produits), mais elle a l'inconvénient de lier la technologie de l'information interne à un système externe ou à un fournisseur particulier. Cette connexion peut devenir à la fois un handicap technique (en écartant l'adoption potentielle de nouvelles solutions plus pertinentes) et un handicap économique (en réduisant les possibilités de négociation et en augmentant les coûts de changement). Dans un scénario idéal d'interopérabilité, cependant, les composantes de base peuvent être substituées; chacune peut être modifiée plus facilement et indépendamment. Cette approche renforce la liberté de choix et rend l'architecture intégrée plus souple, parce que chaque élément de base peut être remplacé par un autre qui a la même fonctionnalité sans avoir d'impact sur le reste des systèmes.

##### Adhésion à l'application - Verrouillage du fournisseur

À l'interne, l'interopérabilité peut être vue en fonction de deux dimensions : La dimension horizontale (entre deux applications distinctes) qui, de par nature, est la dimension en jeu lorsque deux systèmes différents interagissent; et la dimension verticale, qui concerne les composantes d'une seule application. C'est généralement le cas entre l'application elle-même et les composantes de l'infrastructure sous-jacente (p. ex., une application peut nécessiter une base de données particulière qui, elle-même, ne fonctionne que sur un système d'exploitation particulier, sans qu'aucune fonctionnalité n'entre en jeu). C'est là que l'adhésion à l'application entre en ligne de compte, ce qui dépasse la portée de l'interopérabilité même si un certain nombre de principes fondamentaux sont les mêmes.

#### Informatique en nuage

L'informatique en nuage consiste à fournir des services d'infrastructure et des services d'applications sur demande. Cela est possible grâce à un niveau élevé de virtualisation des composantes matérielles au moyen de logiciels d'infrastructure de service. L'informatique en nuage est basée sur une architecture logicielle complexe qui gère simultanément l'élasticité des ressources (processeurs, mémoire d'accès aléatoire, stockage et réseaux) et la capacité des applications d'utiliser ces ressources de façon optimale.

Sur le plan de l'interopérabilité, il n'y a pas de différence fondamentale entre une infrastructure conventionnelle et un nuage, si ce n'est la complexité de ce dernier et la nécessité de normaliser beaucoup plus les composantes verticales et horizontales. En particulier, toute impartition d'une infrastructure ou d'applications à un nuage public doit tenir compte de la capacité de l'organisation privée ou tierce d'appliquer des normes qui permettent le changement de fournisseur ou le rétablissement d'un certain nombre de services, au besoin. Dans ce contexte, l'absence d'un cadre d'interopérabilité et de normes ouvertes acceptées par le fournisseur pose un risque important pour la durabilité de la solution.

En ce qui concerne le déploiement d'un nuage privé, l'interopérabilité favorise la concurrence entre les fournisseurs en ce qui concerne le matériel et les logiciels, ainsi que la capacité de développer davantage l'infrastructure au fil du temps. En effet, l'utilisation de normes, par l'entremise des interfaces de programmation (API) par exemple, accroît l'indépendance par rapport aux différents moteurs propres aux composants matériels, et elle rend ces services d'infrastructure indépendants du logiciel déployé.

La mise en oeuvre d'un nuage est donc une occasion unique de normaliser ces processus et de s'entendre sur un cadre commun. L'utilisation d'un cadre d'interopérabilité et de normes facilite et rend moins coûteuse l'impartition d'une partie de l'infrastructure à un organisme tiers, ou la migration vers Services partagés Canada, dans une solution hybride.

#### Cadre d'interopérabilité

Un cadre d'interopérabilité est défini comme un ensemble de politiques, de lignes directrices, de normes, de règles et de recommandations formulées par un réseau d'acteurs en vue d'atteindre le plus haut niveau d'interopérabilité possible. Il décrit également les règles de fonctionnement qui régissent l'analyse, la sélection, l'adoption et la mise à jour de chacun de ces éléments.

Pour assurer le déploiement et la longévité des systèmes interopérables, il est nécessaire de choisir conjointement les normes à adopter ainsi que les conditions de leur mise en oeuvre. C'est la raison pour laquelle plusieurs pays européens (dont la France et le Royaume-Uni) et des provinces canadiennes comme le Québec ont choisi d'établir des cadres d'interopérabilité. Les résultats sont probants, car les normes ouvertes sont utilisées régulièrement et largement, et elles sont toujours la première approche à envisager lorsque de nouvelles exigences apparaissent.

Comme il est mentionné dans les divers cadres d'interopérabilité déjà publiés, ils sont conçus uniquement pour identifier les normes clés et non pour offrir des solutions prédéfinies et uniques (p. ex., en ce qui concerne le choix du logiciel). L'objectif d'un cadre d'interopérabilité est donc de faciliter et d'orienter les choix d'interopérabilité d'une organisation tout en limitant le nombre de normes potentielles afin de garantir un maximum de clarté.

### Normes ouvertes privilégiées

La [Norme sur l'interopérabilité du Web du GC](https://www.tbs-sct.gc.ca/pol/doc-fra.aspx?id=25875) rend les normes ouvertes suivantes obligatoires pour les sites Web du GC.

- **Langue de balisage** : [HTML5](https://www.w3.org/TR/html5/)
- **Codage du caractère** : [UTF-8](https://tools.ietf.org/html/rfc3629)
- **Données HTML et vocabulaire de données** : [RDFa Lite](https://www.w3.org/TR/rdfa-lite/), [Schema.org](http://schema.org/)
- **Fil Web** : [Format de syndication Atom](https://tools.ietf.org/html/rfc4287)

La [Norme sur l'accessibilité des sites Web du GC](https://www.tbs-sct.gc.ca/pol/doc-fra.aspx?id=23601) rend la norme ouverte suivante obligatoire pour les sites Web du GC.

- [Règles sur l'accessibilité des contenus Web (WCAG) 2.0](https://www.w3.org/TR/WCAG20/)

### Autres normes ouvertes au GC

Bibliothèque et Archives Canada (BAC) [Lignes directrices sur les formats de fichier à utiliser pour transférer des ressources documentaires](http://www.bac-lac.gc.ca/fra/services/gestion-ressources-documentaires-gouvernement/lignes-directrices/Pages/lignes-directrices-formats-fichier-transferers-ressources-documentaires.aspx) recommande les normes ouvertes suivantes.

#### Texte

- [Code standard américain pour l'échange d'information (ASCII)](https://www.iso.org/standard/4777.html)
- [Publication électronique (EPUB) 3.0](http://idpf.org/epub/30)
- [Formats de document ouvert (ODF)](https://www.iso.org/standard/66363.html)
- [Format/archivage de documents portables (PDF/A) 1](https://www.iso.org/standard/38920.html)
- [Format/archivage de documents portables (PDF/A) 2](https://www.iso.org/standard/50655.html)
- [UTF-8](https://tools.ietf.org/html/rfc3629)
- [UTF-16](https://tools.ietf.org/html/rfc2781)

#### Présentation

- [Format de document ouvert (FDO)](https://www.iso.org/standard/66363.html)
- [Format/archivage de documents portables (PDF/A) 1](https://www.iso.org/standard/38920.html)

Les lignes directrices de BAC énumèrent également les formats recommandés pour les courriels, les images fixes, les enregistrements audio, vidéo, géospatiaux, la conception assistée par ordinateur (CAO) et les jeux de données. Le [Référentiel Général d'interopérabilité](http://references.modernisation.gouv.fr/sites/default/files/Referentiel_General_Interoperabilite_V2.pdf) de la France, le [Cadre commun d'interopérabilité du gouvernement du Québec](http://www.tresor.gouv.qc.ca/fileadmin/PDF/ressources_informationnelles/architecture_entreprise_gouvernementale/AEG_3.1-CCIGQinteroperabilite.pdf) du Québec et les « Éléments d'un cadre d'interopérabilité technique » de Patrimoine canadien (disponible à partir de GCpédia) identifient plusieurs des mêmes normes ouvertes recommandées.

[Les principes des données ouvertes du GC](https://ouvert.canada.ca/fr/principes-de-donnees-ouvertes) indique que « l'utilisation de formats communs » est l'un des principes des données ouvertes, de sorte que les jeux de données diffusés par le gouvernement du Canada soient dans des formats de fichier librement accessibles le plus souvent possible.

Services publics et Approvisionnement Canada (SPAC) a mis à l'essai le [Standard de données sur la commande publique ouverte](http://standard.open-contracting.org/latest/fr/) afin de démontrer l'utilisation de la norme en établissant des liens entre les phases du processus d'approvisionnement à l'aide des données provenant des approvisionnements effectués par SPAC au nom des ministères et organismes gouvernementaux. ([source](https://achatsetventes.gc.ca/donnees-sur-l-approvisionnement/projet-pilote-norme-relative-aux-donnees-sur-la-passation-de-marches-ouverts)).

### Normes ouvertes pour le gouvernement du Royaume Uni

Le gouvernement britannique doit choisir un ensemble de normes ouvertes qui sera utilisé dans la technologie gouvernementale. L'objectif est de les appliquer uniformément à l'ensemble des organismes gouvernementaux, afin d'améliorer les services aux utilisateurs. Les normes ouvertes sont sélectionnées après une période d'examen par les pairs et de commentaires du public par l'entremise du [Centre des normes](https://github.com/alphagov/open-standards). Voir les normes approuvées suivantes : [Normes ouvertes pour le gouvernement](https://www.gov.uk/government/publications/open-standards-for-government).

- **Consulter les documents gouvernementaux** : [HTML5](https://www3.org/TR/html5/) [Format/archivage de documents portables (PDF/A) 1](https://www.iso.org/standard/38920.html) [Format/archivage de documents portables (PDF/A) 2](https://www.iso.org/standard/50655.html)
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
