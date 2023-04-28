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

<center> <h1>PROYECTO #2</h1> </center>
<center> <h1>COMUNICACIÓN ENTRE 2 EMPRESAS LEJANAS</h1> </center>



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

  
#  Resumen de IP y VLAN
 
<p align="center">
  <a href="#"><img src="./Imagenes/Central.png"/></a>
</p>

---
---

<p align="center">
  <a href="#"><img src="./Imagenes/Core.png"/></a>
</p>

---
---

<p align="center">
  <a href="#"><img src="./Imagenes/Jutiapa.png"/></a>
</p>

---
---
  
<p align="center">
  <a href="#"><img src="./Imagenes/Central.png"/></a>
</p>

---
---
  
<p align="center">
  <a href="#"><img src="./Imagenes/Jutiapa-J1J2.png"/></a>
</p>

---
---
  
<p align="center">
  <a href="#"><img src="./Imagenes/Centra - C1C2.png"/></a>
</p>

---
---
  
<p align="center">
  <a href="#"><img src="./Imagenes/Tablas.png"/></a>
</p>

---
--- 


# TOPOLOGÍA
<p align="center">
  <a href="#"><img src="./topología.png"/></a>
</p>



# COMANDOS UTILIZADOS

<p align="center">

## Grupo 1: Comandos de configuración de VTP
| Comando |  Descripción |
| ------- |  ----------- |
| `conf t` |  Accede al modo de configuración global del dispositivo |
| `hostname <nombre>` |  Establece el nombre del dispositivo |
| `enable secret <contraseña>` |  Establece la contraseña de nivel de privilegio 15 |
| `username <nombre> secret <contraseña>` |  Crea un nuevo usuario con su respectiva contraseña |
| `interface <interfaz>` |  Accede al modo de configuración de una interfaz |
| `ip address <ip> <máscara>` |  Establece la dirección IP de una interfaz |
| `no shutdown` | Activa una interfaz |
| `exit` |  Sale del modo de configuración actual |
| `show running-config` |  Muestra la configuración actual del dispositivo |
| `copy running-config startup-config` |  Guarda la configuración actual en la memoria persistente |


## Grupo 2: Comandos de configuración de VLAN
| Comando | Descripción |
|---------|-------------|
| vlan NUMERO | Crea una nueva VLAN con el número especificado. |
| name NOMBRE | Asigna un nombre a la VLAN creada anteriormente. |
| do show vlan | Muestra información sobre todas las VLANs configuradas en el switch. |
| do show vtp status | Muestra información sobre el estado actual del protocolo VTP. |

## Grupo 3: Comandos de configuración de interfaces
| Comando | Descripción |
|---------|-------------|
| int e0/1 | Selecciona la interfaz Ethernet 0/1. |
| switchport mode access | Configura la interfaz seleccionada como una puerta de acceso a una sola VLAN. |
| switchport access vlan *número vlan* | Asigna la VLAN especificada a la interfaz seleccionada. |
| interface e0/0 | Selecciona la interfaz Ethernet 0/0. |
| switchport trunk encapsulation dot1q | Configura la interfaz seleccionada para que use la encapsulación 802.1Q para las tramas VLAN. |
| switchport mode trunk | Configura la interfaz seleccionada como un puerto trunk que puede transmitir varias VLANs. |
| interface e0/0.*vlan* | Crea una subinterfaz para la VLAN especificada en la interfaz Ethernet 0/0. |
| encapsulation dot1Q *vlan* | Configura la encapsulación para la subinterfaz de la VLAN especificada. |
| ip address *ip* *máscara de subred* | Asigna una dirección IP y una máscara de subred a la interfaz o subinterfaz seleccionada. |
| no shutdown | Activa la interfaz o subinterfaz seleccionada. |


## Grupo 4: Comandos de configuración de protocolos de redundancia
| Comando                                      | Descripción                                                               |
|----------------------------------------------|---------------------------------------------------------------------------|
| spanning-tree vlan 1 root primary             | Configura el switch como raíz de spanning tree para la VLAN 1.             |
| spanning-tree mode rapid-pvst                | Configura el modo de spanning tree como Rapid PVST+.                       |
| standby 1 ip *ip virtual*                    | Configura la dirección IP virtual para el grupo HSRP 1.                   |
| standby 1 priority 101                       | Configura la prioridad del switch en el grupo HSRP 1 como 101.            |
| standby 1 preempt                            | Activa la función de prelación para el grupo HSRP 1.                       |
| glbp 7 ip *ip virtual*                       | Configura la dirección IP virtual para el grupo GLBP 7.                   |
| glbp 7 priority 99                           | Configura la prioridad del switch en el grupo GLBP 7 como 99.             |
| glbp 7 preempt                               | Activa la función de prelación para el grupo GLBP 7.                       |
| glbp 7 load-balancing round-robin            | Configura el algoritmo de balanceo de carga para el grupo GLBP 7 como round-robin. |
| do show standby brief                        | Muestra información resumida del estado de los grupos HSRP.                |




## GRUPO 5: Comandos empleados para la verificación del correcto funcionamiento de los protocolos 

| Protocolo | Comando | Descripción |
| --- | --- | --- |
| HSRP | show standby brief | Muestra un resumen de la información de HSRP, incluyendo el estado actual de la interfaz virtual y los routers que participan en el protocolo. |
| GLBP | show glbp brief | Muestra un resumen de la información de GLBP, incluyendo el estado actual de los grupos de balanceo de carga y los routers que participan en el protocolo. |
| VPC | ping <ip> | Verifica la conectividad con otra VPC o con un router mediante la transmisión de paquetes ICMP. |
| Rutas estáticas | show ip route | Muestra la tabla de enrutamiento del router, incluyendo las rutas estáticas que se han configurado. |
| PortChannel | show etherchannel summary<br><br>show lacp neighbor<br><br>show interfaces port-channel 1 | Muestra un resumen de la información del PortChannel, incluyendo el estado actual, los puertos que lo conforman y los paquetes transmitidos y recibidos por la interfaz. |


</p>


#  CAPTURAS DE WIRESHARK
  
##  Vlan
<p align="center">
  <a href="#"><img src="./Imagenes/VLAN - WIRESHARK.png"/></a>
</p>

## GLBP
<p align="center">
  <a href="#"><img src="./Imagenes/GLBP - WIRESHARK.png"/></a>
</p>

## HSRP
<p align="center">
  <a href="#"><img src="./Imagenes/HSRP - WIRESHARK.png"/></a>
</p>
