# Huila Extremo & Ancestral

Landing page desarrollada con HTML5, Tailwind CSS v4 y JavaScript puro para una agencia de ecoturismo local del Huila, Colombia.

## Bitácora de Prompts (Iteraciones con IA)

| # | Prompt de ajuste enviado | Problema que buscaba resolver | Resultado obtenido | ¿Funcionó? |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Ajusta el menú móvil para que se cierre automáticamente al hacer clic en cualquier enlace de navegación. | El menú hamburguesa quedaba abierto tapando la pantalla en celular tras elegir una sección. | Se agregó un evento `click` a `.mobile-link` que añade la clase `hidden`. | Sí |
| 2 | Bloquea las fechas anteriores al día de hoy en el campo de fecha del formulario. | El usuario podía seleccionar fechas en el pasado para reservar un tour. | Se configuró el atributo `min` dinámicamente con JavaScript. | Sí |
| 3 | Haz que al hacer clic en "Reservar" dentro de una tarjeta se seleccione ese destino en el formulario. | Mejorar la experiencia de usuario evitando que el visitante busque el plan otra vez en el `<select>`. | Se vinculó cada botón de tarjeta con el `value` del select de planes. | Sí |
| 4 | Guarda la preferencia de modo claro o modo oscuro en `localStorage`. | Al recargar la página el sitio volvía siempre al modo claro. | El tema elegido persiste al actualizar el navegador. | Sí |
| 5 | Agrega un contador que muestre cuántos planes aparecen visibles al usar los botones de filtro. | Dar retroalimentación visual clara al filtrar por Aventura, Cultura o Naturaleza. | Se muestra el total actualizado sobre la cuadrícula de tarjetas. | Sí |
