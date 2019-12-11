# GatewayESP32
Passerelle LoRA à base d'ESP32 TTGO et MySensors.
## Entrées/Sorties
### Sorties:
- 8 sorties Mosfet 220V pour le pilotage du délestage des chauffages et du cumulus
  - Alternative: Bus I2c + MCP23017
- OPtion: Sortie téléinfo (Serial1 3.3V vers Domoticz)
### Entrées:
- 1 Téléinfo (boucle de courant)
- 1 1wire: températures des pièces
### "Devices MySensors"
- (S) Température des pièces
- (S) Mode jour/nuit
- (S) Mode délestage
- (E) Switchs des chauffages (allumé/eteint)
