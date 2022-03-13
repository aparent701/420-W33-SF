## Théorie  - configuration du routage inter-vlans

## Objectifs


 Configurer un routeur pour obtenir la liaison avec des VLANs  

- Expliquer le rôle des sous-interfaces pour le routage inter-vlan

- Configurer l'interface physique  ```ET``` les sous-interfaces avec le protocole DOT1Q

- Vérifier l'adressabilité complète entre périphériques de vlans différents

## Lecture

-  Lire le fichier suivant.  Notez les différentes commandes, leur rôle et la syntaxe.
```./Module_11_Commutateur_RoutageInterVlans.pdf```

## Documenter la configuration pour votre révision

- Durant la lecture, ajouter les commandes et le rôle de chacune dans votre cahier de notes.

exemple ```partiel```

1. R1(config)# interface <*No_interface*>.<*No*>  	==>    configurer une sous-interface

1. R1(config-if)# encapsulation dot1q <*No_vlan*> 	==>    avec le protocole DOT1q

1. R1(config-if)# ip address <*adresse passerelle*>  <*masque sous-réseau*>


