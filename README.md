# webgl-lines

The setup done in the CPU side is located in:
https://github.com/Beak-man/webgl-lines/blob/master/projected/index.js

The vertex shader that provides width to the 3D lines is located in:
https://github.com/Beak-man/webgl-lines/blob/master/projected/vert.glsl

More information can be found here:
https://mattdesl.svbtle.com/drawing-lines-is-hard#screenspace-projected-lines_2

## running demos

First you need to git clone and install dependencies:

```sh
git clone https://github.com/Beak-man/webgl-lines.git
cd webgl-lines
npm install
```

To start developing a demo, use one of the following:

```
  npm run projected
```

And open `localhost:9966` in the browser. Tested in Chrome and Firefox.

## License

MIT, see [LICENSE.md](http://github.com/mattdesl/webgl-lines/blob/master/LICENSE.md) for details.
