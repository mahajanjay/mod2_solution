<!DOCTYPE html>
<html>
<head>
<style>
	h1 {
		text-align: center;
	}
	* {
  box-sizing: border-box;
  
}
	#color {
		background-color: gray; 
	}
	p {
  border: 1px solid black;
  background-color: #555;
  width: 100px;
  height: 150px;
  margin-right: auto;
  margin-left: auto;
  font-family: Helvetica;
  color: white;
  padding: 10px;
  clear: bottom;
  
} 

.row {
	width: 100%;
}

@media (min-width: 992px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
   
  }
  .col-lg-1 {
    width: 8.33%;
  }
  .col-lg-2 {
    width: 16.66%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-4 {
    width: 33.33%;
  }
  .col-lg-5 {
    width: 41.66%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-7 {
    width: 58.33%;
  }
  .col-lg-8 {
    width: 66.66%;
  }
  .col-lg-9 {
    width: 74.99%;
  }
  .col-lg-10 {
    width: 83.33%;
  }
  .col-lg-11 {
    width: 91.66%;
  }
  .col-lg-12 {
    width: 100%;
  }
}


@media (min-width: 768px) and (max-width: 991px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
   
  }
  .col-md-1 {
    width: 8.33%;
  }
  .col-md-2 {
    width: 16.66%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-4 {
    width: 33.33%;
  }
  .col-md-5 {
    width: 41.66%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-7 {
    width: 58.33%;
  }
  .col-md-8 {
    width: 66.66%;
  }
  .col-md-9 {
    width: 74.99%;
  }
  .col-md-10 {
    width: 83.33%;
  }
  .col-md-11 {
    width: 91.66%;
  }
  .col-md-12 {
    width: 100%;
    margin-left: 0%;
    margin-right: 0%;
  }
}

@media (max-width: 767px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
   
  }
  .col-sm-1 {
    width: 8.33%;
  }
  .col-sm-2 {
    width: 16.66%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-4 {
    width: 33.33%;
  }
  .col-sm-5 {
    width: 41.66%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-7 {
    width: 58.33%;
  }
  .col-sm-8 {
    width: 66.66%;
  }
  .col-sm-9 {
    width: 74.99%;
  }
  .col-sm-10 {
    width: 83.33%;
  }
  .col-sm-11 {
    width: 91.66%;
  }
  .col-sm-12 {
    width: 100%;
  }
}


#p1 {
	background-color: #0000ff;
	position: relative;
	width: 15%;
	height: 10%;
	text-align: center;
}
#p2 {
	background-color: #010101;
	position: relative;
	width: 15%;
	height: 10%;
	text-align: center;
}
#p3 {
	background-color: #ff00ff;
	position: relative;
	width: 15%;
	height: 10%;
	
	text-align: center;
}
div#container {
  background-color: #555;
  position: relative; 
  top: 60px;
  border: 10px solid white;
  padding: 10px;                                            
  float: left;
}
</style>
</head>
<body>
<h1>Our Menu</h1>
<div class="row">
	
<div class="col-lg-4 col-md-6 col-sm-12" id="container" ><p id="p1">flower</p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</div>


<div class="col-lg-4 col-md-6 col-sm-12" id="container"><p id="p2">fruit</p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</div>


<div class="col-lg-4 col-md-12 col-sm-12" id="container"><p id="p3">tree</p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.</div>
</div>

</body>
</html>
