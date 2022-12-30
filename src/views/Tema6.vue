<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Marco normativo


    .row.justify-content-center.align-items-center.mb-4
      .col-lg.order-2.order-lg-1(data-aos="fade-right") 
        .custom_box_right.mt-5
          p.mx-5 El marco normativo que regula la contaminación del aire en nuestro país es muy importante para establecer las acciones de prevención y control de los contaminantes que nos afectan en la actualidad. En esta sección, se presentan las leyes, decretos, resoluciones, protocolos y demás documentación vigente.
      .col-auto.onTop.order-1.order-lg-2(data-aos="fade-left")
        img(src="@/assets/curso/images/tema6/img_1.png" alt='AvatarTop', style="width:350px;")
    
    Separador

    #t_6_1.titulo-segundo
      .h2 6.1 Contaminación y calidad ambiental

    p.mb-5 Es importante definir cómo la regulación ambiental marca el camino de la conciencia ambiental en nuestro país, según el Instituto De Hidrología Meteorología Y Estudios Ambientales –IDEAM… “el control de la contaminación en Colombia comienza con la generación de datos e información.  La caracterización de la calidad ambiental que es su equivalente, constituye uno de los más importantes procesos de desarrollo de información orientados a un amplio margen de tomadores de decisiones que van desde el ciudadano del común que busca optimizar sus medios de vida, hasta los altos funcionarios del Estado que deben tomar decisiones de política pública relacionada con grandes grupos poblacionales, especialmente los que habitan las zonas urbanas. “(IDEAM, 2014)”.

    h4.mb-5 Normas Asociadas

    .row.justify-content-center
      .col-lg-10(data-aos="zoom-in-down")
        ImagenInfografica.color-secundario.mb-5
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/images/tema6/info.svg')
          .tarjeta.color-custom-info-1.p-3(x="9%" y="18%" numero="")
            h3.text-center Decreto 1600 de 1994. 
            p.mb-0.text-center Por el cual se reglamenta parcialmente el Sistema Nacional Ambiental (SINA) en relación con los Sistemas Nacionales de Investigación Ambiental y de Información Ambiental.
          .tarjeta.color-custom-info-1.p-3(x="29.7%" y="84%" numero="")
            h3.text-center Decreto 1200 de 2004
            p.mb-0.text-center Por el cual se determinan los Instrumentos de Planificación Ambiental y se adoptan otras disposiciones.

          .tarjeta.color-custom-info-1.p-3(x="50%" y="15%" numero="")
            h3.text-center Resolución 0941 de 2009
            p.mb-0.text-center Por la cual se crea el subsistema de información sobre uso de los recursos naturales renovables – SIUR y se adopta el Registro Único Ambiental RUA.
            
          .tarjeta.color-custom-info-1.p-3(x="70.5%" y="84%" numero="")
            h3.text-center Decreto 2041 de 2014
            p.mb-0.text-center  Por el cual se reglamenta el Título VIII de la Ley 99 de 1993 sobre licencias ambientales.

          .tarjeta.color-custom-info-1.p-3(x="90.8%" y="16%" numero="")
            h3.text-center Decreto 1076 de 2015
            p.mb-0 Por medio del cual se expide el decreto único reglamentario del sector ambiental y desarrollo sostenible.

    Separador
    #t_6_2.titulo-segundo
      .h2 6.2 Contaminación atmosférica

    p.mb-3 “La contaminación atmosférica es la presencia que existe en el aire de pequeñas partículas o productos secundarios gaseosos que pueden implicar riesgo, daño o molestia para las personas, plantas y animales que se encuentran expuestas a dicho ambiente.”                     

    .row.align-items-star.justify-content-center.mb-3(data-aos="zoom-in-down")    
      .col-lg-6.mb-3
        img(src='@/assets/curso/images/tema6/img_2.svg')
      .col-lg-6
        .jumbotron-3.mb-3.p-4
          .row.justify-content-center.align-items-center.p-2
            h3 Normas asociadas.
            ul.lista-ul
              li 
                i.fas.fa-check.c-check
                | Decreto 948 de 1995. Por el cual se reglamentan, parcialmente, la Ley 23 de 1973, los artículos 33, 73, 74, 75 y 76 del Decreto - Ley 2811 de 1974; los artículos 41, 42, 43, 44, 45, 48 y 49 de la Ley 9 de 1979; y la Ley 99 de 1993, en relación con la prevención y control de la contaminación atmosférica y la protección de la calidad del aire.
              li
                i.fas.fa-check.c-check
                | Decreto 979 de 2006.  Por el cual se modifican los artículos 7,10, 93, 94 y 108 del Decreto 948 de 1995.
              li 
                i.fas.fa-check.c-check
                | Política para la prevención y control de la contaminación del aire.
          .row.justify-content.mt-5.p-1
            .col-lg-2
            .col-lg-10
              p.mb-5 Nota. Tomada de Cárdenas (2020). Sectores Normativos.
    Separador
    #t_6_3.titulo-segundo
      .h2 6.3 Calidad del aire y su normativa
    
    .row.align-items-center.justify-content-center.mb-5  
      .col-lg-5.mb-3(data-aos="fade-right") 
        img(src='@/assets/curso/images/tema6/img_3.png'  alt='')
      .col-lg-7(data-aos="fade-left") 
        p.mb-3 Las normas de calidad del aire en Colombia se convierten en la base para el seguimiento. Así lo afirma el Instituto De Hidrología Meteorología Y Estudios Ambientales – IDEAM: “el monitoreo y control de la contaminación atmosférica ha tomado día a día mayor relevancia, debido a que, según cifras de la Organización Mundial de la Salud, una de cada ocho muertes ocurridas a nivel mundial, es ocasionada por la contaminación del aire. 

        p.mb-0 A nivel nacional, el Departamento Nacional de Planeación estimó que, durante el año 2015, los efectos de este fenómeno estuvieron asociados a 10.527 muertes y 67.8 millones de síntomas y enfermedades. Adicionalmente, los costos ambientales asociados a la contaminación atmosférica en Colombia, durante los últimos años, se incrementaron pasando de 1.1% del PIB de 2009 ($5.7 billones de pesos) a 1.59% del PIB de 2014 ($12 billones de pesos) y del 1.93% del PIB en 2015 ($15.4 billones de pesos), lo cual pone en evidencia la necesidad de seguir implementando estrategias para controlar, evaluar y monitorear estas sustancias.”

        p (IDEAM, 2014)

    .tarjeta--container.row.mb-5
      .col-md.tarjeta.color-custom-10.p-4(data-aos="fade-right") 
        .row.justify-content-center.p-5.mb-4
          .col-6
            figure
              img(src='@/assets/curso/images/tema6/ico_6.svg', alt="", style="width:180px; display:block; margin:0 auto;")
          
          .h2.text-center.mt-4.text-white Normas asociadas
          ul.lista-ul--color
            li 
              i.fas.fa-check.c-check
              p.text-white Resolución 2254 de 2017 Por la cual se adopta la norma de calidad del aire ambiente y se dictan otras disposiciones.
            li 
              i.fas.fa-check.c-check
              p.text-white Resolución 650 de 2010. Por la cual se adopta el Protocolo para el monitoreo y seguimiento de la calidad del aire.
            li 
              i.fas.fa-check.c-check
              p.text-white Resolución 2154 de 2010. Por la cual se ajusta el protocolo para el monitoreo y seguimiento de la calidad del aire adoptado a través de la Resolución 650 de 2010 y se adoptan otras disposiciones.

      .col-md.tarjeta.color-custom-11.p-4(data-aos="fade-left")
        .row.justify-content-center.p-5.mb-3
          .col-6
            figure
              img(src='@/assets/curso/images/tema6/ico_7.svg', alt="", style="width:180px; display:block; margin:0 auto;")
            br
          .h2.text-center  Protocolo asociado
          ul.lista-ul--color
            li 
              i.fas.fa-check.c-check
              p Protocolo para el monitoreo y seguimiento de la calidad del aire. 
            li 
              i.fas.fa-check.c-check
              p Manual de diseño de sistemas de vigilancia de calidad del aire.

    Separador
    #t_6_4.titulo-segundo
      .h2 6.4 Fuentes fijas 

    p.mb-4 Las fuentes fijas puntuales, mejor conocidas como “chimeneas” o ductos por donde se expulsan gases contaminantes (MP, SOx, NOx, CO, COV, entre otros) de las industrias que hacen parte del sector productivo que mueve la economía de nuestro país, aportan de manera importante al continuo deterioro de la calidad del aire que respiramos, especialmente en las principales ciudades del país; por esta razón, la normatividad asociada a las fuentes fijas es fundamental para el seguimiento y control de las emisiones en Colombia.

    .row.justify-content-center
      .col-lg-10.mb-5
        .row.justify-content-center.align-items-star.fondo-1.py-5.px-4
          h3 <u> Normas asociadas </u>
          .col-6.col-lg-2.mb-4.mb-lg-0
            img(src="@/assets/curso/images/tema6/ico_8.svg", alt="", style="width:80px; display:block; margin:0 auto;")
          .col-lg-4.mb-5.mb-lg-0(data-aos="fade-right")
            p.mb-3 Resolución 909 de 2008.  Por la cual se establecen las normas y estándares de emisión admisibles de contaminantes a la atmósfera por fuentes fijas y se dictan otras disposiciones.
          .col-lg-6.mb-3(data-aos="fade-left") 
            img(src="@/assets/curso/images/tema6/img_4.png")

    .row.justify-content-center
      .col-lg-10.mb-5(data-aos="zoom-in-down")
        .row.align-items-center.fondo-1.py-5.px-4
          h3.mb-5 <u> Métodos de medición y protocolos asociados </u>
          .col-lg-12
            img(src="@/assets/curso/images/tema6/img_5.png").mb-5
            ul.lista-ul
              li 
                i.fas.fa-check.c-check
                | Resolución 0935 de 2011 por la cual se establecen los métodos para la evaluación de emisiones contaminantes por fuentes fijas y se determina el número de pruebas o corridas para la medición de contaminantes en fuentes fijas.
              li
                i.fas.fa-check.c-check
                | Protocolo para el control y vigilancia de la contaminación atmosférica generada por fuentes fijas.
              li 
                i.fas.fa-check.c-check
                | Método 1 – Determinación del punto y velocidad de muestreo para fuentes estacionarias.
              li 
                i.fas.fa-check.c-check
                | Método 1A - Determinación del punto y velocidad de muestreo para fuentes estacionarias con ductos o chimeneas pequeñas.
              li
                i.fas.fa-check.c-check
                | Método 2 – Determinación de la velocidad y tasa de flujo volumétrica de gases en chimenea (Tubo Pitot tipo S).
              li 
                i.fas.fa-check.c-check
                | Método 3 – Análisis de gases para la determinación del peso molecular base seca.
              li
                i.fas.fa-check.c-check
                | Método 3B – Análisis de gases para la determinación del factor de corrección de tasa de emisión o exceso de aire.
              li 
                i.fas.fa-check.c-check
                | Método 4 – Determinación del contenido de humedad en gases de chimenea.
              li 
                i.fas.fa-check.c-check
                | Método 5 – Determinación de las emisiones de material particulado en fuentes estacionarias.
              li
                i.fas.fa-check.c-check
                | Método 6 – Determinación de las emisiones de dióxido de azufre en fuentes estacionarias.
              li 
                i.fas.fa-check.c-check
                | Método 7 – Determinación de las emisiones de óxidos de nitrógeno en fuentes estacionarias.
              li
                i.fas.fa-check.c-check
                | Método 12 – Determinación de las emisiones de plomo inorgánico en fuentes estacionarias.
              li 
                i.fas.fa-check.c-check
                | Número de pruebas o corridas para la medición de contaminantes.
    Separador
    #t_6_5.titulo-segundo
      .h2 6.5 Fuentes móviles
    
    p.mb-3 “Las emisiones por fuentes móviles se produce por la quema de combustibles fósiles utilizados por el parque automotor, ya que los vehículos automotores son los principales emisores de contaminantes como óxidos de nitrógeno, monóxido de carbono, hidrocarburos no quemados, dióxidos de azufre y compuestos orgánicos volátiles”.

    p.mb-5 (IDEAM, 2014)

    .row.justify-content-center
      .col-lg-10(data-aos="zoom-in-down")
        .jumbotron-9.p-4
          h3 <u> Normas asociadas </u>
          p.mb-3 Resolución 910 de 2008.  Por la cual se reglamentan los niveles permisibles de emisión de contaminantes que deberán cumplir las fuentes móviles terrestres, se reglamenta el Artículo 91 del Decreto 948 de 1995 y se adoptan otras disposiciones.

          p.mb-0 Resolución 1111 de 2013.  Por la cual se modifica la resolución 910 de 2008.












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
