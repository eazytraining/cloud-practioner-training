##### Memo Présentation des concepts du cloud: 


###### Qu'est ce que le cloud computing ?: 

Le cloud computing c’est le fait de consommer des ressources à la demande, en suivant l’un des 3 modèles: IAAS, PAAS, SAAS.

Les termes IAAS, PAAS et SAAS se rapportent tous à des modèles de services cloud, mais chacun offre des niveaux de gestion et de contrôle différents. Voici les différences principales :

1. IAAS (Infrastructure as a Service) : 
   - IAAS fournit une infrastructure informatique virtualisée via Internet.
   - Les fournisseurs d'IAAS offrent des ressources informatiques telles que des serveurs virtuels, du stockage et des réseaux.
   - Les utilisateurs gèrent et contrôlent les systèmes d'exploitation, les applications, les bases de données et d'autres éléments logiciels.
   - Exemples de fournisseurs : Amazon Web Services (AWS), Microsoft Azure, Google Compute Engine.

2. PAAS (Platform as a Service) :
   - PAAS offre une plateforme de développement et de déploiement d'applications via Internet.
   - Les fournisseurs de PAAS fournissent des outils et des environnements de développement, ainsi que des services de déploiement, de mise à l'échelle et de gestion.
   - Les utilisateurs se concentrent sur le développement et le déploiement d'applications sans se soucier de la gestion de l'infrastructure sous-jacente.
   - Exemples de fournisseurs : Google App Engine, Microsoft Azure App Service, Heroku.

3. SAAS (Software as a Service) :
   - SAAS fournit des applications logicielles hébergées et accessibles via Internet.
   - Les utilisateurs accèdent aux logiciels via un navigateur Web ou une interface de programmation.
   - Les fournisseurs de SAAS gèrent toute l'infrastructure, y compris les serveurs, le réseau, la maintenance et les mises à jour logicielles.
   - Les utilisateurs paient généralement un abonnement pour accéder au logiciel en fonction de l'utilisation.
   - Exemples de fournisseurs : Salesforce, Google Workspace, Microsoft Office 365.

En résumé, IAAS fournit une infrastructure de base, PAAS offre une plateforme de développement et de déploiement d'applications, tandis que SAAS fournit des logiciels prêts à l'emploi accessibles via Internet. Les choix entre ces modèles dépendent des besoins spécifiques en termes de contrôle, de gestion et de développement des applications.

IAAS, PAAS et SAAS sont trois modèles de services cloud offerts par des fournisseurs comme Amazon Web Services (AWS). Voici quelques exemples spécifiques pour chaque modèle sur AWS :

1. **Infrastructure as a Service (IAAS)** :
   - Amazon EC2 (Elastic Compute Cloud) : C'est un service qui fournit des instances de serveurs virtuels à la demande. Les utilisateurs peuvent choisir différents types d'instances avec différentes capacités de calcul, de mémoire et de stockage.
   - Amazon S3 (Simple Storage Service) : Il s'agit d'un service de stockage en ligne offrant une grande capacité de stockage sécurisé, permettant aux utilisateurs de stocker et de récupérer des données à tout moment et depuis n'importe où sur le web.

2. **Platform as a Service (PAAS)** :
   - AWS Elastic Beanstalk : C'est un service qui simplifie le déploiement, la gestion et la mise à l'échelle des applications web développées avec des technologies courantes telles que Java, .NET, PHP, Node.js, Python, Ruby et Docker sur des serveurs compatibles avec AWS.
   - AWS RDS (Relational Database Service) : Il s'agit d'un service de base de données relationnelle géré qui simplifie le processus de configuration, d'exploitation et de mise à l'échelle de bases de données relationnelles dans le cloud. Il prend en charge plusieurs moteurs de base de données, y compris MySQL, PostgreSQL, Oracle, SQL Server et Amazon Aurora.

3. **Software as a Service (SAAS)** :
   - Amazon WorkMail : Il s'agit d'un service de messagerie et de calendrier géré qui permet aux entreprises de gérer leurs e-mails, contacts et calendriers en utilisant le client de messagerie de leur choix.
   - Amazon Chime : C'est un service de communication unifié qui offre la messagerie instantanée, les appels audio et vidéo, les réunions en ligne et le partage d'écran, le tout dans une seule application.

Ces exemples illustrent comment AWS fournit des services dans les trois modèles IAAS, PAAS et SAAS pour répondre aux besoins variés des entreprises en matière d'informatique en nuage.

###### Six Avantages du Cloud Computing:

1. Échangez des dépenses en capital contre les charges variables
2. Beneficiez d’énormes économies d’échelle.
3. Eliminer les reflexions sur vos besoins en capacités.
4. Augmenter votre rapidité et agilité.
5. Arretez de dépenser de l’argent pour gérer et entretenir des data centers.
6. Passez à l’international en quelques minutes

###### Qu'est-ce qu'Amazon Web Services ?

AWS est donc une plateforme cloud sécurisée contenant plus de 165 services.
Les services sont repartis en categories et dépendant de votre métier (service métiers).
Pour acceder au cloud AWS, on peut soit utiliser la 
   1. Console de management AWS en interface web ou applivation mobile
   2. En ligne de comme à l’aide de l’interface AWS CLI
   3. Ou alors grace aux outils de développement SDK permettant d’interagir avec AWS (python, java, php…). Cela permet au developpeur de faire des applications pouvant interagir avec AWS.

