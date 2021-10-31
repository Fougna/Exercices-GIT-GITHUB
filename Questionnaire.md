# GIT & GITHUB Survey (Beginner level)
---------------------------------------------------------------------------------
## Questionnaire fin de module GIT et GITHUB (temps 1h00)  
  
***1. Quelle est l'utilité de GIT ?***  
  
***2. Dans quelle situation est-il nécessaire d’utiliser GIT ?***  
  
***3. Quelle commande permet d’initialiser GIT dans un projet ?***  
git init  
  
***4. Où est-ce que la commande GIT INIT doit être exécutée ?***  
À la racine du projet.  
  
***5. Combien d'étapes sont nécessaires pour enregistrer correctement unfichier via GIT ?***  
  
***6. Quelle commande permet d’ajouter l’ensemble des fichiers modifiés ?***  
git add .  
  
***7. Le code suivant est-il correct ? :***git commit  
Non, la code correct est : git commit -m"Commentaire du développeur"  
  
***8. Écrire le code pour enregistrer le fichier "script.js” via GIT.***  
git add script.js  
  
***9. Quelle commande permet d’afficher l’historique des versions ?***  
git log  
  
***10. Écrire toutes les commandes qui permettent de créer un nouveau projet, d’initialiser git, de créer un premier fichier "script.js" et de l’enregistrer dans le dépôt.***  
mkdir nouveauProjet  
cd nouveauProjet  
git init  
touch script.js  
git add script.js  
git add commit -m"Commentaire"  
git remote add origin newRepository  
git push origin master  
  
***11. Quelle est l'utilité des branches ?***  
  
***12. Quelle commande permet de créer une branche ?***  
git branch newBranch  
  
***13. Quelle commande permet de passer d’une branche à une autre ?***  
git checkout newBranch  
  
***14. Que fait la commande  GIT BRANCH ?***  
  
***15. Quelles sont les étapes pour fusionner le code de deux branches ?***  
git merge newBranch  
  
***16. Quelle est la différence entre dépôt local et dépôt distant ?***  
  
***17. Quelle commande permet d’associer notre dépôt local à un dépôt distant ?***  
  
***18. Quelle commande permet d’envoyer les modifications sur le dépôt distant ?***  
git push origin master  
  
***19. Quelle commande doit être effectuée avant un GIT PUSH pour recevoir les modifications du dépôt distant ?***  
git pull origin master  
  
***20. Bonus: Écrire toutes les commandes qui permettent de cloner undépôt à l'url suivant https://github.com/jquery/jquery.git puis d’y associer un nouveau dépôt distant.***