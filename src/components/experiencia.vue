<template>

    <div class="tarjeta">

        <h2>Experiencia</h2>
        
        <div class="experiencia">

            <h3>SwapNetwork</h3><p class="fecha">2024 - Actualmente</p>
            <h4>Proyecto universitario</h4>

        
            <ul>
                <li>
                    Aplicativo web para el agendamiento de tutorias por medio de
                    framework hibrido. Me encuentro en la version 3.0 del proyecto
                    en donde implemente el uso de herramientas Git/GitHub para
                    almacenar el codigo en web y Node.js para la ejecución de
                    backend por consola.
                </li>
            </ul>

        </div>


        <div class="experiencia">

        <h3>Interactivo Contact Center</h3><p class="fecha">2023 - 2024</p>
        <h4>Proyecto Cruz Verde - Agente servicio al cliente - Atención PQRS</h4>

        
        <ul>
            <li>
                Atender, gestionar y dar respuesta oportuna y efectiva a las
                Peticiones, Quejas y Reclamos (PQR) de los clientes, garantizando
                una experiencia positiva y cumpliendo con los lineamientos de
                servicio, calidad y tiempos de respuesta establecidos por la
                compañía.
            </li>
        </ul>

        <p id="jefe">Jefe directo: Cristian Pinto <b>Telefono: (601) 6000000</b></p>
    
        </div>

    </div>
</template>

<style scoped>

h2 {
    font-weight: 700;
    text-align: center;
}

h3 {
    display: inline-flex;
    font-weight: 600;
    margin-top: 15px;
} 

h4 {
    font-weight: 500;
}

.fecha {
  display: inline-flex;
  justify-content: flex-end;
  align-items: center;
  font-weight: 600;
}

.tarjeta {

    display: flex;
    flex-direction: column;
    font-family: "Poppins", Arial, Helvetica, sans-serif;
    color: #2e2e2e;
    justify-content: center;

    width: 80%;
    padding: 20px;
    margin: 2% auto;

    background-color: rgb(241, 241, 243);

}

ul > li {
    list-style: none;
}

#jefe {
    margin-top: 10px;
}

p > b {
    margin-left: 60px;
}
</style>