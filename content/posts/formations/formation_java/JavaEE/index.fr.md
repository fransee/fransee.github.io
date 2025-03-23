---
title: "JEE"
date: 2025-03-02T10:07:31+00:00
description: Java Edition Entreprise JEE
menu:
  sidebar:
    name: JavaEE
    identifier: jee1_fr
    parent: formations_java_fr
    weight: 10
---
*<center>:loudspeaker: Bonjour à tous et à toutes :heavy_exclamation_mark:</center>*
---

<div class="d-sm-block alert alert-info " > <center>
<i class="fas fa-info-circle " style="color: blue;"></i> Au programme de cette formation <i class="fa-brands fa-java fa-2xl"></i> Java Edition Entreprise: </center>
<span class="text-left">

- Introduction-ArchiDistribuees
- Introduction-QuestJEE
- Introduction-Conteneurs et serveurs applications 
- Couche Presentation
- JSP
- Servlet
- Collaboration Servlet Jsp
- Jstl Et El
- Introduction-Persistance
- Persistance-Orm-Hibernate
- Persistance-JPA-Intro
- Persistance-JPA-Associations
- Persistance-JPA-JPQL
- Couche Metier WildFly
- Couche Metier Introduction
- Couche Metier EJBSession
- Couche Metier EJBEntity
- Couche Metier_JMS_MDBe
- Webservice Introduction
- JUnit

</div>

> <img style="float:left; vertical-align: middle;margin-right:0px!important;width:200px" src="250px-Jakarta_ee_logo_stacked.png" alt=""> 
>Jakarta EE (anciennement Java 2 Platform, Enterprise Edition, ou J2EE , puis Java Platform, Enterprise Edition ou Java EE), est une spécification pour la plate-forme Java d'Oracle, destinée aux applications d'entreprise.
>
>La plate-forme étend Java Platform, Standard Edition (Java SE) en fournissant une API de mapping objet-relationnel, des architectures distribuées et multitiers, et des services web.
>La plate-forme se fonde principalement sur des composants modulaires exécutés sur un serveur d'applications.
>
>Alors que Java SE constitue le framework de référence pour Java — avec des bibliothèques standards répondant à la plupart des besoins —, Java EE complète ce framework avec des bibliothèques logicielles additionnelles dédiées à des applications professionnelles, facilitant par exemple le développement d'applications pour architecture distribuée.
>
> <cite>[ <img style="float:left; margin: 1px; " height="40px" src="/files/images/wikipedia.png"> Wikipedia <i class="fas fa-external-link-alt"></i>](https://fr.wikipedia.org/wiki/Jakarta_EE "Définition à lire pour bien comprendre")</cite>
><hr/> 

## <i class="fas fa-clipboard-list "></i> TODO :roller_coaster::
:speech_balloon: Vous devez avoir obligatoirement configuré votre environnement de développement avec les intructions (partie TODO :roller_coaster:) suivantes <i class="fas fa-clipboard-list "></i> :  


Java est tellement populaire qu'il y a des versions concurrentes de la version officielle et surtout des versions entièrement gratuite ce qui ne fut pas toujours le cas des versions de l'OPEN JDK https://fr.wikipedia.org/wiki/OpenJDK.

Afin de vous sensibiliser à l'écosystème du logiciel libre et des différentes versions possibles on utilisera différentes versions du **Java Development Kit (JDK)** qui nous permettrons de développper en <i class="fa-brands fa-java fa-2xl"></i>Java.


- :point_right:  Allez sur [->https://docs.aws.amazon.com/corretto/<-](https://docs.aws.amazon.com/corretto/)
{{< img src="amazoncoretto.png"  align="center" title="amazoncoretto 8" >}}


- :point_right: Puis cliquez sur **Corretto 8 User Guide** puis  **_Downloads_**  (:exclamation: attention il y a plusieurs versions, prenez bien celle de votre OS et surtout la version 8:)

- :point_right: Puis suivez le guide jusqu'à la **partie 3)** comprise (pas besoin de faire le point 4 et 5) :sunglasses: https://docs.aws.amazon.com/corretto/latest/corretto-8-ug/windows-install.html 

- :point_right: Installez-le dans un dossier spécifique car vous installerez différentes versions ultérieurement et vous aurez besoin de le linker avec votre IDE (Éditeur pour développer).
{{< img src="amazoncorettodestfolder.png"  align="center" title="c:\utils\java\amazoncoretto" >}}

- :point_right:  Allez sur  [-> https://www.eclipse.org/downloads/packages/release/2018-12/r <-](https://www.eclipse.org/downloads/packages/release/2018-12/r)
Télécharger la version d'**Eclipse IDE for Enterprise Java Developers** pour votre **OS** puis dezipper la
{{< img src="eclipse.bmp"  align="center" title="Eclipse IDE for Enterprise Java Developers" >}}

   - Au lancement d'Eclipse vous devez spécifier un repertoire de travail, nommez le comme suit : C:\Workspace\Eclipse-2018-12-r (on utilisera plusieurs IDE et les repertoires de travail ne sont pas compatibles entre eux alors faites attention:exclamation::exclamation::exclamation:)


   - Eclipse sera votre IDE pour développer en JavaEE, là encore il y a une multitude de versions, nous choisirons celle-ci qui est compatible avec le JDK et qui ne consomme pas trop en mémoire.

- :point_right:  Allez sur  [-> https://www.apachefriends.org/fr/download.html <-](https://www.apachefriends.org/fr/download.html)

   - Téléchargez la XAMPP dans le dossier de votre choix (notez le car on y retournera).
   - On finira l'installation et la configuration ensemble :exclamation::exclamation:
{{< img src="xampp.bmp"  align="center" title="Xampp" >}}

- :point_right:  Allez sur  [-> http://tomcat.apache.org/whichversion.html <-](http://tomcat.apache.org/whichversion.html)

   - Téléchargez la **Tomcat 9** dans le dossier de votre choix (notez le car on y retournera).
   - On finira l'installation et la configuration ensemble :exclamation::exclamation:    
{{< img src="tomcat9.bmp"  align="center" title="Xampp" >}}





<div class="d-sm-block  alert alert-success  text-left" role="alert">

:mortar_board: Afin de débuter la Formation sur **<i class="fa-brands fa-java fa-2xl"></i>Java EE** ensemble, vous aurez besoin de suivre les instructions du :books:support et/ou de récupérer les éléments de la <span style='display:FLEX;margin:0'> <img style="vertical-align: bottom;" src="/images/icones/w30/capsule_30.png" alt="C">apsule donnés par le formateur &nbsp; <i class="fas fa-chalkboard-teacher"></i> &nbsp; le jour de la formation :exclamation:

</div>

Merci de garder pour vous les ressources qui vous serons fournies et de ne pas les diffuser :smirk:  
Merci de m'avertir de toute erreur ou coquille qui m'auraient échapées :heart_eyes:

:copyright: :no_entry_sign: Do not distribute :relieved: