# GreenTech MVP Sostenible — Refactorización y Auditoría Web

## Introducción

Este proyecto consiste en la refactorización completa del MVP “Salvemos el Planeta”, una landing page originalmente construida con dependencias pesadas e innecesarias (Bootstrap, jQuery, Moment.js, Font Awesome, Google Fonts…).  
El objetivo ha sido transformar esa web en una versión ligera, eficiente y sostenible, alineada con los principios de la economía circular y las Web Sustainability Guidelines (WSG).

---

## Acciones de Optimización Realizadas

### Eliminación de dependencias externas
- Bootstrap → CSS nativo  
- jQuery y Moment → JavaScript nativo  
- Font Awesome → emoji local  
- Google Fonts → fuentes del sistema  

### Optimización de imágenes
- Imagen principal descargada, comprimida y reducida de resolución  
- Implementación de `loading="lazy"`  

### Reducción del peso total
- Eliminación de más de 300–500 KB en librerías externas  
- Reducción del número de peticiones HTTP  
- CSS y JS mínimos, sin frameworks  

---

## Comparativa Antes / Después

| Métrica | Antes | Después |
|--------|--------|---------|
| Peso total aproximado | ~800 KB – 1.2 MB | ~80–150 KB |
| Peticiones HTTP | 10–15 | 2–3 |
| Dependencias externas | 5 | 0 |
| Imagen principal | ~3–4 MB | ~150–200 KB |

Los valores exactos pueden variar según la herramienta de medición (DevTools, WebPageTest, GTmetrix).

---

## Impacto Ambiental y Economía Circular

Reducir el peso de una web no es solo una mejora técnica: es una acción directa contra el impacto ambiental del software.

### Menor consumo energético
Según las Web Sustainability Guidelines del W3C:

“Reducir el tamaño de los recursos y la transferencia de datos disminuye el consumo energético en redes y centros de datos.”  
[1]

### Extensión de la vida útil del hardware
Un software más ligero:
- Requiere menos CPU y RAM  
- Evita sobrecalentamientos en móviles de gama baja  
- Reduce la presión para renovar dispositivos  

Esto se alinea con los principios de economía circular y con los criterios RA4, CE 4.a, 4.c y 4.e del módulo.

### Menos carbono embebido
Cada dispositivo fabricado implica emisiones asociadas a extracción, transporte y ensamblaje.  
Si el software permite que un móvil dure uno o dos años más, se reduce significativamente el carbono embebido asociado a la fabricación de nuevos dispositivos.

---

## Tecnologías Utilizadas
- HTML5  
- CSS3 nativo  
- JavaScript nativo  
- Sin frameworks, sin librerías externas  

---

## Referencias (IEEE)

[1] W3C, “Web Sustainability Guidelines (WSG) 1.0,” 2023.  
[2] Green Software Foundation, “Green Software Practitioner Course,” 2024.  
[3] R. Verdecchia et al., “Green IT and Green Software Engineering: A Systematic Mapping Study,” arXiv:2102.04945, 2021.

---

## Defensa del MVP

Puntos clave para la presentación:

- La web ahora pesa diez veces menos  
- Se han eliminado todas las dependencias innecesarias  
- El diseño sigue siendo atractivo sin sacrificar sostenibilidad  
- El MVP ahora es coherente con el mensaje “Salvemos el Planeta”
  

---

## Autor
Pablo — Especialista en Sostenibilidad TIC (GreenTech Solutions)
