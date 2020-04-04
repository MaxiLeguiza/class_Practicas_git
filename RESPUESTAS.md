#    Programación III
---
**Nombre y apellido:** Maximiliano Leguiza
**Año:** 2020

### Actividades 
---
**1. ¿Qué es git?**
   GIT es un sistema de control de versiones como su nombre lo indica, sistema o programa que controla o administra las distintas versiones de un programa.  
            
**2. ¿Por qué queremos utilizar git?**
    Nosotros queremos utilizar git para poder estar al tanto de cada modificacion que se realiza en el codigo cargando este en un respositorio, ya que debido a esto podemos volver a tener el codigo de una version anterior sin ningun problema y poder asi modificar el actual.Ademas git nos permite que nuestro codigo pueda ser visto por diferentes desarrolladores y obtener un tipo de ayuda para realizar el proyecto. 

**3. ¿Qué es el bash que instala git?**  
   Es una herramienta de tipo consola que basicamente te perminte manipular y gestionar todo el proceso a realizar con el proyecto.

**4. Describa los estados (working directory, staging area, repository)**

   - **Working directory** : En este estado va ser donde nosotros vamos a estar trabajando con todos nuestros archivos.
  
   -  **Staging area**: En este estado es donde  vamos a estar cargando los archivos para ser subidos a git.
  
   -  **Repository**: En este estado va ser el lugar donde van a estar cargadas todas nuestra versiones de software.Junto a las diversas carpetas que realicemos.
   
**5. Describa el flujo para crear un nuevo repositorio git.** 
   El flujo comienza primero abriendo la consola de git bash donde buscaremos nuestra carpeta en la cual se encuentra el proyecto, esto lo realizaremos a traves del uso del comando:

``
    cd desktop
``

Luego:

``
      cd nombreCarpeta/Proyecot 
``

ya una vez teniendo la direccion correcta donde esta nuestro proyecto vamos a inicializar el repositorio a traves del uso del comando:

``
    git init
``

presionamos enter y ya tendremos en git bash creado el REPOSITORIO LOCAL.

Luego para crear un repositorio en nuestra cuenta de GitHub, vamos a dirigirnos al sitio web donde nos registraremos o iniciaremos sesion si ya estamos registrados.

inciaremos llendo al apartado del sitio web llamado " Repositories ", en este apartado vamos a crear nuestro repositorio. Nos dirigiremos al boton new.

Le daremos un nombre y tendriamos creado nuestro repositorio,ademas si queremos podemos agregar una descripcion del proyecto , para finalizar nos dirigiremos al final de la pagina crear repositorio.



**6. Describa el flujo para agregar un archivo simple al repositorio.**
Para agregar un simple archivo lo primero que tenemos que hacer es agregar la direccion a traves de gitBash con el comando :

``
    git remote add origin "dirección"
``

Una vez cargada, vamos a ejecutar otro comando con el cual vamos a poder cargar nuestros archivos.

``
    git push -u origin master 
``

Ya realizado este se nos va abrir una app para ingresar nuestro usuario y contraseña, asi ya tendriamos cargados nuestro diferentes archivos 

**7. Describa el flujo para cambiar el archivo agregado y guardar los cambios en el repositorio.** 
   En este caso vamos primero a revisar  cuales son los archivos modificados o actualizados, utilizando el comando :

``
        git status
    ``

luego de esto agregaremos los archivos modificados para modificar estos archivos en nuestro repositorio con el comando:

``
    git add .
``
y volveremos a verificar si nuestro archivos fueron cargados, una vez realizado esto le pondremos un nombre a la accion realizada para poder llevar el controlor de lo que se a realizado con el uso de:

`` 
    git commit -m "Nombre de lo que se realizo en esta actualizacion"
``

y para ver todos los commit que se han realizados en los podremos ver con el comando:

``
    git log
``

**8.  ¿Cómo hago para ignorar un archivo o carpeta?**
Para ignorar un archivo solo tendremos que crear un archivo en mi proyecto llamado .gitignore donde meteremos los nombres de los o el archivo o carpeta que no queremos que sean cargado a nuestro respositorio.

luego lo agregaremos con " git add ." , y con " git status " podremos ver si se agrego los cambios.

Por ultimo commitearemos para recordar que hemos realizado este cambio.


**9.  Explique qué es un branch. Dé un pequeño ejemplo de cómo haría uno.**
 Un BRANCH es un comando que usaremos principalmente para trabajar con la creación de ramas, borrado de ramas y demás.

 - Ejemplo:
  
     Podriamos decir que tengo una lista ya creada y me gustaria ultilizarla para hacer una lista de producto crearia una rama nueva llamas listProduct a traves del comando:

    `` 
     git branch listProduct
    ``

    luego lo ultinmo que quedaria por hacer seria meternos en esa rama o version alternativa del codigo que creamos con el comando:

     ``
    git checkout listProduct 
     ``

    y ahora solo queda alterar lo que queramos en este proyecto.

**10.  ¿Qué hago con `git add .`?**
    Con este comando lo que realizamos es cargar las modificaciones que se van a ir realizando en nuestro proyecto, el mismo cargara todas las modificaciones.

**11.  ¿Cómo cambiamos de un branch a otro?**
     Para cambiar de un branch a otro solo utilizamos el comando `` git checkout nombre de rama creada``

    
**12.  Investigue qué es Markdown y responda todas las preguntas anteriores en este lenguaje (con el nombre de archivo RESPUESTAS.md). Súbalo al repositorio.**
**Markdown**: Es un lenguaje de marcado ligero que trata de conseguir la máxima legibilidad y facilidad de publicación tanto en su forma de entrada como de salida, inspirándose en muchas convenciones existentes para marcar mensajes de correo electrónico usando texto plano.

Ademas podemos agregar que es una forma sencilla de agregar formato a textos web