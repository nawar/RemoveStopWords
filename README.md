RemoveStopWords
===============

RemoveStopWords Class for PHP


## Usage 
To use it, just open a new file and copy+paste this code. replace `$text` with your own text. 
```php
require_once("RemoveStopWords.php");
$as = new RemoveStopWords();
$text = "Upload the pdf of your newspaper, magazine or catalog in order to have your branded digital replica"; 
echo $as->remove_stop_words( $text ); 
```

This will output 
```bash
Upload pdf newspaper magazine catalog order branded digital replica
```

## License 

```
MIT License
Copyright (C) 2013 Nawar Nory

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated 
documentation files (the "Software"), to deal in the Software without restriction, including without limitation 
the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and 
to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial 
portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT 
NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. 
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, 
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE 
OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
