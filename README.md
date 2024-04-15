[![](https://img.shields.io/badge/Download-111?logo=Visual-Studio-Code&style=for-the-badge)](https://github.com/nyc-nahid/bootstrapoptimization/releases)

## Optimization for Bootstrap
Additional addons to help bootstrap to flow smoothly and increasing website speed, while supporting dark and light mode.<br>

**Requirements**<br>
*Do not use the latest bootstrap version since it has too many issues, uses more space (slower load time) and useless new features. Instead use the older version of bootstrap.*<br>
[![](https://img.shields.io/badge/v5.2.3-Download-blue?logo=cloudbees&logoColor=white&style=flat)](https://getbootstrap.com/docs/5.2/getting-started/introduction/)

**How to Use**<br>
Having trouble setting up your bootstrap or optimization css file? Follow the steps!

1. Drag and drop the CSS file into your project folder.
2. Add Bootstrap into your html or php file. *(Remember, the javascript code must be in the end of your code)*
3. Link the CSS into your html or php file (After the Bootstrap CSS).
 `<link  rel="stylesheet"  href="bundle.css"  />`
 4. Your finished!


**Template**<br>
If you encountered any issues with installing the css to your site, use the html template below.

    <!DOCTYPE  html>
    <html  lang="en">

	    <head>
	            <!-- Website Setup -->
		    <meta  charset="utf-8"  />
		    <meta  name="viewport"  content="width=device-width, initial-scale=1"  />
		    <title>New Website - Who's This?</title>
		    <!-- Bootstrap & Fonts -->
		    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
		    <!-- CSS -->
		    <link  rel="stylesheet"  href="bundle.css"  />
        </head>
    
	    <body>
		    <h1>Your Code Here</h1>

		    <!-- Bootstrap & JS -->
		    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4" crossorigin="anonymous"></script>
	    </body>

    </html>

> This project is original and created to help other developers that are using Bootstrap.

