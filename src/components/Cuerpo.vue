<template>
    <div class="cuerpo">
     <div class="titulo full">
        <h2>Queremos ser lala la versión más consciente de nosotras mismas</h2>
    </div>

        <div class="card">
            <div class="img-card">               
             </div>
                <h2>Titulo</h2>
                <p>
                    Lorem, ipsum dolor sit amet consectetur adipisit.
                   Veniam earum necessitatibus repudiandae nobis, impedit veritatis iure accusamus
                   quae reprehenderit sunt corrupti, vero dolor quos voluptatem quod dolorum praesentium,
                   aliquam tenetur.
                </p>
        </div >
 
        <div class="card">
            <div class="img-card">               
            </div>
                <h2>Titulo las kks s  sss </h2>
                  <p>
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                   Veniam earum necessitatibus robis, impedit veritatis iure accusamus
                   quae reprehenderit sunt corrupti, vero dolor quos voluptatem quod dolorum praesentium,
                   aliquam tenetur.
                </p>
        </div >
        <div class="card">
            <div class="img-card">               
            </div>
            <h2>Titulo</h2>
               <p>
                    Lorem, ipsum dolor sit amet consectetur adipisicing elit.
                   Veniam earum necessitatibus repudiandae nobis, impedit veritatis iure accusamus
                   quae reprehenderit sunt corrupti, vero dolor quos voluptatemd praesentium,
                   aliquam tenetur.
                </p>
        </div >
        <a href="https://mujersinedad.com" class="btn fullw" target="_blank" rel="noopener">Más contenido en Mujer sin edad</a>

    </div>

    <div class="footter">
        Derechos Reservados 2022
    </div>
</template>

<style scoped>

.cuerpo{    
    min-height: 50vh;
    display: grid;
    /*grid-auto-rows: 5rem;*/
    /*grid-template-columns: repeat(auto-fill, minmax(550px, 1fr));*/
    grid-template-columns: repeat(3, 330px);
    justify-content: center;
    align-content: center;   
    gap: 1rem;
    text-align: left;   
    font-family: 'Manrope', sans-serif;    
    margin: auto;
}

.titulo {
    color: #db8a64;
    font-size: 1.5rem;
    line-height: 2rem;
    grid-row: 1/3;

}
.titulo h2{
    grid-column: 2/3;    
    height: 5rem;
    margin: 2rem 6rem;
    text-align: center;
    justify-content: center;
    align-self: center; 
   
}

.full{
    grid-column: 1/-1;
    margin: auto;
    text-align: center;
    justify-content: center;
    align-self: center;  

}
.fullw{
    grid-column: 1/-1;
    width: 50%;
    margin-top: 3rem;
    margin-left: auto;
    margin-right: auto;
    margin-bottom: 3rem;
    text-align: center;
    justify-content: center;
    align-self: center;  
    
}
.card{
    min-height: 25rem;    
    border: solid #db8a64 2px;
    border-radius: 20px;
    margin: auto;
}

.img-card{
    border-radius: 18px 18px 0px 0px;
    background-image: url(../assets/susi2.jpg);
    background-repeat: no-repeat;
    width: 100%;
    height: 250px;
    background-size: cover;
    background-position-y: -5rem;
}

.btn{
    padding: .51rem 2rem;
    background-color: #bd8a64;
    cursor: pointer;
    border-radius: 25px;
    display: flex;
    justify-content: center;
    align-items: center;
    height: fit-content;
    color: #fff;
    text-decoration: none;
    transition: ease .3s;
    font-weight: 800;
 }
 .btn:hover{
       background-color: #e08d4ef3;
 }
.btn a{
    color: #fff;
    text-decoration: none;
}
  .card h2{
      margin:0.5rem 0;
      padding: 0rem 1rem;
      height: auto;
      color: #bd8a64;
      text-transform: uppercase;
      text-align: left;
  }
  .card p{
    text-align: justify;
    margin-bottom: 2rem;
    padding: 1rem;
  }
.footter{
    display: flex;
    justify-content: center;
    align-items: center;
    color: #fff;
    font-weight: 600;
    text-transform: uppercase;
    height: 50px;
    width: 100%;
    margin: auto;
    background-color:gray;
    text-align: center;
}

@media screen and (max-width: 850px) {
.cuerpo{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: left;
    margin: 1rem;
    padding: 1rem;
    gap: 3rem;
  }

 .titulo h2{
    text-align: left;    
    padding: 0;
    margin:2rem 1rem;
  }
.img-card{
   height: 400px;
   background-position-y: -6rem;
}
  .card h2{
     margin: 0rem 1rem 0 1rem;  
     height: auto;
     text-transform: uppercase;
  }
  .card p{
    padding:1rem;  
    margin: 0rem 1rem;  
    text-align: justify;
  }
   .fullw{
    width: 50%;

    }
}

/*///////////////////////////////////////////////////////////////////*/


</style>