###### AWS Cloud Adoption Framework (CAF)

Afin de faciliter l’utilisation et d’optimiser le fonctionnement des ressources du Cloud AWS, AWS a mis sur pied un ensemble de bonnes pratiques à utiliser pour migrer sereinement son infrastructure ou ses services vers le Cloud.
Ces bonnes pratiques sont appelées par le sigle CAF ( AWS Cloud Adoption Framework).
   1. Business perspective : Il s’agit ici de bien vérifier et de se rassurer que le fait de vouloir aller vers le Cloud s’aligne avec notre politique Business
   2. People Perspective : Vérifier quelles sont les compétences dont auront besoin les employés pour passer vers le Cloud
   3. Governance perspective : Est-ce que le fait de passer vers le Cloud s’aligne en tout point avec nos besoins de gouvernances IT définies par la DSI
   4. Platform Perspectives : Quels seront les outils nécessaires pour optimiser nos services sur le cloud AWS
   5. Security Platform : Comment va être définie et implémentée le niveau de sécurité, de gouvernance et de risques pour le Cloud
   6. Operations Perspectives : Comment va-t-on maintenir notre infrastructure sur AWS.


##### Memo Tarification dans le Cloud: 

###### Principes de base de la tarification AWS

Il existe trois facteurs fondamentaux de coût avec AWS : 
   1. le calcul, 
   2. le stockage 
   3. et le transfert de données sortantes. Ces caractéristiques varient quelque peu, selon le produit AWS et le modèle de tarification que vous choisissez.
    
Dans la plupart des cas, il n'y a pas de frais pour le transfert de données entrantes ou pour le transfert de données entre d'autres services AWS au sein de la même région. Il existe quelques exceptions, alors assurez-vous de vérifier les taux de transfert de données avant de commencer à utiliser le service AWS.
   
Le transfert de données sortantes est agrégé entre les services, puis facturé au taux de transfert de données sortantes. Ces frais apparaissent sur le relevé mensuel comme AWS Data Transfer Out.

En résumé, alors que le nombre et les types de services offerts par AWS ont considérablement augmenté, sa philosophie en matière de tarification n'a pas changé. À la fin de chaque mois, vous ne payez que ce que vous utilisez et vous pouvez commencer ou arrêter d'utiliser un produit à tout moment. Aucun contrat à long terme n'est requis.
   
La meilleure façon d'estimer les coûts consiste 
   1. à examiner les caractéristiques fondamentales de chaque service AWS, 
   2. à estimer votre utilisation pour chaque caractéristique, 
   3. puis à mapper cette utilisation sur les prix publiés sur le site Web. Vous pouvez utiliser AWS Pricing Calculator pour estimer les couts en fonctions de vos caracteristiques de fonctionnement;
La stratégie de tarification des services vous offre une grande flexibilité pour choisir les services dont vous avez besoin pour chaque projet et pour ne payer que ce que vous utilisez.
   
Il existe un certain nombre de services AWS gratuits, notamment : Amazon VPC, Elastic Beanstalk, AWS CloudFormation, IAM, Automatic Scaling, AWS OpsWorks, et Consolidated Billing
Alors que les services eux-mêmes sont gratuits, les ressources qu'ils fournissent ne le sont pas. De plus, il n'y a aucun frais pour les données entrantes ou le transfert de données entre les services au sein de la même **région** ; cependant, les coûts de transfert de données sortantes sont échelonnés.

###### AWS Organizations: 

reference: 
    https://docs.aws.amazon.com/fr_fr/organizations/latest/userguide/orgs_introduction.html
    
AWS Organizations est un service de gestion de comptes qui vous permet de consolider plusieurs Comptes AWS en une organisation que vous créez et gérez de façon centralisée. AWS Organizations inclut toutes les fonctions de **facturation consolidée** et de gestion de comptes, qui vous permettent de mieux répondre aux besoins budgétaires, de sécurité et de conformité de votre entreprise. En tant qu'administrateur d'une organisation, vous pouvez créer des comptes dans votre organisation et inviter des comptes existants à rejoindre l'organisation.

reference: 
    https://docs.aws.amazon.com/fr_fr/awsaccountbilling/latest/aboutv2/con-bill-blended-rates.html

La **facturation consolidée** est une fonctionnalité de facturation dans AWS Organizations pour consolider le paiement de plusieurs comptes AWS. La facturation consolidée fournit :
   - Une facture pour plusieurs comptes.
   - La possibilité de suivre facilement les frais de chaque compte.
   - La possibilité de réduire les frais en raison des remises sur les prix de volume de l'utilisation combinée.
A l'aide de la facturation consolidée, bénéficier d'avantages à plusieurs niveaux.

###### Total Cost of Ownership : 

Lorsque vous souhaitez créer un système d’exploitation, il y’a des choses que vous allez devoir acheter (payer les machine, louer l’espace, employer du personnel …) permettant de mettre en place votre solution de facon traditionnelle, contrairement à Amazon où vous ne payez que ce que vous consommez. le cout total de mise en place de cette solution ici est donc appelée TCO (Total Cost Ownership).

Le TCO : c’est le cout total incluant dépenses directes et indirectes nécessaires pour la mise en place de notre infrastructure. AWS propose plusieurs calculateurs de couts permettant d’obtenir ce TCO tels que : AWS Simple Montly Calculator ; AWS TCO Calculator

