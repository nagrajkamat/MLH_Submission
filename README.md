
Step –1: Get API credentialas 
to get Telegram API credentials you can get directly from your mobile app, but I would suggest you go to web.telegram.org and initiate a chat with this username BotFather.
So look for Bot Father and send this message: /newbot, Once you hit enter, the BotFather will ask you this question:
“Alright, a new bot. How are we going to call it? Please choose a name for your bot.”
Let’s give it the name of “WeatherBot”
Next, it’ll ask, “Good. Now let’s choose a username for your bot. It must end in bot. Like this, for example, TetrisBot or tetris_bot.”
Here you have to make sure that it ends with “bot”, so give it a name. For instance, I am giving it “Phoenix_weather_bot

Step –2: Getting Weather API credentials
In this tutorial, we’ll be using OpenWeatherMap API, one of the most popular weather APIs. Sign up with OpenWeatherMap here, create your account, and verify your email, its not the case.

Step –3: Code Setup:
Once you’re done with all the above tasks, let’s set up our project now. So open your terminal and create a new folder by using the below command:
mkdir telegram-api
And then open the folder:

cd telegram-api
Now it’s time to install some dependencies. So on your terminal, paste the below code:

python3 -m pip install requests
We’re installing requests here because it makes it very easy to make API calls.

Once that is done, create a new file by telegram.py and open it in your favorite editor. Now it’s time to write some code!

Step –4: Defining All the Functions:
Implement your Bot Logic!, efine all the functions which you'll be using for your Weather Bot

Step –5: Testing our Bot:
Let’s run the code so on your terminal execute the below code:
python3 telegram-api.py
And then, open your Telegram App and search for the username that you chose for the bot. Now tap on the bot and write /weather.
From here, you can select any predefined city, or share your own location. Let’s go for London, and it’ll return the current weather:
8.56 °C, overcast clouds in London


We have successfully created the Telegram Weather Bot. The Telegram API can do a lot more than just returning the current weather.











Now we’ll define all the functions which we’ll be using for our Weather Bot. So paste the below code:
