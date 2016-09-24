---
layout: inner
title: Images
permalink: /images/
---

I want the images to look like [Unite Gallery](https://unitegallery.net/).

<html>
    <head>
      <script src="https://ajax.googleapis.com/ajax/libs/jquery/1/jquery.js"></script>
      <script src="galleria/galleria-1.4.5.min.js"></script>
      <style>
        .galleria{ width: 700px; height: 400px; background: #000 }
      </style>
    </head>
    <body>  
        <div class="galleria">
            <img src="/images/rictrain1.jpg">
            <img src="/images/rictrain2.jpg">
            <img src="/images/rictrain3.jpg">
            <img src="/images/rictrain4.jpg">
            <img src="/images/rictrain5.jpg">
            <img src="/images/rictrain6.jpg">
            <img src="/images/rictrain7.jpg">
            <img src="/images/rictrain8.jpg">
            <img src="/images/rictrain9.jpg">
        </div>
        <script>
        (function() { 
            Galleria.loadTheme('galleria/themes/classic/galleria.classic.min.js');
            Galleria.run('.galleria');
        }());
        </script>
    </body>
</html>
