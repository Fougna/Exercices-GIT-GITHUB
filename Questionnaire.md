# GIT & GITHUB Survey (Beginner level)
---------------------------------------------------------------------------------
<strong>Questionnaire fin de module Git et github(temps 1h00)<br/>
<br/>
1. Quelle est l'utilité de GIT ?</strong><br/>
<br/>
<strong>2. Dans quelle situation est-il nécessaire d’utiliser GIT ?</strong><br/>
<br/>
<strong>3. Quelle commande permet d’initialiser GIT dans un projet ?</strong><br/>
git init<br/>
<br/>
<strong>4. Où est-ce que la commande GIT INIT doit être exécutée ?</strong><br/>
À la racine du projet.<br/>
<br/>
<strong>5. Combien d'étapes sont nécessaires pour enregistrer correctement unfichier via GIT ?</strong><br/>
<br/>
<strong>6. Quelle commande permet d’ajouter l’ensemble des fichiers modifiés ?</strong><br/>
git add .<br/>
<br/>
<strong>7. Le code suivant est-il correct ? :</strong>git commit<br/>
Non, la code correct est : git commit -m"Commentaire du développeur"<br/>
<br/>
<strong>8. Écrire le code pour enregistrer le fichier "script.js” via GIT.</strong><br/>
git add script.js<br/>
<br/>
<strong>9. Quelle commande permet d’afficher l’historique des versions ?</strong><br/>
git log<br/>
<br/>
<strong>10. Écrire toutes les commandes qui permettent de créer un nouveau projet, d’initialiser git, de créer un premier fichier "script.js" et de l’enregistrer dans le dépôt.</strong><br/>
mkdir nouveauProjet<br/>
cd nouveauProjet<br/>
git init<br/>
touch script.js<br/>
git add script.js<br/>
git add commit -m"Commentaire"<br/>
git remote add newRepository<br/>
git push origin master<br/>
<br/>
<strong>11. Quelle est l'utilité des branches ?</strong><br/>
<br/>
<strong>12. Quelle commande permet de créer une branche ?</strong><br/>
git branch newBranch<br/>
<br/>
<strong>13. Quelle commande permet de passer d’une branche à une autre ?</strong><br/>
git checkout newBranch<br/>
<br/>
<strong>14. Que fait la commande  GIT BRANCH ?</strong><br/>
<br/>
<strong>15. Quelles sont les étapes pour fusionner le code de deux branches ?</strong><br/>
git merge newBranch<br/>
<br/>
<strong>16. Quelle est la différence entre dépôt local et dépôt distant ?</strong><br/>
<br/>
<strong>17. Quelle commande permet d’associer notre dépôt local à un dépôt distant ?</strong><br/>
<br/>
<strong>18. Quelle commande permet d’envoyer les modifications sur le dépôt distant ?</strong><br/>
git push origin master<br/>
<br/>
<strong>19. Quelle commande doit être effectuée avant un GIT PUSH pour recevoir les modifications du dépôt distant ?</strong><br/>
git pull origin master<br/>
<br/>
<strong>20. Bonus: Écrire toutes les commandes qui permettent de cloner undépôt à l'url suivant https://github.com/jquery/jquery.git puis d’y associer un nouveau dépôt distant.</strong>