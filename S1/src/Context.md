
---

# Contexte
---

 ![image](./S1/src/assets/everything-is-fine-itsfine.gif)

---
# Taux de réussite

![image](./S1/src/assets/chaosreport.png)

---

  # Besoin client
 ![image](./S1/src/assets/gestion_projet_balancoire.jpg)

---

# Usage
![image](./S1/src/assets/fonctionnalités.png)

---
 # Temps
![image](./S1/src/assets/NOTime.jfif)

---
 # Coût de la qualité
 ![image](./S1/src/assets/CostOfDefect.webp)

---
  # Evolution de la performance
 ![image](./S1/src/assets/ProductivityByRelease.webp)

---
 # Cas d'utilisation
```plantuml
@startuml
scale 400*400
left to right direction
actor Guest as g
package Professional {
  actor Chef as c
  actor "Food Critic" as fc
}
package Restaurant {
  usecase "Eat Food" as UC1
  usecase "Pay for Food" as UC2
  usecase "Drink" as UC3
  usecase "Review" as UC4
}
fc --> UC4
g --> UC1
g --> UC2
g --> UC3
@enduml
```
---

 # Raisons de la faible qualité des logiciels
* Tâche complexe
* Manque de méthodes et de rigueur
* Mauvaise compréhension des besoins

---
 # Critères de qualité
* Validité : réponse aux besoins des utilisateurs
* **Maintenabilité** : facilité à corriger ou transformer le logiciel
* Performance : temps de réponse, débit, fluidité...

**hardware vs software**

---
# Different niveaux de conceptions

* Organisation de l'entreprise
* Architectures logiciel (Stratégie)
* Schéma de conception (Tactique)
* Algorithmique

---
 # Organisation de l'entreprise

**Loi de conway**:
 _les organisations créent des systèmes à l’image de leurs propres structures de communication_

---
 # Architectures logiciel

* Communication entre les systèmes
    * API
    * Queue
    * ...
* Architecture des systèmes
    * NTiers
    * Hexagonal
    * ...

---
# Schéma de conception

 * Principes de conception orientée objet
    * SOLID
    * Design pattern

