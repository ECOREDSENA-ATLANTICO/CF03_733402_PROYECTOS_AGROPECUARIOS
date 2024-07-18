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
          p.mb-0 Cuando se hace referencia al mercado, se está hablando de los factores que influyen en este y la comercialización del bien agrícola o pecuario que será objeto del proyecto; para el desarrollo de este estudio se debe hacer referencia de la identificación del bien (piscicultura, ganadería de leche o de carne, cacao, arándano).

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

    #t_1_1.titulo-segundo
      .h2(data-aos="fade-right") 1.1 Identificación del bien o servicio
    
    .row.align-items-center.justify-content-center.mb-2
      .col-lg-5.mb-3(data-aos="fade-right")
        img.mt-3(src='@/assets/curso/images/tema1/img_1.png'  alt='')
      .col-lg-7.mb-3(data-aos="fade-left") 
        p.mb-3 El primer factor es la identificación del bien, en este aspecto se debe hacer una caracterización detallada de las condiciones que va a presentar el producto en el momento de la venta al destino final; para la identificación inicialmente debemos tener presente a qué sector productivo pertenece el producto agropecuario.
        
        .cajon.color-acento-contenido.p-4.ps-5.bg_18.mb-4.mb-lg-0
          p.mb-0 En Colombia se han identificado tres sectores productivos que son: 

    //- img.mt-3(src='@/assets/curso/images/tema1/img_1.png'  alt='')
    
    .row.align-items-center.justify-content-center.mb-2
      .col-lg-7.mb-3(data-aos="fade-left") 
        p.mb-3 En el estudio de mercado del sector agropecuario (primario), se debe tener en cuenta que los productos o bienes que son objeto de comercialización son organismos vivos, por lo tanto, para la identificación del producto se debe tener en cuenta características que le otorgan valor en el mercado como: el grado de madurez, la firmeza, color, presentación, peso o si es un producto transformado que necesita condiciones de conservación específicas; en este componente se debe identificar los parámetros que generan valor en el producto y o van a diferenciar del producto de la competencia.
        
        .cajon.color-acento-contenido.p-4.ps-5.bg_18.mb-4.mb-lg-0
          .row
            .col-md-2
              img.mt-1(src='@/assets/curso/images/tema1/img_1.png'  alt='')
            .col-md-10
              p.mb-0 Una posible caracterización para los productos agrícolas y pecuarios es el que se propone a continuación:
      
      .col-lg-5.mb-3(data-aos="fade-right")
        img.mt-3(src='@/assets/curso/images/tema1/img_1.png'  alt='')
      
    .row.align-items-center.justify-content-star.mb-1.ps-2(data-aos="zoom-in-down")
      .col-lg-10.bg-color-1.px-3.py-2.mb-5
        .h3.mx-5.mb-0.mt-4 Sector
    
      p.mb-3 Aquí se debe identificar el sector productivo al que pertenece el producto o servicio; si pertenece al primario agropecuario se puede clasificar de la siguiente forma:

    .row.align-items-center.justify-content-star.mb-1.ps-2(data-aos="zoom-in-down")
      .col-md-4 
        img(src='@/assets/curso/images/tema1/img_1.png'  alt='')
      .col-md-8 
        .col-sm
          h4 Agrícola
          ul.lista-ul--color.lista-ul--separador
            li 
              i.fas.fa-angle-right
              | <b> Frutos: </b> pomo (manzana y níspero, entre otros), vainas en fresco (frijol y habas, entre otros), cereza (uva y tomate, entre otros), agregado (fresa, mora, frambuesa), colectivo (piña e higo), aguacate, arándano, plátano, banano.
            li 
              i.fas.fa-angle-right
              | <b> Semillas: </b> cariópside (trigo, maíz), frijol, arveja, cacao, café.
            li 
              i.fas.fa-angle-right
              | <b> Estructuras vegetativas: </b> tallos (apio, palmito y espárragos), hojas (lechuga y acelga, entre otros).
            li 
              i.fas.fa-angle-right
              | <b> Estructuras reproductivas: </b>  flores ornamentales, coliflor y brócoli.
            li 
              i.fas.fa-angle-right
              | <b> Estructuras subterráneas: </b> raíces (zanahoria y remolacha, entre otros), tubérculos (papa), rizomas (jengibre). (Puentes, 2011, p.46). Adaptación realizada por el autor, 2021.

    .row.align-items-center.justify-content-star.mb-4.ps-2(data-aos="zoom-in-down")
      .col-md-8 
        .col-sm
          h4 Pecuario
          ul.lista-ul--color.lista-ul--separador
            li 
              i.fas.fa-angle-right
              | <b> Subproductos agropecuarios:</b> huevos, derivados lácteos, cueros.
            li 
              i.fas.fa-angle-right
              | <b> Especies menores </b>
            li 
              i.fas.fa-angle-right
              | <b> Ganado doble propósito </b>
            li 
              i.fas.fa-angle-right
              | <b> Ganado lechero </b>
            li 
              i.fas.fa-angle-right
              | <b> Ganado para carne. </b> (Puentes, 2011, p.46). Adaptación realizada por el autor, 2021.
      
      .col-md-4 
        img(src='@/assets/curso/images/tema1/img_1.png'  alt='')
      

    .row.align-items-center.justify-content-center.mb-3.ps-2(data-aos="zoom-in-down")
      .col-lg-10.mb-5
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center.p-3
            .col-auto
              img(src="@/assets/curso/images/tema1/img_1.png").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Identificación del bien o servicio
                  p.mb-0 Estimado aprendiz, para la identificación inicialmente debemos tener presente a qué sector productivo pertenece el producto agropecuario. A continuación más detalle a través del siguiente video: 
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://docs.google.com/document/d/1PPRatnr8cI2Hxkv8hzg_e3qw3N0FVQs3yvO0rZLNaJE/edit?usp=sharing" target="_blank")
                    span Ver video
                    i.fas.fa-file-video

    .tarjeta.tarjeta--azul.p-4
      SlyderA(tipo="b")
        .row
          .col-md-6.mb-4.mb-md-0
            p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.

          .col-md-6
            figure
              img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
              figcaption Leyenda de la imagen

        .row.justify-content-center.align-items-center.my-lg-4
          .col-md-6
            figure
              img(src='@/assets/template/img-placeholder.svg', alt='Texto que describa la imagen')
              figcaption Leyenda de la imagen

          .col-md-6.mb-4.mb-md-0
            p This is another paragraph. I think it needs to be added that the set of elements tested is not exhaustive in any sense. I have selected those elements for which it can make sense to write user style sheet rules, in my opionion.

    Separador
    
    #t_1_2.titulo-segundo
      .h2(data-aos="fade-right") 1.2 Identificación de la demanda
    
    .row.align-items-center.justify-content-center.mb-2
      .col-lg-5.mb-3(data-aos="fade-right")
        img.mt-3(src='@/assets/curso/images/tema1/img_1.png'  alt='')
      .col-lg-7.mb-3(data-aos="fade-left") 
        p.mb-3 Cuando se realiza el estudio de la demanda se hace una labor de búsqueda de información la cual debe ser sistemática, enfocada en registrar eventos como cantidad de producto que puede llegar a ser vendido, cantidad de producto que una comunidad puede llegar a adquirir, analizar los precios, identificar los gustos o preferencias y la capacidad de compra de los consumidores.
        
        .cajon.color-acento-contenido.p-4.ps-5.bg_18.mb-4.mb-lg-0
          .row
            .col-md-3
              img.mt-1(src='@/assets/curso/images/tema1/img_1.png'  alt='')
            .col-md-9
              p.mb-0 La información recolectada y analizada al finalizar la identificación de la demanda aporta elementos básicos para el estudio técnico, esto se traduce en el tamaño o la capacidad de producción, esta información describe la disponibilidad de insumos lo que debe concordar con otros elementos como la capacidad financiera, técnica y administrativa.
    
    .row.justify-content-center.align-items-center.mb-2
      .col-lg-12.mb-5
        .bloque-texto-g.bloque-texto-g--inverso.color-primario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/images/tema1/img_2.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Para orientar mejor el estudio de la demanda debemos reconocer el objetivo, este depende de la intención del formulador del proyecto, puede ser para la generación de ingresos caso en el que se busca una retribución económica satisfaciendo el interés privado o por el contrario puede plantearse un objetivo que solicite el bienestar de una comunidad (social), en este caso el proyecto generaría unos impactos positivos en un grupo de personas o región, sin perseguir la retribución económica.
    
    .row.align-items-center.justify-content-center.mb-2
      .col-lg-4.mb-3(data-aos="fade-right")
        img.mt-3(src='@/assets/curso/images/tema1/img_1.png'  alt='')
      .col-lg-8.mb-3(data-aos="fade-left") 
        .cajon.color-primario.p-4.ps-5.bg_18.mb-4.mb-lg-0
          p.mb-0 En el desarrollo del análisis de la demanda, se debe determinar la población objetivo, es el grupo de personas a las cuales se les desea vender el producto, esta población debe caracterizarse teniendo en cuenta valores como edad, sexo, nivel escolar, estado civil, tamaño de la población (número de personas), tasa de crecimiento; además se debe obtener información sobre nivel actual del ingreso y establecer la zona de influencia que es identificar en lo posible sobre un mapa la zona geográfica en la que se desea comercializar el producto objeto del proyecto; la información anterior también es conocida como área de mercado.
        
    .row.align-items-center.justify-content-center.mb-2
      .col-lg-7.mb-3(data-aos="fade-right") 
        p.mb-1 Otra de las variables que es de gran importancia en el estudio de la demanda es el comportamiento del precio del producto a través de los años; para esto una de las formas de determinar los momentos de mayor o de menor oferta y de mejores o menores precios es utilizando las series de volúmenes de producto comercializado y las series de precios al consumidor.
        .bloque-texto-b.bg-02.p-4
          .bloque-texto-b__texto
            i.fas.fa-quote-left
            p.mb-0 Todos los mercados están compuestos por una serie de submercados o “segmentos” de consumidores que tienen entre ellos características comunes de tipo demográfico, geográfico, psicológico, económico, étnico, cultural, etc. <br>
            p.mb-1 <b> - (Miranda, 2005, p.99).</b>
            i.fas.fa-quote-right
      .col-lg-5.mb-3(data-aos="fade-left")
        img.mt-3(src='@/assets/curso/images/tema1/img_1.png'  alt='')
      
      p.mb-0 La “segmentación” del mercado permite, entonces, organizar y clasificar la demanda, de acuerdo a ciertos y determinados atributos; en efecto, este proceso nos conduce a conocer, entre otros:

      figure.mb-3
        img.mt-3(src='@/assets/curso/images/tema1/img_2_1.png'  alt='')
    
    .row.align-items-center.justify-content-center.mb-3.ps-2(data-aos="zoom-in-down")
      .col-lg-10.mb-5
        .tarjeta.color-primario.p-3
          .row.justify-content-around.align-items-center.p-3
            .col-auto
              img(src="@/assets/curso/images/tema1/img_1.png").img65
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h4.mb-1 Recurso PDF
                  p.mb-0 Infografía - Identificación de la demanda.
                .col-sm-auto
                  a.boton.color-acento-botones(href="https://docs.google.com/document/d/1PPRatnr8cI2Hxkv8hzg_e3qw3N0FVQs3yvO0rZLNaJE/edit?usp=sharing" target="_blank")
                    span Descargar
                    i.fas.fa-file-pdf

    Separador  
    
    #t_1_3.titulo-segundo
      .h2(data-aos="fade-right") 1.3 Identificación de la oferta
      
    .row.align-items-center.justify-content-center.mb-2
      .col-lg-3.mb-3(data-aos="fade-right")
        img.mt-3(src='@/assets/curso/images/tema1/img_1.png'  alt='')
      .col-lg-9.mb-3(data-aos="fade-left") 
        p.mb-1 En la identificación de la oferta se busca establecer la cantidad de producto que se necesita para cubrir la demanda o necesidades de una población en el futuro; esa no es una labor fácil debido a que para tener una aproximación real es necesario tener la información de la competencia para poder tener una visión global de la cantidad de producto sembrado y por lo tanto estimar la posible cantidad (oferta) de producto a ofrecer.
        .bloque-texto-b.bg-02.p-4
          .bloque-texto-b__texto
            i.fas.fa-quote-left
            p.mb-0 La oferta es también una variable que depende de otras, tales como: los costos y disponibilidad de los insumos, las restricciones determinadas por el gobierno, los desarrollos tecnológicos, las alteraciones del clima (especialmente en la oferta agrícola y agroindustrial), los precios de los bienes sustitutos y complementarios, la capacidad instalada de la competencia, etc. <br>
            p.mb-1 <b> - (Miranda, 2005, p.99).</b>
            i.fas.fa-quote-right
    
    p.mb-2 Para iniciar la identificación de la oferta, es necesario generar una lista con los datos de los proveedores de insumos con la siguiente información:
      
    figure.mb-3
        img.mt-3(src='@/assets/curso/images/tema1/img_2_1.png'  alt='')
    
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
