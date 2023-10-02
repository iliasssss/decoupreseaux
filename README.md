## SYMETRIQUE 
Nom du Pole | Adresse réseau | Adresse de broadcast | Adresse de début de plage | Adresse de fin de plage |
|:-----|:-----|:----|:-----|:-----|
|Le Pôle informatique (6 bureaux,  50 équipements au total) |172.16.1.0/26 | 172.16.1.63 |172.16.1.1 |172.16.1.62 |
|Le Pôle développement (6 bureaux, 12 équipements au total) |172.16.1.64/26 | 172.16.1.127 |  172.16.1.65|172.16.1.126 |
|Le Pôle Administratif (4 bureaux,  20 équipements au total) |172.16.1.128/26| 172.16.1.191 |172.16.1.129  | 172.16.1.190 |
|Le Pôle Technicien (4 bureaux, 15 équipements au total) | 172.16.1.192/26 | 172.16.1.255| 172.16.1.193 | 172.16.1.254 | 

Le pole informatique ayany le plus d'équipement sera donc la réference pour le decoupage réseau 
2^6=64-2= 62 donc 62 adresses dispo pour 50 équipement 
CIDR=2^5-6= 26


## ASYMETRIQUE
Nom du Pole | Adresse réseau | Adresse de broadcast | Adresse de début de plage | Adresse de fin de plage |
|:-----|:-----|:----|:-----|:-----|
|Le Pôle informatique (6 bureaux,  50 équipements au total) |172.16.1.0/26 | 172.16.1.63 |172.16.1.1 |172.16.1.62 |
|Le Pôle Administratif (4 bureaux, environ 20 équipements au total) |172.16.1.64/27 |172.16.1.95 |172.16.1.65 |172.16.1.94 |
|Le Pôle Technicien (4 bureaux, environ 15 équipements au total) |172.16.1.96/27|172.16.1.127  | 172.16.1.97 | 172.16.1.126 |
|Le Pôle développement (6 bureaux, environ 12 équipements au total) |172.16.1.128/28  | 172.16.1.143| 172.16.1.129 |172.16.1.142  | 

*Pole informatique* : 2^6=64-2=62 62 adresses dispo pour le réseau Calcul du CIDR : 2^5-6= 26

*Pole admin*: 2^5=32-2=30 30 adresses dispo pour le réseau CIDR : 2^5-5= 27 

*Pole Technicien* : 2^5=32-2= 30 adresse pour le réseau CIDR:  2^5-5= 27 

*Pole développement* : 2^4=16-2=14 14 adresses pour le réseau CIDR : 2^5-4=28

