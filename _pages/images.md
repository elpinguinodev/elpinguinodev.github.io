---
layout: inner
title: Images
permalink: /images/
---

I want the images to look like [Unite Gallery](https://unitegallery.net/).

	            <head>
				...
				<!-- Include Unite Gallery core files -->
				<script src='unitegallery/js/unitegallery.min.js' type='text/javascript'  ></script>
				<link  href='unitegallery/css/unite-gallery.css' rel='stylesheet' type='text/css' />
				
				<!-- include Unite Gallery Theme Files -->
				
				<script src='unitegallery/themes/tiles/ug-theme-tiles.js' type='text/javascript'></script>
				...
				</head>
								
				<body>	
				
				<div id="gallery"> ... </div>
				
				<script type="text/javascript">
				
				jQuery(document).ready(function(){
					
					jQuery("#gallery").unitegallery({
						gallery_theme: "tiles",
		 				tiles_type: "nested"						
					});
				});
				
				</script>
				
				</body>
				
