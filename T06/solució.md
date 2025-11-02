# DNS

## 1. Consulta Bàsica de Registre A
![img1.png](img1.png)
IP de resposta:
En la sección ANSWER SECTION aparece:
xtec.cat.    3171    IN    A    83.247.151.214

Por tanto, la dirección IP que responde para el dominio xtec.cat es 83.247.151.214.


Valor TTL (Time To Live):
El valor TTL está justo después del nombre del dominio en la misma línea:
3171

## 2. Consulta de Servidors de Noms (NS)

Servidor primari autoritatiu (SOA): ns-1071.awsdns-05.org
IP v4: 205.251.196.47
IP v6: 2600:9000:5304:2f00::1


# 3. 

En el registre SOA, el segon camp després del servidor primari indica el correu de l'administrador, però amb el primer punt substituint el signe @.
A la línia:
escolapia.cat. 900 IN SOA dns1.nominalia.com. root.dns1.nominalia.com. 1761028965 86400 7200 2592000 300

El correu és:
root@dns1.nominalia.com


# 4. 

Tipus de registre: PTR
IP consultada: 147.83.2.135
Noms associats:
- edicioweb.produccio.upc.edu
- saladepremsa.upc.edu
- barcelonatech.upc.edu
- barcelonatech-upc.eu
- upc.cat
- upc.edu
- www.upc.es
- masters.upc.edu


# 5. 

- El servidor autoritatiu és aquell que té la informació original del domini (els registres definitius).
- El teu sistema ha consultat un servidor que té la informació en memòria cau (cache) o que ha fet la consulta prèviament a un autoritatiu.
- Per això, la resposta és correcta, però no és autoritativa.


# 6. 

L’ordre no és fix; depèn de com el servidor DNS retorna els registres A. Això pot variar per:
- Round-robin DNS (mecanisme per repartir càrrega entre diversos servidors).
- Cache del resolver.
