---
marp: true
theme: gaia
class:
    - lead
    - invert
 ---
 Programmation Orienté Objet

 ---

Classe, un patron pour creer des objets
 
 ---
 Classe

 * Constructeur -> Comment mon patron va creer une instance de classe (un objet)
 * Propriétés -> Les composants de l'objet
 * Méthode -> comportement de l'objet

 ---
 Classe et objets

Une classe _definie_ un contexte, un comportement interne.
Un objet _implemente_ un contexte, un comportement interne. 

 ---
Encapsulation

Classes et objets peuvent exposer une partie de leurs contextes ou de leurs comportements pour communiquer avec l'exterieur

```
schema voiture utilisé par un conducteur
conducteur.avance(Voiture voiture){
    voiture.roule();
}
```

 ---
 Héritage

Un objet peut être spécialisé, étendu grâce à de l'heritage

```
schema de diffrebtes marques de voitures
```

 ---
Surchage

Un objet spécialisé peut surchargé un comportement ou un contexte

```
avancer avec nitro
```

 ---
Surchage

Un objet spécialisé peut rédifinir un comportement ou un contexte

```
vrombissement de voiture de diffrentes marques
```

 ---
Polymorphisme

Un objet peut être vue comme une classe de sa hierarchie

```
Une voiture est un moyen de locomotion
```
 ---
 Classe abtraite

Patron d'objet qui ne peut pas être instancié

 ---
 Interface

 Definition d'un contrat

 ---
 Sources

 https://www.technologuepro.com/cours-informatique/cours-15-programmation-orientee-objets-poo/