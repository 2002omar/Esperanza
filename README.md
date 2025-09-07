# Esperanza


e hecho hasta ahora.
https://2002omar.github.io/Esperanza/dir/Esperanza.html

## Glosario.

### Quien soy.


Me llamo Omar Santiago.
Y si hay alguna persona que lea esto y sea principiante:
Estoy encantado de a grandes rasgos explicarle como hice una pagina web estática.


###  El porqué de este proyecto.

Este proyecto es muy importante para mí, ya que me ha permitido aprender a subir páginas a GitHub y a crear sitios web desde cero. Al principio fue todo un reto. Este trabajo lo hice con un celular y puedo decirte que no es nada fácil. 

#### El proceso para realizarlo


 Enncontré en Github una oportunidad de contar con un dominio gratis para subir mis proyectos.
 
   Aunque yo tenía una cuenta desde hace muchos años. Nunca la había usado.
 Ahora estoy agradecido con Dios y con los integrantes de Github por esta maravilla.
 
#### ¿Que herramientas usé para crear un entorno de trabajo ideal.


* Termux para Android.

Para mi, la herramienta ideal para subir, editar y borrar archivos del repositorio de Github en la web. La capacidad de Termux es enorme, y como un emulador en Android, genial.
Te aconsejo que la descargues de Github que siempre tiene la última versión; o de Droid. No de la play Store porque no actualiza la app

* NODE.js

Te provee de una variedad de usos solo o acompañado por otras aplicaciones de JS.
Normalmente viene instalado en Termux.
Puedes averguarlo con:
NODE -v
Si no lo esta, usa el siguiente comando para instalarlo:
 ***pkg install  node.js***
Te comento que el gestor de paquetes npm se instala con NODE

*  La hoja de estilo ***Normalize***

Esta hoja de estilo, hace un buen trabajo para rectificar la semántica del HTML, y el que tu página se vea igual en todos los navegadores.
Si necesitas algo más complejo debido a la naturaleza de tu trabajo; puedes optar por otras opciones como Bootsteap.

* Editor VIM para Termux.

Si deseas aprender a programar; este es el editor ideal.
Son pocos los editores que soporta Termux.
Pero este es el más completo.

* Vim-plug
Es necesario para poder descargar plugins de Vim.

Su comando es:

curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim


Necesitas crear en Termux un archivo ***.vimrc*** en el directorio: \~/.vim/ o \~/home/; si te pasa lo que a mi que no lo pude instalar en la primera ruta; en donde guardarás toda la configuracion dw Vim. Alli pondras una serie de configuraciones siendo la primera: 
*Filetype plugin on*
Que permite descargar plugins.
Las otras dos son:
  ***call plug#begin('~/.vim/plugged')***
Que se coloca primero, y
Que dejando varias lineas de intermedio colocas:
***call plug#end()***
En medio de estas 2 configuraciones que conforman el instalador de plugins para Vim; vas a colocar todos los plugins que quieras.
Los plugins se instalan con el comando 
*:PlugInstal*
Y para completar debes poner afuera del instalador la regla ***sintax on***

*  Plugins *molokai*, *prettier* y *CoC*.
Estos son 3 plugins que personalmente me gustan. Tu puedes escoger los que mas te gusten a ti.
Molokai me da un background oscuro y una sintaxis colorida que me encanta.
Prettier le da una organización al codigo limpia y profesional.
Y CoC un autocompletado y que te muestra errores.

* Y por ultimo; un editor de texto externo que te ayudara mucho en tu trabajo. Se llama Markor.
Lo puedes descargar en Droid. Si no tienes otro puedes usar este. Es ligero y de código abierto.

####  Errores que cometí.

No creas que para mi esto fue *coser y cantar*.
Me enfrenté y me enfrentaré a muchos quebraderos de cabeza.
Pero en eso consiste el aprendizaje.
Esto me hizo volver a los manuales de programación web, y la ayuda que ofrece la IA son invaluables.
Ahora te muestro los 3 errores que cometí y espero que tu no lo cometas.


##### 1. Publicar el trabajo antes de estar listo

Esto no se debe hacer; porque hubo momentos en que dañé la página y eso es lo que mostraba a quien pudiera abrirla. Y cosas como eso; lo muestran a uno como poco serio e irresponsable.

##### 2. Editar código aquí, allá y acuyá

El trabajo tiene que hacerse ordenadamente.
Si editas tu página web, empieza por el esqueleto del html, el head, el titulo y lo s links a tu hoja de estilos y otras paginas que compongan tu proyecto.
Eso sin olvidar los metadatos como el *charset y el wieport*.
Luego el *body* al que vas agregando en el css el color de background y así, trabajando a la par html y css hasta que quedes sastifecho con tu trabajo.

##### 3.  Copiar y pegar código

De todos los errores; este es el más infame y el que menos aprovecha para el aprendizaje.
No te culpes si lo haces, porque yo mismo lo he hecho. 
En la ocasión que dañé mi página por un error que no encontraba (Cuando eso no tenía CoC instalado): me dediqué a cortar y pegar código a diestea y siniestra, terminando todo en una chalupa. 
Pero estoy consciente que si lo hacemos con frecuencia lo volvemos un hábito muy perjudicial y difícil de sacar.

### Despedida.

Bueno, no sé si me estoy escribiendo a mi mismo, pero si alguien ha estado leyendo: le deseo mucha suerte en el camino de la programación.
Y si en algo pudiera ayudar.
Puedes enviarme un email a itaigad2002@gmail.com


Att.

***Omar Santiago***  





