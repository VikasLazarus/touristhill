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
        <button class="w3-button w3-teal w3-small w3-card-4" style="border-radius: 30px;">Send Enquiry</button>
      </div>
      <div class="w3-rest">
        <b class="w3-xlarge">INR 36,000 <span class="w3-small w3-text-gray">Per Couple</span></b>
      </div>
    </div>
  </div>

  {% include top.md %}
{% include nav-page.md %}

      
<!-- Header -->





{{ content }}









