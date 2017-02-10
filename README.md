# Noodling
Noodling with code, for fun.
         "CLOCK"



function printTime() {
  var now = new Date();
  var hours = now.getHours();
  var min = now.getMinutes();
  var seconds = now.getSeconds();
  
  document.write(hours+":"+min+":"+seconds+ " <br/> ");
  
}
setInterval("printTime()", 1000);





