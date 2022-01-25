<template>
   <div class="cabecera">
    <div class="circulo"><img alt="Vue logo" src="../assets/susi1.jpg"></div>
     <div class="circulo1"><img alt="Vue logo" src="../assets/susi3.jpg"></div>
    <div class="circulo2"></div>
    <div class="circulo3"></div>  
    <div class="cargo">
     <h2>Susana Ramírez</h2>
     <h3>Mujer sin edad</h3>
      <div class="redes">
        <a href="https://instagram.com/mujersinedad" target="_blank" rel="noopener noreferrer">
          <div class="redes-circulo">
            <img alt="instagram/mujersinedad" src="../assets/instagram.png">
          </div>  
        </a>
    </div>
    </div>
    <!--<div class="redes">
        <a href="https://instagram.com/mujersinedad" target="_blank" rel="noopener noreferrer">
          <div class="redes-circulo">
            <img alt="instagram/mujersinedad" src="../assets/instagram.png">
          </div>  
        </a>
    </div>-->
  </div> 
</template>

<script>
export default {
  name: 'Cabecera'
}
</script>

<style scoped>

.cabecera{
  color: #fff; 
  width: 100%;
  height: 500px;
  display:grid;
  grid-template-columns: 1fr 55%;
  justify-content: center;
  align-items: center;
  background-image: url(../assets/susi3.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position-y: 30%;
  font-family: 'Manrope', sans-serif;
 
}

.circulo{
  display: none;
  width: 200px;
  height: 200px;
  border-radius: 10%;  
  border: #ecc58b 15px solid;
 /* outline: #002fff solid 10px;*/
}
.circulo1 img{
  width: 50%;
  display: none;
}
.cargo{
  width: 50%;
  text-align: left;
  margin-left: 2.5rem;
  margin-top: 2rem;
  grid-column: 2/-1;
  grid-row: 1/3;
  justify-content: center;
  align-items: center;
}
.cargo h2{
  font-size: 3rem;
  line-height: 2.3rem;
  font-weight: 800;
}
.cargo h3{
  font-family: 'Comforter', cursive;
  font-size: 3.5rem;
  line-height: 4rem;
}
.redes{
  display:flex;
  justify-content: flex-start;
  align-items: flex-start;
  margin-top: 1rem;

}
.redes img{
  width: 10%;   
}
.redes-circulo{
  display: flex;
  background: cornsilk;
  width: 35px;
  height: 35px;
  border-radius:50%;
  border: #ff0095 1px solid;
}
.redes-circulo img{
  width: 70%;
  margin: auto;
}
@media screen and (max-width: 700px) {
       .redes{
            display:flex;
            justify-content: center;
            align-items: center;
            margin-top: .3rem;

          }
       .redes img{
            width: 10%;
            margin-top: .5rem;
          }
        .redes-circulo img{
            width: 70%;
            margin: auto;
        }
        .cabecera{
          /*color:#ecc58b ;*/
          color: #bd8a64;
          
          height: 50vh;
          display: flex;
          flex-direction:column;
          justify-content: center;
          align-items: center;
          background-image: none;
          box-shadow: 0px 0px 30px #444444;
          /*background: linear-gradient(to left, #ffecd2 0%, #fcb69f 110%);*/
          background-image: linear-gradient(to top, #fad0c4 0%, #ffd1ff 100%);
         
        }      
      .circulo{
        display: block;
        width: 150px;
        height: 150px;
        position: absolute;
        border-radius: 50%;
        margin-top: -5rem;
        /*border: #ff0033 15px solid;
       outline: #002fff solid 10px;*/
      }
      .circulo img{
        width: 110%;
        height: 105%;
        border-radius: 50%;
        margin-top: -10%;
        margin-left: -5%;
        background-color: #fff;
      }
      .circulo1{
        display: none;
      }
      .circulo2{
        width: 145px;
        height: 150px;
        position: absolute; 
        border-radius: 50%;
        margin-top: -6rem;
        border: #f8c06b 10px solid;
        transform: rotate(90deg);
      }
      .circulo3{
        width: 139px;
        height: 160px;
        position: absolute; 
        margin-top: -5.1rem;
        border: #e08d4ef3 10px solid;
        transform: rotate(99deg);
        border-radius: 50%;
        
      }
      .cargo{
        margin-top: 12rem;
        text-align: center;
        justify-content: center;
        align-items: center;
        margin-left: -0.7rem;
      }
      .cargo h2{
        font-size: 1.8rem;
        line-height: 0.6rem;
        margin-top: 3rem;
      }
      .cargo h3{
        font-size: 2.5rem;
        line-height: 0,2rem;        
      }
}

</style>

