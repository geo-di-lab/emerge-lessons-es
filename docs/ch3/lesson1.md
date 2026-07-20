# Nuestros ojos en el cielo y en el terreno

Para obtener más información, consulta el [artículo de NASA sobre teledetección](https://www.earthdata.nasa.gov/learn/earth-observation-data-basics/remote-sensing).

## Introducción a NASA y la teledetección

La teledetección es la obtención de información a distancia. Se realiza mediante aviones, satélites u otras naves espaciales. Estos instrumentos recopilan tanto imágenes como mediciones de la superficie de la Tierra.

Esta información puede utilizarse en numerosos campos de investigación, como la meteorología, la oceanografía, la ecología terrestre, la geología, la geografía y muchos otros.

NASA participa ampliamente en la teledetección mediante una variedad de plataformas espaciales que registran información sobre la Tierra. El programa de satélites [Landsat](https://science.nasa.gov/mission/landsat/), una colaboración entre NASA y el Servicio Geológico de Estados Unidos, ha sido especialmente importante para documentar los cambios en la superficie terrestre desde la década de 1970. Como estos datos son de acceso abierto, las imágenes de Landsat y de otras misiones de NASA se utilizan en todo el mundo para la investigación, los negocios y la educación.

## ¿Qué observan los satélites y cómo funcionan?

Los satélites de teledetección observan y recopilan datos a distancia mediante la captura de radiación electromagnética reflejada por la Tierra, incluidas las longitudes de onda ultravioleta, infrarroja y visible. Las imágenes se toman simultáneamente en varias longitudes de onda mediante imágenes multiespectrales.

Las imágenes multiespectrales capturan datos en longitudes de onda específicas mediante filtros o instrumentos sensibles a determinadas partes del espectro, lo que permite revelar información que no siempre es visible a simple vista. Al utilizar diferentes filtros de color, elementos como el agua, la vegetación y el suelo pueden resaltarse de forma diferenciada para su análisis. Esto es posible porque cada elemento refleja la luz de manera distinta.

![Espectro electromagnético](https://science.nasa.gov/wp-content/uploads/2023/04/intro_1-jpg.webp)

Imagen de [NASA Science](https://science.nasa.gov/ems/01_intro/)

## Bandas espectrales comunes

Las longitudes de onda son aproximadas y aparecen entre paréntesis:

- **Azul (450–515 nm):** se utiliza para observar la atmósfera y las aguas profundas. En aguas transparentes puede alcanzar profundidades de hasta 150 pies.
- **Verde (515/520–590/600 nm):** se utiliza para observar la vegetación y las estructuras en aguas profundas. En aguas transparentes puede alcanzar profundidades de hasta 90 pies.
- **Rojo (600/630–680/690 nm):** se utiliza para observar objetos construidos por el ser humano, el suelo, la vegetación y el agua hasta una profundidad de aproximadamente 30 pies.
- **Infrarrojo cercano o NIR (750–900 nm):** se utiliza para observar la vegetación.
- **Infrarrojo medio o MIR (1550–1750 nm):** se utiliza para observar la vegetación, el contenido de humedad del suelo y algunos incendios forestales.
- **Infrarrojo lejano o FIR (2080–2350 nm):** se utiliza para estudiar el suelo, la humedad, las características geológicas, los silicatos, las arcillas y los incendios.
- **Infrarrojo térmico (10,400–12,500 nm):** utiliza la radiación emitida en lugar de la reflejada. Se emplea para estudiar estructuras geológicas, incendios, condiciones nocturnas y diferencias térmicas en las corrientes de agua.

## Uso de las bandas espectrales

- Los **colores falsos** son un conjunto de métodos de representación que permiten distinguir partes visibles e invisibles del espectro electromagnético. Una imagen en falso color muestra una escena con colores diferentes de los que tendría a simple vista.

- Las imágenes en **color verdadero** utilizan solamente los canales rojo, verde y azul. Son fáciles de interpretar para quienes comienzan a analizar imágenes, ya que se parecen a fotografías convencionales. Este método es útil para estudiar objetos construidos por el ser humano.

- La combinación **verde-rojo-infrarrojo** sustituye el canal azul por el infrarrojo cercano y suele utilizarse para detectar vegetación.

- En la combinación **azul-NIR-MIR**, el canal azul utiliza la luz azul visible, el canal verde utiliza el infrarrojo cercano para que la vegetación permanezca verde y el infrarrojo medio se representa en rojo. Esta combinación permite observar en una sola imagen la profundidad del agua, la cobertura vegetal, la presencia de incendios y el contenido de humedad del suelo.

## Resolución

La resolución de las imágenes influye considerablemente en la manera en que pueden utilizarse los datos de un instrumento. Existen cuatro tipos de resolución que deben considerarse al trabajar con conjuntos de datos.

La **resolución radiométrica** es la cantidad de información contenida en cada píxel, expresada como el número de bits utilizados para representar la energía registrada. Cada bit representa una potencia de base 2. Por lo tanto, cuanto mayor sea la resolución radiométrica, más valores podrán almacenarse y mejor podrán distinguirse pequeñas diferencias de energía, como variaciones sutiles en el color del océano.

![Arqueología espacial: en el ámbito de la resolución](https://eoimages.gsfc.nasa.gov/images/imagerecords/91000/91071/selselah_oli_2017024.png)

Imágenes de [NASA Earth Observatory, creadas por Joshua Stevens](https://www.visibleearth.nasa.gov/images/91071/space-archaeology-in-the-realm-of-resolution/91074w)

La **resolución espacial** se define por el tamaño de cada píxel de una imagen digital y por el área de la superficie terrestre que representa. Cada píxel corresponde a una zona específica del terreno. Cuanto más fina sea la resolución, es decir, cuanto menor sea el número que representa el tamaño del píxel, mayor será el nivel de detalle visible. En los datos de Landsat, por ejemplo, cada píxel suele representar un área de 30 por 30 metros.

![Tres imágenes satelitales de Landsat con resoluciones de 30 m, 100 m y 300 m](https://earthdata.nasa.gov/s3fs-public/styles/hds_large/public/2022-02/spatial_resolution.jpg)

Imagen de [NASA Earth Observatory](https://earthobservatory.nasa.gov/)

La **resolución espectral** es la capacidad de un instrumento para distinguir intervalos más específicos de longitudes de onda mediante un mayor número de bandas y bandas más estrechas. Cuanto más reducido sea el intervalo de una banda, más fina será la resolución espectral. Muchos instrumentos son multiespectrales y cuentan con entre 3 y 10 bandas, mientras que otros son hiperespectrales y contienen cientos. En el ejemplo siguiente, el espectrómetro aerotransportado de imágenes visibles e infrarrojas, Airborne Visible/Infrared Imaging Spectrometer (AVIRIS), cuenta con 224 canales espectrales que permiten distinguir entre distintos tipos de rocas, minerales y vegetación.

![Cubo de datos hiperespectrales que representa una parte de San Francisco](https://esto.nasa.gov/wp-content/uploads/2022/05/ImgSPEC_Image2.jpg)

Imagen del [Laboratorio de Propulsión a Chorro de NASA](https://esto.nasa.gov/nasa-software-leverages-hyperspectral-data-to-better-understand-climate-change/)

La **resolución temporal** es el tiempo que tarda un satélite en completar una órbita y volver a observar una zona determinada. Depende del tipo de órbita, las características del instrumento y la franja horizontal cubierta por el sensor. Las plataformas de órbita polar suelen tener resoluciones temporales de entre 1 y 16 días. Por ejemplo, un satélite con una resolución temporal de 16 días sería más adecuado para observar cambios que ocurren dos veces al mes que para detectar variaciones diarias.
