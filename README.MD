## Covid-19 Application
Since heroku is hosting back-end server: if the server is not in use within a 30 minute time span, it will go to sleep. 
Once you go on the site, you'll have to wait a bit and reload for the server to wake up which will than load the covid-19 statistics.
## Motivation
With some familiarity of Vue and Node.js, I wanted to fully combine the two and create a simple website that shows covid update.

## Tech/framework used
 ``` bash
- Vuetify
- Bootstrap
- Vue
- Node.JS
- HTML
- CSS
- JS
```
## deployment
 ``` bash
deploying server folder (back-end) on Heroku
deploying client folder (front-end) on vercel now cli
[Server]
1. commit and git push heroku master
[client]
1. npm run serve (local test)
2. npm run build (create dist folder in client)
3. cd dist
4. now login
5. now (in command line)

```

## issues
 ``` bash
a lot of vunerabilities exposed because of un-needed modules.

```

## credits
[https://covidtracking.com/data](https://covidtracking.com/data)

[https://rapidapi.com/axisbits-axisbits-default/api/covid-19-statistics?endpoint=apiendpoint_191c58c7-a995-4024-a5ee-41043d79e542](https://rapidapi.com/axisbits-axisbits-default/api/covid-19-statistics?endpoint=apiendpoint_191c58c7-a995-4024-a5ee-41043d79e542)

[https://coronavirus.jhu.edu/us-map](https://coronavirus.jhu.edu/us-map)

[https://github.com/afeld/emoji-css/](https://github.com/afeld/emoji-css/)

[https://github.com/michalsnik/aos](https://github.com/michalsnik/aos )

