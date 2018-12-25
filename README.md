Titre : Un réseau nommé poésie


Ce travail a été réalisé par Melina Marchetti dans le cadre de sa spécialisation de Master en pédagogie et médiation culturelle, à l’occasion du cours « Publication numérique » dispensé par I. Pante à l’Unil,

Ce travail vise à améliorer, de manière esthétique et pratique, les articles publiés par A. Rodriguez sur poésieromande.ch au sujet du Réseau nommé poésie : http://www.poesieromande.ch/wordpress/reseau-poesie/. Le but initial du projet n’était alors pas d’enrichir sémantiquement le texte, mais de travailler sur sa possible meilleure lecture pour tout utilisateur à travers le point focal qu’est l’ipad –le texte reste lisible sur tout type de média. Ayant tenté de rendre le texte plus attrayant et facile à lire sur une page HTML par le biais de l’utilisation du CSS, de polices téléchargées et de plugins, nous avons décidé de présenter les 10 articles à travers 10 parties, avec un titre, le début de l’article, une photos animée, et un lien qui renvoie à l’article en entier ; ensuite, l’article en entier s’affiche de manière épurée et agréable à lire. 
Le projet se trouve à cette page : 

Pour présenter notre travail, nous avons joint les fichiers suivants dans le dossier github :
-	Le fichier principal HTML, nommé « index », qui renvoie à la page produite s’affichant sur le navigateur. Il est composé de trois parties : 1) un titre 2) un résumé contextuel sur les articles 3) les 10 articles, tous composés d’une titre, du rédacteur et de la date de la parution, du début de l’article, et d’une photo animée. La lecture en deux étapes favorise, selon nous, l’intérêt du lecteur et pousse à scinder sa lecture en plusieurs étapes – donc de finir le texte.
-	Les fichiers secondaires HTML, nommés posts, qui contiennent les 10 fichiers sur lesquels ouvrent les liens. Ceux-ci sont composés d’un titre, d’un résumé, du texte, d’une image et de la référence du texte.
-	Un dossier CSS, qui contient trois fichiers au format CSS gérant le style du document HTML : 1) la feuille de style typique 2) , 3). Nous avons géré le style général afin de rendre la lecture plus agréable : un fond clair et un texte foncé, une couleur violette esthétique ; des marges larges ; un interligne important ; une taille de police facilitant la lecture et des variations sur les tailles présentes mais pas trop conséquentes afin de ne pas saturer le lecteur. 
-	Un dossier de polices, qui touche lui aux polices téléchargées pour le travail. Les polices sélectionnées – accompagnées d’un interligne et de marges conséquentes - permettent, selon nous, une lecture plaisante.
-	Un dossier JS, qui contient le fichier du format JS permettant de 
-	Un dossier image, regroupant les images de notre support (elles proviennent du site poésieromande.ch). 
-	Notons aussi que nous avons ajouté ces 3 fichiers dans le fichier principal directement : 
o	Le premier lien, qui touche à <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
o	Le deuxième lien, qui se rapporte à <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
o	Le troisième lien, qui renvoie au fichier bosstrap.min permettant de rendre responsive le document : il s’adapte à tous les navigateurs  <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>

Respond.min: adaptation aux navigateurs
Animation des images : Javascript : 
Scrolling letter 

Souhaitant faciliter l’acte de lecture des articles tout en développant un design épuré davantage esthétique, nous avons intégré les éléments et fonctionnalités suivantes:
-	un scrolling letter, pour que le lecteur sache quand son acte de lecture se termine (cela constitue une motivation de lecture).
-	une mise en page plus intéressante esthétiquement et rendant la lecture meilleure, en accentuant un numéro plus visible ; en travaillant le choix d’une police (Helvetica Neue), ses diverses tailles et ses couleurs (noir et violets); en choisissant un corps de texte général avec alignement justifié à 13px; en optant pour un saut de ligne tous les 50 signes environ ; en ajoutant des marges de chaque côté du texte (width 85% et des margin 30px); en proposant un résumé pour chaque article avant ouverture ; et en agrandissant les photos. 
-	Un changement de page en cliquant sur le titre ou le more pour la page principale ; et le titre pour les pages secondaires. 
-	Des images animées
-	Une lecture possible de la page html sur toute forme de média (ipad, natel, ordinateur).
