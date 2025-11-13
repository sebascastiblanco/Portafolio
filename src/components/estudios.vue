<template>

    <div class="tarjeta">

        <h2>Educación</h2>

    <!-- Educacion Universitaria -->

        <h3>Universidad de Cundinamarca</h3>

        <p class="fecha">2023 - Actualmente</p>

        <ul>
            <li>Profesional en Ingeniería de Software</li>
        </ul>

    <!-- Educacion Escolar -->

        <h3>I. E. Ciudad Verde</h3>

        <p class="fecha">2013 - 2022</p>

        <ul>
            <li>Bachiller Acádemico</li>
        </ul>

        <div class="tarjeta">
            <h2>Otros estudios</h2>

        <!-- Curso Actual -->

            <h3>UDEMY</h3>

            <ul>
                <li>Curso desarrollador FullStack</li>
            </ul>

            <p class="fecha">2025 - Actualmente</p>

        <!-- Idiomas -->

            <h3>American School Way</h3>

            <ul>
                <li>Academia de idiomas</li>
            </ul>

            <p class="fecha">2023 - Actualmente</p>

        <!-- Cursos finalizados -->

            <h3>UDEMY</h3>

            <ul>
                <li>Curso HTML5</li>
            </ul>

            <p class="fecha">Finalizado</p>


            <h3>Sena</h3>

            <ul>
                <li>Uso de herramientas offimaticas</li>
            </ul>

            <p class="fecha">Finalizado</p>
        </div>

    </div>
</template>

<style scoped>
.tarjeta {
    display: inline-flex;
    flex-direction: column;
    font-family: "Poppins", Arial, Helvetica, sans-serif;
    color: #2e2e2e;
    justify-content: center;

    width: 355px;
    padding: 20px;
    margin: 2% auto;

    background-color: #bfdbf1;
    border: 1px solid #ddd;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.2s ease, box-shadow 0,2s ease;
    border-radius: 10px;
}

.tarjeta:hover {
    transition: transform 0.2s ease;
    transform: scale(1.03);
}

</style>