<?php

if (isset($_POST["send"])) {

	$to = $_POST["to"];
	$subject = $_POST["subject"];
	$message = $_POST["message"];
	$from = $_POST["from"];
	$name = $_POST["name"];

	if (!(filter_var($to, FILTER_VALIDATE_EMAIL) && filter_var($from, FILTER_VALIDATE_EMAIL))) {
		echo "Email address inputs invalid";
		 die();
	} 

	$header = "From: " .  $name . " <" . $from . ">\r\nMIME-Version: 1.0\r\nContent-type: text/html\r\n";

	$retval = mail ($to, $subject, $message, $header);

	if ($retval) {
		echo "Email sent.";
	} else {
		echo "Email did not send. Error: " . $retval;
	}
} else {
	echo 
	'<html>
		<head>
			<style> 
			body{
				background-color:#3a3a3a;
			}
				input[type=submit] {
				  background-color: #c4c4c4;
				  border: none;
				  color: white;
height:8vh;
				  padding: 14px 32px;
				  text-decoration: none;
				  margin: 4px 2px;
				  cursor: pointer;
				  font-size: 16px;
				  border-radius:10px;
				  width:23vh;
				}
input[type=text] {
				  background-color: #c4c4c4;
				  border: none;
				  border-radius:50px;
				  height:4vh;
				  width:70vh;
				  font-size:1em;
				  color:white;
				  font-size:5em;
				  outline:none;
				  text-decoration:none;
				}
				input#subject{
					font-size:1em;
				}
input#to{
					font-size:1em;
				}
				input#from{
					font-size:1em;
				}
				input#name{
					font-size:1em;
				}
				label{
					color:#c4c4c4;
					
				}
				h2{
					color:white;
					font-family:cursive;
					font-size:4em;
				}
				p{
					color:#c4c4c4;
				}
				.container{
					justify-content:center;
					align-items:center;
					text-align:center;
				}
				textarea{
					background-color:#c4c4c4;
					border:none;
					border-radius:20px;
					height:15vh;
					width:70vh;
					outline:none;
					text-decoration:none;
					font-size:1em;
					color:white;
				}
				label{
					font-size:1.5em;
					font-family:cursive;

				}
				.main{
					margin-bottom:30px;
				}
			</style>

		</head>
		<body>
<div class="container">
			<h2><strong>Soft-Mailer</strong></h2>
			<div class="main">

			<form action="/send.php" method="post" id="emailform">

			  <label for="to">To:</label><br>

			  <input type="text" id="to" name="to"><br><br>

			  <label for="from">From:</label><br>

			  <input type="text" id="from" name="from"><br><br>

			  <label for="name">Name (optional):</label><br>

			  <input type="text" id="name" name="name"><br><br>

			  <label for="subject">Subject:</label><br>

			  <input type="text" id="subject" name="subject"><br><br>

			  <label for="message">Message [HTML is supported]:</label><br>
			  

			  <textarea rows="6" cols="50" name="message" form="emailform"></textarea><br><br>
			  

			  <input type="hidden" id="send" name="send" value="true">

			  <input type="submit" value="Submit">

			</form> 
			<p>An e-mail will be sent to the desired target with a spoofed From header when you click Submit.</p>
			</div>
			</div>

		</body>
	</html>' ;
}


?>