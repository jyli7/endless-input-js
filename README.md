## What this is

This is Javascript module that provides a slick, "endless" way of collecting user input.

You can see it in action [here](http://www.jylcreations.com/endless-input)

## How to use this

1. Include these three js files in your HTML file's head:

```
	<script src="js/underscore.min.js"></script>
	<script src="js/jquery-1.11.0.min.js"></script>
	<script src="js/endless-input.js"></script>
```

2. Within a <form></form> element, you can turn any <input type="text"> elements into
endless text inputs by setting the data-endless value. If you give inputs A, B, C the same
input value (e.g. "1", as below), they'll be clustered into the same "endless" input stream.

```
	<form class="my-form" action="/vote" method="post">
		<input type="text" name="my-data" data-endless="1" class="example-input"></input>
		<input type="text" name="my-data" data-endless="1" class="example-input"></input>
		<input type="text" name="my-data" data-endless="1" class="example-input"></input>
		<input type="text" name="my-data" data-endless="1" class="example-input"></input>
		<input type="text" name="my-data" data-endless="1" class="example-input"></input>
		<input type="submit" value="Submit">
	</form>
```

## License

The MIT License (MIT)

Copyright (c) <2014> <Jimmy Li>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.