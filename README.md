# phpmyadmin para dtelab.com.ar

Este repositorio contiene una imagen docker de phpmyadmin preparada
para correr sobre el servidor dtelab.com.ar.

Si quiere vincular su copia local de este repositorio contra nuestro
servidor debería ejecutar lo siguiente:

	git remote add dokku dokku@dtelab.com.ar:admin

Utilice `dokku mysql:list` o `dokku config` para conocer las
credenciales de acceso.

Ah, y por favor vea el archivo `VENDOR_README.md` para conocer más detalles
sobre el proyecto.
