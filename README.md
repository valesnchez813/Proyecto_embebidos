# Monitor Inteligente de Riesgo de Taquicardia por Estrés con Biofeedback Mecánico
## Roles
Valentina Sánchez: Technical lead

Ana Sofia Grajales: Firmware engineer

David Saldarriaga: Verification & testing engineer

Miguel Jiménez: Hardware integration engineer


## Introduccion 
Los trastornos relacionados con el estrés y la ansiedad pueden generar alteraciones fisiológicas, entre ellas episodios de taquicardia asociados a activación del sistema nervioso autónomo. En muchos casos, estos episodios no son percibidos por el usuario en sus etapas iniciales, lo que impide aplicar estrategias de regulación fisiológica de forma oportuna y rápida.
En los últimos años, los dispositivos portátiles de monitoreo fisiológico han permitido registrar variables como la frecuencia cardíaca en tiempo real. Sin embargo, muchos de estos dispositivos se limitan a mostrar información al usuario, sin implementar mecanismos activos de intervención que ayuden a regular el estado fisiológico.
Este proyecto propone el desarrollo de un sistema embebido capaz de monitorear la frecuencia cardíaca mediante un sensor óptico y detectar patrones asociados a riesgo de taquicardia por estrés, activando posteriormente un actuador háptico mecánico que guíe ejercicios de respiración mediante patrones de vibración. De esta forma, el sistema no solo detecta un evento fisiológico, sino que también interviene para ayudar al usuario a regular su respuesta autonómica.

## Descripción del problema
Personas con altos niveles de estrés, ansiedad o sobrecarga autonómica pueden experimentar episodios de taquicardia sostenida. Estos episodios pueden manifestarse como un aumento prolongado de la frecuencia cardíaca, incluso en ausencia de actividad física.
Uno de los principales problemas es que los usuarios no siempre detectan el inicio del episodio, lo que retrasa la aplicación de estrategias de regulación fisiológica como la respiración controlada.
La ausencia de mecanismos de detección temprana y de intervención inmediata puede generar incomodidad, aumento de la ansiedad y empeoramiento del episodio fisiológico.
Por esta razón, se plantea el desarrollo de un sistema embebido que permita:
* Monitorear la frecuencia cardíaca en tiempo real,
* Identificar patrones compatibles con taquicardia asociada a estrés,
* Activar un actuador mecánico que guíe al usuario en un patrón de respiración regulada.
