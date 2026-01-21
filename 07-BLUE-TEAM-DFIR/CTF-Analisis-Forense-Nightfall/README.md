# CTF - Análisis Forense (Caso Nightfall)

## Objetivo
Investigar un incidente de seguridad en el servidor FT-DEV01 correlacionando evidencias de:
- Imagen de disco
- Captura de tráfico de red
- Volcado de memoria

## Evidencias analizadas
- Imagen de disco (.raw)
- Captura de red (.pcapng)
- Memoria (.vmem)

## Metodología DFIR
- Validación de integridad (hashes)
- Análisis de disco (Autopsy)
- Análisis de tráfico (Wireshark)
- Análisis de memoria (Volatility)
- Correlación de hallazgos + timeline
- Extracción de IoCs y recomendaciones

## Hallazgos destacados
- Comunicación sospechosa hacia puerto 4444 (indicativo de Meterpreter)
- Exfiltración de información mediante netcat
- Procesos anómalos y binario sospechoso detectado en memoria
- Reconstrucción completa del incidente con timeline

📄 Informe completo en PDF incluido en esta carpeta.

> Nota: Ejercicio realizado en entorno de laboratorio/CTF con fines educativos.
