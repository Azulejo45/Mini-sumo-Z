
### ┍━━━━━━━━━━━━»•»  «•«━━━━┑
#   ┕Zungetsu-MiniSumo┙        

### - Proyecto de mini sumo con la capacidad de ser controlado de manera bluetooth y automata. Equipado con 4 sensores:  2 laterales, 1 frontal y uno en la parte inferior, el de piso.
♥

## ..••°°━✦❘༻⋞ 〈 Autores  〉 ⋟༺❘✦━━°°••..

- ⋆ˊˎ-   ┌──༺♥༻❀**Velazquez Joaquim**❀༺♥༻
  
- ⋆ˊˎ-  **Rodriguez Thiago**

### *---16/3/2026---*

♥
## •*¨*•.¸¸☆*･ﾟ Especificaciones generales ﾟ･*☆¸¸.•*¨*•

˚₊· ͟͟͞͞➳❥ Dimensiones del robot: 10 cm x 10 cm x 4,5 cm.

˚₊· ͟͟͞͞➳❥ Consumo total: 7,4V.

˚₊· ͟͟͞͞➳❥ Corriente total: 800mA.

˚₊· ͟͟͞͞➳❥ Material de la carrocería: PLA.

˚₊· ͟͟͞͞➳❥ Peso (aproximado): 300g.
## ✭∞∞∞∞∞∞∞∞✭∞∞•,¸,.·' ✩ '·.,¸,•∞∞✭∞∞∞∞∞∞∞∞✭

♥
## Objetivo del proyecto
### ✩°｡𓂃𓏧︶︶︶︶︶︶︶︶┈୨•♡•୧┈︶︶︶︶︶︶︶𓂃𓏧｡°✩
_El objetivo principal de este proyecto es poner a prueba lo aprendido en años anteriores y este, pudiendo aplicarlo en el proceso de preparacion y  creacion de un robot modelo Mini-Sumo, siguiendo el reglamento de la liga nacional de robotica LNR, para que se encuentre en condiciones en poder participar en una competencia de esta misma_
### ✩°｡𓂃𓏧⌒⌒⌒⌒⌒⌒⌒⌒┈୨•♡•୧┈⌒⌒⌒⌒⌒⌒⌒⌒𓂃𓏧｡°✩
\
\
.
### ∘₊✧───∘₊✧───•-•⟮ ◆ ⟯•-•───✧₊∘───✧₊∘
## ˗ˏˋ ꒰ **Este proyecto fue realizado con algunos componentes en donde se puede llegan a encontrar:** ꒱ ˎˊ˗

- Micro: Esp32 C3 super mini.
 > Memoria: 400 KB SRAM, 4 MB Flash.Conectividad: Wi-Fi (2,4 GHz).\
 > Bluetooth 5.0 LE (Low Energy).\
 > Alimentación: Funciona a 3,3 V con entrada USB-C de 5 V.

- Bateria de Lipo.
 > Almacenamiento: 7,4V.\
 > 2 celdas (3,7V por celda)
  
- Sensor de piso: TCRT5000.
 > Voltaje de operación: 3.3V-5V.\
 > Dimensiones: 31 mm × 13 mm × 2 mm.\
 > Rango de detección: 30° más amplio.

- Sensor detector de obstáculos: HC-sr04.
 > Voltaje de operacion: 5V.\
 > Cantidad de pines: 4.\
 > Distancia de deteccion: 2 a 450cm.
 
- Motores: Micro motores Pololu 250RPM.
 > Dimensiones: 26x10x12mm.\
 > Voltaje de operacion: 6V.\
 > Torque maximo: 333Nm (Newton - metro).

- Puente H: DRV8833.
 > Dimensiones: 4 mm × 18,1 mm × 21,1 mm.\
 > Voltaje de operacion: 2.7V-10.8V.\
 > Corriente máxima de salida: 1,5A.
 ### ∘₊✧───∘₊✧──────✧₊∘───✧₊∘
\
.
## ╔══✬✩══╡˚✧Componentes utilizados✧˚╞══✩✬══╗
- ➸ *Esp32 C3 super mini.*
- ➸ *Bateria de Lipo.*
- ➸ *TCRT5000.*
- ➸ *HC-sr04.*
- ➸ *Micro motores Pololu 250RPM.*
- ➸ *DRV8833.*
## ╚═══*+:｡ . ｡:+*═══✮❁•°❀°•❁✮═══*+:｡ . ｡:+*═══╝
/
/
/
/
/
♥
# Diseño del circuito


## Descripcion del funcionamiento

El minisumo utiliza tres sensores para guiarse, con dos ubicados en los costados; otro en la parte frontal. Cuando un objeto entra en el rango del sensor frontal, el minisumo avanza hasta chocar contra dicho objeto. Esto siempre se cumple hasta que se quite la orden.\
Cuando uno de los sensores en los costados detectan algo cerca, se posiciona para estar de frente al objeto, retrocediendo y girando en direccion paralela a este.
Este mismo, utiliza el sensor de piso para evitar salirse del dohyo, detectyando la franja limite y volviendo para no estar tan vulnerable a cualquier empuje que lo saque de juego.

