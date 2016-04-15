# ExamenDCLL

Notes pour le professeur : 

Pour la partie 3 j'ai oublié de checkout conventions avant de faire les modifications, 
l'inverse aurait du etre fait : 
git checkout conventions 
puis modification 
puis git add des 2 fichiers 
puis git commit -m " mon message "
et enfin git checkout master
et pour terminer git merge conventions.
Le même problème est subvenu sur la branche testLoginService (ayant eu un problème avec le test junit j'ai du repasser sur master récupèrer une ligne et oublie de checkout de nouveau sur la branche).

Ces problèmes ne sont plus subvenu par la suite.
Mes excuses.

Ayant eu du temps à la fin j'ai réduis au maximum les problèmes checkstyle.

Notes en plus : dans File > Project Structure dans Module j'ai du ajouté les paths de test et src, n'étant pas définis
ils sont respectivement : src/test/java et src/main/java . Je les donnes au cas où.

