<h1>Linux Manga Downloader²</h1>
<a href='http://kuroscript.files.wordpress.com/2011/06/penc2b2-lmd-lgg-mid.png'><img src='http://kuroscript.files.wordpress.com/2011/06/penc2b2-lmd-lgg-mid.png' alt='' height='280' width='251' title='pen²' /></a>


Como dije, predije y maldije el LMD publica versión estable a finales de mes, el ultimo día si algo apurado voy pero algo es algo, preparaos para leer por que el changelog de esta versión es largo.

<strong>-Novedades-</strong>
<ul>
<blockquote><li>Nueva GUI completamente rediseñada</li>
<li>Nuevo Logo el de arriba</li>
<li>Compilación deb y rpm</li>
<li>Numerosos servidores (Mcanime, submanga, mangafox, futahentai, e-hentai, animea, etc...)</li>
<li>Funciones de lista, listando los ultimos mangas en mcanime y submanga.</li>
<li>limpieza en mangafox, las paginas descargadas se les quita el pie de pagina de manera automatica</li>
<li>Otros scripts, pequeños scripts de descarga.</li>
<li>Soporte para descarga de paginas HD en submanga</li>
<li>Full soporte a submanga v3</li>
<li>Configuracion personalizada.</li>
<li>Multi Idioma (De momento Español y Catalán) (Pronto mas)</li>
<li>Notificaciones por D-Bus con libnotify</li>
<li>Mejor velocidad en descarga.</li>
</ul>
<strong>-Información-</strong>
Esta nueva versión del LMD tiene ciertas dependencias que necesitan cubrirse para que el programa funcione.<br>
Dependencias:<br>
libnotify-bin<br>
wget<br>
gtkdialog<br>
lynx<br>
zenity<br>
Todas excepto pueden ser encontradas en los repositorios officiales, aunque gtkdialog no esta en todas, en ubuntu no esta mientras que en debian si.<br>
para gtkdialog hay estos 2 deb que se pueden descargar:<br>
<a href='http://launchpadlibrarian.net/14537936/gtkdialog_0.7.20-4_i386.deb' title='Gtkdialog i368'>Arquitectura i368</a>
<a href='http://launchpadlibrarian.net/14540941/gtkdialog_0.7.20-4_amd64.deb' title='Gtkdialog amd64'>Arquitectura amd64</a>
<strong></strong></blockquote>

<strong>-Screens-</strong>

<a href='http://kuroscript.wordpress.com/2011/06/30/release-lmd%c2%b2/pen%c2%b2-lmd-lgg-mid/' title='pen²'><img src='http://kuroscript.files.wordpress.com/2011/06/penc2b2-lmd-lgg-mid.png?w=134&#038;h=150' alt='pen²' height='150' width='134' title='pen²' /></a> <a href='http://kuroscript.wordpress.com/2011/06/30/release-lmd%c2%b2/xonf-window/' title='Xonf window'><img src='http://kuroscript.files.wordpress.com/2011/06/xonf-window.png?w=138&#038;h=150' alt='Xonf window' height='150' width='138' title='Xonf window' /></a> <a href='http://kuroscript.wordpress.com/2011/06/30/release-lmd%c2%b2/sm-listpoc/' title='SM-List(POC)'><img src='http://kuroscript.files.wordpress.com/2011/06/sm-listpoc.png?w=150&#038;h=115' alt='SM-List(POC)' height='115' width='150' title='SM-List(POC)' /></a> <a href='http://kuroscript.wordpress.com/2011/06/30/release-lmd%c2%b2/gui/' title='gui'><img src='http://kuroscript.files.wordpress.com/2011/06/gui.png?w=150&#038;h=99' alt='gui' height='99' width='150' title='gui' /></a>

<strong>-Instalación-</strong>
El proceso de instalación es muy simple y no suelta errores si se hace bien eso esta claro.
Primero instalamos todas las dependencias del programa (Dichas arriba)
Nos descargamos el LMD
<ul>
<blockquote><li><a href='http://code.google.com/p/linux-manga-downloader/downloads/detail?name=linux-manga-downloader_0.2.0.1-4Beta_all.deb&amp;can=2&amp;q='>Paquete deb</a></li>
<li><a href='http://code.google.com/p/linux-manga-downloader/downloads/detail?name=linux-manga-downloader_0.2.0.1-4Beta_all.rpm&amp;can=2&amp;q=label%3AFeatured'>Paquete rpm</a></li>
</ul>
lo instalamos con gdebi o con comandos como se prefiera, funciona de las 2 igual, si no se instalase revisad que tenga permisos de ejecucion (chmod +x &lt;file&gt;)<br>
Una vez instalado no lo vayamos a ejecutar aun, hay que ejecutar un comando en la terminal para que el LMD funcione bien.<br>
<blockquote>lmd-fu -reconf</blockquote>
Una vez echo esto ya podremos llamar al LMD ya sea por terminal como por  menu de aplicaciones &gt; graficos &gt; LMD<br>
Es aconsejable estipular un directorio de descarga personalizado, se puede hacer en el menú de configuración del LMD, es muy simple ;)<br>
Recomiendo no ejecutar el programa con sudo, ya que después produce errores de permisos.<br>
En caso de que se quisiera des-instalar se utilizaría el apt<br>
<blockquote>sudo apt-get remove linux-manga-downloader</blockquote>
Y listos programa des-instalado.</blockquote>

<strong>-Extras y Agradecimientos-</strong>
Ahora no pero pronto si publicare un manual de su utilización pero sinceramente no es muy complicado.
Agradezco a Shini-kire que me ha estado ayudando con el beta test y también a Kratter que sus consejos y apoyo me fueron de lujo en alguna parte la programación del LMD.
Avances sobre la próxima versión:
<ul>
<blockquote><li>Soporte a Mangastream &amp; Binktopia</li>
<li>Multi idioma mas idiomas, ingles y frances.</li>
<li>Algun otro servidor.</li>
</ul></blockquote>

Recordad comentar ;) haced algo de feedback que no cuesta nada.