#esquematico

## Layout de PCB

# Pasos a seguir para armar el mini-sumo
## ˚*•̩̩͙✩•̩̩͙*˚＊˚*•̩̩͙✩•̩̩͙*˚＊˚*•̩̩͙✩•̩̩͙*˚＊˚*•̩̩͙✩•̩̩͙*˚＊˚*•̩̩͙✩•̩̩͙*˚

### Primero elistaremos las herramientas necesarias para llevar a cabo la placa.
-Un recipiente\
-Percloruro\
-Una agujereadora\
-Una placa de cobre\
-Papel fotografico\
-Tinta Tonel\
-Una impresora(Para imprimir el diseño PCB)
-Cable USB-C (Para cargar el codigo.)


 
 ### -|preparación de la placa:

1. Descargar el archivo de PCB de "Zungetosu(MiniSumo).kicad_pcb".
2. Imprimir el PCB en una hoja fotográfica (como lo son las hojas de revista) con tinta "tonel".
3. Proceda a planchar el PCB a la placa del lado del cobre.
4. Revisar que el diagrama del PCB se haya pegado correctamente retirando la hoja fotográfica y cualquier excendete de esta(Utilice agua para remover con facilidad el papel).
5. Sumergir la placa en un recipiente con percloruro.
6. Dejarlo descansar un tiempo(Resivar periodicamente el cobre de la placa)
7. Cuando el cobre se haya disuelto y solo quede el diseño, retirarlo con CUIDADO(Es un liquido corrosivo;dificil de quitar de la ropa).
8. Limiparlo la placa con agua para quitar el excedente de percloruro.

 ### -|Soldar los componentes en la placa ya hecha en el siguiente orden:
 
1. Capacitores SMD
2. Pineras
3. Borneras
4. Resistencias SMD
5. Regulador AMS1117 SMD 3.3V
6. Regulador AMS1117 5V

 ### Medidas de seguridad.

- El percloruro es un tanto corrosivo, capáz de manchar con facilidad la ropa y otra prendas.\
- Cuando vaya a hacer agujeros en la placa, tiene que ser en una superficie solida. Es probable que la placa pueda salir dispara en una base dispareja o inquieta.\
- Mientra planche, este atento a no quemar completamente el papel. Podria causar un incendio.

### Tipo de soldadura/ensamble
Todos los componentes deben fijados a la placa mendiante "soldadura de ola", el cual se utiliza para componentes de orificio pasante (THT). Los componentes debe ser introducidos desde el lado de la placa lisa y sin diseño,para ser soldados en el cobre que se encuentra del otro lado.
En las pineras que estan direccionadas en horizontal, se debe colocar el ESP32(integrado).
En la pineras que se encuentran en vertical, el DRV8833.

### -|Carroceria

1. Descargar el modelo 3D de la carroceria.
2. Descargar un modelo 3D de dos braquets y 2 ruedas con un radio de 20mm.
3. Imprimir ambos archivos.
4. Comprar cuatro tornillos para tuerca M3, 6 tuercas M3 y 2 prisioneros M3.
5. Unir la carroseria con los braquets mediante 4 tornillos M3 y 4 tuercas M3.


### -|Codigo

El codigo establece las instrucciones que ejecutara el integrado para poder accionar y manejar al mini-sumo.\
este es bastante simple y considera los 4 sensores teniendo en cuenta que:

- No debe salir del tatami.
- Debe atacar y empujar al otro mini-sumo fuera del area.
- Esquivar al mini-sumo rival cuando se le de la orden.

#### -|Compilacion/Carga

Cuando la placa ya este monatada, se utilizara un cable USB tipo C para conectar el integrado(ESP32) a un ordenador. Mediante el programa [Arduino IDE](https://www.arduino.cc/en/software). Copie el codigo que se encuentra en este repositorio y pueguelo en el programa. En el apartado superior encontrara 4 botones.\
El primero es para verificar si el programa tiene errores\
El segundo es para subir el codigo al integrado\
El tercero no es importante para esto.\
El cuarto es para poder seleccionar la placa y el puerto\
En este ultimo, busque el siguiente modelo: ESP32_C3_SUPER_MINI, y seleccionelo. En caso de no encontrarlo, use el "ESP32 C3 DEV MODULE". Junto a eso, seleccione el puerto USB por el cual esta conectado a su ordenador(Se cuenta de izquierda a derecha).\
Ahora, verifique el codigo por el primero boton de la parte superior. Si marca algun error, copie el codigo entero de nuevo y vuelva a pegarlo./
Una vez verificada la funcionalidad del codigo, utilice el segundo boton presente para poder subir el codigo al integrado de la placa. Si hay alguno otro error durante este proceso, consulte internet.

#### -[Librerias
- Para poner librerias, dirigase al lateral izquierdo de la interfaz de Arduino IDE, y seleccione el tercer boton (que contiene un simbolo con libros).


#### -[Datasheets/Referencias

