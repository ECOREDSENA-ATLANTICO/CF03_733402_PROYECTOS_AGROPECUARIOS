<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Estudio de mercado
      
    .row.align-items-center.justify-content-center.mb-2
      .col-lg-5.mb-3(data-aos="fade-right")
        img.mt-3(src='@/assets/curso/images/tema1/img_1.png'  alt='')
      .col-lg-7.mb-3(data-aos="fade-left") 
        p.mb-3 El estudio de mercado tiene como finalidad hallar y cuantificar el fragmento de demanda que no ha sido cubierta por la oferta y que puede abastecerse con el producto generado en el proyecto agropecuario.
        
        .cajon.color-secundario.p-4.ps-5.bg_18.mb-4.mb-lg-0
          p.mb-5 Cuando se hace referencia al mercado, se está hablando de los factores que influyen en este y la comercialización del bien agrícola o pecuario que será objeto del proyecto; para el desarrollo de este estudio se debe hacer referencia de la identificación del bien (piscicultura, ganadería de leche o de carne, cacao, arándano).

      p.mb-5 En el análisis de mercado es necesario conocer las preferencias de los consumidores, identificar quienes van a proveer los insumos necesarios para el proceso de producción, transporte de insumos y productos, conocer la normatividad que rige el sector o que es necesaria para iniciar el trámite para exportación si es del caso, además de los requerimientos técnicos, sanitarios y legales del país donde va a ser enviado el producto.
    
    .row.justify-content-center.align-items-center.mb-3
      h3.text-center Se debe recordar que las funciones del mercadeo son: 
      figure.mb-3
        img.mt-3(src='@/assets/curso/images/tema1/img_2_1.png'  alt='')
      p.mb-3 De manera alterna se debe identificar variables como: el precio, origen, calidad, disponibilidad en el mercado local o regional de los insumos que son necesarios para la producción del bien que se pretende producir.


    .row.justify-content-center.align-items-center.mb-2
      .col-lg-12.mb-5
        .bloque-texto-g.bloque-texto-g--inverso.color-primario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/images/tema1/img_2.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 El siguiente componente formativo denominado “Riego y drenaje”, desarrolla las temáticas enfocadas al diseño e implementación del sistema de riego y drenaje del cultivo; se puede explorar más en profundidad en el siguiente video:
    
    Separador
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
