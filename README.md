# Test sets for evaluating translation of ambiguous conjunctions

This repository contains test sets specifically designed for two source language ambiguous conjunctions “but” and “and” and their two possible variants in target languages. 

The  test  sets  are  compiled semi-automatically from the OpenSubtitles corpora (http://www.opensubtitles.org/). Only  short  segments  (up  to  20 words) were included, all noise was removed, and rare  named  entities  which  could  introduce  additional  effects  were  avoided  or  replaced.

For the conjunction "but", English and French test sets are available (en.but.test, fr.mais.test).
Expected conjunctions for four target languages, German, Spanish, Croatian and Serbian, can be found in en.expected-target-but.test and fr.expected-target-mais.test.

For the conjunction "and", English and Portuguese test sets are available (en.and.test, pt.e.test).
Expected conjunctions for two target languages, Croatian and Serbian, can be found in en.expected-target-and.test and pt.expected-target-e.test.

The test sets are not limited to the mentioned target languages, they can be used for any other target language with the same conjunction ambiguity.

The test sets do not contain any reference translations. Reference translations are not really needed for this type of evaluation, because checking whether the expected conjunction appears in the translation hypothesis is sufficient.
For (usually a very small number of) unclear cases, manual inspection is needed, but it would be needed with reference translations, too. 

If you use this data set, please cite one of our papers (2019) which introduce its usage:

Maja Popović, Sheila Castilho: "*Are ambiguous conjunctions problematic for machine translation?*", Proceedings of the 12th Conference on Recent Advances in Natural Language Processing (RANLP 2019), September, Varna, Bulgaria

@InProceedings{conj-ranlp2019,

author = {Maja Popovi'{c}, Sheila Castilho},

title = {{Are ambiguous conjunctions problematic for machine translation?}},

booktitle = {Proceedings of the 12th Conference on Recent Advances in Natural Language Processing (RANLP 2019)},

month = {September},

year = {2019},

address = {Varna, Bulgaria},

}



Maja Popović: "*Evaluating conjunction disambiguation on English-to-German and French-to-German WMT 2019 translation hypotheses*", Proceedings of the 4th Conference on Machine Translation (WMT 2019), August, Florence, Italy

@InProceedings{conj-wmt2019,

author = {Maja Popovi'{c}},

title = {{Evaluating conjunction disambiguation on English-to-German \\ and French-to-German WMT 2019 translation hypotheses}},

booktitle = {Proceedings of the 4th Conference on Machine Translation (WMT 2019)},

month = {August},

year = {2019},

address = {Florence, Italy},

}
