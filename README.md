# docs-react-sdk

The repository for Inrupt Solid React SDK documentation
https://docs.inrupt.com/developer-tools/javascript/react-sdk.

The SDK API documentation, via Storybook, is built separately from the
manual.

## To Build

To build:

0. Prereq: [python3](https://www.python.org/downloads/), [Node.js](https://nodejs.org/).

1. Optional but recommended. Create a virtual env.

   ```sh
   python3 -m venv <path to the new virtual environment>
   source <path to the new virtual environment>/bin/activate
   ```

2. Go to the cloned repo directory:

   cd <cloned repo dir>

3. Install the docs requirements (different from API docs requirements):

   ```sh
   pip install -r requirements.txt
   ```

4. Make the docs.

   ```sh
   make dirhtml
   ```

   There should be a `build/<branch>/dirhtml` directory with the html artifacts.

When finished, can deactivate your virtual env.

## Copyright

© Copyright 2020-present, Inrupt Inc.

## Third Party Licenses

This section is incomplete since work in progress - and so the dependencies may change, etc. (right now, acting as placeholder - so that we don't forget)

### Sphinx

Copyright (c) 2007-2020 by the Sphinx team (see AUTHORS file).
All rights reserved.

### sphinx-copybutton

The documentation uses [sphinx-copybutton](https://github.com/executablebooks/sphinx-copybutton), which is under the MIT License:

MIT License

Copyright (c) 2018 Chris Holdgraf

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

### pydata-sphinx-theme

The documentation's theme is based on the [pydata-sphinx-theme](https://github.com/pandas-dev/pydata-sphinx-theme), which is under the BSD-3-Clause license:

BSD 3-Clause License

Copyright (c) 2018, pandas
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

- Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.

- Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.

- Neither the name of the copyright holder nor the names of its
  contributors may be used to endorse or promote products derived from
  this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

#### Fonts

##### Lato

Copyright (c) 2010-2014, Łukasz Dziedzic (dziedzic@typoland.com),
with Reserved Font Name Lato.

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at:
http://scripts.sil.org/OFL

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at: http://scripts.sil.org/OFL

##### Open Sans

These fonts are licensed under the Apache License, Version 2.0.


