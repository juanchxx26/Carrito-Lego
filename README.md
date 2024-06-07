# Carrito-Lego

# Tienda Oficial de LEGO® Colombia

Este proyecto es una tienda en línea de productos LEGO® para el mercado colombiano. Ofrece una variedad de sets de construcción con un diseño responsivo y funcionalidad de carrito de compras.

## Estructura del Proyecto

- `index.html`: Archivo principal de la tienda.
- `css/style.css`: Estilos CSS para la tienda.
- `images/`: Carpeta que contiene las imágenes utilizadas en la tienda.
- `custom.js`: Archivo JavaScript para manejar la funcionalidad del carrito de compras.

## Funcionalidades

### Página Principal (`index.html`)
- **Encabezado**:
  - Incluye un mensaje promocional sobre envíos gratuitos en compras superiores a $299.000.
  - Logotipo de la tienda y un icono de carrito de compras que muestra la cantidad de productos añadidos.

- **Sección de Productos**:
  - Lista de productos disponibles con imágenes, títulos, precios y botones para agregar al carrito.

### Estilos (`css/style.css`)
- Define los estilos para la disposición de los productos, el encabezado y el carrito de compras.
- Asegura una experiencia de usuario coherente y atractiva visualmente.

### Imágenes (`images/`)
- Contiene imágenes de los productos, el logotipo de la tienda y el icono del carrito de compras.

### Funcionalidad de Carrito de Compras (`custom.js`)
- **Agregar Producto**:
  - Al hacer clic en "Agregar al carrito", el producto se añade al carrito.
  - Actualiza el total del carrito y la cantidad de productos.

- **Eliminar Producto**:
  - Permite eliminar productos del carrito y actualizar el total y la cantidad de productos.

- **Visualización del Carrito**:
  - Muestra el contenido del carrito con detalles del producto, precio y cantidad.
  - Calcula y muestra el precio total de los productos en el carrito.

#### Variables
- `allContainerCart`: Selecciona el contenedor de todos los productos.
- `containerBuyCart`: Selecciona el contenedor del carrito de compras.
- `priceTotal`: Selecciona el elemento que muestra el precio total.
- `amountProduct`: Selecciona el elemento que muestra la cantidad de productos en el carrito.

#### Funciones
- `loadEventListenrs()`: Carga los eventos para agregar y eliminar productos.
- `addProduct(e)`: Agrega un producto al carrito.
- `deleteProduct(e)`: Elimina un producto del carrito.
- `readTheContent(product)`: Lee el contenido del producto seleccionado y lo agrega al carrito.
- `loadHtml()`: Carga y actualiza el HTML del carrito.
- `clearHtml()`: Limpia el HTML del carrito.

## Cómo Usar

1. Clonar el repositorio:

    ```sh
    git clone https://github.com/tu-usuario/tu-repositorio.git
    ```

2. Navegar al directorio del proyecto:

    ```sh
    cd tu-repositorio
    ```

3. Abrir `index.html` en un navegador web:

    ```sh
    open index.html
    ```

## Capturas de Pantalla

### Página Principal
![Página Principal](./images/screenshot-main.png)

### Carrito de Compras
![Carrito de Compras](./images/screenshot-cart.png)

## Créditos

- Imágenes y productos de LEGO®.
- Diseño y desarrollo por [Tu Nombre](https://github.com/tu-usuario).

## Licencia

Este proyecto está licenciado bajo la [MIT License](./LICENSE).
