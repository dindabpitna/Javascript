# Javascript
Learning JavaScript

<!DOCTYPE html>
<html>
<head>
<meta charset="Shift_JIS">
<title>Welcome to the new era! ORGCHEMNER</title>
</head>
<body style="background-color:azure;">
            <h1 style="font-family: fantasy; color:navy; text-align: center">This is a pop culture website and to order Chinese food at the same time!</h1>
            <h2 style="text-align: left; font-family:'Franklin Gothic Medium'; color: rgb(17, 31, 228); text-align: center">Introduction !</h2>
            <p style="color:black ; font-family:monospace;" >
            Name       : Dinda Pitna<Br>
            ID         : B1878065 <Br>
            Birthplace : Jakarta, Indonesia <Br>
            Education  : Organic chemistry, Master candidate at Sophia University<br>
            (If you are interested to apply to Sophia, apply <a href="http://www.sophia.ac.jp/" target="_blank" style=""> here</a> and to see my LinkedIn profile <a href="http://www.linkedin.com/in/dindabpitna/" target="_blank">here</a>)
                <br><br>
                Hello everyone! Thank you for visiting this webpage. Since coding takes a lot of time, I would not do something spectacular here.
                Rather I would bring you to a boring journey of pop culture and a a little bit of basic science (or anything you are interested in) while enjoying 
                some Chinese food. I miss how good Indonesian Chinese food back home. Anyways enjoy!<br>
            </p><br><br>

            <form action="/action_page.php" method="post">
              <input type="text" name="fname" required>
              <input type="submit" value="Submit">
            </form>

            <style>
                .container {
                  align-items: center;
                }
                
                .center {
                  position: absolute;
                  top: 50%;
                  left: 50%;
                  transform: translate(-50%, -50%);
                  font-size: 18px;
                }
                </style>
<div style="background-color:black">            
      <h2 style="font-family: 'Franklin Gothic Medium'; color:darkgoldenrod; text-align:center">Game of Thrones Quiz</h2>
          <p style="color:chartreuse; font-family:monospace; size:25pt;">
          Since Game of Thrones Season 8 is approaching. It is much better for us to review previous seasons to prepare yourself. Click the image below to continue.<Br></p>
          <a href="GoT.html"><img id="WiH" src="Winter is here.gif" style="width:35%;height:35%;"></a>
</div>       
      <h2 style="font-family: 'Franklin Gothic Medium'; color:salmon; text-align:center">Organic Chemistry Quiz</h2>
        <p style="color:rebeccapurple; font-family:monospace; size:25pt;">
        This website is not all about nonsense, but I also provided few knowledge about chemistry! Do you mind to do a little bit of organic chemistry quiz? Click here. <Br></p>
          <a href="GoT.html"><img src="Winter is here.gif" style="width:35%;height:35%;" id=""> </a>

          <style>
          .cont
          {background-position: center;}
        
          .center {
            position: relative;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 18px;}
          </style>
<div style="background-color:midnightblue">
      <h2 style="font-family: 'Franklin Gothic Medium'; color:yellowgreen; text-align:center">Chinese Food?</h2>
          <p style="color:rgb(255, 0, 85); font-family:monospace; size:25pt;">
          I know you must have been hungry after doing all those quizzes. Now it is time to eat some Chinese food!<Br></p>
          <a id="Chin" href="Chinese.html" >
            <div class="cont">
            <img id="capcay" src="capcay.jpg" style="width:35%;height:35%;"></div>
          <div class="center">Click Me</div></a>
</div><script>
              document.getElementById("Chin").addEventListener("mouseover", 
              function GoT(){document.getElementById("capcay").style.opacity="0.5"}
    )
      </script>
      <h2 style="font-family: 'Franklin Gothic Medium'; color:black; text-align:center;">Feedback</h2>
            <p style="color:darkgreen; font-family:monospace; size:25pt;">
            Since Game of Thrones Season 8 is approaching. It is much better for us to review previous seasons to prepare yourself. Click image below to continue.<Br></p>
              <style>
                .container {
                  align-items: center;
                }
                
                .center {
                  position: absolute;
                  top: 50%;
                  left: 50%;
                  transform: translate(-50%, -50%);
                  font-size: 18px;
                }
                </style>
                               
                <div class="container">
                  <a href="GoT.html"><img src="Winter is here.gif" style="width:35%;height:35%;"alt="Cinque Terre"> </a>
                </div>
                
                
                
              

              
              
