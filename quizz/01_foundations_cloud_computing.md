## Foundations of Cloud Computing


#### QUESTION 1

##### Vous payez un abonnement mensuel à une entreprise pour héberger votre site web. Quel modèle de cloud computing est-ce un exemple?

1. Infrastructure en tant que service

2. Cloud en tant que service

3. Logiciel en tant que service

4. Plateforme en tant que service (réponse)

#### QUESTION 2

##### Vous devez créer une application hautement disponible dans le cloud. Comment pouvez-vous y parvenir?

1. Assurez-vous de sécuriser l'utilisateur root.

2. Assurez-vous que les ressources utilisent une seule zone de disponibilité (AZ).

3. Assurez-vous d'utiliser un modèle de déploiement privé.

4. Assurez-vous que les ressources utilisent plusieurs zones de disponibilité (AZs) (réponse).

#### QUESTION 3

##### Quelle catégorie de service n'est pas offerte par AWS?

1. Outils pour développeurs 

2. Centre de données (réponse: Il existe des services qui fournissent du matériel que vous pouvez utiliser localement, mais il n'existe pas de catégorie appelée centre de données.)

3. Base de données

4. Calcul

#### QUESTION 4

##### Lequel des énoncés suivants est vrai ?

1. Il y a quatre piliers dans le Well-Architected Framework.

2. Il y a six piliers dans le Well-Architected Framework (réponse: Les piliers comprennent la sécurité, l'optimisation des coûts, la fiabilité, l'efficacité des performances, l'excellence opérationnelle et la durabilité.).

3. Le AWS Well-Architected Framework cartographie les régions AWS.

4. L'un des piliers du Well-Architected Framework est le Renouvellement.

#### QUESTION 5

##### Vous devez mettre en œuvre une faible latence. Que pouvez-vous utiliser pour y parvenir?

1. Zones locales et/ou emplacements Edge (réponse: Les zones locales étendent les régions pour fournir des latences de l'ordre de la milliseconde, tandis que les emplacements Edge fournissent une mise en cache près des utilisateurs finaux.)

2. Centres de données et/ou régions

3. Zones de disponibilité (AZ) et/ou régions

4. Zones locales et EC2

#### QUESTION 6

##### Vous venez de vous faire supprimer tout votre compte AWS par un attaquant. Vous êtes en train de créer un nouveau compte AWS. Comment pouvez-vous vous assurer que la même chose ne se reproduira pas ?

1. Changer fréquemment votre mot de passe.

2. Utiliser un mot de passe plus fort.

3. Activer l'authentification multi-facteurs (MFA) pour l'utilisateur principal (réponse: Lorsque vous créez votre compte AWS, la première chose à faire est d'activer la protection du compte en configurant l'authentification à deux facteurs. Cela protègera l'utilisateur racine, qui dispose de plus de privilèges que les autres utilisateurs.)

4. Les retrouver et obtenir justice.

#### QUESTION 7

##### Quels sont les avantages suivants considérés comme des avantages du cloud ?

1. Logiciel en tant que service

2. Zones locales

3. Modèles hybrides

4. Expansion mondiale en quelques minutes (réponse: Un avantage du cloud est la capacité de lancer des ressources n'importe où dans le monde d'un simple clic. )

#### QUESTION 8

##### Vous devez déployer votre environnement cloud à la fois sur AWS et dans votre centre de données sur site en utilisant Direct Connect. Quel modèle de déploiement cloud peut accomplir cela?

1. Privé

2. Public

3. Sur site

4. Hybride (réponse)

Direct Connect est un service qui permet d'établir une connexion réseau dédiée entre AWS et un centre de données sur site, ce qui facilite l'intégration d'un environnement cloud hybride. Un modèle de déploiement hybride serait donc capable d'accomplir cette tâche.

#### QUESTION 9

##### Quel élément parmi les suivants NE PEUT PAS être utilisé pour accéder à vos ressources AWS?

1. Authentification multi-facteurs (MFA)

2. L'interface de ligne de commande AWS (CLI)

3. Le code d'application (réponse: Le code d'application peut utiliser des SDK (kits de développement logiciel) pour effectuer des appels et accéder à des ressources, mais en soi, le code d'application seul n'est pas un moyen d'accéder directement aux ressources AWS. Les SDK sont des ensembles d'outils et de bibliothèques qui permettent aux développeurs de créer des applications pour une plateforme spécifique. Ces outils facilitent l'accès aux fonctionnalités et aux ressources offertes par la plateforme, ce qui permet aux développeurs de créer des applications plus efficacement.)

4. Kits de développement logiciel (SDK)

#### QUESTION 10

##### Vous vérifiez la latence sur un site web nouvellement lancé. Vous remarquez qu'il se charge très rapidement. Quel type de latence serait-ce ?

1. Haute latence

2. Faible latence (réponse: "Faible latence" est ce que vous voulez pour votre site web, car cela signifie que vos utilisateurs finaux peuvent y accéder très rapidement.)

3. Latence moyenne

4. Latence élastique