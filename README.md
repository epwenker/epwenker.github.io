CSC 461 - Program 4 - Frogger

Ethan Wenker - epwenker


Description: This game is an implementation of the classic arcade game, Frogger, using Three.js.

Thumbnail: https://epwenker.github.io/thumbnail.png

Screencast: 

To Play Game:
	
	Go to https://epwenker.github.io

	Or (requires Python):

		Open command prompt and change working directory to the directory that contains index.html

		Run "python -m SimpleHTTPServer" (Python 2.x) or "python -m http.server" (Python 3.x)

		Open localhost:8000/index.html

Note: I was having problems with loading images hosted on my github.io page from a local file, but for whatever reason, when the server is running and the html file is accessed via localhost:8000/index.html, then the textures get loaded without a problem, even though the image URLs are all pointing to my github.io page. Sorry for any inconvenience this may cause.

Controls:

	w/a/s/d - Move Forward, Left, Backward, Right

	q - Toggle first/third person view

	Esc - Toggle no-clip (collision detection)

Extra Credit:

	Track and display score

	First-person view (press q to toggle 1st/3rd person)

Credits:

	Frog model - https://www.cgtrader.com/free-3d-models/animals/other/stylised-frog-model

	Car model - http://tf3dm.com/3d-model/low-poly-volkswagen-84375.html

	Grass texture - http://seamless-pixels.blogspot.com/2015/04/green-lush-grass-texture.html

	Road texture - http://seamless-pixels.blogspot.com/2012/10/tileable-asphalt-tarmac-texture.html

	Skybox texture - https://raw.githubusercontent.com/mrdoob/three.js/master/examples/textures/skyboxsun25degtest.png
