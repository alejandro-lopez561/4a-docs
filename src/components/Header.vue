<template>
    <header>
        <div class="navbar">
            <div class="container">
                <div class="brand">
                    <div class="img-responsive">
                        <a href="/"></a>
                    </div>
                    <div class="brand-title"> UPCITY HOTEL </div>
                </div>
                <div class="items">
                    <div class="item">
                        <b-button href="#" variant="primary">Ingreso</b-button>
                    </div>
                    <div class="item">
                        <b-button href="#" variant="success">Registro</b-button>
                    </div>
                </div>
            </div>

        </div>
        
    </header>
</template>

<script>

</script>

<style scoped>



.navbar{    
    width: 100%;
    height: 80px;
    display: flex;
    background-color: none;
    color: black;
    flex-direction: row;
    justify-content: space-between;
    z-index: 0;
    
    
}

.navbar:hover{
    background-color: rgba(14, 14, 14, 0.79);
    color: white;
}

.brand{
    font-size: 34px;
    font-weight: 700;
    display: flex;
    flex-direction: row;
}

.img-responsive {
    position: relative;
    top: 2px;
    width: 100px;
    height: 50px;
    background-image: url(~@/assets/bg-img.jpg);
    background-position: 50% 70%;
    background-size: cover;
    background-repeat: no-repeat;
    cursor: pointer;
    border-radius: 30px;
}

.brand-title{
    margin-left: 10px;
    align-items: center;
}

.items{
    font-size: 18px;
    display: flex;
    flex-direction: row;
    margin: 0;
}

.item{
    padding: 0 5px;
}

</style>
