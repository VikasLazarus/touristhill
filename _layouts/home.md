<!DOCTYPE html>
<html lang="en">

<head>
  <title>{{site.title}}</title>
  <link rel="icon" type="image/x-icon" href="images/favicon.svg">
  <meta name="description"
    content="India travel packages, Himalayan treks, cultural tours, adventure tourism, personalized itineraries.">
  <meta name="keywords"
    content="Himachal Pradesh tourism, India travel packages, Shimla tour, Manali tour, Himalayan treks, cultural tours India, adventure tourism India, tailor-made travel India, experienced travel guides India, unforgettable travel experiences India">
  <meta name="author" content="Tourist hill">
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="style.css">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Poppins">

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />

  <style>
    .w3-round {
      border-radius: 30px;
    }
    a {
      text-decoration: none;
    }

    body,
    h1,
    h2,
    h3,
    h4,
    h5,
    h6 {
      font-family: "Poppins"
    }

    .w3-bar,
    h1,
    button {
      font-family: "Poppins"
    }

    .w3-content {
      max-width: 1100px;
    }


    .swiper {
      width: 100%;
      height: 100%;
    }




    .slide-1 {
      width: fit-content;
    }

    .slide-2 {



      height: 530px;
      width: 320px;
      border-radius: 10px;
    }

    .aa {
      overflow: hidden;
      width: 15px;
      height: 36px;
      transform: skewX(-20deg);
      background-image: linear-gradient(to right, #ffffff, #ffffff00, #ffffff, #ffffff);
      opacity: 0.3;
      position: absolute;
      animation-name: example;
      animation-duration: 6s;
      animation-timing-function: linear;
      animation-delay: 1s;
      animation-iteration-count: infinite;
      animation-direction: right;
    }

    @keyframes example {
      0% {
        left: 0%;
        top: 0px;
        opacity: 0;
      }

      25% {
        left: 25%;
        top: 0px;
        opacity: 0.3;
      }

      50% {
        left: 50%;
        top: 0px;
        opacity: 0.5;
      }

      75% {
        left: 75%;
        top: 0px;
        opacity: 0.3;
      }

      100% {
        left: 100%;
        top: 0px;
        opacity: 0;
      }
    }
  </style>
</head>

<body>



{% include top.md %}
  <!-- Navbar -->
{% include nav-home.md %}

  <!-- Header -->









  <!-- Second Grid -->



 {{ content }}



{% include footer.md %}
 



</body>

</html>