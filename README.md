<!DOCTYPE html>

<html>

<head>

   <title> Try It Yourself </title>

   <style type="text/css">

      * {

         box-sizing: border-box;

      }

      html, body {

         margin: 0;

         padding: 0;

      }

      .row::after {

         content: "";

         display: block;

         clear: both;

      }

      [class*="col-"] {

         width: 100%;

         float: left;

      }

      @media only screen and (min-width: 480px) {

         .col-md-1 { width: 8.33333333% }

         .col-md-2 { width: 16.66666667% }

         .col-md-3 { width: 25% }

         .col-md-4 { width: 33.33333333% }

         .col-md-5 { width: 41.66666667% }

         .col-md-6 { width: 50% }

         .col-md-7 { width: 58.33333333% }

         .col-md-8 { width: 66.66666667% }

         .col-md-9 { width: 75% }

         .col-md-10 { width: 83.33333333% }

         .col-md-11 { width: 91.66666667% }

         .col-md-12 { width: 100% }

      }

      @media only screen and (min-width: 768px) {

         .col-l-1 { width: 8.33333333% }

         .col-l-2 { width: 16.66666667% }

         .col-l-3 { width: 25% }

         .col-l-4 { width: 33.33333333% }

         .col-l-5 { width: 41.66666667% }

         .col-l-6 { width: 50% }

         .col-l-7 { width: 58.33333333% }

         .col-l-8 { width: 66.66666667% }

         .col-l-9 { width: 75% }

         .col-l-10 { width: 83.33333333% }

         .col-l-11 { width: 91.66666667% }

         .col-l-12 { width: 100% }

      }

      /* design the layout */

      header, footer {

         padding: 15px;

         color: white;

      }

      .main, .aside {

         padding: 15px;

      }

      .main > p {

         text-align: justify;

      }

      .aside > div {

         background: #89C3D0;

         border: 1px solid black;

         border-radius: 5px;

         padding: 15px;

      }

      header {

         background: #173459;

      }

      footer {

         background: #333333;

      }

      .menu {

         padding: 10px;

      }

      .menu > ul {

         padding: 0;

         margin: 0;

         list-style-type: none;

      }

      .menu > ul > li {

         background: #903C56;

         width: 100%;

         margin-top: 5px;

         padding: 10px;

         font-size: 120%;

         transition-duration: 1s;

      }

      .menu > ul > li:hover {

         background: #76969D;

      }

      .menu > ul > li > a {

         text-decoration: none; /* remove underline */

         color: #f8f9f9;

      }

      img {

         max-width: 100%;

         height: auto;

      }

   </style>

</head>

<body>

   <header>

      <h2> Website chính chủ </h2>

   </header>

   <div class="row">

      <div class="col-md-3 col-l-3 menu">

         <ul>

            <li><a href="huyazz.github.io"> Home </a></li>

            <li><a href="https://www.facebook.com/profile.php?id=100066421973540&mibextid=ZbWKwL"> Facebook </a></li>

            <li><a href="https://www.tiktok.com/@ab980kkw"> Tik tok </a></li>

            <li><a href="#"> .</a></li>

            <li><a href="#">.</a></li>

         </ul>

      </div>

      <div class="col-md-9 col-l-6 main">

         <h1>  </h1>

         <p> . </p>

      </div>

      <div class="col-md-12 col-l-3 aside">

         <div>

            <h3> A City </h3>

            <p> This is a city full of lights, what a beautiful place to stay in. </p>

            <img src="images/city.jpg" />

            <h3> A Road </h3>

            <p> This is a road covered by trees. A long road, a very long road. </p>

            <img src="images/road-big.jpg" />

         </div>

      </div>

   </div>

   <header>

      <h2> địa chỉ liên hệ </h2>

     <p>bynrosv81111@gmail.com</p>

   </header>

</body>

</html>
