<html>
	<head>
		<meta charset="UTF-8" />
		<meta name="viewport" content="width=device-width,
		initial-scale=1.0">
		<meta http-equiv="X-UA-Compatible" content="IE=edge">
		<title>My frist project </title>
		<style type="text/css">
			nav{
				color:blue;
				font-size:17px;
			}
			h1{
				color:green;
			}
			#about-me h2{
				color:blue;
				text-align:center;
			}
			#about-me{
				color:gray;
			}
			#hobby h2{
				color:blue;
				text-align:center;
			}
			#hobby{
				color:gray;
			}
			#education h2{
				color:blue;
				text-align:center;	
			}
			#education table{
				border-collapse: collapse;
				width:100%;
				height:25%;
			}
			#education th{
				color:green;
				padding:10px;
			}
			#education td{
				color:gray;
				text-align:center;
		    }
		    #contact-me{
		    	color:blue;
		    	text-align:center;
		    }
		    #form input{
		    	width:100%;
		    	height:35px;
		    	border-radius:5px;	
		    }
		    body{
		     background-color:#E3E6E3;
		    }
		    .white{
		     background-color:white;
		    }
		    
		    
		    
			
						
		    
		</style>
	</head>
	
	<body>
		<header> <h1>My first project of html </h1> </header>
		<!---header is end here--->
		
		<nav> 
			<ul type="square">
				<li><b>HOME</b></li>
				<li><b>Details</b></li>
				<li><b>About Me</b></li>
				<li><b>Contact With Me</b></li>
			</ul>
		</nav>
		
		<main>
			<section id="about-me">
				<h2>About Me:</h2>
				<strong> Hi I am Maruf Islam. I have been learning html about 2 months.
				</strong>
				I am a student. I read in class 10. I am a SSC candidate. I am 17 years old. I live at Badda at Dhaka in Bangladesh. My home district is Pirojpur
			</section> <br>
			<section id="hobby">
				<h2>My Hobby:</h2>
				<ol>
					<b><li>Reading books</li>
					<li>Playing Cricket</li>
					<li>Travelling</li></b>
				</ol>
			
			</section>
			<section id="education">
				
				<h2>Education: </h2>
					<table border="1px">
						<thead>
							<tr>
								<th>Degree</th>
								<th>Board</th>
								<th>Result</th>
								<th>Year of passing</th>
							</tr>
						</thead>
						<tbody>
							<tr>
								<td>PSC</td>
								<td>Dhaka</td>
								<td>4.83</td>
								<td>2016</td>
							</tr>
							<tr>
								<td> JSC </td>
								<td> Dhaka </td>
								<td> 3.64 </td>
								<td> 2019 </td>
							</tr>
						</tbody>
					</table>
				
			</section>
			
				<h2 id="contact-me">Contact Me:</h2>
				<form id="form">
					<div>
						<label for="name">Name:</label>
						<input type="text" name="name" id="name" tabindex="1" class="white" required >
					</div> <br>
					
					<div>
						<label for="email">Email:</label>
						<input type="email" name="email" id="email" tabindex="2" class="white" required>
					</div> <br>
					<input type="submit" value="Register">
					
				</form>
				
			
			<section id="more-information">
				<details>
					<summary>More Information </summary> <br>
				    Email: marufpc2004@gmail.com <br>
				    Cell: 013145
					
				</details>
			</section>
			
		</main> <br>
		<footer>
		 	Maruf Islam &copy; 2022 <br>
		 	Thanks everyone&#127799;
		</footer>
		
		
		
		
	 	
	
		
	</body>


</html>
