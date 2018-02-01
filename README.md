# cedv-ej1-mod1
Ejercicio 1 del modulo 1 del CEDV
.

Enunciado:

El ejercicio consistirá en una ampliación del proyecto manejado en las sesiones de Blueprints.

A continuación se establecen los requisitos mínimos para el ejercicio a resolver:

Creación de un nuevo nivel, cuya carga o transición se realizará desde algún otro nivel a través de un nuevo portal similar al del resto de niveles.
Integración de un HUD con información relevante asociada al nivel.
Añadir nueva acción al personaje principal para interactuar con el entorno mediante la tecla E (e.g. activar un botón situado en la pared).
Despliegue dinámico de enemigos cada cierto tiempo. El comportamiento de los enemigos será el de dirigirse hacia el jugador, disparando proyectiles hacia el personaje principal. No es necesario implementar IA para los enemigos; se pueden utilizar simples translaciones.
Añadir vida al personaje principal, que se verá afectada cuando un proyectil enemigo impacte sobre el jugador o exista una colisión entre enemigo y personaje principal, haciendo uso del HUD.
El nivel tendrá una serie de mecanismos, del mismo tipo (e.g. botón en pared), de forma que la activación de uno de ellos liberará una llave, mientras que el resto generará enemigos. Cuando el jugador se haga con la llave (no es necesario recrear animaciones), el único portal existente se reactivará de forma que el jugador pueda salir del nivel.
Algunas consideraciones:

El ejercicio está pensado para ser resuelto con Blueprints, pero es posible utilizar C++ como complemento.
Con respecto a la parte gráfica se plantea el uso de cualquier recurso cuya licencia lo permita. No es necesario representar fielmente el objeto integrar (e.g. llave).
En este sentido, y con respecto a los recursos multimedia, es posible utilizar los disponibles en los otros casos prácticos del curso o cualquiera que tenga una licencia que permita su uso. En las siguientes páginas hay multitud de ellos:

    https://www.blendswap.com/
    https://poly.google.com/ (Google)
    https://www.remix3d.com/ (Microsoft)
    http://www.cadnav.com/
    https://opengameart.org/
    http://kenney.nl/assets
El resultado de la solución del ejercicio ha de ser un archivo .zip con el contenido del proyecto (File->Zip Up Project) y cuyo nombre siga el siguiente convenio: CEDV_M1_E01_apellido1_nombre.zip (e.g. CEDV_M1_E01_Vallejo_David.zip). Es importante que el proyecto empaquetado se puede abrir en la propia instalación de UE4.

Debido a las limitaciones de tamaño máximo de las tareas en Moodle, este archivo .zip deberá subirse a alguna plataforma como WeTransfer o Dropbox y la URL resultante será la que se adjunte en la tarea de CampusVirtual.
