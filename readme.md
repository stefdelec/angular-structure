# Angular structure convention

 - Les folders sont toujours au pluriel
 - kebab-case-obligatoire
 - dumbs, api-services et core-services sont wrappés dans un ngModule.
 - Chaque module gère ses modules.
 - Les modules du niveau application sont instanciés au niveau du boostrap une seule fois afin de garantir qu'il n'y ait qu'un singleton
