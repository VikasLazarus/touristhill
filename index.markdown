---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
  <div class="w3-row">

    <div id="Explore" class="city">


      <div class="w3-row w3-light-gray s12 m3 l3 w3-center  w3-container w3-hide-large w3-hide-medium"
        style="height: 50px; display: flex; align-items: center; justify-content: center; padding: 3px 20px;">
        <div class="w3-col  s4 m4 l4 w3-button w3-teal w3-small "
          style=" border-radius: 30px 0px 0px 30px;">
          <strong>Tours</strong>
        </div>
         <div class="w3-col  s4 m4 l4 w3-button  w3-small w3-white w3-border-right w3-border-left w3-border-light-gray" style="border-radius: 0px 0px 0px 0px;">
          <strong>Hotels</strong>
        </div>
        <div class="w3-col  s4 m4 l4 w3-button  w3-small w3-white" style="border-radius: 0px 30px 30px 0px;">
          <strong>Activites</strong>
        </div>

      </div>



      <div class="w3-content w3-hide w3-margin-top" style="padding: 6px 14px;">
        <div class="w3-container w3-card w3-text-dark-gray w3-padding-16 w3-round w3-teal" style="border-radius: 15px;">
          <div class="w3-container w3-content w3-center w3-padding-16 w3-text-white">
            <p class="w3-margin">-- Hurry Limited Time Offer --</p>
            <p class="w3-large"><strong>Get 20% Off On First Booking</strong></p>
             

            <a><button onclick="document.getElementById('id01').style.display='block'"
                class="w3-round w3-card w3-button w3-white w3-text-dark-gray w3-small"><b>Book Now</b></button>
            </a>
            <a href="tel:+918219750359"><button class="w3-round w3-card w3-button w3-white w3-text-dark-gray w3-small"><b>Call
                  Now</b></button></a>
          </div>
        </div>
      </div>

      


{% for category in site.categories %}
 
  <div class="w3-large w3-content w3-padding w3-text-dark-gray">
        <h2 class="w3-large w3-col s8 m8 l8"><strong>Tours In  {{ category | first }}</strong></h2> <a href="{{site.url}}/destination/{{ category | first | downcase }}.html"><span
          class="w3-right w3-col w3-text-dark-gray w3-small" style="width: 70px;">View All <i
            style="padding:3px 5px; border-radius: 30px; margin-top: 15px;"
            class="w3-card w3-teal fa-solid fa-angle-right"></i></span></a>
      </div>
      <br>
   <div class="swiper mySwiper2 w3-content w3-padding">
        <div class="swiper-wrapper">
    {% for post in category.last %}
    <div class="swiper-slide slide-2 w3-row">

            <a href="{{ post.url }}.html">
              <div class="w3-row w3-display-container" style="height: 290px; width:320px;">
                <img class="w3-card-4" src="images/shimla.jpg"
                  style=" border-radius: 10px; object-fit: cover; overflow: hidden; height: 100%; width: 100%;">




              </div>

              <div class="w3-row">

                <div class="w3-row w3-margin-top">
                  <div class="w3-left w3-text-gray"><b>4 Nights 5 Days</b></div>
                  <div class="w3-right w3-text-gray">
                    <svg width="15px" height="15px" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                      <path
                        d="M9.15316 5.40838C10.4198 3.13613 11.0531 2 12 2C12.9469 2 13.5802 3.13612 14.8468 5.40837L15.1745 5.99623C15.5345 6.64193 15.7144 6.96479 15.9951 7.17781C16.2757 7.39083 16.6251 7.4699 17.3241 7.62805L17.9605 7.77203C20.4201 8.32856 21.65 8.60682 21.9426 9.54773C22.2352 10.4886 21.3968 11.4691 19.7199 13.4299L19.2861 13.9372C18.8096 14.4944 18.5713 14.773 18.4641 15.1177C18.357 15.4624 18.393 15.8341 18.465 16.5776L18.5306 17.2544C18.7841 19.8706 18.9109 21.1787 18.1449 21.7602C17.3788 22.3417 16.2273 21.8115 13.9243 20.7512L13.3285 20.4768C12.6741 20.1755 12.3469 20.0248 12 20.0248C11.6531 20.0248 11.3259 20.1755 10.6715 20.4768L10.0757 20.7512C7.77268 21.8115 6.62118 22.3417 5.85515 21.7602C5.08912 21.1787 5.21588 19.8706 5.4694 17.2544L5.53498 16.5776C5.60703 15.8341 5.64305 15.4624 5.53586 15.1177C5.42868 14.773 5.19043 14.4944 4.71392 13.9372L4.2801 13.4299C2.60325 11.4691 1.76482 10.4886 2.05742 9.54773C2.35002 8.60682 3.57986 8.32856 6.03954 7.77203L6.67589 7.62805C7.37485 7.4699 7.72433 7.39083 8.00494 7.17781C8.28555 6.96479 8.46553 6.64194 8.82547 5.99623L9.15316 5.40838Z"
                        fill="#4caf50" />
                    </svg>
                    <span class="w3-text-green">4.5 </span>(360)
                  </div>
                </div>
                <h3 class="w3-text-dark-gray" style="font-size: 20px; margin: 8px 0px;  overflow: hidden;
              display: -webkit-box;
              -webkit-line-clamp: 2;
              font-weight: 700;
              -webkit-box-orient: vertical;">{{ post.title }}</h3>