Dans l'environnement cloud, le coût total de possession est utilisé pour comparer les coûts d'exécution d'un environnement d'infrastructure complet pour une charge de travail spécifique dans une installation sur site ou en colocation, à la même charge de travail s'exécutant sur une infrastructure basée sur le cloud. Cette comparaison est effectuée à des fins de budgétisation ou pour établir une analyse de rentabilisation pour les décisions commerciales concernant la solution de déploiement optimale.

Qu’est ce qui entre dans le TCO :
   1. l’achat des servers
   2. L’achat du stockage
   3. Le cout de mise en place du réséau
   4. Le cout de la main doeuvre des IT admin

En résumé, le coût total de possession est un outil précieux qui peut être utilisé pour comprendre et comparer les coûts associés aux différents déploiements. AWS fournit l'AWS Simple Monthly Calculator et le TCO Calculator pour vous aider dans les calculs nécessaires pour estimer les économies de coûts.

Utilisez le calculateur mensuel simple AWS pour :
Estimer les coûts mensuels
Identifier les opportunités de réduire les coûts mensuels, et
Utiliser des modèles pour comparer les services et les modèles de déploiement

Utilisez le calculateur du coût total de possession pour :
Analysez des rapports détaillés qui montrent une comparaison du coût total de possession sur 3 ans par catégories de coûts
Les rapports qui sont appropriés pour être inclus dans les présentations exécutives, et
La capacité de modifier les hypothèses pour les besoins de l'entreprise

##### Memo Présentation de l’architecture mondiale de AWS:


###### Architecture mondiale de AWS (Datacenters, Region, Zone de disponibilité, Emplacements peripheriques):

**AWS** organise ses datacenter de façon particulière, il les regroupe en régions ; les **régions** représentent un endroit dans le monde où Amazon a implanté ses datacenters. Dans chaque **région** on a au moins deux **zones de disponibilité** qui sont constituée en fait de datacenter,

Dans une zone on retrouve plusieurs datacenters, par exemple si on a une **région** qui se trouve en Californie, dans cette ville, on aura plusieurs **zones de disponibilité** contenant à leur tour plusieurs datacenter chacune. Tous les datacenter d’une même zone de disponibilité sont reliés par des liaisons fibre  extrêmement puissantes facilitant la communication entre les datacenter d’une même zone de dispo

Il est également possible de répliquer ses données dans une autre zone de disponibilité de la même région. 
Les **régions** contiennent les **zones de disponibilité** qui contiennent à leur tour les datacenter composés de serveurs qui hébergeront les applications des clients.

L'infrastructure du cloud AWS est construite autour de **régions** et de **zones de disponibilité**.

Une **région** AWS est un emplacement géographique physique dans le monde où nous avons plusieurs **zones de disponibilité**. Pour atteindre la tolérance aux pannes et la stabilité, les **régions** sont isolées les unes des autres. Les ressources d'une **région** ne sont pas automatiquement répliquées dans d'autres **régions**. Chaque **région** AWS contient au moins deux **zones de disponibilité**. AWS compte 18 **régions** dans le monde.

Lorsque vous stockez des données dans une **région** spécifique, elles ne sont pas répliquées en dehors de cette région. AWS ne déplace jamais vos données hors de la **région** dans laquelle vous les avez placées. Il est de votre responsabilité de répliquer les données entre les **régions**, si les besoins de votre entreprise l'exigent. AWS fournit des informations sur le pays et, le cas échéant, l'état où réside chaque région. Vous êtes responsable de la sélection de la **région** dans laquelle stocker les données, en fonction de vos exigences de conformité et de latence du réseau. Lorsque vous distribuez des applications sur plusieurs **zones de disponibilité**, tenez compte des exigences de confidentialité et de conformité dépendant de l'emplacement, telles que la directive européenne sur la confidentialité des données. Lors de la sélection d'une région, il est également important de considérer quelle **région** vous aidera à optimiser la latence tout en minimisant les coûts et en respectant les exigences réglementaires que vous pourriez avoir.
 
Approfondissons ce point. Si vous utilisez des services de cloud computing, vous pouvez facilement déployer votre application dans plusieurs **régions**. Par exemple, vous pouvez avoir une application dans une **région** la plus proche de votre siège, comme San Diego, puis avoir également une application déployable dans une **région** de la côte est. Disons que votre plus grande clientèle se situe en Virginie. En quelques clics, vous pouvez facilement déployer dans la **région** Est des États-Unis pour offrir une meilleure expérience à vos clients qui s'y trouvent. Vous minimiserez la latence et augmenterez l'agilité de votre organisation en quelques minutes et à un coût minimal.

**Edge Locations** : Zones virtuelles ou datacenters temporaires qu’on déploie dans une zone n’ayant pas de datacenter AWS pour couvrir un besoin ponctuel.
Les edges location permettent d’avoir les services AWS au plus proche de nous là où il n’ya pas de zone de disponibilité.

###### Fonctionnalités de l'infrastructure AWS 

1. High Availability (Haute disponibilité): Accessible quand vous en avez besoin à tout moment
2. Fault Tolerance (Tolérance aux pannes): Capacité à résister à un certain nombre de défaillances tout en restant fonctionnel
3. Scalability (Evolutif): Capacité d'augmenter facilement la taille, la capacité et/ou la portée si nécessaire La croissance est (généralement) basée sur la demande
4. Elasticity (Elastique): Capacité de croître (évoluer) si nécessaire et de réduire la taille lorsque les ressources ne sont plus nécessaires

