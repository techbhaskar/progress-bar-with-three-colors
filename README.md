
# progress bar with three colors without text
	
	<!doctype html>
	<html>
	<head>
	<meta charset="utf-8">
	<title>progress bar with three colors</title>
	<style>
	#progressbar {
	  float: left;
	  width:100%;
	  height:20px;
	  background-color: #ececec;
	}
	#progressbar .succ {
	  background-color: #337ab7;
	  width: 20%;
	  height:100%;
	  float: left;
	}
	#progressbar .fail {
	  background-color: #f0ad4e;
	  width: 30%;
	  height:100%;
	  float: left;
	}
	#progressbar .remain {
	  background-color: #d9534f;
	  width: 40%;
	  height:100%;
	  float: left;
	}
	</style>
	</head>
	<body>
		<div id="progressbar">
		  <div class="succ"></div>
		  <div class="fail"></div>
		  <div class="remain"></div>
		</div>
	</body>
	</html>
# progress bar with three colors with text

	<!doctype html>
	<html>
	<head>
	<meta charset="utf-8">
	<title>Test</title>
	<style>
	#progressbar {
	  float: left;
	  width:100%;
	  height:20px;
	  background-color: #ececec;
	}

	#progressbar .succ {
	  background-color: #337ab7;
	  width: 20%;
	  height:100%;
	  float: left;
	  color:#FFF;
	  text-align:center;
	}
	#progressbar .fail {
	  background-color: #f0ad4e;
	  width: 30%;
	  height:100%;
	  float: left;
	  color:#FFF;
	  text-align:center;
	}
	#progressbar .remain {
	  background-color: #d9534f;
	  width: 40%;
	  height:100%;
	  float: left;
	  color:#FFF;
	  text-align:center;
	}
	</style>
	</head>
	<body class="author-page">
		<!--  Wrapper  -->
		<div id="progressbar">
		  <div class="succ">20%</div>
		  <div class="fail">30%</div>
		  <div class="remain">40%</div>
		</div>
	</body>
	</html>


