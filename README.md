# Caso practico SQL Samantha Pineda

## Resultados del analisis 

--b.1. Encontrar el número de artículos en el menú: R= 32 artículos--

--b.2.1 ¿Cuál es el artículo menos caro? R= MIN= Edamame --

--b.2.2 ¿Cuál es el artículo más caro en el menú? R= MAX = Shrimp Scampi --

--b.3. ¿Cuántos platos americanos hay en el menú? R=6 --

--b.4. ¿Cuál es el precio promedio de los platos? R= 13.2859--

--c.Explorar la tabla “order_details” para conocer los datos que han sido recolectados--

--c.1  ¿Cuántos pedidos únicos se realizaron en total? R= 32--

--c.2. ¿Cuáles son los 5 pedidos que tuvieron el mayor número de artículos? R= 440 / 2675 / 3473 / 4305 / 443--

--c.3.1 ¿Cuándo se realizó el primer pedido? R= 2023-01-01 11:38:36--

--c.3.2 ¿Cuándo se realizó el último pedido? R= 2023-03-31 11:22:20--

--c.4 ¿Cuántos pedidos se hicieron entre el '2023-01-01' y el '2023-01-05'? R= 308--

--d) /* Usar ambas tablas para conocer la reacción de los clientes respecto al menú.--
-- Realizar un left join entre entre order_details y menu_items con el identificador item_id(tabla order_details) y menu_item_id(tabla menu_items).--

--e) Una vez que hayas explorado los datos en las tablas correspondientes y respondido las preguntas planteadas, realiza un análisis adicional utilizando este join entre las tablas--
--El objetivo es identificar 5 puntos clave que puedan ser de utilidad para los dueños del restaurante en el lanzamiento de su nuevo menú. Para ello, crea tus propias consultas y--
--utiliza los resultados obtenidos para llegar a estas conclusiones.--

--e.1 ¿Cuál es la comida que menos se vende?  R= Chicken Tacos = 123--

--e.2 ¿Cuál es la comida que más se vende?  R= Hamburger= 622--

--e.3 ¿Cuál categoria de comida es la más vendida? R= Asian = 3470--

--e.4 ¿Cuál categoria de comida es la menos vendida? R=American = 2734--

--e.5 ¿Cuál es la comida que da mayor ganancia? R=Korean Beef Bowl = 10554.60--