###### Scalabilité vs Élasticité en generale

La différence entre la scalabilité et l'élasticité réside dans leur nature et leur application dans le domaine de l'informatique.

1. **Scalabilité**:
   - La scalabilité se réfère à la capacité d'un système, d'une application ou d'une plateforme à gérer une augmentation de charge ou de volume de manière efficace et sans compromettre les performances.
   - Elle implique généralement la capacité à ajouter des ressources matérielles ou logicielles pour répondre à une augmentation de la demande, que ce soit en ajoutant plus de serveurs, en augmentant la capacité de stockage, ou en mettant à l'échelle le logiciel pour tirer parti de ressources supplémentaires.

2. **Élasticité**:
   - L'élasticité se réfère à la capacité d'un système à s'adapter dynamiquement à une variation de la charge de travail en allouant ou en libérant automatiquement des ressources selon les besoins.
   - Contrairement à la scalabilité qui peut impliquer des ajustements manuels ou prévus à l'avance, l'élasticité implique généralement une réponse automatique et en temps réel aux fluctuations de la demande.

En résumé, la scalabilité se concentre sur la capacité à gérer une augmentation de charge de manière prévisible et souvent planifiée, tandis que l'élasticité se concentre sur la capacité à s'adapter instantanément aux changements de charge de manière automatique et dynamique.

###### Scalabilité vs Élasticité dans le cas AWS

La différence entre la scalabilité et l'élasticité est souvent un sujet de confusion, surtout lorsqu'il s'agit de services cloud comme ceux proposés par AWS (Amazon Web Services). Voici quelques exemples de services AWS illustrant la scalabilité et l'élasticité :

1. Scalabilité :
   - Amazon EC2 (Elastic Compute Cloud) : Avec EC2, vous pouvez augmenter ou diminuer le nombre de machines virtuelles (instances) en fonction des besoins de votre application. Par exemple, si votre site web connaît une augmentation du trafic pendant les heures de pointe, vous pouvez augmenter le nombre d'instances EC2 pour gérer la charge supplémentaire.

2. Élasticité :
   - Amazon S3 (Simple Storage Service) : S3 est un service de stockage d'objets qui offre une capacité de stockage pratiquement illimitée. Il est élastique car il peut s'adapter automatiquement à la demande de stockage. Si vous avez besoin de stocker plus de données, S3 s'adapte en ajoutant automatiquement de l'espace de stockage sans nécessiter d'intervention manuelle de votre part.

3. Autoscaling :
   - AWS Elastic Beanstalk : Ce service permet de déployer et de gérer des applications web avec facilité. Elastic Beanstalk peut automatiquement ajuster la capacité de calcul en fonction de la charge de votre application. Par exemple, il peut ajouter des instances EC2 supplémentaires lorsque la demande augmente et les supprimer lorsque la demande diminue, assurant ainsi une utilisation efficace des ressources.

En résumé, la scalabilité concerne la capacité à augmenter ou diminuer les ressources en fonction des besoins, tandis que l'élasticité implique une adaptation automatique aux fluctuations de la demande, offrant ainsi une flexibilité sans nécessiter d'intervention manuelle. Les services AWS fournissent des outils et des fonctionnalités pour répondre à ces exigences, permettant aux utilisateurs de concevoir des architectures cloud robustes et efficaces.
    
###### role de l'ASG

Le service Auto Scaling Group (ASG) joue un rôle crucial dans le déploiement et la gestion d'applications sur les services de cloud computing tels qu'Amazon Web Services (AWS). Voici quelques-uns des principaux rôles du service Auto Scaling Group :

1. **Élasticité** : L'ASG ajuste automatiquement le nombre d'instances de votre application en fonction de la demande. Il peut augmenter ou diminuer le nombre d'instances en fonction de règles prédéfinies telles que la charge du CPU, la mémoire utilisée ou le trafic réseau.

2. **Gestion de la disponibilité** : En déployant plusieurs instances de votre application sur différentes zones de disponibilité, l'ASG garantit une meilleure disponibilité et résilience de votre application. En cas de défaillance d'une instance, l'ASG peut remplacer automatiquement cette instance défaillante.

3. **Optimisation des coûts** : En ajustant dynamiquement le nombre d'instances en fonction de la demande, l'ASG permet d'optimiser les coûts en évitant le surdimensionnement ou le sous-dimensionnement de l'infrastructure.

4. **Facilité de déploiement** : L'ASG facilite le déploiement et la mise à l'échelle des applications en automatisant de nombreuses tâches liées à la gestion des instances, ce qui permet aux développeurs de se concentrer davantage sur le développement de leur application plutôt que sur la gestion de l'infrastructure.

En résumé, le service Auto Scaling Group permet d'automatiser la gestion de l'évolutivité, de la disponibilité et des coûts des applications déployées sur le cloud, offrant ainsi une meilleure expérience utilisateur et une plus grande efficacité opérationnelle.
    
##### Memo Présentation des services AWS et des catégories de services

    Voici une liste des services AWS répartis par catégories :

###### Calcul


1. **Amazon EC2 (Elastic Compute Cloud)** :
   - Amazon EC2 permet de lancer des instances virtuelles dans le cloud, offrant une grande flexibilité et évolutivité pour exécuter des applications.

