#  INTRODUCTION
#### Une classe devait être ouverte pour l'extension, mais fermée pour la modification.
#### Le système devait pouvoir s'ouvrir pour l'extension (nous pouvions ajouter de nouvelles fonctionnalités) et devait rester fermé à la modification (l'ancien code n'avait pas nécessairement besoin d'être modifié lorsque nous ajoutions ces nouvelles fonctionnalités). En d'autres termes, les nouvelles fonctionnalités ne nécessitaient aucune réécriture du code existant. 

# Enoncé
#### Créer l’interface IDAO.
#### Créer une implémentation de l’interface IDAO.
#### Créer l’interface IMetier.
#### Créer une implémentation de l’interface IMetier.
#### Créer la couche présentation en faisant l’injection de dépendances.
#### => Par instanciation statique Et Par instanciation dynamique.
# Conception
![conception](https://user-images.githubusercontent.com/101672728/158633959-ce326eeb-7a09-47d3-809c-2286e447d3fe.PNG)
# Solution
## Instanciation statique
### Version Capteur:
![pres_cap](https://user-images.githubusercontent.com/101672728/158634834-1dcbf1fa-2668-47c7-8521-15aafc8f67bf.PNG)
### Version Base de Données:
![pres_db](https://user-images.githubusercontent.com/101672728/158634626-864ab48f-d222-49c0-b27f-7470cd068fbc.PNG)
## Instanciation dynamique
### Version Capteur:
![pres2_cap](https://user-images.githubusercontent.com/101672728/158633167-2f49030f-c7f9-4392-b233-2cff5689df93.PNG)
### Version Base de Données:
![pres2_db](https://user-images.githubusercontent.com/101672728/158634216-f35d9b03-b416-4195-9ac9-c705138f658d.PNG)
# Conclusion
#### Pour conclure, nous avons appliqué le concept ouvert/fermé. Ce principe indique que les classes doivent être ouvertes à l'extension, mais fermées à la modification. En effet, nous ne modifions pas le code existant par contre toutes les nouvelles fonctionnalités sont contenues dans les classes nouvellement ajoutées et le risque de régressions est moindre.
