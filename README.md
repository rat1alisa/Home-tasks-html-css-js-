# Home-tasks-html-css-js-



//1 - Реализовать html-страницу с вертикальным меню (задание 2)



<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ex2</title>
    <link rel="stylesheet" href="st1.css">
</head>

<body>
    <div class="menu">

        <div class="menu-title">MENU</div>

        <ul class="menu-links">

            <li><a href=""><span>&#x270e;</span>EDIT</a></li>
            <li><a href=""><span>&#128151;</span>FAVORITES</a></li>
            <li><a href=""><span>&#128339;</span>HISTORY</a></li>
            <li><a href=""><span>&#128737;</span>SECURITY</a></li>
            <li><a href=""><span>&#127760;</span>SETTINGS</a></li>

        </ul>
        
       </div>
    
    </div>
</body>

</html>


* {
    box-sizing: border-box;
}

html,
body {
    margin: 0;
    padding: 0;
    color: white;
}

.tasks {
    padding-top: 15px;
    padding-bottom: 45px;
}

.tasks h2 {
    text-align: center;
}


html,body {
    height: 100%;
    font-family: Arial, sans-serif;
    background-color: lightgrey;
}

.menu {
    position: fixed;
    
    width: 90px;
    height: 100%;

    background: grey;

    padding-top: 30px;

    padding-bottom: 30px;

    color: white;

    transition: width 0.5s linear;

    overflow-x: hidden;
}

.menu:hover {
    width: 250px;
}

.menu-title {
    padding-left: 20px;
    font-weight: 800;
    margin-bottom: 30px;
}

.menu-links {
    list-style: none;
    margin: 0;
    padding: 0;
}

.menu-links li a span {
    display: inline-block;
    width: 60px;

    font-size: 20px;
}

.menu-links li a {
    display: block;
    width: 250px;

    color: white;
    
    padding-top: 20px;
    padding-bottom: 20px;
    padding-left: 30px;
    
    text-decoration: none;
    transition: all 0.3s linear;
}

.menu-links li a:hover {
    background: #6495ED;
}





//2 - Реализовать html-страницу со структурой сайта (задание 3)



<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercise</title>
    <link rel="stylesheet" href="st1.css">
</head>

<body>
  
    <div class="container">

      <div class="header">
        HEADER
        </div>
      
      <div class="menu">
        MENU
        </div>
      
      <div class="all">
        
        <div class="aside">
          <div class="aside1">ASIDE 1</div>
          <div class="aside2">ASIDE 2</div>
        </div>
        
        <div class="main">
          MAIN CONTENT
          <div class="section">SECTION 1</div>
          <div class="section">SECTION 2</div>
        </div>
        
        <div class="aside3">ASIDE 3</div>
        
      </div>
      
      <div class="footer">FOOTER</div>
      
    </div>
  
</body>

</html>



* {
    box-sizing: border-box;
}

html,
body {
    background-color: lightgrey;
  
  display: flex;
  justify-content: center;
  align-items: center;
}

.container {
  display: flex;
  align-items: center;
  gap: 15px;
  
  width: 900px;
  height: 600px;
 
  flex-direction: column;
}

.header{
  width: 900px;
  height: 90px;
  background: white;
  
  display: flex;
  align-items: center;
  justify-content: center;
  color: black;
}

.menu{
  width: 900px;
  height: 50px;
  background: white;
  
  display: flex;
  align-items: center;
  justify-content: center;
  color: black;
}

.all{
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  gap: 15px;
}

.aside{
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  
  gap: 15px;
}

.aside1{
  display: flex;
  align-items: center;
  justify-content: center;
  width: 220px;
  height: 100px;
  background: white;
}
.aside2{
  display: flex;
  align-items: center;
  justify-content: center;
  width: 220px;
  height: 140px;
  background: white;
}

.main{
  display: flex;
  align-items: center;
  justify-content: center;
  width: 500px;
  height: 300px;
  background: white;
  flex-direction: column;
  gap: 10px;
}

.section{
  display: flex;
  align-items: center;
  justify-content: center;
  width: 400px;
  height: 100px;
  background: lightgrey;
}


.aside3{
  display: flex;
  align-items: center;
  justify-content: center;
  width: 150px;
  height: 250px;
  background: white;
}

.footer{
  width: 900px;
  height: 90px;
  background: white;
  
  display: flex;
  align-items: center;
  justify-content: center;
  color: black;
}





