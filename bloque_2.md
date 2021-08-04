### Preguntas del Bloque 2

### 001. Utiliza 8 bits para representar cada carácter, por lo que puede codificar hasta 256 símbolos distintos

A Código Binario  
B Código EBCDIC  
C Código ASCII  
D Código BCD de intercambio normalizado

<details> 
 <summary>Respuesta</summary> 

<blockquote>
EBCDIC encondig family.  <br>
Classification. 8-bit Lating encoding  <br>
Preceded by  BCD
</blockquote>
 </details>

### 002. En el comienzo de cada ciclo de instrucción la CPU busca en la memoria una instrucción. En una CPU tipo Von Neumann para realizar esta tarea se dispone de un registro especial llamado.
A Contador de programa  
B Contador de ciclo  
C Contador de instrucción  
D Registro de control  
<details> 
 <summary>Respuesta</summary> 

A.
<blockquote> 
En la arquitectura Von Neumann es importante conocer el ciclo fetch-decode-execute que procesa las instrucciones de un programa. Los pasos son: <br>
1. La dirección de memoria almacenada en el contador de programa se copia en el registro de dirección de memoria o (RDM)-(MAR). <br>
2. La dirección en el cp aumenta en un valor, almacenando así la siguiente dirección de memoria que se ha de buscar. <br>
3. El procesador envía una señal al bus de direcciones de memoria con la dirección previamente almacenada en el RDM-MAR <br>
4. La instrucción o información que contiene esa dirección de memoria se envía por el bus de datos hacia el registro de datos de memoria RDM - MDR <br>
5. La instrucción o datos contenidos en el RDM- MDR se copian en el registro de instrucción. (RI o CIR) <br>
6. Los datos o instruciones almacenados en el RI o CIR se descodifican y luego se ejecuta para ser finalmente almacenados en el acumulador de la ALU que es un registro de almacenamiento temporal.
 </blockquote>
 </details>


### 003 ¿Qué es un Nibble?**
A. 4 bits  
B. 2 bits   
C. 16 bits  
D. 8 bits  

<details> 
 <summary>Respuesta</summary> 

A. Un nibble son 4 bits o medio octeto.
 </details>

### 004. Existen tres tipos de buses principales

A. De datos, de dirección y de ejecución
B. De datos, de dirección y de registro
C. De datos, de dirección y de control
D. De Datos, de dirección y de memoria
<details> 
 <summary>Respuesta</summary> 

D.
</details>

### 005. El registro contador de Programa

A. contiene la dirección de la instrucción siguiente que hay que leer de la CPU
B. contiene la dirección de la instrucción siguiente que hay que ejecutar
C. contiene la dirección del siguiente registro que hay que leer de la  memoria
D. contiene la dirección de la instrucción siguiente que hay que leer de la memoria
<details> 
 <summary>Respuesta</summary> 
D.
</details>

**El registro de instrucción**                                                                                                                      A. Contiene las instrucciones que se han ejecutado                                                                              B. Contiene la instrucción que hay en la memoria                                                                                      C. Contiene la instrucción que hay que ejecutar                                                                                   D. Contiene la instrucción que hay que registrar

**Según los criterios de localización y la explicitación de los operandos, podemos identificar las siguientes arquitecturas del juego de instrucciones**
A. Arquitecturas basas en pilas, en acumulador y en registros de propósito general                                                             B. Arquitecturas basas en pilas, en acumulador y en registros de datos                                               C. Arquitecturas basas en pilas, en acumulador y en registros                                                            D. Arquitecturas basas en pilas, en acumulador y en registros de información

