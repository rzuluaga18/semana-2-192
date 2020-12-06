<template>
  <div>
      <banner-menu> </banner-menu>
    <div
      id="carouselExampleCaptions"
      class="carousel slide"
      data-ride="carousel"
    >
      <ol class="carousel-indicators my-4">
        <li
          data-target="#carouselExampleCaptions"
          data-slide-to="0"
          class="active"
        ></li>
        <li
          data-target="#carouselExampleCaptions"
          data-slide-to="1"
          class=""
        ></li>
        <li
          data-target="#carouselExampleCaptions"
          data-slide-to="2"
          class=""
        ></li>
      </ol>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img
            src="https://www.xtrafondos.com/descargar.php?id=5006&resolucion=3840x2160"
            class="img-fluid d-block w-100"
            alt="wonder woman 1984"
            
          />
          <div class="carousel-caption d-none d-md-block">
            <h2>WONDER WOMAN 1984</h2>
            <p>Estreno: 18 de diciembre de 2020</p>

            <a
              href="http://www.sensacine.com/peliculas/pelicula-256588/ "
              class="btn btn-secondary"
              role="button"
              aria-pressed="true"
              target="_blank"
            >
              <svg
                width="1em"
                height="1em"
                viewBox="0 0 16 16"
                class="bi bi-info-circle"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
                
              >
                <path
                  fill-rule="evenodd"
                  d="M8 15A7 7 0 1 0 8 1a7 7 0 0 0 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"
                />
                <path
                  d="M8.93 6.588l-2.29.287-.082.38.45.083c.294.07.352.176.288.469l-.738 3.468c-.194.897.105 1.319.808 1.319.545 0 1.178-.252 1.465-.598l.088-.416c-.2.176-.492.246-.686.246-.275 0-.375-.193-.304-.533L8.93 6.588z"
                />
                <circle cx="8" cy="4.5" r="1" />
              </svg>
              Más información</a
            >
          </div>
        </div>
        <div class="carousel-item">
          <img
            src="https://holacine.com.ar/wp-content/uploads/2020/02/Un-lugar-tranquilo-2-Teaser-Featurette-y-3-nuevos-p%C3%B3sters-llegan-con-un-susurro.jpg"
            class="img-fluid d-block w-100"
            alt="quiet place 2"
          />
          <div class="carousel-caption d-none d-md-block bg-transparent mb-4">
            <h2>UN LUGAR TRANQUILO</h2>
            <p>Estreno: 23 de abril de 2021 .</p>
            <a
              href="http://www.sensacine.com/peliculas/pelicula-264385/"
              class="btn btn-secondary"
              role="button"
              aria-pressed="true"
              target="_blank"
            >
              <svg
                width="1em"
                height="1em"
                viewBox="0 0 16 16"
                class="bi bi-info-circle"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M8 15A7 7 0 1 0 8 1a7 7 0 0 0 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"
                />
                <path
                  d="M8.93 6.588l-2.29.287-.082.38.45.083c.294.07.352.176.288.469l-.738 3.468c-.194.897.105 1.319.808 1.319.545 0 1.178-.252 1.465-.598l.088-.416c-.2.176-.492.246-.686.246-.275 0-.375-.193-.304-.533L8.93 6.588z"
                />
                <circle cx="8" cy="4.5" r="1" />
              </svg>
              Más información</a
            >
          </div>
        </div>
        <div class="carousel-item">
          <img
            src="http://es.web.img3.acsta.net/r_1920_1080/pictures/20/02/21/12/09/2042027.jpg"
            class="img-fluid d-block w-100"
            alt="quiet place 2"
          />

          <div class="carousel-caption d-none d-md-block">
            <h2>ANTLERS: CRIATURA OSCURA</h2>
            <p>Estreno: 5 de marzo de 2021</p>
            <a
              href="http://www.sensacine.com/peliculas/pelicula-261340/"
              class="btn btn-secondary"
              role="button"
              aria-pressed="true"
              target="_blank"
            >
              <svg
                width="1em"
                height="1em"
                viewBox="0 0 16 16"
                class="bi bi-info-circle"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M8 15A7 7 0 1 0 8 1a7 7 0 0 0 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"
                />
                <path
                  d="M8.93 6.588l-2.29.287-.082.38.45.083c.294.07.352.176.288.469l-.738 3.468c-.194.897.105 1.319.808 1.319.545 0 1.178-.252 1.465-.598l.088-.416c-.2.176-.492.246-.686.246-.275 0-.375-.193-.304-.533L8.93 6.588z"
                />
                <circle cx="8" cy="4.5" r="1" />
              </svg>
              Más información</a
            >
          </div>
        </div>
      </div>
      <a
        class="carousel-control-prev"
        href="#carouselExampleCaptions"
        role="button"
        data-slide="prev"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a
        class="carousel-control-next"
        href="#carouselExampleCaptions"
        role="button"
        data-slide="next"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
  </div>
</template>




<script>


import BannerMenu from './BannerMenu.vue';
export default {
  
  name: "BannerHeader",
  components: { BannerMenu },
};
</script>

