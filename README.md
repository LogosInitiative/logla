Logla
=====

Logla is a fork of the Loglan and Lojban languages. It's goal is to continue the original mission set out by both projects: the perfection of human language. 

Unlike Loglan, Logla is 100% open source, all material is copyleft, and anyone can participate.

Unlike Lojban, Logla is a living changing language. Dialects are warmly welcome. The best features of dialects may find there way to the mainline language. Changes to the mainline language are decided by long and rigorous debate.

The Github issues tracker will be used propose and debate these ideas. And the Github wiki will be used to write up detailed formal proposals as needed.


## Status

Currently Logla consists of two widely divergent dialects: the original Loglan and its rebel progeny Lojban. Hence much of the initial activity of Logla will center around reconciling these two into a single mainline language. Every aspect of this process will be put under the microscope and in some cases the result may not be like either of the two source languages, should it is decided they are both deficient in some specific area.

Running parallel to this reconciliation, the floor is open to all new ideas. There is nothing too radical or too minor that it should not be given due consideration. 


## History

James Cooke Brown began work on Loglan in 1955, originally devised to test the Sapir-Whorf hypothesis.

The Loglan Institute ...

In the ... a dispute broke out over copyrights.

The Logical Language Group's Bylaws states its purpose as follows:

> The Logical Language Group, Inc. is established to promote the scientific study of the relationships between language, thought and human culture; to investigate the nature of language and to determine the requirements for an artificially-engineered natural language; to implement and experiment with such a language; to devise and promote applications for this language in fields including but not limited to linguistics, psychology, philosophy, logic, mathematics, computer science, anthropology, sociology, education, and human biology; to conduct and support experimental and scholarly research in these fields as they may bear upon the problems of artificial language development; to communicate with and to educate interested persons and organizations about these activities; to devise and develop means and instruments needed for these activities; and to accumulate and publish the results of such studies and developments. In the furtherance of these purposes, and in addition to the above activities, 

With such a purpose one could be forgiven for expecting the Lojban language to hotbed of language experimentation and exploration. Ironically nothing could be further from the truth. Lojban was *baselined* in 1997 for a period of five years. But the baseline has since become a defacto freeze. While still giving lip service to proposals, the language is no longer evolving. Put simply, the LLG's purpose has changed. They now exist "to preserve the investment people have made in learning the language".


## Phonology

Phonology is almost identical to Loglan and Lojban with only a few exceptions.

First, it has not yet been decided, but two new constants might be added corresponding to the `th` in English `thank` and `this`. If not than `f` and `v` will gain these sounds as acceptable pronunciations.

2. `h` is written as a letter, not as an apostrophe.
3. `'` is used to mark a stop instead of `.`.

u a aa 
e i ii
    rr
o   oo

kq ka  ky kr  ke ki  ko ku


## Morphology

Logla has the same same basic morphology as Loglan and Lojban. But Logla avoids the complexities Loglan and Lojban introduce for the production of compund words. 

Logla's root words, called Gisma, are always in the form `CVCCa` or `CCVCa`, where `C` is a constant, `V` is a vowel and `a` is simply the letter "a". 

Logla allows double constants, for example `fimma`. To distinguish these words without ambiguity the pronunciation of the double constant must be held for a period perceptably longer than normal, typically double the length of a single constant. Alternately, the constant can be asperated. So `fimma` would sound like <tt>fim<sup>h</sup>a</tt>.

Compund words of three syllables or more, called *lujva*, are always combinations of `CVC` and `CCV` followed by `Ca`. For example, all three-syllable lujva are of the forms `CVCCVCCa`, `CCVCVCCa`, `CVCCCVCa` or `CCVCCVCa`. The same pattern continues for four or more syllables (which are fairly rare and generally exist only to address techincal terms). Unlike Loglan and Lojban there is no `y` (schwa) to represent a hyphen. Nor are there any rafsi. 

Lujva are formed simply by taking the first three letters of the first gismu and combining it with the entire second gismu. For example, `bitma` and `salfa` would form `bitsalfa`. If the combined form happens to already be an offical word in the Logla dictionary (having utlizing the first three letters of different word), then the a *proper lujva* would be formed by combine the two words in there enirety and insterting an additional constant between them. For example, `bitmassalfa`. The constant choosen is essentially arbitrary, but it should either derive from the original borrowing of the first gisma, be a doubling of the preceeding letter, or taken from the following table.

    b  tc  d  f  g  dj  sk  l  m  n  mp  q  r  s  t  v  x  z
   
Using this table has the advantage of creating a constant redundancy, which makes it easier for listener to parse these long words.

Note that *borrowed* lujva will not necessarily have a semantic deconstruction. For example `balkonni`, meaning "balcony", does not mean a "balanced cone". Most words will desconstruct nicely, just not all.


## Grammar

If you are familar with Loglan or Lojban, you may have already noticed somthing is amiss with the last letter of gisma. They're all "a"! The reason for this is simple. The last letter of any word indicates the predicate slot of the word that is intended. So for example the Lojban word for come/go/travel is `klama`. Hence a *klama* is a travaller, a *klame* is a destination of travel, a *klami* is an origin of travel, a *klamo* is a route travelled, and a *klamu* is a mode of transport.

Gisma will be defined with order but also with case tags wherever they apply. For instance `klama` is defined as:

> x1 goes/comes to x2 (*dio* destination) from x3 (*sua* origin) via x4 (*via* route) using x5 (mode of transportation)

This means one can write:

    le gerka sua la .atlanta. dio la .baltimor. cu klama
    
    a gerka e homma i la .baltimor. cu klama

    le tinka gerko le homme la .baltimor. cu klama

## Vocabulary

### Cmava

Cmava will get a heavy make over, both to reconcile differences between Loglan and Lojban, but also to imporove on both. The primary goal is to utilize common patterns wherever possible and reduce the number of necessary words. For example cmava that create subordinate clauses will either use a redundant closing phonome, e.g. `lu ... ka lu` or a standard set of bracket words, e.g. `so lu ... sa`. Perhaps both forms will be supported.

We will also consdier allowing cmavo in `cvvv` form where the second to last vowel is either `i` or `u`. This more than doubles the available cmavo space, and reduce the over reliance on `h`.

#### Numbers

do rei mi fa so la ti ?


### Gisma

The Gisma will be largey redone. Loglan and Lojban made the mistake of importing words by *mixing* the letters from words of the six most common languages. This only served to create words no one recognizes, and in the case of Lojban that sound mostly like atonal Mandarin. Instead Logla will borrow words whole, modifying them as little as possible to fit the morphology.