- Solución

    A. [http://www.cs.kent.edu/~durand/CS0/Notes/Chapter05/isa.html](http://www.cs.kent.edu/~durand/CS0/Notes/Chapter05/isa.html)

**Los dos registros principales relacionados con el acceso a las instrucciones son**                                A. Contador del programa y registro de instrucción                                                                            B. Contador del programa y registro de programa                                                                                  C. Contador del programa y registro de memoria                                                                                      D. Contador de instrucción y registro de instrucción

- Solución

    A. [https://en.wikipedia.org/wiki/Instruction_cycle](https://en.wikipedia.org/wiki/Instruction_cycle)

Estándar del IEEE para representar números reales en coma flotante
A. IEEE 754
B. IEEE 735
C. IEEE 745
D. IEEE 753

- Solución

    A.  [https://en.wikipedia.org/wiki/IEEE_754](https://en.wikipedia.org/wiki/IEEE_754)

El código ASCII fue desarrollado por:
A. UTC
B. ANSI
C. W3E
D. IBM

- Solución

    B. [https://en.wikipedia.org/wiki/ASCII](https://en.wikipedia.org/wiki/ASCII)

**Hay dos registros necesarios para cualquier operación de lectura o escritura de memoria**                            A. MAR y MBB                                                                                                                                       B. MAR y MMR
C. MMR y MBR                                                                                                                                      D. MMR y MBR

- Solución
    - **Memory address register (MAR)**: registro de direcciones de memoria, donde ponemos la dirección de memoria a la que queremos acceder.
    - **Memory buffer register (MBR)**: registro de datos de memoria; registro donde la memoria deposita el dato leído o el dato que queremos escribir.

El código EBCDIC utiliza...                                                                                                                      A. utiliza n = 7 bits para representar cada carácter de un total de m = 255 caracteres                              B. utiliza n = 2 bits para representar cada carácter de un total de m = 64 caracteres                          C. utiliza n = 16 bits para representar cada carácter de un total de m = 512 caracteres                       D. utiliza n = 8 bits para representar cada carácter de un total de m = 256 caracteres

- Solución

    D.  [https://en.wikipedia.org/wiki/EBCDIC](https://en.wikipedia.org/wiki/EBCDIC)

El Código ASCII es un código…
A. De 8 bits con 255 caracteres
B. De 8 bits con 256 caracteres
C. De 7 bits con 128 caracteres
D. De 4 bits con 512 caracteres

- Solución

    C.  [https://en.wikipedia.org/wiki/ASCII](https://en.wikipedia.org/wiki/ASCII)

El formato de codificación UTF-8 utiliza símbolos de longitud variable                                              A. de 1 a 32 bytes por carácter Unicode                                                                                               B. de 1 a 8 bytes por carácter Unicode                                                                                                 C. de 1 a 16 bytes por carácter Unicode                                                                                                D. de 1 a 4 bytes por carácter Unicode

- Solución

    D.  [https://en.wikipedia.org/wiki/UTF-8#Encoding](https://en.wikipedia.org/wiki/UTF-8#Encoding)

Se denomina ASCII extendido a cualquier juego de caracteres de
A. 16 bits
B. 32 bits
C. 8 bits
D. 64 bits

- Solución

    C. [https://en.wikipedia.org/wiki/Extended_ASCII](https://en.wikipedia.org/wiki/Extended_ASCII)

**El Bit de desbordamiento se activa**                                                                                                       A. si una operación ha producido un resultado que se puede representar en el formato que estamos utilizando                                                                                                                                  B. si la última operación ha producido un resultado que no se puede representar en el formato que estamos utilizando                                                                                                                                  C. si una operación ha producido un resultado que no se puede representar en el formato que estamos utilizando                                                                                                                                 D. si la última operación ha producido un resultado que se puede representar en el formato que estamos utilizando

- Solución

    Da B pero es C? . [https://es.wikipedia.org/wiki/Desbordamiento_aritmético](https://es.wikipedia.org/wiki/Desbordamiento_aritm%C3%A9tico)

¿Cuántos caracteres imprimibles y no imprimibles tiene el código ASCII?
A. 33 caracteres no imprimibles y 95 imprimibles
B. 34 caracteres no imprimibles y 94 imprimibles
C. 30 caracteres no imprimibles y 95 imprimibles
D. 35 caracteres no imprimibles y 93 imprimibles

- Solución

    A. [https://en.wikipedia.org/wiki/ASCII](https://en.wikipedia.org/wiki/ASCII)

Cada una de las operaciones que hacemos durante la ejecución de una instrucción se denomina:
A. Microinstrucción
B. Miniregistro
C. Microregistro
D. Microoperación

- Solución

    D. In computer central processing units, micro-operations are detailed low-level instructions used in some designs to implement complex machine instructions.

¿Cuál de los siguientes es el almacenamiento de mayor memoria?
A. 23 TB
B. 256 PB
C. 25 EB
D. 124 GB

- Solución

    C. 

    - Kilo
    - Mega
    - Giga
    - Tera
    - Peta
    - Exa
    - Zetta
    - Yotta

Las memorias DDR permiten la lectura de datos ...
A. Tanto en la fase alta como baja del ciclo de reloj, con lo que se obtiene la mitad de ancho de banda que con la SDRAM estándar
B. Tanto en la fase alta como baja del ciclo de reloj, con lo que se obtiene el doble de ancho de banda que con la DRAM
C. Tanto en la fase alta como baja del ciclo de reloj, con lo que se obtiene el doble de ancho de banda que con la SDRAM estándar
D. Ninguna de las anteriores es correcta

- Solución

    A. **Double Data Rate**: transfers data on both the rising and falling edges of the clock signal.               

    1. SDR SDRAM: Las primeras DRAM´s, tasa de datos simple
    2. DDR SDRAM: Tasa de datos doble
    3. DDR2 SDRAM
    4. DDR3 SDRAM
    5. DDR4 SDRAM

---

La ALU es la unidad encargada de realizar las operaciones elementales de tipo ...

A. Aritmético y gráfico

B. Gráfico y lógico

C. Aritmético y lógico

D. Ninguna

- Solución

    C.  La ALU puede realizar las siguientes operaciones

    - aritméticas de números enteros
    - lógica de bits (AND, NOT, OR, XOR, NOR, XNOR, NAND)
    - desplazamiento de bits

---

Indique en cuál de los siguientes grupos de siglas hay al menos una que no pertenece a la misma
familia:
a) ISA, PCI, EISA, AGP
b) Thunderbolt, HDMI, FireWire, FiberChannel
c) SATA, IDE, SCSI, SAS
d) CRT, TFT, LCD, AMOLED

- ver solución

    B

---

**La velocidad teórica máxima del USB 3.0 es:**
a) 5 Gbps pero solo con el conector reversible tipo C.
b) Similar a la del USB 2.0.
c) Más de 10 veces superior a la del USB 2.0.
d) 480 Mbps.

- ver solución

    [Untitled](https://www.notion.so/2f48dcf86d744e0b8079808d612e97fe)

---

**En relación con las tecnologías de gestión de la impresión, diga qué expresión no es correcta:**
a) Con Pull Printing se alcanza mayor seguridad, gracias a que solo puede acceder a un documento
el usuario que previamente estuviese autorizado a hacerlo.
b) Con Pull Printing se evitan las impresiones no recopiladas por los usuarios, ayudando, por
tanto, a reducir los costes de tóner y papel.
c) Push Printing presenta más dificultad de ser utilizado con impresoras antiguas.
d) Push Printing facilita la reducción de los costes extras de licencias y hardware.

