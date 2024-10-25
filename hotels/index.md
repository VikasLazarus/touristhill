---
layout: pages
title:  "Hotels"
date:   2024-09-09 05:16:52 -0700
permalink: /hotels/index.html
---
 <div class="w3-row-padding w3-padding-16 w3-container">
    <div class="w3-content">
      <div class="w3-row">
        
        
        

        <h1 class="w3-text-dark-gray w3-xlarge"><strong>Explore Best Hotels</strong></h1>
 
        <p class="w3-text-grey">Experiance The Best Stay In Himachal With Us.</p>
      <hr style="margin:2px 0px; border-top:2px solid #ff5722; border-radius:30px; width:40%;">
<div class="w3-row">

      <div class="w3-col s12 m12 l12 w3-white" style="padding:0px 0px; padding-top:6px;">
        <!-- Swiper -->
        <div class="swiper mySwiper w3-text-gray">
          <div class="swiper-wrapper">
            <div class="swiper-slide slide-1 w3-button w3-hover-none w3-small w3-hover-text-teal tablink w3-text-teal"
              onclick="openCity(event,'Explore')">
              <i class="fas fa-hotel w3-large"></i>
              <br>

              <strong>Hotels</strong>
            </div>
            <div class="swiper-slide slide-1 w3-button w3-hover-none w3-small w3-hover-text-teal tablink"
              onclick="openCity(event,'London')">
              <i class="fas fa-mountain w3-large"></i>
              <br>
              <strong>Shimla</strong>
            </div>
            <div class="swiper-slide slide-1 w3-button w3-hover-none w3-small w3-hover-text-teal tablink"
              onclick="openCity(event,'Paris')">
              <i class="fas fa-skiing-nordic w3-large"></i><br>
              <strong>Manali</strong>
            </div>
            <div class="swiper-slide slide-1 w3-button w3-hover-none w3-small w3-hover-text-teal tablink"
              onclick="openCity(event,'Tokyo')">
              <i class="fa fa-heart w3-large" aria-hidden="true"></i> <br>
              <strong>Honeymoon</strong>
            </div>


            <div class="swiper-slide slide-1 w3-button w3-hover-none w3-small w3-hover-text-teal ">
              <i class="fa-solid fa-mountain-sun w3-large"></i><br>
              <strong>Dharamshala</strong>
            </div>
          </div>

        </div>



      </div>

</div>

        <hr>
 <div class="w3-content">
        <div class="w3-row w3-row-padding" style="margin: 0px -16px;">

  
  {% for page in site.pages %}
      {% if page.categories contains 'Hotel' %}
        
        <div class="w3-third w3-row w3-margin-bottom">
<a href="{{ page.url }}">

            <div class="w3-row w3-display-container" style="height: 290px; width:100%;">
              <img class="w3-border w3-border-light-gray"  alt="{{page.title}}" src="{{site.url}}/images/{{page.img1}}"
                style=" border-radius: 10px; object-fit: cover; overflow: hidden; height: 100%; width: 100%;">
<div class="w3-display-topright" style="padding: 12px;">
   <div style="background-color: #00000080; padding: 2.5px 7px; border-radius: 30px;">
    <i style="margin-top: 6px;" class="w3-large w3-text-light-gray fa-regular fa-heart"></i>
</div>
</div>



            </div>

            <div class="w3-row">

              <div class="w3-row w3-margin-top">
                <div class="w3-left w3-text-gray"><b><i class="w3-text-gray fas fa-map-marker-alt" style="margin-right: 6px;"></i> {{ page.location }}</b></div>
                <div class="w3-right w3-text-gray">
                  <svg width="15px" height="15px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path d="M9.15316 5.40838C10.4198 3.13613 11.0531 2 12 2C12.9469 2 13.5802 3.13612 14.8468 5.40837L15.1745 5.99623C15.5345 6.64193 15.7144 6.96479 15.9951 7.17781C16.2757 7.39083 16.6251 7.4699 17.3241 7.62805L17.9605 7.77203C20.4201 8.32856 21.65 8.60682 21.9426 9.54773C22.2352 10.4886 21.3968 11.4691 19.7199 13.4299L19.2861 13.9372C18.8096 14.4944 18.5713 14.773 18.4641 15.1177C18.357 15.4624 18.393 15.8341 18.465 16.5776L18.5306 17.2544C18.7841 19.8706 18.9109 21.1787 18.1449 21.7602C17.3788 22.3417 16.2273 21.8115 13.9243 20.7512L13.3285 20.4768C12.6741 20.1755 12.3469 20.0248 12 20.0248C11.6531 20.0248 11.3259 20.1755 10.6715 20.4768L10.0757 20.7512C7.77268 21.8115 6.62118 22.3417 5.85515 21.7602C5.08912 21.1787 5.21588 19.8706 5.4694 17.2544L5.53498 16.5776C5.60703 15.8341 5.64305 15.4624 5.53586 15.1177C5.42868 14.773 5.19043 14.4944 4.71392 13.9372L4.2801 13.4299C2.60325 11.4691 1.76482 10.4886 2.05742 9.54773C2.35002 8.60682 3.57986 8.32856 6.03954 7.77203L6.67589 7.62805C7.37485 7.4699 7.72433 7.39083 8.00494 7.17781C8.28555 6.96479 8.46553 6.64194 8.82547 5.99623L9.15316 5.40838Z" fill="#4caf50"></path>
                  </svg>
                  <span class="w3-text-green">4.5 </span>(360)
                </div>
              </div>
              <h3 class="w3-text-dark-gray" style="font-size: 20px; margin: 8px 0px;  overflow: hidden;
            display: -webkit-box;
            -webkit-line-clamp: 2;
            font-weight: 700;
            -webkit-box-orient: vertical;">{{ page.title }}</h3>


<p style="line-height: 1.5em; height: 3em; overflow: hidden;">{{page.discription}}</p>


              


              <b class="w3-xlarge" style="margin-top: 0px;">INR {{ page.price }} <span class="w3-small w3-text-gray">{{ page.price-per }}</span> </b>
          <br><strike class="w3-text-gray">INR {{ page.price-strike }}</strike>  
        </div></a>

            


          </div>

     
        
    {% endif %}
  {% endfor %}

          </div>

      </div>


       </div>
  
      
    </div>
  </div>