2. **Amazon EC2 Auto Scaling** :
   - Amazon EC2 Auto Scaling ajuste automatiquement le nombre d'instances EC2 en fonction de la demande, assurant une disponibilité constante et des coûts optimisés.

3. **AWS Lambda** :
   - AWS Lambda est un service de calcul sans serveur qui permet d'exécuter du code en réponse à des événements, sans avoir à gérer l'infrastructure sous-jacente.

4. **Amazon ECS (Elastic Container Service)** :
   - Amazon ECS est un service de gestion de conteneurs hautement évolutif qui permet de déployer et d'orchestrer des applications conteneurisées sur AWS.

5. **AWS Batch** :
   - AWS Batch permet d'exécuter facilement des charges de travail par lots à grande échelle sur AWS, en automatisant les tâches de calcul, de planification et de gestion des ressources.

6. **Amazon Elastic Beanstalk** :
   - Amazon Elastic Beanstalk simplifie le déploiement et la gestion d'applications web en automatisant l'approvisionnement des ressources sous-jacentes, comme les instances EC2 et les bases de données.


###### Stockage


1. **Amazon S3 (Simple Storage Service)** :
   - Amazon S3 est un service de stockage d'objets offrant une scalabilité, une disponibilité et une durabilité élevées pour stocker et récupérer des données.

2. **Amazon EBS (Elastic Block Store)** :
   - Amazon EBS fournit un stockage de blocs persistants pour une utilisation avec les instances EC2, offrant des performances fiables et une disponibilité élevée.

3. **Amazon EFS (Elastic File System)** :
   - Amazon EFS est un service de stockage de fichiers entièrement géré qui permet de créer des systèmes de fichiers partagés élastiques pour les instances EC2.

4. **AWS Storage Gateway** :
   - AWS Storage Gateway permet d'intégrer les solutions de stockage sur site avec le cloud AWS, offrant une extension sans interruption du stockage sur site vers le cloud.

5. **Amazon Glacier** :
   - Amazon Glacier est un service de stockage d'archives à bas coût et à long terme, idéal pour l'archivage et la sauvegarde de données peu fréquemment consultées.

6. **Amazon FSx** :
   - Amazon FSx offre des systèmes de fichiers entièrement gérés pour les charges de travail Windows et Lustre, offrant une haute performance, une fiabilité et une intégration facile avec d'autres services AWS.

###### Base de données


1. **Amazon RDS (Relational Database Service)** :
   - Amazon RDS est un service de base de données relationnelle entièrement géré qui prend en charge plusieurs moteurs de base de données, offrant évolutivité, disponibilité et performances.

2. **Amazon DynamoDB** :
   - Amazon DynamoDB est une base de données NoSQL entièrement gérée, offrant une latence faible, une scalabilité automatique et une haute disponibilité pour les applications web et mobiles.

3. **Amazon Redshift** :
   - Amazon Redshift est un service de data warehousing entièrement géré, conçu pour l'analyse de données à grande échelle, offrant des performances élevées et des capacités de requête complexes.

4. **Amazon DocumentDB** :
   - Amazon DocumentDB est un service de base de données de documents compatible avec MongoDB, offrant une scalabilité, une disponibilité et une performance élevées pour les charges de travail basées sur des documents.

5. **Amazon Neptune** :
   - Amazon Neptune est un service de base de données graphes entièrement géré, conçu pour stocker et naviguer dans des données hautement connectées à l'aide de modèles de graphe.

6. **Amazon ElastiCache** :
   - Amazon ElastiCache est un service de mise en cache entièrement géré qui prend en charge les moteurs de cache open source populaires, offrant des performances rapides et une scalabilité automatique pour les charges de travail de mise en cache.

###### Réseau et mise en réseau


1. **Amazon VPC (Virtual Private Cloud)** :
   - Amazon VPC permet de créer un réseau virtuel isolé dans le cloud AWS, offrant un contrôle complet sur l'environnement réseau virtuel, y compris la sélection de l'adresse IP, les tables de routage et les passerelles.

2. **Amazon Route 53** :
   - Amazon Route 53 est un service de DNS (Domain Name System) scalable et fiable qui permet de diriger le trafic web vers les ressources AWS ou externes en fonction des règles de routage définies.

3. **AWS Direct Connect** :
   - AWS Direct Connect permet d'établir une connexion dédiée et privée entre l'infrastructure sur site et AWS, offrant une bande passante élevée, une latence faible et une meilleure sécurité pour les charges de travail sensibles.

4. **AWS Global Accelerator** :
   - AWS Global Accelerator est un service qui améliore la disponibilité et les performances des applications mondiales en acheminant le trafic vers les points de terminaison les plus proches des utilisateurs, en utilisant le réseau mondial d'AWS.

5. **Amazon CloudFront** :
   - Amazon CloudFront est un service de distribution de contenu (CDN) qui offre une diffusion de contenu rapide et sécurisée à travers un réseau mondial de centres de données, réduisant la latence et améliorant l'expérience utilisateur.

6. **AWS App Mesh** :
   - AWS App Mesh est un service de maillage d'applications qui facilite la surveillance et le contrôle du trafic entre les services d'une application distribuée, offrant une visibilité et une gestion centralisées du trafic réseau.

###### Analytique

