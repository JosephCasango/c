<style>
  /* Menu */






* {box-sizing: border-box}


/* Style tab links */
.tablink .ButtonPro{
  background-color: #555;
  color: white;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 14px 16px;
  font-size: 17px;
  width: 25%;
}

.tablink .ButtonPro:hover {
  background-color: #777;
}

/* Style the tab content (and add height:100% for full page content) */
.tabcontent {
  color: white;
  display: none;
  padding: 100px 20px;
  height: 100%;
}


#InicioPag {
  background-color: white;
  height: 100%;
}
#ProductoPag{
background: radial-gradient(circle at 100% 107%, #ff89cc 0%, #9cb8ec 30%, #00ffee 60%, #62c2fe 100%);
  height: 530%;

}
#TramitePag {
  background-color: white;
  height: 70%;
}

#CarritoPag {
 background-image: linear-gradient(to right, rgb(255, 174, 0), rgb(204, 0, 255));
    height: 900%;
}



body, html {

  margin: 0;
  font-family: Arial;
}












/* Barra */
/* Menu Barra */
.Menu{
 color: #df0044;
    position: absolute;
top: 20px; left: 1200px;
}


.Icono{
  border-radius: 90%;
    border: 8px #212529 solid;


      position: absolute;
top: 15px; left: 15px;

  }


.Punto{
    color: #212529;
  }


.PapeSub{

      position: absolute;
top: 32px; left: 23px;

  }


.P{

      position: absolute;
top: 30px; left: 140px;

  }










/* Button Menu */
.MenuB {
  width: 150px;
  height: 50px;
  border-radius: 5px;
  border: none;
  transition: all 0.5s ease-in-out;
  font-size: 20px;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  font-weight: 600;
  display: flex;
  align-items: center;
  background: #df0044;
  color: #f5f5f5; 
    cursor: pointer;
}

.MenuB:hover {
  box-shadow: 0 0 20px 0px #2e2e2e3a;
}

.MenuB .iconMenu {
  position: absolute;
  height: 40px;
  width: 70px;
  display: flex;
  justify-content: center;
  align-items: center;
  transition: all 0.5s;
}

.MenuB .textM {
  transform: translateX(55px);
}

.MenuB:hover .iconMenu {
  width: 175px;
}

.MenuB:hover .textM {
  transition: all 0.5s;
  opacity: 0;
}

.MenuB:focus {
  outline: none;
}

.MenuB:active .iconMenu {
  transform: scale(0.85);
}







/* Botones dentro del menu */

/* Boton Inicio */
.BuIni{

      position: absolute;
top: 150px; left: 65px;

  }




.ButtonIni {
  width: 140px;
  height: 56px;
  overflow: hidden;
  border: none;
  color: hotpink;
  background: none;
  position: relative;
  padding-bottom: 2em;
      cursor: pointer;
}

.ButtonIni > div,.ButtonIni > svg {
  position: absolute;
  width: 100%;
  height: 100%;
  display: flex;
}

.ButtonIni:before {
  content: "";
  position: absolute;
  height: 2px;
  bottom: 0;
  left: 0;
  width: 100%;
  transform: scaleX(0);
  transform-origin: bottom right;
  background: currentColor;
  transition: transform 0.25s ease-out;
}

.ButtonIni:hover:before {
  transform: scaleX(1);
  transform-origin: bottom left;
}

.ButtonIni .cloneIni > *,.ButtonIni .textIni > * {
  opacity: 1;
  font-size: 1.3rem;
  transition: 0.2s;
  margin-left: 4px;
}

.ButtonIni .cloneIni > * {
  transform: translateY(60px);
}

.ButtonIni:hover .cloneIni > * {
  opacity: 1;
  transform: translateY(0px);
  transition: all 0.2s cubic-bezier(0.215, 0.61, 0.355, 1) 0s;
}

.ButtonIni:hover .textIni > * {
  opacity: 1;
  transform: translateY(-60px);
  transition: all 0.2s cubic-bezier(0.215, 0.61, 0.355, 1) 0s;
}

.ButtonIni:hover .cloneIni > :nth-child(1) {
  transition-delay: 0.15s;
}

.ButtonIni:hover .cloneIni > :nth-child(2) {
  transition-delay: 0.2s;
}

.ButtonIni:hover .cloneIni > :nth-child(3) {
  transition-delay: 0.25s;
}

.ButtonIni:hover .cloneIni > :nth-child(4) {
  transition-delay: 0.3s;
}
/* icon style and hover */
.ButtonIni svg {
  width: 20px;
  right: 0;
  top: 50%;
  transform: translateY(-50%) rotate(-90deg);
  transition: 0.2s ease-out;
}

.ButtonIni:hover svg {
  transform: translateY(-50%) rotate(-50deg);
}







/* Boton Producto */
  .BuPro{

      position: absolute;
top: 250px; left: 65px;

  }


.ButtonPro {
  width: 170px;
  height: 56px;
  overflow: hidden;
  border: none;
  color: yellow;
  background: none;
  position: relative;
  padding-bottom: 2em;
      cursor: pointer;
}

.ButtonPro > div,.ButtonPro > svg {
  position: absolute;
  width: 100%;
  height: 100%;
  display: flex;
}

.ButtonPro:before {
  content: "";
  position: absolute;
  height: 2px;
  bottom: 0;
  left: 0;
  width: 100%;
  transform: scaleX(0);
  transform-origin: bottom right;
  background: currentColor;
  transition: transform 0.25s ease-out;
}

.ButtonPro:hover:before {
  transform: scaleX(1);
  transform-origin: bottom left;
}

.ButtonPro .clonePro > *,.ButtonPro .textPro > * {
  opacity: 1;
  font-size: 1.3rem;
  transition: 0.2s;
  margin-left: 4px;
}

.ButtonPro .clonePro > * {
  transform: translateY(60px);
}

.ButtonPro:hover .clonePro > * {
  opacity: 1;
  transform: translateY(0px);
  transition: all 0.2s cubic-bezier(0.215, 0.61, 0.355, 1) 0s;
}

.ButtonPro:hover .textPro > * {
  opacity: 1;
  transform: translateY(-60px);
  transition: all 0.2s cubic-bezier(0.215, 0.61, 0.355, 1) 0s;
}

.ButtonPro:hover .clonePro > :nth-child(1) {
  transition-delay: 0.15s;
}

.ButtonPro:hover .clonePro > :nth-child(2) {
  transition-delay: 0.2s;
}

.ButtonPro:hover .clonePro > :nth-child(3) {
  transition-delay: 0.25s;
}

.ButtonPro:hover .clonePro > :nth-child(4) {
  transition-delay: 0.3s;
}
/* icon style and hover */
.ButtonPro svg {
  width: 20px;
  right: 0;
  top: 50%;
  transform: translateY(-50%) rotate(-90deg);
  transition: 0.2s ease-out;
}

.ButtonPro:hover svg {
  transform: translateY(-50%) rotate(-50deg);
}










/* Boton Tramites */

  .BuTra{

      position: absolute;
top: 350px; left: 65px;

  }



  .ButtonTra {
  width: 170px;
  height: 56px;
  overflow: hidden;
  border: none;
  color: orange;
  background: none;
  position: relative;
  padding-bottom: 2em;
      cursor: pointer;
}

.ButtonTra > div,.ButtonTra > svg {
  position: absolute;
  width: 100%;
  height: 100%;
  display: flex;
}

.ButtonTra:before {
  content: "";
  position: absolute;
  height: 2px;
  bottom: 0;
  left: 0;
  width: 100%;
  transform: scaleX(0);
  transform-origin: bottom right;
  background: currentColor;
  transition: transform 0.25s ease-out;
}

.ButtonTra:hover:before {
  transform: scaleX(1);
  transform-origin: bottom left;
}

.ButtonTra .cloneTra > *,.ButtonTra .textTra > * {
  opacity: 1;
  font-size: 1.3rem;
  transition: 0.2s;
  margin-left: 4px;
}

.ButtonTra .cloneTra > * {
  transform: translateY(60px);
}

.ButtonTra:hover .cloneTra > * {
  opacity: 1;
  transform: translateY(0px);
  transition: all 0.2s cubic-bezier(0.215, 0.61, 0.355, 1) 0s;
}

.ButtonTra:hover .textTra > * {
  opacity: 1;
  transform: translateY(-60px);
  transition: all 0.2s cubic-bezier(0.215, 0.61, 0.355, 1) 0s;
}

.ButtonTra:hover .cloneTra > :nth-child(1) {
  transition-delay: 0.15s;
}

.ButtonTra:hover .cloneTra > :nth-child(2) {
  transition-delay: 0.2s;
}

.ButtonTra:hover .cloneTra > :nth-child(3) {
  transition-delay: 0.25s;
}

