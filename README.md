# node-ecb-exchange-rate
Node.js wrapper for the ECB Echange Rate Daily [XML](http://www.ecb.europa.eu/stats/eurofxref/eurofxref-daily.xml)

### Disclaimer

This module is a work in progress. Not all methods are available yet. Feel free to add them and send in a pull request

# Install

```bash
npm install ecb-exchange-rate
```
# Usage 

Get the rates as a JSON object (content may vary)
```javascript
var ecb = require('ecb-exchange-rate');
var rates = ecb.getCurrentRate();
```

# Support
Found a bug? Have a great idea? Feel free to create an issue or a pull request!

# License

The MIT License (MIT)

Copyright (c) 2015 Aan Zee

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

