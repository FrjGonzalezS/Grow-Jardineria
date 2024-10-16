# Proyecto Grow Jardinería 🌱

### Descripción
**Grow Jardinería** es una plataforma web diseñada para la gestión y venta de productos de jardinería, ofreciendo una interfaz amigable para que los usuarios puedan explorar y adquirir plantas, herramientas, y otros artículos relacionados con la jardinería. El sistema cuenta con un carrito de compras, un sistema de autenticación de usuarios, y funcionalidades administrativas para la gestión de productos.

### Tecnologías Utilizadas
- **Django**: Framework de Python utilizado para el desarrollo del backend, permitiendo una gestión eficiente de las operaciones del sistema.
- **Django REST Framework**: Implementado para crear una API que facilita la comunicación entre el frontend y el backend, permitiendo la consulta, creación y modificación de productos y usuarios.
- **HTML5 & CSS3**: Utilizados para diseñar la estructura y estilo de la interfaz de usuario, brindando una experiencia visual atractiva y fácil de usar.
- **Base de Datos**: El sistema utiliza una base de datos relacional para almacenar información de usuarios, productos y órdenes de compra.

### Funcionalidades Clave
1. **Gestión de Productos**: 
   - Los administradores pueden crear, modificar y eliminar productos de jardinería desde un panel dedicado. Estos productos incluyen detalles como nombre, precio, descripción, y fotos.
   - El sistema cuenta con formularios para la modificación de plantas (`form_mod_plantas.html`).

2. **Carrito de Compras**:
   - Los usuarios pueden añadir productos al carrito de compras desde la interfaz principal, con la posibilidad de revisar los artículos seleccionados antes de proceder al pago.
   - Se gestiona un resumen de los productos en el carrito, permitiendo la actualización y eliminación de productos directamente desde la interfaz de usuario.

3. **Sistema de Autenticación**:
   - Los usuarios pueden registrarse e iniciar sesión en la plataforma. Se incluyen páginas dedicadas para registro (`ingresar-registro.html`) e inicio de sesión (`ingresar.html`).
   - La autenticación está integrada con el backend de Django, asegurando un sistema seguro y escalable.

4. **API REST**:
   - La plataforma implementa una API basada en Django REST Framework para realizar las operaciones CRUD (Crear, Leer, Actualizar, Eliminar) en productos y usuarios.
   - La API permite que el frontend interactúe dinámicamente con los datos de los productos y los usuarios, mejorando la experiencia del usuario con tiempos de carga reducidos y respuestas en tiempo real.

5. **Interfaz de Usuario Amigable**:
   - Se implementa una interfaz atractiva y sencilla para que los usuarios puedan navegar fácilmente por el catálogo de productos y gestionar sus compras.
   - El diseño está optimizado con archivos CSS (`estilos.css`) para ofrecer una experiencia visual coherente en todas las páginas del sitio.

### Estructura del Proyecto
- **Backend**: Gestionado con Django y Django REST Framework, proporciona la lógica de negocio, las bases de datos y las API para el frontend.
- **Frontend**: Desarrollado con HTML y CSS para ofrecer una interfaz intuitiva, con plantillas como `index.html`, `carrito.html`, y `perfil_usuario.html`.
- **Bases de Datos**: Implementadas para almacenar información relevante sobre productos, usuarios y pedidos de compra.
