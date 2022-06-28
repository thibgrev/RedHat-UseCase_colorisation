# RedHat-UseCase_colorisation

Récupéré de la video:
<br>https://www.youtube.com/watch?v=dAWPuqZwlOA

<br>Permet de comprendre:
<ul>
  <li>le loadbalancer entre container
  <li>le changement sans rupture de service
</ul>
<br>Les annotations de la route a ajouter sont:
<ul>
  <li>haproxy.router.openshift.io/balance avec la valeur roundrobin
  <li>haproxy.router.openshift.io/disable_cookies avec la valeur true
</ul>
