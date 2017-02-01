###FLUJO CORRECTO CON GIT

A continuacion daremos una breve explicacion sobre el flujo de git y un paso a paso de como se va dando ese flujo.

![alt text](http://i2.wp.com/jaiversin.com/wp-content/uploads/2015/11/basic-remote-workflow.png)

1.- EL primero paso sera crear un repositorio nuevo en Github el cual llamaremos **"FlujoGIT"**, le daremos una breve descripcion de lo que sera nuestro contenido, inicializaremos nuestro repositorio con el README.md y le damos a crear repositorio.


2.- Despues de haber creado nuestro repositorio, abrimos nuestra terminal y le damos "git clone https://github.com/ManuelJF/FlujoGIT.git" donde colocaremos el link a nuestro git que no dara una copia de el en nuestro ordenador donde podremos trabajar en el.

3.- Entramos a nuestra carpeta de git con un "cd FlujoGIT", crearemos 2 **branchs (Ramas)** dentro de nuestra carpeta flujo git por defecto tenemos la branchs (Master) en donde estara todo nuestro proyecto finalizado en una version estable, con un **"git branch + el nombre de las ramas que deseamos"** en nuestro caso **develop** y **add-new-branch**.

4.- Hasta el momento tenemos 3 branchs "Master, develop y add-new-branch", entraremos a add-new-branch con un **"git checkout + el nombre de nuestra branch a la que deseamos entrar"**, abrimos nuestro editor de texto donde haremos todas las modificaciones deseadas, al terminar daremos **"git status"** para conocer el estado actual de nuestra branch y los cambios que se han efectuado.

5.-Al hacer el **"git status"** nos salta un mensaje que nos indica los cambios que podemos agregarcon un **"git add + el nombre del archivo en el que trabajamos"**, damos un **"git commit -v"** nos saltara una ventana donde podremos agregar un mensaje sobre las actualizaciones que se efectuaron.

6.- Ya estamos listos para enviar todo al origin de Github, damos **"git push origin + el nombre de la rama a la que queremos dar push"**, a continuacion daremos un **"git push origin + el nombre de la rama que se enviara hacia el servidor de github"**.

7.- ahora volvemos a nuestro navegador, actualizamos github y veremos que ahi estan los cambios, damos en comparar branchs donde pasaremos el contenido de la rama "add-new-branch" comparando con "develop", hacemos un merge para fusionar ambas y listo tenemos nuestros avance dentro de "develop".

8.- Podemos verificarlo en github que nos muestre lo que se modifico para estar seguros y ahora podemos eliminar la branch "add-new-branch" ya que solo la utilizaremos para efectuar avances sin modificar directamente el develop y sin tocar **"MASTER"**.


**Estos serian los 8 paso sencillos mostrando el flujo de git y un como llevarlo acabo.**
