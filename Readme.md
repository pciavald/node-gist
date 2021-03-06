[![Build Status](https://secure.travis-ci.org/emerleite/node-gist.png)](http://travis-ci.org/emerleite/node-gist)

Node.js Gist client
===================
Gist API client for Node.JS

Dependencies
------------

### Runtime
* Node 0.4.x+

### Development/Tests
* mocha
 *should.js

Instalation
-----------
> npm install gist 

Usuage
------
    var gist = require('gist');

    gist.create('your gist content', function (url) {
      console.log(url); //prints created gist url
    });

Running tests
-------------

### Unit
$ node_modules/mocha/bin/mocha test/gist.test.js

### Integration
$ node_modules/mocha/bin/mocha test/integration.test.js

### All tests (3 ways)
$ npm test 
$ mocha (installed global)
$ node_modules/mocha/bin/mocha

Note: Integration test creates real gist. Please, be carreful with this test to not flood gist.

To-Do
-----
 (<https://github.com/emerleite/node-gist/issues>)

Author
------

* Emerson Macedo (<http://codificando.com/>)

License:
--------

(The MIT License)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
