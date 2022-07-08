# gif-randomizer
:hammer: I searched for an app like this online, i didnt find one that suited what i wanted so i made one!
It's a single html page that runs a Vue.js instance, it takes the text from the input and starts querying Gifs from one of two popular gif APIs. Then after 3 gifs are loaded, it starts displaying gifs until you reload or restart the gif queue by changing a parameter and pressing enter or pressing the Reload Gif Stack button! 5000ms of gif display time is recomended so the gif stack always full.

# Online Version
[gif-randomizer :sparkles: ](https://gif-randomizer.web.app)

# Gif Queue Logic
📖 The queueing doesnt start until you write something and press enter or just press the Get Gifs button (in that case it will really get random gifs).
If you input a search term the app will start querying for random gifs with that tag, if you change any of the parameters while the program is running and dont press enter, the "new parameter" gifs will start to be placed at the end of the queue, if you only want to get gifs with the new parameters just press enter after inputing it or press the Reload Gif Stack button. Gif duration time is in ms. 😺
