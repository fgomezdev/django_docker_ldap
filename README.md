# django_docker_ldap
Proyecto base de django con LDAP

Para sincronizar el directorio del server de prueba correr:

`./manage.py ldap_sync_users`


Para dar permisos de admin a un usuario:
`./manage.py ldap_promote <username>`


**usuario de prueba** (o cualquiera de los que sincroniza el directorio, todos con la misma password):

*username: einstein*

*password: password*


Para más información sobre la librería utilizada:
https://github.com/etianen/django-python3-ldap


Servidor LDAP configurado para el ejemplo:
https://www.forumsys.com/2022/05/10/online-ldap-test-server/