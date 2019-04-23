## Que es una interface


*Una interfaz es un conjunto de m�todos abstractos (es decir, se declaran los metodos pero no se implementan) y sus atributos son constantes. Cuando una clase implementa una interfaz , la clase implementa los metodos que posee dicha interfaz. Tener en cuenta que *:


 - Las interfaces no pueden ser instanciadas, solo pueden ser implementadas por clases o extendidas por otras interfaces.

 - ***se puede implementar varias interfaces***, asi: "*public class clase implements Interface1,Interface2,...*" ***a diferencia del concepto de herencia que solo permite heredar de una clase***.

 - En los m�todos abstractos  no es necesario escribir abstract.

 - Todos los atributos son constates p�blicos y est�ticos. Por lo tanto, se pueden omitir los modificadores public static final cuando se declara el atributo. Se deben inicializar en la misma instrucci�n de declaraci�n.

 Cabe aclarar que en java 8,  el concepto de Interface ha cambiado. En Java 8 podemos considerar una interface como una clase abstracta que s�lo puede contener constantes, m�todos abstractos, m�todos por defecto, m�todos est�ticos y tipos anidados, por lo cual:

 - ***Los m�todos por defecto se especifican mediante el modificador default*** (estos si deben de implementar en la interfaz, para saber mas acerca de estos metodos: [https://www.youtube.com/watch?v=Ixn8Ypri90w](https://www.youtube.com/watch?v=Ixn8Ypri90w).


-*Los m�todos est�ticos se especifican mediante la palabra reservada static*.

*Es importante mencionar  que una interfaz se puede hacer de la forma tradicional en donde sus m�todos son puramente est�ticos o utilizando estos m�todos default que aparece en java 8.*
Referencias:

 - [http://picarcodigo.blogspot.com/2012/10/interfaces.html](http://picarcodigo.blogspot.com/2012/10/interfaces.html)
 - [https://www.youtube.com/watch?v=7MlB-K9AMxY](https://www.youtube.com/watch?v=7MlB-K9AMxY)
 - [https://www.youtube.com/watch?v=Ixn8Ypri90w](https://www.youtube.com/watch?v=Ixn8Ypri90w)
 - [http://puntocomnoesunlenguaje.blogspot.com/2013/09/java-interfaces.html](http://puntocomnoesunlenguaje.blogspot.com/2013/09/java-interfaces.html)

## Ejercicio propuesto interface


*El gerente de un zoologico quiere un que desarrolle un programa para saber si los animales del zoologico ya han comido y en caso que no lo hayan hecho alimentarlos, por lo cual se requiere un crear una interfaz llamada alimentacion la cual posea los metodos abstractos   
hasBeenFed(boolean feed) y feed(). Tener en cuenta que hay diferentes animales en el zoologico estos comen alimentos diferentes, por lo cual se plantea crear 2 clases, las cuales representen a un animal del zoologico y que implementen la interfaz alimentaci�n, ademas de ello cada una de esta debe tener un atributo booleano para verificar si ya a comido. (ver la implementaci�n del ejemplo en los archivos de la carpeta interface)* 