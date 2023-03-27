<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.justify-content-center.align-items-end.mb-5
      .col-lg-8
        .row.justify-content-center.align-items-center.mb-3
          .col-lg-2.mb-lg-0.mb-3
            img(src='@/assets/curso/images/intro/1.svg', alt='')
          .col-lg-10
            p La contaminación atmosférica se ha convertido en una problemática que actualmente tiene a todo el planeta y nuestra sociedad en una total incertidumbre climática. El impacto que generan las diferentes actividades antrópicas, cuyas consecuencias se ven representadas en la situación actual que ambientalmente estamos viviendo, trae cambios climáticos y situaciones atmosféricas complejas (incendios forestales devastadores, inundaciones catastróficas, tormentas demoledoras, nevadas extremas, ciclones y huracanes trágicos, entre otros).
        .cajon.color-acento-contenido.p-4
          p.mb-0 Otras situaciones climáticas muestran cómo se deteriora con gran velocidad la armonía de los ecosistemas en nuestro planeta; estas situaciones influyen directamente en las actividades que regulan al hombre, como la consecución de los alimentos, la proyección de la infraestructura, la comunicación, el transporte, la educación, la sociedad y la generación de nuevas políticas que son determinantes en la nueva dirección que se le dará a las próximas generaciones, que serán quienes continúen con este legado o definitivamente den el cambio en la dirección correcta para que el planeta renazca y vuelvan a vivir en armonía hombre y naturaleza.
      .col-lg-4: img(src='@/assets/curso/images/intro/2.png', alt='')
    p.mb-5(data-aos='fade-right') De ahí la importancia que tienen estas unidades temáticas y el desarrollo del componente formativo. La verificación de las emisiones resultantes de procesos y operaciones productivas se convierte en la base del contenido que se verá a profundidad para desarrollar el diagnóstico de la problemática atmosférica que se presenta en la organización y/o proyecto.
      br
      br
      |Para la elaboración de este componente, se abordaron varios autores conocidos en contaminación atmosférica, de quienes se han citado y referenciado conceptos y ejemplos para los fines educativos de esta materia, en el entendido que el conocimiento es social y, por lo tanto, es para usarlo por quienes necesitan adquirirlo. Se espera que este documento sea útil para todos, aprendices y lectores en general, que estén interesados en acercarse a asuntos básicos de prevención y control ambiental.
    


</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>
<style lang="sass"></style>