- ver solución

    Pull printing is a printing feature where a user's print job is held on a server (server-based pull printing) or on a user's workstation (serverless pull printing) and released by the user at any printing device (pulled to the printer) which supports this feature. A number of software products exist that support pull printing. The user needs to first authenticate themselves at the printer, either using embedded software (e.g. i.c.w. a pincode), or an external device (e.g. i.c.w. a smartcard). Once they have been authenticated, the user may select from the list of print jobs from the server, web portal or directly from the client PC[citation needed] which ones they wish to release at the current device. Some systems also allow delegation where the user may access print jobs submitted by other users or systems.

    ## Advantages

    - Flexibility: The user can print first and choose the printer afterwards (while standing next to it).
    - IT management: instead of having to manage hundreds of print queues on print servers and multiple printers on the user desktops there is only one print queue on each user PC.
    - Costs and environment: Reduces uncollected paper.
    - Green IT: the server-less flavour of pull printing allows the removal of all print servers throughout the company. A widget can show users the environmental impact of printing by showing them the number of trees and amount of CO2 and energy used to deliver a print job.
    - Security: No more unattended documents on printers output trays, the user must authenticate, increasing privacy policy compliance.
    - Accounting: Although this is not really a Pull Printing feature, centralized printing solutions often come with these additional features (e.g. [reporting](https://en.wikipedia.org/wiki/Report), charging, [monitoring](https://en.wikipedia.org/w/index.php?title=System_Monitoring&action=edit&redlink=1)).

    ### Disadvantages

    - Speed: The user has to wait for the job to be copied and processed from the moment the [print job](https://en.wikipedia.org/wiki/Print_job) is pulled.
    - Costs: Extra [licensing](https://en.wikipedia.org/wiki/License) and hardware.
    - Specialised software may be required on the [server](https://en.wikipedia.org/wiki/Server_(computing)) and also possibly on the printer.
    - Compatibility: The print driver used when the user initially prints must be compatible with all the devices that the user might release their print job to. Some software solutions can perform conversions or a common print driver to negate this requirement.
    - Printer Hardware-Specific: Often solutions are only compatible with certain vendor's own hardware; there are however exceptions.

---

**El modelo de reproducción del color CMYK:**
a) Es el modelo utilizado por la mayoría de los escáneres.
b) Es un modelo de tipo sustractivo.
c) Se basa en la combinación de tres colores: rojo, verde y azul.
d) Es el modelo utilizado por la mayoría de los monitores.

- ver solución

    El modelo CMYK (siglas de Cyan, Magenta, Yellow y Key) es un modelo de color **sustractivo** que se utiliza en la impresión en colores

---

**En el estándar USB 2.0, ¿Qué tipo de transmisión de datos se utiliza entre un
dispositivo USB y el puerto USB del PC?**
A) Paralela.
B) Serie.
C) Primero serie para sincronizar y después paralela para enviar datos.
D) Primero paralela para sincronizar y después serie para enviar datos.

