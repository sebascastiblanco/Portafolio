<template>
    <div class="tarjeta">
        <h2>Habilidades</h2>
            <ul>                
                <li>Pensamiento análitico</li>
                <li>Agilidad</li>
                <li>Aprendizaje rápido</li>
                <li>Mejora continua</li>
                <li>Interes</li>
                <li>Colaborativo</li>
            </ul>
        </div>
</template>

<style scoped>

h2 {
    font-weight: 700;
    text-align: center;
}

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