<div class="w3-row" style="padding: 3px 12px; border-radius: 7px;background-image: linear-gradient(#f1f1f1, #ffffff00);" >
  2D Shimla 2D Manali
</div>

                


                <b class="w3-xlarge" style="margin-top: 0px;">INR 36,000 <span class="w3-small w3-text-gray">Per Couple</span> </b>
            <br><strike class="w3-text-gray">INR 46,000</strike>  
          </div>
            </a>
            <div class="w3-row">
              <div class="w3-col" style="width: 50px;">
                <button class="w3-button w3-small w3-border w3-border-teal"
                  style="width: 34px; height: 34px; padding: 0px; border-radius: 30px;">
                  <i class="fa fa-phone w3-text-teal"></i>
                </button>
              </div>
              <div class="w3-rest">
                <button class="w3-card w3-button w3-small w3-teal" style="border-radius: 30px;">Request
                  Callback</button>

              </div>
            </div>


          </div>
      
    {% endfor %}
              

            <div class="swiper-slide w3-row w3-round" style="width:90px; height:310px;">

            <div class="w3-round" style="padding:0px 0px;">


              <a href="https://touristhill.in/category/Adventure">
                <div class=" w3-center" style="margin-top:60px; padding:14px 0px;">

                  <svg xmlns="http://www.w3.org/2000/svg"
                    style="padding:10px; border-radius:50px; border:2px solid #393E46;" height="30px" width="30px"
                    fill="none" viewBox="0 0 24 24" stroke="#ff5722
  " stroke-width="2">
                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 5l7 7-7 7"></path>
                  </svg>
                  <div class="w3-small w3-text-dark-gray"><b>View All <span
                        class="w3-hide-small w3-hide-medium w3-hide-large">Destinatons</span></b></div>
                </div>
              </a>
            </div>


          </div>

        </div>

      </div>

      
    
      <hr>
{% endfor %}


      

          

      </div>

    <div id="London" class="city" style="display:none">



      <div class="w3-large w3-content w3-padding w3-text-dark-gray">
        <h2 class="w3-large w3-col s8 m8 l8"><strong>Tours In Shimla</strong></h2>
      </div>
      <br>

      <div class="w3-content w3-padding">
        <div class="w3-row w3-row-padding" style="margin: 0px -16px;">

  {% for post in site.categories.Shimla %}
    {% if post.url %}
        
        <div class="w3-third w3-row w3-margin-bottom">
<a href="{{ post.url }}.html">

            <div class="w3-row w3-display-container" style="height: 290px; width:100%;">
              <img class="w3-card-4" src="images/shimla.jpg"
                style=" border-radius: 10px; object-fit: cover; overflow: hidden; height: 100%; width: 100%;">




            </div>

            <div class="w3-row">

              <div class="w3-row w3-margin-top">
                <div class="w3-left w3-text-gray"><b>4 Nights 5 Days</b></div>
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
            -webkit-box-orient: vertical;">{{ post.title }}</h3>

<div class="w3-row" style="padding: 3px 12px; border-radius: 7px;background-image: linear-gradient(#ff572226, #ffffff00);">
2D Shimla 2D Manali
</div>

              


              <b class="w3-xlarge" style="margin-top: 0px;">INR 36,000 <span class="w3-small w3-text-gray">Per Couple</span> </b>
          <br><strike class="w3-text-gray">INR 46,000</strike>  
        </div></a>

            <div class="w3-row">
              <div class="w3-col" style="width: 50px;">
                <button class="w3-button w3-small w3-border w3-border-teal"
                  style="width: 34px; height: 34px; padding: 0px; border-radius: 30px;">
                  <i class="fa fa-phone w3-text-teal"></i>
                </button>
              </div>
              <div class="w3-rest">
                <button class="w3-card w3-button w3-small w3-teal" style="border-radius: 30px;">Request
                  Callback</button>

              </div>
            </div>


          </div>

     
        
    {% endif %}
  {% endfor %}

          </div>

      </div>
    </div>

    <div id="Paris" class="w3-container w3-border city" style="display:none">
      <h2>Paris</h2>
      <p>Paris is the capital of France.</p>
    </div>

    <div id="Tokyo" class="w3-container w3-border city" style="display:none">
      <h2>Tokyo</h2>
      <p>Tokyo is the capital of Japan.</p>
    </div>
  </div>

  <script>
    function openCity(evt, cityName) {
      var i, x, tablinks;
      x = document.getElementsByClassName("city");
      for (i = 0; i < x.length; i++) {
        x[i].style.display = "none";
      }
      tablinks = document.getElementsByClassName("tablink");
      for (i = 0; i < x.length; i++) {
        tablinks[i].className = tablinks[i].className.replace(" w3-text-teal", "");
      }
      document.getElementById(cityName).style.display = "block";
      evt.currentTarget.className += " w3-text-teal";
    }
  </script>
