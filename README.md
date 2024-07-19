<h1>Pizza Sales Analytics</h1>
<p>Este proyecto que consiste en dos (2) Dashboards en Power BI y Excel, es totalmente hecho por mí, es decir que no es un proyecto guiado como el de Semana Power BI Imparable
que recreé los Dashboards que otra persona hizo, no, este me di a la tarea de hacerlo todo yo sola. Lo primero que hice fue buscar un dataset en Kaggle y el turno fue para "Pizza Sales Dataset" del usuario Saher Muhamed, este es el dataset: https://www.kaggle.com/datasets/nextmillionaire/pizza-sales-dataset</p>
<p>En palabras del mismo, la información que contiene dicho dataset es: "Este conjunto de datos contiene información detallada sobre los pedidos de pizza, incluidos detalles sobre las variantes de pizza, cantidades, precios, fechas, horas y detalles de categorización:"</p>
<ul>
    <li><strong>pizza_id:</strong> un identificador único asignado a cada variante de pizza distinta disponible para realizar pedidos.</li>
    <li><strong>order_id:</strong> un identificador único para cada pedido realizado, que vincula a varias pizzas.</li>
    <li><strong>pizza_name_id:</strong> un identificador que vincula a un nombre específico de la pizza.</li>
    <li><strong>quantity:</strong> la cantidad de unidades de una variante de pizza específica solicitadas dentro de un pedido.</li>
    <li><strong>order_date:</strong> la fecha en la que se realizó el pedido.</li>
    <li><strong>order_time:</strong> la hora en que se realizó el pedido.</li>
    <li><strong>unit_price:</strong> el costo de una sola unidad de la variante de pizza específica.</li>
    <li><strong>total_price:</strong> el costo agregado de todas las unidades de una variante de pizza específica en un pedido.</li>
    <li><strong>pizza_size:</strong> representa el tamaño de la pizza (por ejemplo, pequeña, mediana, grande).</li>
    <li><strong>pizza_category:</strong> indica la categoría de la pizza, como vegetariana, no vegetariana, etc.</li>
    <li><strong>pizza_ingredients:</strong> proporciona una lista o descripción de los ingredientes utilizados en la pizza.</li>
    <li><strong>pizza_name:</strong> especifica el nombre de la variante de pizza específica solicitada.</li>
</ul>

<h2>En Power BI</h2>
<p>El primer Dashboard lo hice en Power BI y el análisis lo plasmé de la siguiente manera:</p>
<ul>
  <li><strong>Total Ventas y Número de Pedidos:</strong> Tarjeta (nueva)</li>
  NOTA: En un pedido hay varios productos, por eso cuando se usan las segmentaciones se puede pensar que los datos no coinciden.
  <li><strong>Nombre de pizza:</strong> Segmentación de datos</li>
  <li><strong>Total de ventas por nombre (Top 10):</strong> Gráfico de Columnas</li>
  NOTA: Solo se muestra el Top 10 ya que si se decide visualizar la segmentación de datos por nombre, hay 32 nombres de pizza, entonces para que no se vea tan cargado el gráfico.
  <li><strong>Total de ventas por categoría:</strong> Gráfico de Barras</li>
  <li><strong>Total de ventas por categoría:</strong> Gráfico Circular</li>
  <li><strong>Ingredientes:</strong> Nube de palabras (Complemento en Power BI)</li>
</ul>

![image](https://github.com/user-attachments/assets/6f03b2c0-ee88-40a5-aff1-b52a27cbf590)

<h2>En Excel</h2>
<p>El Dashboard quise recrearlo en Excel ya que estuve viendo algunos videos en Youtube y vi que también se usa Excel para hacer Dashboards, entonces lo hice como una forma de practicar más para crecer en todo este tema del Análisis y Visualización de Datos. El análisis lo plasmé de la misma
forma, solo que aquí hice algunos cambios en cuanto a los filtros y la nube de palabras. El archivo de Excel tiene 3 hojas: </p>
<ul>
  <li><strong>pizza_sales:</strong> Dataset en formato de tabla</li>
  <li><strong>Análisis:</strong> Tablas dinámicas y Gráficos Dinámicos</li>
  <li><strong>Dashboard:</strong> Como su nombre lo dice, el Dashboard producto de lo que está en la hoja de Análisis</li>
</ul>

<h3>Cambios</h3>
<ul>
  <li>Para las segmentaciones, le quité el de Nombre de Pizza ya que salía muy extensa la segmentación y no se podía convertir a lista desplegable como sí se puede
  en Power BI. Entonces le puse segmentaciones por Categoría y Tamaño.</li>
  <li>La nube de palabras la hice con el sitio web Voc AI https://www.voc.ai/es/tools/wordcloud y solo adjunté la imagen de esta.</li>
</ul>
<p>Lo demás, todo es igual.</p>

![image](https://github.com/user-attachments/assets/cb1272db-d1a6-45a5-b2ef-ce0b57f51597)

Por último, los dejo con esta imagen que quise pedirle a la IA para que relacionara la pizza con el análisis de datos y me entregó esta imagen que también está aquí en el repositorio:

![pizza_analytics](https://github.com/user-attachments/assets/7ce7c03a-3398-4251-beeb-6769c6d028eb)

¡Saludos!

