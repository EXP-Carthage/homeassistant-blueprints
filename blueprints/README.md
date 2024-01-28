# Blueprints

## Automation

### heating_management.yaml

Pilote un radiateur avec fil pilote en comparant une température de consigne avec la température ambiante relevée dans la pièce,
et n'utilisant que 2 modes (Confort et Off).

**_Prérequis_**

* Une entrée `input_number` à créer pour la température de consigne
* Un capteur de température
* Un module avec fil pilote

**_Lien d'importation_**

`https://github.com/EXP-Carthage/homeassistant-blueprints/blob/master/blueprints/automation/heating_management.yaml`

### heating_management_with_window_sensor.yaml

Pilote un radiateur avec fil pilote en comparant une température de consigne avec la température ambiante relevée dans la pièce,
gérant un capteur d'ouverture de fenêtre (ou groupe de capteurs) et n'utilisant que 2 modes (Confort et Off).

**_Prérequis_**

* Une entrée `input_number` à créer pour la température de consigne
* Un capteur de température
* Un capteur d'ouverture de fenêtre (ou groupe de capteurs)
* Un module avec fil pilote

**_Lien d'importation_**

`https://github.com/EXP-Carthage/homeassistant-blueprints/blob/master/blueprints/automation/heating_management_with_window_sensor.yaml`
