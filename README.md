Abe: a free block chain browser for Bitcoin-based currencies.
https://github.com/bitcoin-abe/bitcoin-abe

    Copyright(C) 2011,2012,2013 by Abe developers.
    License: GNU Affero General Public License, see the file LICENSE.txt.
    Portions Copyright (c) 2010 Gavin Andresen, see bct-LICENSE.txt.

Execution
=========

Remember to edit the gcoin.conf to satisfy the configuration.

**Initialize**

```
$ python2.7 -m Abe.abe --config gcoin.conf --commit-bytes 100000 --no-serve
```

**Start up server**

```
$ python2.7 -m Abe.abe --config gcoin.conf
```

Configuration
-------------

* Port: 100000
