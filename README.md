<!DOCTYPE html>
<html>
<title>Radheshyam is learning HTML</title>
<body BGCOLOR="33CFFF">
  
  <h1> Indian flag is tricolour flag  </h1>
  <h2><a href="https://en.wikipedia.org/wiki/Flag_of_India">INDIAN FLAG</a></h2>
  <img src="https://upload.wikimedia.org/wikipedia/en/thumb/4/41/Flag_of_India.svg/383px-Flag_of_India.svg.png">
  
  <p>The three colours from  the top are</p>
  
  <ul>
    <li><p style="color: orange;">Orange</p></li>
    <li><p style="color: gray;">White</p></li>
    <li><p style="color: green;">Green</p></li> 
  </ul>
  
  <p> There is a blue colour ashok chakra in the middle of the flag with 24 spokes in it.</p>

  <h3><a href="https://en.wikipedia.org/wiki/Friends">Friends</a></h3>
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a0/Friends_.jpg/1280px-Friends_.jpg" height=300 width=450>
  <p> Friend are the most precious in any living 's life.Happy friendship day </p>
  
  <h4>FEEDBACK.How much did you like the website?<br>
    Excellent<br>
    Good<br>
    Bad<br>
    Worst</br>
  </h4>

<input id="myInput" type="text">

<button onclick="myFunction()">submit</button>

<p id="demo"></p>

<script>
function myFunction() {
  var feedback = document.getElementById("myInput").value;
  var text;

  // If the feedback is "Bad" or "bad"
  if (feedback === "Bad" || feedback === "bad") {
    text = "Oh,thanks we'll see towards the problems.😑😐😎🙄😏";
    
  // If the feedback is "Excellent" or "Good" or "excellent" or "good"
  } else if (feedback === "Excellent" || feedback === "Good" || feedback === "good" || feedback === "excellent") {
    text = "thank you, we will make it more better.😃😎😀😊😉.."; 
    
  // If the feedback is anything else
  } else {
    text = "Oops! Unable to send feedback please enter something else.🤣😂🤣😎😋😎😉..";
  }
  document.getElementById("demo").innerHTML = text;
}
</script>
    
</body>
</html>
