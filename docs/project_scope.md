# Project Scope: Eidon 

## 1. Visión General
**Eidon** es una bitácora digital personal diseñada para centralizar, organizar y calificar el consumo de medios (películas, libros, podcasts, música y artículos). El objetivo es que el usuario deje de preguntarse "¿en qué capítulo iba?" o "¿cómo se llamaba aquel documental?" y tenga un historial estético y funcional de su vida mediática.

## 2. Audiencia Objetivo
- Entusiastas de la cultura pop y el aprendizaje continuo.
- Personas que consumen contenido en múltiples plataformas y pierden el rastro de lo que han visto/leído.
- Usuarios que disfrutan de las estadísticas personales y la organización.

## 3. Funcionalidades Clave (MVP - Producto Mínimo Viable)
- **Registro de Entrada:** Formulario para añadir título, tipo de media (Video, Audio, Lectura), fecha y estado.
- **Estados de Consumo:**
  - *Pendiente*: Contenido por empezar.
  - *En progreso*: Consumo actual.
  - *Completado*: Contenido finalizado.
  - *Abandonado*: Contenido que no se terminó.
- **Sistema de Rating:** Escala de 1 a 5 estrellas para valoración personal.
- **Filtros Rápidos:** Visualizar solo "Libros" o solo contenido "En progreso".

## 4. Funcionalidades Futuras (Backlog)
- **Dashboard de Estadísticas:** Gráficos que muestran el porcentaje de media consumida por mes.
- **Integración con APIs:** Autocompletado de datos desde IMDb o Google Books.
- **Modo Social:** Compartir listas de recomendados con otros usuarios.

## 5. Reglas de Negocio
- Un registro no puede estar en dos estados al mismo tiempo.
- Cada entrada debe tener obligatoriamente un "Tipo de Media" asignado.
- La privacidad es prioridad: el contenido es privado por defecto.