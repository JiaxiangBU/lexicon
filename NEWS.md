NEWS
====

Versioning
----------

Releases will be numbered with the following semantic versioning format:

&lt;major&gt;.&lt;minor&gt;.&lt;patch&gt;

And constructed with the following guidelines:

* Breaking backward compatibility bumps the major (and resets the minor
  and patch)
* New additions without breaking backward compatibility bumps the minor
  (and resets the patch)
* Bug fixes and misc changes bumps the patch


lexicon 0.1.0 -
----------------------------------------------------------------

**BUG FIXES**

**NEW FEATURES**

* The `ratings` and `grades` keys from *sentimentr* have been moved to the
  *lexicon* package and renamed to `key_rating` and `key_grade`.

**MINOR FEATURES**

**IMPROVEMENTS**

* Added the positve terms 'spot on', 'on time', & 'on point' to `hash_sentiment`.

**CHANGES**


lexicon 0.0.1
----------------------------------------------------------------

This package is a collection of lexical hash tables, dictionaries, and word
lists.