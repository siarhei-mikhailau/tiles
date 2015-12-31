# tiles

The project is about collecting data about market stocks in Proxy Web Server (using NodeJS, Express, Mangoose, MongoDB) and providing up to date information to client side.

# Project structure

Open API
- https://web.archive.org/web/20111209142224/http://code.google.com/apis/finance/docs/finance-gadgets.html#hello_world_example
- http://www.google.com/finance/info?q=NASDAQ%3aGOOG
- need to find alternatives
- etc
- maybe we can add weather and some additional services

Proxy Web Server
- Grabber (gets information from Open APIs, transfers data to unified structure)
- Storage (provides API for communication with database: save/retrieve)
- Config file in file system that sets default settings of the server (update timing for example)
- Static folder with minified js/css files, index.html, assets, etc.
- Build using Grunt (LESS compiling, js/css minification, js linting)

Client side
- Widget
- Dashboard
- Settings
- Local Storage


