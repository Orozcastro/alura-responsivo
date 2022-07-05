# Proyecto Apeperia

Archivos iniciales del proyecto para Apeperia del curso "Layouts Responsivos: Trabajando con layouts mobile", de Alura LATAM.

[Figma](<https://www.figma.com/file/Cv9OIfwW20qbM2ywcSXOnK/Apeperia-Mobile-First-(inicial)?node-id=15%3A198>)

### EMMET

####Es un plugin que va a generar código predefinido de manera abreviada.
header>img+nav>ul>li\*6.item

section.destacados.container>h2.destacados**titulos+a\*2>figure.destacados**panel>img.destacados**panel-img+figC.destacados**panel-texto+a.destacados\_\_boton

//los parentesis para poner el boton despues de la figure
section.destacados.container>h2.destacados**titulo+(a\*2>figure.destacados**panel>img.destacados**panel-img+figC.destacados**panel-texto)+a.destacados\_\_boton

section.institucional.container>h2.institucional\_\_titulo

### REM | EM

Medida relativa en relacion a la raiz (del HTML).
Adaptable a todos los navegadores web

REM proviene de “Root ephemeral” que en traducción técnica es la “variable de la raíz”, o sea, es una variable en relación de la propiedad font-size de la etiqueta raiz (HTML). EM proviene de “ephemeral” que significa “variable” y es una variable de la propiedad font-size de la etiqueta madre.

### IMAGENES

#### PNG

- Poco compacto
- Mantiene la claidad de la img
- Tamaño elevado
- Con transparencia
- Acercamiento malo

#### JPG

- Muy compacto
- Calidad de la img baja
- Tamaño leve
- Sin transparencia

#### GIF

- Calidad de la img baja
- Tamaño depende de la calidad de la img
- Uso limitado

#### SVG

- Img vectorial en 2 dimensiones (tamaño/posicion)
- Tamaño variable
- Es leve
- Acercamiento mejor
- Pierden los colores
- Usarlo para: LOGOTIPOS | ICONOS | ILUSTRACIONES SENCILLAS

## MOBILE FIRST

Concepto para diseñarla primera version de la pagina primero para mobile

#### Ventajas

- Se concentra en lo esencial, diseño es minimalista y simplificado
- Informaciones de facil accceso
- Maximo rendimiento(pensar en distintos formatos para dispositivos)
- Reduce le codigo fuente
- Uso de HTML5
- Enfoque en el contenido.

## desktop-first:

- El interfaz tiene features más ricas;
- Mayor capacidad de ejecución de las instrucciones;
- El producto es optimizado para desktop (ejemplo: Google Docs).

#### VIEW PORT

    <meta name='viewport' content='width=device-width, initial-scale=1'>

// EL NAVEGADOR RECONOCE EL TAMAÑO DEL DISPOSITIVO
// initial-scale=1' // especifica que el tamaño es el 100%f

#### VARIABLES CSS

:root{
--background-mobile: #00161C;
}

body{
background-color: var(--background-mobile);
}
