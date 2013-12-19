Animate.styl
==================

Este proyecto es equivalente al de [animate.css](//github.com/daneden/animate.css).

`animate.css` es un montón de divertidas animaciones cross-browser para que puedan utilizar en sus proyectos.

Esta versión está escrita en `stylus`. Se tiene las animaciones en formato de clases para usar con javascript y en formato de mixins para poder utilizar con la pseudo clase :hover por ejemplo.

Para que funcione correctamente se debe importar el archivo `keyframes.styl` sobre `animate.styl` ó `animate-mixins.styl`

##Instrucciones

Tener instalado `stylus` y `nib`

`npm install stylus`

`npm install nib`

En tu hoja de estilos importar los siguiente:

    @import "keyframes.styl"
    @import "animate.styl"
    @import "animate-mixins.styl"

nib ya se importa en keyframes ya que es el archivo necesario para cualquiera de los otros 2 archivos.

Si se quiere utilizar sobre un elemento para el hover:

   .elemento
   	&:hover
   		animated()
		animatedpulse()

Los nombres de los mixins tienen el formato `animatedNOMBREANIMACION`

==================

Para más información visitar http://daneden.me/animate/

## License
Animate.styl se encuentra bajo licencia MIT. (http://opensource.org/licenses/MIT)
