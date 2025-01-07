## Development, Messaging, and Deployment Technology and Services


#### QUESTION 1

##### Quel outil de développement vous permet d'écrire du code dans votre navigateur web ?


AWS CloudFormation


Amazon CloudWatch


AWS Cloud9 


AWS CloudTrail

#### QUESTION 2

##### Quel service AWS peut être utilisé pour centraliser le stockage et le contrôle des versions du code source, des binaires et des bibliothèques de votre application ?


CodeCommit 


CodeBuild


Système de fichiers élastiques


CodePipeline

#### QUESTION 3

##### Laquelle des configurations SQS suivantes est généralement recommandée pour la plupart des cas d'utilisation et pourquoi ?


L'interrogation courte est recommandé pour la plupart des cas d'utilisation, car il ne renvoie une réponse que lorsqu'un message se trouve dans la file d'attente ou que le délai d'attente est atteint. Cela évite de payer pour un grand nombre de réponses vides.


L'interrogation longue est recommandée pour la plupart des cas d'utilisation, car elle ne renvoie une réponse que lorsqu'un message est dans la file d'attente ou que le délai d'attente est atteint. Cela évite de payer pour un grand nombre de réponses vides. 


L'interrogation longue est recommandée dans la plupart des cas d'utilisation, car elle garantit que les messages sont traités dans l'ordre où ils ont été reçus et qu'aucun doublon ne sera introduit.


L'interrogation courte est recommandée pour la plupart des cas d'utilisation, car une réponse est renvoyée immédiatement même s'il n'y a pas de message dans la file d'attente.

#### QUESTION 4

##### Lequel des énoncés suivants correspond à la description correcte d'un couplage faible dans le cadre d'une application ?


Les composants de l'application peuvent être connectés les uns aux autres mais ne sont pas dépendants les uns des autres. 


Les composants d'application sont séparés et la communication entre les composants n'est pas autorisée.


Si une partie de l'application tombe en panne, c'est tout le système qui risque de s'effondrer.


Les différentes parties du système sont très dépendantes les unes des autres.

#### QUESTION 5

##### Quel service pourriez-vous recommander à un développeur pour automatiser le processus de mise à disposition des logiciels ?


CodeCommit


CodeBuild


Cloud9


CodePipeline (réponse: CodePipeline est un outil de développement qui vous permet d'automatiser en permanence le processus de publication des logiciels.)

#### QUESTION 6

##### Lequel des services AWS suivants fournit un shell basé sur un navigateur avec la CLI AWS préinstallée ?


AWS CodeCommit


AWS CodeBuild


AWS Cloud9 (réponse: AWS CloudShell est un shell basé sur un navigateur avec la CLI AWS préinstallée.)


AWS CloudShell

#### QUESTION 7

##### Quel service AWS est utilisé pour les notifications et la messagerie ?


L'outil de messagerie CloudWatch


Service de notification simple (SNS(Simple Notification Service)) 


Service de messages courts (SMS(Short Message Service))


Protocole de messagerie et de présence extensible (XMPP (Extensible Messaging and Presence Protocol))

#### QUESTION 8

##### Lequel des éléments suivants est un référentiel d'artefacts qui permet aux développeurs de trouver facilement les progiciels approuvés dont ils ont besoin pour créer leurs applications ?


CodeBuild


CodePipeline


CodeDeploy


CodeArtifact 

#### QUESTION 9

##### Lesquelles des affirmations suivantes sont vraies à propos de Simple Queue Service (SQS) ?


Les files d'attente standard ne garantissent pas le maintien de l'ordre exact des messages. 


Il s'agit d'un service qui ne permet qu'à un seul composant d'ajouter des messages à une file d'attente.


Il s'agit d'un service qui transfère des messages de manière non cryptée.


SQS est limité à une taille de message maximale de 64 KB.

#### QUESTION 10

##### Parmi les services AWS suivants, lesquels peuvent être utilisés pour visualiser et orchestrer une application sans serveur ?


X-Ray


La trame élastique (Elastic Beanstalk)


Fonctions d'étape (Step Functions) 


CloudFormation

#### QUESTION 11

##### Quel service vous permet de pratiquer l'Infrastructure as Code en provisionnant vos ressources AWS à l'aide de modèles scriptés ?


AWS Marketplace


AWS Lambda


AWS CloudFormation 


AWS Elastic Beanstalk

#### QUESTION 12

##### Vous souhaitez envoyer des informations marketing à vos clients, avec des détails sur les lancements de produits et des codes de réduction. Quel service vous permettra d'envoyer des courriers électroniques au format HTML ?


Amazon Simple Notification Service (SNS)


Amazon Simple Email Service (SES) 


Amazon Simple Queue Service (SQS)


Service de stockage simple (S3)

#### QUESTION 13

##### Quel service AWS permet d'envoyer des messages texte et des messages électroniques à partir de vos applications ?


Simple Queue Service (SQS)


Service de messagerie simple


Simple Email Service (SES)


Service de notification simple (SNS) 

#### QUESTION 14

##### Quel service AWS peut être utilisé pour installer automatiquement le code de votre application sur EC2, les systèmes sur site et Lambda ?


X-Ray


CodeBuild


CodeDeploy 


CodeCommit

#### QUESTION 15

##### Quel service peut être utilisé pour découpler les composants d'une application ?


X-Ray


CloudFormation


SQS 


CodeCommit

#### QUESTION 16

##### Quel service AWS est utilisé pour vous aider à créer des applications orientées événements qui répondent aux changements d'état déclenchés par les services AWS tels que EC2 ?


EventBridge 


CloudFormation


X-Ray


Fonctions des étapes

#### QUESTION 17

##### Laquelle des pratiques suivantes permet à plusieurs développeurs travaillant sur la même application de fusionner fréquemment des modifications de code, sans impact les uns sur les autres, et d'identifier les bogues dès le début du processus de publication ?


La livraison continue


Développement continu


Déploiement continu


Intégration continue 

#### QUESTION 18

##### Lequel des services AWS suivants peut être utilisé pour déployer rapidement et facilement une application web Java, y compris le provisionnement des instances EC2 nécessaires à l'exécution de l'application, la configuration d'un Elastic Load Balancer et même l'installation d'Apache Tomcat ?


CodeBuild


Elastic Beanstalk 


CodePipeline


CodeDeploy

#### QUESTION 19

##### Votre entreprise a migré vers AWS afin de pouvoir utiliser "Infrastructure as Code". Vous aimeriez pouvoir provisionner l'infrastructure AWS de manière cohérente et reproductible. Quel service devriez-vous utiliser pour y parvenir ?


CodeCommit


CloudFormation 


CloudWatch


Elastic Beanstalk

#### QUESTION 20

##### Lesquels des éléments suivants peuvent être stockés dans CodeArtifact ?


La documentation relative à votre application


Demandes compilées


Paquets déployables


Tous ces éléments conviennent 


Bibliothèques

#### QUESTION 21

##### Quel service AWS fournit une vue de bout en bout des requêtes qui transitent par une application distribuée et peut être utilisé pour résoudre les problèmes de connectivité et de performance ?


Step Functions


La trame de fond élastique (Elastic Beanstalk)


CloudFormation


X-Ray 

#### QUESTION 22

##### Quel service AWS peut être utilisé pour compiler le code source, exécuter des tests et empaqueter le code ?


CodeCommit


CodePipeline


CodeDeploy


CodeBuild 