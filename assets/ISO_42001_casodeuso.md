
# Casos de uso — ISO/IEC 42001:2023

**Norma:** Sistema de Gestión de Inteligencia Artificial  
**Materia:** Legalidad y Protección de la Información  
**Proyecto:** Corpus para Harness LLM RAG  
**Categoría:** Inteligencia Artificial

---

## Caso 11. Discriminación algorítmica en procesos de contratación

### Contexto
Una empresa multinacional implementa un sistema de inteligencia artificial para analizar currículums y seleccionar candidatos a puestos de trabajo.

El modelo fue entrenado con información histórica de contrataciones y asigna puntuaciones a los aspirantes según su experiencia, formación académica y trayectoria profesional.

### Problemática
Durante una auditoría interna se identifica que el sistema asigna puntuaciones desfavorables a determinados grupos de candidatos.

El problema puede originarse por sesgos presentes en los datos históricos, variables utilizadas como indicadores indirectos o deficiencias en el proceso de evaluación.

Esto representa un riesgo de discriminación y puede afectar la equidad del proceso de contratación.

### Objetivo
Promover decisiones de contratación responsables, transparentes y supervisadas, reduciendo los riesgos de discriminación algorítmica.

### Desarrollo
El departamento de Recursos Humanos detecta diferencias significativas en las recomendaciones del modelo.

Se forma un equipo integrado por especialistas en IA, Recursos Humanos, seguridad de la información y cumplimiento normativo.

El equipo revisa los datos utilizados para entrenar el sistema, analiza las variables de clasificación y evalúa los resultados obtenidos.

Posteriormente, establece procedimientos de revisión humana y mecanismos para detectar desviaciones en el comportamiento del modelo.

### Medidas de solución
1. Evaluar la calidad y representatividad de los datos de entrenamiento.
2. Identificar posibles sesgos en las variables y resultados.
3. Documentar la finalidad y las limitaciones del sistema.
4. Implementar supervisión humana en decisiones relevantes.
5. Establecer indicadores para monitorear diferencias de desempeño.
6. Crear procedimientos de revisión de decisiones.
7. Realizar auditorías periódicas del sistema de IA.

### Resultado esperado
Reducir decisiones discriminatorias, mejorar la transparencia del proceso de selección y fortalecer la confianza de los candidatos.

### Pregunta para el agente
¿Qué medidas debe implementar una empresa cuando detecta que su sistema de inteligencia artificial utilizado para seleccionar personal produce resultados discriminatorios?

### Respuesta esperada
La organización debe investigar las causas de las diferencias identificadas, evaluar los datos y criterios utilizados por el modelo y determinar el impacto sobre los candidatos.

Debe implementar medidas correctivas, documentar las evaluaciones y garantizar una supervisión humana efectiva.

Asimismo, debe revisar las disposiciones legales aplicables en materia de igualdad y protección de datos.

### Referencia normativa
ISO/IEC 42001:2023 — Sistema de Gestión de Inteligencia Artificial.

Referencia oficial: https://www.iso.org/standard/42001

---

## Caso 12. Inteligencia artificial como apoyo en diagnósticos médicos

### Contexto
Un hospital incorpora una herramienta de inteligencia artificial para analizar imágenes médicas y apoyar la detección temprana de enfermedades.

El sistema procesa estudios clínicos y genera recomendaciones para el personal médico.

### Problemática
Durante una evaluación se identifica que el modelo puede generar predicciones incorrectas cuando recibe imágenes de baja calidad o información diferente a la utilizada durante su entrenamiento.

Una recomendación incorrecta podría influir en decisiones clínicas y afectar la seguridad del paciente.

### Objetivo
Establecer una gestión responsable del sistema de IA, garantizando supervisión profesional, evaluación de riesgos y monitoreo de su desempeño.

### Desarrollo
El hospital realiza pruebas para evaluar la precisión del modelo en diferentes condiciones.

Se documentan las limitaciones del sistema y se establecen procedimientos para que el personal médico revise las recomendaciones generadas.

La institución define responsabilidades para el uso, mantenimiento y evaluación del sistema.

También establece mecanismos para registrar errores y suspender temporalmente su utilización cuando se identifiquen riesgos importantes.

### Medidas de solución
1. Validar el desempeño del modelo antes de utilizarlo.
2. Documentar sus limitaciones y condiciones de uso.
3. Mantener supervisión de profesionales médicos.
4. Registrar errores y recomendaciones relevantes.
5. Evaluar periódicamente el comportamiento del sistema.
6. Establecer procedimientos de suspensión ante riesgos graves.
7. Revisar los requisitos regulatorios aplicables.

### Resultado esperado
Utilizar la inteligencia artificial como herramienta de apoyo clínico, reduciendo riesgos y manteniendo responsabilidades claramente definidas.

### Pregunta para el agente
¿Es adecuado permitir que un sistema de inteligencia artificial determine diagnósticos médicos sin supervisión profesional?

