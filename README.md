# Project 3

Toque personal: Historial de pedidos para el usuario.

# Pizza

 ¡Muy bien, es momento de realmente construir nuestra aplicación web! Aquí están los requerimientos:

    - Menu: Tu aplicación web deberá soportar todos los elementos del menú disponibles para Pinocchio's Pizza & Subs (un lugar popular de pizzas en Cambridge). 
    Está en tu cuenta, basado en analizar el menú y los varios tipos de elementos ordenados (pequeño vs grande, coberturas, adicionales, etc) para 
    decidir cómo construir tus modelos para representar mejor la información. 
    Agrega tus modelos a orders/models.py, realiza las migraciones de archivos necesarias, y aplicar esas migraciones.
    
    - Agregando Items: Usa Django Admin, Administradores del sitio (para los dueños del restaurante) que deberán ser capaz de agregar, actualizar y remover ítems en el menú. 
    Agrega todos los ítems desde el menú de Pinocchio en tu base de datos usando ya sea el Admin UI o ejecutando comandos Python en el shell de Django.
    
    - Registro, Login, Logout: Usuarios del sitio (clientes) deberán ser capaces de registrarse para tu aplicación web con un nombre de usuario, contraseña, primer nombre, apellido, y su dirección email. 
    Los clientes deberán luego ser capaz de acceder y salir de tu sitio web.
    -Carrito de Compras: Una vez que accedan, los usuarios deberán ver una representación del menú del restaurante, donde ellos puedan agregar ítems (según con coberturas o extras, si es apropiado) a su “carrito de compras” virtual. El contenido de las compras deberán ser guardadas incluso si el usuario cierra la ventana, o sale y vuelve acceder de nuevo.
    
    - Colocar una Orden: Una vez que al menos esté un ítem en el carrito de compras del usuario, ellos deberán ser capaces de colocar una orden, donde el usuario se le pregunta si confirma los ítems en el carrito de compras, y el total (¡no necesitas preocuparte sobre impuestos!) antes de colocar una orden.
    -Ver Órdenes: Los Administradores del sitio deberán tener acceso a una página donde ellos puedan ver cualquiera de las órdenes que ya se hayan solicitado.
    
    - Toque Personal: Agregar al menos una funcionalidad adicional de tu elección a la aplicación web. Posibles inclusiones: permitir a los Administradores del sitio de marcar las órdenes como completadas y permitir a los usuarios el ver el estado de sus órdenes pendientes o las completadas, integrándose con la API Stripe para permitirle a los usuarios usar en realidad una tarjeta de crédito para realizar una compra durante la facturación, o soportar el envío de confirmaciones email a los usuarios una vez que sus compras estén completas. Si necesitas usar cualquier credencial (como contraseñas o credenciales API) para tu toque personal, asegúrate de no guardar cualquiera de esas credenciales en tu código fuente, ¡es mejor usar variables de entorno!
    
    - En README.md, incluye un pequeño escrito describiendo tu proyecto, qué es lo contiene en cada archivo que hayas creado o modificado, y (opcionalmente) cualquier información adicional que el Staff debería saber sobre tu proyecto. También, incluye una descripción de tu toque personal y qué es lo que escogiste añadir al proyecto.
    
    - Si has agregado paquetes de Python que deban ser instalados para ejecutar tu aplicación web, asegúrate de agregarlos a requirements.txt.


