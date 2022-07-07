# Trabajo Final Coderhouse Comisión 20645

Aplicación eCommerce Backend que implementa un servidor de aplicación basado en la plataforma Node.js 
y el módulo express.

## Base routes

## Producto: /api/productos

#### GET: '/' 
Lista todos los productos disponibles.
#### GET: '/:id' 
Muestra un producto por su id (disponible para usuarios y administradores).
#### POST: '/' 
Para incorporar productos al listado (disponible para administradores).
#### PUT: '/:id' 
Actualiza un producto por su id (disponible para administradores).
#### DELETE: '/:id' 
Borra un producto por su id (disponible para administradores).

## Carrito: /api/carrito

#### POST: '/' 
Crea un carrito y devuelve su id.
#### DELETE: '/:id' 
Vacía un carrito y lo elimina.
#### GET: '/:id/productos' 
Me permite listar todos los productos guardados en el carrito.
#### POST: '/:id/productos/:id_prod' 
Para incorporar productos al carrito por su id de carrito y de producto.
#### DELETE: '/:id/productos/:id_prod' 
Eliminar un producto del carrito por su id de carrito y de producto.