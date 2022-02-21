---
title: "Formation PhP - Premier Niveau - "
date: 2021-06-13T10:11:25+00:00
description: php formation bases initiation 
menu:
  sidebar:
    name: PhP LvL 1
    identifier: php1_en
    parent: formations_php_en
    weight: 10
---

## _<center>:loudspeaker: Bonjour à tous et à toutes :heavy_exclamation_mark:</center>_

---

<div class="d-sm-block alert alert-info text-center" > 
<i class="fas fa-info-circle " style="color: blue;"></i> Nous verrons dans ce premier niveau de la formation sur <img style="vertical-align: middle;" src="/images/icones/php_h40.png" alt="PhP"> 7, les fondamentaux, ses principales fonctions et structures de contrôle, ainsi que des explications sur la transmission des données entre les <i class="fas fa-file-code"></i> pages et donc l’essentiel pour bien débuter avec ce <a href="https://fr.wikipedia.org/wiki/Langage_serveur">  langage de script coté <i class="fas fa-server"></i> serveur  <i class="fas fa-external-link-alt"></i></a> très utilisé pour les <i class="fas fa-sitemap"></i> sites internet et les <i class="fas fa-file-code"></i> pages web.<br/>
La formation dans ses débuts sera très axé sur l'excellent travail de mon ancien collègue, <a href="https://www.editions-eni.fr/supports-de-cours/recherche?exp=olivier%20rollet"><mark> Olivier ROLLET</mark>, Ingénieur maître et auteur chez les éditions Eni dont vous pouvez trouver ses livres -> :books: ICI <i class="fas fa-external-link-alt"></i> <-</a>
</div>

<div class="float-right img-fluid"  >
<img   src="variableselonbesoin-red.png" style="transform: rotate(-45deg); position : absolute; margin-right:15%;margin-left:15%; margin-top:30%; z-index: 1; ">
<img src="phpbaseliste.png" style="z-index: 0;">
</div>

