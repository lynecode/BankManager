Description
Application Java illustrant le principe d'héritage en programmation orientée objet.
Une classe parente BankAccount est étendue par trois classes spécialisées : CheckingAccount, SavingsAccount et COD.

Arborescence
FichierRôleBankAccount.javaClasse parente — attributs account et balanceCheckingAccount.javaCompte courant — ajoute l'attribut limitSavingsAccount.javaCompte épargne — ajoute l'attribut interestRateCOD.javaCertificat de dépôt — ajoute l'attribut durationMonthsMain.javaPoint d'entrée — instancie et affiche chaque compte

Prérequis

Java JDK 21
IntelliJ IDEA (ou IDE compatible)
Git


Lancer le projet
bashgit clone https://github.com/TON_USERNAME/BankManager.git

Ouvrez le projet dans IntelliJ IDEA
Configurez le JDK en version 21
Exécutez la classe Main


Ce que fait le programme

Crée une instance de CheckingAccount, SavingsAccount et COD
Chaque instance hérite de account et balance via BankAccount
Les attributs sont initialisés et affichés directement dans main
Les montants sont exprimés en FCFA


Concepts clés abordés

extends — mise en place de l'héritage entre classes
Classe parente / Classe enfant — BankAccount transmet ses attributs aux trois classes dérivées
