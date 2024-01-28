# Blueprints

## Automation

### heating_management.yaml

Pilote un radiateur avec fil pilote en comparant une température de consigne avec la température ambiante relevée dans la pièce,
et n'utilisant que 2 modes (Confort et Off).

**_Prérequis_**

* Une entrée `input_number` à créer pour la température de consigne
* Un capteur de température
* Un module avec fil pilote
