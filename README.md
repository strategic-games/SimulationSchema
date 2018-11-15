# Simulation Schema
This is the protocol buffers schema used for creating game simulations for Begriffix, a verbal strategic game. It defines input configuration and output results. Simulation messages can be passed to [Hangman](https://github.com/strategic-games/hangman) which runs the games and produces result messages.

## Usage
The schema can be used in any environment which supports protocol buffers. In my projects, I include it as a git submodule. For example usage, see my [R package](https://github.com/strategic-games/sg.data).

## Documentation
The schema is documented, but I havent found a tool which handles subsubmessages. You can inspect the comments in the SimulationSchema.proto file.