//3 - Реализовать html-страницу с футером (задание 4)


<!DOCTYPE html> 
<html lang="en"> 
 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>Exercise</title> 
    <link rel="stylesheet" href="st1.css"> 
</head> 
 
<body> 
   
    <div class="container"> 
 
      <div class="other"> 
         
        <ul class="ull"> 
          <li><a>Home</a></li> 
          <li><a>About</a></li> 
          <li><a>Gallery</a></li> 
          <li><a>News</a></li> 
        </ul> 
         
        <ul class="ull"> 
          <li><a>Blog</a></li> 
          <li><a>FAQ</a></li> 
          <li><a>Contacts</a></li> 
          <li><a>Privacy&cookies</a></li> 
        </ul> 
         
         
        <div class="social"> 
           
          <svg class="s" xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="70" height="70" viewBox="0,0,256,256"> 
<g fill="white" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><g transform="scale(10.66667,10.66667)"><path d="M12,4c0,0 -6.25445,-0.00003 -7.81445,0.41797c-0.861,0.23 -1.53758,0.90758 -1.76758,1.76758c-0.418,1.56 -0.41797,5.81445 -0.41797,5.81445c0,0 -0.00003,4.25445 0.41797,5.81445c0.23,0.861 0.90758,1.53758 1.76758,1.76758c1.56,0.418 7.81445,0.41797 7.81445,0.41797c0,0 6.25445,0.00003 7.81445,-0.41797c0.86,-0.23 1.53758,-0.90758 1.76758,-1.76758c0.418,-1.56 0.41797,-5.81445 0.41797,-5.81445c0,0 0.00003,-4.25445 -0.41797,-5.81445c-0.23,-0.86 -0.90758,-1.53758 -1.76758,-1.76758c-1.56,-0.418 -7.81445,-0.41797 -7.81445,-0.41797zM12,6c2.882,0 6.49087,0.13361 7.29688,0.34961c0.169,0.045 0.30752,0.18352 0.35352,0.35352c0.241,0.898 0.34961,3.63888 0.34961,5.29688c0,1.658 -0.10861,4.39787 -0.34961,5.29688c-0.045,0.169 -0.18352,0.30752 -0.35352,0.35352c-0.805,0.216 -4.41488,0.34961 -7.29687,0.34961c-2.881,0 -6.48987,-0.13361 -7.29687,-0.34961c-0.169,-0.045 -0.30752,-0.18352 -0.35352,-0.35352c-0.241,-0.898 -0.34961,-3.63888 -0.34961,-5.29687c0,-1.658 0.10861,-4.39883 0.34961,-5.29883c0.045,-0.168 0.18352,-0.30656 0.35352,-0.35156c0.805,-0.216 4.41488,-0.34961 7.29688,-0.34961zM10,8.53516v6.92969l6,-3.46484z"></path></g></g> 
</svg> 
           
           
          <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="70" height="70" viewBox="0,0,256,256"> 
<g fill="#ffffff" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><g transform="scale(5.12,5.12)"><path d="M16,3c-7.16752,0 -13,5.83248 -13,13v18c0,7.16752 5.83248,13 13,13h18c7.16752,0 13,-5.83248 13,-13v-18c0,-7.16752 -5.83248,-13 -13,-13zM16,5h18c6.08648,0 11,4.91352 11,11v18c0,6.08648 -4.91352,11 -11,11h-18c-6.08648,0 -11,-4.91352 -11,-11v-18c0,-6.08648 4.91352,-11 11,-11zM37,11c-1.10457,0 -2,0.89543 -2,2c0,1.10457 0.89543,2 2,2c1.10457,0 2,-0.89543 2,-2c0,-1.10457 -0.89543,-2 -2,-2zM25,14c-6.06329,0 -11,4.93671 -11,11c0,6.06329 4.93671,11 11,11c6.06329,0 11,-4.93671 11,-11c0,-6.06329 -4.93671,-11 -11,-11zM25,16c4.98241,0 9,4.01759 9,9c0,4.98241 -4.01759,9 -9,9c-4.98241,0 -9,-4.01759 -9,-9c0,-4.98241 4.01759,-9 9,-9z"></path></g></g> 
</svg> 
           
           
          <svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="70" height="70" viewBox="0,0,256,256"> 