><i class="fab fa-php fa-2x" style="color:blue; vertical-align:middle;"></i> :“ Hypertext Preprocessor, est un [langage de programmation libre <i class="fas fa-external-link-alt"></i>](https://fr.wikipedia.org/wiki/Logiciel_libre) , principalement utilisé pour produire des pages Web dynamiques via un <i class="fas fa-server"></i> serveur HTTP, mais pouvant également fonctionner comme n'importe quel langage interprété de façon locale.
>PHP est un langage impératif orienté objet.
>
>PHP a permis de créer un grand nombre de sites web célèbres, comme Facebook et Wikipédia. <strong><i>Il est considéré comme une des bases de la création de sites web dits <mark> [dynamiques <i class="fas fa-external-link-alt"></i>](https://fr.wikipedia.org/wiki/Page_web_dynamique) </mark> </strong></i> mais également des applications web.
>
> Il a été conçu pour permettre la création d'applications dynamiques, le plus souvent développées pour le Web. PHP est le plus souvent couplé à un serveur Apache bien qu'il puisse être installé sur la plupart des serveurs HTTP tels que IIS ou nginx.  
>Ce couplage permet de récupérer des informations issues d'une <i class="fas fa-database"></i> base de données [(très souvent MySQL ou MariaDb) <i class="fas fa-external-link-alt"></i>](https://fr.wikipedia.org/wiki/MySQL#Utilisation), d'un système de fichiers (contenu de fichiers et de l'arborescence) ou plus simplement des données envoyées par le navigateur afin d'être interprétées ou stockées pour une utilisation ultérieure.”  
> <cite>[ <img style="-webkit-user-select: none; margin: auto; " height="40px" src="/images/wikipedia.png"> Wikipedia <i class="fas fa-external-link-alt"></i>](https://fr.wikipedia.org/wiki/PHP "Définition à lire pour bien comprendre")</cite>
>
> <hr/>
>
><i class="fab fa-php fa-2x" style="color:blue; vertical-align:middle;" ></i>“
Au lieu d'utiliser des tonnes de commandes afin d'afficher du HTML (comme en C ou en Perl), les pages PHP contiennent des fragments HTML dont du code qui fait "quelque chose" (dans ce cas, il va afficher "Bonjour, je suis un script PHP !").<br/>
>Le code PHP est inclus entre une balise de début `<?php `et une balise de fin` ?>` qui permettent au serveur web de passer en mode PHP.
>
>Ce qui distingue PHP des langages de script comme le Javascript, est que le code <mark> est exécuté sur le serveur</mark> , générant ainsi le HTML, qui sera ensuite envoyé au client.  
>Le client ne reçoit que le résultat du script, sans aucun moyen d'avoir accès au code qui a produit ce résultat. Vous pouvez configurer votre serveur web afin qu'il analyse tous vos fichiers HTML comme des fichiers PHP.  
>Ainsi, il n'y a aucun moyen de distinguer les pages qui sont produites dynamiquement des pages statiques.”
>
> <cite>[<img style="-webkit-user-select: none; margin: auto; " src="/images/icones/php_h40.png" alt="PHP">.net <i class="fas fa-external-link-alt"></i>](https://www.php.net/manual/fr/intro-whatis.php "Définition à lire pour bien comprendre")</cite>  

   Je vous invite à lire l'`Introduction au Web dynamique` [-> ICI <- <i class="fas fa-external-link-alt"></i>](http://romainlebreton.github.io/ProgWeb-CoteServeur/classes/class1.html "Définition à lire pour bien comprendre") afin de mieux comprendre les différences entre sites statiques et dynamiques ainsi que le rôle de Php.
   		
<link rel="stylesheet" href="minified/bootstrap-gallery.min.css">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="minified/bootstrap-gallery.min.js"></script>
<div class="row">
  <div class="col-6 col-sm-3">
    <a href="/images/carte_conceptuelle_du_logiciel_libre.svg.png" class="thumbnail">
      <img src="/images/carte_conceptuelle_du_logiciel_libre.300.png" alt="Carte_conceptuelle_du_logiciel_libre plus d'info sur April https://www.april.org/carte-conceptuelle-du-logiciel-libre" />
    </a>
  </div>
 <div class="col-6 col-sm-3">
    <a href="sitedynaphp.png" class="thumbnail">
      <img src="sitedynaphp300.png" alt="(1) Interaction de l'utilisateur (clic pour afficher une page) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (2) Demande envoyée par le navigateur : GET/index.php HTTP/1.1 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; (3) Le serveur web réceptionne la requête, transmet à l'interpréteur PhP qui exécute les instructions du fichier php puis éventuellement retourne une page en HTML/CSS &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (4) Le serveur retourne la page en HTML/CSS (le code PhP n'est jamais visible)" />
    </a>
  </div>
  <div class="col-6 col-sm-3">
    <a href="frameworks-PHP.jpg" class="thumbnail" >
      <img src="frameworks-PHP450.jpg" alt="Php a énormément de framework nous simplifiant la tâche. Parmi les plus utilisés, Laravel , Symfony, Zend Framework ... " />
    </a>
  </div>
  <div class="col-6 col-sm-3">
    <a href="php_cms.png" class="thumbnail">
      <img src="php_cms400.png" alt="Php est aussi le langage dominant de très très nombreux CMS : Wordpress, Prestashop, Jommla, Drupal, la liste est longue !!!" />
    </a>
  </div>
</div>


Si vous avez bien tout lu vous serez arrivé à la conclusion que PhP est idéal pour les débutants et qu'il a beaucoup de fonctions avancées.  
Il rajoute une couche de <i class="fas fa-shield-alt"></i> sécurité non négligeable à nos pages web (on va plus se faire piquer notre code comme ça :tongue:).  
:closed_lock_with_key: On va surtout pouvoir stocker coté serveur (et donc de façon protégée) nos logins et mots de passes afin d'accéder à nos bases de données ou à des applications Web Externe sécurisées.


<div class="d-sm-block  alert alert-dark text-left" role="alert">

Paramétrons notre [environnement de développement (IDE) <i class="fas fa-external-link-alt"></i>](https://fr.wikipedia.org/wiki/Environnement_de_d%C3%A9veloppement) afin de gagner du temps le premier jour de la formation :

</div>

## <i class="fas fa-clipboard-list "></i> TODO :roller_coaster::

  <h4> 1.Dans un premier temps on va Installer puis configurer un éditeur de code : Visual Studio Code <img style="vertical-align:bottom;" height="30px" src="/images/icones/Visual studio code logo.png" alt="img"> : </h4>  Il devient un incontournable (en gratuit, merci crocsoft au passage) des éditeurs légers :

 - `Télécharger` _PUIS_ `installer` Visual Studio Code <img style="vertical-align:bottom;" height="30px" src="/images/icones/Visual studio code logo.png" alt="img"> :[->ICI <i class="fas fa-external-link-alt"></i><- ](https://code.visualstudio.com/).
 - Installer les extensions <i class="fab fa-php fa-2x" style="color:blue; vertical-align:middle;" ></i>ci-dessous pour VSC : <kbd>CTRL + SHIFT + X</kbd> puis tapez,` PHP Debug` (on s'en servira plus tard), `PHP IntelliSense` (pour le linter et des aides très pratiques), `php cs fixer` (pour le formattage du texte via <kbd>CTRL + SHIFT + H</kbd>)


  <div  class="row justify-content-center">
  <img src="extension1.png" >
  <img src="extension2.png" >  
  <img src="extension3.png" >  
  </div>

  - Il faudra peut-être redémarrer entre-temps VSC, faites lui plaisir, faites-le s'il vous le demande.
  - Ouvrez un répertoire de travail File -> Open Folder puis
    - On va dans le menu des fichiers en haut à gauche <kbd>CTRL + SHIFT + E</kbd> 
    - Ensuite soit on clique sur le symbole situé en (1) soit on fait File -> New file, soit on fait <kbd>CTRL + N</kbd> pour  créer un nouveau fichier que l'on va enregistrer <kbd>CTRL + S</kbd> en tant que <mark> index`.php` </mark>
    - Et ensuite on entre à l'intérieur le code suivant :

    ```php
    <!DOCTYPE html>
    <html>
    <body>
      
        <h2>Ma premiere page PHP</h2>
        <button type="button" onclick="document.getElementById('demo').innerHTML = Date()">
            Click me to display Date and Time.</button>
        <p id="demo"></p>
        <script>//un commentaire en JS, rajout perso
            alert("Hello World");
            console.log("Tu peux me voir en appuyant sur F12 ou allant dans les outils de dev de ton navigateur ;)");
        </script>
    </body>
    </html>
    ```

    Le fichier `JsJour1.html` est disponible ici [->ICI<-](Jsjour1.html) en cas de <i class="fas fa-briefcase-medical"></i>  
  Vous pouvez demander à votre navigateur de l'interpréter comme pour du html en double cliquant dessus ou en utilisant html preview dans VSC : clic droit puis `Open With Live Server` :  

      <div  class="row justify-content-start">
      <img src="rendu1.png">  
      <img src="rendu2.png">   
    </div>

  Comme vous pouvez le voir le code Javascript s'exécute entre 2 balises ` <script> et </script> ` et il nous permet d'interagir avec l'utilisateur ou de modifier dynamiquement la page.  
  On en verra beaucoup plus tout bien évidemment au long la formation.

<h4> 3. Pour finir notre configuration, et pour la fin de la formation, on va avoir besoin d'installer un serveur Web (si cela n'est pas déjà fait) sur votre ordinateur : </h4>

  - Pour ceux sont sur <img style="vertical-align: bottom;" src="/images/icones/w30/linux_30.png" alt="img"> Linux, <img style="vertical-align: bottom;" src="/images/icones/w30/ubuntu_30.png" alt="img"> Ubuntu :
    - Suivez les instructions de la `communauté` : [->ICI <i class="fas fa-external-link-alt"></i><- ](https://doc.ubuntu-fr.org/xampp)  
    - Ou alors `Télécharger` *PUIS* `installer` <img style="vertical-align: bottom;" src="/images/icones/w30/xampp_30.png" > Xampp ( <mark>La 5.6.28, pas la derniere !!! </mark>) :[->ICI <i class="fas fa-external-link-alt"></i><-](https://sourceforge.net/projects/xampp/files/XAMPP%20Linux/5.6.28/).
  - Pour ceux qui sont sur <i class="fab fa-windows"></i> Windows, `Télécharger` *PUIS* `installer` <img style="vertical-align: bottom;" src="/images/icones/w30/xampp_30.png" > Xampp ( <mark>La 5.6.28, pas la derniere !!! </mark>) :[->ICI <i class="fas fa-external-link-alt"></i><-](https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/5.6.28/).
  - Pour ceux qui sont sur <i class="fab fa-apple"></i> Mac, `Télécharger` *PUIS* `installer` <img style="vertical-align: bottom;" src="/images/icones/w30/xampp_30.png" > Xampp ( <mark>La 5.6.28, pas la derniere !!! </mark>) :[->ICI <i class="fas fa-external-link-alt"></i><-](https://sourceforge.net/projects/xampp/files/XAMPP%20Mac%20OS%20X/5.6.28/).

<div class="d-sm-block  alert alert-success  text-left" role="alert">
Vous avez pu tout faire c'est super :+1: :muscle: , sinon redonnez-vous une chance, au pire on verra ça rapidement le premier jour.  

:speech_balloon: Maintenant que l'on a configurer notre environnement de développement et que l'on a un premier fichier pour démarrer, on peut passer à la formation :astronaut: :  

:mortar_board: [Afin de débuter la Formation sur Javascript ensemble, vous aurez besoin de suivre les instructions du :books:support suivant et/ou de récupérer les éléments de la <img style="vertical-align: bottom;" src="/images/icones/w30/capsule_30.png" alt="C">apsule : (Logins & Passswords :closed_lock_with_key: donnés par le formateur <i class="fas fa-chalkboard-teacher"></i> ) <i class="fas fa-external-link-alt"></i>.](http://franpan.free.fr/formation/_javascript996 "lien vers le site contenant les fichiers de la formation")

</div>

Merci de garder pour vous les ressources que vous y trouverez et de ne pas les diffuser :smirk:  
Merci de m'avertir de toute erreur ou coquille qui m'auraient échapées :heart_eyes:

:copyright: :no_entry_sign: Do not distribute :relieved:
