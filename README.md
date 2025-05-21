# Sistema de Riego Semiautomatizado para Zonas Rurales

## Resumen
Este proyecto propone un sistema de riego semiautomatizado para agricultores rurales que optimiza el uso del agua mediante sensores y control lógico simple. Es económico, fácil de usar y adaptable. Building AI course project.

## Background

El riego manual es común en muchas zonas rurales y puede ser ineficiente y costoso en términos de tiempo y agua. Los agricultores con pocos recursos y acceso limitado a tecnología necesitan soluciones sencillas, confiables y económicas.

* Falta de acceso a tecnología moderna
* Pérdida de agua por riego ineficiente
* Dificultad para regar zonas amplias manualmente

## How is it used?

El sistema se instala en parcelas agrícolas con sensores de humedad del suelo. Cuando el suelo está seco, activa una electroválvula o bomba para iniciar el riego. El sistema se alimenta con energía solar y puede tener opción de activación manual o remota.

## Data sources and AI methods

Los sensores proveen datos de humedad y temperatura. Con un microcontrolador (como Arduino o ESP32), se aplican reglas simples o modelos ligeros de aprendizaje automático para decidir cuándo activar el riego.

## Challenges

Este proyecto no aborda problemas de infraestructura de agua ni garantiza cobertura para terrenos de gran tamaño. Requiere cierta capacitación básica para su instalación y mantenimiento.

## What next?

Se planea implementar alertas por SMS, interfaces móviles sencillas y escalabilidad para diferentes tamaños de terreno. También se podrían integrar modelos más complejos de IA si se dispone de más datos.

## Acknowledgments

Proyecto desarrollado con inspiración en fincas rurales de Boyacá, Colombia. Basado en ideas del Building AI course por Reaktor Innovations y University of Helsinki.
