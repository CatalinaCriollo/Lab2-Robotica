# Laboratorio N°2 - Robotica-O peración, Análisis y Comparación del Manipulador Motoman MH6

Integrantes: Catalina Criollo Castelblanco - Diego Fernando Malagón Saenz

# Resumen

En este informe de laboratorio se comparan dos manipuladores ampliamente utilizados en la industria: el Motoman MH6 de Yaskawa y el ABB IRB 140 de ABB. La comparación se realiza en función de especificaciones técnicas, precisión, capacidad de carga, flexibilidad, control y aplicaciones, con el fin de determinar cuál es más adecuado para diferentes escenarios industriales*.


# Desarrollo

## Apariencia*

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
* Motoman MH6:
    - El controlador DX100 del robot proporciona funciones avanzadas de programación y movimiento, lo que permite una integración perfecta en entornos de fabricación complejos. Su interfaz fácil de usar simplifica la programación y el funcionamiento, minimizando el tiempo de configuración y mejorando la productividad.
      
* ABB IRB 140:
    Equipado con el último controlador IRC5 .
    IRC5 es el controlador de robot de quinta generación de ABB. Su tecnología de control de movimiento, TrueMove y QuickMove, es clave para el rendimiento del robot en términos de precisión, velocidad, tiempo de ciclo, programación y sincronización con dispositivos externos.
    Basado en un modelado dinámico avanzado, el IRC5 optimiza el rendimiento del robot para el tiempo de ciclo físicamente más corto posible (QuickMove) y la precisión precisa de la trayectoria (TrueMove). Junto con una ruta independiente de la velocidad, el comportamiento predecible y de alto rendimiento se entrega automáticamente, sin necesidad de ajuste por parte del programador.
    Lenguaje de programacion rapido
    
    La combinación perfecta de simplicidad, flexibilidad y potencia. RAPID es un lenguaje verdaderamente ilimitado con múltiples funciones avanzadas y un potente soporte para muchas aplicaciones de proceso.
    Comunicación
    
    El IRC5 es compatible con los buses de campo de última generación para E / S y es un nodo de buen comportamiento en cualquier red de planta. Las interfaces de sensores, el acceso a discos remotos y los mensajes de socket son ejemplos de las muchas funciones de red potentes.
## Aplicaciones industruales

* Motoman MH6: El Motoman MH6 es un robot industrial versátil diseñado para una amplia variedad de aplicaciones en sectores como manufactura, ensamblaje, logística y automotriz. Su diseño delgado, alta velocidad y capacidad de montaje en múltiples posiciones lo hacen ideal para entornos industriales donde se requiere precisión, flexibilidad y eficiencia. Entre sus principales aplicaciones se encuentra:
  
  - Manufactura aditiva: Puede integrarse en procesos de impresión 3D industrial para la deposición de material en múltiples capas.
  - Dispensado: Precisión en la aplicación de adhesivos, selladores o recubrimientos en líneas de producción automatizadas.
  - TCP remoto: Ajuste automático de la posición del herramental en tareas de alta precisión.
  - Soldadura: Especialmente en soldadura por arco, permitiendo un control preciso de la trayectoria y optimización del tiempo de ciclo.
  - Manipulación de materiales: Carga y descarga de máquinas (CNC, prensas); empaque y paletizado en la clasificación de productos en líneas de producción.
  - Ensamblaje: Integración en celdas de manufactura para el ensamblaje de productos complejos.
  - Pintura y recubrimientos: Aplicaciones de pintura industrial con movimiento preciso y repetitivo. Recubrimientos protectores y selladores en diversas industrias.
  - Corte por plasma y láser: Permitiendo formas complejas con alta precisión.
  
* ABB IRB 140: El ABB IRB 140 es un robot industrial compacto diseñado para aplicaciones que requieren alta precisión, velocidad y flexibilidad. Gracias a su capacidad de montaje en múltiples posiciones y su alta repetibilidad (±0.01 mm), es ideal para tareas exigentes que demandan exactitud y eficiencia. Entre sus principales aplicaciones se encuentra:
  -  Ensamblaje y la manipulación de piezas pequeñas:  Se destaca en la fabricación de dispositivos electrónicos, como teléfonos móviles, radios y circuitos integrados. Su capacidad para operar en salas limpias lo convierte en una opción ideal para la industria de semiconductores, donde la manipulación de microcomponentes requiere entornos controlados. Además, su rapidez y precisión lo hacen adecuado para el empaquetado y la clasificación de productos pequeños en líneas de producción automatizadas.
  -  Soldadura y acabado superficial: Desempeña un papel clave en la soldadura por arco, integrándose en celdas compactas como FlexArc® Compact, diseñadas para optimizar la producción en espacios reducidos. También es utilizado en tareas de pulido y desbarbado de aluminio, así como en el mantenimiento de prensas y otras máquinas industriales, garantizando superficies de alta calidad y reduciendo tiempos de procesamiento.
  -  Industria de fundición y moldeo: El IRB 140 está disponible con protección IP67, lo que le permite operar en entornos hostiles. Su diseño lo hace ideal para la pulverización de matriz en fundiciones y la manipulación en máquinas de fundición a presión, asegurando una aplicación uniforme y eficiente. En el sector del moldeo por inyección, es utilizado para cargar y descargar insertos y piezas moldeadas, agilizando el ciclo de trabajo y mejorando la productividad.
  -  Carga, descarga y manipulación de materiales: Se emplea en líneas de producción automatizadas, optimizando la transferencia de piezas y el mantenimiento de máquinas. Su capacidad para manipular materiales frágiles y de alta precisión le permite mejorar la calidad del proceso productivo, minimizando el margen de error y reduciendo el desgaste de los componentes.   

# Practica

Se realizo un código en python
