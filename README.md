Sabor Local es una aplicación diseñada para descubrir, registrar y gestionar reseñas de restaurantes locales preferidos, integrando además recomendaciones personalizadas mediante IA.


Entorno y Tecnologías
IDE: Android Studio (Versión Otter 2025.2.1)

Lenguaje: Kotlin y XML (Layouts escritos a mano en vista Split)

Diseño UI: Material 3 (Compatible con Modo Claro y Modo Oscuro)

Control de versiones: Git y GitHub (https://github.com/Saintkirk/SaborLocal)

Estructura de Pantallas (Evaluación Sumativa N°1)
Login (activity_login.xml): Acceso seguro con enmascaramiento de contraseña (textPassword) y opción para recordar sesión.

Registro (activity_registro.xml): Creación de cuenta con validación de contraseña, selección de preferencia gastronómica (RadioGroup) y aceptación de términos.

Lista (activity_lista.xml): Visualización de reseñas registradas dentro de un ScrollView con barra superior de navegación.

Agregar Reseña (activity_agregar.xml): Formulario completo con selección de tipo de comida (Spinner) y puntaje (RadioGroup).

Detalle (activity_detalle.xml): Vista completa de la reseña seleccionada con opciones para editar, eliminar o marcar como favorita.

Recomendaciones IA (activity_iaactivity.xml): Interfaz de consulta interactiva con área de respuesta adaptada.