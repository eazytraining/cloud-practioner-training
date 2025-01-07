## Security, Compliance, and Governance

#### QUESTION 1

##### Quel service peut être utilisé pour rechercher des vulnérabilités réseau et logicielles sur vos instances EC2 ?


1. GuardDuty (GuardDuty est un service intelligent de détection des menaces, principalement utilisé pour détecter les activités malveillantes autour de votre compte AWS.)


2. Inspecteur (Inspector) (réponse : Inspector permet une gestion automatisée et continue des vulnérabilités à grande échelle.)


3. Détective (Detective)


4. Conseiller de confiance (Trusted Advisor)

#### QUESTION 2

##### Une autorité de régulation a demandé la documentation prouvant que vos solutions AWS peuvent être conformes au GDPR. Quel service peut vous aider à répondre à cette demande ?


1. Hub de sécurité (Security Hub)


2. Tour de contrôle AWS (AWS Control Tower)


3. Artifice AWS (AWS Artifact) (réponse : Artifact est un portail libre-service gratuit qui permet d'accéder aux rapports de conformité.)


4. Sécurité du nuage AWS (AWS Cloud Security)

#### QUESTION 3

##### Quel service AWS protège vos ressources AWS contre les attaques DDoS ?


1. Le pare-feu réseau (Network firewall)


2. Bouclier AWS (AWS Shield) (réponse : Shield est conçu pour détecter et atténuer dynamiquement les attaques DDoS.)


3. Hub de sécurité (Security Hub)


4. AWS WAF 

#### QUESTION 4

##### Que pouvez-vous utiliser pour attribuer des autorisations granulaires aux utilisateurs, aux rôles et aux groupes ?


1. Règles de configuration


2. KMS


3. Service de jetons de sécurité (Security Token Service (STS))


4. Politiques IAM (IAM Policies) (Les politiques IAM définissent des autorisations d'accès granulaires pour n'importe quel critère.)

#### QUESTION 5

##### Votre entreprise souhaite utiliser l'apprentissage automatique pour l'aider à surveiller les données sensibles telles que les PII (informations personnelles identifiables) dans ses buckets S3. Quel est le moyen le plus simple d'y parvenir ?


1. Activer GuardDuty


2. Utiliser Macie (réponse : Macie utilise l'apprentissage automatique (ML) et la recherche de modèles pour découvrir et vous aider à protéger vos données sensibles.)


3. Activer Detective (Bien que Detective exploite l'apprentissage automatique, il est utilisé pour enquêter sur les événements de sécurité plutôt que pour inspecter les objets S3 à la recherche de données sensibles.)


4. S3 recherche et détecte automatiquement les informations sensibles telles que les PII.

#### QUESTION 6

##### Vous souhaitez donner à votre application basée sur EC2 l'accès à des secrets tels que des identifiants de base de données et des mots de passe, et vous voulez que ces identifiants changent automatiquement. Quel service devez-vous utiliser ?


1. Magasin de paramètres (Parameter Store) (réponse : Le gestionnaire de secrets vous permet d'accéder de manière programmatique à des secrets cryptés et d'effectuer une rotation automatique des secrets.)


2. Gestionnaire de secrets (Secrets Manager)


3. CloudHSM


4. Attachez une stratégie basée sur les rôles à l'instance EC2 pour lui donner accès à un bucket S3 contenant les secrets.

#### QUESTION 7

##### Votre entreprise a décidé de répartir ses charges de travail sur plusieurs comptes AWS, mais elle souhaite toujours pouvoir bénéficier de la facturation consolidée. Comment peut-elle y parvenir ?


1. Isolez les charges de travail en utilisant des balises.


2. Utiliser le centre d'identité IAM pour gérer de manière centralisée l'accès aux comptes AWS.


3. Utilisez Security Hub pour centraliser les résultats de facturation dans un seul compte.


4. Utiliser AWS Organizations pour gérer plusieurs comptes. (réponse: AWS Organizations vous permet de connecter plusieurs comptes à un compte de gestion, de bénéficier d'une facturation consolidée et de mettre en place une surveillance centralisée des ressources et de la sécurité.)

#### QUESTION 8

##### Lequel des énoncés suivants décrit le mieux le principe du moindre privilège ?


1. Vous devez limiter le nombre d'utilisateurs IAM de votre compte aux seuls utilisateurs strictement indispensables.


2. Activez toujours l'authentification multifactorielle pour l'utilisateur root.


3. Vous ne devez accorder que les autorisations nécessaires à l'accomplissement d'une tâche. (réponse : Limiter les autorisations aux seules personnes nécessaires permet d'éviter l'approvisionnement accidentel en ressources et de limiter le rayon d'action en cas de violation de la sécurité.)


4. Vous ne devez utiliser que des services gérés afin d'éviter toute surcharge opérationnelle.

#### QUESTION 9

##### Votre entreprise souhaite tirer parti de l'apprentissage automatique pour détecter automatiquement les événements de sécurité dans votre environnement AWS. Comment y parvenir en réduisant au maximum les coûts d'exploitation ?


1. Conseiller de confiance (Trusted Advisor)


2. Activer le détective


3. Activer Amazon Inspector


4. Activer GuardDuty (réponse : GuardDuty est un service intelligent de détection des menaces qui peut détecter dynamiquement les menaces dans votre compte AWS ou votre organisation.)

#### QUESTION 10

##### Quel est le moyen le plus simple de s'assurer que les objets S3 sont chiffrés au repos ?


1. Chiffrer le bucket S3 avec Secrets Manager.


2. Chiffrer les données au repos en appliquant les clés gérées par KMS. (Les clés KMS peuvent être utilisées pour chiffrer les buckets S3, mais il est plus facile d'utiliser le chiffrement par défaut.)


3. Les buckets S3 sont chiffrés par défaut côté serveur avec des clés gérées SSE-S3. (réponse : Les buckets S3 sont cryptés par défaut lors de leur création.)


4. Utilisez le Gestionnaire de certificats pour fournir des certificats SSL/TLS afin de crypter le conteneur S3.