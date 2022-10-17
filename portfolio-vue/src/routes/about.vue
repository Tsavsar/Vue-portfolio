<script setup>
import { ref } from "vue";
import capacitor from "../assets/imgs/capacitor.png";
import mapbox from "../assets/imgs/mapboxlogo.png";
import Vuejs from "../assets/imgs/image_2022-10-07_100639671-removebg-preview.png";

console.log(capacitor);
</script>

<template>
  <div class="row">
    <h1 class="rot">ABOUT</h1>

    <div class="col">
      <div class="txt">
        <span class="hd">I'M</span> <br />
        MCHIAGA T SHATER
      </div>
      <br />
      <div class="p">
        A Front-end Web developer with Vuejs and a skilled UI Designer and UX Researcher.
      </div>
      <br />
      <div class="p">
        I am constantly looking to improve on what I know while trying to contibute as much as i
        can.
      </div>
      <br />
      <div class="p">My notable skills incude Javascript, HTML, CSS, UI Design using Figma</div>
      <br />
      <br />

      <div>
        <div class="norm p">I’VE <span class="bol">WORKED</span> WITH</div>
        <div class="row center left">
          <div class="dis css">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512">
              <!--! Font Awesome Pro 6.2.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
              <path
                d="M0 32l34.9 395.8L192 480l157.1-52.2L384 32H0zm313.1 80l-4.8 47.3L193 208.6l-.3.1h111.5l-12.8 146.6-98.2 28.7-98.8-29.2-6.4-73.9h48.9l3.2 38.3 52.6 13.3 54.7-15.4 3.7-61.6-166.3-.5v-.1l-.2.1-3.6-46.3L193.1 162l6.5-2.7H76.7L70.9 112h242.2z"
              />
            </svg>
          </div>

          <div class="dis html">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512">
              <!--! Font Awesome Pro 6.2.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
              <path
                d="M0 32l34.9 395.8L191.5 480l157.6-52.2L384 32H0zm308.2 127.9H124.4l4.1 49.4h175.6l-13.6 148.4-97.9 27v.3h-1.1l-98.7-27.3-6-75.8h47.7L138 320l53.5 14.5 53.7-14.5 6-62.2H84.3L71.5 112.2h241.1l-4.4 47.7z"
              />
            </svg>
          </div>

          <div class="dis js">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
              <!--! Font Awesome Pro 6.2.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
              <path
                d="M0 32v448h448V32H0zm243.8 349.4c0 43.6-25.6 63.5-62.9 63.5-33.7 0-53.2-17.4-63.2-38.5l34.3-20.7c6.6 11.7 12.6 21.6 27.1 21.6 13.8 0 22.6-5.4 22.6-26.5V237.7h42.1v143.7zm99.6 63.5c-39.1 0-64.4-18.6-76.7-43l34.3-19.8c9 14.7 20.8 25.6 41.5 25.6 17.4 0 28.6-8.7 28.6-20.8 0-14.4-11.4-19.5-30.7-28l-10.5-4.5c-30.4-12.9-50.5-29.2-50.5-63.5 0-31.6 24.1-55.6 61.6-55.6 26.8 0 46 9.3 59.8 33.7L368 290c-7.2-12.9-15-18-27.1-18-12.3 0-20.1 7.8-20.1 18 0 12.6 7.8 17.7 25.9 25.6l10.5 4.5c35.8 15.3 55.9 31 55.9 66.2 0 37.8-29.8 58.6-69.7 58.6z"
              />
            </svg>
          </div>

          <div class="hs">
            <img class="hs" :src="capacitor" />
          </div>

          <div class="hs1">
            <img class="hs1" :src="mapbox" />
          </div>

          <div class="hs2">
            <img class="hs2 vue" :src="Vuejs" />
          </div>
        </div>
      </div>
    </div>

    <div class="con">
      <h><span class="big">CONNECT</span><br />WITH ME</h>
      <div class="row">
        <a href="https://github.com/Tsavsar">
          <div class="svg git">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 496 512">
              <!--! Font Awesome Pro 6.2.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
              <path
                d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3.3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5.3-6.2 2.3zm44.2-1.7c-2.9.7-4.9 2.6-4.6 4.9.3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3.7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3.3 2.9 2.3 3.9 1.6 1 3.6.7 4.3-.7.7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3.7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3.7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z"
              />
            </svg>
          </div>
        </a>
        <a href="https://twitter.com/akuma_virussama">
          <div class="svg twt">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
              <!--! Font Awesome Pro 6.2.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
              <path
                d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z"
              />
            </svg>
          </div>
        </a>
        <div class="svg ig">
          <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
            <!--! Font Awesome Pro 6.2.0 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license (Commercial License) Copyright 2022 Fonticons, Inc. -->
            <path
              d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z"
            />
          </svg>
        </div>
      </div>
    </div>
  </div>
</template>
<style>
.js:hover {
  fill: #f3e314;
}

.css:hover {
  fill: #244ce4;
}

.html:hover {
  fill: #e44c24;
}

.vue:hover {
  box-shadow: 0 5px 15px rgba(60, 179, 124, 0.4);
}

.left {
  margin-left: 130px;
  margin-top: 30px;
}

.hs2 {
  width: 184px;
  height: 96px;
  margin-right: 30px;
}

.hs1 {
  width: 245px;
  height: 55px;
  margin-right: 30px;
}

.hs {
  width: 245px;
  height: 46px;
  margin-right: 30px;
}

.dis {
  width: 60px;
  height: 84.65px;
  margin-right: 30px;
}

.bol {
  font-family: Lato;
  font-size: 40px;
  font-weight: 800;
  line-height: 48px;
  letter-spacing: 0em;
}
.norm {
  font-family: Lato;
  font-size: 40px;
  font-weight: 400;
  line-height: 48px;
  letter-spacing: 0em;
}

.twt:hover {
  fill: blue;
}

.svg {
  width: 50px;
  height: 49px;
  margin-right: 10px;
  margin-top: 15px;
}

.big {
  font-family: "Lato";
  font-style: normal;
  font-weight: 800;
  font-size: 35px;
  line-height: 42px;
  width: 237px;
  color: #000000;
}

.con {
  margin-left: 30px;
  font-family: "Lato";
  font-style: normal;
  font-weight: 500;
  font-size: 25px;
  line-height: 30px;
  color: #000000;
}

.col {
  display: flex;
  flex-direction: column;
}

.center {
  align-items: center;
}

.row {
  display: flex;
  flex-direction: row;
}

.rot {
  transform: rotate(-90deg);
  font-family: "Lato";
  font-style: normal;
  font-weight: 800;
  font-size: 45px;
  line-height: 54px;
  width: 357px;
  height: 53px;
  /* identical to box height */

  color: #000000;
}

.hd {
  font-family: "Lato";
  font-style: normal;
  font-weight: 500;
  font-size: 40px;
  line-height: 48px;
  /* identical to box height */

  color: #929090;
}

.txt {
  margin-left: 130px;

  font-family: "Lato";
  font-style: normal;
  font-weight: 800;
  font-size: 45px;
  line-height: 54px;
  /* identical to box height */
  color: #000000;
}

.p {
  font-family: "Lato";
  font-style: normal;
  font-weight: 500;
  font-size: 33px;
  line-height: 40px;
  margin-left: 130px;
  color: #000000;
  width: 929px;
}
</style>
