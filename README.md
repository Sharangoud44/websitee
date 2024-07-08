<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
    <title>Document</title>


<style>

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    
    
}

button{
    cursor: pointer;
}



html,body{
    height: 100%;
    width: 100%;
    scroll-behavior: smooth;
}
.adv{
    width: auto;
    height: 50px;
    padding: 10px;
    
    background-color: rgba(26, 115, 232, 0.15)  ;
    
}
h5{
    font-family: Inter;
font-size: 16.88px;
font-weight: 500;
line-height: 28px;
text-align: center;

}

span{
    color: rgba(26, 115, 232, 1);
}
.nav-icons{
    
}
.nav ul{
    list-style: none;
    display: flex;
    margin-right: 90px;
    margin-top: 10px;
    
    
   
    
}
.nav ul li{
    padding: 5px;
    margin: 10px;
   
    
}
.nav{
  
    justify-content: flex-end;
    display: flex;
    
}
.icon{
    justify-content: left;
    position: absolute;
    left: 10%;
}
 .buttonblue{
    padding: 5px 20px;
    background-color: rgba(26, 115, 232, 1);
    color: white;
    margin-left: 10px;
    border-radius: 5px;
    border: none;
    margin-right: 20px;
}
.login{
    padding: 5px 20px;
    border-radius: 5px;
    border: none;
   
}
.logo{
    top: 15px;
    position: relative;
}
.links{
    display: flex;
    justify-content: center;
    z-index: 1;

}
.links ul li{
    list-style: none;
    margin: 10px 40px;
    font-size: 18px;
    cursor: pointer;
    z-index: 1;
}

.links ul li :hover{
    color: whitesmoke;
}




.links ul {
    display: flex;
    background-color: rgba(26, 115, 232, 0.11);
    padding: 10px;
    margin-top: 20px;
    border-radius: 40px;
    
}

.largepic{
   
    background-color: rgba(238, 245, 255, 1);
   height: 461px;
   margin-top: 15px ;
   margin-left: 100px;
   margin-right: 100px;
   margin-bottom: 5px;
   border-radius: 20px;
   display: flex;
   position: relative;
   padding: 50px;
   padding-right: 0px;
 
    
    

}
.largepicdata h1{
    font-family: Roboto;
    font-size: 60px;
    font-weight: 700;
    
    text-align: left;
    

}
.largepicdata h2{
    
    margin-top: 10px;
    font-family: Roboto;
    font-size: 40px;
    font-weight: 400;
    
    
    text-align: left;

}
.largepicdata h2 span{
    font-weight: 600;
    line-height: 50px;
    font-size: 40px;
    font-family: Roboto;

}
.largepicdata .buttonblue{
    padding: 10px 20px;
    background-color: rgba(26, 115, 232, 1);
    color: white;
    border-radius: 5px;
    border: none;
    margin-top: 30px;
    
    right: 10px;
    
}


.mulpic img{
    position: relative;
    bottom: 60%;
    z-index: 0;
    
    left: 15%;
    

}

.first-page{
    
    height: 100%;
    width: 100%;

    
}

.secound-page{
    
    height: 100%;
    width: 100%;
   
    
   
  
    
    
    
   
}
.contentsecound{
    background-color:  rgba(238, 245, 255, 1);
    height: 100%;
    width: 100%;
  position: relative;
    
    
   

   
   
}
#addfriend{
 position: absolute;
 left: 23%;
 top: 40%;
}
.secound-page .contentsecound img{
    position: relative;
    left: 80px;
    bottom: 10%;
}
#notepad{
    position: absolute;
    left: 48%;
    top: 40%;
}
#wallet{
    position: absolute;
    left: 73%;
    top: 40%;
}
.contentsecound h2{
    font-family: roboto;
}
.contentsecound h2 span{
    color:rgba(26, 115, 232, 1);
}

.contentsecound .addfriendsub{
    font-family: roboto;
    text-align: center;
    position: absolute;
    left: 19%;
    top: 55%;
    font-size: 15px;
    font-weight: 400;
}
.contentsecound .notepadsub{
    font-family: roboto;
    text-align: center;
    position: absolute;
    left: 44%;
    top: 55%;
    font-size: 15px;
    font-weight: 400;
}
.contentsecound .walletsub{
    font-family: roboto;
    text-align: center;
    position: absolute;
    left: 71%;
    top: 54%;
    font-size: 15px;
    font-weight: 400;
}
.contentsecound h2{
    font-size: 28px;
    font-weight: 700;
   position: relative;
   left: 45%;
   top: 5%;
   margin-top: 30px;
  
}
.contentsecound .buttonblue{
    position:absolute;
    top: 90%;
    left: 47%;
    
    padding: 10px 22px;
    background-color: rgba(26, 115, 232, 1);
    color: white;
   
    border-radius: 5px;
    border: none;
    font-weight: 500;
   
}
.third-page{
    height: 100%;
    width: 100%;
    
}
.third-contentmix{
    display: flex;
    justify-content: center;
    align-items: center;
    
}

table{
   
    
    border-collapse: collapse;
   
    background-color:rgba(235, 243, 255, 0.35) ;

    box-shadow: 0px 4px 29.3px 0px rgba(60, 60, 60, 0.15);

}


.tablehead{
    background-color: rgba(26, 115, 232, 0.35);
    
    color: rgba(19, 80, 160, 1);
    
    font-family: Source Sans Pro;
   
   
   
    
}
.onerow{
    padding:10px;
    font-family: Source Sans Pro;
    padding-right: 15px;
    padding-left: 15px;
    font-weight: 500;
   border-top-left-radius: 20px;
   
    
}
.threerow{
    border-top-right-radius: 20px;
}

.two_three_column{
    padding: 20px 40px;
    border-style: solid;
    border-width: thin;
    border-bottom: none;
    border-top: none;
    font-family: Source Sans Pro;
    font-weight: 300;
}
td{
    padding-right: 15px;
    padding-left: 15px;
    font-family: Source Sans Pro;
    font-weight: 300;
    font-size: 16px;
   
}

.third-content-two{
    margin-top: 10px;
}
.third-content-two svg{
    height: 14px;
    padding-right: 5px;
}
.oneline{
    background-color: rgba(26, 115, 232, 1);
    font-family: Source Sans Pro;
    padding:4px;
    border: none;
    border-top-left-radius: 8px;
    border-top-right-radius: 8px;
    color:white;
}
.third-content-one{
   background-color: background: rgba(255, 255, 255, 1);
   box-shadow: 0px 1px 24.4px 1px rgba(0, 0, 0, 0.16);
   margin-right:20px;
   margin-top:2px;
   cursor:pointer;
   
   

}
.third-content-one li{
    list-style: none;
    font-family: Source Sans Pro;
    font-weight: 300;
    padding: 8px 8px 10px 10px;
    font-size: 15px;
   
    
    
   
    
}
.third-content-one svg{
    padding-left: 10px;
    height: 10px;
    padding-right: 20px;
   
}
.allline{
    border-style: solid;
    border-width: thin;
   
    border-bottom: none;
    border-left: none;
    border-right: none;
    margin-top: 15px;
    padding-top: 5px;
   
    
}
.twoline{
    border: none;
}


.third-page{
    padding: 30px 50px;
    position: relative;
}
.third-page h2{
    font-family: Roboto;
font-size: 27.66px;
font-weight: 600;
line-height: 43px;
text-align: center;
justify-content: center;

}
.third-page h3{
    font-style:Source Sans Pro;
    font-weight: 400;
    font-size: 18px;
    text-align: end;
    justify-content: end;
    margin-bottom: 10px;
}
.third-page h3 svg{
    margin-left: 5px;
    padding: 1px;
   
    

}

.third-page button{
    border: 1px solid rgba(182, 182, 182, 1);
    width: 118.66px;
height: 40px;
top: 2632px;
left: 1407px;
padding: 13px 10px 13px 15px;
gap: 0px;
border-radius: 8px 0px 0px 0px;
border: 1px 0px 0px 0px;
opacity: 0px;
margin-left: 90%;


}

.third-page .buttonblue{
    margin-left: 50%;
    margin-bottom: 10%;
}
.fourth-content{
  
    display: flex;
}
.fourth-content button{
    display: block;
}
.fourth-page{
    height: 100%;
    width: 100%;
   
}

.fourth-page h1{
    justify-content: center;
    margin-top: 40px;
    font-size: 27px;
    
    display: flex;

    font-family: Inter;

font-weight: 600;
line-height: 36px;


}





.eligibility_btn{
    color: rgba(26, 115, 232, 1);
    border: 2px solid rgba(226, 232, 240, 1);
    background-color:rgba(255, 255, 255, 1);
    width: 159px;
height: 58px;



border-radius: 7px 0px 0px 0px;
border: 2px 0px 0px 0px;
opacity: 0px;
font-weight: 600;
font-size: 12px;

}
.fourth-content h4{
    font-family: Inter;
    font-weight: 400;
    padding: 10px;

}
 .h_t_u_btn{
    border: 2px solid rgba(115, 115, 115, 1);
   background-color: white;

   font-family: Inter;
font-size: 12px;
font-weight: 500;
line-height: 28px;
text-align: center;


width: 159px;
height: 58px;

}
.t_c_btn{
    border: 2px solid rgba(115, 115, 115, 1);
   background-color: white;
   font-family: Inter;
font-size: 12px;
font-weight: 500;
line-height: 28px;
text-align: center;


width: 159px;
height: 58px;
}
.fourth-page{
    padding: 10px 25px;
}

.info {
    padding: 50px;
}
.info h4{
    font-size: 15px;
    font-weight: 400;
    margin-top: 30px;
}
.info .firstline{
   color: rgba(26, 115, 232, 1); 
   font-weight: 600;
   margin: 0;
}
.Buttons{
    margin-left: 90px;
    margin-top: 30px;
}
.Buttons button{
    margin: 15px;
}
.fourth-page svg{
    margin-left: 90px;
}
.fifth-page{
    height: 100%;
    width: 100%;
    background-color: black;
    color: whitesmoke;
}
.secound_body{
    display: flex;
    margin-top: 50px;
}
.fp_logo{
    height: 50px;
}
.first_header .bluebutton{

    color:rgba(255, 255, 255, 1);
    border: 2px solid rgba(226, 232, 240, 1);
    background-color:rgba(26, 115, 232, 1);
    width: 200px;
height: 40px;




border-radius: 7px 0px 0px 0px;
border: 2px 0px 0px 0px;
opacity: 0px;
font-weight: 400;
font-size: 12px;
position: absolute;
right: 20px;





}

.first_header h3{
    
    justify-content: center;
    font-size: 14px;
    font-weight: 400;
    position: absolute;
    right: 40px;
}
.fifth-page{
    padding:5% 15%;
}
.programs{
    padding: 15px 25px;
}
.programs ul li{
    list-style: none;
    margin: 9px 0px;
    font-size: 14px;
    font-weight: 400;
}

.contactus p{
   
    margin: 9px 0px;
    font-size: 14px;
    font-weight: 400;
    line-height: 1.5;
}
.contactus{
    margin-top: 10px;
    margin-left: 20px;
    padding: 10px;
}
.contactus svg{
    height: 25px;
    margin-top: 10px;
}
.accredian ul li{
    list-style: none;
    margin: 9px 0px;
    font-size: 14px;
    font-weight: 400;
}
.accredian{
    margin-left: 50px;
    padding: 10px;
}
.secound_body h1{
    font-family: Roboto;
    font-weight: 500;
    font-size: 16px;
}
.first_header{
    position: relative;
}
.fifth-page h5{
    font-size: 12px;
    font-weight: 400;
    font-family: Roboto;
    position: relative;
    top: 20%;
}
.fifth-page .callicon{
    position: absolute;
    left: 90%;
}
.moneypic1{
    position: absolute;
    transform: rotate(180deg);
    top: 0%;
    right: 1%;
   
    

}
.moneypic2{
    position: absolute;
    transform: rotate(180deg);
    bottom: 1%;
    right: 1%;
}
.moneypic3{
    position: absolute;
    position: absolute;
    transform: rotate(280deg);
    bottom: 1%;
    left: 49%;
}
.moneypic4{
    position: absolute;
    position: absolute;
    transform: rotate(180deg);
    top: 10%;
    left: 45%;
}
.moneypic5{
    position: absolute;
    top:-15px;
    left: 10px;
}
.moneypic6{
    position: absolute;
    bottom: 0%;
    left: 20%;
    transform: rotate(190deg);
}

</style>







</head>

