
<div align="center">
<h1> Altium Introuction</h1> 
<p>

</p>

</div>


Shortcurs

el p abre el menu del esquematico 

Doble P -- pin 
G --- cambiar el tamaño del grid 
ctrl + reuda del raton --- eso se puede cambiar
p, l ---- shortcut para linea +.



<h2>Skematic </h2>
tool - neew componente 
La cracion de lineas es la misma que kica


dobleclid en el nombre del componente me abre las propiedadddes del sistena 
__________________________________ Hasta el video 3 es la misma joda que kicadd

u -- cambio de unidades

rotar el componenete ( x para vertical y para horizontal ) pero tengo que tener el item moviendose
cable p - w


tools -- anotation -- anotation schematic --  update change list - ok - acceot changes list  - execute changes - close x2

Place sheet symbol para añadir las secciones verdes 

<h2>Foortprint</h2>

Foor print similar a KICAd


Silskane  de arriba se crea en la capa top overlay 
''  de anajo  ''''' en la capa bottom overlay

vinculacion de modelo 3d a foodprint 

place--3d body 

se da tab, se abre las propieades de la hyella y se asigna el modelo 3d


clic derech ¿para mover
clir ddrecho mas shift oara rotar 

en la seccion rotar se puede alinear la huella con el modeo 3d a partir de la opcion toll- 3d body placemnet y sus opciones 

En esquematico el catodo es el numero 1 


  3 para mostra visualizacion 3d y 2 para 2d 


  Footprint wizard ---- importante para generar footprinrts ( no se si modelos 3d tambien)

  Para variar el centro del componente eddit-set reference y se selecciona la opcion 



  Diseño de la PCB

  Project - class generation y se dddeddsactiva  generate rooms
  desing - update ´pcb docuemnts -- execute changes

  Para el tamaño de la placa , se traza una area  en la capa mechanical y luego se selecciona y se da desing - board shape   - define from selectedd objects



  Desing - rules  aca estan las reglas de diseño de la opcb 



  track es la pista 

  zonas se hace el area y se presiona tab 


  Exportar docuemtnos 
    click derecho en el nombre del proyecto add new project output job file    ...  ddenro de esta ventaan se va  la pesraña ddocuemntation outputs- pcb print  pcb document   
    Se da clicj derecho sobre ese archivo para ver las capas que muestra el pdf 


    la caoa de arriba suempre se hace con mirror 

    Show holes es una importnte opcion  Si algo este punto es mi debil --.. entonces queda pedniente revisar el vide 10


Video 11 --- genracion de los archivos gerber 

En la misma o¿opcion anterior se da en fabiraction outputs  ---- geber x2 files -- pcb docuemtn -- se seleccionan todas las capas 
mirar video 11 minuti 1:30

eFabricarion outpus ---- drill ocuemtn



Video 12 Genrar pdf 3d



<h2>Curso Basico FAC Altium </h2>




Se da en doducment generator 

Clase de 4/27/2023
Normativa IPC para documentos electronicos
Materuales 

Clase de 02/05/2023 
Inicio de ALtium 
Tipos de Pines Input I . Output O I/O Bidirecciianl
Puertos y referencia de puertos 
Customizacion de Altium
Shortcuts 
[Altium Shortcut ](https://www.altium.com/documentation/altium-designer/shortcut-keys)



Clase de 04/05/2023

Smart Pase -- muy importante
cTRL+SHIFT+V

Panel de busqueda de elementps - Manufacturer Part Search
En interntet Octopart, se peuen buscar disponibilidad de componentes electronicos disponibles pra la compra 


Desde el teimpo 1:15 hay una forma de generar un nuevo bus de infromacion por otras opciones. Valdra la pena repasar esto si en algun momento necesito otras opciones 

Para añadir librerias se abre el menu de la barra derecha que dice componentes y en las tres lineas se da filled based-componentes preferences. Se añade el archivo ,lib y queda.

El tab funciona como una especie de pausa de aoperacion o pausa de comando para poder editar el comando que se queire realziar.


Altium tiene distinas formas de colocar el esquematico de un componente. Por ende , si se quiere seleccionar que tipo de configuración se usa el tab y se selecciona la opcipn.
Hay varuas configuraciones como lo son la fisica, la division por funcionalidad de los pines ( seññales, entradas, alimeantaciones) etc
 

EStuair Interfaces de comunicacion 

Clase de 09/05/2023


Creacion de biblioteca de componentes

Igual que kicad


Thermal RElief  investigar sobre este efectok 

REvisar este vieo la verdad no puse demasiada atencuon se hizo una confugracuin de grilla



Clase 11/05/2023

ESquematicos Jerarquicos 

Esqueematico multicanal 
ERC  Electrical Rules Check 
Creaacion del esquematico del proyecto 


Clase 16/05/2023


Herramienta  para la asignacion de designadores  de referencia 


Designador ( Letra+ numero)
Para realizar la designacion en de los componentes de manera atutomatica   Tools  ---- Annotation --- Anotate Schematic 
Priomera meddia hora del videdo es sobre asignacion hasta el minuto 38
En tools --- Annotatio -- Number Schematic Sheets .... Para definir el orden de designacion de omponenes en caso que se tengana varios esquematicos 


Tools --- Annotation --- Board Level Annotation 

Verificacion ERC



Creacion de la PCB 



//// PC/104 es un estandar para montaje de sistemas embebios -- vale la pena darle una revisada

Exportar componnentes --- En el esquematico Desing --update PCB Document ...


En el entorno de la PCB para ver las lineas de econexion ctrl + clicl izquierdo sobre el pin 


IMPORTANTE ---  ESQUEMATICOS EL PROYECTO AL TIEMPO 1:36:01 



Clase 18/05/2023 


No hay nada 


Clase 23/05/2023


Diseño multicanal 

Parte incial del curso habla de una configuracion para mejorar la veisualizacion 

Mas o menos en la mitad de etse video muestran como tener una ventana separada para tenrr esquemtico y pcb unidos 


Place -- Fill para generar zonas 


Al generar archivos por jerarquia se generar boards en la pcb . Para poder mover los componentes ascociados  a la board se usa Tools - Componente Placemean - Arrange Within Room 

Navegacion 
 


Clase 25/05/2023


Para verficiar erroes en los esquematicos darle ala pcB y luego la primera opcion --- referencia 18:57 min


Clase   30/05/2023

Simulacion SPICE en altium ddesinger
Generacion de archivos de farbicacion 
