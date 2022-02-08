<template>
   <div class="cabecera">
    <div class="presentacion">       
          <div class="circulo"><img alt="Vue logo" src="../assets/susi1.jpg"></div>
          <div class="circulo1"><img alt="Vue logo" src="../assets/susi3.jpg"></div>
          <div class="circulo2"></div>
          <div class="circulo3"></div>  
          <div class="cargo">
          <h2>Susana Ramírez</h2>
          <h3>Mujer sin edasssssssssd</h3>
          <div class="redes">
              <a href="https://instagram.com/mujersinedad" target="_blank" rel="noopener noreferrer">
                <div class="redes-circulo">
                  <img alt="instagram/mujersinedad" src="../assets/instagram.png">
                </div>  
              </a>   
          </div>

      por que mierda no veo los cambios
      
    </div>

        <div class="waves">        
              <div class="circulo-wave1"></div>
              <div class="circulo-wave2"></div>  
              <div class="circulo-wave3"></div>    
           
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
  overflow: hidden;

}
.presentacion{
 grid-column: 2/-1;
 overflow: hidden;
}

.waves{
  display: none;
}

.circulo{
  display: none;
  width: 200px;
  height: 200px;
  border-radius: 10%;  
  border: #ecc58b 15px solid;
 /* outline: #002fff solid 10px;*/
  z-index: 3;
}
.circulo1 img{
  width: 50%;
  display: none;
  z-index: 2;
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
  z-index: 1;
}
.cargo h2{
  font-size: 3rem;
  line-height: 2.3rem;
  font-weight: 800;
  z-index: 2;
}
.cargo h3{
  font-family: 'Comforter', cursive;
  font-size: 2.5rem;
  line-height: 4rem;
  z-index: 2;
}
.redes{
  display:flex;
  justify-content: flex-start;
  align-items: flex-start;
  margin-top: 1rem;
  z-index: 2;

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
  z-index: 3;
}
.redes-circulo img{
  width: 70%;
  margin: auto;
  z-index: 3;
}

@media screen and (max-width: 850px) {
  
        .presentacion{
            display: flex;
            justify-content: center;
            align-items: center;     
            width: 100%;
            margin: auto;
        }
       .redes{
            display:flex;
            justify-content: center;
            align-items: center;
            margin-top: .3rem;
          }
       .redes img{
            width: 10%;
            margin-top: .5rem;
            z-index: 3;
          }
        .redes-circulo img{
            width: 70%;
            margin: auto;
        }
        .cabecera{
          /*color:#ecc58b ;*/
          color: #bd8a64;          
          height: 457px;
          display: flex;
          flex-direction:column;
          justify-content: center;
          align-items: center;
          background-image: none;
          box-shadow: 0px 0px 30px #929292;
          /*background: linear-gradient(to left, #ffecd2 0%, #fcb69f 110%);*/
          background-image: linear-gradient(to top, #fad0c4 0%, #ffd1ff 100%);
         z-index: 1;      
        }      
      .circulo{
        display: block;
        width: 150px;
        height: 150px;
        position: absolute;
        border-radius: 50%;
        margin-top: -5rem;
      }
      .circulo img{
        width: 110%;
        height: 105%;
        border-radius: 50%;
        margin-top: -10%;
        margin-left: -5%;
        background-color: #fff;
        z-index: 3;
      }
      .circulo1{
        border-radius: 50%;
        display: none;
        border: #ff0095 10px solid;
      }
      .circulo2{
        width: 145px;
        height: 150px;
        position: absolute; 
        border-radius: 50%;
        margin-top: -6rem;
        border: #f8c06b 10px solid;
        transform: rotate(90deg);
        z-index: 3;
        animation: circulo2 2s ease infinite;
      }
      .circulo3{
        width: 139px;
        height: 160px;
        position: absolute; 
        margin-top: -5.1rem;
        border: #e08d4ef3 10px solid;
        transform: rotate(99deg);
        border-radius: 50%;
        z-index: 3;
        animation: circulo2 8s ease infinite;
   
      }
   
        @keyframes circulo2 {
          from{
            transform: rotate(0deg);        
          }
         to {
            transform: rotate(360deg);
          }
        }
      .cargo{
        margin-top: 12rem;
        text-align: center;
        justify-content: center;
        align-items: center;
        margin-left: -0.7rem;      
        z-index:3 ;
      }
      .cargo h2{
        font-size: 1.8rem;
        line-height: 1.6rem;
        margin-top: 3.8rem;
      
        
      }
      .cargo h3{
        font-size: 2.5rem;
        line-height: 0,2rem;
               
      }

            /* ////////////////////////////////////////////// ////////////// */

     
      .waves {      
          display: flex;
          position: absolute;
          height: 457px;
          width: 100%;
          overflow: hidden;
          z-index: 1;
          /* background-color: mediumaquamarine; */
          top: 0px;
          left: 0%;
         
    } 
        .circulo-wave1{
        width: 1200px;
        height: 960px;
        position: absolute; 
        margin-top: -65rem;
        margin-left: -35rem;
        border: #f3f4f5 530px solid;
        transform: rotate(9deg);
         border-radius: 50%;
        z-index: 9;
        opacity: .36;
        animation: circulo2 15s ease infinite;
      } 
       .circulo-wave2{
        width: 1339px;
        height: 760px;
        position: absolute; 
        margin-top: -15.1rem;
        margin-left: -10rem;
        border: #f3f4f5 530px solid;
        transform: rotate(199deg);
         border-radius: 50%;
        z-index: 9;
        opacity: .3;
        animation: circulo2 15s ease infinite;
      } 
       .circulo-wave3{
        width: 539px;
        height: 660px;
        position: absolute; 
        margin-top: -5.1rem;
        border: #f3f4f5 630px solid;
        transform: rotate(299deg);
         border-radius: 50%;
        z-index: 9;
        opacity: .4;
        animation: circulo2 12s ease infinite;
      } 
          .wave {
            display: flex;            
            overflow: hidden; 
            z-index: 1;
            animation: 5s wave ease-in-out infinite alternate;
                       
            /*
            background: url(https://static.platzi.com/media/files/waves_c8551f5d-ecf6-4a81-ae1d-f3a0ad55ba10.png) center bottom no-repeat;
            */
          }
       
          .wave.a {
           animation-delay: .1s;            
           top: 20px;       
           overflow: hidden; 
           position: absolute;          
            
          }
          .wave.b {
            animation-delay: .9s;
            position: absolute;
            top: 175px;        
            overflow: hidden; 
      
          }
          .wave.c {
            animation-delay: 2.2s;
            position: absolute;
            top: 175px;
            left: 0%;
            overflow: hidden; 
          
          }
          @keyframes wave {
            0% {
              transform: translate(-45px , 0px);
            }
            50% {
              transform: translate(-180px, 0px);
            }
            100% {
              transform: translate(-45px, 0px);
            }
          }

 }   
</style>

