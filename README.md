Sabor Local

Aplicación Android de reseñas de restaurantes desarrollada para la asignatura Aplicaciones Móviles para IoT (TI3V42), correspondiente a la Evaluación Sumativa N°1 (ES1: Interfaz de la app) en INACAP Sede Puente Alto.

Nota de privacidad y alcance: Este proyecto corresponde a la capa de interfaz y recursos de la app con datos de ejemplo ficticios. No contiene RUT, correos personales, teléfonos reales ni credenciales/claves sensibles.

Descripción General

Sabor Local permite explorar, registrar, consultar y gestionar reseñas de locales gastronómicos, además de contar con una pantalla dedicada a sugerencias de recomendación.

Pantallas implementadas (6 Activities y Layouts)

Login (LoginActivity / activity_login.xml): Identidad visual con logotipo, nombre de la app, campos de correo y contraseña, opción de recordar y botón de ingreso.

Registro (RegistroActivity / activity_registro.xml): Campos de registro, confirmación de contraseña, selector de preferencia gastronómica (RadioGroup), aceptación de términos y botón de creación de cuenta.

Lista (ListaActivity / activity_lista.xml): Encabezado con acciones y listado desplazable (ScrollView) con reseñas de ejemplo (por ejemplo: La Picada de Ñuñoa, Trattoria Bella y Sushi Norte).

Agregar (AgregarActivity / activity_agregar.xml): Formulario desplazable (ScrollView) para crear una nueva reseña (nombre del restaurante, tipo de comida, comuna, puntaje del 1 al 5, comentario y botón para guardar), con áreas táctiles de al menos 48dp, autofillHints y contraste ajustado en el botón de volver.

Detalle (DetalleActivity / activity_detalle.xml): Visualización completa de una reseña con información del local, valoración, comentario, marcador de favorito y acciones para editar o eliminar.

IA (IaActivity / activity_ia.xml): Entrada de preferencia o antojo, botón para solicitar recomendaciones y área de respuesta con texto de ejemplo.

Recursos, Tema e Identidad Visual

Textos y accesibilidad (res/values/strings.xml): Centralización de textos visibles, hint y contentDescription, además del nombre de la aplicación (Sabor Local).

Colores y tema (res/values/colors.xml, res/values-night/colors.xml, res/values/themes.xml): Paleta semántica por función y soporte de modo claro y modo oscuro.

Estilos reutilizables: Estilos propios aplicados en los layouts de la aplicación.

Ícono adaptativo propio: Generado mediante Asset Studio a partir de logo_sabor_local.webp con color de fondo #FBF3E4 y recursos en res/mipmap-* y res/values/ic_launcher_background.xml.