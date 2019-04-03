<template>
  <div>
    <div class="episode">
      <div class="container">
        <div class="columns is-2">
          <div class="column episode__video">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/uBco8a6odH4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
          <div class="column episode__content">
            <div class="episode__content__title">Ultraman</div>
            <div class="episode__content__date">26 de Marzo</div>
            <div class="episode__content__date">Sesión y entrevista en vivo</div>
          </div>
        </div>
      </div>
    </div>

    <div class="episode">

      <div class="container inverted">
        <div class="columns ">
          <div class="column episode__content">
            <div class="episode__content__title">Maskatesta</div>
            <div class="episode__content__date">2 de Abril</div>
            <div class="episode__content__date">Sesión y entrevista en vivo</div>
          </div>

          <div class="column episode__video">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/OPc8xvJUKDQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
  .episode{ padding: 100px 0; display: block; }
  .episode__content{ color: #FFF; margin-top: auto; }
  .episode__content__title{ font-size: 100px; transform: translateX(-10%) }
  /* .episode__content__date{ text-align: right } */
  iframe{ height: 129%; }

  .inverted .episode__content{ text-align: right; }
  .inverted .episode__content__title{ font-size: 100px; transform: translateX(10%) }
  /* .inverted .episode__content__date{ text-align: left } */
</style>
