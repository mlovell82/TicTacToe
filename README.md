<html>
<head>
<script type="text/javascript">
  function toggleLike(score,btId){
    if(score == " "){
      document.getElementById(btId).value = "X";
    }else if(score == "X"){
      document.getElementById(btId).value = "O";
    }
    
  }
  </script>
  </head>
<body>

<table>
  <tr>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="a1"></td>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="a2"></td>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="a3"></td>
  </tr>
  <tr>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="b1"></td>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="b2"></td>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="b3"></td>
  </tr>
  <tr>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="c1"></td>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="c2"></td>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="c3"></td>
  </tr>
</table>


</body>

</html>
