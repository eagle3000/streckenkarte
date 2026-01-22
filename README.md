# Streckenkarte

This repository stores the data files used for generation of [Streckenkarte](https://karte.para-craft.de).

When a change is pushed, a CI/CD workflow builds the static files using [homologic's streckenkarte tool](https://github.com/homologic/streckenkarte) and [margau's images](https://github.com/margau). These static files are then deployed to a webserver.
