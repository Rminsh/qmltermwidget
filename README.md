# QMLTermWidget

This project is a QML port of qtermwidget. It is written to be as close as possible to the upstream project in order to make cooperation possible.

At the moment this plugin is powering cool-retro-term and the ubuntu-terminal-app.

This package also contains a simple test application.

## Requirements
Qt 5

## Build and install

To build it:

`qmake && make`

To test it:

`qmlscene -I . test-app/test-app.qml`