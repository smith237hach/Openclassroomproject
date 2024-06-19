# **PHP**
 Ce language est vraiment tres ouvert sur beaucoup de debouches. 
 
 Il permet entre autre de concevoir un code executable sur le serveur. 
 
 Il est transferer au navigateur sous forme de code **HTML** brut pour pouvoir etre compris par ce dernier. 
 
 Comme le **HTML** et le **CSS**, le **PHP** lui aussi a une extension qui es << **.PHP** >>. 

 le **PHP** est de plus en plus surprenant c'est a dire que il peut etre present dans le **HTML**, wordpress en es completement constituer de ce lamguage qu'est le **PHP**.
 
 les instructions a linterieur de ce code ce termine par un point-virgule ( **;** ), En **PHP**, les mots-clés (par exemple , , , , etc.), les classes, les fonctions, et les fonctions définies par l’utilisateur ne sont pas sensibles à la casse, Toutefois; Tous les noms de variables sont sensibles à la casse !  

j'ai pu observer que on distinguais plusieurs type de commentaires en **PHP** tous bien sur non impactant dans le code, mais permettant de se retrouver pour un autre utilisateur qui voudrais comprendre le code alors:
1. /* */ : representant la syntaxe d'un commentaire multi-ligne
2. "#" : represente la syntaxe d'un commemntaire sur une seule ligne tout comme ( // )
3. 'C': represente la syntaxe du commentaire de type C il ne s'arrete qu'apres la rencontre du premier " */ "

  j'ai aussi pu observer que les variables etaient tres importante en **PHP**,les  Règles pour les variables **PHP** :

1. Une variable commence par le signe, suivi du nom de la variable$

2. Un nom de variable doit commencer par une lettre ou un trait de soulignement

3. Un nom de variable ne peut pas commencer par un nombre
Un nom de variable ne peut contenir que des caractères alphanumériques et des traits de soulignement (A-z, 0-9 et _ )

4. Les noms de variables sont sensibles à la casse (et sont deux variables différentes)

j'ai pu remarquer qu'on avais plusieurs type de donnees pris en charge par **PHP**  a savoir:

1. Corde
2. Entier
3. Float (nombres à virgule flottante - également appelés doubles)
4. Booléen
5. Tableau
6. Objet
7. ZÉRO
8. Ressource.

#### GESTION DE FORMULAIRE PHP
 j'ai pu constater que en conception de formulaire le php est tres important.
 
 exple: <!DOCTYPE HTML>
<html>  
<body>

<form action="welcome.php" method="post">
Name: <input type="text" name="name"><br>
E-mail: <input type="text" name="email"><br>
<input type="submit">
</form>

</body>
</html>

dans cette exemple je viens de taper du code html associer a du php pour faire ressortir cette petite partie de formulaire nous permettant de voir que et de comprendre que le php et le html se compense. alors