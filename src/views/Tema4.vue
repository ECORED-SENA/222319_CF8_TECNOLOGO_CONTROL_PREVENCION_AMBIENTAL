<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.cs
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Bases conceptuales

    p.mb-5 La contaminación atmosférica es una problemática que impacta directamente en la atmósfera y que consecuentemente afecta la calidad del aire que respiramos, generando en el ser humano consecuencias relacionadas con enfermedades, especialmente respiratorias, que impactan en gran medida al hombre y su bienestar.

    .row.justify-content-center.align-items-center.my-5
      .col-lg-6
        .jumbotron-1.p-5.h-100(data-aos="fade-right")
          h4.mb-3 Los contaminantes 
          img(src="@/assets/curso/images/tema4/img_1.png")
          p.mt-3 Los contaminantes criterio como el CO2, los dióxidos de azufre, óxidos de nitrógeno, el material particulado, entre otros, se condensan en la parte superior de la tropósfera produciendo lo que conocemos como smog fotoquímico. Estos compuestos, al reaccionar con la radiación solar, exacerban las concentraciones y la temperatura media del planeta, aumentando las consecuencias, tanto en los receptores humanos como en los ecosistemas, debido a las actividades antrópicas que impactan directamente en la sociedad por la relación del consumo y la economía para el desarrollo de la humanidad. 

      .col-lg-6
        .jumbotron-2.p-5.h-100(data-aos="fade-left")
          h4.mb-3 Fuentes contaminantes
          img(src="@/assets/curso/images/tema4/img_2.png").mb-5
          p.mb-4 La mayoría de los contaminantes que se vierten en la atmósfera provienen de diversas fuentes, las cuales se pueden clasificar en naturales y antrópicas. En ese mismo sentido, las fuentes también pueden variar entre puntuales, dispersas, difusas, de área, entre otras. A continuación, se presentan los conceptos para comprender cómo estas fuentes influyen directamente en la contaminación que se genera en el ambiente. 

    Separador

    #t_4_1.titulo-segundo
      .h2 4.1 La contaminación atmosférica
    
    p.mb-3 Para hablar de la contaminación atmosférica, se deben tener en cuenta ciertos elementos que nos favorecen su asimilación y comprensión:

    .row.align-items-center.justify-content-center.p-4(data-aos="zoom-in-down") 
      SlyderF.slyder-color.mb-5(columnas="col-lg-6 col-xl-4")(data-aos="zoom-in-down")
        .tarjeta-avatar
          img(src='@/assets/curso/images/tema4/ico_1.svg' alt='', style="width:130px; display:block; margin:auto 0 ;")
          .tarjeta.color-tarjeta-slyder-1
            .p-4.text-ce
              h4.text-center Fuentes biogénicas
              p.text-center Corresponden a los eventos de contaminación producidos por fenómenos propios de la naturaleza.Entre éstos, se encuentran las erosiones, los incendios forestales, las erupciones volcánicas, la descomposición de la vegetación y tormentas de polvo.  


        .tarjeta-avatar
          img(src='@/assets/curso/images/tema4/ico_2.svg' alt='', style="width:130px; display:block; margin:auto 0 ;")
          .tarjeta.color-tarjeta-slyder-1
            .p-4
              h4.text-center Fuentes antropogénicas
              p.text-center “Estas corresponden a actividades o intervenciones que realizan las personas, siendo la principal causa la combustión de materiales, sea ésta originada por las industrias, los vehículos o en el hogar. Esta clasificación tiene a su vez una subdivisión en tres grupos: las fuentes fijas, las fuentes móviles y las fuentes fugitivas”.


        .tarjeta-avatar
          img(src='@/assets/curso/images/tema4/ico_3.svg' alt='', style="width:130px; display:block; margin:auto 0 ;")

          .tarjeta.color-tarjeta-slyder-1
            .p-4
              h4.text-center Las fuentes fijas
              p.text-center “Corresponden a aquéllas situadas en un lugar físico particular, definido e inamovible. Considera las emisiones generadas por la quema de combustibles producto de actividades industriales y residenciales”.

        .tarjeta-avatar
          img(src='@/assets/curso/images/tema4/ico_4.svg' alt='', style="width:130px; display:block; margin:auto 0 ;")
          .tarjeta.color-tarjeta-slyder-2
            .p-4
              h4.text-center Las fuentes móviles
              p.text-center Corresponden a aquellas fuentes que sí pueden desplazarse. A estas se asocian las emisiones de gases en tubos de escape, desgaste de frenos y neumáticos de distintos tipos de transporte motorizado, como automóviles, camiones, buses y motocicletas.


        .tarjeta-avatar
          img(src='@/assets/curso/images/tema4/ico_5.svg'  alt='', style="width:130px; display:block; margin:auto 0 ;")
          .tarjeta.color-tarjeta-slyder-2
            .p-4
              h4.text-center Las fuentes fugitivas
              p.text-center Comprenden emisiones que no son canalizadas por ductos, chimeneas u otros sistemas hacia el exterior, tales como aquellas provenientes del tránsito de vehículos por calles sin pavimentar, de la construcción y las demoliciones, entre otras.

    p.mb-3 Sin embargo, y ampliando la conceptualización sobre las fuentes contaminantes de la atmósfera, la Resolución 909 de 2008, que corresponde a la norma de fuentes fijas en Colombia, define los siguientes conceptos asociados a los tipos de fuentes:
    .jumbotron-3.p-3.mb-5(data-aos="zoom-in-down") 
      .row.aling-items-stretch.justify-content-evenly.my-4
        .col-lg-2.bor_tar.px-0.mt-5
          .head_tar.mt-0.p-2
            h4.mb-0.text-center.text-white Fuente de emisión
          .p-4
            p.text-center Es toda actividad, proceso u operación realizado por los seres humanos, o con su intervención, susceptible de emitir contaminantes al aire. (MADS, Res 909 de 2008, p. 34).
        .col-lg-2.bor_tar.px-0.mt-5
          .head_tar.mt-0.p-2
            h4.mb-0.text-center.text-white Fuente fija
          .p-4
            p.text-center Es la fuente de emisión situada en un lugar determinado e inamovible, aún cuando la descarga de contaminantes se produzca en forma dispersa. (MADS, Res 909 de 2008, p. 34).

        
        .col-lg-2.bor_tar.px-0.mt-5
          .head_tar.mt-0.p-2
            h4.mb-0.text-center.text-white  Fuente fija dispersa o difusa.
          .p-4
            p.text-center Es aquella en que los focos de emisión de una fuente fija se dispersan en un área, por razón del desplazamiento de la acción causante de la emisión, como en el caso de las quemas abiertas controladas en zonas rurales. (MADS, Res 909 de 2008, p. 34).

        .col-lg-2.bor_tar.px-0.mt-5
          .head_tar.mt-0.p-2
            h4.mb-0.text-center.text-white Fuente fija puntual
          .p-4
            p.text-center Es la fuente fija que emite contaminantes al aire por ductos o chimeneas. (MADS, Res 909 de 2008, p. 34).

        
        .col-lg-2.bor_tar.px-0.mt-5
          .head_tar.mt-0.p-2
            h4.mb-0.text-center.text-white  La calidad del aire
          .p-4
            p.text-center La calidad del aire es dinámica y responde a las distintas fuentes de contaminación existentes en un momento (actividades económicas, procesos y tecnologías de combustión, composición de los combustibles utilizados, entre otros).
      figcaption.text-center (Ministerio del Medio Ambiente. Gobierno de Chile, 2018)

    p.mb-5 ¡Atención! Dentro de las múltiples fuentes antropogénicas que contribuyen a la contaminación atmosférica se encuentran:

    .row.align-items-stretch.justify-content-center.mb-3(data-aos="zoom-in-down")    
      .col-lg-4
        img.mx-1(src='@/assets/curso/images/tema4/img_3.png' alt='', style="width:365px; display:block; margin:auto 0 ;")
      .col-lg-8
        .jumbotron-4.mb-3.p-4
          ul.lista-ul
            li.mb-0
              i.fas.fa-check.c-check
              | Uso de combustibles fósiles, como el carbón, el gas, el petróleo y sus derivados.
            li.mb-0
              i.fas.fa-check.c-check
              | Quemar leña como medio de calefacción y cocina en los hogares.
            li.mb-0 
              i.fas.fa-check.c-check
              | Emplear productos químicos de manera directa o indirecta, tales como los clorofluorocarbonos (CFC).
            li.mb-0 
              i.fas.fa-check.c-check
              | Estos se encuentran en aerosoles de espray, en refrigeradores antiguos, en fertilizantes químicos para cuidar tus plantas o cosechas agrícolas.
            li 
              i.fas.fa-check.c-check
              | Deforestar bosques.
            li.mb-0
              i.fas.fa-check.c-check
              | Quemar rastrojos agrícolas.
            li.mb-0 
              i.fas.fa-check.c-check
              | Efectuar tronaduras en la industria minera.
            li.mb-0 
              i.fas.fa-check.c-check
              | Construir grandes obras como edificios, puentes, caminos.
          
    Separador

    #t_4_2.titulo-segundo
      .h2 4.2 Contaminantes atmosféricos

    p.mb-3 Los contaminantes que afectan al ser humano, en su gran mayoría, son los adquiridos por vía aérea. Estos están constituidos por gases y partículas. A ellos se les denomina Criterio, en otras palabras, aquellos que generan una afectación directa en la salud.

    .jumbotron-5.p-4(data-aos="zoom-in-down")    
      .row.justify-content-center.align-items-center
        .col-3.col-lg-1.mb-4.mb-lg-0
          img(src="@/assets/curso/images/tema4/bomb.svg" alt='', style="width:65px; display:block; margin:auto 0 ;")
        .col-lg-10
          h3.mb-2 ¿En qué consisten? 
          p Según la Guía de calidad del aire y educación ambiental, “Los contaminantes de la atmósfera consisten en una gran variedad de gases, vapores y partículas, cuya presencia y cantidad afectan a las personas, las plantas, los animales y los materiales. Según sea el origen de los contaminantes, estos pueden clasificarse en dos grandes grupos -los primarios y los secundarios-, para así estudiar mejor su origen, distribución y tratamiento o prevención”.

    .row.justify-content-center.align-items-center.my-3
      .col-lg-6
        .jumbotron-6.p-5.h-100(data-aos="fade-right")
          .row.justify-content-center.align-items-center
            .col-6.col-lg-2.mb-4.mb-lg-0
              img(src="@/assets/curso/images/tema4/milk.svg",  alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-3.text-white Contaminantes primarios
                  p.mt-3.text-white “Son aquellos que proceden directamente de las fuentes de emisión, tales como artefactos de calefacción domiciliarios, chimeneas industriales y tubos de escape de automóviles”.
      .col-lg-6
        .jumbotron-6.p-5.h-100(data-aos="fade-left")
          .row.justify-content-center.align-items-center
            .col-6.col-lg-2.mb-4.mb-lg-0
              img(src="@/assets/curso/images/tema4/oil.svg",  alt='', style="width:100px; display:block; margin:auto 0 ;")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-3.text-white Contaminantes secundarios
                  p.mt-3.text-white  “Son aquellos que se originan en el aire, a raíz de reacciones químicas que pueden ocurrir entre dos o más contaminantes primarios, o entre contaminantes primarios y elementos propios de la atmósfera”.
      .row.justify-content-center.mt-3
        .col-lg-6 
        .col-lg-6 
          .jumbotron-4.p-4
            p.text-center (Ministerio del Medio Ambiente. Gobierno de Chile, 2018) 

    p.mb-3 A continuación, se presenta información muy importante sobre los principales contaminantes de la atmósfera. Se recomienda prestar mucha atención y tomar nota atenta de los elementos que se visualizará.

    .row.justify-content-center
      .col-lg-10(data-aos="zoom-in-down")
        ImagenInfografica.color-secundario.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/images/tema4/info.svg')
          .tarjeta.color-custom-info.p-3(x="49%" y="8%" numero="")
            h3 Material Particulado
            p.mb-0 “El Material Particulado (MP) se clasifica según su diámetro, característica de la cual depende la intensidad de sus impactos. Las partículas de diámetros menores a 10 micrones, conocidas como MP10, y de diámetros menores a 2.5 micrones, conocidas como MP2.5. Este último es el contaminante más dañino para la salud y que genera mayores niveles de mortalidad prematura en la población”.
          .tarjeta.color-custom-info.p-3(x="82.7%" y="40%" numero="")
            h3 Monóxido de carbono (CO)
            p.mb-3 “Este gas es producto de la combustión incompleta de los combustibles, al existir una cantidad insuficiente de oxígeno, dando como resultado CO en vez de CO2. Los vehículos a motor y los procesos industriales son responsables de aproximadamente el 80% de estas emisiones a la atmósfera. Sin embargo, también se produce al interior del hogar por la combustión residencial de leña para calefacción, cocinas, humo de cigarrillo y calefones”.

            p.mb-0 Este compuesto es uno de los gases más letales por su capacidad inhibidora de oxígeno - molécula en la sangre, lo que produce en el organismo una ausencia porcentual del mismo, siendo de esta manera muy letal.

          .tarjeta.color-custom-info.p-3(x="69%" y="85%" numero="")
            h3 Óxidos de nitrógeno (NOx)
            p.mb-3 Estos gases se producen durante el quemado de maderas y combustibles fósiles, como gasolina, carbón y gas natural.
            p.mb-3 “El sector transporte constituye la fuente principal de emisión de NOx. El mayor desplazamiento en vehículos particulares por parte de la población en las grandes ciudades y el crecimiento sostenido del parque automotriz son una de las causas más importantes del aumento de las emisiones de este contaminante. Cabe tener presente que los vehículos con motor a diésel emiten una mayor cantidad de contaminantes que aquéllos a gasolina, por lo que también es relevante considerar la composición del parque automotriz.”

            p.mb-0 (Ministerio del Medio Ambiente. Gobierno de Chile, 2018)

          .tarjeta.color-custom-info.p-3(x="30%" y="86%" numero="")
            p Cuando hablamos de los NOx, se incluye una <b>familia de compuestos nitrogenados </b> en la que se encuentran:

            p * Óxido nítrico (NO).
            p * Dióxido de nitrógeno (NO2).
            p * Trióxido de nitrógeno (NO3).
            p * Óxido nitroso (N2O).
            p * Pentóxido de nitrógeno (N2O5).


          .tarjeta.color-custom-info.p-3(x="18.7%" y="43%" numero="")
            h3 Óxidos de azufre (SOx)
            p.mb-0 “El dióxido de azufre (SO2) y trióxido de azufre (SO3) son los óxidos dominantes del azufre presentes en la atmósfera. Son producto de la combustión de combustibles fósiles, principalmente derivados del petróleo y carbón. Los óxidos de azufre pueden acelerar la corrosión de los materiales al formar primero ácido sulfúrico en la atmósfera o sobre la superficie de los metales”.
         
    .row.align-items-center.aling
      .col-lg-10(data-aos="zoom-in-down")
        .tarjeta.color-primario.p-4.mb-5
          .row.justify-content-center.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/images/tema1/ico_3.svg",  alt='', style="width:60px; display:block; margin:auto 0 ;")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 La contaminación del aire
                  p.text-small https://www.youtube.com/watch?v=1nhyQiWmVio
                .col-md-auto
                  a.boton.color-acento-contenido.texto-blanco(href="https://www.youtube.com/watch?v=1nhyQiWmVio" target="_blank")
                    span Ver
                    .row
                      .col-auto
                        img.mx-3(src="@/assets/curso/images/tema1/Ico-video.svg",  alt='', style="width:20px; display:block; margin:auto 0 ;")

    p.mb-3 Para finalizar con el estudio de los principales contaminantes atmosféricos, se recomienda observar atentamente los que se muestran a continuación.

    TabsB.color-acento-contenido.mb-5(data-aos="zoom-in-down")
      .py-4.py-md-5(titulo="Compuestos Orgánicos Volátiles (COV)" :icono="require('@/assets/curso/images/tema4/ico_11.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-8
            h4 Compuestos Orgánicos Volátiles (COV)
            p “Las emisiones de estos compuestos proceden de distintas fuentes, como el transporte, industrias de disolventes, minería, vertederos, entre otros, además de fuentes biogénicas, como la vegetación. Muchos de estos compuestos interactúan con otros componentes para producir niebla y contaminación por aerosoles en presencia de radiación solar.” 
            .row.justify-content-center.mt-3
              .col-lg-8
                .jumbotron-4.p-3
                  p (Ministerio para la Transición Ecológica y el Reto Demográfico, 2016)
              .col-lg-4
                
          .col-lg-4
            figure
              img.mx-2(src="@/assets/curso/images/tema4/img_4.svg",  alt='', style="width:300px; display:block; margin:auto 0 ;").my-3

      .py-4.py-md-5(titulo="Especificación sobre los COV" :icono="require('@/assets/curso/images/tema4/ico_12.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-8
            h4 Especificación sobre los COV
            p Según el Ministerio para la Transición Ecológica y el Reto Demográfico (2016),  “Los compuestos orgánicos volátiles (COV) son todos aquellos hidrocarburos que se presentan en estado gaseoso a la temperatura ambiente normal o que son muy volátiles a dicha temperatura. Se puede considerar como COV aquel compuesto orgánico que a 20ºC tenga una presión de vapor de 0.01 kPa o más, o una volatilidad equivalente en las condiciones particulares de uso”.
            .row.justify-content-center.mt-3
              .col-lg-8
                .jumbotron-4.p-3
                  p (Ministerio para la Transición Ecológica y el Reto Demográfico, 2016)
              .col-lg-4
                
          .col-lg-4
            figure
              img.mx-2(src="@/assets/curso/images/tema4/img_5.svg",  alt='', style="width:300px; display:block; margin:auto 0 ;").my-3

      .py-4.py-md-5(titulo="Peligrosidad de los COV" :icono="require('@/assets/curso/images/tema4/ico_13.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-8
            h4 Peligrosidad de los COV
            p Con respecto a su peligrosidad, los COV pueden clasificarse en 3 grupos:
            p Compuestos extremadamente peligrosos para la salud: Benceno, cloruro de vinilo y 1,2 dicloroetano.
            p Compuestos clase A: Los que pueden causar daños significativos al medio ambiente, como acetaldehído, anilina, tricloroetileno, etc.
            p Compuestos clase B: tienen menor impacto en el medio ambiente. Pertenecen a este grupo, entre otros, acetona y etanol.
            .row.justify-content-center.mt-3
              .col-lg-8
                .jumbotron-4.p-3
                  p (Ministerio para la Transición Ecológica y el Reto Demográfico, 2016)
              .col-lg-4
                
          .col-lg-4
            figure
              img.mx-5(src="@/assets/curso/images/tema4/img_6.svg",  alt='', style="width:200px; display:block; margin:auto 0 ;").my-3

      .py-4.py-md-5(titulo="Para tener en cuenta" :icono="require('@/assets/curso/images/tema4/ico_14.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-8
            h4 Para tener en cuenta
            p.mb-2 Los COV afectan tanto de manera medioambiental como directamente sobre la salud del ser humano. Estos compuestos están presentes por actividades en las que se emplean disolventes orgánicos. Algunas de las actividades donde es posible que se den emisiones de COV son:
            p Pinturas y barnices (e industrias donde se usen éstos) 
            p Industria siderúrgica
            p Industria de la madera
            p Industria cosmética 
            p Industria farmacéutica

            .row.justify-content-center.mt-3
              .col-lg-8
                .jumbotron-4.p-3
                  p (Ministerio para la Transición Ecológica y el Reto Demográfico, 2016)
              .col-lg-4
                
          .col-lg-4
            figure
              img.mx-2(src="@/assets/curso/images/tema4/img_7.svg",  alt='', style="width:250px; display:block; margin:auto 0 ;").my-3


      .py-4.py-md-5(titulo="Plomo (Pb)" :icono="require('@/assets/curso/images/tema4/ico_15.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-8
            h4 Plomo (Pb)
            p “Este contaminante proviene de la combustión de gasolinas con plomo, de la minería y fundiciones, y de la incineración de residuos. El plomo puede depositarse en el agua y alimentos que consumimos, por lo que puede ser absorbido por nuestro cuerpo”. 
            .row.justify-content-center.mt-3
              .col-lg-8
                .jumbotron-4.p-3
                  p (Ministerio para la Transición Ecológica y el Reto Demográfico, 2016)
              .col-lg-4
                
          .col-lg-4
            figure
              img.mx-2(src="@/assets/curso/images/tema4/img_8.svg",  alt='', style="width:250px; display:block; margin:auto 0 ;").my-3

      .py-4.py-md-5(titulo="Ozono troposférico (O3)" :icono="require('@/assets/curso/images/tema4/ico_16.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-8
            h4 Ozono troposférico (O3)
            p “Se trata del principal componente del smog fotoquímico y uno de los más fuertes agentes oxidantes. El ozono se forma en la tropósfera y de la acción de esta en las moléculas de ozono en la estratósfera, como producto de la reacción entre los NOX, los COV y los hidrocarburos (HC) en presencia de radiación solar. Las fuentes de hidrocarburos y NOx en las zonas urbanas son primordialmente los vehículos”.
            .row.justify-content-center.mt-3
              .col-lg-8
                .jumbotron-4.p-3
                  p (Ministerio para la Transición Ecológica y el Reto Demográfico, 2016)
              .col-lg-4
                
          .col-lg-4
            figure
              img.mx-2(src="@/assets/curso/images/tema4/img_9.svg",  alt='', style="width:300px; display:block; margin:auto 0 ;").my-3


      .py-4.py-md-5(titulo="Ozono troposférico (O3)" :icono="require('@/assets/curso/images/tema4/ico_17.svg')")
        .row.justify-content-center.align-items-center
          .col-lg-8
            h4 Ozono troposférico (O3)
            p En Colombia, la Resolución 909 de 2008, por la cual se establecen los estándares de emisiones industriales a nivel nacional, establece la principal actividad antrópica generadora de estos contaminantes tipo criterio. Es importante reconocer qué tipo de procesos son generadores de estos compuestos. A continuación, se presenta un fragmento de la tabla 3 de las actividades industriales y contaminantes a monitorear por actividad industrial.
            .row.justify-content-center.mt-3
              .col-lg-8
                .jumbotron-4.p-3
                  p (Ministerio para la Transición Ecológica y el Reto Demográfico, 2016)
              .col-lg-4
                
          .col-lg-4
            figure
              img.mx-2(src="@/assets/curso/images/tema4/img_10.svg",  alt='', style="width:300px; display:block; margin:auto 0 ;").my-3


    .row.align-items-center.aling.my-5
      .col-lg-10              
        .row.justify-content-center
          .col-md-6.col-lg.mb-5.mb-lg-0(data-aos="fade-right")  
            .tarjeta-avatar
              img.mt-3(src="@/assets/curso/images/tema4/ico_18.svg",  alt='', style="width:90px; display:block; margin:auto 0 ;")
              .tarjeta-2.p-5.h-100
                h4.mb-3  Plomo (Pb)
                p “Este contaminante proviene de la combustión de gasolinas con plomo, de la minería y fundiciones, y de la incineración de residuos. El plomo puede depositarse en el agua y alimentos que consumimos, por lo que puede ser absorbido por nuestro cuerpo”. 

          .col-md-6.col-lg.mb-5.mb-lg-0(data-aos="fade-left")
            .tarjeta-avatar
              img.mt-3(src="@/assets/curso/images/tema4/ico_19.svg",  alt='', style="width:90px; display:block; margin:auto 0 ;")
              .tarjeta-2.p-5.h-100
                h4.mb-3 Ozono troposférico (O3)
                p.mb-2 “Se trata del principal componente del smog fotoquímico y uno de los más fuertes agentes oxidantes. El ozono se forma en la tropósfera y de la acción de esta en las moléculas de ozono en la estratósfera, como producto de la reacción entre los NOX, los COV y los hidrocarburos (HC) en presencia de radiación solar. Las fuentes de hidrocarburos y NOx en las zonas urbanas son primordialmente los vehículos”.
                p (Ministerio de Medio Ambiente. Gobierno de Chile, 2018)


    .row.mb-5.ps-2(data-aos="zoom-in-down")
      .col-lg-3.bg-color-3.px-4.py-2
        .h4.mb-0.text-white Estándares de emisiones en Colombia

    p.mb-3 En Colombia, la Resolución 909 de 2008, por la cual se establecen los estándares de emisiones industriales a nivel nacional, establece la principal actividad antrópica generadora de estos contaminantes tipo criterio. Es importante reconocer qué tipo de procesos son generadores de estos compuestos. A continuación, se presenta un fragmento de la tabla 3 de las actividades industriales y contaminantes a monitorear por actividad industrial.

    Separador

    #t_4_3.titulo-segundo
      .h2 4.3 Afectación de los contaminantes
    
    p.mb-3 Teniendo en cuenta que los principales contaminantes atmosféricos son los denominados “criterio”, que son los que afectan la salud humana, se analizarán cuáles son las principales afecciones y sus características.

    p Principales afectaciones en la salud y el ambiente por contaminantes: 

    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")(data-aos="fade-up")
      div(titulo="Material Particulado (MP).")
        .row.align-items-center.justify-content-center.p-4
          .col-lg-12
            p.mb-3 Por su tamaño, estas partículas son capaces de ingresar al sistema respiratorio, provocando potenciales daños a sus órganos principales. Mientras menor sea su diámetro, mayor será el potencial de daño a la salud humana. Las partículas de MP2,5 penetran hasta los alvéolos pulmonares e ingresan directamente al torrente sanguíneo, aumentando los riesgos de mortalidad prematura. En general, el MP puede también dañar las plantas, inhibir el crecimiento de la vegetación y corroer materiales.
        

      div(titulo="Impacto del monóxido de carbono (CO)")
        .row.align-items-center.justify-content-center.p-4
          .col-lg-12
            p.mb-3 Los NOx son responsables de importantes efectos sobre la salud y el medio ambiente, como problemas respiratorios o daño pulmonar, enfermedades en pulmones y bronquios, mayor susceptibilidad a las infecciones, daño celular, irritación ocular y pérdida de las mucosas. El NO2 puede reaccionar con la humedad presente en la atmósfera para formar ácido nítrico, que puede ser causa de corrosión de las superficies metálicas y detener el crecimiento de plantas.

      
      div(titulo="Óxidos de azufre (SOx).")
        .row.align-items-center.justify-content-center.p-4
          .col-lg-12
            p.mb-3 Estos gases pueden alterar el funcionamiento de los bronquios, producir daño pulmonar y a las vías respiratorias, irritación ocular y paros cardíacos en personas. Concentraciones altas de SO2 pueden conducir a lesiones crónicas en plantas, mientras que producen daño al medio ambiente al inhibir el crecimiento de vegetación.

      div(titulo="Compuestos Orgánicos Volátiles (COV).")
        .row.align-items-center.justify-content-center.p-4
          .col-lg-12
            p.mb-3 Estos compuestos pueden producir irritación de ojos, garganta y pulmones, así como inhibición del crecimiento de las plantas. También se asocia a una mayor probabilidad de desarrollar leucemia y otros tipos de cáncer.
        

      div(titulo="Plomo (Pb).")
        .row.align-items-center.justify-content-center.p-4
          .col-lg-12
            p.mb-3 Este contaminante proviene de la combustión de gasolina con plomo, de la minería y fundiciones, y de la incineración de residuos. El plomo puede depositarse en el agua y alimentos que consumimos, por lo que puede ser absorbido por nuestro cuerpo.

      
      div(titulo="Ozono troposférico (O3).")
        .row.align-items-center.justify-content-center.p-4
          .col-lg-12
            p.mb-3 Su toxicidad ocurre en continuo, a mayores concentraciones se generan efectos más nocivos. Provocan tos y dolores de cabeza, irritación de ojos, nariz y garganta, incremento de la mucosidad, estertores, cierre de las vías respiratorias, dolores de tórax, languidez, malestar y náuseas, con aumento en la incidencia de ataques asmáticos. También puede agravar enfermedades crónicas del corazón.
            p (Ministerio de Medio Ambiente. Gobierno de Chile, 2018)


    Separador

    #t_4_3.titulo-segundo
      .h2 4.4 La Calidad del aire y su seguimiento

    p.mb-3 Para saber cómo es la calidad del aire que respiramos, es importante conocer su estado, y más cuando es lo que nos afecta directamente, ya que el aire es un componente vital para el ser humano.

    p.mb-5 Según el marco normativo establecido en Colombia: la Resolución 601 de 2006 del MAVDT; Resolución 610 de 2010 del MAVDT; Informe del estado de la calidad del aire en Colombia 2007-2010; Informe del estado del medio ambiente y de los recursos naturales renovables; Comunidad Andina –CAN; se establece la incorporación de la herramienta Índice de Calidad del Aire, mejor conocida por sus siglas como ICA.  

    .row.align-items-center.aling
      .col-lg-10(data-aos="zoom-in-down")
        .tarjeta.color-primario.p-4.mb-5
          .row.justify-content-center.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/images/tema4/ico_20.svg",  alt='', style="width:60px; display:block; margin:auto 0 ;")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 Contaminación del Aire
                  p.text-small Para contextualizar el contenido, es posible visualizar el siguiente video: https://www.youtube.com/watch?v=FtKg9zJ6oNQ
                .col-md-auto
                  a.boton.color-acento-contenido.texto-blanco(href="https://www.youtube.com/watch?v=FtKg9zJ6oNQ" target="_blank")
                    span Ver
                    .row
                      .col-auto
                        img.mx-2(src="@/assets/curso/images/tema4/ico_video_1.svg",  alt='', style="width:20px; display:block; margin:auto 0 ;")

   
    .row.justify-content-center.align-items-center.mb-5
      .col-12.col-lg-5.mb-5.mb-lg-0(data-aos="fade-right")
        h3 ICA
        p.mb-3 Según el Instituto de Hidrología, Meteorología y Estudios Ambientales – IDEAM, en su hoja metodología de la calidad del aire, establece que “el Índice de calidad del aire (ICA) permite comparar los niveles de contaminación del aire de las estaciones de monitoreo que conforman un Sistema de Vigilancia de Calidad del Aire (Unidades espaciales de referencia), en un tiempo t, que corresponde al período de exposición previsto en la norma para cada uno de los contaminantes que se está midiendo”. 

      .col-12.col-lg-5.mb-5.mb-lg-0(data-aos="fade-left")
        img(src='@/assets/curso/images/tema4/img_11.png' alt="")

      .row.justify-content-star.mt-3
        .col-lg-6
        .col-lg-4
          .jumbotron-4.p-3
            p.mb-0 (IDEAM, 2012)


    .row.mb-5.ps-2(data-aos="zoom-in-down")
      .col-lg-3.bg-color-4.px-4.py-2
        .h4.mb-0.text-white Contexto nacional

    p.mb-3 Teniendo en cuenta los contaminantes que son monitoreados en el país, las características de los combustibles que se distribuyen y los equipos que actualmente se encuentran en las SVCA, el índice se calcula de manera independiente para cada uno de los seis principales contaminantes, los cuales son PM10, PM2,5, SO2, NO2, O3 y CO. 

    .row.justify-content-center.align-items-center
      .col-12.col-lg-10
        hr
      .col-12.col-lg-6.mb-5.mb-lg-0(data-aos="fade-right")
        
        .bloque-texto-b.color-custom-6.p-4
          .bloque-texto-b__texto
            i.fas.fa-quote-left
            p.mb-0 “Los valores del ICA se ubican en una escala adimensional de 0 a 500, agrupados en 6 rangos que guardan estrecha relación con la amenaza que, a la salud humana, representan dichos niveles de contaminación del aire. Para facilitar su interpretación cada uno de estos rangos ha sido asociado a un color que sirve de alerta”. 
            i.fas.fa-quote-right 

        .bloque-texto-b.color-custom-6.p-4
          .col-12.col-lg-12
            hr
          .bloque-texto-b__texto
            i.fas.fa-quote-left
            p.mb-0 “En la Tabla No. 1, se presentan los rangos en los que han sido clasificados los valores que puede tomar el Índice, junto con el color que le fue asignado para identificar de forma sencilla la alerta que representa el nivel de contaminación”.
            i.fas.fa-quote-right 

      .col-12.col-lg-4.mb-lg-0(data-aos="fade-left")
        img(src='@/assets/curso/images/tema4/img_12.svg' alt="")
      

    .row.mb-5.ps-2(data-aos="zoom-in-down")
      .col-lg-3.bg-color-4.px-4.py-2
        .h4.mb-0.text-white Acciones preventivas

    p.mb-3 Es muy importante conocer qué acciones preventivas debemos ejecutar cuando se conocen los diferentes estados de la concentración de los contaminantes presentes en el aire que respiramos. La hoja metodológica versión 1 (IDEAM, 2012) “establece las diferentes acciones a ejecutar, la cuales están contenidas en los niveles de contaminación del aire reflejados por cada uno de los rangos del ICA para los cuales determinan un conjunto de acciones preventivas que se recomienda sean tenidas en cuenta por la población”. 

    p.mb-5 De esta manera, se puede evidenciar en el ejemplo (Tabla 2), cuáles son las acciones que se deben ejecutar dependiendo del color y el contaminante que se esté monitoreando. Así podremos realizar una vigilancia más pertinente del estado del aire en nuestro país

    .row.align-items-center.aling
      .col-lg-10(data-aos="zoom-in-down")
        .tarjeta.color-primario.p-4.mb-5
          .row.justify-content-center.align-items-center
            .col-3.col-sm-2.col-lg-1
              img(src="@/assets/curso/images/tema4/ico_20.svg",  alt='', style="width:60px; display:block; margin:auto 0 ;")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h3.mb-1 Secretaría de Ambiente lanza sistema que alerta el estado de calidad del aire.
                  p.text-small Para contextualizar este contenido, se puede visualizar el video del siguiente enlace: https://www.youtube.com/watch?v=aW8Wuxxbv6E
                .col-md-auto
                  a.boton.color-acento-contenido.texto-blanco(href="https://www.youtube.com/watch?v=aW8Wuxxbv6E" target="_blank")
                    span Ver
                    .row
                      .col-auto
                        img.mx-2(src="@/assets/curso/images/tema4/ico_video_1.svg",  alt='', style="width:20px; display:block; margin:auto 0 ;")


    p.mb-3 Para profundizar en lo estudiado hasta este punto, se invita a visitar el sitio sugerido en el siguiente recurso. Esta acción es de suma importancia. Se deben tener presentes todos los elementos de aplicación que se encuentre y tomar nota atenta de todo ello.

    .row.align-items-center.justify-content-center.mb-3     
      .col-lg-12(data-aos="fade-up")
        .jumbotron.mb-3.p-5
          .row.justify-content-center.align-items-center.px-2
            .col-lg-5.mb-0
              img(src="@/assets/curso/images/tema4/tox.svg",  alt='', style="width:350px; display:block; margin:auto 0 ;").mb-5
            .col-lg-5
              h3.mb-3 Calidad del aire y su seguimiento
              p.mb-3  A continuación, se invita a ingresar al siguiente link interactivo que le permitirá visualizar el estado de la calidad del aire y establecer las medidas de prevención mediante el índice de la calidad del aire.
              .row.align-items-center.aling
                .tarjeta-3.p-4.mb-5
                  .row.justify-content-center.align-items-center
                    .col
                      .row.justify-content-center.align-items-center
                        .col.mb-3.mb-sm-0
                          p.aling.text-small.text-white http://iboca.ambientebogota.gov.co
                        .col-md-auto
                          a.boton.color-acento-contenido.texto-blanco(href=" http://iboca.ambientebogota.gov.co/" target="_blank")
                            span Ver
                            .row
                              .col-auto
                                img.mx-2(src="@/assets/curso/images/tema4/ico_video_1.svg",  alt='', style="width:20px; display:block; margin:auto 0 ;")














</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({}),
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
