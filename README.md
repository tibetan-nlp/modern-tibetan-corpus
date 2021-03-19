# Modern Tibetan Corpus
This repository contains a small collection of linguistically analyzed Modern Tibetan texts. The collection includes blog posts, online newspaper articles, a classic essay, and three short works of fiction. The following table summarizes the collection. The short story _Black Fox Valley_ by Tsering Dondrup has yet to be deposited.

Text ID | Tagging | Annotation | Alignment
------- | ------- | ---------- | ---------
blackfoxvalley | machine | human | human 
conflict | machine | human | human
japanese | machine | human | human
narrowfootpath | machine | human | human
snowpilgrimage | machine | human | human
summerpastures | machine | human | human
tenvirtues | machine | human | human
theparty | machine | human | human
tibetcm | none | human | none
tibettimes | none | human | none
vegetarianism | machine | human | none
wink | machine | human | human
women | machine | human | human

With the exception of _tibettimes_ and _tibetcm_, the texts were machine segmented and part-of-speech tagged. Texts were then converted to [BRAT standoff format](https://brat.nlplab.org/standoff.html) for human annotation using the _brat rapid annotation tool_.

Humans then focused on annotating the argument structure of verbs, approximating the guidelines of the [Universal Dependencies](https://universaldependencies.org/u/dep/) project. Part-of-speech tags were not corrected, except when they interacted with the required annotation.

In the case of _tibettimes_ and _tibetcm_, which were imported into BRAT as unanalyzed text, humans annotated the argument structure of verbs, assigning part-of-speech tags to only those words implicated in the annotation.

Texts were then converted to [CoNLLU format](https://universaldependencies.org/format.html) for broader dissemination and use. To facilitate the proper assembly of Tibetan sentences, untagged spans of text were automatically assigned the tag ```NOTAG```. Again with the exception of _tibettimes_ and _tibetcm_, English translations of the remaining texts were aligned to the Tibetan, which can be seen in the corresponding CoNLL-U files.

Final BRAT configuration and data files for these texts are included in this repository for completeness, in case anyone wishes to reproduce the BRAT configuration used for annotating the texts. In addition, unannotated texts from the _tibettimes_ and _tibetcm_ subcollections are included. These are the wider datasets from which the annotated materials were selected.

It is important to stress that moving forward, only the CoNLL-U files will be maintained.

You may cite this work by referencing the repository and its authors: Jamyang Dakpa, Tashi Dhondup, Yeshi Jigme Gangne, Edward Garrett, Marieke Meelen, and Sonam Wangyal. We thank the AHRC for its funding of the project _Lexicography in Motion_ (2017-2020, PI Ulrich Pagel).
