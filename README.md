# Simulador de los Tres Cerebros – Comida Saludable

## Descripción del proyecto

Este proyecto es una herramienta educativa interactiva desarrollada para la asignatura **Semiótica de la Imagen** de la Universidad Tecnológica del Perú. Su objetivo es demostrar cómo la **teoría de los tres cerebros** de Paul MacLean –reptiliano, límbico y neocórtex– se aplica en el diseño de una pieza gráfica publicitaria: un flyer promocional de **comida saludable**.

El usuario puede explorar los elementos visuales del flyer, comprender qué mensajes subconscientes activa cada capa cerebral y poner a prueba sus conocimientos mediante un cuestionario. La interfaz combina una estética fresca y saludable (colores verdes y amarillos) con una lógica de capas superpuestas que permite visualizar cómo cada cerebro procesa distintos estímulos.

## Contexto académico

- **Curso:** Semiótica de la Imagen · 2026 · Semana 7  
- **Docente:** Mg. Mario Quiroz  
- **Institución:** Universidad Tecnológica del Perú  
- **Tema:** Aplicación de la teoría de los tres cerebros al diseño gráfico publicitario.

## Funcionalidades principales

- **Flyer interactivo con capas:** el diseño se compone de tres imágenes PNG superpuestas:
  - `REPTILIANO.png` (fondo): fotografía de comida, llamado "¡Pide hoy!" y fondo amarillo. Activa el instinto de supervivencia.
  - `LIMBICO.png` (capa intermedia): promoción de jugo de regalo, slogan "SABOR & SALUD", colores verdes. Genera emociones y vínculo afectivo.
  - `NEOCORTEX.png` (capa superior): números de contacto (WhatsApp/teléfono) y argumento racional "Comer bien ya no es una excusa". Proporciona información lógica.

- **Botones de selección de cerebro:** al hacer clic en *Reptiliano*, *Límbico* o *Neocórtex*, la capa correspondiente se vuelve nítida mientras las otras se desenfocan u ocultan. El panel derecho muestra información detallada sobre ese cerebro:
  - Elemento gráfico asociado.
  - Mensaje subconsciente (p. ej., *“Alimento disponible, actúa ahora”*).
  - Psicología subyacente.
  - Pregunta que responde (p. ej., *«¿Tengo hambre?»*).
  - Aplicación práctica en diseño publicitario.

- **Panel informativo dinámico:** se actualiza al instante según la capa seleccionada, con colores distintivos para cada cerebro (rojo para reptiliano, verde para límbico, azul para neocórtex).

- **Botones de control inferior:**
  - **🔆 VISTA COMPLETA NÍTIDA:** muestra todas las capas sin desenfoque, permitiendo apreciar el diseño global del flyer.
  - **🔄 RESTABLECER DESENFOQUE:** vuelve al estado de enfoque del último cerebro activo.

- **Formulario de datos del estudiante:** campos para **Nombre y Apellido** y **Correo Electrónico**, ubicados al inicio del cuestionario.

- **Cuestionario interactivo:** cuatro preguntas de opción múltiple que evalúan la comprensión de la teoría aplicada al flyer. Al finalizar, se muestra el número de aciertos y un mensaje de retroalimentación.

- **Botón de envío al docente:** al hacer clic en **✉️ Enviar resultados al docente**, se genera un correo electrónico dirigido a `c12139@utp.edu.pe` con los datos del estudiante y el resultado del cuestionario, facilitando la entrega de la actividad académica.

## Tecnologías utilizadas

- HTML5, CSS3 y JavaScript (ES6) puros, sin librerías externas.
- Diseño responsivo, adaptable a distintos tamaños de pantalla.
- Uso de imágenes PNG con transparencia para la superposición de capas.
- Estética de comida saludable con paleta de colores verdes, amarillos y tonos tierra.

## Instrucciones de uso

1. **Abrir el archivo:** descargue o clone el repositorio y abra `index.html` en cualquier navegador moderno (Chrome, Firefox, Edge, etc.).
2. **Explorar las capas:**
   - Haga clic en los botones superiores (*Reptiliano*, *Límbico*, *Neocórtex*) o directamente sobre las imágenes del flyer.
   - Observe cómo se desenfocan las capas no seleccionadas y cómo cambia la información en el panel derecho.
3. **Activar vista completa nítida:** pulse el botón **🔆 VISTA COMPLETA NÍTIDA** para ver todas las capas nítidas a la vez. A partir de ahí, puede volver a seleccionar cualquier cerebro para recuperar el efecto de enfoque selectivo.
4. **Restablecer desenfoque:** use el botón **🔄 RESTABLECER DESENFOQUE** para volver al estado de enfoque del último cerebro activo.
5. **Completar datos del estudiante:** ingrese su nombre y correo electrónico en los campos correspondientes.
6. **Responder el cuestionario:** marque una opción por cada pregunta y presione **COMPROBAR RESPUESTAS**. Recibirá un resultado inmediato.
7. **Enviar al docente:** una vez obtenido el resultado, haga clic en **✉️ Enviar resultados al docente** para abrir su cliente de correo con la información prellenada. Solo debe enviar el mensaje.

## Notas importantes

- Las imágenes (`REPTILIANO.png`, `LIMBICO.png`, `NEOCORTEX.png`) deben ubicarse en la misma carpeta que el archivo `index.html`. Si faltan, se mostrará un patrón de fondo de respaldo.
- Se recomienda utilizar imágenes PNG con transparencia para garantizar la correcta superposición de las capas.
- La capa `NEOCORTEX.png` tiene el z-index más alto para que su texto (teléfono, WhatsApp) sea siempre legible, incluso cuando está debajo de otras capas en la vista completa.

## Créditos

- **Docente:** Mg. Mario Quiroz  
- **Curso:** Semiótica de la Imagen · 2026 · Semana 7  
- **Universidad Tecnológica del Perú**  
- Basado en la teoría de los tres cerebros de **Paul MacLean**.

## Licencia

Este proyecto es de uso educativo y libre distribución para fines académicos. Queda prohibido su uso con fines comerciales sin autorización expresa de los autores.