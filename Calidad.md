# Modelo de calidad de McCall

Define tres puntos de vista:

- **Operación de producto:** Se relaciona con la funcionalidad.
  
- **Revisión del producto:** Se relaciona con la capacidad del software para adaptarse a posibles cambios.
  
- **Transición del producto:** Se relaciona con la capacidad del software para adaptarse a ciertos contextos de operación.

Clasifica los requisitos de software en 11 factores de calidad:

  1. **Corrección**  
 - **Trazabilidad:** Atributos del software que proporcionan una capacidad de registrar y rastrear las etapas clave durante el desarrollo desde los requisitos a la implementación con respecto a un entorno operativo concreto.  
 - **Compleción:** Atributos del software que proporcionan la implementación completa de todas las funciones requeridas.  
 - **Consistencia:** Atributos del software que proporcionan regularidad en las técnicas de diseño e implementación.
2. **Fiabilidad**
- **Consistencia**
- **Exactitud:** La precisión del control y los cálculos hechos para el software.
- **Tolerancia a fallos:** Atributos del software que hacen posible la continuidad del funcionamiento bajo condiciones no previstas.
3. **Eficiencia**
   - **Eficiencia en ejecución:** Atributos del software que minimizan el tiempo de procesamiento (ejecución de instrucciones).
   - **Eficiencia en almacenamiento:** Atributos del software que minimizan el espacio de almacenamiento necesario.
1. **Integridad**
   - **Control de acceso:** Atributos del software que proporcionan control de acceso al software y a los datos que utiliza.
   - **Auditoría de acceso:** Atributos del software que facilitan la auditoría de los accesos al software.
2.  **Usabilidad**
   - **Operabilidad:** Atributos del software que determinan la facilidad de operación.
   - **Formación:** El grado en que el software ayuda para permitir que nuevos usuarios apliquen el sistema.
   - **Facilidad de comunicación:** Atributos del software que proporcionan entradas y salidas fácilmente incorporadas.
6.   **Facilidad del mantenimiento**
   - **Simplicidad**
   - **Concisión:** Atributos del software que posibilitan la implementación de una función con la menor cantidad de códigos posible.
   - **Autodescripción:** Atributos del software que proporcionan explicaciones sobre la implementación de las funciones.
   - **Modularidad**
7.  **Facilidad de evaluación**
   - **Instrumentación:** Atributos del software que posibilitan la observación del comportamiento del software durante su ejecución para facilitar las mediciones del uso o la identificación de errores.
   - **Autodescripción**
   - **Modularidad**
  8. **Flexibilidad**
   - **Simplicidad**
   - **Extensibilidad:** Atributos del software que posibilitan la expansión del software en cuanto a capacidades funcionales y datos.
   - **Generalidad:** Atributos del software que proporcionan extensión a las funciones implementadas
   - **Modularidad**
9.  **Portabilidad**
   - **Simplicidad**
   - **Independencia del sistema y software**
   - **Independencia de la máquina**
10.  **Reusabilidad**
   - **Simplicidad**
   - **Generalidad**
   - **Modularidad**
   - **Independencia del sistema software**
   - **Independencia de la máquina**
11.  **Interoperabilidad**
   - **Modularidad**
   - **Comunicaciones comunes:** Atributos del software que posibilitan el uso de protocolos de comunicación e interfaces estándar.
   - **Datos comunes:** Atributos del software que posibilitan el uso representaciones de datos estándar.

# Modelo de calidad de Boëhm

Adopta tres principales perspectivas para definir la calidad de un software:

- **Revisión del producto:** Capacidad de ser sometido a cambios.
  
- **Transición del producto:** Capacidad de ser adaptado a nuevos entornos.
  
- **Operaciones del producto:** Características operativas del software.

Requisitos de software para asegurar la calidad:

1. **Portabilidad**
   - **Independencia del dispositivo**
   - **Autocontención**
2. **Fiabilidad**
   - **Autocontención**
   - **Exactitud**
   - **Compleción**
   - **Integridad**
   - **Consistencia**
3. **Eficiencia**
   - **Capacidad para rendir cuentas**
   - **Eficiencia de dispositivos**
   - **Accesibilidad**
4.  **Ergonomía**
   - **Integridad**
   - **Accesibilidad**
   - **Facilidad de comunicación**
5.  **Facilidad de evaluación**
   - **Capacidad para rendir cuentas**
   - **Accesibilidad**
   - **Facilidad de comunicación**
   - **Autodescripción**
   - **Estructuración**
6.  **Comprensibilidad**
   - **Consistencia**
   - **Autodescripción**
   - **Estructuración**
   - **Concisión**
   - **Legibilidad**
7.  **Facilidad para ser modificado**
   - **Estructuración**
   - **Extensibilidad**  
## *Modelo aplicado en TuriAmigos*

Para ser aplicado en nuestro proyecto, consideramos que la opción más óptima sería el modelo de McCall, esto debido a que, es fácilmente reutilizable para evaluar otros productos, gracias a las métricas claras y sencillas que presenta, la utilización de este modelo se vuelve relativamente fácil de utilizar.

En el caso del modelo de Boëhm, funciona mejor con grandes proyectos y se vuelve un modelo costoso, cosa que perjudicaría más que ayudar en el caso de TuriAmigos, más que nada por este ser un proyecto pequeño y para el cual no se cuenta con una cantidad enorme de presupuesto.
