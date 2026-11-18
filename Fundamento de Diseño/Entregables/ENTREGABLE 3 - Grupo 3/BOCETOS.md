### SOLUCIÓN 1 (ELEGIDA)

<img width="1390" height="937" alt="WhatsApp Image 2026-11-17 at 10 30 24 PM" src="https://github.com/user-attachments/assets/c9db353a-4628-4bc0-8923-f3cc2718f20c" />
<br><br><br>
<img width="1060" height="726" alt="WhatsApp Image 2026-11-17 at 1 21 39 PM" src="https://github.com/user-attachments/assets/798fbdbd-0426-45b5-8bea-94df6b31facf" />
<br><br><br>
<img width="1600" height="1153" alt="WhatsApp Image 2026-11-17 at 12 55 38 PM" src="https://github.com/user-attachments/assets/dd84581c-7431-4340-8457-1c715568b863" />
<br><br><br>
<img width="1228" height="794" alt="WhatsApp Image 2026-11-17 at 12 58 50 PM" src="https://github.com/user-attachments/assets/9b968515-2556-4aa6-962d-913c80f27e3d" />

<br><br>
### Descripción del funcionamiento 

El sistema opera como una estructura flotante operada manualmente, diseñada para la recolección de residuos sólidos superficiales en cuerpos de agua. Su desplazamiento y dirección son controlados directamente por un operario mediante un sistema de propulsión compuesto por motores y hélices. A medida que avanza por la superficie, el flujo de agua dirige los residuos flotantes a través de una abertura frontal hacia una red colectora integrada, donde quedan retenidos para su posterior extracción y disposición.

| PIEZA | NOMBRE | MATERIAL |
|:---:|---|---|
| 1 | Baterías LiPo de 11.1V | Polímero de litio y aluminio |
| 2 | Diodo Schottky MBR2045CT | Silicio, plástico epoxi y cobre estañado |
| 3 | Módulo convertidor DC-DC Buck LM2596 | Fibra de vidrio (PCB), silicio y cobre |
| 4 | Batería 12V 7AH de plomo ácido | Polímero de litio, fibra de vidrio (PCB), polipropileno y plomo |
| 5 | Tubos de PVC y plancha de PVC | Policloruro de vinilo (PVC) |
| 6 | Malla plástica flexible moldeable | Polietileno (PE) o polipropileno (PP) |
| 7 | 2 motores/Propulsores 12V + Hélices | Acero, cobre y plástico ABS |
| 8 | Caja estanca de plástico | Plástico ABS o policarbonato (con sello de silicona) |
| 9 | ESP32-CAM | Fibra de vidrio (PCB), silicio, vidrio óptico y aluminio |
| 10 | Microcontrolador ESP32 con Wi-Fi integrado | Fibra de vidrio (PCB), silicio y aluminio |
| 11 | Aplicación móvil personalizada para medir las 3 variables | No aplica (Software) |
| 12 | Sensor infrarrojo para detección de obstáculos frontal | Fibra de vidrio (PCB), silicio y plástico ABS |
| 13 | Abrazaderas | Plástico PVC |
| 14 | Resistencias | Cerámica, película de carbón (o metal) y cobre |
| 15 | Borneras | Plástico poliamida (nailon) y latón/acero |
| 16 | Drivers BTS7960 | Fibra de vidrio (PCB), silicio y aluminio (disipador) |
| 17 | INA226 2 mΩ | Fibra de vidrio (PCB), silicio y aleación de cobre-manganeso (manganina) |
| 18 | Portafusible | Plástico ABS/baquelita y latón |
| 19 | Interruptor basculante 12V (o Rocker Switch 12V / Switch RS-201-4C) | Plástico (o Nylon) |

<br><br><br>

### SOLUCIÓN 2
<br>
<img width="966" height="782" alt="WhatsApp Image 2026-11-17 at 1 14 21 PM" src="https://github.com/user-attachments/assets/933669f6-981e-47df-a9f9-320621c7ee9d" />
<br><br>
<img width="960" height="648" alt="WhatsApp Image 2026-11-17 at 1 19 26 PM" src="https://github.com/user-attachments/assets/ff1ea76b-fcb7-48cd-b532-1a7256e8401d" />

<br><br>
### Descripción del funcionamiento

