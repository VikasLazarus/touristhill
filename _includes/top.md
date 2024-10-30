 <!--end-->
<style>
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
        left: 90%;
        top: 0px;
        opacity: 0;
      }
    }
</style>

  <div class="w3-row w3-text-white w3-teal" style="background:url({{site.url}}/images/texture.png); padding: 1px 12px ;  z-index: 4;">
    <div class="aa"></div>
    <div class="w3-content" style="max-width: 1100px;">
      <span class="w3-col l12  m12 s12 w3-small w3-center" style="padding: 8px 0px ;"><span><b style="font-weight:900;">Winter Sale!</b> Save Up To <b style="font-weight:900;">70% Off</b> On Your Trip
        </span>


    </span></div>
  </div>