
|Producto|Descripción|Persona encargada de la Investigación|
|:----|:---|:---|:---:| :---:|
|Almorzamos.com (desktop(web))| *Plataforma web que te muestra los paltos del día de diferentes restaurantes*
| *Trinidad Mejía* |
***
almorzamos,es una plataforma web que agrupa los diferentes platos del día de algunos restaurantes de Lima.

<center><img width="900" alt="Almorzamos" src="![plataforma almorzamos](https://user-images.githubusercontent.com/51333504/69842048-b94fd080-122f-11ea-844f-d0deda504a14.JPG)"></center>

Durante mucho tiempo el servicio en los restaurantes para poder realizar pedidos   ha sido la siguiente: Las personas van hacia el local y son atendidas por una persona que se encarga de tomar su pedido y luego de un tiempo servirlo.

Hoy en día esto representa un problema enorme porque, conlleva a una pérdida de tiempos y movimientos por parte del usuario .
Es por ello que ya se están creando las tecnologías  necesarias para solucionar este problema.


><br>*Según datos del [Yeeply](https://www.yeeply.com/blog/tendencias-desarrollo-apps-moviles-2019//https) [Economiatic]//economiatic.com/importancia-apps-moviles-empresas/), En la última década, las apps móviles se han posicionado como unas de las herramientas más eficaces para las empresas, especialmente en el campo del e-commerce. Y no es para menos, pues las aplicaciones facilitan la vida de los usuarios, promueven la interconectividad y mejoran la experiencia en la adquisición de productos y servicios.*
<br>


## Objetivos del proyecto

- validar el prototipo que tenemos y cómo podríamos mejorarlo para acercarnos más al cliente esperado.
- Optimizar el flujo propuesto para las funcionalidades de la plataforma web.

## Proceso 
<center><img width="900" alt="Almorzamos" src="[Proceso](https://user-images.githubusercontent.com/51333504/69841896-02535500-122f-11ea-9b18-7bc1535e8ec7.JPG)"
></center>

## 1. Investigación

### 1.1. Entrevistas a usuarios

La plataforma fue creada para usuarios cuyo centro laboral sea con  horarios de ofcinas, cuyos perfiles definí como el user target. Agende entrevistas con 5 usuarios entre 21 y 40 años que cumplan con estos características. 

>[**Problemas encontrados a nivel de usuario**][problems statemente](https://user-images.githubusercontent.com/51333504/69842096-f6b45e00-122f-11ea-9914-4faea82a2629.JPG)<br>
Luego de realizarlas identificamos los siguientes problemas a nivel de usuario:

- Todos los usuarios de telefonía móvil tienen al menos 1 app relacionado a la comida instalado.
- Las aplicaciones que más usan son WhatsApp, Instagram, Netflix y dentro de las apps de comidas, las preferidas fueron las de rappy y del uber Eats.
- Todos los usuarios se tardan demasiado buscando un restaurante que le ofrezca algo que me guste, y que los restaurantes más cercanos no cuentan con mesas disponibles, y que se tardan demasiado en tomarme el pedido y en servirlo.
- Para los usuarios el tiempo es primordial por lo que utilizan distintas aplicaciones; sin embargo el principal problema para ellos es que los restaurantes no muestran opciones de comidas saludable, no muestran  informacion necesaria(review), y que tenga una opción de buscar por categorías por ejemplo se me antoja comida china, criolla, etc.

> *“Quiero que la app de comida que me ofresca un buen servicio y sea rápido y seguro”*
> **Vannia salazeta (27 años)**
<br>


#### 1.1.2.Guerrilla Testing

Además de los user personas, necesitábamos validar el flujo de la plataforma web. Para ello realizamos testing de guerrilla.

Especificamos **3 tareas** a realizar:
<center><img width="900" alt="Testing" src="https://user-images.githubusercontent.com/51206952/65444776-63f1e000-ddf6-11e9-87ad-6626685f18ec.png"></center>

<center><img width="900" alt="Registro fotografico" src="https://user-images.githubusercontent.com/51206952/65438989-16707580-ddec-11e9-8c23-965d18c13a6c.png"></center>

### [1.1.3. Benchmark]
<center><img width="900" alt="Testing" src="![bemchmarck](https://user-images.githubusercontent.com/51333504/69844184-097f6080-1239-11ea-9795-3fb9700b872a.png)">
</center>

En el bechmark considere a varios tipos de aplicaciones en a nivel internacional.

## 2. Síntesis y definición

### [2.1 Affinity Map]
La guia de entrevista estuvo orientada a conocer a los usuarios y su experiencia con los restaurantes. Estas preguntas nos permitieron encontrar patrones de conducta para diseñar el user persona.

<br>
<center><img width="900" alt="affinity map" src="![affinity map original](https://user-images.githubusercontent.com/51333504/69843940-bce75580-1237-11ea-8ffb-5ed216e631f8.png)">

</center>
<br>

### 2.1. User persona
[user persona](https://user-images.githubusercontent.com/51333504/69839628-5279e980-1226-11ea-9d84-0b958a366401.JPG)

|Perfil |Persona|Edad|
|:----|:---|:---:|
|**User persona 1**| Liliana |28 años |

Luego de las entrevistas a los usuarios, la conclución es:

- Las necesidades de Liliana tienen requerimientos que por el momento la plataforma web de  Almorzamos no puede ofrecer.
- Requieren otras funcionalidades como ubicación de los restaurantes variedades de tipos de platos, reviews.

### 2.2 Costumer Journey Map 

Para identificar los puntos de mejora de la app realizamos un Costumer Journey Map del uso de la plataforma almorzamos.
<center><img width="2000" alt="Customer Journey Map - Almorzamos" src="[customer juourney map](https://user-images.githubusercontent.com/51333504/69841931-3c245b80-122f-11ea-8768-34b6fad3a8ac.JPG)
">
</center>
<br>

Estos fueron los siguientes puntos críticos:

1. Le gusta saber que existen esta plataforma para poder encontrar los restaurantes de la aplicación, pero no logra entender.
1. No tenian vison del plato que muestra la plataforma. Le pareció genial poder ver el menú de toda la semana.
1. No puedo obtener más información  del restaurante, no me permite hacer nada más.
### 2.4. Problem Statements
Teniendo en cuenta al user persona, se consideraron 8 problem statements iniciales. Luego de analizar las restricciones de tiempo y recursos, se priorizo los siguientes:

<center><img width="900" alt="problem statement" src="[problems statemente](https://user-images.githubusercontent.com/51333504/69839825-2b6fe780-1227-11ea-9c2b-747fb0301670.JPG)">
</center>

Para profundizar y priorizar las soluciones para nuestros problems statement se utilizo las siguientes herramientas:

*1. How Might We / Cómo podríamos*

*2. What if*

*3. Feature List*

## 3. Conclusión de la investigación

Los usuarios se toman más de la mitad del tiempo que tiene para ir almorzar en busqueda de restaurante con disponibilidad de mesa, la atención se demora demasiado y no disfrutan tanto sus almuerzo como quisieran.
Los usuarios necesitan poder pagar con diferentes metodos (tajetas de credito o débito) ya que no siempre cuentan con efectivo.
A los usuarios eligen  los productos que tienen recomendaciones u opiniones positivas de otros comensales.

### 3.1 Recomendaciónes
La plataforma web alamorzamos necesita implementar mejoras y nuevas funcionalidades para ofrecer el mejor servicio a los usuarios asegurando que tengan la facilidad desde su móvil.
Implementación de funcionalidades para obetener el público deseado:
Que le permita al usuario acceder a la información de los restaurantes(reviews)
1. Ver las variedades de  menús por restaurantes.
1. Los platos a la cartas  (Los destacados)
1. Ver las promociones que los restaurantes ofrecen.
1. Qué te permitirá realizar pedidos de diversos restaurantes.
1. Tiempo que se demora la cocción de comida(approx)
1. Que pueda seleccionar el tipo de comida que desee adquirir.
1. Ver  cuáles restaurantes ofrecen el servicio de delivery, si es que se desea que el pedido llegue al centro de labor.
1. Por medio de la geolocalización los  usuario puedan ver qué restaurantes que  hay en su entorno.

## Enlaces 

#### [1. Link a documentación en Google Drive](https://docs.google.com/presentation/d/1RO6XfReDGp_qGbA6eOWQ6X8WdzcM-y6CycQn9Os8inI/edit#slide=id.p1)








