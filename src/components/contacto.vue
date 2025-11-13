<template>
    <div id="contacto">
        <h2>Contactame</h2>

        <p><b>Telefono:</b> 302 756 0856</p>
        <p><b>Correo:</b> sebastiancastiblanco0710@gmail.com</p>
        <p><b>Dirección:</b> Cra 38 # 13 - 119</p>

        <div>
            <button @click="whatsApp" id="wpp"><img class="imagen" src="/public/imagenes/WhatsApp.png"></img></button>
            <button @click="correo" id="correo"><img class="imagen" src="/public/imagenes/gmail.png"/></button>
        </div>
        
    </div>
</template>

<script>

    export default {
    name: "Chat",
    
    methods:
     {
    whatsApp() {
        window.open("https://wa.me/573118145323", "_blank");
    },
    correo() {
        window.open("mailto:sebastiancastiblanco0710@gmail.com", "_blank");
    }
    }
};


</script>

<style scoped>

h2 {
    font-weight: 700;
    text-align: center;
}

#contacto {
    display: inline-flex;
    flex-direction: column;
    font-family: "Poppins", Arial, Helvetica, sans-serif;
    color: #2e2e2e;
    justify-content: center;

    width: auto;
    padding: 20px;
    margin: 2% auto;

    background-color: #bfdbf1;
    border: 1px solid #ddd;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
}

#contacto:hover {
    transition: transform 0.1s ease;
    transform: scale(1.03);
}


p > b {
    font-weight: 600;
}

/*Estilos del boton*/

#wpp {
    display: inline-block;
    height: auto;
    width: auto;
    border: transparent;
    margin-top: 5%;
    margin-left: 70px;
    border-radius: 15px;
    background-color: rgb(92, 230, 92);

    max-width: 80px;
    min-width: 60px;
}

#wpp:hover {
    cursor: pointer;
    transition: transform 0.2s ease;
    transform: scale(1.05);
}

.imagen {
    display: inline-block;
    height: 40px;
    width: 40px;
    margin-top: 3%;
    padding-bottom: 0%;
    margin-bottom: 0%;

}

#correo {
    display: inline-block;
    height: auto;
    width: auto;
    border: transparent;
    margin-top: 5%;
    margin-left: 50px;
    border-radius: 15px;
    background-color: rgb(180, 188, 255);

    max-width: 80px;
    min-width: 60px;
}

#correo:hover {
    cursor: pointer;
    transition: transform 0.2s ease;
    transform: scale(1.05);
}

</style>

