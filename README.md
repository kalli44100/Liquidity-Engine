# Liquidity-Engine
Creating an App to summarise and visualise various elements of Liquidity in US Indices. Options Positioning with Gamma and Charm, Psyochologically enticing artifically created price moves, correllated markets, Time of Day sensitivites, buying and selling algorhythms on different timeframes: Liquidity is the concept that controls the markets and will always be present regardless of macro contexts.
![Liquidity_Engine](https://github.com/user-attachments/assets/8dc962e0-81bc-4aa1-8622-706256981405)

After years of learning about the financial markets, discovering my personal edge and visualising it in various individual indicators throughout a multitude of custom trading software, I finally decided it was time to merge all of these indicators and platforms in one place. Not only to avoid platform costs but also to circum-navigate the limitations of each platform.

At this point however I did not know any Python, yet it was the go-to language for my requirements in this context connecting via the Interactive Brokers Gateway API for my Data needs. In the past I would start out with a problem and a platform and as a result I would learn the relevant programming environment (MQL, Ninjascript, Pinescript) to get to my desired outcome. So I knew from experience how time intensive an endeavour it is to become comfortable in a new language (and how much fun it can be). I was also daunted by the prospect of creating an all encompassing Python app that would connect to an API, then send the data to a WebApp to be able to integrate it with a website and Discord to eventually create a business. Fortunately at that point I discovered AI. I started out with Bolt, which was the latest hype then. It was incredible to speak to a machine like that and have it create something for you, that would have taken me a long time to do on my own. I later migrated the project to Claude within the Windsurf Editor (Being a Windsurfer myself, I couldn't possible resist an editor themed this way!). In the mean-time I learned Python fundamentals through a Data Analysis Bootcamp, DataCamp courses and a Cisco Course which helped me overcome a seemingly simple issue that the AI could not resolve. And it helped me understand the structure of the code and improved my interactions with AI. In the beginning you blindly copy and paste the log messages into the AI chat only to realise that the AI would be going around in circles, making the exact same mistakes every time. Now I am able to guide the AI and work with it hand in hand, using it in the most efficient way.

On the downside, AI has significantly inhibited my Python learning curve so once I finish my bootcamp, I shall endeavour to build a small app to collect data for a part-time remote job, and do so un-aided (for the most part). My brother just explained to me the concept of your brain providing a certain type of molecules to build new synapses when you have experiences. When you don't make experiences, your body produces less of these olecules over time so when you then learn new knowledge or make experiences, you are lacking those molecules and your brain overrides old knowledge in order to store the new experiences. This is certainly an issue that society en large will be struggling with in years to come.
On the upside, AI quickly helps you understand code and concepts. For this app I chose an SQLite Database to store Trade data, effectively doing my own forward testing. In dialogue with AI, we came to this decision by talking through various scenarios. My Bootcamp Training came in handy at this point. An earlier issue with the app was that randomly generated test data was stored inside a chart element and therefore wasn't accessible by other elements of the app. I was not able to solve this fundamental problem until after the bootcamp. The AI helps you avoid some mistakes but causes other ones. It's a different type of learning. Similarly to having to make a conscious effort to eat healthy and avoid eating too much sugar, AI is equally omnipresent and provides us with shortcuts. The modern human being needs to learn when to say no, and when to give into a quick fix. Long-term thinking when possible and short-term thinking only when necessary.

Philosophy aside, the app has come a long way and still has some way to go before it may become commercially viable. I have only just started forward testing on the app while starting to backtest the same approach on the QuantConnect platform.
