<html>
<head>
<style>

input, button, select, option, textarea{
font-size: 100px;
}
</style>
<script type="text/javascript">
  function toggleLike(score,btId){
    play(btId);
    winnerYet();
  }
  function play(btId){
  var space = [];
  var i, count;
  count = 0;
  space[0] = document.getElementById("a1").value;
  space[1] = document.getElementById("a2").value;
  space[2] = document.getElementById("a3").value;
  space[3] = document.getElementById("b1").value;
  space[4] = document.getElementById("b2").value;
  space[5] = document.getElementById("b3").value;
  space[6] = document.getElementById("c1").value;
  space[7] = document.getElementById("c2").value;
  space[8] = document.getElementById("c3").value;
  
  for(i = 0; i < space.length; i++){
	if(space[i] == " ")
		count++;
	}
	
 if((count == 9) || (count == 7) || (count == 5) || (count == 3) || (count == 1)) 
	document.getElementById(btId).value = "X";
if((count == 8) || (count == 6) || (count == 4) || (count == 2))
	document.getElementById(btId).value = "O";
  }
  function winnerYet(){
  var one = document.getElementById("a1").value;
  var two = document.getElementById("a2").value;
  var three = document.getElementById("a3").value;
  var four = document.getElementById("b1").value;
  var five = document.getElementById("b2").value;
  var six = document.getElementById("b3").value;
  var seven = document.getElementById("c1").value;
  var eight = document.getElementById("c2").value;
  var nine = document.getElementById("c3").value;
  if(((one =='X') && (two == 'X') && (three == 'X')) || ((four == 'X') && (five == 'X') && (six == 'X')) || ((seven == 'X') && (eight == 'X') && (nine == 'X')) || ((one == 'X') && (five == 'X') && (nine == 'X')) || ((three == 'X') && (five == 'X') && (seven == 'X')) || ((one == 'X') && (four == 'X') && (seven == 'X')) || ((two == 'X') && (five == 'X') && (eight == 'X')) || ((three == 'X') && (six == 'X') && (nine == 'X')))
	window.alert("X is winner!");
  if(((one =='O') && (two == 'O') && (three == 'O')) || ((four == 'O') && (five == 'O') && (six == 'O')) || ((seven == 'O') && (eight == 'O') && (nine == 'O')) || ((one == 'O') && (five == 'O') && (nine == 'O')) || ((three == 'O') && (five == 'O') && (seven == 'O')) || ((one == 'O') && (four == 'O') && (seven == 'O')) || ((two == 'O') && (five == 'O') && (eight == 'O')) || ((three == 'O') && (six == 'O') && (nine == 'O')))
	window.alert("O is winner!")
  }
  function celebration(){
  
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
