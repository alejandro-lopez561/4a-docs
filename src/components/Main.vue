<template>
    <div class="container">
        <div class="main-section">
            <b-jumbotron>
                <template #header><span class="title">Bienvenido a Upcity Hotel®</span></template>
            
                <template #lead>
                <span class="p1">Te invitamos a registrarte/iniciar sesión para que puedas gestionar tus reservas de habitación, comidas y los demás servicios a tu disposición.</span>
                
                </template>

                <hr class="my-4">

                <p class="p2">
                No estas seguro de iniciar sesión aún? Da click en los botones a continuación para que deleites tus ojos con una pequeña muestra de lo que puedes encontrar en nuestro Hotel, siempre pensando en tu comodidad y experiencia!
                
                </p>
                <div class="content-items">
                    <div class="sidebar-room">
                        <SidebarRoom />
                    </div>
                    <div class="sidebar-food">
                        <SidebarFood />
                    </div>
                </div>
                
                <!-- <b-button variant="primary" href="#">Do Something</b-button>
                <b-button variant="success" href="#">Do Something Else</b-button> -->
            </b-jumbotron>
        </div>
    </div>
</template>


<script>

import SidebarRoom from './SidebarRoom.vue';
import SidebarFood from './SidebarFood.vue';

export default {
  name: 'Main',
  components: {
    SidebarRoom,
    SidebarFood
  }
}

</script>

<style scoped>
.main-section{
    display: flex;
    position: absolute;
    align-items: center;
    width: auto;
    max-width: 800px;
    height: 60%;
    top: 30%;
    margin: 0 15% 50px;
    background-color: rgba(208, 244, 213, 0.8);
    color: black;
    padding: 0 15px;
    border-radius: 35px;
    
}

.title{
    color: black;
}

.content-items{
    z-index: 10 ;
    display: flex;
    flex-direction: row;

}
.sidebar-room{
    margin-right: 10px;
}

.p1{
    /* background-color: rgba(255, 255, 255, 0.6); */
    font-weight: 500;
}

.p2{
    /* background-color: rgba(255, 255, 255, 0.6); */
    font-weight: 500;
}
/* #fff4e3 */
</style>