---
marp: true
theme: gaia
class:
    - lead
    - invert
 ---
# Principe de programmation Orienté Objet

 ---
# Don't repeat yourself (DRY)

* Dans un système, toute connaissance doit avoir une représentation unique,  non-ambiguë, faisant autorité.
* Tout développeur devrait être payé à la ligne de code qu'il n'écrit pas.

 ---
# Keett it simple stupid (KISS)

* Un programme simple est plus facile à maintenir et à comprendre
* Il est difficile de faire simple

 ---
# You ain't gonna need it (YAGNI)

* Mettre en ouvre le choses que nous avons effectivement besoin et non pas les choses que nous prévoyons avoir besoin.

 ---
# SOLID

* **S**ingle responsability principle (SRP)
* **O**pen close principle (OCP)
* **L**iskov principle (LSP)
* **I**nterface segregation principle (ISP)
* **D**ependency inversion principle (DIP)

 ---
 # Single responsability principle (SRP)

 * Chaque module d'un système ne devrait avoir qu'une seule raison de changer
 * /!\ Penser à la source de la demande de changement, les gens.

 ---
 # Open close principle (OCP)

 * Le comportement d'un système doit pouvoir être étendu sans changer ce système

 ---
 # Open close principle (OCP)

![img](./build/ocp.png)

OK -> L'ajout d'une forme ne modifie pas la classe Shape

 ---
 # Liskov principle (LSP)

* Un programme ne doit pas dépendre de l'implementation de ces abstractions

 ---
 # Liskov principle (LSP)

![img](./build/lsp.png)

KO -> Les canards électriques peuvent ne pas décoller de la mare s'il ne sont pas allumés

 ---
 # Interface segregation principle (ISP)

* Les interfaces doivent rester petites pour ne pas dépendre d'éléments non nécessaires.
* L’appelant ne devrait pas connaître les méthodes qu’il n’a pas à utiliser

 ---
 # Interface segregation principle (ISP)

![img](./build/isp.png)

KO -> Il serait preferable d'avoir trois interfaces et de les assigner aux classes qui les utilisent

 ---
 # Dependency invertion principle (DIP)

* Les modules de haut niveau ne devraient pas dépendre des details des modules de bas niveaux.

 ---
 # Dependency invertion principle (DIP)

![img](./build/dip1.png)

 ---
 # Dependency invertion principle (DIP)

![img](./build/dip2.png)

 ---
 # Sources

 * [The Pragmatic Programmer](https://github.com/lighthousand/books/blob/master/the-pragmatic-programmer.pdf)
 * [Extreme Programming Explained](https://ptgmedia.pearsoncmg.com/images/9780321278654/samplepages/9780321278654.pdf)
 * [Clean code en français](https://dl.leneveu.fr/public/Coder_Proprement.pdf)
