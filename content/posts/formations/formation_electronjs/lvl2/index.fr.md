---
title: "Formation Electron Avancée"
date: 2025-03-28T10:10:29+00:00
description: Electron formation Avancé framework
menu:
  sidebar:
    name: Electron 2
    identifier: electron2_fr
    parent: formations_electronjs_fr
    weight: 10
---
*<center>:loudspeaker: Bonjour à tous et à toutes :heavy_exclamation_mark:</center>*
---

<div class="d-sm-block alert alert-info " > <center>
<i class="fas fa-info-circle " style="color: blue;"></i> Au programme de cette formation sur la programmation graphique avec AWT, SWING et <i class="fa-brands fa-java fa-2xl"></i> JavaFX : </center>
<span class="text-left">

- 10 - 0 - Introduction a la programmation graphique
- 10 - A - Programmation graphique Avancée  JAVA-FX
- 10 – B - Compléments de programmation
- 10 – C – Architecture Concepts techniques
- 10 – D – Conteneurs Layout-Panes
- 10 – E – Composants de base
- 10 – F – Architecture MVC Gestion Evenement
- 10 – G – FXML SceneBuilder
- 10 – H – Menus Choix Selection
- 10 – I – Panneaux spécialisés
- 10 - J – Boîtes de dialogue
- 10 - K – Feuilles de style CSS
- 10 - L - Jar executable Installeur

</div>

> <img style="float:left; vertical-align: middle;margin-right:0px!important;width:440px" src="440px-JavaFX_Logo.png" alt="">  <div style="clear:both"></div>
> JavaFX est un framework et une bibliothèque d'interface utilisateur issue du projet OpenJFX, qui permet aux développeurs Java de créer une interface graphique pour des applications de bureau, des applications internet riches et des applications smartphones et tablettes tactiles.
>
>Créé à l'origine par Sun MicroSystems, puis développé par Oracle après son rachat et ce, jusqu'à la version 11 du JDK, c'est depuis lors à la communauté OpenJFX que revient la poursuite de son développement1.
>
>Cette bibliothèque a été conçue pour remplacer Swing et AWT, qui ont été développés à partir de la fin des années 90, pour pallier les défauts de ces derniers et fournir de nouvelles fonctionnalités (dont le support des écrans tactiles).
>Le cycle de sortie d'une nouvelle version de JavaFX correspond à celui de Java, soit tous les 6 mois.
>
> <cite>[ <img style="float:left; margin: 1px; " height="40px" src="/files/images/wikipedia.png"> Wikipedia <i class="fas fa-external-link-alt"></i>](https://fr.wikipedia.org/wiki/JavaFX "Définition à lire pour bien comprendre")</cite>
><hr/> 

## <i class="fas fa-clipboard-list "></i> TODO :roller_coaster::
:speech_balloon: Vous devez avoir obligatoirement configuré votre environnement de développement avec les intructions (partie TODO :roller_coaster:) suivantes <i class="fas fa-clipboard-list "></i> :  


Avec l'apparition de la version 8 de Java (en mars 2014), JavaFX devient la bibliothèque de création d'interface graphique officielle du langage Java, le développement de son prédécesseur Swing (avec AWT) étant abandonné, excepté pour les corrections de bogues.

Depuis la version 11 de Java, le projet est dissocié du JDK, pour suivre son propre processus de développement. Toutefois, le numéro de version de JavaFX concorde avec celui du JDK pour indiquer sa compatibilité (car toute application JavaFX est basée sur le JDK)


- :point_right:  Allez sur [->https://docs.aws.amazon.com/corretto/<-](https://docs.aws.amazon.com/corretto/)
![amazoncoretto.png](amazoncoretto.png)

- :point_right: Puis cliquez sur **Corretto 11 User Guide** puis  **_Downloads_**  (:exclamation: attention il y a plusieurs versions, prenez bien celle de votre OS et surtout la version 11:)

- :point_right: Puis suivez le guide jusqu'à la **partie 3)** comprise (pas besoin de faire le point 4 et 5) :sunglasses: https://docs.aws.amazon.com/corretto/latest/corretto-11-ug/windows-install.html 

- :point_right: Installez-le dans un dossier spécifique car vous installerez différentes versions ultérieurement et vous aurez besoin de le linker avec votre IDE (Éditeur pour développer).
![c:\utils\java\amazoncoretto ](amazoncorettodestfolder.png)

- :point_right:  Allez sur  [-> https://www.eclipse.org/downloads/packages/release/2020-12/r <-](https://www.eclipse.org/downloads/packages/release/2020-12/r)
Télécharger la version d'**Eclipse IDE 2020-12 R _for Java Developpers_** pour votre **OS** puis dezipper dans un dossier spécifique, on reviendra dessus le jour J
{{< img src="eclipseIDE.bmp"  align="center" title="Eclipse IDE 2020-12 R pour java" >}}

- :point_right:  Gardez bien la version zippé, ca vous permettra de la reinstaller facilement en cas de mauvaise configuration ce qui pourrait arriver

- :point_right:  Allez sur  [-> https://gluonhq.com/products/javafx/ <-](https://gluonhq.com/products/javafx/)

On va télécharger et dézipper les versions 11.02  « JavaFX Windows SDK » et « JavaFX Windows jmods » (dans les versions archivées) dans un dossier spécifique que l'on réutilisera le jour de la formation
{{< img src="javafxsdketjmod.bmp"  align="center" title="" >}}


- :point_right:  Allez sur  [-> https://gluonhq.com/products/scene-builder/ <-](https://gluonhq.com/products/scene-builder/)
Télécharger la version d'**8.5 ou la dernière _(mais pas la candidate)_** pour votre **OS** puis dezipper dans un dossier spécifique, on reviendra dessus le jour J
{{< img src="scenebuilder.bmp"  align="center" title="scenebuilder" >}}



<div class="d-sm-block  alert alert-success  text-left" role="alert">

:mortar_board: Afin de débuter la Formation sur **<i class="fa-brands fa-java fa-2xl"></i>Java programmation graphique avec AWT, SWING et JAVAFX** ensemble, vous aurez besoin de suivre les instructions du :books:support et/ou de récupérer les éléments de la <span style='display:FLEX;margin:0'> <img style="vertical-align: bottom;" src="/images/icones/w30/capsule_30.png" alt="C">apsule donnés par le formateur &nbsp; <i class="fas fa-chalkboard-teacher"></i> &nbsp; le jour de la formation :exclamation:

</div>

Merci de garder pour vous les ressources qui vous serons fournies et de ne pas les diffuser :smirk:  
Merci de m'avertir de toute erreur ou coquille qui m'auraient échapées :heart_eyes:

:copyright: :no_entry_sign: Do not distribute :relieved: