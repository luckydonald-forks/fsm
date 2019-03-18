# Finite State Machine Designer

https://luckydonald-forks.github.io/fsm/

This project is a fork off of https://github.com/evanw/fsm and others with some major 
changes in the behaviour with some fixes as well.

# Added Features:
- Export & Import as json.
- Multiline Text labels.
- Copy, paste, cut text.


# Try it
- To run the project locally open the `index.html` file in the browser.
- Or `python3 -m http.server 8080` and open http://0.0.0.0:8080.

# Development
To make changes you need to run the `build.py` script since it compiles
all the js files into one js file named `fsm.js`.

You can also run it checking twice every second for changes via `python3 build.py --watch`.
