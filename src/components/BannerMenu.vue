<template>
    <nav class="navbar navbar-expand-lg  navbar-dark bg-dark">
            <div class="navbar-header">
                <a class="navbar-brand align-top" href="#">
                    <div>
                        <svg width="2em" height="2em" viewBox="0 0 16 16" class="bi bi-camera-reels" fill="currentColor"
                            xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd"
                                d="M0 8a2 2 0 0 1 2-2h7.5a2 2 0 0 1 1.983 1.738l3.11-1.382A1 1 0 0 1 16 7.269v7.462a1 1 0 0 1-1.406.913l-3.111-1.382A2 2 0 0 1 9.5 16H2a2 2 0 0 1-2-2V8zm11.5 5.175l3.5 1.556V7.269l-3.5 1.556v4.35zM2 7a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1h7.5a1 1 0 0 0 1-1V8a1 1 0 0 0-1-1H2z" />
                            <path fill-rule="evenodd"
                                d="M3 5a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z" />
                            <path fill-rule="evenodd"
                                d="M9 5a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm0 1a3 3 0 1 0 0-6 3 3 0 0 0 0 6z" />
                        </svg>

                        <!-- <img src="https://www.freepik.es/vector-gratis/tablero-badajo-abierto-diseno-fondo-tira-pelicula_8998544.htm#page=3&query=film&position=12"
                        width="30" height="30" class="align-top" alt="" loading="lazy"> -->
                    </div>
                    <div>
                        FILMS
                    </div>

                </a>
            </div>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse justify-content-end nav-tabs" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item active">
                        <a class="nav-link" href="#">Inicio <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Servicios</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Películas</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link " href="#">Equipo</a>
                    </li>
                </ul>
            </div>
        </nav>
</template>

<script>
export default {
    name: "BannerMenu"
}
</script>