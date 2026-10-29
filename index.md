All documents listed below are written in French, unless specified otherwise. 

<div align="center" style="font-size: 2.0em;">
Liste des séances de travaux pratiques
</div>

<div align="center" style="font-size: 2.0em;">
Bac Pro CIEL, Rectorat de Poitiers
</div>

(1) Séquence LTspice 1

LTspice est un simulateur électrique qui permet d’analyser les circuits analogiques. Il est offert par la société Analog Devices. Il repose sur un logiciel libre appelé Spice développé par l’université de Californie à Berkeley (UC Berkeley). Spice signifie « Simulation Program with Integrated Circuit Emphasis ».

Spice permet en fait de simuler le comportement des circuits électroniques analogiques conçus à partir de composants comme les résistances, condensateurs, inductances, diodes, transistors, etc.

LTspice est un logiciel qui ajoute à Spice une interface graphique ainsi qu’une bibliothèque de composants afin de rendre son utilisation plus conviviale.

Vous pouvez télécharger LTspice à partir du site de Analog Devices.

Il faut peu de temps pour apprendre à utiliser ce logiciel car il est très convivial. Votre professeur vous expliquera comment faire la saisie d’un circuit électronique (schematic capture, en anglais) et ensuite comment simuler le comportement de ce circuit dans des conditions diverses et variées.

