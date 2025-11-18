button de agregar al carrito: //*[@id=":R4pj2kckp7te:"]

button preguntar: //*[@id=":R3ikab4p7te:"]

img de producto: //*[@id="ui-pdp-main-container"]/div[1]/div/div[7]/div/div/div/div/div/div[1]/a/img

img: //*[@id="ui-pdp-main-container"]/div[1]/div/div[2]/div[1]/div/div/div/span[2]/figure/img

label: //*[@id="picker-label-COLOR"]

label titulo producto: //*[@id="ui-pdp-main-container"]/div[1]/div/div[2]/div[2]/div[1]/div/div[2]/h1

button ingresar : //*[@andes-button__content]document.querySelector("#primary_action > span").click();

boton seguir: //*[@id=":r14:"]/span

link medio de pagos: //*[@id="ui-pdp-price__payments-link"]

link devolucion: //*[@id="buybox-form"]/ul/li[1]/div/div/div/div/div/div/a

------------------------------------------------------------------------------------------------------------------------------

Caso de Uso y Casos de Prueba - Mercado Libre
1. Caso de Uso: Búsqueda de Producto
Actor(es): Usuario visitante
Descripción: El usuario busca un producto en Mercado Libre.
Flujo Principal
1.	1. El usuario ingresa a la página de Mercado Libre.
2.	2. El sistema muestra la barra de búsqueda.
3.	3. El usuario escribe un término de búsqueda.
4.	4. El usuario hace clic en el botón Buscar.
5.	5. El sistema procesa la búsqueda.
6.	6. El sistema muestra resultados relacionados.
Localizadores
- input[name='as_word']
- button[type='submit']
- img[class='ui-search-image']
- h2.ui-search-item__title
- span.andes-money-amount__fraction
- input[type='checkbox']
- label.ui-search-filter-name
- ol.ui-search-layout
- a.andes-pagination__link
- a.ui-search-link
Caso de Prueba: Búsqueda de Laptop
7.	1. Abrir Mercado Libre.
8.	2. Escribir 'Laptop' en el cuadro de búsqueda.
9.	3. Presionar el botón Buscar.
10.	4. Validar que aparezcan productos.
11.	5. Validar que cada producto tenga título.
12.	6. Validar que se muestre un precio.
