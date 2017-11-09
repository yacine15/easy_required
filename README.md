# easy_required

An extremely simply way for a client-side form protection.

<strong>Guide:</strong>

Just insert:

```
// insert the script
<script src="shining_star.js"></script>

// and call
easy_required("#myform");
```

and set the parameter:

```
// this is the first field (the two classes are required):
<input class="easy_required req_1" data-message="Name" type="text" />

// an example of second field (just increment req1 to req2 etc...)
<input class="easy_required req_2" data-message="Surname" type="text" />
```
<br>

<p>💾💾💾 <a href="http://www.testersite.it/github/easy_required/v1/">DEMO HERE</a> 💾💾💾</p>

<br>

# MIT License

Copyright (c) 2017 Eugenio Segala

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