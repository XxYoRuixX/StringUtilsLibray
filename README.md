# StringUtilsLibrary
La biblioteca StringUtilsLibrary proporciona métodos útiles para manipular cadenas en Java. **Incluye funciones para convertir texto a mayúsculas y minúsculas, invertir cadenas y eliminar espacios en blanco.** Estas funciones facilitan la transformación y manipulación de cadenas de caracteres, lo que puede ser útil en diversos contextos de programación. Simplifica la tarea de realizar operaciones comunes en cadenas sin tener que escribir código adicional

## **Ejemplo De Uso**

``` java
import sul.StringUtilsLibrary;

public class Probardor {

    public static void main(String[] args) {
       StringUtilsLibrary sul = new StringUtilsLibrary();
       System.out.println("El Chico y La Chica Se Fueron De Vacaciones = " + sul.convertirMayusculas("El Chico y La Chica Se Fueron De Vacaciones"));
       System.out.println("El Chico y La Chica Se Fueron De Vacaciones = " + sul.convertirMinusculas("El Chico y La Chica Se Fueron De Vacaciones"));
       System.out.println("El Chico y La Chica Se Fueron De Vacaciones = " + sul.invertir("El Chico y La Chica Se Fueron De Vacaciones"));
       System.out.println("El Chico y La Chica Se Fueron De Vacaciones = " + sul.sinEspacios("El Chico y La Chica Se Fueron De Vacaciones"));
    }
}
/*
El resultado seria:
Papa y mama fueron de compras = EL CHICO Y LA CHICA SE FUERON DE VACACIONES
Papa y mama fueron de compras = el chico y la chica se fueron de vacaciones
Papa y mama fueron de compras = senoicacaV eD noreuF eS acihC aL y ocihC lE
Papa y mama fueron de compras = ElChicoyLaChicaSeFueronDeVacaciones
*/
```
**Licencia**

Este proyecto está bajo la Licencia MIT. Consulta el archivo [MIT License](LICENSE.txt) para más detalles.