<g fill="#ffffff" fill-rule="nonzero" stroke="none" stroke-width="1" stroke-linecap="butt" stroke-linejoin="miter" stroke-miterlimit="10" stroke-dasharray="" stroke-dashoffset="0" font-family="none" font-weight="none" font-size="none" text-anchor="none" style="mix-blend-mode: normal"><g transform="scale(5.12,5.12)"><path d="M9,4c-2.74952,0 -5,2.25048 -5,5v32c0,2.74952 2.25048,5 5,5h32c2.74952,0 5,-2.25048 5,-5v-32c0,-2.74952 -2.25048,-5 -5,-5zM9,6h32c1.66848,0 3,1.33152 3,3v32c0,1.66848 -1.33152,3
8 -1.33152,3 -3,3h-32c-1.66848,0 -3,-1.33152 -3,-3v-32c0,-1.66848 1.33152,-3 3,-3zM23.39648,15.99219c-1.05749,-0.00243 -2.00043,0.05667 -2.84375,0.4707c-0.00065,0.00065 -0.0013,0.0013 -0.00195,0.00195c-0.41113,0.20256 -0.70091,0.45985 -0.93164,0.76563c-0.11537,0.15289 -0.23356,0.29013 -0.29687,0.63867c-0.03166,0.17427 -0.04944,0.45667 0.13281,0.76172c0.18226,0.30504 0.54873,0.4785 0.7832,0.50977c0.16288,0.02168 0.53054,0.17817 0.56445,0.22461c0.00065,0.0013 0.0013,0.00261 0.00195,0.00391c0.00024,0.00033 0.14258,0.372 0.18359,0.70313c0.04102,0.33112 0.03906,0.59961 0.03906,0.59961c-0.00042,0.02671 0.00023,0.05342 0.00195,0.08008c0,0 0.05793,0.86756 0.01953,1.76367c-0.0153,0.35715 -0.06149,0.67489 -0.10937,0.95898c-0.35611,-0.39316 -0.88084,-1.10515 -1.63867,-2.41797c-0.84069,-1.4572 -1.50977,-2.76367 -1.50977,-2.76367c-0.03514,-0.11382 -0.15941,-0.46794 -0.64453,-0.82422c-0.53033,-0.39087 -1.04297,-0.44922 -1.04297,-0.44922c-0.06431,-0.0129 -0.12973,-0.01944 -0.19531,-0.01953l-3.94141,0.00195c0,0 -0.23632,-0.01367 -0.51953,0.02539c-0.28322,0.03906 -0.70968,0.07085 -1.12109,0.55859c-0.00065,0.00065 -0.0013,0.0013 -0.00195,0.00195c-0.36769,0.43934 -0.34545,0.92493 -0.30078,1.19922c0.04466,0.27429 0.14453,0.48242 0.14453,0.48242c0.00193,0.00392 0.00388,0.00783 0.00586,0.01172c0,0 3.22389,6.77825 6.86719,10.76953c2.64568,2.89802 5.36122,2.94727 7.60156,2.94727h1.67188c0.42683,0 0.81292,-0.01668 1.24023,-0.26562c0.42732,-0.24895 0.71484,-0.855 0.71484,-1.27539c0,-0.44052 0.06577,-0.78682 0.14648,-0.96484c0.05676,-0.1252 0.1017,-0.17028 0.17188,-0.20703c0.01484,0.00941 0.00526,0.00394 0.04688,0.0332c0.16647,0.11707 0.44136,0.38393 0.74023,0.7168c0.59775,0.66574 1.27626,1.57889 2.1875,2.20508c0.65281,0.44899 1.26946,0.64837 1.73828,0.7207c0.29372,0.04532 0.52185,0.03659 0.68359,0.02344l3.73438,0.01563c0.02215,0.00008 0.0443,-0.00057 0.06641,-0.00195c0,0 0.64346,0.0075 1.3125,-0.39258c0.33452,-0.20006 0.72906,-0.57936 0.85742,-1.13281c0.12836,-0.55345 -0.03296,-1.12692 -0.34766,-1.65039c0,-0.00065 0,-0.0013 0,-0.00195c0.05465,0.0906 -0.04948,-0.09557 -0.15625,-0.26953c-0.10677,-0.17396 -0.2618,-0.40838 -0.48437,-0.69922c-0.44515,-0.58167 -1.15812,-1.39565 -2.31055,-2.46875c-0.00065,0 -0.0013,0 -0.00195,0c-0.58533,-0.54459 -0.98058,-0.93016 -1.14258,-1.14453c-0.162,-0.21437 -0.10887,-0.10176 -0.09766,-0.15625c0.02243,-0.10898 0.72492,-1.12238 2.1543,-3.03125c0.86889,-1.16189 1.47868,-2.03421 1.88086,-2.75977c0.40218,-0.72556 0.69217,-1.35393 0.49023,-2.12305c-0.00065,-0.0013 -0.0013,-0.00261 -0.00195,-0.00391c-0.08965,-0.33762 -0.33449,-0.64882 -0.58594,-0.81836c-0.25144,-0.16954 -0.48983,-0.23585 -0.70312,-0.27734c-0.42659,-0.08299 -0.79885,-0.06836 -1.14453,-0.06836c-0.72476,0 -3.94041,0.02539 -4.20508,0.02539c-0.31273,0 -0.82985,0.14224 -1.05859,0.2793c-0.57511,0.34608 -0.74023,0.80078 -0.74023,0.80078c-0.0104,0.01921 -0.02017,0.03875 -0.0293,0.05859c0,0 -0.66333,1.47093 -1.51758,2.92383c-0.86538,1.47373 -1.50468,2.17662 -1.89062,2.50195c-0.01062,-0.05786 -0.00879,-0.01088 -0.01562,-0.0918c-0.03459,-0.41154 0.00391,-0.98022 0.00391,-1.53516c0,-1.49451 0.12668,-2.54049 0.05859,-3.46484c-0.03404,-0.46217 -0.11965,-0.93876 -0.42383,-1.37695c-0.30417,-0.43819 -0.81031,-0.72286 -1.31055,-0.84375c-0.30015,-0.0724 -0.64229,-0.26071 -1.88086,-0.27344c-0.00065,0 -0.0013,0 -0.00195,0c-0.37877,-0.00379 -0.74321,-0.01091 -1.0957,-0.01172zM24.47266,18.00391c1.09597,0.01126 0.82297,0.07159 1.43164,0.21875c0.18876,0.04561 0.14303,0.04535 0.13867,0.03906c-0.0044,-0.0063 0.05106,0.09681 0.07227,0.38477c0.04242,0.5759 -0.06445,1.72092 -0.06445,3.31641c0,0.43507 -0.0525,1.05592 0.00195,1.70313c0.0544,0.6472 0.21492,1.47779 0.98828,1.97852c0.36659,0.23763 0.79224,0.2526 1.15625,0.16211c0.36401,-0.0905 0.69425,-0.27898 1.04102,-0.55664c0.69354,-0.55532 1.46711,-1.49254 2.43945,-3.14844c0.90881,-1.5457 1.56986,-3.01759 1.5918,-3.06641c0.00429,-0.00344 0.00864,-0.00581 0.01367,-0.00977c0.01249,0.00014 -0.00045,0 0.01563,0c0.37334,0 3.52984,-0.02539 4.20508,-0.02539c0.15763,0 0.21501,0.0095 0.33984,0.01367c-0.03393,0.11327 0.0038,0.04102 -0.14453,0.30
859c-0.31107,0.56119 -0.88431,1.39519 -1.73242,2.5293c-1.39362,1.86113 -2.2574,2.5904 -2.51172,3.82617c-0.12716,0.61788 0.11116,1.30278 0.46094,1.76563c0.34978,0.46285 0.79128,0.85939 1.37695,1.4043c1.08457,1.0099 1.72083,1.74362 2.08594,2.2207c0.18255,0.23854 0.29763,0.41084 0.36914,0.52734c0.07151,0.11651 0.05384,0.10421 0.14648,0.25781c0.06099,0.10221 0.03852,0.03983 0.04883,0.07031c-0.1199,0.0338 -0.26516,0.07449 -0.27344,0.07617l-3.67773,-0.01562c-0.06624,-0.00004 -0.13232,0.0065 -0.19727,0.01953c0,0 0.0092,0.01082 -0.1875,-0.01953c-0.19673,-0.03035 -0.50962,-0.11548 -0.91211,-0.39258c-0.48576,-0.33381 -1.16579,-1.15056 -1.83203,-1.89258c-0.33312,-0.37101 -0.66534,-0.7273 -1.07812,-1.01758c-0.41278,-0.29028 -1.03045,-0.56324 -1.69727,-0.35352c-0.69222,0.21736 -1.23104,0.75758 -1.49414,1.33789c-0.19584,0.43197 -0.2117,0.88317 -0.24219,1.33203c-0.03319,0.0025 0.005,0 -0.03711,0h-1.67187c-2.27166,0 -3.88468,0.15711 -6.125,-2.29687c-3.01349,-3.30132 -5.77446,-8.79416 -6.22461,-9.69922l3.46875,-0.00195c0.06097,0.0234 0.19146,0.0724 0.19922,0.07813c0.0013,0.00131 0.0026,0.00261 0.00391,0.00391c-0.12679,-0.09268 0.00586,0.03711 0.00586,0.03711c0.01224,0.02994 0.02593,0.05927 0.04102,0.08789c0,0 0.68733,1.3428 1.55664,2.84961c0.85272,1.47719 1.47409,2.39998 2.07422,3.00977c0.30006,0.30489 0.60296,0.54942 1.00781,0.6875c0.40485,0.13808 0.92761,0.08743 1.2793,-0.10547c0.71843,-0.39327 0.81495,-0.97334 0.93164,-1.48047c0.11685,-0.50784 0.16337,-1.04884 0.18555,-1.56641c0.04304,-1.0046 -0.01783,-1.87404 -0.02148,-1.92773c0.00022,-0.01883 0.0048,-0.38139 -0.05273,-0.8457c-0.0589,-0.47545 -0.12459,-1.05676 -0.55469,-1.64258l-0.00195,-0.00195c-0.003,-0.0041 -0.00677,-0.00381 -0.00977,-0.00781c0.56875,-0.08157 1.0554,-0.18198 2.06641,-0.17187zM33.29492,18.98438l-0.01367,0.03125c-0.00212,0.00121 -0.00144,-0.00144 -0.00391,0c0.00423,-0.00806 0.01758,-0.03125 0.01758,-0.03125z"></path></g></g>
</svg>
        
      </div>
      </div>
           
      <p>Copyright @Company 2018-2019</p>
    </div>
  
