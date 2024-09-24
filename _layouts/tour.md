<!DOCTYPE html>
<html lang="en">
<head>
<title>{{page.title}}</title>
<link rel="icon" type="image/x-icon" href="{{site.url}}/images/favicon.svg">
<meta name="description" content="{{page.discription}}">
  <meta name="keywords" content="{{page.keywords}}">
  <meta name="author" content="Tourist hill">
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="{{site.url}}/style.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Poppins">

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />

<style>
  hr {
    border-bottom: 2px solid #f1f1f1;
    border-top: 2px solid #ffffff;
    border-radius: 30px;
  }
  excluded ul {
  --icon-space: 1.3em;
  list-style: none;
  padding: 0;
}
   included ul {
  --icon-space: 1.3em;
  list-style: none;
  padding: 0;
}
excluded li {
  padding-left: var(--icon-space);
}

excluded li:before {
  content: "\f00d"; /* FontAwesome Unicode */
  font-family: FontAwesome;
  display: inline-block;
  color: red;
  margin-left: calc( var(--icon-space) * -1 );
  width: var(--icon-space);
}
included li {
  padding-left: var(--icon-space);
}

included li:before {
  content: "\f00c"; /* FontAwesome Unicode */
  font-family: FontAwesome;
  display: inline-block;
  color: green;
  margin-left: calc( var(--icon-space) * -1 );
  width: var(--icon-space);
}
.swiper-pagination{
    margin-bottom: 70px;
    
  }
   .swiper-pagination-bullet {
      width: 20px;
      height: 4px;
     
      
    
      opacity: 1;
      background: #ffffff;
      border-radius: 5px;
    }

    .swiper-pagination-bullet-active {
      
      color: #ffffff;
      background: #ff5722;
      border-radius: 5px;
    }

  a{
    text-decoration: none;
  }
body,h1,h2,h3,h4,h5,h6 {font-family: "Poppins"}
.w3-bar,h1,button,p {font-family: "Poppins"}

.w3-content{
  max-width: 1100px;
}


.swiper {
      width: 100%;
      height: 100%;
    }

    
</style>
</head>
<body>

   <!--bottom fixed-->
   <div id="Fixed" class="w3-display-container w3-row w3-white w3-border-top w3-border-light-gray w3-hide-large w3-hide-medium w3-animate-zoom" style="width: 100%; padding:12px; position: fixed; bottom: -190px; left: 0px; z-index: 30;">
   <div class="w3-display-topright" style="padding: 0px 12px; margin-top: -96px;">
   <a href="tel:{{site.phone1}}">
   <div class="w3-ro w3-teal w3-card-4" style="border-radius:30px ; height: 40px; width: 40px;  padding: 8px 12px; margin-right: 6px; margin-bottom: 8px;">
  <i class="w3-text-white  fa fa-phone small" style="padding-left:0px ;"></i>
</div></a>
<a href="https://wa.me/91{{site.phone1}}">
 <div class="w3-ro w3-green w3-card-4" style="border-radius:30px ; height: 40px; width: 40px; padding: 10px 12px; margin-right: 6px;">
      <i class="w3-text-white  fab fa-whatsapp w3-large" style="padding-left:0px ;"></i>
</div>
</a>

   </div>
    <div class="w3-row">
      <div class="w3-col w3-right" style="width: 110px;">
        <button  onclick="document.getElementById('id01').style.display='block'" class="w3-button w3-teal w3-small w3-card-4" style="border-radius: 30px;">Send Enquiry</button>
      </div>
      <div class="w3-rest">
        <b class="w3-xlarge">INR {{page.price}} <span class="w3-small w3-text-gray">{{page.price-per}}</span></b>
      </div>
    </div>
  </div>
