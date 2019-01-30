# Sesión 1 - ¿Qué es Git?

+ Es un sistema de control de versiones que originalmente fue diseñado para operar en un entorno Linux.

+ Un sistema de control de versiones es el conjunto de herramientas que tenemos disponibles para poder gestionar de una forma eficiente las distintas versiones de nuestros proyectos.

## Características Importantes Git

+ Usualmente otros sistemas almacenan información en una lista de cambios de archivos, mientras Git lo hace como un conjunto de archivos.

+ La integridad con la que cuenta es bastante seria. No existen cambios, corrupción en archivos o cualquier alteración sin que Git lo sepa. Esto funciona gracias a una verificación con la que cuenta mediante un Checksum.

+ Casi todo en Git es local, basta con los recursos locales con los que cuenta.

+ Tiene tres estados:

    * **Commited:** Es la parte en la que nuestra información está segura alojada en nuestras bases de datos.
	
    * **Modified:** En esta parte hemos realizado cambios en nuestros archivos, pero aún no se ven reflejados en nuestra base de datos.
	
    * **Staged:** En esta parte marcamos nuestros archivos modificados, dejándolos listos para confirmarlos. 

## Directorios en Git

+ Una buena práctica para tener todo en orden y eliminar lo innecesario, es crear un archivo .gitignore donde podamos incluir esos directorios que no dan valor a nuestros proyectos y así mantener solamente lo necesario.