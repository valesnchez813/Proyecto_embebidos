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
# Plan de testing y pruebas
# Plantillas para los test cases
