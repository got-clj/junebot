# junebot

An online game written in clojure. Requires leiningen (https://github.com/technomancy/leiningen) and foreman (https://github.com/ddollar/foreman)

## Usage

To start the server:

    foreman start server

To start a client:

    foreman start client

## License

Copyright (C) 2012 FIXME

Distributed under the Eclipse Public License, the same as Clojure.

## TODO

### Server Side
- Fix terminology for shots (position -> coord)
- Fix remove dependency of graphics library in server
- Fix initial world
- Fix initial player position
- Fix tests
- Better random walls
- Use refs to update the world

### Client
- Write test
- Interpolate moves
- Remember the walls
- Center on the player
- Use refs to update the world
