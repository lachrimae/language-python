Introduction
============

A lexer, parser and pretty printing library for Python 2 and 3.

License
-------

language-python is released as open source software under the terms of the 3 clause BSD License. See the file LICENCE.txt in the [source code repository of language-python](https://github.com/bjpop/language-python).

Installation
------------

language-python can be installed with cabal (cabal version 3.0.0.0 onwards):

```
cabal build all
```

Testing
-------

Test cases are provided in a language-python-test. Test binaries can be built and run as below (cabal version 3.0.0.0 onwards):

```
cabal install shelltestrunner
cabal install --overwrite-policy=always language-python-test
cd language-python-test/
PATH=$HOME/.cabal/bin/:$PATH make test
```

If all goes well you should see a long list of test cases and a summary at the end, that should look like the following:
```
         Test Cases    Total        
 Passed  517           517          
 Failed  0             0            
 Total   517           517       
```

Pull requests
-------------

Pull requests are greatly appreciated. If you plan to submit a pull request, please test your code in the test suite first. New test cases are desirable, especially if you are fixing a bug or adding a new feature.
