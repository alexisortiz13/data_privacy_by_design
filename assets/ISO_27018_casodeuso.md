
# Casos de uso — ISO/IEC 27018:2025

**Norma:** Protección de información personal en servicios de nube pública  
**Materia:** Legalidad y Protección de la Información  
**Proyecto:** Corpus para Harness LLM RAG

---

## Caso 08. Filtración de datos personales en la nube

### Contexto
Una empresa almacena información personal de sus clientes en una plataforma de nube pública para facilitar el acceso a documentos y respaldos empresariales.

### Problemática
Una configuración incorrecta de permisos permite que una carpeta con información personal sea consultada mediante enlaces públicos, exponiendo datos de clientes sin autorización.

### Objetivo
Evitar la exposición de información personal y fortalecer los controles de privacidad en los servicios de almacenamiento en la nube.

### Desarrollo
El equipo de Sistemas detecta que una carpeta contiene documentos accesibles públicamente. Se identifica el recurso comprometido, se revisan los permisos y se determina qué información pudo quedar expuesta.

Posteriormente, se analiza la configuración del servicio, se revisan los registros de acceso y se coordina con el proveedor de nube la implementación de medidas correctivas.

### Medidas de solución
1. Eliminar inmediatamente el acceso público a la carpeta.
2. Preservar registros y evidencias del incidente.
3. Identificar los datos personales potencialmente comprometidos.
4. Revisar y corregir las configuraciones de seguridad.
5. Implementar permisos restrictivos según las funciones del personal.
6. Establecer monitoreo continuo de recursos compartidos.
7. Evaluar las obligaciones legales y contractuales de notificación.

### Resultado esperado
Contener la exposición de datos personales, reducir la probabilidad de nuevas configuraciones inseguras y mejorar la protección de la información almacenada en la nube.

### Pregunta para el agente
¿Qué medidas debe implementar una empresa cuando una carpeta de almacenamiento en la nube que contiene datos personales queda accesible públicamente?

### Respuesta esperada
La empresa debe restringir inmediatamente el acceso público, preservar evidencias, evaluar qué datos estuvieron expuestos, revisar registros y corregir los permisos.

También debe coordinarse con el proveedor de nube y determinar las obligaciones legales y contractuales aplicables.

### Referencia normativa
ISO/IEC 27018:2025 — Protección de información de identificación personal en servicios de nube pública.

Referencia oficial: https://www.iso.org/standard/27018

---

## Caso 09. Acceso indebido de proveedores a información personal

### Contexto
Una organización contrata un proveedor de nube pública para almacenar y procesar información personal de clientes y empleados.

### Problemática
Personal técnico del proveedor dispone de permisos amplios sobre la información almacenada, sin mecanismos suficientes de supervisión y trazabilidad.

Esta situación puede ocasionar accesos injustificados o divulgación no autorizada de datos personales.

### Objetivo
Delimitar las responsabilidades del proveedor y establecer mecanismos de control sobre el acceso a información personal.

### Desarrollo
La organización realiza una evaluación de los servicios contratados e identifica que el proveedor puede acceder a determinados conjuntos de datos mediante cuentas administrativas.

Se revisan los contratos, los perfiles autorizados y los procedimientos utilizados para acceder a la información.

Posteriormente, se establecen responsabilidades, controles de acceso y mecanismos de auditoría.

### Medidas de solución
1. Definir responsabilidades contractuales sobre el tratamiento de datos.
2. Limitar los permisos administrativos del proveedor.
3. Exigir registros de acceso a información personal.
4. Revisar la participación de subencargados del tratamiento.
5. Establecer procedimientos de supervisión y auditoría.
6. Definir mecanismos de notificación de incidentes.
7. Revisar periódicamente los controles establecidos.

### Resultado esperado
Mejorar la transparencia y el control sobre la información personal procesada por proveedores externos.

### Pregunta para el agente
¿Cómo puede una empresa controlar el acceso de un proveedor de nube pública a la información personal de sus clientes?

### Respuesta esperada
La empresa debe establecer responsabilidades contractuales, aplicar permisos mínimos, exigir registros de acceso y supervisar el tratamiento de datos personales.

También debe evaluar los controles del proveedor, revisar los subencargados y establecer procedimientos para gestionar incidentes.

### Referencia normativa
ISO/IEC 27018:2025 — Protección de información personal en servicios de nube pública.

Referencia oficial: https://www.iso.org/standard/27018

---

## Caso 10. Eliminación segura de datos al finalizar un contrato cloud

### Contexto
Una empresa utiliza servicios de nube pública para almacenar expedientes digitales de clientes y documentación empresarial.

Después de varios años decide cambiar de proveedor tecnológico.

### Problemática
El proveedor anterior conserva copias de información personal en sus sistemas y respaldos, aun después de finalizar el contrato.

La organización desconoce si los datos fueron eliminados completamente o si permanecen accesibles.

### Objetivo
Garantizar que la devolución, conservación y eliminación de datos personales se realicen bajo condiciones documentadas y verificables.

### Desarrollo
Antes de finalizar el contrato, la empresa identifica los datos almacenados en la plataforma y revisa las condiciones de devolución y eliminación.

Se analizan los periodos de conservación, las copias de respaldo y las responsabilidades del proveedor.

Finalmente, se ejecuta un procedimiento de cierre que incluye la recuperación de información y la solicitud de evidencias de eliminación.

### Medidas de solución
1. Elaborar un inventario de información almacenada.
2. Recuperar los datos necesarios antes de cancelar el servicio.
3. Definir contractualmente los plazos de eliminación.
4. Revisar el tratamiento de copias de respaldo.
5. Solicitar evidencias o constancias de eliminación.
6. Revocar accesos y credenciales del proveedor anterior.
7. Documentar el cierre del servicio y verificar las obligaciones de conservación.

### Resultado esperado
Reducir el riesgo de exposición de datos personales después de finalizar la relación contractual y disponer de evidencias del procedimiento de eliminación.

### Pregunta para el agente
¿Qué debe verificar una empresa antes de cancelar un servicio de nube pública que almacena información personal?

### Respuesta esperada
La empresa debe comprobar que recuperó la información necesaria, revisar las obligaciones legales de conservación y verificar las condiciones de eliminación de datos.

También debe considerar las copias de respaldo, revocar accesos y solicitar evidencias documentales del proveedor.

### Referencia normativa
ISO/IEC 27018:2025 — Protección de información personal en servicios de nube pública.

Referencia oficial: https://www.iso.org/standard/27018

---

## Conclusión

Los tres casos de uso muestran situaciones relacionadas con la exposición, el acceso y la eliminación de información personal en servicios de nube pública.

La ISO/IEC 27018:2025 constituye una referencia para establecer prácticas de protección de datos personales en este entorno.

Estos escenarios podrán incorporarse posteriormente al corpus del proyecto Harness LLM RAG para evaluar respuestas sobre privacidad, seguridad y responsabilidades de los proveedores.

**Nota académica:** Los escenarios son hipotéticos y las medidas descritas son propuestas de aplicación. No constituyen transcripciones de requisitos específicos de la norma.