1. **Amazon Athena** :
   - Amazon Athena est un service qui permet d'interroger facilement des données stockées dans Amazon S3 en utilisant SQL standard, sans avoir besoin de provisionner ou de gérer une infrastructure.

2. **Amazon EMR (Elastic MapReduce)** :
   - Amazon EMR est un service de traitement de données distribué qui permet de traiter de grandes quantités de données à l'aide de frameworks open source comme Apache Hadoop, Spark et Presto.

3. **Amazon Redshift** :
   - Amazon Redshift est un service de data warehousing entièrement géré, conçu pour l'analyse de données à grande échelle, offrant des performances élevées et des capacités de requête complexes.

4. **Amazon QuickSight** :
   - Amazon QuickSight est un service de business intelligence qui permet de créer facilement des tableaux de bord interactifs et des visualisations de données à partir de diverses sources de données.

5. **AWS Glue** :
   - AWS Glue est un service d'extraction, de transformation et de chargement (ETL) entièrement géré qui permet de préparer et de charger facilement des données pour l'analyse.

6. **Amazon Kinesis** :
   - Amazon Kinesis est une plateforme pour la collecte, le traitement et l'analyse en temps réel de données en streaming, offrant des services comme Kinesis Data Streams, Kinesis Data Firehose et Kinesis Data Analytics.

###### Machine Learning

Voici une liste des services AWS dans la catégorie Machine Learning avec une brève description pour chacun :

1. Amazon SageMaker : Plateforme entièrement gérée qui permet aux développeurs et aux scientifiques des données de créer, former et déployer rapidement des modèles d'apprentissage machine.

2. Amazon Comprehend : Service de traitement du langage naturel qui permet d'analyser et de tirer des informations à partir de texte.

3. Amazon Rekognition : Service de vision par ordinateur qui permet de détecter, d'analyser et de reconnaître des objets, des visages et du texte dans les images et les vidéos.

4. Amazon Polly : Service de synthèse vocale qui transforme du texte en discours réaliste.

5. Amazon Translate : Service de traduction automatique qui permet de traduire du texte d'une langue à une autre.

6. Amazon Transcribe : Service de transcription automatique qui convertit l'audio en texte.

7. Amazon Personalize : Service de recommandation qui utilise l'apprentissage machine pour créer des recommandations personnalisées pour les utilisateurs.

Ces services AWS dans la catégorie Machine Learning offrent une variété d'outils pour permettre aux entreprises d'exploiter la puissance de l'apprentissage machine dans leurs applications et leurs processus.

###### Sécurité, identité et conformité

1. **AWS IAM (Identity and Access Management)** :
   - AWS IAM est un service de gestion des identités et des accès qui permet de contrôler de manière sécurisée l'accès aux ressources AWS en définissant des politiques d'autorisation et en gérant les utilisateurs et les groupes.

2. **AWS Cognito** :
   - AWS Cognito est un service d'authentification et d'autorisation qui permet d'ajouter des fonctionnalités d'inscription, de connexion et de gestion des utilisateurs à vos applications web et mobiles.

3. **AWS Shield** :
   - AWS Shield est un service de protection contre les attaques DDoS (Distributed Denial of Service) qui aide à protéger les applications web hébergées sur AWS contre les attaques malveillantes.

4. **AWS WAF (Web Application Firewall)** :
   - AWS WAF est un pare-feu d'application web qui permet de contrôler et de filtrer le trafic HTTP/HTTPS entrant vers les applications web en définissant des règles de sécurité personnalisées.

5. **Amazon Inspector** :
   - Amazon Inspector est un service d'évaluation de la sécurité automatisé qui analyse automatiquement les applications déployées sur AWS pour identifier les vulnérabilités de sécurité et les violations des bonnes pratiques.

6. **AWS Key Management Service (KMS)** :
   - AWS KMS est un service de gestion des clés de chiffrement qui permet de créer, contrôler et gérer facilement les clés de chiffrement utilisées pour chiffrer les données stockées et transitant sur AWS.

###### Gestion des coûts et de la facturation

1. **AWS Cost Explorer** :
   - AWS Cost Explorer est un outil d'analyse des coûts qui permet de visualiser, comprendre et gérer les coûts et l'utilisation des services AWS, en fournissant des insights et des recommandations pour optimiser les dépenses.

2. **AWS Budgets** :
   - AWS Budgets est un service qui permet de définir des budgets personnalisés pour surveiller les dépenses liées aux services AWS, en recevant des alertes lorsque les coûts dépassent les seuils définis.

3. **AWS Cost and Usage Report** :
   - Le rapport AWS Cost and Usage Report fournit des informations détaillées sur les coûts et l'utilisation des services AWS, permettant une analyse approfondie des dépenses et une optimisation des ressources.

4. **AWS Pricing Calculator** :
   - L'AWS Pricing Calculator est un outil en ligne qui permet d'estimer les coûts des services AWS en fonction de la configuration souhaitée, aidant les utilisateurs à planifier et à budgétiser leurs dépenses cloud.

5. **AWS Reserved Instance Reporting** :
   - AWS Reserved Instance Reporting fournit des rapports détaillés sur l'utilisation des instances réservées AWS, permettant aux utilisateurs de suivre et d'optimiser l'utilisation de leurs réservations pour réduire les coûts.

###### Développement d'applications

1. **AWS CodeDeploy** :
   - AWS CodeDeploy est un service de déploiement automatisé qui permet de déployer rapidement et de manière fiable des applications sur des instances EC2 ou des services AWS comme ECS et Lambda.

