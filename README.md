#Websterium

_A web adaptation of the board game [Mysterium](https://boardgamegeek.com/boardgame/181304/mysterium), where one player (the ghost) use gifs and picutres to describe their untimely demise to the other players (the psychics)._

The frontend and backend are implemented as two separate applications. The frontend, built with React, is a static site, while the backend, built with Sanic, keeps track of game state and handles API calls.

To get it up and running, clone the repo. Go into the "backend" folder first, and create a Python 3 virtual environment. Run

```pip install -r requirements.txt```

Then start the backend server by running

```python application.py```

Open a separate terminal window and navigate to the "frontend" folder. Run

```npm install```

Then run

```npm run dev```

The app should be running at localhost:8080