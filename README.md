# EcoCity - Gestión de Incidencias Urbanas

**EcoCity** es una solución móvil diseñada para fortalecer el vínculo entre los ciudadanos y su ayuntamiento. A través de una interfaz intuitiva basada en **Material Design**, permite reportar, gestionar y hacer seguimiento de incidencias en la vía pública de forma eficiente.

Este proyecto ha sido desarrollado para el módulo de **Desarrollo de Interfaces** (2º DAM).

---

## Autores
* **Félix Caballero Peña**
* **Miguel Ceballos Sánchez**

---

## Enlaces del Proyecto
* **Prototipo en Figma:** [Acceder al Prototipo Interactuable](https://www.figma.com/proto/zEWyhfruel0aKNhgebbJvt/EcoCity?node-id=0-1&t=6MdDGFAevaeLi9t6-1)
* **Presentación en Canva:** [Ver Presentación del Proyecto](https://github.com/mcs0056/EcoCity_Documentacion/blob/main/Canva-EcoCity.pdf))

---

## Descripción del Proyecto
EcoCity permite a los usuarios:
- **Reportar incidencias** con descripción, ubicación y archivos multimedia.
- **Visualizar estados** en tiempo real (Pendiente, En Proceso, Resuelta).
- **Comunicación directa** mediante un chat de soporte integrado.
- **Filtrado inteligente** para localizar avisos previos de forma rápida.

### Fundamentos de Diseño
- **Material Design:** Uso de componentes oficiales (FAB, Cards, TextFields).
- **Tipografía:** Inter (legible y jerarquizada).
- **Accesibilidad:** Contraste optimizado y feedback visual constante.

---

## Proceso de Diseño e Iteración (v1 -> v2)

Tras realizar pruebas de usabilidad con 5 usuarios externos, identificamos puntos de fricción críticos que fueron resueltos en la versión final:

| Problema Detectado (v1) | Mejora Implementada (v2) | Impacto |
| :--- | :--- | :--- |
| Inseguridad al escribir la contraseña | Botón de visibilidad (ojo) en Login | Seguridad y reducción de errores |
| Confusión ante listas vacías | Pantalla de estado vacío con ilustración/texto | Feedback comunicativo |
| Dificultad para localizar incidencias | Sistema de búsqueda y filtros | Eficiencia y ahorro de tiempo |
| Imposibilidad de retroceder en el chat | Botón de navegación "Atrás" | Control y libertad del usuario |
| Falta de control sobre el progreso | Botón de actualización de estado manual | Transparencia en la gestión |

---

## Estructura del Repositorio
El repositorio está organizado de la siguiente manera:

* `/figma`: Enlaces al archivo de diseño y prototipos v1 y v2.
* `/documentacion`: Documentación GUI detallada en formato PDF.
* `/pruebas_usabilidad`: Plan de pruebas, metodología y análisis de resultados.
* `/imagenes`: Capturas de pantalla.

---

## Herramientas Utilizadas
- **Figma:** Diseño de interfaz y prototipado de alta fidelidad.
- **Canva:** Presentación visual del proyecto.
- **GitHub:** Control de versiones y alojamiento de documentación.
- **Material Design 3:** Guía de estilos y componentes.

---

## Recursos Visuales e Imágenes

En esta sección se muestran las capturas de pantalla del flujo principal, comparando el **Prototipo v1 (Sin Retoques)** frente al **Prototipo v2 (Con Retoques)** tras aplicar las mejoras de usabilidad.

### Comparativa de Evolución (v1 vs v2)

| Pantalla | Versión Original (v1) | Versión Mejorada (v2) |
| :--- | :---: | :---: |
| **Inicio de Sesión** | [Ver v1](Imagenes/SinRetoques/InicioSesion.png) | [Ver v2](Imagenes/ConRetoques/InicioSesionRetoque.png) |
| **Menú de Incidencias** | [Ver v1](Imagenes/SinRetoques/IncidenciasMenu.png) | [Ver v2](Imagenes/ConRetoques/IncidenciasMenuRetoques.png) |
| **Detalle Incidencia** | [Ver v1](Imagenes/SinRetoques/Incidencia.png) | [Ver v2](Imagenes/ConRetoques/IncidenciaRetoques.png) |
| **Chat Multihilo** | [Ver v1](Imagenes/SinRetoques/ChatMultihilo.png) | [Ver v2](Imagenes/ConRetoques/ChatMultihiloRetoques.png) |
| **Soporte Técnico** | [Ver v1](Imagenes/SinRetoques/SoporteTecnico.png) | [Ver v2](Imagenes/ConRetoques/SoporteTecnicoRetoques.png) |

> [!TIP]
> Puedes encontrar todos los recursos gráficos brutos y exportaciones en las carpetas correspondientes dentro del directorio `/Imagenes`.
