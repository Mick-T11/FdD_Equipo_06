# TALLER 4: ANÁLISIS DE PATENTES PARA DISPOSITIVOS DE REDUCCIÓN DE TEMBLOR

---

## PATENTE 1

* **TÍTULO:** Innovative kit that includes a wearable for detecting, characterizing, and monitoring involuntary movement and attachable non-intrusive interventions to relieve tremors in human limbs
* **CÓDIGO:** US20220322970A1
* **CIP/CPC:** 
  * `A61B 5/1101` (Detección de temblor)
  * `A61B 5/681` (Dispositivos tipo reloj de muñeca)
  * `A61N 1/36031` (Control de estimulación usando parámetros fisiológicos)

### ¿Qué aporta?
Aporta una arquitectura muy cercana a nuestro proyecto: una unidad *wearable* de muñeca que registra el movimiento, procesa las señales del temblor y permite conectar una intervención no invasiva[cite: 1]. La patente describe un ESP32 como unidad principal de procesamiento y un sensor de movimiento, además de una pantalla, almacenamiento micro-SD y una unidad TENS[cite: 1]. Para nuestro prototipo, sirve como referencia para integrar monitoreo, visualización y un módulo de respuesta en un solo dispositivo[cite: 1].

### Características
* Mide aceleración en tres dimensiones ($x, y, z$)[cite: 1].
* Analiza frecuencia dominante, intensidad, porcentaje de tiempo con temblor y duración de los eventos[cite: 1].
* Incluye una intervención TENS que puede activarse manual o automáticamente según inicio, duración e intensidad del temblor[cite: 1].
* El kit descrito utiliza una batería de 9 V para la unidad TENS[cite: 1].

#### Figura 1. Representación CAD de referencia asociada a US20220322970A1
> **Nota:** Imagen esquemática de apoyo visual; consultar la publicación original en Espacenet para las figuras oficiales[cite: 1].  
> **Fuente Espacenet:** [US20220322970A1 en Espacenet](https://worldwide.espacenet.com/patent/search/family/083509951/publication/US2022322970A1?q=US20220322970A1)[cite: 1]

---

## PATENTE 2

* **TÍTULO:** Wearable device to treat tremor[cite: 1]
* **CÓDIGO:** US20220054349A1[cite: 1]
* **CIP/CPC:** 
  * `A61B 5/1101` (Detección de temblor)[cite: 1]
  * `A61B 5/4836` (Diagnóstico combinado con tratamiento en lazo cerrado)[cite: 1]

### ¿Qué aporta?
Aporta un método mecánico para reducir el temblor mediante amortiguadores de masa sintonizada (TMD) y mecanismos de amortiguamiento por fricción[cite: 1]. El sistema puede colocarse en la muñeca/mano y ajustar su respuesta de acuerdo con la frecuencia del temblor[cite: 1]. Para nuestro proyecto, la idea más útil es incorporar un módulo mecánico compacto que responda a la frecuencia detectada, en vez de limitar la pulsera únicamente al monitoreo[cite: 1].

### Características
* **Frecuencia característica de temblor indicada:** aproximadamente $3\text{–}12\text{ Hz}$[cite: 1].
* **Ejemplo de sintonización:** $3.8\text{–}4\text{ Hz}$[cite: 1].
* **Ejemplo de rango ampliado con sistema de masas anidadas:** $3.3\text{–}4.5\text{ Hz}$[cite: 1].
* **Ejemplo del modelo:** a $5\text{ Hz}$ se plantea una rigidez efectiva de $100\text{ N/m}$; a $6\text{ Hz}$, $150\text{ N/m}$[cite: 1].
* **Variables que puede seguir:** frecuencia, amplitud e intensidad del temblor[cite: 1].
* Usa resonadores, resortes y mecanismos de amortiguamiento para interferir con el movimiento del temblor[cite: 1].

#### Figura 2. Representación CAD de referencia asociada a US20220054349A1
> **Nota:** Imagen esquemática de apoyo visual; consultar la publicación original en Espacenet para las figuras oficiales[cite: 1].  
> **Fuente Espacenet:** [US20220054349A1 en Espacenet](https://worldwide.espacenet.com/patent/search/family/072666384/publication/US2022054349A1?q=US20220054349A1)[cite: 1]

---

## PATENTE 3

* **TÍTULO:** Systems, Methods, And Devices For Tremor Reduction[cite: 1]
* **CÓDIGO:** US20200163588A1[cite: 1]
* **CIP/CPC:** 
  * `A61B 5/1101` (Detección de temblor)[cite: 1]
  * `A61B 5/4836` (Diagnóstico y tratamiento en lazo cerrado)[cite: 1]
  * `A61B 5/6824` (Brazo o muñeca)[cite: 1]
  * `A61B 2562/0219` (Sensores inerciales: acelerómetros y giroscopios)[cite: 1]

### ¿Qué aporta?
Aporta el principio de detectar la magnitud y dirección del movimiento y aplicar una fuerza en sentido contrario para reducir el temblor[cite: 1]. Describe wearables con acelerómetro, giroscopio, procesador e interfaz de usuario[cite: 1]. Para nuestra pulsera, sirve como referencia para que el MPU6050 mida el movimiento y el microcontrolador determine una respuesta mecánica opuesta, formando un sistema de control basado en la señal detectada[cite: 1].

### Características
* **Sensores propuestos:** acelerómetro y giroscopio; también contempla micrófono y transceptor[cite: 1].
* Detecta magnitud y dirección del movimiento (por ejemplo: arriba, abajo, izquierda o derecha)[cite: 1].
* **Ejemplos de zona de detección:** movimientos dentro de $3$, $5$ o $7\text{ pulgadas}$ de la parte corporal, según la realización descrita[cite: 1].
* **Material de la prenda wearable:** elongación de $58\text{–}75\%$[cite: 1].
* Los pesos opcionales del dispositivo pueden sumar menos de $2\text{ lb}$ ($\approx 0.91\text{ kg}$)[cite: 1].
* La fuerza opuesta puede ajustarse según el movimiento y la zona corporal[cite: 1].

#### Figura 3. Representación CAD de referencia asociada a US20200163588A1
> **Nota:** Imagen esquemática de apoyo visual; consultar la publicación original en Espacenet para las figuras oficiales[cite: 1].  
> **Fuente Espacenet:** [US20200163588A1 en Espacenet](https://worldwide.espacenet.com/patent/search/family/070771109/publication/US2020163588A1?q=US20200163588A1)[cite: 1]

---

## Referencias

1. Singh J, Mandal P, Singh-Miller N, Sharma P. *Innovative Kit That Includes a Wearable for Detecting, Characterizing, and Monitoring Involuntary Movement and Attachable Non-Intrusive Interventions to Relieve Tremors in Human Limbs*. US2022322970A1, 2022[cite: 1]. 
2. Narula M. *Wearable Device to Treat Tremor*. US2022054349A1, 2022[cite: 1]. 
3. Prevost NE, Goddard NS, Spivey CC. *Systems, Methods, And Devices For Tremor Reduction*. US2020163588A1, 2020[cite: 1].