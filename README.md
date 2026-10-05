# Como juntar todos los repositorios


## Se deben ejecutar los siguientes comandos:

```
 git clone https://github.com/eliascardona/ldap-simple-login-backend
```


```
 git clone https://github.com/eliascardona/ldap-simple-login-frontend
```


```
 git clone https://github.com/eliascardona/ldap-simple-login-rotator
```

## Aviso

Los archivos del repositorio del rotador (secrets rotator) debe ser colocados en la raíz de una carpeta, luego, dentro de esa carpeta se deben ubicar los otros dos repositorios descargados.
De este modo, tenemos un punto de entrada global (docker-compose.yml) que es capaz de ejecutar todo el proyecto.

En clase se solicitaron repositorios separados preferentemente




