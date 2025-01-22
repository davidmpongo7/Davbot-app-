<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <style>
  body {

  letter-spacing: 0.2em;

  font-size: 0.8em;
}

.container {
  max-width: 400px;
}

#footer {
  padding: 7% 15%;
  text-align: center;
}

.social-icon {
  margin: 20px 10px;
}

@media (max-width: 1028px) {
  #title {
    text-align: center;
  }

  .title-image {
    position: static;
    transform: rotate(0);
  }
}

@media only screen and (max-width: 500px) {
  #title {
    margin-top: -220%;
    color: #010a43;
    right: 30%;
    z-index: 1;
  }
}

@media only screen and (min-width: 992px) {
  #title {
    margin-top: -60%;
    color: #010a43;
    right: 30%;
    z-index: 1;
  }
}

.container-fliud {
  padding: 3% 15% 7%;
}

#banner {
  background-image: linear-gradient(120deg, #91C4FF 0%, #F0F7FF 87%);
  position: relative;
  width: 100%;
  height: 950px;
  z-index: -1;
}

#cloud-scroll {
  background: url(http://9a2e1a2047765d2a004e-e6d2db425d8d4f2619e5cee56a48bcef.r55.cf2.rackcdn.com/clouds.png) repeat-x;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-size: cover;
  position: absolute;
  -webkit-animation: 900000s backgroundScroll infinite linear;
  -moz-animation: 900000s backgroundScroll infinite linear;
  -o-animation: 900000s backgroundScroll infinite linear;
  -ms-animation: 900000s backgroundScroll infinite linear;
  animation: 900000s backgroundScroll infinite linear;
}

@-webkit-keyframes backgroundScroll {
  from {
    background-position: 0 0;
  }

  to {
    background-position: -99999999px 0;
  }
}

@keyframes backgroundScroll {
  from {
    background-position: 0 0;
  }

  to {
    background-position: -99999999px 0;
  }
}
</style>
  <script src="https://kit.fontawesome.com/7e5f32b196.js"></script>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
  <link rel="stylesheet" href="styletest.css">
  <script src="apptest.js"></script>


  <title>Météo</title>
</head>

