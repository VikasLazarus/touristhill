<!DOCTYPE html>
<html lang="en">

<head>
  <title>{{page.title}}</title>
  <link rel="icon" type="image/x-icon" href="../images/logo.png">
  <meta name="description"
    content="India travel packages, Himalayan treks, cultural tours, adventure tourism, personalized itineraries.">
  <meta name="keywords"
    content="Himachal Pradesh tourism, India travel packages, Shimla tour, Manali tour, Himalayan treks, cultural tours India, adventure tourism India, tailor-made travel India, experienced travel guides India, unforgettable travel experiences India">
  <meta name="author" content="Tourist hill">
 <meta name="google-adsense-account" content="ca-pub-3313624136394536">
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="../style.css">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Poppins">

  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />
<script type="application/ld+json">
{
    "@context" : "https://schema.org",
    "@type" : "WebSite",
    "name" : "Tourist Hill Travels",
    "url" : "https://touristhill.in/"
}
</script>
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
      max-width: 1200px;
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


  </style>
</head>

<body>



  {% include top.md %}
  <!-- Navbar -->
{% include nav-pages.md %}

  <!-- Header -->

  


 

{{content}}
      
     


  <!--about-->


  <script>
    function openCity(evt, cityName) {
      var i, x, tablinks;
      x = document.getElementsByClassName("city");
      for (i = 0; i < x.length; i++) {
        x[i].style.display = "none";
         document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
      }
      tablinks = document.getElementsByClassName("tablink");
      for (i = 0; i < x.length; i++) {
        tablinks[i].className = tablinks[i].className.replace(" w3-text-teal", "");
      }
      document.getElementById(cityName).style.display = "block";
      evt.currentTarget.className += " w3-text-teal";
    }
    
  </script>
  

 {% include footer.md %}