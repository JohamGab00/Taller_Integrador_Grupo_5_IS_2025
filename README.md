# 📡 Tracker LoRa Tracker. GR-5 📡
Proyecto de desarrollo de un tracker LoRa APRS basado en ESP32, diseñado para operar en la frecuencia de 433 MHz dentro del territorio costarricense. Compatible con la red APRS y servicios como [aprs.fi](https://aprs.fi/).
## Integrantes 👨‍💻👨‍💻👨‍💻
- Natalia Hernández López
- Josué Marín Vargas
- Joham Mora Castrillo

# Descripciones de LoRa, APRS y Legislación costarricense📝
# LoRa
LoRa, que significa Long Range, es una tecnología de comunicación inalámbrica patentada que se destaca por su combinación de bajo consumo de energía y largo alcance efectivo. Desarrollada en Francia en 2012 por Cycleo y posteriormente adquirida por Semtech
## Aplicaciones  
LoRa se utiliza en diversas aplicaciones de Internet de las cosas (IoT), como:
  - Monitoreo y control de cultivos en agricultura inteligente.
  - Medidores inteligentes para agua, gas y electricidad.
  - Rastreo de activos y logística.
  - Redes de sensores ambientales.
  - Seguridad y monitoreo industrial.
## Disponibilidad en el mercado 💸
  - TTGO LoRa32.
  - RA-02 LoRa module con ESP32.
## Frecuencias de operación 📡
  |Frecuencia (MHz)|Ubicación|
  |----------------|---------|
  |433|Europa, China|
  |868|Europa|
  |915|América del norte y Australia|
# ARPS
El Automatic Packet Reporting System (APRS) es un sistema de comunicaciones basado en radiofrecuencia que permite la transmisión de datos en tiempo real. Se utiliza principalmente en la comunidad de radioaficionados para compartir información como ubicación, mensajes cortos, telemetría y datos meteorológicos.
## Aplicaciones 
El sistema tiene diversas aplicaciones, por ejemplo
  - Rastreo de vehículos y personas en tiempo real.
  - Monitoreo y reporte de condiciones meteorológicas.
  - Envío de mensajes cortos sin necesidad de Internet.
  - Integración con redes digitales mediantes APRS-IS.
## Protocolos de comunicación 
APRS  utiliza principalmente el protocolo AX.25, que es un estándar de comunicaciones para la transmisión de datos en paquetes en la radioaficiónn. AX.25 es un protocolo de enlace de datos basado en la conmutación de paquetes, utilizado para la transmisión de información a través de redes de radio. Este protocolo fue diseñado para permitir que las estaciones de radioaficionados intercambien datos de manera eficiente y confiable, incluso en condiciones de baja calidad de señal. AX.25 define cómo los datos deben ser encapsulados, dirigidos y transmitidos en las redes de radio. Además, APRS puede utilizar TCP/IP (Transmission Control Protocol/Internet Protocol), un conjunto de protocolos de comunicación utilizados para la interconexión de dispositivos a través de redes, como Internet. TCP/IP permite la transmisión de datos de manera confiable y garantiza que los paquetes de información lleguen a su destino, facilitando la integración de APRS con sistemas basados en Internet.
## Frecuencias de operación 📡
  |Frecuencia (MHz)|Ubicación|
  |----------------|---------|
  |144.4 en VHF|América del norte|
  |145.8|Comunicación Satelital|
## Componentes necesarios para sistema APRS
  - Transceptor de radio VHF/UHF/HF.
  - TNC o software para modulación y demodulación de paquetes.
  - GPS para datos de ubicación.
  - Microcontrolador para procesar y enviar datos.
  - Servidores APRS-IS.

# Legislación Costarricense 🔵⚪🔴⚪🔵
## Cuadro Nacional de Atribución del PNAF (https://sutel.go.cr/sites/default/files/normativas/Plan%20Nacional%20de%20Atribuicio%CC%81n%20de%20Frecuencias%20%28mayo%202023%29_0.pdf )
El Plan Nacional de Atribución de Frecuencias (PNAF), establecido mediante el Decreto Nº 44010-MICITT y publicado en el Alcance N°99 de la Gaceta N°95, con fecha 30 de mayo de 2023, define las bandas de frecuencia destinadas a diversos servicios de telecomunicaciones, incluyendo aquellas utilizadas por tecnologías como LoRa y APRS.
## Permisos requeridos para operar un sistema LoRa/APRS
En Costa Rica, la operación de sistemas de radiofrecuencia debe cumplir con las normativas establecidas por el MICITT. Para el caso de los sistemas APRS, es obligatorio que los operadores cuenten con una licencia de radioaficionado válida. En cuanto al uso de tecnología LoRa, su legalidad depende de la banda de frecuencia empleada, la cual puede estar clasificada como de uso libre o requerir una autorización específica.
## Clases de Emisión
Las clases de emisión especifican el tipo de modulación y la naturaleza del contenido de la señal transmitida. En el caso de APRS y LoRa, se emplean las siguientes clases de emisión:
  - APRS: F2D (datos en modulación de frecuencias)
  - LoRa: G1D (datos en modulación de espectro ensanchado)
## Bandas de Frecuencias en las que operan LoRa/APRS
Las bandas de frecuencia permitidas en Costa Rica para estos sistemas son:
  - APRS: [144.39, 148.82] MHz
  - LoRa: [915, 921] MHz