<!--model bottom  fixed-->
  <div class="w3-container">

  
    <div id="id01" class="w3-modal" style="background-color: #48484889; z-index: 120;">
      <div class="w3-bottom w3-white w3-card-4"style="border-radius: 15px 15px 0px 0px;">
        <div class="w3-row">
          <span onclick="document.getElementById('id01').style.display='none'" class="w3-button w3-teal w3-opacity-min w3-card-4 w3-display-topright" style="padding: 6px 12px; border-radius: 30px; margin-top: -45px; margin-right: 12px;">&times;</span>
         
         <div class="w3-half w3-padding">
           
            <div class="w3-text-dark-gray" style="border-radius: 15px;">
                <div style="margin-top: 30px;">
                  <h2 class="w3-large"><strong>
                    {{page.title}}
                  </strong></h2>
                  <p><b class="w3-xlarge">INR {{page.price}} <span class="w3-small w3-text-gray">{{page.price-per}}</span></b> 
                    <br><strike class="w3-text-gray">INR {{page.price-strike}}</strike></p>

                </div>
                <hr>
                <form class="w3-text-dark-gray w3-row" onsubmit="alert('Thanks For Submiting The Form. Our Executives Will Reach To You Within 24 Hours');" method="page">
                  <div style="margin-bottom: 6px;" class="elem-group w3-col s12 m12 l12">
      <lable class="w3-small" style="margin-bottom: 4px;">Full Name <span class="w3-text-red">*</span></lable>
                    <input style="border-radius: 15px;" class=" w3-input w3-large w3-round w3-tiny w3-border" type="text" id="name" name="visitor_name" placeholder="Jonh Doe" pattern="[A-Z\sa-z]{3,20}" required="">
                  </div>
                 <div class="elem-group w3-col s12 m12 l12" style="margin-bottom: 6px;">
                    <lable class="w3-small" style="margin-bottom: 4px;">Email Address <span class="w3-text-red">*</span></lable>
                    
                    <input style="border-radius: 15px;" class=" w3-input w3-large w3-round w3-tiny w3-border" type="email" id="email" name="visitor_email" placeholder="john.doe@email.com" required="">
                  </div>
                  <div class="elem-group w3-col s12 m12 l12" style="margin-bottom: 6px;">
                    <lable class="w3-small" style="margin-bottom: 4px;">Contect Number <span class="w3-text-red">*</span></lable>
                    
                    <input style="border-radius: 15px;" class="w3-input w3-large w3-round w3-tiny w3-border" type="tel" id="phone" name="visitor_phone" placeholder="+91-81294-71645" pattern="(\d{3})-?\s?(\d{3})-?\s?(\d{4})" required="">
                  </div>
      <div class="w3-row">
                  <div class=" w3-col s4 m4 l4" style="margin-bottom: 6px;">
                    <lable class="w3-small" style="margin-bottom: 4px;">Traveller Count <span class="w3-text-red">*</span></lable>
                  <input style="border-radius: 15px;" class=" w3-input w3-large w3-round w3-tiny w3-border" type="number" id="adult" name="total_adults" placeholder="Travelrs Count" min="1" required="">
                  </div>

                  <div class="w3-col s8 m8 l8" style="padding-left: 12px;">
                    <lable class="w3-small" style="margin-bottom: 4px;">Travel Date <span class="w3-text-red">*</span></lable>
                  
                     <input  style="margin-bottom: 4px; border-radius: 15px;" class="w3-right-align w3-rest w3-input w3-large w3-round w3-tiny w3-border" type="date" id="checkout-date" name="checkout" required="">
                    </div>

                 </div>
                

                 </div>
                    <div class="w3-row">
                    <button class="w3-large w3-mobile w3-button w3-round w3-text-white w3-margin-top w3-margin-bottom w3-left w3-teal w3-small" style="border-radius: 30px;" type="submit">Connect With a Expert</button>
                </div>  
                  </div>

         </div>
        </div>
      </div>
    </div>
  </div>


  {% include top.md %}
{% include nav-page.md %}

      
<!-- Header -->













{% include inclusion-exclusion.md %}


<!-- Footer -->


<!-- Footer -->
 
{% include footer.md %}
 
<!-- Swiper JS -->
<script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>

<!-- Initialize Swiper -->
<script>
  
  var swiper2 = new Swiper(".mySwiper3", {
    loop: true,
    spaceBetween: 0,
    autoplay: {
        delay: 2500,
        disableOnInteraction: false,
      },
      pagination: {
        el: ".swiper-pagination",
        clickable: true,
        renderBullet: function (index, className) {
          return '<span class="' + className + '">'  + "</span>";
        },
      },
   
  });
</script>
<script>
  function myFunction(id) {
    var x = document.getElementById(id);
    if (x.className.indexOf("w3-show") == -1) {
      x.className += " w3-show";
    } else { 
      x.className = x.className.replace(" w3-show", "");
    }
  }
  </script>

<script>
  // When the user scrolls down 80px from the top of the document, resize the navbar's padding and the logo's font size
  window.onscroll = function() {scrollFunction()};
  
  function scrollFunction() {
    if (document.body.scrollTop > 290 || document.documentElement.scrollTop > 290) {
      document.getElementById("Fixed").style.bottom = "0px";
      
    } else {
      document.getElementById("Fixed").style.bottom = "-180px";
     
    }
  }
  </script>
</body>
</html>