.ButtonTra:hover .cloneTra > :nth-child(4) {
  transition-delay: 0.3s;
}
/* icon style and hover */
.ButtonTra svg {
  width: 20px;
  right: 0;
  top: 50%;
  transform: translateY(-50%) rotate(-90deg);
  transition: 0.2s ease-out;
}

.ButtonTra:hover svg {
  transform: translateY(-50%) rotate(-50deg);
}










/* Boton Carrito */


  .BuCar{

      position: absolute;
top: 450px; left: 65px;

  }


  .ButtonCar {
  width: 170px;
  height: 56px;
  overflow: hidden;
  border: none;
  color: limegreen;
  background: none;
  position: relative;
  padding-bottom: 2em;
      cursor: pointer;
}

.ButtonCar > div,.ButtonCar > svg {
  position: absolute;
  width: 100%;
  height: 100%;
  display: flex;
}

.ButtonCar:before {
  content: "";
  position: absolute;
  height: 2px;
  bottom: 0;
  left: 0;
  width: 100%;
  transform: scaleX(0);
  transform-origin: bottom right;
  background: currentColor;
  transition: transform 0.25s ease-out;
}

.ButtonCar:hover:before {
  transform: scaleX(1);
  transform-origin: bottom left;
}

.ButtonCar .cloneCar > *,.ButtonCar .textCar > * {
  opacity: 1;
  font-size: 1.3rem;
  transition: 0.2s;
  margin-left: 4px;
}

.ButtonCar .cloneCar > * {
  transform: translateY(60px);
}

.ButtonCar:hover .cloneCar > * {
  opacity: 1;
  transform: translateY(0px);
  transition: all 0.2s cubic-bezier(0.215, 0.61, 0.355, 1) 0s;
}

.ButtonCar:hover .textCar > * {
  opacity: 1;
  transform: translateY(-60px);
  transition: all 0.2s cubic-bezier(0.215, 0.61, 0.355, 1) 0s;
}

.ButtonCar:hover .cloneCar > :nth-child(1) {
  transition-delay: 0.15s;
}

.ButtonCar:hover .cloneCar > :nth-child(2) {
  transition-delay: 0.2s;
}

.ButtonCar:hover .cloneCar > :nth-child(3) {
  transition-delay: 0.25s;
}

.ButtonCar:hover .cloneCar > :nth-child(4) {
  transition-delay: 0.3s;
}
/* icon style and hover */
.ButtonCar svg {
  width: 20px;
  right: 0;
  top: 50%;
  transform: translateY(-50%) rotate(-90deg);
  transition: 0.2s ease-out;
}

.ButtonCar:hover svg {
  transform: translateY(-50%) rotate(-50deg);
}


















/* Boton sobreesdrujula */


  .BuSobre{

      position: absolute;
top: 530px; left: 65px;

  }


  .ButtonSo {
  width: 170px;
  height: 56px;
  overflow: hidden;
  border: none;
  color: red;
  background: none;
  position: relative;
  padding-bottom: 2em;
      cursor: pointer;
}

.ButtonSo > div,.ButtonSo > svg {
  position: absolute;
  width: 100%;
  height: 100%;
  display: flex;
}

.ButtonSo:before {
  content: "";
  position: absolute;
  height: 2px;
  bottom: 0;
  left: 0;
  width: 100%;
  transform: scaleX(0);
  transform-origin: bottom right;
  background: currentColor;
  transition: transform 0.25s ease-out;
}

.ButtonSo:hover:before {
  transform: scaleX(1);
  transform-origin: bottom left;
}

.ButtonSo .cloneSo > *,.ButtonSo .textSo > * {
  opacity: 1;
  font-size: 1.3rem;
  transition: 0.2s;
  margin-left: 4px;
}

.ButtonSo .cloneSo > * {
  transform: translateY(60px);
}

.ButtonSo:hover .cloneSo > * {
  opacity: 1;
  transform: translateY(0px);
  transition: all 0.2s cubic-bezier(0.215, 0.61, 0.355, 1) 0s;
}

.ButtonSo:hover .textSo > * {
  opacity: 1;
  transform: translateY(-60px);
  transition: all 0.2s cubic-bezier(0.215, 0.61, 0.355, 1) 0s;
}

.ButtonSo:hover .cloneSo > :nth-child(1) {
  transition-delay: 0.15s;
}

.ButtonSo:hover .cloneSo > :nth-child(2) {
  transition-delay: 0.2s;
}

.ButtonSo:hover .cloneSo > :nth-child(3) {
  transition-delay: 0.25s;
}

.ButtonSo:hover .cloneSo > :nth-child(4) {
  transition-delay: 0.3s;
}
/* icon style and hover */
.ButtonSo svg {
  width: 20px;
  right: 0;
  top: 50%;
  transform: translateY(-50%) rotate(-90deg);
  transition: 0.2s ease-out;
}

.ButtonSo:hover svg {
  transform: translateY(-50%) rotate(-50deg);
}












/* Pagina de inicio fondo principal */
.container {
  position: relative;
  font-family: Arial;

}

.text-block {

      position: absolute;
  bottom: 20px;
  right: 150px;
  background-color: black;
  color: white;
  padding-left: 20px;
  padding-right: 20px;
    border-radius: 10%;
}













/* Pagina de inicio abajo del fondo */
.Recep {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;

}

.Recep {
  box-sizing: border-box;

}



.column21 {
  float: left;
  width: 22.3%;
  margin-bottom: 46px;
  padding: -40 -50px;

}

.card21 {
  box-shadow: 0 24px 48px 0 rgba(0, 0, 0, 0.2);
  margin: 8px;
}

.about-section21 {
  padding: 8px;
  text-align: center;
  background-color: grey;
  color: white;
}

.container21 {
  padding: 10 16px;


}

.container21::after, .row21::after {
  content: "";
  clear: both;
  display: table;

}


@media screen and (max-width: 700px) {
  .column21 {
    width: 500%;
    display: block;


  }
}













.IMG{
  border-radius: 1%;

  }












/* Pagina de inicio Google Maps */
.Recep {
  font-family: Arial, Helvetica, sans-serif;
  margin: 0;

}

.Recep {
  box-sizing: border-box;
}



.column210 {
  float: left;
  width: 97%;
  margin-bottom: 16px;
  padding: 0 0px;

}

.card210 {
  box-shadow: 0 14px 18px 0 rgba(0, 0, 0, 0.2);
  margin: 8px;
}

.about-section210 {
  padding: 50px;
  text-align: center;
  background-color: grey;
  color: white;
}

.container210 {
  padding: 0 16px;
}

.container210::after, .row210::after {
  content: "";
  clear: both;
  display: table;
}


@media screen and (max-width: 950px) {
  .column210 {
    width: 100%;
    display: block;

  }
}





















/* Producto Lapiz 1 Ticonderoga*/

.Lapiz1 {
  overflow: hidden;
  object-fit: cover;
  border-radius: 1rem;
  max-width: 300px;
  background-color: #fff;
  color: #212121;

      float: left;

margin: .3em;
  margin-left: 1em;


}








.image1 {
  height: 15rem;

  
  width: 100%;
  object-fit: cover;
  background-color: rgb(204, 0, 255);
  background-image: linear-gradient(to right, rgb(255, 174, 0), rgb(204, 0, 255));
}

.content1 {
  padding: .5rem;
  text-align: center;
  cursor: pointer;
}

.text-1 {
  font-size: .875rem;
  line-height: 0.25rem;
  font-weight: 600;
  letter-spacing: 0.3em;
  text-transform: uppercase;
}

.text-2 {
  margin-top: 1rem;
  font-weight: 900;
  text-transform: uppercase;
}

.text-2 span:first-child {
  font-size: 2.25rem;
  line-height: 2.5rem;
  font-weight: 900;
}

.text-2 span:last-child {
  margin-top: 0.5rem;
  display: block;
  font-size: 0.875rem;
  line-height: 1.25rem;
}

.action1 {

  margin-top: 1rem;
  display: inline-block;
  width: 100%;
  background-color: rgb(0, 0, 0);
  padding-top: 1rem;
  padding-bottom: 1rem;
  border-radius: 110px;
  font-size: .875rem;
  line-height: 1.25rem;
  font-weight: 200;
  letter-spacing: .1em;
  text-transform: uppercase;
  color: rgba(275, 255, 255, 1);
  text-decoration: none;
}

.date1 {
  margin-top: 1rem;
  font-size: 0.75rem;
  line-height: 1rem;
  font-weight: 500;
  text-transform: uppercase;
  color: rgba(156, 163, 175, 1);
}

















/* Carrito Cescripcion*/
.cardDes {
  overflow: hidden;
  border-radius: 0.5rem;
  max-width: 9000px;
  background-color: white;
  color: black;
    padding: 1rem;
}

