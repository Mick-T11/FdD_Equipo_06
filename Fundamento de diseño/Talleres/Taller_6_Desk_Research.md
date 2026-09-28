from pathlib import Path

md = """# MATRIZ DE DESK RESEARCH

**Grupo 06**

---

## Patentes

| N° | Fuente | Autor o entidad | Año | Referencia | Estado de tecnología encontrado | Exigencia o requisito identificado | Restricción o limitación | Función principal | Aplicación al proyecto |
|---|---|---|---:|---|---|---|---|---|---|
| 01 | Patente | Park y cols. | 2023 | ES2953946T3 | Sistema portátil que registra señales fisiológicas cardíacas. | Considerar registro continuo y módulo de datos desmontable. | Mide actividad cardíaca, no temblor de mano. | Adquirir y almacenar datos. | Antecedente general de arquitectura portable; no sustenta la medición del temblor. |
| 02 | Patente | Zhang y Ding | 2023 | CN113616194B | Dispositivo que mide frecuencia e intensidad del temblor de mano. | Medir frecuencia e intensidad con sensor de movimiento. | Requiere verificar el método con nuestro montaje de muñeca. | Detectar y cuantificar temblor. | Referencia directa para los ensayos técnicos de medición. |
| 03 | Patente | Wong y cols. | 2020 | US10765856B2 | Módulos de monitorización y estimulación eléctrica periférica. | Separar captación y actuación con control de seguridad. | Su estimulación eléctrica queda fuera de nuestro alcance. | Medir y activar respuesta. | Antecedente de arquitectura; actuación vibratoria solo en banco. |

---

## Artículos

| N° | Fuente | Autor o entidad | Año | Referencia | Estado de tecnología encontrado | Exigencia o requisito identificado | Restricción o limitación | Función principal | Aplicación al proyecto |
|---|---|---|---:|---|---|---|---|---|---|
| 04 | Artículo | Saez y cols. | 2025 | doi:10.3390/s25092763 | Sistema ELENA con sensor inercial y análisis digital del temblor. | Registrar señales para medir frecuencia e intensidad. | Su validación no demuestra precisión de nuestro prototipo. | Captar y procesar temblor. | Orienta adquisición y prueba de medición en banco. |
| 05 | Artículo | Channa y cols. | 2021 | doi:10.3390/s21030981 | Pulsera A-WEAR para detectar temblor y bradicinesia. | Captar movimiento desde la muñeca y procesarlo. | Incluye tareas y síntomas fuera de nuestro alcance. | Detectar síntomas motores. | Sustenta explorar el formato de pulsera; verificar señal propia. |
| 06 | Artículo | Vescio y cols. | 2021 | doi:10.3389/fneur.2021.680011 | Revisión de dispositivos portátiles para evaluar temblor. | Comparar sensores, señales y métodos de análisis. | Una revisión no valida la precisión de nuestra pulsera. | Evaluar temblor. | Base comparativa para seleccionar medición y registro. |

---

## Tesis

| N° | Fuente | Autor o entidad | Año | Referencia | Estado de tecnología encontrado | Exigencia o requisito identificado | Restricción o limitación | Función principal | Aplicación al proyecto |
|---|---|---|---:|---|---|---|---|---|---|
| 07 | Tesis | Sigcha | 2021 | Repositorio UPM 68904 | Reloj y teléfono analizan tareas motoras. | Definir condiciones de medición y guardar sesiones. | El análisis no equivale a diagnóstico con nuestra pulsera. | Registrar y analizar movimiento. | Orienta protocolo y exportación de datos. |
| 08 | Tesis | Torres Portella | 2025 | Repositorio PUCP 33174 | Sensor inercial para cuantificar temblor de mano. | Medir frecuencia e intensidad; verificar resultados. | Los resultados de la tesis no se transfieren a nuestro equipo. | Cuantificar temblor. | Guía la prueba técnica de medición. |
| 09 | Tesis | Villa Bernal | 2021 | Repositorio UAEM 110445 | Seguimiento óptico Leap Motion para cuantificar temblor de fatiga. | Comparar extracción de frecuencia y amplitud. | Estudia sujetos sanos y medición óptica, no Parkinson con pulsera. | Cuantificar movimiento. | Comparación de método de análisis, sin transferir resultados. |

---

## Productos

| N° | Fuente | Autor o entidad | Año | Referencia | Estado de tecnología encontrado | Exigencia o requisito identificado | Restricción o limitación | Función principal | Aplicación al proyecto |
|---|---|---|---|---|---|---|---|---|---|
| 10 | Producto | Cala Health | s. f. | Cala kIQ | Dispositivo de muñeca con estimulación. | Ajuste cómodo y controles comprensibles. | Su eficacia terapéutica no se atribuye al prototipo. | Administrar estimulación. | Referencia de formato y experiencia de uso. |
| 11 | Producto | Vilimed | s. f. | VILIM Ball | Dispositivo de mano con vibración mecánica. | Definir magnitud, duración y condiciones de vibración. | Su uso y resultados difieren de una pulsera. | Aplicar vibración. | Antecedente de actuación que se ensayará en banco. |
| 12 | Producto | Encora Therapeutics | s. f. | Encora X1 | Pulsera con estimulación mecánica para temblor esencial. | Comparar interfaz, ajuste y control de estímulo. | Está indicado para temblor esencial, no valida uso en Parkinson. | Detectar y estimular. | Referencia de diseño de muñeca; sin extrapolar eficacia. |

---

## Normas y alcance

| N° | Fuente | Autor o entidad | Año | Referencia | Estado de tecnología encontrado | Exigencia o requisito identificado | Restricción o limitación | Función principal | Aplicación al proyecto |
|---|---|---|---|---|---|---|---|---|---|
| 13 | Norma | IEC | 2013 | IEC 60529 | Clasifica la protección de envolventes frente a ingreso de agua. | Exigir IPX4 con informe de ensayo de la carcasa. | Sin ensayo conforme no puede declararse IPX4. | Proteger la electrónica. | Si no cumple, queda pendiente esta exigencia. |
| 14 | Norma | ISO | 2001 | ISO 5349-1 | Método para evaluar exposición humana a vibración mano-brazo. | Documentar magnitud y tiempo de vibración. | No fija una dosis terapéutica para este prototipo. | Evaluar exposición a vibración. | Referencia para fase humana futura; ahora solo banco. |
| 15 | Institución | Parkinson’s Foundation | s. f. | Etapas de Parkinson | Describe los estadios de Hoehn y Yahr. | Delimitar la población objetivo a estadios 1–3. | El estadio clínico requiere valoración profesional. | Definir alcance de usuarios. | Sustenta el alcance; no permite diagnosticar. |

---

## Referencias y enlaces

El número corresponde a la fila de la matriz.

| N° | Referencia | Enlace |
|---|---|---|
| 01 | ES2953946T3 | https://patents.google.com/patent/ES2953946T3/es |
| 02 | CN113616194B | https://patents.google.com/patent/CN113616194B/en |
| 03 | US10765856B2 | https://patents.google.com/patent/US10765856B2/en |
| 04 | doi:10.3390/s25092763 | https://doi.org/10.3390/s25092763 |
| 05 | doi:10.3390/s21030981 | https://doi.org/10.3390/s21030981 |
| 06 | doi:10.3389/fneur.2021.680011 | https://doi.org/10.3389/fneur.2021.680011 |
| 07 | Repositorio UPM 68904 | https://oa.upm.es/68904/ |
| 08 | Repositorio PUCP 33174 | https://tesis.pucp.edu.pe/items/2a76658d-7dfe-4097-9acd-cc4df05bac90 |
| 09 | Repositorio UAEM 110445 | https://ri.uaemex.mx/handle/20.500.11799/110445 |
| 10 | Cala kIQ | https://calahealth.com/ |
| 11 | VILIM Ball | https://vilimed.com/es |
| 12 | Encora X1 | https://www.encoratherapeutics.com/meet-encora-x1 |
| 13 | IEC 60529 | https://webstore.iec.ch/en/publication/2452 |
| 14 | ISO 5349-1 | https://www.iso.org/standard/32355.html |
| 15 | Etapas de Parkinson | https://www.parkinson.org/espanol/entendiendo-parkinson/que-es-parkinson/etapas |

> **s. f.**: sin fecha de publicación indicada. Fuentes consultadas en 2026.
"""

path = Path("/mnt/data/Taller_6_Desk_Research.md")
path.write_text(md, encoding="utf-8")

print(f"Archivo creado: {path}")
print(f"Tamaño: {path.stat().st_size} bytes")