2. **AWS CodePipeline** :
   - AWS CodePipeline est un service de livraison continue qui permet d'automatiser le processus de publication et de déploiement de code, en orchestrant les étapes du pipeline de déploiement.

3. **AWS CodeCommit** :
   - AWS CodeCommit est un service de gestion de code source sécurisé basé sur Git, offrant un stockage privé et évolutif pour les dépôts de code source.

4. **AWS CodeBuild** :
   - AWS CodeBuild est un service de compilation entièrement géré qui compile le code source, exécute les tests et crée des packages prêts pour le déploiement de manière automatique.

5. **AWS CodeStar** :
   - AWS CodeStar est un service qui permet de développer, de créer et de déployer des applications sur AWS rapidement en fournissant un environnement de développement intégré et des modèles prédéfinis.

6. **AWS Cloud9** :
   - AWS Cloud9 est un environnement de développement intégré (IDE) basé sur le cloud qui permet de coder, de déboguer et de collaborer facilement sur des projets en ligne, offrant une flexibilité pour travailler n'importe où.

###### IoT

1. **AWS IoT Core** :
   - AWS IoT Core est un service de gestion des appareils IoT (Internet of Things) qui permet de connecter des appareils IoT à des services cloud, de gérer leur état et de sécuriser les communications.

2. **AWS IoT Device Management** :
   - AWS IoT Device Management est un service qui facilite l'enregistrement, la gestion et la mise à jour à distance des appareils IoT, offrant une gestion centralisée et évolutive des flottes d'appareils.

3. **AWS IoT Analytics** :
   - AWS IoT Analytics est un service qui permet d'analyser et de visualiser les données générées par les appareils IoT, en fournissant des insights pour prendre des décisions basées sur les données.

4. **Amazon FreeRTOS** :
   - Amazon FreeRTOS est un système d'exploitation temps réel open source pour les appareils IoT qui facilite le développement d'applications IoT sécurisées et connectées.

5. **AWS IoT Greengrass** :
   - AWS IoT Greengrass est un service qui étend les capacités de l'IoT Core vers les appareils locaux, permettant l'exécution de traitements locaux, la connectivité locale et la synchronisation avec le cloud.

6. **AWS IoT Events** :
   - AWS IoT Events est un service qui permet de détecter et de réagir aux événements générés par les appareils IoT en temps réel, en automatisant les actions en fonction des conditions détectées.

###### Intégration


1. **Amazon MQ** :
   - Amazon MQ est un service de messagerie managé basé sur Apache ActiveMQ qui permet de configurer, gérer et exécuter des brokers de messagerie compatibles avec les protocoles standard.

2. **Amazon SNS (Simple Notification Service)** :
   - Amazon SNS est un service de messagerie pub/sub (publication/abonnement) qui permet d'envoyer des notifications à des abonnés via des protocoles comme HTTP, email, SMS, etc.

3. **Amazon SQS (Simple Queue Service)** :
   - Amazon SQS est un service de file d'attente entièrement géré qui permet de décomposer les composants d'une application en modules indépendants, améliorant la scalabilité et la fiabilité.

4. **AWS Step Functions** :
   - AWS Step Functions est un service de gestion de workflow qui permet de coordonner les composants d'une application serverless en créant des workflows visuels basés sur des états.

5. **Amazon AppFlow** :
   - Amazon AppFlow est un service de transfert de données entièrement géré qui permet de créer des flux de données entre différentes applications AWS et externes, facilitant l'échange de données.

6. **AWS DataSync** :
   - AWS DataSync est un service qui permet de transférer de manière sécurisée et automatisée des données entre des systèmes de stockage sur site et AWS, facilitant la migration et la synchronisation des données.

###### Migration et transfert de données


1. **AWS Database Migration Service (DMS)** :
   - AWS Database Migration Service est un service qui facilite la migration de bases de données vers AWS ou entre différents moteurs de bases de données, en minimisant le temps d'arrêt et en assurant la cohérence des données.

2. **AWS Snow Family** :
   - AWS Snow Family est une gamme de services physiques pour transférer de grandes quantités de données vers et depuis AWS de manière sécurisée, offrant des appareils comme Snowcone, Snowball et Snowmobile.

3. **AWS Transfer Family** :
   - AWS Transfer Family est une famille de services qui permettent de transférer des fichiers vers et depuis AWS de manière sécurisée, offrant des options comme AWS Transfer for SFTP et AWS Transfer for FTP.

4. **AWS DataSync** :
   - AWS DataSync est un service qui permet de transférer de manière sécurisée et automatisée des données entre des systèmes de stockage sur site et AWS, facilitant la migration et la synchronisation des données.

5. **AWS Data Pipeline** :
   - AWS Data Pipeline est un service qui permet d'orchestrer et d'automatiser le traitement des données entre différents services AWS et sources de données externes, en créant des flux de travail de données.

6. **AWS DMS** :
   - AWS DMS (Database Migration Service) est un service qui facilite la migration des bases de données vers AWS ou entre différents moteurs de bases de données, en assurant une réplication fiable et continue des données.

##### Memo AWS Core Services - Compute 

###### Présentation des services de calcul

