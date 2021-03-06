<!DOCTYPE html>
<html lang="en-us">

<head>
    <!-- Required meta tags -->
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

  <!-- Bootstrap CSS -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
  <link rel="stylesheet" href="styles.css">

  <title>Latitude Plots</title>
</head>

<body style="background-color: lightgray;">

    <nav class="navbar navbar-expand-lg navbar-light bg-light">

        <div class="container-fluid">

            <b><a class="navbar-brand brand" href="#">Latitude</a></b>
        
            <div class="collapse navbar-collapse justify-content-end" id="navbarNavDropdown">
                <ul class="nav navbar-nav">
            
                    <li class="nav-item dropdown">
                        <a class="nav nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                        Plots
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                        <a class="dropdown-item" href="maxtemp.html">Max Temperature</a>
                        <a class="dropdown-item" href="humidity.html">Humidity</a>
                        <a class="dropdown-item" href="cloudiness.html">Cloudiness</a>
                        <a class="dropdown-item" href="windspeed.html">Wind Speed</a>           
                        </div>
                    </li>
            
                    <li class="nav-item">
                    <a class="nav-link" href="comparison.html">Comparison</a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link" href="data.html">Data</a>
                    </li>
                </ul>
            </div>

            <div class="pos-f-t">
                <div class="collapse" id="navbarToggleExternalContent">
                <div class="p-4">
                    <span class="text-muted"><a class="dropdown-item" href="maxtemp.html">Max Temperature</a></span>
                    <span class="text-muted"><a class="dropdown-item" href="humidity.html">Humidity</a></span>
                    <span class="text-muted"><a class="dropdown-item" href="cloudiness.html">Cloudiness</a></span>
                    <span class="text-muted"><a class="dropdown-item" href="windspeed.html">Wind Speed</a></span>
                </div>
                </div>
                <nav class="navbar">
                <button class="navbar-toggler"  type="button" data-toggle="collapse" data-target="#navbarToggleExternalContent" aria-controls="navbarToggleExternalContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                </nav>
            </div>    
        </div>
    </nav>

    <br>
    <br>

    <div class="container-fluid">
        <div class="row justify-content-md-center">
            <div class="col-md-6 col-sm-3 container_cust" style="max-width: 1000px; height: 675px; margin-right: 30px; padding-right: 50px; padding-left:30px">
                <br><br><br>
                <h1 class="container_head">Summary: Latitude vs. X</h1>
                <hr> <br>                
                <img class="float-left" src="Resources\assets\images\Fig1.png" alt="maxtemp" height="300" width="300" style="margin-right:30px;">    
                
                <p style="padding-top: 25px;line-height:2;font-size:125%;">
                    The purpose of this project was to analyze how weather changes as you get closer to the equator. To accomplish this analysis, we first pulled data from the 
                    OpenWeatherMap API to assemble a data set on over 500 cities.
                </p>

                <br/>
                <br/>                            

                <p style="line-height:2;font-size:125%;">
                    After assembling the dataset, we used MatplotLib to plot various aspects of the weather vs latitude.  Factors we looked at included:
                    temperature, cloudiness, wind speed, and humidity.  This site provides the source data and visualizations created as part of the 
                    analysis, as well as explanations and descriptions of any trends and correlations witnessed.
                </p>
            </div>

            <div class="col-md-6 col-sm-3 container_cust" style="max-width: 530px;height: 635px; padding-left:30px">
                <br><br>
                <h2 class="container_head">Visualizations</h2>

                <hr>

                <div class="row">
                    <div class="col-md-5 col-sm-3">
                        <a href="maxtemp.html">
                            <img src="Resources\assets\images\Fig1.png" alt="maxtemp" height="250" width="250" style="padding:0%">
                        </a>
                    </div>
                    <div class="col-md-5 col-sm-3">
                        <a href="humidity.html">
                            <img src="Resources\assets\images\Fig2.png" alt="maxtemp" height="250" width="250" style="padding:0%">
                        </a>
                    </div>

                    <div class="w-100 d-none d-md-block"></div>

                    <div class="col-md-5 col-sm-3">
                        <a href="cloudiness.html">
                            <img src="Resources\assets\images\Fig3.png" alt="maxtemp" height="250" width="250" style="padding:0%">
                        </a>    
                    </div>
                    <div class="col-md-5 col-sm-3">
                        <a href="windspeed.html">
                            <img src="Resources\assets\images\Fig4.png" alt="maxtemp" height="250" width="250" style="padding:0%">
                        </a>
                    </div>
                </div>
            </div>              
        </div>
    </div>       

    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>   
   
</body>
</html>