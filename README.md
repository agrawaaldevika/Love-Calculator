<html>

<head>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  
  <style>
 body{background-color:pink;} 
  
  
  </style>
<script>

function lovedata()
  {
  var lovedata = Math.random() * 100;
  lovedata = Math.floor(lovedata);
  document.getElementById('lovevalue').value = lovedata + "%"; }



</script>

</head>
<body>
<center>
<form class= "w-75 m-auto" class="form-group">
  <input name="name" class="form-control text-center" placeholder="Your Name" /> <span class= "pl-4 pr-4">+</span>
  <input name="name" class="form-control text-center" placeholder="Your Partner Name"/><br/><br/>
  <button  class="btn btn-success w-50" OnClick= "lovedata()">Click</button><br/><br/>
  <input name="name" id="lovevalue" class="form-control text-center" placeholder="Result" />
</form>
</center>
 </body>
