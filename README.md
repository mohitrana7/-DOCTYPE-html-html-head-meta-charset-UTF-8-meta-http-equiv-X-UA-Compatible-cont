
<!DOCTYPE html>

<html>

<head>
	<meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>BASIC OF "CLOUD COMPUTING"</title>

	<style>
		* {
			margin: 0;
			padding: 0;
		}


		.navbar {
			display: flex;
			align-items: center;
			justify-content: center;
			position: sticky;
			top: 0;
			cursor: pointer;
		}

		.background {
			background: rgb(8, 67, 85);
			background-blend-mode: darken;
			background-size: cover;
		}

		.nav-list {
			width: 70%;
			display: flex;
			align-items: center;
		}

		.logo {
			display: flex;
			justify-content: center;
			align-items: center;
		}

		.logo img {
			width: 80px;
			border-radius: 25px;
		}

		.nav-list li {
			list-style: none;
			padding: 26px 30px;
		}

		.nav-list li a {
			text-decoration: none;
			color: white;
		}

		.nav-list li a:hover {
			color: black;
		}
		.nav-list a.active{
			background-color: rgb(8,67,85);
              color: black;
		}

		.rightnav {
			width: 25%;
			text-align: right;
		}
		@media only screen and (max-width :675px) {
			.nav-list{
				flex-direction: column;

			}
			.nevbar{
				flex-direction: column;
				height: 80px;
			}
			.rightnav{
				text-align: left;
			}
			
		}

		#search {
			padding: 5px;
			font-size: 17px;
			border: 2px solid grey;
			border-radius: 9px;
		}
		#search:hover{
			color:black;
		}

		
		
		.box-main {
			padding: 30px 60px;
			justify-content: center;
			text-align: center;
		}

		
		
		.text-big {
			font-family: 'Piazzolla', serif;
			padding: 30px 60px;
			justify-content: center;
			text-align: center;
			

		}

		.text-small {
			font-size: 18px;
			padding: 30px 60px;
			text-align: center;
		}

		.btn {
			padding: 8px 20px;
			margin: 7px 0;
			border: 2px solid white;
			border-radius: 8px;
			background: none;
			color: white;
			cursor: pointer;
		}

		.btn-sm {
			padding: 6px 10px;
			vertical-align: middle;
		}

		

		.paras {
			padding: 30px 60px;
			text-align: center;
		}

		

		.center {
			text-align: center;
		}

		.text-footer {
			text-align: center;
			padding: 30px 0;
			font-family: 'Ubuntu', sans-serif;
			display: flex;
			justify-content: center;
			color: white;
		}
	</style>
</head>

<body>
	<nav class="navbar background">
		<ul class="nav-list">
			<div class="logo">
				<img src= "CLOUD COMPUTING-g54746adb1_640.png" alt="no internet conrction">
			</div>
			
			<li><a class="active" href="#home">HOME</a></li>
			<li><a href="#details">DETAILS</a></li>
			<li><a href="#about">ABOUTS</a></li>
 		</ul>
           
		<div class="rightNav">
			<input type="text" name="search" id="search">
			<button class="btn btn-sm">Search</button>
		</div>
	</nav>

	
		       <div class="box-main">
				<h1 class="text-big" >WELCOME<br></br>to<br></br>"Cloud Computing"</h1>
				<hr></hr>
				<h2 class="text-big">We are provide the basic information of cloud computing to student,who are interested in cloud computing and new in field of cloud computinng.<br></br>Like:-
				</h2>
				
				<h1>What is cloud computing?</h1>
				<h1 >What are the advantages of cloud computing?</h1>
				<h1 >What are the disadvantages of cloud computing?</h1>
				<h1 >Different types of Clouds</h1>
				<br></br>
				<br></br>
				</div>

				<div class="box-main">
				<h1 class="text-big">What is Cloud Computing?</h1>
				<hr></hr>
				<p class="text-small">
					The term cloud refers to a network or the internet. It is a technology that uses remote servers on the internet to store, manage, and access data online rather than local drives. The data can be anything such as files, images, documents, audio, video, and more.
				</p>
		</div>
		<br></br>
	


		<div class="box-main">
			
				<h1 class="text-big">What are the advantages of cloud computing?</h1>
				<hr></hr>
				<p class="text-small">
					1) <u><b>Back-up & restore data</b><br></u>
                       Once the data is stored in the cloud, it is easier to get back-up&restore that data using the cloud.<br>
                    2) <u><b>Collaboration</b><br></u>
                       Cloud applications improve collaboration by allowing groups of people to quickly and easily share information in the cloud via shared storage.<br>
                    3) <u><b>Low maintenance cost</b><br></u> 
                       Cloud computing reduces both hardware and software maintenance costs for organizations.<br>
                    4) <u><b>Mobility</b><br></u>
                       Cloud computing allows us to easily access all cloud data via mobile.<br>          
				</p>
				<br></br>	
		</div>
	

	
		<div class="paras">
			<h1 class=" text-big">What are the disadvantages of cloud computing?</h1>
<hr></hr>
			<p class="text-small">
				1) <u><b>Internet Connectivity</b><br></u>
				   As you know, in cloud computing, every data (image,audio,video,etc..) is stored on the cloud, and we access these data through the cloud by using the Internet Connection. If you do not have good internet connectivity, you cannot access these data. However, we have no any other way to access data from the cloud.<br>
				2) <u><b>Security</b><br></u>
				   Although cloud service providers implement the best security standards to store important information. But, before adopting cloud technology, you should we aware thatyou will be sending all your organization's sensitive informatiion to a third party, i.e.;a cloud computing service provider. While sending the data on the cloud there may be a chance that your organization's information is hacked by Hackers.<br>     
			</p>
			<br></br>
		</div>
		
		<div class="paras">
			<h1 class=" text-big">Different types of Clouds</h1>
            <h1 class="text-big">There are four types of clouds</h1>
			<hr></hr>
					<p class="text-small">
						1) <u><b>Public Cloud</b></u><br>
						   Public cloud is open to all to store and access information via the Internet using the pay-per-usage method.<br>
						   In public cloud, computing resources are managed and operated by the cloud service provider(CSP).<br>
						   <b>Example:</b>Amazon Elastic Compute Cloud(EC2), Google App Engine.<br>
						2) <u><b>Private Cloud</b></u><br>
						   Private cloud is also known as an internal cloud or corporate cloud. It is used by organizations to build and manage their own data centers internally or by the third party. Itcan be deployed using Opensource tools such as Openstack and Eucalyptus.<br>
						   Private cloud provides a high level of security and privacy to the users.<br>
						   Private cloud offers better performance with improved speed and space capacity.<br>
                        3) <u><b>Hybrid Cloud</b></u><br>
						   <b><i>Hybrid cloud = Public cloud + Private cloud</i></b><br>
						   Hybrid cloud is partially secure because the services which are running on the public cloud can be accessed by anyone, while the services which are running on a private cloud can be accessed only by the organization's users.<br>
						   <b>Example:</b>Office 365, Amazon Web Services.<br>
						4) <u><b>Community Cloud</b></u><br>
						   Community cloud allows systems and services to be accessible by  a group of several organizations to share  the information between the organization and a specifc community. It is owned, managed, and operated by one or more organizations in the community, a third party, or a combnation of them.<br>
                           <b>Example:</b>Health care community cloud.
					</p>
		
		
				</div>
				<br></br>




	<footer class="background">
		<p class="text-footer">
			 Design by @DIVYANSH GUPTA
		</p>


	</footer>
</body>

</html>
