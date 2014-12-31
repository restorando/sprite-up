# Sprite-Up

Take the pain away from spriting! With the fruitiness of this refreshing tropical mixin.
Sprite Up is a very simple tool to generate sprites for retina and non-retina displays.

## Build your sprites

1. Organize your retina and non-retina images

  TO-DO

2. Include the `generate-sprites` mixin in your stylesheets

  ```sass
  # Some part of your sass files
  +generate-sprites("normal-icons/*.png", "retina-icons/*.png")
  ```

## Requirements

[compass](https://github.com/compass/compass) >= 0.12.2

## Testing

Tested against `compass-0.12.X` and `compass-1.0.1`

## Run middleman example

  ```bash
  $ git clone git@github.com:restorando/sprite-up.git
  $ cd examples/middleman
  $ bundle install
  # ...
  $ bower install
  # ...
  $ middleman
  # ...
  ```

Visit `http://localhost:4567`

## Version

0.1.0

## License

Copyright (c) 2013 Restorando

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
