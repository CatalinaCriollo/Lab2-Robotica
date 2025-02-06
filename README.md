# Laboratorio N°2 - Robotica- Operación, Análisis y Comparación del Manipulador Motoman MH6

Integrantes: Catalina Criollo Castelblanco - Diego Fernando Malagón Saenz

# Resumen

En este informe de laboratorio se comparan dos manipuladores ampliamente utilizados en la industria: el Motoman MH6 de Yaskawa y el ABB IRB 140 de ABB. La comparación se realiza en función de especificaciones técnicas, precisión, capacidad de carga, flexibilidad, control y aplicaciones, con el fin de determinar cuál es más adecuado para diferentes escenarios industriales*.


# Comparación

* Motoman MH6:
  
![](Motoman_MH6_cutout.png)

* ABB IRB 140:
  
![](ABB_IRB_140_0001.png)

## Especificaciones Técnicas

| Característica | Motoman MH6 | ABB IRB 140 |
| --- | --- | --- |
| Fabricante | Yaskawa Motoman | ABB|
| Grados de libertad (DOF) | 6 | 6 |
| Capacidad de carga | 6 kg | 6 kg |
| Alcance máximo | 1422 mm  | 810 mm |
| Repetibilidad | ±0.08 mm | ±0.01 mm |
| Peso | 130 kg | 98 kg |
| Montaje | Suelo, pared, techo | Suelo, pared, inclinado, techo| 
|Velocidad máxima por eje | 200-250°/s | 250-300°/s |
| Controlador | DX100/ DX200 | IRC5 |
| Software de programación | MotoPlus, INFORM II | RAPID|
| Aplicaciones principales | Soldadura, ensamblaje, manipulación de materiales | Ensamblaje, manipulación de materiales, carga/descarga, soldadura |

## Controlador 
### Motoman MH6:
  
  ![](Motoman_DX100_Controller.jpg)
  
El DX100 es un controlador cuenta con una interfaz intuitiva que simplifica la programación y el manejo del robot, reduciendo los tiempos de configuración y mejorando la productividad en entornos de manufactura complejos.

Una de sus principales ventajas es su capacidad multi-robot, ya que puede controlar hasta 8 robots simultáneamente (72 ejes en total). Esto lo convierte en una opción ideal para aplicaciones que requieren la sincronización de múltiples robots en celdas de producción de alta densidad. Su arquitectura modular y centralizada permite la gestión eficiente de manipuladores, optimizando los tiempos de respuesta mediante procesamiento en paralelo. Además, su diseño compacto reduce el espacio ocupado en la celda de trabajo, facilitando la integración en distintas configuraciones industriales.

La programación del DX100 se basa en el lenguaje INFORM, desarrollado por Motoman. Aunque es un sistema potente y versátil, presenta una curva de aprendizaje más pronunciada en comparación con otros entornos de programación más intuitivos. El controlador permite la programación en línea a través de un teach pendant con pantalla a color, así como programación offline mediante el software MotoSim, lo que ofrece flexibilidad para simular y optimizar tareas antes de su implementación en la producción.

En términos de conectividad, el DX100 está diseñado principalmente para la coordinación de múltiples robots dentro de una celda de trabajo, pero también ofrece compatibilidad con diversos protocolos de comunicación industrial. Soporta Ethernet/IP, DeviceNet, Profibus y CC-Link, permitiendo la integración con PLCs y sistemas SCADA. Además, cuenta con soporte para visión artificial y sensores externos, lo que amplía su aplicabilidad en entornos de manufactura avanzada.
* Teach Pendant
  
  ![](teachmoto.png)
      
### ABB IRB 140:
  
 ![](30265-2663583.jpg) 
 
El IRC5 es un controlador modular y escalable de quinta generación desarrollado por ABB, diseñado para ofrecer un control avanzado y preciso del movimiento de los robots industriales. Su arquitectura flexible permite la personalización mediante módulos adaptables a distintas aplicaciones, garantizando un rendimiento óptimo en términos de velocidad, precisión y sincronización con dispositivos externos.

Uno de sus principales diferenciadores es su tecnología de control de movimiento, basada en TrueMove™ y QuickMove™. TrueMove™ asegura trayectorias suaves y exactas independientemente de la velocidad, mientras que QuickMove™ optimiza la aceleración y desaceleración, reduciendo los tiempos de ciclo al mínimo posible. Gracias a su modelado dinámico avanzado, el IRC5 entrega un comportamiento predecible y de alto rendimiento sin necesidad de ajustes adicionales por parte del programador.

