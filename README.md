# RedHat-UseCase_colorisation

Récupéré de la video:
https://www.youtube.com/watch?v=dAWPuqZwlOA

Permet de comprendre:
-le loadbalancer entre container
le changement sans rupture de service

Les annotations de la route a ajouter sont:

haproxy.router.openshift.io/balance         valeur roundrobin
haproxy.router.openshift.io/disable_cookies valeur true
