# Apuntes de R
<img src="" width="300" height="200" text-align: center></div>
<br>

Por Rober J

[![](https://img.shields.io/badge/@roberer_-white?style=for-the-badge&labelColor=blue&logo=Twitter&logoColor=white)](https://twitter.com/roberer_)[![](https://img.shields.io/badge/Portfolio-black?style=for-the-badge&logo=github)](https://roberer.github.io)[![](https://img.shields.io/badge/Roberto-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/robertojl)


## 馃О Comandos b谩sicos

<details>
  <summary><strong>Entorno de trabajo</strong></summary><br>
  
  <p>Obtener informaci贸n sobre una funci贸n:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
help('funci贸n')
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Seleccionar directorio de trabajo:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
setwd('ruta')
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Obtener directorio de trabajo:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
getwd()
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Obtener ruta de instalaci贸n de R:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
.libPaths()
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Mostrar lista de archivos del directorio de trabajo:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
list.files()
</pre></div>
  
 <br></details>
 
 <details>
  <summary><strong>Funciones estad铆sticas</strong></summary><br>
  
  <p class="has-text-align-left">R permite hacer toda clase de operaciones estad铆sticas con la informaci贸n que hayamos guardado como objeto mediante el uso de funciones. A continuaci贸n ten茅is resumidas algunas de las m谩s b谩sicas con las que trabajar:</p>



<p><strong>Sumar </strong>todos los valores que contenga un objeto:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
sum(objeto)
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Obtener el <strong>valor m谩ximo</strong> del objeto:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
max(objeto)
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Obtener el <strong>valor m铆nimo</strong> del objeto:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
min(objeto)
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Calcular la media</strong> de los valores del objeto:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
mean(objeto)
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Calcular la mediana</strong> de los valores del objeto:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
median(objeto)
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Calcular la desviaci贸n t铆pica</strong> de los valores del objeto:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
sd(objeto)

</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Generar un<strong> resumen estad铆stico</strong> del objeto:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
summary(objeto)

</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Redondear </strong>el valor o valores de un objeto. Por defecto redondea al entero superior a partir del 0.51 :</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
round(objeto)

</pre></div>
  
 <br></details>
 
 <details>
  <summary><strong>Gesti贸n de objetos</strong></summary><br>
  
  <p class="has-text-align-left">Las siguientes instrucciones sirven para operar a nivel b谩sico con los objetos en R: c贸mo crearlos, borrarlos u obtener informaci贸n de ellos.</p>



<p><strong>Crear un objeto</strong> guardando bajo un nombre todo lo que vaya despu茅s del signo &#8216;=&#8217; , desde una funci贸n a una tabla, un procedimiento, un resultado, shapefiles, etc. :</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
nombre_objeto = 
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Obtener un <strong>listado</strong> de los objetos creados:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
ls()
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Borrar </strong>un objeto:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
rm(objeto)
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Borrar </strong>todos los objetos de la sesi贸n:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
rm(list=ls())
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Liberar memoria</strong> del garbage collector:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
gc()
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Crear un rango</strong>, devolviendo en este caso una lista con todos los valores entre el 1 y el 10. Admite n煤meros negativos y el intervalo es siempre 1:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
1:10
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Crear un vector</strong>. Los vectores son colecciones de datos del mismo tipo, en este caso n煤meros enteros:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
c(5, 7, 8)
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Mostrar el tipo de valor</strong> del objeto. Puede ser entero (integer) o decimal (float):</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
str(objeto)
</pre></div>

  
 <br></details>
 
 <details>
  <summary><strong>Manejo de tablas</strong></summary><br>
  
  <p class="has-text-align-left">Funciones y argumentos b谩sicos para abrir archivos que contengan tablas, visualizarlas, editarlas y combinarlas.</p>



<p><strong>Abrir tabla</strong> dentro del directorio de trabajo en <strong>archivo .txt</strong> cuyos valores se separan por puntos y mostrando la cabecera:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
read.table('nombre.txt', header = TRUE, sep ='.')
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Abrir tabla</strong> dentro del directorio de trabajo en <strong>archivo .csv</strong> cuyos valores se separan por espacios y sin mostrar la cabecera:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
read.csv('nombre.csv', header = FALSE, sep = ',')
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Argumento</strong> de las funciones read. y write. que indica el <strong>s铆mbolo</strong> con el que se separan los valores en la tabla que vamos a abrir o guardar:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
sep = ''
sep = '.'
sep = ','
sep = '/'
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Argumento</strong> de las funciones read. y write. para indicar el <strong>caracter</strong> usado en los decimales de la tabla que vamos a abrir o guardar:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
dec = ','
dec = '.'
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Guardar</strong> la tabla abierta en un objeto llamado tabla1:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
tabla1 = read.csv(.....
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Visualizar</strong> la tabla guardada en el objeto tabla1:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
tabla1
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Obtener</strong> solo las 5 <strong>primeras filas</strong> de tabla1:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
head(tabla1, 5)
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Obtener</strong> solo las 24 <strong>煤ltimas filas</strong> de tabla1:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
tail(tabla1, 24)
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Crear o sobrescribir una tabla .txt</strong> en el directorio de trabajo con los valores del objeto tabla1, separ谩ndolos con espacios y mostrando nombres de filas:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
write.table(tabla1, 'nombre.txt', row.names = TRUE, sep = '')
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Crear o sobrescribir una tabla .csv</strong> en el directorio de trabajo con los valores del objeto tabla1 separ谩ndolos con comas:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
write.csv(tabla1, 'nombre.csv', sep = ',')
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Seleccionar</strong> <strong>columnas </strong>por su nombre:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
subset(tabla1, select = c(columna1,columna2))
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Seleccionar</strong> <strong>filas</strong> que contengan un valor espec铆fico en una columna:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
subset(tabla1, columna1 == 'Albacete')
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Seleccionar un valor indicando su posici贸n</strong> en la tabla. Dejar vac铆o para seleccionar filas o columnas enteras. Pueden usarse rangos para seleccionar trozos espec铆ficos:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
tabla1&#91;n潞fila,n潞columna]
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Seleccionar</strong> <strong>una columna</strong> de tabla1 indicando su nombre:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
tabla1$nombrecolumna
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Guardar columnas</strong> en objetos:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
col1 = tabla1$nombrecolumna1
col2 = tabla1$nombrecolumna2
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Combinar</strong> columnas guardadas en objetos en una nueva tabla:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
cbind(col1,col2) 
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Combinar</strong> <strong>tablas</strong> completas. Deben compartir nombres de columna para que encajen:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
rbind(tabla1,tabla2)
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Renombrar la columna</strong> de la posici贸n se帽alada:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
colnames(tabla1)&#91;n潞columna] = c(鈥榥ombre鈥?)
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Obtener una lista</strong> con los valores de la columna indicada <strong>ordenados</strong> de menor a mayor (por defecto):</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
sort(tabla1$nombrecolumna)
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Aplicar una funci贸n</strong> a todas las filas (sustituir margin por 1) o a todas las columnas (sustituir margin por 2):</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
apply(tabla1, margin, funci贸n)
</pre></div>


  
 <br></details>
 
## 馃搳 Crear gr谩ficos

<details>
  <summary><strong>Puntos</strong></summary><br>
  
  <p>La funci贸n plot() sirve para <strong>generar un gr谩fico de puntos</strong> indicando valores a partir de columnas para una 煤nica variable:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
plot(tabla$nombrecolumna)
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>A esta funci贸n se le puede a帽adir los siguientes <strong>argumentos</strong> para modificar su apariencia.</p>



<p>Argumento de la funci贸n plot() para <strong>cambiar el s铆mbolo</strong> usado para mostrar los puntos. Sustituir n por alg煤n n煤mero:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
pch = n
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Argumento de la funci贸n plot() en la que n indica el <strong>tama帽o de los puntos</strong>:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
cex = n 
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Argumento de plot() que funciona igual que col, solo que <strong>cambia el fondo</strong> de algunos s铆mbolos:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
bg = 'blue'
</pre></div>

  
 <br></details>
 
 <details>
  <summary><strong>L铆neas</strong></summary><br>
  
  <p>Funci贸n para <strong>generar un gr谩fico de l铆neas</strong> especificando el argumento type como 禄l禄:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
plot(tabla$nombrecolumna, type = ''l'')
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>A la funci贸n plot() se le puede a帽adir los siguientes <strong>argumentos</strong> para modificar su apariencia.</p>



<p>Argumento para <strong>cambiar el tipo de l铆nea:</strong></p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
lty = n
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Argumento para <strong>cambiar el grosor de la l铆nea:</strong></p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
lwd = n
</pre></div>

  
 <br></details>
 
 <details>
  <summary><strong>Barras</strong></summary><br>
  
  <p>Funci贸n para <strong>generar un histograma</strong> o gr谩fico de barras para una columna de una tabla:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
hist(tabla$columna)
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>N煤mero de cortes</strong> o barras que tendr谩 el histograma:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
breaks = n
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Argumento de la funci贸n hist() para<strong> establecer el color del borde de las barras</strong>. Funciona con nombres (en ingl茅s), n煤meros o <a rel="noreferrer noopener" href="https://color.adobe.com/es/create/color-wheel" target="_blank">c贸digos RGB</a>:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
border = 'red'
border = n
border = #DBD361
</pre></div>

  
 <br></details>
 
 <details>
  <summary><strong>Dispersi贸n</strong></summary><br>
  
  <p>Funci贸n para <strong>generar un gr谩fico de dispersi贸n</strong> a partir de dos variables distintas:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
plot(tabla$nombrecolumnaX, tabla$nombrecolumnaY)
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p><strong>Crear la recta de regresi贸n</strong> del gr谩fico de dispersi贸n:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
abline(lm(tabla$columna~tabla$columna))
</pre></div>

  
 <br></details>
 
  <details>
  <summary><strong>Dar formato</strong></summary><br>
  
  <p>En este apartado dejo una recopilaci贸n de argumentos que pod茅is usar para cambiar el aspecto de los gr谩ficos anteriores.</p>



<p>Argumentos de la funci贸n plot() para <strong>establecer l铆mites en los ejes</strong> <strong>del gr谩fico</strong>. n y z ser铆an sustituidos por los valores l铆mite.</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
xlim = c(n, z)
ylim = c(n, z)
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Argumento de la funci贸n plot() para <strong>establecer el color de los puntos, las l铆neas o las barras</strong>. Funciona con nombres (en ingl茅s), n煤meros o <a rel="noreferrer noopener" href="https://color.adobe.com/es/create/color-wheel" target="_blank">c贸digos RGB</a></p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
col = 'red'
col = n
col = #DBD361
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Argumentos de plot() para <strong>a帽adir t铆tulo al gr谩fico y nombres a los ejes</strong>:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
main = 't铆tulo'
xlab = 'texto'
ylab = 'texto'
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Funci贸n para <strong>a帽adir series de datos adicionales</strong> a un gr谩fico creado con plot() . Puede cambiarse su apariencia usando sus mismos argumentos (seg煤n sea l铆nea, punto o barra):</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
points(tabla$nombrecolumna)
lines(tabla$nombrecolumna)
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Funci贸n para <strong>agregar leyenda al gr谩fico</strong>. La posici贸n se indica con t茅rminos ingleses como 禄topleft禄 (arriba a a izquierda) y se usa un vector para indicar las series de datos que aparecer谩n representadas:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
legend( "posici贸n" , legend = c("Serie 1", ''Serie 2''))
</pre></div>


<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Argumentos de la funci贸n legend() para <strong>cambiar el color del texto y de los puntos</strong> de la leyenda:</p>


<div class="wp-block-syntaxhighlighter-code "><pre class="brush: r; title: ; notranslate" title="">
text.col =
pt.bg =
</pre></div>
  
 <br></details>
 
 ## 馃椇 Librer铆as geoespaciales

<details>
  <summary><strong>Importar librer铆as</strong></summary><br>
  
  <p>Cargar la <strong>librer铆a spatial</strong>:</p>



<pre class="wp-block-code"><code>library(sp)</code></pre>



<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Cargar la <strong>librer铆a maptools</strong>:</p>



<pre class="wp-block-code"><code>library(maptools)</code></pre>



<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Cargar la <strong>librer铆a raster</strong> para obtener funciones de tratamiento r谩ster:</p>



<pre class="wp-block-code"><code>library(raster)</code></pre>



<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Cargar la<strong> librer铆a RColorBrewer</strong>:</p>



<pre class="wp-block-code"><code>library(RColorBrewer)</code></pre>



<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Cargar la <strong>librer铆a gridExtra</strong>:</p>



<pre class="wp-block-code"><code>library(gridExtra)</code></pre>



<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Cargar la <strong>librer铆a ggplot2</strong> para dise帽ar layouts cartogr谩ficos de forma avanzada:</p>



<pre class="wp-block-code"><code>library(ggplot2)</code></pre>



<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Cargar la <strong>librer铆a gstat </strong>que permite hacer an谩lisis como kriging:</p>



<pre class="wp-block-code"><code>library(gstat)</code></pre>



<div style="height:20px;" aria-hidden="true" class="wp-block-spacer"></div>



<p>Cargar la <strong>librer铆a rgdal</strong> o data abstraction library:</p>



<pre class="wp-block-code"><code>library(rgdal)</code></pre>

  
 <br></details>
