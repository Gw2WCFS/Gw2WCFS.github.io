<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Fractal Tomorrow</title>
    <script src="jquery/jquery-3.5.1.min.js"></script>
  </head>
  <body>
    <script></script>
    <p id="test">This is a test.</p>
    <script>
      console.log("beef");
      $(document).ready(function() {
        $.getJSON('https://api.guildwars2.com/v2/achievements/daily/tomorrow',function(data){
            var results = data;
            console.log(results);
          });
        });
      <!-- $("#test").css("background-color","#FF00FF"); -->
    </script>
    </body>
</html>
