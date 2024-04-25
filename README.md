Documento Explicativo

Este documento describe cómo usar un pipeline junto con un script de Bash para obtener información del sistema. El pipeline se divide en tres etapas: 
    1.-Establecer permisos
    2.-Ingresar parámetros
    3.-Ejecutar un script. 
    
A continuación se detalla cada parte del pipeline junto con el script de Bash que se ejecutará.

    1.-Establecer Permisos: Aquí se garantizan los permisos necesarios para el script de Bash.

    2.-Ingresar Parámetros: Se solicita al usuario que ingrese el nombre del proceso que desea buscar. Este nombre será utilizado más adelante.

    3.-Ejecutar Script: Se ejecuta el script de Bash con el nombre del proceso ingresado como parámetro.

Script de Bash (practica.sh)

El script de Bash realiza las siguientes operaciones:

    *Obtiene el nombre del host.
    *Muestra la fecha y hora actuales.
    *Informa sobre el uso del disco raíz.
    *Muestra los usuarios activos en el sistema.
    *Muestra la cantidad total de memoria y la memoria disponible.
    *Busca procesos en ejecución que coincidan con el nombre proporcionado como argumento.

    Uso

    *Configuración del Pipeline: El codigo se configura desde la cuenta de Github para conectar directamente con Jenkins.

    *Configuración del Script de Bash: Guarde el script de Bash en un archivo llamado practica.sh y asegúrese de que tenga permisos de ejecución.

    *Ejecución del Pipeline: Inicie el pipeline. Durante la etapa 'Ingresar Parámetros', ingrese el nombre del proceso que desea buscar.

    *Resultados: Después de que el pipeline se ejecute con éxito, verá los resultados de los comandos en la salida del pipeline, incluyendo información sobre el host, fecha y hora, uso del disco, usuarios activos, memoria y procesos coincidentes.