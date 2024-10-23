<!DOCTYPE html>
<html lang="en">
<head>
<title>{{page.title}}</title>
<link rel="icon" type="image/x-icon" href="{{site.url}}/images/logo.png">
<meta name="description" content="{{page.discription}}">
  <meta name="keywords" content="{{page.keywords}}">
  <meta name="author" content="Tourist hill">
  <meta name="google-adsense-account" content="ca-pub-3313624136394536">
  <script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-3313624136394536"
     crossorigin="anonymous"></script>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="{{site.url}}/style.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Poppins">
<script type="application/ld+json">
{
    "@context" : "https://schema.org",
    "@type" : "WebSite",
    "name" : "Tourist Hill Travels",
    "url" : "https://touristhill.in"
}
</script>
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
  max-width: 1200px;
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

<div class="w3-row  w3-content w3-hide-small">
<div class="w3-half" style="padding-right: 6px; padding-top: 8px; padding-left: 16px;"  >

    <div class="w3-row "style="height: 320px; border-radius: 15px 0px 0px 15px;">
        <img class="w3-border w3-border-light-gray" alt="Shimla Manali Adventure Package" style="object-fit: cover; overflow: hidden; height: 100%; width: 100%; border-radius: 15px 0px 0px 15px;" src="{{site.url}}/images/{{page.img1}}" />
      
    </div>

</div>
<div class="w3-half" style="height: 320px;">
    <div class="w3-half" style="padding-top:8px;">
        <div class="w3-row " style="height: 157px;">
            <img class="w3-border w3-border-light-gray" alt="Shimla Manali Adventure Package" style="object-fit: cover; overflow: hidden; height: 100%; width: 100%; " src="{{site.url}}/images/{{page.img2}}" />
      
        </div>
        <div class="w3-row " style="height: 157px; margin-top: 6px;">
            <img class="w3-border w3-border-light-gray" alt="Shimla Manali Adventure Package" style="object-fit: cover; overflow: hidden; height: 100%; width: 100%;" src="{{site.url}}/images/{{page.img3}}" />
      
        </div>
    </div>
    <div class="w3-half" style="padding-top:8px; padding-left: 6px; padding-right: 16px;">
        <div class="w3-row " style="height: 157px;">
            <img class="w3-border w3-border-light-gray" alt="Shimla Manali Adventure Package" style="object-fit: cover; overflow: hidden; height: 100%; width: 100%; border-radius: 0px 15px 0px 0px;" src="{{site.url}}/images/{{page.img4}}" />
      
        </div>
        <div class="w3-row " style="height: 157px; margin-top: 6px;">
            <img class="w3-border w3-border-light-gray" alt="Shimla Manali Adventure Package" style="object-fit: cover; overflow: hidden; height: 100%; width: 100%; border-radius: 0px 0px 15px 0px;" src="{{site.url}}/images/{{page.img5}}" />
      
        </div>
    </div>
</div>

</div>
<!-- Header mobile-->

