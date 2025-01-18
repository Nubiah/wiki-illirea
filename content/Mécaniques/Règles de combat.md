---
title: Règles de combat
draft: false
---
A son tour de jeu, un personnage peut agir en choisissant l'une des options suivantes :

- 1 action limitée (L)
- 1 action de mouvement et 1 action d'attaque (dans n'importe quel ordre)
- 2 actions de mouvement

# Défense

- ~~La défense est déterminée par l'armure que le personnage porte, mais également par sa capacité à anticiper les coups et les éviter~~
- ~~Ainsi, chaque armure possède une valeur de défense, mais également une valeur d'agilité maximum pouvant être pris en compte dans le calcul de la défense~~

- Chaque pièce d’armure possède une défense associée. Certaines voies et compétences apportent des points de défense supplémentaires
- Chaque point de défense correspond à un dé 6
- Lorsque le personnage subit des dégâts physiques (fonctionne de la même manière pour la défense magique, contre les dégâts magiques) il lance alors tous ses dés de défenses. La règle des succès est la même que pour tout les autres jets.
	- Si le jet de défense est supérieur au jet d’attaque de l’assaillant, l’attaque échoue
	- Si le jet de défense est inférieur au jet d’attaque de l’assaillant, l’attaque réussie
	- Si les deux jets sont égaux, l’attaque est considérée comme réussie, mais seule la moitié des dégâts est infligée
- Cf. [[Equipement]] pour plus d’informations sur les valeurs de défense des armures


# L'action de mouvement

- L'action de mouvement d'un personnage lui permet de se déplacer d'environ 10 m. Certaines créatures ou certaines capacités peuvent influer sur ce déplacement. Il est possible de dégainer (sans coût) pendant un déplacement.

## Déplacement ralenti

- A la libre interprétation du MJ, certains terrains sont plus ou moins difficiles à parcourir, et la valeur de déplacement peut donc être réduite en fonction.

## Sprint

- Il est également possible de sprinter pour atteindre plus rapidement un point, au détriment de toutes précautions
- En utilisant son tour complet, un personnage peut parcourir environ 30 m (3 x sa distance initiale). Mais en contrepartie il perd 5 en défense sur la première attaque qui devrait le toucher sur ce tour.
- Certaines conditions peuvent empêcher une telle action : encombrement, blessure, nature du terrain…

## Autres modes de déplacement

- Nage : #WIP
- Escalade : #WIP

# L'action d'attaque

- En combat, lorsqu'un personnage veut en attaquer un autre, il doit réussir un test de la compétence associée à son attaque
    - Attaque en mêlée avec une arme = Combat à l'arme
    - Attaque en mêlée sans arme = Combat en mêlée
    - Attaque à distance avec une arme = Combat à distance
    - Attaque à distance avec un objet = Lancer d'objet
- De la même manière que les tests de caractéristiques, le personnage lance un nombre de dès égal à sa compétence et la caractéristique qui va avec
- Le nombre de succès réalisé s'oppose ensuite à la **Défense** de la cible, déterminée par son armure et ses caractéristiques
- Si le test d'attaque est réussi alors l'attaque touche l'adversaire. Les dégâts sont déterminés par l'arme directement.

## Cas des critiques en combat

- C'est la même règle que celle des tests de caractéristique, à l'exception qu'ils influent sur les combats
    - 2 succès de plus : c'est un coup puissant et les dégâts sont multipliés par 1,5.
    - 4 succès de plus : c'est un coup critique et les dégâts sont multipliés par 2.
- Une majorité de 1 : c'est un échec critique, et non seulement l'attaque ne porte pas, mais un effet négatif risque de se produire

## Riposte

- Au début du round (avant le tour du premier personnage dans l'ordre d'initiative) un personnage peut se déclarer en posture de riposte. Durant ce round, si une créature l'attaque au contact, il peut prendre son tour pour riposter immédiatement (une seule fois par tour)
- Si cela l'amène à agir avant sa propre valeur d'initiative, il ne peut réaliser qu'une action d'attaque

## Retarder son tour