<body>
    
    <div class="first-page">
        <header>



            <section class="adv">
                <h5>Navigate your ideal career path with tailored expert advice <span> Contact Expert</span></h5>
            </section>

            <div class="nav-icons">

                <div class="icon">
                    <img src="logo.png" alt="logo" height="40px" class="logo">
                    <Button class="buttonblue">Courses</Button>
                </div>

                <div class="nav">



                    <ul>
                        <li>Refer & Earn</li>
                        <li>Resources</li>
                        <li>About US</li>
                        <Button class="login">Login</Button>
                        <Button class="buttonblue">Try for free</Button>
                    </ul>





                </div>

            </div>


        </header>
        <section class="links">
            <ul>

                <li><a href="#secound-page">Refer</a></li>
                <li><a href="#third-page">Benefits</a></li>
                <li><a href="#fourth-page">FAQs</a></li>
                <li><a href="#fifth-page">Support</a></li>
            </ul>

        </section>
        <section class="largepic">
            <img src="money.png" alt="" class="moneypic1" height="120px">
            <img src="money.png" alt="" class="moneypic2" height="130px">
            <img src="money.png" alt="" class="moneypic3" height="110px">
            <img src="money.png" alt="" class="moneypic4" height="110px">
            <img src="money.png" alt="" class="moneypic5" height="80px">
            <img src="money.png" alt="" class="moneypic6" height="80px">
            
            <div class="largepicdata">

                <h1>Let's Learn</br>
                    & Earn</h1><br>
                <h2>Get a chance to win</br>
                    up-to <span>Rs. 15,000</span></h2>
                <Button class="buttonblue">Refer Now</Button>

            </div>




            <section class="mulpic">
                <img src="mobiledisplay.png" alt="logo" srcset="" height="730px">
            </section>












        </section>
    </div>
    <section class="secound-page" id="secound-page">

        <section class="contentsecound">
            <h2>How Do I <span>Refer?</span></h2>
            <img src="secound.png" alt="" height="600px">


            <svg width="88" height="67" viewBox="0 0 88 67" fill="none" xmlns="http://www.w3.org/2000/svg"
                id="addfriend">
                <path
                    d="M40.1156 39.9094H19.2844C8.62812 39.9094 0 48.5375 0 59.1937C0 63.4906 3.47188 66.9625 7.76875 66.9625H51.6312C55.9281 66.9625 59.4 63.4906 59.4 59.1937C59.4 48.5375 50.7719 39.9094 40.1156 39.9094Z"
                    fill="#1A73E8" />
                <path
                    d="M29.7 34.4094C39.2019 34.4094 46.9047 26.7066 46.9047 17.2047C46.9047 7.7028 39.2019 0 29.7 0C20.1981 0 12.4953 7.7028 12.4953 17.2047C12.4953 26.7066 20.1981 34.4094 29.7 34.4094Z"
                    fill="#1A73E8" />
                <path
                    d="M82.5687 19.5766H75.5219V12.5297C75.5219 9.52189 73.0984 7.09845 70.0906 7.09845C67.0828 7.09845 64.6594 9.52189 64.6594 12.5297V19.5766H57.6125C54.6219 19.5766 52.1812 22 52.1812 25.0078C52.1812 27.9984 54.6047 30.4391 57.6125 30.4391H64.6594V37.4859C64.6594 40.4766 67.0828 42.9172 70.0906 42.9172C73.0812 42.9172 75.5219 40.4938 75.5219 37.4859V30.4391H82.5687C85.5766 30.4391 88 28.0156 88 25.0078C88 22.0172 85.5766 19.5766 82.5687 19.5766Z"
                    fill="#1A73E8" />
            </svg>

            <h3 class="addfriendsub">Submit referrals easily via <br>
                our website's referral<br>
                section.</h3>



            <svg width="66" height="68" viewBox="0 0 66 68" fill="none" xmlns="http://www.w3.org/2000/svg" id="notepad">
                <path
                    d="M39.4987 12.5486H18.8049C16.839 12.5486 15.2437 10.9533 15.2437 8.98737V3.56126C15.2437 1.59535 16.839 0 18.8049 0H39.4987C41.4647 0 43.06 1.59535 43.06 3.56126V8.98737C43.06 10.9557 41.4647 12.5486 39.4987 12.5486Z"
                    fill="#1A73E8" />
                <path
                    d="M63.4289 38.4761C61.2151 36.2623 57.6057 36.2623 55.392 38.4761L52.7644 41.1181L60.8061 49.1574L63.4289 46.5346C65.6667 44.2992 65.6667 40.7139 63.4289 38.4761Z"
                    fill="#1A73E8" />
                <path
                    d="M50.2186 43.6736L36.1901 57.678C35.9013 57.9908 35.7088 58.3758 35.6366 58.7849L34.5779 65.0171C34.3373 66.3886 35.5404 67.5677 36.912 67.3511L43.1442 66.2924C43.5532 66.2202 43.9382 66.0277 44.227 65.739L58.2555 51.7105L50.2186 43.6736Z"
                    fill="#1A73E8" />
                <path
                    d="M49.6651 6.28015H46.6693V8.98719C46.6693 12.9407 43.4522 16.1578 39.4987 16.1578H18.8049C14.849 16.1578 11.6342 12.9407 11.6342 8.98719V6.28015H8.59033C3.85001 6.28015 0 10.1302 0 14.8705V58.7847C0 63.525 3.85001 67.375 8.59033 67.375H31.3463C30.9806 66.4342 30.8434 65.4139 31.0215 64.3961L32.0778 58.1807C32.2655 57.0786 32.7708 56.0608 33.5312 55.2306L48.847 39.9365L52.8294 35.9324C54.3092 34.4502 56.2077 33.5719 58.2507 33.3193V14.8945C58.2555 10.1061 54.4295 6.28015 49.6651 6.28015ZM25.4053 41.9722H14.9645C13.7686 41.9722 12.7989 41.0024 12.7989 39.8065C12.7989 38.6106 13.7686 37.6409 14.9645 37.6409H25.4053C26.6012 37.6409 27.5709 38.6106 27.5709 39.8065C27.5709 41.0024 26.6012 41.9722 25.4053 41.9722ZM38.1873 29.681H14.9669C13.771 29.681 12.8013 28.7113 12.8013 27.5154C12.8013 26.3195 13.771 25.3497 14.9669 25.3497H38.1873C39.3832 25.3497 40.3529 26.3195 40.3529 27.5154C40.3529 28.7113 39.3832 29.681 38.1873 29.681Z"
                    fill="#1A73E8" />
            </svg>

            <h3 class="notepadsub">Earn rewards once your<br>
                referral joins on Accredian<br>
                program.</h3>

            <svg width="65" height="68" viewBox="0 0 65 68" fill="none" xmlns="http://www.w3.org/2000/svg" id="wallet">
                <path
                    d="M24.6552 44.1595V38.8026C24.6552 36.5724 22.8397 34.7569 20.6095 34.7569H4.04569C1.81552 34.7569 0 36.5724 0 38.8026V44.1595C0 46.3897 1.81552 48.2052 4.04569 48.2052H20.6095C22.8397 48.2052 24.6552 46.3897 24.6552 44.1595ZM15.6897 44.8431C13.8405 44.8431 12.3276 43.3302 12.3276 41.481C12.3276 39.6319 13.8405 38.119 15.6897 38.119C17.5388 38.119 19.0517 39.6319 19.0517 41.481C19.0517 43.3302 17.5388 44.8431 15.6897 44.8431Z"
                    fill="#1A73E8" />
                <path
                    d="M6.72418 20.8378V32.5154H22.1112C24.7449 32.5154 26.8966 34.9361 26.8966 37.9059V45.0447C26.8966 48.0145 24.7561 50.4352 22.1112 50.4352H6.72418V62.1128C6.72418 64.9481 9.0216 67.2455 11.8569 67.2455H59.8673C62.7026 67.2455 65 64.9481 65 62.1128V20.8378C65 18.0024 62.7026 15.705 59.8673 15.705H11.8569C9.0216 15.705 6.72418 18.0024 6.72418 20.8378Z"
                    fill="#1A73E8" />
                <path
                    d="M32.2198 11.5808L31.2672 8.38684C30.5836 8.6446 30.1465 9.04805 29.9784 9.37305C29.9112 9.49632 29.844 9.68684 29.8888 9.85494L30.2586 11.1101C30.3819 11.536 31.256 11.8162 32.2198 11.592V11.5808Z"
                    fill="#1A73E8" />
                <path d="M35.0216 13.1051L35.1336 13.4637H36.9267C36.6914 13.1051 35.8957 12.9034 35.0216 13.1051Z"
                    fill="#1A73E8" />
                <path
                    d="M39.4707 1.48351C36.5793 -0.0854523 33.2397 -0.421659 30.0793 0.530927C26.9302 1.48351 24.3302 3.60162 22.7612 6.493C21.5957 8.65593 21.1138 11.0654 21.3379 13.4637H29.631C28.9026 13.0939 28.3423 12.5223 28.1069 11.749L27.7371 10.4939C27.5241 9.79903 27.6138 9.01455 27.9948 8.30851C28.4991 7.36713 29.4517 6.63869 30.6172 6.23524L29.9672 4.07231L32.119 3.43351L32.7578 5.57403L35.9741 4.59903L36.6129 6.75075L33.3966 7.72575L34.3716 10.9533C36.5457 10.393 38.6078 11.2223 39.1233 12.9258L39.2802 13.4525H45.881C46.0267 11.8947 45.881 10.3033 45.4216 8.79041C44.469 5.64127 42.3509 3.04127 39.4595 1.47231L39.4707 1.48351Z"
                    fill="#1A73E8" />
                <path
                    d="M61.7837 13.4638C62.1199 13.4638 62.4337 13.5087 62.7587 13.5647V11.3121C62.7587 8.90264 61.0552 6.95264 58.9483 6.95264H46.8337C47.1139 7.55781 47.3716 8.1854 47.5733 8.8354C48.0328 10.3483 48.2233 11.9061 48.1673 13.4638H61.7949H61.7837Z"
                    fill="#1A73E8" />
                <path
                    d="M20.4078 6.94108H12.4733C10.3776 6.94108 8.96558 8.54366 8.96558 10.9531V13.5531C9.27937 13.4971 9.60437 13.4523 9.94058 13.4523H19.0742C18.9957 11.2221 19.444 9.00315 20.4078 6.92987V6.94108Z"
                    fill="#1A73E8" />
            </svg>

            <h3 class="walletsub">Both parties recieve<br>
                a bonus 30 days after <br>
                program enrollment.</h3>

            <Button class="buttonblue">Refer Now</Button>

        </section>


    </section>

    <section class="third-page" id="third-page">
        <h2>What Are The <span>Referral Benefits</span></h2>
        <h3> Enrolled<svg width="35" height="17" viewBox="0 0 35 17" fill="none" xmlns="http://www.w3.org/2000/svg">
                <circle cx="24.9515" cy="8.50016" r="5.57527" fill="#1A73E8" />
                <rect x="0.75" y="0.75" width="32.6828" height="15.5" rx="7.75" stroke="#3C4852" stroke-width="1.5" />
            </svg></h3>

        <div class="third-contentmix">
            <div class="third-content-one">
                <ul>
                    <li class="oneline">ALL PROGRAMS <svg viewBox="0 0 10 16" fill="none"
                            xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                d="M1.64601 1.64599C1.69245 1.59943 1.74763 1.56249 1.80837 1.53728C1.86912 1.51207 1.93424 1.4991 2.00001 1.4991C2.06578 1.4991 2.1309 1.51207 2.19164 1.53728C2.25239 1.56249 2.30756 1.59943 2.35401 1.64599L8.35401 7.64599C8.40057 7.69244 8.43751 7.74761 8.46272 7.80836C8.48793 7.86911 8.5009 7.93423 8.5009 7.99999C8.5009 8.06576 8.48793 8.13088 8.46272 8.19163C8.43751 8.25237 8.40057 8.30755 8.35401 8.35399L2.35401 14.354C2.26012 14.4479 2.13278 14.5006 2.00001 14.5006C1.86723 14.5006 1.7399 14.4479 1.64601 14.354C1.55212 14.2601 1.49938 14.1328 1.49938 14C1.49938 13.8672 1.55212 13.7399 1.64601 13.646L7.29301 7.99999L1.64601 2.35399C1.59945 2.30755 1.5625 2.25237 1.5373 2.19163C1.51209 2.13088 1.49911 2.06576 1.49911 1.99999C1.49911 1.93423 1.51209 1.86911 1.5373 1.80836C1.5625 1.74761 1.59945 1.69244 1.64601 1.64599Z"
                                fill="white" stroke="white" stroke-width="1.5" />
                        </svg>
                    </li>

                    <li class="twoline">PRODUCT MANGEMENT <svg viewBox="0 0 7 12" fill="none"
                            xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                d="M1.08702 1.53234C1.11968 1.4996 1.15847 1.47363 1.20118 1.4559C1.24389 1.43818 1.28968 1.42906 1.33592 1.42906C1.38217 1.42906 1.42796 1.43818 1.47067 1.4559C1.51338 1.47363 1.55217 1.4996 1.58483 1.53234L5.80358 5.75109C5.83632 5.78375 5.8623 5.82255 5.88002 5.86526C5.89774 5.90797 5.90687 5.95376 5.90687 6C5.90687 6.04624 5.89774 6.09203 5.88002 6.13474C5.8623 6.17745 5.83632 6.21625 5.80358 6.24891L1.58483 10.4677C1.51882 10.5337 1.42928 10.5708 1.33592 10.5708C1.24257 10.5708 1.15303 10.5337 1.08702 10.4677C1.021 10.4016 0.983918 10.3121 0.983918 10.2187C0.983918 10.1254 1.021 10.0359 1.08702 9.96984L5.05757 6L1.08702 2.03016C1.05428 1.9975 1.0283 1.9587 1.01058 1.91599C0.992857 1.87328 0.983734 1.82749 0.983734 1.78125C0.983734 1.73501 0.992857 1.68922 1.01058 1.64651C1.0283 1.6038 1.05428 1.565 1.08702 1.53234Z"
                                fill="#3C4852" stroke="#3C4852" stroke-width="1.05469" />
                        </svg>
                    </li>
                    <li class="allline">STRATEGY & LEADERSHIP <svg viewBox="0 0 7 12" fill="none"
                            xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                d="M1.08702 1.53234C1.11968 1.4996 1.15847 1.47363 1.20118 1.4559C1.24389 1.43818 1.28968 1.42906 1.33592 1.42906C1.38217 1.42906 1.42796 1.43818 1.47067 1.4559C1.51338 1.47363 1.55217 1.4996 1.58483 1.53234L5.80358 5.75109C5.83632 5.78375 5.8623 5.82255 5.88002 5.86526C5.89774 5.90797 5.90687 5.95376 5.90687 6C5.90687 6.04624 5.89774 6.09203 5.88002 6.13474C5.8623 6.17745 5.83632 6.21625 5.80358 6.24891L1.58483 10.4677C1.51882 10.5337 1.42928 10.5708 1.33592 10.5708C1.24257 10.5708 1.15303 10.5337 1.08702 10.4677C1.021 10.4016 0.983918 10.3121 0.983918 10.2187C0.983918 10.1254 1.021 10.0359 1.08702 9.96984L5.05757 6L1.08702 2.03016C1.05428 1.9975 1.0283 1.9587 1.01058 1.91599C0.992857 1.87328 0.983734 1.82749 0.983734 1.78125C0.983734 1.73501 0.992857 1.68922 1.01058 1.64651C1.0283 1.6038 1.05428 1.565 1.08702 1.53234Z"
                                fill="#3C4852" stroke="#3C4852" stroke-width="1.05469" />
                        </svg>
                    </li>
                    <li class="allline">BUSSINESS MANAGEMENT <svg viewBox="0 0 7 12" fill="none"
                            xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                d="M1.08702 1.53234C1.11968 1.4996 1.15847 1.47363 1.20118 1.4559C1.24389 1.43818 1.28968 1.42906 1.33592 1.42906C1.38217 1.42906 1.42796 1.43818 1.47067 1.4559C1.51338 1.47363 1.55217 1.4996 1.58483 1.53234L5.80358 5.75109C5.83632 5.78375 5.8623 5.82255 5.88002 5.86526C5.89774 5.90797 5.90687 5.95376 5.90687 6C5.90687 6.04624 5.89774 6.09203 5.88002 6.13474C5.8623 6.17745 5.83632 6.21625 5.80358 6.24891L1.58483 10.4677C1.51882 10.5337 1.42928 10.5708 1.33592 10.5708C1.24257 10.5708 1.15303 10.5337 1.08702 10.4677C1.021 10.4016 0.983918 10.3121 0.983918 10.2187C0.983918 10.1254 1.021 10.0359 1.08702 9.96984L5.05757 6L1.08702 2.03016C1.05428 1.9975 1.0283 1.9587 1.01058 1.91599C0.992857 1.87328 0.983734 1.82749 0.983734 1.78125C0.983734 1.73501 0.992857 1.68922 1.01058 1.64651C1.0283 1.6038 1.05428 1.565 1.08702 1.53234Z"
                                fill="#3C4852" stroke="#3C4852" stroke-width="1.05469" />
                        </svg>
                    </li>
                    <li class="allline">FINTECH <svg viewBox="0 0 7 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                d="M1.08702 1.53234C1.11968 1.4996 1.15847 1.47363 1.20118 1.4559C1.24389 1.43818 1.28968 1.42906 1.33592 1.42906C1.38217 1.42906 1.42796 1.43818 1.47067 1.4559C1.51338 1.47363 1.55217 1.4996 1.58483 1.53234L5.80358 5.75109C5.83632 5.78375 5.8623 5.82255 5.88002 5.86526C5.89774 5.90797 5.90687 5.95376 5.90687 6C5.90687 6.04624 5.89774 6.09203 5.88002 6.13474C5.8623 6.17745 5.83632 6.21625 5.80358 6.24891L1.58483 10.4677C1.51882 10.5337 1.42928 10.5708 1.33592 10.5708C1.24257 10.5708 1.15303 10.5337 1.08702 10.4677C1.021 10.4016 0.983918 10.3121 0.983918 10.2187C0.983918 10.1254 1.021 10.0359 1.08702 9.96984L5.05757 6L1.08702 2.03016C1.05428 1.9975 1.0283 1.9587 1.01058 1.91599C0.992857 1.87328 0.983734 1.82749 0.983734 1.78125C0.983734 1.73501 0.992857 1.68922 1.01058 1.64651C1.0283 1.6038 1.05428 1.565 1.08702 1.53234Z"
                                fill="#3C4852" stroke="#3C4852" stroke-width="1.05469" />
                        </svg>
                    </li>
                    <li class="allline">SENIOUR MANAGEMENT <svg viewBox="0 0 7 12" fill="none"
                            xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                d="M1.08702 1.53234C1.11968 1.4996 1.15847 1.47363 1.20118 1.4559C1.24389 1.43818 1.28968 1.42906 1.33592 1.42906C1.38217 1.42906 1.42796 1.43818 1.47067 1.4559C1.51338 1.47363 1.55217 1.4996 1.58483 1.53234L5.80358 5.75109C5.83632 5.78375 5.8623 5.82255 5.88002 5.86526C5.89774 5.90797 5.90687 5.95376 5.90687 6C5.90687 6.04624 5.89774 6.09203 5.88002 6.13474C5.8623 6.17745 5.83632 6.21625 5.80358 6.24891L1.58483 10.4677C1.51882 10.5337 1.42928 10.5708 1.33592 10.5708C1.24257 10.5708 1.15303 10.5337 1.08702 10.4677C1.021 10.4016 0.983918 10.3121 0.983918 10.2187C0.983918 10.1254 1.021 10.0359 1.08702 9.96984L5.05757 6L1.08702 2.03016C1.05428 1.9975 1.0283 1.9587 1.01058 1.91599C0.992857 1.87328 0.983734 1.82749 0.983734 1.78125C0.983734 1.73501 0.992857 1.68922 1.01058 1.64651C1.0283 1.6038 1.05428 1.565 1.08702 1.53234Z"
                                fill="#3C4852" stroke="#3C4852" stroke-width="1.05469" />
                        </svg>
                    </li>
                    <li class="allline">DATA SCIENCE <svg viewBox="0 0 7 12" fill="none"
                            xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                d="M1.08702 1.53234C1.11968 1.4996 1.15847 1.47363 1.20118 1.4559C1.24389 1.43818 1.28968 1.42906 1.33592 1.42906C1.38217 1.42906 1.42796 1.43818 1.47067 1.4559C1.51338 1.47363 1.55217 1.4996 1.58483 1.53234L5.80358 5.75109C5.83632 5.78375 5.8623 5.82255 5.88002 5.86526C5.89774 5.90797 5.90687 5.95376 5.90687 6C5.90687 6.04624 5.89774 6.09203 5.88002 6.13474C5.8623 6.17745 5.83632 6.21625 5.80358 6.24891L1.58483 10.4677C1.51882 10.5337 1.42928 10.5708 1.33592 10.5708C1.24257 10.5708 1.15303 10.5337 1.08702 10.4677C1.021 10.4016 0.983918 10.3121 0.983918 10.2187C0.983918 10.1254 1.021 10.0359 1.08702 9.96984L5.05757 6L1.08702 2.03016C1.05428 1.9975 1.0283 1.9587 1.01058 1.91599C0.992857 1.87328 0.983734 1.82749 0.983734 1.78125C0.983734 1.73501 0.992857 1.68922 1.01058 1.64651C1.0283 1.6038 1.05428 1.565 1.08702 1.53234Z"
                                fill="#3C4852" stroke="#3C4852" stroke-width="1.05469" />
                        </svg>
                    </li>
                    <li class="allline">DIGITAL TRANSFORMATION <svg viewBox="0 0 7 12" fill="none"
                            xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                d="M1.08702 1.53234C1.11968 1.4996 1.15847 1.47363 1.20118 1.4559C1.24389 1.43818 1.28968 1.42906 1.33592 1.42906C1.38217 1.42906 1.42796 1.43818 1.47067 1.4559C1.51338 1.47363 1.55217 1.4996 1.58483 1.53234L5.80358 5.75109C5.83632 5.78375 5.8623 5.82255 5.88002 5.86526C5.89774 5.90797 5.90687 5.95376 5.90687 6C5.90687 6.04624 5.89774 6.09203 5.88002 6.13474C5.8623 6.17745 5.83632 6.21625 5.80358 6.24891L1.58483 10.4677C1.51882 10.5337 1.42928 10.5708 1.33592 10.5708C1.24257 10.5708 1.15303 10.5337 1.08702 10.4677C1.021 10.4016 0.983918 10.3121 0.983918 10.2187C0.983918 10.1254 1.021 10.0359 1.08702 9.96984L5.05757 6L1.08702 2.03016C1.05428 1.9975 1.0283 1.9587 1.01058 1.91599C0.992857 1.87328 0.983734 1.82749 0.983734 1.78125C0.983734 1.73501 0.992857 1.68922 1.01058 1.64651C1.0283 1.6038 1.05428 1.565 1.08702 1.53234Z"
                                fill="#3C4852" stroke="#3C4852" stroke-width="1.05469" />
                        </svg>
                    </li>
                    <li class="allline">BUSSINESS ANALYTICS <svg viewBox="0 0 7 12" fill="none"
                            xmlns="http://www.w3.org/2000/svg">
                            <path fill-rule="evenodd" clip-rule="evenodd"
                                d="M1.08702 1.53234C1.11968 1.4996 1.15847 1.47363 1.20118 1.4559C1.24389 1.43818 1.28968 1.42906 1.33592 1.42906C1.38217 1.42906 1.42796 1.43818 1.47067 1.4559C1.51338 1.47363 1.55217 1.4996 1.58483 1.53234L5.80358 5.75109C5.83632 5.78375 5.8623 5.82255 5.88002 5.86526C5.89774 5.90797 5.90687 5.95376 5.90687 6C5.90687 6.04624 5.89774 6.09203 5.88002 6.13474C5.8623 6.17745 5.83632 6.21625 5.80358 6.24891L1.58483 10.4677C1.51882 10.5337 1.42928 10.5708 1.33592 10.5708C1.24257 10.5708 1.15303 10.5337 1.08702 10.4677C1.021 10.4016 0.983918 10.3121 0.983918 10.2187C0.983918 10.1254 1.021 10.0359 1.08702 9.96984L5.05757 6L1.08702 2.03016C1.05428 1.9975 1.0283 1.9587 1.01058 1.91599C0.992857 1.87328 0.983734 1.82749 0.983734 1.78125C0.983734 1.73501 0.992857 1.68922 1.01058 1.64651C1.0283 1.6038 1.05428 1.565 1.08702 1.53234Z"
                                fill="#3C4852" stroke="#3C4852" stroke-width="1.05469" />
                        </svg>
                    </li>
                </ul>
            </div>

            <div class="third-content-two">
                <table>
                    <tr class="tablehead">
                        <td class="onerow">programs</td>
                        <td class="tworow">Referrer Bonus</td>
                        <td class="threerow">Referre Bonus</td>
                    </tr>

                    <tr>
                        <td> <svg width="25" height="18" viewBox="0 0 25 18" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path
                                    d="M12.0235 12.0904L11.4957 11.8927L6.01172 9.83601V11.9882C6.01172 13.6484 8.7032 14.9941 12.0235 14.9941C15.3438 14.9941 18.0353 13.6484 18.0353 11.9882V9.83601L12.5514 11.8927L12.0235 12.0904Z"
                                    fill="url(#paint0_linear_1_317)" />
                                <path
                                    d="M22.5443 6.53999L23.7093 6.10313C23.9125 6.02689 24.0472 5.83255 24.0472 5.61544V4.83439C24.0472 4.61727 23.9125 4.42293 23.7093 4.3467L12.2065 0.0331629C12.0886 -0.0110543 11.9586 -0.0110543 11.8407 0.0331629L0.337968 4.3467C0.134678 4.42293 0 4.61727 0 4.83439V5.61544C0 5.83255 0.134678 6.02689 0.337968 6.10313L12.0236 10.4852L21.0413 7.1036V8.70875V11.4453C20.594 11.7056 20.2898 12.1848 20.2898 12.7397C20.2898 13.2946 20.594 13.7737 21.0413 14.034L19.7068 16.8882C19.594 17.1295 19.6802 17.4173 19.908 17.5555C20.3643 17.8323 21.0512 18 21.7928 18C22.5344 18 23.2213 17.8323 23.6776 17.5555C23.9054 17.4173 23.9916 17.1295 23.8788 16.8882L22.5443 14.034C22.9916 13.7737 23.2958 13.2946 23.2958 12.7397C23.2958 12.1848 22.9916 11.7056 22.5443 11.4453V8.14515V6.53999Z"
                                    fill="url(#paint1_linear_1_317)" />
                                <defs>
                                    <linearGradient id="paint0_linear_1_317" x1="-2.35216" y1="-3.50628" x2="24.0881"
                                        y2="23.6511" gradientUnits="userSpaceOnUse">
                                        <stop offset="0.184358" stop-color="#29ABE2" />
                                        <stop offset="0.821198" stop-color="#6200D2" />
                                    </linearGradient>
                                    <linearGradient id="paint1_linear_1_317" x1="0.664209" y1="-6.44287" x2="27.1043"
                                        y2="20.7148" gradientUnits="userSpaceOnUse">
                                        <stop offset="0.184358" stop-color="#29ABE2" />
                                        <stop offset="0.821198" stop-color="#6200D2" />
                                    </linearGradient>
                                </defs>
                            </svg>
                            Professional Certificate Program in<br>
                            Product Management</td>
                        <td class="two_three_column">₹ 7000</td>
                        <td class="two_three_column">₹ 9000</td>
                    </tr>

                    <tr>
                        <td> <svg width="25" height="18" viewBox="0 0 25 18" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path
                                    d="M12.0235 12.0904L11.4957 11.8927L6.01172 9.83601V11.9882C6.01172 13.6484 8.7032 14.9941 12.0235 14.9941C15.3438 14.9941 18.0353 13.6484 18.0353 11.9882V9.83601L12.5514 11.8927L12.0235 12.0904Z"
                                    fill="url(#paint0_linear_1_317)" />
                                <path
                                    d="M22.5443 6.53999L23.7093 6.10313C23.9125 6.02689 24.0472 5.83255 24.0472 5.61544V4.83439C24.0472 4.61727 23.9125 4.42293 23.7093 4.3467L12.2065 0.0331629C12.0886 -0.0110543 11.9586 -0.0110543 11.8407 0.0331629L0.337968 4.3467C0.134678 4.42293 0 4.61727 0 4.83439V5.61544C0 5.83255 0.134678 6.02689 0.337968 6.10313L12.0236 10.4852L21.0413 7.1036V8.70875V11.4453C20.594 11.7056 20.2898 12.1848 20.2898 12.7397C20.2898 13.2946 20.594 13.7737 21.0413 14.034L19.7068 16.8882C19.594 17.1295 19.6802 17.4173 19.908 17.5555C20.3643 17.8323 21.0512 18 21.7928 18C22.5344 18 23.2213 17.8323 23.6776 17.5555C23.9054 17.4173 23.9916 17.1295 23.8788 16.8882L22.5443 14.034C22.9916 13.7737 23.2958 13.2946 23.2958 12.7397C23.2958 12.1848 22.9916 11.7056 22.5443 11.4453V8.14515V6.53999Z"
                                    fill="url(#paint1_linear_1_317)" />
                                <defs>
                                    <linearGradient id="paint0_linear_1_317" x1="-2.35216" y1="-3.50628" x2="24.0881"
                                        y2="23.6511" gradientUnits="userSpaceOnUse">
                                        <stop offset="0.184358" stop-color="#29ABE2" />
                                        <stop offset="0.821198" stop-color="#6200D2" />
                                    </linearGradient>
                                    <linearGradient id="paint1_linear_1_317" x1="0.664209" y1="-6.44287" x2="27.1043"
                                        y2="20.7148" gradientUnits="userSpaceOnUse">
                                        <stop offset="0.184358" stop-color="#29ABE2" />
                                        <stop offset="0.821198" stop-color="#6200D2" />
                                    </linearGradient>
                                </defs>
                            </svg>PG Certificate Program in Strategic <br>
                            Product Management</td>
                        <td class="two_three_column">₹ 9,000</td>
                        <td class="two_three_column">₹ 11,000</td>
                    </tr>

                    <tr>
                        <td><svg width="25" height="18" viewBox="0 0 25 18" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path
                                    d="M12.0235 12.0904L11.4957 11.8927L6.01172 9.83601V11.9882C6.01172 13.6484 8.7032 14.9941 12.0235 14.9941C15.3438 14.9941 18.0353 13.6484 18.0353 11.9882V9.83601L12.5514 11.8927L12.0235 12.0904Z"
                                    fill="url(#paint0_linear_1_317)" />
                                <path
                                    d="M22.5443 6.53999L23.7093 6.10313C23.9125 6.02689 24.0472 5.83255 24.0472 5.61544V4.83439C24.0472 4.61727 23.9125 4.42293 23.7093 4.3467L12.2065 0.0331629C12.0886 -0.0110543 11.9586 -0.0110543 11.8407 0.0331629L0.337968 4.3467C0.134678 4.42293 0 4.61727 0 4.83439V5.61544C0 5.83255 0.134678 6.02689 0.337968 6.10313L12.0236 10.4852L21.0413 7.1036V8.70875V11.4453C20.594 11.7056 20.2898 12.1848 20.2898 12.7397C20.2898 13.2946 20.594 13.7737 21.0413 14.034L19.7068 16.8882C19.594 17.1295 19.6802 17.4173 19.908 17.5555C20.3643 17.8323 21.0512 18 21.7928 18C22.5344 18 23.2213 17.8323 23.6776 17.5555C23.9054 17.4173 23.9916 17.1295 23.8788 16.8882L22.5443 14.034C22.9916 13.7737 23.2958 13.2946 23.2958 12.7397C23.2958 12.1848 22.9916 11.7056 22.5443 11.4453V8.14515V6.53999Z"
                                    fill="url(#paint1_linear_1_317)" />
                                <defs>
                                    <linearGradient id="paint0_linear_1_317" x1="-2.35216" y1="-3.50628" x2="24.0881"
                                        y2="23.6511" gradientUnits="userSpaceOnUse">
                                        <stop offset="0.184358" stop-color="#29ABE2" />
                                        <stop offset="0.821198" stop-color="#6200D2" />
                                    </linearGradient>
                                    <linearGradient id="paint1_linear_1_317" x1="0.664209" y1="-6.44287" x2="27.1043"
                                        y2="20.7148" gradientUnits="userSpaceOnUse">
                                        <stop offset="0.184358" stop-color="#29ABE2" />
                                        <stop offset="0.821198" stop-color="#6200D2" />
                                    </linearGradient>
                                </defs>
                            </svg>Executive Program in Data Driven<br>
                            Product Management</td>
                        <td class="two_three_column">₹ 10,000</td>
                        <td class="two_three_column">₹ 10,000</td>
                    </tr>

                    <tr>
                        <td><svg width="25" height="18" viewBox="0 0 25 18" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path
                                    d="M12.0235 12.0904L11.4957 11.8927L6.01172 9.83601V11.9882C6.01172 13.6484 8.7032 14.9941 12.0235 14.9941C15.3438 14.9941 18.0353 13.6484 18.0353 11.9882V9.83601L12.5514 11.8927L12.0235 12.0904Z"
                                    fill="url(#paint0_linear_1_317)" />
                                <path
                                    d="M22.5443 6.53999L23.7093 6.10313C23.9125 6.02689 24.0472 5.83255 24.0472 5.61544V4.83439C24.0472 4.61727 23.9125 4.42293 23.7093 4.3467L12.2065 0.0331629C12.0886 -0.0110543 11.9586 -0.0110543 11.8407 0.0331629L0.337968 4.3467C0.134678 4.42293 0 4.61727 0 4.83439V5.61544C0 5.83255 0.134678 6.02689 0.337968 6.10313L12.0236 10.4852L21.0413 7.1036V8.70875V11.4453C20.594 11.7056 20.2898 12.1848 20.2898 12.7397C20.2898 13.2946 20.594 13.7737 21.0413 14.034L19.7068 16.8882C19.594 17.1295 19.6802 17.4173 19.908 17.5555C20.3643 17.8323 21.0512 18 21.7928 18C22.5344 18 23.2213 17.8323 23.6776 17.5555C23.9054 17.4173 23.9916 17.1295 23.8788 16.8882L22.5443 14.034C22.9916 13.7737 23.2958 13.2946 23.2958 12.7397C23.2958 12.1848 22.9916 11.7056 22.5443 11.4453V8.14515V6.53999Z"
                                    fill="url(#paint1_linear_1_317)" />
                                <defs>
                                    <linearGradient id="paint0_linear_1_317" x1="-2.35216" y1="-3.50628" x2="24.0881"
                                        y2="23.6511" gradientUnits="userSpaceOnUse">
                                        <stop offset="0.184358" stop-color="#29ABE2" />
                                        <stop offset="0.821198" stop-color="#6200D2" />
                                    </linearGradient>
                                    <linearGradient id="paint1_linear_1_317" x1="0.664209" y1="-6.44287" x2="27.1043"
                                        y2="20.7148" gradientUnits="userSpaceOnUse">
                                        <stop offset="0.184358" stop-color="#29ABE2" />
                                        <stop offset="0.821198" stop-color="#6200D2" />
                                    </linearGradient>
                                </defs>
                            </svg>Executive Program in Product Management <br>
                            and Digital Transformation</td>
                        <td class="two_three_column">₹ 10,000</td>
                        <td class="two_three_column">₹ 10,000</td>
                    </tr>

                    <tr>
                        <td><svg width="25" height="18" viewBox="0 0 25 18" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path
                                    d="M12.0235 12.0904L11.4957 11.8927L6.01172 9.83601V11.9882C6.01172 13.6484 8.7032 14.9941 12.0235 14.9941C15.3438 14.9941 18.0353 13.6484 18.0353 11.9882V9.83601L12.5514 11.8927L12.0235 12.0904Z"
                                    fill="url(#paint0_linear_1_317)" />
                                <path
                                    d="M22.5443 6.53999L23.7093 6.10313C23.9125 6.02689 24.0472 5.83255 24.0472 5.61544V4.83439C24.0472 4.61727 23.9125 4.42293 23.7093 4.3467L12.2065 0.0331629C12.0886 -0.0110543 11.9586 -0.0110543 11.8407 0.0331629L0.337968 4.3467C0.134678 4.42293 0 4.61727 0 4.83439V5.61544C0 5.83255 0.134678 6.02689 0.337968 6.10313L12.0236 10.4852L21.0413 7.1036V8.70875V11.4453C20.594 11.7056 20.2898 12.1848 20.2898 12.7397C20.2898 13.2946 20.594 13.7737 21.0413 14.034L19.7068 16.8882C19.594 17.1295 19.6802 17.4173 19.908 17.5555C20.3643 17.8323 21.0512 18 21.7928 18C22.5344 18 23.2213 17.8323 23.6776 17.5555C23.9054 17.4173 23.9916 17.1295 23.8788 16.8882L22.5443 14.034C22.9916 13.7737 23.2958 13.2946 23.2958 12.7397C23.2958 12.1848 22.9916 11.7056 22.5443 11.4453V8.14515V6.53999Z"
                                    fill="url(#paint1_linear_1_317)" />
                                <defs>
                                    <linearGradient id="paint0_linear_1_317" x1="-2.35216" y1="-3.50628" x2="24.0881"
                                        y2="23.6511" gradientUnits="userSpaceOnUse">
                                        <stop offset="0.184358" stop-color="#29ABE2" />
                                        <stop offset="0.821198" stop-color="#6200D2" />
                                    </linearGradient>
                                    <linearGradient id="paint1_linear_1_317" x1="0.664209" y1="-6.44287" x2="27.1043"
                                        y2="20.7148" gradientUnits="userSpaceOnUse">
                                        <stop offset="0.184358" stop-color="#29ABE2" />
                                        <stop offset="0.821198" stop-color="#6200D2" />
                                    </linearGradient>
                                </defs>
                            </svg>Executive Program in Product<br>
                            Management</td>
                        <td class="two_three_column">₹ 10,000</td>
                        <td class="two_three_column">₹ 10,000</td>
                    </tr>

                    <tr>
                        <td><svg width="25" height="18" viewBox="0 0 25 18" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path
                                    d="M12.0235 12.0904L11.4957 11.8927L6.01172 9.83601V11.9882C6.01172 13.6484 8.7032 14.9941 12.0235 14.9941C15.3438 14.9941 18.0353 13.6484 18.0353 11.9882V9.83601L12.5514 11.8927L12.0235 12.0904Z"
                                    fill="url(#paint0_linear_1_317)" />
                                <path
                                    d="M22.5443 6.53999L23.7093 6.10313C23.9125 6.02689 24.0472 5.83255 24.0472 5.61544V4.83439C24.0472 4.61727 23.9125 4.42293 23.7093 4.3467L12.2065 0.0331629C12.0886 -0.0110543 11.9586 -0.0110543 11.8407 0.0331629L0.337968 4.3467C0.134678 4.42293 0 4.61727 0 4.83439V5.61544C0 5.83255 0.134678 6.02689 0.337968 6.10313L12.0236 10.4852L21.0413 7.1036V8.70875V11.4453C20.594 11.7056 20.2898 12.1848 20.2898 12.7397C20.2898 13.2946 20.594 13.7737 21.0413 14.034L19.7068 16.8882C19.594 17.1295 19.6802 17.4173 19.908 17.5555C20.3643 17.8323 21.0512 18 21.7928 18C22.5344 18 23.2213 17.8323 23.6776 17.5555C23.9054 17.4173 23.9916 17.1295 23.8788 16.8882L22.5443 14.034C22.9916 13.7737 23.2958 13.2946 23.2958 12.7397C23.2958 12.1848 22.9916 11.7056 22.5443 11.4453V8.14515V6.53999Z"
                                    fill="url(#paint1_linear_1_317)" />
                                <defs>
                                    <linearGradient id="paint0_linear_1_317" x1="-2.35216" y1="-3.50628" x2="24.0881"
                                        y2="23.6511" gradientUnits="userSpaceOnUse">
                                        <stop offset="0.184358" stop-color="#29ABE2" />
                                        <stop offset="0.821198" stop-color="#6200D2" />
                                    </linearGradient>
                                    <linearGradient id="paint1_linear_1_317" x1="0.664209" y1="-6.44287" x2="27.1043"
                                        y2="20.7148" gradientUnits="userSpaceOnUse">
                                        <stop offset="0.184358" stop-color="#29ABE2" />
                                        <stop offset="0.821198" stop-color="#6200D2" />
                                    </linearGradient>
                                </defs>
                            </svg>Advanced Certification in Product<br>
                            Management</td>
                        <td class="two_three_column">₹ 10,000</td>
                        <td class="two_three_column">₹ 10,000</td>
                    </tr>

                    <tr>
                        <td><svg width="25" height="18" viewBox="0 0 25 18" fill="none"
                                xmlns="http://www.w3.org/2000/svg">
                                <path
                                    d="M12.0235 12.0904L11.4957 11.8927L6.01172 9.83601V11.9882C6.01172 13.6484 8.7032 14.9941 12.0235 14.9941C15.3438 14.9941 18.0353 13.6484 18.0353 11.9882V9.83601L12.5514 11.8927L12.0235 12.0904Z"
                                    fill="url(#paint0_linear_1_317)" />
                                <path
                                    d="M22.5443 6.53999L23.7093 6.10313C23.9125 6.02689 24.0472 5.83255 24.0472 5.61544V4.83439C24.0472 4.61727 23.9125 4.42293 23.7093 4.3467L12.2065 0.0331629C12.0886 -0.0110543 11.9586 -0.0110543 11.8407 0.0331629L0.337968 4.3467C0.134678 4.42293 0 4.61727 0 4.83439V5.61544C0 5.83255 0.134678 6.02689 0.337968 6.10313L12.0236 10.4852L21.0413 7.1036V8.70875V11.4453C20.594 11.7056 20.2898 12.1848 20.2898 12.7397C20.2898 13.2946 20.594 13.7737 21.0413 14.034L19.7068 16.8882C19.594 17.1295 19.6802 17.4173 19.908 17.5555C20.3643 17.8323 21.0512 18 21.7928 18C22.5344 18 23.2213 17.8323 23.6776 17.5555C23.9054 17.4173 23.9916 17.1295 23.8788 16.8882L22.5443 14.034C22.9916 13.7737 23.2958 13.2946 23.2958 12.7397C23.2958 12.1848 22.9916 11.7056 22.5443 11.4453V8.14515V6.53999Z"
                                    fill="url(#paint1_linear_1_317)" />
                                <defs>
                                    <linearGradient id="paint0_linear_1_317" x1="-2.35216" y1="-3.50628" x2="24.0881"
                                        y2="23.6511" gradientUnits="userSpaceOnUse">
                                        <stop offset="0.184358" stop-color="#29ABE2" />
                                        <stop offset="0.821198" stop-color="#6200D2" />
                                    </linearGradient>
                                    <linearGradient id="paint1_linear_1_317" x1="0.664209" y1="-6.44287" x2="27.1043"
                                        y2="20.7148" gradientUnits="userSpaceOnUse">
                                        <stop offset="0.184358" stop-color="#29ABE2" />
                                        <stop offset="0.821198" stop-color="#6200D2" />
                                    </linearGradient>
                                </defs>
                            </svg>Executive Program in Product Management <br>
                            and Project Management</td>
                        <td class="two_three_column">₹ 10,000</td>
                        <td class="two_three_column">₹ 10,000</td>
                    </tr>
                </table>

            </div>
        </div>
        <button>Show More <svg width="15" height="9" viewBox="0 0 15 9" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path
                    d="M1.49545 0.514712L0.0812378 1.92892L7.1523 8.99999L14.2234 1.92889L12.8092 0.514679L7.15231 6.17157L1.49545 0.514712Z"
                    fill="#B6B6B6" />
            </svg>
        </button><br>

        <button class="buttonblue">Refer Now</button>
    </section>

    <section class="fourth-page" id="fourth-page">
        <h1> Frequently Asked <span> Questions </span> </h1>
        <div class="fourth-content">
            <div class="Buttons">
                <button class="eligibility_btn">Eligibility</button>
                <button class="h_t_u_btn">How to Use?</button>
                <button class="t_c_btn">Terms & Conditions</button>
            </div>

            <div class="info">
                <h4 class="firstline">Do I need to have prior Product Management and Project Management experience to enroll in the
                    program?</h4>

                <h4>No, the program is designed to be inclusive of all levels of experience. All topics will be covered
                    from the basics,<br>
                    making it suitable for individuals from any field of work.</h4>

                <h4>What is the minimum system configuration required?</h4>
            </div>
            
                
        </div>
        <svg width="1060" height="210" viewBox="0 0 1360 210" fill="none" xmlns="http://www.w3.org/2000/svg">
            <rect x="0.5" y="0.5" width="1359" height="209" rx="11.5" fill="#1A73E8"/>
            <rect x="0.5" y="0.5" width="1359" height="209" rx="11.5" stroke="#1A73E8"/>
            <g clip-path="url(#clip0_1_297)">
            <path d="M1048.39 644.193C1222.8 644.193 1364.19 502.803 1364.19 328.389C1364.19 153.975 1222.8 12.584 1048.39 12.584C873.974 12.584 732.584 153.975 732.584 328.389C732.584 502.803 873.974 644.193 1048.39 644.193Z" fill="#237CF2"/>
            <path d="M1050.4 587.871C1192.6 587.871 1307.87 472.597 1307.87 330.4C1307.87 188.203 1192.6 72.9287 1050.4 72.9287C908.203 72.9287 792.929 188.203 792.929 330.4C792.929 472.597 908.203 587.871 1050.4 587.871Z" fill="#3289FC"/>
            <path d="M1048.39 515.457C1151.7 515.457 1235.46 431.704 1235.46 328.388C1235.46 225.073 1151.7 141.319 1048.39 141.319C945.074 141.319 861.32 225.073 861.32 328.388C861.32 431.704 945.074 515.457 1048.39 515.457Z" fill="#4696FF"/>
            </g>
            <rect x="49" y="65" width="80" height="80" rx="12" fill="#E2E8F0" fill-opacity="0.35"/>
            <rect x="53" y="69" width="72" height="72" rx="12" fill="white"/>
            <path d="M110 95.6667C112.577 95.6667 114.667 97.756 114.667 100.333V109.667C114.667 112.244 112.577 114.333 110 114.333H107.522C106.374 123.541 98.519 130.667 89 130.667V126C96.7319 126 103 119.732 103 112V98C103 90.2681 96.7319 84 89 84C81.268 84 75 90.2681 75 98V114.333H68C65.4226 114.333 63.3333 112.244 63.3333 109.667V100.333C63.3333 97.756 65.4226 95.6667 68 95.6667H70.4777C71.626 86.4587 79.4809 79.3334 89 79.3334C98.519 79.3334 106.374 86.4587 107.522 95.6667H110ZM79.1053 113.831L81.579 109.874C83.7304 111.221 86.2742 112 89 112C91.7258 112 94.2696 111.221 96.4209 109.874L98.8947 113.831C96.0261 115.628 92.6344 116.667 89 116.667C85.3656 116.667 81.9739 115.628 79.1053 113.831Z" fill="#1A73E8"/>
            <path d="M167.296 93L161.547 72.6307H165.515L169.186 87.5993H169.374L173.293 72.6307H176.904L180.832 87.6093H181.011L184.681 72.6307H188.65L182.901 93H179.261L175.183 78.7077H175.024L170.936 93H167.296ZM193.886 93.3083C192.918 93.3083 192.046 93.1359 191.271 92.7911C190.501 92.4397 189.891 91.9225 189.44 91.2396C188.996 90.5566 188.774 89.7145 188.774 88.7133C188.774 87.8513 188.933 87.1385 189.251 86.5749C189.57 86.0113 190.004 85.5604 190.554 85.2223C191.105 84.8841 191.725 84.6288 192.414 84.4564C193.111 84.2774 193.83 84.1481 194.573 84.0685C195.468 83.9757 196.194 83.8928 196.751 83.8199C197.308 83.7403 197.712 83.621 197.964 83.4618C198.223 83.2961 198.352 83.0408 198.352 82.696V82.6363C198.352 81.8871 198.13 81.3069 197.686 80.8958C197.241 80.4847 196.602 80.2791 195.766 80.2791C194.884 80.2791 194.185 80.4714 193.667 80.856C193.157 81.2406 192.812 81.6948 192.633 82.2186L189.271 81.7412C189.537 80.8129 189.974 80.0371 190.584 79.4138C191.194 78.7839 191.94 78.3131 192.822 78.0015C193.704 77.6832 194.679 77.5241 195.746 77.5241C196.482 77.5241 197.215 77.6103 197.944 77.7827C198.674 77.9551 199.34 78.2402 199.943 78.638C200.547 79.0292 201.031 79.563 201.396 80.2393C201.767 80.9157 201.952 81.7611 201.952 82.7756V93H198.491V90.9014H198.372C198.153 91.3258 197.845 91.7236 197.447 92.0949C197.056 92.4596 196.562 92.7547 195.965 92.9801C195.375 93.1989 194.682 93.3083 193.886 93.3083ZM194.821 90.6627C195.544 90.6627 196.171 90.5201 196.701 90.235C197.231 89.9433 197.639 89.5587 197.924 89.0813C198.216 88.6039 198.362 88.0834 198.362 87.5198V85.7196C198.249 85.8124 198.057 85.8986 197.785 85.9782C197.52 86.0577 197.222 86.1273 196.89 86.187C196.558 86.2467 196.23 86.2997 195.905 86.3462C195.58 86.3926 195.299 86.4324 195.06 86.4655C194.523 86.5384 194.042 86.6578 193.618 86.8236C193.193 86.9893 192.859 87.2214 192.613 87.5198C192.368 87.8115 192.245 88.1895 192.245 88.6536C192.245 89.3167 192.487 89.8173 192.971 90.1555C193.455 90.4936 194.072 90.6627 194.821 90.6627ZM209.173 84.0486V93H205.573V77.723H209.014V80.3189H209.193C209.545 79.4636 210.105 78.7839 210.874 78.28C211.65 77.7761 212.608 77.5241 213.748 77.5241C214.803 77.5241 215.721 77.7495 216.503 78.2004C217.292 78.6513 217.902 79.3044 218.333 80.1598C218.771 81.0151 218.987 82.0528 218.98 83.2729V93H215.38V83.8298C215.38 82.8087 215.114 82.0097 214.584 81.4329C214.06 80.856 213.334 80.5676 212.406 80.5676C211.776 80.5676 211.215 80.7068 210.725 80.9853C210.241 81.2571 209.86 81.6517 209.581 82.1689C209.309 82.686 209.173 83.3126 209.173 84.0486ZM230.269 77.723V80.5079H221.486V77.723H230.269ZM223.655 74.0629H227.255V88.405C227.255 88.889 227.328 89.2603 227.474 89.5189C227.626 89.7709 227.825 89.9433 228.071 90.0361C228.316 90.1289 228.588 90.1753 228.886 90.1753C229.112 90.1753 229.317 90.1588 229.503 90.1256C229.695 90.0925 229.841 90.0626 229.94 90.0361L230.547 92.8508C230.355 92.9171 230.08 92.9901 229.722 93.0696C229.37 93.1492 228.939 93.1956 228.429 93.2089C227.527 93.2354 226.715 93.0995 225.992 92.8011C225.269 92.4961 224.696 92.0253 224.271 91.3888C223.853 90.7522 223.648 89.9565 223.655 89.0017V74.0629ZM247.856 77.723V80.5079H239.073V77.723H247.856ZM241.241 74.0629H244.842V88.405C244.842 88.889 244.915 89.2603 245.061 89.5189C245.213 89.7709 245.412 89.9433 245.657 90.0361C245.903 90.1289 246.175 90.1753 246.473 90.1753C246.699 90.1753 246.904 90.1588 247.09 90.1256C247.282 90.0925 247.428 90.0626 247.527 90.0361L248.134 92.8508C247.942 92.9171 247.667 92.9901 247.309 93.0696C246.957 93.1492 246.526 93.1956 246.016 93.2089C245.114 93.2354 244.302 93.0995 243.579 92.8011C242.856 92.4961 242.282 92.0253 241.858 91.3888C241.44 90.7522 241.235 89.9565 241.241 89.0017V74.0629ZM257.366 93.2984C255.874 93.2984 254.582 92.9702 253.487 92.3137C252.393 91.6573 251.545 90.739 250.941 89.5587C250.345 88.3784 250.046 86.9993 250.046 85.4212C250.046 83.8431 250.345 82.4606 250.941 81.2737C251.545 80.0868 252.393 79.1652 253.487 78.5087C254.582 77.8523 255.874 77.5241 257.366 77.5241C258.858 77.5241 260.151 77.8523 261.245 78.5087C262.339 79.1652 263.185 80.0868 263.782 81.2737C264.385 82.4606 264.687 83.8431 264.687 85.4212C264.687 86.9993 264.385 88.3784 263.782 89.5587C263.185 90.739 262.339 91.6573 261.245 92.3137C260.151 92.9702 258.858 93.2984 257.366 93.2984ZM257.386 90.4141C258.195 90.4141 258.872 90.1919 259.415 89.7477C259.959 89.2968 260.363 88.6934 260.629 87.9375C260.9 87.1816 261.036 86.3395 261.036 85.4112C261.036 84.4763 260.9 83.6309 260.629 82.875C260.363 82.1125 259.959 81.5058 259.415 81.0549C258.872 80.604 258.195 80.3786 257.386 80.3786C256.557 80.3786 255.868 80.604 255.318 81.0549C254.774 81.5058 254.366 82.1125 254.094 82.875C253.829 83.6309 253.696 84.4763 253.696 85.4112C253.696 86.3395 253.829 87.1816 254.094 87.9375C254.366 88.6934 254.774 89.2968 255.318 89.7477C255.868 90.1919 256.557 90.4141 257.386 90.4141ZM280.359 93.2685C279.159 93.2685 278.085 92.9602 277.136 92.3436C276.188 91.7269 275.439 90.8318 274.889 89.6582C274.338 88.4845 274.063 87.0589 274.063 85.3814C274.063 83.684 274.342 82.2517 274.899 81.0847C275.462 79.9111 276.221 79.0259 277.176 78.4292C278.131 77.8258 279.195 77.5241 280.369 77.5241C281.264 77.5241 282 77.6766 282.577 77.9816C283.154 78.28 283.611 78.6414 283.949 79.0657C284.288 79.4834 284.549 79.878 284.735 80.2493H284.884V72.6307H288.495V93H284.954V90.5931H284.735C284.549 90.9644 284.281 91.3589 283.93 91.7766C283.578 92.1877 283.114 92.5392 282.537 92.8309C281.96 93.1227 281.234 93.2685 280.359 93.2685ZM281.363 90.3146C282.126 90.3146 282.776 90.109 283.313 89.6979C283.85 89.2802 284.258 88.7 284.536 87.9574C284.815 87.2148 284.954 86.3495 284.954 85.3615C284.954 84.3735 284.815 83.5149 284.536 82.7855C284.264 82.0561 283.86 81.4892 283.323 81.0847C282.792 80.6803 282.139 80.478 281.363 80.478C280.561 80.478 279.891 80.6869 279.354 81.1046C278.817 81.5224 278.413 82.0992 278.141 82.8352C277.869 83.5712 277.733 84.4133 277.733 85.3615C277.733 86.3163 277.869 87.1684 278.141 87.9176C278.419 88.6602 278.827 89.2471 279.364 89.6781C279.908 90.1024 280.574 90.3146 281.363 90.3146ZM299.095 93.2984C297.563 93.2984 296.24 92.9801 295.126 92.3436C294.019 91.7004 293.167 90.792 292.57 89.6184C291.973 88.4381 291.675 87.049 291.675 85.451C291.675 83.8796 291.973 82.5004 292.57 81.3135C293.173 80.12 294.016 79.1917 295.096 78.5286C296.177 77.8589 297.447 77.5241 298.906 77.5241C299.847 77.5241 300.736 77.6766 301.571 77.9816C302.413 78.28 303.156 78.7441 303.799 79.374C304.449 80.004 304.959 80.8063 305.331 81.781C305.702 82.749 305.888 83.9028 305.888 85.2422V86.3462H293.366V83.9193H302.436C302.43 83.2298 302.281 82.6164 301.989 82.0793C301.697 81.5356 301.289 81.108 300.766 80.7963C300.248 80.4847 299.645 80.3289 298.955 80.3289C298.219 80.3289 297.573 80.5079 297.016 80.8659C296.459 81.2174 296.025 81.6815 295.713 82.2584C295.408 82.8286 295.252 83.4552 295.246 84.1382V86.2566C295.246 87.1451 295.408 87.9077 295.733 88.5442C296.058 89.1741 296.512 89.6582 297.095 89.9963C297.679 90.3279 298.362 90.4936 299.144 90.4936C299.668 90.4936 300.142 90.4207 300.567 90.2748C300.991 90.1223 301.359 89.9002 301.671 89.6084C301.982 89.3167 302.218 88.9553 302.377 88.5243L305.739 88.9023C305.526 89.7908 305.122 90.5666 304.525 91.2296C303.935 91.8861 303.179 92.3966 302.257 92.7613C301.336 93.1194 300.282 93.2984 299.095 93.2984ZM312.534 72.6307V93H308.934V72.6307H312.534ZM329.882 77.723L324.442 93H320.464L315.023 77.723H318.862L322.373 89.0713H322.532L326.053 77.723H329.882ZM338.617 93.2984C337.086 93.2984 335.763 92.9801 334.649 92.3436C333.542 91.7004 332.69 90.792 332.093 89.6184C331.496 88.4381 331.198 87.049 331.198 85.451C331.198 83.8796 331.496 82.5004 332.093 81.3135C332.696 80.12 333.538 79.1917 334.619 78.5286C335.7 77.8589 336.97 77.5241 338.428 77.5241C339.37 77.5241 340.258 77.6766 341.094 77.9816C341.936 78.28 342.679 78.7441 343.322 79.374C343.972 80.004 344.482 80.8063 344.853 81.781C345.225 82.749 345.41 83.9028 345.41 85.2422V86.3462H332.889V83.9193H341.959C341.953 83.2298 341.803 82.6164 341.512 82.0793C341.22 81.5356 340.812 81.108 340.288 80.7963C339.771 80.4847 339.168 80.3289 338.478 80.3289C337.742 80.3289 337.096 80.5079 336.539 80.8659C335.982 81.2174 335.547 81.6815 335.236 82.2584C334.931 82.8286 334.775 83.4552 334.768 84.1382V86.2566C334.768 87.1451 334.931 87.9077 335.256 88.5442C335.581 89.1741 336.035 89.6582 336.618 89.9963C337.202 90.3279 337.885 90.4936 338.667 90.4936C339.191 90.4936 339.665 90.4207 340.089 90.2748C340.514 90.1223 340.882 89.9002 341.193 89.6084C341.505 89.3167 341.74 88.9553 341.9 88.5243L345.261 88.9023C345.049 89.7908 344.645 90.5666 344.048 91.2296C343.458 91.8861 342.702 92.3966 341.78 92.7613C340.859 93.1194 339.804 93.2984 338.617 93.2984ZM361.073 93.2685C359.873 93.2685 358.799 92.9602 357.85 92.3436C356.902 91.7269 356.153 90.8318 355.603 89.6582C355.052 88.4845 354.777 87.0589 354.777 85.3814C354.777 83.684 355.056 82.2517 355.613 81.0847C356.176 79.9111 356.935 79.0259 357.89 78.4292C358.845 77.8258 359.909 77.5241 361.083 77.5241C361.978 77.5241 362.714 77.6766 363.291 77.9816C363.868 78.28 364.325 78.6414 364.663 79.0657C365.002 79.4834 365.263 79.878 365.449 80.2493H365.598V72.6307H369.209V93H365.668V90.5931H365.449C365.263 90.9644 364.995 91.3589 364.643 91.7766C364.292 92.1877 363.828 92.5392 363.251 92.8309C362.674 93.1227 361.948 93.2685 361.073 93.2685ZM362.077 90.3146C362.84 90.3146 363.49 90.109 364.027 89.6979C364.564 89.2802 364.972 88.7 365.25 87.9574C365.529 87.2148 365.668 86.3495 365.668 85.3615C365.668 84.3735 365.529 83.5149 365.25 82.7855C364.978 82.0561 364.574 81.4892 364.037 81.0847C363.506 80.6803 362.853 80.478 362.077 80.478C361.275 80.478 360.605 80.6869 360.068 81.1046C359.531 81.5224 359.127 82.0992 358.855 82.8352C358.583 83.5712 358.447 84.4133 358.447 85.3615C358.447 86.3163 358.583 87.1684 358.855 87.9176C359.133 88.6602 359.541 89.2471 360.078 89.6781C360.622 90.1024 361.288 90.3146 362.077 90.3146ZM379.809 93.2984C378.277 93.2984 376.954 92.9801 375.84 92.3436C374.733 91.7004 373.881 90.792 373.284 89.6184C372.687 88.4381 372.389 87.049 372.389 85.451C372.389 83.8796 372.687 82.5004 373.284 81.3135C373.887 80.12 374.729 79.1917 375.81 78.5286C376.891 77.8589 378.161 77.5241 379.62 77.5241C380.561 77.5241 381.45 77.6766 382.285 77.9816C383.127 78.28 383.87 78.7441 384.513 79.374C385.163 80.004 385.673 80.8063 386.045 81.781C386.416 82.749 386.602 83.9028 386.602 85.2422V86.3462H374.08V83.9193H383.15C383.144 83.2298 382.995 82.6164 382.703 82.0793C382.411 81.5356 382.003 81.108 381.479 80.7963C380.962 80.4847 380.359 80.3289 379.669 80.3289C378.933 80.3289 378.287 80.5079 377.73 80.8659C377.173 81.2174 376.739 81.6815 376.427 82.2584C376.122 82.8286 375.966 83.4552 375.959 84.1382V86.2566C375.959 87.1451 376.122 87.9077 376.447 88.5442C376.772 89.1741 377.226 89.6582 377.809 89.9963C378.393 90.3279 379.076 90.4936 379.858 90.4936C380.382 90.4936 380.856 90.4207 381.281 90.2748C381.705 90.1223 382.073 89.9002 382.385 89.6084C382.696 89.3167 382.932 88.9553 383.091 88.5243L386.452 88.9023C386.24 89.7908 385.836 90.5666 385.239 91.2296C384.649 91.8861 383.893 92.3966 382.971 92.7613C382.05 93.1194 380.995 93.2984 379.809 93.2984ZM396.411 93.2984C394.879 93.2984 393.556 92.9801 392.442 92.3436C391.335 91.7004 390.483 90.792 389.886 89.6184C389.29 88.4381 388.991 87.049 388.991 85.451C388.991 83.8796 389.29 82.5004 389.886 81.3135C390.49 80.12 391.332 79.1917 392.413 78.5286C393.493 77.8589 394.763 77.5241 396.222 77.5241C397.163 77.5241 398.052 77.6766 398.887 77.9816C399.729 78.28 400.472 78.7441 401.115 79.374C401.765 80.004 402.276 80.8063 402.647 81.781C403.018 82.749 403.204 83.9028 403.204 85.2422V86.3462H390.682V83.9193H399.753C399.746 83.2298 399.597 82.6164 399.305 82.0793C399.013 81.5356 398.606 81.108 398.082 80.7963C397.565 80.4847 396.961 80.3289 396.272 80.3289C395.536 80.3289 394.889 80.5079 394.332 80.8659C393.775 81.2174 393.341 81.6815 393.029 82.2584C392.724 82.8286 392.568 83.4552 392.562 84.1382V86.2566C392.562 87.1451 392.724 87.9077 393.049 88.5442C393.374 89.1741 393.828 89.6582 394.412 89.9963C394.995 90.3279 395.678 90.4936 396.461 90.4936C396.984 90.4936 397.458 90.4207 397.883 90.2748C398.307 90.1223 398.675 89.9002 398.987 89.6084C399.298 89.3167 399.534 88.9553 399.693 88.5243L403.055 88.9023C402.843 89.7908 402.438 90.5666 401.841 91.2296C401.251 91.8861 400.495 92.3966 399.574 92.7613C398.652 93.1194 397.598 93.2984 396.411 93.2984ZM406.25 98.7289V77.723H409.791V80.2493H410C410.185 79.878 410.447 79.4834 410.785 79.0657C411.123 78.6414 411.581 78.28 412.158 77.9816C412.735 77.6766 413.471 77.5241 414.366 77.5241C415.546 77.5241 416.61 77.8258 417.558 78.4292C418.513 79.0259 419.269 79.9111 419.826 81.0847C420.39 82.2517 420.672 83.684 420.672 85.3814C420.672 87.0589 420.396 88.4845 419.846 89.6582C419.296 90.8318 418.546 91.7269 417.598 92.3436C416.65 92.9602 415.576 93.2685 414.376 93.2685C413.5 93.2685 412.774 93.1227 412.198 92.8309C411.621 92.5392 411.157 92.1877 410.805 91.7766C410.46 91.3589 410.192 90.9644 410 90.5931H409.85V98.7289H406.25ZM409.781 85.3615C409.781 86.3495 409.92 87.2148 410.198 87.9574C410.484 88.7 410.891 89.2802 411.422 89.6979C411.959 90.109 412.609 90.3146 413.371 90.3146C414.167 90.3146 414.833 90.1024 415.37 89.6781C415.907 89.2471 416.312 88.6602 416.584 87.9176C416.862 87.1684 417.001 86.3163 417.001 85.3615C417.001 84.4133 416.866 83.5712 416.594 82.8352C416.322 82.0992 415.917 81.5224 415.38 81.1046C414.843 80.6869 414.173 80.478 413.371 80.478C412.602 80.478 411.949 80.6803 411.412 81.0847C410.875 81.4892 410.467 82.0561 410.188 82.7855C409.917 83.5149 409.781 84.3735 409.781 85.3615ZM430.518 93.2984C428.986 93.2984 427.664 92.9801 426.55 92.3436C425.442 91.7004 424.59 90.792 423.993 89.6184C423.397 88.4381 423.098 87.049 423.098 85.451C423.098 83.8796 423.397 82.5004 423.993 81.3135C424.597 80.12 425.439 79.1917 426.52 78.5286C427.601 77.8589 428.87 77.5241 430.329 77.5241C431.271 77.5241 432.159 77.6766 432.995 77.9816C433.837 78.28 434.579 78.7441 435.222 79.374C435.872 80.004 436.383 80.8063 436.754 81.781C437.125 82.749 437.311 83.9028 437.311 85.2422V86.3462H424.789V83.9193H433.86C433.853 83.2298 433.704 82.6164 433.412 82.0793C433.121 81.5356 432.713 81.108 432.189 80.7963C431.672 80.4847 431.068 80.3289 430.379 80.3289C429.643 80.3289 428.996 80.5079 428.439 80.8659C427.882 81.2174 427.448 81.6815 427.136 82.2584C426.831 82.8286 426.676 83.4552 426.669 84.1382V86.2566C426.669 87.1451 426.831 87.9077 427.156 88.5442C427.481 89.1741 427.935 89.6582 428.519 89.9963C429.102 90.3279 429.785 90.4936 430.568 90.4936C431.092 90.4936 431.566 90.4207 431.99 90.2748C432.414 90.1223 432.782 89.9002 433.094 89.6084C433.406 89.3167 433.641 88.9553 433.8 88.5243L437.162 88.9023C436.95 89.7908 436.545 90.5666 435.949 91.2296C435.358 91.8861 434.602 92.3966 433.681 92.7613C432.759 93.1194 431.705 93.2984 430.518 93.2984ZM440.357 93V77.723H443.848V80.2692H444.007C444.286 79.3873 444.763 78.7077 445.439 78.2303C446.122 77.7462 446.901 77.5042 447.777 77.5042C447.976 77.5042 448.198 77.5141 448.443 77.534C448.695 77.5473 448.904 77.5705 449.07 77.6037V80.9157C448.917 80.8626 448.675 80.8162 448.344 80.7764C448.019 80.73 447.704 80.7068 447.399 80.7068C446.742 80.7068 446.152 80.8494 445.628 81.1345C445.111 81.413 444.703 81.8009 444.405 82.2982C444.107 82.7954 443.957 83.369 443.957 84.0188V93H440.357ZM458.409 93V77.723H462.009V93H458.409ZM460.219 75.5548C459.649 75.5548 459.158 75.3658 458.747 74.9879C458.336 74.6033 458.13 74.1425 458.13 73.6054C458.13 73.0617 458.336 72.6008 458.747 72.2229C459.158 71.8383 459.649 71.646 460.219 71.646C460.796 71.646 461.287 71.8383 461.691 72.2229C462.102 72.6008 462.308 73.0617 462.308 73.6054C462.308 74.1425 462.102 74.6033 461.691 74.9879C461.287 75.3658 460.796 75.5548 460.219 75.5548ZM469.312 84.0486V93H465.712V77.723H469.153V80.3189H469.332C469.684 79.4636 470.244 78.7839 471.013 78.28C471.789 77.7761 472.747 77.5241 473.887 77.5241C474.942 77.5241 475.86 77.7495 476.642 78.2004C477.431 78.6513 478.041 79.3044 478.472 80.1598C478.91 81.0151 479.126 82.0528 479.119 83.2729V93H475.518V83.8298C475.518 82.8087 475.253 82.0097 474.723 81.4329C474.199 80.856 473.473 80.5676 472.545 80.5676C471.915 80.5676 471.354 80.7068 470.864 80.9853C470.38 81.2571 469.998 81.6517 469.72 82.1689C469.448 82.686 469.312 83.3126 469.312 84.0486ZM490.408 77.723V80.5079H481.625V77.723H490.408ZM483.794 74.0629H487.394V88.405C487.394 88.889 487.467 89.2603 487.613 89.5189C487.765 89.7709 487.964 89.9433 488.21 90.0361C488.455 90.1289 488.727 90.1753 489.025 90.1753C489.251 90.1753 489.456 90.1588 489.642 90.1256C489.834 90.0925 489.98 90.0626 490.079 90.0361L490.686 92.8508C490.494 92.9171 490.219 92.9901 489.861 93.0696C489.509 93.1492 489.078 93.1956 488.568 93.2089C487.666 93.2354 486.854 93.0995 486.131 92.8011C485.408 92.4961 484.835 92.0253 484.41 91.3888C483.992 90.7522 483.787 89.9565 483.794 89.0017V74.0629ZM499.918 93.2984C498.427 93.2984 497.134 92.9702 496.039 92.3137C494.945 91.6573 494.097 90.739 493.493 89.5587C492.897 88.3784 492.598 86.9993 492.598 85.4212C492.598 83.8431 492.897 82.4606 493.493 81.2737C494.097 80.0868 494.945 79.1652 496.039 78.5087C497.134 77.8523 498.427 77.5241 499.918 77.5241C501.41 77.5241 502.703 77.8523 503.797 78.5087C504.891 79.1652 505.737 80.0868 506.334 81.2737C506.937 82.4606 507.239 83.8431 507.239 85.4212C507.239 86.9993 506.937 88.3784 506.334 89.5587C505.737 90.739 504.891 91.6573 503.797 92.3137C502.703 92.9702 501.41 93.2984 499.918 93.2984ZM499.938 90.4141C500.747 90.4141 501.424 90.1919 501.967 89.7477C502.511 89.2968 502.915 88.6934 503.181 87.9375C503.453 87.1816 503.588 86.3395 503.588 85.4112C503.588 84.4763 503.453 83.6309 503.181 82.875C502.915 82.1125 502.511 81.5058 501.967 81.0549C501.424 80.604 500.747 80.3786 499.938 80.3786C499.109 80.3786 498.42 80.604 497.87 81.0549C497.326 81.5058 496.918 82.1125 496.646 82.875C496.381 83.6309 496.248 84.4763 496.248 85.4112C496.248 86.3395 496.381 87.1816 496.646 87.9375C496.918 88.6934 497.326 89.2968 497.87 89.7477C498.42 90.1919 499.109 90.4141 499.938 90.4141ZM524.87 77.723V80.5079H516.088V77.723H524.87ZM518.256 74.0629H521.857V88.405C521.857 88.889 521.93 89.2603 522.075 89.5189C522.228 89.7709 522.427 89.9433 522.672 90.0361C522.918 90.1289 523.189 90.1753 523.488 90.1753C523.713 90.1753 523.919 90.1588 524.104 90.1256C524.297 90.0925 524.443 90.0626 524.542 90.0361L525.149 92.8508C524.957 92.9171 524.681 92.9901 524.323 93.0696C523.972 93.1492 523.541 93.1956 523.03 93.2089C522.129 93.2354 521.316 93.0995 520.594 92.8011C519.871 92.4961 519.297 92.0253 518.873 91.3888C518.455 90.7522 518.25 89.9565 518.256 89.0017V74.0629ZM531.81 84.0486V93H528.21V72.6307H531.731V80.3189H531.91C532.268 79.4569 532.821 78.7773 533.571 78.28C534.326 77.7761 535.288 77.5241 536.455 77.5241C537.516 77.5241 538.441 77.7462 539.23 78.1905C540.019 78.6347 540.629 79.2845 541.06 80.1399C541.497 80.9952 541.716 82.0396 541.716 83.2729V93H538.116V83.8298C538.116 82.8021 537.851 82.0031 537.32 81.4329C536.796 80.856 536.06 80.5676 535.112 80.5676C534.476 80.5676 533.905 80.7068 533.401 80.9853C532.904 81.2571 532.513 81.6517 532.228 82.1689C531.949 82.686 531.81 83.3126 531.81 84.0486ZM552.15 93.2984C550.618 93.2984 549.295 92.9801 548.181 92.3436C547.074 91.7004 546.222 90.792 545.625 89.6184C545.028 88.4381 544.73 87.049 544.73 85.451C544.73 83.8796 545.028 82.5004 545.625 81.3135C546.228 80.12 547.071 79.1917 548.151 78.5286C549.232 77.8589 550.502 77.5241 551.961 77.5241C552.902 77.5241 553.791 77.6766 554.626 77.9816C555.468 78.28 556.211 78.7441 556.854 79.374C557.504 80.004 558.014 80.8063 558.386 81.781C558.757 82.749 558.943 83.9028 558.943 85.2422V86.3462H546.421V83.9193H555.491C555.485 83.2298 555.336 82.6164 555.044 82.0793C554.752 81.5356 554.344 81.108 553.82 80.7963C553.303 80.4847 552.7 80.3289 552.01 80.3289C551.274 80.3289 550.628 80.5079 550.071 80.8659C549.514 81.2174 549.08 81.6815 548.768 82.2584C548.463 82.8286 548.307 83.4552 548.3 84.1382V86.2566C548.3 87.1451 548.463 87.9077 548.788 88.5442C549.113 89.1741 549.567 89.6582 550.15 89.9963C550.734 90.3279 551.417 90.4936 552.199 90.4936C552.723 90.4936 553.197 90.4207 553.622 90.2748C554.046 90.1223 554.414 89.9002 554.726 89.6084C555.037 89.3167 555.273 88.9553 555.432 88.5243L558.793 88.9023C558.581 89.7908 558.177 90.5666 557.58 91.2296C556.99 91.8861 556.234 92.3966 555.312 92.7613C554.391 93.1194 553.336 93.2984 552.15 93.2984ZM568.936 98.7289V77.723H572.477V80.2493H572.686C572.871 79.878 573.133 79.4834 573.471 79.0657C573.809 78.6414 574.267 78.28 574.844 77.9816C575.421 77.6766 576.157 77.5241 577.052 77.5241C578.232 77.5241 579.296 77.8258 580.244 78.4292C581.199 79.0259 581.955 79.9111 582.512 81.0847C583.076 82.2517 583.358 83.684 583.358 85.3814C583.358 87.0589 583.082 88.4845 582.532 89.6582C581.982 90.8318 581.232 91.7269 580.284 92.3436C579.336 92.9602 578.262 93.2685 577.062 93.2685C576.186 93.2685 575.46 93.1227 574.884 92.8309C574.307 92.5392 573.843 92.1877 573.491 91.7766C573.146 91.3589 572.878 90.9644 572.686 90.5931H572.536V98.7289H568.936ZM572.467 85.3615C572.467 86.3495 572.606 87.2148 572.884 87.9574C573.17 88.7 573.577 89.2802 574.108 89.6979C574.645 90.109 575.295 90.3146 576.057 90.3146C576.853 90.3146 577.519 90.1024 578.056 89.6781C578.593 89.2471 578.998 88.6602 579.27 87.9176C579.548 87.1684 579.687 86.3163 579.687 85.3615C579.687 84.4133 579.552 83.5712 579.28 82.8352C579.008 82.0992 578.603 81.5224 578.066 81.1046C577.529 80.6869 576.859 80.478 576.057 80.478C575.288 80.478 574.635 80.6803 574.098 81.0847C573.561 81.4892 573.153 82.0561 572.874 82.7855C572.603 83.5149 572.467 84.3735 572.467 85.3615ZM586.441 93V77.723H589.932V80.2692H590.091C590.369 79.3873 590.847 78.7077 591.523 78.2303C592.206 77.7462 592.985 77.5042 593.86 77.5042C594.059 77.5042 594.281 77.5141 594.527 77.534C594.779 77.5473 594.988 77.5705 595.153 77.6037V80.9157C595.001 80.8626 594.759 80.8162 594.427 80.7764C594.102 80.73 593.788 80.7068 593.483 80.7068C592.826 80.7068 592.236 80.8494 591.712 81.1345C591.195 81.413 590.787 81.8009 590.489 82.2982C590.19 82.7954 590.041 83.369 590.041 84.0188V93H586.441ZM603.58 93.2984C602.088 93.2984 600.795 92.9702 599.701 92.3137C598.607 91.6573 597.758 90.739 597.155 89.5587C596.558 88.3784 596.26 86.9993 596.26 85.4212C596.26 83.8431 596.558 82.4606 597.155 81.2737C597.758 80.0868 598.607 79.1652 599.701 78.5087C600.795 77.8523 602.088 77.5241 603.58 77.5241C605.072 77.5241 606.365 77.8523 607.459 78.5087C608.553 79.1652 609.399 80.0868 609.995 81.2737C610.599 82.4606 610.9 83.8431 610.9 85.4212C610.9 86.9993 610.599 88.3784 609.995 89.5587C609.399 90.739 608.553 91.6573 607.459 92.3137C606.365 92.9702 605.072 93.2984 603.58 93.2984ZM603.6 90.4141C604.409 90.4141 605.085 90.1919 605.629 89.7477C606.173 89.2968 606.577 88.6934 606.842 87.9375C607.114 87.1816 607.25 86.3395 607.25 85.4112C607.25 84.4763 607.114 83.6309 606.842 82.875C606.577 82.1125 606.173 81.5058 605.629 81.0549C605.085 80.604 604.409 80.3786 603.6 80.3786C602.771 80.3786 602.082 80.604 601.531 81.0549C600.988 81.5058 600.58 82.1125 600.308 82.875C600.043 83.6309 599.91 84.4763 599.91 85.4112C599.91 86.3395 600.043 87.1816 600.308 87.9375C600.58 88.6934 600.988 89.2968 601.531 89.7477C602.082 90.1919 602.771 90.4141 603.6 90.4141ZM620.6 99.0471C619.307 99.0471 618.197 98.8714 617.268 98.52C616.34 98.1752 615.594 97.7111 615.03 97.1276C614.467 96.5441 614.076 95.8976 613.857 95.1881L617.099 94.4024C617.245 94.7008 617.457 94.9958 617.736 95.2876C618.014 95.5859 618.389 95.8313 618.86 96.0236C619.337 96.2225 619.937 96.3219 620.66 96.3219C621.681 96.3219 622.526 96.0733 623.196 95.576C623.866 95.0853 624.201 94.2764 624.201 93.1492V90.2549H624.022C623.836 90.6262 623.564 91.0075 623.206 91.3987C622.855 91.7899 622.387 92.1181 621.804 92.3834C621.227 92.6486 620.501 92.7812 619.625 92.7812C618.452 92.7812 617.388 92.506 616.433 91.9557C615.485 91.3987 614.729 90.5699 614.165 89.4692C613.608 88.3619 613.33 86.9761 613.33 85.3118C613.33 83.6342 613.608 82.2186 614.165 81.0649C614.729 79.9045 615.488 79.0259 616.443 78.4292C617.398 77.8258 618.462 77.5241 619.635 77.5241C620.531 77.5241 621.267 77.6766 621.843 77.9816C622.427 78.28 622.891 78.6414 623.236 79.0657C623.581 79.4834 623.843 79.878 624.022 80.2493H624.22V77.723H627.771V93.2486C627.771 94.5549 627.46 95.6357 626.836 96.491C626.213 97.3464 625.361 97.9862 624.28 98.4106C623.199 98.835 621.973 99.0471 620.6 99.0471ZM620.63 89.9565C621.393 89.9565 622.042 89.7709 622.579 89.3996C623.116 89.0282 623.524 88.4945 623.803 87.7983C624.081 87.102 624.22 86.2666 624.22 85.2919C624.22 84.3304 624.081 83.4884 623.803 82.7656C623.531 82.0429 623.126 81.4826 622.589 81.0847C622.059 80.6803 621.406 80.478 620.63 80.478C619.828 80.478 619.158 80.6869 618.621 81.1046C618.084 81.5224 617.679 82.0959 617.407 82.8253C617.136 83.548 617 84.3702 617 85.2919C617 86.2268 617.136 87.0457 617.407 87.7485C617.686 88.4448 618.094 88.9885 618.631 89.3797C619.175 89.7642 619.841 89.9565 620.63 89.9565ZM631.461 93V77.723H634.952V80.2692H635.111C635.39 79.3873 635.867 78.7077 636.544 78.2303C637.226 77.7462 638.006 77.5042 638.881 77.5042C639.08 77.5042 639.302 77.5141 639.547 77.534C639.799 77.5473 640.008 77.5705 640.174 77.6037V80.9157C640.021 80.8626 639.779 80.8162 639.448 80.7764C639.123 80.73 638.808 80.7068 638.503 80.7068C637.846 80.7068 637.256 80.8494 636.732 81.1345C636.215 81.413 635.808 81.8009 635.509 82.2982C635.211 82.7954 635.062 83.369 635.062 84.0188V93H631.461ZM646.688 93.3083C645.72 93.3083 644.848 93.1359 644.073 92.7911C643.303 92.4397 642.693 91.9225 642.243 91.2396C641.798 90.5566 641.576 89.7145 641.576 88.7133C641.576 87.8513 641.735 87.1385 642.054 86.5749C642.372 86.0113 642.806 85.5604 643.356 85.2223C643.907 84.8841 644.527 84.6288 645.216 84.4564C645.913 84.2774 646.632 84.1481 647.375 84.0685C648.27 83.9757 648.996 83.8928 649.553 83.8199C650.11 83.7403 650.514 83.621 650.766 83.4618C651.025 83.2961 651.154 83.0408 651.154 82.696V82.6363C651.154 81.8871 650.932 81.3069 650.488 80.8958C650.043 80.4847 649.404 80.2791 648.568 80.2791C647.686 80.2791 646.987 80.4714 646.47 80.856C645.959 81.2406 645.614 81.6948 645.435 82.2186L642.073 81.7412C642.339 80.8129 642.776 80.0371 643.386 79.4138C643.996 78.7839 644.742 78.3131 645.624 78.0015C646.506 77.6832 647.481 77.5241 648.548 77.5241C649.284 77.5241 650.017 77.6103 650.746 77.7827C651.476 77.9551 652.142 78.2402 652.745 78.638C653.349 79.0292 653.833 79.563 654.198 80.2393C654.569 80.9157 654.755 81.7611 654.755 82.7756V93H651.293V90.9014H651.174C650.955 91.3258 650.647 91.7236 650.249 92.0949C649.858 92.4596 649.364 92.7547 648.767 92.9801C648.177 93.1989 647.484 93.3083 646.688 93.3083ZM647.623 90.6627C648.346 90.6627 648.973 90.5201 649.503 90.235C650.034 89.9433 650.441 89.5587 650.726 89.0813C651.018 88.6039 651.164 88.0834 651.164 87.5198V85.7196C651.051 85.8124 650.859 85.8986 650.587 85.9782C650.322 86.0577 650.024 86.1273 649.692 86.187C649.361 86.2467 649.032 86.2997 648.707 86.3462C648.383 86.3926 648.101 86.4324 647.862 86.4655C647.325 86.5384 646.844 86.6578 646.42 86.8236C645.995 86.9893 645.661 87.2214 645.415 87.5198C645.17 87.8115 645.047 88.1895 645.047 88.6536C645.047 89.3167 645.289 89.8173 645.773 90.1555C646.257 90.4936 646.874 90.6627 647.623 90.6627ZM658.375 93V77.723H661.816V80.3189H661.995C662.313 79.4437 662.841 78.7607 663.577 78.27C664.313 77.7727 665.191 77.5241 666.212 77.5241C667.247 77.5241 668.119 77.7761 668.828 78.28C669.544 78.7773 670.048 79.4569 670.34 80.3189H670.499C670.837 79.4702 671.407 78.7939 672.21 78.2899C673.019 77.7794 673.977 77.5241 675.084 77.5241C676.49 77.5241 677.637 77.9683 678.525 78.8568C679.414 79.7454 679.858 81.0416 679.858 82.7457V93H676.248V83.3027C676.248 82.3545 675.996 81.6616 675.492 81.224C674.988 80.7797 674.371 80.5576 673.642 80.5576C672.773 80.5576 672.094 80.8295 671.603 81.3732C671.119 81.9103 670.877 82.6098 670.877 83.4718V93H667.346V83.1535C667.346 82.3645 667.107 81.7345 666.63 81.2638C666.159 80.793 665.543 80.5576 664.78 80.5576C664.263 80.5576 663.792 80.6902 663.368 80.9554C662.943 81.214 662.605 81.582 662.353 82.0594C662.101 82.5302 661.975 83.0806 661.975 83.7105V93H658.375ZM686.952 87.0125V86.7539C686.959 85.5538 687.071 84.599 687.29 83.8895C687.516 83.18 687.834 82.6098 688.245 82.1788C688.656 81.7412 689.157 81.34 689.747 80.9753C690.151 80.7234 690.513 80.4482 690.831 80.1498C691.156 79.8448 691.411 79.5067 691.597 79.1353C691.783 78.7574 691.875 78.3363 691.875 77.8722C691.875 77.3484 691.753 76.8942 691.507 76.5096C691.262 76.125 690.931 75.8266 690.513 75.6145C690.102 75.4023 689.641 75.2962 689.13 75.2962C688.66 75.2962 688.212 75.399 687.788 75.6045C687.37 75.8034 687.022 76.1085 686.743 76.5196C686.471 76.924 686.319 77.4379 686.286 78.0612H682.745C682.778 76.8014 683.083 75.7471 683.66 74.8984C684.244 74.0496 685.013 73.4131 685.967 72.9887C686.929 72.5644 687.99 72.3522 689.15 72.3522C690.417 72.3522 691.531 72.5743 692.492 73.0186C693.46 73.4628 694.213 74.0961 694.75 74.9183C695.293 75.7338 695.565 76.7019 695.565 77.8225C695.565 78.5784 695.443 79.2547 695.197 79.8514C694.959 80.4482 694.617 80.9787 694.173 81.4428C693.729 81.9069 693.202 82.3214 692.591 82.686C692.054 83.0176 691.613 83.3624 691.269 83.7204C690.931 84.0785 690.679 84.4995 690.513 84.9836C690.354 85.461 690.271 86.0511 690.264 86.7539V87.0125H686.952ZM688.683 93.2188C688.086 93.2188 687.572 93.0066 687.141 92.5823C686.71 92.1579 686.495 91.6407 686.495 91.0307C686.495 90.4339 686.71 89.9234 687.141 89.499C687.572 89.0747 688.086 88.8625 688.683 88.8625C689.273 88.8625 689.783 89.0747 690.214 89.499C690.652 89.9234 690.871 90.4339 690.871 91.0307C690.871 91.4352 690.768 91.8032 690.563 92.1347C690.364 92.4662 690.098 92.7315 689.767 92.9304C689.442 93.1227 689.081 93.2188 688.683 93.2188Z" fill="white"/>
            <path d="M168.975 120.027C168.912 119.464 168.65 119.028 168.191 118.719C167.731 118.406 167.153 118.25 166.455 118.25C165.956 118.25 165.524 118.329 165.16 118.488C164.795 118.642 164.512 118.856 164.31 119.129C164.112 119.399 164.013 119.706 164.013 120.05C164.013 120.34 164.08 120.589 164.215 120.799C164.354 121.009 164.534 121.185 164.756 121.328C164.982 121.467 165.223 121.584 165.481 121.679C165.738 121.77 165.986 121.845 166.224 121.905L167.412 122.214C167.8 122.309 168.198 122.437 168.607 122.6C169.015 122.762 169.393 122.976 169.742 123.242C170.09 123.507 170.371 123.836 170.585 124.228C170.803 124.62 170.912 125.09 170.912 125.636C170.912 126.326 170.734 126.938 170.377 127.473C170.025 128.008 169.512 128.43 168.838 128.739C168.169 129.048 167.359 129.202 166.408 129.202C165.497 129.202 164.708 129.057 164.043 128.768C163.377 128.479 162.856 128.069 162.48 127.538C162.103 127.003 161.895 126.369 161.856 125.636H163.698C163.734 126.076 163.876 126.443 164.126 126.736C164.379 127.025 164.702 127.241 165.094 127.384C165.491 127.522 165.924 127.592 166.396 127.592C166.915 127.592 167.376 127.51 167.781 127.348C168.189 127.182 168.509 126.952 168.743 126.659C168.977 126.361 169.094 126.015 169.094 125.619C169.094 125.258 168.991 124.963 168.785 124.733C168.583 124.503 168.307 124.313 167.959 124.163C167.614 124.012 167.224 123.879 166.788 123.765L165.35 123.372C164.375 123.107 163.603 122.717 163.032 122.202C162.466 121.687 162.183 121.005 162.183 120.157C162.183 119.456 162.373 118.844 162.753 118.321C163.133 117.798 163.648 117.392 164.298 117.103C164.948 116.81 165.681 116.663 166.497 116.663C167.321 116.663 168.048 116.808 168.678 117.097C169.312 117.386 169.811 117.784 170.175 118.291C170.54 118.795 170.73 119.373 170.746 120.027H168.975ZM174.741 123.58V129H172.964V116.83H174.717V121.358H174.83C175.044 120.867 175.371 120.476 175.81 120.187C176.25 119.898 176.825 119.753 177.534 119.753C178.16 119.753 178.706 119.882 179.174 120.14C179.645 120.397 180.01 120.781 180.267 121.292C180.529 121.8 180.66 122.433 180.66 123.194V129H178.883V123.408C178.883 122.738 178.71 122.219 178.366 121.851C178.021 121.479 177.542 121.292 176.928 121.292C176.508 121.292 176.131 121.382 175.799 121.56C175.47 121.738 175.21 122 175.02 122.344C174.834 122.685 174.741 123.097 174.741 123.58ZM185.687 129.202C185.109 129.202 184.586 129.095 184.118 128.881C183.651 128.663 183.28 128.348 183.007 127.936C182.738 127.524 182.603 127.019 182.603 126.421C182.603 125.906 182.702 125.482 182.9 125.149C183.098 124.816 183.365 124.553 183.702 124.359C184.039 124.165 184.415 124.018 184.831 123.919C185.247 123.82 185.671 123.745 186.103 123.693C186.65 123.63 187.093 123.578 187.434 123.539C187.775 123.495 188.023 123.426 188.177 123.331C188.332 123.236 188.409 123.081 188.409 122.867V122.826C188.409 122.307 188.262 121.905 187.969 121.619C187.68 121.334 187.248 121.191 186.674 121.191C186.075 121.191 185.604 121.324 185.259 121.59C184.918 121.851 184.683 122.142 184.552 122.463L182.882 122.083C183.08 121.528 183.369 121.08 183.75 120.74C184.134 120.395 184.576 120.146 185.075 119.991C185.574 119.833 186.099 119.753 186.65 119.753C187.014 119.753 187.401 119.797 187.809 119.884C188.221 119.967 188.605 120.122 188.961 120.348C189.322 120.573 189.617 120.896 189.847 121.316C190.077 121.732 190.192 122.273 190.192 122.939V129H188.456V127.752H188.385C188.27 127.982 188.098 128.208 187.868 128.43C187.638 128.651 187.343 128.836 186.983 128.982C186.622 129.129 186.19 129.202 185.687 129.202ZM186.073 127.776C186.565 127.776 186.985 127.679 187.333 127.485C187.686 127.291 187.953 127.037 188.135 126.724C188.322 126.407 188.415 126.068 188.415 125.708V124.531C188.351 124.595 188.229 124.654 188.046 124.709C187.868 124.761 187.664 124.807 187.434 124.846C187.204 124.882 186.981 124.915 186.763 124.947C186.545 124.975 186.363 124.999 186.216 125.018C185.871 125.062 185.556 125.135 185.271 125.238C184.99 125.341 184.764 125.49 184.594 125.684C184.427 125.874 184.344 126.128 184.344 126.445C184.344 126.884 184.506 127.217 184.831 127.443C185.156 127.665 185.57 127.776 186.073 127.776ZM192.558 129V119.872H194.276V121.322H194.371C194.537 120.831 194.83 120.445 195.25 120.163C195.674 119.878 196.153 119.735 196.688 119.735C196.799 119.735 196.93 119.739 197.081 119.747C197.235 119.755 197.356 119.765 197.443 119.777V121.477C197.372 121.457 197.245 121.435 197.063 121.411C196.88 121.384 196.698 121.37 196.516 121.37C196.096 121.37 195.722 121.459 195.393 121.637C195.068 121.811 194.81 122.055 194.62 122.368C194.43 122.677 194.335 123.03 194.335 123.426V129H192.558ZM202.588 129.184C201.689 129.184 200.914 128.992 200.264 128.608C199.619 128.22 199.119 127.675 198.767 126.974C198.418 126.268 198.244 125.442 198.244 124.496C198.244 123.561 198.418 122.736 198.767 122.023C199.119 121.31 199.611 120.754 200.241 120.354C200.874 119.953 201.615 119.753 202.463 119.753C202.978 119.753 203.477 119.838 203.961 120.009C204.444 120.179 204.878 120.447 205.262 120.811C205.646 121.176 205.949 121.649 206.171 122.231C206.393 122.81 206.504 123.513 206.504 124.341V124.971H199.248V123.64H204.763C204.763 123.172 204.668 122.758 204.478 122.398C204.287 122.033 204.02 121.746 203.675 121.536C203.335 121.326 202.934 121.221 202.475 121.221C201.976 121.221 201.54 121.344 201.168 121.59C200.799 121.831 200.514 122.148 200.312 122.54C200.114 122.929 200.015 123.351 200.015 123.806V124.846C200.015 125.456 200.122 125.975 200.336 126.403C200.553 126.831 200.857 127.158 201.245 127.384C201.633 127.605 202.087 127.716 202.606 127.716C202.942 127.716 203.249 127.669 203.527 127.574C203.804 127.475 204.044 127.328 204.246 127.134C204.448 126.94 204.602 126.7 204.709 126.415L206.391 126.718C206.256 127.213 206.015 127.647 205.666 128.019C205.321 128.388 204.888 128.675 204.365 128.881C203.846 129.083 203.253 129.184 202.588 129.184ZM214.027 132.423C213.762 132.423 213.52 132.401 213.302 132.358C213.084 132.318 212.922 132.274 212.815 132.227L213.243 130.771C213.568 130.858 213.857 130.896 214.111 130.884C214.364 130.872 214.588 130.777 214.782 130.599C214.98 130.42 215.154 130.129 215.305 129.725L215.525 129.119L212.185 119.872H214.087L216.398 126.956H216.494L218.805 119.872H220.713L216.951 130.218C216.777 130.694 216.555 131.096 216.286 131.425C216.016 131.757 215.695 132.007 215.323 132.173C214.95 132.34 214.519 132.423 214.027 132.423ZM225.917 129.184C225.061 129.184 224.314 128.988 223.677 128.596C223.039 128.204 222.544 127.655 222.191 126.95C221.838 126.245 221.662 125.421 221.662 124.478C221.662 123.531 221.838 122.703 222.191 121.994C222.544 121.285 223.039 120.734 223.677 120.342C224.314 119.949 225.061 119.753 225.917 119.753C226.773 119.753 227.52 119.949 228.157 120.342C228.795 120.734 229.29 121.285 229.643 121.994C229.996 122.703 230.172 123.531 230.172 124.478C230.172 125.421 229.996 126.245 229.643 126.95C229.29 127.655 228.795 128.204 228.157 128.596C227.52 128.988 226.773 129.184 225.917 129.184ZM225.923 127.693C226.478 127.693 226.937 127.546 227.302 127.253C227.666 126.96 227.936 126.569 228.11 126.082C228.288 125.595 228.377 125.058 228.377 124.472C228.377 123.889 228.288 123.355 228.11 122.867C227.936 122.376 227.666 121.982 227.302 121.685C226.937 121.388 226.478 121.239 225.923 121.239C225.364 121.239 224.901 121.388 224.532 121.685C224.168 121.982 223.897 122.376 223.718 122.867C223.544 123.355 223.457 123.889 223.457 124.472C223.457 125.058 223.544 125.595 223.718 126.082C223.897 126.569 224.168 126.96 224.532 127.253C224.901 127.546 225.364 127.693 225.923 127.693ZM237.937 125.215V119.872H239.72V129H237.973V127.419H237.878C237.668 127.907 237.331 128.313 236.868 128.638C236.408 128.958 235.836 129.119 235.15 129.119C234.564 129.119 234.045 128.99 233.593 128.733C233.146 128.471 232.793 128.085 232.536 127.574C232.282 127.063 232.155 126.431 232.155 125.678V119.872H233.932V125.464C233.932 126.086 234.104 126.581 234.449 126.95C234.794 127.318 235.241 127.502 235.792 127.502C236.125 127.502 236.456 127.419 236.785 127.253C237.117 127.086 237.393 126.835 237.611 126.498C237.832 126.161 237.941 125.734 237.937 125.215ZM242.108 129V119.872H243.825V121.322H243.92C244.087 120.831 244.38 120.445 244.8 120.163C245.224 119.878 245.703 119.735 246.238 119.735C246.349 119.735 246.479 119.739 246.63 119.747C246.784 119.755 246.905 119.765 246.992 119.777V121.477C246.921 121.457 246.794 121.435 246.612 121.411C246.43 121.384 246.248 121.37 246.065 121.37C245.645 121.37 245.271 121.459 244.942 121.637C244.617 121.811 244.36 122.055 244.17 122.368C243.98 122.677 243.884 123.03 243.884 123.426V129H242.108ZM256.376 129.178C255.639 129.178 254.981 128.99 254.403 128.614C253.828 128.233 253.377 127.693 253.048 126.991C252.723 126.286 252.561 125.44 252.561 124.454C252.561 123.467 252.725 122.624 253.054 121.922C253.387 121.221 253.842 120.684 254.421 120.312C254.999 119.94 255.655 119.753 256.388 119.753C256.954 119.753 257.41 119.848 257.755 120.039C258.103 120.225 258.373 120.443 258.563 120.692C258.757 120.942 258.907 121.162 259.014 121.352H259.121V116.83H260.898V129H259.163V127.58H259.014C258.907 127.774 258.753 127.996 258.551 128.245C258.353 128.495 258.079 128.713 257.731 128.899C257.382 129.085 256.93 129.178 256.376 129.178ZM256.768 127.663C257.279 127.663 257.711 127.528 258.064 127.259C258.42 126.985 258.689 126.607 258.872 126.124C259.058 125.64 259.151 125.078 259.151 124.436C259.151 123.802 259.06 123.248 258.878 122.772C258.695 122.297 258.428 121.926 258.075 121.661C257.723 121.395 257.287 121.263 256.768 121.263C256.233 121.263 255.788 121.401 255.431 121.679C255.074 121.956 254.805 122.334 254.623 122.814C254.444 123.293 254.355 123.834 254.355 124.436C254.355 125.046 254.446 125.595 254.629 126.082C254.811 126.569 255.08 126.956 255.437 127.241C255.797 127.522 256.241 127.663 256.768 127.663ZM267.368 129.184C266.469 129.184 265.694 128.992 265.045 128.608C264.399 128.22 263.9 127.675 263.547 126.974C263.198 126.268 263.024 125.442 263.024 124.496C263.024 123.561 263.198 122.736 263.547 122.023C263.9 121.31 264.391 120.754 265.021 120.354C265.655 119.953 266.396 119.753 267.243 119.753C267.758 119.753 268.258 119.838 268.741 120.009C269.224 120.179 269.658 120.447 270.042 120.811C270.427 121.176 270.73 121.649 270.952 122.231C271.173 122.81 271.284 123.513 271.284 124.341V124.971H264.028V123.64H269.543C269.543 123.172 269.448 122.758 269.258 122.398C269.068 122.033 268.8 121.746 268.456 121.536C268.115 121.326 267.715 121.221 267.255 121.221C266.756 121.221 266.32 121.344 265.948 121.59C265.579 121.831 265.294 122.148 265.092 122.54C264.894 122.929 264.795 123.351 264.795 123.806V124.846C264.795 125.456 264.902 125.975 265.116 126.403C265.334 126.831 265.637 127.158 266.025 127.384C266.413 127.605 266.867 127.716 267.386 127.716C267.723 127.716 268.03 127.669 268.307 127.574C268.584 127.475 268.824 127.328 269.026 127.134C269.228 126.94 269.383 126.7 269.49 126.415L271.171 126.718C271.037 127.213 270.795 127.647 270.446 128.019C270.102 128.388 269.668 128.675 269.145 128.881C268.626 129.083 268.034 129.184 267.368 129.184ZM277.517 119.872V121.298H272.531V119.872H277.517ZM273.868 117.685H275.645V126.32C275.645 126.665 275.696 126.924 275.799 127.098C275.902 127.269 276.035 127.386 276.197 127.449C276.364 127.508 276.544 127.538 276.738 127.538C276.881 127.538 277.006 127.528 277.113 127.508C277.22 127.489 277.303 127.473 277.362 127.461L277.683 128.929C277.58 128.968 277.433 129.008 277.243 129.048C277.053 129.091 276.815 129.115 276.53 129.119C276.063 129.127 275.627 129.044 275.223 128.869C274.819 128.695 274.492 128.426 274.242 128.061C273.993 127.697 273.868 127.239 273.868 126.688V117.685ZM282.139 129.202C281.56 129.202 281.037 129.095 280.57 128.881C280.102 128.663 279.732 128.348 279.458 127.936C279.189 127.524 279.054 127.019 279.054 126.421C279.054 125.906 279.153 125.482 279.351 125.149C279.55 124.816 279.817 124.553 280.154 124.359C280.49 124.165 280.867 124.018 281.283 123.919C281.699 123.82 282.123 123.745 282.554 123.693C283.101 123.63 283.545 123.578 283.886 123.539C284.226 123.495 284.474 123.426 284.628 123.331C284.783 123.236 284.86 123.081 284.86 122.867V122.826C284.86 122.307 284.714 121.905 284.42 121.619C284.131 121.334 283.699 121.191 283.125 121.191C282.527 121.191 282.055 121.324 281.711 121.59C281.37 121.851 281.134 122.142 281.003 122.463L279.334 122.083C279.532 121.528 279.821 121.08 280.201 120.74C280.586 120.395 281.027 120.146 281.526 119.991C282.026 119.833 282.551 119.753 283.101 119.753C283.466 119.753 283.852 119.797 284.26 119.884C284.672 119.967 285.056 120.122 285.413 120.348C285.773 120.573 286.069 120.896 286.298 121.316C286.528 121.732 286.643 122.273 286.643 122.939V129H284.908V127.752H284.836C284.722 127.982 284.549 128.208 284.319 128.43C284.09 128.651 283.795 128.836 283.434 128.982C283.073 129.129 282.642 129.202 282.139 129.202ZM282.525 127.776C283.016 127.776 283.436 127.679 283.785 127.485C284.137 127.291 284.405 127.037 284.587 126.724C284.773 126.407 284.866 126.068 284.866 125.708V124.531C284.803 124.595 284.68 124.654 284.498 124.709C284.319 124.761 284.115 124.807 283.886 124.846C283.656 124.882 283.432 124.915 283.214 124.947C282.996 124.975 282.814 124.999 282.667 125.018C282.323 125.062 282.008 125.135 281.723 125.238C281.441 125.341 281.215 125.49 281.045 125.684C280.879 125.874 280.795 126.128 280.795 126.445C280.795 126.884 280.958 127.217 281.283 127.443C281.608 127.665 282.022 127.776 282.525 127.776ZM289.01 129V119.872H290.786V129H289.01ZM289.907 118.464C289.598 118.464 289.333 118.361 289.111 118.155C288.893 117.945 288.784 117.695 288.784 117.406C288.784 117.113 288.893 116.863 289.111 116.657C289.333 116.447 289.598 116.342 289.907 116.342C290.216 116.342 290.479 116.447 290.697 116.657C290.919 116.863 291.03 117.113 291.03 117.406C291.03 117.695 290.919 117.945 290.697 118.155C290.479 118.361 290.216 118.464 289.907 118.464ZM294.954 116.83V129H293.177V116.83H294.954ZM304.184 122.101L302.574 122.386C302.506 122.18 302.399 121.984 302.253 121.798C302.11 121.611 301.916 121.459 301.67 121.34C301.425 121.221 301.118 121.162 300.749 121.162C300.246 121.162 299.826 121.275 299.489 121.5C299.153 121.722 298.984 122.01 298.984 122.362C298.984 122.667 299.097 122.913 299.323 123.099C299.549 123.285 299.913 123.438 300.416 123.557L301.866 123.889C302.706 124.083 303.332 124.383 303.744 124.787C304.156 125.191 304.362 125.716 304.362 126.361C304.362 126.908 304.204 127.395 303.887 127.823C303.574 128.247 303.136 128.58 302.574 128.822C302.015 129.063 301.367 129.184 300.63 129.184C299.608 129.184 298.774 128.966 298.129 128.531C297.483 128.091 297.087 127.467 296.94 126.659L298.657 126.397C298.764 126.845 298.984 127.184 299.317 127.413C299.65 127.639 300.084 127.752 300.619 127.752C301.201 127.752 301.666 127.631 302.015 127.39C302.364 127.144 302.538 126.845 302.538 126.492C302.538 126.207 302.431 125.967 302.217 125.773C302.007 125.579 301.684 125.432 301.248 125.333L299.703 124.995C298.852 124.801 298.222 124.492 297.814 124.068C297.41 123.644 297.207 123.107 297.207 122.457C297.207 121.918 297.358 121.447 297.659 121.043C297.96 120.639 298.376 120.324 298.907 120.098C299.438 119.868 300.046 119.753 300.731 119.753C301.718 119.753 302.494 119.967 303.061 120.395C303.627 120.819 304.002 121.388 304.184 122.101ZM315.006 119.872V121.298H310.02V119.872H315.006ZM311.357 117.685H313.134V126.32C313.134 126.665 313.185 126.924 313.288 127.098C313.391 127.269 313.524 127.386 313.686 127.449C313.853 127.508 314.033 127.538 314.227 127.538C314.37 127.538 314.495 127.528 314.601 127.508C314.708 127.489 314.792 127.473 314.851 127.461L315.172 128.929C315.069 128.968 314.922 129.008 314.732 129.048C314.542 129.091 314.304 129.115 314.019 129.119C313.552 129.127 313.116 129.044 312.712 128.869C312.308 128.695 311.981 128.426 311.731 128.061C311.482 127.697 311.357 127.239 311.357 126.688V117.685ZM320.718 129.184C319.862 129.184 319.115 128.988 318.478 128.596C317.84 128.204 317.344 127.655 316.992 126.95C316.639 126.245 316.463 125.421 316.463 124.478C316.463 123.531 316.639 122.703 316.992 121.994C317.344 121.285 317.84 120.734 318.478 120.342C319.115 119.949 319.862 119.753 320.718 119.753C321.574 119.753 322.32 119.949 322.958 120.342C323.596 120.734 324.091 121.285 324.444 121.994C324.797 122.703 324.973 123.531 324.973 124.478C324.973 125.421 324.797 126.245 324.444 126.95C324.091 127.655 323.596 128.204 322.958 128.596C322.32 128.988 321.574 129.184 320.718 129.184ZM320.724 127.693C321.278 127.693 321.738 127.546 322.103 127.253C322.467 126.96 322.736 126.569 322.911 126.082C323.089 125.595 323.178 125.058 323.178 124.472C323.178 123.889 323.089 123.355 322.911 122.867C322.736 122.376 322.467 121.982 322.103 121.685C321.738 121.388 321.278 121.239 320.724 121.239C320.165 121.239 319.702 121.388 319.333 121.685C318.969 121.982 318.697 122.376 318.519 122.867C318.345 123.355 318.258 123.889 318.258 124.472C318.258 125.058 318.345 125.595 318.519 126.082C318.697 126.569 318.969 126.96 319.333 127.253C319.702 127.546 320.165 127.693 320.724 127.693ZM331.385 129V119.872H333.102V121.322H333.197C333.364 120.831 333.657 120.445 334.077 120.163C334.501 119.878 334.98 119.735 335.515 119.735C335.626 119.735 335.757 119.739 335.907 119.747C336.062 119.755 336.183 119.765 336.27 119.777V121.477C336.198 121.457 336.072 121.435 335.889 121.411C335.707 121.384 335.525 121.37 335.343 121.37C334.923 121.37 334.548 121.459 334.22 121.637C333.895 121.811 333.637 122.055 333.447 122.368C333.257 122.677 333.162 123.03 333.162 123.426V129H331.385ZM341.415 129.184C340.515 129.184 339.741 128.992 339.091 128.608C338.445 128.22 337.946 127.675 337.593 126.974C337.245 126.268 337.07 125.442 337.07 124.496C337.07 123.561 337.245 122.736 337.593 122.023C337.946 121.31 338.437 120.754 339.067 120.354C339.701 119.953 340.442 119.753 341.29 119.753C341.805 119.753 342.304 119.838 342.787 120.009C343.271 120.179 343.704 120.447 344.089 120.811C344.473 121.176 344.776 121.649 344.998 122.231C345.22 122.81 345.331 123.513 345.331 124.341V124.971H338.075V123.64H343.59C343.59 123.172 343.494 122.758 343.304 122.398C343.114 122.033 342.847 121.746 342.502 121.536C342.161 121.326 341.761 121.221 341.302 121.221C340.802 121.221 340.367 121.344 339.994 121.59C339.626 121.831 339.341 122.148 339.138 122.54C338.94 122.929 338.841 123.351 338.841 123.806V124.846C338.841 125.456 338.948 125.975 339.162 126.403C339.38 126.831 339.683 127.158 340.071 127.384C340.46 127.605 340.913 127.716 341.432 127.716C341.769 127.716 342.076 127.669 342.353 127.574C342.631 127.475 342.87 127.328 343.072 127.134C343.275 126.94 343.429 126.7 343.536 126.415L345.218 126.718C345.083 127.213 344.841 127.647 344.493 128.019C344.148 128.388 343.714 128.675 343.191 128.881C342.672 129.083 342.08 129.184 341.415 129.184ZM351.147 129.184C350.264 129.184 349.503 128.984 348.865 128.584C348.231 128.18 347.744 127.623 347.403 126.914C347.062 126.205 346.892 125.393 346.892 124.478C346.892 123.551 347.066 122.733 347.415 122.023C347.764 121.31 348.255 120.754 348.889 120.354C349.523 119.953 350.269 119.753 351.129 119.753C351.822 119.753 352.441 119.882 352.983 120.14C353.526 120.393 353.964 120.75 354.297 121.209C354.633 121.669 354.833 122.206 354.897 122.82H353.167C353.072 122.392 352.855 122.023 352.514 121.714C352.177 121.405 351.725 121.251 351.159 121.251C350.664 121.251 350.23 121.382 349.857 121.643C349.489 121.901 349.202 122.269 348.996 122.748C348.79 123.224 348.687 123.786 348.687 124.436C348.687 125.102 348.788 125.676 348.99 126.159C349.192 126.643 349.477 127.017 349.846 127.283C350.218 127.548 350.656 127.681 351.159 127.681C351.496 127.681 351.801 127.619 352.074 127.497C352.351 127.37 352.583 127.189 352.769 126.956C352.96 126.722 353.092 126.441 353.167 126.112H354.897C354.833 126.702 354.641 127.229 354.32 127.693C353.999 128.156 353.57 128.521 353.031 128.786C352.496 129.052 351.868 129.184 351.147 129.184ZM360.731 129.184C359.832 129.184 359.057 128.992 358.407 128.608C357.762 128.22 357.262 127.675 356.91 126.974C356.561 126.268 356.387 125.442 356.387 124.496C356.387 123.561 356.561 122.736 356.91 122.023C357.262 121.31 357.754 120.754 358.384 120.354C359.017 119.953 359.758 119.753 360.606 119.753C361.121 119.753 361.62 119.838 362.104 120.009C362.587 120.179 363.021 120.447 363.405 120.811C363.789 121.176 364.092 121.649 364.314 122.231C364.536 122.81 364.647 123.513 364.647 124.341V124.971H357.391V123.64H362.906C362.906 123.172 362.811 122.758 362.621 122.398C362.431 122.033 362.163 121.746 361.818 121.536C361.478 121.326 361.078 121.221 360.618 121.221C360.119 121.221 359.683 121.344 359.311 121.59C358.942 121.831 358.657 122.148 358.455 122.54C358.257 122.929 358.158 123.351 358.158 123.806V124.846C358.158 125.456 358.265 125.975 358.479 126.403C358.697 126.831 359 127.158 359.388 127.384C359.776 127.605 360.23 127.716 360.749 127.716C361.086 127.716 361.393 127.669 361.67 127.574C361.947 127.475 362.187 127.328 362.389 127.134C362.591 126.94 362.745 126.7 362.852 126.415L364.534 126.718C364.4 127.213 364.158 127.647 363.809 128.019C363.465 128.388 363.031 128.675 362.508 128.881C361.989 129.083 361.397 129.184 360.731 129.184ZM366.619 129V119.872H368.395V129H366.619ZM367.516 118.464C367.207 118.464 366.941 118.361 366.72 118.155C366.502 117.945 366.393 117.695 366.393 117.406C366.393 117.113 366.502 116.863 366.72 116.657C366.941 116.447 367.207 116.342 367.516 116.342C367.825 116.342 368.088 116.447 368.306 116.657C368.528 116.863 368.639 117.113 368.639 117.406C368.639 117.695 368.528 117.945 368.306 118.155C368.088 118.361 367.825 118.464 367.516 118.464ZM378.594 119.872L375.284 129H373.383L370.067 119.872H371.974L374.286 126.896H374.381L376.687 119.872H378.594ZM383.888 129.184C382.988 129.184 382.214 128.992 381.564 128.608C380.918 128.22 380.419 127.675 380.067 126.974C379.718 126.268 379.544 125.442 379.544 124.496C379.544 123.561 379.718 122.736 380.067 122.023C380.419 121.31 380.911 120.754 381.54 120.354C382.174 119.953 382.915 119.753 383.763 119.753C384.278 119.753 384.777 119.838 385.261 120.009C385.744 120.179 386.178 120.447 386.562 120.811C386.946 121.176 387.249 121.649 387.471 122.231C387.693 122.81 387.804 123.513 387.804 124.341V124.971H380.548V123.64H386.063C386.063 123.172 385.968 122.758 385.778 122.398C385.587 122.033 385.32 121.746 384.975 121.536C384.635 121.326 384.234 121.221 383.775 121.221C383.276 121.221 382.84 121.344 382.468 121.59C382.099 121.831 381.814 122.148 381.612 122.54C381.414 122.929 381.315 123.351 381.315 123.806V124.846C381.315 125.456 381.422 125.975 381.636 126.403C381.853 126.831 382.157 127.158 382.545 127.384C382.933 127.605 383.387 127.716 383.906 127.716C384.242 127.716 384.549 127.669 384.827 127.574C385.104 127.475 385.344 127.328 385.546 127.134C385.748 126.94 385.902 126.7 386.009 126.415L387.691 126.718C387.556 127.213 387.315 127.647 386.966 128.019C386.621 128.388 386.188 128.675 385.665 128.881C385.146 129.083 384.553 129.184 383.888 129.184ZM398.138 129.184C397.239 129.184 396.464 128.992 395.815 128.608C395.169 128.22 394.67 127.675 394.317 126.974C393.968 126.268 393.794 125.442 393.794 124.496C393.794 123.561 393.968 122.736 394.317 122.023C394.67 121.31 395.161 120.754 395.791 120.354C396.425 119.953 397.166 119.753 398.013 119.753C398.528 119.753 399.028 119.838 399.511 120.009C399.994 120.179 400.428 120.447 400.812 120.811C401.197 121.176 401.5 121.649 401.722 122.231C401.943 122.81 402.054 123.513 402.054 124.341V124.971H394.798V123.64H400.313C400.313 123.172 400.218 122.758 400.028 122.398C399.838 122.033 399.57 121.746 399.226 121.536C398.885 121.326 398.485 121.221 398.025 121.221C397.526 121.221 397.09 121.344 396.718 121.59C396.349 121.831 396.064 122.148 395.862 122.54C395.664 122.929 395.565 123.351 395.565 123.806V124.846C395.565 125.456 395.672 125.975 395.886 126.403C396.104 126.831 396.407 127.158 396.795 127.384C397.183 127.605 397.637 127.716 398.156 127.716C398.493 127.716 398.8 127.669 399.077 127.574C399.354 127.475 399.594 127.328 399.796 127.134C399.998 126.94 400.153 126.7 400.26 126.415L401.941 126.718C401.807 127.213 401.565 127.647 401.216 128.019C400.872 128.388 400.438 128.675 399.915 128.881C399.396 129.083 398.804 129.184 398.138 129.184ZM405.216 119.872L407.23 123.426L409.263 119.872H411.206L408.359 124.436L411.23 129H409.286L407.23 125.589L405.18 129H403.231L406.072 124.436L403.267 119.872H405.216ZM413.03 132.423V119.872H414.766V121.352H414.914C415.017 121.162 415.166 120.942 415.36 120.692C415.554 120.443 415.823 120.225 416.168 120.039C416.513 119.848 416.968 119.753 417.535 119.753C418.272 119.753 418.929 119.94 419.508 120.312C420.086 120.684 420.54 121.221 420.869 121.922C421.201 122.624 421.368 123.467 421.368 124.454C421.368 125.44 421.203 126.286 420.875 126.991C420.546 127.693 420.094 128.233 419.52 128.614C418.945 128.99 418.29 129.178 417.553 129.178C416.998 129.178 416.544 129.085 416.192 128.899C415.843 128.713 415.57 128.495 415.372 128.245C415.174 127.996 415.021 127.774 414.914 127.58H414.807V132.423H413.03ZM414.772 124.436C414.772 125.078 414.865 125.64 415.051 126.124C415.237 126.607 415.506 126.985 415.859 127.259C416.212 127.528 416.643 127.663 417.154 127.663C417.685 127.663 418.129 127.522 418.486 127.241C418.842 126.956 419.112 126.569 419.294 126.082C419.48 125.595 419.573 125.046 419.573 124.436C419.573 123.834 419.482 123.293 419.3 122.814C419.121 122.334 418.852 121.956 418.492 121.679C418.135 121.401 417.689 121.263 417.154 121.263C416.639 121.263 416.204 121.395 415.847 121.661C415.495 121.926 415.227 122.297 415.045 122.772C414.863 123.248 414.772 123.802 414.772 124.436ZM427.293 129.184C426.393 129.184 425.619 128.992 424.969 128.608C424.323 128.22 423.824 127.675 423.471 126.974C423.123 126.268 422.949 125.442 422.949 124.496C422.949 123.561 423.123 122.736 423.471 122.023C423.824 121.31 424.315 120.754 424.945 120.354C425.579 119.953 426.32 119.753 427.168 119.753C427.683 119.753 428.182 119.838 428.665 120.009C429.149 120.179 429.582 120.447 429.967 120.811C430.351 121.176 430.654 121.649 430.876 122.231C431.098 122.81 431.209 123.513 431.209 124.341V124.971H423.953V123.64H429.468C429.468 123.172 429.373 122.758 429.182 122.398C428.992 122.033 428.725 121.746 428.38 121.536C428.039 121.326 427.639 121.221 427.18 121.221C426.681 121.221 426.245 121.344 425.872 121.59C425.504 121.831 425.219 122.148 425.017 122.54C424.818 122.929 424.719 123.351 424.719 123.806V124.846C424.719 125.456 424.826 125.975 425.04 126.403C425.258 126.831 425.561 127.158 425.95 127.384C426.338 127.605 426.791 127.716 427.31 127.716C427.647 127.716 427.954 127.669 428.232 127.574C428.509 127.475 428.749 127.328 428.951 127.134C429.153 126.94 429.307 126.7 429.414 126.415L431.096 126.718C430.961 127.213 430.719 127.647 430.371 128.019C430.026 128.388 429.592 128.675 429.069 128.881C428.55 129.083 427.958 129.184 427.293 129.184ZM433.18 129V119.872H434.898V121.322H434.993C435.159 120.831 435.452 120.445 435.872 120.163C436.296 119.878 436.775 119.735 437.31 119.735C437.421 119.735 437.552 119.739 437.703 119.747C437.857 119.755 437.978 119.765 438.065 119.777V121.477C437.994 121.457 437.867 121.435 437.685 121.411C437.502 121.384 437.32 121.37 437.138 121.37C436.718 121.37 436.344 121.459 436.015 121.637C435.69 121.811 435.432 122.055 435.242 122.368C435.052 122.677 434.957 123.03 434.957 123.426V129H433.18ZM444.403 119.872V121.298H439.417V119.872H444.403ZM440.754 117.685H442.531V126.32C442.531 126.665 442.582 126.924 442.685 127.098C442.788 127.269 442.921 127.386 443.084 127.449C443.25 127.508 443.43 127.538 443.624 127.538C443.767 127.538 443.892 127.528 443.999 127.508C444.106 127.489 444.189 127.473 444.248 127.461L444.569 128.929C444.466 128.968 444.32 129.008 444.129 129.048C443.939 129.091 443.702 129.115 443.416 129.119C442.949 129.127 442.513 129.044 442.109 128.869C441.705 128.695 441.378 128.426 441.128 128.061C440.879 127.697 440.754 127.239 440.754 126.688V117.685ZM450.797 129V119.872H452.574V129H450.797ZM451.694 118.464C451.385 118.464 451.12 118.361 450.898 118.155C450.68 117.945 450.571 117.695 450.571 117.406C450.571 117.113 450.68 116.863 450.898 116.657C451.12 116.447 451.385 116.342 451.694 116.342C452.003 116.342 452.267 116.447 452.485 116.657C452.707 116.863 452.818 117.113 452.818 117.406C452.818 117.695 452.707 117.945 452.485 118.155C452.267 118.361 452.003 118.464 451.694 118.464ZM456.741 123.58V129H454.964V119.872H456.67V121.358H456.783C456.993 120.874 457.322 120.486 457.769 120.193C458.221 119.9 458.789 119.753 459.475 119.753C460.097 119.753 460.641 119.884 461.109 120.146C461.576 120.403 461.939 120.787 462.196 121.298C462.454 121.809 462.583 122.441 462.583 123.194V129H460.806V123.408C460.806 122.746 460.634 122.229 460.289 121.857C459.944 121.481 459.471 121.292 458.869 121.292C458.457 121.292 458.09 121.382 457.769 121.56C457.452 121.738 457.201 122 457.014 122.344C456.832 122.685 456.741 123.097 456.741 123.58ZM471.806 122.101L470.195 122.386C470.128 122.18 470.021 121.984 469.874 121.798C469.732 121.611 469.538 121.459 469.292 121.34C469.046 121.221 468.739 121.162 468.371 121.162C467.868 121.162 467.448 121.275 467.111 121.5C466.774 121.722 466.606 122.01 466.606 122.362C466.606 122.667 466.719 122.913 466.945 123.099C467.17 123.285 467.535 123.438 468.038 123.557L469.488 123.889C470.328 124.083 470.954 124.383 471.366 124.787C471.778 125.191 471.984 125.716 471.984 126.361C471.984 126.908 471.825 127.395 471.509 127.823C471.196 128.247 470.758 128.58 470.195 128.822C469.637 129.063 468.989 129.184 468.252 129.184C467.23 129.184 466.396 128.966 465.75 128.531C465.104 128.091 464.708 127.467 464.562 126.659L466.279 126.397C466.386 126.845 466.606 127.184 466.939 127.413C467.271 127.639 467.705 127.752 468.24 127.752C468.822 127.752 469.288 127.631 469.637 127.39C469.985 127.144 470.16 126.845 470.16 126.492C470.16 126.207 470.053 125.967 469.839 125.773C469.629 125.579 469.306 125.432 468.87 125.333L467.325 124.995C466.473 124.801 465.843 124.492 465.435 124.068C465.031 123.644 464.829 123.107 464.829 122.457C464.829 121.918 464.98 121.447 465.281 121.043C465.582 120.639 465.998 120.324 466.529 120.098C467.059 119.868 467.668 119.753 468.353 119.753C469.339 119.753 470.116 119.967 470.682 120.395C471.249 120.819 471.623 121.388 471.806 122.101ZM473.938 129V119.872H475.714V129H473.938ZM474.835 118.464C474.526 118.464 474.26 118.361 474.039 118.155C473.821 117.945 473.712 117.695 473.712 117.406C473.712 117.113 473.821 116.863 474.039 116.657C474.26 116.447 474.526 116.342 474.835 116.342C475.144 116.342 475.407 116.447 475.625 116.657C475.847 116.863 475.958 117.113 475.958 117.406C475.958 117.695 475.847 117.945 475.625 118.155C475.407 118.361 475.144 118.464 474.835 118.464ZM481.932 132.613C481.207 132.613 480.583 132.518 480.06 132.328C479.541 132.138 479.117 131.886 478.788 131.573C478.459 131.26 478.214 130.917 478.051 130.545L479.579 129.915C479.686 130.089 479.828 130.274 480.006 130.468C480.189 130.666 480.434 130.834 480.743 130.973C481.056 131.112 481.458 131.181 481.95 131.181C482.623 131.181 483.18 131.017 483.62 130.688C484.059 130.363 484.279 129.844 484.279 129.131V127.336H484.166C484.059 127.53 483.905 127.746 483.703 127.984C483.505 128.222 483.231 128.428 482.883 128.602C482.534 128.776 482.08 128.863 481.522 128.863C480.801 128.863 480.151 128.695 479.573 128.358C478.998 128.017 478.543 127.516 478.206 126.855C477.873 126.189 477.707 125.371 477.707 124.4C477.707 123.43 477.871 122.598 478.2 121.905C478.533 121.211 478.988 120.68 479.567 120.312C480.145 119.94 480.801 119.753 481.534 119.753C482.1 119.753 482.558 119.848 482.906 120.039C483.255 120.225 483.526 120.443 483.721 120.692C483.919 120.942 484.071 121.162 484.178 121.352H484.309V119.872H486.05V129.202C486.05 129.986 485.868 130.63 485.503 131.133C485.139 131.637 484.646 132.009 484.024 132.251C483.406 132.492 482.708 132.613 481.932 132.613ZM481.914 127.39C482.425 127.39 482.857 127.271 483.21 127.033C483.566 126.791 483.835 126.447 484.018 125.999C484.204 125.547 484.297 125.007 484.297 124.377C484.297 123.763 484.206 123.222 484.024 122.754C483.841 122.287 483.574 121.922 483.221 121.661C482.869 121.395 482.433 121.263 481.914 121.263C481.379 121.263 480.933 121.401 480.577 121.679C480.22 121.952 479.951 122.324 479.769 122.796C479.59 123.267 479.501 123.794 479.501 124.377C479.501 124.975 479.592 125.5 479.775 125.951C479.957 126.403 480.226 126.756 480.583 127.009C480.943 127.263 481.387 127.39 481.914 127.39ZM490.21 123.58V129H488.433V116.83H490.186V121.358H490.299C490.513 120.867 490.84 120.476 491.28 120.187C491.719 119.898 492.294 119.753 493.003 119.753C493.629 119.753 494.176 119.882 494.643 120.14C495.115 120.397 495.479 120.781 495.737 121.292C495.998 121.8 496.129 122.433 496.129 123.194V129H494.352V123.408C494.352 122.738 494.18 122.219 493.835 121.851C493.49 121.479 493.011 121.292 492.397 121.292C491.977 121.292 491.6 121.382 491.268 121.56C490.939 121.738 490.679 122 490.489 122.344C490.303 122.685 490.21 123.097 490.21 123.58ZM502.761 119.872V121.298H497.775V119.872H502.761ZM499.112 117.685H500.889V126.32C500.889 126.665 500.94 126.924 501.043 127.098C501.146 127.269 501.279 127.386 501.441 127.449C501.608 127.508 501.788 127.538 501.982 127.538C502.125 127.538 502.25 127.528 502.357 127.508C502.464 127.489 502.547 127.473 502.606 127.461L502.927 128.929C502.824 128.968 502.677 129.008 502.487 129.048C502.297 129.091 502.059 129.115 501.774 129.119C501.307 129.127 500.871 129.044 500.467 128.869C500.063 128.695 499.736 128.426 499.486 128.061C499.237 127.697 499.112 127.239 499.112 126.688V117.685ZM511.419 122.101L509.809 122.386C509.741 122.18 509.634 121.984 509.488 121.798C509.345 121.611 509.151 121.459 508.905 121.34C508.66 121.221 508.353 121.162 507.984 121.162C507.481 121.162 507.061 121.275 506.724 121.5C506.388 121.722 506.219 122.01 506.219 122.362C506.219 122.667 506.332 122.913 506.558 123.099C506.784 123.285 507.148 123.438 507.651 123.557L509.101 123.889C509.941 124.083 510.567 124.383 510.979 124.787C511.391 125.191 511.597 125.716 511.597 126.361C511.597 126.908 511.439 127.395 511.122 127.823C510.809 128.247 510.371 128.58 509.809 128.822C509.25 129.063 508.602 129.184 507.865 129.184C506.843 129.184 506.009 128.966 505.364 128.531C504.718 128.091 504.322 127.467 504.175 126.659L505.892 126.397C505.999 126.845 506.219 127.184 506.552 127.413C506.885 127.639 507.319 127.752 507.853 127.752C508.436 127.752 508.901 127.631 509.25 127.39C509.599 127.144 509.773 126.845 509.773 126.492C509.773 126.207 509.666 125.967 509.452 125.773C509.242 125.579 508.919 125.432 508.483 125.333L506.938 124.995C506.087 124.801 505.457 124.492 505.049 124.068C504.644 123.644 504.442 123.107 504.442 122.457C504.442 121.918 504.593 121.447 504.894 121.043C505.195 120.639 505.611 120.324 506.142 120.098C506.673 119.868 507.281 119.753 507.966 119.753C508.953 119.753 509.729 119.967 510.296 120.395C510.862 120.819 511.237 121.388 511.419 122.101ZM522.324 119.872V121.298H517.166V119.872H522.324ZM518.58 129V118.814C518.58 118.244 518.705 117.77 518.954 117.394C519.204 117.014 519.535 116.731 519.947 116.544C520.359 116.354 520.806 116.259 521.29 116.259C521.646 116.259 521.951 116.289 522.205 116.348C522.458 116.404 522.647 116.455 522.769 116.503L522.353 117.941C522.27 117.917 522.163 117.889 522.033 117.858C521.902 117.822 521.743 117.804 521.557 117.804C521.125 117.804 520.816 117.911 520.63 118.125C520.448 118.339 520.357 118.648 520.357 119.052V129H518.58ZM524.157 129V119.872H525.874V121.322H525.97C526.136 120.831 526.429 120.445 526.849 120.163C527.273 119.878 527.752 119.735 528.287 119.735C528.398 119.735 528.529 119.739 528.679 119.747C528.834 119.755 528.955 119.765 529.042 119.777V121.477C528.971 121.457 528.844 121.435 528.662 121.411C528.479 121.384 528.297 121.37 528.115 121.37C527.695 121.37 527.32 121.459 526.992 121.637C526.667 121.811 526.409 122.055 526.219 122.368C526.029 122.677 525.934 123.03 525.934 123.426V129H524.157ZM534.098 129.184C533.242 129.184 532.495 128.988 531.857 128.596C531.219 128.204 530.724 127.655 530.372 126.95C530.019 126.245 529.843 125.421 529.843 124.478C529.843 123.531 530.019 122.703 530.372 121.994C530.724 121.285 531.219 120.734 531.857 120.342C532.495 119.949 533.242 119.753 534.098 119.753C534.953 119.753 535.7 119.949 536.338 120.342C536.976 120.734 537.471 121.285 537.824 121.994C538.176 122.703 538.352 123.531 538.352 124.478C538.352 125.421 538.176 126.245 537.824 126.95C537.471 127.655 536.976 128.204 536.338 128.596C535.7 128.988 534.953 129.184 534.098 129.184ZM534.103 127.693C534.658 127.693 535.118 127.546 535.482 127.253C535.847 126.96 536.116 126.569 536.29 126.082C536.469 125.595 536.558 125.058 536.558 124.472C536.558 123.889 536.469 123.355 536.29 122.867C536.116 122.376 535.847 121.982 535.482 121.685C535.118 121.388 534.658 121.239 534.103 121.239C533.545 121.239 533.081 121.388 532.713 121.685C532.348 121.982 532.077 122.376 531.899 122.867C531.724 123.355 531.637 123.889 531.637 124.472C531.637 125.058 531.724 125.595 531.899 126.082C532.077 126.569 532.348 126.96 532.713 127.253C533.081 127.546 533.545 127.693 534.103 127.693ZM540.336 129V119.872H542.041V121.358H542.154C542.344 120.855 542.655 120.462 543.087 120.181C543.519 119.896 544.036 119.753 544.638 119.753C545.248 119.753 545.759 119.896 546.171 120.181C546.587 120.466 546.894 120.859 547.093 121.358H547.188C547.405 120.871 547.752 120.482 548.228 120.193C548.703 119.9 549.269 119.753 549.927 119.753C550.755 119.753 551.431 120.013 551.954 120.532C552.48 121.051 552.744 121.833 552.744 122.879V129H550.967V123.046C550.967 122.427 550.799 121.98 550.462 121.702C550.125 121.425 549.723 121.286 549.256 121.286C548.677 121.286 548.228 121.465 547.907 121.821C547.586 122.174 547.425 122.628 547.425 123.182V129H545.654V122.933C545.654 122.437 545.5 122.039 545.191 121.738C544.882 121.437 544.48 121.286 543.985 121.286C543.648 121.286 543.337 121.376 543.052 121.554C542.77 121.728 542.542 121.972 542.368 122.285C542.198 122.598 542.113 122.96 542.113 123.372V129H540.336ZM563.399 129.184C562.543 129.184 561.796 128.988 561.159 128.596C560.521 128.204 560.026 127.655 559.673 126.95C559.32 126.245 559.144 125.421 559.144 124.478C559.144 123.531 559.32 122.703 559.673 121.994C560.026 121.285 560.521 120.734 561.159 120.342C561.796 119.949 562.543 119.753 563.399 119.753C564.255 119.753 565.002 119.949 565.639 120.342C566.277 120.734 566.772 121.285 567.125 121.994C567.478 122.703 567.654 123.531 567.654 124.478C567.654 125.421 567.478 126.245 567.125 126.95C566.772 127.655 566.277 128.204 565.639 128.596C565.002 128.988 564.255 129.184 563.399 129.184ZM563.405 127.693C563.96 127.693 564.419 127.546 564.784 127.253C565.148 126.96 565.418 126.569 565.592 126.082C565.77 125.595 565.859 125.058 565.859 124.472C565.859 123.889 565.77 123.355 565.592 122.867C565.418 122.376 565.148 121.982 564.784 121.685C564.419 121.388 563.96 121.239 563.405 121.239C562.846 121.239 562.383 121.388 562.014 121.685C561.65 121.982 561.379 122.376 561.2 122.867C561.026 123.355 560.939 123.889 560.939 124.472C560.939 125.058 561.026 125.595 561.2 126.082C561.379 126.569 561.65 126.96 562.014 127.253C562.383 127.546 562.846 127.693 563.405 127.693ZM575.419 125.215V119.872H577.202V129H575.455V127.419H575.36C575.15 127.907 574.813 128.313 574.35 128.638C573.89 128.958 573.318 129.119 572.632 129.119C572.046 129.119 571.527 128.99 571.075 128.733C570.628 128.471 570.275 128.085 570.018 127.574C569.764 127.063 569.637 126.431 569.637 125.678V119.872H571.414V125.464C571.414 126.086 571.586 126.581 571.931 126.95C572.276 127.318 572.723 127.502 573.274 127.502C573.607 127.502 573.938 127.419 574.267 127.253C574.599 127.086 574.875 126.835 575.093 126.498C575.314 126.161 575.423 125.734 575.419 125.215ZM579.59 129V119.872H581.307V121.322H581.402C581.569 120.831 581.862 120.445 582.282 120.163C582.706 119.878 583.185 119.735 583.72 119.735C583.831 119.735 583.961 119.739 584.112 119.747C584.266 119.755 584.387 119.765 584.474 119.777V121.477C584.403 121.457 584.276 121.435 584.094 121.411C583.912 121.384 583.73 121.37 583.547 121.37C583.127 121.37 582.753 121.459 582.424 121.637C582.099 121.811 581.842 122.055 581.652 122.368C581.462 122.677 581.367 123.03 581.367 123.426V129H579.59ZM590.441 132.423V119.872H592.176V121.352H592.325C592.428 121.162 592.576 120.942 592.77 120.692C592.964 120.443 593.234 120.225 593.579 120.039C593.923 119.848 594.379 119.753 594.945 119.753C595.682 119.753 596.34 119.94 596.918 120.312C597.497 120.684 597.95 121.221 598.279 121.922C598.612 122.624 598.778 123.467 598.778 124.454C598.778 125.44 598.614 126.286 598.285 126.991C597.956 127.693 597.505 128.233 596.93 128.614C596.356 128.99 595.7 129.178 594.963 129.178C594.409 129.178 593.955 129.085 593.602 128.899C593.254 128.713 592.98 128.495 592.782 128.245C592.584 127.996 592.432 127.774 592.325 127.58H592.218V132.423H590.441ZM592.182 124.436C592.182 125.078 592.275 125.64 592.461 126.124C592.648 126.607 592.917 126.985 593.27 127.259C593.622 127.528 594.054 127.663 594.565 127.663C595.096 127.663 595.54 127.522 595.896 127.241C596.253 126.956 596.522 126.569 596.704 126.082C596.891 125.595 596.984 125.046 596.984 124.436C596.984 123.834 596.893 123.293 596.71 122.814C596.532 122.334 596.263 121.956 595.902 121.679C595.546 121.401 595.1 121.263 594.565 121.263C594.05 121.263 593.614 121.395 593.258 121.661C592.905 121.926 592.638 122.297 592.455 122.772C592.273 123.248 592.182 123.802 592.182 124.436ZM600.769 129V119.872H602.487V121.322H602.582C602.748 120.831 603.041 120.445 603.461 120.163C603.885 119.878 604.364 119.735 604.899 119.735C605.01 119.735 605.141 119.739 605.291 119.747C605.446 119.755 605.567 119.765 605.654 119.777V121.477C605.583 121.457 605.456 121.435 605.274 121.411C605.091 121.384 604.909 121.37 604.727 121.37C604.307 121.37 603.933 121.459 603.604 121.637C603.279 121.811 603.021 122.055 602.831 122.368C602.641 122.677 602.546 123.03 602.546 123.426V129H600.769ZM610.71 129.184C609.854 129.184 609.107 128.988 608.469 128.596C607.831 128.204 607.336 127.655 606.984 126.95C606.631 126.245 606.455 125.421 606.455 124.478C606.455 123.531 606.631 122.703 606.984 121.994C607.336 121.285 607.831 120.734 608.469 120.342C609.107 119.949 609.854 119.753 610.71 119.753C611.565 119.753 612.312 119.949 612.95 120.342C613.588 120.734 614.083 121.285 614.436 121.994C614.788 122.703 614.964 123.531 614.964 124.478C614.964 125.421 614.788 126.245 614.436 126.95C614.083 127.655 613.588 128.204 612.95 128.596C612.312 128.988 611.565 129.184 610.71 129.184ZM610.716 127.693C611.27 127.693 611.73 127.546 612.094 127.253C612.459 126.96 612.728 126.569 612.902 126.082C613.081 125.595 613.17 125.058 613.17 124.472C613.17 123.889 613.081 123.355 612.902 122.867C612.728 122.376 612.459 121.982 612.094 121.685C611.73 121.388 611.27 121.239 610.716 121.239C610.157 121.239 609.693 121.388 609.325 121.685C608.96 121.982 608.689 122.376 608.511 122.867C608.337 123.355 608.249 123.889 608.249 124.472C608.249 125.058 608.337 125.595 608.511 126.082C608.689 126.569 608.96 126.96 609.325 127.253C609.693 127.546 610.157 127.693 610.716 127.693ZM620.775 132.613C620.05 132.613 619.426 132.518 618.903 132.328C618.384 132.138 617.96 131.886 617.631 131.573C617.302 131.26 617.057 130.917 616.894 130.545L618.422 129.915C618.529 130.089 618.671 130.274 618.849 130.468C619.032 130.666 619.277 130.834 619.586 130.973C619.899 131.112 620.301 131.181 620.793 131.181C621.466 131.181 622.023 131.017 622.463 130.688C622.902 130.363 623.122 129.844 623.122 129.131V127.336H623.009C622.902 127.53 622.748 127.746 622.546 127.984C622.348 128.222 622.074 128.428 621.726 128.602C621.377 128.776 620.923 128.863 620.365 128.863C619.644 128.863 618.994 128.695 618.416 128.358C617.841 128.017 617.386 127.516 617.049 126.855C616.716 126.189 616.55 125.371 616.55 124.4C616.55 123.43 616.714 122.598 617.043 121.905C617.376 121.211 617.831 120.68 618.41 120.312C618.988 119.94 619.644 119.753 620.377 119.753C620.943 119.753 621.401 119.848 621.749 120.039C622.098 120.225 622.369 120.443 622.564 120.692C622.762 120.942 622.914 121.162 623.021 121.352H623.152V119.872H624.893V129.202C624.893 129.986 624.711 130.63 624.346 131.133C623.982 131.637 623.489 132.009 622.867 132.251C622.249 132.492 621.551 132.613 620.775 132.613ZM620.757 127.39C621.268 127.39 621.7 127.271 622.053 127.033C622.409 126.791 622.678 126.447 622.861 125.999C623.047 125.547 623.14 125.007 623.14 124.377C623.14 123.763 623.049 123.222 622.867 122.754C622.684 122.287 622.417 121.922 622.064 121.661C621.712 121.395 621.276 121.263 620.757 121.263C620.222 121.263 619.777 121.401 619.42 121.679C619.063 121.952 618.794 122.324 618.612 122.796C618.433 123.267 618.344 123.794 618.344 124.377C618.344 124.975 618.435 125.5 618.618 125.951C618.8 126.403 619.069 126.756 619.426 127.009C619.786 127.263 620.23 127.39 620.757 127.39ZM627.276 129V119.872H628.993V121.322H629.089C629.255 120.831 629.548 120.445 629.968 120.163C630.392 119.878 630.871 119.735 631.406 119.735C631.517 119.735 631.648 119.739 631.798 119.747C631.953 119.755 632.074 119.765 632.161 119.777V121.477C632.09 121.457 631.963 121.435 631.781 121.411C631.598 121.384 631.416 121.37 631.234 121.37C630.814 121.37 630.44 121.459 630.111 121.637C629.786 121.811 629.528 122.055 629.338 122.368C629.148 122.677 629.053 123.03 629.053 123.426V129H627.276ZM636.273 129.202C635.695 129.202 635.172 129.095 634.704 128.881C634.237 128.663 633.866 128.348 633.593 127.936C633.324 127.524 633.189 127.019 633.189 126.421C633.189 125.906 633.288 125.482 633.486 125.149C633.684 124.816 633.952 124.553 634.288 124.359C634.625 124.165 635.001 124.018 635.417 123.919C635.833 123.82 636.257 123.745 636.689 123.693C637.236 123.63 637.68 123.578 638.02 123.539C638.361 123.495 638.609 123.426 638.763 123.331C638.918 123.236 638.995 123.081 638.995 122.867V122.826C638.995 122.307 638.848 121.905 638.555 121.619C638.266 121.334 637.834 121.191 637.26 121.191C636.661 121.191 636.19 121.324 635.845 121.59C635.505 121.851 635.269 122.142 635.138 122.463L633.468 122.083C633.666 121.528 633.956 121.08 634.336 120.74C634.72 120.395 635.162 120.146 635.661 119.991C636.16 119.833 636.685 119.753 637.236 119.753C637.6 119.753 637.987 119.797 638.395 119.884C638.807 119.967 639.191 120.122 639.548 120.348C639.908 120.573 640.203 120.896 640.433 121.316C640.663 121.732 640.778 122.273 640.778 122.939V129H639.042V127.752H638.971C638.856 127.982 638.684 128.208 638.454 128.43C638.224 128.651 637.929 128.836 637.569 128.982C637.208 129.129 636.776 129.202 636.273 129.202ZM636.659 127.776C637.151 127.776 637.571 127.679 637.919 127.485C638.272 127.291 638.539 127.037 638.722 126.724C638.908 126.407 639.001 126.068 639.001 125.708V124.531C638.937 124.595 638.815 124.654 638.632 124.709C638.454 124.761 638.25 124.807 638.02 124.846C637.791 124.882 637.567 124.915 637.349 124.947C637.131 124.975 636.949 124.999 636.802 125.018C636.457 125.062 636.142 125.135 635.857 125.238C635.576 125.341 635.35 125.49 635.18 125.684C635.013 125.874 634.93 126.128 634.93 126.445C634.93 126.884 635.093 127.217 635.417 127.443C635.742 127.665 636.156 127.776 636.659 127.776ZM643.144 129V119.872H644.85V121.358H644.963C645.153 120.855 645.464 120.462 645.896 120.181C646.328 119.896 646.845 119.753 647.447 119.753C648.057 119.753 648.568 119.896 648.98 120.181C649.396 120.466 649.703 120.859 649.901 121.358H649.996C650.214 120.871 650.561 120.482 651.036 120.193C651.512 119.9 652.078 119.753 652.736 119.753C653.564 119.753 654.239 120.013 654.762 120.532C655.289 121.051 655.552 121.833 655.552 122.879V129H653.776V123.046C653.776 122.427 653.607 121.98 653.271 121.702C652.934 121.425 652.532 121.286 652.064 121.286C651.486 121.286 651.036 121.465 650.715 121.821C650.394 122.174 650.234 122.628 650.234 123.182V129H648.463V122.933C648.463 122.437 648.308 122.039 647.999 121.738C647.69 121.437 647.288 121.286 646.793 121.286C646.456 121.286 646.145 121.376 645.86 121.554C645.579 121.728 645.351 121.972 645.177 122.285C645.006 122.598 644.921 122.96 644.921 123.372V129H643.144ZM666.624 119.872V121.298H661.638V119.872H666.624ZM662.975 117.685H664.752V126.32C664.752 126.665 664.803 126.924 664.906 127.098C665.009 127.269 665.142 127.386 665.304 127.449C665.471 127.508 665.651 127.538 665.845 127.538C665.988 127.538 666.112 127.528 666.219 127.508C666.326 127.489 666.41 127.473 666.469 127.461L666.79 128.929C666.687 128.968 666.54 129.008 666.35 129.048C666.16 129.091 665.922 129.115 665.637 129.119C665.17 129.127 664.734 129.044 664.33 128.869C663.926 128.695 663.599 128.426 663.349 128.061C663.1 127.697 662.975 127.239 662.975 126.688V117.685ZM672.425 129.184C671.526 129.184 670.751 128.992 670.101 128.608C669.456 128.22 668.957 127.675 668.604 126.974C668.255 126.268 668.081 125.442 668.081 124.496C668.081 123.561 668.255 122.736 668.604 122.023C668.957 121.31 669.448 120.754 670.078 120.354C670.712 119.953 671.452 119.753 672.3 119.753C672.815 119.753 673.314 119.838 673.798 120.009C674.281 120.179 674.715 120.447 675.099 120.811C675.483 121.176 675.787 121.649 676.008 122.231C676.23 122.81 676.341 123.513 676.341 124.341V124.971H669.085V123.64H674.6C674.6 123.172 674.505 122.758 674.315 122.398C674.125 122.033 673.857 121.746 673.513 121.536C673.172 121.326 672.772 121.221 672.312 121.221C671.813 121.221 671.377 121.344 671.005 121.59C670.636 121.831 670.351 122.148 670.149 122.54C669.951 122.929 669.852 123.351 669.852 123.806V124.846C669.852 125.456 669.959 125.975 670.173 126.403C670.391 126.831 670.694 127.158 671.082 127.384C671.47 127.605 671.924 127.716 672.443 127.716C672.78 127.716 673.087 127.669 673.364 127.574C673.641 127.475 673.881 127.328 674.083 127.134C674.285 126.94 674.44 126.7 674.547 126.415L676.228 126.718C676.094 127.213 675.852 127.647 675.503 128.019C675.159 128.388 674.725 128.675 674.202 128.881C673.683 129.083 673.091 129.184 672.425 129.184ZM680.969 129.202C680.391 129.202 679.868 129.095 679.4 128.881C678.933 128.663 678.562 128.348 678.289 127.936C678.019 127.524 677.885 127.019 677.885 126.421C677.885 125.906 677.984 125.482 678.182 125.149C678.38 124.816 678.647 124.553 678.984 124.359C679.321 124.165 679.697 124.018 680.113 123.919C680.529 123.82 680.953 123.745 681.385 123.693C681.932 123.63 682.375 123.578 682.716 123.539C683.057 123.495 683.304 123.426 683.459 123.331C683.613 123.236 683.691 123.081 683.691 122.867V122.826C683.691 122.307 683.544 121.905 683.251 121.619C682.962 121.334 682.53 121.191 681.955 121.191C681.357 121.191 680.886 121.324 680.541 121.59C680.2 121.851 679.965 122.142 679.834 122.463L678.164 122.083C678.362 121.528 678.651 121.08 679.032 120.74C679.416 120.395 679.858 120.146 680.357 119.991C680.856 119.833 681.381 119.753 681.932 119.753C682.296 119.753 682.682 119.797 683.09 119.884C683.503 119.967 683.887 120.122 684.243 120.348C684.604 120.573 684.899 120.896 685.129 121.316C685.359 121.732 685.473 122.273 685.473 122.939V129H683.738V127.752H683.667C683.552 127.982 683.38 128.208 683.15 128.43C682.92 128.651 682.625 128.836 682.264 128.982C681.904 129.129 681.472 129.202 680.969 129.202ZM681.355 127.776C681.846 127.776 682.266 127.679 682.615 127.485C682.968 127.291 683.235 127.037 683.417 126.724C683.604 126.407 683.697 126.068 683.697 125.708V124.531C683.633 124.595 683.51 124.654 683.328 124.709C683.15 124.761 682.946 124.807 682.716 124.846C682.486 124.882 682.262 124.915 682.045 124.947C681.827 124.975 681.644 124.999 681.498 125.018C681.153 125.062 680.838 125.135 680.553 125.238C680.272 125.341 680.046 125.49 679.876 125.684C679.709 125.874 679.626 126.128 679.626 126.445C679.626 126.884 679.788 127.217 680.113 127.443C680.438 127.665 680.852 127.776 681.355 127.776ZM687.84 129V119.872H689.546V121.358H689.659C689.849 120.855 690.16 120.462 690.592 120.181C691.023 119.896 691.54 119.753 692.143 119.753C692.753 119.753 693.264 119.896 693.676 120.181C694.092 120.466 694.399 120.859 694.597 121.358H694.692C694.91 120.871 695.257 120.482 695.732 120.193C696.207 119.9 696.774 119.753 697.432 119.753C698.26 119.753 698.935 120.013 699.458 120.532C699.985 121.051 700.248 121.833 700.248 122.879V129H698.471V123.046C698.471 122.427 698.303 121.98 697.966 121.702C697.63 121.425 697.227 121.286 696.76 121.286C696.182 121.286 695.732 121.465 695.411 121.821C695.09 122.174 694.93 122.628 694.93 123.182V129H693.159V122.933C693.159 122.437 693.004 122.039 692.695 121.738C692.386 121.437 691.984 121.286 691.489 121.286C691.152 121.286 690.841 121.376 690.556 121.554C690.275 121.728 690.047 121.972 689.873 122.285C689.702 122.598 689.617 122.96 689.617 123.372V129H687.84ZM704.87 116.83L704.716 125.5H703.07L702.915 116.83H704.87ZM703.896 129.113C703.567 129.113 703.285 128.998 703.052 128.768C702.818 128.534 702.703 128.253 702.707 127.924C702.703 127.6 702.818 127.322 703.052 127.092C703.285 126.859 703.567 126.742 703.896 126.742C704.216 126.742 704.494 126.859 704.728 127.092C704.961 127.322 705.08 127.6 705.084 127.924C705.08 128.142 705.023 128.342 704.912 128.525C704.805 128.703 704.662 128.845 704.484 128.952C704.306 129.059 704.109 129.113 703.896 129.113Z" fill="#F5F5F5"/>
            <rect x="1111" y="87" width="200" height="52" rx="8" fill="white"/>
            <path d="M1154.5 110.718C1154.39 110.359 1154.23 110.037 1154.04 109.753C1153.85 109.464 1153.62 109.218 1153.35 109.014C1153.08 108.809 1152.77 108.656 1152.43 108.554C1152.08 108.448 1151.7 108.394 1151.29 108.394C1150.56 108.394 1149.91 108.579 1149.34 108.947C1148.76 109.316 1148.31 109.857 1147.99 110.572C1147.66 111.282 1147.5 112.148 1147.5 113.169C1147.5 114.198 1147.66 115.071 1147.99 115.785C1148.31 116.5 1148.76 117.044 1149.34 117.417C1149.91 117.785 1150.58 117.969 1151.35 117.969C1152.04 117.969 1152.64 117.836 1153.15 117.57C1153.66 117.303 1154.05 116.926 1154.32 116.438C1154.6 115.945 1154.74 115.368 1154.74 114.707L1155.3 114.793H1151.59V112.862H1157.13V114.5C1157.13 115.668 1156.88 116.677 1156.38 117.53C1155.88 118.382 1155.2 119.039 1154.33 119.501C1153.46 119.958 1152.46 120.186 1151.33 120.186C1150.08 120.186 1148.98 119.905 1148.03 119.341C1147.08 118.773 1146.34 117.967 1145.81 116.924C1145.28 115.876 1145.02 114.633 1145.02 113.195C1145.02 112.094 1145.17 111.111 1145.48 110.245C1145.8 109.38 1146.24 108.645 1146.8 108.042C1147.36 107.433 1148.03 106.972 1148.78 106.657C1149.54 106.337 1150.37 106.177 1151.26 106.177C1152.02 106.177 1152.72 106.288 1153.37 106.51C1154.02 106.728 1154.6 107.038 1155.11 107.442C1155.62 107.846 1156.04 108.326 1156.37 108.881C1156.7 109.435 1156.91 110.048 1157.01 110.718H1154.5ZM1163.94 120.2C1162.91 120.2 1162.03 119.987 1161.28 119.561C1160.54 119.13 1159.97 118.522 1159.57 117.736C1159.17 116.946 1158.97 116.016 1158.97 114.946C1158.97 113.894 1159.17 112.971 1159.57 112.176C1159.97 111.377 1160.54 110.756 1161.26 110.312C1161.98 109.864 1162.83 109.64 1163.81 109.64C1164.44 109.64 1165.04 109.742 1165.6 109.946C1166.16 110.146 1166.66 110.456 1167.09 110.878C1167.52 111.3 1167.86 111.837 1168.11 112.489C1168.36 113.137 1168.48 113.91 1168.48 114.806V115.546H1160.1V113.921H1166.17C1166.17 113.459 1166.07 113.049 1165.87 112.689C1165.68 112.325 1165.41 112.039 1165.06 111.83C1164.71 111.622 1164.31 111.517 1163.84 111.517C1163.35 111.517 1162.92 111.637 1162.55 111.877C1162.17 112.112 1161.88 112.423 1161.67 112.809C1161.47 113.191 1161.36 113.61 1161.36 114.067V115.486C1161.36 116.08 1161.47 116.591 1161.69 117.017C1161.9 117.439 1162.21 117.763 1162.6 117.989C1162.99 118.211 1163.45 118.322 1163.97 118.322C1164.32 118.322 1164.64 118.273 1164.92 118.176C1165.21 118.074 1165.45 117.925 1165.66 117.729C1165.87 117.534 1166.03 117.292 1166.13 117.004L1168.38 117.257C1168.24 117.852 1167.97 118.371 1167.57 118.815C1167.18 119.254 1166.67 119.596 1166.05 119.84C1165.44 120.08 1164.73 120.2 1163.94 120.2ZM1175.63 109.773V111.637H1169.75V109.773H1175.63ZM1171.2 107.322H1173.61V116.924C1173.61 117.248 1173.66 117.496 1173.76 117.67C1173.86 117.838 1174 117.954 1174.16 118.016C1174.32 118.078 1174.51 118.109 1174.71 118.109C1174.86 118.109 1174.99 118.098 1175.12 118.076C1175.25 118.054 1175.34 118.034 1175.41 118.016L1175.82 119.9C1175.69 119.945 1175.5 119.993 1175.26 120.047C1175.03 120.1 1174.74 120.131 1174.4 120.14C1173.8 120.158 1173.25 120.067 1172.77 119.867C1172.28 119.663 1171.9 119.347 1171.62 118.921C1171.34 118.495 1171.2 117.963 1171.2 117.323V107.322ZM1182.3 120V109.773H1184.71V120H1182.3ZM1183.51 108.321C1183.13 108.321 1182.8 108.195 1182.52 107.942C1182.25 107.684 1182.11 107.376 1182.11 107.016C1182.11 106.652 1182.25 106.344 1182.52 106.091C1182.8 105.833 1183.13 105.704 1183.51 105.704C1183.9 105.704 1184.22 105.833 1184.49 106.091C1184.77 106.344 1184.91 106.652 1184.91 107.016C1184.91 107.376 1184.77 107.684 1184.49 107.942C1184.22 108.195 1183.9 108.321 1183.51 108.321ZM1189.6 114.007V120H1187.19V109.773H1189.49V111.511H1189.61C1189.85 110.938 1190.22 110.483 1190.74 110.146C1191.25 109.808 1191.9 109.64 1192.66 109.64C1193.37 109.64 1193.98 109.79 1194.5 110.092C1195.03 110.394 1195.44 110.831 1195.73 111.404C1196.02 111.977 1196.17 112.671 1196.16 113.488V120H1193.75V113.861C1193.75 113.177 1193.57 112.642 1193.22 112.256C1192.87 111.87 1192.38 111.677 1191.76 111.677C1191.34 111.677 1190.96 111.77 1190.64 111.957C1190.31 112.139 1190.06 112.403 1189.87 112.749C1189.69 113.095 1189.6 113.515 1189.6 114.007ZM1208.37 109.773V111.637H1202.49V109.773H1208.37ZM1203.94 107.322H1206.35V116.924C1206.35 117.248 1206.4 117.496 1206.5 117.67C1206.6 117.838 1206.73 117.954 1206.9 118.016C1207.06 118.078 1207.24 118.109 1207.44 118.109C1207.6 118.109 1207.73 118.098 1207.86 118.076C1207.99 118.054 1208.08 118.034 1208.15 118.016L1208.56 119.9C1208.43 119.945 1208.24 119.993 1208 120.047C1207.77 120.1 1207.48 120.131 1207.14 120.14C1206.53 120.158 1205.99 120.067 1205.51 119.867C1205.02 119.663 1204.64 119.347 1204.36 118.921C1204.08 118.495 1203.94 117.963 1203.94 117.323V107.322ZM1214.74 120.2C1213.74 120.2 1212.87 119.98 1212.14 119.541C1211.41 119.101 1210.84 118.486 1210.44 117.696C1210.04 116.906 1209.84 115.983 1209.84 114.926C1209.84 113.87 1210.04 112.944 1210.44 112.15C1210.84 111.355 1211.41 110.738 1212.14 110.299C1212.87 109.859 1213.74 109.64 1214.74 109.64C1215.74 109.64 1216.6 109.859 1217.33 110.299C1218.07 110.738 1218.63 111.355 1219.03 112.15C1219.44 112.944 1219.64 113.87 1219.64 114.926C1219.64 115.983 1219.44 116.906 1219.03 117.696C1218.63 118.486 1218.07 119.101 1217.33 119.541C1216.6 119.98 1215.74 120.2 1214.74 120.2ZM1214.75 118.269C1215.29 118.269 1215.74 118.12 1216.11 117.823C1216.47 117.521 1216.74 117.117 1216.92 116.611C1217.1 116.105 1217.19 115.541 1217.19 114.92C1217.19 114.294 1217.1 113.728 1216.92 113.222C1216.74 112.711 1216.47 112.305 1216.11 112.003C1215.74 111.701 1215.29 111.551 1214.75 111.551C1214.2 111.551 1213.73 111.701 1213.37 112.003C1213 112.305 1212.73 112.711 1212.55 113.222C1212.37 113.728 1212.28 114.294 1212.28 114.92C1212.28 115.541 1212.37 116.105 1212.55 116.611C1212.73 117.117 1213 117.521 1213.37 117.823C1213.73 118.12 1214.2 118.269 1214.75 118.269ZM1228.2 115.699V109.773H1230.61V120H1228.28V118.182H1228.17C1227.94 118.755 1227.56 119.223 1227.03 119.587C1226.51 119.951 1225.86 120.133 1225.09 120.133C1224.42 120.133 1223.83 119.984 1223.31 119.687C1222.8 119.385 1222.4 118.948 1222.12 118.375C1221.83 117.798 1221.68 117.101 1221.68 116.285V109.773H1224.09V115.912C1224.09 116.56 1224.27 117.075 1224.63 117.456C1224.98 117.838 1225.45 118.029 1226.02 118.029C1226.38 118.029 1226.72 117.943 1227.06 117.769C1227.39 117.596 1227.66 117.339 1227.88 116.997C1228.09 116.651 1228.2 116.218 1228.2 115.699ZM1237.55 120.2C1236.53 120.2 1235.65 119.976 1234.92 119.527C1234.19 119.079 1233.63 118.46 1233.24 117.67C1232.85 116.875 1232.65 115.961 1232.65 114.926C1232.65 113.888 1232.85 112.971 1233.25 112.176C1233.65 111.377 1234.21 110.756 1234.94 110.312C1235.67 109.864 1236.54 109.64 1237.54 109.64C1238.37 109.64 1239.1 109.793 1239.74 110.099C1240.39 110.401 1240.9 110.829 1241.28 111.384C1241.66 111.934 1241.88 112.578 1241.93 113.315H1239.63C1239.54 112.822 1239.31 112.412 1238.96 112.083C1238.62 111.75 1238.15 111.584 1237.57 111.584C1237.08 111.584 1236.65 111.717 1236.27 111.983C1235.9 112.245 1235.61 112.623 1235.4 113.115C1235.2 113.608 1235.1 114.198 1235.1 114.886C1235.1 115.583 1235.2 116.183 1235.4 116.684C1235.61 117.181 1235.89 117.565 1236.26 117.836C1236.63 118.102 1237.07 118.236 1237.57 118.236C1237.93 118.236 1238.24 118.169 1238.52 118.036C1238.81 117.898 1239.05 117.701 1239.24 117.443C1239.43 117.186 1239.56 116.873 1239.63 116.504H1241.93C1241.88 117.228 1241.66 117.869 1241.29 118.429C1240.93 118.983 1240.42 119.419 1239.79 119.734C1239.15 120.044 1238.41 120.2 1237.55 120.2ZM1246.32 114.007V120H1243.91V106.364H1246.27V111.511H1246.39C1246.63 110.934 1247 110.479 1247.5 110.146C1248.01 109.808 1248.65 109.64 1249.43 109.64C1250.14 109.64 1250.76 109.788 1251.29 110.086C1251.82 110.383 1252.23 110.818 1252.52 111.391C1252.81 111.963 1252.95 112.662 1252.95 113.488V120H1250.54V113.861C1250.54 113.173 1250.37 112.638 1250.01 112.256C1249.66 111.87 1249.17 111.677 1248.53 111.677C1248.11 111.677 1247.73 111.77 1247.39 111.957C1247.06 112.139 1246.79 112.403 1246.6 112.749C1246.42 113.095 1246.32 113.515 1246.32 114.007Z" fill="#3B82F6"/>
            <path d="M1269.79 113L1264.82 108.039C1264.46 107.672 1264.46 107.078 1264.82 106.715C1265.19 106.352 1265.78 106.352 1266.15 106.715L1271.78 112.336C1272.13 112.691 1272.14 113.262 1271.8 113.629L1266.16 119.289C1265.97 119.473 1265.73 119.562 1265.49 119.562C1265.25 119.562 1265.01 119.473 1264.83 119.289C1264.46 118.922 1264.46 118.328 1264.83 117.965L1269.79 113Z" fill="#3B82F6"/>
            <defs>
            <clipPath id="clip0_1_297">
            <rect width="1360" height="210" fill="white"/>
            </clipPath>
            </defs>
            </svg>
            
    </section>


    <section class="fifth-page" id="fifth-page">
        <div class="first_header">
           
                <img src="whitelogo.png" alt="" class="fp_logo">
           

          
            <button class="bluebutton">Schedule 1-on-1 Call Now</button>
            <h3>Speak with our Learning Advisor</h3>
           
            
         </div>
         <div class="secound_body">
            <section class="programs">
                <h1>Programs</h1>

                <ul>
                    <li>Data Science & AI <svg width="14" height="15" viewBox="0 0 14 15" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M14 8.58997H8V14.59H6V8.58997H0V6.58997H6V0.589966H8V6.58997H14V8.58997Z" fill="white"/>
                        </svg>
                        </li>
                    <li>Product Management <svg width="14" height="15" viewBox="0 0 14 15" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M14 8.58997H8V14.59H6V8.58997H0V6.58997H6V0.589966H8V6.58997H14V8.58997Z" fill="white"/>
                        </svg>
                        </li>
                    <li>Business Analytics <svg width="14" height="15" viewBox="0 0 14 15" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M14 8.58997H8V14.59H6V8.58997H0V6.58997H6V0.589966H8V6.58997H14V8.58997Z" fill="white"/>
                        </svg>
                        </li>
                    <li>Digital Transformation <svg width="14" height="15" viewBox="0 0 14 15" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M14 8.58997H8V14.59H6V8.58997H0V6.58997H6V0.589966H8V6.58997H14V8.58997Z" fill="white"/>
                        </svg>
                        </li>
                    <li>Business Management <svg width="14" height="15" viewBox="0 0 14 15" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M14 8.58997H8V14.59H6V8.58997H0V6.58997H6V0.589966H8V6.58997H14V8.58997Z" fill="white"/>
                        </svg>
                        </li>
                    <li>Project Management <svg width="14" height="15" viewBox="0 0 14 15" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M14 8.58997H8V14.59H6V8.58997H0V6.58997H6V0.589966H8V6.58997H14V8.58997Z" fill="white"/>
                        </svg>
                        </li>
                    <li>Strategy & Leadership <svg width="14" height="15" viewBox="0 0 14 15" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M14 8.58997H8V14.59H6V8.58997H0V6.58997H6V0.589966H8V6.58997H14V8.58997Z" fill="white"/>
                        </svg>
                        </li>
                    <li>Senior Management <svg width="14" height="15" viewBox="0 0 14 15" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M14 8.58997H8V14.59H6V8.58997H0V6.58997H6V0.589966H8V6.58997H14V8.58997Z" fill="white"/>
                        </svg>
                        </li>
                    <li>Fintech <svg width="14" height="15" viewBox="0 0 14 15" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M14 8.58997H8V14.59H6V8.58997H0V6.58997H6V0.589966H8V6.58997H14V8.58997Z" fill="white"/>
                        </svg>
                        </li>

                </ul>

            </section>



            <section class="contactus">
                <h1>Contact Us</h1>
                <p>Email us (For Data Science Queries): admissions@accredian.com<br>
                    Email us (For Product Management Queries):pm@accredian.com<br>
                    Data Science Admission Helpline:+91 9079653292 (9 AM - 7 PM)<br>
                    Product Management Admission Helpline:+91 9625811095<br>
                    Enrolled Student Helpline: +91 7969322507<br>
                    Office Address: 4th Floor, 250, Phase IV, Udyog Vihar, Sector 18, Gurugram,<br>
                    Haryana 122015<br>
                    Why Accredian<br>
                    Follow Us<br>
                    <svg width="28" height="28" viewBox="0 0 28 28" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M5.66458 3.81885H21.5254C22.1263 3.81885 22.7027 4.05757 23.1276 4.48249C23.5525 4.90742 23.7912 5.48374 23.7912 6.08468V21.9455C23.7912 22.5465 23.5525 23.1228 23.1276 23.5477C22.7027 23.9726 22.1263 24.2113 21.5254 24.2113H5.66458C5.06364 24.2113 4.48732 23.9726 4.06239 23.5477C3.63746 23.1228 3.39874 22.5465 3.39874 21.9455V6.08468C3.39874 5.48374 3.63746 4.90742 4.06239 4.48249C4.48732 4.05757 5.06364 3.81885 5.66458 3.81885ZM20.3925 6.08468H17.5602C16.5086 6.08468 15.5 6.50244 14.7564 7.24606C14.0128 7.98968 13.595 8.99825 13.595 10.0499V12.8822H11.3292V16.2809H13.595V24.2113H16.9937V16.2809H20.3925V12.8822H16.9937V10.6163C16.9937 10.3159 17.1131 10.0277 17.3256 9.81526C17.538 9.60279 17.8262 9.48343 18.1267 9.48343H20.3925V6.08468Z" fill="white"/>
                        </svg>
                        <svg width="44" height="28" viewBox="0 0 44 28" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M37.7154 3.81885C38.3164 3.81885 38.8927 4.05757 39.3176 4.48249C39.7425 4.90742 39.9813 5.48374 39.9813 6.08468V21.9455C39.9813 22.5465 39.7425 23.1228 39.3176 23.5477C38.8927 23.9726 38.3164 24.2113 37.7154 24.2113H21.8546C21.2536 24.2113 20.6773 23.9726 20.2524 23.5477C19.8275 23.1228 19.5888 22.5465 19.5888 21.9455V6.08468C19.5888 5.48374 19.8275 4.90742 20.2524 4.48249C20.6773 4.05757 21.2536 3.81885 21.8546 3.81885H37.7154ZM37.149 21.3791V15.3746C37.149 14.3951 36.7598 13.4557 36.0672 12.763C35.3746 12.0704 34.4352 11.6813 33.4557 11.6813C32.4927 11.6813 31.3711 12.2704 30.8273 13.1541V11.8965H27.6664V21.3791H30.8273V15.7938C30.8273 14.9214 31.5297 14.2077 32.402 14.2077C32.8227 14.2077 33.2261 14.3748 33.5236 14.6722C33.821 14.9697 33.9881 15.3731 33.9881 15.7938V21.3791H37.149ZM23.9845 10.1179C24.4893 10.1179 24.9734 9.91734 25.3303 9.5604C25.6872 9.20346 25.8878 8.71935 25.8878 8.21456C25.8878 7.16095 25.0381 6.29994 23.9845 6.29994C23.4767 6.29994 22.9897 6.50165 22.6306 6.86072C22.2716 7.21978 22.0698 7.70677 22.0698 8.21456C22.0698 9.26818 22.9309 10.1179 23.9845 10.1179ZM25.5592 21.3791V11.8965H22.421V21.3791H25.5592Z" fill="white"/>
                            </svg>
                            <svg width="50" height="28" viewBox="0 0 50 28" fill="none" xmlns="http://www.w3.org/2000/svg">
                                <g clip-path="url(#clip0_1_216)">
                                <path d="M47.3853 7.21749C46.513 7.61401 45.5726 7.87459 44.5983 7.99921C45.5953 7.39876 46.3657 6.44711 46.7282 5.30286C45.7879 5.86932 44.7456 6.26584 43.6467 6.49243C42.7517 5.51812 41.4941 4.95166 40.0667 4.95166C37.4043 4.95166 35.2291 7.12686 35.2291 9.81187C35.2291 10.1971 35.2744 10.5709 35.3537 10.9221C31.3205 10.7182 27.7292 8.78092 25.3387 5.84666C24.9196 6.5604 24.6817 7.39876 24.6817 8.28244C24.6817 9.97048 25.5313 11.4659 26.8455 12.3156C26.0412 12.3156 25.2934 12.089 24.6363 11.7492V11.7831C24.6363 14.1396 26.3131 16.1109 28.5336 16.5527C27.8207 16.7478 27.0722 16.775 26.347 16.632C26.6547 17.5978 27.2574 18.4429 28.0702 19.0485C28.8831 19.654 29.8653 19.9896 30.8787 20.0081C29.1608 21.3681 27.0313 22.1032 24.8403 22.0927C24.4551 22.0927 24.0699 22.07 23.6847 22.0247C25.8372 23.4069 28.3976 24.2112 31.1393 24.2112C40.0667 24.2112 44.9722 16.802 44.9722 10.3783C44.9722 10.1631 44.9722 9.95915 44.9609 9.7439C45.9125 9.06415 46.7282 8.20313 47.3853 7.21749Z" fill="white"/>
                                </g>
                                <defs>
                                <clipPath id="clip0_1_216">
                                <rect width="27.19" height="27.19" fill="white" transform="translate(21.94 0.420044)"/>
                                </clipPath>
                                </defs>
                                </svg>
                    
                                <svg width="44" height="28" viewBox="0 0 44 28" fill="none" xmlns="http://www.w3.org/2000/svg">
                                    <path d="M24.9665 2.68567H34.483C38.1084 2.68567 41.054 5.63125 41.054 9.25659V18.7731C41.054 20.5158 40.3617 22.1871 39.1294 23.4194C37.8971 24.6517 36.2258 25.344 34.483 25.344H24.9665C21.3412 25.344 18.3956 22.3984 18.3956 18.7731V9.25659C18.3956 7.51387 19.0879 5.84253 20.3202 4.61025C21.5525 3.37796 23.2238 2.68567 24.9665 2.68567ZM24.74 4.9515C23.6583 4.9515 22.6209 5.3812 21.856 6.14607C21.0912 6.91093 20.6615 7.94832 20.6615 9.03V18.9997C20.6615 21.2542 22.4855 23.0782 24.74 23.0782H34.7096C35.7913 23.0782 36.8287 22.6485 37.5936 21.8836C38.3584 21.1187 38.7881 20.0814 38.7881 18.9997V9.03C38.7881 6.7755 36.9641 4.9515 34.7096 4.9515H24.74ZM35.6726 6.65088C36.0482 6.65088 36.4084 6.80008 36.674 7.06566C36.9395 7.33124 37.0887 7.69144 37.0887 8.06702C37.0887 8.44261 36.9395 8.80281 36.674 9.06839C36.4084 9.33397 36.0482 9.48317 35.6726 9.48317C35.297 9.48317 34.9368 9.33397 34.6712 9.06839C34.4057 8.80281 34.2565 8.44261 34.2565 8.06702C34.2565 7.69144 34.4057 7.33124 34.6712 7.06566C34.9368 6.80008 35.297 6.65088 35.6726 6.65088ZM29.7248 8.35025C31.2271 8.35025 32.6679 8.94705 33.7303 10.0094C34.7926 11.0717 35.3894 12.5125 35.3894 14.0148C35.3894 15.5172 34.7926 16.958 33.7303 18.0203C32.6679 19.0826 31.2271 19.6794 29.7248 19.6794C28.2224 19.6794 26.7816 19.0826 25.7193 18.0203C24.657 16.958 24.0602 15.5172 24.0602 14.0148C24.0602 12.5125 24.657 11.0717 25.7193 10.0094C26.7816 8.94705 28.2224 8.35025 29.7248 8.35025ZM29.7248 10.6161C28.8234 10.6161 27.9589 10.9742 27.3215 11.6116C26.6841 12.2489 26.326 13.1134 26.326 14.0148C26.326 14.9162 26.6841 15.7807 27.3215 16.4181C27.9589 17.0555 28.8234 17.4136 29.7248 17.4136C30.6262 17.4136 31.4907 17.0555 32.1281 16.4181C32.7655 15.7807 33.1235 14.9162 33.1235 14.0148C33.1235 13.1134 32.7655 12.2489 32.1281 11.6116C31.4907 10.9742 30.6262 10.6161 29.7248 10.6161Z" fill="white"/>
                                    </svg>
                     
                                    <svg width="44" height="28" viewBox="0 0 44 28" fill="none" xmlns="http://www.w3.org/2000/svg">
                                        <path d="M27.6392 17.4138L33.519 14.015L27.6392 10.6163V17.4138ZM40.7357 8.54302C40.883 9.07549 40.9849 9.78923 41.0529 10.6956C41.1322 11.6019 41.1662 12.3836 41.1662 13.0634L41.2342 14.015C41.2342 16.4961 41.0529 18.3201 40.7357 19.487C40.4525 20.5066 39.7954 21.1637 38.7757 21.4469C38.2433 21.5942 37.269 21.6962 35.7735 21.7642C34.3007 21.8435 32.9525 21.8775 31.7063 21.8775L29.905 21.9454C25.1581 21.9454 22.2012 21.7642 21.0343 21.4469C20.0146 21.1637 19.3575 20.5066 19.0743 19.487C18.927 18.9545 18.8251 18.2408 18.7571 17.3345C18.6778 16.4281 18.6438 15.6464 18.6438 14.9667L18.5758 14.015C18.5758 11.5339 18.7571 9.70993 19.0743 8.54302C19.3575 7.5234 20.0146 6.86631 21.0343 6.58308C21.5667 6.4358 22.541 6.33384 24.0365 6.26586C25.5093 6.18656 26.8575 6.15257 28.1037 6.15257L29.905 6.08459C34.6519 6.08459 37.6088 6.26586 38.7757 6.58308C39.7954 6.86631 40.4525 7.5234 40.7357 8.54302Z" fill="white"/>
                                        </svg>
                                        
                </p>

            </section>



            <section class="accredian">
                <h1>Accredian</h1>
                <ul>
                    <li>About</li>
                    <li>Career</li>
                    <li>Blog</li>
                    <li>Admission Policy</li>
                    <li>Referral Policy</li>
                    <li>Privacy Policy</li>
                    <li>Terms Of Service</li>
                    <li>Master FAQs</li>
                </ul>
            </section>

         </div>
         <h5>© 2024 Accredian A Brand of FullStack Education Pvt Ltd. All Rights Reserved</h5>
         <svg class="callicon" width="60" height="61" viewBox="0 0 60 61" fill="none" xmlns="http://www.w3.org/2000/svg">
             <path d="M4.97778 29.3303C4.97797 22.749 7.57093 16.4328 12.195 11.7497C16.8191 7.06656 23.102 4.39372 29.6827 4.31008L29.6577 4.28507L48.2291 4.13721C48.2291 4.13721 54.8025 4.26061 54.8025 11.4162C54.8025 15.9923 54.8677 22.7363 54.915 27.0048C54.9857 27.7709 55.0219 28.5461 55.0237 29.3303C55.0237 32.6164 54.3765 35.8703 53.119 38.9062C51.8614 41.9421 50.0183 44.7006 47.6947 47.0242C45.3711 49.3478 42.6126 51.191 39.5766 52.4485C36.5407 53.7061 33.2868 54.3533 30.0008 54.3533C26.7147 54.3533 23.4608 53.7061 20.4249 52.4485C17.3889 51.191 14.6304 49.3478 12.3068 47.0242C9.98324 44.7006 8.14006 41.9421 6.88254 38.9062C5.62502 35.8703 4.97778 32.6164 4.97778 29.3303Z" fill="#1D65FF"/>
             <path d="M36.5877 36.3403L30.6961 33.8152C30.3885 33.6829 30.0526 33.6296 29.7191 33.6602C29.3857 33.6909 29.0652 33.8046 28.7869 33.9908L25.6367 36.0919C23.7115 35.1555 22.1533 33.6042 21.2084 31.6832L23.3008 28.4857C23.4827 28.208 23.5931 27.8897 23.6221 27.5591C23.6512 27.2284 23.5979 26.8957 23.4671 26.5906L20.9399 20.6925C20.7678 20.2923 20.4707 19.9586 20.0932 19.7413C19.7156 19.5241 19.2778 19.4349 18.8453 19.4873C17.1457 19.7057 15.5838 20.5355 14.4514 21.8215C13.3189 23.1075 12.6934 24.7618 12.6917 26.4754C12.6971 31.2777 14.6073 35.8818 18.0031 39.2775C21.3989 42.6732 26.003 44.5832 30.8053 44.5885C32.5189 44.5868 34.1732 43.9613 35.4592 42.8288C36.7452 41.6963 37.575 40.1344 37.7934 38.4348C37.8457 38.0023 37.7564 37.5645 37.5391 37.187C37.3217 36.8094 36.9879 36.5124 36.5877 36.3403Z" fill="white"/>
             <path d="M43.6736 29.9344C43.5736 29.9344 43.4992 29.9344 43.4313 29.9344C41.7461 29.904 39.458 29.8888 36.6242 29.8888C31.8285 29.8888 26.9864 29.9339 26.9478 29.9344V17.9277C27.0798 17.1884 27.385 16.4907 27.8383 15.8919C28.2829 15.3001 28.8601 14.8207 29.5235 14.4925C30.4672 14.0487 31.5012 13.831 32.5437 13.8565H43.4334C43.4503 13.8565 43.4941 13.8565 43.5643 13.8565C44.3927 13.8565 48.5302 14.1214 48.6232 19.3531C48.7243 25.129 48.6232 26.5647 48.6232 26.5783C48.6519 26.931 48.6099 27.2859 48.4992 27.622C48.3886 27.9581 48.2116 28.2684 47.979 28.5351C47.1723 29.4597 45.7247 29.9344 43.6736 29.9344ZM31.2369 23.4483C31.0126 23.4486 30.7975 23.5375 30.6389 23.6962C30.4803 23.8549 30.3911 24.0701 30.391 24.2945C30.3911 24.5188 30.4803 24.7341 30.6389 24.8928C30.7975 25.0514 31.0126 25.1404 31.2369 25.1407H39.7396C39.9639 25.1404 40.1788 25.0514 40.3374 24.8928C40.4959 24.7341 40.5851 24.5188 40.5853 24.2945C40.5851 24.0701 40.4959 23.8549 40.3374 23.6962C40.1788 23.5375 39.9639 23.4486 39.7396 23.4483H31.2369ZM31.2369 19.3584C31.0126 19.3587 30.7975 19.4482 30.6389 19.6069C30.4803 19.7656 30.3911 19.9803 30.391 20.2046C30.3911 20.429 30.4803 20.6443 30.6389 20.8029C30.7975 20.9616 31.0126 21.0511 31.2369 21.0514H44.3733C44.5977 21.0512 44.8129 20.9616 44.9716 20.8029C45.1303 20.6442 45.2194 20.4291 45.2195 20.2046C45.2194 19.9802 45.1303 19.7651 44.9716 19.6064C44.8129 19.4477 44.5977 19.3586 44.3733 19.3584H31.2369Z" fill="white"/>
             </svg>
    </section>
 
        
</body>

</html>