1. **Amazon Elastic Compute Cloud (Amazon EC2)** : Permet la création d’environnement ou de machine virtuelles de calcul dans le cloud
2. **AWS Lambda** :  permet de gérer tout ce qui est serverless (fait références aux applications dont l'allocation et la gestion des ressources sont entièrement gérées par le fournisseur de services cloud)
3. **Automatic Scaling** : permet de gérer la montée en performance si besoin et la haute disponibilité de nos machines EC2 
4. **Elastic Load Balancer** :  qui nous permet de repartir le traffic entrant et permet d’atteindre un niveau élevé de tolérance aux pannes.
5. **AWS Elastic Beanstalk** :  permet de gérer rapidement nos déploiement, nos besoins de montée en performance et de manager rapidement nos applications
6. **Amazon Lightsail** offrant tout ce dont vous avez besoin pour démarrer un projet, y compris une machine virtuelle, un stockage SSD, un transfert de données, une gestion DNS et une adresse IP statique, le tout pour un prix bas et prévisible. Gérez plus facilement des serveurs Web et d'applications simples.
7. **Amazon Elastic Container Service** est un service de gestion de conteneurs hautement évolutif et hautes performances qui prend en charge les conteneurs Docker et vous permet d'exécuter facilement des applications sur un cluster géré d'instances Amazon EC2.
8. **AWS Fargate** est une technologie pour Amazon ECS et Amazon Elastic Container Service pour Kubernetes qui permet aux utilisateurs d'exécuter des conteneurs sans avoir à gérer de serveurs ou de clusters.
9. **Amazon Elastic Container Service for Kubernetes (ou Amazon EKS)** est un service géré qui simplifie l'exécution de Kubernetes sur AWS sans avoir besoin d'installer ou d'exploiter vos propres clusters Kubernetes.

###### Amazon EC2 (Tarification Amazon)

1. **On-demand Instances:**
    - Capacité de calcul à l'heure et à la seconde 
    - Au moins 60 secondes

2. **Reserved Instances:**
    - Paiement intégral, partiel ou nul pour les instances réservées
    - Remise sur les frais horaires pour cette instance
    - mandat de 1 ou 3 ans

3. **Dedicated Hosts:**
    - Peut être acheté à la demande (horaire)
    - Peut être acheté en tant que réservation

4. **Spot Instances:**
    - Enchérir pour la capacité Amazon EC2 inutilisée
    - Prix ​​en fonction de l'offre et de la demande
    - Des instances peuvent être perdues si vous surenchérissez
    - les instances peuvent être interrompues si le prix Spot dépasse le maximum

###### Amazon EC2 (RESUME)

1. Amazon EC2 signifie Amazon Elastic Compute Cloud.
2. Amazon EC2 est un ordinateur dans le cloud:
    - Prend en charge la plupart des systèmes d'exploitation de serveur
    - Possibilité de lancer une instance à la fois, ou de lancer toute une flotte
    - Ajoutez des instances au besoin ; mettre fin lorsque plus nécessaire
3. Amazon EC2 propose une large sélection de types d'instances optimisés pour s'adapter à différents cas d'utilisation.
4. Il existe quatre façons de payer pour les instances Amazon EC2 : à la demande, instances réservées, instances ponctuelles et hôtes dédiés.

###### Amazon EC2 Cost Optimization
    reference: [Piliers d'optimisation des coûts](https://docs.aws.amazon.com/fr_fr/whitepapers/latest/cost-optimization-laying-the-foundation/cost-optimization-pillars.html)

Pour optimiser les coûts, vous devez prendre en compte quatre piliers principaux qui sont :

1. Dimensionnement correct - Choisissez le bon équilibre de types d'instances
2. L’utilisation d’instances réservées : tirez parti des instances réservées lorsque vous avez des charges de travail à long terme avec des modèles d'utilisation prévisibles
3. Élasticité: Augmentez l'élasticité à l'aide de la mise à l'échelle automatique (Automatic scaling)
4. Surveiller et améliorer : Surveillez en mesurant et en analysant votre système. Améliorez-vous continuellement et ajustez-vous au fur et à mesure.


##### Memo Serverless

Une application serverless sur AWS se caractérise par plusieurs aspects :
https://aws.amazon.com/fr/serverless/build-a-web-app/

1. **Absence de gestion de l'infrastructure**: Avec le modèle serverless, vous n'avez pas à vous soucier de la gestion des serveurs, de leur provisionnement ou de leur mise à l'échelle. AWS gère toute l'infrastructure sous-jacente pour vous.

2. **Fonctionnement basé sur les événements**: Les applications serverless sont généralement déclenchées par des événements, tels que des requêtes HTTP, des modifications dans des bases de données, des messages dans des files d'attente, etc.

3. **Facturation à l'utilisation**: Vous ne payez que pour les ressources que vous utilisez réellement et le temps pendant lequel votre code s'exécute. Cela rend le modèle serverless très économique pour les charges de travail à faible trafic ou à utilisation intermittente.

4. **Scalabilité automatique**: Les services serverless sur AWS, comme AWS Lambda, sont capables de s'adapter automatiquement à la demande en redimensionnant les ressources en fonction du nombre d'événements à traiter.

5. **Gestion simplifiée du déploiement**: AWS fournit des outils pour déployer facilement des applications serverless, tels que AWS SAM (Serverless Application Model) et AWS Serverless Application Repository.

En utilisant ces caractéristiques, les développeurs peuvent créer des applications évolutives, hautement disponibles et rentables sur AWS sans se soucier de l'infrastructure sous-jacente.