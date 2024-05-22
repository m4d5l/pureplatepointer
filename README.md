<!DOCTYPE html>
<html>
<head>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
<link rel="stylesheet" href="style.css">

<style>
.imghover:hover {
    background-color: black;
}
.imghover:hover img {
    transition: 0.5s;
    opacity: 0.5;
}

.caption-img1:hover {
    opacity: 1;
}
.caption-img1 h3 {
    font-size: 100px;
}
h1{
 
  text-align: left;
  font-style:normal;
  font-size:20px;

}
.date-time-container {
    display: flex;
            flex-direction: column; 
            align-items: flex-start; 
            margin: 20px 0;
            text-align: right;
        }
        .date-time {
            color: beige;
            font-size: 50px;
            text-align: right;
            font-family: 'Times New Roman', Times, serif;
        }
</style>

<title>PurePlate Pointer </title>	
	
</head>

<body>
   


<div class="nav">
    <nav>
        <label class="logo">PurePlate Pointer</label>
        <ul>
            <li><a href="PurePlate Pointer.html">Home</a></li>
            <li><a href="serv.html">Services</a></li>
            <li><a href="Reviews.html">Reviews</a></li>
            <li><a href="res-Resources Page.html">Resources</a></li>
            <li><a href="AboutUs.html">About Us</a></li>
            <li ><a  href="ContactUs.html">Contact Us</a></li>
            <li ><a  href="calculateBMR.html">BMR</a></li>
            
            
            
        </ul>
    </nav>
    <br>
    <div class="container">
        <div class="row">
            <div class="col-8">
                <p id="midt" style="text-align: left; text-indent: -100px;">Welcome to "PurePlate Pointer!"</p>
            </div>
            <div class="col-4">
                <div id="date" style="text-align: right;text-indent: 100px; " class="date-time"></div>
                <div id="clock" style="text-align: right;text-indent: 100px;" class="date-time"></div>
            </div>
        </div>
    </div>
    
    
    
        
  
    <br><br><br><br><br><br><br>
</div>
<br>
<br>
    <br>
    
   <div class="container-fluid">
<div class="accordion" id="accordionExample">
    <div class="accordion-item">
      <h2 class="accordion-header" id="headingOne">
        <button  id="midt" class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne" style="color: green;" >
          Introducing Pureplate Pointer:
        </button>
      </h2>
      <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
        <div class="accordion-body">
          <strong><p style="font-size: 20px;">Introducing the Pureplate indicator:
            Your ultimate guide to a healthy, vibrant lifestyle! Say goodbye to diet problems with our team of nutritionists and fitness coaches, who are dedicated to overcoming any health challenge you face. In addition, we provide assistance in choosing high-quality, healthy restaurants in Jordan!</p>
        </div>
      </div>
    
</div>


    
<div class="card-container" >
    <div class="card"style="width: 25%;height:10px;height:10px">
        <div class="col">
            <div class="p-3 border bg-light">
        <img src="cc.jpg" alt="f" >
        <div class="card-content">
            <h1> Healthy Restaurants</h1>
            <p style="font-size: 17px;">Healthy restaurants prioritize nutritious and wholesome food options, emphasizing dishes low in unhealthy fats, sugars, and processed ingredients while rich in essential nutrients.</p>
            <a href="res-Resources Page.html" class="btn">Choose your healthy restaurant</a>
        </div>
    </div>
</div>
</div>

    <div class="card"style="width: 25%;height:10px;">
        <div class="col">
            <div class="p-3 border bg-light">
        <img src="f.jpg" alt="f">
        <div class="card-content">
            <h1> Sports Coach</h1>
            <p style="font-size: 17px;">A sports coach promotes a healthy lifestyle by designing exercise programs, emphasizing nutrition, and fostering discipline. They provide guidance on physical fitness.</p>
            <a href="res-Resources Page.html" class="btn">Book an appointment</a>
        </div>
    </div>
</div>
</div>

    <div class="card"style="width: 25%;height:10px;">
        <div class="col">
            <div class="p-3 border bg-light">
        <img src="m.jpeg" alt="m">
        <div class="card-content">
            <h1>Nutritionist</h1>
            <p style="font-size: 17px;">A nutritionist educates individuals on healthy eating habits, develops personalized dietary plans to meet specific health goals, and provides ongoing support and guidance for lifestyle changes.</p>
            <a href="res-Resources Page.html" class="btn">Book an appointment</a>
        </div>
    </div>
</div>
</div>
<br>

<script>
    let timer = setInterval(myTimer);
    function myTimer(){
        const x = new Date();
        document.getElementById("clock").innerHTML = x.toLocaleTimeString();
    }
    let date = setInterval(myDate);
    function myDate(){
        const x = new Date();
        document.getElementById("date").innerHTML = x.toLocaleDateString();
    }
</script>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
</body>
</html>