<div style="--swiper-navigation-color: #ffffff00; --swiper-pagination-color: #ff5722;" class="w3-hide-large w3-hide-medium w3-display-container swiper mySwiper3">
    <div class="w3-display-bottomleft w3-white w3-hide-large w3-hide-medium" style="box-shadow: 0 4px 10px 0 rgba(0, 0, 0, 0.19), 0 4px 20px 0 rgba(0, 0, 0, 0.2); ; z-index: 30; width: 100%; border-radius: 15px 15px 0px 0px; padding: 0px 18px; margin-bottom: -3px;">
      <div class="w3-row w3-margin-bottom" style="margin-top: 30px;">
        <div class="w3-col s6 m6 l6"><strong class="w3-text-gray"><i class="w3-text-gray fas fa-map-marker-alt" style="margin-right: 6px;"></i> {{ page.location }}</strong></div>
        <div class="w3-col s6 m6 l6 w3-right"><div class="w3-right w3-text-gray">
          <svg width="15px" height="15px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M9.15316 5.40838C10.4198 3.13613 11.0531 2 12 2C12.9469 2 13.5802 3.13612 14.8468 5.40837L15.1745 5.99623C15.5345 6.64193 15.7144 6.96479 15.9951 7.17781C16.2757 7.39083 16.6251 7.4699 17.3241 7.62805L17.9605 7.77203C20.4201 8.32856 21.65 8.60682 21.9426 9.54773C22.2352 10.5006 21.3968 11.4691 19.7199 13.4299L19.2861 13.9372C18.8096 14.4944 18.5713 14.773 18.4641 15.1177C18.357 15.4624 18.393 15.8341 18.465 16.5776L18.5306 17.2544C18.7841 19.8706 18.9109 21.1787 18.1449 21.7602C17.3788 22.3417 16.2273 21.8115 13.9243 20.7512L13.3285 20.4768C12.6741 20.1755 12.3469 20.0248 12 20.0248C11.6531 20.0248 11.3259 20.1755 10.6715 20.4768L10.0757 20.7512C7.77268 21.8115 6.62118 22.3417 5.85515 21.7602C5.08912 21.1787 5.21588 19.8706 5.4694 17.2544L5.53498 16.5776C5.60703 15.8341 5.64305 15.4624 5.53586 15.1177C5.42868 14.773 5.19043 14.4944 4.71392 13.9372L4.2801 13.4299C2.60325 11.4691 1.76482 10.5006 2.05742 9.54773C2.35002 8.60682 3.57986 8.32856 6.03954 7.77203L6.67589 7.62805C7.37485 7.4699 7.72433 7.39083 8.00494 7.17781C8.28555 6.96479 8.46553 6.64194 8.82547 5.99623L9.15316 5.40838Z" fill="#4caf50"></path>
          </svg>
          <span class="w3-text-green">4.5 </span>(360)
        </div></div>
  
      </div>
    </div>


    <div class="swiper-wrapper w3-display-container">
  
  
  
      <div class="swiper-slide" style="height: 570px; width: 100%;">
        <img alt="Shimla Manali Adventure Package" style="object-fit: cover; overflow: hidden; height: 100%; width: 100%;" src="{{site.url}}/images/{{page.img1}}" />
      </div>
      <div class="swiper-slide" style="height: 570px; width: 100%;">
        <img alt="Shimla Manali Adventure Package" style="object-fit: cover; overflow: hidden; height: 100%; width: 100%;" src="{{site.url}}/images/{{page.img2}}" />
      </div>
      <div class="swiper-slide" style="height: 570px; width: 100%;">
        <img alt="Shimla Manali Adventure Package" style="object-fit: cover; overflow: hidden; height: 100%; width: 100%;" src="{{site.url}}/images/{{page.img3}}" />
      </div>
      <div class="swiper-slide" style="height: 570px; width: 100%;">
        <img alt="Shimla Manali Adventure Package" style="object-fit: cover; overflow: hidden; height: 100%; width: 100%;" src="{{site.url}}/images/{{page.img4}}" />
      </div>
      <div class="swiper-slide" style="height: 570px; width: 100%;">
        <img alt="Shimla Manali Adventure Package" style="object-fit: cover; overflow: hidden; height: 100%; width: 100%;" src="{{site.url}}/images/{{page.img5}}" />
      </div>
   
    </div>
    <div class="swiper-pagination w3-hide-large w3-hide-medium" style="margin-top: -100px;"></div>
