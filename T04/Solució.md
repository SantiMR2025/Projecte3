# GUIA LDAP
Instalarem dues maquines virtuals un ubuntus per el servidor i un Zorin per l'usuari, i confugurem els adaptador, el primer ha de estar xarxa nat i el segon en pont i cuan entrem al server configurem el domini per que sigui server.innovatech17.test


## 1. Instalarem LDAP amb la comanda sudo apt install LDAP -y i tendrem que configurem 
### seleccionem que no volem saltar la configuracio 
![img.1](img/img01.png)

### posem el domini del nostre server
![img.1](img/img02.png)

### fique la una contrasenya en aquest cas posarem p@ssw0rd 
![img.1](img/img01.png)

### comprobarem que el servei LDAP funcioni i estigui actiu
![img.1](img/img03.png)
![img.1](img/img04.png)

### creem les Unitats Organitzatives per els usuaris
![img.1](img/img05.png)
![img.1](img/img06.png)

### creem les Unitats Organitzatives per els grups
![img.1](img/img07.png)
![img.1](img/img08.png)

### comproven que estiguin ben creades
![img.1](img/img12.png)

### Anyadim un nou usuari com administrador
![img.1](img/img11.png)

### Instalarem el LDAP MANAGER
![img.1](img/img09.png)
![img.1](img/img14.png)

## 2. Configurarem el server usan el LDAP MANAGER desde el buscador del nostre ordinador
### Etrem posant al buscador la ip mes lan i cliquem en configuracio de lam que esta a dalt a la dreta
![img.1](img/img15.png)

### Seleccionem de les tres opcions la de Editar perfils del servidor
![img.1](img/img16.png)

### Fiquem la contrasenya que es lam
![img.1](img/img17.png)

### Configurem tot com esta les imatges
![img.1](img/img18.png)
![img.1](img/img19.png)
![img.1](img/img20.png)

### Anem a la opcio de cuentas que esta adalt a l'esquerra i crearem els grups que seran dos managers i tech
![img.1](img/img22.png)
![img.1](img/img23.png)
![img.1](img/img48.png)

### Ara crearem els usuaris
![img.1](img/img24.png)

MANAGER01
![img.1](img/img49.png)
![img.1](img/img51.png)
![img.1](img/img26.png)
![img.1](img/img25.png)

TECH01
![img.1](img/img27.png)
![img.1](img/img51.png)
![img.1](img/img26.png)
![img.1](img/img25.png)

# 3. cofiguracio del usuari





























