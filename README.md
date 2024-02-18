![](https://img.shields.io/badge/Github-Classroom-green.svg)

# Guide Github Classroom

Une présentation de la plateforme [Github Classroom](https://classroom.github.com/) qui permet de gérer des devoirs dans une salle de classe et surtout de les automatiser. On retrouve des [modèles de TP](#des-modèles-de-devoir) avec notation automatique sous forme de badges pour de nombreux langages (bash, C++, Java, PHP, Python, Javascript, Dart, Go) et _frameworks_ (Qt, Android, PlatformIO, Flutter).


- [Guide Github Classroom](#guide-github-classroom)
  - [GitHub Classroom](#github-classroom)
    - [Créer un modèle de dépôt](#créer-un-modèle-de-dépôt)
    - [Créer une classe](#créer-une-classe)
    - [Créer un devoir](#créer-un-devoir)
    - [Le devoir](#le-devoir)
    - [_Feedback_](#feedback)
    - [Extension Visual Studio Code](#extension-visual-studio-code)
    - [Un devoir avec auto-test](#un-devoir-avec-auto-test)
  - [Des modèles de devoir](#des-modèles-de-devoir)
  - [Aperçus](#aperçus)
  - [Auteurs](#auteurs)

---

## GitHub Classroom

[Github](https://github.com/) a un programme pour l'[éducation](https://docs.github.com/fr/education) qui comprend l'(excellent) outil [Github Classroom](https://classroom.github.com/).

[GitHub Classroom](https://classroom.github.com/) automatise la création et le contrôle d'accès de dépôts [GitHub](https://github.com/) pour l'enseignement. [GitHub Classroom](https://classroom.github.com/) s'adresse aux étudiants pour récupérer un code de démarrage et aux enseignants pour la collecte des devoirs.

![Le logo Classroom](./images/classroom-logo.png)

[GitHub Classroom](https://classroom.github.com/) est gratuit pour tous. Il est possible aussi de profiter des avantages de [GitHub Education](https://education.github.com/) (étudiants et enseignants).

![GitHub Education](./images/classroom-education.png)

https://fr.wikipedia.org/wiki/GitHub[GitHub] est un service web d'hébergement et de gestion de développement de logiciels, utilisant le logiciel de gestion de versions Git.

![Le logo GitHub](./images/github-logo.png)

[Git](https://fr.wikipedia.org/wiki/Git) est un logiciel de **gestion de versions décentralisé** (DVCS). C'est un logiciel libre créé par *Linus Torvalds* en 2005. Il s'agit maintenant du logiciel de gestion de versions le plus populaire devant [Subversion](https://fr.wikipedia.org/wiki/Apache_Subversion) (`svn`) qu'il a remplacé avantageusement.

![Le logo Git](./images/git-logo.png)

Sites officiels :

- [GitHub Classroom](https://classroom.github.com/)
- [GitHub Education](https://docs.github.com/en/education)
- [GitHub](https://github.com/)
- [Git](https://git-scm.com/)

Documentation : [Manage coursework with GitHub Classroom](https://docs.github.com/en/education/manage-coursework-with-github-classroom)

Tutoriels : [Basics of setting up Github Classroom](https://docs.github.com/fr/education/manage-coursework-with-github-classroom/get-started-with-github-classroom/basics-of-setting-up-github-classroom)

### Créer un modèle de dépôt

Il faut créer préalablement un dépôt (_repository_) dans [GitHub](https://github.com/) :

![](./images/classroom-create-repository.png)

Puis le paramètrer en "modèle" (_template_):

![](./images/classroom-template-repository.png)

### Créer une classe

On commence par créer une nouvelle classe (_classroom_) :

![](./images/classroom-new.png)

Exemple :

![](./images/classroom-github.png)

> [!NOTE]
> On pourra ensuite créer des devoirs (_assignments_) pour cette classe.

Les étudiants de cette classe :

![](./images/classroom-students.png)

On peut connecter un système de gestion de cours comme [Google Classroom]https://classroom.google.com/) ou importer une liste des étudiants au format CSV.

Et les enseignants et administrateurs :

![](./images/classroom-tas-and-admins.png)

L'onglet _Settings_ permet notamment de connecter un système de gestion de cours comme [Google Classroom](https://classroom.google.com/) (afin de récupèrer la liste des étudiants) :

![](./images/classroom-settings.png)

On se connecte à [Google Classroom](https://classroom.google.com/) :

![](./images/classroom-connect-lms.png)

Et on sélectionne un cours :

![](./images/classroom-connect-google.png)

[GitHub Classroom](https://classroom.github.com/) récupère la liste des étudiants ce qui facilitera l'attibution des devoirs par la suite.

### Créer un devoir

On peut créer des devoirs (_assignments_) individuels ou de groupe :

![](./images/classroom-new-assignement-1.png)

> [!NOTE]
> Pour un devoir individuel, GitHub Classroom nomme les dépôts par le préfixe du dépôt du devoir et le nom d'utilisateur GitHub de l'étudiant. Un devoir de groupe est un travail de cours collaboratif pour des groupes d'étudiants sur GitHub Classroom. Les étudiants pourront travailler ensemble sur un devoir de groupe dans un dépôt partagé, comme une équipe de développeurs professionnels.

On sélectionne ensuite le modèle de dépôt :

![](./images/classroom-new-assignement-2.png)

On termine la création :

![](./images/classroom-new-assignement-3.png)

On obtient une invitation que l'on peut partager avec les étudiants concernés :

![](./images/classroom-new-assignement-4.png)

### Le devoir

L'étudiant accepte le devoir :

![](./images/classroom-accepted-assignment.png)

Et il est prêt à "travailler" sur le dépôt :

![](./images/classroom-student-ready.png)

GitHub a créé un dépôt privé dans l'organisation :

![](./images/classroom-etudiant-organisation.png)

Le nom du dépôt possède en suffixe le nom du compte GitHub de l'étudiant :

![](./images/classroom-repository-etudiant.png)

Le dépôt contient une copie du dépôt "modèle" :

![](./images/classroom-repository-etudiant-vue.png)

L'enseignant reçoit un email confirmant l'inscription de l'étudiant au devoir :

![](./images/classroom-email-teacher.png)

L'enseignant "voit" (et peut accèder à) l'ensemble des devoirs étudiants (et l'évolution des _commits_) et peut récupérer l'ensemble des dépôts (_Download Repositories_) :

![](./images/classroom-assignement-etudiant.png)

Pour récupérer les travaux, [GitHub Classroom](https://classroom.github.com/) fournit un [assistant](https://classroom.github.com/assistant) pour Windows(C), MacOS(C) et Linux.

![](./images/classroom-assistant-0.png)

Ou directement à partir de l'outil :

![](./images/classroom-assistant-1.png)

On sélectionne ensuite les travaux à récupérer :

![](./images/classroom-assistant-2.png)

On peut préciser le chemin de stockage de l'archive :

![](./images/classroom-assistant-3.png)

On obtient :

![](./images/classroom-assistant-archive.png)

### _Feedback_

Lors de la création du devoir, il est possible d'y associer une _Pull Request_ pour assurer une communication Étudiant/Enseignant sur ce devoir :

![](./images/classroom-new-assignement-pull-request.png)

On reçoit alors un email :

![](./images/classroom-email-student.png)

La _Pull Request_ dans GitHub :

![](./images/classroom-pr.png)

Elle permet :

![](./images/classroom-pr-feedback.png)

### Extension Visual Studio Code

[Visual Studio Code](https://code.visualstudio.com/) possède une extension dédiée à [GitHub.classroom](https://marketplace.visualstudio.com/items?itemName=GitHub.classroom).

![](./images/classroom-vscode-extension.png)

Elle permet de parcourir les devoirs et de commencer à travailler dessus. Elle apparaît dans l'onglet de l'extension [GitHub.vscode-pull-request-github](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github) et il faut commencer par s'authentifier. La liste des devoirs apparaît alors dans l'arborescence.

### Un devoir avec auto-test

Il est possible de configurer un devoir avec des tests exécutés automatiquement pour chaque soumission (`push`) de code dans le dépôt.

[GitHub Actions](https://docs.github.com/en/actions) exécutera les commandes pour le test automatique dans un environnement Linux contenant le code le plus récent de l'étudiant. Il est possible d'y associer des points pour obtenir une note finale pour le devoir.

Lien : [Use autograding](https://docs.github.com/en/education/manage-coursework-with-github-classroom/teach-with-github-classroom/use-autograding)

Il est possible d'ajouter des tests à la création du devoir ou plus tard en l'éditant :

![](./images/classroom-add-test.png)

Il existe deux méthodes distinctes : les tests d'entrée/sortie et les tests de commande d'exécution.

![](./images/classroom-choix-test.png)

Un test de commande d'exécution :

![](./images/classroom-test-run.png)

Un test d'entrée/sortie :

![](./images/classroom-test-io.png)

On peut suivre l'exécution du test dans GitHub Actions :

//![](./images/classroom-result-commit-fail.png)

![](./images/classroom-result-actions-success.png)

Et dans Classroom :

![](./images/classroom-result-student-success.png)

Ici, le test n'est pas passé :

![](./images/classroom-result-student-fail.png)

Les détails dans GitHub Actions :

![](./images/classroom-result-actions-fail.png)

Pour les tests de commande d'exécution, il est intéressant d'y associer des *tests unitaires*.

Il y a une exemple fourni pour C++ avec `make` et [Catch2](https://github.com/catchorg/Catch2).

[Autograding Example C++](https://github.com/education/autograding-example-cpp)

![](./images/classroom-autograding.png)

## Des modèles de devoir

Chaque exemple de devoir intègre la notation automatique avec sa visualisation sous forme de badge :

- ![C++ Badge](https://img.shields.io/badge/C%2B%2B-00599C?logo=cplusplus&logoColor=fff&style=plastic)

    https://github.com/btssn-lasalle84/tp-poo-cpp

- ![GNU Bash Badge](https://img.shields.io/badge/GNU%20Bash-4EAA25?logo=gnubash&logoColor=fff&style=plastic) ![Linux Badge](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=000&style=plastic) ![Ubuntu Badge](https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=fff&style=plastic)

    https://github.com/btssn-lasalle84/tp-script-bash

- ![C++ Badge](https://img.shields.io/badge/C%2B%2B-00599C?logo=cplusplus&logoColor=fff&style=plastic) ![Qt Badge](https://img.shields.io/badge/Qt-41CD52?logo=qt&logoColor=fff&style=plastic) ![PlatformIO](https://img.shields.io/badge/build%20with-PlatformIO-orange?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB3aWR0aD0iMjUwMCIgaGVpZ2h0PSIyNTAwIiB2aWV3Qm94PSIwIDAgMjU2IDI1NiIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiBwcmVzZXJ2ZUFzcGVjdFJhdGlvPSJ4TWlkWU1pZCI+PHBhdGggZD0iTTEyOCAwQzkzLjgxIDAgNjEuNjY2IDEzLjMxNCAzNy40OSAzNy40OSAxMy4zMTQgNjEuNjY2IDAgOTMuODEgMCAxMjhjMCAzNC4xOSAxMy4zMTQgNjYuMzM0IDM3LjQ5IDkwLjUxQzYxLjY2NiAyNDIuNjg2IDkzLjgxIDI1NiAxMjggMjU2YzM0LjE5IDAgNjYuMzM0LTEzLjMxNCA5MC41MS0zNy40OUMyNDIuNjg2IDE5NC4zMzQgMjU2IDE2Mi4xOSAyNTYgMTI4YzAtMzQuMTktMTMuMzE0LTY2LjMzNC0zNy40OS05MC41MUMxOTQuMzM0IDEzLjMxNCAxNjIuMTkgMCAxMjggMCIgZmlsbD0iI0ZGN0YwMCIvPjxwYXRoIGQ9Ik0yNDkuMzg2IDEyOGMwIDY3LjA0LTU0LjM0NyAxMjEuMzg2LTEyMS4zODYgMTIxLjM4NkM2MC45NiAyNDkuMzg2IDYuNjEzIDE5NS4wNCA2LjYxMyAxMjggNi42MTMgNjAuOTYgNjAuOTYgNi42MTQgMTI4IDYuNjE0YzY3LjA0IDAgMTIxLjM4NiA1NC4zNDYgMTIxLjM4NiAxMjEuMzg2IiBmaWxsPSIjRkZGIi8+PHBhdGggZD0iTTE2MC44NjkgNzQuMDYybDUuMTQ1LTE4LjUzN2M1LjI2NC0uNDcgOS4zOTItNC44ODYgOS4zOTItMTAuMjczIDAtNS43LTQuNjItMTAuMzItMTAuMzItMTAuMzJzLTEwLjMyIDQuNjItMTAuMzIgMTAuMzJjMCAzLjc1NSAyLjAxMyA3LjAzIDUuMDEgOC44MzdsLTUuMDUgMTguMTk1Yy0xNC40MzctMy42Ny0yNi42MjUtMy4zOS0yNi42MjUtMy4zOWwtMi4yNTggMS4wMXYxNDAuODcybDIuMjU4Ljc1M2MxMy42MTQgMCA3My4xNzctNDEuMTMzIDczLjMyMy04NS4yNyAwLTMxLjYyNC0yMS4wMjMtNDUuODI1LTQwLjU1NS01Mi4xOTd6TTE0Ni41MyAxNjQuOGMtMTEuNjE3LTE4LjU1Ny02LjcwNi02MS43NTEgMjMuNjQzLTY3LjkyNSA4LjMyLTEuMzMzIDE4LjUwOSA0LjEzNCAyMS41MSAxNi4yNzkgNy41ODIgMjUuNzY2LTM3LjAxNSA2MS44NDUtNDUuMTUzIDUxLjY0NnptMTguMjE2LTM5Ljc1MmE5LjM5OSA5LjM5OSAwIDAgMC05LjM5OSA5LjM5OSA5LjM5OSA5LjM5OSAwIDAgMCA5LjQgOS4zOTkgOS4zOTkgOS4zOTkgMCAwIDAgOS4zOTgtOS40IDkuMzk5IDkuMzk5IDAgMCAwLTkuMzk5LTkuMzk4em0yLjgxIDguNjcyYTIuMzc0IDIuMzc0IDAgMSAxIDAtNC43NDkgMi4zNzQgMi4zNzQgMCAwIDEgMCA0Ljc0OXoiIGZpbGw9IiNFNTcyMDAiLz48cGF0aCBkPSJNMTAxLjM3MSA3Mi43MDlsLTUuMDIzLTE4LjkwMWMyLjg3NC0xLjgzMiA0Ljc4Ni01LjA0IDQuNzg2LTguNzAxIDAtNS43LTQuNjItMTAuMzItMTAuMzItMTAuMzItNS42OTkgMC0xMC4zMTkgNC42Mi0xMC4zMTkgMTAuMzIgMCA1LjY4MiA0LjU5MiAxMC4yODkgMTAuMjY3IDEwLjMxN0w5NS44IDc0LjM3OGMtMTkuNjA5IDYuNTEtNDAuODg1IDIwLjc0Mi00MC44ODUgNTEuODguNDM2IDQ1LjAxIDU5LjU3MiA4NS4yNjcgNzMuMTg2IDg1LjI2N1Y2OC44OTJzLTEyLjI1Mi0uMDYyLTI2LjcyOSAzLjgxN3ptMTAuMzk1IDkyLjA5Yy04LjEzOCAxMC4yLTUyLjczNS0yNS44OC00NS4xNTQtNTEuNjQ1IDMuMDAyLTEyLjE0NSAxMy4xOS0xNy42MTIgMjEuNTExLTE2LjI4IDMwLjM1IDYuMTc1IDM1LjI2IDQ5LjM2OSAyMy42NDMgNjcuOTI2em0tMTguODItMzkuNDZhOS4zOTkgOS4zOTkgMCAwIDAtOS4zOTkgOS4zOTggOS4zOTkgOS4zOTkgMCAwIDAgOS40IDkuNCA5LjM5OSA5LjM5OSAwIDAgMCA5LjM5OC05LjQgOS4zOTkgOS4zOTkgMCAwIDAtOS4zOTktOS4zOTl6bS0yLjgxIDguNjcxYTIuMzc0IDIuMzc0IDAgMSAxIDAtNC43NDggMi4zNzQgMi4zNzQgMCAwIDEgMCA0Ljc0OHoiIGZpbGw9IiNGRjdGMDAiLz48L3N2Zz4=)

    https://github.com/btssn-lasalle84/tp-poo-cpp

    https://github.com/btssn-lasalle84/tp-poo-qt

    https://github.com/btssn-lasalle84/tp-poo-platformio

- ![Java Badge](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white&style=plastic) ![Android Badge](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=fff&style=plastic)

    https://github.com/btssn-lasalle84/tp-poo-java

    https://github.com/btssn-lasalle84/tp-poo-android


- ![Python Badge](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff&style=plastic)

    https://github.com/btssn-lasalle84/tp-poo-python

- ![PHP Badge](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=fff&style=plastic)

    https://github.com/btssn-lasalle84/tp-poo-php

- ![JavaScript Badge](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000&style=plastic)

    https://github.com/btssn-lasalle84/tp-poo-javascript

- ![Dart Badge](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=fff&style=plastic) ![Flutter Badge](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=fff&style=plastic)

    https://github.com/btssn-lasalle84/tp-poo-dart

    https://github.com/btssn-lasalle84/tp-poo-flutter

- ![Go Badge](https://img.shields.io/badge/Go-ED8B00?style=for-the-badge&logo=go&logoColor=white&style=plastic)

    https://github.com/btssn-lasalle84/tp-poo-go

## Aperçus

Ma salle de classe pour cette année :

![](images/screenshot-classroom.png)

La vue d'ensemble pour un devoir :

![](images/screenshot-assignment.png)

Le dépôt privé d'un étudiant automatiquement créé par [Github Classroom](https://classroom.github.com/) avec l'évolution de la note à chaque _commit/push_ :

![](images/screenshot-github.png)

Chaque _commit/push_ déclenche un _workflow_ dans Github Actions :

![](images/screenshot-autograding.png)

Lors de la création du devoir, il est possible d’y associer une _Pull Request_ _Feedback_ pour assurer une communication Étudiant/Enseignant sur ce devoir (mettre des commentaires et/ou répondre aux questions d’un étudiant) :

![](images/screenshot-feedback.png)

Les devoirs sont hébergés dans une organisation :

![](images/screenshot-organisation.png)

## Auteurs

- [Thierry VAIRA](thierry.vaira@gmail.com) : [tvaira.free.fr](http://tvaira.free.fr/)

---
©️ 2023 BTS LaSalle Avignon