</div>



  <div class="w3-row w3-white">
    <div class="w3-content">
     
      <div class="w3-col l8 s12">
        <div class="w3-row w3-round w3-padding ">
         
       
    
         
         
       
        <div class="w3-row w3-hide-small" style="height: 25px;"> </div>
          
        
  
          <h1 class="w3-text-dark-gray" style=" font-size: 28px; margin: 2px 0px;
              font-weight: 700;">{{page.title}}</h1>
              <div class="w3-row">
              <div class="w3-tag w3-sand" style="borde-radius:30px;">
              <i class="w3-text-dark-gray fa-solid fa-share-from-square"></i> Share
              </div>
              </div>
              <div class="w3-row w3-margin-top">
                <p>{{page.detail}}</p>
              </div>
  <hr>
  <div class="w3-hide-large">
          <p><b class="w3-xlarge">INR {{ page.price }} <span class="w3-small w3-text-gray">{{ page.price-per }}</span></b> 
            <br><strike class="w3-text-gray">INR {{ page.price-strike }}</strike></p>
          
  <hr>
  </div>
  <div class="w3-row">
    <div class="w3-col s12 m4 l4" style="padding: 6px 0px;">
      <i class="fa-solid fa-taxi w3-text-gray" style="margin-right: 6px;"></i> <strong class="w3-text-gray">Transfer Included</strong>
    </div>
    <div class="w3-col s12 m4 l4" style="padding: 6px 0px;">
      <i class="fas fa-bed w3-text-gray" style="margin-right: 6px;"></i> <strong class="w3-text-gray">Stay Included</strong>
    </div>
    <div class="w3-col s12 m4 l4" style="padding: 6px 0px;">
      <i class="fa-solid fa-utensils w3-text-gray" style="margin-right: 12px;"></i> <strong class="w3-text-gray">Breakfast & Dinner Included</strong>
    </div>
    <div class="w3-col s12 m4 l4" style="padding: 6px 0px;">
      <i class="fa-solid fa-images w3-text-gray" style="margin-right: 8px;"></i> <strong class="w3-text-gray">Sightseeing Included</strong>
    </div>
  </div>
  
  <hr>
  
        </div>

        
  <div class="w3-row">
    <h2 class="w3-large w3-padding w3-text-dark-gray"><strong>Trip Duration</strong></h2>
    <div style="padding: 0px 12px;">
    <span class="w3-tag w3-light-gray w3-col w3-center w3-text-dark-gray" style="padding: 0px 20px; margin-right: 6px; margin-top:10px; height: 31px; width: fit-content; border-radius: 15px; display: flex;
                align-items: center;
                justify-content: center;"><strong>4 Nights | 5 Days</strong></span>
                </div>
  </div>
  
  <div class="w3-row ">
    <h2 class="w3-large w3-padding w3-text-dark-gray"><strong>Destination Routes</strong></h2>
    <div class="w3-row w3-light-gray w3-padding w3-margin" style="border-radius: 15px; padding: 0px 12px;">
   <strong class="w3-text-dark-gray w3-small">Chandighrar <i class="fa-solid fa-arrow-right"></i> Shimla <i class="fa-solid fa-arrow-right"></i> Manali <i class="fa-solid fa-arrow-right"></i> Chandigarh </strong>
                </div>
  </div>
  
  <div class="w3-row ">
    <h2 class="w3-large w3-padding w3-text-dark-gray"><strong>Stay Category</strong></h2>
    <div class="w3-tag w3-light-gray w3-padding w3-margin" style="border-radius: 15px; padding: 0px 12px;">
   <strong class="w3-text-dark-gray">Delux Property</strong>
                </div>
  </div>
  
  <hr>
        <div class="w3-row">
    <h2 class="w3-large w3-padding w3-text-dark-gray"><strong>Trip Hightlights</strong></h2>
    <ul class="w3-text-gray">
      <li>
  <strong class="w3-text-dark-gray">Rohtang Pass:</strong> Drive to one of the highest motorable roads in the world and enjoy panoramic views.
      </li>
      <li>
        <strong class="w3-text-dark-gray">Solang Valley:</strong> Engage in various adventure activities like paragliding, skiing, and zorbing.
      </li>
      <li>
        <strong class="w3-text-dark-gray">Hadimba Temple:</strong> Visit this ancient temple dedicated to the goddess Hadimba and explore the surrounding Van Vihar.
      </li>
      <li>
        <strong class="w3-text-dark-gray">Hadimba Temple:</strong> Visit this ancient temple dedicated to the goddess Hadimba and explore the surrounding Van Vihar.
      </li>
  <li>
    <strong class="w3-text-dark-gray">Vashisht Village:</strong> Relax in the hot springs and visit the ancient Vashisht Temple.
  </li>
  <li>
    <strong class="w3-text-dark-gray">Scenic Drives:</strong> Enjoy breathtaking views during your journey between Shimla and Manali.
  </li>
  <li>
   <strong class="w3-text-dark-gray">Local Markets:</strong> Explore the vibrant markets of Shimla and Manali for souvenirs and local handicrafts.
  </li>
    </ul>
  </div>
  
 
  </div>
  
    
  
  
  
  
  
    <div class="w3-col l4 s12 w3-hide-small" style="object-fit: contain; padding: 6px 6px; position: sticky; top: 0px;">
      <div class="w3-row w3-round w3-padding">
  
        <div class="w3-row">
          <div class="w3-row w3-display-container w3-border w3-border-light-gray w3-padding" style="border-radius: 15px;">
            <div class="w3-display-topright w3-padding">
              <div class="w3-right w3-text-gray w3-small">
                <svg width="15px" height="15px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path d="M9.15316 5.40838C10.4198 3.13613 11.0531 2 12 2C12.9469 2 13.5802 3.13612 14.8468 5.40837L15.1745 5.99623C15.5345 6.64193 15.7144 6.96479 15.9951 7.17781C16.2757 7.39083 16.6251 7.4699 17.3241 7.62805L17.9605 7.77203C20.4201 8.32856 21.65 8.60682 21.9426 9.54773C22.2352 10.5006 21.3968 11.4691 19.7199 13.4299L19.2861 13.9372C18.8096 14.4944 18.5713 14.773 18.4641 15.1177C18.357 15.4624 18.393 15.8341 18.465 16.5776L18.5306 17.2544C18.7841 19.8706 18.9109 21.1787 18.1449 21.7602C17.3788 22.3417 16.2273 21.8115 13.9243 20.7512L13.3285 20.4768C12.6741 20.1755 12.3469 20.0248 12 20.0248C11.6531 20.0248 11.3259 20.1755 10.6715 20.4768L10.0757 20.7512C7.77268 21.8115 6.62118 22.3417 5.85515 21.7602C5.08912 21.1787 5.21588 19.8706 5.4694 17.2544L5.53498 16.5776C5.60703 15.8341 5.64305 15.4624 5.53586 15.1177C5.42868 14.773 5.19043 14.4944 4.71392 13.9372L4.2801 13.4299C2.60325 11.4691 1.76482 10.5006 2.05742 9.54773C2.35002 8.60682 3.57986 8.32856 6.03954 7.77203L6.67589 7.62805C7.37485 7.4699 7.72433 7.39083 8.00494 7.17781C8.28555 6.96479 8.46553 6.64194 8.82547 5.99623L9.15316 5.40838Z" fill="#4caf50"></path>
                </svg>
                <span class="w3-text-green">4.5 </span>(360)
              </div>
            </div>
            <p><b class="w3-xlarge">INR 36,000 <span class="w3-small w3-text-gray">Per Couple</span></b> 
              <br><strike class="w3-text-gray">INR 46,000</strike></p>
  
              <hr>
  
              <div class="w3-row w3-margin-bottom">
                <div class="w3-col" style="width: 40px;">
                  <button class="w3-button w3-small w3-sand" style="width: 34px; height: 34px; padding: 0px; border-radius: 30px;">
                  <i class="fa fa-phone w3-text-teal"></i>
                  </button>
                </div>
                <div class="w3-rest">
                  <button class="w3-button w3-small w3-teal" style="border-radius: 30px;">Send Enquiry</button>
              
                </div>
              </div>
  
          </div>
        </div>
        
        <div class="">
          
          <div class="w3-text-dark-gray w3-border w3-margin-top w3-border-light-gray" style="border-radius: 15px;">
            <div class="w3-padding">
                <h2 class="w3-large"><strong>
                      {{page.title}}
                    </strong></h2>
                    <p><b class="w3-xlarge">INR {{page.price}} <span class="w3-small w3-text-gray">{{page.price-per}}</span></b> 
                      <br><strike class="w3-text-gray">INR {{page.price-strike}}</strike></p>
  
            </div>
            <form class="w3-text-dark-gray w3-row w3-padding" onsubmit="alert('Thanks For Submiting The Form. Our Executives Will Reach To You Within 24 Hours');" method="page">
              <div style="margin-bottom: 6px;" class="elem-group w3-col s12 m12 l12">
  
                <input style="border-radius: 15px;" class=" w3-input w3-round w3-tiny w3-border" type="text" id="name" name="visitor_name" placeholder="Full Name" pattern="[A-Z\sa-z]{3,20}" required="">
              </div>
             <div class="elem-group w3-col s12 m12 l12" style="margin-bottom: 6px;">
  
                <input style="border-radius: 15px;" class=" w3-input w3-round w3-tiny w3-border" type="email" id="email" name="visitor_email" placeholder="john.doe@email.com" required="">
              </div>
              <div class="elem-group w3-col s12 m12 l12" style="margin-bottom: 6px;">
  
                <input style="border-radius: 15px;" class="w3-input w3-round w3-tiny w3-border" type="tel" id="phone" name="visitor_phone" placeholder="Mobile Number" pattern="(\d{3})-?\s?(\d{3})-?\s?(\d{4})" required="">
              </div>
  
              <div class=" w3-col s12 m12 l12" style="margin-bottom: 6px;">
                <input style="border-radius: 15px;" class=" w3-input w3-round w3-tiny w3-border" type="number" id="adult" name="total_adults" placeholder="Travelrs Count" min="1" required="">
              </div>
              
             
                <div class="w3-left">
                  <label style="height: 35px; display: flex;
                  align-items: center;
                  justify-content: center;" class="w3-col s6 m6 l6" for="checkout-date">Travel date</label>
                  <input  style="margin-bottom: 4px; border-radius: 15px;" class="w3-col s6 m6 l6 w3-input w3-round w3-tiny w3-border" type="date" id="checkout-date" name="checkout" required="">
                </div>
                <button class="w3-button w3-round w3-text-white w3-margin-top w3-margin-bottom w3-left w3-teal w3-small" style="border-radius: 30px;" type="submit">Send Enquiry</button>
              
              </div>
  
            </form>
          </div>
        </div>
  
      </div>
    </div>
  

    </div>













<!-- Footer -->


<!-- Footer -->
 
{% include footer.md %}
 
<!-- Swiper JS -->
<script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>

<!-- Initialize Swiper -->
 <!-- Initialize Swiper -->
  <script>
    var swiper = new Swiper(".mySwiper4", {
      loop: true,
      autoplay: {
        delay: 2500,
        disableOnInteraction: false,
      },
      slidesPerView: 3,
      centeredSlides: true,
      spaceBetween: 10,
      pagination: {
        el: ".swiper-pagination",
        clickable: true,
      },
    });
  </script>
<script>
  
  var swiper = new Swiper(".mySwiper2", {
      slidesPerView: "auto",
      spaceBetween: 20,
      

      pagination: {
        el: ".swiper-pagination",
        clickable: true,
      },
    });

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
