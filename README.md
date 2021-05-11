# Sprint 1

## Landing page responsiva

El desafío está enfocado en el maquetado de la landing page de un canal de Podcast, siguiendo las guías visuales de una
interfaz de usuario otorgada y desarrollando funcionalidades de reproducción de contenidos, navegación, compatibilidad
con múltiples exploradores y dispositivos.

## Preparación

Lo primero es revisar los requisitos y configurar el proyecto inicial.

1. Descargar los recursos del proyecto
2. Organizar los archivos del proyecto (HTML y CSS)
3. Configurar los estilos iniciales

En este último paso, mi configuración será esto:

```css
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
```

Así puedo editar cada elemento al tamaño necesario.

También usaré `rem` como unidad de medida, correspondiente a 16px. Para no confundirme en el tamaño de los pixeles, lo
convertiré a 10px usando este código:

```css
html{
    font-size: 62.5%;
}
```

Ajustaré el `body` a `120rem` como `max-width` para conservar el estilo en pantallas grandes.

Usaré los colores con `var()` para poder reusarlos e identificarlos.

Iconos se instalarán de `fontawesome` y la tipografía de `Google Fonts`.

## Desarrollo

1. Dividir todas las secciones y desarrollarlas de manera individual, el CSS está separado en módulos, por lo que
   resulta más fácil distribuir las propiedades.
2. Mi idea fue crear tantos div parents como fuera posible para poder tener los elementos separados de otros
3. Estuve jugando con el tamaño de los elementos usando Firefox Developer edition

## Obstáculos

1. Al principio, empecé el diseño por "Desktop-first" pero se venía complicando cuando intentaba aplicar media queries,
   así que empecé el proyecto desde cero y las media queries las hice para que se ajustaran al desktop.
2. Aún no sé por qué la propiedad `justify-content: space-between` no funciona para mi navbar, a pesar de que tengo solo
   dos elementos parent.
3. Usar fontawesome genera muchos errores en la consola, así que descargué los iconos en SVG

## Conclusión

1. Empezar por mobile design y luego usar media queries para adaptarlo a Desktop.
2. Iframes pueden hacer tu código algo lento

Puedes ver la presentación del proyecto en este link <https://www.canva.com/design/DAEeIXEovIc/PbnPmnHU_CdJn6tADXBmmg/view>

El proyecto se encuentra en este link <https://sprint-1-acamica.vercel.app/>

Link a GitHub <https://github.com/DavidSalomonDev/sprint-1_acamica>
