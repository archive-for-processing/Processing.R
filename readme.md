# R Mode for Processing

Something like [processing.py](https://github.com/jdf/processing.py)

WIP now.

## Demo

### Editor

Change `processing.modes` in build.xml, and run `ant install`, you will get a mode in your `processing.modes`.

<img src="./docs/img/editor.png" width="600">

<img src="./docs/img/demo.gif" width="600">

### Runner.jar

Run `ant try`, you will get a runner demo in `try/`, and run `java -jar ./try/RLangMode.jar <your R script>`.

```
posAX <- 11
posAY <- 22

posBX <- 33
posBY <- 22

processing$line(posAX, posAY, posBX, posBY)
```

The output is:

<img src="./docs/img/demo.png" height="200">

## MIT License

Copyright (c) 2016 Ce Gao

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
