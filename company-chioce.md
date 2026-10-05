## 1. Por qué elegí TrackFlow

Elegí TrackFlow porque trabajo en logística de distribución y reconozco sus problemas: incidencias de entrega que se gestionan a mano y datos de rendimiento que nadie tiene estructurados. Es una empresa con un mandato claro de automatizar (TrackFlow Tech) y con dos mercados, Estados Unidos y España, lo que da escala a cualquier solución. Sus procesos más costosos son repetitivos y de alto volumen (consultas de clientes, devoluciones, seguimiento de transportistas), que es donde la IA ofrece resultados medibles rápido. Y mi experiencia construyendo herramientas internas para logística me permite proponer soluciones realistas y no solo teóricas.

## 2. Departamentos con problemas interesantes

### Última Milla y Gestión de Transportistas
- Se trabaja con 8 transportistas (UPS, FedEx, MRW, SEUR...) y todo el seguimiento se hace a mano, consultando el portal de cada uno por separado.
- Los datos de rendimiento de los transportistas no existen en forma estructurada, así que no se puede decidir con datos quién lleva cada envío.
- **Por qué me interesa:** unificar el seguimiento y detectar entregas en riesgo antes de que fallen tiene un impacto directo en coste y en satisfacción del cliente.

### Atención al Cliente
- 15 agentes responden consultas muy repetitivas ("¿dónde está mi paquete?") consultando un documento de Word en Google Drive.
- El 80% de las consultas podría resolverse automáticamente y hoy no hay cobertura fuera del horario de oficina.
- **Por qué me interesa:** es el caso clásico para un agente de IA con acceso a datos reales. Libera al equipo para los casos complejos y responde al instante, a cualquier hora.

*(Tercera opción: **Logística Inversa**, con devoluciones del 18-25% y cada decisión pasando por revisión humana.)*

## 3. Reto que más ganas tengo de construir

**Un agente de IA de seguimiento de incidencias de última milla.**

Detecta paquetes perdidos, entregas fallidas y direcciones incorrectas en los 8 transportistas, y avisa al cliente antes de que pregunte. Me motiva porque conecta dos departamentos (Última Milla y Atención al Cliente) y porque convierte datos dispersos en una decisión accionable.

## Mi idea de Agente de IA

El agente vigila los envíos de los 8 transportistas de TrackFlow y detecta incidencias (paquete parado, entrega fallida, dirección incorrecta) antes de que el cliente pregunte. Para ello necesita el estado de seguimiento de cada transportista, los datos del pedido (cliente, dirección, fecha prometida) y las políticas de cada marca sobre reintentos y compensaciones. Cuando detecta un problema, avisa al consumidor con un mensaje claro y propone una solución, y si el caso es complejo lo pasa a Atención al Cliente con el contexto ya resumido. Además, guarda cada incidencia de forma estructurada, lo que genera por primera vez datos de rendimiento por transportista.
