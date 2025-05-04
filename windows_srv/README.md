# Administration d'une VM sur laquelle est installé Windows Server 2019 avec interface

## Réalisation des premières maintenances

J'ai commencé par réguler le trafic en bloquant toutes les demandes qui arrivent de l'extérieur avec le firewall de Windows Defender.
J'ai mis à jour les dernières fonctionnalités ajoutés par microsoft et donné un nom respectant le principe:

[SRV][role][lieu][numero]

Puis, j'ai également désactivé la recherche LM Hosts pour ne conserver que le DNS.

## Création du rôle DHCP

J'ai donné une adresse fixe à mon serveur.
J'ai mis en place une plage d'adresse et j'ai ajouté la mise à jour des statistiques pour avoir les informations sur les demandes.

## Création du rôle DNS

