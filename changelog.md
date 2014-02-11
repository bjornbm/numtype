1.1 (2014-02)
-------------
GHC 7.8.1 compatibility fix.

*  Added a `Sub c b a` constraint to `Sum a b c`. This
   prevents a liberal coverage condition failure on GHC 7.8.1 RC1.

I don't expect this to break any existing code but am updating
the major version number just in case.


1.0.1 (2013-07)
---------------
*  Typeable NumTypes.


1.0 (2009-06)
-------------
See the [announcement][1].

[1]: http://flygdynamikern.blogspot.se/2009/06/announce-numtype-10-type-level-low.html)
