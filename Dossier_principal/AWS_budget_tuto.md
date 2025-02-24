# Creation de budget sur AWS

Pour créer un nouveau budget sur AWS, suivez ces étapes 
1. Accédez à AWS Budgets :
   - Connectez-vous à la [Console AWS Management] (https://aws.amazon.com/console/).
   - Dans la barre de menu en haut de la page à droite, cherchez votre identifiant (Username).
   - Cliquez sur Gestion de la facturations et couts.
   - Cliquez sur Budgets dans le sous menu Budgets et Facturation.
 2. Créer un nouveau budget :
Dans la création de votre budget vous pouvez choisir entre deux configurations de budget :
a-	Utiliser un modèle (simplifié), c’est le modèle par défaut propose par aws, qui comprend quatre modèles :
   - Budget de dépense nul ;
   - Budget de couts mensuel ;
   - Budget de couverture quotidienne des Savings Plans ;
   - Budget quotidien d’utilisation des réservations ;
Ensuite il vous suffira de cocher sur le modèle qui vous intéresse , donnez un nom au budget et indiquez votre adresse-email. Puis cliquez sur Créer un budget.
Votre budget a été créer avec succès vous pouvez le voir dans la liste de vos budget.
NB : lire les descriptions de chaque menu pour plus d’information.
Dans cet exemple nous avons utilisez le modèle de budget de dépense nul.


B-	Personnaliser(avancé), c’est le modèle qui permet de personnaliser et de définir des paramètres spécifiques à votre cas d’utilisation :

Etape 1 : Choisir le type de budget
   - Budget de couts-Recommande : Pour suivre les coûts.
   - Budget d’utilisation : Pour suivre l'utilisation des services.
   - Budget Savings Plans : Pour suivre la couverture des Savings Plans.
   - Budget de réservation : Pour suivre l'utilisation et la couverture associes à vos              réservations.
Etape 2 : Définir votre budget
Dans cette partie vous allez saisir les détails de votre budget(nom).
Définir le montant en sélectionnant une période, indiquez si vous choisissez un budget fixe ou maniable puis saisissez le montant.
Définir la portee de votre budget(facultatif).
Ensuite cliquez sur suivant.
Etape 3 : Configurer des alertes
Afin de surveiller l’etat de votre budget vous pouvez créer jusqu’à 5 alertes différentes en fonction de votre montant.En définissant des seuils d’alertes, EX : 80%.
Etape 4 : définir des actions
Aucune action n’as été defini par defaut.
Etape 5 : Vérifications
Veuillez vérifier les informations de votre budget et modifier ci besoin.
Ensuite cliquez sur créer un budget.



