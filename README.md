# turbo-octo-disco
body{
    background: #e5e5e5;
    margin: 0;
}

.blå{
    background: #c7ddea;
}

p{
    max-width: 30rem;
}


.orange{
    background: #f17949;
}

.gul{
    background: #fab131;
}

.grå{
    background: #a9a19e;
    height: 760px;
}
/* Ändringar 200909 */
.grå > article{
    display: grid;
    grid-template-columns: auto, auto, auto;
    
}

.bild{
    height: 200px;
}

.korttext{
    position: absolute;
    top: 150px;
    left: 20px;
    background: white;
    width: 256px;
    height: 308px;
    border-radius: 2%;
    align-items: center;
    
}

.korttext > p{
    position: absolute;
    bottom: 30px;
    color: rgba(0, 0, 0, 0.4);
    text-align: center;
    font-size: 11px;
    padding: 15px;
    font-weight: bold;
    line-height: 18px;
    
}

.korttext > h3{
    position: absolute;
    bottom: 140px;
    left: 85px;
}
.bildkort{
    position: absolute;
    width: 256px;
    height: 308px;
    left: 309px;
    top: 1065px;
    clip-path: margin-box;
}

.bildkort2{
    position: absolute;
    width: 256px;
    height: 308px;
    left: 592px;
    top: 1065px;
}

.bildkort3{
    position: absolute;
    width: 256px;
    height: 308px;
    left: 875px;
    top: 1065px;
}



/* Ändringar 200909 */

.hejhej{ 
    background: #fab131;
}

.låda1{
   background: #c7ddea; 
   justify-content: space-evenly;
}

.låda1 > h1{
    width: 300px;
    font-size: 50px; /*  fixat font-size */
}
.låda2, .låda4, .låda6{
    background: #ffffff;
}

.låda3{
    background: #ebebeb;
}
.låda5{
    background: #f17949;
}

aside{
    background: #a9a19e;
}

footer{
    background: #777574;
}


header, main, footer {
    margin: 0px 180px;
    padding: 0px;
}
p {
    font-family: 'Fira Sans', sans-serif;
}
h1 , h2, h3{
    font-family: 'Frank Ruhl Libre', serif;
}

.cards {
    display: grid;
    grid-template-rows: repeat(2, 280px);
    grid-template-columns: repeat(3, 1fr);
}


aside {
    height: 68px;
    display: flex;
    justify-content: center;
    align-items: center;
}

aside > a{
    text-decoration: none;
    color: black;
    
}

aside > img{
    font-size: 30px;
    font: larger;
    position: relative;
    bottom: 15px;
    left: 70px;
}

/*Ändringar, kväll 200908*/
footer {
    height: 340px;
}

.nummerlåda {
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    font: bolder;
    color:rgba(0, 0, 0, 0.7);
}
.nummerlåda > article{
    display: flex;
    width: 386px;
    height: 385px;
    justify-content: center;
    text-align: center;
}

.center{
    align-self: center;
    font-weight: 600;
    width: 257px;
}



.nr{
    color: rgba(128, 128, 128, 0.562);
    right: 100px;
    font-size: 40px;
} 


.boxar > p{
    color: white;
    font: bolder;
}
/*Ändringar kväll 200809*/
.hejhej{
    height: 760px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
}

.hejhej > h1, p{
    align-self: center;
    line-height: 20px;
}

.hejhej > h1{
    color: white;
    font-weight: bold;
    font-size: 50px;
    line-height: 20px;

}

/*Ändringar, kväll 200809*/

body {
    margin: 0;
}
.container {
    display: flex;
    height: 544px;
}
.blå {
    width: 50%;
    background-image: url(./images/family.png);
    background-size: 279px;
    background-repeat: no-repeat;
    background-position: bottom right;
}
.blå > h1 {
    position: relative;
    left: 120px;
    font-size: 2.5rem;
    max-width: 300px;
    margin-top: 80px;
    margin-bottom: 25px;
    font-style: normal;
    font-weight: 900;
    font-size: 45px;
    line-height: 100%;
    letter-spacing: -0.02em;
}
.blå > p {
    font-family: Fira Sans;
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    line-height: 24px;
    max-width: 268px;
}
.nodollar {
    max-width: 300px;
    position: relative;
    left: 120px;
    bottom: 10px;
    color: rgba(0, 0, 0, 0.6);
}
.dollar {
    color: #FFFFFF;
    position: relative;
    left: 210px;
    bottom: 48px;
}
.button {
    color: rgba(0, 0, 0, 0.8);
    background-color: #FFFFFF;
    text-decoration: none;
    border-radius: 50px;
    padding: 13px 40px;
    box-shadow: 1px 1px 5px grey;
    font-size: 10px;
    line-height: 12px;
    position: relative;
    left: 120px;
color: rgba(0, 0, 0, 0.8);
}
.gulorange {
    width: 50%;
    display: flex;
    flex-direction: column;
}
.gulorange > article > p {
    font-family: Frank Ruhl Libre;
    font-style: normal;
    color: #FFFFFF;
    font-weight: 900;
    font-size: 32px;
    line-height: 41px;
    letter-spacing: -0.02em;
    margin: 0;
}
.gulorange > article > h3 {
    color: rgba(0, 0, 0, 0.5);
    font-style: normal;
    font-weight: bold;
    font-size: 11px;
    line-height: 13px;
    letter-spacing: -0.02em;
    margin: 0;
}
.orange {
    height: 100%;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
.gul {
    height: 100%;
    text-align: center;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
.menu > ul {
    list-style-type: none;
    display: flex;
    justify-content: center;
    margin: 5px;
    font-style: normal;
    font-weight: 600;
    font-size: 12px;
    line-height: 100%;
    letter-spacing: -0.02em;
}
.menu > ul > li {
    padding: 20px 60px;
}
.fade {
    opacity: 0.4;
}
.grå > h2 {
    margin-top: 0;
}
