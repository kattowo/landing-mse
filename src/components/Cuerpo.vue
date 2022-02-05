<template>
    <div class="cuerpo">
     <div class="titulo full">
        <h2>Queremos ser la versión más consciente de nosotras mismas</h2>
        
    </div>

        <div class="card">
            <div class="img-card">               
             </div>
                <h2>Titulo</h2>
                <p>te invito a invitar para que invitemos kfkafkfkaskf</p>
        </div >

  
        <div class="card">
            <div class="img-card">               
            </div>
                <h2>Titulo las kks s  sss </h2>
                <p>te invito a invitar para que invitemos kfkafkfkaskf</p>
        </div >
        <div class="card">
            <div class="img-card">               
            </div>
            <h2>Titulo</h2>
             <p>te invito a invitar para que invitemos kfkafkfkaskf</p>
        </div >
        <a href="https://mujersinedad.com" class="btn fullw" target="_blank" rel="noopener">Más contenido en Mujer sin edad</a>

    </div>

  
</template>



<style scoped>


.cuerpo{    
    min-height: 50vh;
    display: grid;
    /*grid-auto-rows: 5rem;*/
    grid-template-columns: repeat(auto-fill, minmax(30rem, 0.2fr));
    justify-content: center;
    align-content: space-around;   
    gap: 1rem;
    text-align: left;   
    font-family: 'Manrope', sans-serif;    

}

.cuerpo h2{
    grid-column: 2/3;    
    height: 5rem;
    margin-top: 2rem;
    text-align: center;
    justify-content: center;
    align-self: center;    
 
}
.titulo{
    line-height: 1.7rem;
    color: #db8a64;
    font-size: 1.5rem;
    grid-row: 1/3;

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
    text-align: center;
    justify-content: center;
    align-self: center;  
}
.card{
    max-width: 65%;
    min-height: 25rem;    
    border: solid #db8a64 2px;
    border-radius: 20px;
    margin: auto;
}
.card h2 {
    margin-top: 0;
    text-align: left;  
    color:#db8a64; 
    text-transform: uppercase; 
    font-weight: 800;
    padding: .5rem ;
}
.card p{
    margin: 0px;
     margin-left: 1rem;
    margin-right: 1rem;
}
.img-card{
    border-radius: 20px 20px 0px 0px;
    height: 12rem;
    background-image: url(../assets/susi2.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position-y: -8rem;    
}

.btn{
    padding: .51rem 1rem;
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
@media screen and (max-width: 700px) {
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
  .cuerpo h2{
      margin-top:1rem;
      margin-bottom: 1.5rem;
      padding: 0 3rem;
      line-height: 2rem;
 
      
  }
  .titulo h2{
      text-align: left;
   }
   .fullw{
    width: 50%;
    }
}

/*///////////////////////////////////////////////////////////////////*/


</style>