/* Producto Lapiz 1 Ticonderoga Carrito*/
.card001 {
  overflow: hidden;
  border-radius: 0.5rem;
  max-width: 9000px;
  background-color: white;
  color: black;
    padding: 0rem;

}


  
  






  /* Buscador de la pagina productos*/

  .input[type=text] {

  background-color: #fff;
  color: #242424;
  padding: .20rem 5.5rem;

  border-radius: 4px;
  outline: none;
  border: none;
  box-shadow: 0px 10px 20px -18px blue;
  border-bottom: 3px solid #0d14e9;

}




  /*  Input Lapiz 7 pesos*/

.input1 {
  cursor: pointer;
}

.input1 input {
  display: none;
}

.input1 svg {
  overflow: visible;
}

.path {
  fill: none;
  stroke: hotpink;
  stroke-width: 6;
  stroke-linecap: round;
  stroke-linejoin: round;
  transition: stroke-dasharray 0.5s ease, stroke-dashoffset 0.5s ease;
  stroke-dasharray: 241 9999999;
  stroke-dashoffset: 0;
}

.input1 input:checked ~ svg .path {
  stroke-dasharray: 70.5096664428711 9999999;
  stroke-dashoffset: -262.2723388671875;
}





  /*  Borrar1*/

  .Borrar1 {
  width: 50px;
  height: 50px;
  border-radius: 50%;
  background-color: rgb(20, 20, 20);
  border: none;
  font-weight: 600;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.164);
  cursor: pointer;
  transition-duration: .3s;
  overflow: hidden;
  position: relative;
}

.svgIcon {
  width: 12px;
  transition-duration: .3s;
}

.svgIcon path {
  fill: white;
}

.Borrar1:hover {
  transition-duration: .3s;
  background-color: rgb(255, 69, 69);
  align-items: center;
}















/* Tramites*/


.cardTra {
  overflow: hidden;
  border-radius: 0.5rem;
      border: 5px black solid;
  max-width: 9000px;
  background-color: limegreen;
  color: limegreen;
    padding: 2rem;
}


.TexC {

  color: white;

}






.cardTra2 {
  overflow: hidden;
  border-radius: 0.5rem;
      border: 5px black solid;
  max-width: 9000px;
  background-color: orangered;
  color: orangered;
    padding: 2rem;
}


.TexR2 {

  color: white;

}














/* Pagina tramites */
.Tra {
  color: white;
  display: none;
  padding: 100px 20px;
  height: 100%;
}




/* Menu */






/* Pagina tramites */
#Curp {background-color: green;
    height: 250%;
      font-family: Arial;
        border-radius: 2%;

}

#Rfc {background-color: #16C0CD;
    height: 250%;
      font-family: Arial;
        border-radius: 2%;
}


#Acta {background-color: #C83636;
    height: 200%;
      font-family: Arial;
        border-radius: 2%;
}



/* Mbutton Curp */
.ir1 {
 padding: 15px 25px;
 border: unset;
 border-radius: 15px;
 color: #212121;
 z-index: 1;
 background: white;
 position: relative;
 font-weight: 1000;
 font-size: 17px;
 -webkit-box-shadow: 4px 8px 19px -3px rgba(0,0,0,0.27);
 box-shadow: 4px 8px 19px -3px rgba(0,0,0,0.27);
 transition: all 250ms;
 overflow: hidden;
  cursor: pointer;
}

.ir1::before {
 content: "";
 position: absolute;
 top: 0;
 left: 0;
 height: 100%;
 width: 0;
 border-radius: 15px;
 background-color: green;
 z-index: -1;
 -webkit-box-shadow: 4px 8px 19px -3px rgba(0,0,0,0.27);
 box-shadow: 4px 8px 19px -3px rgba(0,0,0,0.27);
 transition: all 250ms
}

.ir1:hover {
 color: #e8e8e8;
}

.ir1:hover::before {
 width: 100%;
}




/* button rfc*/
.ir2 {
 padding: 15px 25px;
 border: unset;
 border-radius: 15px;
 color: #212121;
 z-index: 1;
 background: white;
 position: relative;
 font-weight: 1000;
 font-size: 17px;
 -webkit-box-shadow: 4px 8px 19px -3px rgba(0,0,0,0.27);
 box-shadow: 4px 8px 19px -3px rgba(0,0,0,0.27);
 transition: all 250ms;
 overflow: hidden;
  cursor: pointer;
}

.ir2::before {
 content: "";
 position: absolute;
 top: 0;
 left: 0;
 height: 100%;
 width: 0;
 border-radius: 15px;
 background-color: blue;
 z-index: -1;
 -webkit-box-shadow: 4px 8px 19px -3px rgba(0,0,0,0.27);
 box-shadow: 4px 8px 19px -3px rgba(0,0,0,0.27);
 transition: all 250ms
}

.ir2:hover {
 color: #e8e8e8;
}

.ir2:hover::before {
 width: 100%;
}




/* Button acta de nacimiento */
.ir3 {
 padding: 15px 25px;
 border: unset;
 border-radius: 15px;
 color: #212121;
 z-index: 1;
 background: white;
 position: relative;
 font-weight: 1000;
 font-size: 17px;
 -webkit-box-shadow: 4px 8px 19px -3px rgba(0,0,0,0.27);
 box-shadow: 4px 8px 19px -3px rgba(0,0,0,0.27);
 transition: all 250ms;
 overflow: hidden;
  cursor: pointer;
}

.ir3::before {
 content: "";
 position: absolute;
 top: 0;
 left: 0;
 height: 100%;
 width: 0;
 border-radius: 15px;
 background-color: darkred;
 z-index: -1;
 -webkit-box-shadow: 4px 8px 19px -3px rgba(0,0,0,0.27);
 box-shadow: 4px 8px 19px -3px rgba(0,0,0,0.27);
 transition: all 250ms
}

.ir3:hover {
 color: #e8e8e8;
}

.ir3:hover::before {
 width: 100%;
}






/* Tramites pagina CURP*/


.CNombre {
  --input-focus: #2d8cf0;
  --font-color: #323232;
  --font-color-sub: #666;
  --bg-color: #fff;
  --main-color: #323232;
  width: 200px;
  height: 40px;
  border-radius: 5px;
  border: 2px solid var(--main-color);
  background-color: var(--bg-color);
  box-shadow: 4px 4px var(--main-color);
  font-size: 15px;
  font-weight: 600;
  color: var(--font-color);
  padding: 5px 10px;
  outline: none;
}

.CNombre::placeholder {
  color: var(--font-color-sub);
  opacity: 0.8;
}

.CNombre:focus {
  border: 2px solid var(--input-focus);
}






.Gobierno{
  border-radius: 10%;



      position: absolute;
top: 250px; left: 1170px;

  }








/* Pagar Tramites Curp*/

.PagarCurp {
 padding: 15px 25px;
 border: unset;
 border-radius: 15px;
 color: #212121;
 z-index: 1;
 background: #e8e8e8;
 position: relative;
 font-weight: 1000;
 font-size: 17px;
 -webkit-box-shadow: 4px 8px 19px -3px rgba(0,0,0,0.27);
 box-shadow: 4px 8px 19px -3px rgba(0,0,0,0.27);
 transition: all 250ms;
 overflow: hidden;
   cursor: pointer;
}

.PagarCurp::before {
 content: "";
 position: absolute;
 top: 0;
 left: 0;
 height: 100%;
 width: 0;
 border-radius: 15px;
 background-color: #212121;
 z-index: -1;
 -webkit-box-shadow: 4px 8px 19px -3px rgba(0,0,0,0.27);
 box-shadow: 4px 8px 19px -3px rgba(0,0,0,0.27);
 transition: all 250ms
}

.PagarCurp:hover {
 color: #e8e8e8;
}

.PagarCurp:hover::before {
 width: 100%;
}




/* Tabla de la pagina producto inferior*/
.cardDesP {
  overflow: hidden;
  border-radius: 0.5rem;
  max-width: 500px;
  background-color: hotpink;

    padding: 1rem;
}

/* Lo borre por accidente*/

.cardDesP2 {
  overflow: hidden;
  border-radius: 0.5rem;
    border: 2px hotpink solid;

  max-width: 9000px;
  background-color: white;
  color: black;
    padding: 1rem;
}



/* PagInicio Califica la pagina*/

.calif {

  padding: 1rem;
  background-color: #fff;
  max-width: 1020px;
  border-radius: 20px;
  box-shadow: 10px 10px #323232;
  border: 3px solid #323232;
     
}




.rating:not(:checked) > input {

  position: absolute;
  appearance: none;


}

.rating:not(:checked) > label {

  float: right;
  cursor: pointer;
  font-size: 30px;
  color: #666;

}

.rating:not(:checked) > label:before {

  content: '★';

}

.rating > input:checked + label:hover,
.rating > input:checked + label:hover ~ label,
.rating > input:checked ~ label:hover,
.rating > input:checked ~ label:hover ~ label,
.rating > label:hover ~ input:checked ~ label {
  color: #e58e09;


}