AquaGuard funciona mediante una estructura flotante formada por tuberías de PVC selladas en forma de “V”, las cuales proporcionan flotabilidad y ayudan a dirigir los residuos hacia la zona de recolección. Los residuos sólidos superficiales son retenidos por una rejilla colectora pasiva de alta densidad y almacenados en un contenedor fijo sellado. Un sensor ultrasónico de distancia detecta el nivel de llenado y envía la información al microcontrolador ESP32, que procesa la señal y muestra el estado del sistema a través de un panel local con LEDs. La alimentación eléctrica se realiza mediante un panel solar monocristalino compacto, un regulador de carga PWM y una batería convencional de plomo-ácido. Asimismo, la información puede transmitirse mediante comunicación Wi-Fi local.


| PIEZA | NOMBRE | MATERIAL |
|:---:|---|---|
| 1 | Baterías LiPo de 11.1 V | Polímero de litio y aluminio |
| 2 | Fusible de vidrio básico | Vidrio y latón |
| 3 | Regulador de carga solar PWM estándar | Plástico ABS y fibra de vidrio (PCB) |
| 4 | Batería de plomo-ácido convencional | Polipropileno y plomo |
| 5 | Tuberías de PVC selladas en "V" con PET | Plástico PVC y PET |
| 6 | Interruptor | Plástico ABS y cobre |
| 7 | Rejilla colectora pasiva de alta densidad | Polietileno de alta densidad (HDPE) |
| 8 | Gabinete metálico sin sellado | Acero o aluminio |
| 9 | Sensor ultrasónico de distancia | Fibra de vidrio (PCB) y aluminio |
| 10 | Microcontrolador ESP32 con Wi-Fi integrado | Silicio, fibra de vidrio (PCB) y aluminio |
| 11 | Panel local con LEDs indicadores | Acrílico y fibra de vidrio (PCB) |
| 12 | Módulo Wi-Fi | Fibra de vidrio (PCB) y aluminio |

<br><br><br>
### SOLUCIÓN 3
<br><br>
<img width="782" height="757" alt="WhatsApp Image 2026-11-17 at 1 16 53 PM" src="https://github.com/user-attachments/assets/b01a9787-ba37-427f-b94e-99e9dd463002" />
<br><br>
<img width="636" height="785" alt="WhatsApp Image 2026-11-17 at 1 16 58 PM" src="https://github.com/user-attachments/assets/da6b5138-7089-458b-af06-e61c65f72f22" />
<br><br>
### Descripción del funcionamiento 

El sistema opera de forma semiautónoma en lagunas mediante un generador híbrido solar-eólico que alimenta una batería con bus DC y un conversor Buck. Los pontones de polietileno mantienen la flotabilidad. El agua superficial ingresa a un tambor filtrante rotativo que retiene los sólidos. Un sensor láser óptico detecta el nivel de llenado y acciona el sistema de compactación mecánica. Por su parte, la Raspberry Pi, protegida por un relé de estado sólido y una carcasa de aluminio, procesa los datos y los transmite vía celular GSM/4G hacia una plataforma web IoT en la nube.

| PIEZA | NOMBRE | MATERIAL |
|:---:|---|---|
| 1 | Sistema híbrido solar-eólico básico | Silicio, vidrio, aluminio y plástico ABS |
| 2 | Módulo de protección con relé de estado sólido | Fibra de vidrio (PCB), silicio y plástico ABS |
| 3 | Módulo convertidor DC-DC Buck LM2596 | Fibra de vidrio (PCB), silicio y cobre |
| 4 | Batería 12V-20Ah | Polipropileno y plomo (o litio) |
| 5 | Pontones de polietileno de alta resistencia | Polietileno de alta densidad (HDPE) |
| 6 | Tambor filtrante rotativo manual | Acero inoxidable |
| 7 | Sistema de compactación mecánica | Acero inoxidable y aluminio |
| 8 | Carcasa hermética de aluminio con doble sello | Aluminio y caucho/silicona (sellos) |
| 9 | Sensor láser óptico | Fibra de vidrio (PCB), vidrio óptico y aluminio |
| 10 | Raspberry Pi de placa completa | Fibra de vidrio (PCB), silicio y acero |
| 11 | Plataforma web IoT / Dashboard en la nube | No aplica (Software) |
| 12 | Sensor infrarrojo de detección de obstáculos frontal | Fibra de vidrio (PCB), silicio y plástico ABS |


