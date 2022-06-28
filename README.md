# RedHat-UseCase_colorisation

Récupéré de la video:
<br>https://www.youtube.com/watch?v=dAWPuqZwlOA

<br>Permet de comprendre:
<br>-le loadbalancer entre container
<br>le changement sans rupture de service

<br>Les annotations de la route a ajouter sont:
<br>haproxy.router.openshift.io/balance avec la valeur roundrobin
<br>haproxy.router.openshift.io/disable_cookies avec la valeur true
