# Guide de préparation d'entrée en ING1 à l'EPITA

[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/pp5x/epita-ing1-prep/blob/main/README.md)
[![fr](https://img.shields.io/badge/lang-fr-blue.svg)](https://github.com/pp5x/epita-ing1-prep/blob/main/README.fr.md)

![EPITA logo](res/epita.svg)

- Table des matières
  - [Introduction](#introduction)
    - [Se préparer pour la Piscine](#se-préparer-pour-la-piscine)
    - [Harmonisation informatique](#harmonisation-informatique)
    - [Concrêtement ?](#concrêtement-)
  - [Ressources](#ressources)

## Introduction

Bienvenue à l'EPITA (École Pour l'Informatique et les Techniques Avancées). Si
vous lisez ceci, c'est probablement parce que vous souhaitez vous préparer à
rejoindre l'ING1 (première année du cycle ingénieur). Ce guide est destiné aux
étudiants ayant passés les concours Advance Parallèle, Advance CPGE,
apprentissage ou encore les échanges internationaux (Exchanges). Alors que le
mois de septembre approche, la rentrée se profile à l'horizon. Que vous soyez
en train de revoir vos cours de programmation ou à profiter au bord de la
Piscine, ce guide vous permettra de commencer l'année un peu plus préparé.

En parlant de **Piscine** 🏊‍♂️...

### Se préparer pour la Piscine

Depuis la création de l'école en 1984, la Piscine est un atelier de
programmation en C/UNIX. On y apprend les bases de la programmation en C, on y
implémente *from scratch* des algorithmes, des structures données et à
construire des programmes simples qui s'interfacent avec le système
d'exploitation. Cet atelier *ressource* pose les fondamentaux pour que par la
suite les étudiants soient capables de réaliser des projets de programmation de
plus en plus complexes, d'abord seuls puis en équipe. On apprend à collaborer
sur des projets de plus en plus grands, ce qui est proche du monde du travail
en entreprise. Cette expertise s'acquiert avec le temps et par une pratique
régulière de la programmation.

### Harmonisation informatique

L'EPITA se distingue par une certaine identité dans la construction de ses
activités. On cherche à acquérir une *expertise* en informatique et on souhaite
devenir *efficace* dans la réalisation des projets.

Afin de s'acculturer, le premier mois dispense les enseignements suivants (pour
ceux qui débutent en informatique ou qui ont peu de pratique) :

- Mon PC & Systèmes UNIX
- Algorithmes et structures de données
- Initiation à la programmation
- Architecture des ordinateurs

Le but de l'harmonisation informatique est d'amener tout le monde à prendre
goût à la programmation, à personnaliser son système, de chercher à comprendre
*pourquoi* les choses sont comme elles sont et *comment* tout cela fonctionne !
En d'autre termes, l'apprentissage n'est pas uniquement théorique, il est rendu
possible par la mise en place d'un *environnement* particulier. Vous serez
amenés à quitter votre zone de confort et à vous adapter aux contraintes.

### Concrêtement ?

Voici une liste non exhaustive de ce que vous serez amené à faire :

- Installer Linux nativement sur votre machine personnelle et le configurer
- Utiliser un terminal pour taper des lignes de commande en shell
- Chainer des commandes entre elles pour faire un traitement de données
- Utiliser un éditeur en mode texte comme `vim` ou `emacs`
- Réimplémenter une structure de données comme une liste chaînée en C en
  faisant appel à un allocateur de mémoire
- Compiler et lancer votre programme en ligne de commande
- Personnaliser votre environnement de travail sous i3
- Apprendre à saisir du texte sur votre clavier efficacement (dactylographie)
- Programmer en assembleur dans un émulateur
- Utiliser `git` pour sauvegarder son travail

## Ressources

En attendant d'avoir accès au contenu pédagogique mis en place par l'EPITA,
voici un regroupement de diverses ressources que vous pourriez explorer pendant
environ deux semaines (la régularité est plus importante que la quantité).

Pas d'inquiétude si vous ne faites pas tout, c'est long et c'est normal ! Nous
verrons tout cela bientôt.

### Linux

Linux est un système d'exploitation au même titre que Windows ou MacOS.
L'apprentissage de la programmation se fait quasi-exclusivement sur cette
plateforme.

#### Niveau 1 : Ubuntu

Si vous n'avez jamais utilisé Linux, je vous recommande Ubuntu comme première
distribution.

Vous retrouverez une initiation à Linux orientée Ubuntu à l'adresse suivante :

- [OpenClassRooms - Initiez-vous à Linux](https://openclassrooms.com/fr/courses/7170491-initiez-vous-a-linux)

#### Niveau 2 : ArchLinux

Si vous avez déjà installé Linux chez vous et que vous êtes à l'aise avec la
ligne de commande et l'édition de fichier, je vous recommande plutôt de
réaliser une installation d'[ArchLinux](https://wiki.archlinux.org/) (dans une
machine virtuelle dans un premier temps, mais ensuite envisagez de l'avoir en
natif).

ArchLinux est une distribution où l'on part de zéro pour construire son
système. Ce principe amène donc son utilisateur à résoudre des problèmes au fur
et à mesure qu'il souhaite avoir des fonctionnalités supplémentaires (comme le
wifi par exemple).

- [ArchLinux - Installation Guide](https://wiki.archlinux.org/title/Installation_guide)

Window manager (WM) recommandé : i3

### Programmation

#### Python

Dans un premier temps, s'assurer que l'on est capable de réaliser des petits
programmes, algorithmes en Python et si possible d'implémenter des structures
de données.

C'est aussi l'occasion si vous ne l'avez jamais fait de s'intéresser aux
*tests* (pytest) qui permettent de valider le bon fonctionnement d'un code. Ils
sont essentiels pour batîr des programmes plus conséquents, mais permettent
aussi de programmer plus rapidement.

- [Zeste de Savoir - Python](https://zestedesavoir.com/tutoriels/2514/un-zeste-de-python/)
- [PyFlo - A Free, Interactive Guide to Python Programming](https://pyflo.net/)
- <https://fr.futurecoder.io/course>
- [https://nostarch.com/learn-code-solving-problems](https://nostarch.com/learn-code-solving-problems)

#### C/UNIX

S'intéresser à la gestion de la mémoire et aux structures de données.

- [Zeste de Savoir - Le language C](https://zestedesavoir.com/tutoriels/755/le-langage-c-1/)
- [Learn X in Y minutes - C](https://learnxinyminutes.com/docs/c/)
- <https://nostarch.com/Effective_C>

### Algorithmes

- [Zeste de Savoir - Algorithmique pour l'apprenti programmeur](https://zestedesavoir.com/tutoriels/621/algorithmique-pour-lapprenti-programmeur/)
- <https://www.coursera.org/learn/algorithms-part1>
- [VisuAlgo](https://visualgo.net)

#### Sur quoi se concentrer ?

- Manipulation des chaines de caractères
- Manipulation des tableaux et algorithmes de recherche
- Implémentation des listes chainées (avec chainage)

### Editeur de texte

#### vim

`vim` sera probablement votre éditeur de texte pour le semestre à venir. Une
fois qu'on est habitué à l'édition "modale", on devient très efficace lorsqu'il
s'agit de modifier ou naviguer du texte. Un tutoriel est normalement installé
avec l'éditeur, il se lance avec `vimtutor`.

Il existe de nombreuses ressources en ligne :

- <https://github.com/iggredible/Learn-Vim>
- <https://www.openvim.com/tutorial.html>

N'en faites pas nécessairement une priorité, le plus d'important est d'être à
l'aise avec son éditeur pour écrire quelques programmes en Python ou en C.

## Explorer et aller plus loin

- [No Starch Press](https://nostarch.com/): nombreux ouvrages sur la
  programmation et les systèmes.
- [Advent of Code](https://adventofcode.com/): challenges de programmation
- [LeetCode](https://leetcode.com/): problèmes de programmation
