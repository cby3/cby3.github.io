<doctype html>
<html>
<head>
<body>
<script type="text/javascript">
function Pinger_ping(ip, callback) {

  if(!this.inUse) {

    this.inUse = true;
    this.callback = callback
    this.ip = ip;

    var _that = this;

    this.img = new Image();

    this.img.onload = function() {_that.good();};
    this.img.onerror = function() {_that.good();};

    this.start = new Date().getTime();
    this.img.src = "http://" + ip;
    this.timer = setTimeout(function() { _that.bad();}, 1500);

  }
}
</script>
<script type="text/javascript">
       alert("Disclemer:we hold no responsibility for any individual by continue using this platform you agree to the terms and conditions provided by this platform ");  
   </script>
<meta name="viewport" content="width=device-width, initial-scale=1" />
   <center>
   <img src="usman.jpeg" style="width: 285px; height: 300px" />
   </center>
   <center>
    <code style="color: blue">we are anounymos</code>   
    <center>
     <code style="color: red">CODED BY MALITIOUS CODERS</code>

<body style="background-color: black">
