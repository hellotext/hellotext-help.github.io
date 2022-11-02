Una de las técnicas de marketing más poderosas es la capacidad de rastrear lo que hacen tus clientes cuando interactúan con tu marca, ya sea en tu sitio o tienda. El seguimiento de las acciones de tus clientes es tan importante para generar informes como para llegar a ellos de manera más precisa con promociones y ventas activas por parte de tu equipo.

Uno de los aspectos clave que hace que Hellotext sea único es su capacidad para rastrear fácilmente todas las acciones importantes que realizan tus clientes sin importar cual sea su origen: por ejemplo lo que hacen en tu eCommerce, tu comercio físico o en cualquier otro lugar.

## Comprendiendo las acciones

Las acciones son las actividades genéricas que realizan tus clientes.

Están agrupados por su tipo de acción y separados por un punto.

Por ejemplo, ejemplos de acciones son:

### Acciones del carrito

* `cart.added` Se agregó un artículo al carrito.
* `cart.removed` Se eliminó un artículo del carrito.

### Ordenar acciones

* `order.placed` Se ha realizado el pedido.
* `order.confirmed` Confirmaste el pedido.
* `order.cancelled` El pedido ha sido cancelado por tí o tú cliente.
* `order.shipped` El pedido ha sido enviado a tu cliente.

### Acciones del producto

* `product.purchased` Se ha comprado un producto.
* `product.viewed` Se ha visto una página de producto.

### Acciones de cupones

* `coupon.redeemed` Un cliente canjeó un cupón.

### Acciones de reembolso

* `refund.requested` Un cliente solicitó un reembolso.
* `refund.received` Realizaste un reembolso a su cliente.

### Acciones de vistas de página

* `page.viewed` Una página fue vista por un cliente.

### Acciones de la aplicación

* `app.install` Se instaló una aplicación.
* `app.remove` Se eliminó una aplicación.
* `app.spent` Un cliente gastó en una aplicación.

### Acciones de formulario

* `form.completed` El cliente completó un formulario.

### Acciones personalizadas

Es posible crear tus propias acciones definidas directamente usando la API. Por ejemplo:

* `formulario_de_registro.completado`
* `tienda_fisica.pago`
* `evento.asistio`

Obtén más información en **[Referencia de API para acciones](https://www.hellotext.com/api#actions)**.

## Comprender los eventos

Un evento es el objeto que crea una relación entre una acción y el suscriptor en un momento determinado.

Es el objeto que se crea cuando realizas un seguimiento de una acción de un cliente.

## Maneras de rastrear eventos

* Usando una de las integraciones como Mercado Libre.
* Utilizando la librería de Javascript.
* Mediante la API.

## Seguimiento con integraciones

### Mercado Libre

Si vendes en Mercado Libre, rastreas las compras de tus clientes automáticamente.

Simplemente conecta tu cuenta de Mercado Libre en pocos clics y comenzarás a rastrear los siguientes eventos de inmediato:

* `order.confirmed` Has confirmado el pedido.
* `order.shipped` El pedido ha sido enviado a tu cliente.
* `order.cancelled` El pedido ha sido cancelado por tí o tú cliente.
* `refund.requested` Un cliente solicitó un reembolso.
* `refund.received` Realizaste un reembolso a su cliente.

## Seguimiento de eventos programáticamente

### Seguimiento con Javascript

Para realizar un seguimiento de los eventos del lado del cliente, puedes usar la libreria de javascript **[Hellotext.js](https://github.com/hellotext/hellotext.js)**.

Consulta el repositorio de Github en **[hellotext/hellotext.js](https://github.com/hellotext/hellotext.js)** para ver las últimas instrucciones de instalación y configuración.

### Seguimiento mediante la API

Obtén más información en **[Referencia de API para seguimiento](https://www.hellotext.com/api#tracking)**.