</body>

</html>





//4 - Реализовать html-страницу со списком продуктов (задание 1)

<!DOCTYPE html> 
<html lang="en"> 
 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>Exercise</title> 
    <link rel="stylesheet" href="st1.css"> 
</head> 
 
<body> 
   
    <div class="container"> 
 
      <p class="text">What do I have in my fridge?</p> 
       
      <div class="blocks"> 
         
        <div class="block"> 
        <img src="https://upload.wikimedia.org/wikipedia/commons/2/2b/Hot_chili_red_pepper_icon_emote.png" alt="текст" class="images"></img> 
        <b>Pepper</b> 
      </div> 
       
       
      <div class="block"> 
        <img src="https://static.vecteezy.com/system/resources/previews/009/637/562/original/bright-yellow-vegetable-corn-file-png.png" alt="текст" class="images"></img> 
        <b>Corn</b> 
      </div> 
       
       
      <div class="block"> 
        <img src="https://static.vecteezy.com/system/resources/previews/015/100/030/non_2x/apple-transparent-background-free-png.png" alt="текст" class="images"></img> 
        <b>Apple</b> 
      </div> 
   
      <div class="block"> 
        <img src="https://static.vecteezy.com/system/resources/thumbnails/009/380/457/small/cheese-clipart-design-illustration-free-png.png" alt="текст" class="images"></img> 
        <b>Cheese</b> 
      </div> 
    
      </div> 
         
<p>... that's all ...</p> 
    </div> 
            
    </div> 
</body> 
 
</html>


* {    box-sizing: border-box;
}
html,
body {    margin: 0;
    padding: 0;    background-color: lightgrey;
      display: flex;
    align-items: center;    justify-content: center;
}
.container {    background: lightgrey;
    display: flex;    align-items: center;
    justify-content: center;    
    flex-direction: column;}
.blocks{
  background: lightgrey;  display: flex;
  align-items: center;  justify-content: center;
    width: 900px;
  gap: 30px;}
.block{
  background: lightgrey;  display: flex;
  align-items: center;  justify-content: center;
  width: 160px;  height: 180px;
  border: 1px solid black;  border-radius: 20px;
    flex-direction: column;
  gap: 10px;}

.images{  width: 100px;
  height: 120px;}
  
.text{
  font-size: 20px;
  font-weight: 700;
  }