* [TP 1 : Pont diviseur de tension](1 Pont Diviseur de Tension.pdf) 
* [TP 2 : Résistance alimentée par une tension alternative](2 Resistance in AC Mode.pdf)
* [TP 3 : Analyse d'un circuit résistif](3 Circuit Resistif.pdf)
* [TP 4 : Condensateur alimenté par une tension alternative](4 Capacitance in AC Mode.pdf)
* [TP 5 : Condensateur de découplage](5 Decoupling Capacitor.pdf) 
* [TP 6 : Impédance d'un condensateur](6 Impedance of a Capacitance.pdf)
* [TP 7 : Inductance alimentée par un courant alternatif](7 Inductance in AC Mode.pdf)
* [TP 8 : Facteur de puissance d'une installation électrique](8 Power Factor.pdf)

(2) Séquence électronique numérique 1 sur Tinkercad

Cette séquence introduit les apprenants aux concepts fondamentaux des circuits électroniques numériques (digital electronic circuits), c’est-à-dire les circuits qui fonctionnent en utilisant seulement deux niveaux de tension stables : un niveau bas, égal à 0 volt, qui est appelé « 0 logique » et un niveau haut, égal à la tension d’alimentation du circuit, appelé « 1 logique ».

Les circuits numériques sont tous, de nos jours, conçus à l’aide de composants analogiques appelés « transistors ». Il s’agit plus précisément de transistors à effet de champ (FET, field-effect transistors) fonctionnant comme de minuscules interrupteurs qui peuvent bloquer ou, au contraire, laisser passer un courant électrique, selon la valeur d’une tension de contrôle qui leur est appliquée.

La possibilité de fabriquer des circuits intégrés numériques à partir de milliards de transistors FET implantés sur des puces de silicium est la raison première derrière l’essor des technologies de l’information et de la communication au cours des dernières décennies. Sans l’électronique numérique, il n’y aurait, par exemple, ni ordinateurs ni téléphones mobiles.

Nous allons donc, au cours de cette première séquence, commencer notre voyage à travers le monde fascinant des circuits électroniques numériques. Nous allons construire plusieurs circuits, ainsi que simuler le fonctionnement de ces derniers, en utilisant le logiciel Tinkercad Circuits. Sur le plan purement pratique, nous allons également construire, à l’aide du logiciel KiCad, plusieurs circuits imprimés.

La représentation décimale est utilisée par les humains depuis la nuit des temps. Elle est aussi appelée la base 10 car elle utilise 10 chiffres.

La représentation binaire est utilisée par les circuits électroniques numériques (ordinateurs par exemple). Elle est aussi appelée la base 2 car elle utilise 2 chiffres : 0 et 1. Il n'y a donc rien de plus simple. Une tension haute en un point quelconque d'un circuit correspond à un 1 tandis qu'une tension basse est associée à un 0. Les tensions intermédiaires entre les deux tensions hautes et basses ne sont pas utilisées en électronique numérique. C'est une représentation simple mais illisible pour un humain à cause du grand nombre de chiffres requis. Par contre, elle est idéale pour des machines pour lesquelles la lisibilité n'est pas un paramètre pertinent.

La représentation hexadécimale ne sert qu'à compacter un nombre binaire afin de rendre ce dernier plus lisible pour les humains (1 chiffre hexadécimal regroupe 4 chiffres binaires). Elle est aussi appelée la base 16 car elle utilise 16 chiffres de la manière suivante :
<p>
0 en hexadécimal = 0 en décimal = 0000 en binaire,<br>
1 en hexadécimal = 1 en décimal = 0001 en binaire,<br>
2 en hexadécimal = 2 en décimal = 0010 en binaire,<br>
3 en hexadécimal = 3 en décimal = 0011 en binaire,<br>
4 en hexadécimal = 4 en décimal = 0100 en binaire,<br>
5 en hexadécimal = 5 en décimal = 0101 en binaire,<br>
6 en hexadécimal = 6 en décimal = 0110 en binaire,<br>
7 en hexadécimal = 7 en décimal = 0111 en binaire,<br>
8 en hexadécimal = 8 en décimal = 1000 en binaire,<br>
9 en hexadécimal = 9 en décimal = 1001 en binaire,<br>
A en hexadécimal = 10 en décimal = 1010 en binaire,<br>
B en hexadécimal = 11 en décimal = 1011 en binaire,<br>
C en hexadécimal = 12 en décimal = 1100 en binaire,<br>
D en hexadécimal = 13 en décimal = 1101 en binaire,<br>
E en hexadécimal = 14 en décimal = 1110 en binaire,<br>
F en hexadécimal = 15 en décimal = 1111 en binaire.
</p>

* [TD 1 : Nombres binaires](Exercices - Logique Binaire.pdf)
* [TD 2 : Portes logiques](Exercices - Portes Logiques.pdf)

* [TP 1 : Affichage de nombres binaires à l'aide de plusieurs LEDs](Travaux Pratiques - Four LED Display.pdf)
* [TP 2 : Affichage de nombres binaires à l'aide d'un afficheur 7 segments](Travaux Pratiques - 7 Segment Display.pdf)
* [TP 3 : Allumage de LEDs à l'aide de boutons poussoirs](Travaux Pratiques - Push Buttons.pdf)
* [TP 4 : Génération de signaux périodiques et monostables à l'aide du circuit intégré 555](Travaux Pratiques - 555.pdf)
* [TP 5 : Construction d'un chronomètre numérique - étape 1](Travaux Pratiques - Stopwatch - Part 1.pdf)
* [TP 6 : Construction d'un chronomètre numérique - étape 2](Travaux Pratiques - Stopwatch - Part 2.pdf)
* [TP 7 : Construction d'un chronomètre numérique - étape 3](Travaux Pratiques - Stopwatch - Part 3.pdf)
* [TP 8 : Construction d'un chronomètre numérique - étape 4](Travaux Pratiques - Stopwatch - Part 4.pdf)
* [TP 9 : Construction d'un chronomètre numérique - étape 5](Travaux Pratiques - Stopwatch - Part 5.pdf)
* [TP 10 : Construction d'un chronomètre numérique - étape 6](Travaux Pratiques - Stopwatch - Part 6.pdf)
* [TP 11 : Construction d'un chronomètre numérique - étape 7](Travaux Pratiques - Stopwatch - Part 7.pdf)
* [TP 12 : Construction d'un chronomètre numérique - étape 8](Travaux Pratiques - Stopwatch - Part 8.pdf)
