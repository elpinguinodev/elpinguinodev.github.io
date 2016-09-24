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
            <img src="/images/Rictrain1.jpg">
            <img src="/images/Rictrain2.jpg">
            <img src="/images/Rictrain3.jpg">
            <img src="/images/Rictrain4.jpg">
            <img src="/images/Rictrain5.jpg">
            <img src="/images/Rictrain6.jpg">
            <img src="/images/Rictrain7.jpg">
            <img src="/images/Rictrain8.jpg">
            <img src="/images/Rictrain9.jpg">
        </div>
        <script>
        (function() { 
            Galleria.loadTheme('galleria/themes/classic/galleria.classic.min.js');
            Galleria.run('.galleria');
        }());
        </script>
    </body>
</html>
