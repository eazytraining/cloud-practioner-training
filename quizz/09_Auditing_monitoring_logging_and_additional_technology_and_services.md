## Auditing, Monitoring, Logging, and Additional Technology and Services

#### QUESTION 1

##### Quelle fonction peut être utilisée pour analyser vos charges de travail et générer des plans d'action pour vous aider à obtenir une architecture plus fiable et plus rentable ?


1. L'outil Well-Architected (bien architecturé) (réponse : L'outil Well-Architected vous aide à utiliser le cadre Well-Architected comme un ensemble de lentilles à travers lesquelles analyser vos charges de travail. Vous pouvez l'utiliser pour vous familiariser avec le cadre d'une bonne architecture et générer des plans d'action pour aligner vos architectures sur ce cadre.)


2. Gestionnaire d'audit (Audit Manager)


3. Gestionnaire des systèmes (Systems Manager)


4. AWS Config

#### QUESTION 2

##### Que fait AWS Config ?


1. AWS Config vous permet de définir des règles applicables à l'ensemble du compte et de détecter les ressources non conformes. (réponse: AWS Config établit des règles de détection, et non des contrôles préventifs. Config s'appuie sur des règles prédéfinies ou personnalisées pour alerter les administrateurs lorsque des ressources non conformes sont détectées.)


2. AWS Config vous permet de définir des règles applicables à l'ensemble du compte et d'assurer la conformité en interdisant la création de ressources non conformes.


3. AWS Config vous permet de prendre des mesures automatisées sur de grands groupes de ressources en nuage.


4. AWS Config vous permet d'auditer les ressources non conformes et de générer des rapports d'audit.

#### QUESTION 3

##### Quel service fournit des recommandations à l'échelle du compte concernant l'optimisation des coûts, les limites de service et les meilleures pratiques en matière de sécurité ?


1. Conseiller de confiance (Trusted Advisor) (réponse : Trusted Advisor utilise les règles AWS Cofig pour déterminer si vous suivez les meilleures pratiques, et fournit une liste de recommandations classées par ordre de priorité.)


2. Tableau de bord de la santé AWS (AWS Health Dashboard)


3. Alarmes CloudWatch (CloudWatch Alarms)


4. Amazon Connect

#### QUESTION 4

##### Quel service vous informe des événements, des pannes, des modifications prévues et des notifications de compte ?


1. Tableau de bord AWS Health (AWS Health Dashboard) (réponse : Le service AWS Health Dashboard vous donnera une vue de toutes les pannes sur AWS, ainsi qu'un tableau de bord personnel qui n'affiche que les services et les régions qui sont pertinents pour vos ressources dans le cloud.)


2. Gestionnaire de systèmes (Systems Manager)


3. Alarmes CloudWatch (CloudWatch Alarms)


4. Conseiller de confiance (Trusted Advisor)

#### QUESTION 5

##### Comment recevoir une notification lorsque l'utilisation du CPU de votre instance EC2 atteint 90% ?


1. Systems Manager suit automatiquement l'utilisation du CPU et avertit les administrateurs lorsqu'elle dépasse 90 % sur une instance donnée.


2. Créez une alarme CloudWatch qui se déclenche lorsque l'utilisation du CPU atteint 90 %. (réponse : Les alarmes CloudWatch peuvent être utilisées pour envoyer des notifications ou déclencher des événements automatisés lorsque les mesures atteignent des seuils définis.)


3. Trusted Advisor génère automatiquement une recommandation lorsque l'utilisation du CPU de votre instance EC2 atteint 90 %.


4. Créez une alarme CloudTrail qui se déclenche lorsque l'utilisation du CPU atteint 90 %.

#### QUESTION 6

##### Quel service vous permet de créer des tableaux de bord dans lesquels vous visualisez les mesures produites par les services et les applications sur AWS ?


1. Trusted Advisor


2. Amazon CloudWatch (réponse : CloudWatch collecte des données en temps réel qui peuvent être visualisées dans un tableau de bord.)


3. Amazon CloudTrail (CloudTrail fournit un historique des appels à l'API AWS pour votre compte.)


4. Tableau de bord AWS Health (AWS Health Dashboard)

#### QUESTION 7

##### Combien de temps les logs de CloudWatch sont-ils stockés par défaut ?


1. Indéfiniment (réponse : Sauf indication contraire, les journaux CloudWatch seront stockés indéfiniment.)


2. 30 jours (Vous pouvez fixer la durée de conservation des journaux à 30 jours, mais ils seront conservés indéfiniment par défaut.)


3. 24 heures


4. 10 ans

#### QUESTION 8

##### Quel service vous permet de convertir le plus facilement une application existante en un Software-as-a-Service hébergé dans le cloud ?


1. Amazon Connect


2. AppStream (AppStream s'occupera de l'hébergement, de la mise à l'échelle et de la gestion des utilisateurs de votre application et vous aidera à la convertir en un produit SaaS pour vos employés ou vos clients.)


3. Espaces de travail (WorkSpaces)


4. AppSpaces

#### QUESTION 9

##### Lequel des éléments suivants n'est PAS une fonction de AWS Audit Manager ?


1. Utiliser des cadres prédéfinis pour vous aider à respecter les normes de sécurité et de configuration propres à votre secteur d'activité.


2. Centraliser les données d'audit provenant d'AWS Config et de divers services de sécurité.


3. Trouvez les causes profondes de la non-conformité et générez des rapports.


4. Générer des informations et des recommandations pour vous aider à respecter le cadre bien structuré. (réponse : Cela s'applique plutôt avec  Well-Architected Tool.)

#### QUESTION 10

##### Comment pouvez-vous regrouper et visualiser les ressources AWS par projet, environnement ou application ?


1. Tags (réponse : L'application de balises à vos ressources peut vous aider à les regrouper et à les visualiser sur CloudWatch ou System Manager.)


2. Conseiller de confiance (Trusted Advisor)


3. CloudTrail


4. Gestionnaire d'audit