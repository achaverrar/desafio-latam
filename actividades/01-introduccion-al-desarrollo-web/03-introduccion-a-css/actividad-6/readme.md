# Actividad 6: Revisando los aprendizajes

- ¿Qué línea de código deberíamos utilizar para integrar un CSS que esté en la subcarpeta estilos?
  - R/
  ```html
  <link rel="stylesheet" href="assets/css/subcarpeta/style.css" />
  ```
- ¿Cuál es el selector universal o comodín que permite seleccionar todos los elementos? Si no lo recuerdas, revisa dentro de la sección modelo de caja.
  - R/ El selector `*`
- ¿Qué propiedad y valor deberíamos ocupar para asignar margen solo a la derecha y arriba?
  - R/
  ```css
  selector {
    margin-right: value;
    margin-top: value;
  }
  ```
- En el siguiente CSS, ¿cuál es el error?
  ```css
  .header{
    width: 100%
    height: 20em
  }
  ```
  - R/ Falta el ';' al final de cada declaración.
- Verdadero o falso: Por defecto, un `1em` mide `18px`.
  - R/ Falso. Por defecto, `1em` mide `16px`.
- Verdadero o falso: La primera regla manda.
  - R/ Falso. La regla más específica manda, y entre reglas igual de específicas, la última regla manda.
- ¿Para tipografías es mejor ocupar px o em?
  - R/ Es preferible usar rem; pero entre pixeles y ems, em podría ser una mejor opción, pues al ser una medida relativa, le permite al usuario cambiar el tamaño de la letra según necesite; pero hay que tener cuidado con cómo puede cambiar el valor de la letra, según el contenedor, y cambiar el layout de manera no deseada.
