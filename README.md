# pa-heart react ako ng post namin
ano g??
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Hello...</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
  body {
    margin: 0;
    height: 100vh;
    background: #ffffff;
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: Tahoma, Arial, sans-serif;
    background-image: url('https://i1.sndcdn.com/avatars-F35OU0eOpcjHaeiP-jEMs5w-t240x240.jpg');
    background-size: cover
  }

  input { display: none; }

 
  .window {
    width: 320px;
    background: #c0c0c0;
    border: 2px solid #000;
    box-shadow: 2px 2px 0 #404040;
    display: none;
  }

  
  .title {
    background: linear-gradient(to right, #000080, #1084d0);
    color: white;
    padding: 4px 6px;
    font-size: 14px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .close {
    background: #ff0000;
    border: 1px solid #000;
    width: 16px;
    height: 16px;
    text-align: center;
    font-weight: bold;
    font-size: 12px;
    line-height: 14px;
  }

  
  .content {
    display: flex;
    gap: 12px;
    padding: 18px;
    color: black;
    font-size: 14px;
  }

  .icon {
    font-size: 28px;
  }

  
  .buttons {
    display: flex;
    justify-content: center;
    gap: 10px;
    padding: 0 18px 18px;
  }



  .btn {
    background: #c0c0c0;
    border: 2px outset #fff;
    padding: 4px 16px;
    cursor: pointer;
    font-size: 13px;
  }

  .btn1 {
   
    background: #c0c0c0;
    border: 2px outset #fff;
    padding: 4px 16px;
    cursor: pointer;
    font-size: 13px;
  }

  .btn2 {
    background: #c0c0c0;
    border: 2px outset #fff;
    padding: 4px 16px;
    cursor: pointer;
    font-size: 13px;
  }

  .btn:active {
    border: 2px inset #fff;
  }

  .btn1:active {
    border: 2px inset #fff;
  }
  .btn2:active {
    border: 2px inset #fff;
  }

  
  #s1:checked ~ .w1,
  #s2:checked ~ .w2,
  #s3:checked ~ .w3,
  #s4:checked ~ .w4,
  #s5:checked ~ .w5,
  #s6:checked ~ .w6,
  #s7:checked ~ .w7
  {
    display: block;
  }
</style>
</head>
<body>


<input type="radio" name="step" id="s1" checked>
<input type="radio" name="step" id="s2">
<input type="radio" name="step" id="s3">
<input type="radio" name="step" id="s4">
<input type="radio" name="step" id="s5">
<input type="radio" name="step" id="s6">
<input type="radio" name="step" id="s7">

<div class="window w1">
  <div class="title">
    <span>Hello...</span>
    <div class="close">×</div>
  </div>

  <div class="content">
    <div class="icon">ℹ️</div>
    <div>Pwedeng pa-heart react ako sa post namin??.</div>
  </div>

  <div class="buttons">
    <label for="s2" class="btn">OK</label>
  </div>
</div>


<div class="window w2">
  <div class="title">
    <span>Hello...</span>
    <div class="close">×</div>
  </div>

  <div class="content">
    <div class="icon">ℹ️</div>
    <div>pa heart react na ako ng post namin <br>please please</div>
  </div>

  <div class="buttons">
    <label for="s3" class="btn">OK</label>
  </div>
</div>

<div class="window w3">
  <div class="title">
    <span>Hello...</span>
    <div class="close">×</div>
  </div>

  <div class="content">
    <div class="icon">ℹ️</div>
    <div>Sure yan, pa-share na din kung ok lang.</div>
  </div>

  <div class="buttons">
    <label for="s4" class="btn">OK</label>
  </div>
</div>

<div class="window w4">
  <div class="title">
    <span>Hello...</span>
    <div class="close">×</div>
  </div>

  <div class="content">
    <div class="icon">ℹ️</div>
    <div>thank you very much</div>
  </div>

  <div class="buttons">
    <label for="s5" class="btn">Welcome</label>
  </div>
</div>

<div class="window w5">
  <div class="title">
    <span>Hello...</span>
    <div class="close">×</div>
  </div>

  <div class="content">
    <div class="icon">❤️</div>
    <div>
      Critical Question Detected:<br><br>
      I-heart mo ba talaga??
    </div>
  </div>


  <div class="buttons">
    <label for="s6" class="btn1">Yes</label>
    <label for="s7" class="btn2">No</label>
  </div>
</div>

<div class="window w6">
  <div class="title">
    <span>Hello...</span>
    <div class="close">×</div>
  </div>

  <div class="content">
    <div class="icon">ℹ️</div>
    <div>heto link ng post namin <br>
      <a href="https://www.facebook.com/share/p/1F9fVYGF3D/">pa-click nalang poo!</a>
      , thank you so much!<br>❤️❤️❤️</div>
  </div>

  <div class="buttons">
    <label for="s1" class="btn">OK</label>
  </div>
</div>

<div class="window w7">
  <div class="title">
    <span>Hello...</span>
    <div class="close">×</div>
  </div>

  <div class="content">
    <div class="icon">ℹ️</div>
    <div>Thank you for being honest.
I understand and respect your answer.
Wishing you all the best.<br>❤️❤️❤️</div>
  </div>

  <div class="buttons">
    <label for="s1" class="btn">OK</label>
  </div>
</div>



</body>
</html>
