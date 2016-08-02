The code below creates the api.json file and puts the conversion of mk to json files in it. 

-w 1000 stands for 1000 width and it makes it so the whole preview of quotes will show up.

node_modules/.bin/m2j -w 1000 quotes > api.json