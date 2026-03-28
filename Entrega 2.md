# Requerimientos funcionales
## Sensado
RF-001: El sistema debe medir la frecuencia cardíaca (BPM) mediante un sensor PPG.  
RF-002: El sistema debe calcular la frecuencia cardíaca en tiempo real.  
RF-003: El sistema debe detectar valores fuera de rango (BPM < 40 o > 180).  
RF-004: El sistema debe detectar desconexión o falla del sensor.

## Procesamiento
RF-005: El sistema debe detectar taquicardia cuando BPM supere un umbral configurado.  
RF-006: El sistema debe identificar eventos sostenidos (ej: > X segundos).  
RF-007: El sistema debe permitir configurar el umbral de BPM desde la GUI.

## Actuación
RF-008: El sistema debe activar un motor vibrador cuando se detecte un evento.  
RF-009: El sistema debe generar patrones de vibración para guiar la respiración (ej: 4-2-6).  
RF-010: El sistema debe detener la vibración cuando el evento finalice.

## Comunicación / GUI
RF-011: El sistema debe enviar datos por UART para monitoreo.  
RF-012: El sistema debe mostrar la frecuencia cardíaca en la GUI.  
RF-013: El sistema debe registrar eventos detectados en la GUI.

# Requerimientos no funcionales
RNF-001: El sistema debe operar en tiempo real con actualización ≤ 1 segundo.  
RNF-002: El sistema debe implementar logging con niveles (INFO, WARN, ERROR).  
RNF-003: El sistema debe manejar errores del sensor sin detener el sistema.  
RNF-004: El sistema debe ser portátil y funcionar con batería externa.  
RNF-005: El cálculo de BPM debe tener un error máximo de ±5 BPM.  
RNF-006: La interfaz debe ser intuitiva y comprensible para un usuario no técnico.


# Plan de testing y pruebas
# Plantillas para los test cases![WhatsApp Image 2026-03-27 at 8 11 08 PM](https://github.com/user-attachments/assets/f27d1512-b83a-43d2-aab5-9265b1c0cc4f)

<img width="1414" height="2000" alt="Test Type" src="https://github.com/user-attachments/assets/720c0585-de4b-4689-99cb-35aff47b5f69" />


