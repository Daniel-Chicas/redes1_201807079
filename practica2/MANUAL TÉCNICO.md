<p>UNIVERSIDAD DE SAN CARLOS DE GUATEMALA</p>
<p>FACULTAD DE INGENIERIA</p>
<p>ESCUELA DE CIENCIAS Y SISTEMAS</p>
<p>LABORATORIO DE REDES Y COMPUTADORAS 1</p>
<p>PRIMER SEMESTRE 2023</p>
<p>ING. PEDRO PABLO HERNÁNDEZ RAMÍREZ</p>
<p>TUTOR EDWIN ANTONIO LÓPEZ ORDÓÑEZ</p>

---


---


---


---


---


---


---

<center> <h1>PRACTICA #2</h1> </center>
<center> <h1>COMUNICACIÓN ENTRE 2 EMPRESAS</h1> </center>



---


---


---


---



| Nombre   |      Carnet      |  
|----------|:-------------:|
| Daniel Estuardo Chicas Carías    | 201807079 | 


---


---


---


---




---


---


---


---


---



---

# <a name="nothing"></a>MANUAL DE TÉCNICO
Este documento contiene toda la información sobre los recursos utilizados por el programa para desplegarlo y utilizarlo, explicando todo el trabajo que se ha realizado al crear la topología de red.

>“Programa desarrollado en PNETLab y Wireshark que permite simular una topología de una red para un pequeño negocio de dos niveles.”
## <a name="intro" ></a>ÍNDICE

