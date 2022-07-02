<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Bases conceptuales

    p.mb-5 Para continuar adentrándose en el estudio de este componente, es fundamental afianzar y reforzar algunos conceptos, términos, elementos teóricos y técnicos que tienen relación directa con el tema y que potenciarán su comprensión, asimilación y apropiación de los temas.

     .bloque-texto-g.color-custom-3.p-3.p-sm-4.p-md-5.mb-5.d-none.d-lg-block
      .bloque-texto-g__img(data-aos="fade-right")(
        :style="{'background-image': `url(${require('@/assets/curso/images/tema3/img_1.png')})`}"
      )
      .bloque-texto-g__texto.p-5.m-right(data-aos="fade-left")
        h3.mb-3 Meteorología  #[br]
        p.mb-0 Según el Instituto de Hidrología, Meteorología y Estudios Ambientales IDEAM, la meteorología es “el estudio de la atmósfera y sus fenómenos – especialmente las condiciones del tiempo y del clima – y las aplicaciones prácticas de este estudio. Además de la física, la química y la dinámica de la atmósfera, la meteorología abarca muchos de los efectos directos de la atmósfera en la superficie de la tierra, los océanos y vida en general” (IDEAM, 2019).

    .bloque-texto-a.color-custom-4.p-md-0.mb-5.d-block.d-lg-none
      .row.m-4.align-items-center.justify-content-between
        .col-lg-9(data-aos="fade-right")
          .bloque-texto-a__texto.p-5.my-5
            h3 Meteorología
            p Según el Instituto de Hidrología, Meteorología y Estudios Ambientales IDEAM, la meteorología es “el estudio de la atmósfera y sus fenómenos – especialmente las condiciones del tiempo y del clima – y las aplicaciones prácticas de este estudio. Además de la física, la química y la dinámica de la atmósfera, la meteorología abarca muchos de los efectos directos de la atmósfera en la superficie de la tierra, los océanos y vida en general” (IDEAM, 2019).
        .col-lg-3.mb-3.mb-lg-0(data-aos="fade-left")
          figure
            img(src='@/assets/curso/images/tema3/img_1.png' alt='', style="width:400px; display:block; margin:-1rem 0 ;").mb-3

    h3 Para poder entender la meteorología 

    p.mb-3 Es necesario comprender sus conceptos claves, como Atmósfera: “envoltura gaseosa que rodea la tierra. Capa gaseosa que rodea nuestro planeta. Además de contener el aire, incluye partículas sólidas y líquidas en suspensión o aerosoles y nubes”. (IDEAM, 2019)

    h3.mb-5 Formación de la atmósfera terrestre

    .row.align-items-center.aling.my-5
      .col-lg-10(data-aos="zoom-in-down")
        .bloque-texto-f.color-custom-5.pt-4.px-5.mb-5
          .bloque-texto-f__comillas
            i.fas.fa-quote-left
            i.fas.fa-quote-right
          h4.text-regular.bloque-texto-f__texto.p-4 <b> Según el portal www.capasdelatierra.org: </b> “Se cree que la tierra se formó hace unos 5 mil millones de años y que muchos de los gases de nuestra atmósfera fueron expulsados al aire por los primeros volcanes; durante los primeros 500 millones de años, hubo poco o nada de oxígeno libre alrededor de la tierra. El oxígeno libre consiste en moléculas de oxígeno no unidas a otro elemento, por ejemplo, el carbono (para formar dióxido de carbono) o el hidrógeno (para formar agua)”.“Hace mil millones de años, los primeros organismos acuáticos, llamados algas verdeazuladas, comenzaron a usar la energía del sol para dividir las moléculas de agua (H2O) y el dióxido de carbono (CO2), recombinándolas en compuestos orgánicos y oxígeno molecular (O2). Este proceso de conversión de energía solar se conoce como fotosíntesis”.“En lo alto de la atmósfera, algunas moléculas de oxígeno (O2) absorbieron energía de los rayos ultravioleta (UV) del sol y se dividieron para formar átomos individuales de oxígeno. Estos átomos se combinaron con el oxígeno restante y formaron moléculas de ozono (O3), un gas capaz de absorber los rayos UV. La capa de ozono que rodea la tierra actúa como escudo protector contra la radiación UV”.#[br]#[br]“El aire que respiramos está compuesto en un 78% de nitrógeno (N2), un 21% de oxígeno (O2), 0.9% de argón (Ar) y 0.04% de dióxido de carbono (CO2). El resto está compuesto por elementos llamados oligoelementos, que incluyen vapor de agua, ozono y otras partículas / moléculas que flotan alrededor”.
          .bloque-texto-f__autor.mb-3.aling-1
            p.mb-0 (Capas de la Tierra, 2018)

    .row.justify-content-center.align-items-center.my-5
      .col-lg-12
        TabsA.color-acento-contenido(data-aos="zoom-in-down")
          .tarjeta.back-tab.px-5.py-4(titulo="1. ¿Capas de la atmósfera")
            .row.px-2.py-2.justify-content-center
              .col-lg-12
                h3 1. Capas de la atmósfera
                p.mb-3 La atmósfera está compuesta por una serie de niveles o capas, las cuales están constituidas de gases que permiten la vida en el planeta. Estas capas dependen en su formación de la altitud, densidad y composición. A continuación, se presentan las características de cada una de las 5 capas que rodean y protegen el planeta.
            .row.align-items-center
              .col-lg-10
              .col-lg-2
                img.mx-5(src="@/assets/curso/images/tema1/ico_2.svg",  alt='', style="width:60px; display:block; margin:auto 0 ;")

          .tarjeta.back-tab.px-5.py-4(titulo="Tropósfera")
            .row.px-2.py-2.justify-content-center
              .col-lg-12
                h3 Troposfera
                p.mb-3 “La primera de las capas de la atmosfera es la troposfera y es la más cercana a la superficie terrestre y, por lo tanto, es en aquella capa en la que vivimos nosotros. Se extiende desde el nivel del mar hasta más o menos unos 10-15 km de altura. Es en la tropósfera donde se desarrolla la vida en el planeta. Más allá de la troposfera las condiciones no permiten el desarrollo de la vida. La temperatura y la presión atmosférica van disminuyendo en la troposfera conforme vamos incrementando la altura en la que nos encontramos”. (Portillo, 2021)
            .row.align-items-center
              .col-lg-10
              .col-lg-2
                img.mx-5(src="@/assets/curso/images/tema1/ico_2.svg",  alt='', style="width:60px; display:block; margin:auto 0 ;")
  
          .tarjeta.back-tab.px-5.py-4(titulo="Estratósfera")
            .row.px-2.py-2.justify-content-center
              .col-lg-12
                h3 Estratósfera
                p.mb-3 “Se encuentra a partir de la tropopausa y se extiende desde los 10-15 km de altura hasta los 45-50 km. La temperatura en la estratósfera es mayor en la parte superior que en la inferior ya que conforme aumenta en altura, va absorbiendo mayor cantidad de rayos solares y va aumentando su temperatura. Es decir, el comportamiento de la temperatura en altura es al contrario que en la troposfera. Comienza siendo estable, pero baja, y conforme aumenta la altitud, aumenta la temperatura”.
                p.mb-0 Al final de la estratósfera se encuentra la estratopausa. Se trata de una zona de la atmósfera donde terminan las altas concentraciones de ozono y la temperatura se vuelve muy estable (sobre los 0 grados centígrados). La estratopausa es la que da paso a la mesosfera.  (Portillo, 2021)
            .row.align-items-center
              .col-lg-10
              .col-lg-2
                img.mx-5(src="@/assets/curso/images/tema1/ico_2.svg",  alt='', style="width:60px; display:block; margin:auto 0 ;")
          

          .tarjeta.back-tab.px-5.py-4(titulo="Mesosfera")
            .row.px-2.py-2.justify-content-center
              .col-lg-12
                h3 Mesosfera
                p.mb-3 “Al final de la estratósfera, se encuentra la estratopausa. Se trata de una zona de la atmósfera donde terminan las altas concentraciones de ozono y la temperatura se vuelve muy estable (sobre los 0 grados centígrados). La estratopausa es la que da paso a la mesosfera”.
                p.mb-0 La mesosfera es la capa más delgada de la atmósfera, ya que sólo contiene el 0,1% de la masa de aire total, y en ella se pueden alcanzar temperaturas de hasta -80 grados centígrados. En esta capa tienen lugar las reacciones de quimioluminiscencia y aeroluminiscencia.  (Portillo, 2021)

          .tarjeta.back-tab.px-5.py-4(titulo="Termosfera")
            .row.px-2.py-2.justify-content-center
              .col-lg-12
                h3 Termosfera
                p.mb-3 “Es la capa de la atmósfera más amplia. Se extiende desde los 80-90 km hasta los 640 km. A estas alturas ya apenas queda aire y las partículas que existen en esta capa se ionizan por la radiación ultravioleta. A esta capa también se le llama ionosfera debido a las colisiones de los iones que tienen lugar en ella. La ionosfera tiene gran influencia en la propagación de las ondas de radio. Una parte de la energía radiada por un transmisor hacia la ionósfera es absorbida por el aire ionizado y otra es refractada, o desviada, de nuevo hacia la superficie de la tierra”.

                p.mb-2 La temperatura en la termosfera es muy alta, llegando a ser de hasta miles de grados Celsius. Todas las partículas que se encuentran en la termosfera están altamente cargadas de energía proveniente de los rayos del sol.
                p (Portillo, 2021)

          .tarjeta.back-tab.px-5.py-4(titulo="Exosfera")
            .row.px-2.py-2.justify-content-center
              .col-lg-12
                h3 Exosfera
                p.mb-3 “La última de las capas de la atmosfera es la exosfera. Esta es la capa más alejada de la superficie terrestre y, debido a su altura, es la más indefinida y por eso no es en sí considerada una capa de la atmósfera. Más o menos se extiende entre los 600-800 km de altura hasta los 9.000-10.000 km. Esta capa de la atmósfera es la que separa el planeta tierra del espacio exterior y en ella los átomos se escapan. Está compuesta en su mayoría de hidrógeno”.
                p (Portillo, 2021)

    .row.align-items-center.aling.my-5
      .col-lg-10(data-aos="fade-right")               
        .row.justify-content-center
          .col-md-6.col-lg.mb-5.mb-lg-0
            .tarjeta-avatar
              img.mt-3(src="@/assets/curso/images/tema3/ico_2.svg",  alt='', style="width:90px; display:block; margin:auto 0 ;")
              .tarjeta-1.p-5.h-100
                p Usted debe conocer que, entre las metas que se establecen en este acuerdo mundial, el cual fue firmado por Colombia, están:
                .row
                  .col-lg-6
                    ol.lista-ol
                      li 
                        span.text-bold 1. 
                        | Dióxido de carbono (CO2) 
                      li 
                        span.text-bold 3. 
                        | Óxido nitroso (N2O)
                      li 
                        span.text-bold 5. 
                        | Perfluorocarbonos (PFC) 
                  .col-lg-6
                    ol.lista-ol
                      li 
                        span.text-bold 2.
                        | Metano (CH4)
                      li 
                        span.text-bold 4. 
                        |  Hidrofluorocarbonos (HFC)
                      li 
                        span.text-bold 6. 
                        | Hexafluoruro de azufre (SF6)

          .col-md-6.col-lg.mb-5.mb-lg-0(data-aos="fade-left")
            .tarjeta-avatar
              img.mt-3(src="@/assets/curso/images/tema3/ico_3.svg",  alt='', style="width:90px; display:block; margin:auto 0 ;")
              .tarjeta-1.p-5.h-100
                p.my-5 Como aprendiz, conozca y reconozca la importancia de los acuerdos que firma Colombia y a lo que se compromete, con la finalidad de que sea veedor y cabal vigilante desde su casa y trabajo, con las acciones que se realizan día a día.

    p.mb-3 Para continuar conociendo los aspectos conceptuales básicos que favorecerán el estudio de este componente y que ayudarán a apropiar, más y mejor, la problemática atmosférica, se invita a desarrollar la siguiente actividad.

    h3 Bases conceptuales:
    
    p.mb-3 Se presentan otros elementos conceptuales que tienen que ver, directamente, con la presión atmosférica. Ello favorecerá la asimilación de los contenidos de este componente y ampliará las posibilidades de aplicación de estrategias técnicas y mecanismos sistemáticos para enfrentar la problemática atmosférica actual. Se debe estudiar la gráfica de manera ordenada, siguiendo la numeración de sus partes.


    TabsC.color-acento-contenido(data-aos="zoom-in-down")
      .py-3.py-md-4(titulo="1. Presión atmosférica")
        .row.justify-content-center
          .col-2.col-lg-2.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/images/tema3/img_2.png', ,  alt='', style="width:100px; display:block; margin:auto 0 ;").mb-3
          .col-lg-10
            h3 Presión atmosférica
            p.mb-3 Presión (fuerza por unidad de área) ejercida por la atmósfera sobre cualquier superficie en virtud de su peso. Equivale al peso de una columna de aire de sección transversal unitaria que se extiende desde un nivel dado hasta el límite superior de la atmósfera (IDEAM, 2019). 
            p.mb-0 Las unidades de medida de la presión atmosférica se establecen en diferentes unidades dependiendo del sistema empleado, algunas de las equivalencias más utilizadas se las presentamos en los botones siguientes de esta gráfica.

      .py-3.py-md-4(titulo="2. Temperatura")
        .row.justify-content-center
          .col-2.col-lg-2.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/images/tema3/img_3.png', ,  alt='', style="width:100px; display:block; margin:auto 0 ;").mb-3
          .col-lg-10
            h3 Temperatura
            p.mb-3 Magnitud física que caracteriza el movimiento aleatorio medio de las moléculas en un cuerpo físico (IDEAM, 2019). Entonces se podría decir que entre más movimiento de las moléculas, mayor es la temperatura que se genera en el elemento, sustancia o cuerpo.

            p.mb-0 La unidad con la que se determina la temperatura se establece en diferentes unidades, dependiendo del sistema de unidades empleado. Diríjase al punto tres de esta gráfica.

     
      .py-3.py-md-4(titulo="3. Velocidad del viento")
        .row.justify-content-center
          .col-2.col-lg-2.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/images/tema3/img_4.png', ,  alt='', style="width:100px; display:block; margin:auto 0 ;").mb-3
          .col-lg-10
            h3 Velocidad del viento
            p.mb-3 Es la relación entre la distancia recorrida por el aire y el tiempo que tarda en recorrerla. La "velocidad instantánea" o, con mayor brevedad, la "velocidad", corresponde al caso de un intervalo de tiempo infinitamente pequeño. La "velocidad media" corresponde al caso en que el intervalo de tiempo es finito. (IDEAM, 2019).
 
            p.mb-0 La velocidad del viento mide la componente horizontal del desplazamiento del aire en un punto y en un instante determinados. La unidad de medida es habitualmente metros por segundo (m/s).


      .py-3.py-md-4(titulo="4. Dirección del viento")
        .row.justify-content-center
          .col-2.col-lg-2.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/images/tema3/img_5.png', ,  alt='', style="width:100px; display:block; margin:auto 0 ;").mb-3
          .col-lg-10
            h4 Dirección del viento"
            p.mb-3 Dirección desde la que sopla el viento. (IDEAM, 2019).
            p.mb-0 Según Guerrero (2011) “La rosa de los vientos, también llamada rosa náutica, es un instrumento marino usado en las cartas de navegación que se utiliza para representar la circunferencia del horizonte mediante el uso de 32 rombos unidos por sus extremos. Frecuentemente, también se puede ver en el mismo instrumento una flor de lis, que se utiliza para representar el norte”.


      .py-3.py-md-4(titulo="5. ¿Rosa de los vientos?")
        .row.justify-content-center
          .col-2.col-lg-2.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/images/tema3/img_6.png', ,  alt='', style="width:100px; display:block; margin:auto 0 ;").mb-3
          .col-lg-10
            h4 ¿Rosa de los vientos?
            p.mb-3 La rosa de los vientos es el instrumento que permite visualizar los puntos cardinales, donde toma como referencia el norte por los campos magnéticos que se producen en la tierra, por ende…
            p.mb-0  “Las cuatro principales y fundamentales (divisiones) indican los cuatro puntos cardinales: norte, sur, este y oeste, mediante los cuales se divide el horizonte en cuatro sectores de 90º cada uno. La recta que conecta los puntos norte y sur es llamada meridiana o línea norte-sur, la recta que une este y oeste es llamada línea este-oeste. Como resultado de las bisectrices de los ángulos rectos representados en la rosa de los vientos se observan ocho nuevas divisiones llamadas laterales, que son: noreste, sureste, suroeste y noroeste. Si se dividen nuevamente estos rumbos laterales y los cuatro principales se obtendrán ocho nuevos sectores que se llamarán: nor-noreste, este-noreste, este-sureste, sur-sureste, sur-suroeste, oeste-suroeste, oeste-noroeste y norte-noroeste.” (Guerrero, 2011)


      .py-3.py-md-4(titulo="6. Precipitación")
        .row.justify-content-center
          .col-2.col-lg-2.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/images/tema3/img_7.png', ,  alt='', style="width:100px; display:block; margin:auto 0 ;").mb-3
          .col-lg-10
            h4 Precipitación
            p.mb-3 La precipitación es la caída de partículas de agua líquida o sólida que se originan en una nube, atraviesan la atmósfera y llegan al suelo. La cantidad de precipitación es el volumen de agua lluvia que pasa a través de una superficie en un tiempo determinado. (IDEAM, 2019)
            p.mb-0 Teniendo en cuenta qué es la lluvia, a la cual se denomina técnicamente precipitación, es importante definir las unidades en las que se cuantifica. 

      .py-3.py-md-4(titulo="7. ¿Cómo medir la precipitación?")
        .row.justify-content-center
          .col-2.col-lg-2.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/images/tema3/img_8.png', ,  alt='', style="width:100px; display:block; margin:auto 0 ;").mb-3
          .col-lg-10
            h4 ¿Cómo medir la precipitación?
            p.mb-3 …” La precipitación se mide en milímetros de agua, o litros caídos por unidad de superficie (m²), es decir, la altura de la lámina de agua recogida en una superficie plana es medida en mm o L/m².
            p.mb-3 Por ende, la cantidad de lluvia que cae en un lugar se mide por los pluviómetros. La medición se expresa en milímetros de agua y equivale al agua que se acumularía en una superficie horizontal e impermeable durante el tiempo que dure la precipitación o sólo en una parte del periodo de la misma”.
            p.mb-3 (MeteoLobios, 2013)
            p.mb-3 Para medir la precipitación se cuenta con diversos instrumentos, los más empleados se conocen como pluviómetros (manual, totalizadores, sifón, basculantes, etc.), siendo el pluviómetro manual uno de los más empleados por su practicidad.
            p.mb-3 Pluviómetro manual: “Es un indicador simple de la lluvia caída, consiste en un recipiente especial cilíndrico, por lo general de plástico, con una escala graduada donde todas las marcas están a igual distancia entre sí. La altura del agua que llena la jarra es equivalente a la precipitación y se mide en mm”.


    .row.aling.my-5   
      .col-lg-10(data-aos="zoom-in-down")
        .cajon.color-custom-2.p-4.mb-4.p-5
          .row.justify-content-star
            .col-lg-2.col-sm-2
              img.mx-3(src="@/assets/curso/images/tema3/ico_2.svg",  alt='', style="width:90px; display:block; margin:auto 0 ;").mb-2
            .col-lg-10
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p Según el IDEAM, la evaporación del agua se relaciona en 2 conceptos
                  ul.lista-ul--color
                    li 
                      i.fas.fa-circle.cac
                      | Emisión de vapor de agua por una superficie líquida de agua libre a temperatura inferior a su punto de ebullición.
                    li
                      i.fas.fa-circle.cac
                      | Cantidad de agua evaporada. (IDEAM,2019)

                  p.mb-3 Por ende, la evaporación relaciona indirectamente la cantidad de evaporatividad que influye en los diversos cambios en el comportamiento de la atmósfera. A esa relación se le conoce como:

                  p Evaporación potencial
                  p.mb-3 “Cantidad de vapor de agua que puede ser emitida por una superficie de agua pura, por unidad de superficie y por unidad de tiempo, en las condiciones atmosféricas existentes”. (IDEAM, 2019).

                  p Los instrumentos que miden la evaporación se conocen como evaporímetros, los cuales miden la cantidad de agua que se evapora en la atmósfera.

    .row.aling.my-5   
      .col-lg-10(data-aos="zoom-in-down")
        .cajon.color-custom-2.p-4.mb-4.p-5
          .row.justify-content-star
            .col-lg-2.col-sm-2
              img.mx-3(src="@/assets/curso/images/tema3/ico_3.svg",  alt='', style="width:90px; display:block; margin:auto 0 ;").mb-2
            .col-lg-10
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.mb-3 Finalmente, le presentamos el elemento de la Radiación: es la emisión o transferencia de energía en forma de ondas o partículas electromagnéticas. (IDEAM, 2019)

                  p.mb-2 Cuando se habla de radiación se puede ver desde diferentes perspectivas conceptuales, no solo es lo que conocemos como lo que produce la luz del sol. La radiación electromagnética se puede clasificar en diferentes tipos. El portal foronuclear.org define los siguientes conceptos.

                  p.mb-2 Radiación no ionizante: “no tiene la suficiente energía como para romper los enlaces que unen los átomos del medio que irradian (ondas de radio y TV, microondas, luz visible, etc.)”.

                  p.mb-2 Radiación ionizante: “tiene suficiente energía como para producir ionizaciones de los átomos del medio o materia que es irradiado. Van desde los rayos X hasta la radiación cósmica”.

                  p.mb-2 Dependiendo de la relación que estas tengan con diversas materias o elementos, también se clasifican con el alfabeto griego para diferenciarlas técnicamente en:

                  p.mb-2 alfa: con capacidad limitada de penetración en la materia, pero mucha intensidad energética.
                  p.mb-2 beta: algo más penetrantes, pero menos intensas que las radiaciones alfa.
                  p.mb-2 gamma: es la radiación más penetrante de todas.

                  p.mb-2 (Foro Nuclear, 2020)




















</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