- ver solución

    B. Universal **Serial** Bus

---

**¿Cuál de los siguientes no es uno de los 6 principios básicos del Esquema Nacional de Seguridad?**
a) Seguridad integral.
b) Realizar copias de seguridad.
e) Prevención, reacción y recuperación.
d) Gestión de riesgos.

- ver solució

    a)      Seguridad integral.
    b)      Gestión de riesgos.
    c)      Prevención, reacción y recuperación.
    d)      Líneas de defensa.
    e)      Reevaluación periódica.
    f)       Función diferenciada.

---

**En relación con el Esquema Nacional de Seguridad, ¿Cuál de las siguientes afirmaciones no es
correcta?**
a) Está constituido por los principios básicos y requisitos mínimos requeridos para una protección
adecuada de la información.
b) El responsable de la información determinará los requisitos de los servicios prestados.
c) El análisis y gestión de riesgos será parte esencial del proceso de seguridad.
d) Las líneas de defensa han de estar constituidas por medidas de naturaleza organizativa, física y
lógica.

- ver solución

    El responsable de la información determinará los requisitos de la información tratada;

---

**De acuerdo con el artículo 4 del Real Decreto que regula el Esquema Nacional de Interoperabilidad, ¿Cuál de los siguientes conceptos no es un principio específico de la interoperabilidad?**
a) Carácter multidimensional de la interoperabilidad.
b) Gestión de riesgos de la interoperabilidad.
c) Enfoque de soluciones multilaterales.
d) La interoperabilidad como cualidad integral.

- ver solución

    a) La interoperabilidad como cualidad integral.
    b) Carácter multidimensional de la interoperabilidad.
    c) Enfoque de soluciones multilaterales.

---

**¿Qué regula el Real Decreto 4/2010, de 8 de enero?**
a) El Esquema Nacional de Interoperabilidad.
b) El Esquema Nacional de Seguridad.
e) El Esquema Nacional de Interoperabilidad y el Esquema Nacional de Seguridad.
d) La ley Orgánica de Protección de Datos Personales y garantía de los derechos digitales.

- ver solución

    Real Decreto 4/2010, de 8 de enero, por el que se regula el Esquema Nacional
    de Interoperabilidad en el ámbito de la Administración Electrónica.

---

**¿Es posible tener instalados macOS High Sierra y Windows 10 en un mismo equipo?**
a) No, son dos sistemas incompatibles entre sí.
b) Si, además macOS te ofrece el asistente Boot Camp para guiarte en la instalación de Windows
sobre Mac.
c) Si, pero necesitas tener instalado en el mismo equipo alguna versión de Linux para permitir el
arranque dual.
d) No, solamente es posible instalar Linux y macOS en el mismo equipo.

- ver solución

    Boot Camp es una utilidad que viene instalada en tu Mac y te permite cambiar entre macOS y Windows.

---

Identifique cuál tiene uno o más términos no ligado/s a conceptos de las bases de datos
relacionales:
a) Columna, atributo, instancia, tupla.
b) Dominio, grado, fila, registro.
c) Cardinalidad, fila, relación, tabla.
d) Todas las respuestas anteriores son incorrectas.

- ver solución

---

Cuál de las siguientes tecnologías no está relacionada con la identificación y autentificación:
a) Certificado X.509.
b) Single Sign On.
e) Kerberos.
d) NetBios.

- ver solución

    NetBIOS, "Network Basic Input/Output System", es, (en sentido estricto) una especificación de interfaz para acceso a servicios de red, es decir, **una capa de software** desarrollado para enlazar un sistema operativo de red con hardware específico.

---
