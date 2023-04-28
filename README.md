
# API de Tienda en JavaScript con Express
Este proyecto es una API de tienda en JavaScript que utiliza el marco de trabajo Express. La API permite a los clientes ver productos, agregar productos al carrito y realizar pedidos.

## Comenzando
Para comenzar a utilizar la API, sigue los siguientes pasos:

1. Clona este repositorio en tu computadora usando el siguiente comando en la terminal:

```
git clone https://github.com/tunombredeusuario/aqui-va-el-nombre-del-repositorio.git
```
2. Navega al directorio del proyecto en la terminal:

```
cd aqui-va-el-nombre-del-repositorio 
```

3. Instala las dependencias necesarias utilizando el siguiente comando:

```
npm install
```

4. Crea un archivo .env en la raíz del proyecto y agrega las siguientes variables de entorno:

```
PORT=3000
DATABASE_URL=tu-url-de-mongodb
```

5. Inicia la API utilizando el siguiente comando:

```
npm start
```

6. La API estará disponible en http://localhost:3000.

## Endpoints
La API tiene los siguientes endpoints:

* ` GET /productos: ` devuelve una lista de todos los productos disponibles.
* ` GET /productos/:id: ` devuelve los detalles de un producto específico.
* ` POST /carrito: ` agrega un producto al carrito de compras.
* ` GET /carrito: ` devuelve una lista de los productos en el carrito de compras.
* ` DELETE /carrito/:id: ` elimina un producto del carrito de compras.
* ` POST /pedido: ` realiza un pedido con los productos en el carrito de compras.

## Contribuyendo
Si deseas contribuir a este proyecto, haz un fork del repositorio y envía una pull request con tus cambios. Antes de hacerlo, asegúrate de seguir las pautas de contribución del proyecto.

## Licencia
Este proyecto está licenciado bajo la Licencia MIT.
