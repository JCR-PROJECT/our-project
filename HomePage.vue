<template>
    <h1> MICP ICT SCHOOL </h1>

<div style="padding:20px;margin-top:30px;background-color:skyblue;height:1500px;">
  <h2>Enrollment Form</h2>
  <p>Please fill out the online enrollment form with your information .<br> Read terms and conditions carefully. The MICP ICT Admins will<br> review your request and contact you shortly by email or phone.<br> Thank you for completing our online enrollment form!</p> 
<form action="/HomePage.php">
 <div class="container">
    <label for="name"><b>Full Name : </b></label> 
    <input type="text" placeholder="Enter your Full Name" name="name" id="name" required> <br>

    <label for="address"><b>Home Address : </b></label>
    <input type="text" placeholder="Enter your home address" name="name" id="name" required> <br>

    <label for="contact"><b>Contact  : </b></label>
    <input type="text" placeholder="Enter a valid phone  number" name="name" id="name" required> <br>

    <label for="birthplace"><b>Place of Birth : </b></label>
    <input type="text" placeholder="Enter your place of birth" name="name" id="name" required> <br>

    <label for="birthdate"><b>Birth Date  : </b></label>
    <input type="text" placeholder="MM/DD/YY" name="name" id="name" required> <br>

     
<a href="SecondPage.vue" class="next">Next Page &raquo;</a>


</div>
</form>



</div>

</template>
<style>
h1 {
  background-color: #3BACB6;
  position: fixed;
  top:0;
  width: 100%;
}
body {font-family: Arial, Helvetica, sans-serif;}
* {box-sizing: border-box}

input[type=text], input[type=password] {
  width: 50%;
  padding: 8px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: none;
  background: #f1f1f1;
}

input[type=text]:focus, input[type=password]:focus {
  background-color: #ddd;
  outline: none;
}

button {
  background-color: #04AA6D;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}

button:hover {
  opacity:1;
}


.cancelbtn {
  padding: 14px 20px;
  background-color: #f44336;
}


.cancelbtn, .signupbtn {
  float: left;
  width: 50%;
}

.container {
  padding: 16px;
}


.clearfix::after {
  content: "";
  clear: both;
  display: table;
}

@media screen and (max-width: 300px) {
  .cancelbtn, .signupbtn {
     width: 100%;
  }
}

a:hover {
  background-color: #ddd;
  color: black;
}

.next {
  color: black;
}

</style>