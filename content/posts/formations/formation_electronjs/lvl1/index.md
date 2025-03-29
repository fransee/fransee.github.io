---
title: "Formation Electron Initiation"
date: 2025-03-28T11:11:25+00:00
description: Electron formation bases initiation framework javascript
menu:
  sidebar:
    name: Electron Lvl 1
    identifier: electron1_en
    parent: formations_electronjs_en
    weight: 10
---

## _<center>:loudspeaker: Bonjour à tous et à toutes :heavy_exclamation_mark:</center>_

---

<div class="d-sm-block alert alert-info " > <center>
<i class="fas fa-info-circle " style="color: blue;"></i> Au programme de cette formation <i class="fa-classic fa-atom fa-2xl"></i> Electron : </center>
<span class="text-left">

- Créer votre première application
- Importation de modules
- Exécution de l’application Electron
- Débogage avec VS Code
- Débogage avec Chromium DevTools
- Utiliser des scripts de préchargement
- Enrichir le moteur de rendu avec un script de préchargement
- Ajouter des fonctionnalités I II III IV
- Empaqueter votre application
- Création d’une distribution livrable – ajout d’un icon 
- Création d’une distribution livrable EXE – MSI Windows
- Signer son code

</div>

> <img style="float:left; vertical-align: middle;margin-right:0px!important;width:50px" src="electron.png" alt=""> 
> Electron est un environnement permettant de développer des applications multi-plateformes de bureau avec des technologies web (JavaScript, HTML et CSS).
>
>L'infrastructure (backend) est codée en Node.js, et l'interface (frontend) est bâtie sur les outils Chromium, la partie open source de Google Chrome.
>
>Electron est un logiciel libre open source développé par GitHub sous licence MIT.
>
>Electron a notamment permis de développer les éditeurs de texte libres Atom de GitHub et Visual Studio Code de Microsoft
>
> <cite>[ <img style="float:left; margin: 1px; " height="40px" src="/files/images/wikipedia.png"> Wikipedia <i class="fas fa-external-link-alt"></i>](https://fr.wikipedia.org/wiki/Java_(langage) "Définition à lire pour bien comprendre")</cite>
><hr/> 

## <i class="fas fa-clipboard-list "></i> TODO :roller_coaster::
:speech_balloon: Vous devez avoir obligatoirement configuré votre environnement de développement avec les intructions (partie TODO :roller_coaster:) suivantes <i class="fas fa-clipboard-list "></i> :  


Java est tellement populaire qu'il y a des versions concurrentes de la version officielle et surtout des versions entièrement gratuite ce qui ne fut pas toujours le cas des versions de l'OPEN JDK https://fr.wikipedia.org/wiki/OpenJDK.

Afin de vous sensibiliser à l'écosystème du logiciel libre et des différentes versions possibles on utilisera différentes versions du **Java Development Kit (JDK)** qui nous permettrons de développper en <i class="fa-brands fa-java fa-2xl"></i>Java.


- :point_right:  Allez sur [->https://docs.aws.amazon.com/corretto/<-](https://docs.aws.amazon.com/corretto/)
![amazoncoretto.png](amazoncoretto.png)

- :point_right: Puis cliquez sur **Corretto 8 User Guide** puis  **_Downloads_**  (:exclamation: attention il y a plusieurs versions, prenez bien celle de votre OS et surtout la version 8:)

- :point_right: Puis suivez le guide jusqu'à la **partie 3)** comprise (pas besoin de faire le point 4 et 5) :sunglasses: https://docs.aws.amazon.com/corretto/latest/corretto-8-ug/windows-install.html 

- :point_right: Installez-le dans un dossier spécifique car vous installerez différentes versions ultérieurement et vous aurez besoin de le linker avec votre IDE (Éditeur pour développer).
![c:\utils\java\amazoncoretto ](amazoncorettodestfolder.png)

- :point_right:  Allez sur  [-> https://archive.eclipse.org/eclipse/downloads/drops4/R-4.6-201606061100/ <-](https://archive.eclipse.org/eclipse/downloads/drops4/R-4.6-201606061100/)
Télécharger la version d'**Eclipse SDK** pour votre **OS** puis dezipper la

Au lancement d'Eclipse Neon vous devez spécifier un repertoire de travail, nommez le comme suit : (on utilisera plusieurs IDE et les repertoires de travail ne sont pas compatibles entre eux alors faites attention:exclamation::exclamation::exclamation:)
![C:\Workspace\Eclipse-neon](eclipseworkspace.png)

Eclipse sera votre IDE pour développer en java, là encore il y a une multitude de versions, nous choisirons celle-ci qui est compatible avec le JDK et qui ne consomme pas trop en mémoire.

<div class="d-sm-block  alert alert-success  text-left" role="alert">

:mortar_board: Afin de débuter la Formation sur **<i class="fa-brands fa-java fa-2xl"></i>Java Lvl1** ensemble, vous aurez besoin de suivre les instructions du :books:support et/ou de récupérer les éléments de la <span style='display:FLEX;margin:0'> <img style="vertical-align: bottom;" src="/images/icones/w30/capsule_30.png" alt="C">apsule donnés par le formateur &nbsp; <i class="fas fa-chalkboard-teacher"></i> &nbsp; le jour de la formation :exclamation:

</div>

Merci de garder pour vous les ressources qui vous serons fournies et de ne pas les diffuser :smirk:  
Merci de m'avertir de toute erreur ou coquille qui m'auraient échapées :heart_eyes:

:copyright: :no_entry_sign: Do not distribute :relieved: