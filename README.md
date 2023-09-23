# project_1
coffee shop
html{
    scroll-behavior: smooth;
}
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;

}
body{
    background-color: rgba(0, 0, 0, 0.952);
}
/*this is for grid*/
[class*="col-"]{
    float: left;
    padding: 10px;
}
[class*="col-"]{
    width: 100%;
}

/*this is for small screen for 600px*/
@media only screen and (min-width: 600px) {
    /* For tablets: */
    .col-s-1 {width: 8.33%;}
    .col-s-2 {width: 16.66%;}
    .col-s-3 {width: 25%;}
    .col-s-4 {width: 33.33%;}
    .col-s-5 {width: 41.66%;}
    .col-s-6 {width: 50%;}
    .col-s-7 {width: 58.33%;}
    .col-s-8 {width: 66.66%;}
    .col-s-9 {width: 75%;}
    .col-s-10 {width: 83.33%;}
    .col-s-11 {width: 91.66%;}
    .col-s-12 {width: 100%;}
  }
  /*this is for medium screen for 768px*/
@media only screen and (min-width: 768px) {
    /* For desktop: */
    .col-m-1 {width: 8.33%;}
    .col-m-2 {width: 16.66%;}
    .col-m-3 {width: 25%;}
    .col-m-4 {width: 33.33%;}
    .col-m-5 {width: 41.66%;}
    .col-m-6 {width: 50%;}
    .col-m-7 {width: 58.33%;}
    .col-m-8 {width: 66.66%;}
    .col-m-9 {width: 75%;}
    .col-m-10 {width: 83.33%;}
    .col-m-11 {width: 91.66%;}
    .col-m-12 {width: 100%;}
  }
  /*this is for large screen for 992px*/
  
  @media only screen and (min-width: 992px) {
    /* For desktop: */
    .logo-div{
        text-align: left;
    }
    nav ul{
        display: inline-block;
        padding: 40px;
        margin-left: 40px;
        
    }
    nav ul li{
        display: inline-block;
        float: left;
        margin-left: 60px;
    }
    nav ul li a{
        display: inline-block;
    }
    .col-l-1 {width: 8.33%;}
    .col-l-2 {width: 16.66%;}
    .col-l-3 {width: 25%;}
    .col-l-4 {width: 33.33%;}
    .col-l-5 {width: 41.66%;}
    .col-l-6 {width: 50%;}
    .col-l-7 {width: 58.33%;}
    .col-l-8 {width: 66.66%;}
    .col-l-9 {width: 75%;}
    .col-l-10 {width: 83.33%;}
    .col-l-11 {width: 91.66%;}
    .col-l-12 {width: 100%;}
  }
/* header stats */
.container{
    max-width: 100%;
    margin: auto;
    
    /* font-family: 'Croissant One', cursive;
    font-family: 'Dancing Script', cursive;
    font-family: 'Pacifico', cursive;
    font-family: 'Poppins', sans-serif;
    font-family: 'Roboto', sans-serif; */
}
.row{
    width: 100%;
}
.row::after{
    clear: both;
    display: table;
    content: '';
}
header{
    background-image: linear-gradient(to right, rgba(248, 247, 247, 0.945) , rgba(201, 110, 110, 0.5));
    text-align: center;
    padding: 1px;
    margin-top: -10px;
}
.logo{
    height: 100px;
    width: 100px;
    margin-top: 5px;
    border-radius: 50%;
    transition: 0.4s;
    margin-left: 5px;
}
.logo:hover{
    box-shadow:  0px 1px 20px rgb(197, 131, 84);
    margin-left: 10px;
}
.logo-div {
    display: block;
}
nav ul li{
    display: block;
}
nav ul li a{
    display: block;
    color:white;
    font-size:20px;
    padding: 5px;
    text-decoration: none;
    text-transform: uppercase;
    font-family:'Poppins', sans-serif ;
    font-weight: bold;
    letter-spacing: 1px;
    transition: 0.5s; 
}
nav ul li a:hover{
    border-radius: 10px;
    background-color:0px 1px 20px rgb(165, 136, 116);
    box-shadow:0px 1px 20px rgb(90, 65, 48);
    letter-spacing: 3px;
    color: black;
}

/* header ends */

/*main start here*/
/*bannar section*/
#bannar-section{
    background-image: url(/images/istockphoto-1125725514-1024x1024.jpg);
    background-position:center;
    background-attachment: fixed;
    background-size: cover;
    background-repeat: no-repeat;
    height: 700px;
    width: 100%;
    transition: 0.6s;
    
}
#bannar-section:hover{
    box-shadow: 0px 1px 5px rgb(90, 49, 49);
}
.bannar-content{
    text-align: center;
    padding: 150px ;
}
.bannar-content h1{
    text-align: center;
    color: rgba(249, 252, 250, 0.856);
    background-image: linear-gradient(to right, rgba(71, 29, 29, 0.541), rgba(19, 1, 11, 0.521) );
    border-radius: 10px;
    font-family: 'Dancing Script', cursive;
    text-transform: capitalize;
    letter-spacing: 2px;
    font-size: 40px;
    margin-top: 50px;
    transition: 0.6s; 
}
.bannar-content h1:hover{
    box-shadow: 0px 1px 5px grey;
    letter-spacing: 3px;
}
.bannar-content p{
    margin: 40px;
    background-image: linear-gradient(to right, rgba(31, 14, 14, 0.212), rgba(80, 16, 53, 0.993) );
    border-radius: 10px;
    color: rgb(183, 183, 219);
    font-family: 'Croissant One', cursive;
    font-size: x-large; 
    transition: 0.6s;
}
.bannar-content p:hover{
    
    box-shadow: 0px 0.5px 4px rgba(255, 255, 255, 0.589);
}
.bannar-btn{
    padding: 10px 15px;
    font-size: large;
    border: none;
    border-radius: 10px;
    font-weight: bold;
    letter-spacing: -1px;
    color: rgb(131, 89, 35);
    background-color: rgba(0, 0, 0, 0.788);
    cursor: pointer;
    transition: 0.6s;
}
.bannar-btn:hover{
    box-shadow: 0px 1px 5px grey;
    font-size: 20px;
    letter-spacing: 1px;
}

/*about us section*/
.about-us{
    padding: 10px;
}
.about-content{
    background-color: rgba(209, 203, 195, 0.336);
    text-align: center;
    padding: 10px;
    font-family:'Croissant One', cursive; ;
    border-radius: 10px;
    transition: 0.3s;
}
.about-content:hover{
    box-shadow: 0px 1px 6px rgba(168, 124, 43, 0.63);
    margin-top: -3px;
}
.about-content h2{
    padding: 10px;
    color: rgb(216, 93, 5);
    font-size: 30px;
    transition: 0.6s;
}
.about-content h2:hover{
    color: rgb(243, 100, 5);
}
.about-content p{
    color: bisque;
    text-align: justify;
}
/*item section */
#coffee{
    padding: 10px 1px; 

    
}
.card-item img{
    height: auto;
    max-width: 100%;
    display: block;
}
.card{
    text-align: center;
    background-color: rgba(94, 59, 8, 0.445);
    margin: 5px;
    margin-top: -20px;
    padding: 1px;
    border-radius: 8px;
    height: 100%;
    transition: 0.4s;
    box-shadow: 0px 1px 5px rgba(255, 255, 255, 0.637);
}
.card:hover{
    /* transform: scale(1.1); */
   margin-top: -15px;
    box-shadow: 0px 1px 15px rgb(184, 84, 50);
}
.card-desc{
    padding: 2px;
    background-color: rgba(206, 190, 138, 0.514);
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
}
.card-h3{
    text-transform: uppercase;
    color: white;
    background-color: rgba(0, 0, 0, 0.795);
    border-radius: 5px;
    padding: 10px;
    letter-spacing: 2px;
    transition: 0.6s;
    font-family: 'Dancing Script', cursive;
}
.card-h3:hover{
    letter-spacing: 3px;
    background-color: rgba(10, 9, 9, 0.959);
    
}
.card-desc > p{
    color: rgba(1, 0, 12, 0.938);
    font-family: 'Poppins', sans-serif;
    font-size: 18px;  
}
/*contact section*/
#contact{
    padding: 2px;
    margin-top: -10px;
    border-radius: 10px;
    border: 2px solid rgb(73, 52, 14);
    transition: 0.6s;
    font-family: 'Poppins', sans-serif;
}
#contact:hover{
    box-shadow:0px 2px 5px rgb(100, 30, 30) ;
    
}
.map{
    width: 100%;
    height: 300px;
    border-radius: 5px;
    box-shadow: 0px 2px 5px grey;
    transition: 0.4s;
}
.map:hover{
    box-shadow:0px 2px 5px white ;
}
.contact-list{
    text-align: center;
    padding: 25px;
    margin:5px;
    background-color: black;
    margin-top: -1px;
    border-radius: 5px;
    transition: 0.4s;
}
.contact-list:hover{
    box-shadow: 0px 0px 8px rgb(56, 28, 8);
    margin-left: -2px;
}
h4{
    color: wheat;
    margin: 5px;
    font-size: 25px;
}
h5{
    color:aliceblue;
    padding: 5px;
    font-size: 15px;
}
.contact-list p, address{
    color: rgb(126, 121, 121);
    font-size: 13px;
}
/* main end here*/
/*footer start here*/
footer{
    background-color: rgb(77, 69, 60);
    height: 100%;
    padding: 1px;
    margin:2px;
    border-bottom-left-radius: 10px;
    border-bottom-right-radius: 10px;
    text-align: center;
}
footer span{
    color: rgb(0, 174, 255);
}
footer p{
    color: rgb(248, 241, 241);
    padding: 20px;  
}
.icon{
    color: rgb(255, 255, 255);
    padding: 10px;
    margin: 5px;
    border: 1px solid rgb(255, 246, 246);
    border-radius: 50%;
    box-shadow: 0px 1px 4px rgb(255, 246, 246);
    transition: 0.6s;
    
}
.icon:hover{
    box-shadow: 0px 1px 10px rgb(255, 246, 246);
    transform: scale(1.3);
    background-color: black;
}


/*footer end here*/
