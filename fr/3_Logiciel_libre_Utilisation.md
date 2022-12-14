[<- Page précédente : Normes ouvertes](2_Normes_ouvertes.md) | [Table des matières](../README.md#table-des-mati%C3%A8res) | [Page suivante : Logiciels libres - Contribution ->](4_Logiciel_libre_Contribution.md)

## Logiciels libres - Utilisation

- [Définitions](#définitions)
- [Historique](#historique)
- [Propriété intellectuelle](#propriété-intellectuelle)
- [Utilisation des logiciels libres](#utilisation-des-logiciels-libres)
- [Avantages](#avantages)
- [Risques et inconvénients](#risques-et-inconvénients)
- [Pratiques exemplaires pour l'utilisation des logiciels libres](#pratiques-exemplaires-pour-lutilisation-de-logiciels-libres)
- [Contribution aux logiciels libres](#contribution-aux-logiciels-libres)
- [Logiciels libres privilégiées](#logiciels-libres-privilégiées)
- [Normes relatives au numérique du gouvernement du Canada](#normes-relatives-au-numérique-du-gouvernement-du-canada)

### Définitions

#### Logiciels libres

Les logiciels libres sont des logiciels qui respectent la liberté et la collectivité des utilisateurs. Le terme « libre » (_free_ en anglais) est davantage une question de liberté que de prix, car il fait référence à la liberté des utilisateurs.

Le terme « logiciel libre » a d'abord été proposé par Richard Stallman et défendu par la _Free Software Foundation_ (FSF). Le logiciel libre est défini par [quatre libertés essentielles](https://www.gnu.org/philosophy/free-sw.fr.html) : La liberté d'exécuter le programme, la liberté d'étudier son fonctionnement, la liberté de le modifier et la liberté de le redistribuer. L'accès au code source est une condition préalable de ces libertés; il ne constitue pas le but ultime en soi.

#### Logiciel à source ouverte

Logiciel dont le code source est rendu disponible avec une licence dans laquelle le titulaire du droit d'auteur donne les droits d'étudier, de modifier et de distribuer le logiciel à n'importe qui et à n'importe quelle fin.

Le terme utilisé par l'_Open Source Initiative_ (OSI). La [définition du logiciel à source ouverte](https://opensource.org/docs/osd) s'appuie sur dix critères.

#### Désambiguïsation

Les logiciels libres (LL) et les logiciels à source ouverte sont des logiciels dont le code source est distribué et peut être utilisé, copié, étudié et redistribué.

Les LL et les logiciels à source ouverte sont presque équivalents, mais ils correspondent à deux visions différentes, et aucun ne veut être inclus dans l'autre. Des auteurs utilisent les termes « logiciels libres et à source ouverte » (FOSS, pour _free open source software_ ou FLOSS, pour _free/libre open source software_). Aux fins du présent livre blanc, nous avons choisi d'utiliser le terme « logiciels libres (LL) » pour englober les termes « logiciel libre » et « logiciels à source ouverte ».

### Historique

Le LL remonte aux débuts de l'informatique. Un grand nombre des réussites du gouvernement ouvert seraient impossibles sans un code source libre et la générosité des collectivités d'internautes. Nous devrions rendre la pareille.

Les licences d'utilisation de logiciels (libres ou exclusives) tirent leur origine d'une source commune : le système d'exploitation Unix. ([source](https://opensource.com/article/17/9/open-source-licensing)) L'histoire est décrite en détail dans le document [Origins and History of Unix](http://www.faqs.org/docs/artu/ch02s01.html). Unix, premier système d'exploitation général, a été mis au point par AT&T Bell Laboratories à la fin des années 1960 et au début des années 1970. À cette époque, le département de la Justice des États-Unis avait émis un décret de consentement interdisant à AT&T de se livrer à des activités commerciales à l'extérieur de son champ d'activité principal, le service téléphonique. En raison du décret de consentement, AT&T ne pouvait pas exploiter Unix en tant que produit commercial, ce qui a poussé Bell Laboratories à céder Unix sous forme de code source selon des modalités autorisant sa modification ou sa redistribution. Cette situation a permis une utilisation généralisée d'Unix par les informaticiens et favorisé sa grande popularité dans les années 1970 et 1980.

Après l'abrogation du décret de consentement par le département de la Justice des États-Unis en 1983, AT&T a commercialisé Unix en tant que produit exclusif et adopté des conditions de licence plus restrictives. Pendant ce temps, il y a eu l'avènement des micro-ordinateurs (ou ordinateurs personnels) dans les années 1980, ce qui a conduit à une normalisation des logiciels. Cette normalisation a ensuite incité les entreprises à distribuer leurs logiciels sous forme binaire seulement parce que les utilisateurs avaient moins besoin d'examiner ou de corriger le code source. La licence exclusive est donc devenue le modèle dominant pour l'octroi de licences de logiciels.

À la suite de ce changement, Richard Stallman et le projet GNU ont commencé la conception d'un système d'exploitation offrant une alternative libre à UNIX. À la même période environ, la FSF a été créée pour promouvoir l'utilisation de LL. Le système d'exploitation avait à la fois besoin du noyau et des outils nécessaires à l'installation, à l'exécution et au développement de programmes. Le projet GNU a mis au point les outils, mais il manquait un noyau fonctionnel. C'est à ce moment que Linus Torvalds, un adolescent finlandais, a développé le premier noyau Linux dans le cadre d'un projet scolaire.

L'ensemble du noyau Linux et des outils GNU, communément appelé « Linux », a été publié dans le cadre de la [licence publique générale GNU](https://www.gnu.org/licenses/gpl-3.0.fr.html) (GPL), un modèle de licence créé par le projet GNU. La licence GPL a accordé aux bénéficiaires des droits illimités de redistribution du logiciel à condition que le code source ne puisse pas être tenu secret. Avec la popularité croissante de Linux, de ses milliers de contributeurs et de ses milliards d'utilisateurs, l'industrie a appris à suivre et à adopter les modalités de la licence GPL. Vers la fin des années 1990, la licence GPL et le paradigme des licences libres ont gagné en popularité et reçu un accueil largement favorable à l'échelle de l'industrie.

### Propriété intellectuelle

La propriété intellectuelle est une catégorie de propriété qui comprend les créations intangibles de l'intellect humain et englobe principalement les droits d'auteur, les brevets et les marques de commerce. Elle comprend également d'autres types de droits, comme les secrets commerciaux, les droits de publicité, les droits moraux et les droits contre la concurrence déloyale.

#### Licences

Aujourd'hui, la licence GPL en est à sa troisième version et elle n'est qu'un des nombreux types de licences libres. L'[OSI a approuvé plus de 80 licences libres](https://opensource.org/licenses/alphabetical). Ces licences appartiennent habituellement à l'une de deux catégories suivantes : les licences permissives et les licences réciproques.

Même parmi les licences que la FSF et l'OSI approuvent parce qu'elles possèdent les caractéristiques de base du LL, les modalités et les obligations varient grandement. On observe toutefois plusieurs catégories de clauses courantes :

- les avis généraux sur l'exonération de garantie ou la non-responsabilité;
- les obligations de notification, qui exigent généralement d'aviser les utilisateurs en aval de la licence de LL qui s'applique à l'oeuvre;
- les obligations relatives au code source, qui exigent généralement la fourniture du code source du logiciel au moment de la distribution;
- les obligations relatives à l'octroi de licence réciproque, qui nécessitent généralement la publication de toute modification ou amélioration en vertu de la même licence.

On retrouve les deux premiers types de clauses, soit les avis et les obligations de notification, dans presque toutes les licences de LL. En fait, la [licence BSD à deux clauses](https://opensource.org/licenses/BSD-2-Clause), courte et populaire, contient à peine plus que ces deux obligations. D'autres licences plus vastes, comme la licence GPL, contiennent des clauses qui énoncent ces quatre obligations.

Pour obtenir de plus amples détails sur les clauses de licences et d'autres questions juridiques, veuillez consulter l'[annexe A - Questions d'ordre juridique](Annexe_légale.md).

### Utilisation des logiciels libres

Dans le contexte de l'utilisation d'un logiciel libre pour lequel personne ne distribue le logiciel, les organisations s'en servent habituellement à cinq fins : services Web et de fichiers, suite bureautique, application logicielle spécialisée, logiciel personnalisé à des fins internes et logiciel personnalisé qui sera utilisé par d'autres services de la même organisation.

Le [Guide de l'open source](http://www.open-source-guide.com/) de Smile énumère actuellement plus de 350 solutions professionnelles de LL avec examens et évaluations.

#### Logiciel côté serveur

Surtout dans Internet, les LL sont depuis longtemps une pierre angulaire du logiciel serveur. Les LL de serveur Web comme Apache et Nginx exploitent plus de 65 % des sites actifs dans Internet selon l'[enquête sur les serveurs Web de février 2017 de Netcraft](https://news.netcraft.com/archives/2017/02/27/february-2017-web-server-survey.html). Les serveurs libres de bases de données MySQL et MariaDB sont très populaires, et le LL Tomcat occupe la majorité du marché des serveurs d'applications Java. ([source](https://blog.jelastic.com/2016/04/14/software-stacks-market-share-first-quarter-of-2016/))

Les organisations du secteur public déploient des LL pour les serveurs aussi rapidement que les organisations du secteur privé. Par exemple, le site Web principal du gouvernement du Canada à [Canada.ca](https://www.canada.ca) utilise le serveur Web libre Apache. Le Conseil national de recherches du Canada (CNRC) utilise Apache, MySQL et l'outil d'authentification OpenLDAP pour les publications électroniques. En fait, dans l'ensemble, les logiciels côté serveur demeurent la principale utilisation des LL au sein des organisations du secteur public.

#### Suite bureautique sur la productivité

Comparativement à l'utilisation des LL côté serveur, l'utilisation institutionnelle et opérationnelle des logiciels de bureau libres est un phénomène relativement nouveau. Toutefois, un document de recherche publié en 2008 intitulé [The Migration of Public Administrations Towards Open Source Desktop Software](https://www.igi-global.com/chapter/migration-public-administrations-towards-open/10088) montre que ce domaine des LL a suscité un intérêt accru ces dernières années, surtout dans le secteur public. Par exemple, les administrateurs publics de la Ville de Paris ont décidé de transférer 17 000 ordinateurs de bureau exécutant Microsoft Office et Microsoft Internet Explorer vers OpenOffice.org et Mozilla Firefox. Selon un [article publié dans le site Web de l'Interoperability Solutions for Public Administrations de l'Union européenne](https://joinup.ec.europa.eu/news/french-gendarmerie-open-sou), la Gendarmerie nationale française a commencé par utiliser OpenOffice sur la totalité de ses 90 000 ordinateurs personnels. En 2006, elle a installé le navigateur Web Mozilla Firefox et le client de courriel Mozilla Thunderbird sur tous ses ordinateurs personnels, puis d'autres outils de bureau libres, y compris le logiciel de manipulation d'images Gimp et l'application multimédia VLC. En 2008, elle a mis en œuvre Ubuntu Linux sur 5000 postes de travail; aujourd'hui, elle possède 72 000 postes de travail exécutant Ubuntu Linux. Bien que LibreOffice et Firefox soient parmi les applications de bureautique libres les plus courantes, un large éventail d'applications sont disponibles.

#### Logiciels spécialisés

De nombreux services publics et applications libres desservent un secteur d'activité particulier ou d'autres intérêts. Dans le cas des logiciels hautement spécialisés, il n'existe peut-être même pas de solutions de rechange à une application libre particulière si aucun marché suffisamment important n'a été développé pour attirer des fournisseurs de produits exclusifs. Dans bien des cas, les chercheurs universitaires publient directement leurs initiatives de recherche spécialisées sous la forme de bibliothèques et d'applications de LL.

À titre d'exemple, dans le domaine spécialisé de la géomatique, [MapServer](http://mapserver.org/) est un LL couramment utilisé pour afficher des cartes spatiales dynamiques par l'entremise d'Internet. MapServer a été mis au point à l'Université du Minnesota. Publié en vertu de la licence de LL, il est maintenant administré par l'Open Source Geospatial Foundation (OSGeo), et il est utilisé et appuyé par une collectivité mondiale de développeurs.

#### Modification interne

Toutes les [licences](Annexe_légale.md#licences) de LL accordent aux utilisateurs de vastes droits pour modifier le logiciel. Étant donné que seule la distribution peut déclencher des obligations réciproques, il est possible de modifier les logiciels à des fins internes sans déclencher d'autres obligations juridiques. Le contexte juridique de la modification d'un LL et de son utilisation interne est le même que celui de son utilisation interne sans modification.

Cependant, bien qu'il n'y ait pas de différence juridique entre ces deux scénarios, certaines organisations et entreprises pourraient toujours souhaiter établir une politique différente pour le traitement des logiciels modifiés, comme les « Lignes directrices sur les LL du CNRC » (disponibles par l'entremise de GCpédia). Le suivi et le traitement des logiciels modifiés avec une plus grande prudence peuvent aider à veiller à ce qu'une organisation ou une entreprise ne distribue pas le logiciel par erreur ultérieurement (ce qui pourrait alors avoir d'autres conséquences juridiques).

#### Distribution interne

Le scénario d'« utilisation sans distribution » (c.‑à‑d. le contexte qui ne déclenche pas d'obligations en matière de licence réciproque) a une portée relativement vaste. En général, la distribution interne au sein d'une entreprise ou d'une organisation ne constitue pas un « transfert » ou une « distribution » de nature juridique, et elle ne comprend pas d'obligations en matière licence réciproque. Par exemple, la licence GPL considère la distribution comme étant « tout type de propagation qui permet à d'autres parties de faire ou de recevoir des copies ». Une société n'est qu'une seule partie juridique et elle peut faire des LL, les modifier et les distribuer à ses employés sans déclencher d'autres obligations.

Étant donné que les ministères distincts fonctionnent de façon semi-autonome, on peut appuyer que les différents ministères constituent des « parties » différentes. Toutefois, cette interprétation est peu probable. Une telle interprétation serait incompatible avec l'interprétation juridique générale selon laquelle le gouvernement fédéral ou un gouvernement provincial constitue une seule entité juridique. Un document de recherche de 2005 intitulé [Legal Issues for the Use of Free and Open Source Software in Government](http://www.austlii.edu.au/au/journals/MelbULawRw/2005/13.html) démontre qu'Eben Moglen, avocat général de la FSF, qui encourage habituellement une interprétation forte et étendue de la distribution, considère que les « organisations du gouvernement fédéral peuvent partager des LL sans « distribution ».

Toutefois, la distribution entre des entités juridiques différentes du gouvernement fédéral et d'un gouvernement provincial, ou entre gouvernements provinciaux, constitue presque certainement une « distribution ».

### Avantages

L'une des principales caractéristiques des LL est que n'importe qui peut les distribuer librement. Par conséquent, la plupart des LL peuvent être téléchargées par l'entremise d'Internet sans frais, mais il y a certainement encore des dépenses d'entretien et de gestion. Pour les entreprises qui choisissent d'utiliser des LL, l'absence de droits de licence initiaux constitue un facteur crucial et attrayant pour prendre cette décision. En effet, cette décision peut réduire les dépenses de fonctionnement. Pour le secteur public, le coût est également important. En outre, d'autres avantages publics peuvent inciter le secteur public à utiliser des LL.

Les organisations modernes optent pour les LL pour mettre au point leurs logiciels. Parmi les avantages documentés par rapport aux logiciels mis au point par une poignée de développeurs, il y a la qualité des solutions générées par la diversité des idées et des collectivités qui se forment autour d'un défi commun. L'exposition de la problématique à d'autres organisations intéressées apporte également un capital humain supplémentaire pour relever les défis. Par exemple, le système d'exploitation libre Linux est le plus grand projet de développement au monde; des milliers de personnes contribuent à chaque publication. De nombreuses entreprises concurrentes contribuent à Linux et à d'autres LL, ce qui leur permet de tirer parti du travail d'une collectivité mondiale de développeurs de LL et de faire passer les développeurs d'un travail de faible valeur à un travail de grande valeur.

L'utilisation des LL permet de personnaliser les produits, fait progresser l'interopérabilité entre les outils grâce à l'utilisation de [normes ouvertes](2_Normes_ouvertes.md) et améliore la qualité globale du produit final. Voici d'autres avantages :

#### Évitement du verrouillage

Lorsqu'une application logicielle exclusive est intégrée aux processus ou aux produits d'une organisation ou d'une entreprise, cette organisation devient dépendante de ce fournisseur de logiciels, ou « verrouillé », pour les nouvelles fonctionnalités, les corrections de bogues et, dans bien des cas, le soutien du produit. Si un fournisseur n'est pas disposé à mettre en œuvre une nouvelle fonction, il faudra peut-être opter pour une solution de rechange, souvent à un coût considérable. Lorsqu'un fournisseur tarde à fournir des correctifs de bogues ou du soutien, cela peut avoir une incidence négative sur vos propres échéances et peut aussi poser un risque pour la sécurité.

Les LL comportent un avantage en ce sens qu'il crée [marchés ouverts](5_Marchés_ouverts.md) pour les fournisseurs de tous les types de soutien. Toute entreprise de soutien ayant des compétences suffisantes en développement de logiciels peut ajouter de nouvelles fonctions et corriger des bogues dans le logiciel. Les utilisateurs de LL peuvent aussi passer à un fournisseur de soutien différent chaque fois qu'une entreprise existante ne répond plus à leurs besoins ou ne respectent plus leurs échéances.

La souplesse de l'utilisation des LL oblige le gouvernement du Canada à répondre aux besoins des utilisateurs en modifiant ou en créant de nouveaux LL. Les LL sont particulièrement adaptées au prototypage et à l'expérimentation rapides. Le processus de mise à l'essai génère des coûts minimes, et le processus favorise le recensement et l'élimination des défauts non reconnus par l'équipe de développement d'origine.

#### Soutien de l'économie et des collectivités locales

Selon la dynamique de l'industrie du logiciel à un endroit donné, l'utilisation des LL pourrait mieux appuyer les entreprises locales de la région. Étant donné que les LL sont disponibles, distribuables et modifiables, un plus grand nombre de petites entreprises offrant des services de soutien peuvent offrir des services commerciaux. Au lieu d'un seul fournisseur qui offre la garantie et le soutien technique, toute entreprise locale de la technologie de l'information (TI) compétente peut fournir ces services. Au lieu d'un seul fournisseur qui est le seul à pouvoir personnaliser les logiciels, une entreprise locale de consultation ou de développement de logiciels peut fournir des versions spécialisées du logiciel. Cette dynamique peut contribuer directement à la croissance économique canadienne.

Le code source accessible au public permet un examen continu et général par les pairs. Qu'il s'agisse simplement de publier le code terminé ou d'ouvrir le processus de développement, la pratique consistant à étendre le processus d'examen et de mise à l'essai à un public plus large au-delà de l'équipe de développement assure une fiabilité et une sécurité accrues des logiciels. Le fait de se développer dans un environnement libre permet aussi à d'autres opinions d'éclairer l'orientation d'un produit afin de maximiser son utilité pour la collectivité qu'il dessert.

Le code créé par une administration publique appartient au public. En mettant au point des LL, nous favorisons le développement d'un espace commun plus vaste dans lequel les villes, les états, les entreprises et les individus peuvent mener des activités. Cela crée une véritable valeur économique en réduisant le fardeau du dédoublement des travaux similaires et en permettant au secteur privé de créer de nouvelles entreprises fondées sur le code développé par le gouvernement du Canada ou de s'en inspirer. Les LL sont reconnus mondialement comme un important catalyseur de l'innovation.

#### Coût

Le coût total de propriété de toute application logicielle comprend trois grandes catégories de dépenses : (1) les coûts initiaux d'octroi de licence et de mise en œuvre; (2) les coûts permanents d'entretien et de soutien; et (3) les coûts de mise à niveau ou de transition des logiciels.

Lorsqu'on utilise des LL, le coût de licence initial est nul (à l'exception des coûts internes d'évaluation du logiciel et d'octroi de licence). Une licence LL est toujours « libre » et accordée au monde entier, en ce sens qu'elle permet à tout le monde d'utiliser le logiciel sans frais exigibles. De plus, en raison du fait que les licences de LL donnent à chacun le droit de redistribuer le logiciel, presque tous les LL peuvent être téléchargés gratuitement par l'entremise d'Internet.

De plus, les coûts d'entretien permanent des LL sont souvent moins élevés. En ce qui concerne les logiciels exclusifs, le fournisseur et ses partenaires d'affaires sont souvent les seules entreprises capables d'offrir le soutien nécessaire (soit parce que la licence du logiciel accorde au fournisseur un contrat de soutien exclusif ou que le fournisseur est le seul à détenir l'expertise spécialisée ou la capacité d'examen ou d'utilisation du code source). Cela peut nuire à un appel d'offres concurrentiel et, dans certains cas, entraîner un mauvais soutien sans solution de rechange. En revanche, les LL permettent à quiconque d'installer, de réparer et d'appuyer autrement le logiciel. Cela favorise un appel d'offres plus concurrentiel pour les services de soutien entre les entreprises. En ce qui concerne les mises à niveau des logiciels, certains fournisseurs exclusifs exigent que les titulaires de licence achètent une nouvelle licence ou paient des frais de mise à niveau pour les nouvelles versions d'un logiciel. En revanche, pour les LL, aucune nouvelle licence n'est nécessaire pour commencer à utiliser la nouvelle version d'un logiciel.

La souplesse des LL permet de réagir rapidement à l'évolution des missions et des marchés, ainsi que de répondre rapidement aux besoins des utilisateurs connus et imprévus. Le fait d'être extensible dans les deux sens entraîne une réduction des risques des répercussions financières à long terme (et des licences potentiellement redondantes). Le soutien et la mise à jour des LL, contrairement aux utilisations plus lourdes des logiciels exclusifs, offrent un avantage réel sur le plan des coûts lorsque de multiples copies de logiciels sont requises ou lorsque le nombre d'utilisateurs augmente. Le coût total de propriété est partagé avec une collectivité, et non pas seulement par le gouvernement du Canada.

#### Sécurité

L'un des aspects les plus mal compris du modèle de développement des LL concerne les avantages qu'ils offrent en matière de sécurité. La sécurité des LL repose sur un code véritablement renforcé qui est mis à l'essai par un grand nombre d'examinateurs dans diverses circonstances. Linus Torvalds a simplement fait remarquer que « les belles paroles ne valent rien, mais montrez-moi plutôt le code ».

Lorsque vous utilisez des LL, le code source est publié ouvertement dans son intégralité. Il est donc difficile pour quiconque d'insérer subrepticement un code malveillant. Il permet également aux vérificateurs de la sécurité et aux chercheurs en sécurité d'inspecter le code pour y déceler des lacunes. Bien que la sécurité des logiciels soit une préoccupation pour toutes les entités, elle revêt une importance primordiale pour les gouvernements. Voilà pourquoi les organisations de défense et de sécurité nationale utilisent très souvent des LL. Le document de recherche de 2008 intitulé « [Open Source Technology and Policy](http://www.cambridge.org/gb/academic/subjects/computer-science/computing-and-society/open-source-technology-and-policy)», donne l'exemple de l'utilisation étendue des LL au sein du département de la Défense des États-Unis et de la National Security Agency et explique les avantages pour la sécurité :
> L'un des principaux facteurs de l'attrait des LL dans les applications de sécurité (et de sécurité nationale) est leur capacité de vérification. Il est évidemment plus difficile de dissimuler des choses dans du code source libre. Par ailleurs, les gouvernements peuvent avoir des raisons de se méfier du contenu des codes exclusif. Dans le contexte américain, le principal fournisseur exclusif est une société des États-Unis; on peut donc s'attendre du gouvernement qu'il travaille sur les mécanismes de divulgation avec le fournisseur. Il s'agit toutefois d'un scénario moins probable pour les entités détenues à l'étranger. Par exemple, est-ce que Microsoft est susceptible de divulguer un code exclusif au gouvernement vénézuélien parce que ce gouvernement veut examiner les applications Microsoft pour y déceler des pièges ou des lacunes de sécurité?

Par conséquent, lorsqu'un LL est bien élaboré et bien inspecté par des tiers, la sécurité est généralement améliorée. Il existe aussi certains risques pour la sécurité, dont il est question ci-dessous.

##### Recours au durcissement plutôt qu'à l'obscurcissement

Le logiciel libre s'appuie sur des pratiques exemplaires en matière de sécurité plutôt que sur l'obscurcissement. On croit souvent à tort que le fait de cacher un code aide à prévenir les attaques réussies. Comme le recommande l'organisme de normalisation du National Institute of Standards and Technology (NIST) : « La sécurité d'un système ne devrait pas dépendre du secret de la mise en œuvre ou de ses composantes. » Les pratiques de développement des LL reposent sur le durcissement (ou l'amélioration de la sécurité) du code en le mettant à la disposition des pairs pour qu'ils puissent le mettre à l'essai et tentent de le briser, puis en réglant les problèmes relevés.

Les LL ne sont pas toujours plus sûrs, mais, en théorie et en pratique, le modèle de sécurité des LL a démontré qu'ils favorisent une réaction plus rapide aux problèmes de sécurité et facilitent leur correction.

L'obscurcissement repose sur l'ignorance des agresseurs et cache les mauvaises pratiques de sécurité. Dans les cinq mois qui ont suivi la diffusion du code source de la version 6 d'InterBase, une porte dérobée à code fixe rigide qui existait depuis sept ans a été trouvée et réparée par la collectivité des LL.

##### Vaste examen par les pairs

Si l'on suppose que l'objectif soit de créer des logiciels sûrs, il est évident que la façon la plus facile de trouver des défauts dans un projet est de rendre tout le code du projet complètement transparent. Cette approche peut sembler contre-intuitive, si le but ultime correspond à d'autres choses que l'intégrité de la technologie.

En publiant ouvertement le code d'un projet et en le rendant facilement accessible par l'entremise d'Internet, la collectivité des pairs examinateurs s'étend à l'échelle mondiale. La collectivité trouvera rapidement des lacunes, et l'équipe de projet pourra prendre des mesures pour les corriger. Cette méthode permet aussi de recueillir les commentaires exceptionnellement étendus et approfondis des promoteurs qui ont besoin que le code soit aussi sûr que possible pour leur propre usage, et celui de la collectivité. Les propriétaires du projet et la collectivité profitent du partage des lacunes et des solutions.

Étant donné que le modèle de sécurité des LL est fondé sur les pratiques exemplaires reconnues par l'industrie et que le code actuel est largement disponible, les projets populaires sont grandement examinés, scrutés minutieusement, améliorés concrètement et durcis rapidement.

Seul un examen ouvert par des pairs peut rendre possibles des pratiques exemplaires en matière de sécurité. Voilà la base d'une approche fondée sur des données probantes dans n'importe quel domaine d'études. La technologie n'est pas différente et elle ne devrait pas être traitée comme si les fournisseurs étaient les seuls à détenir la vérité.

Si vous voulez en apprendre davantage sur la sécurité des LL, vous pouvez consulter le document [UK CESG OSS - Exploring the Risk (PDF)](https://www.ncsc.gov.uk/content/files/guidance_files/GPG%2038%20-%20Open%20Source%20Software%20%20-%20issue%201.1%20-%20Oct%2015%20-%20NCSC%20Web.pdf) et [la foire aux questions sur les LL du département de la Défense des États-Unis](http://dodcio.defense.gov/Open-Source-Software-FAQ/#OSS_and_Security.2FSoftware_Assurance.2FSystem_Assurance.2FSupply_Chain_Risk_Management).

#### Gains de productivité

L'ouverture des projets de LL et la disponibilité du code source permettent aux professionnels de la technologie de l'information (TI) d'être plus efficaces à bien des égards, notamment :

- en évaluant ou mettant rapidement à l'essai une plateforme à moindres coûts, et ayant le moins de retards administratifs possibles (p. ex., validation de principe);
- interagissant facilement avec la collectivité (développeurs, utilisateurs) pour poser des questions, proposer des améliorations et signaler les bogues;
- trouvant rapidement de l'information pertinente par l'entremise de nombreux canaux ouverts (p. ex., documentation, wiki, forum, système de suivi des bogues) et en l'améliorant au besoin;
- influençant la feuille de route du projet;
- tenant compte du fait qu'il existe une collectivité suffisamment large autour d'un logiciel libre, et que la solution finale souhaitable pourrait déjà exister en tant que paquet prêt pour la mise en production, ce qui réduirait les besoins en matière de développement, de soutien et de révision de la sécurité nécessaire avant le déploiement.

#### Compétences en matière de technologie de l'information (TI) et satisfaction au travail

Le [Rapport sur les emplois en LL 2018](https://www.linuxfoundation.org/publications/2018/06/open-source-jobs-report-2018/) a constaté que l'embauche de talents en LL est une priorité pour 80% des gestionnaires d'embauche. Il a également montré que seulement 3% des professionnels de LL disent que l'argent est la meilleure partie de leur travail. Un nombre croissant de professionnels de la TI ont des antécédents ou de l'expérience dans le domaine des services opérationnels pour de nombreuses raisons :

- les LL sont largement utilisés par les entreprises, du développement à la production, ce qui générant une forte demande de compétences;
- les contributions aux projets de LL permettent de faire partie d'un « réseau de confiance » public et de produire un curriculum vitæ précieux;
- certains préfèrent travailler avec les LL parce que cela améliore leur satisfaction au travail (voir l'avantage suivant);
- plus de possibilités d'apprentissage, car ils ont accès à toute la mécanique;
- le sentiment positif qu'ils prennent part à quelque chose de plus important qu'eux-mêmes grâce aux contributions aux LL (corrections de code source, rapports sur les bogues, mises à jour de la documentation, etc.);
- l'amélioration des compétences en matière de collaboration au fur et à mesure qu'ils s'engagent auprès d'autres développeurs du projet de LL (et qu'ils apprennent des personnes plus expérimentées).

Par conséquent, il devient de plus en plus nécessaire de s'ouvrir aux LL pour attirer des personnes talentueuses et des compétences novatrices en matière de TI.

#### Réduction de la responsabilité

Les licences de LL ne créent pas d'obligations sur la simple utilisation de logiciels et elles ne réduisent pas les risques juridiques accrus associés à l'utilisation de solutions exclusives. Le fait de ne pas accepter d'obligations pour la simple utilisation du logiciel fait partie de la définition de logiciel libre de la FSF et de la définition de logiciel à source ouverte de l'OSI. S'il existe une obligation découlant de l'utilisation du logiciel, celui-ci ne peut pas être considéré comme étant un LL.

### Risques et inconvénients

Bien entendu, une entreprise ou une organisation gouvernementale doit trouver un équilibre entre ces avantages et plusieurs inconvénients, comme une mauvaise connaissance des LL par l'utilisateur.

#### Moins de grande familiarité de la part des utilisateurs

La familiarité qu'a l'utilisateur avec les LL est souvent beaucoup plus faible que celle sur les logiciels exclusifs. Les logiciels exclusifs sont bien mis en œuvre dans les écoles (du moins au Canada), et de nombreuses personnes apprennent à utiliser des ordinateurs au moyen de logiciels exclusifs, en raison de leur préinstallation par des fournisseurs de matériel. Voilà pourquoi les LL peuvent exiger plus de formation et de soutien.

#### Sécurité

Étant donné que tout le code source des LL est publié ouvertement, n'importe qui - y compris les « pirates aux mauvaises intentions » - peut examiner le code pour y déceler des failles de sécurité. En particulier, les attaquants malveillants peuvent observer où les LL partagent la même conception, la même base de codes ou la même architecture que le logiciel qui peut avoir des vulnérabilités connues en matière de sécurité. ([source](https://www.igi-global.com/book/handbook-research-open-source-software/494))

Bien sûr, il faut tenir compte de ce désavantage par rapport aux avantages de sécurité mentionnés précédemment. Dans bien des cas, les pirates malveillants peuvent toujours avoir accès au code source des logiciels exclusifs lorsque les ententes de non-divulgation, les procédures éthiques de l'organisation ou les mécanismes de sécurité des fournisseurs font défaut. Ou ils peuvent démonter le système binaire exclusif et l'analyser pour cerner les défauts potentiels. Attendu que la sécurité des logiciels exclusifs dépend d'une tentative de maintien d'un déséquilibre d'information entre les « bienveillants » (analystes de la sécurité informatique) et les « malveillants » (pirates informatiques mal intentionnés), la sécurité des LL dépend d'un processus concurrentiel ouvert pour trouver et combler les failles de sécurité. Les modèles reposent sur des stratégies différentes, et chaque modèle comporte des risques particuliers qu'une organisation doit évaluer et prendre en considération.

#### Perte de contrôle sur la gestion des logiciels

La facilité et l'option sans frais du téléchargement des LL à partir d'Internet, et de leur installation instantanée, peuvent créer une proposition attrayante pour les employés qui souhaitent contourner les processus d'approvisionnement. Par conséquent, le personnel de la technologie de l'information (TI) peut perdre de vue les logiciels qui fonctionnent sur les postes de travail des employés, ce qui rend plus difficile la gestion de la sécurité des systèmes.

Il en va de même pour les codes sources modifiés ou mélangés sans surveillance adéquate, y compris par l'entremise d'un entrepreneur externe, des risques juridiques peuvent survenir en matière de propriété intellectuelle (droit d'auteur et licence). Il est important de veiller au respect de la Loi sur le droit d'auteur et à ce que ces activités soient intégrées et planifiées dans le cycle de développement de logiciels.

#### Expertise interne

Ceux qui envisagent d'utiliser et de mettre au point des LL « internes » doivent veiller à ce qu'ils aient le bon niveau d'expertise pour la gérer efficacement. Le personnel est habituellement formé à l'utilisation de logiciels exclusifs, de sorte que l'introduction de nouvelles solutions libre peut nécessiter un recyclage.

#### Disponibilité des fournisseurs

Les grands intégrateurs de systèmes peuvent être réticents à proposer des solutions libres qui peuvent générer moins de revenus et ne pas être harmonisés avec leurs produits ou leurs compétences.

#### Taux de changement

Certains projets de logiciel libre évoluent rapidement avec de courts cycles de publication, ce qui peut exiger plus de travail pour déployer les mises à jour aux utilisateurs. D'un autre côté, certains projets peuvent avoir un taux de changement très lent en raison d'un manque de participation de la collectivité (utilisateurs, fournisseurs, etc.). C'est pourquoi il est important d'évaluer soigneusement le niveau d'activité d'une collectivité donnée si nous envisageons de nous y fier d'une certaine façon.

### Pratiques exemplaires pour l'utilisation de logiciels libres

#### Évaluation et acquisition de logiciels

##### Évaluation des caractéristiques des logiciels

En général, les mêmes facteurs qui s'appliquent à l'évaluation de l'ensemble de caractéristiques et de la maturité de logiciels exclusifs s'appliquent également aux LL. Les facteurs suivants méritent d'être pris en considération lors de l'évaluation des LL :

- **Collectivité** Une forte collectivité d'utilisateurs participant à un projet permet aux gens de répondre aux questions, de procéder à la mise à l'essai des logiciels, de signaler les bogues, de suggérer des améliorations et de susciter un intérêt général pour les logiciels.
- **Activité de publication** Une forte collectivité de développeurs ayant des antécédents de publication et une participation continue tend à démontrer que les correctifs et les améliorations aux logiciels se poursuivront à l'avenir.
- **Longévité** La longévité, mesurée en fonction de l'âge du produit et du nombre de versions publiées, indique la stabilité et les chances de survie d'un projet.
- **Licence** Le logiciel est disponible pour une réutilisation en vertu d'une licence de LL, et le code se trouve dans un dépôt de codes communs. La licence d'un projet peut avoir une incidence sur le niveau de risque juridique que vous devez assumer (voir [Gestion des risques juridiques](Annexe_légale.md#gestion-des-risques-juridique)).
- **Disponibilité du soutien** Les considérations de soutien comprennent le soutien aux utilisateurs (c.-à-d. la disponibilité de l'aide pour l'installation et l'utilisation) et la maintenance (c.-à-d. la résolution des problèmes dans le logiciel). Le soutien des LL peut être fourni par la collectivité ou les entreprises de services de soutien rémunérés.
- **Documentation** La documentation de l'utilisateur fournit des renseignements importants pour aider les utilisateurs à installer le logiciel et à utiliser ses fonctions. La documentation technique fournit les exigences et les instructions pour l'installation, le développement, le déploiement et la configuration du logiciel.
- **Sécurité** Bien que le code des LL soit vérifiable, cela ne signifie pas nécessairement qu'il est sécurisé. La qualité du code et le temps de réponse habituel pour corriger les lacunes de sécurité aident à indiquer le niveau de sécurité du logiciel.
- **Fonctionnalité** Les besoins particuliers en matière de fonctionnalité dépendent de l'analyse de rentabilisation du logiciel, et ils doivent être évalués au cas par cas.
- **Intégration** Lorsqu'un logiciel interagit avec d'autres logiciels, ou avec des formats de données particuliers, la compatibilité et la capacité d'intégrer le logiciel et les données ensemble devient une considération primordiale.

Le site Web [OpenHub](https://www.openhub.net/) fournit de nombreuses mesures utiles pour aider à l'évaluation des LL. Par exemple, il énumère les vulnérabilités en matière de sécurité du projet, le nombre de collaborateurs et la fréquence des mises à jour des logiciels.

##### Comparaison des logiciels libres et exclusifs

Lorsqu'il s'agit de prendre des décisions en matière d'acquisition de logiciels, il est pratique courante d'évaluer les LL sur un pied d'égalité avec les logiciels exclusifs. À partir d'une liste des exigences opérationnelles, une organisation gouvernementale ou une entreprise peut évaluer dans quelle mesure l'ensemble de fonctions d'un LL correspond aux exigences et calculer le coût global par fonction pendant la durée de vie utile du logiciel.

Ce type d'évaluation constitue un point de départ utile. Cependant, plusieurs personnes interrogées ont fait état d'expériences difficiles dans l'établissement de comparaisons « entre pommes » entre les LL et les logiciels exclusifs. Bien qu'une évaluation du coût total de la propriété soit possible pour les deux, il est difficile de tenir compte de facteurs comme les avantages pour le public (p. ex., l'efficacité économique globale, le soutien aux entreprises locales, etc.).

En plus de cette difficulté, les processus établis d'acquisition de logiciels et d'appel d'offres de services sont parfois adaptés aux solutions exclusives. Les processus ne sont pas toujours assez souples pour évaluer et traiter adéquatement les solutions libres. Par exemple, un processus d'approvisionnement peut d'abord comprendre un appel d'offres pour le contrat de licence initial. Dans ce cas-ci, les entreprises fondées sur des LL ne sont pas susceptibles de soumissionner, car elles n'ont pas de licences à vendre. Lorsque la prochaine étape d'un processus d'approvisionnement consisterait à lancer un appel d'offres pour des services de soutien, les entreprises de soutien basées sur les LL pourraient déjà être écartées. Les fournisseurs de logiciels exclusifs interdisent souvent à quiconque d'assurer l'entretien ou le soutien de leur produit, ce qui empêche les entreprises fondées sur des LL de participer à l'ensemble du processus. ([source](http://www.cbc.ca/news/technology/an-open-door-for-open-source-1.810739))

Par conséquent, bien qu'une comparaison directe entre toutes les solutions possibles - libres et exclusives - soit une pratique utile, il peut également être nécessaire pour les entreprises et les organisations de revoir les procédures et processus existants afin de veiller à ce qu'ils tiennent compte adéquatement des deux catégories de logiciels.

#### Soutien

La vérification et la mise en œuvre d'une solution LL représente généralement la partie la plus facile. En ce qui a trait à l'infrastructure LL critique, le vrai défi se pose en matière de maintenance et de soutien. Le risque d'utiliser un logiciel sans garantie ni responsabilité de la part du fournisseur en est un qui est important. Avec les LL, il existe toute une gamme de modèles de soutien à partir desquels on peut choisir, et le bon choix variera en fonction de nos besoins opérationnels. Ces options ne s'excluent pas mutuellement, et nous pouvons constater, par exemple, que notre organisation est mieux desservie en utilisant divers degrés de chacune des options qui figurent ci-dessous. Quels que soient nos besoins, la meilleure façon de tirer le meilleur parti des LL, tout en atténuant les risques, est de veiller à ce que notre organisation adopte un modèle de soutien solide et stratégique, et que nous l'utilisions de la façon la plus optimale possible.

- Élaborer un plan de soutien dans le cadre du processus d'adoption du produit.
- Déterminer les compétences et les besoins en matière de soutien en fonction des compétences/ressources de l'organisation, des caractéristiques des composantes LL, et des caractéristiques générales de l'application.
- Déterminer comment les composantes OSS seront gardées à jour avec les correctifs de bogues et de vulnérabilités.

#### Autosuffisance

Les avantages de compter sur nos équipes informatiques internes et sur notre personnel pour appuyer les LL que nous déployons sont les suivants :

- nous avons le code source, nous avons le contrôle;
- tirer parti de nos ressources existantes;
- la possibilité d'embaucher des spécialistes pour effectuer l'entretien interne des produits;
- au besoin, nous pouvons trouver du matériel pédagogique et de la formation pour affiner nos compétences;
- nous devons désigner les propriétaires de code afin qu'ils soient responsables des divers codes à source ouverte qui ont été mis en œuvre. Ces propriétaires seraient responsables de ce qui suit :
  - garder une longueur d'avance sur les nouvelles mises à jour et fonctionnalités;
  - être vigilants et proactifs en ce qui concerne les notifications de sécurité;
  - assurer la vérification interne des logiciels par rapport aux processus opérationnels afin de s'assurer de leur pertinence;
  - interagir avec les collectivités pour demander des fonctionnalités et signaler des bogues;
  - transmettre la connaissance du produit aux parties prenantes.

Le fait de procéder à une mise en œuvre libre pourrait présenter certains défis immédiats, tels :

- viable que si nous avons suffisamment d'expertise à l'interne;
- documentation inappropriée;
- la lenteur de la réaction des collectivités;
- manque de preuve de concepts pertinents à votre domaine.

De plus, malgré les avantages de l'autosuffisance, du moins sur papier, le présent modèle ne suffit généralement pas si on souhaite obtenir la fiabilité à laquelle nous nous attendons de la part de nos systèmes essentiels.

##### Collectivité du gouvernement du Canada

La collectivité du gouvernement du Canada offrira initialement le même type de soutien que celui qui est décrit ci-dessous, en ce qui a trait au soutien accordé à la collectivité internationale. La différence est que dans le cas de ces collectivités, il est possible d'introduire d'autres niveaux de soutien - par exemple, si un produit a été développé à l'aide du LL par un ministère homologue, un protocole d'entente pourrait être mis en place où le soutien de deuxième ou troisième ligne pourrait être fourni par le ministère homologue, ou son expert en la matière pourrait être mis temporairement à la disposition de notre ministère et vice versa, si nous sommes propriétaires d'une solution spécifique au LL. La collectivité du gouvernement du Canada présente de nombreuses possibilités en matière de soutien, de partage et de réutilisation des codes d'élaboration en collaboration, que nous devons explorer cette option davantage, et en discuter avec l'ensemble du gouvernement du Canada.

##### Collectivité internationale

Le soutien de la collectivité offre l'avantage de conserver la distribution originale du logiciel. Il ne s'agit pas d'une approche de soutien direct. Il s'agit d'une approche de recherche où l'on chercherait à obtenir de l'aide et des conseils en posant des questions et en décrivant la situation en ligne, puis en invitant la collectivité des développeurs et des utilisateurs du même produit ou projet LL à participer.

##### Vendeur

La majorité des principaux LL qu'une entreprise peut utiliser sont accompagnés d'une option de soutien commercial payant. Red Hat et Canonical, par exemple, offrent tous deux un soutien commercial pour leur distribution de Linux.

L'embauche d'un tiers pour le soutien au niveau du code source peut mener à une dérivation de la distribution principale du logiciel par rapport à la collectivité/au fournisseur. La maintenance de la version bifurquée du logiciel exige que l'on déploie des efforts, une expertise technique et des ressources supplémentaires. Par conséquent, il est prudent d'utiliser la version prise en charge par la collectivité. Il y a des entreprises qui fournissent des éditions intégrées des logiciels communautaires qu'elles prennent en charge, et ces éditions sont souvent accompagnées d'options en matière de soutien et de formation fondés sur un accord de niveau de service. Il y a également des organisations qui peuvent nous aider à bâtir l'infrastructure de soutien dont nous avons besoin à l'interne, ou même nous fournir cette équipe de soutien. Bien que ces options ne soient pas gratuites, il convient de mentionner que de nombreuses études ont confirmé les avantages financiers du LL dans un contexte commercial, même avec un soutien rémunéré. Le LL, en plus de l'assistance payée, ne dépassent pas le prix du logiciel payant, en plus de l'assistance payée. Il s'agit d'une simple question de mathématique. Lorsqu'on juxtapose les coûts de licence associés au soutien d'une infrastructure commerciale sophistiquée ou les coûts d'embauche associés à la création et au maintien d'une équipe de soutien interne, le rendement du capital investi est généralement considérable.

Comme le code source des LL est, par définition, librement disponible, cela signifie que nous n'avons pas à nous limiter à choisir entre les offres de soutien des entreprises qui fournissent des contrats de soutien. Nous pouvons être proactifs et répondre à vos besoins exacts en matière d'aide. En choisissant le bon fournisseur commercial comme partenaire architectural dans le cadre des efforts que nous déployons par rapport au développement entourant la source ouverte, nous pouvons obtenir à la fois la liberté et la flexibilité qu'offre l'adoption de LL, et la tranquillité d'esprit que procure le soutien accordé aux entreprises de qualité commerciale. La principale motivation de l'adoption du LL est d'avoir des choix multiples pour les solutions logicielles et une plus grande compétition de la part des fournisseurs de services, mais sans qu'il n'y ait de blocage ou de perte de propriété intellectuelle (PI). Si un modèle de soutien crée l'immobilisation ou la perte d'une PI sous le nom de LL, l'objectif principal de l'option de LL est annulé.

##### Mélange des modèles de soutien

En combinant les modèles, nous pouvons tirer le meilleur parti de chacun d'eux lorsque le soutien commercial vient compléter le soutien interne, de même que celui de la ou des collectivités.

Le mélange de modèles évoluera au fil du temps où une organisation commencera généralement par un soutien interne et perfectionnera certaines compétences internes, puis, en raison de la demande, le nombre de contrats de soutien de tiers augmentera au besoin, habituellement en ce qui a trait aux applications les plus exigeantes en ressources.

#### Formation

Selon le contexte, il est prudent d'affecter des ressources appropriées à la formation et à l'aide aux LL. Même si cela n'est peut-être pas nécessaire lorsqu'il s'agit simplement d'installer un nouveau LL sur un serveur (où seul le personnel compétent est susceptible d'interagir avec lui), cet élément est particulièrement important quand il est question des logiciels de bureautique libres. Souvent, les utilisateurs sont plus habitués aux logiciels exclusifs, populaires depuis longtemps, et ils connaissent peut-être peu les LL. Les organisations qui ont opté pour les applications de bureau libres ont tiré plusieurs leçons utiles et pratiques exemplaires de leur décision. ([source](https://www.igi-global.com/chapter/migration-public-administrations-towards-open/10088))

##### Analyse et préparation

- Étudier et planifier les coûts et les analyses de rentabilisation de la migration
- Réaliser des études pilotes.

##### Migration

- Modérer le rythme de la migration, en évitant une approche de « big bang » (p. ex., favoriser d'abord l'adoption volontaire pour avoir des utilisateurs expérimentés qui peuvent ensuite aider leurs collègues).
- Prévoir une période de transition durant laquelle les utilisateurs ont accès aux logiciels existants et à l'alternative libre.
- Obtenir le soutien de la haute direction.
- Susciter une attitude positive chez les utilisateurs.

##### Fonctionnalité

- Les fonctionnalités générales sont souvent équivalentes dans les LL analogues, mais les ensembles de fonctions ne correspondent pas toujours parfaitement, ce qui peut engendrer des problèmes précis pour les utilisateurs.

#### Gestion des risques juridiques

Dans l'ensemble, il est peu probable qu'une licence de LL influe fortement sur la décision d'utiliser ou non des LL. Comme on l'a mentionné précédemment, une simple utilisation de LL déclenche peu d'obligations relatives aux licences. Plus important encore, les obligations réciproques en matière de licence ne s'appliquent pas. Dans ce contexte, seulement trois caractéristiques des licences de LL ont tendance à être très différentes des licences exclusives, et il faut s'y attarder : (1) l'absence de garantie; 2) l'avis de non-responsabilité et d'absence d'indemnisation; et (3) l'absence de clause de compétence législative ou de clause attributive de compétence.

Pour obtenir de plus amples détails sur la gestion des risques et d'autres questions juridiques, veuillez consulter l'[annexe A - Questions d'ordre juridique](Annexe_légale.md).

#### Interopérabilité et harmonisation des licences

L'interopérabilité des licences pose rarement des problèmes pour une simple utilisation de LL, à condition qu'il n'y ait pas de distribution du logiciel. Comme on l'a déjà mentionné, en général, les seules obligations en matière de licence que l'on doit accepter et respecter en cas de simple utilisation sont des avis d'exonération de garantie et de non-responsabilité. Même lorsque des logiciels provenant de sources multiples sont modifiés et combinés en vertu de licences multiples, ces avis ne sont jamais susceptibles d'entrer en conflit. Les avis n'imposent qu'une obligation passive, c'est-à-dire qu'ils ne vous obligent pas à prendre une mesure particulière ou à renoncer à une mesure précise. Le titulaire d'une licence n'a qu'à accepter le risque juridique imposé.

Bien que l'interopérabilité des licences ne soit pas une préoccupation pour l'utilisation des LL, le format et l'interopérabilité des données peuvent avoir une incidence sur les décisions d'utiliser ou non les LL. Pour évaluer l'interopérabilité des données, il est important de faire une analyse au cas par cas. Les logiciels exclusifs peuvent toujours mettre en œuvre des « normes libres » largement interopérables pour les données. De la même façon, les LL peuvent, dans certains cas, utiliser des normes spécialisées non publiées et non libres pour le stockage des données.

Toutefois, les tendances culturelles et la dynamique du modèle opérationnel des LL tendent à pousser les projets de LL vers l'utilisation de l'interopérabilité et des [normes ouvertes](2_Normes_ouvertes.md) pour la lecture, la rédaction et le stockage des données. En effet, même lorsque les LL ne mettent pas en œuvre une norme libre pour le partage de données, la disponibilité du code source offre toujours une « mise en œuvre libre » à tout le moins. Le code source est un exemple que n'importe qui d'autre peut mettre en œuvre la même fonctionnalité pour lire et écrire le format de données sous-jacent.

### Contribution aux logiciels libres

Voir [Logiciel libre - Contribution](4_Logiciel_libre_Contribution.md).

### Logiciels libres privilégiées

Les critères d'évaluation des LL sont définis ci-dessus dans la section [Évaluation et acquisition des logiciels](#Évaluation-et-acquisition-des-logiciels). Les LL doivent également appuyer l'utilisation des [normes ouvertes](2_Normes_ouvertes.md).

Pour tirer le maximum d'avantages économiques et en matière de qualité, il faut utiliser les LL de façon concertée et coordonnée. Le Conseil d'examen de l'architecture intégrée (CEAI) et l'Équipe du gouvernement ouvert du Secrétariat du Conseil du Trésor tiendront à jour une liste des LL présentement utilisés basé sur l'auto-identification, la gestion de portefeuille d'applications et les évaluations de solutions présentées par les ministères.

La liste des LL utilisés est actuellement accessible à partir du site l'[Échange de ressources ouvert](https://canada-ca.github.io/ore-ero/).

### Normes relatives au numérique du gouvernement du Canada

Les [Normes relatives au numérique du gouvernement du Canada](https://www.canada.ca/fr/gouvernement/fonctionpublique/modernisation/normes-numeriques-gouvernement-canada.html) incluent une norme pour utiliser des normes et des solutions ouvertes.

Le Comité d'examen de l'architecture intégrée (CEAI) GC se servira des [normes architecturales](https://canada-ca.github.io/digital-playbook-guide-numerique/views-vues/gc-earb-ceai/en/gc-earb.html) pour évaluer les investissements et les solutions en matière de numérique. Les normes architecturales relatives au numérique viennent compléter les normes relatives au numérique du gouvernement du Canada, en misant sur les pratiques exemplaires qui visent la planification architecturale et la conception. Sous [Architecture d'application](https://canada-ca.github.io/digital-playbook-guide-numerique/views-vues/gc-earb-ceai/fr/ceai-gc.html#architecture-dapplication) ils incluent une norme pour utiliser des normes ouvertes et des logiciels libres pour éviter le verrouillage lorsque des logiciels libres ou des normes ouvertes sont disponibles.
