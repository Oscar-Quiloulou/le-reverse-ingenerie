Source originale : [gist de n4sm](https://gist.githubusercontent.com/n4sm/71ecaac0b7a7ef294987f939cf59ab16/raw/91cca8b5904b54299ab4d97ea266f8f2ec1c749d/Commencer%2520le%2520Reverse%2520Engineering%2520!)

# Commencer le Reverse Engineering et le low level


## Sommaire

- [Introduction](#introduction)
- [Prérequis](#prérequis)
- [1. Apprendre le C](#1-apprendre-le-c)
- [2. Apprendre l’assembleur](#2-apprendre-lassembleur)
- [3. Pratiquer](#3-pratiquer)
- [Ressources d’entraînement](#ressources-dentraînement)
- [Livres conseillés](#livres-conseillés)
- [Ressources externes](#ressources-externes)
- [Conclusion](#conclusion)

---

## Introduction

Salut !

Comme beaucoup de personnes me demandent comment commencer le low level et le Reverse Engineering, je vais essayer de faire un petit résumé basé essentiellement sur ma propre expérience.

## Prérequis

Je ne pense pas qu’il faille obligatoirement des connaissances préalables pour se lancer dans le low level. Cependant, certaines notions sont indispensables et apparaissent plus naturellement quand on a déjà codé en C, ou mieux, en assembleur.

Savoir programmer dans un langage de bas niveau est donc un bon point de départ. C’est, je pense, la première étape pour envisager le low level.

## 1. Apprendre le C

Je conseille d’abord d’apprendre le C. C’est un langage que vous devrez très souvent lire, et les programmes en C sont souvent ceux que l’on commence à analyser quand on débute, notamment parce que le code assembleur généré est relativement clair.

Pour apprendre le C :

- **Cours écrit en français** : [Le langage C](https://zestedesavoir.com/tutoriels/755/le-langage-c-1/) — même si ce n’est pas toujours une bonne habitude de rester uniquement sur des ressources francophones.
- **Formation vidéo** : [Playlist YouTube](https://www.youtube.com/watch?v=90hGCMC3Chc&list=PLrSOXFDHBtfEh6PCE39HERGgbbaIHhy4j).

## 2. Apprendre l’assembleur

Une fois les bases du C acquises, le mieux est, je pense, d’attaquer l’assembleur. Il existe aujourd’hui de plus en plus de ressources pour faciliter son apprentissage.

Cependant, il est assez facile de savoir développer en assembleur sans vraiment comprendre les concepts sous-jacents. C’est pourquoi je pense que l’apprentissage de l’assembleur doit être couplé à des notions de plus bas niveau, que l’on ne retrouve pas toujours dans les cours plus scolaires.

**Ressource vivement conseillée** : [Applied Reverse Engineering Series](https://revers.engineering/applied-reverse-engineering-series/). Ce cours est en anglais et, en plus d’enseigner l’assembleur, il aborde des concepts bas niveau au-delà des besoins de la programmation en assembleur.

## 3. Pratiquer

Une fois l’assembleur appris, une bonne façon de se faire la main est de faire des crackmes, ou plus généralement de faire du RE pour consommer un maximum d’assembleur et commencer à acquérir des automatismes.

Ensuite, c’est à vous de trouver ce que vous préférez : RE, pwn, etc.

Le bas niveau, et plus particulièrement le bas niveau orienté sécurité, est un domaine passionnant qui paraît sans fin quand on débute. Profitez bien de cet étonnement, qui ne disparaît jamais vraiment — et c’est ça qui est fabuleux. Mais c’est certain que ce n’est pas facile : si vous voulez avancer, il faudra pas mal s’accrocher au début.

## Ressources d’entraînement

Pour s’entraîner à la sécurité low level (RE / pwn) :

- [Root-Me](https://www.root-me.org/) — plateforme de challenges généraliste avec du cracking (RE) et de l’app sys (pwn), notamment.
- [Crackmes.one](http://crackmes.one/) — plateforme pour s’entraîner à faire des crackmes.
- [pwnable.kr](http://pwnable.kr/) et [pwnable.tw](http://pwnable.tw/) — plateformes pour faire du pwn.

## Livres conseillés

Si vous cherchez des bouquins sympas dans le domaine, j’en ai acheté pas mal et je conseille :

- **Understanding the Linux Kernel** — peut-être moins abordable pour un débutant.
- **Practical Malware Analysis** — fortement conseillé quand on débute.
- **Techniques de Hacking** de Jon Erickson — en français ; c’est le deuxième livre d’informatique que j’ai acheté.
- **Practical Binary Analysis** — pas vraiment adapté aux débutants, mais très cool, orienté DBI plus que RE.
- **Windows Internals Part 1 & 2** — une vraie pépite, assez adaptée pour le débutant qui a un minimum de bases.

J’en ai pas mal d’autres, plus plein d’autres choses sur mon [Mega](https://mega.nz/#F!WLY1iApS!fqafqQejFJEqUELa2bhFLQ).

## Ressources externes

Pour d’autres ressources externes, n’hésitez pas à consulter les canaux :

- `#reverse`
- `#pwn`
- `#ring0`

## Conclusion

Cette introduction au monde du bas niveau peut être utile quand on commence, car c’est normal de ne pas avoir de repères au début. Mais au fur et à mesure que l’on avance, on découvre par soi-même d’autres manières d’approfondir ses connaissances. Cela se fait de manière naturelle.

J’espère que vous avez maintenant une idée un peu plus précise de comment commencer le bas niveau et que vous êtes moins perdu !

Bon courage !