### Respuesta esperada
La organización debe evaluar el riesgo clínico, las limitaciones del modelo y los requisitos regulatorios correspondientes.

En aplicaciones de alto impacto se recomienda mantener supervisión médica, validación continua y procedimientos de intervención cuando las recomendaciones sean incorrectas o inciertas.

### Referencia normativa
ISO/IEC 42001:2023 — Gestión responsable de sistemas de IA.

Referencia oficial: https://www.iso.org/standard/42001

---

## Caso 13. Implementación responsable de chatbots institucionales

### Contexto
Una institución pública implementa un chatbot basado en un modelo de lenguaje para responder preguntas de los ciudadanos sobre servicios, trámites y requisitos administrativos.

El sistema utiliza una arquitectura de recuperación aumentada por generación (RAG) para consultar documentos institucionales.

### Problemática
Durante las pruebas se detecta que el chatbot genera ocasionalmente información incorrecta y presenta respuestas que no están respaldadas por documentos oficiales.

También existe el riesgo de que el sistema recupere documentos restringidos y divulgue información no autorizada.

### Objetivo
Establecer mecanismos de gobernanza y control para generar respuestas confiables, verificables y alineadas con la información institucional.

### Desarrollo
La institución define un conjunto de fuentes documentales autorizadas para el chatbot.

Se establece un procedimiento de revisión de documentos y se configuran controles para restringir el acceso a información sensible.

Posteriormente, el equipo evalúa las respuestas generadas mediante preguntas de prueba, comparándolas con la información recuperada.

Se implementan mecanismos para registrar errores, actualizar fuentes y supervisar el funcionamiento del sistema.

### Medidas de solución
1. Utilizar fuentes documentales autorizadas y actualizadas.
2. Incorporar recuperación de información mediante RAG.
3. Evaluar la correspondencia entre respuestas y fuentes.
4. Restringir el acceso a documentos confidenciales.
5. Establecer procedimientos de supervisión humana.
6. Registrar errores y respuestas incorrectas.
7. Implementar mecanismos de actualización documental.

### Resultado esperado
Proporcionar respuestas institucionales confiables, trazables y sustentadas en documentos verificables.

### Pregunta para el agente
¿Cómo debe responder un chatbot institucional cuando no encuentra información suficiente en su base de conocimientos?

### Respuesta esperada
El chatbot debe reconocer que no dispone de información suficiente para responder con certeza.

No debe inventar procedimientos, requisitos o referencias normativas.

Debe comunicar la limitación al usuario y, cuando corresponda, recomendar la consulta de fuentes oficiales o canales institucionales.

### Referencia normativa
ISO/IEC 42001:2023 — Sistema de Gestión de Inteligencia Artificial.

Referencia oficial: https://www.iso.org/standard/42001

---

## Caso 14. Supervisión humana en decisiones automatizadas de crédito

### Contexto
Una institución financiera implementa un modelo de inteligencia artificial para analizar solicitudes de crédito.

El sistema considera información financiera, historial de pagos y otras variables para emitir recomendaciones de aprobación o rechazo.

### Problemática
El modelo rechaza automáticamente algunas solicitudes sin ofrecer mecanismos adecuados de revisión.

Los solicitantes desconocen los criterios generales utilizados y no disponen de un procedimiento claro para solicitar una evaluación adicional.

### Objetivo
Garantizar una gestión responsable de las decisiones automatizadas mediante supervisión, documentación y evaluación de impactos.

### Desarrollo
La institución financiera revisa el proceso de evaluación crediticia y analiza los riesgos derivados de las decisiones automatizadas.

Se identifican las variables utilizadas por el modelo, los posibles errores y las consecuencias para los solicitantes.

La organización establece procedimientos de revisión humana y mecanismos para registrar las decisiones relevantes.

También se implementa monitoreo periódico para identificar cambios en el desempeño del sistema.

### Medidas de solución
1. Evaluar los riesgos e impactos del modelo.
2. Documentar los criterios generales de decisión.
3. Establecer mecanismos de supervisión humana.
4. Habilitar procedimientos de revisión de solicitudes.
5. Monitorear errores y posibles sesgos.
6. Registrar las decisiones automatizadas.
7. Verificar el cumplimiento de las disposiciones legales aplicables.

### Resultado esperado
Mejorar la transparencia, reducir decisiones injustificadas y fortalecer los mecanismos de revisión de solicitudes de crédito.

### Pregunta para el agente
¿Qué controles debe implementar una institución financiera cuando utiliza inteligencia artificial para rechazar solicitudes de crédito?

### Respuesta esperada
La institución debe evaluar los riesgos del sistema, documentar sus criterios de funcionamiento y establecer mecanismos de supervisión y revisión.

También debe monitorear posibles errores o sesgos, conservar registros de decisiones y verificar el cumplimiento de las obligaciones legales aplicables.

### Referencia normativa
ISO/IEC 42001:2023 — Sistema de Gestión de Inteligencia Artificial.

Referencia oficial: https://www.iso.org/standard/42001

---
