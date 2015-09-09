# TCC
/* reset layout */

*{
max-width:1440px;
margin:0;
padding:0;
}

h1 , h2, h3, h4{
font-family:DidactGothic;
text-shadow:#DDD 1px 1px;
}

p, a, li, label {
font-family:Molengo;
font-size:20px;
line-height:30px;
}

html, body{
width:100%;
height:100%;
}

/* Cabeça do Site */

header{
height:180px;
}

.textura{
position:absolute;
z-index:-10000;
background:url(../Imagem/12vkH.png);
width:100%;
height:180px;
opacity:0.5;
}

.Logo {
position:relative;
top:35px;
left:490px;
width:450px;
}

 /* Conteúdo do site - Header */
 

.Icone {
position:absolute;
z-index:10000;
top:359px;
left:5px;
}

.Icone img {
width:30px;
}

.Search {
position:absolute;
left:190px;
bottom:73px;
}

.Login {
position:absolute;
left:745px;
bottom:70px;
width:380px;

}

.Login a {
text-decoration:none;
color:#000;
font-size:24px;
text-shadow:#DDD 1px 1px;
}

.L {
/* Link Login */
position:relative;
padding:0px 83px 0 50px;
}

.L a:hover {
color:#ee5500;
text-shadow:#CCC 1px 1px;
}

.C {
/* Link Cadastro */
position:relative;
left:1px;
padding:0px 35px 0 38px;
}

.C a:hover {
color:#33AAFF;
text-shadow:#CCC 1px 1px;
}

.Login li{
position:relative;
list-style:none;
float:left;
}
 
.Ln-E {
position:absolute;
z-index:10000;
top:288px;
left:140px;
width:480px;
border:1px solid;
}

.Ln-D {
position:absolute;
z-index:10000;
top:288px;
left:808px;
width:480px;
border:1px solid;
/*margin-left:138px;*/
}

.Menu {
position:absolute;
top:240px;
left:670px;
z-index:10000;
}

.Menu img {
width:90px;
}

/* Contéudo - Container */

.Container {
/* BluePrint */
  background-image: linear-gradient(0deg, transparent 0%, transparent 9px, rgba(105, 94, 255, 0.2) 9px, rgba(105, 94, 255, 0.2) 10px, transparent 10px, transparent 19px, rgba(105, 94, 255, 0.1) 19px, rgba(105, 94, 255, 0.1) 20px, transparent 20px, transparent 29px, rgba(105, 94, 255, 0.1) 29px, rgba(105, 94, 255, 0.1) 30px, transparent 30px, transparent 39px, rgba(105, 94, 255, 0.1) 39px, rgba(105, 94, 255, 0.1) 40px, transparent 40px, transparent 49px, rgba(105, 94, 255, 0.1) 49px, rgba(105, 94, 255, 0.1) 50px), linear-gradient(-90deg, transparent 0%, transparent 9px, rgba(105, 94, 255, 0.2) 9px, rgba(105, 94, 255, 0.2) 10px, transparent 10px, transparent 19px, rgba(105, 94, 255, 0.1) 19px, rgba(105, 94, 255, 0.1) 20px, transparent 20px, transparent 29px, rgba(105, 94, 255, 0.1) 29px, rgba(105, 94, 255, 0.1) 30px, transparent 30px, transparent 39px, rgba(105, 94, 255, 0.1) 39px, rgba(105, 94, 255, 0.1) 40px, transparent 40px, transparent 49px, rgba(105, 94, 255, 0.1) 49px, rgba(105, 94, 255, 0.1) 50px);
  background-size: 50px 50px;
  height:1900px;
  opacity:0.8;
  box-shadow:#ccc 0px 1px 2px 2px;
}

.Conteudo {
position:absolute;
top:412px;
left:140px;
margin-right:95px;
z-index:50000;
}

.Conteudo h1 {
margin-top:20px;
}

/*.Lr-D {
width:810px;
position:relative;
bottom:16px;
left:150px;
border:1px solid #eeee00;
}*/

.P1 img, .P2 img, .P3 img, .P4 img {
width:100%;
}

.P1, .P2, .P3,.P4 {
border-radius:3px;
box-shadow:#ccc 1px 1px 1px 1px;
}

.P1 {
position:absolute;
top:100px;
width:450px;
height:418px;
background:#33AAFF;
}

.P2 {
position:absolute;
top:100px;
left:452px;
width:699px;
height:208px;
background:#ee5500;
}

.P3{
position:absolute;
top:310px;
left:452px;
width:349px;
height:208px;
background:#33AAFF;
}

.P4 {
position:absolute;
top:310px;
left:802px;
width:349px;
height:208px;
background:#ee5500;
}

.titulo {
position:absolute;
width:150px;
top:810px;
left:503px;
}

.Text {
position:absolute;
padding:20px;
background: rgba(255,255,255,0.8);
top:900px;
width:1111px;
height:500px;
text-align:justify;
box-shadow:#ccc 1px 1px 1px 1px;
}

/* Rodapé */

footer{
height:150px;
}

.Logo2 {
position:absolute;
top:2130px;
left:628px;
width:90px;
z-index:10000;
}

/* Icones Rede Social */

.rede-social {
position:relative;
top:63px;
left:100px;
width:180px;
}

.rede-social a:hover {
opacity:0.5;
}

.rede-social img {
width:35px;
padding-left:5px;
}

/* Media Querys */

@media screen and (max-width: 960px) {

}



/* Fontes */


/* Títulos */

@font-face {
font-family:QuattrocentoSans;
font-style:normal;
font-weight:normal;
src:url(Font/QuattrocentoSans-Regular.ttf);
}

@font-face {
font-family:DidactGothic;
font-style:normal;
font-weight:normal;
src:url(Font/Didactgothic.ttf);
}

/* Paragrafos */

@font-face {
font-family:nobile;
font-style:normal;
font-weight:normal;
src:url(Font/nobile.ttf);
}

@font-face {
font-family:Molengo;
font-style:normal;
font-weight:normal;
src:url(Font/Molengo-Regular.ttf);
}