- Un personnage peut choisir de retarder son tour pour jouer plus tard. Il retrouve son initiative initiale au tour suivant
- On ne peut pas accélérer son tour

## Manœuvres tactiques

- Le personnage choisit une manoeuvre et utilise une action limitée pour déclencher un test opposé d'attaque (se joue au nombre de succès, pas de réussite ou d'échec critique)
- Selon la manoeuvre certains facteurs supplémentaires peuvent entrer en considération
- En cas de réussite la manoeuvre n'inflige pas de dégâts, mais inflige un effet ou une condition à la cible

### Liste des manœuvres :

- Distraire (+ **Charisme**) : la cible subit un malus de -4 succès à tous ses tests de **Perception** et -3 en **Défense** pendant 1 round. Elle est considérée comme étant surprise pour les attaques sournoises.
- Repousser : la cible recule de **Force** de l'attaquant + 3 mètres et l'attaquant prend sa place sur le terrain ainsi libéré. Si la cible était déjà acculée elle perd autant de Défense pour le tour. Cette action peut être précédée d'un déplacement de 10 m en direction de la cible.
- Bloquer (-3 succès) : la cible est immobilisée pendant 1 round.
- Désarmer (-3 succès) : la cible est forcée de laisser tomber son arme au sol. Elle peut la ramasser avant tout le monde en sacrifiant son prochain tour.
- Aveugler (-3 succès) : la cible est aveuglée pendant son prochain tour (-3 succès pour une attaque au corps à corps, -5 à distance). Elle perd également 2 en **Défense**
- Renverser (-3 succès, -5 contre un quadrupède) : la cible est renversée (-5 en **Défense** et doit utiliser une action d'attaque pour se relever). Cette action peut être précédée d'un déplacement en direction de la cible.
- Etourdir (-5 succès) : la cible est étourdie pendant son prochain tour. Elle n'aura pas la possibilité de jouer et perd 5 en **Défense**.

## Les dégâts

- Si le test d'attaque est réussi, il faut déterminer les dommages et le résultat obtenu est alors retranché au nombre de point de vie de la cible.
- **Combat avec arme** : on détermine les dégâts infligés avec une arme en lançant le ou les dé(s) de dommage de l'arme (cf. [[Equipement]])) en y ajoutant éventuellement un modificateur :
    - Par défaut, il s'agit de la **Force** mais certaines capacités peuvent modifier cela
    - Pour les attaques à distance, on n'ajoute pas de caractéristique sauf si une capacité indique le contraire

**Dégâts = dé(s) de dégât de l'arme + Bonus éventuel**

Combat à mains nues **: un personnage qui ne possède pas de capacité particulière pour se battre à mains nues inflige des dommages égaux à 1d2 +** Force

Attaques magiques **: ces attaques n'ont pas de formule de dégâts par défaut, et dépendent souvent de la capacité.**

## Les points de vies

### Règle du dernier point de vie

- Les PV représente la force vitale d'un individu
- Ainsi on considère que lorsqu'un personnage n'a plus qu'un seul point de vie, la mort est proche
- Pour les personnages joueurs, cela signifie passer en Vie Critique, qui retire 2 succès à tous les tests
- Autrement, cela signifie tomber dans l'inconscience jusqu'à la mort ou le sauvetage de quelqu'un

### Inconscience et mort

Quand un personnage joueur voit ses points de vie arriver à 0, il tombe au sol, inconscient.

> [!note]
> On ne peut pas descendre en dessous de 0 PV.

Lorsqu'il est inconscient il ne peut plus faire quoique ce soit.

S'il n'est pas soigné (sort de soin, potion …) dans l'heure qui suit, il meurt.

### Premiers soins

Un personnage peut tenter de prodiguer les premiers soins à un personnage inconscient aux portes de la mort

- Cela requiert un test d'Intelligence (Médecine) de difficulté 3 succès.
    - En cas d'échec, le personnage est stabilité mais met 30 minutes à revenir à lui, avec 1 PV
    - En cas de réussite, il reprend connaissance presque immédiatement, et récupère 1d4° PV
- La difficulté du test est augmenté à 5 succès si le dernier coup qu'à reçu le personnage était un coup critique