## v2ex ![npm](https://badge.fury.io/js/v2ex.png)

[![Gitter](https://badges.gitter.im/Join Chat.svg)](https://gitter.im/song940/v2ex-api?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

v2ex API for nodejs .

### Installation

````
$ [sudo] npm install [-g] v2ex-api [--save]
````


### CLI Useage

````
➜ v2ex

  Usage: v2ex [command] [options]

  Options:

    -h, --help            output usage information
    -V, --version         output the version number
    -t, --hot [id]        top 10 of topics
    -l, --latest [id]     all topics
    -n, --node <name>     node info
    -u, --profile <user>  member info
````

### Example

````javascript
var V2EX = require('v2ex-api');

var v2ex = new V2EX({ 
	api: 'https://v2ex.com/api' 
});

v2ex.latest(function(err, topics){
	console.log(topics);
});

````

### Contributing
- Fork this repo
- Clone your repo
- Install dependencies
- Checkout a feature branch
- Feel free to add your features
- Make sure your features are fully tested
- Open a pull request, and enjoy <3

### MIT license
Copyright (c) 2014 Lsong

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the &quot;Software&quot;), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED &quot;AS IS&quot;, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

---
![docor](https://cdn1.iconfinder.com/data/icons/windows8_icons_iconpharm/26/doctor.png)
built upon love by [docor](https://github.com/turingou/docor.git) v0.1.3
