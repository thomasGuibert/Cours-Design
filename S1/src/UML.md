---
marp: true
theme: gaia
class:
    - lead
    - invert
 ---
 # UML
 _Unified Modeling Language_

 ---
 # Quoi
* Langage
  * Syntaxe
  * Normalisées
* Modélisation
  * Abstraction du fonctionnement
  * Spécification et conception
* Unifié
  * Standard

 ---
# Pourquoi
* Analyser
* Documenter
* Apprendre

 ---
# Differents diagrammes
|Diagrammes structurels|Diagrammes comportementaux|Diagrammes d'interaction|
| :--------------- |:---------------:| -----:|
|**Diagramme de classes**|**Diagramme de cas d'utilisation**|**Diagramme de séquence**|
| Diagramme d'objets|Diagramme états-transitions|Diagramme de communication|
| Diagramme de composants|Diagramme d'activité|Diagramme global d'interaction|
|Diagramme de déploiement|||

 ---
 # Cas d'utilisation
![img](./assets/uml/usecase.png)

 ---
 # Activités
![img](./assets/uml/activité.png)

 ---
 # Classes: class
![img](./assets/uml/class.png)
```
public class MyClass() { }
```

 ---
 # Classes: Extension
![img](./assets/uml/extension.png)
```
public class MyClass1() extends MyParentClass{ }
```

 ---
 # Classes: Relation
 ![img](./assets/uml/relation.png)
```
public class MyClass1(){
    public void doSomething(){ myClass2.doSomething(); }
}
```

 ---
 # Classes: Composition
 ![img](./assets/uml/composition.png)
 ```
public class MyClass1(){
    public MyClass1() { this.myClass2 = new MyClass2(); }
}
 ```

 ---
 # Classes: Agregation
 ![img](./assets/uml/agregation.png)
 ```
public class MyClass1(){
    public MyClass1(MyClass2 myClass2) { this.myClass2 = myClass2; }
}
 ```

 ---
 # Classes: Interface
 ![img](./assets/uml/interface.png)
 ```
public class MyClass1() implements MyClass2{ }
 ```

 ---
 # Séquence
 ![img](./assets/uml/sequence.png)

 ---
 # Ressources

 * [UML](https://www.lucidchart.com/pages/fr/langage-uml#:~:text=Le%20langage%20UML%20(Unified%20Modeling,et%20riche%20s%C3%A9mantiquement%20et%20syntaxiquement))
 * [Modélisation UML de Christine Solnon](https://perso.liris.cnrs.fr/christine.solnon/coursUML.pdf)
 * [Introduction au génie logiciel
et à la modélisation de
Delphine Longuet](https://www.lri.fr/~longuet/Enseignements/17-18/Et3-UML/)