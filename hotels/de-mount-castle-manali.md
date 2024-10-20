---
layout: hotel
title:  "De Mount Castle Manali"
date:   2024-09-09 05:16:52 -0700
categories: Hotels
permalink: /hotels/de-mount-castle-manali.html
location: Manali
price: "1,300"
price-per: Per Night 
price-strike: "27,000"
price-save: "10,000"
reviews-count: 360
rating: 4.5
img1: placeholder.png
img2: placeholder.png
img3: placeholder.png
img4: placeholder.png
img5: placeholder.png
detail: 
---
<!--Related Packages-->
{% if site.related_page.size >= 1 %}
<div class="w3-large w3-content w3-padding w3-text-dark-gray">
    <h2 class="w3-large w3-col s8 m8 l8"><strong>Related Packages</strong></h2>
  </div>
  <br>
<div class="swiper mySwiper2 w3-content w3-padding">
    <div class="swiper-wrapper">
    {% for related_post in site.related_page limit: 5 %}
    <div class="swiper-slide slide-2 w3-row" style="width:320px; height:520px;">

        <a href="{{ related_post.url }}.html">
          <div class="w3-row w3-display-container" style="height: 290px; width:320px;">
            <img class="w3-border w3-border-light-gray" alt="{{related_post.title}}" src="{{site.url}}/images/{{related_post.img1}}"
              style=" border-radius: 10px; object-fit: cover; overflow: hidden; height: 100%; width: 100%;">




          </div>

          <div class="w3-row">

            <div class="w3-row w3-margin-top">
              <div class="w3-left w3-text-gray"><b><i class="fa fa-clock-o"></i> {{related_post.duration}}</b></div>
              <div class="w3-right w3-text-gray">
               
                <span class=""><i class="fa fa-star w3-text-green"></i> {{related_post.rating}} </span>(<span>{{related_post.reviews-count}}</span>)
              </div>
            </div>
            <h3 class="w3-text-dark-gray" style="font-size: 20px; margin: 8px 0px;  overflow: hidden;
          display: -webkit-box;
          -webkit-line-clamp: 2;
          font-weight: 700;
          -webkit-box-orient: vertical; font-size:16px;">{{ related_post.title }}</h3>

<div class="w3-row" style="padding: 3px 12px; border-radius: 7px;background-image: linear-gradient(#f1f1f1, #ffffff00);" >
{{related_post.duration-days}}
</div>

            


            <b class="w3-xlarge" style="margin-top: 0px;">INR {{related_post.price}} <span class="w3-small w3-text-gray">{{related_post.price-per}}</span> </b>
        <br><strike class="w3-text-gray">INR {{related_post.price-strike}}</strike>  
      </div>
        </a>
        <div class="w3-row">
          <div class="w3-col" style="width: 50px;">
<a href="tel:{{site.phone1}}">
            <button class="w3-button w3-small w3-border w3-border-teal"
              style="width: 34px; height: 34px; padding: 0px; border-radius: 30px;">
              <i class="fa fa-phone w3-text-teal"></i>
            </button></a>
          </div>
          <div class="w3-rest">
            <button class="w3-card w3-button w3-small w3-teal" style="border-radius: 30px;">Request
              Callback</button>

          </div>
        </div>


      </div>
  
    {% endfor %}
</div>

</div>
{% endif %}