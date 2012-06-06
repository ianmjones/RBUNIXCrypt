# RBUNIXCrypt #

A REALbasic library for validating UNIX crypt style passwords.

You can use the UNIXCrypt REALbasic module to simulate UNIX Crypt by simply calling “UNIXCrypt” with a string and two character salt.


## How To Use ##

Simply add this module to your project and call the UNIXCrypt function with a password and salt.

The salt should be a 2 character string.

If you are using UNIXCrypt to check that a supplied password matches a UNIX crypt encrypted string,
the salt should be the first 2 characters of the encrypted string.

This is classic crypt, only the first 8 characters of the password count.


## Author ##

Ian M. Jones  
http://www.ianmjones.com  
mailto:ian@ianmjones.com  


## License ##

The source in this file is heavily borrowed from a crypt3.c file found at http://michael.dipperstein.com/crypt/index.html

The original source was released into the public domain by the author, but as that is illegal in some countries, I've reverted to the MIT License as it's the most open license I know of...

Copyright (c) 2005 Ian M. Jones, IMiJ Ltd

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.


## Version History ##

1.2 2012-05-25

* Moved to GitHub.

1.1 2008-07-10

* Added README.

1.0 2008-03-05

* Initial public release.

--- EOF ---