<html>
<head>
<style>

input, button, select, option, textarea{
font-size: 100px;
}
</style>
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

<table border="3" width="600" height="600">
  <tr>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="a1" style="width:100%; height:100%;"></td>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="a2" style="width:100%; height:100%;"></td>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="a3" style="width:100%; height:100%;"></td>
  </tr>
  <tr>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="b1" style="width:100%; height:100%;"></td>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="b2" style="width:100%; height:100%;"></td>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="b3" style="width:100%; height:100%;"></td>
  </tr>
  <tr>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="c1" style="width:100%; height:100%;"></td>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="c2" style="width:100%; height:100%;"></td>
    <td><input onclick="toggleLike(this.value,this.id)" type="button" value=" " id="c3" style="width:100%; height:100%;"></td>
  </tr>
</table>


</body>

</html>
