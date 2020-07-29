<!--
  _    _          _____  _____  ______ _____   _____   __  __          _____  _____  ______ _____  
 | |  | |   /\   |  __ \|  __ \|  ____|  __ \ / ____| |  \/  |   /\   |  __ \|  __ \|  ____|  __ \ 
 | |__| |  /  \  | |  | | |  | | |__  | |__) | (___   | \  / |  /  \  | |  | | |  | | |__  | |__) |
 |  __  | / /\ \ | |  | | |  | |  __| |  _  / \___ \  | |\/| | / /\ \ | |  | | |  | |  __| |  _  / 
 | |  | |/ ____ \| |__| | |__| | |____| | \ \ ____) | | |  | |/ ____ \| |__| | |__| | |____| | \ \ 
 |_|  |_/_/    \_\_____/|_____/|______|_|  \_\_____/  |_|  |_/_/    \_\_____/|_____/|______|_|  \_\
                                                                                                   
                                                                                                   
-->

<style> 
  html, body {
    height: 100%;
    margin: 0;
    background: #000;
  }
  img {
    border: none;
    margin-bottom: 2rem
  }
  </style>
<div style="text-align:center">
   <img alt="Retarded Faggot in headphones" title="Retarded faggot" src="retardedfaggot.PNG" />
  <div id="slazy"></div>
</div>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

<!-- Design madder -->
<script src="./vendor/blotter.min.js"></script>
<script src="./vendor/liquidDistortMaterial.js"></script>

<script>
  
  function setupB() {
  var slobtawk = ['wathuph, B!', 'B'];
  
   var text = new Blotter.Text(slobtawk[Math.floor(Math.random() * slobtawk.length)], {
      family : "Verdana, serif",
      size : 80,
      fill : "#ffffff",
      paddingLeft : 40,
      paddingRight : 40
  });

var material = new Blotter.LiquidDistortMaterial();


var blotter = new Blotter(material, {
  texts : text
});

var elem = document.getElementById("slazy");
var scope = blotter.forText(text);

scope.appendTo(elem);
  }
  
$(document ).ready(setupB)


</script>

<!-- Homeless cats madder: -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-89580040-7"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-89580040-7');
</script>
