
# Delys Nort Snack
=====================
:sparkles:  :heart: **Bienvenidos a Delys Nort Snack** :heart:  :sparkles:

## Sobre nosotros
---------------
**Nuestra historia**
Delys Nort Snack es una empresa dedicada a la venta de snacks de alta calidad y variedad. Nuestra misión es brindar a nuestros clientes una experiencia de compra única y satisfactoria.

**Nuestros valores**
:heart: **Calidad**: ofrecemos solo los mejores snacks para nuestros clientes.
:smile: **Servicio**: nuestro equipo de atención al cliente está siempre listo para ayudarte.
:gift: **Variedad**: tenemos una amplia selección de snacks para todos los gustos.

## Productos
------------

### Snacks salados
#### :fries: :peanuts: **Snacks clásicos**

* ofrecemos una amplia variedad de snacks salados, desde clásicos como papas fritas y cacahuetes hasta opciones más gourmet como snacks de queso y cebolla.

### Snacks dulces
#### :cake: :chocolate: **Dulces deliciosos**

* nuestros snacks dulces son perfectos para aquellos con un dulce tooth. Desde galletas y brownies hasta frutas secas y chocolates.

### Snacks saludables
#### :apple: :carrot: **Opciones saludables**

* también ofrecemos opciones saludables para aquellos que buscan una alternativa más nutritiva. Nuestros snacks saludables incluyen opciones como frutas frescas, nueces y semillas.

## BASE DE DATOS
------------
##Tablas
carrito

id_carrito (Clave primaria): Identificador único para cada carrito.
Campos: id_usuario, fecha_creacion.
carrito_productos

id_carrito_producto (Clave primaria): Identificador único para cada producto en el carrito.
Campos: id_carrito, id_producto, cantidad.
detalle_pedidos

id_detalle_pedido (Clave primaria): Identificador único para cada detalle de pedido.
Campos: id_pedido, id_producto, cantidad, precio_unitario.
historial_ordenes

id_historial (Clave primaria): Identificador único para cada registro del historial de órdenes.
Campos: id_usuario, id_pedido, estado_anterior, estado_nuevo, fecha_modificacion.
pedidos

id_pedido (Clave primaria): Identificador único para cada pedido.
Campos: id_usuario, fecha_pedido, total, estado.
productos

id_producto (Clave primaria): Identificador único para cada producto.
Campos: nombre_producto, descripcion, precio, stock, imagen_url.
roles

id_rol (Clave primaria): Identificador único para cada rol.
Campos: nombre_rol.
trabajadores

id_trabajador (Clave primaria): Identificador único para cada trabajador.
Campos: id_usuario, puesto, salario.
usuarios

id_usuario (Clave primaria): Identificador único para cada usuario.
Campos: nombre, correo, contrasena, direccion, fecha_registro.
usuario_roles

id_usuario_rol (Clave primaria): Identificador único para cada relación usuario-rol.
Campos: id_usuario, id_rol.



### Servicio al cliente
#### :phone: :email: **Atención al cliente**

* nuestro equipo de atención al cliente está disponible para ayudarte con cualquier pregunta o inquietud que tengas.

## Contacto
------------

### Dirección
#### :truck: **Visítanos**

* [inserta dirección]

### Teléfono
#### :phone: **Llámanos**

* [inserta teléfono]

### Correo electrónico
#### :email: **Escríbenos**

* [inserta correo electrónico]

### :computer: Redes sociales
#### :facebook: :instagram: :twitter: **Síguenos**

* [inserta enlaces a redes sociales]

## ¡Gracias por visitarnos!
===============

:heart: **Esperamos verte pronto en Delys Nort Snack** :heart:
