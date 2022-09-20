alfred scrcpy
===

# ![](image.png)

Launch [scrcpy](https://github.com/Genymobile/scrcpy) by [Alfred](https://www.alfredapp.com/)

# Usage

<img src="launch-scrcpy.gif" width="600">

- In Alfred, type `scrcpy` then enter
- Select a device which you want to display with scrcpy

# Requirements

- Alfred 4 with the [Powerpack](https://www.alfredapp.com/powerpack/) upgrade
- Node
- Ruby
- Android Platform Tools
  - _Installed at `$HOME/Library/Android/sdk/platform-tools`_
- scrcpy
  - _Installed at `/opt/homebrew/bin/scrcpy`_

If requirement tools are installed different path, You can change the path by edit script through Alfred Preference.

# Install

```
$ npm install --global alfred-scrcpy
```

# License

```
Copyright 2022 Tomoki Yamashita

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