</body>
</html>


<!DOCTYPE html>
<html>
<head>
<meta charset="Shift_JIS">
<title>Welcome to the new era! ORGCHEMNER</title>
</head>
<body style="background-color:black;">
<h1 style="font-family: Verdana; color:turquoise; text-align: center">Welcome to Game of Thrones Review Session!</h1>

<h2 style="font-style:italic; font-family: cursive ; color: red; text-align: center ">It is time for quiz!</h2>
<p style="color:palevioletred ; font-family: Arial, Helvetica, sans-serif;" >

  <style>
  .col-2{
  float: left;
  color:orangered ;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  font-size: 14pt;
  align-content: space-between;
  margin-top:12px;
  }
  .col-25 {
  float: left;
  width: 35%;
  margin-top: 15px;
  color: deeppink;
  font-size: 13pt;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.pic{
  width:20%;
  size: 15%;
  
}

.row:after {
  content: "";
  display: table;
  clear: both;}

  </style>

<script>
  document.getElementById("subm").addEventListener("click", nextt());
  function nextt(){
    
    var js1=document.got.js.value;
    var reek1=document.got.reek.value;  
    var valara1=document.got.valara.value;
    var brans1=document.got.brans.value;
    var chaos1=document.got.chaos.value;
    var white1=document.got.white.value;
    var js2;
    var reek2;
    var valara2;
    var brans2;
    var chaos2;
    var white2;

    if (js1=="jon"){(js2==1)};
      else {(js1=0);} 

    
    if (reek1=="theon"){(reek2==1)};
    else {reek2=0;}

    
    if (valara1=="serve"){(valara2==1)};
    else {valara2=0;}
     

    
    if (brans1=="jaime"){(brans2==1)};
    else {brans2=0;}
      

    
    if (chaos1=="ladder"){(chaos2==1)};
    else {chaos2=0;{}}
          
    
    
    if (white1=="dragonglass"){(white2==1)};
    (white1=="valyrian"){(white2==white2+1)};
    else {white2=0;}
    

    function next(score,js2,reek2,valara2,brans2,chaos2,white2){
    score=js2+reek2+valara2+brans2+chaos2+white2;
    if (score < 5) { alert("5") ; return false;}
    else if (score <4 ){alert("4"); return false;}
    else if (score <3 ){alert("3"); return false;}
    else if (score <2 ){alert("2"); return false;}
    else {alert("1"); return true;}}
    }
</script>

<form name="got">
<div class="row">
  <div class="col-25">
    <label for="1" id="b">Which one is Jon Snow?</label>
  </div>
  <div class="col-2">
    <input type="radio" name="js" value="jon" checked="checked"><img class="pic" src="jon.gif">
    <input type="radio" name="js" value="sansa"><img class="pic" src="sansa.gif">
    <input type="radio" name="js" value="arya"><img class="pic" src="arya.gif">
    <input type="radio" name="js" value="ned"><img class="pic" src="ned.gif">

</div>
</div>

<div class="row">
  <div class="col-25">
    <label for="2" id="c">Which one is Reek?</label>
  </div>
  <div class="col-2">
    <input type="radio" name="reek" value="gendry" checked="checked"><img class="pic" src="gendry.gif">
    <input type="radio" name="reek" value="lf"><img class="pic" src="lf.gif">
    <input type="radio" name="reek" value="theon"><img class="pic" src="theon greyjoy.gif">
    <input type="radio" name="reek" value="jm"><img class="pic" src="jm.gif">

</div>
</div>

<div class="row">
  <div class="col-25">
    <label for="3" id="d">The phrase 'Valar Morghulis' or 'all men must die' is usually responded with:</label>
  </div>
  <div class="col-2">
    <input type="radio" name="valara" value="serve" checked="checked">Valar Dohaeris or all men must serve<br>
    <input type="radio" name="valara" value="live">Valar Rohnas or all men must live<br>
    <input type="radio" name="valara" value="kill">Valar Korashi or all men must kill<br>
    <input type="radio" name="valara" value="suffer">Valar Irushas or all men must suffer<br> 

</div>
</div>
<div class="row">
    <div class="col-25">
      <label for="3" id="d">Who pushed Bran Stark that lead him to paralyze?</label>
    </div>
    <div class="col-2">
      <input type="radio" name="brans" value="cersei" checked="checked"><img class="pic" src="cersei.gif">
      <input type="radio" name="brans" value="tyrion"><img class="pic" src="tyrion.gif">
      <input type="radio" name="brans" value="jaime"><img class="pic" src="jaime.gif">
      <input type="radio" name="brans" value="tywin"><img class="pic" src="tywin.gif">
  
  </div>
  </div>

  <div class="row">
      <div class="col-25">
        <label for="3" id="d">Chaos is a ....</label>
      </div>
      <div class="col-2">
        <input type="radio" name="chaos" value="pit" checked="checked">Pit<br>
        <input type="radio" name="chaos" value="gift">Gift<br>
        <input type="radio" name="chaos" value="must">Mustl<br>
        <input type="radio" name="chaos" value="ladder">Ladder<br>
</div>
  </div>

  <div class="row">
      <div class="col-25">
        <label for="3" id="d">Check substances that can defeat White Walkers:</label>
      </div>
      <div class="col-2">
        <input type="checkbox" name="white" value="weirwood" checked="checked">Weirwood<br>
        <input type="checkbox" name="white" value="wildfire">Wildfire<br>
        <input type="checkbox" name="white" value="valyrian">Valyrian Steel<br>
        <input type="checkbox" name="white" value="dragonglass">Dragonglass<br> 
        <input type="checkbox" name="white" value="dragonteeth">Dragonteeth<br> 
    </div>
    </div>

 

  <div class="row">
      <input type="submit" value="submit" id="subm">
    </div>
    <div class="row">
          <input type="reset" value="reset">
    </div>
  </form>
</body>
</html>


<!DOCTYPE html>
<html>
<head>
<meta charset="Shift_JIS">
<title>Welcome to the new era! ORGCHEMNER</title>
</head>
<body style="background-color:black;">
<h1 style="font-family: Verdana; color:turquoise; text-align: center">Welcome to Game of Thrones Review Session!</h1>

<h2 style="font-style:italic; font-family: cursive ; color: red; text-align: center ">It is time for quiz!</h2>
<p style="color:palevioletred ; font-family: Arial, Helvetica, sans-serif;" >

  <style>
  .col-2{
  float: left;
  color:orangered ;
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  font-size: 14pt;
  align-content: space-between;
  margin-top:12px;
  }
  .col-25 {
  float: left;
  width: 35%;
  margin-top: 15px;
  color: deeppink;
  font-size: 13pt;
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
.pic{
  width:20%;
  size: 15%;
  
}

.row:after {
  content: "";
  display: table;
  clear: both;}

  </style>

<script>
  document.getElementById("subm").addEventListener("click", next());
  
    
    var js1=document.got.js.value;
    var reek1=document.got.reek.value;  
    var valara1=document.got.valara.value;
    var brans1=document.got.brans.value;
    var chaos1=document.got.chaos.value;
    var white1=document.got.white.value;
    var js2;
    var reek2;
    var valara2;
    var brans2;
    var chaos2;
    var white2;

    function jss(js1,js2){
    if (js1=="jon"){(js2=1)};
      else (js1=null);} 
  
    function reekk(reek1,reek2){ 
    if (reek1=="theon"){(reek2=1)};
    else reek2=null;
   }

    function val(valara1,valara2){
    if (valara1=="serve"){(valara2=1)};
    else {valara2=null;}}

    function bra(brans1,brans2){
    if (brans1=="jaime"){(brans2=1)};
    else {brans2=null;}}

    function chao(chaos1,chaos2){
    if (chaos1=="ladder"){(chaos2=1)};
    else {chaos2=null;}}

    function whit(white1,white2){
    if (white1=="dragonglass"){(white2=1)};
    (white1=="valyrian"){(white2=white2+1)};
    else {white2=null;}}

    function next(score,js2,reek2,valara2,brans2,chaos2,white2){
    score=js2+reek2+valara2+brans2+chaos2+white2;
    if (score < 5) { alert("5") ; return false;}
    else if (score <4 ){alert("4"); return false;}
    else if (score <3 ){alert("3"); return false;}
    else if (score <2 ){alert("2"); return false;}
    else {alert("1"); return true;}}
    
</script>

<form name="got">
<div class="row">
  <div class="col-25">
    <label for="1" id="b">Which one is Jon Snow?</label>
  </div>
  <div class="col-2">
    <input type="radio" name="js" value="jon" checked="checked"><img class="pic" src="jon.gif">
    <input type="radio" name="js" value="sansa"><img class="pic" src="sansa.gif">
    <input type="radio" name="js" value="arya"><img class="pic" src="arya.gif">
    <input type="radio" name="js" value="ned"><img class="pic" src="ned.gif">

</div>
</div>

<div class="row">
  <div class="col-25">
    <label for="2" id="c">Which one is Reek?</label>
  </div>
  <div class="col-2">
    <input type="radio" name="reek" value="gendry" checked="checked"><img class="pic" src="gendry.gif">
    <input type="radio" name="reek" value="lf"><img class="pic" src="lf.gif">
    <input type="radio" name="reek" value="theon"><img class="pic" src="theon greyjoy.gif">
    <input type="radio" name="reek" value="jm"><img class="pic" src="jm.gif">

</div>
</div>

<div class="row">
  <div class="col-25">
    <label for="3" id="d">The phrase 'Valar Morghulis' or 'all men must die' is usually responded with:</label>
  </div>
  <div class="col-2">
    <input type="radio" name="valara" value="serve" checked="checked">Valar Dohaeris or all men must serve<br>
    <input type="radio" name="valara" value="live">Valar Rohnas or all men must live<br>
    <input type="radio" name="valara" value="kill">Valar Korashi or all men must kill<br>
    <input type="radio" name="valara" value="suffer">Valar Irushas or all men must suffer<br> 

</div>
</div>
<div class="row">
    <div class="col-25">
      <label for="3" id="d">Who pushed Bran Stark that lead him to paralyze?</label>
    </div>
    <div class="col-2">
      <input type="radio" name="brans" value="cersei" checked="checked"><img class="pic" src="cersei.gif">
      <input type="radio" name="brans" value="tyrion"><img class="pic" src="tyrion.gif">
      <input type="radio" name="brans" value="jaime"><img class="pic" src="jaime.gif">
      <input type="radio" name="brans" value="tywin"><img class="pic" src="tywin.gif">
  
  </div>
  </div>

  <div class="row">
      <div class="col-25">
        <label for="3" id="d">Chaos is a ....</label>
      </div>
      <div class="col-2">
        <input type="radio" name="chaos" value="pit" checked="checked">Pit<br>
        <input type="radio" name="chaos" value="gift">Gift<br>
        <input type="radio" name="chaos" value="must">Mustl<br>
        <input type="radio" name="chaos" value="ladder">Ladder<br>
</div>
  </div>

  <div class="row">
      <div class="col-25">
        <label for="3" id="d">Check substances that can defeat White Walkers:</label>
      </div>
      <div class="col-2">
        <input type="checkbox" name="white" value="weirwood" checked="checked">Weirwood<br>
        <input type="checkbox" name="white" value="wildfire">Wildfire<br>
        <input type="checkbox" name="white" value="valyrian">Valyrian Steel<br>
        <input type="checkbox" name="white" value="dragonglass">Dragonglass<br> 
        <input type="checkbox" name="white" value="dragonteeth">Dragonteeth<br> 
    </div>
    </div>

 

  <div class="row">
      <input type="submit" value="submit" id="subm">
    </div>
    <div class="row">
          <input type="reset" value="reset">
    </div>
  </form>
</body>
</html>