.rating:not(:checked) > label:hover,
.rating:not(:checked) > label:hover ~ label {
  color: #ff9e0b;

}

.rating > input:checked ~ label {
  color: #ffa723;

}








.social-links,.flex-center {
  display: flex;
  justify-content: center;
  align-items: center;
}

.social-btn {
  cursor: pointer;
  height: 50px;
  width: 50px;
  font-family: 'Titillium Web', sans-serif;
  color: #333;
  border-radius: 10px;
  box-shadow: 0px 10px 10px rgba(0,0,0,0.1);
  background: white;
  margin: 5px;
  transition: 0.3s;
  justify-content: center;
}

.social-btn svg {
  height: 24px;
  width: 24px;
}

.social-btn span {
  width: 0px;
  overflow: hidden;
  transition: 0.3s;
  text-align: center;
  margin-left: 5px;
}

.social-btn:hover {
  width: 300px;
  border-radius: 5px;
}

.social-btn:hover span {
  padding: 2px;
  width: 260px;
}

#Facebook svg {
  fill: #3b5999;
}

#Gmail svg {
  fill: #dd4b39;
}

#Wassap {
  fill: #00ff00;
}












  /* Pagina productos  */


.Prod {
  /* color used to softly clip top and bottom of the .words container */
--bg-color:white;
  background-color: var(--bg-color);
  padding: -20rem -5rem;
  border-radius: 1.25rem;
}
.loader {
  color: rgb(124, 124, 124);
  font-family: "Poppins", sans-serif;
  font-weight: 500;
  font-size: 25px;
  -webkit-box-sizing: content-box;
  box-sizing: content-box;
  height: 50px;
  padding: 10px 10px;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  border-radius: 8px;
}

.words {
  overflow: hidden;
  position: relative;
}
.words::after {
  content: "";
  position: absolute;
  inset: 8;
  background: linear-gradient(
    var(--bg-color) 5%,
    transparent 20%,
    transparent 70%,
    var(--bg-color) 90%
  );
  z-index: 100;
}

.word {
  display: block;
  height: 100%;
  padding-left: 8px;

  animation: spin_4991 10s infinite;
}

@keyframes spin_4991 {
  15% {
    -webkit-transform: translateY(-102%);
    transform: translateY(-102%);
  }

  25% {
    -webkit-transform: translateY(-100%);
    transform: translateY(-100%);
  }

  35% {
    -webkit-transform: translateY(-202%);
    transform: translateY(-202%);
  }

  50% {
    -webkit-transform: translateY(-200%);
    transform: translateY(-200%);
  }

  60% {
    -webkit-transform: translateY(-302%);
    transform: translateY(-302%);
  }

  75% {
    -webkit-transform: translateY(-300%);
    transform: translateY(-300%);
  }

  85% {
    -webkit-transform: translateY(-402%);
    transform: translateY(-402%);
  }



  100% {
    -webkit-transform: translateY(-400%);
    transform: translateY(-400%);
  }
}




  /* Pagina carrito Input cantidad  */

  .inputCan {
  max-width: 190px;
  height: 44px;
  background-color: #05060f0a;
  border-radius: .5rem;
  padding: 0 1rem;
  border: 2px solid transparent;
  font-size: 1rem;
  transition: border-color .3s cubic-bezier(.25,.01,.25,1) 0s, color .3s cubic-bezier(.25,.01,.25,1) 0s,background .2s cubic-bezier(.25,.01,.25,1) 0s;
}


  /* Pagina carrito bUTTON Pagar  */

  .cartBtn {

  width: 155px;
  height: 50px;
  border: none;
  border-radius: 0px;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 7px;
  color: white;
  font-weight: 500;
  position: relative;
  background-color: rgb(29, 29, 29);
  box-shadow: 0 20px 30px -7px rgba(27, 27, 27, 0.219);
  transition: all 0.3s ease-in-out;
  cursor: pointer;
  overflow: hidden;
}

.cart {
  z-index: 2;
}

.cartBtn:active {
  transform: scale(0.96);
}

.product {
  position: absolute;
  width: 12px;
  border-radius: 3px;
  content: "";
  left: 50px;
  bottom: 23px;
  opacity: 0;
  z-index: 1;
  fill: rgb(211, 211, 211);
}

.cartBtn:hover .product {
  animation: slide-in-top 1.2s cubic-bezier(0.250, 0.460, 0.450, 0.940) both;
}

@keyframes slide-in-top {
  0% {
    transform: translateY(-30px);
    opacity: 1;
  }

  100% {
    transform: translateY(0) rotate(-90deg);
    opacity: 1;
  }
}

.cartBtn:hover .cart {
  animation: slide-in-left 1s cubic-bezier(0.250, 0.460, 0.450, 0.940) both;
}

@keyframes slide-in-left {
  0% {
    transform: translateX(-10px);
    opacity: 0;
  }

  100% {
    transform: translateX(0);
    opacity: 1;
  }
}






  /* Pagina carrito INPUT pagar   */

  .input-container {
  position: relative;
  margin: 20px;
}

label {
  display: block;
  margin-bottom: 5px;
  color: #333;
}

.input[type="text"] {
  padding: 10px;
  font-size: 16px;
  border: none;
  border-radius: 4px;
  background-color: #f1f1f1;
  color: #333;
  width: 300px;
  outline: none;
}

