# Sistema de Riego Inteligente para Agricultores Rurales

Building AI course project

## Resumen

Este proyecto busca ofrecer una solución de riego inteligente, económica y funcional que pueda ser utilizada por pequeños agricultores en regiones rurales, especialmente en zonas como Tunja, Boyacá (Colombia), donde los recursos son limitados y el conocimiento tecnológico puede ser básico. A partir del uso de sensores de humedad, el sistema permite automatizar parte del proceso de riego, alertando al agricultor cuando el nivel de agua en el suelo baja de un umbral específico o activando un sistema de riego de forma autónoma si así se configura.

La propuesta nace como respuesta a una problemática común: muchos agricultores deben recorrer sus cultivos diariamente para revisar manualmente si las plantas necesitan agua, lo que consume tiempo y recursos. Este proyecto tiene como objetivo reducir ese esfuerzo, optimizar el uso del agua y ayudar a mantener la salud de los cultivos.

Además, el sistema está diseñado para adaptarse a diferentes niveles de automatización. Puede funcionar de forma semiautomática (enviando notificaciones por SMS o activando una luz LED cuando es momento de regar), o completamente automática (activando una bomba de agua o válvula solenoide). La lógica es simple, confiable y pensada para ser fácilmente replicable con componentes de bajo costo.

El enfoque también contempla el uso de energía solar, para hacerlo más sostenible y útil en zonas sin acceso constante a electricidad. Este proyecto busca ser un punto de partida para futuras mejoras que integren predicción climática, inteligencia artificial y una interfaz más intuitiva para los usuarios.

Building AI course project
## Background

El riego manual en zonas rurales representa un gran desafío por el esfuerzo físico y el tiempo que consume, afectando la productividad agrícola y la calidad de vida de los agricultores.  
Este problema es frecuente en pequeñas fincas que carecen de sistemas automatizados debido al costo y la complejidad tecnológica.  
Personalmente, quiero contribuir a mejorar las condiciones de trabajo de estos agricultores con una solución sencilla, accesible y eficiente.

Problemas que soluciona:  
* Uso ineficiente del agua en riego manual  
* Gran dedicación de tiempo y esfuerzo físico en la tarea de regar  
* Falta de acceso a tecnologías de riego automatizado asequibles y fáciles de usar  

## How is it used?

El sistema se instala en fincas pequeñas con acceso a electricidad solar y agua de nacederos. Utiliza sensores de humedad para monitorear el suelo y activa el riego automáticamente cuando es necesario, pero manteniendo la posibilidad de control manual.  
Los usuarios son agricultores rurales con conocimientos limitados de tecnología, por lo que la interfaz y controles son intuitivos y accesibles.  
El sistema puede operar en diferentes condiciones climáticas y cultivos, adaptándose a las necesidades locales.

## Data sources and AI methods

El sistema utiliza datos propios recolectados mediante sensores de humedad instalados en el terreno. No depende de bases de datos externas.  
Se emplea lógica simple de control basada en umbrales de humedad para activar o desactivar el riego, evitando la complejidad de modelos predictivos avanzados para mantener la accesibilidad y bajo costo.

## Challenges

El proyecto no soluciona:  
* Riego en grandes superficies agrícolas ni con sistemas industriales complejos  
* Problemas estructurales del terreno o fuentes de agua limitadas  
* Implementación de inteligencia artificial avanzada para predicción meteorológica (en esta etapa)  

Limitaciones éticas y técnicas:  
* Es necesario asegurar que el sistema no sobreconsuma agua ni cause desperdicios  
* La adopción depende de capacitación mínima para los usuarios  

## What next?

Para continuar el desarrollo, se podrían incorporar:  
* Integración con pronósticos meteorológicos para optimizar riegos  
* Implementación de alertas vía SMS o app móvil sencilla  
* Mejoras en la interfaz para mayor accesibilidad  
* Adaptación para otros tipos de cultivos y terrenos  

Se requeriría colaboración con expertos en agricultura local y soporte técnico para usuarios.

## Acknowledgments

* Inspiración basada en las necesidades de agricultores rurales en Boyacá, Colombia 
