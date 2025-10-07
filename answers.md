# Answers of Gilles Nicol Gilles-Nicol

## Basics
### Task 1
1 unstaged change: signifie qu'un fichier a été modifié mais pas encore ajouté à l'index (staging area) pour le prochain commit.
### Task 2
- Que signifie le message de commit CHG: personal data changed in answer.md?
Le message de commit "CHG: personal data changed in answer.md" indique qu'une modification a été apportée au fichier "answer.md" et que cette modification concerne les données personnelles. Le préfixe "CHG:" est souvent utilisé pour signaler un changement (change) dans le fichier.

- Peut-on créer un commit sans message de commit?
Non, il n'est pas possible de créer un commit sans message de commit. 
- Quest - ce qui change déshormet dans le depot?
Lorsque vous créez un commit, les modifications qui ont été ajoutées à l'index (staging area) sont enregistrées de manière permanente dans l'historique du dépôt. Cela signifie que les changements apportés aux fichiers suivis sont maintenant versionnés et peuvent être consultés, restaurés ou partagés avec d'autres collaborateurs.
-  Le dépôt distant (ici Github) est-il à jour avec nos modifications locales?
Non, le dépôt distant (comme GitHub) n'est pas automatiquement mis à jour avec les modifications locales. Pour synchroniser les modifications locales avec le dépôt distant, vous devez utiliser la commande `git push` pour envoyer vos commits locaux vers le dépôt distant.
### Task 3
 Consultez à nouveau le statut de votre dépôt, que constatez-vous ? Il y a un message untracked files
### Task 4
- Que se passe-t-il lorsque vous revenez au commit « Initial commit » ?
Lorsque vous revenez au commit "Initial commit", votre dépôt local est restauré à l'état exact de ce commit. Cela signifie que toutes les modifications apportées après ce commit seront perdues dans votre espace de travail, et les fichiers seront remis à l'état qu'ils avaient lors de ce commit initial. Cependant, les commits ultérieurs restent dans l'historique du dépôt et peuvent être récupérés si nécessaire.
-  Que se passe-t-il lorsque vous revenez au dernier commit ?
Lorsque vous revenez au dernier commit, votre dépôt local est restauré à l'état exact ou vous étiez lors de ce commit. Toutes les modifications apportées après ce commit seront perdues dans votre espace de travail, et les fichiers seront remis à l'état qu'ils avaient lors de ce dernier commit. Cependant, les commits ultérieurs restent dans l'historique du dépôt et peuvent être récupérés si nécessaire.

### Task 5
- quel est la difference entre le depot local et le depot distant?
Le dépôt local est la copie de votre projet qui réside sur votre machine locale, où vous effectuez des modifications, créez des commits et gérez votre historique de version. Le dépôt distant, en revanche, est une copie du projet hébergée sur un serveur distant (comme GitHub, GitLab, etc.) qui permet la collaboration avec d'autres développeurs et le partage de votre code.
- Que se passe -t-il si on supprime le depot local?
Si vous supprimez le dépôt local, vous perdez toutes les modifications non poussées vers le dépôt distant. Cependant, si vous avez déjà poussé vos commits vers le dépôt distant, vous pouvez toujours cloner à nouveau le dépôt distant pour récupérer une copie du projet.

### Task 6
-  Avec toutes ces manipulations, qu’en est-il du dépôt originel, celui ayant été forké ? A-t’il été modifié ?
 Le dépôt originel, celui ayant été forké, n'a pas été modifié par les manipulations effectuées dans votre fork. Les modifications apportées dans votre fork sont isolées et n'affectent pas le dépôt original. Pour que les modifications de votre fork soient intégrées dans le dépôt original, vous devez créer une pull request (PR) et obtenir l'approbation des mainteneurs du dépôt original.

## Gitgraph

### Task 7
1. nom de la branche
2. hash de commit
3. message de commit
4. auteur du commit
5. tag
6. dernier commit
7. branche secondaire (feature-auth)
8. last commit de la branche initiale
9. branche secondaire (develop)
10. branche main

![Gitgraph](img/gitgraph.svg)