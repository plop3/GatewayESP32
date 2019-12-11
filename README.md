# GatewayESP32
Passerelle LoRA à base d'ESP32 TTGO et MySensors.
## Entrées/Sorties
### Sorties:
- 8 sorties Mosfet 220V pour le pilotage du délestage des chauffages et du cumulus
  - Alternative: Bus I2c + MCP23017
- Option: Sortie téléinfo (Serial1 3.3V vers Domoticz)
### Entrées:
- 1 Téléinfo (boucle de courant)
- 1 1wire: températures des pièces
### "Devices MySensors"
- (S) Température des pièces
- (S) Mode jour/nuit
- (S) Mode délestage
- (E) Switchs des chauffages (allumé/eteint)
## Matériel
- TTGO LoRa (ESP32)
- Optocoupleur pour la téléinfo.
- Convertisseur 3.3V/5V (1wire, MCP23017)
- Carte 8 sorties Mosfet 220V
- Résistances (téléinfo, 1wire)
- DS18S20 (T° grenier)
## Fonctionnement
En focntion de la consommation électrique, coupe ou allume les éléments.
