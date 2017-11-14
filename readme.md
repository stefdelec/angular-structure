1/ les folders sont toujours au pluriel
2/ kebab-case-obligatoire
3/ dumbs, api-services et core-services sont wrappés dans un ngModule.
4/ Chaque module gère ses modules.
5/ Les modules du niveau application sont instancié au niveau du boostrap une seule fois afin de garantir qu'il n'y ait qu'un singleton

