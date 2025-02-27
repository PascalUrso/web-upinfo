---
layout: page-contents
show_meta: false
title: "Première année"
subheadline: "Licence Informatique"
logo: "logo-l.png"
header:
    image_fullwidth: "header-valrose-printemps-petite.jpg"

permalink: "/ancien-licence/l1/"
---


{% include alert info="<b>Cette page correspond à l’année 2023/2024. Pour l’année prochaine, merci de consulter [cette page](/licence/l1) </b>" %}


## Organisation de la L1 à Valrose ##

La première année de licence en sciences (campus Valrose) est
commune à beaucoup de disciplines et est sous la responsabilité du
[portail sciences et
technologies](https://univ-cotedazur.fr/portails/portail-sciences-et-technologies). Nous
vous invitons à consulter cette page pour l’organisation générale du
portail (calendrier, question administrative, etc.).


Une présentation des métiers de l’informatique et de la mention
informatique (plus particulièrement de la L1) a été faite lors de la
période enjeux (07/09/2023).  Les transparents correspondants sont
disponibles [ici](/data/licence/présentation-rentrée-licence.pdf).


### Qui contacter et pourquoi ? ###


Si vous êtes étudiant et que vous avez des questions concernant les
inscriptions administratives en L1, merci de voir directement avec le
responsable du portail {% respo portail %} et son adjoint {% respo
portail-adjoint %}. Si vous n’êtes pas encore étudiant et que vous
souhaitez le devenir, veuillez consulter la page concernant les
[candidatures]({% link pages/ancien-licence-admission.md %}).

Pour des questions concernant l’orientation de manière générale, votre
contact au sein du portail est {% respo portail-orientation %}. Pour
tout ce qui concerne votre orientation et votre parcours en vue d’une
licence informatique, vous pouvez contacter le référent L1 pour la
discipline informatique :  {% respo L1 %}.

Pour des questions concernant les UE d’informatique de première année
vous pouvez directement contacter les responsables dont vous trouverez
les noms en cliquant sur le nom de l’UE.

{% comment %}

### Choisir ses cours (UE) ###

Lors de son inscription en première année, l’étudiant choisit une
discipline (informatique, mathématique, électronique, etc.) qui lui
recommande alors un parcours.


Les étudiants ayant choisit une autre discipline qu’informatique,
auront quand même la possibilité de suivre une UE d’informatique au
premier semestre. S’il se découvre un intérêt pour l’informatique, il
aura la possibilé de changer de parcours et de passer en info


Lors de la première année, l’étudiant est déjà inscrit dans un
parcours disciplinaire mais peut découvrir différentes disciplines. Il
aura ainsi la possibilité, s’il le souhaite, de se réorienter vers une
autre discipline du portail SITE (mathématiques, informatiques,
physique, chimie, électronique, science de la terre, etc.).


Durant vos trois années de licence, vous devez choisir quatre UE
scientifiques par semestre ; à cela s’ajoute une UE transversale
obligatoire.

Pour le premier semestre, une UE de mathématique est obligatoire entre
{% syllabus SPUM11 : Math fondements 1 %} et {% syllabus SPUM12 : Math
méthode 1%}. Pour les trois UE suivantes vous devez choisir trois
disciplines distinctes (dont éventuellement une autre de math).

Pour le second semestre, une UE de mathématique est obligatoire entre
{% syllabus SPUM21 : Math fondements 2 %} et {% syllabus SPUM22 : Math
méthode 2 %}. Chaque discipline propose alors deux UE qu’il faudra
suivre pour continuer dans la L2 correspondante. Les règles précises
dépendent de chaque disciplines.

Le principe du portail est de pouvoir essayer, se tromper, changer
d’avis afin de choisir le parcours qui vous correspond au mieux. Ceci
étant, pour éviter de trop complexifier la présentation, nous allons
dorénavement présenter le parcours type à choisir pour ceux qui
savent déjà vouloir continuer en informatique.

Pour une présentation plus générale, il existe un cours moodle
public : [S'orienter en Sciences et
Technologies](https://opencourses.univ-cotedazur.fr/course/search.php?search=portail+sciences+et+Technologies)



{% endcomment %}


## L’informatique en L1 ##

Chaque année de licence, les étudiants doivent suivre quatre UE
scientifiques ainsi qu’une UE commune à tous les étudiants, les
compétences transversales (anglais, etc.).


### Vous êtes inscrits dans le parcours informatique ###


Au premier semestre, vous ne suivez qu’une UE d’informatique. Cela
vous permet de changer de parcours si vous changez d’avis en cours de
semestre. Typiquement, un premier semestre dans le parcours
informatique vous permet de faire un second semestre en électronique
ou en mathématiques.

{% include ancien-cours-parcours entry="S1" %}





Lors du second semestre, vous commencez à vous spécialiser avec deux
UE d’informatique. À cela s’ajoute une UE de mathématiques
obligatoire : {% syllabus SPUM21 : Math fondements 2 %}.

Pour la quatrième UE du semestre, vous avez le choix entre quatre
options, deux de mathématique, deux d’électronique.



{% include ancien-cours-parcours entry="S2" %}

### Vous souhaitez faire une autre licence  ###

Ce n’est pas grave, ça arrive à des gens biens. Dans ce cas, on vous
conseille de choisir au premier semestre le cours d’{% UE L1-IIW
%}. C’est un cours d’introduction à la programmation destiné à ceux
qui ne veulent pas se spécialiser dans l’informatique mais qui veulent
malgré tout apprendre à programmer. Si vous hésitez sérieusement à
continuer en informatique, on vous conseille cependant et si possible
de suivre l’UE destiné aux informaticiens : {% UE L1-BI %}



Pour le second semestre, vous pouvez choisir une UE d’informatique. On
vous conseille plutôt le cours de {% UE L1-PI %}. Ce dernier reste
pertinent même si vous avez déjà suivie {% UE L1-IIW %} au premier
semestre qui reste une UE d’introduction.  Pour ceux déjà à l’aise
avec la programmation et veulent découvrir un autre aspect de
l’informatique, vous pouvez choisir à la place {% UE L1-sys-1 %} pour
apprendre l’utilisation avancée d’un ordinateur sous Unix.



## Présentation des UE de L1 ##

### Premier semestre ###

{% include ancien-cours-description-semestre annee='L1-info' semestre='S1' %}

### Second semestre ###

{% include ancien-cours-description-semestre annee='L1-info' semestre='S2' %}


## Règles pour valider l’année

Pour valider l’année de L1 informatique et passer en L2 informatique
vous devez valider au moins quatre UE scientifiques.

En particulier vous devez valider deux UE d’informatique parmi :

1. : {% UE L1-BI %}
2. : {% UE L1-sys-1 %}
3. : {% UE L1-PI %} (ou éventuellement {%UE L1-IIW%}).

Ainsi que deux UE de mathématiques parmi:

1. {% syllabus SPUM11 : Math fondements 1 %}
2. {% syllabus SPUM13 : Math approfondissement 1 %}
3. {% syllabus SPUM21 : Math fondements 2 %}
4. {% syllabus SPUM22 : Math méthode 2 %}
5. {% syllabus SPUM23 : Math approfondissement 2 %}

En plus de cela, vous devez avoir 10 de moyenne.
- 10 de moyenne générale en sciences (8 meilleures UE scientifiques).
- 10 de moyenne avec les CT

{% comment %}

## Organisation ##


Nota bene : dans tout le texte, les UE correspondent aux UE disciplinaires et non aux UE de Compétences Transversales (non concernées par les dispositifs), les UE disciplinaires du portail sont associées à un semestre qui indique aussi leur niveau (S1, S2 pour les UE de niveau L1 ; S3, S4 pour les UE de niveau L2 ; S5, S6 pour les UE de niveau L3).

### Philosophie de base du portail ST ###

Le portail Sciences et Technologies a été créé pour flexibiliser les études en Sciences au niveau de Licence dans
les disciplines Mathématiques, Informatiques, MIASHS, Physique, Chimie, Electronique et Sciences de la Terre au
regard du nouvel arrêté de la Licence.

L’idée de base déposée est très simple : avec l’aide d’une direction d’études l’étudiant(e) du portail construit
un parcours formé d’au moins 24 UE (=blocs à 6 ECTS) parmi l’offre de formation complète du portail (Licence à
la carte). La durée normale est trois ans – et pendant ce temps l’étudiant doit aussi suivre 6 UE (36 ECTS) de
compétences transversales. La validation de 180 ECTS donnera alors lieu au diplôme de L3 Sciences et Technologies.
Si de plus au moins 84 ECTS sont acquises dans une discipline alors l’étudiant aura droit à la mention de la
Licence dans cette discipline.

Le portail s’engage à trouver un mode de fonctionnement qui pourra réaliser cette philosophie aussi bien que
possible dans les limites de nos infrastructures administratives et pédagogiques.

### Généralités ###

Les étudiant.e.s inscrit.e.s au niveau L1/L2 du portail Sciences et Technologies (SITE) sont sous la
responsabilité de la coordination centrale du portail (le responsable et son adjoint), assistée par la commission
pédagogique du portail SITE. La commission pédagogique est formellement composée du responsable du portail (ou son
représentant), du (ou des) ROSP du portail (ou son représentant) et d’un membre de chaque mention du portail (ou
de son représentant).

En fonction des résultats de son parcours (y compris son parcours hors portail) l’étudiant est autorisé à
s’inscrire dans les UE de semestre impair/pair des années supérieures (en fonction des prérequis éventuels de
chaque UE). La gestion des étudiants restera sous la responsabilité de la coordination centrale du portail jusqu’à
l’inscription administrative dans une étape de L3 disciplinaire. Pour les étudiants CPGE, la commission mixte ad
hoc prévue par les conventions UCA-Lycées pourrait être assistée par la commission pédagogique pour proposer à
l’étudiant un parcours pédagogique prenant en compte ses acquis de CPGE.

Une commission pédagogique disciplinaire (sous la direction du responsable de la L3 disciplinaire) se prononce sur
l’autorisation d’inscription des étudiants dans la mention disciplinaire demandée (en fonction des UE
disciplinaires validées lors des années précédentes et le cas échéant du parcours d’un étudiant hors portail).
Cette année L3 disciplinaire est ensuite gérée par le coordonnateur disciplinaire.

Si un étudiant ne peut satisfaire aux conditions d’accès à la mention disciplinaire de son choix, il restera inscrit dans la Licence Sciences et Technologies pour la totalité de son parcours dans le portail.


### L’étape L1 portail Sciences et Technologies (PO1, PO0) ###

Les étudiants entrants sont autorisés à s’inscrire via Parcoursup ou Etudes en France (dossiers visés par les
responsables de portail, la commission Parcoursup et/ou les responsables disciplinaires)

Les étudiants sont admis en parcours normal (PO1) ou parcours aménagé (PO0, appelé aussi « Oui-si »).

Dans l’étape PO1 SITE l’étudiant(e) choisit 4 UE pour son premier semestre dans le portail dont 1 UE obligatoire
de Mathématiques. Suivant son contrat pédagogique, et uniquement avec l’accord de la direction d’études, un(e)
étudiant(e) pourra s’inscrire à plus que 4 UE par semestre à partir du deuxième semestre. C’est le cas notamment
des étudiants qui veulent se diriger vers le parcours 2D PC et des étudiants en phase test pour une admission en
double licence.

Dans l’étape PO0 SITE l’étudiant(e) doit obligatoirement suivre l’UE Bases des Mathématiques et la Méthodologie
qui est associée à cette UE (sauf s’il/elle a déjà validé une UE de Mathématiques du portail). Puis l’étudiant(e)
choisit 2 UE pour son premier semestre. Suivant son contrat pédagogique, et uniquement avec l’accord de la
direction d’études, un(e) étudiant(e) pourra s’inscrire à plus que 2 UE par semestre à partir du deuxième
semestre.

Suivant son contrat pédagogique, et après discussion avec un ROSP, un étudiant pourra aussi s’inscrire à moins de
4 UE par semestre. C’est le cas notamment des étudiants qui passent une deuxième année dans l’étape PO1 ou ceux
qui sont inscrits sur l’étape PO0, qui auront l’obligation à la base de faire leur première année en 2 ans et de
suivre les dispositifs d’accompagnement pédagogiques.

A l’issue de chaque semestre, un jury de portail validera les notes de chaque UE et les bonus obtenus par les
étudiants (Sport et Engagement). Le jury valide le statut acquis/non acquis des UE suivies par les étudiants.

Il n’y a aucune compensation entre les UE à ce stade. Les points bonus sont conservés.

Un(e) étudiant(e) ayant validé au moins 4 UE de la maquette PO1 SITE est autorisé(e) à passer en PO2 SITE. Ceci
est valable aussi pour les étudiant(e)s du parcours aménagé (Oui-si).

Un(e) étudiant(e) validant moins de 4 UE disciplinaire redouble son année de L1 en PO1 SITE (mais une dérogation
en cas de trois UE validées peut être accordé par le responsable du portail en concertation avec la commission
pédagogique). Le responsable du portail préside un seul jury de passage annuel après les deuxièmes sessions pour
constater le droit de passages des étudiant(e)s.

Un(e) étudiant(e) validant moins de 2 UE sera inscrit dans l’étape du parcours aménagé (Oui-si) et passera donc en
PO0.

Un(e) étudiant(e) du parcours aménagé (Oui-si) qui n’est pas assidu(e) aux dispositifs d’accompagnement pourra se
voir désinscrit(e) de la Faculté des Sciences.

Un(e) étudiant(e) en deuxième année de l’étape PO0 (Oui-Si) qui n’a validé aucune UE disciplinaire lors de sa
première année PO0 ne peut prendre que 2 UE au S1 et 2 UE au S2 (comme un(e) primo inscrit(e)).

Un(e) étudiant(e) en deuxième année de l’étape PO0 (Oui-Si) ayant validé au moins deux UE (ou une UE et Bases des
Mathématiques) lors de sa première année PO0 est autorisé(e) à s’inscrire dans 3 UE par semestre.

{% endcomment %}
