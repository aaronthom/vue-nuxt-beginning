<script setup>
var mysql = require('mysql');

var con = mysql.createConnection({
  host: "secutimetec.de",
  user: "kalkulator",
  password: "Kalkulator_1"
});

con.connect(function(err) {
  if (err) throw err;
  console.log("Connected!");
  
}); 

</script>