<body>
  <div id="banner">
   
    <div id="cloud-scroll"></div>
  </div>
  <section id="title" style="top: 0;">
    <div class="container-fluid">
      <nav class="navbar navbar-expand-lg navbar-dark">  <p><b>appuyez sur le bouton rechercher et patientez 5 seconde </b></p>
        <a class="navbar-brand" href="">Davbot météo 🧑‍💻</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link" href="https://www.facebook.com/p/David-Mpongo-Bot-61550884726891/">suivez notre chaîne Facebook 🧑‍💻</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href=" https://www.facebook.com/profile.php?id=100092277325670">contactez moi 🧑‍💻</a>
            </li>
          </ul>
        </div>
      </nav>


      <div class="container my-5 mx-auto">



        <div class=search>


          <form class="change-location my-4 text-center text-muted">

            <input type="text" name="city" placeholder="Entrez le nom de votre ville ou pays " class="form-control p-4">
          </form>
        </div>

        <div class=button>
          <button style="margin-top: -5%;" type="button" class="btn btn-primary btn-lg btn-block">recherchez🧑‍💻</button>
        </div>
        <br>

        <div class=search_button>

          <div class="card shadow-lg rounded d-none ">
            <img src="https://via.placeholder.com/400x300" class="time card-img-top">
            <div class="icon bg-light mx-auto text-center">
            </div>
            <div class="text-muted text-uppercase text-center details  ">
              <h5 class="my-3">City name</h5>
              <div class="my-3">Weather condition</div>
              <div class="display-4 my-4">
                <span>temp</span>
                <span>&deg;C</span>
              </div>
            </div>

          </div>

        </div>

      </div>

      <footer id="footer">
        <i class="social-icon fab fa-facebook-f"></i>
        <i class="social-icon fab fa-instagram"></i>
        <i class="social-icon fab fa-twitter"></i>
        <i class="social-icon fab fa-github"></i>

        <p><b>Fait par 𝑫𝑨𝑽𝑰𝑫 𝑴𝑷 🧑‍💻</b></p>

      </footer>
    </div>
  </section>
  <script>
  window.onload = function() {

  $("button").click(function() {




    const city = cityForm.city.value.trim();
    cityForm.reset();

    updateCity(city)
      .then(data => updateUI(data))
      .catch(err => console.log(err));
  });

  const key ='    Ffj3Rq1uOGdQScHjhAaT9UuxeA8b9Byc ';


  const getWeather = async (id) => {
    const base = 'https://dataservice.accuweather.com/currentconditions/v1/';
    const query = `${id}?apikey=${key}`;
    const response = await fetch(base + query);
    const data = await response.json();

    return data[0];
  };

  const getCity = async (city) => {
    const base = 'https://dataservice.accuweather.com/locations/v1/cities/search';
    const query = `?apikey=${key}&q=${city}`;

    const response = await fetch(base + query);
    const data = await response.json();

    return data[0];

  };



  const cityForm = document.querySelector('form');
  const card = document.querySelector('.card');
  const details = document.querySelector('.details');
  const time = document.querySelector('img.time');
  const icon = document.querySelector('.icon img');


  const updateUI = (data) => {

    const cityDets = data.cityDets;
    const weather = data.weather;


    details.innerHTML = `
<h5 class="my-3">${cityDets.EnglishName}</h5>
<div class="my-3">${weather.WeatherText}</div>
<div class="display-4 my-4">
<span>${weather.Temperature.Metric.Value}</span>
<span>&deg;C</span>
</div>
`;

    let timeSrc = null;
    if (weather.IsDayTime) {
      timeSrc = 'https://i.imgur.com/MbcC6II.jpg';
    } else {
      timeSrc = 'https://i.imgur.com/PKf8NXh.jpg';
    }
    time.setAttribute('src', timeSrc);


    if (card.classList.contains('d-none')) {

      card.classList.remove('d-none');
    }
    card.classList.remove('d-none');
  };

  const updateCity = async (city) => {


    const cityDets = await getCity(city);
    const weather = await getWeather(cityDets.Key);

    return {
      cityDets,
      weather
    };
  };

  if (cityForm) {
    cityForm.addEventListener('submit', e => {

      e.preventDefault();

      const city = cityForm.city.value.trim();
      cityForm.reset();

      updateCity(city)
        .then(data => updateUI(data))
        .catch(err => console.log(err));

    });
  }
}

  </script>
</body>

</html>
<style>
        <link rel="icon" href="http://us2.bot-hosting.net:21194/image/favicon.ico" type="image/ico">
  <link rel="shortcut icon" href="https://frost-afb.vercel.app/image/favicon.ico">
        body{
    background-image: URL('https://i.imgur.com/AnFWx6c.jpeg');
    font-family: Roboto,Helvetica Neue,Arial,sans-serif;
    font-size: 10pt;
    overflow: hidden;
	}
	
	
		
        .game-container {
            background-color:  #ecececb1;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 990px rgba(0, 0, 0, 5.1);
            text-align: center;
        }
        

        h1 {
            margin-bottom: 20px;
        }

        .checkboxes {
            margin-bottom: 20px;
        }

        .checkbox {
            margin: 0 10px;
            transform: scale(1.5);
        }

        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
            background-color: #007bff;
            color: #fff;
        }

        button:hover {
            background-color: #0056b3;
        }

        #message {
            margin-top: 50px;
            font-size:18px;
        }
        
        .btn {
  background-color: #40a1ff;
  color: white;
  padding: 10px 20px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  border-radius: 5px;
      }
    </style> 
<Style>
    body {
  background-color: #000;
  color: #fff;
  font-family: 'Courier New', monospace;
}

h1 {
  font-size: 36px;
  text-align: center;
  text-transform: uppercase;
}

h2 {
  font-size: 24px;
  color: #0f0;
}

p {
  margin-bottom: 20px;
}

ul {
  list-style-type: none;
}

li {
  padding: 10px;
  border: 1px solid #0f0;
  margin: 5px;
}
v{padding: 10px;
  border: 1px solid #ff0;
  margin: 5px;
}
a {
  color: #f00;
  text-decoration: none;
  border: 1px solid #f00;
  padding: 0px 10px;
  margin: 10px;
}

a:hover {
  background-color: #f00;
  color: #000;
    
      </style>
