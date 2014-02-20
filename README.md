*This repository is a mirror of the [component](http://component.io) module [brighthas/window2canvas](http://github.com/brighthas/window2canvas). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/brighthas-window2canvas`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# window2canvas

  window mouse position transform to canvas position.

## Installation

  Install with [component(1)](http://component.io):

    $ component install brighthas/window2canvas

## API

    var w2c = require("window2canvas");
    var cavansXY = w2c(canvasElement,clientX,clientY);
    console.log(cavansXY.x , cavansXY.y);

## License

  MIT
