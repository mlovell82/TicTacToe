<html>
<head>
<script type="text/javascript">
  function toggleLike(score,btId){
    if(score == " "){
      document.getElementById(btId).value = "X";
    }else if{
      document.getElementById(btId).value = "O";
    }
    
  }
</head>
<body>

<table>
  <tr>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="score"></td>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="score"></td>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="score"></td>
  </tr>
  <tr>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="score"></td>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="score"></td>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="score"></td>
  </tr>
  <tr>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="score"></td>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="score"></td>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="score"></td>
  </tr>
</table>


</body>
</html>