.underline {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 0;
  height: 1px;
  background-color: #4158D0;
  background-image: linear-gradient(43deg, #4158D0 0%, #C850C0 10%, #FFCC70 100%);
  transition: width 0.3s;
}

.input[type="text"]:focus + .underline {
  width: 47%;
}

@keyframes floating-label {
  0% {
    transform: translateY(0);
    opacity: 1;
  }

  100% {
    transform: translateY(-25px);
    opacity: 0;
  }
}

.input[type="text"]:placeholder-shown + label {
  position: absolute;
  top: 50%;
  left: 10px;
  transform: translateY(-50%);
  font-size: 14px;
  color: #777;
  pointer-events: none;
  transition: transform 0.3s, font-size 0.3s, color 0.3s;
}

.input[type="text"]:focus:not(:placeholder-shown) + label {
  transform: translateY(-25px);
  font-size: 12px;
  background-color: #4158D0;
  background-image: linear-gradient(43deg, #4158D0 0%, #C850C0 46%, #FFCC70 100%);
  animation: floating-label 0.3s forwards;
}







  /* Pagina carrito INPUT Number   */
label {
  display: block;
  margin-bottom: 5px;
  color: #333;
}

.input[type="number"] {
  padding: 10px;
  font-size: 16px;
  border: none;
  border-radius: 4px;
  background-color: #f1f1f1;
  color: #333;
  width: 300px;
  outline: none;
}

.underline {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 0;
  height: 1px;
  background-color: #4158D0;
  background-image: linear-gradient(43deg, #4158D0 0%, #C850C0 10%, #FFCC70 100%);
  transition: width 0.3s;
}

.input[type="number"]:focus + .underline {
  width: 47%;
}

@keyframes floating-label {
  0% {
    transform: translateY(0);
    opacity: 1;
  }

  100% {
    transform: translateY(-25px);
    opacity: 0;
  }
}

.input[type="number"]:placeholder-shown + label {
  position: absolute;
  top: 50%;
  left: 10px;
  transform: translateY(-50%);
  font-size: 14px;
  color: #777;
  pointer-events: none;
  transition: transform 0.3s, font-size 0.3s, color 0.3s;
}

.input[type="number"]:focus:not(:placeholder-shown) + label {
  transform: translateY(-25px);
  font-size: 12px;
  background-color: #4158D0;
  background-image: linear-gradient(43deg, #4158D0 0%, #C850C0 46%, #FFCC70 100%);
  animation: floating-label 0.3s forwards;
}






  /* Pagina carrito INPUT tel   */
label {
  display: block;
  margin-bottom: 5px;
  color: #333;
}

.input[type="tel"] {
  padding: 10px;
  font-size: 16px;
  border: none;
  border-radius: 4px;
  background-color: #f1f1f1;
  color: #333;
  width: 300px;
  outline: none;
}

.underline {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 0;
  height: 1px;
  background-color: #4158D0;
  background-image: linear-gradient(43deg, #4158D0 0%, #C850C0 10%, #FFCC70 100%);
  transition: width 0.3s;
}

.input[type="tel"]:focus + .underline {
  width: 47%;
}

@keyframes floating-label {
  0% {
    transform: translateY(0);
    opacity: 1;
  }

  100% {
    transform: translateY(-25px);
    opacity: 0;
  }
}

.input[type="tel"]:placeholder-shown + label {
  position: absolute;
  top: 50%;
  left: 10px;
  transform: translateY(-50%);
  font-size: 14px;
  color: #777;
  pointer-events: none;
  transition: transform 0.3s, font-size 0.3s, color 0.3s;
}

.input[type="tel"]:focus:not(:placeholder-shown) + label {
  transform: translateY(-25px);
  font-size: 12px;
  background-color: #4158D0;
  background-image: linear-gradient(43deg, #4158D0 0%, #C850C0 46%, #FFCC70 100%);
  animation: floating-label 0.3s forwards;
}




  /* Pagina carrito INPUT email   */
label {
  display: block;
  margin-bottom: 5px;
  color: #333;
}

.input[type="email"] {
  padding: 10px;
  font-size: 16px;
  border: none;
  border-radius: 4px;
  background-color: #f1f1f1;
  color: #333;
  width: 300px;
  outline: none;
}

.underline {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 0;
  height: 1px;
  background-color: #4158D0;
  background-image: linear-gradient(43deg, #4158D0 0%, #C850C0 10%, #FFCC70 100%);
  transition: width 0.3s;
}

.input[type="email"]:focus + .underline {
  width: 47%;
}

@keyframes floating-label {
  0% {
    transform: translateY(0);
    opacity: 1;
  }

  100% {
    transform: translateY(-25px);
    opacity: 0;
  }
}

.input[type="email"]:placeholder-shown + label {
  position: absolute;
  top: 50%;
  left: 10px;
  transform: translateY(-50%);
  font-size: 14px;
  color: #777;
  pointer-events: none;
  transition: transform 0.3s, font-size 0.3s, color 0.3s;
}

.input[type="email"]:focus:not(:placeholder-shown) + label {
  transform: translateY(-25px);
  font-size: 12px;
  background-color: #4158D0;
  background-image: linear-gradient(43deg, #4158D0 0%, #C850C0 46%, #FFCC70 100%);
  animation: floating-label 0.3s forwards;
}


















  /* Pagina inicio comentario  */
label {
  display: block;
  margin-bottom: 5px;
  color: #333;
}
.input2[type="text"] {
  padding: 10px;
  font-size: 16px;
  border: none;
  border-radius: 4px;
  background-color: #f1f1f1;
  color: #333;
  width: 800px;
  outline: none;
}

.underline2 {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 0;
  height: 1px;
  background-color: #4158D0;
  background-image: linear-gradient(63deg, #4158D0 0%, #C850C0 50%, #FFCC70 100%);
  transition: width 0.3s;
}

.input2[type="text"]:focus + .underline2 {
  width: 97%;
}

@keyframes floating-label {
  0% {
    transform: translateY(0);
    opacity: 1;
  }

  100% {
    transform: translateY(-25px);
    opacity: 0;
  }
}

.input2[type="text"]:placeholder-shown + label {
  position: absolute;
  top: 50%;
  left: 10px;
  transform: translateY(-50%);
  font-size: 14px;
  color: #777;
  pointer-events: none;
  transition: transform 0.3s, font-size 0.3s, color 0.3s;
}

.input2[type="text"]:focus:not(:placeholder-shown) + label {
  transform: translateY(-25px);
  font-size: 12px;
  background-color: #4158D0;
  background-image: linear-gradient(43deg, #4158D0 0%, #C850C0 46%, #FFCC70 100%);
  animation: floating-label 0.3s forwards;
}











.comen {

  width: 1500px;
  height: 300px;

  padding: 1rem;
  background: white;
  max-width: 1340px;
  border-radius: 10px;
  box-shadow: 10px 10px #323232;
  border: 3px solid #323232;
}




.ReglasOrtograficas {
    color: #df0044;
        font-family: 'Montserrat';font-size: 50px;


  font-style: italic;
}


.ReglasOrtograficas2 {
    color: #df0044;
        font-family: 'Montserrat';


  font-style: italic;
}





/* Tabla  */

.AutoIn {
  overflow: hidden;
  border-radius: 0.5rem;
  max-width: 300px;
  background-color: #fff;
  color: #212121;
}

.image {
  height: 8rem;
  width: 100%;
  object-fit: cover;
  background-color: rgb(204, 0, 255);
  background-image: linear-gradient(to right, rgb(255, 174, 0), rgb(204, 0, 255));
}

.content {
  padding: 1rem;
  text-align: center;
}



.action {
  margin-top: 1rem;
  display: inline-block;
  width: 100%;
  background-color: rgb(0, 0, 0);
  padding-top: 1rem;
  padding-bottom: 1rem;
  border-radius: 4px;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 700;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: rgba(255, 255, 255, 1);
  text-decoration: none;
}


/* Tabla  */

.LapizIn {
  overflow: hidden;
  border-radius: 0.5rem;
  max-width: 300px;
  background-color: #fff;
  color: #212121;
}

.image {
  height: 8rem;
  width: 100%;
  object-fit: cover;
  background-color: rgb(204, 0, 255);
  background-image: linear-gradient(to right, rgb(255, 174, 0), rgb(204, 0, 255));
}

.content {
  padding: 1rem;
  text-align: center;
}



.action {
  margin-top: 1rem;
  display: inline-block;
  width: 100%;
  background-color: rgb(0, 0, 0);
  padding-top: 1rem;
  padding-bottom: 1rem;
  border-radius: 4px;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 700;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: rgba(255, 255, 255, 1);
  text-decoration: none;
}

/* Tabla  */



.AguilaIn {
  overflow: hidden;
  border-radius: 0.5rem;
  max-width: 300px;
  background-color: #fff;
  color: #212121;
}

.image {
  height: 8rem;
  width: 100%;
  object-fit: cover;
  background-color: rgb(204, 0, 255);
  background-image: linear-gradient(to right, rgb(255, 174, 0), rgb(204, 0, 255));
}

.content {
  padding: 1rem;
  text-align: center;
}



.action {
  margin-top: 1rem;
  display: inline-block;
  width: 100%;
  background-color: rgb(0, 0, 0);
  padding-top: 1rem;
  padding-bottom: 1rem;
  border-radius: 4px;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 700;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: rgba(255, 255, 255, 1);
  text-decoration: none;
}


/* Tabla  */

/* From Uiverse.io by Yaya12085 */ 
.LeerIn {
  overflow: hidden;
  border-radius: 0.5rem;
  max-width: 300px;
  background-color: #fff;
  color: #212121;
}

.image {
  height: 8rem;
  width: 100%;
  object-fit: cover;
  background-color: rgb(204, 0, 255);
  background-image: linear-gradient(to right, rgb(255, 174, 0), rgb(204, 0, 255));
}

.content {
  padding: 1rem;
  text-align: center;
}



.action {
  margin-top: 1rem;
  display: inline-block;
  width: 100%;
  background-color: rgb(0, 0, 0);
  padding-top: 1rem;
  padding-bottom: 1rem;
  border-radius: 4px;
  font-size: 0.875rem;
  line-height: 1.25rem;
  font-weight: 700;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  color: rgba(255, 255, 255, 1);
  text-decoration: none;
}




.TitAgu {
    color: Black;
        font-family: 'Montserrat';font-size: 70px;


  font-style: italic;
}

.InfAgu {
    color: Black;
        font-family: 'Montserrat';font-size: 30px;


  font-style: italic;
}


.EjeAgu {
    color: Black;
        font-family: 'Montserrat';font-size: 30px;

  text-indent: 50px;
  font-style: italic;
}















   .TitAgu {
   color: white;
        font-family: 'Montserrat';font-size: 50px;

  
  font-style: italic;
}
   .InfGra {
   color: white;
        font-family: 'Montserrat';font-size: 30px;


  font-style: italic;
}

   .EjemGra {
   color: White;
        font-family: 'Montserrat';font-size: 30px;

  text-indent: 50px;
  font-style: italic;
}



.PagGra{
  background-color: #030500;

}









.text-2 {
  margin-top: 1rem;
  font-weight: 900;
  text-transform: uppercase;
}

.text-2 span:first-child {
  font-size: 2.25rem;
  line-height: 2.5rem;
  font-weight: 900;
}

.text-2 span:last-child {
  margin-top: 0.5rem;
  display: block;
  font-size: 0.875rem;
  line-height: 1.25rem;
}


.mark1 { 
  background-color: yellow;
  color: black;
}


.PagEs { 
  background-color: #de0e56 ;
}


   .InIn {
   color: #df0044;
        font-family: 'Montserrat';font-size: 20px;

  text-indent: 50px;
  font-style: italic;
}





/* From Uiverse.io by Mike11jr */ 
.Inte {
 width: 330px;
 height: 50px;
 font-size: 1.1em;
 cursor: pointer;
 background-color: black;
 color: #fff;
 border: none;
 border-radius: 5px;
 transition: all .4s;
}

.Inte:hover {
 border-radius: 5px;
 transform: translateY(-10px);
 box-shadow: 0 7px 0 -2px #f85959,
  0 15px 0 -4px #39a2db,
  0 16px 10px -3px #39a2db;
}

.Inte:active {
 transition: all 0.2s;
 transform: translateY(-5px);
 box-shadow: 0 2px 0 -2px red,
  0 8px 0 -4px #39a2db,
  0 12px 10px -3px #39a2db;
}
  </style>
<div id="Integrantes" class="tabcontent">
  <br>
  <br>

<center><h1><FONT class="TitAgu">Integrantes del equipo 1</FONT></h1></center>
<br>
<center>
<table>

  <tbody id="myTable">
  <tr>





<td>


<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
.cardinal {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  max-width: 300px;
  margin: auto;
  text-align: center;
  font-family: arial;
}

.titlePro {
  color: grey;
  font-size: 18px;
}

.Con {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
  font-size: 18px;
}

a {
  text-decoration: none;
  font-size: 22px;
  color: black;
}

button:hover, a:hover {
  opacity: 0.7;
}
</style>
</head>
<body>

<div class="cardinal">
  <img src="https://i.pinimg.com/736x/e2/a8/00/e2a8006cdf31b9fd5d41fee67cdfbc80.jpg" alt="John" style="width:100%">
   <FONT COLOR="black"><h1>Casango</h1></FONT>
  <p class="titlePro">Programador</p>
  <p class="titlePro">Ing. Manufactura Aeronautica</p>
  <FONT COLOR="black"><p>UTT</p></FONT>
  <p><button class="Con">664-200-8313</button></p>
</div>

</body>
</html>



</td>






<td>


<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
.cardinal {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  max-width: 300px;
  margin: auto;
  text-align: center;
  font-family: arial;
}

.titlePro {
  color: grey;
  font-size: 18px;
}

.Con {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
  font-size: 18px;
}

a {
  text-decoration: none;
  font-size: 22px;
  color: black;
}

button:hover, a:hover {
  opacity: 0.7;
}
</style>
</head>
<body>

<div class="cardinal">
  <img src="https://i.pinimg.com/736x/39/dc/c8/39dcc85b4e5dbbb187c715e9fbe8dfb9.jpg" alt="John" style="width:100%">
   <FONT COLOR="black"><h1>Jesus</h1></FONT>
     <p class="titlePro">Programador</p>
  <p class="titlePro">Ing. Manufactura Aeronautica</p>
  <FONT COLOR="black"><p>UTT</p></FONT>

  <p><button class="Con">663-300-0663</button></p>
</div>

</body>
</html>



</td>



<td>


<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
.cardinal {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  max-width: 300px;
  margin: auto;
  text-align: center;
  font-family: arial;
}

.titlePro {
  color: grey;
  font-size: 18px;
}

.Con {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
  font-size: 18px;
}

a {
  text-decoration: none;
  font-size: 22px;
  color: black;
}

button:hover, a:hover {
  opacity: 0.7;
}
</style>
</head>
<body>

<div class="cardinal">
  <img src="https://i.pinimg.com/736x/58/94/9a/58949a0ea74d57d5bd5c7f1257b9f21b.jpg" alt="John" style="width:100%">
   <FONT COLOR="black"><h1>Emmanuel</h1></FONT>
     <p class="titlePro">Programador</p>
  <p class="titlePro">Ing. Manufactura Aeronautica</p>

  <FONT COLOR="black"><p>UTT</p></FONT>
  <p><button class="Con">663-300-0663</button></p>
</div>

</body>
</html>



</td>




<td>


<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
.cardinal {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  max-width: 300px;
  margin: auto;
  text-align: center;
  font-family: arial;
}

.titlePro {
  color: grey;
  font-size: 18px;
}

.Con {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
  font-size: 18px;
}

a {
  text-decoration: none;
  font-size: 22px;
  color: black;
}

button:hover, a:hover {
  opacity: 0.7;
}
</style>
</head>
<body>

<div class="cardinal">
  <img src="https://i.pinimg.com/736x/ac/38/0b/ac380b779fee182cb1a5e5c59bdb2768.jpg" alt="John" style="width:100%">
   <FONT COLOR="black"><h1>Nacho</h1></FONT>
     <p class="titlePro">Programador</p>
  <p class="titlePro">Ing. Manufactura Aeronautica</p>
  <FONT COLOR="black"><p>UTT</p></FONT>
 
  <p><button class="Con">664-445-9228</button></p>
</div>

</body>
</html>



</td>




</tr>
</tbody>
</table>
</center>









</div>











<div id="SobreEsdrujula" class="tabcontent">
<div class="PagEs">















<br>
<center><h1><FONT class="TitAgu">Sobreesdrujula</FONT></h1></center>
<br>
<br>
<center><h3 class="InfAgu"> Son aquellas cuya sílaba tónica está antes de la
antepenúltima y se tildan siempre.
</h3></center>

<center><h3 class="InfAgu"> Cada sílaba representa un sonido específico compuesto por una o varias vocales y una o más consonantes. Por ejemplo, la palabra “fríamente” se compone de “frí-”, “a-”, “men-” y “-te”.
</h3></center>

<br>
<h2 class="EjeAgu">Ejemplos de sobreesdrujula:</h2>

<br>
<br>









<center>
<table>

  <tbody id="myTable">
  <tr>





<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/e6/d6/3f/e6d63ffe005b56abc338c8cd80a3f92e.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      mágicamente
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/30/26/d2/3026d201dd4082571c5bc3f44bea8e01.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      tómatelo
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/26/d1/59/26d159b8ad75f77884e6c6687fb71f96.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      Ábremelo
    </a>

 
  </div>
</div>
</td>



</tr>
</tbody>
</table>
</center>



<br>









<center>
<table>

  <tbody id="myTable">
  <tr>





<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/18/a6/99/18a699f7313bc7aec566d2e17f8d3610.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      Académicamente
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/7a/5a/36/7a5a368b0cb4d390bf285935ce69ab1c.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
       Ágilmente
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/82/d2/37/82d2375393b5aa1683aa6e28b3813041.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      Apréndetelo
    </a>

 
  </div>
</div>
</td>



</tr>
</tbody>
</table>
</center>




<br>





<center>
<table>

  <tbody id="myTable">
  <tr>





<td>
<div class="AutoIn">
        <img src="https://www.chumbogordo.com.br/wp-content/uploads/2020/10/INUTIL.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      Inútilmente
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/1f/bc/6a/1fbc6a1ec738b9f25bbb0a13c3d3266b.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      Quédatelo
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/ba/4a/f3/ba4af3efca70d551f143d9e9fbf913fa.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      lléveselo
    </a>

 
  </div>
</div>
</td>







<td>
<div class="AutoIn">
        <img src="https://mentat.com.ar/blogmentat/wp-content/uploads/2014/12/Analog-and-digital-minds_vectorized.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      Analógicamente
    </a>

 
  </div>
</div>
</td>



</tr>
</tbody>
</table>
</center>























</div>
</div>













































<div id="ProductoPag" class="tabcontent">

<br>
<center><h1><FONT class="TitAgu">Agudas</FONT></h1></center>
<br>
<br>
<center><h3 class="InfAgu"> Las palabras agudas son las que llevan el acento en la última
sílaba y se les marca la tilde a aquellas que terminan en n, s y
vocal.
</h3></center>

<br>
<h2 class="EjeAgu">Ejemplos Concterminancion en N:</h2>

<br>
<br>









<center>
<table>

  <tbody id="myTable">
  <tr>





<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/75/3f/b1/753fb1ba4bad65a3e73ecc6965dd88ad.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      Alacr&Aacute;n
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/18/f2/a4/18f2a4761c5b979596a9dccc2b58703a.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      Emoci&Oacute;n
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/d4/cf/5c/d4cf5cac38edb4f6d7cf05002c0f4ae8.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      Jard&Iacute;n
    </a>

 
  </div>
</div>
</td>



</tr>
</tbody>
</table>
</center>



<br>

<br>
<h2 class="EjeAgu">Ejemplos Concterminancion en S:</h2>

<br>
<br>







<center>
<table>

  <tbody id="myTable">
  <tr>





<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/03/35/fb/0335fbd8555a3cd20f2a644ba573a391.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      Estr&Eacute;s
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/474x/e5/56/ab/e556abe60be7421d18de3d911f6bb958.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      Adi&Oacute;s
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/c0/bf/b9/c0bfb9dd674ac393baecf11da75c16f7.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      Autob&Uacute;s
    </a>

 
  </div>
</div>
</td>



</tr>
</tbody>
</table>
</center>




<br>

<br>
<h2 class="EjeAgu">Cuando terminan en Vocal:</h2>

<br>
<br>





<center>
<table>

  <tbody id="myTable">
  <tr>





<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/29/a6/69/29a6696b81ee42c48fef9db47e3134a1.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      Subi&Oacute;
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/32/4b/7d/324b7d4936f4b3e3c04dfb7be8bcb3a3.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      Manat&Iacute;
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/736x/98/87/c9/9887c9ae48332888916f92a57d4c6127.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      MAM&Aacute;
    </a>

 
  </div>
</div>
</td>







<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/736x/d5/31/be/d531bee7e479e262b6ae57f167ee49e0.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      Comit&Eacute;
    </a>

 
  </div>
</div>
</td>



</tr>
</tbody>
</table>
</center>











</div>






































<!DOCTYPE html>
<html>
<head>
   <link rel="stylesheet" href="Style.css">
<meta name="viewport" content="width=device-width, initial-scale=1">
</head>
<body>






  <!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
  <script src="https://cdn.jsdelivr.net/npm/jquery@3.7.1/dist/jquery.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>

</head>







<nav class="navbar navbar-expand-sm bg-dark navbar-dark fixed-top">  

</nav>
</body>


</body>
</html>







<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<div class="Hola offcanvas offcanvas-start text-bg-dark" id="Menu">
  <div class="Hola offcanvas-header">
    <h5><FONT class="ReglasOrtograficas" COLOR="white">UTT</FONT></h5>


    <button type="button" class="Hola btn-close btn-close-white" data-bs-dismiss="offcanvas"></button>



  </div>

  <div class="Hola offcanvas-body">



 <div class="BuIni">


 <button class="ButtonIni" class="tablink" onclick="openPage('InicioPag')" id="defaultOpen" data-bs-dismiss="offcanvas">

    <div class="textIni">
        <h1><span>Inicio</span></h1>
    </div>
    <div class="cloneIni">
        <h1><span>Inicio</span></h1>

    </div>
    <svg width="20px" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
        <path stroke-linecap="round" stroke-linejoin="round" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
    </svg>
</button></div>

</div>




 <div class="BuPro">  


<button class="ButtonPro" class="tablink" onclick="openPage('ProductoPag')" data-bs-dismiss="offcanvas">

    <div class="textPro">
        <h1><span>Agudas</span></h1>
    </div>
    <div class="clonePro">
        <h1><span>Agudas</span></h1>

    </div>
    <svg width="20px" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
        <path stroke-linecap="round" stroke-linejoin="round" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
    </svg>
</button>

</div>



<div class="BuSobre"> 


<button class="ButtonSo" class="tablink" onclick="openPage('SobreEsdrujula')" data-bs-dismiss="offcanvas">

    <div class="textSo">
        <h1><span>Sobreesdrujula</span></h1>
    </div>
    <div class="cloneSo">
        <h1><span>Sobreesdrujula</span></h1>

    </div>
    <svg width="20px" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
        <path stroke-linecap="round" stroke-linejoin="round" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
    </svg>
</button>
</div>





 <div class="BuTra"> 


<button class="ButtonTra" class="tablink" onclick="openPage('Graves')" data-bs-dismiss="offcanvas">

    <div class="textTra">
        <h1><span>Graves</span></h1>
    </div>
    <div class="cloneTra">
        <h1><span>Graves</span></h1>

    </div>
    <svg width="20px" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
        <path stroke-linecap="round" stroke-linejoin="round" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
    </svg>
</button>

</div>






 <div class="BuCar"> 



<button class="ButtonCar" class="tablink" onclick="openPage('CarritoPag')" data-bs-dismiss="offcanvas">

    <div class="textCar">
        <h1><span>Esdrujula</span></h1>
    </div>
    <div class="cloneCar">
        <h1><span>Esdrujula</span></h1>

    </div>
    <svg width="20px" xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
        <path stroke-linecap="round" stroke-linejoin="round" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
    </svg>
</button>
</div>











  </div>


</div>

<nav class="navbar navbar-expand-sm bg-dark navbar-dark fixed-top"> 
<div class="Hola container-fluid mt-3">

<img class="Icono" src="https://i.pinimg.com/736x/21/94/ea/2194ea4009476303116804052f792d39.jpg" class="rounded-circle" alt="Cinque Terre" width="105" height="105">




  <h1><font class="Punto">............</font><FONT class="ReglasOrtograficas">UTT</FONT></h1>








  <div class="Menu">
  
<button class="MenuB" type="button" data-bs-toggle="offcanvas" data-bs-target="#Menu">
    <span class="iconMenu">
        <svg viewBox="0 0 175 80" width="40" height="40">
            <rect width="80" height="15" fill="#f0f0f0" rx="10"></rect>
            <rect y="30" width="80" height="15" fill="#f0f0f0" rx="10"></rect>
            <rect y="60" width="80" height="15" fill="#f0f0f0" rx="10"></rect>
        </svg>
    </span>
    <span class="textM">MENU</span>
</button>

</div>







</nav>
</div>

</body>
</html>
























<div id="CarritoPag" class="tabcontent">

<br>
<br>







<br>





<br>
<center><h1><FONT class="TitGra">Esdrujúla</FONT></h1></center>
<br>
<br>
<center><h3 class="InfGra">Las palabras esdrújulas son excepcionales y bastante menos comunes en la lengua española, al menos en comparación con las graves y agudas, que componen casi la mayoría de las palabras de nuestro idioma. En parte porque sólo palabras de tres sílabas o más pueden ser esdrújulas. En general, llevan tilde en su sílaba tónica, sin importar su terminación.</h3></center>

<br>
<center><h3 class="InfGra"> Su antepenúltima sílaba es la sílaba tónica.</h3></center>

<br>
<br>
<h2 class="EjemGra">Ejemplos de palabras esdrújulas:</h2>

<br>
<br>









<center>
<table>

  <tbody id="myTable">
  <tr>





<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/e0/05/1e/e0051e5aadf4941a3dbc9adc2c328151.jpg" alt="Jane" width="300" height="250">
  <div class="content">

    <div class="text-2">

      <span>TE<mark class="mark1">LE</mark>FONO</span>
    </div>

    <a class="action">
      teléfono
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/d3/d0/a3/d3d0a34ffc92504b1b463aa81b54a82a.jpg" alt="Jane" width="300" height="250">
  <div class="content">

    <div class="text-2">

      <span><mark class="mark1">AR</mark>BOLES</span>
    </div>


    <a class="action">
      árboles
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/13/f4/47/13f447b12d02019d1c5feeeb6165fe80.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <div class="text-2">

      <span>O<mark class="mark1">CA</mark>MARA</span>
    </div>



    <a class="action">
      cámara
    </a>

 
  </div>
</div>
</td>



</tr>
</tbody>
</table>
</center>




<br>
<br>







<center>
<table>

  <tbody id="myTable">
  <tr>





<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/fc/22/f7/fc22f7ad0fdae77f9587e939a17c2a9e.jpg" alt="Jane" width="300" height="250">
  <div class="content">


    <div class="text-2">

      <span><mark class="mark1">PE</mark>TALO</span>
    </div>



    <a class="action">
      pétalo
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/48/f2/94/48f294d2f017b1355ca0854d1fd5778e.jpg" alt="Jane" width="300" height="250">
  <div class="content">


    <div class="text-2">

      <span><mark class="mark1">PA</mark>LIDO</span>
    </div>


    <a class="action">
      pálido
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/e6/94/af/e694af440d234ec15e33c3944dcd7c53.jpg" alt="Jane" width="300" height="250">
  <div class="content">


    <div class="text-2">

      <span>A<mark class="mark1">ME</mark>RICA</span>
    </div>



    <a class="action">
      América
    </a>

 
  </div>
</div>
</td>



</tr>
</tbody>
</table>
</center>





<br>





<center>
<table>

  <tbody id="myTable">
  <tr>





<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/fd/0e/31/fd0e314801b555609aee9f42534d0fa6.jpg" alt="Jane" width="300" height="250">
  <div class="content">


    <div class="text-2">

      <span><mark class="mark1">HI</mark>GADO</span>
    </div>


    <a class="action">
      hígado
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/46/96/8c/46968c4a0370f0df41b178d1429d79aa.jpg" alt="Jane" width="300" height="250">
  <div class="content">


 <div class="text-2">

      <span>E<mark class="mark1">JER</mark>CITO</span>
    </div>

    <a class="action">
      ejército
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/0c/ec/16/0cec16dc9eb382b8798be65510902f8a.jpg" alt="Jane" width="300" height="250">
  <div class="content">


 <div class="text-2">

      <span><mark class="mark1">FOS</mark>FORO</span>
    </div>


    <a class="action">
      fósforo
    </a>

 
  </div>
</div>
</td>







<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/c7/90/3b/c7903be4aa95cb8557eef48e4ec7d03b.jpg" alt="Jane" width="300" height="250">
  <div class="content">

<div class="text-2">

      <span><mark class="mark1">MA</mark>QUINA</span>
    </div>

    <a class="action">
      máquina
    </a>

 
  </div>
</div>
</td>



</tr>
</tbody>
</table>
</center>













</div>











































































<script>
function openCity(evt, cityName) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("contenido");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("ir1", "ir2", "ir3");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }
  document.getElementById(cityName).style.display = "block";
  evt.currentTarget.className += " active";
}

// Get the element with id="defaultOpen" and click on it
document.getElementById("defaultOpen").click();
</script>
   
</body>
</html> 








</div>






<div id="InicioPag" class="tabcontent">




<br>
<br>

 <center><h1><font class="Punto"></font><FONT class="ReglasOrtograficas">Ingeneria en Manufactura Aeronautica</FONT></h1></center>
<br>
<br>


<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<!-- Carousel -->
<div id="demo" class="carousel slide" data-bs-ride="carousel">

  <!-- Indicators/dots -->
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
  </div>
  
  <!-- The slideshow/carousel -->
  <div class="carousel-inner">
    <div class="carousel-item active">
      <center><img src="https://i.pinimg.com/736x/1d/f0/76/1df0768f543fb5bd46a815844af69226.jpg" alt="Los Angeles" class="d-block" style="width:50%"></center>
    </div>
    <div class="carousel-item">
      <center><img src="https://i.pinimg.com/736x/a8/18/ea/a818ea7847fd6f2fe0843123d2b9c22b.jpg" alt="Chicago" class="d-block" style="width:50%"></center>
    </div>
    <div class="carousel-item">
      <center><img src="https://i.pinimg.com/736x/31/0f/9d/310f9dc10801dba17978d457760ccd91.jpg" alt="New York" class="d-block" style="width:50%"></center>
    </div>
  </div>
  
  <!-- Left and right controls/icons -->
  <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
    <span class="carousel-control-next-icon"></span>
  </button>
</div>


</body>
</html>



<br>
 <center><h2><font class="Punto"></font><FONT class="ReglasOrtograficas2">Reglas Ortograficas</FONT></h2></center>
<br>



<center>
<table>

  <tbody id="myTable">
  <tr>





<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/c0/bf/b9/c0bfb9dd674ac393baecf11da75c16f7.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action" href="" onclick="openPage('ProductoPag')" data-bs-dismiss="offcanvas">
      Agudas
    </a>

 
  </div>
</div>
</td>




<td>

<div class="LapizIn">
        <img src="https://i.pinimg.com/564x/9c/0d/49/9c0d4957ff6fb4ea528106c34d9085a4.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action" href="" onclick="openPage('Graves')" data-bs-dismiss="offcanvas">
      Graves
    </a>

 
  </div>
</div>
</td>





<td>

<div class="AguilaIn">
        <img src="https://i.pinimg.com/564x/a9/c0/b1/a9c0b1c041bbc094ff46f28c4b0e57e6.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action" href="" onclick="openPage('CarritoPag')" data-bs-dismiss="offcanvas">
      Esdrujula
    </a>

 
  </div>
</div>
</td>





<td>
<div class="LeerIn">
        <img src="https://i.pinimg.com/564x/06/d1/45/06d145df3a6bfc2596855338340552b2.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action" href="" onclick="openPage('SobreEsdrujula')" data-bs-dismiss="offcanvas">
      sobreEsdrujula
    </a>

 
  </div>
</div>
</td>










</tr>




</tbody>
</table>
</center>


<br>

<center class="InIn"><h3>Tanto el acento prosódico, como el ortográfico y diacrítico presentan características específicas, ya sea que se aplican a una palabra, o bien, que son usados dentro de una oración. Al final todos tienen un papel incuestionable en el sistema de nuestra lengua.</h3></center>


<br>




<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">

</head>
<body>



<div class="GoogleMaps">
<div class="row210">
  <div class="column210">
    <div class="card210">
      
   <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3040.959731867018!2d-116.82750460484299!3d32.45997509597224!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80d93e743f2e3bd7%3A0xbf19e069ae61d678!2sUniversidad%20Tecnol%C3%B3gica%20de%20Tijuana!5e1!3m2!1ses-419!2smx!4v1724951190535!5m2!1ses-419!2smx" width="1326.5" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>

 






      <div class="container210">
        <FONT COLOR="black"><h2>Google Maps</h2>

        <p></p></FONT>


      </div>
    </div>
  </div>
</div>

</div>
<br>
<center> <button class="Inte" onclick="openPage('Integrantes')" id="defaultOpen" data-bs-dismiss="offcanvas">Integrantes</button></center>
<br>

</div>

</body>
</html>

</div>




    </div></div>
</div>
</center>
<br>
<br>













<div id="Graves" class="tabcontent">
<div class="PagGra">






<br>





<br>
<center><h1><FONT class="TitGra">Graves</FONT></h1></center>
<br>
<br>
<center><h3 class="InfGra"> En la lengua española, las palabras se dividen en sílabas. Una sílaba abarca un sonido específico compuesto por una o varias vocales y una o más consonantes. Por ejemplo, la palabra “lápiz” se compone de “lá-” y “piz”.</h3></center>

<br>
<center><h3 class="InfGra"> Como en el caso que nos interesa, “lápiz”, una palabra grave es aquella cuya sílaba tónica se encuentra en la penúltima sílaba, de modo que se trata de una palabra grave o palabra llana, técnicamente conocidas como palabras paroxítonas.</h3></center>

<br>
<br>
<h2 class="EjemGra">Ejemplos de palabras graves sin tilte:</h2>

<br>
<br>









<center>
<table>

  <tbody id="myTable">
  <tr>





<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/f2/43/b5/f243b5ba4a154244e4d14273c257b5a6.jpg" alt="Jane" width="300" height="250">
  <div class="content">

    <div class="text-2">

      <span><mark class="mark1">CO</mark>RREN</span>
    </div>

    <a class="action">
      Corren
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/12/93/32/1293324da9ff63459437db374aaea0c6.jpg" alt="Jane" width="300" height="250">
  <div class="content">

    <div class="text-2">

      <span><mark class="mark1">GER</mark>MEN</span>
    </div>


    <a class="action">
      Germen
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/4b/8d/00/4b8d00a673c80cb5cbb25d5e938f202b.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <div class="text-2">

      <span>O<mark class="mark1">ME</mark>GA</span>
    </div>



    <a class="action">
      Omega
    </a>

 
  </div>
</div>
</td>



</tr>
</tbody>
</table>
</center>




<br>
<br>







<center>
<table>

  <tbody id="myTable">
  <tr>





<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/58/f5/e1/58f5e1cd255217421e421cbe83e299b6.jpg" alt="Jane" width="300" height="250">
  <div class="content">


    <div class="text-2">

      <span><mark class="mark1">PO</mark>NY</span>
    </div>



    <a class="action">
      Pony
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/37/80/7b/37807b108e71557937fef9896de4068b.jpg" alt="Jane" width="300" height="250">
  <div class="content">


    <div class="text-2">

      <span>DE<mark class="mark1">RRA</mark>ME</span>
    </div>


    <a class="action">
      Derrame
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/97/e3/bf/97e3bf4afd6aba54c81770b90e8338f4.jpg" alt="Jane" width="300" height="250">
  <div class="content">


    <div class="text-2">

      <span>MI<mark class="mark1">RAN</mark>DO</span>
    </div>



    <a class="action">
      Mirando
    </a>

 
  </div>
</div>
</td>



</tr>
</tbody>
</table>
</center>




<br>

<br>
<h2 class="EjemGra">Palabras graves con tilde:</h2>

<br>
<br>





<center>
<table>

  <tbody id="myTable">
  <tr>





<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/4c/ce/fc/4ccefc3731861d2080bd145f2634aa05.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      L&Aacute;piz
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/96/dc/55/96dc55675e59412eabb985a35b52fb30.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      C&Eacute;sped
    </a>

 
  </div>
</div>
</td>



<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/70/aa/4d/70aa4d642c682c30f6d8a752985db6de.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      C&Aacute;rcel
    </a>

 
  </div>
</div>
</td>







<td>
<div class="AutoIn">
        <img src="https://i.pinimg.com/564x/19/a7/a8/19a7a84caaad981e4a263fc8d63516ae.jpg" alt="Jane" width="300" height="250">
  <div class="content">



    <a class="action">
      &Aacute;rbol
    </a>

 
  </div>
</div>
</td>



</tr>
</tbody>
</table>
</center>






















</div>
</div>






























</div>


<script>
function openPage(pageName,elmnt,color) {
  var i, tabcontent, tablinks;
  tabcontent = document.getElementsByClassName("tabcontent");
  for (i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < tablinks.length; i++) {
    tablinks[i].style.backgroundColor = "";
  }
  document.getElementById(pageName).style.display = "block";
  elmnt.style.backgroundColor = color;
}

// Codigo del navegador para cambiar pagina 
document.getElementById("defaultOpen").click();
</script>
   
</body>
</html> 
