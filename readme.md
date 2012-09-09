# KOTools - tools for working with KnockoutJS
 
	KOTools is a collection of utilities and extensions for working with KnockoutJS

## Test

	You can test KOTools [here](http://jsguy.github.com/kotools/test.htm).

## Features

	- Re-use the values in existing fields, rather than specifying in the model
	- Binding check boxes and radios to 'checked' attribute no longer necessary, just use valueInit, and this will do the rest
	- Binding selects is a lot simpler, we automatically set the optionText and optionValue, so you don't have to

	Note: when using selectboxes, don't forget to add the optionsInit valueArray too - KO needs this to work properly with select boxes; this won't work with optionsCaption - provide an empty option yourself instead.

## License

(The MIT License)

Copyright (c) 2012 jsguy &lt;mikkel@jsguy.com&gt;

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