# heroku-example
using heroku

files needed:
	composer.json
		{}
	index.php
		<&php include('file-name.html');

steps: 
	1) create github repo
	2) clone to computer
	3) create index.php and composer.json files
	4) add html + css files to local repo
	5) git add . <--- adds all files
	6) git commit -m "message" <--- saves work to local repo
	7) git push <--- add files to github
	8) heroku create
	9) git push heroku master <--- transfer files to heroku 
	10) to open from heroku website click on repo -> settings -> domains (link should be there)