| Topico | Link |
| ------ | ------ |
| Introducción | [Ir](#intro) |
| Información del sistema | [Ir](#inf) |
| Objetivos y alcances del sistema| [Ir](#ob) |
| Información del Sistema requerido | [Ir](#sis) |
| Sistema Operativo | [Ir](#sis) |
| Tecnologías utilizadas | [Ir](#tech) | 
| Conclusiones | [Ir](#Conclu) |

## <a name="intro" ></a>INTRODUCCIÓN
El presente manual técnico tiene como finalidad describir la estructura y diseño del programa que se realizó como parte de Practica 2, así como dar explicación de los como usted como desarrollador puede mejorar y comprender el funcionamiento.

## <a name="inf"></a>Informacion del Sistema
La topología de red se define como un mapa físico o lógico de una red para intercambiar datos. En otras palabras, es la forma en que está diseñada la red, sea en el plano físico o lógico. El concepto de red puede definirse como «conjunto de nodos interconectados».

En esta práctica se realizó una topología de red básica, en donde se puede realizar ping entre computadoras de los 2 niveles, donde cada una tiene una ip asignada y se puede realizar captura de paquetes entre ellas.

## <a name="ob"></a>Objetivos y alcances del sistema

### Objetivo General
- Que el estudiante demuestre los conocimientos adquiridos en clase y ponga en práctica lo aprendido para configurar enrutamiento entre redes.
### Objetivos Específicos
- Demostrar el conocimiento adquirido respecto a la agregación de enlaces.
- Demostrar el conocimiento adquirido para la creación de rutas estáticas.
- Demostrar el conocimiento adquirido respecto a la puerta de enlace predeterminada, así como también para el manejo de protocolos de redundancia en la misma.
- Emplear la herramienta PNETLab para desarrollar la topología de acuerdo con las especificaciones dadas.

## <a name="sis"></a>Especificaciones del Sistema requerido

### <a name="sis"></a>Requisitos de Hardware 
|  | PNETLab |
| ------ | ------ |
|Memoria mínima|  1 GB|
|Memoria recomendada |  2 GB|
|Espacio en disco mínimo| 500 MB de espacio libre |
|Espacio en disco recomendado |  1 GB de espacio libre|
|Sistema operativo | Windows 7 o posterior, MacOS X 10.12 o posterior, o Linux con glibc 2.19 o posterior | 
|Procesador | Intel Core i3 o equivalente |

### <a name="sis"></a>Requisitos de software
## <a name="sis"></a>Sistema operativo 
Windows
- Windows 10 (8u51 y superiors)
- Tener instalado el programa de Proteus y Librerias de Arduino Code u otro editor
- RAM: 128 MB
- Espacio en disco: 124 MB 
- Procesador: Mínimo Pentium 2 a 266 MHz 
- Algún explorador de internet
Mac OS X 
- Tener instalado el programa Proteus Code u otro editor
- Explorador de 64 bits 
- Se requiere un explorador de 64 bits (Safari, Firefox, por ejemplo) para ejecutar Oracle Java en Mac OS X.
Linux
- Oracle Linux 5.5+1 
- Oracle Linux 6.x (32 bits), 6.x (64 bits)2 
- Exploradores: Firefox


## <a name="tech"></a>Tecnologías Utilizadas
- PNETLab 

## <a name="Conclu"></a>Conclusiones


### PNETLab: 
- Es una herramienta de simulación de redes de computadoras que permite a los usuarios crear, simular y evaluar diferentes topologías de redes.
- Ofrece una interfaz gráfica de usuario intuitiva y fácil de usar para configurar y visualizar la simulación. 

## <a name="Conclu"></a>Apéndice

<p align="center">
  
## <a></a>TOPOLOGÍA
  <a href="#"><img src="./Topología.jpeg"/></a>

  
## <a></a>CONFIGURACIÓN DE ROUTERS R1, R2 Y R5
  <a href="#"> 
    # <a></a>ROUTER 1
    <img src="./Configuración de Router/R1.PNG"/> 
    # <a></a>ROUTER 2
    <img src="./Configuración de Router/R2.PNG"/> 
    <img src="./Configuración de Router/HSRP R2.PNG"/> 
    <img src="./Configuración de Router/R2-VIRTUAL.PNG"/>
    # <a></a>ROUTER 3
    <img src="./Configuración de Router/R3.PNG"/> 
    <img src="./Configuración de Router/HSRP R3.PNG"/> 
    <img src="./Configuración de Router/R3-VIRTUAL.PNG"/>
    # <a></a>ROUTER 5
    <img src="./Configuración de Router/R5.PNG"/>  
    <img src="./Configuración de Router/R5-VIRTUAL.PNG"/>
    # <a></a>ROUTER 6
    <img src="./Configuración de Router/R6.PNG"/>  
    <img src="./Configuración de Router/R6-VIRTUAL.PNG"/>
  </a>


## <a></a>CONFIGURACIÓN DE SWITCH S7
  <a href="#"> 
    <img src="./Configuracion SW7/1.PNG"/>  
    <img src="./Configuracion SW7/2.PNG"/>  
    <img src="./Configuracion SW7/3.PNG"/>
    <img src="./Configuracion SW7/4.PNG"/>    
  </a>

## <a></a>CONFIGURACIÓN DE MÁQUINA VPC11
  <a href="#"> 
    <img src="./Configuracion VPC11/1.PNG"/>    
  </a>


## <a></a>COMANDOS UTILIZADOS PARA LA PRÁCTICA
| Comando | Descripción |
| --- | --- |
| enable | Activa el modo de privilegio ejecutivo en el switch o router. |
| configure terminal | Permite al usuario ingresar al modo de configuración global en el switch o router. |
| hostname sw8 / hostname R2 | Permite cambiar el nombre del switch o router a "sw8" o "R2", respectivamente. |
| interface Port-channel 1 | Crea una interfaz de portchannel con el número de puerto 1 en el switch. |
| description conexion a SW7 | Agrega una descripción a la interfaz de portchannel creada. |
| exit | Permite al usuario salir del modo de configuración de interfaz. |
| do show run | Muestra la configuración actual de ejecución en el switch o router. |
| interface range ethernet 0/0-1 | Selecciona los puertos ethernet 0/0 y 0/1. |
| channel-group 1 mode | Agrega los puertos ethernet seleccionados al grupo de canales de puerto 1, utilizando el modo especificado (PAGP o LACP). |
| show etherchannel summary | Muestra un resumen de la configuración del canal de Ethernet en el switch. |
| show lacp neighbor | Muestra información sobre los vecinos LACP del switch. |
| show run interface e0/0 | Muestra la configuración actual del puerto e0/0. |
| configure terminal | Permite al usuario ingresar al modo de configuración global en el switch o router. |
| interface range e0/0-2 | Selecciona los puertos ethernet e0/0, e0/1 y e0/2. |
| no channel-group 1 mode | Desactiva la agrupación de canales de puerto para los puertos seleccionados. |
| ip *ip* *puerta de enlace* / ip address *puerta de enlace* *máscara* | Configura la dirección IP y la puerta de enlace en un dispositivo VPC o router. |
| save | Guarda la configuración actual del dispositivo VPC. |
| standby 1 ip *ip virtual* / glbp 7 ip *ip* | Configura la dirección IP virtual para HSRP o GLBP en un router. |
| standby 1 priority 101 / glbp 7 priority 99 | Configura la prioridad para HSRP o GLBP en un router. |
| standby 1 preempt / glbp 7 load-balancing round-robin | Configura la preemption para HSRP o el balanceo de carga para GLBP en un router. |
| do show standby brief / do show glbp brief | Muestra un resumen de la configuración de HSRP o GLBP en un router. |
| ip route *red que se conecta* *máscara de red* *ip a la que me quiero enlazar* | Agrega una ruta estática a la tabla de enrutamiento de un router. |
| show running-config | section ip route | Muestra la sección de la configuración actual que contiene información sobre las rutas estáticas en un router. |
| /29: 255.255.255.248 <br> /30: 255.255.255.252 <br> /24: 255.255.255.0 | Ejemplos de máscaras de subred utilizadas para definir el tamaño



## <a></a>Comandos para  Creación de ruta estática, creación de PortChannel con PAGP y LACP, creación de IP virtual con HSRP y GLBP y configuración de VPC.

| Funcionalidad | Comando | Descripción |
| --- | --- | --- |
| Creación de ruta estática | enable<br><br>configure terminal<br><br>ip route <red> <máscara> <ip> | Habilita el modo privilegiado, entra en la configuración y agrega una ruta estática hacia una red determinada. |
| Creación de PortChannel con PAGP y LACP | enable<br><br>configure terminal<br><br>hostname <nombre><br><br>interface Port-channel 1<br><br>description <descripción><br><br>exit<br><br>interface range ethernet 0/0-1<br><br>channel-group 1 mode <modo><br><br>show etherchannel summary<br><br>show lacp neighbor<br><br>show run interface e0/0<br><br>configure terminal<br><br>interface range e0/0-2<br><br>no channel-group 1 mode <modo> | Habilita el modo privilegiado, entra en la configuración, asigna un nombre al switch y configura un PortChannel con PAGP y LACP. Luego, muestra información sobre el PortChannel creado y los puertos que lo conforman. Por último, desactiva los puertos del switch. |
| Creación de IP virtual con HSRP y GLBP | **HSRP:**<br><br>enable<br><br>configure terminal<br><br>hostname R2<br><br>interface e0/1<br><br>ip address <ip> <máscara><br><br>no shut<br><br>standby 1 ip <ip virtual><br><br>standby 1 priority 101<br><br>standby 1 preempt<br><br>do show standby brief<br><br>**GLBP:**<br><br>enable<br><br>configure terminal<br><br>glbp 7 ip <ip><br><br>glbp 7 priority 99<br><br>glbp 7 load-balancing round-robin<br><br>do show glbp brief | Habilita el modo privilegiado, entra en la configuración, asigna un nombre al router y configura una IP en una interfaz. Luego, configura un IP virtual con HSRP o GLBP y muestra información sobre el protocolo configurado. |
| Configuración de VPC | ip <ip> <puerta de enlace><br><br>save | Configura una dirección IP y una puerta de enlace en una VPC y guarda la configuración. |

## <a></a>Comandos empleados para la verificación del correcto funcionamiento de los protocolos empleados para la realización de la práctica

| Protocolo | Comando | Descripción |
| --- | --- | --- |
| HSRP | show standby brief | Muestra un resumen de la información de HSRP, incluyendo el estado actual de la interfaz virtual y los routers que participan en el protocolo. |
| GLBP | show glbp brief | Muestra un resumen de la información de GLBP, incluyendo el estado actual de los grupos de balanceo de carga y los routers que participan en el protocolo. |
| VPC | ping <ip> | Verifica la conectividad con otra VPC o con un router mediante la transmisión de paquetes ICMP. |
| Rutas estáticas | show ip route | Muestra la tabla de enrutamiento del router, incluyendo las rutas estáticas que se han configurado. |
| PortChannel | show etherchannel summary<br><br>show lacp neighbor<br><br>show interfaces port-channel 1 | Muestra un resumen de la información del PortChannel, incluyendo el estado actual, los puertos que lo conforman y los paquetes transmitidos y recibidos por la interfaz. |


</p>

