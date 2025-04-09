<html>
<body bgcolor="yellow">
Enter fruits No:<br>
<input type="text" id="f"><br>
<input type="button" value="display fruit rate" onclick="fru()">
<script>
function fru()
{
f=document.getElementById("f").value;
switch (f)
{
 case "apple": alert("200 rs per kg");
               break;
 case "banana": alert("60 rs per kg"); 
               break ;
 case "orange": alert("95 rs per kg");
               break;
 case "grapes": alert("100 rs per kg");
               break;
 case "water meton": alert("45 rs per kg");
               break;
 default: alert("not avaliable in our shop");
  }
}
</script>
</body>
</html>
