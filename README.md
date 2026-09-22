<!DOCTYPE html><html><head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>
	
    <style>
        body {
            font-family: Constantia, "Lucida Bright", "DejaVu Serif", Georgia, "serif"
            width: 1024px;
            margin: 0 auto;
            padding: 20px;
        }
		
        h1 {
            font-size: 64pt;
            margin-bottom: 20px;
			text-shadow:
        0 0 6px #E033FF,
        0 0 12px #E033FF,
        0 0 24px #E033FF;
        }

        /* Flexbox container */
        .portfolio-box {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }

        figure {
            width: 200px;
            text-align: center;
        }

        figure img {
            width: 200px;
            height: auto;
            border: 1px solid #ccc;
            box-shadow: 2px 2px 6px rgba(0,0,0,0.2);
        }

        figcaption {
            font-size: 12pt;
            margin-top: 8px;
        }
    </style>
</head>

<body>

<h1>My Portfolio</h1>

    <!-- Drawing 1 -->
    <figure>
      <a href="highres-drawing1.jpg" target="_blank">
            <img src="Self-Portrait Movie Poster (1).png" alt="Drawing 1">
        </a>
        <figcaption>The Alley Movie Poster</figcaption>
    </figure>
    <!-- Drawing 2 -->
    <figure>
        <a href="highres-drawing2.jpg" target="_blank">
        <img src="Tour Poster Rough Draft copy.png" alt="Drawing 2">
        </a>
        <figcaption>The Springers World Tour Poster</figcaption>
    </figure>
    <!-- Drawing 3 -->
  <figure>
        <a href="highres-drawing3.jpg" target="_blank">
        <img src="Self Portrait Illustrator.JPG" alt="Drawing 3">
        </a>
        <figcaption>Self Drawing on Illustrator</figcaption>
    </figure>


</div>


</body></html>