El controlador opera con RobotWare, un sistema operativo que facilita actualizaciones y personalización, además de permitir la integración con dispositivos externos y periféricos. Su lenguaje de programación, RAPID, combina simplicidad, flexibilidad y potencia, ofreciendo un entorno sin restricciones con múltiples funciones avanzadas. Este lenguaje es más intuitivo y accesible en comparación con otros sistemas, brindando un amplio soporte para diversas aplicaciones industriales.

La programación del IRC5 se potencia con RobotStudio, un entorno de simulación que permite desarrollar, probar y optimizar programas tanto online como offline, reduciendo tiempos de configuración y mejorando la productividad. Su teach pendant cuenta con una interfaz gráfica avanzada y pantalla táctil, lo que facilita la interacción con el sistema y la programación en tiempo real.

En términos de conectividad, el IRC5 es compatible con una amplia gama de protocolos industriales, como OPC UA, PROFINET, EtherNet/IP y Modbus, lo que le permite integrarse fácilmente en entornos de automatización interconectados. Su compatibilidad con visión artificial, sensores inteligentes y sistemas de seguridad lo hace ideal para aplicaciones de manufactura avanzada. Además, su capacidad de comunicación con la nube e IoT le permite adaptarse a los requerimientos de la Industria 4.0.


* Teach Pendant
  ![](teachabb.png)

    
## Aplicaciones industruales

### Motoman MH6:
* El Motoman MH6 es un robot industrial versátil diseñado para una amplia variedad de aplicaciones en sectores como manufactura, ensamblaje, logística y automotriz. Su diseño delgado, alta velocidad y capacidad de montaje en múltiples posiciones lo hacen ideal para entornos industriales donde se requiere precisión, flexibilidad y eficiencia. Entre sus principales aplicaciones se encuentra:
  
  - Manufactura aditiva: Puede integrarse en procesos de impresión 3D industrial para la deposición de material en múltiples capas.
  - Dispensado: Precisión en la aplicación de adhesivos, selladores o recubrimientos en líneas de producción automatizadas.
  - TCP remoto: Ajuste automático de la posición del herramental en tareas de alta precisión.
  - Soldadura: Especialmente en soldadura por arco, permitiendo un control preciso de la trayectoria y optimización del tiempo de ciclo.
  - Manipulación de materiales: Carga y descarga de máquinas (CNC, prensas); empaque y paletizado en la clasificación de productos en líneas de producción.
  - Ensamblaje: Integración en celdas de manufactura para el ensamblaje de productos complejos.
  - Pintura y recubrimientos: Aplicaciones de pintura industrial con movimiento preciso y repetitivo. Recubrimientos protectores y selladores en diversas industrias.
  - Corte por plasma y láser: Permitiendo formas complejas con alta precisión.
  
  ### ABB IRB 140:
* El ABB IRB 140 es un robot industrial compacto diseñado para aplicaciones que requieren alta precisión, velocidad y flexibilidad. Gracias a su capacidad de montaje en múltiples posiciones y su alta repetibilidad (±0.01 mm), es ideal para tareas exigentes que demandan exactitud y eficiencia. Entre sus principales aplicaciones se encuentra:
  -  Ensamblaje y la manipulación de piezas pequeñas:  Se destaca en la fabricación de dispositivos electrónicos, como teléfonos móviles, radios y circuitos integrados. Su capacidad para operar en salas limpias lo convierte en una opción ideal para la industria de semiconductores, donde la manipulación de microcomponentes requiere entornos controlados. Además, su rapidez y precisión lo hacen adecuado para el empaquetado y la clasificación de productos pequeños en líneas de producción automatizadas.
  -  Soldadura y acabado superficial: Desempeña un papel clave en la soldadura por arco, integrándose en celdas compactas como FlexArc® Compact, diseñadas para optimizar la producción en espacios reducidos. También es utilizado en tareas de pulido y desbarbado de aluminio, así como en el mantenimiento de prensas y otras máquinas industriales, garantizando superficies de alta calidad y reduciendo tiempos de procesamiento.
  -  Industria de fundición y moldeo: El IRB 140 está disponible con protección IP67, lo que le permite operar en entornos hostiles. Su diseño lo hace ideal para la pulverización de matriz en fundiciones y la manipulación en máquinas de fundición a presión, asegurando una aplicación uniforme y eficiente. En el sector del moldeo por inyección, es utilizado para cargar y descargar insertos y piezas moldeadas, agilizando el ciclo de trabajo y mejorando la productividad.
  -  Carga, descarga y manipulación de materiales: Se emplea en líneas de producción automatizadas, optimizando la transferencia de piezas y el mantenimiento de máquinas. Su capacidad para manipular materiales frágiles y de alta precisión le permite mejorar la calidad del proceso productivo, minimizando el margen de error y reduciendo el desgaste de los componentes.   

# Practica

Se realizo un código en python
